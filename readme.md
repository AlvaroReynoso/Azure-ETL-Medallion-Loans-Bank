# 🏦 Proyecto ETL End-to-End: Modelo Medallón aplicado a Préstamos Bancarios (Español)

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

👉 [Proyecto Final Data Engineer.pdf](https://github.com/user-attachments/files/21026502/Proyecto.Final.Data.Engineer.pdf)



> Incluye esquemas, ejemplos, descripciones técnicas, y justificación de decisiones a lo largo del pipeline.

---


# 🏦 End-to-End ETL Project: Medallion Architecture Applied to Banking Loans (English)

## This project implements a **full end-to-end ETL pipeline** using the **Medallion Architecture (Bronze, Silver, Gold)** approach, applied to a **real-world business case in the banking sector**, specifically focused on **loan data**.

## 📌 Pipeline Objectives
- Implement a **modular and scalable** data processing flow.
- Maintain **traceability and version control** at each stage.
- Prepare **reliable data** for banking decision-making.
- Automate processes with **ADF** and execute logic using **PySpark**.

## 🚀 Technologies Used

- **🔗 Azure Data Factory (ADF):** Pipeline orchestration and workflow management.
- **⚙️ Azure Databricks:** Data transformation and processing with PySpark (Apache Spark).
- **📦 Delta Lake:** Transactional storage with data versioning.
- **☁️ Azure Data Lake Storage:** Main repository for raw and processed data files.

---

## 🧱 Medallion Architecture

The **Medallion Architecture** is a multi-layered approach to data processing:

### 🥉 Bronze Layer – Raw Data Ingestion
- Stores the original dataset without modifications.
- Preserves file format (CSV, JSON, etc.).
- Enables versioning and traceability of the source data.

### 🥈 Silver Layer – Data Cleaning & Enrichment
- Handles null or inconsistent values.
- Converts and standardizes data types.
- Enriches data with calculated columns or external sources.
- Ensures dataset consistency and quality.

### 🥇 Gold Layer – Metrics & Business Models
- Computes relevant KPIs and financial metrics.
- Aggregates data by customer, account, city, etc.
- Final output ready for BI tools or analytical systems.

---

## 📄 Additional Documentation (Important)

For detailed information about the architecture, transformations, and technical decisions, please refer to the following document:

👉 [Final Project Data Engineer.pdf](https://github.com/user-attachments/files/21026502/Proyecto.Final.Data.Engineer.pdf)

> The document includes diagrams, examples, technical descriptions, and a rationale for the pipeline design choices.



## Algunas Capturas / Few Screenshots:

![1](https://github.com/user-attachments/assets/6e701d75-b4cc-4ac5-8cea-63aa50c6f894)
![2](https://github.com/user-attachments/assets/19c5ad6b-7427-4d33-9b99-bbf651f4a49d)
![3](https://github.com/user-attachments/assets/c4073864-037e-4332-b3d2-a47aa8ad7d36)
![4](https://github.com/user-attachments/assets/5839a02e-d884-43a0-bfe2-24d170046f10)
![5](https://github.com/user-attachments/assets/084e2945-a63a-45cf-a27b-c8f51289da42)
![6](https://github.com/user-attachments/assets/094f1a01-7599-496c-ad05-675c070b214a)
![7](https://github.com/user-attachments/assets/79f8b035-10f8-443c-9380-56c9e1db0ac0)

