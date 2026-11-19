# Ficha de Versión 

# Identificación
- Versión: v0.1.0
- Proyecto: Proyecto final s.o
- Curso: Sistemas operativos.
- Grupo: Grupo 9, subgrupo 9c.
- Repositorio: Proyecto-so-9c.

  # Estado y Sprint 0
  - Etapa: Sprint 0 
  - Estado: Configuración inicial del repositorio y archivos basa de planeación y control.
  - Notas: Creación inicial de plan-de-trabajo.md y ficha-version.md.
 
 # Manjaro (VM gráfica)
- Versión y fecha de lanzamiento: Edición estable actual (Xfce); fecha no listada en descarga (rolling release)
- Soporte de seguridad: Actualización continua (rolling release) en rama estable
- Requisitos y VirtualBox: 64 bits (sin soporte de 32 bits); compatible con VirtualBox leyendo el ISO directamente
- Particionado manual: Verificar en guías de instalación de la wiki
- Fuente: https://wiki.manjaro.org/index.php?title=Download_Manjaro/es
 
# Ubuntu Server ( VM de consola)
- Versión y fecha de lanzamiento: Ubuntu 26.04.1 LTS (rama LTS 26.04, abril de 2026)
- Soporte de seguridad: 5 años de soporte estándar LTS (hasta abril/mayo de 2031; ampliable con Ubuntu Pro)
- Requisitos y VirtualBox: 64 bits; compatible con VirtualBox (VM consola: 25 GB disco, 2 CPU, 2 GB RAM al instalar / 3 GB en Sprint 3)
- Particionado manual: Sí, permite particionado manual
- Guía oficial de Docker: https://docs.docker.com/engine/install/ubuntu/
- Fuente: https://ubuntu.com/download/server y documentación oficial de Ubuntu

# Fedora (imagen base del Dockerfile)
- Versión y lanzamiento: Fedora Linux 45 (3 de noviembre de 2026)
- Soporte: ~13 meses (hasta diciembre de 2027)
- Requisitos / VirtualBox: No aplica VM/VirtualBox (contenedor; amd64/arm64v8)
- Particionado manual: No aplica (contenedor)
- Guía oficial de Docker: https://developer.fedoraproject.org/tools/docker/docker-images.html
- Docker Hub: https://hub.docker.com/_/fedora
- Fuentes: https://fedoraproject.org/, https://docs.fedoraproject.org/en-US/releases/ y https://hub.docker.com/_/fedora

- 
