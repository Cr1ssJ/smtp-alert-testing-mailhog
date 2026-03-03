# smtp-alert-testing-mailhog
Reusable Python email alerting template with MailHog-based local SMTP testing.

## 🔧 Requisitos

- Python 3
- MailHog
- Linux (probado en Ubuntu)

## 🚀 Uso rápido

1. Levantar MailHog:
   mailhog

2. Exportar variables de entorno:

   export SMTP_SERVER=localhost
   export SMTP_PORT=1025
   export ALERT_TO=test@lab.local

3. Ejecutar:

   python3 test_smtp.py

4. Ver correos en:
   http://<IP_VM>:8025

## 📌 Notas

Este script usa variables de entorno y valores por defecto
pensados únicamente para laboratorio.
