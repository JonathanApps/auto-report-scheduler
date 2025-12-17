# 🤖 Auto-Report Scheduler

**Script en Python para automatizar la generación y envío de reportes.** Este proyecto demuestra cómo se pueden ahorrar horas de trabajo manual mediante la automatización de tareas repetitivas con Python.

**Estado del proyecto:** 🟢 En desarrollo
**Tecnologías:** Python, Pandas, Schedule, smtplib

---

## ✨ ¿Qué hace este script?

Este script automatiza el proceso de generar un reporte a partir de datos de ventas y guardarlo automáticamente. Es ideal para:
- 📊 **Dueños de pequeños negocios** que necesitan reportes diarios/semanales.
- 📈 **Equipos comerciales** que requieren consolidar datos.
- ⏱️ **Cualquier persona** que pierde tiempo haciendo reportes manuales.

**Características principales:**
1.  **Lee datos** desde un archivo CSV (`data/sales_data.csv`).
2.  **Procesa y calcula** métricas clave (ventas totales, promedio, producto más vendido).
3.  **Genera un reporte** en formato de texto (.txt) con la fecha en el nombre.
4.  **Guarda automáticamente** el reporte en la carpeta `reports/`.
5.  *(Próxima función)*: **Envía el reporte por correo electrónico** de forma programada.

---

## 🚀 Cómo empezar (Instalación y uso)

Sigue estos pasos para ejecutar el script en tu máquina:

### **Prerrequisitos**
Asegúrate de tener instalado **Python 3.8 o superior**. Si no lo tienes, descárgalo desde [python.org](https://www.python.org/).

### **1. Clona este repositorio**
Abre tu terminal (o Git Bash si usas Windows) y escribe:
```bash
git clone https://github.com/JonathanApps/auto-report-scheduler.git
cd auto-report-scheduler
