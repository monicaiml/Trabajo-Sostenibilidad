# Análisis de Materialidad y Stakeholders

## 1. Identificación y Mapeo de Stakeholders (Grupos de Interés)

Para asegurar que la aplicación web responda a las necesidades de **ACME Transport S.L.**, se han identificado y priorizado los siguientes grupos de interés internos y externos:

| Grupo de Interés | Tipo | Intereses y Expectativas Clave | Relación con la Aplicación Web |
| --- | --- | --- | --- |
| **Dirección y Gerencia** | Interno | Cumplimiento normativo, eficiencia operativa, reducción de costes energéticos/combustible y mejora del valor de marca. | Consultará el dashboard ejecutivo para la toma de decisiones estratégicas. |
| **Conductores y Personal de Reparto** | Interno | Rutas eficientes, condiciones de trabajo seguras, carga justa y concienciación ambiental. | Proveen datos operativos de consumo/rutas y se benefician de la optimización de trayectos. |
| **Personal de Almacén y Operaciones** | Interno | Seguridad laboral, reducción de residuos de embalaje, facilitación del reciclaje y gestión eficiente del consumo eléctrico. | Registrarán datos de uso de materiales/residuos y consumo de instalaciones en la plataforma. |
| **Clientes (Comercio Electrónico)** | Externo | Envíos sostenibles, transparencia en la huella de carbono por paquete y embalajes ecológicos. | Recibirán informes/certificados de emisiones asociadas a sus envíos y métricas de reciclaje. |
| **Proveedores de Materiales y Flota** | Externo | Exigencias de empaquetado sostenible, vehículos de bajas emisiones y contratos éticos. | Integración progresiva de criterios ASG en la cadena de suministro. |
| **Organismos Reguladores y Admin. Pública** | Externo | Cumplimiento de normativas ambientales (emisiones, gestión de residuos) y reporte ASG veraz. | La aplicación generará reportes estructurados para auditorías e inspecciones. |

---

## 2. Integración de Necesidades de los Stakeholders en las Funciones del Software

Para dar respuesta directa a las necesidades identificadas en el mapeo de grupos de interés, la propuesta de aplicación web de **ACME Transport S.L.** integra sus prioridades en las siguientes funcionalidades del software:

### 1. Dirección y Gerencia (Toma de decisiones y control)
* **Funcionalidad en la app:** **Dashboard Ejecutivo y Panel de Alertas**.
* **Integración de necesidades:** Visualización clara de los KPI principales de sostenibilidad (emisiones globales, costes energéticos y tasa de reciclaje). Incluye un sistema de alertas automáticas ante desviaciones presupuestarias o de emisiones para facilitar la toma de decisiones informada.

### 2. Conductores y Personal de Reparto (Eficiencia operativa en ruta)
* **Funcionalidad en la app:** **Módulo de Gestión de Flota y Consumos en Ruta**.
* **Integración de necesidades:** Registro simplificado de datos de combustible y kilometraje. Proporciona información consolidada sobre la eficiencia por ruta, ayudando a reducir el tiempo de conducción, el estrés en la entrega (*última milla*) y el gasto de combustible.

### 3. Personal de Almacén y Operaciones (Gestión de residuos y energía)
* **Funcionalidad en la app:** **Módulo de Residuos, Embalajes y Consumo Eléctrico**.
* **Integración de necesidades:** Formulario de registro rápido para el peso de materiales de embalaje utilizados y reciclados, así como lecturas de consumo energético del almacén. Permite controlar el exceso de packaging y llevar el seguimiento de la economía circular.

### 4. Clientes de Comercio Electrónico (Transparencia y valor añadido)
* **Funcionalidad en la app:** **Módulo de Transparencia e Informes por Envió**.
* **Integración de necesidades:** Cálculo y reporte de la huella de carbono asociada a cada envío individual (*última milla*). Genera informes descargables sobre el uso de embalajes sostenibles para que los clientes puedan demostrar el impacto positivo a sus compradores finales.

### 5. Organismos Reguladores y Administración Pública (Cumplimiento normativo)
* **Funcionalidad en la app:** **Módulo de Generación de Reportes ASG Veraces**.
* **Integración de necesidades:** Exportación automatizada de informes estructurados con datos inalterables y auditables de emisiones ($CO_2$) y trazabilidad de residuos, garantizando el cumplimiento de la legislación ambiental y evitando el *greenwashing*.

### 6. Proveedores y Sociedad (Impacto indirecto)
* **Funcionalidad en la app:** **Módulo de Evaluación y Criterios ASG en Cadena de Suministro**.
* **Integración de necesidades:** Seguimiento del porcentaje de proveedores con certificación ambiental y control del volumen global de emisiones reducidas en las zonas urbanas de reparto.