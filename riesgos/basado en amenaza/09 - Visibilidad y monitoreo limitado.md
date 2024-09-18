# Amenaza: Visibilidad y monitoreo limitado (Equipo DevOps deshabilita logs)

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Equipo DevOps interno que deshabilita logs y monitoreo en la nube para reducir costos en la suscripción, lo que compromete la capacidad de detectar incidentes de seguridad. |
| **Motivación**              | Reducir los costos de la suscripción en la nube al deshabilitar los logs de monitoreo y auditoría, sin evaluar los riesgos asociados a la pérdida de visibilidad sobre la actividad de los sistemas. |
| **Amenaza**                 | La falta de visibilidad y monitoreo debido a la desactivación de logs deja a la organización ciega ante posibles incidentes de seguridad y configuraciones incorrectas, exponiendo datos sensibles. |
| **Activos**                 | Información confidencial de clientes y datos sensibles que requieren monitoreo continuo para detectar accesos no autorizados, cambios en configuraciones y otros eventos críticos. |
| **Controles Actuales**      | Logs deshabilitados para ahorrar costos, con monitoreo limitado de la infraestructura en la nube y sin alertas automáticas sobre configuraciones inseguras o actividades sospechosas. |
| **Nivel de Exposición**     | Alto, ya que la falta de visibilidad y monitoreo continuo incrementa la posibilidad de que incidentes de seguridad pasen desapercibidos hasta que los daños sean severos.  |
| **Probabilidad**            | Alta, dado que el equipo DevOps no supervisa la actividad ni las configuraciones críticas, lo que permite que las brechas de seguridad y los errores humanos no se detecten a tiempo. |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Exposición de datos sensibles sin que la organización lo detecte. | Interrupciones en los servicios por incidentes de seguridad no detectados a tiempo. | Pérdidas económicas derivadas de sanciones regulatorias y compensaciones a clientes por la exposición de sus datos. | Daño significativo a la reputación de la organización, afectando la confianza de clientes y socios comerciales. |
| Falta de detección de accesos no autorizados y configuraciones incorrectas. | Sobrecarga en los equipos de TI para contener y mitigar el daño una vez que se detecta el incidente. | Costos adicionales para restaurar la seguridad y auditar los sistemas tras el incidente. | Publicidad negativa en medios y redes sociales, con una pérdida de competitividad en el mercado. |

---

## Declaración de Riesgo

> El equipo de DevOps deshabilita los logs de monitoreo en la nube para reducir costos, lo que resulta en la **pérdida de visibilidad** sobre los sistemas y actividades críticas. Esta decisión permite que datos sensibles de clientes se expongan sin que la organización lo detecte a tiempo, comprometiendo la privacidad de los clientes y generando **sanciones regulatorias** y pérdidas financieras. El incidente daña gravemente la reputación de la organización, y la confianza de los clientes e inversores disminuye debido a las malas prácticas de seguridad.

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Habilitar logs de monitoreo y auditoría en todos los entornos críticos en la nube.<br>- Implementar alertas automáticas para detectar configuraciones inseguras o accesos no autorizados.<br>- Realizar auditorías periódicas del estado de seguridad y visibilidad de los entornos.                                                                                                           |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Eliminar el uso de soluciones en la nube que dependan de suscripciones basadas en costos limitados.<br>- Migrar a soluciones internas o con proveedores que ofrezcan visibilidad continua sin restricciones de costos en el monitoreo de seguridad.                                                                                                                                           |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran las pérdidas económicas ocasionadas por la exposición de datos sensibles debido a la falta de monitoreo.<br>- Subcontratar proveedores externos especializados en monitoreo continuo y gestión de la seguridad en la nube.                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---
