# Resumen del Curso: Criptografía y Seguridad Informática 04

Este módulo se enfoca en la **seguridad de redes** y cubre aspectos técnicos relacionados con el **modelo OSI** y el **modelo TCP/IP**. Los objetivos principales incluyen el diseño de arquitecturas seguras, la protección de los componentes de red y la implementación de canales seguros de comunicación.

Se analizan las **capas del modelo OSI** (desde la capa física hasta la capa de aplicación), describiendo sus funciones, amenazas típicas y contramedidas específicas para cada capa. Entre las amenazas se encuentran la suplantación de direcciones MAC, ataques de inyección SQL, y ataques de denegación de servicio (DoS y DDoS).

También se presentan principios avanzados de diseño como el uso de **Zero Trust**, defensa en profundidad, y la correcta configuración de **firewalls**, **IDS/IPS** y **Network Access Control (NAC)**. Por último, se detallan conceptos de **traducción de direcciones (NAT)** y configuraciones de seguridad para redes públicas y privadas.

---

## Preguntas Tipo Examen con Respuestas

1. **¿Cuáles son los objetivos principales de la seguridad de redes?**
   - **Aplicar principios seguros de diseño** para arquitecturas de red.
   - **Asegurar los componentes de red** (routers, switches, firewalls).
   - **Diseñar canales de comunicación seguros** (VPN, IPSec).
   - **Prevenir y mitigar ataques** como sniffing, spoofing y DoS.

2. **¿Qué es el modelo OSI y cuáles son sus capas?**
   - El modelo OSI (Interconexión de Sistemas Abiertos) define cómo se comunican las redes mediante siete capas:
     1. **Capa 1 - Física**: Transmisión de bits (hardware).
     2. **Capa 2 - Enlace de datos**: Mueve frames entre dispositivos.
     3. **Capa 3 - Red**: Mueve paquetes entre redes.
     4. **Capa 4 - Transporte**: Proporciona transferencia confiable de datos.
     5. **Capa 5 - Sesión**: Establece, gestiona y termina sesiones.
     6. **Capa 6 - Presentación**: Formatea, cifra y serializa los datos.
     7. **Capa 7 - Aplicación**: Interactúa directamente con las aplicaciones del usuario.

3. **¿Cuál es la principal diferencia entre el modelo OSI y el modelo TCP/IP?**
   - Aunque ambos modelos cumplen funciones similares, el **modelo TCP/IP** tiene menos capas, combinando algunas del modelo OSI:
     - **Capa de Aplicación (equivalente a las capas 5, 6 y 7 de OSI)**.
     - **Capa de Transporte**.
     - **Capa de Internet (equivalente a la capa de red)**.
     - **Capa de Acceso a la red (equivalente a las capas 1 y 2 de OSI)**.

4. **Describe las amenazas comunes en la Capa 2 (Enlace de datos) y sus contramedidas.**
   - **Amenazas**:
     - Suplantación de direcciones MAC.
     - Tormentas de transmisión y ataques ARP.
     - Ataques DHCP y VLAN inseguras.
   - **Contramedidas**:
     - Configuración segura de la NIC.
     - Monitoreo de ARP y DHCP.
     - Uso adecuado de VLAN y detección de intrusiones en capa 2.

5. **¿Qué es un ataque de enrutamiento en la Capa 3 y cómo se mitiga?**
   - Un ataque de enrutamiento, como el **RIP Spoofing**, implica manipular las tablas de enrutamiento para redirigir el tráfico.
   - **Contramedidas**:
     - Configurar adecuadamente las ACL (Listas de Control de Acceso).
     - Habilitar autenticación de protocolos de enrutamiento.
     - Monitorear el tráfico de red para detectar rutas sospechosas.

6. **¿Qué diferencias hay entre TCP y UDP en la Capa 4?**
   - **TCP**: Protocolo orientado a la conexión que garantiza la entrega de datos mediante retransmisión y secuenciación.
   - **UDP**: Protocolo sin conexión, no garantiza la entrega ni retransmisión, pero es más rápido.

7. **Explica los principios de diseño de seguridad: Mínimo privilegio y Confianza cero.**
   - **Mínimo privilegio**: Cada usuario o sistema debe tener solo los permisos mínimos necesarios para realizar su tarea.
   - **Confianza cero (Zero Trust)**: Asume que ninguna entidad dentro o fuera de la red es confiable. Requiere autenticación continua y verificación de cada solicitud.

8. **¿Qué es NAT y qué tipos existen?**
   - **NAT (Network Address Translation)** traduce direcciones IP privadas a IP públicas, permitiendo a varios dispositivos compartir una sola dirección pública.
   - **Tipos de NAT**:
     - **NAT Estática**: Una IP privada se mapea siempre a la misma IP pública.
     - **NAT Dinámica**: Una IP privada se mapea a una IP pública de un grupo predefinido.
     - **NAT de Sobrecarga (PAT)**: Se usa el puerto para distinguir conexiones, permitiendo que múltiples dispositivos usen una sola IP pública.

9. **¿Cuáles son las funciones de los firewalls y las diferencias entre firewalls tradicionales y NGFW?**
   - **Firewalls tradicionales**: Filtran el tráfico basándose en direcciones IP, puertos y protocolos.
   - **Next Generation Firewalls (NGFW)**: Proporcionan inspección profunda de paquetes, control de aplicaciones y protección avanzada contra amenazas (por ejemplo, bloqueo de malware).

10. **Describe el papel de IDS/IPS en la seguridad de red.**
    - **IDS (Sistema de Detección de Intrusiones)**: Monitorea el tráfico para detectar actividades sospechosas y generar alertas.
    - **IPS (Sistema de Prevención de Intrusiones)**: Además de detectar, previene los ataques mediante la implementación de políticas que bloquean el tráfico malicioso.

---

