#  Mini-Lab educativo: phishing con Zphisher

🔒 Mini-Lab educativo: phishing con Zphisher

He realizado este laboratorio usando Zphisher, una herramienta ligera en Bash, para mostrar cómo se capturan credenciales en un entorno controlado.

Resumen del laboratorio:

🔹 Utilicé la plantilla GitHub (n:33) y levanté un servidor localhost, mostrando cómo un atacante ficticio podría recibir credenciales de prueba.

🔹Importancia del segundo factor de autenticación (2FA): aunque el atacante reciba la contraseña, no lo tiene todo. En este laboratorio se vio cómo Zphisher genera un formulario de reseteo, buscando romper ese segundo factor y forzar el acceso.

Laboratorio seguro vs clonación real:

🔹En el laboratorio usamos localhost y plantillas de prueba, todo seguro.

🔹En un ataque real, un atacante podría clonar páginas auténticas y exponerlas vía Cloudflare, Ngrok o VPS, generando enlaces peligrosos que engañarían a víctimas reales.

<img src="1-Zphish">

<img src="2-Zphish">

<img src="3-Zphish">

<img src="4-Zphish">

