# Proyecto-Final
# 🌱 EcoBuddy — Tu compañero virtual por un planeta más limpio

## 💡 Descripción del proyecto

EcoBuddy es un bot de Discord diseñado para motivar a las personas a recoger basura y desarrollar hábitos más sostenibles. Funciona como un compañero virtual inteligente que adapta sus mensajes al estilo de comunicación de cada usuario, registra sus avances y celebra sus logros.

El objetivo es convertir pequeñas acciones ecológicas en un hábito constante, haciendo que cuidar el planeta sea una experiencia motivadora y divertida.

## 🌍 Problema que busca resolver

La contaminación por residuos es un problema ambiental importante. Aunque muchas personas quieren ayudar al planeta, a veces les falta motivación para convertir sus buenas intenciones en acciones constantes.

EcoBuddy busca ayudar mediante metas personales, seguimiento de avances y mensajes de motivación personalizados.

## 🎯 Objetivos

- Motivar a las personas a recoger basura de manera responsable.
- Ayudar a establecer y cumplir metas semanales.
- Fomentar la constancia mediante rachas de actividad.
- Personalizar la experiencia con inteligencia artificial.
- Promover la conciencia ambiental a través de Discord.

## ⚙️ Funcionalidades principales (MVP)

1. **Compañero virtual inteligente:** genera mensajes personalizados mediante un modelo de IA ejecutado localmente con Ollama.
2. **Perfil del usuario:** realiza preguntas iniciales para adaptar el tono y el estilo de comunicación del bot.
3. **Metas semanales:** permite que cada usuario establezca una meta personal de recolección.
4. **Seguimiento de progreso:** registra los puntos acumulados y el avance hacia la meta.
5. **Rachas de actividad:** registra los días en los que el usuario participa para fomentar la constancia.

## 📸 Funcionalidad adicional

**Verificación básica mediante imágenes:** explorar un clasificador de imágenes que distinga fotografías con basura de fotografías sin basura.

Esta función será experimental: una imagen no demuestra por sí sola que una persona haya recogido los residuos. El conteo automático de objetos podría añadirse en una versión futura.

## 🛠️ Tecnologías previstas

- **Python:** lenguaje principal.
- **Discord.py:** conexión con Discord y gestión de comandos.
- **Ollama:** ejecución local de un modelo de inteligencia artificial para generar mensajes personalizados.
- **SQLite:** almacenamiento de usuarios, metas, puntos y rachas.
- **Git y GitHub:** control de versiones y documentación.
- **Teachable Machine o TensorFlow/Keras:** posible clasificación de imágenes.

Las tecnologías podrán ajustarse según las pruebas y el tiempo disponible.

## 🗓️ Plan de desarrollo de tres semanas

### Semana 1 — Fundamentos
- Preparar el entorno de desarrollo.
- Crear el bot y conectarlo a Discord.
- Diseñar los comandos iniciales.
- Probar Ollama y seleccionar un modelo adecuado.

### Semana 2 — Funcionalidades principales
- Crear el perfil y la personalización de mensajes.
- Implementar metas semanales y puntos.
- Guardar el progreso de los usuarios.
- Añadir el registro de rachas.

### Semana 3 — Pruebas y presentación
- Corregir errores y probar el bot.
- Mejorar los mensajes y la experiencia de usuario.
- Explorar la clasificación de imágenes si queda tiempo.
- Finalizar la documentación y preparar la demostración.

## ⚠️ Riesgos y alternativas

- **Ollama funciona lentamente:** probar un modelo más pequeño o reducir la complejidad de las respuestas.
- **Problemas con el almacenamiento:** comenzar con una estructura SQLite sencilla.
- **La clasificación de imágenes lleva demasiado tiempo:** priorizar el bot, la personalización y el seguimiento de metas.
- **Tiempo limitado:** completar primero las funcionalidades esenciales antes de añadir extras.

## 🌎 Impacto esperado

EcoBuddy busca fomentar hábitos ecológicos mediante tecnología accesible, motivación personalizada y seguimiento del progreso. Su propósito es demostrar cómo la inteligencia artificial puede ayudar a convertir pequeñas acciones individuales en un compromiso ambiental más constante.

## 📌 Estado del proyecto

En planificación y desarrollo inicial. Las funcionalidades descritas son objetivos previstos y se validarán durante el desarrollo del hackathon.
