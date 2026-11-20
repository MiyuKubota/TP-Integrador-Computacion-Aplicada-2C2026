# Trabajo Práctico Integrador - Computación Aplicada

**Universidad de Palermo — Segundo Cuatrimestre 2026**

## Integrantes

- Denis Eduardo Quintana
- Esteban Rivas Molina
- Roberto Rafael Saavedra

## Descripción del trabajo

En este Trabajo Práctico Integrador configuramos una máquina virtual con GNU/Linux Debian 12 utilizando Oracle VirtualBox.

Las tareas realizadas incluyen:

- Configuración del hostname TPServer.
- Configuración de acceso remoto mediante SSH.
- Instalación de Apache con soporte para PHP.
- Instalación de MariaDB y carga de la base de datos ingenieria.
- Configuración de una dirección IP estática.
- Incorporación de un disco adicional de 10 GB.
- Creación y montaje de las particiones /www_dir y /backup_dir.
- Desarrollo de un script para realizar backups.
- Programación de tareas automáticas mediante Cron.

## Entregables

Los archivos solicitados para la entrega son:

- root.tar.gz
- etc.tar.gz
- opt.tar.gz
- www_dir.tar.gz
- backup_dir.tar.gz
- var.tar.gz`, dividido en partes.

## Aclaración sobre los backups

La consigna menciona el directorio /var/logs, pero Debian utiliza /var/log para almacenar los registros del sistema. Por eso, configuramos el backup utilizando /var/log.
