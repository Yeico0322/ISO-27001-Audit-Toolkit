# 📋 Checklist de Auditoría: Controles de Acceso (Identity & Access Management)

**Objetivo:** Evaluar el diseño y la eficacia operativa de los controles de acceso lógico para garantizar que solo los usuarios autorizados tengan acceso a los activos de información.
**Referencia Normativa:** ISO/IEC 27001:2022 (Controles 5.15, 5.16, 5.18, 8.2, 8.3)

---

## 1. Gobernanza y Políticas de Acceso
- [ ] **1.1.** ¿Existe una Política de Control de Accesos documentada, aprobada por la dirección y comunicada a toda la organización?
- [ ] **1.2.** ¿La política define claramente los principios de "Necesidad de saber" (Need-to-know) y "Menor privilegio" (Least privilege)?
- [ ] **1.3.** ¿Se establecen lineamientos claros para el acceso a redes corporativas y servicios en la nube (ej. arquitecturas Zero Trust)?

## 2. Gestión del Ciclo de Vida de la Identidad
- [ ] **2.1. Alta de usuarios (Provisioning):** ¿El proceso de creación de cuentas requiere una aprobación formal del responsable de la información o jefe directo?
- [ ] **2.2. Modificación (Movimientos):** ¿Existe un proceso automatizado o manual definido para ajustar los permisos cuando un empleado cambia de rol?
- [ ] **2.3. Baja de usuarios (Deprovisioning):** ¿Los accesos se revocan inmediatamente (o en un SLA definido) tras la terminación del contrato? *Evidencia requerida: Muestra de tickets de baja vs. fechas de salida de RRHH.*
- [ ] **2.4. Cuentas genéricas:** ¿Se prohíbe el uso de cuentas compartidas o genéricas? En caso de existir excepciones, ¿están debidamente justificadas, monitoreadas y controladas?

## 3. Autenticación y Autorización Tecnológica
- [ ] **3.1. Gestión de contraseñas:** ¿Se aplican políticas de contraseñas robustas (longitud, complejidad, rotación) alineadas a las mejores prácticas actuales o directrices del NIST?
- [ ] **3.2. Autenticación Multifactor (MFA):** ¿Se exige MFA para todos los accesos remotos, plataformas en la nube y cuentas con privilegios administrativos?
- [ ] **3.3. Acceso Condicional:** ¿Existen políticas tecnológicas que restrinjan el acceso según el contexto (ej. ubicación geográfica, estado de cumplimiento del dispositivo)?

## 4. Gestión de Accesos Privilegiados (PAM)
- [ ] **4.1. Separación de roles:** ¿Los administradores utilizan cuentas estándar para tareas cotidianas y cuentas con privilegios elevados exclusivamente para labores de administración?
- [ ] **4.2. Monitoreo:** ¿Se auditan y registran (logs) las actividades realizadas por las cuentas de administrador?
- [ ] **4.3. Bóveda de contraseñas:** ¿Las credenciales de servicios críticos, bases de datos o cuentas "Break-glass" se almacenan de forma segura?

## 5. Revisión y Recertificación de Accesos
- [ ] **5.1. Revisiones periódicas:** ¿Se realizan campañas de recertificación de accesos al menos de forma anual (o con mayor frecuencia para sistemas críticos)?
- [ ] **5.2. Evidencia de revisión:** ¿Los dueños de los sistemas han documentado formalmente la aprobación o revocación de los permisos revisados?
- [ ] **5.3. Cuentas huérfanas:** ¿Se ejecutan scripts o herramientas automatizadas para detectar y deshabilitar cuentas inactivas durante más de 30/60/90 días?

---

### 📝 Notas del Auditor
*Utilice este espacio para documentar observaciones generales, nombres de las evidencias recolectadas (ej. Capturas de pantalla del Directorio Activo, reportes de Azure AD) y cualquier limitación durante la evaluación.*

- 
-
