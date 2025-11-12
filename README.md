# Actividad 22 - Automatización Inteligente con n8n

## Descripción
Este proyecto forma parte de la actividad de **Automatización Inteligente con n8n**, en la cual se diseñaron dos workflows:
1. **Workflow Básico:** integra un formulario web con envío automático de correos electrónicos y registro en Google Sheets.
2. **Workflow Avanzado:** utiliza condicionales para enviar notificaciones a diferentes plataformas (Telegram, Slack y WhatsApp).

---

## Tecnologías utilizadas
- [n8n](https://n8n.io)
- Google Sheets
- Gmail SMTP
- Telegram Bot API
- Slack API
- Twilio WhatsApp API

---

## Estructura del proyecto

📂 actividad22-n8n/
├── actividad22_basico_TuApellido.json
├── actividad22_avanzado_TuApellido.json
├── capturas/
│ ├── workflow_basico.png
│ ├── workflow_avanzado.png
│ └── evidencias.png
└── Informe_APA_TuApellido.pdf


---

## Cómo reproducir los workflows
1. Crear una cuenta en [n8n.cloud](https://app.n8n.cloud) o instalar n8n localmente.
2. Importar los archivos `.json` desde **Import Workflow → Upload file**.
3. Configurar las credenciales:
   - **Gmail:** conexión por OAuth2.
   - **Google Sheets:** seleccionar la hoja de destino.
   - **Telegram / Slack / WhatsApp:** ingresar los tokens o API keys correspondientes.
4. Activar los workflows y realizar una prueba con el botón **Execute Workflow** o mediante un `POST` al Webhook.

---

## Flujo básico
`Formulario Web` → `Configuración del Workflow` → `Enviar Correo` + `Registrar en Hoja de Cálculo`

## Flujo avanzado
`Webhook` → `Configuración` → `Check Action Type` → Notificación (Telegram / Slack / WhatsApp)

---

## Créditos
**Autor:** Franco Fernandez Devicenzi
**Curso:** 7° 2° A – PWD  
**Año:** 2025  
**Institución:** Escuela de Educación Secundaria Técnica Nro 1 "Eduardo Ader"

---

## Licencia
Proyecto educativo de uso libre con fines académicos.
