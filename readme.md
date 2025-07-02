# 🏦 Proyecto ETL End-to-End: Modelo Medallón aplicado a Préstamos Bancarios

## Este proyecto implementa un pipeline **ETL de punta a punta** utilizando el enfoque del **Modelo Medallón (Bronze, Silver, Gold)**, aplicado a un **caso de negocio real del sector bancario**, específicamente sobre datos de **préstamos**. 

## 📌 Objetivos del pipeline
  -Implementar un flujo modular y escalable de procesamiento de datos.

  -Mantener trazabilidad y versionado en cada capa.

  -Preparar datos confiables para toma de decisiones bancarias.

  -Automatizar procesos con ADF y ejecutar lógica con PySpark.


## 🚀 Tecnologías utilizadas

- **🔗 Azure Data Factory (ADF):** Orquestación de pipelines y flujos de trabajo.
- **⚙️ Azure Databricks:** Transformaciones y procesamiento con PySpark (Apache Spark).
- **📦 Delta Lake:** Almacenamiento transaccional y versionado de datos.
- **☁️ Azure Data Lake Storage:** Repositorio principal de archivos y tablas.

---

## 🧱 Arquitectura Medallón

El método **Medallón** se basa en un enfoque estructurado por capas:

### 🥉 Capa Bronze – Ingesta de datos crudos
- Almacenamiento del dataset original sin modificaciones.
- Formato de archivo conservado (CSV, JSON, etc.).
- Control de versiones y trazabilidad de datos fuente.

### 🥈 Capa Silver – Limpieza y enriquecimiento
- Eliminación de valores nulos o inconsistentes.
- Conversión de tipos de datos.
- Enriquecimiento con columnas calculadas o datos externos.
- Estandarización y consistencia del dataset.

### 🥇 Capa Gold – Métricas y modelos de negocio
- Cálculo de KPIs y métricas financieras relevantes.
- Agrupaciones por cliente, cuenta, ciudad, etc.
- Datos listos para ser consumidos por herramientas de BI o sistemas analíticos.


---

## 📄 Documentación adicional (Importante)

Para más información detallada sobre la arquitectura, transformaciones y decisiones técnicas, podés consultar el siguiente documento:

👉 **[Proyecto Final Data Engineer.pdf](https://github.com/user-attachments/files/21026490/Proyecto.Final.Data.Engineer.pdf)**


> Incluye esquemas, ejemplos, descripciones técnicas, y justificación de decisiones a lo largo del pipeline.
