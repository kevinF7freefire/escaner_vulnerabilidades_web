#🛡️ Ultrascan: Escáner de Vulnerabilidades Web
Psychic Engine es una herramienta automatizada diseñada para identificar fallos de seguridad comunes en aplicaciones web. Ideal para estudiantes de informática y entusiastas del pentesting que buscan agilizar la fase de reconocimiento.

🚀 Características principales
Escaneo de puertos: Identificación de servicios abiertos.

Detección de vulnerabilidades: (Ej: XSS, SQLi, Directorios expuestos).

Ligero y rápido: Optimizado para sistemas basados en Debian/Kali Linux.

Formato .deb: Instalación sencilla y limpia.

🛠️ Instalación
Para instalar el escáner en tu sistema, descarga el archivo .deb de este repositorio y ejecuta:

Bash
sudo dpkg -i ultrascan-v3.deb
sudo apt-get install -f  # Para resolver posibles dependencias
📖 Uso básico
Una vez instalado, puedes iniciar el escaneo con el siguiente comando:

Bash
psychic-engine --target https://ejemplo.com
(O cambia por el comando real que use tu herramienta).

📋 Requisitos
Kali Linux o cualquier distribución basada en Debian.

Python 3.x (si el binario lo requiere).

Privilegios de superusuario (root).

⚖️ Aviso Legal (Disclaimer)
Este proyecto fue creado exclusivamente con fines educativos y de auditoría ética. El uso de esta herramienta contra objetivos sin autorización previa es ilegal. El desarrollador no se hace responsable del mal uso de este software.
