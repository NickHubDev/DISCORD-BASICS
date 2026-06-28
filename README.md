# Curso Completo de Discord | Estructura Base



# MÓDULO 1 · GANCHO O INICIO

---

## Objetivo

Esta sección debería empezar con una frase gancho para que el espectador no cierre el video rápido.

> ¿Te has fijado en que, hoy en día, da igual si eres gamer, estudiante, programador, creador de contenido o simplemente formas parte de una comunidad? Tarde o temprano acabarás utilizando Discord.
>
> Y no solo para hablar con tus amigos. Empresas, proyectos de código abierto, universidades, comunidades de videojuegos e incluso equipos de trabajo organizan su día a día dentro de esta plataforma.
>
> Pero... ¿por qué?
>
> ¿Qué tiene Discord para haberse convertido en el estándar cuando existen decenas de aplicaciones para comunicarse?
>
> Y, sobre todo, ¿cómo funciona realmente?
>
> En este vídeo no solo vas a aprender a usar Discord. Cuando termines, entenderás por qué está diseñado de la forma en que está y cómo aprovechar prácticamente todas las funciones de su interfaz.

Una vez logrado el gancho pasaremos a lo que considero más importante de todo.



# MÓDULO 2 · HISTORIA DE DISCORD

---

## Objetivo

Lo importante de este apartado es que se resalten los puntos clave porque se creo Discord y para que publicó.


# MÓDULO 3 · ANATOMÍA DE DISCORD

---

## Objetivo

En este apartado lo importante es dejar claro que hace cada cosa que apreciamos en la GUI de Discord, dividiéndolo en los siguientes bloques:

* **Barra izquierda:** Lista de Servidores y DMs.
* **Barra interior izquierda:** Lista de Categorías y Canales.
* **Centro:** Centro de Mensajería o Chat del Canal.
* **Barra derecha (Escondida):** Usuarios del servidor.

---

También estaría bien usar el esquema visual en estilo `.md` para mostrar la organización de cada apartado de Discord para que el usuario tenga una referencia técnica además de visual.

### Ejemplo

```text
Discord
│
├── Mensajes Directos (DMs)
│
├── Servidores
│   ├── Categorías
│   │   ├── Canal de texto
│   │   ├── Canal de voz
│   │   ├── Foro
│   │   └── Escenario
│   │
│   └── Usuarios
│
└── Ajustes de Usuario
```



# MÓDULO 4 · EL "USER" O CUENTA DEL USUARIO

---

## Objetivo

Con este apartado, lo que buscamos es que el usuario entienda para que sirve cada apartado que ve en los ajustes de su cuenta o perfil, en este apartado nos centraremos en la vista estética y global de su perfíl.

---

## Apartados

* Perfil global
* Nombre
* Avatar
* Biografía
* Estado
* Estado personalizado
* Pronombres
* Insignias
* Nitro

# MÓDULO 5 · COMUNIDADES Y SERVIDORES / CATEGORÍAS

---

## Objetivo

En este módulo daremos las bases de los servidores y comunidades, llegando hasta las configuraciones básicas y esenciales de este, los apartados que tocaremos serán:

---

## Apartados

* Crear servidor
* Unirse a servidor
* Abandonar servidor
* Carpetas
* Organización
* Configuración básica



# MÓDULO 6 · CANALES

---

## Objetivo

Este módulo marca un antes y un después en el curso y es que a partir de aquí, empezaremos a detallar los apartados más importantes y esenciales de un servidor de Discord, además de que aprenderemos a configurarlo a fondo.

En este apartado en concreto, tocaremos los canales y por tanto también:

---

## Tipos de canales

* Texto
* Voz
* Escenario
* Foro
* Anuncios
* Hilos

---

### Esquema visual

```text
Servidor
│
├── 📁 Información
│   ├── # reglas
│   ├── # anuncios
│   └── # bienvenida
│
├── 📁 Comunidad
│   ├── # general
│   ├── # memes
│   ├── # multimedia
│   └── # sugerencias
│
├── 📁 Voz
│   ├── 🔊 General
│   ├── 🔊 Gaming
│   └── 🎙️ Escenario
│
└── 📁 Foro
    └── 💬 Preguntas y respuestas
```



# MÓDULO 7 · ROLES

---

## Objetivo

Este es el que yo considero el capítulo más importante de todo el curso, pues en este entenderemos como personalizar cada Rol, hacerlo estético, funcional, diferenciarlo, etc…

Lo separaremos de manera básica en:

---

## Apartados

* Qué son.
* Para qué sirven.
* Jerarquía.
* Colores.
* Menciones.

---

### Ejemplo de jerarquía

```text
👑 Propietario
│
├── 🛠️ Administrador
│
├── 🛡️ Moderador
│
├── ⭐ VIP
│
└── 👤 Miembro
```



# MÓDULO 8 · PERMISOS

---

## Objetivo

Este es otro de los módulos más importantes, pues es este el que genera más duda y errores en principiantes:

---

## Apartados

* Permisos globales.
* Permisos por canal.
* Herencia.
* Sobrescrituras.

---

### Esquema visual

```text
Servidor
│
├── Rol: Moderador
│      │
│      ├── Leer mensajes ✅
│      ├── Gestionar mensajes ✅
│      ├── Banear miembros ✅
│      └── Administrador ❌
│
└── Canal #staff
       │
       └── Sobrescribe permisos
```

# MÓDULO 9 · MENSAJERÍA

---

## Objetivo

En este módulo el usuario aprenderá cómo hacer sus mensajes más dinámicos y estáticos.

Tocando puntos como:

---

## Apartados

* Formato
* Negrita.
* Cursiva.
* Subrayado.
* Tachado.
* Spoilers
* Citas
* Emojis
* Stickers
* GIFs
* Reacciones
* Encuestas
* Archivos

---

### Ejemplo de formato Markdown

````md
**Negrita**

*Cursiva*

__Subrayado__

~~Tachado~~

> Cita

||Spoiler||

`Código`

```js
console.log("Discord");
```
````

# MÓDULO 10 · COMUNICACIÓN

---

## Objetivo

En este módulo aprenderemos a usar canales de voz, audio, video en su máximo esplendor, tocaremos los siguientes puntos:

---

## Apartados

* Llamadas
* Canales de voz
* Videollamadas
* Compartir pantalla
* Streaming
* Actividades

---

### Esquema visual

```text
Canal de Voz
│
├── 🎤 Micrófono
├── 🔊 Altavoz
├── 📷 Cámara
├── 🖥️ Compartir pantalla
├── 🎮 Actividades
└── 👥 Participantes
```

# MÓDULO 11 · CONFIGURACIÓN

---

## Objetivo

Si al inicio el usuario aprendio a personalizar su perfil de manera básica, ahora aprenderá a personalizar su perfil y cuenta en general para sacarle el mayor provecho posible a Discord.

---

## Apartados

* Cuenta
* Seguridad
* Privacidad
* Voz
* Vídeo
* Notificaciones
* Accesibilidad
* Apariencia
* Idioma
* Keybinds

---

### Organización de los ajustes

```text
⚙️ Ajustes de Usuario
│
├── Mi Cuenta
├── Perfiles
├── Privacidad y Seguridad
├── Dispositivos
├── Conexiones
├── Voz y Vídeo
├── Notificaciones
├── Apariencia
├── Accesibilidad
├── Idioma
└── Keybinds
```

# MÓDULO 12 · HERRAMIENTAS PARA COMUNIDADES

---

## Objetivo

En este módulo finalmente mostraremos todo lo que son capaces de hacer las herramientas de comunidad como INTEGRACIONES COMO DISCOHOOK:

---

## Apartados

* Eventos
* Calendario
* AutoMod
* Verificación
* Comunidad
* Reglas
* Bienvenida
* Screening
* Onboarding



Muchas de estas posibilidades se verán más a fondo el curso de **BOTS PARA PRINCIPIANTES (SIN PROGRAMACIÓN).**

---

### Esquema de una comunidad

```text
Comunidad
│
├── Reglas
├── Bienvenida
├── Screening
├── AutoMod
├── Eventos
├── Onboarding
└── Integraciones
```

# MÓDULO 13 · NITRO

---

## Objetivo

Una vez el curso en sí está acabado, pasamos al Nitro, la herramienta sobre la que se “sostiene” Discord y permite que siga en mantenimiento y constante actualización.

---

## Apartados

* Qué es.
* Qué ventajas tiene.
* Qué ventajas NO tiene.
* Qué merece la pena.

---

### Resumen visual

```text
Discord
│
├── Gratuito
│   ├── Mensajería
│   ├── Voz
│   ├── Vídeo
│   ├── Servidores
│   └── Comunidades
│
└── Nitro
    ├── Personalización
    ├── Mejor calidad
    ├── Más límites
    ├── Insignia
    └── Otras ventajas
```

# MÓDULO 14 · CASOS DE USO

---

## Objetivo

Y por último cerramos con unas demostraciones para que el usuario tenga una idea visual total de todo lo que puede lograrse con lo aprendido en diferentes comunidades de Discord.

---

## Casos de uso

* Discord para gamers
* Discord para programadores
* Discord para estudios
* Discord para creadores
* Discord para empresas

---

### Comparativa

```text
Discord
│
├── 🎮 Gaming
│
├── 💻 Programación
│
├── 📚 Estudios
│
├── 🎥 Creadores de contenido
│
└── 🏢 Empresas
```

# MÓDULO 15 · ERRORES COMUNES

---

## Objetivo

Hay múltiples errores que se cometen comúnmente en principiantes y que se recomienda tener en cuenta a la hora de hacer tu propio servidor:

---

## Errores frecuentes

* Dar Administrador a todo el mundo.
* No entender la jerarquía.
* Crear demasiados canales.
* Poner demasiados roles.
* No usar categorías.
* Silenciar @everyone.
* Configurar mal los permisos.

---

### Ejemplo de una mala organización

```text
Servidor
│
├── #general
├── #general-2
├── #general-3
├── #chat
├── #chat-2
├── #chat-3
├── #nuevo-chat
├── #nuevo-chat-2
└── (Demasiados canales)
```

---

### Ejemplo de una buena organización

```text
Servidor
│
├── 📁 Información
│   ├── #reglas
│   ├── #anuncios
│   └── #bienvenida
│
├── 📁 Comunidad
│   ├── #general
│   ├── #multimedia
│   └── #memes
│
└── 📁 Voz
    ├── 🔊 General
    └── 🔊 Gaming
```

# MÓDULO 16 · RETO FINAL

---

## Objetivo

Para cerrar el curso por todo lo alto y demostrar que lo aprendido a servido para algo, se reta al usuario a crear su propio servidor de Discord desde cero (En caso de no haberlo hecho ya).

---

## Requisitos del reto

Crear un servidor completamente funcional incluyendo, como mínimo:

* Un nombre e imagen para el servidor.
* Varias categorías bien organizadas.
* Diferentes tipos de canales.
* Una jerarquía de roles.
* Permisos correctamente configurados.
* Canales de voz.
* Un sistema de bienvenida.
* Una estructura preparada para una comunidad real.

---

## Resultado esperado

Al finalizar este reto, el usuario habrá puesto en práctica prácticamente todos los conocimientos adquiridos durante el curso y dispondrá de un servidor listo para evolucionar junto a los siguientes cursos del canal.



# FIN DEL CURSO

---

## Próximos cursos recomendados

```text
Curso Completo de Discord
            │
            ▼
Bots para Principiantes (Sin Programación)
            │
            ▼
Discord Developer Portal
            │
            ▼
Curso de Discord.js
            │
            ├── Bot de Moderación
            ├── Bot de Tickets
            ├── Bot Musical
            ├── Base de Datos
            └── Despliegue 24/7

                    o

Curso de Discord.py
            │
            ├── Bot de Moderación
            ├── Bot de Tickets
            ├── Bot Musical
            ├── Base de Datos
            └── Despliegue 24/7
```


