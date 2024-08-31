# Practica 1

**Los ejercicios de la practica que no se encuentras aqui fueron realizados en cuaderno.**

## **Índice**
- [Ejercicio 4](#ejercicio-4-kernel)
    - [¿Qué es? Indique una breve reseña histórica acerca de la evolución del Kernel de GNU/Linux](#ejercicio-a-4)
    - [¿Cuáles son sus funciones principales?](#ejercicio-b-4)
    - [¿Cuál es la versión actual? ¿Cómo se definía el esquema de versionado del    Kernel en versiones anteriores a la 2.4? ¿Qué cambió en el versionado se impuso a partir de la versión 2.6?](#ejercicio-c-4)
    - [¿Es posible tener más de un Kernel de GNU/Linux instalado en la misma máquina?](#ejercicio-d-4)
    - [¿Dónde se encuentra ubicado dentro del File System?](#ejercicio-e-4)
    - [¿El Kernel de GNU/Linux es monolítico? Justifique.](#ejercicio-f-4)
- [Ejercicio 5](#ejercicio-5-interpretador-de-comandos)

## Ejercicio 4 Kernel

### Ejercicio A-4
**¿Qué es? Indique una breve reseña histórica acerca de la evolución del Kernel de GNU/Linux**

- El kernel es el núcleo central de un sistema operativo. Su función principal es gestionar los recursos del hardware de la computadora (como la CPU, la memoria y los dispositivos de entrada/salida) y proporcionar una interfaz para que el software pueda interactuar con el hardware de manera eficiente. El kernel opera en el nivel más bajo del sistema operativo, ejecutándose en modo privilegiado para tener control completo sobre el hardware.

- Historia breve:
    - 1983: Richard Stallman inició el Proyecto GNU para crear un sistema operativo libre, pero faltaba un kernel funcional.

    - 1991: Linus Torvalds, un estudiante de Helsinki, desarrolló el kernel Linux como un proyecto personal. Combinado con los componentes de GNU, nació GNU/Linux.

    - 1994: Se lanzó la versión 1.0 del kernel de Linux, marcando su madurez.

    - Años 90: Linux ganó popularidad en servidores y sistemas Unix, expandiendo su uso.

    - 2000-presente: Linux se consolidó en servidores, dispositivos móviles (como Android) y más. Su desarrollo es colaborativo, con miles de contribuciones globales.

    - En resumen, el kernel de GNU/Linux pasó de ser un proyecto estudiantil a convertirse en la base de sistemas operativos en todo el mundo, gracias a su desarrollo abierto y colaborativo.

### Ejercicio B-4
**¿Cuáles son sus funciones principales?**

- Gestión de Procesos:

    - Controla la creación, planificación y terminación de procesos. También maneja la multitarea, permitiendo que múltiples procesos se ejecuten simultáneamente.
- Gestión de Memoria:

    - Administra la memoria del sistema, asignando y liberando espacio según lo necesiten los procesos. También gestiona la memoria virtual, proporcionando una abstracción de más memoria de la que físicamente está disponible.
    
- Gestión de Dispositivos:
    - Actúa como intermediario entre el hardware y el software, controlando y comunicándose con dispositivos como discos duros, impresoras y otros periféricos mediante controladores de dispositivos.
- Gestión del Sistema de Archivos:

    - Administra cómo se almacenan, recuperan y organizan los datos en los dispositivos de almacenamiento. Proporciona una estructura jerárquica para el acceso a archivos y directorios.
- Gestión de Seguridad y Permisos:

    - Implementa mecanismos de seguridad, controlando el acceso a los recursos del sistema y garantizando que solo los procesos autorizados puedan realizar ciertas operaciones.
- Interrupciones y Señales:

    - Maneja las interrupciones de hardware, que son señales enviadas por dispositivos para indicar que necesitan atención. También gestiona señales entre procesos para la comunicación y sincronización.
- Abstracción del Hardware:

    - Proporciona una interfaz estándar para que el software interactúe con el hardware, independientemente de las diferencias en los componentes físicos.

### Ejercicio C-4
**¿Cuál es la versión actual? ¿Cómo se definía el esquema de versionado del Kernel en
 versiones anteriores a la 2.4? ¿Qué cambió en el versionado se impuso a partir de la
 versión 2.6?**

 - Esquema de Versionado Anterior a la Versión 2.4
- Antes de la versión 2.4, el esquema de versionado del kernel de Linux seguía el formato X.Y.Z:

    - X: Indica la versión principal (major).
    - Y: Indica la versión secundaria (minor).
    - Z: Indica la versión de parche (patch).
    - Un aspecto clave de este sistema es que si el número Y es par, la versión es considerada estable (e.g., 1.2.x). Si el número Y es impar, la versión es considerada de desarrollo o inestable (e.g., 1.3.x).

- Cambios en el Versionado a Partir de la Versión 2.6
A partir de la versión 2.6, el esquema de versionado cambió significativamente:

    - Se eliminó la distinción entre números pares e impares para versiones estables e inestables. Todas las versiones 2.6.x eran consideradas estables.
    - El kernel comenzó a seguir un ciclo de lanzamientos más regular, con nuevas versiones menores (actualizaciones del tercer dígito, Z) lanzadas aproximadamente cada 2 o 3 meses.
    - Se mantuvo el formato X.Y.Z, pero con un enfoque en la evolución continua y mejoras incrementales, sin hacer cambios drásticos en el número de versión principal (X) o secundaria (Y) durante un largo período.
- Este cambio hizo que el desarrollo del kernel fuera más predecible y facilitó la integración de nuevas características de manera más gradual. En versiones posteriores, específicamente a partir de la versión 4.x, el kernel de Linux adoptó un esquema de versionado que no distinguía entre versiones mayores y menores de la misma manera que antes, con versiones lanzadas de manera continua y el número de versión incrementado conforme era necesario.

### Ejercicio D-4

**¿Es posible tener más de un Kernel de GNU/Linux instalado en la misma máquina?**

- Si, tener multiples kernel instalados en tu maquina es una practica comun en linux. Sin embargo en ejecucion solo se podra tener uno solo por obvias razones.

### Ejercicio E-4
**¿Dónde se encuentra ubicado dentro del File System?**

- Se encuentra dentro del directorio:
~~~
/boot
~~~ 
- Aqui se encuentran los archivos del kernel y otros archivos necesarios para el arranque del sistema.


### Ejercicio F-4
**¿El Kernel de GNU/Linux es monolítico? Justifique.**

- Primero definamos lo que es un kernel monolitico:
    - 

## Ejercicio 5 Interpretador de comandos

