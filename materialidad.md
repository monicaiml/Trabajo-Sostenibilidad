# Análisis de Materialidad y Stakeholders

## 1. Mapeo de Stakeholders y Funciones de la Aplicación Web

Para responder a las necesidades de **ACME Transport S.L.**, se relacionan los principales grupos de interés con sus necesidades prioritarias y la función concreta que les ofrece la aplicación web:

| Grupo de Interés | Tipo | Necesidad Principal | Función en la Aplicación Web |
| :--- | :--- | :--- | :--- |
| **Dirección y Gerencia** | Interno | Controlar KPI globales y reducir costes energéticos. | **Dashboard Ejecutivo:** Vista general con gráficos de emisiones y alertas de consumo. |
| **Conductores y Reparto** | Interno | Optimizar rutas y reducir consumo en entregas. | **Módulo de Flota:** Registro de consumos e indicadores de eficiencia en la *última milla*. |
| **Personal de Almacén** | Interno | Reducir el uso de embalajes y facilitar el reciclaje. | **Módulo de Residuos:** Registro de peso de materiales de packaging y tasa de reciclaje. |
| **Clientes (e-Commerce)** | Externo | Conocer el impacto ambiental de sus envíos. | **Módulo de Impacto:** Certificados de $CO_2$ y reporte de packaging ecológico por paquete. |
| **Organismos Reguladores** | Externo | Disponer de datos veraces y auditables. | **Módulo de Reporte ASG:** Exportación de informes oficiales para auditorías e inspecciones. |
| **Proveedores y Comunidad** | Externo | Fomentar la sostenibilidad y reducir la contaminación. | **Módulo de Cadena de Suministro:** Seguimiento de criterios ASG en compras y reparto urbano. |

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