# Ciencia de Datos

La **Ciencia de Datos** es una disciplina que transforma grandes volúmenes de datos en información útil y decisiones estratégicas. Busca predecir tendencias, optimizar procesos, personalizar servicios y/o detectar fraudes. Combina:

- Matemáticas y estadísticas para crear modelos y entender los números.
- Programación para limpiar, organizar y procesar los datos. Por ejemplo, Python.
- Aprendizaje automático, *Machine Learning*, para que los sistemas aprendan de los datos y hagan predicciones.
- Conocimientos del sector específico para que los resultados sirvan para resolver problemas reales.

---

## Ingeniería de Datos

La **Ingeniería de Datos** es la disciplina que diseña, construye y mantiene los sistemas, arquitecturas y *pipelines* (tuberías) para recolectar, almacenar y procesar grandes volúmenes de datos de forma segura y eficiente.

### Ingeniería de Datos vs Ciencia de Datos


**| Característica | Ingeniería de datos | Ciencia de Datos |**
| --------- | --------- | --------- |
| Objetivo principal | Desarrollar y mantener la infraestructura de datos | Extraer valores, patrones y predicciones de los datos |
| Enfoque diario | Recolección, limpieza, almacenamiento y optimización de la base de datos | Análisis estadístico, creación de modelos de *Machine Learning* y visualización |
| Herramientas comunes (ej.) | SQL, Docker | Python, SQL |
| Habilidad fuerte | Desarrollo de software, arquitectura de sistemas y optimización de código | Matemáticas, estadística y conocimiento profundo del negocio |
| Resultado final | Una base de datos limpia, rápida y accesible para toda la empresa | Gráficos, reportes, predicciones o algoritmos inteligentes |
| Ejemplo 1 | Ambientalista | Biólogo |
| Ejemplo 2 | Worldbuilding | Personajes |
| Ejemplo 3 | Canción | Productor |

---

## Lenguajes de Programación

Un **lenguaje de programación** es un conjunto de reglas, símbolos y palabras clave que permite dar instrucciones precisas a un ordenador para que realice tareas específicas. Los lenguajes de programación sirven como traductor entre el humano y el ordenador.

1. El humano escribe el **código fuente** en un lenguaje comprensible para sí mismo.
2. Un software especial traduce ese código al idioma de la máquina, ya que un ordenador solo procesa código binario. 
   1. Un **compilador** es 
   2. Un **intérprete** es 
3. El ordenador realiza la acción solicitada.

Hay dos tipos de lenguajes de programación:

- Los lenguajes de **bajo nivel** están más cerca del idioma del *hardware*, pero son más difíciles de entender para los humanos. Su ventaja es que son más rápidos y eficientes. Un ejemplo es Ensamblador, o Assembly, como veremos en el proyecto **LIBASM** más adelante.
- Los lenguajes de **alto nivel** están más cerca de la comprensión humana. Uitliza palabras en inglés y estructuras lógicas fáciles de aprender. Son los más utilizados a día de hoy, con ejemplos como:
  - C++: usado en proyectos como [CPP-Module-04]\(https://github.com/anatermay/42_malaga_/tree/main/42-common-core/14-cpp-module-04) o [CPP-Module-09]\(https://github.com/anatermay/42_malaga_/tree/main/42-common-core/20-cpp-module-09)
  - Python, que usamos esta piscina.

### Python

Python es un lenguaje de programación de alto nivel, código abierto y propósito general. Su sintaxis es extremadamente limpia, clara y parecida al inglés. El programador holandés Guido van Rossum lo creó a principio de los años 90 centrándose en la legibilidad del código. Aunque es mucho más fácil de leer, escribir y mantener que otros lenguajes tradicionales como C o C++, el científico danés de la computación, Bjarne Stroustrup, quien desarrolló C++ en 1979, a menudo critica que Python prefiera código fácil y legible sobre rendimiento.

### SQL

SQL son las siglas de *Structured Query Language*. Esto se traduce como Lenguaje de Consulta Estructurado. Es un lenguaje de programación estándar desarrollado en los años 80 para comunicarse, gestionarl y manipular bases de datos reales.

Este lenguaje se emplea en Ingeniería de Datos para estructurar bases de datos masivas y mover información de un lugar a otro. Un científico de datos lo utiliza para extraer la materia prima para entrenar a sus modelos predictivos.

#### Lenguaje de Programación Estándar

Las reglas, sintaxis y funcionamiento de los **lenguajes de programación estándar** han sido aprobados por una organización oficial de estándares. Un documento oficial dicta exactamente cómo debe comportarse el lenguaje en cualquier ordenador o sistema. Esto permite que:

- **Portabilidad**: El código funciona en cualquier ordenador sin importar la marca o el sistema operativo.
- **Universalidad**: Cualquiera puede crear herramientas para ese lenguaje siempre que respete el estándar oficial.
- **Durabilidad**: Los programas siguen funcionando 20 años después porque las bases no cambian de golpe.

Un lenguaje que es indiscutiblemente un pilar de la informática y el cual está regulado estrictamente por la organización **ISO** es C, desarrollado pro Dennis Ritchie entre 1969 y 1973 en los Bell Labs de AT&T para facilitar la reescritura y portabilidad del sistema operativo Unix, en el cual se basan los sistemas operativos actuales.

> *Gracias, Dennis Ritchie.*

La Organización INternacional de Normalización (ISO) es una federación mundial independiente que nació en 1947 en Suiza. Está compuesta por los organismos nacionales de normalización de más de 170 países. Su función es crear estándares que faciliten el comercio global y garanticen la calidad. Un ejemplo de sus estándares es el formato de las fechas (AAAA-MM-DD).

El Instituto Nacional Estadounidense de Estándares (ANSI) es una organización privada sin fines de lucro fundada en 1918 en Estados Unidos para administrar y coordinar el sistema de estandarización voluntario dentro de EEUU. Aprueba las normas desarrolladas por comités de expertos, universidades y empresas estadounidenses para asegurarse de que sean justas y seguras.

ANSI reunió a los expertos de la industria en SQL para el primer estándar oficial en 1986. Un año después, ISO adoptó el mismo documento y lo convirtió en norma internacional. Así se evitó que cada empresa inventara su propia versión de SQL y se garantizó que cualquier motor de base de datos del mundo pueda entender el lenguaje.

#### Base de datos en SQL

Una base de datos es una colección organizada de información estructurada. Las bases de datos relacionales se almacena en un sistema informático y se gestiona mediante el lenguaje SQL.

##### Componentes

- Las **tablas** son los contenedores principales.
- Las **columnas** son los campos que definen el tipo de dato que se va a guardar.
- Las **filas** son los registros individuales de cada elemento.
- Las **llaves** o **claves** son los enlaces que conectan las tablas, evitando la necesidad de repetir información que está en otra tabla.

##### Gestión

Las bases de datos relacionales, en SQL, requieren un software llamado **RDBMS**: Sistema de Gestión de Bases de Datos Relacionales. Estos programas interpretan las órdenes enviadas en SQL. MySQL/PostgreSQL son opciones de código abierto muy utilizadas en aplicaciones web y plataformas modernas.

**PostgreSQL** es uno de los sistemas de gestión de bases de datos relacionales de código abierto más avanzados, potentes y populares. Es completamente gratuito y está mantenido por una comunidad enorme de desarrolladores independientes. Esto no quita que siguen de forma muy estricta los estándares oficiales de ISO y ANSI, así que los códigos funcionarán de forma casi idéntica en cualquier otro sistema profesional.

Algunas características de PostgreSQL son:

- Se comporta, en parte, como la programación orientada a objetos en tanto permite definir tipos de datos complejos y personalizados.
- Garantiza transacciones de datos seguras y precisas incluso si hay cortes de energía y/o fallos en el servidor. Al ser extremadamente robusto, es el favorito de los bancos y las aplicaciones financieras.
- Permite guardar y consultar documentos en formato JSON con una velocidad increíble, lo que le da la flexibilidad de las bases de datos modernas. **JSON** (siglas de *JavaScript Object Notation* o Notación de Objetos de JavaScript) es un formato de texto ligero y de código abierto que se utiliza para almacenar e intercambiar datos. Un dato en JSON se organiza siempre en pares de "clave" y "valor" rodeados por llaves `{}`. Es una estructura muy similar a una ficha técnica.
- Es extensible usando lenguajes como Python, C o C++.
