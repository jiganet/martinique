# 🤖 Contexto para Agentes (Agent-First approach)

Este archivo proporciona el contexto necesario para que cualquier IA (como Antigravity) pueda mantener y actualizar este repositorio adecuadamente.

## 📋 Reglas de Edición
1. **Rutas de Recursos:** Todos los archivos multimedia (fotos, modelos 3D, PDFs) deben vivir en la carpeta `resources/`.
2. **Nombres de Archivos:** Evitar espacios en los nombres de archivos dentro de `resources/` para evitar problemas de carga en el navegador (ejemplos: `apartment.glb`, `plano.pdf`).
3. **Optimización 3D:** El modelo principal es `apartment.glb`. Se usa `model-viewer` de Google para su renderización.
4. **Actualización de WhatsApp:** El número de contacto actual es `+57 3116344184`. Cualquier cambio debe actualizar tanto el enlace `wa.me` como el código QR generado por la API.

## 🛠 Tareas Comunes
- **Agregar fotos:** Mover a `resources/`, renombrar de forma descriptiva (ej. `cuarto_nuevo.jpeg`) y actualizar el `grid` correspondiente en `index.html`.
- **Cambiar Precio:** Localizar la clase `.price-tag` en el HTML.
- **Mantenimiento del Modelo 3D:** Si se actualiza el modelo `.glb`, asegurarse de que la barra de progreso en el `index.html` siga funcionando correctamente.

## 🏗 Arquitectura del Sitio
- **Frontend:** Vanilla HTML5/CSS3.
- **JS Externo:** `model-viewer` (de Google) para el 3D.
- **Diseño:** Responsive (Mobile-First) con soporte para impresión profesional.
