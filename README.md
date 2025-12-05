# Validador de Datos Productivos

## 📌 Descripción
Este proyecto es un **validador de datos** desarrollado en Python que permite revisar archivos CSV y detectar problemas comunes como:
- Registros duplicados
- Valores nulos por columna
- Tipos de datos inconsistentes

La aplicación incluye una interfaz interactiva construida con **Streamlit**, que facilita la carga de archivos y la visualización de resultados en tiempo real.

---

## 🛠️ Tecnologías utilizadas
- **Python 3.10+**
- **Pandas** para manipulación de datos
- **Streamlit** para la interfaz web
- **MongoDB** *(opcional)* para almacenar reglas y logs
- **Docker** *(opcional)* para despliegue

---

## 🚀 Funcionalidades
- Carga de archivos CSV desde la interfaz.
- Validación automática de duplicados y valores nulos.
- Visualización de tipos de datos por columna.
- Reporte interactivo con métricas básicas.
- Exportación de resultados *(en desarrollo)*.

---

## 📊 Ejemplo de impacto
- Detecta inconsistencias en **10.000 registros en menos de 2 segundos**.
- Genera un informe claro y reutilizable para equipos técnicos y no técnicos.

---

## ▶️ Cómo ejecutar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/validador-datos.git
   cd validador-datos

