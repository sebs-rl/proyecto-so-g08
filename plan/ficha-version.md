# Ficha de verificación de versión - Grupo 8

## Distribuciones:

### Pop!_OS (VM gráfica)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Pop!_OS 24.04 LTS. Su actualización fue anunciada el 3 de marzo de 2026. | https://blog.system76.com/blog/post/pop-24-04-lts-upgrade |
| Hasta cuándo recibe actualizaciones de seguridad | La fecha de referencia registrada para Pop!_OS 24.04 LTS es el 31 de mayo de 2029. El mantenimiento de la versión depende también del lanzamiento de la siguiente versión LTS. | https://endoflife.date/pop-os |
| Requisitos de hardware y si funciona en VirtualBox | Requiere procesador de 64 bits, mínimo 4 GB de RAM y 20 GB de almacenamiento. Puede utilizarse como sistema invitado en VirtualBox. | https://support.system76.com/support/install-pop |
| ¿El instalador permite particionado manual? | Sí. El instalador ofrece la opción Avanzada, que permite configurar las particiones. | https://support.system76.com/support/install-pop |
| Guía oficial para instalar Docker Engine en esa familia | Pop!_OS está basado en Ubuntu. Se puede consultar la guía de Docker para Ubuntu, aunque Docker aclara que la instalación en distribuciones derivadas no está oficialmente soportada. | https://docs.docker.com/engine/install/ubuntu/ |
| Imagen base del Dockerfile para esa versión | No aplica. Pop!_OS es la distribución de la máquina virtual gráfica; la imagen base asignada al grupo para Docker es Debian. | https://hub.docker.com/_/debian |

### AlmaLinux (VM de consola)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | AlmaLinux OS 10.3, publicada el 16 de noviembre de 2026. | https://wiki.almalinux.org/release-notes/ |
| Hasta cuándo recibe actualizaciones de seguridad | AlmaLinux 10 recibe soporte activo hasta el 31 de mayo de 2030 y actualizaciones de seguridad hasta el 31 de mayo de 2035. Las versiones menores, como 10.3, dejan de recibir soporte cuando se publica la siguiente versión menor. | https://wiki.almalinux.org/release-notes/ |
| Requisitos de hardware y si funciona en VirtualBox | Requiere como mínimo 1.5 GB de RAM y 10 GB de almacenamiento. Es compatible con procesadores Intel/AMD de 64 bits y puede instalarse en VirtualBox. | https://wiki.almalinux.org/documentation/installation-guide.html |
| ¿El instalador permite particionado manual? | Sí. El instalador Anaconda permite seleccionar «Custom» en la configuración del almacenamiento para crear y configurar particiones manualmente. | https://wiki.almalinux.org/documentation/installation-guide.html |
| Guía oficial para instalar Docker Engine en esa familia | Sí. Docker incluye AlmaLinux entre las plataformas compatibles y ofrece documentación para instalar Docker Engine en sistemas de la familia RHEL. | https://docs.docker.com/engine/install/rhel/ |
| Imagen base del Dockerfile para esa versión | No aplica. AlmaLinux corresponde a la máquina virtual de consola; la imagen base asignada al grupo para Docker es Debian. | https://hub.docker.com/_/debian |

### Debian

### Debian (imagen base de Docker)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Debian 13.8 (Trixie), publicada el 21 de noviembre de 2026. | https://www.debian.org/releases/stable/errata |
| Hasta cuándo recibe actualizaciones de seguridad | Debian 13 recibe soporte completo hasta el 9 de agosto de 2028 y soporte LTS hasta el 30 de junio de 2030. | https://www.debian.org/releases/stable/ |
| Requisitos de hardware y si funciona en VirtualBox | Al utilizarse como imagen de Docker, no necesita recursos propios de una máquina virtual. Utiliza los recursos del sistema anfitrión. La imagen oficial admite arquitectura amd64. | https://hub.docker.com/_/debian |
| ¿El instalador permite particionado manual? | No aplica directamente. La imagen de Docker no utiliza un instalador tradicional ni requiere configurar particiones; funciona dentro de un contenedor. | https://hub.docker.com/_/debian |
| Guía oficial para instalar Docker Engine en esa familia | Sí. Docker dispone de una guía oficial para instalar Docker Engine en Debian. | https://docs.docker.com/engine/install/debian/ |
| Imagen base del Dockerfile para esa versión | Sí. Existe una imagen oficial de Debian en Docker Hub. Se puede utilizar la etiqueta `debian:13`, correspondiente a Debian 13 (Trixie). | https://hub.docker.com/_/debian/tags |

---

**Nota:** La información sobre versiones, arquitecturas, requisitos y gestores de paquetes fue consultada en la documentación y los sitios oficiales de cada distribución.

Fecha de consulta: 20 de noviembre de 2026.
