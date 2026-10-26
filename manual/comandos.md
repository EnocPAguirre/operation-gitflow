cat << 'EOF' > manual/comandos.md
# Manual - comandos md Bitácora: comandos que descubrimos

Completen esto hablando entre sí y explorando la terminal. No es un reporte para entregar.

| Situación | Comando | ¿Qué sucedió? | ¿En qué carpeta estoy? |
| :--- | :--- | :--- | :--- |
| ¿En qué carpeta estoy? | `pwd` | Muestra la ruta absoluta del directorio actual. | Ruta actual |
| ¿Qué contiene la carpeta? | `ls -la` | Lista todos los archivos y carpetas, incluidos los ocultos. | Ruta actual |
| ¿Cómo entrar a otra carpeta? | `cd exploracion` | Cambia la navegación al directorio especificado. | `/exploracion` |
| ¿Cómo regresar a la carpeta anterior? | `cd -` | Regresa al último directorio donde estuviste ubicado. | Carpeta previa |
| ¿Qué archivos cambiaron? | `git status` | Muestra el estado del árbol de trabajo y archivos modificados. | Raíz del repo |
| ¿En qué rama estoy? | `git branch` | Lista las ramas locales y marca con `*` la actual. | Raíz del repo |
| ¿Cómo traer cambios remotos? | `git fetch origin` | Descarga las referencias del repositorio remoto sin fusionar. | Raíz del repo |
| ¿Cómo ver el historial? | `git log --oneline --graph` | Muestra el historial de commits simplificado y en forma de árbol. | Raíz del repo |

### Recordatorio
`git pull` actualiza tu copia local; un Pull Request es la solicitud de revisión e integración de cambios en GitHub. No son lo mismo.
EOF
