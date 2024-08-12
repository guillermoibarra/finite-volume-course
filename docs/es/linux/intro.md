# Introducción a Linux

Este curso, titulado **"Fundamentos de los Métodos de Volúmenes Finitos en CFD: Teoría, Práctica e Implementación en Python,"** se enfoca en las herramientas utilizadas en la dinámica de fluidos computacional (CFD). Si tuviéramos que resumir la esencia de este curso en una sola línea, podría ser algo como **"Introducción a las Herramientas para el Análisis Multidisciplinario de Sistemas de Ingeniería."** Aquí, utilizamos el término "herramienta" en un sentido amplio: no solo como un dispositivo físico, sino como cualquier cosa que ayude a alcanzar un objetivo, resolver un problema o facilitar un proceso. Esta interpretación más amplia incluye no solo dispositivos físicos, sino también software, metodologías, técnicas y algoritmos.

Por ejemplo, el método de volúmenes finitos—una técnica que exploraremos en este curso—es una herramienta para resolver ecuaciones diferenciales, lo cual, a su vez, nos ayuda a representar procesos físicos. En este sentido, es una herramienta utilizada dentro de otra herramienta. A medida que avancemos en este curso, encontrarás una variedad de herramientas como estas, cada una con sus fortalezas y limitaciones. Comprender estos aspectos es crucial para utilizarlas efectivamente en ingeniería.

Ahora, dirijamos nuestra atención a Linux. A menudo descrito como una familia de sistemas operativos de código abierto y similares a Unix, Linux es una herramienta de software por excelencia. Así como las herramientas físicas nos permiten manipular nuestro entorno, Linux nos permite controlar e interactuar con nuestro entorno computacional. Al igual que otros sistemas operativos como Windows o macOS, Linux gestiona la memoria y el procesador de una computadora, facilitando la comunicación entre el hardware y el software a través de su componente central, el kernel.

En el contexto de este curso, Linux es más que solo un sistema operativo; es la base sobre la cual construiremos y ejecutaremos las diversas herramientas necesarias para el análisis multidisciplinario. Su naturaleza de código abierto, flexibilidad y amplio soporte para la computación científica lo hacen un entorno ideal para las simulaciones y análisis complejos que realizaremos. A medida que te adentres en este curso, verás cómo Linux, junto con otras herramientas, desempeña un papel crucial en la habilitación de un análisis riguroso y en la resolución innovadora de problemas que definen la ingeniería moderna.

## Distribuciones y los Muchos Sabores de Linux

Si estás listo para explorar Linux, tu primer paso será elegir una distribución de Linux, o distro. Linux en sí es esencialmente el kernel, la parte central del sistema operativo, mientras que una distro combina el kernel con bibliotecas y herramientas de soporte para crear un sistema operativo completo. En febrero de 2024, había más de 400 distribuciones activas de Linux, según Tecmint. En lugar de sugerir una distribución específica, es más útil comprender los factores clave que las diferencian: gestión de paquetes, interfaz gráfica y ciclo de lanzamiento.

### Repositorios y Gestión de Paquetes

La columna vertebral de cualquier distribución de Linux es su sistema de repositorios y gestión de paquetes, que determina cómo se instala, actualiza y gestiona el software. Diferentes distros utilizan diferentes gestores de paquetes y repositorios, lo que influye en la disponibilidad del software, la facilidad de instalación y qué tan actualizado está tu sistema.

#### Sistemas Basados en Debian

Las distros basadas en Debian, como Ubuntu, Linux Mint y Kali Linux, utilizan el gestor de paquetes APT (Advanced Package Tool). APT es conocido por su gran repositorio de paquetes y estabilidad, lo que lo hace adecuado tanto para entornos de escritorio como de servidor. Este equilibrio entre el software más reciente y la estabilidad lo convierte en una excelente opción para principiantes y aquellos que buscan ejecutar un servidor.

#### Sistemas Basados en Arch

Distros como EndeavourOS y Manjaro utilizan el gestor de paquetes Pacman. Los sistemas basados en Arch, particularmente cuando se instalan desde cero, permiten a los usuarios controlar cada detalle del proceso de instalación y selección de paquetes. Mientras que distros como EndeavourOS y Manjaro ofrecen una experiencia de instalación más sencilla, aún ofrecen los beneficios del modelo de lanzamiento continuo de Arch y el control del usuario. Estos sistemas están recomendados para usuarios que desean tener un control total sobre su sistema, aunque vienen con una curva de aprendizaje pronunciada.

#### Sistemas Basados en RPM

Los sistemas basados en RPM, como Fedora y Red Hat Enterprise Linux (RHEL), están más orientados a entornos empresariales, priorizando la estabilidad y la seguridad. Estos sistemas son ideales para usuarios que priorizan la estabilidad, particularmente en entornos profesionales o de producción.

### Interfaz Gráfica

El entorno de escritorio (DE) define la experiencia visual e interactiva de usar tu sistema Linux. Dicta la apariencia, el rendimiento y el nivel de personalización posible. Elegir el DE adecuado puede mejorar significativamente tu experiencia como usuario.

#### GNOME

GNOME ofrece una interfaz pulida y coherente con un enfoque en la simplicidad y la eficiencia. Sin embargo, puede ser intensivo en recursos, lo que lo hace menos ideal para hardware más antiguo. Es adecuado para usuarios que prefieren un entorno moderno y rico en funciones, con menos énfasis en la personalización.

#### XFCE

XFCE está diseñado para ser eficiente en recursos mientras aún proporciona una experiencia completa de escritorio. Es una excelente opción para usuarios con hardware más antiguo o aquellos que prefieren un enfoque minimalista. XFCE es ideal para aquellos que priorizan la velocidad y la simplicidad, especialmente en hardware más antiguo.

#### KDE Plasma

KDE Plasma es conocido por su flexibilidad y atractivo estético. Ofrece una amplia gama de opciones de personalización, lo que permite a los usuarios adaptar la interfaz a sus preferencias sin sacrificar el rendimiento. Es perfecto para usuarios que valoran la personalización y el atractivo visual.

#### Gestores de Ventanas en Tiling (e.g., i3, Sway, Awesome)

Los gestores de ventanas en tiling (TWMs) proporcionan un espacio de trabajo minimalista y altamente eficiente al organizar las ventanas en un patrón de cuadrícula sin superposición. Están diseñados para usuarios que prefieren la navegación mediante el teclado y un entorno libre de distracciones. Los TWMs son increíblemente ligeros y altamente personalizables, aunque a menudo vienen con una curva de aprendizaje más pronunciada. Son ideales para usuarios que priorizan la eficiencia, el minimalismo y los flujos de trabajo centrados en el teclado.

### Ciclo de Lanzamiento

El ciclo de lanzamiento de una distribución define con qué frecuencia se entregan las actualizaciones y cómo se manejan los cambios importantes del sistema. Esto puede afectar la estabilidad del sistema y la frescura de su software.

#### Lanzamiento Continuo

Las distros de lanzamiento continuo proporcionan las últimas actualizaciones de software tan pronto como están disponibles, eliminando la necesidad de actualizaciones importantes del sistema. Aunque esto asegura que siempre tengas las características más recientes, a veces puede conducir a la inestabilidad. Las distros de lanzamiento continuo son ideales para usuarios que prefieren tener el software más reciente y se sienten cómodos gestionando los posibles riesgos asociados con las actualizaciones frecuentes.

#### Lanzamiento Punto

Las distros de lanzamiento punto siguen un calendario de lanzamiento fijo, ofreciendo actualizaciones importantes periódicamente. Estos sistemas a menudo vienen con opciones de soporte a largo plazo (LTS), lo que garantiza estabilidad durante un período prolongado. Las distros de lanzamiento punto son beneficiosas para usuarios que priorizan la estabilidad y la predictibilidad del sistema, particularmente en entornos profesionales o de producción.

