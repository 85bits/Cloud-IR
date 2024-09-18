# Amenaza: Divulgación accidental de datos en la nube

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Empleado interno que configura incorrectamente un bucket en la nube (S3), lo que expone datos sensibles a accesos públicos no autorizados.                      |
| **Motivación**              | Falta de capacitación adecuada en la gestión de configuraciones de seguridad en la nube, lo que lleva a errores no intencionados que resultan en la divulgación de datos sensibles. |
| **Amenaza**                 | La mala configuración de un bucket S3 en la nube expone 48,000 registros, incluyendo 4,600 pasaportes y 12,000 tarjetas de crédito, permitiendo accesos no autorizados a estos datos. |
| **Activos**                 | Información confidencial almacenada en la nube, como pasaportes y números de tarjetas de crédito, que son altamente sensibles y están sujetos a regulaciones estrictas de protección de datos. |
| **Controles Actuales**      | Controles de seguridad básicos en la configuración de la nube, sin revisiones exhaustivas o auditorías continuas para detectar configuraciones incorrectas.       |
| **Nivel de Exposición**     | Alto, ya que los datos confidenciales están accesibles a cualquier persona con el enlace directo al bucket debido a la configuración incorrecta.                 |
| **Probabilidad**            | Alta, ya que la falta de revisiones automáticas y la supervisión insuficiente sobre las configuraciones de seguridad en la nube aumentan la probabilidad de errores humanos. |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Exposición de datos personales, como pasaportes y tarjetas de crédito. | Interrupciones en los servicios debido a la gestión de incidentes y la respuesta a la filtración de datos. | Multas regulatorias significativas por incumplimientos de leyes de protección de datos (como GDPR o PCI DSS) y costos de recuperación. | Daño a la reputación de la organización por la falta de control sobre los datos sensibles, lo que afecta la confianza de clientes e inversores. |
| Pérdida de control sobre datos confidenciales en la nube. | Sobrecarga en los equipos de seguridad y TI para contener la filtración y corregir las configuraciones. | Costos asociados con demandas legales de los afectados y la compensación por los daños sufridos. | Publicidad negativa y mala imagen en los medios, lo que genera una pérdida de clientes y oportunidades comerciales. |

---

## Declaración de Riesgo

> Un empleado interno configura incorrectamente un bucket S3 en la nube, lo que provoca la exposición de 48,000 registros, incluyendo 4,600 pasaportes y 12,000 tarjetas de crédito, a accesos públicos no autorizados. Esto resulta en una **violación masiva de datos**, multas regulatorias significativas y daños a la reputación de la organización. La confianza de los clientes se ve gravemente afectada, mientras que los costos de recuperación y las demandas legales aumentan considerablemente. La **reputación de la organización** queda dañada debido a la divulgación de datos altamente sensibles.

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Implementar revisiones automáticas de configuraciones de seguridad en los buckets S3.<br>- Capacitar al personal en buenas prácticas de seguridad en la nube.<br>- Activar auditorías continuas y alertas de seguridad cuando se detecten configuraciones incorrectas.                                                                                                           |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Eliminar el uso de buckets S3 públicos y migrar a soluciones internas más controladas.<br>- Limitar el acceso a datos sensibles a entornos locales o soluciones en la nube con mayores garantías de control y visibilidad.                                                                                                                                           |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran las pérdidas económicas por filtraciones de datos sensibles.<br>- Subcontratar proveedores de ciberseguridad especializados para realizar auditorías periódicas y garantizar la seguridad de los datos en la nube.                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---
