# make-airtable-webhook-integration
Integración de Webhook HTTP a Airtable usando Make para sincronización de datos.
# ⚡ Integración de Webhook HTTP a Airtable mediante Make

Este proyecto demuestra una automatización en Make (Integromat) diseñada para recibir datos de entrada en tiempo real mediante un endpoint Webhook y procesarlos directamente en una base de datos de Airtable.

---

## 🛠️ Tech Stack & Herramientas

* **Orquestador:** Make (Integromat)
* **Entrada de Datos:** Custom Webhook (HTTP POST)
* **Base de Datos / CRM:** Airtable API

---

## ⚙️ Funcionamiento del Flujo

1. **Recepción:** El módulo Webhook escucha eventos de entrada estructurados en JSON.
2. **Transformación:** Mapeo automático de los parámetros del payload.
3. **Inserción:** Creación/actualización dinámica del registro correspondiente en Airtable.

---

## 🚀 Cómo importar este proyecto

1. Descarga el archivo `.json` (Blueprint) presente en este repositorio.
2. En tu cuenta de Make, crea un nuevo escenario.
3. En el menú inferior de tres puntos (`...`), selecciona **Import Blueprint**.
4. Sube el archivo y reconecta las credenciales de Airtable.
