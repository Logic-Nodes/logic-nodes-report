<div style="text-align: center">
  <p align="center">
    <br />
    <img
      src="https://www.upc.edu.pe/static/img/logo_upc_red.png"
      width="100px"
    />
    <br />
    <strong>Universidad Peruana de Ciencias Aplicadas</strong>
    <br /><br />
    <strong>Carrera de Ingeniería de Software</strong>
    <br /><br />
    <strong>Ciclo 202610</strong>
    <br /><br />
    1ASI0572 - Desarrollo de Soluciones IOT
    <br /><br />
    <strong>NRC:</strong> 6770 <br /><br />
    <strong>Profesor:</strong> Prudencio Vidal, Javier Antonio <br /><br />
    <strong>Informe de TB1</strong>
  </p>

  <div style="width: 80%; margin: 0 auto; text-align: center">
    <p>
      <strong>Startup:</strong> LogicNodes 
      <br />
      <strong>Producto:</strong> OmniTrack
    </p>

  <div>
      <strong>Relación de integrantes</strong>
      <br /><br />
      <table style="width: 60%; margin: 0 auto;   text-align: left">
        <thead>
          <tr>
            <th>Código</th>
            <th>Nombre</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>u202216698 </td>
            <td> Rodrigo Alonso, Alcántara Cruz, </td>
          </tr>
          <tr>
            <td> u20191e562 </td>
            <td> Paulo Percy, Quincho Gamarra </td>
          </tr>
          <tr>
            <td> u202210334 </td>
            <td> Adrian Emanuel, Valerio Garcia  </td>
          </tr>
          <tr>
            <td> U202011431 </td>
            <td> Luiggi Jeremy Jouvenel, Antonio Loayza </td>
          </tr>
          <tr>
            <td> u202313397 </td>
            <td> Alejandro Daniel, Oroncoy Almeyda </td>
          </tr>
        </tbody>
      </table>
      <p style="text-align: center">
        <br />
        <strong>Abril 2026</strong>
      </p>
    </div>

  </div>
</div>

<div style="page-break-after: always;"></div>

| Versión | Fecha | Autor | Descripción de modificación |
| :--- | :--- | :--- | :--- |
|  1.0    |              |              |                    |
|  1.0.1  |              |               |                   |
|  1.0.2  |              |              |                    |
|  1.0.3    |              |              |                    |

# Project Report Collaboration Insights

En esta seccion se registra la colaboración de todo el equipo durante el desarrollo del informe del proyecto, se adjunta el enlace del repositorio 

| Repository Name | Link |
| :--- | :--- |
| **logic-nodes-report** | [https://github.com/Logic-Nodes/logic-nodes-report](https://github.com/Logic-Nodes/logic-nodes-report) |

# Contenido

_Tabla de contenidos_


- [Student Outcome]
- [Capítulo I: Introducción]
  - [1.1. Startup Profile]
    - [1.1.1. Descripción de la Startup]
    - [1.1.2. Perfiles de integrantes del equipo]
  - [1.2. Solution Profile]
    - [1.2.1. Antecedentes y problemática]
    - [1.2.2. Lean UX Process]
      - [1.2.2.1. Lean UX Problem Statements]
      - [1.2.2.2. Lean UX Assumptions]
      - [1.2.2.3. Lean UX Hypothesis Statements]
      - [1.2.2.4. Lean UX Canvas]
  - [1.3. Segmentos objetivo]
- [Capítulo II: Requirements Elicitation \& Analysis]
  - [2.1. Competidores]
    - [2.1.1. Análisis competitivo]
    - [2.1.2. Estrategias y tácticas frente a competidores]
  - [2.2. Entrevistas]
    - [2.2.1. Diseño de entrevistas]
    - [2.2.2. Registro de entrevistas]
    - [2.2.3. Análisis de entrevistas]
  - [2.3. Needfinding]
    - [2.3.1. User Personas]
    - [2.3.2. User Task Matrix]
    - [2.3.3. User Journey Mapping]
    - [2.3.4. Empathy Mapping]
  - [2.4. Big Picture EventStorming]
  - [2.5. Ubiquitous Language]
- [Capítulo III: Requirements Specification]
  - [3.1. User Stories]
  - [3.2. Impact Mapping]
  - [3.3. Product Backlog]
- [Capítulo IV: Solution Software Design]
  - [4.1. Strategic-Level Domain-Driven Design]
    - [4.1.1. Design-Level EventStorming]
      - [4.1.1.1 Candidate Context Discovery]
      - [4.1.1.2. Domain Message Flows Modeling]
      - [4.1.1.3. Bounded Context Canvases]
    - [4.1.2. Context Mapping]
    - [4.1.3. Software Architecture]
      - [4.1.3.1. Software Architecture System Landscape Diagram]
      - [4.1.3.2. Software Architecture Context Level Diagrams]
      - [4.1.3.2. Software Architecture Container Level Diagrams]
      - [4.1.3.3. Software Architecture Deployment Diagrams]
  - [4.2. Tactical-Level Domain-Driven Design]
    - [4.2.1. Bounded Context: Identity and Access Management]
      - [4.2.1.1. Domain Layer]
      - [4.2.1.2. Interface Layer]
      - [4.2.1.3. Application Layer]
      - [4.2.1.4. Infrastructure Layer]
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.1.6.2. Bounded Context Database Design Diagram]
    - [4.2.2. Bounded Context: _Subscriptions and Billing_]
      - [4.2.2.1. Domain Layer]
      - [4.2.2.2. Interface Layer]
      - [4.2.2.3. Application Layer]
      - [4.2.2.4. Infrastructure Layer]
      - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.2.6.2. Bounded Context Database Design Diagram]
    - [4.2.3. Bounded Context: _Alerts \& Resolution_]
      - [4.2.3.1. Domain Layer]
      - [4.2.3.2. Interface Layer]
      - [4.2.3.3. Application Layer]
      - [4.2.3.4. Infrastructure Layer]
      - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.3.6.2. Bounded Context Database Design Diagram]
    - [4.2.4. Bounded Context: _Real-Time Monitoring_]
      - [4.2.4.1. Domain Layer.]
      - [4.2.4.2. Interface Layer.]
      - [4.2.4.3. Application Layer.]
      - [4.2.4.4. Infrastructure Layer.]
      - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.4.6.2. Bounded Context Database Design Diagram]
    - [4.2.5. Bounded Context: _Trip management_]
      - [4.2.5.1. Domain Layer.]
      - [4.2.5.2. Interface Layer.]
      - [4.2.5.3. Application Layer.]
      - [4.2.5.4. Infrastructure Layer.]
      - [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams.]
      - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.]
        - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.]
        - [4.2.5.6.2. Bounded Context Database Design Diagram.]
    - [4.2.6. Bounded Context: Fleet Management]
      - [4.2.6.1. Domain Layer]
      - [4.2.6.2. Interface Layer]
      - [Controllers principales (HTTP REST)]
      - [4.2.6.3. Application Layer]
      - [4.2.6.4. Infrastructure Layer]
      - [4.2.6.5. Bounded Context Software Architecture Component Level Diagrams.]
      - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.]
        - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.]
        - [4.2.5.6.2. Bounded Context Database Design Diagram.]
    - [4.2.7. Bounded Context: Profile and Preferences Management]
      - [4.2.7.1. Domain Layer.]
      - [4.2.7.2. Interface Layer.]
      - [4.2.7.3. Application Layer.]
      - [4.2.7.4. Infrastructure Layer.]
      - [4.2.7.5. Bounded Context Software Architecture Component Level Diagrams.]
      - [4.2.7.6. Bounded Context Software Architecture Code Level Diagrams.]
        - [4.2.7.6.1. Bounded Context Domain Layer Class Diagrams.]
        - [4.2.7.6.2. Bounded Context Database Design Diagram]
    - [4.2.8. Bounded Context: Visualization Analytics]
      - [4.2.8.1. Domain Layer]
      - [4.2.8.2. Interface Layer]
      - [4.2.8.3. Application Layer]
      - [4.2.8.4. Infrastructure Layer]
      - [4.2.8.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.8.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.8.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.8.6.2. Bounded Context Database Design Diagram]
    - [4.2.9. Bounded Context: Merchant]
      - [4.2.9.1. Domain Layer]
      - [4.2.9.2. Interface Layer]
      - [4.2.9.3. Application Layer]
      - [4.2.9.4. Infrastructure Layer]
      - [4.2.9.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.9.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.9.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.9.6.2. Bounded Context Database Design Diagram]

# Student Outcome

El curso cumple de manera directa el cumplimiento del Student Outcome 5 definido por ABET - EAC, asegurando que los integrantes logren alcanzar las competencias establecidas

Criterio: La capacidad de funcionar efectivamente en un
equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de
colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Alcantara Cruz, Rodrigo Alonso** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Quincho Gamarra, Paulo Percy** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Valerio Garcia, Adrian Emanuel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Antonio Loayza, Luiggi Jeremy Jouvenel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Oroncoy Almeyda, Alejandro Daniel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] | [pending...] |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** | **Alcantara Cruz, Rodrigo Alonso** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Quincho Gamarra, Paulo Percy** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Valerio Garcia, Adrian Emanuel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Antonio Loayza, Luiggi Jeremy Jouvenel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Oroncoy Almeyda, Alejandro Daniel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] | [pending...] |

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos objetivo
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
## 2.4. Big Picture EventStorming
## 2.5. Ubiquitous Language
# Capítulo III: Requirements Specification
## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog
# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. Design-Level EventStorming
#### 4.1.1.1 Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases
### 4.1.2. Context Mapping

En esta etapa se definió el **Context Map** de LogicaNodes a partir de los ocho *bounded contexts* previamente identificados. El objetivo principal fue modelar las **relaciones estructurales** entre ellos utilizando patrones de *Domain-Driven Design* como *Customer/Supplier*, *Conformist* y *Anti-Corruption Layer (ACL)*.

### Resultado

El mapa construido permitió:

1. **Entender las dependencias entre contextos**, identificando qué módulos exponen información y cuáles la consumen.
2. **Diferenciar los contextos según su rol**, distinguiendo los núcleos del negocio (Trip Management, Monitoring, Alerts), los de soporte (Fleet, Profiles, Analytics) y los genéricos (IAM, Billing).
3. **Clasificar los tipos de relación**:
   - Predominio de *Customer/Supplier* en flujos operativos (Billing → IAM, Trip → Monitoring, Monitoring → Alerts).
   - Uso de *Conformist* en el consumo de datos por Analytics.
   - Aplicación de *Anti-Corruption Layer* en la interacción entre Analytics y Profiles.

Este mapeo proporciona una visión global del sistema, evidenciando cómo los distintos contextos se articulan para soportar las capacidades del negocio.

![EventStorming – Context Mapping](img/Context_Mapping.png)

---

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

El **System Landscape Diagram** ofrece una visión general del **ecosistema empresarial** en el que opera LogicNodes. No se limita a un único sistema, sino que incluye los actores y plataformas relevantes, tanto internos como externos, involucrados en la operación logística.

### Propósito

Este diagrama tiene como finalidad:

1. Delimitar el alcance organizacional y la interacción entre sistemas.
2. Identificar a las **personas, sistemas internos, servicios SaaS y proveedores externos** involucrados.
3. Mostrar cómo **LogicNodes (SaaS)** se integra dentro de este entorno.

![Software Architecture – System Landscape Diagram](img/System_Landscape_Diagram.png)

### Elementos incluidos

- **Actores**: Company Operator, Driver, End Customer  
- **Sistemas internos**: Logistics Planning, Power BI Data  
- **Servicios externos**: LogicNodes (SaaS), Stripe, Google Maps, Notification Services, IoT Devices  
- **Agrupaciones**:
  - Logistics company  
  - Field / Devices  
  - Customers and Regulators  
  - SaaS and Vendors  

### Relaciones principales

- Logistics Planning → LogicNodes: envío de planes y asignaciones  
- IoT Devices → LogicNodes: transmisión de telemetría (temperatura, humedad, vibración, inclinación, GPS, batería)  
- LogicNodes → Google Maps: consulta de rutas y tiempos estimados  
- LogicNodes → Notification Services: envío de alertas  
- LogicNodes → Stripe: procesamiento de pagos  
- LogicNodes → Power BI Data: exportación de datos consolidados  
- Company Operator / Driver ↔ LogicNodes: interacción operativa  
- End Customer ← LogicNodes: acceso a estado y reportes  

### Resultado

El diagrama posiciona a LogicNodes como el punto central de integración entre operaciones logísticas, dispositivos IoT y servicios externos, además de alimentar plataformas analíticas.

---

#### 4.1.3.2. Software Architecture Context Level Diagrams

El **Context Diagram** presenta una vista de alto nivel del sistema y sus interacciones con usuarios y servicios externos.

![Software Architecture – Context Level Diagram](img/Context_Level_Diagram.png)

LogicNodes se ubica en el centro como el sistema encargado del monitoreo, la trazabilidad y la generación de alertas.

### Actores principales

- **Company Operator**: gestiona viajes, flota y reportes  
- **Driver**: ejecuta viajes y reporta información  
- **End Customer**: consulta estados y reportes  

### Sistemas externos

- Google Maps: rutas, geocodificación y ETA  
- Firebase Cloud Messaging: notificaciones push  
- Stripe: pagos y facturación  

Este diagrama permite identificar responsabilidades y flujos de interacción entre actores y servicios.

---

#### 4.1.3.2. Software Architecture Container Level Diagrams

En esta sección se detalla la estructura interna de **LogicNodes**, mostrando sus contenedores, tecnologías y comunicación.

![Software Architecture – Container Level Diagram](img/Container_Level_Diagram.png)

### Contenedores principales

- **Landing Page**: sitio público orientado a marketing  
- **Web Frontend**: interfaz para operadores  
- **Single Web**: vista pública para clientes sin autenticación  
- **Mobile App**: aplicación para conductores con enfoque offline-first y almacenamiento en SQLite  
- **Backend API**: núcleo de la lógica de negocio  
- **PostgreSQL**: base de datos principal  
- **Edge Application (Python)**: procesamiento local y sincronización  
- **Embedded Application (C++)**: captura de datos en dispositivos limitados  

### Interacción con usuarios

- Company Operator → Web Frontend  
- Driver → Mobile App  
- End Customer → Single Web / Mobile App  

### Integraciones externas

- Google Maps  
- Stripe  
- Firebase Cloud Messaging (FCM)  

Este nivel refleja una arquitectura modular que soporta operación tanto en línea como sin conectividad.

---

#### 4.1.3.3. Software Architecture Deployment Diagrams

El **Deployment Diagram** describe cómo se implementa LogicNodes en un entorno productivo, incluyendo infraestructura y comunicación entre componentes.

![Software Architecture – Deployment Diagram](img/Deployment_Diagram.png)

### Clientes

- Acceso web mediante CDNs (CloudFlare / AWS CloudFront)  
- Aplicación móvil Flutter con base de datos SQLite local  
- Comunicación vía HTTPS hacia un Load Balancer  

### Backend

- API desplegada en un clúster de Kubernetes con múltiples instancias  
- Gestión centralizada de lógica de negocio y procesamiento en tiempo real  

### Base de datos

- PostgreSQL gestionado (AWS RDS / Google Cloud SQL)  
- Instancia principal y réplicas de lectura  
- Persistencia local en SQLite para operación offline  

### Integraciones externas

- Google Maps: rutas y geolocalización  
- Stripe: pagos  
- Firebase Cloud Messaging: notificaciones push  

### Resultado

La arquitectura de despliegue refleja un enfoque *cloud-native* con:

- Separación de responsabilidades  
- Soporte offline en dispositivos móviles  
- Orquestación mediante Kubernetes  
- Distribución eficiente mediante CDNs  
- Base de datos escalable con replicación  
- Notificaciones en tiempo real  

Este diseño permite escalabilidad, resiliencia y continuidad operativa, incluso en escenarios con conectividad limitada.
## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Identity and Access Management
#### 4.2.1.1. Domain Layer
#### 4.2.1.2. Interface Layer
#### 4.2.1.3. Application Layer
#### 4.2.1.4. Infrastructure Layer
#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.1.6.2. Bounded Context Database Design Diagram
### 4.2.2. Bounded Context: Subscriptions and Billing
#### 4.2.2.1. Domain Layer
#### 4.2.2.2. Interface Layer
#### 4.2.2.3. Application Layer
#### 4.2.2.4. Infrastructure Layer

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
## Diagrama de componentes – Backend – Subscriptions and Billing

![Component diagrams](img/Component_diagram_backend.png)

El backend correspondiente al bounded context de Suscripciones y Pagos se estructura en cuatro capas principales:

- **Interface Layer**: contiene los controladores REST encargados de atender solicitudes relacionadas con suscripciones, pagos, planes y compañías. Actúa como punto de acceso para usuarios y sistemas externos que consumen la API.
- **Application Layer**: gestiona la ejecución de los casos de uso mediante Command Services, Query Services y Event Handlers. En esta capa se coordinan las operaciones y se invocan las reglas de negocio necesarias.
- **Domain Layer**: reúne la lógica central del negocio, incluyendo entidades, objetos de valor, servicios de dominio y fábricas. Define las reglas que gobiernan el ciclo de vida de las suscripciones y los pagos.
- **Infrastructure Layer**: proporciona implementaciones concretas de repositorios y conectores hacia bases de datos y servicios externos. Se encarga de la persistencia y la integración técnica.

Las integraciones externas consideradas son:

- Postgres, utilizado para la persistencia transaccional de datos como suscripciones, pagos y compañías.
- Stripe, empleado para la gestión y procesamiento de pagos.
- Firebase Cloud Messaging (FCM), utilizado para el envío de notificaciones push.
- Google Maps, usado para consultas de rutas y estimaciones de tiempo (ETA).

---

## Diagrama de componentes – Application Web – Subscriptions and Billing

![Component diagrams](img/Component_diagram_applicationweb.png)

La aplicación web interactúa con el bounded context **Subscriptions & Billing** exclusivamente mediante APIs:

- _Subscriptions API_: utilizada para ejecutar acciones como crear o cancelar suscripciones.
- _Query API_: destinada a la consulta de información como planes o facturas.

En el cliente, la aplicación se organiza en tres componentes principales:

- **UI (interfaz de usuario)**: incluye las vistas relacionadas con suscripciones, pagos y facturación.
- **Estado de la aplicación**: administra la sesión del usuario, el almacenamiento en caché de consultas y la autenticación.
- **Servicios de datos**: implementa el cliente HTTP encargado de consumir las APIs, añadir el token de seguridad y manejar reintentos o errores.

La lógica de negocio no reside en el frontend; su función se limita a presentar información y enviar las acciones del usuario al backend. Las validaciones, reglas y persistencia se gestionan completamente en el servidor.

---

## Diagrama de componentes – Mobile Application – Subscriptions and Billing

![Component diagrams](img/Component_diagram_mobile.png)

La aplicación móvil de **Subscriptions & Billing** sigue una arquitectura similar a la versión web, ya que también se comunica con el backend mediante:

- _Subscriptions API_
- _Query API_

Como diferencia principal, incorpora una base de datos local (SQLite), lo que permite operar en modo offline: la aplicación puede almacenar datos localmente y continuar funcionando sin conexión, sincronizando la información cuando se restablece el acceso a internet.

Su estructura incluye:

- Pantallas orientadas a suscripciones y facturación.
- Un estado de aplicación que controla la sesión y el caché.
- Un cliente de API que gestiona las solicitudes al backend incorporando el token de autenticación.

Al igual que en la versión web, toda la lógica de negocio se mantiene en el backend; el cliente únicamente se encarga de la visualización de datos y del envío de las acciones realizadas por el usuario.

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
#### 4.2.2.6.2. Bounded Context Database Design Diagram
### 4.2.3. Bounded Context: Alerts & Resolution
#### 4.2.3.1. Domain Layer
#### 4.2.3.2. Interface Layer
#### 4.2.3.3. Application Layer
#### 4.2.3.4. Infrastructure Layer
#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.3.6.2. Bounded Context Database Design Diagram
### 4.2.4. Bounded Context: Real-Time Monitoring
#### 4.2.4.1. Domain Layer.
#### 4.2.4.2. Interface Layer.
#### 4.2.4.3. Application Layer.
#### 4.2.4.4. Infrastructure Layer.
#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.4.6.2. Bounded Context Database Design Diagram
### 4.2.5. Bounded Context: Trip management
#### 4.2.5.1. Domain Layer.
#### 4.2.5.2. Interface Layer.
#### 4.2.5.3. Application Layer.
#### 4.2.5.4. Infrastructure Layer.
#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.5.6.2. Bounded Context Database Design Diagram.
### 4.2.6. Bounded Context: Fleet Management
#### 4.2.6.1. Domain Layer
#### 4.2.6.2. Interface Layer
#### 4.2.6.3. Application Layer
#### 4.2.6.4. Infrastructure Layer
#### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.5.6.2. Bounded Context Database Design Diagram.
### 4.2.7. Bounded Context: Profile and Preferences Management
#### 4.2.7.1. Domain Layer.
#### 4.2.7.2. Interface Layer.
#### 4.2.7.3. Application Layer.
#### 4.2.7.4. Infrastructure Layer.
#### 4.2.7.5. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.7.6. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.7.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.7.6.2. Bounded Context Database Design Diagram
### 4.2.8. Bounded Context: Visualization Analytics
#### 4.2.8.1. Domain Layer
#### 4.2.8.2. Interface Layer
#### 4.2.8.3. Application Layer
#### 4.2.8.4. Infrastructure Layer
#### 4.2.8.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.8.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.8.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.8.6.2. Bounded Context Database Design Diagram
### 4.2.9. Bounded Context: Merchant
#### 4.2.9.1. Domain Layer
#### 4.2.9.2. Interface Layer
#### 4.2.9.3. Application Layer
#### 4.2.9.4. Infrastructure Layer
#### 4.2.9.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.9.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.9.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.9.6.2. Bounded Context Database Design Diagram
