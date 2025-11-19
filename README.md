# INFORME FINAL DE AUDITORÍA DE SISTEMAS

## CARÁTULA

**Entidad Auditada:** Corporate EPIS Pilot - Sistema de Help Desk con Inteligencia Artificial  

**Ubicación:** [Ciudad, distrito, provincia, país]  

**Período auditado:** [Desde dd/mm/aaaa hasta dd/mm/aaaa]  

**Equipo Auditor:** Mirian Cuadros Garcia - 2021071083  

**Fecha del informe:** [dd/mm/aaaa]  

---

## ÍNDICE

1. [Resumen Ejecutivo](#1-resumen-ejecutivo)  

2. [Antecedentes](#2-antecedentes)  

3. [Objetivos de la Auditoría](#3-objetivos-de-la-auditoría)  

4. [Alcance de la Auditoría](#4-alcance-de-la-auditoría)  

5. [Normativa y Criterios de Evaluación](#5-normativa-y-criterios-de-evaluación)  

6. [Metodología y Enfoque](#6-metodología-y-enfoque)  

7. [Hallazgos y Observaciones](#7-hallazgos-y-observaciones)  

8. [Análisis de Riesgos](#8-análisis-de-riesgos)  

9. [Recomendaciones](#9-recomendaciones)  

10. [Conclusiones](#10-conclusiones)  

11. [Plan de Acción y Seguimiento](#11-plan-de-acción-y-seguimiento)  

12. [Anexos](#12-anexos)  

---

## 1. RESUMEN EJECUTIVO

Este apartado se desarrolla al final de la auditoría realizada y es una descripción breve y concisa del propósito de la auditoría, principales hallazgos, conclusiones y recomendaciones más relevantes.

**Evidencia:** [A completar]

---

## 2. ANTECEDENTES

El sistema Corporate EPIS Pilot es una aplicación de Help Desk asistida por Inteligencia Artificial diseñada para brindar soporte técnico a usuarios de EPIS Corp. El sistema implementa una arquitectura RAG (Retrieval-Augmented Generation) utilizando el modelo de lenguaje `smollm:360m` mediante Ollama para proporcionar respuestas contextualizadas basadas en documentación interna de la empresa.

**Características principales del sistema:**
- Arquitectura basada en microservicios (Frontend React, Backend FastAPI)
- Base de datos vectorial (ChromaDB) para almacenamiento de conocimiento
- Base de datos SQLite para gestión de tickets de soporte
- Despliegue mediante Docker y Docker Compose
- Integración con modelos de IA local (Ollama)
- Sistema de embeddings multilingüe (Hugging Face multilingual-e5-large)

**Antecedentes de auditorías previas:** [Indicar si existen auditorías previas o si esta es la primera]

**Evidencia:** [A completar]

---

## 3. OBJETIVOS DE LA AUDITORÍA

### 3.1. Objetivo General

**Evaluar la seguridad, integridad, disponibilidad y cumplimiento normativo del sistema Corporate EPIS Pilot, identificando riesgos y vulnerabilidades que puedan afectar la confidencialidad de la información, la continuidad del servicio y la calidad de la atención al usuario.**

**Evidencia:** [A completar]

---

### 3.2. Objetivos Específicos

#### Objetivo Específico 1: Evaluar la Seguridad de la Información y Protección de Datos Personales
Evaluar las medidas de seguridad implementadas para proteger la información almacenada en el sistema, incluyendo datos personales de usuarios, historiales de conversación y tickets de soporte. Verificar el cumplimiento de principios de confidencialidad, integridad y disponibilidad de la información.

**Evidencia:** [A completar]

---

#### Objetivo Específico 2: Evaluar la Disponibilidad y Continuidad del Servicio
Verificar la disponibilidad del sistema y las medidas implementadas para garantizar la continuidad del servicio de Help Desk, incluyendo evaluación de la infraestructura de despliegue (Docker, Kubernetes), redundancia de componentes y procedimientos de recuperación ante desastres.

**Evidencia:** [A completar]

---

#### Objetivo Específico 3: Evaluar la Integridad y Confiabilidad de los Datos Almacenados
Examinar la integridad de los datos almacenados en las bases de datos (SQLite para tickets y ChromaDB para conocimiento vectorial), verificando mecanismos de respaldo, recuperación de datos, validación de entrada y consistencia de la información.

**Evidencia:** [A completar]

---

#### Objetivo Específico 4: Evaluar el Cumplimiento de Buenas Prácticas de Desarrollo y Despliegue
Revisar la implementación del código, configuración de servicios, gestión de dependencias y despliegue del sistema, verificando el cumplimiento de estándares de desarrollo seguro, gestión de versiones, documentación técnica y prácticas de DevOps.

**Evidencia:** [A completar]

---

## 4. ALCANCE DE LA AUDITORÍA

### 4.1. Ámbitos Evaluados
- **Tecnológico:** Arquitectura, componentes de software, bases de datos, infraestructura de despliegue
- **Organizacional:** Procedimientos, documentación, roles y responsabilidades
- **Normativo:** Cumplimiento de estándares y mejores prácticas de seguridad

### 4.2. Sistemas y Procesos Incluidos
- Sistema de Help Desk (Frontend React + Backend FastAPI)
- Base de datos de tickets (SQLite)
- Base de datos vectorial de conocimiento (ChromaDB)
- Integración con modelo de IA (Ollama - smollm:360m)
- Sistema de embeddings (Hugging Face)
- Infraestructura de despliegue (Docker, Docker Compose, Kubernetes)
- Procesos de ingesta de documentación
- Flujos de creación y gestión de tickets

### 4.3. Unidades o Áreas Auditadas
- Código fuente del frontend (React/TypeScript)
- Código fuente del backend (Python/FastAPI)
- Configuraciones de despliegue (Docker, docker-compose.yml, Kubernetes manifests)
- Bases de datos y almacenamiento de datos
- Configuración de servicios externos (Ollama, Hugging Face)

### 4.4. Período Auditado
[Desde dd/mm/aaaa hasta dd/mm/aaaa]

**Evidencia:** [A completar]

---

## 5. NORMATIVA Y CRITERIOS DE EVALUACIÓN

### 5.1. Normas y Estándares Aplicados
- **COBIT 2019:** Marco de gobierno y gestión de tecnologías de la información
- **ISO/IEC 27001:2022:** Gestión de seguridad de la información
- **OWASP Top 10:** Principales vulnerabilidades de seguridad en aplicaciones web
- **CWE (Common Weakness Enumeration):** Clasificación de debilidades de software

### 5.2. Políticas y Mejores Prácticas
- Políticas internas de seguridad de TI de la entidad
- Mejores prácticas de desarrollo seguro (Secure Coding Practices)
- Estándares de despliegue en contenedores (Docker, Kubernetes)
- Mejores prácticas de gestión de datos personales

### 5.3. Criterios de Evaluación
- Confidencialidad, integridad y disponibilidad de la información (CIA)
- Cumplimiento de principio de menor privilegio
- Implementación de controles de seguridad adecuados
- Calidad del código y mantenibilidad
- Disponibilidad y recuperabilidad del servicio

**Evidencia:** [A completar]

---

## 6. METODOLOGÍA Y ENFOQUE

### 6.1. Enfoque Utilizado
Enfoque mixto basado en riesgos y cumplimiento normativo.

### 6.2. Métodos Aplicados
- **Entrevistas:** Con desarrolladores y responsables de TI
- **Inspección de documentos:** Revisión de código fuente, configuración y documentación
- **Pruebas técnicas:**
  - Análisis de código estático
  - Revisión de configuraciones de seguridad
  - Verificación de logs del sistema
  - Pruebas de funcionamiento del sistema
- **Revisión de configuraciones:** Docker, docker-compose, Kubernetes, servicios
- **Aplicación de listas de verificación:** Basadas en OWASP, CWE y mejores prácticas

**Evidencia:** [A completar]

---

## 7. HALLAZGOS Y OBSERVACIONES

### 7.1. Hallazgo 1: [Título del Hallazgo]
**Descripción del hallazgo:** [Descripción detallada]

**Evidencia objetiva:** [A completar]

**Grado de criticidad:** [Alto/Medio/Bajo]

**Criterio vulnerado:** [Indicar norma, estándar o práctica vulnerada]

**Causa:** [Análisis de la causa raíz]

**Efecto:** [Impacto del hallazgo en el sistema]

---

### 7.2. Hallazgo 2: [Título del Hallazgo]
**Descripción del hallazgo:** [Descripción detallada]

**Evidencia objetiva:** [A completar]

**Grado de criticidad:** [Alto/Medio/Bajo]

**Criterio vulnerado:** [Indicar norma, estándar o práctica vulnerada]

**Causa:** [Análisis de la causa raíz]

**Efecto:** [Impacto del hallazgo en el sistema]

---

### 7.3. Hallazgo 3: [Título del Hallazgo]
**Descripción del hallazgo:** [Descripción detallada]

**Evidencia objetiva:** [A completar]

**Grado de criticidad:** [Alto/Medio/Bajo]

**Criterio vulnerado:** [Indicar norma, estándar o práctica vulnerada]

**Causa:** [Análisis de la causa raíz]

**Efecto:** [Impacto del hallazgo en el sistema]

---

[Continuar con más hallazgos según corresponda]

---

## 8. ANÁLISIS DE RIESGOS

| Hallazgo | Riesgo Asociado | Impacto | Probabilidad | Nivel de Riesgo |
|----------|-----------------|---------|--------------|-----------------|
| 1        | [Descripción del riesgo] | Alto/Medio/Bajo | Alta/Media/Baja | Alto/Medio/Bajo |
| 2        | [Descripción del riesgo] | Alto/Medio/Bajo | Alta/Media/Baja | Alto/Medio/Bajo |
| 3        | [Descripción del riesgo] | Alto/Medio/Bajo | Alta/Media/Baja | Alto/Medio/Bajo |

**Evidencia:** [A completar]

---

## 9. RECOMENDACIONES

### 9.1. Recomendación 1 (Asociada al Hallazgo 1)
**Descripción:** [Descripción de la recomendación técnica u organizativa]

**Prioridad:** [Alta/Media/Baja]

**Evidencia:** [A completar]

---

### 9.2. Recomendación 2 (Asociada al Hallazgo 2)
**Descripción:** [Descripción de la recomendación técnica u organizativa]

**Prioridad:** [Alta/Media/Baja]

**Evidencia:** [A completar]

---

### 9.3. Recomendación 3 (Asociada al Hallazgo 3)
**Descripción:** [Descripción de la recomendación técnica u organizativa]

**Prioridad:** [Alta/Media/Baja]

**Evidencia:** [A completar]

---

[Continuar con más recomendaciones según corresponda]

---

## 10. CONCLUSIONES

### 10.1. Estado General del Sistema
[Evaluación general del estado de control y gestión del sistema Corporate EPIS Pilot]

### 10.2. Aspectos Positivos
- [Aspecto positivo identificado]
- [Aspecto positivo identificado]

### 10.3. Aspectos Críticos Identificados
- [Aspecto crítico identificado]
- [Aspecto crítico identificado]

### 10.4. Cumplimiento Normativo
[Evaluación del cumplimiento con las normativas y estándares aplicables]

### 10.5. Síntesis Evaluativa
[Síntesis sobre la adecuación y eficacia de los controles existentes]

**Evidencia:** [A completar]

---

## 11. PLAN DE ACCIÓN Y SEGUIMIENTO

| Hallazgo | Recomendación | Responsable | Fecha Comprometida | Estado |
|----------|---------------|-------------|---------------------|--------|
| 1        | [Texto de recomendación] | [Área o persona] | [dd/mm/aaaa] | [Pendiente/En proceso/Completado] |
| 2        | [Texto de recomendación] | [Área o persona] | [dd/mm/aaaa] | [Pendiente/En proceso/Completado] |
| 3        | [Texto de recomendación] | [Área o persona] | [dd/mm/aaaa] | [Pendiente/En proceso/Completado] |

**Evidencia:** [A completar]

---

## 12. ANEXOS

### Anexo A: Cuestionarios Aplicados
[Descripción y copia de cuestionarios utilizados en la auditoría]

**Evidencia:** [A completar]

---

### Anexo B: Capturas de Pantalla
[Descripción de capturas de pantalla relevantes]

**Evidencia:** [A completar]

---

### Anexo C: Registros de Logs
[Descripción de registros de logs analizados]

**Evidencia:** [A completar]

---

### Anexo D: Configuraciones Revisadas
[Descripción de archivos de configuración revisados]

**Evidencia:** [A completar]

---

### Anexo E: Revisión de Código Fuente
[Descripción de archivos de código fuente revisados]

**Evidencia:** [A completar]

---

### Anexo F: Políticas y Documentación Revisada
[Descripción de políticas y documentación técnica revisada]

**Evidencia:** [A completar]

---

### Anexo G: Información Técnica del Sistema

#### Stack Tecnológico
- **Backend:** Python 3.12, FastAPI, LangChain, Ollama (smollm:360m), Uvicorn
- **IA & NLP:** RAG, Hugging Face Embeddings (multilingual-e5-large), ChromaDB
- **Frontend:** React, TypeScript, Material-UI (MUI), Vite
- **Base de Datos:** SQLite (tickets), ChromaDB (vector store)
- **DevOps:** Docker, Docker Compose, Kubernetes, NGINX Ingress

#### Arquitectura del Sistema
El sistema implementa una arquitectura de microservicios con:
- Frontend React que gestiona el estado de la conversación
- Backend stateless FastAPI que responde a consultas
- Router LangChain para clasificación de intenciones
- RAG Chain para respuestas basadas en conocimiento
- Bases de datos persistentes para tickets y conocimiento vectorial

**Evidencia:** [A completar]

---

**Fin del Informe**

---

*Este informe de auditoría fue generado el [dd/mm/aaaa] por el equipo auditor y refleja el estado del sistema al momento de la evaluación.*

**Equipo Auditor:**  
Mirian Cuadros Garcia - 2021071083
