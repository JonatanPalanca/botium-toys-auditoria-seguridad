# Auditoría Interna de Seguridad – Botium Toys
Curso: Certificado Profesional Google Ciberseguridad  
Framework utilizado: NIST Cybersecurity Framework (CSF)

---

# 1. Introducción
El objetivo de esta auditoría es evaluar el estado actual de seguridad de Botium Toys, una empresa dedicada al diseño y venta de juguetes con operaciones físicas y en línea. El departamento de TI solicitó este análisis para:

- Identificar vulnerabilidades  
- Evaluar riesgos  
- Revisar controles existentes  
- Verificar cumplimiento (PCI DSS, GDPR)

---

# 2. Alcance
La auditoría abarca:

- Red interna  
- Sitio web y comercio electrónico  
- Infraestructura física  
- Procesamiento de pagos  
- Gestión de accesos  
- Servidores y base de datos  
- Copias de seguridad  
- Políticas y procedimientos de TI  

---

# 3. Objetivos de la auditoría

- Detectar amenazas y vulnerabilidades  
- Evaluar riesgos mediante la fórmula: Riesgo = Probabilidad × Impacto  
- Validar controles actuales  
- Comparar el estado de seguridad con NIST CSF  
- Proponer mejoras y recomendaciones inmediatas

---

# 4. Activos Críticos Identificados

| Activo                 | Descripción                                                   |
|------------------------|---------------------------------------------------------------|
| Base de datos          | Contiene información de clientes, pagos y transacciones       |
| Sitio web / e-commerce | Principal canal de ventas                                     |
| Servidores             | Soportan procesos internos y tienda online                    |
| Terminales POS         | Procesan pagos presenciales                                   |
| Red interna            | Comunicación y operaciones internas                           |
| Personal TI            | Configuración, mantenimiento y seguridad                      |
| Información financiera | Datos altamente sensibles                                     |

---

# 5. Amenazas Identificadas

| Amenaza                | Descripción                                   |
|------------------------|-----------------------------------------------|
| Malware                | Infecciones por phishing o descargas          |
| Acceso no autorizado   | Interno o externo                             |
| Ingeniería social      | Manipulación psicológica de empleados         |
| Ataques web            | SQLi, XSS, CSRF                               |
| Fuga de datos          | Robo de información o error humano            |

---

# 6. Vulnerabilidades Detectadas

- Falta de política formal de contraseñas  
- Ausencia de monitoreo y registros centralizados  
- Copias de seguridad incompletas o no verificadas  
- Parches de seguridad desactualizados  
- Firewall básico sin reglas avanzadas  
- No existe un IDS/IPS  
- Permisos excesivos de usuarios  
- No existe un plan de respuesta a incidentes  
- Seguridad física insuficiente  

---

# 7. Evaluación de Riesgos

**Fórmula:** Riesgo = Probabilidad (1–5) × Impacto (1–5)

| Riesgo                            | Prob | Impacto | Nivel | Clasificación |
|-----------------------------------|------|---------|-------|---------------|
| Robo de datos de clientes         | 4    | 5       | 20    | Alto          |
| Caída del sitio web               | 3    | 5       | 15    | Alto          |
| Malware en servidores             | 4    | 4       | 16    | Alto          |
| Procesamiento inseguro de pagos   | 4    | 5       | 20    | Alto          |
| Fuga interna                      | 3    | 4       | 12    | Medio         |
| Falta de copias de seguridad      | 3    | 5       | 15    | Alto          |

---

# 8. Estado de Controles (resumen)

- Control de accesos: No cumple  
- Firewall: Parcial  
- Gestión de parches: No aplicada  
- Copias de seguridad: Incompletas  
- Inventario de activos: Parcial  
- Monitoreo y registros: No implementado  
- Cumplimiento PCI DSS: Incompleto  
- Cumplimiento GDPR: Parcial  

---

# 9. Controles Recomendados

## Accesos
- Implementar MFA  
- Políticas sólidas de contraseñas  
- Revisión periódica de permisos  

## Infraestructura
- Actualizaciones automáticas  
- Hardening de servidores  
- Implementar IDS/IPS  

## Copias de Seguridad
- Copias diarias  
- Verificación mensual  
- Copias externas cifradas  

## Sitio Web
- WAF  
- Escaneo mensual de vulnerabilidades  
- Fortalecimiento de API  

## Cumplimiento
- Políticas documentadas  
- Capacitación a todo el personal  
- Plan formal de respuesta a incidentes  

---

# 10. Riesgo Residual

| Riesgo               | Antes | Después | Estado   |
|---------------------|--------|---------|----------|
| Robo de datos       | 20     | 8       | Reducido |
| Malware             | 16     | 6       | Reducido |
| Caída del sitio web | 15     | 7       | Reducido |

---

# 11. Conclusión
Botium Toys presenta vulnerabilidades críticas que requieren atención inmediata.  
La implementación de los controles recomendados reducirá significativamente los riesgos operativos, financieros y legales.

---

# 12. Autor
Jonatan Palanca – Auditoría Interna (Botium Toys)  
Certificado Profesional Google Cybersecurity
