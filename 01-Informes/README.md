# Informe técnico — LAB-011 MR ROBOT CTF

**Plataforma:** TryHackMe
**Objetivo:** 10.64.170.84
**Resultado:** Tres claves recuperadas y ejecución como ROOT.

## Hallazgos
1. WordPress 4.3.1 con credenciales débiles.
2. Editor de temas que permitió ejecución de PHP.
3. Archivo con hash MD5 legible por usuarios no privilegiados.
4. Nmap 3.81 con permisos SUID que permitió escalada de privilegios.

## Impacto
Compromiso completo del sistema del laboratorio.

## Mitigaciones
Actualizar componentes, restringir el editor PHP, utilizar hashes de contraseña robustos y eliminar permisos SUID innecesarios.
