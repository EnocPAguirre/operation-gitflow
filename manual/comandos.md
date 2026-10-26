# Manual - comandos md

## Bitácora: comandos que descubrimos

| Situación | Comando | ¿Qué sucedió? | ¿En qué carpeta estoy? |
| :--- | :--- | :--- | :--- |
| ¿En qué carpeta estoy? | `pwd` | Muestra la ruta absoluta del directorio actual. | `/home/usuario/proyecto` |
| ¿Qué contiene la carpeta? | `ls -la` | Muestra todos los archivos y carpetas, incluidos los ocultos. | `/home/usuario/proyecto` |
| ¿Cómo entrar a otra carpeta? | `cd misiones` | Cambia el directorio de trabajo a la carpeta especificada. | `/home/usuario/proyecto/misiones` |
| ¿Cómo regresar a la carpeta anterior? | `cd -` | Regresa al último directorio en el que estuviste ubicado. | `/home/usuario/proyecto` |
| ¿Qué archivos cambiaron? | `git status` | Lista los archivos modificados, creados o preparados para commit. | `/home/usuario/proyecto` |
| ¿En qué rama estoy? | `git branch` | Muestra la lista de ramas locales e indica con un asterisco la actual. | `/home/usuario/proyecto` |
| ¿Cómo traer cambios remotos? | `git fetch origin` | Descarga las referencias del repositorio remoto sin alterar tus archivos. | `/home/usuario/proyecto` |
| ¿Cómo ver el historial? | `git log --oneline --graph --decorate --all` | Muestra el historial de commits y ramas de forma gráfica y condensada. | `/home/usuario/proyecto` |

---

### Recordatorio
`git pull` actualiza tu copia local descargando e integrando cambios; un Pull Request es la solicitud de revisión e integración de cambios en GitHub. No son lo mismo[cite: 1].
