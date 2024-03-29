# Información sobre la práctica DUAL de 2º DAM

# Proyectos realizados

## Proyecto Viewnext Lista facturas

Practica DAM 1º y 2º – Lista facturas MVC KOTLIN

1. Introducción

    Esta es una práctica de iniciación en la cual se pretende emular el trabajo diario en un equipo de desarrollo. A la hora de realizar una tarea es tan importante la capacidad de desarrollo como uso de herramientas para el trabajo en equipo y la comunicación.

2. Arquitectura

    Esta práctica es de un nivel para introducir a los alumnos al desarrollo Android por los cual se establece la arquitectura MVC por defecto.
    El lenguaje utilizado será Kotlin.

3. Listado de facturas

    Consiste en la creación de la siguiente pantalla en la cual se cargarán los datos a través de un servicio.

    Especificaciones gráficas de la pantalla:

    - La zona superior de la pantalla usara el componente Toolbar nativo con la configuración para mostrar el título en grande.
    - Para el listado de facturas se usará el componente apropiado.
    - Al pulsar sobre una celda se mostrará un popup nativo:
        - Título: “Información”
        - Mensaje: “Esta funcionalidad aún no está disponible”
        - Botón: “Cerrar”
    - Al pulsar el botón de filtros se mostrará la pantalla de los filtros. En caso de no obtener ninguna factura mostrar un texto informativo en el centro de la pantalla.
    - Los recursos para los iconos son:
    - Al cargar la pantalla y cuando se cambien los filtros se deben recargar los datos de las facturas. Para obtener el listado de facturas se usará la librería Retrofit mediante una consulta GET a la url:
      https://viewnextandroid.mocklab.io/facturas

    Los filtros se aplicarán de forma local, es decir se cargan los datos de la url y a continuación se filtran desde la app.

4. Pantalla de filtros

    Esta pantalla se encargará de configurar los filtros para las facturas, las especificaciones de la pantalla son las siguientes:

    - La zona superior de la pantalla usara el componente Toolbar nativo con la configuración para mostrar el título en grande.
    - La X cierra la pantalla sin hacer ningún cambio en los filtros.
    - Sección de fechas, se visualizará un selector de fecha del sistema en cada campo
    - Sección de importes: No será un slider doble, será simple e irá de 0 al máximo de valor de las facturas (campo de entrada de la pantalla 1)
    - Sección de checks
    - Botón verde con fondo en blanco con texto “Aplicar”
    - Botón gris sin fondo con texto “Eliminar filtros” que borra los filtros.

5. Proyecto

    Para el desarrollo de la tarea se creará un proyecto desde cero conectado a un repositorio git personal.
    Las llamadas a los servicios deberán de hacerse mediante la librería Retrofit.

## Recursos para el Proyecto aplicación de facturas en Kotlin

-   Repositorio
    -   https://github.com/Juanma-Gutierrez/ProyectoViewnextKotlin
-   Video de uso de la aplicación final
    -   https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/blob/main/videos/Video%20Facturas.mp4
 
![312223849-e8c06d67-6b4c-4f0b-a277-9300d67ab302](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/6d30829c-f4b3-4e42-b81e-aa69ec72d390)
![312223875-09e10fc7-0d93-4bd5-b86b-11c407713f03](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/eed6fd9b-8f5f-4b88-970b-e503ab5e64b8)
![312223924-6aa55364-145f-4d6e-9744-52125a2407dd](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/1d73710a-23f9-4b48-ab35-6a93b1d2d1e8)
![312223949-2b98b7fe-0f1d-422e-89d2-8724ff4fc5a4](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/dad1d067-62cb-4981-b369-725e2728e4c6)
![312223990-806ee0a6-0289-4126-88de-8714547bfcbb](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/44190632-57c2-4c58-a610-28f802a2c969)

---

# Ejercicio Bull's Eye

Creación de un juego en iOS, con Xcode y Swift, en el que hay que intentar acertar la posición de un número aleatorio mediante el uso de un selector horizontal.

1. Se incluye también una pantalla con las instrucciones del juego en HTML embebido.
2. También incluye una página del autor.

## Recursos para el ejercicio Bull's Eye

-   Repositorio
    -   https://github.com/Juanma-Gutierrez/Swift-Bulls-Eye
-   Video de uso de la aplicación iOS Bull's Eye
    -   https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/blob/main/videos/Video%20BullsEye.mp4

![312223365-b6460f93-1b6e-4a45-947b-826b3a71d3d0](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/d2ca3c2f-b30f-4eaa-bd59-fcbfec713ecd)
![312223576-91249abc-3066-49ac-b6ed-b5ff62e5cd38](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/877f8a2e-0eb8-464d-a413-ea6693763145)
![312223607-b8f56fc2-1ae2-44ff-9ffb-d4c441b0fea3](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/bb25d86c-a403-4e14-b591-41e92df3f1f1)
![312223643-157048e9-dca2-4c43-82bb-980a903159a4](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/c505b39a-742d-4179-8c40-b88b4103483d)
![312223677-9759d8ac-8e7d-4822-8789-cd5d16bdc6dc](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/cc46e56c-7034-4fcf-923a-37f4b89b614c)

---

# Ejercicio Pitch Perfect

Creación de una aplicación en iOS, Xcode y Swift en la que se puede grabar una voz y posteriormente editarla para aplicarle efectos de sonido como eco, reverberación, ponerla grave o aguda.

1. Se utilizará la libraría AVFountain para la edición del audio.

## Recursos para el ejercicio iOS Pitch Perfect

-   Repositorio
    -   https://github.com/Juanma-Gutierrez/Pitch-Perfect
-   Video de uso de la aplicación iOS Pitch Perfect
    -   https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/blob/main/videos/Video%20PitchPerfect.mp4

![312224081-e4242edf-8bca-408d-959d-7bc88b3de098](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/3e7c82dc-8876-463f-a04b-e2de65827d29)
![312224113-517c7bb6-43b0-4141-82db-8a8c62e2250c](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/18a87127-3092-4859-a839-3f21ed498d4a)
![312224147-b12f504f-a11a-43d7-9da5-5b9ee6319ca1](https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/assets/101201349/c0841aa7-deab-4f02-94ff-6ff79f2c376f)

---
# Presentación en formato Google Slides

- https://docs.google.com/presentation/d/11bTC3WeKzvISnqmMHRO2JnurJZ1FemqOFR9Gk_InfU8

---
  
# Presentación en formato PDF

- https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/blob/main/documentacion/Presentaci%C3%B3n%20Dual%20Viewnext%202%C2%BA%20DAM.pdf
- https://github.com/Juanma-Gutierrez/Presentacion-Dual-2DAM/blob/main/documentacion/Presentacion%20Empresa%20Viewnext%202024.pdf
