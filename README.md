libft 📚💡

Es una librería personalizada en C que implementa una colección de funciones de propósito general inspiradas en las de la biblioteca estándar de C (libc). Este proyecto es la base de futuros desarrollos en C, proporcionando herramientas reutilizables que facilitan la programación y fomentan una comprensión profunda del funcionamiento interno de estas funciones.
En libft_bonus se implementan a mayores funciones para la manipulación de listas.
Se utiliza la siquiente estructura para representar un nodo de una lista:
  typedef struct s_list
  {
    void *content;
    struct s_list *next;
  } t_list;

Los miembros de la estructura t_list son:
• content: la información contenida por el nodo.
void *: permite guardar cualquier tipo de información.
• next: la dirección del siguiente nodo, o NULL si el siguiente nodo es el último.
