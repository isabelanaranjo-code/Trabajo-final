# Huellitas🐾🐶🐱
### Sistema de gestión de PQRS para el bienestar animal UdeA

## 1. - 2. Integrantes👯👯
### • Laura Valentina Forero Rojas
Soy estudiante de Ingeniería Industrial con interés por la organización de procesos, el análisis de información y el desarrollo de soluciones que mejoren la gestión administrativa. Me destaco por ser responsable, creativa y metódica al documentar proyectos, elaborar informes y estructurar el trabajo en equipo. Dentro del desarrollo de "Huellitas" puedo aportar en la planificación del proyecto y la documentación en GitHub.

### • Isabela Naranjo Gómez
Soy estudiante de Ingeniería Industrial y me interesa aprender sobre diferentes áreas de la carrera y adquirir nuevos conocimientos. Me considero una persona responsable, perfeccionista y analítica, por lo que me gusta trabajar con detalle, revisar la información y comprender bien cada actividad antes de realizarla. También tengo una actitud de aprendizaje constante y un alto compromiso con los proyectos en los que participo. Dentro del desarrollo de "Huellitas", puedo aportar principalmente en el manejo y organización de los datos, la gestión de los archivos del programa y la revisión detallada de la información.

### • Luciana Mejía Cardona
Soy estudiante de Ingeniería Industrial y me interesan especialmente temas como la automatización, el manejo del personal, el control de calidad y la producción. Me considero una persona paciente, curiosa, sociable y alegre. También me gusta hacer las cosas de la mejor manera posible, por lo que suelo ser muy detallista y cuidadosa al momento de revisar mi trabajo. Dentro de un equipo me gusta proponer ideas y buscar nuevas perspectivas, pero también escuchar las opiniones de los demás y apoyar la opción que mejor contribuya al objetivo del proyecto. Para la realización de nuestro proyecto "Huellitas", puedo aportar principalmente en el diseño, el manejo de datos y la programación, además de la revisión de errores, la organización de estructuras y la elaboración de presentaciones.

### • Juliana Silva Moreno
Soy estudiante de Ingeniería Industrial, con interés por aprender y desarrollar conocimientos en diferentes áreas de la carrera. Me caracterizo por ser una persona creativa, comprometida y con iniciativa, a quien le gusta proponer ideas, buscar soluciones y cuidar los detalles en los proyectos que realiza. También considero importante el trabajo en equipo y la comunicación para lograr buenos resultados. Dentro del desarrollo de "Huellitas", puedo aportar principalmente en la generación de ideas, la organización y planificación del proyecto, el análisis de información y la elaboración de propuestas que contribuyan al desarrollo del programa.

## 3. Huellitas🐾🐾
<img src="images/logo.png" alt="Logo de Huellitas" width="180">

Huellitas es un sistema de gestión de PQRS diseñado para registrar y administrar las solicitudes relacionadas con el bienestar de perros y gatos de la Universidad de Antioquia. El software permitirá almacenar la información de cada caso en archivos planos independientes, generar radicados consecutivos, consultar el estado de las solicitudes y obtener estadísticas que apoyen la gestión del programa de bienestar animal. Su desarrollo se realizará completamente en Python mediante una aplicación de consola intuitiva y fácil de utilizar.

## 4. Licencia del software🧑‍💻🪪

Huellitas ©️ 2026 es un proyecto académico desarrollado por Laura Valentina Forero Rojas, Isabela Naranjo Gómez, Luciana Mejía Cardona y Juliana Silva Moreno.

Este proyecto está licenciado bajo la *Creative Commons Atribución–NoComercial–SinDerivadas 4.0 Internacional (CC BY-NC-ND 4.0)*.

Esto significa que el proyecto puede compartirse siempre que se reconozca la autoría, no se utilice con fines comerciales y no se distribuyan versiones modificadas.

>* <a href="https://github.com/isabelanaranjo-code/Trabajo-final">Huellitas</a> ©️ 2026 by <a href="https://github.com/isabelanaranjo-code/Trabajo-final">Laura Valentina Forero Rojas, Isabela Naranjo Gómez, Luciana Mejía Cardona, Juliana Silva Moreno</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nd.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

## 5. Reporte de visión🗒️🖋️
### Visión

Desarrollar un software confiable y organizado que facilite la gestión de las PQRS relacionadas con el bienestar de perros y gatos de la Universidad de Antioquia, permitiendo registrar, consultar y realizar seguimiento a cada solicitud de manera eficiente y estructurada.

### Objetivo general

Crear un programa en Python que permita registrar, consultar y administrar documentos PQRS mediante archivos planos, garantizando radicados consecutivos, validación de datos y una gestión organizada de la información.

### Objetivos específicos

- Registrar peticiones, quejas, reclamos y sugerencias.
- Validar la información ingresada por el usuario.
- Generar radicados únicos y consecutivos.
- Consultar el estado de las solicitudes registradas.
- Obtener estadísticas relevantes para apoyar la toma de decisiones.

### Beneficios del software

- Organiza la información de forma estructurada.
- Reduce errores en el registro manual.
- Facilita el seguimiento de cada PQRS.
- Genera estadísticas útiles para la gestión del bienestar animal.
- Mantiene la información separada según el tipo de solicitud.

## 6. Especificación de requisitos🔐📑

Los requisitos del sistema Huellitas establecen las funcionalidades y condiciones que deberá cumplir el software para gestionar adecuadamente las peticiones, quejas, reclamos y sugerencias relacionadas con el bienestar animal de la Universidad de Antioquia.

Los requisitos funcionales describen las operaciones que podrá realizar el usuario dentro del programa, mientras que los requisitos no funcionales determinan las características técnicas, de seguridad, organización, confiabilidad y facilidad de uso que deberá cumplir el sistema.

### Requisitos funcionales

| Código | Descripción |
| :--- | :--- |
| *RF-01* | El sistema permitirá registrar peticiones, quejas, reclamos y sugerencias relacionadas con el bienestar de perros y gatos de la Universidad de Antioquia. Para ello, solicitará la información del usuario, el tipo de solicitud, la descripción detallada de la situación y los datos necesarios para identificar el caso. |
| *RF-02* | El sistema generará automáticamente un número de radicado único y consecutivo para cada solicitud registrada. Este identificador permitirá diferenciar los casos, evitar duplicidades y facilitar su consulta y seguimiento posterior. |
| *RF-03* | El sistema verificará que los campos obligatorios estén completos antes de guardar una solicitud. También validará que los nombres, documentos de identidad, números telefónicos, correos electrónicos y fechas cumplan con los formatos establecidos. Si encuentra información incorrecta o incompleta, informará al usuario y solicitará su corrección. |
| *RF-04* | El sistema almacenará las solicitudes en cuatro archivos planos independientes, correspondientes a peticiones, quejas, reclamos y sugerencias. Cada registro deberá conservar su información para que pueda consultarse incluso después de cerrar y volver a ejecutar el programa. |
| *RF-05* | El sistema calculará automáticamente la fecha máxima de respuesta de cada solicitud, tomando como referencia un plazo de 30 días calendario desde la fecha de radicación. Esta fecha quedará asociada al registro para facilitar el control de los tiempos de atención. |
| *RF-06* | Después de registrar una solicitud, el programa generará un comprobante en formato TXT que incluirá el número de radicado, la fecha de registro, el tipo de PQRS y los datos principales del caso. El comprobante servirá como soporte de la recepción de la solicitud. |
| *RF-07* | El usuario podrá consultar una solicitud ingresando su número de radicado. El sistema buscará el registro correspondiente y mostrará los datos del solicitante, la descripción del caso, la fecha de radicación, la fecha máxima de respuesta y el estado actual. Si el radicado no existe, presentará un mensaje informativo. |
| *RF-08* | El sistema permitirá modificar el estado de las solicitudes registradas, de acuerdo con las etapas de atención establecidas: Registrada, En proceso y Solucionada. Los cambios de estado deberán conservar la información original de la solicitud y permitir identificar su situación actual. |
| *RF-09* | El programa permitirá identificar las solicitudes pendientes de atención, las que se encuentran en proceso y las que ya fueron solucionadas. También facilitará la identificación de los casos cuya fecha máxima de respuesta esté próxima o se haya vencido, para apoyar el seguimiento oportuno. |
| *RF-10* | El sistema generará reportes estadísticos a partir de la información almacenada. Deberá calcular obligatoriamente el promedio de días que tarda la atención de las PQRS y, adicionalmente, cinco estadísticas que permitan analizar la gestión, como la cantidad de solicitudes por tipo, la cantidad por estado, el total de solicitudes recibidas, la proporción de solicitudes solucionadas y la cantidad de solicitudes pendientes. Los resultados deberán presentarse de manera clara y comprensible. |

### Requisitos no funcionales

| Código | Descripción |
| :--- | :--- |
| *RNF-01* | El software será desarrollado en el lenguaje de programación Python y funcionará mediante una aplicación de consola. Las operaciones principales de registro, consulta y seguimiento deberán poder ejecutarse sin requerir conexión permanente a internet. |
| *RNF-02* | La interfaz de consola deberá contar con un menú principal organizado, con opciones claramente identificadas para registrar, consultar, actualizar y generar reportes de PQRS. La navegación deberá ser sencilla y permitir que el usuario comprenda qué acción debe realizar en cada momento. |
| *RNF-03* | La información se almacenará de manera persistente en archivos planos con extensión TXT. Los archivos deberán estar organizados por tipo de solicitud y conservar los registros después de finalizar la ejecución del programa. |
| *RNF-04* | El código fuente tendrá una estructura modular que facilite su lectura, mantenimiento y modificación. Las funciones de validación, manejo de archivos, registro de solicitudes y generación de reportes deberán organizarse en módulos independientes, de acuerdo con las necesidades del proyecto. |
| *RNF-05* | El sistema deberá manejar adecuadamente los errores de entrada y las situaciones inesperadas, como datos incompletos, formatos incorrectos, radicados inexistentes o dificultades al acceder a los archivos. En estos casos, mostrará mensajes comprensibles y evitará que el programa se cierre inesperadamente. |
| *RNF-06* | La información presentada en pantalla y en los comprobantes TXT deberá tener una estructura clara, ordenada y legible. Los mensajes deberán utilizar un lenguaje sencillo para facilitar la comprensión de los usuarios. |
| *RNF-07* | El sistema deberá proteger la integridad de los registros almacenados, evitando la duplicación de radicados y la modificación accidental de la información durante las consultas. Las actualizaciones deberán conservar los datos originales que no sean objeto de modificación. |


## 7. Plan de proyecto💸💰⌛

El plan de proyecto organiza las actividades necesarias para desarrollar Huellitas, establece los responsables de cada proceso, distribuye el trabajo durante las *16 semanas* del semestre y presenta la valoración del tiempo de práctica formativa invertido por el equipo.

### Actividades y responsables

Las actividades se distribuyen teniendo en cuenta los intereses, habilidades y fortalezas de cada integrante. Cada persona tendrá responsabilidades principales dentro del proyecto, pero las etapas de desarrollo, integración y revisión se realizarán de manera colaborativa para garantizar que todas conozcan el funcionamiento general del sistema.

| Actividad | Responsable(s) | Descripción del trabajo |
| :--- | :--- | :--- |
| *Coordinación y seguimiento del proyecto* | Laura Valentina Forero Rojas | Organizar las actividades del equipo, hacer seguimiento al cumplimiento del cronograma, coordinar reuniones de trabajo y registrar los avances y compromisos establecidos. También apoyará la identificación de dificultades que puedan afectar el desarrollo del proyecto. |
| *Documentación del proyecto* | Todo el equipo | Elaborar, organizar y actualizar la documentación del proyecto en GitHub. Esta actividad incluye la descripción del software, los objetivos, los requisitos, las actividades, el cronograma, el presupuesto y el registro de los avances realizados durante el semestre. |
| *Diseño de identidad visual* | Laura Valentina Forero Rojas y Luciana Mejía Cardona | Diseñar el logo y los elementos gráficos que representarán a Huellitas. También apoyar la organización visual de los documentos y materiales utilizados para presentar el proyecto. |
| *Análisis y organización de datos* | Isabela Naranjo Gómez | Crear y organizar el repositorio de GitHub, sus carpetas y el README. Definir cómo se organizará y almacenará la información de las PQRS, establecer la estructura de los registros, organizar los cuatro archivos planos por tipo de solicitud y comprobar que los datos puedan guardarse, recuperarse y consultarse correctamente. |
| *Validación de información* | Isabela Naranjo Gómez y todo el equipo | Definir y verificar las condiciones que deben cumplir los datos ingresados por los usuarios. Realizar pruebas de nombres, documentos, teléfonos, correos y fechas, comprobando que el programa identifique los errores y solicite las correcciones necesarias. |
| *Diseño de la solución y programación* | Luciana Mejía Cardona y todo el equipo | Participar en la definición de la estructura del programa y desarrollar las funcionalidades principales en Python. Esto incluye el menú de navegación, el registro de PQRS, la generación de radicados, las consultas, la actualización de estados y la generación de estadísticas. |
| *Planeación y análisis de requisitos* | Juliana Silva Moreno y todo el equipo | Analizar las necesidades que busca atender Huellitas, organizar las ideas del equipo y establecer las funcionalidades que deberá tener el software. Formular, revisar y ampliar los requisitos funcionales y no funcionales para que correspondan con el propósito del proyecto. |
| *Pruebas y corrección de errores* | Todo el equipo, con coordinación de Isabela Naranjo Gómez | Realizar pruebas de funcionamiento para comprobar el registro, almacenamiento, consulta, validación y actualización de las solicitudes. Identificar errores, registrar las dificultades encontradas y verificar que las correcciones permitan obtener los resultados esperados. |
| *Integración y revisión final* | Todo el equipo | Integrar las funcionalidades desarrolladas, comprobar que los diferentes módulos trabajen correctamente en conjunto y verificar que la información se conserve adecuadamente. Revisar la documentación, organizar los archivos del repositorio y preparar la entrega y sustentación del proyecto. |

Aunque cada actividad tiene responsables principales, todos los integrantes participarán en las decisiones importantes, la revisión de resultados y la solución de dificultades. De esta manera, el equipo podrá mantener una comunicación constante y garantizar que el desarrollo del software responda a los objetivos establecidos.

### Cronograma (Diagrama de Gantt - 16 semanas)

El cronograma contempla las 16 semanas del semestre académico y organiza las actividades de acuerdo con las etapas del proyecto: planeación, análisis, diseño, programación, integración, pruebas y entrega. 

Convención: 🟪 = semana en la que se desarrolla la actividad.

| Actividad | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| *Conformación del grupo y elaboración de actas* | 🟪 | 🟪 | 🟪 | 🟪 |   |   |   |   |   |   |   |   |   |   |   |   |
| *Organización del equipo y planeación* |   |   |   | 🟪 | 🟪 |   |   |   |   |   |   |   |   |   |   |   |
| *Análisis del problema y contexto* |   |   |   |   | 🟪 | 🟪 |   |   |   |   |   |   |   |   |   |   |
| *Identificación y especificación de requisitos* |   |   |   |   |   |   | 🟪 | 🟪 |   |   |   |   |   |   |   |   |
| *Documentación inicial del proyecto* |   |   |   |   | 🟪 | 🟪 | 🟪 | 🟪 |   |   |   |   |   |   |   |   |
| *Elaboración del reporte de visión, licencia y plan de proyecto* |   |   |   |   |   | 🟪 | 🟪 | 🟪 |   |   |   |   |   |   |   |   |
| *Diseño del logo e identidad del proyecto* |   |   |   |   |   |   |   | 🟪 |   |   |   |   |   |   |   |   |
| *Primera entrega y revisión de observaciones* |   |   |   |   |   |   |   | 🟪 | 🟪 |   |   |   |   |   |   |   |
| *Diseño de la estructura del programa y archivos* |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 | 🟪 |   |   |   |   |
| *Desarrollo del registro de PQRS* |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 |   |   |   |   |   |
| *Implementación de validaciones* |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 | 🟪 |   |   |   |   |
| *Almacenamiento en archivos y generación de comprobantes* |   |   |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 |   |   |   |
| *Desarrollo de consultas y actualización de estados* |   |   |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 |   |   |   |
| *Desarrollo de estadísticas y seguimiento de plazos* |   |   |   |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 |   |   |
| *Integración de funcionalidades* |   |   |   |   |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 |   |
| *Pruebas generales y corrección de errores* |   |   |   |   |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 | 🟪 |
| *Elaboración y revisión del manual y documentación final* |   |   |   |   |   |   |   |   |   |   |   |   |   | 🟪 | 🟪 | 🟪 |
| *Entrega final del software* |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   | 🟪 |
| *Preparación y sustentación del proyecto* |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   | 🟪 |

### Presupuesto del proyecto

De acuerdo con las indicaciones establecidas en la guía del trabajo final, el presupuesto corresponde al tiempo de práctica formativa invertido por los cuatro integrantes del equipo. Se contempla un total de *50 horas de trabajo, valoradas económicamente con referencia a un (1) Salario Mínimo Legal Mensual Vigente (SMLMV) de 2026, equivalente a *$1.750.905 COP**.

Este presupuesto representa una valoración académica del trabajo realizado y no un desembolso de dinero. Para distribuir el valor entre las actividades, se calcula una tarifa de referencia por hora dividiendo el SMLMV entre las 50 horas totales del proyecto.

$$\text{Valor de referencia por hora} = \frac{\$1.750.905}{50} = \$35.018,10\text{ COP}$$

La tarifa de $35.018,10 COP por hora es un valor de referencia que resulta de dividir el SMLMV entre las 50 horas del proyecto, no corresponde al valor legal de la hora de trabajo.

| Actividad | Horas estimadas | Valor estimado (COP) |
| :--- | :---: | :---: |
| *Planeación y reuniones de equipo* | 7 | $245.126,70 |
| *Investigación y análisis de requisitos* | 7 | $245.126,70 |
| *Documentación del proyecto* | 8 | $280.144,80 |
| *Desarrollo e integración del software* | 18 | $630.325,80 |
| *Pruebas y corrección de errores* | 10 | $350.181,00 |
| *Total* | *50* | *$1.750.905,00* |

En consecuencia, el valor total estimado del proyecto es de *$1.750.905 COP*, correspondiente a un SMLMV de 2026. Las 50 horas representan el tiempo total de trabajo formativo del equipo y se distribuyen entre las actividades necesarias para completar el desarrollo del software Huellitas.

