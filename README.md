# Checkpoint: Mi primer laboratorio seguro de ciberseguridad

## 1. Red aislada
Se configuró la máquina virtual en modo NAT para reducir la exposición en la red local y proteger el host.

![Red NAT](evidencias/01-red-nat.png)

## 2. Usuario estándar y actualizaciones
Se utilizó un usuario sin privilegios elevados y se verificó que el sistema estuviera actualizado.

![Usuario estándar](evidencias/02-usuario-estandar.png)
![APT Update](evidencias/03-apt-update.png)

## 3. Permisos y gestión
Se revisaron permisos de archivos con `ls -l` y se buscaron actualizaciones de paquetes con `sudo apt update`.

![Permisos](evidencias/04-ls-l-permisos.png)

## 4. Snapshot inicial
Se creó una instantánea inicial llamada `Clean Install - Hardening applied`.

![Snapshot](evidencias/05-snapshot-clean-install-hardening-applied.png)


Durante la ejecución del laboratorio, la instalación de Ubuntu en VirtualBox presentó fallas de arranque/carga que impidieron completar la generación de todas las evidencias solicitadas, siempre se congelaba al final del procedimiento. Se documentó la configuración de red en NAT y el estado del entorno como evidencia parcial del intento de implementación.


<img width="1278" height="885" alt="image" src="https://github.com/user-attachments/assets/38f6376b-79df-4d9d-9aa8-3da87c76ba8a" />

