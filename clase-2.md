# Resumen del Curso: Criptografía y Seguridad Informática 02

Este curso se centra en la **gestión de riesgos y ciberseguridad**. Los temas principales incluyen la identificación de **amenazas** (intencionales y no intencionales), **vulnerabilidades** y **análisis de riesgos**. Se exploran marcos de seguridad como **ISO 27000**, **NIST**, y **CIS**, así como las técnicas para analizar y mitigar vulnerabilidades en el entorno de TI. Un aspecto clave es la categorización de las debilidades mediante estándares como el **OWASP Top Ten** y el **Common Weakness Enumeration (CWE)**.

El curso también cubre herramientas de evaluación de riesgos como **CVSS (Common Vulnerability Scoring System)** para priorizar la severidad de las amenazas y determinar el impacto potencial en los sistemas. Además, se estudian ejemplos de ataques específicos como **Buffer Overflow** y **SQL Injection**, detallando cómo estas vulnerabilidades pueden explotarse y las mejores prácticas para su mitigación.

Finalmente, se introduce el concepto de **gestión de riesgos** y sus metodologías, abarcando la valoración de activos y la selección de tratamientos de riesgos (aceptar, evitar, mitigar o transferir). Se revisan las mejores prácticas para proteger la infraestructura organizacional de ciberataques.

---

## Preguntas Tipo Examen con Respuestas

1. **¿Qué tipos de amenazas existen y cuáles son sus principales características?**
   - **Amenazas no intencionales**: Incluyen desastres naturales (terremotos, inundaciones), fallas humanas (errores y accidentes), y eventos accidentales (obras civiles).
   - **Amenazas intencionales**: Incluyen ataques dirigidos como **fraudes**, **ransomware**, **DDoS**, y **cryptojacking** realizados por actores maliciosos como hacktivistas, organizaciones criminales, o estados.

2. **Define vulnerabilidad y menciona los tipos más comunes en un entorno de seguridad informática.**
   - Una vulnerabilidad es una **debilidad** en un activo que permite la materialización de un riesgo.
   - Tipos de vulnerabilidades:
     - **Software**: Errores en el código o configuraciones inseguras.
     - **Físicas**: Falta de controles físicos o acceso no autorizado.
     - **Personales**: Falta de capacitación o errores humanos.

3. **Explica el concepto de análisis de riesgos y menciona sus componentes.**
   - El análisis de riesgos evalúa el **impacto** y la **probabilidad** de que un evento ocurra.
   - Componentes:
     - **Impacto**: Consecuencias potenciales de la materialización del riesgo.
     - **Probabilidad**: Posibilidad de que el evento ocurra.
     - **Categorías**: Análisis cualitativo y cuantitativo.

4. **¿Qué es el OWASP Top Ten y por qué es importante para la seguridad de aplicaciones?**
   - El **OWASP Top Ten** es una lista de las diez vulnerabilidades más críticas en aplicaciones web, como **Cross-site Scripting (XSS)** y **SQL Injection**.
   - Es importante porque proporciona un punto de referencia para desarrolladores y organizaciones para mejorar la seguridad de las aplicaciones web.

5. **Menciona tres vulnerabilidades del CWE Top 25 y explica en qué consisten.**
   - **CWE-787: Out-of-bounds Write**: Ocurre cuando un programa escribe datos fuera de los límites de la memoria.
   - **CWE-79: Cross-site Scripting (XSS)**: Permite a un atacante inyectar scripts maliciosos en sitios web.
   - **CWE-89: SQL Injection**: Inyección de comandos SQL a través de la entrada del usuario para ejecutar consultas no autorizadas.

6. **¿Qué es el CVSS y cómo se utiliza en el análisis de riesgos?**
   - El **Common Vulnerability Scoring System (CVSS)** es un sistema para asignar puntajes a las vulnerabilidades basado en el impacto, la complejidad de ataque y la capacidad de explotación.
   - Se utiliza para priorizar y clasificar la severidad de las vulnerabilidades y enfocar los recursos en las más críticas.

7. **Define "riesgo" según la norma ISO y menciona los cuatro métodos principales para su tratamiento.**
   - Según ISO, un riesgo es el **efecto de la incertidumbre en los objetivos**.
   - Métodos para su tratamiento:
     - **Aceptar**: Aceptar el riesgo tal como es.
     - **Evitar**: Cambiar procesos para evitar la exposición.
     - **Mitigar**: Implementar controles para reducir el impacto.
     - **Transferir**: Transferir el riesgo a terceros (por ejemplo, un seguro).

8. **Explica el modelo cuantitativo de exposición al riesgo con un ejemplo.**
   - El modelo cuantitativo se basa en el **Single Loss Expectancy (SLE)**, la **Annual Rate of Occurrence (ARO)** y la **Annual Loss Expectancy (ALE)**.
   - Ejemplo:
     - Supón que un incendio en un Data Center tiene un SLE de $500,000 y un ARO de 0.05 (1 vez cada 20 años).
     - ALE = SLE x ARO = $500,000 x 0.05 = $25,000.

9. **¿Qué es la gestión de riesgos y cuáles son sus pasos principales?**
   - La gestión de riesgos es el proceso de identificar, analizar y responder a riesgos que puedan afectar a la organización.
   - Pasos principales:
     - **Identificación**: Detectar riesgos potenciales.
     - **Evaluación**: Medir el impacto y la probabilidad.
     - **Mitigación**: Implementar controles y respuestas.
     - **Monitoreo**: Revisar continuamente el estado de los riesgos.

10. **¿Cuáles son los marcos normativos más importantes en ciberseguridad y qué regulan?**
    - **ISO 27000**: Estándar para sistemas de gestión de seguridad de la información.
    - **NIST CSF**: Marco de ciberseguridad para gestionar y reducir el riesgo.
    - **CIS 18**: Controles críticos para mejorar la defensa.
    - **GDPR**: Reglamento europeo de protección de datos personales.
    - **Ley 29773**: Protección de datos personales en Perú.

---

