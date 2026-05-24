# Ejercicio 10 - JavaFX

## Descripción

Este proyecto corresponde al ejercicio 10 del bloque BC5 de JavaFX.

El objetivo del ejercicio es crear una interfaz gráfica que contenga una lista desplegable y un botón.

Cuando el usuario selecciona una opción de la lista y pulsa el botón, se muestra la opción seleccionada en una etiqueta.

## Tecnologías utilizadas

- Java
- JavaFX
- Maven
- IntelliJ IDEA

## Funcionamiento

La aplicación muestra una ventana con una etiqueta, una lista desplegable y un botón.

La lista desplegable contiene varias opciones:

- Java
- JavaFX
- IntelliJ IDEA
- GitHub

Cuando el usuario selecciona una opción y pulsa el botón, el programa muestra el texto:

```text
Has seleccionado: opción
```

## Conceptos utilizados

- `Application`: clase base para crear aplicaciones JavaFX.
- `Stage`: ventana principal de la aplicación.
- `Scene`: contenido visual de la ventana.
- `Label`: control utilizado para mostrar texto.
- `ComboBox`: lista desplegable que permite seleccionar una opción.
- `Button`: botón que ejecuta una acción.
- `setOnAction`: método utilizado para programar el evento del botón.
- `getValue`: obtiene el valor seleccionado en el ComboBox.
- `setText`: cambia el texto de la etiqueta.
- `VBox`: layout que organiza los elementos en vertical.

## Estructura del proyecto

```text
Ejercicio10_JavaFX
 ├── pom.xml
 └── src
     └── main
         └── java
             └── org
                 └── example
                     └── Main.java
```

## Cómo ejecutar el proyecto

Para ejecutar el proyecto desde IntelliJ IDEA:

1. Abrir el proyecto en IntelliJ.
2. Sincronizar el archivo `pom.xml` con Maven.
3. Abrir el panel Maven.
4. Ejecutar:

```bash
mvn javafx:run
```

## Autor

Andrés Huéscar Fernández
