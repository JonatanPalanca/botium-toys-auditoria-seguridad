# 🛡️ Auditoría Interna de Seguridad – Botium Toys  
**Curso: Certificado Profesional Google Ciberseguridad**  
**Auditoría Interna – NIST CSF**

---

# 1. Introducción  
Botium Toys es una empresa pequeña dedicada al diseño y venta de juguetes, con presencia física y un e-commerce que crece rápidamente.  
El departamento de TI solicitó una auditoría interna para:

- Evaluar el estado actual de seguridad  
- Identificar vulnerabilidades y riesgos críticos  
- Prepararse para cumplir regulaciones (PCI DSS, GDPR)  
- Proteger sus activos tecnológicos  

---

# 2. Alcance de la auditoría  
Incluye:

- Servidores internos  
- Sitio web y plataforma de ventas  
- Procesamiento de pagos  
- Red interna y Wi-Fi  
- Control de accesos  
- Políticas de TI  
- Backups y recuperación  
- Seguridad física  

---

# 3. Objetivos  
- Identificar amenazas y vulnerabilidades  
- Evaluar riesgos  
- Verificar controles existentes  
- Comparar con estándares NIST CSF  
- Emitir recomendaciones  

---

# 4. Activos Críticos Identificados

| Activo | Descripción |
|--------|-------------|
| Base de datos | Información de clientes y transacciones |
| Sitio web e-commerce | Punto principal de ventas |
| Servidores | Procesos internos y tienda online |
| Red interna | Comunicación interna |
| Personal TI | Administración de seguridad |
| Terminales POS | Procesan pagos |
| Información financiera | Datos sensibles |

---

# 5. Amenazas Identificadas

| Amenaza | Descripción |
|--------|-------------|
| Malware | Infección por phishing, descargas o accesos inseguros |
| Acceso no autorizado | Interno o externo |
| Ingeniería social | Ataques a empleados |
| Ataques web | SQL Injection, XSS, CSRF |
| Fuga de datos | Robo o exposición accidental |

---

# 6. Vulnerabilidades Detectadas

- No existe política formal de contraseñas  
- No se aplican parches regularmente  
- No hay registro centralizado de logs  
- Backups no documentados  
- Firewall básico y mal configurado  
- Falta de monitoreo del sitio web  
- No existe plan de respuesta a incidentes  
- Seguridad física mínima  
- Usuarios con permisos innecesarios  

---

# 7. Evaluación de Riesgos  
**Método:** Riesgo = Probabilidad × Impacto (1 a 5)

| Riesgo | Prob | Impacto | Nivel |
|--------|------|---------|-------|
| Robo de datos de clientes | 4 | 5 | 20 (ALTO) |
| Caída del sitio web | 3 | 5 | 15 (ALTO) |
| Malware en servidores | 4 | 4 | 16 (ALTO) |
| Procesamiento inseguro de pagos | 4 | 5 | 20 (ALTO) |
| Fuga interna de información | 3 | 4 | 12 (MEDIO) |
| Falta de backups | 3 | 5 | 15 (ALTO) |

---

# 8. Checklist de Controles (resumen)
- Control de acceso: ❌ No cumple  
- Firewall: ❌ Parcial  
- Gestión de parches: ❌ Insuficiente  
- Backups: ❌ Incompleto  
- Seguridad física: ❌ Débil  
- Inventario de activos: ✔ Parcial  
- Registros y monitoreo: ❌ No implementado  
- Cumplimiento PCI DSS: ❌ No  
- Cumplimiento GDPR: ❌ No

---

# 9. Controles recomendados

## 🔐 Accesos
- Implementar MFA  
- Política de contraseñas fuertes  
- Revisar permisos cada 3 meses  

## 🖥️ Infraestructura
- Actualizaciones automáticas  
- Hardening de servidores  
- IDS/IPS recomendado  

## 📦 Backups
- Copias diarias  
- Pruebas de restauración mensuales  
- Almacenamiento fuera del sitio  

## 🌐 Sitio web
- WAF (Web Application Firewall)  
- Escaneo automático de vulnerabilidades  
- Revisar API y bases de datos  

## 🧾 Cumplimiento
- Documentar políticas  
- Entrenamiento para empleados (phishing)  
- Plan de respuesta a incidentes  

---

# 10. Riesgo Residual
Tras implementar controles:

| Riesgo | Antes | Después | Estado |
|--------|--------|----------|--------|
| Robo de datos | 20 | 8 | Reducido |
| Malware | 16 | 6 | Reducido |
| Caída del sitio | 15 | 7 | Reducido |

---

# 11. Conclusión  
La empresa presenta **varias vulnerabilidades críticas** que deben corregirse de inmediato.  
La aplicación de los controles recomendados reducirá significativamente los riesgos operativos, legales y financieros.

---

# 12. Autor  
**Tu nombre** – Auditoría Interna (Botium Toys)  
Curso: Google Cybersecurity Professional Certificate
