# Documento de propuesta  

| <img width="200px" src="./assets/NeuroPlay/NeuroPlay-Photoroom.png"/> | NeuroPlay  es una plataforma de juegos interactivos orientada a personas con TDAH (Trastorno por Déficit de Atención e Hiperactividad)  |
| ----------- | ----------- |

![Banner de la aplicación](../assets/NeuroPlay.png)

1. [Idea](#idea)
2. [Audiencia objetivo](#audiencia)
3. [Análisis de mercado](#análisis-de-mercado)
4. [Funcionalidades clave](#funcionalidades-clave)
6. [Lenguajes de programación web](#lenguajes-de-programación-web)
5. [Modelos de ejecución](#modelos-de-ejecución)
7. [Tecnologías a utilizar](#)
8. [Compatibilidad en navegadores](#)
---
9. [Bibliografía](#bibliografía)

## Idea

**NeuroPlay** será una plataforma de **juegos interactivos** diseñada específicamente para personas con TDAH (Trastorno por Déficit de Atención e Hiperactividad). Su propósito es ofrecer una experiencia de juego **atractiva** y **envolvente** que ayude a mejorar el **enfoque**, la **concentración** y las **habilidades cognitivas** mediante sistemas de recompensa inmediatos y juegos diseñados para mantener el interés y motivación de los usuarios. Cada juego se adaptará a los patrones de atención y comportamiento comúnmente observados en personas con TDAH, brindando entretenimiento y refuerzos positivos continuos.

## Audiencia 

La audiencia principal de la aplicación son **niños, adolescentes y adultos jóvenes con TDAH** que buscan formas atractivas y dinámicas para mejorar su enfoque y disfrutar de experiencias de juego. También puede ser útil para padres y profesionales (como psicólogos y educadores) que buscan herramientas que complementen las intervenciones tradicionales. La relevancia de esta aplicación radica en su capacidad para ofrecer entretenimiento diseñado con base en las necesidades cognitivas y de atención de personas con TDAH, lo que les permitirá disfrutar mientras desarrollan habilidades como la concentración y la organización.

## Análisis de mercado 

Algunas aplicaciones que ya abordan el TDAH o proporcionan juegos de entrenamiento mental son [Lumosity](https://www.lumosity.com/es/), [Elevate](https://elevateapp.com/), [CogniFit](https://www.cognifit.com/es?srsltid=AfmBOor6sW8jNPi0H_cDEtImTVcAVeBpm5RymFDW9_JZ51LagFVqR4Dc) y [Peak](https://www.peak.net/). Estas apps se enfocan en el entrenamiento cognitivo, pero no están completamente diseñadas para el TDAH ni tienen un sistema de recompensas inmediato que se alinee con sus necesidades. La diferenciación de nuestra aplicación estará en los **juegos rápidos, interactivos y con refuerzos visuales y sonoros inmediatos, que mantendrán el interés**. Además, la plataforma incluirá la capacidad de personalizar la experiencia y enfocarse en diferentes áreas cognitivas (memoria, atención, rapidez de respuesta) con recompensas sociales y de personalización, lo que fomentará la adherencia a largo plazo.

## Funcionalidades clave 

- **Sistema de autenticación**: Registro e inicio de sesión seguro para usuarios, con la posibilidad de perfiles múltiples (orientado a la familia p. ej., padres e hijos).
- **Gestión de usuarios**: Personalización de perfiles y seguimiento del progreso individual.
- **Sistema de recompensas**: Recompensas inmediatas por logros en los juegos (puntos, medallas, skins personalizables).
- **Tablas de clasificación**: Rankings globales y por grupo, para fomentar la competencia amistosa.
- **Monitoreo del progreso**: Función de seguimiento de mejoras cognitivas y estadísticas del juego.
- **Juegos interactivos**: Diferentes tipos de juegos diseñados específicamente para mejorar la atención y concentración.
- **Notificaciones personalizadas**: Recordatorios de juegos y eventos especiales, personalizados según el comportamiento del usuario.
- **Modo sin conexión**: Algunos juegos podrán jugarse sin conexión a Internet.
- **Interfaz accesible**: Diseño intuitivo y sencillo, con colores llamativos y navegación clara para evitar la sobrecarga sensorial.

## Modelos de ejecución

En el modelo de ejecución en cliente, las operaciones y la lógica del juego se ejecutan directamente en el navegador del usuario. Este modelo es ideal para la parte interactiva y visual de los juegos, ya que proporciona una respuesta rápida y fluida sin depender constantemente del servidor.

En el modelo de ejecución en servidor, las operaciones se realizan en el servidor y luego los resultados se envían al cliente. Esto es más adecuado para el almacenamiento de perfiles de usuarios, las recompensas, el progreso y las estadísticas, ya que requiere seguridad y persistencia de datos.

Un ejemplo claro es usar el modelo de cliente para la lógica de los juegos y el modelo de servidor para la autenticación y gestión de datos de usuarios.

## Lenguajes de programación web

JavaScript: Es el lenguaje más utilizado en el lado del cliente, permitiendo interactividad en tiempo real en los juegos. Ventajas: Gran compatibilidad con navegadores, velocidad y capacidad de crear experiencias interactivas complejas. Desventajas: Puede ser difícil de depurar en aplicaciones muy grandes y puede requerir bibliotecas adicionales.

TypeScript: Una extensión de JavaScript que añade tipado estático. Ventajas: Mayor robustez y detección de errores en tiempo de desarrollo, especialmente útil en proyectos grandes. Desventajas: Mayor curva de aprendizaje comparada con JavaScript puro, y requiere compilación.


## Bibliografía

1. Aquí busqué información acerca de ventajas y desventajas de Javascript y Typescript -> [Click aquí](https://www.campusmvp.es/recursos/post/typescript-contra-javascript-cual-deberias-utilizar.aspx)

2. toma [chatgpt](chatgpt.com)