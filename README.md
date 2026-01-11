# **Flujo de automatización con Make, Google Forms, Trello**
Flujo de automatización desarrollado con Make, enfocado en optimizar la gestión de solicitudes. Cada vez que alguien completa un 𝗚𝗼𝗼𝗴𝗹𝗲 𝗙𝗼𝗿𝗺, el proceso se ejecuta automáticamente.

<img width="1365" height="634" alt="Flujo Make" src="https://github.com/user-attachments/assets/f5dc47f5-e6c0-4d5d-adf1-4d2a67295ed1" />

## **Configuración**:
1. Para la creación del flujo se debe crear una cuenta en Make: `https://www.make.com/en`
2. Una vez creada la cuenta se deberá crear un escenario e importar el JSON del flujo, donde se deberán configurar las distintas conexiones a las herramientas integradas

## **Flujo**:

- Se detecta una nueva respuesta
- Se evalúa el contenido del mensaje
- Si el mensaje es 𝘂𝗿𝗴𝗲𝗻𝘁𝗲:
<img width="1365" height="632" alt="Google Forms 1" src="https://github.com/user-attachments/assets/59634a88-732a-4bfd-9bab-e86c8cdfce68" />
<img width="1365" height="633" alt="Google Forms 2" src="https://github.com/user-attachments/assets/07493cee-d5fd-4451-8686-f25a3e945c2d" />

  - Se envía un correo automático vía Gmail
  <img width="1365" height="632" alt="Correo Alerta" src="https://github.com/user-attachments/assets/72db5737-fa82-4dba-be62-db2736d8f5e0" />

  - Se crea una tarjeta en Trello para atención inmediata
  <img width="1365" height="631" alt="Tarea Trello 1" src="https://github.com/user-attachments/assets/24e1d146-0c13-4302-a983-7c1150609dd6" />
    
- Si el mensaje es 𝗻𝗼𝗿𝗺𝗮𝗹:
<img width="1365" height="632" alt="Google Forms 3" src="https://github.com/user-attachments/assets/bbb7893d-9912-4b77-a142-d2a96e793323" />
<img width="1365" height="631" alt="Google Forms 4" src="https://github.com/user-attachments/assets/1c1b3421-d5d4-4675-8615-00c47c71135d" />

  - La información se guarda en Google Sheets
  <img width="1365" height="633" alt="image" src="https://github.com/user-attachments/assets/ddf1f7cd-218a-4dbe-ad94-77b58525df8c" />
    
  - Se crea una tarjeta en Trello para seguimiento
  <img width="1365" height="633" alt="Tarea Trello 2" src="https://github.com/user-attachments/assets/dee5ddbe-5a43-425f-a781-898f8b685b0e" />
  <img width="1365" height="633" alt="Tarea Trello 3" src="https://github.com/user-attachments/assets/9d224fc0-a04a-4b24-953c-78a18660e588" />

