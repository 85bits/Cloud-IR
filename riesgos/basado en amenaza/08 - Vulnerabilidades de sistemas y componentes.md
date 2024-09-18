# Amenaza: Vulnerabilidades de sistemas y componentes (Kubernetes no parchado)

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Actor externo (atacante) que explota una vulnerabilidad no parchada en Kubernetes para crear cuentas no autorizadas, acceder a datos sensibles y cifrarlos.      |
| **Motivación**              | El atacante busca explotar una vulnerabilidad conocida en Kubernetes para obtener acceso no autorizado a entornos de clientes, cifrar datos y extorsionar a la organización pidiendo un rescate. |
| **Amenaza**                 | La explotación de una vulnerabilidad no parchada en Kubernetes permite al atacante crear cuentas no autorizadas en los entornos de clientes, descargar y cifrar datos sensibles y luego pedir un rescate. |
| **Activos**                 | Datos sensibles almacenados en entornos Kubernetes, incluyendo información confidencial de clientes, propiedad intelectual y sistemas críticos de la organización. |
| **Controles Actuales**      | Parches de seguridad no aplicados a tiempo en los sistemas Kubernetes, sin monitoreo avanzado o respuesta rápida ante vulnerabilidades detectadas.                 |
| **Nivel de Exposición**     | Alto, ya que la falta de parcheo oportuno de vulnerabilidades en Kubernetes deja los sistemas expuestos a actores maliciosos que pueden explotar estas brechas.    |
| **Probabilidad**            | Alta, dado que la explotación de vulnerabilidades no parchadas es una de las tácticas más comunes de los actores de amenazas, y la organización no ha aplicado los parches de seguridad en tiempo. |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Creación de cuentas no autorizadas y cifrado de datos. | Interrupciones en las operaciones debido a la pérdida de acceso a datos críticos cifrados por el atacante. | Pérdidas económicas por el pago del rescate y por las sanciones regulatorias derivadas de la exposición de datos. | Daño a la confianza de los clientes e inversores debido a la falta de gestión de vulnerabilidades críticas, lo que afecta la imagen de la empresa como un proveedor seguro. |
| Pérdida de control sobre los sistemas Kubernetes comprometidos. | Sobrecarga en los equipos de TI para restaurar los datos y asegurar los sistemas afectados. | Costos elevados para recuperar datos cifrados, restaurar sistemas y mitigar el impacto financiero a largo plazo. | Publicidad negativa y daño a la reputación de la empresa, afectando la competitividad en el mercado. |

---

## Declaración de Riesgo

> Un atacante externo explota una vulnerabilidad no parchada en Kubernetes para crear cuentas no autorizadas, descargar y cifrar datos sensibles en entornos de clientes. Posteriormente, exige un rescate para restaurar el acceso a los datos. Esto resulta en la **pérdida de acceso a sistemas críticos**, daños financieros debido al pago del rescate, multas regulatorias y la pérdida de confianza por parte de los clientes. Las operaciones se ven gravemente afectadas, y la **reputación de la empresa** sufre debido a la falta de gestión proactiva de las vulnerabilidades.

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Aplicación de parches de seguridad de forma oportuna en todos los entornos Kubernetes.<br>- Implementar monitoreo continuo de vulnerabilidades y alertas automáticas cuando se detecten fallos de seguridad.<br>- Establecer un plan de respuesta ante incidentes para reaccionar rápidamente a las vulnerabilidades explotadas.                                                                                                           |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Descontinuar el uso de entornos Kubernetes expuestos al público sin los controles de seguridad adecuados.<br>- Migrar a entornos más controlados y supervisados, con una política estricta de actualización de seguridad y revisión de vulnerabilidades.                                                                                                                                           |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran las pérdidas económicas causadas por el cifrado de datos y extorsiones.<br>- Subcontratar proveedores externos especializados en la gestión y parcheo continuo de vulnerabilidades en Kubernetes.                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---
