# Checkpoint: Mi primer laboratorio seguro de ciberseguridad

## 1. Red aislada
Se configuró la máquina virtual en modo NAT para reducir la exposición en la red local y proteger el host.

![Red NAT](evidencias/01rednat.png)

## 2. Usuario estándar y actualizaciones
Se utilizó un usuario sin privilegios elevados y se verificó que el sistema estuviera actualizado.

![Usuario estándar](evidencias/02usuarioestandar.png)
![APT Update](evidencias/03aptupdate.png)

## 3. Permisos y gestión
Se revisaron permisos de archivos con `ls -l` y se buscaron actualizaciones de paquetes con `sudo apt update`.

![Permisos](evidencias/04lslpermisos.png)

## 4. Snapshot inicial
Se creó una instantánea inicial llamada `Clean Install - Hardening applied`.

![Snapshot](evidencias/05snapshotcleaninstallhardeningapplied.png)
