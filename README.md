Sorteo de Amigos.

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
![Screenshot 2025-03-18 162543](https://github.com/user-attachments/assets/9faef5ed-1a40-4b2d-8065-9b518d83e96d)


3. Renderizar Lista de Amigos
Función renderizarAmigos(): Esta función recorre el array amigo y crea un elemento <li> por cada nombre en la lista.
Cada elemento <li> se agrega al contenedor <ul> con el id listaAmigos, que muestra la lista de amigos en la interfaz de usuario.
![Screenshot 2025-03-18 163750](https://github.com/user-attachments/assets/beb8ba09-a0c3-478c-892d-10d11c1a93aa)


5. Sortear Amigo
Función sortearAmigo(): Esta función selecciona un nombre al azar del array amigo.
Si la lista está vacía, se muestra una alerta indicando que no hay amigos para sortear.
Si hay nombres en la lista, se selecciona uno al azar utilizando Math.random() y se muestra en el elemento con el id resultado.
Finalmente, la lista de amigos en la interfaz de usuario se limpia.
![Screenshot 2025-03-18 164047](https://github.com/user-attachments/assets/d1ee795f-13c8-45ad-885d-238e582366b0)


Cómo usar
Agregar Amigos: Ingresa el nombre de un amigo en el campo de texto y presiona "Agregar". El nombre se añadirá a la lista.
Sortear Amigo: Una vez que hayas agregado varios amigos, presiona el botón "Sortear" para seleccionar un amigo al azar. El nombre del amigo sorteado se mostrará en la pantalla y la lista se limpiará.

Requisitos
Un navegador web moderno que soporte JavaScript.

Amigo Secreto - Aplicación Web
Este proyecto es una aplicación web simple que permite a los usuarios organizar un juego de "Amigo Secreto". Los participantes pueden agregar sus nombres a una lista, y la aplicación seleccionará al azar un "amigo secreto" para cada uno. El objetivo es facilitar la organización de este juego tradicional, común en reuniones y celebraciones.

Características principales
Interfaz intuitiva: Diseño limpio y fácil de usar.
Agregar participantes: Los usuarios pueden ingresar nombres de amigos en un campo de texto.
Lista de participantes: Los nombres agregados se muestran en una lista en tiempo real.
Sortear amigo secreto: La aplicación selecciona al azar un nombre de la lista y lo muestra como el "amigo secreto".
Diseño responsivo: Compatible con dispositivos móviles y de escritorio.
Accesibilidad: Uso de atributos ARIA para mejorar la accesibilidad.

Cómo funciona
1. Estructura HTML
Encabezado (header): Contiene el título principal y una imagen representativa del juego.
Sección de entrada (input-section): Incluye un campo de texto para ingresar nombres y un botón para agregarlos a la lista.
Lista de amigos (listaAmigos): Muestra los nombres agregados en una lista.
Resultado del sorteo (resultado): Muestra el nombre del "amigo secreto" seleccionado.
Botón de sorteo: Inicia el proceso de selección aleatoria.

2. Funcionalidad JavaScript
Agregar amigos:
El usuario ingresa un nombre en el campo de texto y presiona "Añadir".
El nombre se agrega a un array (amigo) y se actualiza la lista en la interfaz.
Si el campo está vacío, se muestra una alerta.

Ejemplo de uso
Ingresa "Juan" en el campo de texto y presiona "Agregar".
Ingresa "Ana" en el campo de texto y presiona "Agregar".
Presiona "Sortear" y el sistema seleccionará al azar entre "Juan" y "Ana".
![Screenshot 2025-03-18 164325](https://github.com/user-attachments/assets/f97ad768-33f3-4772-bce1-89f2bf097f05)

Renderizar lista de amigos:
La función renderizarAmigos() recorre el array amigo y crea elementos <li> para cada nombre, mostrándolos en la lista.
![Screenshot 2025-03-18 164449](https://github.com/user-attachments/assets/832b9c96-b285-4d9d-a2af-f6c7de9cfdbc)

Sortear amigo secreto:
La función sortearAmigo() selecciona un nombre al azar del array amigo.
Si la lista está vacía, se muestra una alerta.
El nombre seleccionado se muestra en el área de resultados y la lista se limpia.
![Screenshot 2025-03-18 164719](https://github.com/user-attachments/assets/e78f5e15-e556-40b9-9a92-c862fcb90421)


3. Estilos CSS
Fuentes personalizadas: Uso de Google Fonts (Inter y Merriweather) para un diseño moderno.
Diseño responsivo: La interfaz se adapta a diferentes tamaños de pantalla.
Estilos visuales: Botones y listas con estilos atractivos y coherentes.

Cómo usar
Agregar amigos:
Ingresa el nombre de un amigo en el campo de texto y presiona "Añadir".
Repite este proceso para agregar todos los participantes.

Sortear amigo secreto:
Una vez que hayas agregado todos los nombres, presiona el botón "Sortear amigo".
El nombre del "amigo secreto" seleccionado se mostrará en la pantalla.

Reiniciar:
Para realizar otro sorteo, recarga la página o agrega nuevos nombres.

Requisitos
Navegador web moderno (Chrome, Firefox, Edge, Safari, etc.).
Conexión a Internet (para cargar las fuentes de Google Fonts).

Ejemplo de uso
Ingresa "Juan" en el campo de texto y presiona "Añadir".
Ingresa "Ana" en el campo de texto y presiona "Añadir".

Presiona "Sortear amigo".
La aplicación seleccionará al azar entre "Juan" y "Ana" y mostrará el resultado.
