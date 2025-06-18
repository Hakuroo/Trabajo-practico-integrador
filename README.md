git init
git remote add origin https://github.com/TU_USUARIO/Trabajo-practico-integrador.git
git add .
git commit -m "Entrega completa TP integrador"
git push -u origin master
# Trabajo Práctico Integrador - Administración de Sistemas GNU/Linux

**Participantes:**
- Elian Wussler

**Resumen:**
Este repositorio contiene la configuración del entorno Debian, con los servicios y automatización solicitados.

### Contenido:
- Servicios: SSH, Apache + PHP, MariaDB
- Particiones: /www_dir y /backup_dir
- Script de backup automatizado con `cron`
- Archivos comprimidos del sistema

### Archivos:
- root.tar.gz
- etc.tar.gz
- opt.tar.gz
- proc.tar.gz
- www_dir.tar.gz
- backup_dir.tar.gz
- var_part_aa, var_part_ab, ...
