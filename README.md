🎧 BrunoSound
Plataforma de playlists sin anuncios ni suscripciones
🧠 Contexto del proyecto

La mayoría de plataformas de música actuales están saturadas de anuncios, restricciones o pagos mensuales.
BrunoSound nace como una alternativa simple: control total del usuario sobre su música, sin interrupciones ni costos.

Este proyecto fue desarrollado como una solución práctica enfocada en experiencia de usuario, rendimiento y simplicidad.

🚀 ¿Qué es BrunoSound?

BrunoSound es una aplicación web que permite:

Crear playlists personalizadas
Agregar canciones desde YouTube
Reproducir contenido sin salir de la app
Gestionar música de forma rápida y fluida

Todo esto en una interfaz moderna, responsive y sin distracciones.

🎯 Propuesta de valor

✔️ Cero anuncios
✔️ Cero pagos mensuales
✔️ Sin dependencias de plataformas premium
✔️ Experiencia limpia y enfocada en el usuario

A diferencia de otras apps, aquí el usuario tiene el control total.

⚙️ Funcionalidades clave
👤 Sistema multiusuario
Acceso por perfil con PIN
Separación de datos por usuario
Persistencia de sesión
📂 Gestión de playlists
Crear y eliminar playlists
Organización por usuario
Actualización en tiempo real
➕ Integración con YouTube
Agregar canciones mediante URL
Extracción automática de metadatos
Reproductor embebido
▶️ Reproductor avanzado
Control de reproducción (next / prev)
Autoplay inteligente
Modo aleatorio (shuffle)
Sin cortes ni redirecciones externas
🔍 Búsqueda dinámica
Filtrado en tiempo real
Resaltado de coincidencias
☁️ Persistencia de datos
Firebase Firestore (tiempo real)
Fallback a localStorage (modo offline)
🧱 Arquitectura y tecnologías

Frontend:

HTML5
CSS3 (Diseño responsive + UI personalizada)
JavaScript Vanilla (sin frameworks)

Backend / Servicios:

Firebase Firestore (NoSQL en tiempo real)

Integraciones:

YouTube Iframe API
📱 Experiencia de usuario (UX)
Diseño tipo aplicación nativa
Layout adaptativo:
💻 Desktop: 3 columnas (playlists / player / tracks)
📱 Mobile: navegación por tabs
Interacciones rápidas y fluidas
Feedback visual (toasts, animaciones, estados)
🔄 Lógica destacada
Sincronización en tiempo real con Firestore
Manejo de estado del reproductor
Validación de URLs de YouTube
Control de reproducción automatizado
Gestión de estado offline vs online
💡 Retos técnicos resueltos
Integración fluida con YouTube sin salir de la app
Sincronización en tiempo real sin recargar la página
Manejo de múltiples usuarios sin autenticación compleja
Diseño responsive con múltiples layouts dinámicos
Fallback automático cuando Firebase no está disponible
📈 Impacto del proyecto

Este proyecto demuestra:

Capacidad para construir aplicaciones completas sin frameworks
Dominio de lógica de frontend y manejo de estado
Integración con servicios externos (Firebase + YouTube)
Enfoque en experiencia de usuario real
Pensamiento orientado a producto
🚧 Posibles mejoras
Autenticación real (Firebase Auth)
Compartir playlists entre usuarios
Drag & drop para ordenar canciones
Sistema de recomendaciones
Migración a React (escalabilidad)
👨‍💻 Autor

Julián David Ortiz Gaviria
Ingeniero en Desarrollo de Software (en formación)

🧩 Nota final

BrunoSound no busca competir con grandes plataformas, sino demostrar que se pueden construir soluciones funcionales, bien diseñadas y centradas en el usuario sin necesidad de modelos de pago o experiencias saturadas.
