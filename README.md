Laboratorio #2: Modelado de Clases y Gestión de Atributos en C# (.NET)
Descripción general

Este repositorio contiene el desarrollo del Laboratorio #2, enfocado en la introducción y aplicación de los fundamentos de la Programación Orientada a Objetos (POO) mediante aplicaciones de consola desarrolladas en C# y .NET.

A lo largo de los ejercicios se aplican conceptos fundamentales como la creación e instanciación de clases, métodos, parámetros, atributos, propiedades, constructores y encapsulamiento. Además, se incluyen validaciones de datos de entrada y manejo de posibles errores durante la interacción con el usuario.

El laboratorio está dividido en tres ejercicios que aumentan progresivamente el nivel de complejidad y permiten comprender cómo se modelan y gestionan los objetos dentro de una aplicación.

Requisitos previos y tecnologías

Para ejecutar este proyecto se recomienda contar con las siguientes herramientas:

Lenguaje: C#
Framework: .NET 10.0
Entorno de desarrollo: Visual Studio 2026
Tipo de aplicación: Aplicación de consola

También es posible ejecutar el proyecto desde la línea de comandos utilizando el SDK de .NET.

Ejercicios desarrollados
Problema 1: Declaración de Clase Básica e Instanciación

El primer ejercicio introduce la estructura básica de una clase y el proceso de creación de objetos.

Conceptos aplicados
Declaración de clases.
Convención de nomenclatura PascalCase.
Creación de métodos públicos.
Instanciación de objetos.
Invocación de métodos mediante el operador punto (.).
Implementación

Se crea una clase denominada LibroCalificacion que contiene un método público llamado MostrarMensaje().

<img width="944" height="172" alt="image" src="https://github.com/user-attachments/assets/8f67e757-bb41-4c27-9b7f-2183105327f8" />

Posteriormente, se crea una instancia de la clase dentro del método Main:

<img width="959" height="98" alt="image" src="https://github.com/user-attachments/assets/748386a2-76ed-4392-bd0a-8de8d50862d0" />

Finalmente, se invoca el método mediante el operador punto:

<img width="991" height="121" alt="image" src="https://github.com/user-attachments/assets/9e33013e-2e7c-4400-a20b-be8f5a49acfa" />

Este ejercicio permite comprender la relación entre una clase, que funciona como un modelo, y un objeto, que representa una instancia creada a partir de dicha clase.

Problema 2: Métodos con Parámetros y Formato de Salida

El segundo ejercicio amplía el uso de métodos mediante la incorporación de parámetros.

Conceptos aplicados
Métodos con parámetros.
Paso de argumentos.
Entrada de datos mediante Console.ReadLine().
Formato de salida.
Marcadores de posición por índice.
Uso de caracteres de escape como \n.
Implementación

Se implementa un método que recibe el nombre de un curso como parámetro:
<img width="960" height="164" alt="image" src="https://github.com/user-attachments/assets/a8b83fc7-0078-4f69-bab4-1a617d11fdd9" />

El usuario puede ingresar el nombre del curso mediante la consola:

<img width="943" height="116" alt="image" src="https://github.com/user-attachments/assets/db9e887c-c129-48e6-8bac-e6020a5610b2" />

Después, el valor introducido se envía como argumento al método:

<img width="970" height="112" alt="image" src="https://github.com/user-attachments/assets/511f50c9-0fb9-466b-a9eb-716c3469cde7" />
Este ejercicio demuestra cómo los métodos pueden recibir información externa y utilizarla para generar resultados dinámicos.

Problema 3: Encapsulamiento, Variables de Instancia, Propiedades y Constructores

El tercer ejercicio profundiza en los principios fundamentales de la Programación Orientada a Objetos.

Conceptos aplicados
Encapsulamiento.
Ocultamiento de información.
Variables o campos de instancia.
Modificadores de acceso private y public.
Propiedades.
Métodos get y set.
Constructores.
Inicialización de objetos.
Validación de datos.
Manejo de posibles errores y excepciones.
Variables privadas

El estado interno del objeto se protege utilizando un campo privado:
private string nombreCurso;




