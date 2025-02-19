# Ansible Playbook: Actualización y Mantenimiento de Sistemas

Este repositorio contiene un playbook de Ansible para actualizar el sistema operativo, limpiar paquetes antiguos y realizar tareas de mantenimiento en máquinas basadas en Ubuntu y Proxmox.

## Inventario de Hosts

El inventario de hosts (`hosts`) debe contener las direcciones IP o nombres de host de las máquinas que deseas actualizar y mantener. Ejemplo:

```ini
[ubuntu_machines]
ubuntu_host1 ansible_host=192.168.1.10
ubuntu_host2 ansible_host=192.168.1.11

[proxmox_machines]
proxmox_host ansible_host=192.168.1.12
