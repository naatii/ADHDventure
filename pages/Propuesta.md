# Documento de propuesta  

| <img width="200px" src="../assets/NeuroPlay/NeuroPlay-Photoroom.png"/> | NeuroPlay  es una plataforma de juegos interactivos orientada a personas con TDAH (Trastorno por Déficit de Atención e Hiperactividad)  |
| ----------- | ----------- |

![Banner de la aplicación](../assets/NeuroPlay.png)

1. [Idea](#idea)
2. [Audiencia objetivo](#audiencia)
3. [Análisis de mercado](#análisis-de-mercado)
4. [Funcionalidades clave](#funcionalidades-clave)
5. [Tecnologías usadas](#)
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

## Tecnologías usadas y justificación

En mi caso habiendo comparado las distintas herramientas como: Vue, React, Springboot y Laravel he llegado a la siguiente conclusión:

- **Backend: Laravel**

    Laravel es más rápido de implementar y es fácil de integrar con MongoDB. También ofrece un sistema muy cómodo para manejar autenticación y recompensas (usando Eloquent ORM). Dado que la aplicación inicial está más enfocada en la entrega de funcionalidades rápidas y escalabilidad moderada, Laravel es ideal, frente a Springboot.

- **Frontend: React** 

    React es perfecto ya que busco una interfaz de usuario interactiva y escalable a largo plazo. Me permitirá crear componentes reutilizables y manejar los estados de la aplicación de manera eficiente, especialmente si quiero integrar muchas funcionalidades dinámicas (como notificaciones, recompensas y estadísticas en tiempo real).

- **Base de datos: MongoDB**

    MongoDB se adapta perfectamente a las necesidades de la plataforma, permitiendo un crecimiento rápido en cuanto al número de usuarios y flexibilidad para modificar los esquemas de datos de los juegos y recompensas.

## Bibliografía

1. Aquí busqué información acerca de ventajas y desventajas de Javascript y Typescript -> [Click aquí](https://www.campusmvp.es/recursos/post/typescript-contra-javascript-cual-deberias-utilizar.aspx)