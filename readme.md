# Flujos de Trabajo de Automatización con n8n

Este repositorio contiene flujos de trabajo de n8n para automatizar diversas tareas, incluyendo el procesamiento de formularios web, notificaciones por correo electrónico e integración con bots de Telegram.

## 📋 Estructura del Proyecto

- `Procesar formulario web con notificación por correo y registro en hoja de cálculo (1).json` - Flujo para procesar formularios web con notificaciones por correo y registro en hojas de cálculo
- `automatization-telegram.json` - Flujo de automatización para Telegram
- `index.html` - Interfaz web del proyecto

## 🚀 Características

- **Procesamiento de Formularios Web**: Procesa automáticamente los envíos de formularios
- **Notificaciones por Correo**: Envía alertas por correo electrónico cuando se reciben formularios
- **Integración con Hojas de Cálculo**: Almacena los datos de los formularios en una hoja de cálculo
- **Bot de Telegram**: Automatiza interacciones a través de Telegram

## 🛠️ Requisitos Previos

- [n8n](https://n8n.io/) instalado y en ejecución
- Node.js (si ejecutas n8n localmente)
- Credenciales de la API de Hojas de Cálculo de Google (para la integración con hojas de cálculo)
- Detalles del servidor SMTP (para las notificaciones por correo)
- Token de Bot de Telegram (para la automatización con Telegram)

## 📥 Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/cristobalmaier/n8n-codes.git
   cd n8n-codes
   ```

2. Importa los archivos de flujo de trabajo en tu instancia de n8n:
   - Abre n8n
   - Ve a "Workflows"
   - Haz clic en "Import from File"
   - Selecciona el archivo `.json` de flujo de trabajo deseado

## 🔧 Configuración

### Procesamiento de Formularios Web
1. Actualiza la URL del webhook en tu formulario para que apunte a tu instancia de n8n
2. Configura el nodo de correo con los detalles de tu servidor SMTP
3. Configura el nodo de Google Sheets con tus credenciales de API

### Automatización con Telegram
1. Crea un bot de Telegram usando [@BotFather](https://t.me/botfather)
2. Reemplaza el token del bot en el flujo de trabajo
3. Configura el ID del chat para los destinatarios de los mensajes

## 🤖 Uso

1. Inicia tu instancia de n8n
2. Activa los flujos de trabajo que desees utilizar
3. Prueba el envío de formularios o los comandos de Telegram

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).