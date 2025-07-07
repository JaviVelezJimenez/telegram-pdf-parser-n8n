# 🤖 Telegram PDF Parser con n8n

Este proyecto implementa un flujo automatizado usando **n8n** para recibir archivos PDF vía Telegram, convertirlos a texto, extraer su contenido estructurado y almacenarlo en una hoja de cálculo de Google Sheets.

## 📌 Características

- Recibe archivos PDF enviados por Telegram.
- Usa PDF.co para convertir el PDF a texto.
- Extrae y convierte los datos en JSON usando GPT.
- Guarda la información en Google Sheets.
- Notifica al usuario si el registro fue exitoso o si hubo un error.
- Incluye lógica para evitar duplicados y puede extenderse para guardar los PDF en Google Drive.

## 🧠 Flujo de trabajo en n8n

Puedes importar este flujo directamente en tu instancia de n8n usando el archivo [`telegram-pdf-workflow.json`](./telegram-pdf-workflow.json).

### Vista general del flujo

Capturas destacadas

Consulta la carpeta /assets para ver el proceso visual paso a paso.

## ⚙️ Requisitos

- Cuenta en **n8n** (puede ser autoalojada o en Render).
- Bot de **Telegram** creado y enlazado con el Trigger.
- API Key de **PDF.co**.
- Cuenta de **Google Sheets** y credenciales configuradas en n8n.

## 🚀 Cómo usar

1. Clona este repositorio.
2. Importa el archivo JSON en tu instancia de n8n.
3. Configura tus credenciales (Telegram, Google Sheets, PDF.co).
4. Activa el webhook.
5. Envía un PDF por Telegram al bot.

## 🛡️ Notas

- El flujo incluye manejo de errores y respuestas personalizadas.
- Próximas mejoras: detección de duplicados, almacenamiento en Google Drive y empaquetado para uso de terceros.

---

## 👨‍💼 Autor

Javier Vélez Jiménez  
Desarrollador Full Stack | Automatización | AngularJS | Spring Boot  
[LinkedIn](www.linkedin.com/in/javier-velez-jimenez)  
