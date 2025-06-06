💱 PSP-SS-CLIENT_SERVER-DIVISAS
Aplicación de consola desarrollada en Java que implementa una arquitectura cliente-servidor basada en sockets para la conversión de divisas. El cliente envía peticiones al servidor, que responde con el resultado de la conversión solicitada.

Este proyecto fue realizado como parte de la UF2 del módulo de Programación de Servicios y Procesos (PSP) del ciclo DAM.

🧠 Funcionalidad
Comunicación cliente-servidor mediante sockets TCP.

Conversión de divisas entre diferentes monedas.

Respuestas personalizadas según la petición del cliente.

Código modular y orientado a objetos.

📁 Estructura del repositorio
text
Copiar
Editar
PSP-SS-CLIENT_SERVER-DIVISAS/
│
├── T3-CLIENTEDIVISAS/      → Código fuente del cliente
│   └── ClienteDivisas.java
│
├── T3-SERVERDIVISAS/       → Código fuente del servidor
│   └── ServidorDivisas.java
│
├── Actividad UF2-2. Servidor socket para conversión de divisas.docx
└── Actividad UF2-2. Servidor socket para conversión de divisas.pdf
🖥️ Ejecución del proyecto
1. Clona el repositorio
bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PSP-SS-CLIENT_SERVER-DIVISAS.git
2. Compila y ejecuta el servidor
bash
Copiar
Editar
cd PSP-SS-CLIENT_SERVER-DIVISAS/T3-SERVERDIVISAS
javac ServidorDivisas.java
java ServidorDivisas
3. Compila y ejecuta el cliente
Abre otra terminal:

bash
Copiar
Editar
cd PSP-SS-CLIENT_SERVER-DIVISAS/T3-CLIENTEDIVISAS
javac ClienteDivisas.java
java ClienteDivisas
📌 Requisitos
Java JDK 8 o superior

Entorno de desarrollo como IntelliJ, Eclipse o simplemente consola

📚 Documentación
El repositorio incluye documentación detallada sobre la práctica:

📄 Actividad UF2-2. Servidor socket para conversión de divisas.docx

📄 Actividad UF2-2. Servidor socket para conversión de divisas.pdf

Contienen la descripción de los objetivos, estructura y funcionalidades implementadas.

👨‍💻 Autor
Iván Núñez Rodríguez
📧 ivannr20@gmail.com
🎓 Desarrollador de Aplicaciones Multiplataforma (DAM)
