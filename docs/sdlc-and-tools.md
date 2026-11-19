SDLC and tools


Estoy usando java y maven




# 🔄 Software Development Life Cycle (SDLC) & Tools

Este documento describe el ciclo de vida del desarrollo de software (SDLC) y el stack de herramientas utilizado en este proyecto.

## 🛠️ Tech Stack Principal
* **Lenguaje:** Java
* **Gestor de Dependencias y Build:** Maven
* **API Gateway:** Kong API Gateway

---

## 🚀 Fases del SDLC y Herramientas

### 1. Planificación y Diseño (Plan)
Definición de requerimientos, historias de usuario y arquitectura del sistema.
* **Gestión de tareas:** Jira / GitHub Projects
* **Documentación:** Confluence / GitHub Wiki

### 2. Desarrollo (Code)
Escritura del código fuente y control de versiones.
* **IDE Recomendado:** IntelliJ IDEA / Eclipse / VS Code
* **Control de Versiones:** Git
* **Repositorio:** GitHub

### 3. Construcción (Build)
Compilación del código Java y empaquetado del artefacto (JAR/WAR).
* **Herramienta:** **Maven**
* **Comando principal:** `mvn clean install`

### 4. Pruebas y Calidad (Test)
Ejecución de pruebas automatizadas y análisis de código estático.
* **Pruebas Unitarias:** JUnit / Mockito
* **Cobertura de Código:** JaCoCo
* **Calidad y Seguridad:** SonarQube

### 5. Integración Continua / Despliegue Continuo (CI/CD)
Automatización de la compilación, pruebas y despliegue cada vez que se hace un *push* o *Pull Request*.
* **Pipeline:** GitHub Actions / Jenkins
* **Repositorio de Artefactos:** Nexus / JFrog Artifactory

### 6. Despliegue y Operación (Deploy & Operate)
Puesta en producción de la aplicación.
* **Contenedores:** Docker
* **Orquestación:** Kubernetes
* **Infraestructura:** AWS / GCP / Azure

### 7. Monitoreo (Monitor)
Supervisión de la salud y rendimiento de la aplicación en tiempo real.
* **Métricas y Logs:** Prometheus / Grafana / ELK Stack (Elasticsearch, Logstash, Kibana)

---
