# Amenaza: Interfaces y APIs inseguras

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Actor externo, como ciberdelincuentes que buscan explotar vulnerabilidades en APIs para acceder a datos o sistemas sensibles.                                   |
| **Motivación**              | Los ciberdelincuentes buscan vulnerabilidades en las interfaces y APIs mal configuradas para explotar servicios críticos y acceder a información confidencial.   |
| **Amenaza**                 | Vulnerabilidades en APIs o interfaces inseguras que permiten la manipulación de datos, ataques de inyección, o eludir controles de autenticación para acceder a sistemas críticos. |
| **Activos**                 | Aplicaciones y bases de datos conectadas a APIs, que pueden incluir información confidencial de clientes, registros financieros y otros sistemas de producción.   |
| **Controles Actuales**      | Autenticación básica y controles de seguridad mínimos para las APIs, sin implementación de seguridad avanzada o revisiones regulares de vulnerabilidades.        |
| **Nivel de Exposición**     | Alto, ya que las APIs expuestas públicamente sin la debida seguridad incrementan el riesgo de que actores externos exploten vulnerabilidades.                     |
| **Probabilidad**            | Alta, dado que las APIs no están completamente protegidas y son un objetivo común de ataques por parte de actores maliciosos externos.                           |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Compromiso de la integridad de las aplicaciones conectadas a las APIs. | Interrupción de servicios y posible pérdida de control de los sistemas conectados. | Pérdidas económicas significativas debido a la exposición de datos sensibles y multas por incumplimientos regulatorios. | Daño a la imagen pública de la organización debido a brechas de seguridad visibles, afectando la confianza de clientes y socios. |
| Explotación de vulnerabilidades en APIs para obtener acceso no autorizado a sistemas. | Sobrecarga en los equipos de desarrollo e IT para mitigar el ataque y solucionar las vulnerabilidades. | Costos elevados de remediación y compensaciones por el robo de datos de clientes. | Reputación dañada ante el público y la industria, lo que genera una pérdida de competitividad y reducción de ingresos. |

---

## Declaración de Riesgo

> Un actor externo aprovecha vulnerabilidades en nuestras APIs inseguras para manipular datos o acceder a sistemas críticos. Esto resulta en la **exposición de información confidencial**, la pérdida de control sobre aplicaciones críticas y sanciones por incumplimientos regulatorios. Además, las operaciones de la organización se ven interrumpidas, generando altos costos de recuperación. La confianza de los clientes se ve afectada gravemente, y la **reputación de la empresa** queda dañada de forma permanente. Todo esto debido a la falta de controles de seguridad robustos en nuestras interfaces y APIs expuestas.

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Implementar autenticación avanzada y cifrado de tráfico en APIs.<br>- Realizar pruebas regulares de penetración y revisiones de seguridad de las APIs.<br>- Limitar el acceso a las APIs mediante listas de control de acceso (ACL).                                                                                                          |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Dejar de exponer APIs directamente al público y utilizar soluciones internas para la comunicación de sistemas sensibles.<br>- Migrar a APIs privadas o de acceso restringido mediante redes internas seguras.                                                                                                                                           |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran las pérdidas ocasionadas por vulnerabilidades en APIs.<br>- Utilizar proveedores externos especializados en seguridad de APIs, que ofrezcan soporte y monitoreo continuo mediante contratos de nivel de servicio (SLA).                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---
