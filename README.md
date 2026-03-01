# Sistema Avanzado de Gestión de Inventario (POO)

Este proyecto es una aplicación de consola desarrollada en **Python** para la gestión eficiente de inventarios. Utiliza principios de Programación Orientada a Objetos (POO), manejo de colecciones dinámicas y persistencia de datos mediante archivos de texto.

## Características

* **Gestión Completa (CRUD):** Añadir, buscar, actualizar y eliminar productos.
* **Estructura POO:** Uso de clases `Producto` e `Inventario` para una lógica desacoplada.
* **Colecciones Optimizadas:** Implementación de diccionarios para búsquedas rápidas por ID.
* **Persistencia de Datos:** Los datos se guardan automáticamente en un archivo `inventario.txt`, permitiendo que la información se mantenga al cerrar el programa.
* **Interfaz de Usuario:** Menú interactivo y amigable por consola.

##  Requisitos

* Python 3.x
* PyCharm (Recomendado) o cualquier editor de texto/IDE.

## Instalación y Ejecución

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/NOMBRE_DEL_REPOSITORIO.git](https://github.com/TU_USUARIO/NOMBRE_DEL_REPOSITORIO.git)
    ```
2.  **Navegar al directorio:**
    ```bash
    cd NOMBRE_DEL_REPOSITORIO
    ```
3.  **Ejecutar la aplicación:**
    ```bash
    python inventario.py
    ```

## Estructura del Código

* `Producto`: Clase que define los atributos del objeto (ID, nombre, cantidad, precio).
* `Inventario`: Clase encargada de la lógica de almacenamiento (diccionarios) y los métodos de lectura/escritura en archivos.
* `menu()`: Función principal que gestiona la interacción con el usuario.

##  Institución
* **Universidad:** Universidad Estatal Amazónica.
* **Materia:** Programación Avanzada / Estructura de Datos.
