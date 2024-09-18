# Amenaza: Configuraciones erróneas y control inadecuado de cambios

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Administrador de sistemas sin la capacitación adecuada o con falta de supervisión.                                                                             |
| **Motivación**              | Urgencia por implementar cambios rápidamente sin seguir los procedimientos adecuados de control de cambios, o falta de conocimiento sobre buenas prácticas.    |
| **Amenaza**                 | Configuración incorrecta de un bucket de almacenamiento en la nube, lo que permite accesos no autorizados a datos confidenciales.                               |
| **Activos**                 | Datos sensibles almacenados en la nube, como información de clientes, registros financieros o datos internos críticos para la organización.                      |
| **Controles Actuales**               | Políticas de acceso y auditorías regulares que buscan mitigar el riesgo de accesos no autorizados y proteger los datos sensibles.      |
| **Nivel de Exposición**     | Elevado, ya que los activos sensibles están accesibles debido a configuraciones incorrectas y a controles insuficientes o mal aplicados.                         |
| **Probabilidad**            | Alta, ya que el administrador de sistemas no sigue los controles formales y las configuraciones erróneas son comunes en este tipo de operaciones.                 |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Pérdida de integridad en los datos almacenados en la nube. | Interrupción en las operaciones diarias debido a la filtración de datos y respuestas de emergencia. | Multas millonarias impuestas por reguladores debido al incumplimiento de normativas de protección de datos. | Pérdida de confianza en la marca, fuga de clientes y daños irreversibles a la reputación de la organización. |
| Acceso no autorizado a datos confidenciales. | Sobrecarga en los equipos de IT para resolver el incidente y contener la filtración. | Pérdidas económicas debido a la reducción de ingresos por la fuga de clientes. | Titulares en medios resaltando la falta de control de la organización sobre sus datos confidenciales. |

---

## Declaración de Riesgo

> Un pequeño error de configuración, pasado por alto por un administrador sin la supervisión adecuada, permite que todos nuestros datos confidenciales en la nube—desde la información personal de los clientes hasta los informes financieros más sensibles—queden expuestos al público. Al día siguiente, los titulares en los medios destacan la **brecha de seguridad masiva**, y nuestras acciones comienzan a desplomarse. Los reguladores se involucran rápidamente, imponiendo multas millonarias por incumplimientos normativos, mientras que las demandas de los clientes no se hacen esperar. La confianza de los inversores se desploma, los costos de recuperación son elevados, esto reducirá nuestras utilidades y afectará nuestra competitividad. La **reputación de la compañía** queda permanentemente manchada, generando una pérdida de ingresos y oportunidades comerciales. Y todo esto, porque un simple control de cambios no fue implementado correctamente.

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Política que evite la creación de buckets con mala configuración.<br>- Auditorías de permisos de acceso.<br>- Políticas estrictas de control de cambios.<br>- Habilitar logs de acceso de los buckets para detectar y responder ante amenazas.                                                                                                           |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Dejar de utilizar la nube para almacenar datos sensibles.<br>- Migrar los datos críticos a soluciones de almacenamiento internas controladas, con mayor supervisión sobre los accesos.                                                                                                                                           |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran las pérdidas en caso de una filtración.<br>- Establecer contratos con proveedores de servicios en la nube que incluyan auditorías de seguridad y cláusulas de responsabilidad mediante Acuerdos de Nivel de Servicio (SLA).                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---

