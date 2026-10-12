# EDUMARKET-RD
## Sistema educativo infantil – Educación, Creatividad y Sabiduría Infantil

### 1. Descripción del sistema

EDUMARKET RD es una propuesta de plataforma digital educativa dirigida a niños, padres y docentes. Su objetivo es facilitar la búsqueda y consulta de recursos educativos y actividades infantiles mediante una interfaz organizada y sencilla.

### 2. Problema que resuelve

Los recursos y las actividades educativas pueden encontrarse dispersos en diferentes lugares, lo que dificulta su búsqueda y organización. EDUMARKET RD propone reunir estos recursos en una plataforma que permita consultarlos de forma ordenada, clasificarlos por categorías y facilitar la navegación.

### 3. Objetivo general

Diseñar una plataforma educativa infantil que facilite el acceso a recursos educativos y actividades, mediante una organización clara de la información y una interfaz fácil de utilizar.

### 4. Funcionalidades principales

- Buscar recursos educativos.
- Registrar nuevos usuarios.
- Iniciar sesión.
- Organizar los recursos por categorías.
- Consultar actividades educativas infantiles.
- Navegar por las diferentes secciones de la plataforma.

### 5. Arquitectura seleccionada

Se propone una arquitectura por capas que separa las responsabilidades del sistema:

**Usuario → Frontend → Backend → Acceso a Datos → Base de Datos**

- **Frontend:** presenta las pantallas, los formularios, el catálogo y las opciones de navegación.
- **Backend:** procesa las solicitudes, aplica las reglas del sistema y coordina las funcionalidades.
- **Servicios/API:** permiten la comunicación entre el frontend y el backend.
- **Acceso a datos:** organiza las operaciones de consulta, registro y actualización de la información.
- **Base de datos:** almacenará la información de usuarios, recursos educativos, categorías y actividades infantiles.

La arquitectura descrita corresponde a la propuesta técnica del proyecto. Su implementación completa y la conexión funcional entre sus componentes deben verificarse durante el desarrollo.

### 6. Organización del frontend y backend

El frontend será la parte visible con la que interactuarán los usuarios. Desde esta sección podrán buscar recursos, consultar actividades, navegar por categorías y utilizar los formularios de registro e inicio de sesión.

El backend será responsable de recibir las solicitudes del frontend, validar los datos, aplicar la lógica del sistema y solicitar las operaciones necesarias a la capa de acceso a datos.

Ambas partes se comunicarán mediante servicios o una API. Por ejemplo, cuando un usuario busque un recurso educativo, el frontend enviará la solicitud al backend; este procesará la consulta, solicitará los datos correspondientes y devolverá los resultados para mostrarlos en pantalla.

### 7. Modelado del sistema

El proyecto contempla el uso de diagramas UML para representar sus requisitos, estructura e interacciones. Entre las clases principales identificadas se encuentran:

- Usuario.
- RecursoEducativo.
- Categoría.
- ActividadInfantil.

Estos elementos se relacionan con los requisitos funcionales y con la estructura de datos propuesta.

### 8. Herramientas utilizadas

- **GitHub:** almacenamiento del repositorio y control de versiones.
- **Git:** seguimiento de los cambios realizados en los archivos.
- **GitHub Projects:** organización y seguimiento de las tareas.
- **GitHub Issues:** registro y seguimiento de incidencias, mejoras y actividades pendientes.
- **Visual Paradigm Online:** elaboración de diagramas UML.
- **Markdown:** elaboración de la documentación mediante el archivo README.md.

### 9. Gestión del proyecto

El tablero de GitHub Projects se organiza en cinco estados:

- Backlog.
- Por hacer.
- En progreso.
- En revisión.
- Finalizado.

Estos estados permiten visualizar las actividades pendientes, las que se están desarrollando, las que requieren verificación y las que se han completado.

### 10. Estado actual del proyecto

EDUMARKET RD cuenta con requisitos funcionales identificados, una propuesta de arquitectura por capas, elementos de modelado UML, una estructura de datos propuesta y un tablero para organizar las tareas.

El diseño de la base de datos y la revisión de los requisitos aparecen como finalizados en el tablero de referencia. La arquitectura inicial está en revisión y varias funcionalidades e interfaces continúan en diferentes etapas de desarrollo.

Por tanto, el proyecto mantiene una base de análisis y diseño, pero las funcionalidades completas y su integración deben verificarse antes de considerarlas terminadas.

### 11. Próximos pasos

1. Continuar el desarrollo de la interfaz y la estructura de la plataforma.
2. Avanzar en el registro e inicio de sesión.
3. Desarrollar y validar el catálogo de recursos educativos.
4. Continuar con la consulta de actividades infantiles.
5. Completar la organización por categorías.
6. Verificar la comunicación entre frontend y backend.
7. Realizar pruebas de las funcionalidades.
8. Completar la documentación técnica y controlar las versiones mediante Git.

### 12. Control de versiones

Los cambios de la documentación y de los archivos del proyecto se registrarán mediante Git y se publicarán en GitHub con mensajes de confirmación descriptivos. Cada versión deberá reflejar el estado real de los archivos y de las funcionalidades implementadas.

**Proyecto:** EDUMARKET RD – Educación, Creatividad y Sabiduría Infantil.

**Estado:** proyecto en desarrollo, con requisitos, modelado y propuesta arquitectónica documentados.
