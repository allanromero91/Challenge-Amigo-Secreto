Sorteo de Amigos
Este proyecto es una pequeña aplicación web que permite a los usuarios agregar nombres de amigos a una lista y luego realizar un sorteo para seleccionar un amigo al azar. El objetivo principal de este código es fortalecer las habilidades en lógica de programación y manipulación del DOM (Document Object Model) utilizando JavaScript.

Funcionalidades
Agregar Amigos: Los usuarios pueden ingresar nombres de amigos en un campo de texto y agregarlos a una lista.
Renderizar Lista de Amigos: Cada vez que se agrega un nuevo amigo, la lista se actualiza automáticamente en la interfaz de usuario.
Sortear Amigo: Se puede realizar un sorteo para seleccionar un amigo al azar de la lista. El nombre del amigo sorteado se muestra en la pantalla y la lista se limpia automáticamente.

Cómo funciona
1. Agregar Amigos
Función agregarAmigo(): Esta función se encarga de obtener el valor del campo de texto donde el usuario ingresa el nombre del amigo.
Si el campo está vacío, se muestra una alerta indicando que se debe ingresar un nombre.
Si el campo no está vacío, el nombre se agrega al array amigo y el campo de texto se limpia y se enfoca para una nueva entrada.
Luego, se llama a la función renderizarAmigos() para actualizar la lista en la interfaz de usuario.

2. Renderizar Lista de Amigos
Función renderizarAmigos(): Esta función recorre el array amigo y crea un elemento <li> por cada nombre en la lista.
Cada elemento <li> se agrega al contenedor <ul> con el id listaAmigos, que muestra la lista de amigos en la interfaz de usuario.

3. Sortear Amigo
Función sortearAmigo(): Esta función selecciona un nombre al azar del array amigo.
Si la lista está vacía, se muestra una alerta indicando que no hay amigos para sortear.
Si hay nombres en la lista, se selecciona uno al azar utilizando Math.random() y se muestra en el elemento con el id resultado.
Finalmente, la lista de amigos en la interfaz de usuario se limpia.

Cómo usar
Agregar Amigos: Ingresa el nombre de un amigo en el campo de texto y presiona "Agregar". El nombre se añadirá a la lista.
Sortear Amigo: Una vez que hayas agregado varios amigos, presiona el botón "Sortear" para seleccionar un amigo al azar. El nombre del amigo sorteado se mostrará en la pantalla y la lista se limpiará.

Requisitos
Un navegador web moderno que soporte JavaScript.

Ejemplo de uso
Ingresa "Juan" en el campo de texto y presiona "Agregar".
Ingresa "Ana" en el campo de texto y presiona "Agregar".
Presiona "Sortear" y el sistema seleccionará al azar entre "Juan" y "Ana".
