# Amenaza: Recursos inseguros de terceros (LAPSUS$ hacking group)

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Grupo externo de hackers (LAPSUS$) que compromete los sistemas de la organización a través de un proveedor de servicios de terceros con acceso privilegiado.     |
| **Motivación**              | El grupo LAPSUS$ busca explotar las vulnerabilidades en los recursos de terceros para acceder a sistemas internos críticos, con el objetivo de robar información confidencial y causar daños operacionales. |
| **Amenaza**                 | Compromiso de la cuenta de un ingeniero de soporte de un tercero que permitió a LAPSUS$ acceder a los sistemas administrativos internos, datos de clientes, portales y información confidencial de la organización. |
| **Activos**                 | Sistemas internos administrativos, portales de datos, y credenciales de clientes que están vinculados con proveedores externos, lo que podría poner en riesgo la confidencialidad y disponibilidad de los datos. |
| **Controles Actuales**      | Seguridad básica en los accesos de terceros, sin monitoreo avanzado ni segmentación de acceso para limitar la exposición en caso de un compromiso.                |
| **Nivel de Exposición**     | Elevado, ya que los ingenieros de soporte de terceros tienen acceso amplio a los sistemas críticos sin un monitoreo exhaustivo, lo que permite que un ataque se mantenga durante largos periodos sin ser detectado. |
| **Probabilidad**            | Alta, dado que los terceros no tienen la misma supervisión ni las mismas políticas de seguridad que la organización, lo que incrementa el riesgo de accesos no autorizados. |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Compromiso de sistemas administrativos internos, exponiendo datos confidenciales. | Interrupciones en las operaciones de los clientes debido a accesos no autorizados a sus datos y sistemas. | Pérdidas económicas por robos de información crítica, sanciones regulatorias y demandas por incumplimientos. | Daño grave a la reputación de la empresa, lo que genera una pérdida de confianza de los clientes, socios y del mercado. |
| Acceso no autorizado a los portales de datos de clientes y a información sensible. | Sobrecarga en los equipos de seguridad para contener el incidente y mitigar los daños. | Costos elevados de recuperación y compensación a los clientes afectados por el ataque. | Mala prensa y titulares que afectan la imagen de la organización como un proveedor seguro y confiable de servicios en la nube. |

---

## Declaración de Riesgo

> Un grupo de hackers externos, como LAPSUS$, compromete la cuenta de un ingeniero de soporte de un proveedor externo, lo que les permite acceder a los sistemas administrativos internos y a la información confidencial de clientes. Esto lleva a la **exposición de datos confidenciales**, la interrupción de los servicios críticos y el robo de información valiosa. Los clientes pierden confianza en la empresa, mientras que las multas regulatorias y los costos de recuperación se disparan. La **reputación de la organización** queda severamente dañada, afectando la estabilidad financiera y la competitividad en el mercado. Todo esto ocurre debido a la falta de controles de seguridad adecuados para gestionar los accesos de terceros.

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Monitoreo continuo de las actividades de terceros con acceso a sistemas críticos.<br>- Limitar los accesos de terceros mediante segmentación y privilegio mínimo.<br>- Implementar autenticación multifactor para todos los accesos de terceros y revisar periódicamente los accesos concedidos.                                                                                                          |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Limitar o eliminar los accesos de soporte de terceros a sistemas críticos.<br>- Migrar a una solución interna para gestionar los sistemas que actualmente dependen de proveedores externos, eliminando la necesidad de dependencias de terceros.                                                                                                                                           |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran las pérdidas ocasionadas por brechas de seguridad de terceros.<br>- Subcontratar proveedores especializados en ciberseguridad para la gestión y monitoreo de los accesos de terceros, incluyendo auditorías continuas de seguridad.                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---
