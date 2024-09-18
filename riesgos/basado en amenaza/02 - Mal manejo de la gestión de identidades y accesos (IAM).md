# Amenaza: Mal manejo de la gestión de identidades y accesos (IAM)

## Factores de Riesgo y Descripción

| **Elemento/Factor**        | **Descripción**                                                                                                                                               |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Agente de amenaza**       | Empleado con acceso excesivo a sistemas sensibles o atacante externo que obtiene credenciales comprometidas.                                                   |
| **Motivación**              | Falta de control sobre los privilegios asignados, concesión de permisos excesivos, o la ausencia de revisión periódica de accesos.                             |
| **Amenaza**                 | Acceso no autorizado a sistemas sensibles mediante el mal manejo de las políticas de identidades y accesos (IAM), lo que permite a usuarios tener privilegios innecesarios o a atacantes usar credenciales comprometidas. |
| **Activos**                 | Sistemas críticos de la organización, incluyendo bases de datos con información confidencial, registros financieros y sistemas de producción.                   |
| **Controles Actuales**      | Políticas de acceso estándar y revisiones de acceso ocasionales, pero sin monitoreo continuo ni políticas estrictas de privilegios mínimos.                     |
| **Nivel de Exposición**     | Alto, debido a la falta de controles adecuados sobre la gestión de accesos, lo que permite que se mantengan permisos excesivos y cuentas inactivas sin ser desactivadas. |
| **Probabilidad**            | Alta, ya que el mal manejo de IAM es común, y los permisos no se revisan adecuadamente ni se ajustan cuando los roles cambian o los empleados dejan la empresa.  |

## Impactos

| **Impacto Técnico**         | **Impacto Operacional**                   | **Impacto Financiero**                              | **Impacto Reputacional**                          |
|----------------------------|------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Acceso no autorizado a sistemas críticos. | Interrupción en las operaciones debido a accesos no controlados, posibles sabotajes o robos de información. | Multas por incumplimiento de normativas de seguridad y pérdida de activos valiosos. | Pérdida de confianza de los clientes y socios comerciales debido a la falta de control sobre quién tiene acceso a los sistemas. |
| Escalación de privilegios para usuarios no autorizados. | Sobrecarga en los equipos de IT para auditar, corregir y ajustar los accesos y permisos. | Pérdidas económicas por robo de información valiosa o manipulación de sistemas. | Publicidad negativa que afecta la percepción de la organización como segura y confiable. |

---

## Declaración de Riesgo

> Un empleado con permisos excesivos o un atacante que consigue acceso mediante credenciales comprometidas puede manipular los sistemas críticos de la organización, accediendo a datos sensibles y comprometiendo la seguridad de la infraestructura. Esto resulta en **acceso no autorizado** a sistemas clave, pérdida de información confidencial, sanciones regulatorias por incumplimiento de normativas, y daños irreparables a la **reputación** de la compañía. Las operaciones se ven interrumpidas, los costos de recuperación aumentan, y la confianza de clientes e inversores se desploma. Todo esto ocurre debido a la falta de controles adecuados en la gestión de identidades y accesos (IAM).

---

## Estrategia de Respuesta al Riesgo

A continuación, selecciona la estrategia de respuesta que la empresa desea implementar marcando con una "X" en el campo correspondiente. Cada estrategia contempla los controles, acciones o responsables correspondientes.

| **Seleccionar (X)** | **Estrategia de Respuesta** | **Descripción**                                                                                                                                               |
|---------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ ]                 | **Mitigar**                 | Implementar controles para reducir la probabilidad o el impacto del riesgo. **Controles** a implementar: <br>- Implementar políticas de privilegio mínimo (least privilege).<br>- Revisiones periódicas de accesos y desactivación inmediata de cuentas inactivas.<br>- Implementar autenticación multifactor (MFA) y políticas de rotación de contraseñas.                                                                                                           |
| [ ]                 | **Evitar**                  | Abandonar la actividad o proceso que genera el riesgo. **Acciones a tomar**: <br>- Minimizar el uso de credenciales de alto privilegio en sistemas críticos.<br>- Migrar a sistemas donde no sea necesario gestionar identidades internas, delegando la gestión a proveedores externos con mejores controles de IAM.                                                                                                                                          |
| [ ]                 | **Transferir**              | Transferir el riesgo a un tercero o compartir la responsabilidad. **Con quién se transfiere**: <br>- Contratar seguros cibernéticos que cubran las pérdidas en caso de accesos no autorizados.<br>- Subcontratar la gestión de IAM a un proveedor especializado en identidad y gestión de accesos, con cláusulas de cumplimiento regulatorio y auditorías continuas.                                                                         |
| [ ]                 | **Aceptar**                 | La organización decide aceptar el riesgo tal como está. **Responsable de aceptar el riesgo**: <br>- El Director de Seguridad de la Información (CISO) acepta formalmente el riesgo y asume la responsabilidad de las posibles consecuencias.<br> **Rol del responsable**: <br>- El CISO es responsable de gestionar el riesgo y notificar a la alta dirección en caso de materialización.                                                |

---
