# Aplicación de Resultados de Pilotos

## Resumen

Esta aplicación Java es una herramienta GUI simple construida con JavaFX que muestra los resultados de los pilotos basados en las temporadas seleccionadas. Los usuarios pueden seleccionar un año de un cuadro combinado desplegable, y la aplicación mostrará los resultados correspondientes en un formato de tabla.

## Funcionalidades

- **Selección de Año:** Los usuarios pueden elegir un año del cuadro combinado para filtrar los resultados de los pilotos.
- **Visualización de Resultados de Pilotos:** La aplicación muestra los resultados de los pilotos, incluyendo el nombre del piloto, victorias, puntos totales y clasificación.
- **Carga Dinámica de Datos:** Los datos se cargan dinámicamente según el año seleccionado.

## Estructura

- **Main.java:** El punto de entrada principal de la aplicación. Configura la ventana de JavaFX, el cuadro combinado y la vista de tabla.
- **Repositorios:** Clases como `DriverResultRepository` y `SeasonRepository` manejan la obtención de datos y la interacción con las fuentes de datos.
- **Modelos:** Clases como `DriverResult` y `Season` representan los modelos de datos utilizados en la aplicación.
![ejemplo 1](https://github.com/AndresDr71/TableView-Individual/assets/104042777/8f86b06a-b44c-4ad8-ba34-12ed020a95ed)


![ejemplo 2](https://github.com/AndresDr71/TableView-Individual/assets/104042777/ba4ee7d7-5251-4af0-b4cf-bc64c696d079)


![ejemplo 3](https://github.com/AndresDr71/TableView-Individual/assets/104042777/1c5e0097-4922-4c18-b269-3b5f6688231b)


```bash
javac demo_jdbc/Main.java
java demo_jdbc.Main

