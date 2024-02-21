# Informe de Práctica 5: Objetos, Clases e Interfaces en TypeScript

| **Autor** | **Profesor** | **Asignatura** | **Universidad** | **Ubicación** | **Fecha** | 
|--------------|--------------|--------------|--------------|--------------|--------------|
| ***TOMÁS JAVES TOMMASONE*** | ***Dr. EDUARDO MANUEL SEGREDO GONZALEZ*** | ***DESARROLLO DE SISTEMAS INFORMÁTICOS*** | ***UNIVERSIDAD DE LA LAGUNA*** | ***SAN CRISTOBAL DE LA LAGUNA*** | ***21/02/2024*** |

#### Índice:  
1. [_Objetivo_](#1-objetivo)
2. [_Tareas Previas_](#2-tareas-previas)
3. [_Ejercicios Propuestos_](#3-ejercicios-propuestos)  
3.1 [Ejercicio 1 - Gestor de Referencias Bibliográficas](#ejercicio-1---gestor-de-referencias-bibliográficas)  
3.2 [Ejercicio 2 - Menús Saludables Orientados a Objetos](#ejercicio-2---menús-saludables-orientados-a-objetos)  
4. [_Conclusión_](#4-conclusión)
5. [_Referencias Bibliográficas_](#5-referencias-bibliográficas)

## 1. Objetivo
La práctica 5 se centra en el uso de objetos, clases e interfaces en TypeScript para resolver una serie de ejercicios prácticos. Estos conceptos son fundamentales en el desarrollo de software orientado a objetos, ya que permiten organizar y estructurar el código de manera eficiente, facilitando la reutilización y mantenimiento del mismo.

Al profundizar en el manejo de objetos, clases e interfaces, adquirimos una comprensión más sólida de cómo diseñar y estructurar sistemas de software de manera modular y escalable. Esto nos permite abordar problemas de mayor complejidad y desarrollar soluciones más robustas y flexibles.

Durante la práctica, hemos aplicado los principios SOLID de programación orientada a objetos, lo que nos ayuda a escribir código más limpio, mantenible y extensible. Además, aprendemos a documentar adecuadamente el código utilizando herramientas como TypeDoc, lo que mejora la legibilidad y comprensión del mismo para otros desarrolladores.

Además de resolver los ejercicios propuestos, también tenemos la oportunidad de familiarizarnos con herramientas como Instanbul y Coveralls para realizar pruebas de cobertura de código y evaluar la calidad del mismo. Esto nos ayuda a identificar áreas que requieren mayor atención y a mejorar la calidad general del código.

## 2. Tareas Previas
Antes de abordar la resolución de los ejercicios propuestos en la práctica 5, es crucial realizar una serie de tareas previas para asegurar un desarrollo efectivo y eficiente. Estas tareas previas proporcionan una base sólida y preparan el terreno para el trabajo práctico que se realizará a continuación. Aquí se detallan estas tareas:

1. Aceptación de la asignación de GitHub Classroom para la práctica: El primer paso es aceptar la asignación de la práctica en GitHub Classroom. Esta plataforma proporciona un entorno de desarrollo colaborativo y versionado que facilita la gestión de proyectos y la colaboración entre los miembros del equipo.

2. Familiarización con los principios SOLID de Programación Orientada a Objetos: Los principios SOLID son un conjunto de reglas y directrices que guían el diseño de software orientado a objetos hacia la creación de sistemas más mantenibles, flexibles y escalables. Es fundamental comprender estos principios antes de comenzar a desarrollar el código, ya que nos ayudarán a estructurar nuestras clases y objetos de manera coherente y eficaz.

3. Investigación sobre las herramientas Instanbul y Coveralls: Instanbul y Coveralls son herramientas utilizadas para evaluar la cobertura de código en proyectos de software. Proporcionan informes detallados sobre qué partes del código están siendo ejecutadas durante las pruebas y cuáles no, lo que permite identificar áreas que requieren más pruebas o refactorización.

4. Configuración de las herramientas mencionadas: Una vez comprendido el propósito y funcionamiento de Instanbul y Coveralls, es importante configurar correctamente estas herramientas en nuestro entorno de desarrollo. Esto implica instalar las dependencias necesarias, configurar los archivos de configuración y establecer una integración continua para que los informes de cobertura se generen automáticamente después de cada ejecución de pruebas.

Estas tareas previas sientan las bases para un desarrollo exitoso en la práctica 5, garantizando que estemos bien preparados y equipados con las herramientas y conocimientos necesarios para abordar los ejercicios propuestos de manera efectiva.

## 3. Ejercicios Propuestos
### Ejercicio 1 - Gestor de Referencias Bibliográficas
Para abordar este ejercicio, se diseñó un conjunto de clases e interfaces que representan un gestor de referencias bibliográficas. Se crearon clases para diferentes tipos de elementos bibliográficos, como artículos de revista, contribuciones a congresos, capítulos de libro, libros, trabajos de fin de grado y trabajos de fin de máster. Cada clase implementa una interfaz común que define los métodos para obtener la información del elemento en formato IEEE y para realizar búsquedas y exportaciones.

Además, se implementaron métodos para almacenar la información de múltiples elementos bibliográficos, mostrar la información almacenada en formato de tabla y permitir búsquedas y exportaciones en formato IEEE.

### Ejercicio 2 - Menús Saludables Orientados a Objetos
En este ejercicio, se diseñó un sistema para automatizar el diseño de menús saludables. Se crearon clases para representar una solución al problema del menú, una instancia específica del menú y las heurísticas de resolución. Cada heurística se implementó como una clase que cumple con una interfaz común, lo que permite evaluar la idoneidad de un menú según los criterios de la heurística y aplicar la heurística a una instancia del menú.

El enfoque orientado a objetos utilizado en este ejercicio facilita la modularidad y la extensibilidad del sistema, permitiendo agregar nuevas heurísticas o funcionalidades con relativa facilidad mediante la implementación de clases adicionales que siguen el contrato definido por las interfaces.

## 4. Conclusión
La práctica ha sido una oportunidad valiosa para explorar en profundidad el uso avanzado de objetos, clases e interfaces en TypeScript. Al desarrollar soluciones para problemas complejos de programación, hemos podido apreciar de manera más clara cómo el enfoque orientado a objetos puede ser beneficioso en la construcción de sistemas de software sofisticados.

Una de las ventajas destacadas del diseño orientado a objetos es su capacidad para promover la reutilización del código. Al dividir la funcionalidad en clases y componentes bien definidos, podemos encapsular la lógica de negocio de manera que sea fácilmente accesible y reutilizable en diferentes partes de la aplicación. Esto no solo reduce la duplicación de código, sino que también facilita la mantenibilidad del sistema a largo plazo, ya que los cambios en una parte del código pueden propagarse de manera controlada a otras partes relacionadas.

Además, el uso de interfaces nos ha permitido establecer contratos claros entre diferentes componentes del sistema. Esto fomenta la interoperabilidad y la modularidad, ya que las clases pueden comunicarse entre sí de manera predecible a través de las interfaces definidas. Además, las interfaces proporcionan una forma de abstracción que facilita la comprensión del sistema en su conjunto, ya que nos permite centrarnos en cómo interactúan los componentes sin preocuparnos por los detalles de implementación.

Otro aspecto importante del diseño orientado a objetos es la separación de preocupaciones. Al dividir la funcionalidad en clases y componentes con responsabilidades específicas, podemos mantener el código limpio y modular, lo que facilita su comprensión y mantenimiento. Esto es especialmente útil en proyectos grandes y complejos, donde múltiples desarrolladores pueden estar trabajando en diferentes partes del sistema simultáneamente.

Concluimos diciendo que la práctica ha resaltado la importancia y la utilidad del diseño orientado a objetos en el desarrollo de software de calidad. Al aprovechar los conceptos de objetos, clases e interfaces en TypeScript, hemos podido construir sistemas robustos, escalables y fácilmente mantenibles que pueden adaptarse a las necesidades cambiantes del negocio.

## 5. Referencias Bibliográficas
- [_SOLID Principles_](https://samueleresca.net/solid-principles-using-typescript/)
- [_TypeScript Documentation_](https://www.typescriptlang.org/docs/)
- [_Istanbul_](https://istanbul.js.org)
- [_Coveralls_](https://coveralls.io)
