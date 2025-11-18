# Cloud Computing

## 1. Tipos de Nubes (Modelos de Despliegue)
Definen dónde se aloja la infraestructura y quién la gestiona.

### Nube Pública (Public Cloud)
**Descripción:**  
Los recursos (servidores, almacenamiento, redes, aplicaciones) son propiedad de un proveedor externo (como AWS, Azure, GCP), quien los opera y los pone a disposición de múltiples usuarios o el público general a través de internet. Los usuarios acceden a estos servicios bajo demanda y pagan solo por lo que utilizan.

**Características Clave:**
- **Alta Escalabilidad:** Permite escalar recursos rápidamente según la demanda.  
- **Pago por Uso:** Modelo de consumo flexible, se paga por los recursos consumidos.  
- **Mantenimiento Gestionado:** El proveedor se encarga de infraestructura y actualizaciones.  
- **Menor Control:** Los usuarios tienen menos control sobre la infraestructura física.

**Ejemplo:** Alojar un sitio web en Amazon EC2 o usar Google Cloud Storage.

---

### Nube Privada (Private Cloud)
**Descripción:**  
La infraestructura se utiliza exclusivamente por una sola organización. Puede estar en el centro de datos de la empresa o ser gestionada por un tercero, siempre para un único cliente.

**Características Clave:**
- **Mayor Control y Seguridad:** Control total sobre datos e infraestructura.  
- **Personalización:** Se adapta a las necesidades exactas de la empresa.  
- **Mayor Inversión y Gestión:** Requiere inversión inicial y gestión propia.

**Ejemplo:** Un banco que mantiene su propio centro de datos para aplicaciones críticas.

---

### Nube Híbrida (Hybrid Cloud)
**Descripción:**  
Combinación de nube pública y privada interconectadas, operando como una sola entidad, permitiendo mover aplicaciones y datos entre ambos entornos.

**Características Clave:**
- **Flexibilidad y Agilidad:** Aprovecha ventajas de ambas nubes.  
- **Optimización de Costos:** Uso eficiente de recursos según demanda.  
- **Resiliencia:** Distribución de cargas de trabajo para mayor disponibilidad.

**Ejemplo:** Una tienda que usa nube privada para bases de datos y pública para su sitio web durante Black Friday.

---

## 2. Modelos de Servicio en la Nube
Definen el nivel de responsabilidad que asume el proveedor frente al usuario.

### IaaS (Infrastructure as a Service)
**Descripción:**  
El proveedor gestiona infraestructura básica (servidores, almacenamiento, redes, virtualización). El usuario controla sistemas operativos, middleware, runtime y aplicaciones.

**Analogía:** Alquilar un terreno y construir tu propia casa.

**Responsabilidad del Usuario:** Sistemas operativos, middleware, runtime, datos, aplicaciones.  
**Responsabilidad del Proveedor:** Redes, almacenamiento, servidores, virtualización.

**Ejemplos:** Amazon EC2, Azure Virtual Machines, Google Compute Engine.

---

### PaaS (Platform as a Service)
**Descripción:**  
El proveedor ofrece hardware y un entorno de desarrollo completo, incluyendo SO, runtime, bases de datos y middleware, permitiendo desarrollar y ejecutar aplicaciones sin preocuparse por infraestructura.

**Analogía:** Alquilar un apartamento totalmente amueblado y con servicios incluidos.

**Responsabilidad del Usuario:** Datos, aplicaciones.  
**Responsabilidad del Proveedor:** Redes, almacenamiento, servidores, virtualización, sistemas operativos, middleware, runtime.

**Ejemplos:** AWS Elastic Beanstalk, Azure App Service, Google App Engine.

---

### SaaS (Software as a Service)
**Descripción:**  
El proveedor ofrece una aplicación completa lista para usarse, accesible vía internet. El usuario solo gestiona sus datos.

**Analogía:** Ir a un hotel; todo está gestionado.

**Responsabilidad del Usuario:** Datos del usuario.  
**Responsabilidad del Proveedor:** Toda la pila (redes, almacenamiento, servidores, virtualización, SO, middleware, runtime, aplicaciones).

**Ejemplos:** Gmail, Microsoft 365, Salesforce, Dropbox.

---

## 3. Principales Proveedores de Servicios en la Nube
Líderes del mercado que ofrecen servicios IaaS, PaaS y SaaS.

### AWS (Amazon Web Services)
- **Operador:** Amazon  
- **Fortaleza:** Liderazgo de mercado, gran cartera de servicios, escalabilidad, comunidad y herramientas.  
- **Enfoque:** Startups, grandes empresas, desarrollo, análisis de datos, ML.  
- **Servicios Clave:** Amazon EC2, Amazon S3, Amazon RDS, Lambda.

---

### Microsoft Azure
- **Operador:** Microsoft  
- **Fortaleza:** Integración con productos Microsoft (Windows, SQL, .NET, AD).  
- **Enfoque:** Nube híbrida, aplicaciones empresariales, datos, seguridad, IA/ML.  
- **Servicios Clave:** Azure Virtual Machines, Azure Storage, Azure SQL Database, Azure App Service, Azure AD.

---

### GCP (Google Cloud Platform)
- **Operador:** Google  
- **Fortaleza:** Big Data, IA/ML, contenedores, infraestructura de red global.  
- **Enfoque:** Análisis de datos, ML, aplicaciones con contenedores, análisis geoespacial.  
- **Servicios Clave:** Google Compute Engine, BigQuery, Google Kubernetes Engine, TensorFlow.

---

### OCI (Oracle Cloud Infrastructure)
- **Operador:** Oracle  
- **Fortaleza:** Rendimiento y costo optimizados, seguridad, ideal para aplicaciones Oracle.  
- **Enfoque:** Bases de datos Oracle, aplicaciones empresariales, infraestructura de alto rendimiento.  
- **Servicios Clave:** OCI Compute, Autonomous Database, servicios de red, almacenamiento de bloques y objetos.
