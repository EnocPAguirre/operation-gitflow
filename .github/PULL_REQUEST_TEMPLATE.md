### ¿Qué problema resuelve este PR?
Completa los pasos del plan de misión y actualiza el panel de control para coordinar las operaciones.

### ¿Qué archivos cambié?
- `misiones/aurora.md` (o `misiones/orbita.md`)
- `panel/estado.md`
- `manual/comandos.md`

### ¿Cómo lo comprobé?
Ejecutando el script local de verificación con `python scripts/verificar.py` y validando con `git status` y `git diff`.

### ¿Qué debería revisar el otro equipo?
Verificar que la redacción del plan sea clara y que los cambios en `panel/estado.md` respeten el formato requerido.

### Lista de comprobación
- [x] Mi PR va de `feature/*` hacia `develop` (o de `develop` hacia `main` para publicar).
- [x] Mis cambios no se hicieron directamente en `main`/`develop`.
- [x] Revisé la pestaña Files changed.
- [x] Solicité una revisión al otro equipo.
