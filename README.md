# Fleet Management Software API

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Consideraciones generales](#4-consideraciones-generales)
* [5. Criterios de aceptación del proyecto](#5-criterios-de-aceptación-del-proyecto)
* [6. Stack de tecnologías](#6-stack-de-tecnologías)
* [7. Pistas, tips y lecturas complementarias](#7-pistas-tips-y-lecturas-complementarias)
* [8. Funcionalidades opcionales](#8-funcionalidades-opcionales)

***

## 1. Preámbulo

De acuerdo con
[Wikipedia](https://es.wikipedia.org/wiki/Internet_de_las_cosas),
la internet de las cosas (IoT, por sus siglas en inglés)​ es un concepto que
se refiere a una interconexión digital de objetos cotidianos con internet.
Constituye un cambio radical en la calidad de vida de las personas en la
sociedad, ofreciendo nuevas oportunidades en el acceso a
datos, educación, seguridad, asistencia
sanitaria y en el transporte, entre otros campos. Por ejemplo,
en logística y manejo de flotas, se puede hacer seguimiento en
todo momento de la ubicación y las condiciones de vehículos
mediante sensores inalámbricos conectados a internet que envían alertas en
caso de eventualidades (demoras, daños, robos, etc.).

![zach-vessels-utMdPdGDc8M-unsplash](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fthumb.jpg?alt=media)

La IoT también plantea retos como el almacenamiento, análisis y
visualización de la gran cantidad de información que genera.
Se calcula que para el 2025 los dispositivos IoT generen
[79.4 zettabytes](https://www.statista.com/statistics/1017863/worldwide-iot-connected-devices-data-size/)
(1 zettabyte equivale a 1 trillón de gigabytes).
Como desarrolladoras debemos estar al tanto de estos retos y contribuir para
su solución desde nuestra experiencia, conocimiento y ganas de aprender.

## 2. Resumen del proyecto

En este proyecto construirás la API REST de un
[Fleet Management Software](https://en.wikipedia.org/wiki/Fleet_management)
para consultar las ubicaciones de los vehículos de una empresa
de taxis en Beijing, China.

Te entregaremos las ubicaciones de casi 10 mil
taxis. Esperamos que como desarrolladora explores nuevas alternativas y
técnicas para almacenar y consultar esta
información y puedas garantizar la mejor experiencia de usuaria en tu
API REST.

## 3. Objetivos de aprendizaje


Reflexiona y luego marca los objetivos que has llegado a entender y aplicar en tu proyecto. Piensa en eso al decidir tu estrategia de trabajo.

### Programación Orientada a Objetos (OOP)

- [ ] **Clases**

- [ ] **Objetos**

- [ ] **Métodos**

- [ ] **Atributos**

- [ ] **Constructores**

- [ ] **Encapsulamiento**

- [ ] **Abstracción**

- [ ] **Composición**

- [ ] **Interfaces**

- [ ] **Herencia (super, extends, override)**

- [ ] **Lenguaje de Modelado Unificado (UML, class diagrams)**


### SQL

- [ ] **Creación y modificación de tablas**

  <details><summary>Links</summary><p>

  * [SQL CREATE TABLE Statement - w3schools (en inglés)](https://www.w3schools.com/sql/sql_create_table.asp)
  * [CREATE TABLE Statement - PostgreSQL Docs (en inglés)](https://www.postgresql.org/docs/9.1/sql-createtable.html)
  * [ALTER TABLE Statement - PostgreSQL Docs (en inglés)](https://www.postgresql.org/docs/9.1/sql-altertable.html)
</p></details>

- [ ] **Operaciones CRUD (Create-Read-Update-Delete)**

  <details><summary>Links</summary><p>

  * [INSERT](https://www.postgresql.org/docs/9.5/sql-insert.html)
  * [SELECT](https://www.postgresql.org/docs/9.5/sql-select.html)
  * [UPDATE](https://www.postgresql.org/docs/9.1/sql-update.html)
  * [DELETE](https://www.postgresql.org/docs/8.1/sql-delete.html)
</p></details>

- [ ] **Borrado de tablas o bases de datos enteras con DROP**

  <details><summary>Links</summary><p>

  * [DROP TABLE](https://www.postgresql.org/docs/8.2/sql-droptable.html)
  * [DROP DATABASE](https://www.postgresql.org/docs/8.2/sql-dropdatabase.html)
</p></details>

### Bases de datos

- [ ] **Modelado de datos**

- [ ] **Conexión**

- [ ] **Índices y limitaciones**

### C#

- [ ] **Variables**

  <details><summary>Links</summary><p>

  * [Variables (en inglés) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/language-specification/variables)
  * [C# | Variables](https://www.geeksforgeeks.org/c-sharp-variables/)
  * [Variables y Tipos en C#](https://desarrolloweb.com/articulos/variables-tipos-csharp)
</p></details>

- [ ] **Condicionales**

  <details><summary>Links</summary><p>

  * [Instrucciones de selección - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/statements/selection-statements)
</p></details>

- [ ] **Bucles/Ciclos**

  <details><summary>Links</summary><p>

  * [Instrucciones de iteración - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/statements/iteration-statements)
</p></details>

- [ ] **Operadores**

  <details><summary>Links</summary><p>

  * [Operadores y expresiones de C# (referencia de C#) - Microsoft Docs](https://docs.microsoft.com/es-es/dotnet/csharp/language-reference/operators/)
</p></details>

- [ ] **Genéricos**

  <details><summary>Links</summary><p>

  * [Clases y métodos genéricos (C# Programming Guide) - Microsoft Docs](https://docs.microsoft.com/es-es/dotnet/csharp/programming-guide/generics/)
</p></details>

- [ ] **Modificadores de Acceso**

  <details><summary>Links</summary><p>

  * [Modificadores de acceso (Guía de programación de C#) - Microsoft Docs](https://docs.microsoft.com/es-es/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
</p></details>

- [ ] **Espacios de Nombres (namespaces)**

  <details><summary>Links</summary><p>

  * [Declaración de espacios de nombres para organizar los tipos - Microsoft Docs](https://docs.microsoft.com/es-es/dotnet/csharp/programming-guide/namespaces/)
</p></details>

- [ ] **LINQ**

  <details><summary>Links</summary><p>

  * [LINQ (Language-Integrated Query) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/linq/)
  * [LINQ Conceptos básicos y consultas (en inglés) - Tutorial Teacher](https://www.tutorialsteacher.com/linq)
  * [LINQ Tutorial For Beginners and Professionals (en inglés)](https://dotnettutorials.net/course/linq/)
</p></details>

- [ ] **Async-Await**

  <details><summary>Links</summary><p>

  * [Escenarios de programación asincrónica - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/asynchronous-programming/async-scenarios)
</p></details>

- [ ] **.NET Core**

  <details><summary>Links</summary><p>

  * [.NET and .NET Core - Microsoft Docs](https://docs.microsoft.com/es-es/dotnet/)
  * [.NET para principiantes - Microsoft Docs](https://learn.microsoft.com/es-es/shows/dotnet-for-beginners/)
  * [Introducción a .NET - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/core/introduction)
  * [Tutoriales .NET - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/core/tutorials/)
</p></details>

- [ ] **Paquetes NuGet**

  <details><summary>Links</summary><p>

  * [NuGet Documentación - Microsoft Docs](https://docs.microsoft.com/es-es/nuget/)
  * [NuGet Library](https://www.nuget.org/)
  * [Administrar paquetes NuGet con la CLI de NuGet - Microsoft Docs](https://learn.microsoft.com/es-es/nuget/consume-packages/install-use-packages-nuget-cli)
  * [Instalar paquetes Nuget en Visual Studio Code](https://www.youtube.com/watch?v=Qy-vwB_TEW4)
  * [Instalar paquetes Nuget en Visual Studio](https://www.youtube.com/watch?v=J3_io5mBEnU)
</p></details>

#### Tipos de datos

- [ ] **Tipos de datos primitivos**

  <details><summary>Links</summary><p>

  * [Tipos integrados (referencia de C#) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/builtin-types/built-in-types)
  * [C# | Data Types (en inglés)](https://www.geeksforgeeks.org/c-sharp-data-types/)
</p></details>

- [ ] **Tipos de datos no primitivos**

  <details><summary>Links</summary><p>

  * [Common Type System - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/fundamentals/types/#the-common-type-system)
</p></details>

- [ ] **Estructuras**

  <details><summary>Links</summary><p>

  * [Tipos de estructura (Referencia de C#) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/builtin-types/struct)
</p></details>

- [ ] **Enumeración**

  <details><summary>Links</summary><p>

  * [Tipos de enumeración (Referencia de C#) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/builtin-types/enum)
</p></details>

- [ ] **Tipos anónimos**

  <details><summary>Links</summary><p>

  * [Tipos anónimos - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/fundamentals/types/anonymous-types)
</p></details>

- [ ] **Tipos dinámicos**

  <details><summary>Links</summary><p>

  * [dynamic (Referencia de C#) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/builtin-types/reference-types#the-dynamic-type)
  * [Uso del tipo dynamic - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/advanced-topics/interop/using-type-dynamic)
</p></details>

#### Colecciones

- [ ] **Listas**

  <details><summary>Links</summary><p>

  * [List<T> Clase - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/api/system.collections.generic.list-1?view=net-8.0)
  * [Aprenda a administrar colecciones de datos mediante List<T> en C# - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/tour-of-csharp/tutorials/arrays-and-collections)
</p></details>

- [ ] **Arreglos**

  <details><summary>Links</summary><p>

  * [Matrices - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/builtin-types/arrays)
</p></details>

- [ ] **Conjuntos (Sets)**

  <details><summary>Links</summary><p>

  * [HashSet<T> Clase - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/api/system.collections.generic.hashset-1?view=net-8.0)
  * [HashSet in C# with Examples (en inglés)](https://www.geeksforgeeks.org/hashset-in-c-sharp-with-examples/)
</p></details>

#### Funciones

- [ ] **Funciones Lambda**

  <details><summary>Links</summary><p>

  * [Expresiones lambda y funciones anónimas (referencia de C#) - Microsoft Docs](https://docs.microsoft.com/es-es/dotnet/csharp/programming-guide/statements-expressions-operators/lambda-expressions)
</p></details>

- [ ] **Decoradores (Atributos)**

  <details><summary>Links</summary><p>

  * [Atributos (en Inglés) - Microsoft Docs](https://docs.microsoft.com/es-es/dotnet/csharp/programming-guide/concepts/attributes/)
  * [Definición y lectura de atributos personalizados - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/advanced-topics/reflection-and-attributes/attribute-tutorial)
</p></details>

#### Manejo de Errores

- [ ] **try-catch**

  <details><summary>Links</summary><p>

  * [try-catch (Referencia de C#) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/statements/exception-handling-statements)
</p></details>

- [ ] **throw**

  <details><summary>Links</summary><p>

  * [throw (Referencia de C#) - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/csharp/language-reference/statements/exception-handling-statements#the-throw-statement)
</p></details>

#### Pruebas

- [ ] **xUnit**

  <details><summary>Links</summary><p>

  * [xUnit.net Documentación - xUnit.net](https://xunit.net/#documentation)
  * [Prueba unitaria de C# en .NET Core mediante pruebas de dotnet y xUnit - Microsoft Docs](https://learn.microsoft.com/es-es/dotnet/core/testing/unit-testing-with-dotnet-test)
</p></details>

- [ ] **MSTest**

  <details><summary>Links</summary><p>

  * [MSTest V2 - GitHub](https://github.com/microsoft/testfx?tab=readme-ov-file)
  * [Prueba unitaria de C# con MSTest y .NET](https://learn.microsoft.com/es-es/dotnet/core/testing/unit-testing-with-mstest)
</p></details>

#### Entity Framework

- [ ] **Code First**

  <details><summary>Links</summary><p>

  * [Code First en una nueva base de datos - Microsoft Docs](https://learn.microsoft.com/es-es/ef/ef6/modeling/code-first/workflows/new-database)
</p></details>

- [ ] **Modelos**

  <details><summary>Links</summary><p>

  * [Creación de un modelo - Microsoft Docs](https://learn.microsoft.com/es-es/ef/ef6/modeling/)
</p></details>

- [ ] **Fluent API**

  <details><summary>Links</summary><p>

  * [Fluent API, Relaciones | Microsoft Docs](https://learn.microsoft.com/es-es/ef/ef6/modeling/code-first/fluent/relationships)
</p></details>

- [ ] **Controladores**

  <details><summary>Links</summary><p>

  * [Agregar modelos y controladores - Microsoft Docs](https://learn.microsoft.com/es-es/aspnet/web-api/overview/data/using-web-api-with-entity-framework/part-2#add-web-api-controllers)
  * [Creación de API web con ASP.NET Core](https://learn.microsoft.com/es-es/aspnet/core/web-api/?view=aspnetcore-8.0)
  * [Entendiendo los Web API con .Net Core y Entity framework](https://bravedeveloper.com/2021/07/20/entendiendo-los-web-api-con-net-core-y-entity-framework/)
</p></details>

- [ ] **Migraciones**

  <details><summary>Links</summary><p>

  * [Descripción general de las migraciones - Microsoft Docs](https://docs.microsoft.com/es-es/ef/core/managing-schemas/migrations/)
</p></details>

### PostgreSQL

- [ ] **Tipos de datos**

  <details><summary>Links</summary><p>

  * [Chapter 8. Data Types - Docs (en inglés)](https://www.postgresql.org/docs/14/datatype.html)
</p></details>

- [ ] **Índices**

  <details><summary>Links</summary><p>

  * [Chapter 11. Indexes - Docs (en inglés)](https://www.postgresql.org/docs/14/indexes.html)
</p></details>

### Control de Versiones (Git y GitHub)

#### Git

- [ ] **Git: Instalación y configuración**

- [ ] **Git: Control de versiones con git (init, clone, add, commit, status, push, pull, remote)**

- [ ] **Git: Integración de cambios entre ramas (branch, checkout, fetch, merge, reset, rebase, tag)**

#### GitHub

- [ ] **GitHub: Creación de cuenta y repos, configuración de llaves SSH**

- [ ] **GitHub: Colaboración en Github (branches | forks | pull requests | code review | tags)**

- [ ] **GitHub: Organización en Github (projects | issues | labels | milestones | releases)**

### Typescript

#### Tipos básicos

- [ ] **Tipos primitivos**

  <details><summary>Links</summary><p>

  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)
</p></details>

- [ ] **Arreglos**

  <details><summary>Links</summary><p>

  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#arrays)
</p></details>

- [ ] **Funciones**

  <details><summary>Links</summary><p>

  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#functions)
  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/functions.html)
</p></details>

- [ ] **Tipos Union**

  <details><summary>Links</summary><p>

  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#union-types)
</p></details>

- [ ] **Interfaces**

  <details><summary>Links</summary><p>

  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#interfaces)
</p></details>

- [ ] **Enums**

  <details><summary>Links</summary><p>

  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#enums)
</p></details>

##### Tipos Objecto _(Tipos básicos)_

- [ ] **Propiedades opcionales**

  <details><summary>Links</summary><p>

  * [Documentación oficial de Typescript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#optional-properties)
</p></details>

## 4. Consideraciones generales

* Este proyecto se debe "resolver" en duplas.
* El rango de tiempo estimado para completar el proyecto es de 4 a 6 Sprints.

## 5. Criterios de aceptación del proyecto

Nuestra cliente ha instalado dispositivos GPS en sus taxis.
Estos dispositivos utilizan señales satelitales para determinar
con precisión las coordenadas geográficas del taxi.

Nuestra clienta requiere:

1. Cargar la información de archivos SQL a una
base de datos Postgresql.
2. Desarrollar una API REST que permita consultar, mediante
peticiones HTTP, la información almancenada en la base de datos.

### Definición del producto

El [_Product Owner_](https://www.youtube.com/watch?v=r2hU7MVIzxs&t=202s)
nos presenta este _backlog_ que es el resultado de su trabajo con la clienta
hasta hoy.

***

#### [Historia de usuario 1] Cargar información a base de datos

Yo, como desarrolladora, quiero cargar la información almacenada hasta ahora en
[archivos sql](https://drive.google.com/file/d/1T5m6Vzl9hbD75E9fGnjbOiG2UYINSmLx/view?usp=drive_link)
en una base de datos PostgreSQL, para facilitar su consulta y análisis.

##### Criterios de aceptación

* Se debe tener en cuenta el siguiente diagrama para la implementación de las
relaciones entre las tablas

![mer](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fsql-diagram.png?alt=media)

* La tabla de _trajectories_ se debe crear con el "id" que se incremente
automáticamente (SERIAL) para poder insertar los valores sin necesidad
de especificar un identificador

##### Definición de terminado

* La base de datos tiene creada la tabla de taxis
* La tabla de taxis tiene cargada la data de taxis
* La base de datos tiene creada la tabla de trayectorias
* La tabla de taxis tiene cargada la data de trayectorias

***

##### [Historia de usuario 2] Endpoint listado de taxis

Yo como clienta de la API REST requiero un _endpoint_ para
listar todos los taxis.

##### Criterios de aceptación

* El _endpoint_ responde para cada taxi: id y placa.
* El _endpoint_ paginamos los resultados para asegurar que las
respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

#### [Historia de usuario 3] Endpoint historial de ubicaciones

Yo como clienta de la API REST requiero un _endpoint_ para
consultar todas las ubicaciones de un taxi dado el id y una fecha.

##### Criterios de aceptación

* El _endpoint_ responde con el id del taxi y una fecha mostrando
  la siguiente información: latitud, longitud y timestamp (fecha y hora).
* El _endpoint_ paginamos los resultados para asegurar que las
  respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

#### [Historia de usuario 4] Endpoint última ubicación

Yo como clienta de la API REST requiero un _endpoint_ para
consultar la última ubicación reportada por cada taxi.

##### Criterios de aceptación

* El _endpoint_ responde para cada taxi la siguiente información:
id, placa, latitud, longitud y timestamp (fecha y hora).
* El _endpoint_ paginamos los resultados para asegurar que las
respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

## 6. Stack de tecnologías

Utiliza las siguientes recomendaciones para implementar tu proyecto: 

* [C#](./docs/stack-csharp.md)

## 7. Pistas, tips y lecturas complementarias

### Modelamiento de datos

La base de datos recomendada para tu aplicación es PostgreSQL. Te
recomendamos usar [vercel Postgresql](https://vercel.com/docs/storage/vercel-postgres)
para que no tengas que instalar PostgreSQL en tu computadora.

Una vez tengas acceso a una instancia de PostgreSQL, deberás crear tablas en
tu base de datos para almacenar la información entregada. Te recomendamos
entonces crear dos tablas, una para almacenar la información de taxis y otra
para almacenar la información de ubicaciones. Deberás definir las columnas
de cada tabla de acuerdo a la información entregada.

Puedes crear una tabla en PostgreSQL usando
[SQL](https://www.postgresqltutorial.com/postgresql-create-table/).

### Definir endpoints de API

Deberás definir y documentar los endpoints de tu API.
Debes usar [Swagger](https://swagger.io/) para esto.

Para una API REST debes definir para cada endpoint entre otras cosas el
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).

Por ejemplo, en la siguiente figura se define un endpoint para consultar la
información de los taxis en la aplicación. El método del endpoint es _GET_,
la url es _/taxis_. Recibe un parámetro _query_, retorna la información con
_código HTTP_ 200 en formato json gracias al _header_
`Content-type` con valor `application/json`.

![Ejemplo Endpoint API Rest](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fexample-endpoint-api-rest.png?alt=media)

## 8. Funcionalidades opcionales

Si completaste todas las funcionalidades del proyecto te invitamos a trabajar en
las [funcionalides opcionales](./docs/extension.md)
