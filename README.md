# SilentExposure — CTF Write-Up

Este repositorio contiene el write-up completo del reto de ciberseguridad **Silent Exposure**,
realizado como práctica académica en el contexto de un escenario simulado de respuesta ante incidentes.

El reto plantea una situación en la que la organización ficticia InGen detecta una intrusión
no autorizada en uno de sus servidores. A lo largo de los distintos apartados se aplican técnicas
reales de análisis: reconocimiento web, fuzzing de directorios, lectura de ficheros de configuración
expuestos, descifrado con GPG, acceso por SSH y auditoría del sistema.

El objetivo principal es educativo: aprender a identificar vulnerabilidades comunes, entender cómo
un atacante podría moverse lateralmente por un sistema y comprender la importancia de una correcta
configuración de permisos y servicios de seguridad.

## 🛠️ Herramientas utilizadas

- `dirb` — Fuzzing de directorios
- `Gobuster` — Fuzzing de directorios
- `GPG` — Descifrado de claves
- `SSH` — Acceso remoto al sistema
- Comandos estándar de auditoría en Linux

## 📂 Contenido del repositorio

`writeup.md` — [Resolución completa del reto, apartado por apartado](https://github.com/AmaliaBM/SilentExposure/blob/master/WRITE_UP.md)

## ⚠️ Aviso

Todo el contenido de este repositorio ha sido desarrollado en un entorno controlado
con fines estrictamente académicos.
