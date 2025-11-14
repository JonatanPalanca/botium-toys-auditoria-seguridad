# 🛡️ Auditoría Interna de Seguridad – Botium Toys  
**Curso: Certificado Profesional Google Ciberseguridad**  
**Framework: NIST Cybersecurity Framework (CSF)**

---

# 1. Introducción  
El propósito de esta auditoría es evaluar el estado actual de seguridad de **Botium Toys**, una empresa dedicada al diseño y venta de juguetes con operaciones físicas y en línea.  
El departamento de TI solicitó este análisis para:

- Identificar vulnerabilidades  
- Evaluar riesgos  
- Revisar controles existentes  
- Cumplir estándares (PCI DSS, GDPR)  

---

# 2. Alcance  

Incluye:

- Red interna  
- Sitio web y e-commerce  
- Procesamiento de pagos  
- Gestión de accesos  
- Servidores y base de datos  
- Infraestructura física  
- Backups  
- Políticas y procedimientos de TI  

---

# 3. Objetivos de la auditoría  

- Identificar amenazas y vulnerabilidades  
- Evaluar riesgos (probabilidad × impacto)  
- Verificar controles existentes  
- Comparar con NIST CSF  
- Proponer recomendaciones inmediatas  

---

# 4. Activos Críticos Identificados

| Activo | Descripción |
|--------|-------------|
| Base de datos | Contiene información de clientes, pagos y transacciones |
| Sitio web / e-commerce | Canal principal de ventas |
| Servidores | Procesos internos y tienda online |
| Terminales POS | Realizan pagos en tienda |
| Red interna | Comunicación y operaciones |
| Personal TI | Configuración y seguridad |
| Información financiera | Datos-sensibles |

---

# 5. Amenazas Identificadas

| Amenaza | Descripción |
|--------|-------------|
| Malware | Infecciones por phishing o descargas |
| Acceso no autorizado | Interno o externo |
| Ingeniería social | Ataques a empleados |
| Ataques web | SQLi, XSS, CSRF |
| Fuga de datos | Robo o error humano |

---

# 6. Vulnerabilidades Detectadas

- No existe política formal de contraseñas  
- No hay monitoreo ni logs centralizados  
- Backups incompletos o no verificados  
- Falta de parches de seguridad  
- Firewall básico sin reglas avanzadas  
- Falta de IDS/IPS  
- Permisos excesivos en usuarios  
- No hay plan de respuesta a incidentes  
- Seguridad física mínima  

---

# 7. Evaluación de Riesgos

**Fórmula:** Riesgo = Probabilidad (1–5) × Impacto (1–5)

| Riesgo | Prob | Impacto | Nivel | Clasificación |
|--------|------|---------|--------|---------------|
| Robo de datos de clientes | 4 | 5 | 20 | ALTO |
| Caída del sitio web | 3 | 5 | 15 | ALTO |
| Malware en servidores | 4 | 4 | 16 | ALTO |
| Procesamiento inseguro de pagos | 4 | 5 | 20 | ALTO |
| Fuga interna | 3 | 4 | 12 | MEDIO |
| Falta de backups | 3 | 5 | 15 | ALTO |

---

# 8. Checklist de Controles (resumen)

- Control de acceso: ❌ No cumple  
- Firewall: ❌ Parcial  
- Gestión de parches: ❌ No aplicada  
- Backups: ❌ Incompleto  
- Inventario de activos: ✔ Parcial  
- Registros/Monitoreo: ❌ No implementado  
- Cumplimiento PCI DSS: ❌ Incompleto  
- Cumplimiento GDPR: ❌ Parcial  

---

# 9. Controles recomendados

## 🔐 Accesos
- MFA obligatorio  
- Contraseñas seguras  
- Revisión periódica de permisos  

## 🖥️ Infraestructura
- Parches automáticos  
- Hardening  
- Implementar IDS/IPS  

## 📦 Backups
- Copias automáticas diarias  
- Pruebas mensuales  
- Copias externas cifradas  

## 🌐 Sitio web
- WAF  
- Escaneos mensuales de vulnerabilidades  
- Seguridad en API  

## 🧾 Cumplimiento
- Políticas documentadas  
- Capacitación a empleados  
- Plan de respuesta a incidentes  

---

# 10. Riesgo Residual

| Riesgo | Antes | Después | Estado |
|--------|--------|----------|--------|
| Robo de datos | 20 | 8 | Reducido |
| Malware | 16 | 6 | Reducido |
| Caída del sitio | 15 | 7 | Reducido |

---

# 11. Conclusión  
Botium Toys presenta vulnerabilidades críticas que deben tratarse con urgencia.  
La aplicación de los controles recomendados reducirá significativamente riesgos operativos, legales y financieros.

---

# 12. Autor  
**Jonatan Palanca** – Auditoría Interna (Botium Toys)  
Curso: Google Cybersecurity Professional Certificate
