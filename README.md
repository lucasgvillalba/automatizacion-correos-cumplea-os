# 🎉 Automatización de Correos de Cumpleaños con Google Apps Script

Este proyecto utiliza Google Apps Script para automatizar el envío de correos electrónicos de cumpleaños directamente desde una hoja de cálculo de Google Sheets.

## 🎯 Objetivo

Automatizar el saludo de cumpleaños a empleados de forma personalizada y programada, mejorando la experiencia interna sin intervención manual.

## 📋 Requisitos

- Tener una cuenta de Google
- Una hoja de cálculo con las siguientes columnas:
  - Nombre
  - Apellido
  - Email
  - Fecha de nacimiento (formato: `dd/mm/yyyy`)
  - Enviado (marcado automáticamente)

## 📦 ¿Qué incluye este proyecto?

- `enviarFelicitaciones.gs`: script que envía los correos.
- `reiniciarEnvios.gs`: resetea el estado de los envíos al iniciar un nuevo año.
- `ejemplo_empleados.csv`: plantilla de ejemplo de la hoja.

## 🛠 Cómo usarlo

1. Crear una hoja de cálculo con los campos mencionados.
2. Ir a **Extensiones > Apps Script**.
3. Copiar el contenido del archivo `.gs` (ver `/src/enviarFelicitaciones.gs`).
4. Guardar.
5. Ir a **Desplegar > Triggers** y agregar uno para que se ejecute todos los días a las 9 AM.
6. ¡Listo! Se enviarán correos automáticamente a quienes cumplan años ese día.

## 📨 Formato del correo

- Asunto: `¡Feliz cumpleaños! 🎂🎉`
- Cuerpo: HTML con mensaje personalizado e imagen incluida.

## 👨‍💻 Autor

Lucas – Automatización aplicada a RRHH · Ciencia de Datos


