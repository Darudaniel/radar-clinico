🧭 Radar Clínico Quirúrgico

Un dashboard minimalista y altamente funcional para cirujanos que desean mantenerse actualizados en tiempo real con la literatura científica de PubMed.

Este proyecto convierte un archivo HTML estático en una revista personalizada, capaz de leer un RSS dinámico generado desde PubMed y mostrar automáticamente los artículos más recientes sobre las áreas quirúrgicas de interés del usuario.

Diseñado para uso personal, académico y clínico, especialmente para residentes de cirugía general que deben navegar un volumen masivo de información sin perder tiempo.

🚀 Características principales
✔️ Feed único y personalizado

El usuario genera un solo RSS desde PubMed a partir de una búsqueda personalizada (ej. cirugía general, trauma, HPB, pared abdominal, ERAS, sepsis, laparoscopia, etc.), lo pega en el panel derecho…
y el dashboard lo convierte inmediatamente en un feed legible.

✔️ Actualización en tiempo casi real

Un clic sobre Actualizar trae los artículos más recientes sin recargar la página.

✔️ Interfaz moderna, limpia y centrada en contenido

Construida en HTML, CSS y JavaScript puro:

diseño oscuro profesional

tarjetas legibles

scroll suave

animación mínima

lectura rápida de títulos

clic directo al artículo original en PubMed

✔️ Sin backend, sin dependencias, sin instalación

Solo necesitas abrir el archivo HTML en tu navegador.

✔️ Almacenamiento local opcional

El dashboard puede recordar automáticamente el RSS que pegaste, guardándolo en localStorage, para que no tengas que introducirlo cada vez.

✔️ Protección contra CORS

Implementa un proxy público (allorigins) para permitir la lectura de RSS externos desde el navegador de forma segura.

🩺 ¿Para quién está pensado?

Especialmente útil para:

Residentes de cirugía general (R1–R5)

Cirujanos generales

Cirujanos de trauma / acute care

Coloproctólogos

Cirujanos HPB

Investigadores quirúrgicos

Profesores que desean un flujo constante de literatura

Este dashboard permite mantenerse actualizado sin necesidad de suscripciones costosas ni plataformas externas.

🔧 ¿Cómo funciona?

El usuario va a PubMed y construye su búsqueda personalizada (ej. vólvulo, trauma abdominal, pancreatitis, ERAS, etc.).

En PubMed hace clic en:
Create RSS → Create RSS → RSS

Copia la URL generada y la pega en el campo de configuración del dashboard.

El dashboard muestra inmediatamente los artículos más recientes, ordenados del más nuevo al más antiguo.

📡 Tecnologías usadas

HTML5

CSS3 (UI minimalista + modo oscuro)

JavaScript vanilla

DOMParser para parseo XML

allorigins API para evitar CORS

LocalStorage para recordar el RSS del usuario

No usa frameworks, no necesita servidor, no requiere instalación.

🔮 Próximas mejoras (ideas)

Filtros por palabras clave dentro del dashboard

Agrupación por temas (trauma, HPB, hernias, colorectal…)

Exportación directa a Zotero

Marcar artículos como “leído” o “favorito”

Integración con medRxiv para preprints

Modo “guías” (solo SAGES, WSES, AAST, ESPEN, ERAS Society)

Versión móvil optimizada

📄 Licencia

MIT — completamente libre para usar, modificar y distribuir.

✨ Autor

Daniel Ruiz Zambrano
Residente de Cirugía General
Universidad del Cauca – Popayán, Colombia