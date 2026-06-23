# 📊 Matriz de Evaluación y Tratamiento de Riesgos (ISO 27001)

**Objetivo:** Identificar, analizar, evaluar y tratar los riesgos de seguridad de la información asociados a los activos y procesos críticos de la organización.

---

## 1. Criterios de Evaluación

El nivel de riesgo se calcula multiplicando la **Probabilidad** por el **Impacto** (Riesgo Inhente = P x I).

### Probabilidad (P)
* **1 - Rara vez:** Es muy poco probable que la amenaza se materialice.
* **2 - Posible:** Podría materializarse en algún momento (ej. 1 vez al año).
* **3 - Frecuente:** Es muy probable que suceda a corto plazo.

### Impacto (I)
*(Evaluado sobre la Confidencialidad, Integridad y Disponibilidad)*
* **1 - Bajo:** Afectación operativa mínima; impacto financiero insignificante.
* **2 - Medio:** Interrupción notable de operaciones; daño reputacional temporal.
* **3 - Alto:** Paro total de operaciones críticas; impacto legal/regulatorio severo.

### Nivel de Riesgo (P x I)
* **1 a 2:** Riesgo Bajo (Aceptable)
* **3 a 4:** Riesgo Medio (Requiere monitoreo y controles)
* **6 a 9:** Riesgo Alto (Inaceptable - Acción inmediata requerida)

---

## 2. Registro y Tratamiento de Riesgos

| ID | Activo / Proceso | Amenaza | Vulnerabilidad | P | I | Riesgo Inherente | Tratamiento | Controles Propuestos (Anexo A) | Riesgo Residual | Responsable |
| :--- | :--- | :--- | :--- | :---: | :---: | :---: | :--- | :--- | :---: | :--- |
| RSK-01 | Servidor de BD Core | Ransomware / Malware | Falta de parches de seguridad (OS) | 3 | 3 | **9 (Alto)** | Mitigar | A.8.8 Gestión de vulnerabilidades, A.8.13 Copias de seguridad | 3 (Medio) | Líder de TI |
| RSK-02 | Portal VPN / Nube | Acceso no autorizado | Cuentas sin MFA habilitado | 2 | 3 | **6 (Alto)** | Mitigar | A.5.17 Información de autenticación, A.8.5 Autenticación segura | 2 (Bajo) | Admin Nube |
| RSK-03 | Red Wi-Fi Invitados | Fuga de información | Red no segmentada de la red corporativa | 2 | 2 | **4 (Medio)** | Mitigar | A.8.22 Separación de redes | 2 (Bajo) | Redes |

---
*Nota: Esta matriz es un modelo técnico. Los criterios de impacto deben alinearse siempre con el apetito de riesgo definido por la alta dirección.*
