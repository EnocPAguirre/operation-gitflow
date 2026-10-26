# Bitácora: comandos que descubrimos

Completen esto hablando entre sí y explorando la terminal. No es un reporte para entregar.

| Situación | Comando | ¿Qué sucedió? |
| :--- | :--- | :--- |
| ¿En qué carpeta estoy? | `pwd` | Muestra la ruta absoluta del directorio actual. |
| ¿Qué contiene la carpeta? | `ls -la` | Lista todos los archivos y carpetas, incluyendo los ocultos (que empiezan con `.`). |
| ¿Cómo entrar a otra carpeta? | `cd exploracion` | Cambia el directorio de trabajo actual a la carpeta especificada. |
| ¿Cómo regresar a la carpeta anterior? | `cd -` | Regresa de inmediato al último directorio donde estuvimos parados. |
| ¿Qué archivos cambiaron? | `git status` | Muestra el estado del árbol de trabajo (archivos modificados, staged o untracked). |
| ¿En qué rama estoy? | `git branch -a` | Muestra todas las ramas locales y las remotas (`origin/`). |
| ¿Cómo traer cambios remotos? | `git fetch origin` | Descarga las referencias del repositorio remoto sin alterar nuestras ramas locales. |
| ¿Cómo ver el historial? | `git log --oneline --graph --decorate --all` | Muestra una representación gráfica abreviada del historial de commits y ramas. |

### Recordatorio
`git pull` actualiza tu copia local; un Pull Request es la solicitud de revisión e integración de cambios en GitHub. No son lo mismo.
