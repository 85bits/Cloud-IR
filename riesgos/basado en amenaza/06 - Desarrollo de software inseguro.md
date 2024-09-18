# Amenaza: Desarrollo de software inseguro (Ingeniero DevOps)

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Ingeniero DevOps interno que introduce vulnerabilidades en el código o utiliza prácticas de desarrollo inseguras en el ciclo de vida del software.                |
| **Motivación**              | Presión por entregar software rápidamente sin seguir los procedimientos de seguridad adecuados o falta de capacitación sobre prácticas de desarrollo seguro.     |
| **Amenaza**                 | Introducción de código inseguro o vulnerabilidades en aplicaciones críticas debido a la falta de revisiones de seguridad, lo que expone la organización a ataques y fallos en producción. |
| **Activos**                 | Aplicaciones críticas y bases de datos que contienen información sensible de clientes, así como sistemas de producción que son clave para las operaciones del negocio. |
| **Controles Actuales**      | Revisión ocasional del código y tests automáticos, pero sin auditorías continuas ni herramientas robustas de seguridad para identificar vulnerabilidades en el desarrollo. |
| **Nivel de Exposición**     | Alto, ya que las prácticas de desarrollo inseguro pueden pasar desapercibidas, dejando vulnerabilidades críticas en los sistemas en producción.                    |
| **Probabilidad**            | Alta, dado que la presión por entregar software rápidamente sin las revisiones adecuadas y la falta de capacitación incrementan el riesgo de fallos de seguridad en el código. |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Vulnerabilidades en aplicaciones en producción que permiten accesos no autorizados. | Interrupciones en las operaciones debido a fallos de seguridad en los sistemas, afectando la disponibilidad de los servicios. | Costos asociados a la remediación de vulnerabilidades, multas por incumplimientos regulatorios, y pérdida de contratos. | Daño a la confianza de los clientes e inversores debido a las fallas de seguridad en los productos de la organización. |
| Inyecciones de código malicioso que comprometen la integridad del sistema. | Sobrecarga en los equipos de desarrollo y operaciones para mitigar las vulnerabilidades y corregir los errores de seguridad. | Pérdidas financieras por pérdida de clientes y por la necesidad de soluciones urgentes de seguridad. | Mala prensa y daño a la imagen de la empresa como proveedor confiable de soluciones tecnológicas seguras. |

---

## Declaración de Riesgo

> Un Ingeniero DevOps introduce sin querer vulnerabilidades críticas en el código al priorizar la rapidez sobre la seguridad. Estas vulnerabilidades pasan desapercibidas y llegan a producción, lo que permite que actores maliciosos exploten fallos en el sistema para acceder a información confidencial o interrumpir los servicios. Las operaciones de la empresa se ven afectadas, los costos de recuperación aumentan, y la confianza de los clientes disminuye. Las sanciones regulatorias no se hacen esperar, mientras que la **reputación de la empresa** queda severamente dañada debido a fallos de seguridad evitables en el desarrollo del software.

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Implementar herramientas de seguridad en el ciclo de vida del desarrollo (DevSecOps).<br>- Capacitar a los ingenieros DevOps sobre prácticas seguras de desarrollo y revisión de código.<br>- Auditorías frecuentes del código fuente y pruebas continuas de seguridad en aplicaciones.                                                                                                           |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Evitar la implementación de código no revisado por pares y establecer criterios estrictos de aprobación de código.<br>- Migrar a procesos automatizados que incluyan revisiones de seguridad obligatorias antes de pasar el software a producción.                                                                                                                                           |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran los daños ocasionados por vulnerabilidades en el software.<br>- Subcontratar proveedores externos especializados en pruebas de penetración y auditoría de seguridad para el software antes de su despliegue en producción.                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---
