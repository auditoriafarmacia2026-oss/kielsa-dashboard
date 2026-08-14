# 📊 Kielsa – Dashboard Control Interno de Campo

Dashboard web para auditoría de inventarios generales de **Kielsa Farmacéutica**.

## 🗂️ Archivos en este repositorio

| Archivo | Descripción |
|---|---|
| `index.html` | El dashboard (no cambiar) |
| `datos.json` | **Los datos actualizables** — este es el que cambia cada mes |
| `actualizar_dashboard.py` | Script Python para actualizar datos.json automáticamente |

## 🔄 Cómo actualizar los datos (tú solo, sin ayuda)

### Opción A — Desde la web (más fácil, sin instalar nada)

1. Abre tu repositorio en https://github.com
2. Haz clic en `datos.json`
3. Haz clic en el ícono de lápiz ✏️ (editar)
4. Borra todo el contenido
5. Pega el nuevo JSON (generado por el script Python)
6. Haz clic en **"Commit changes"**
7. En ~30 segundos el dashboard se actualiza

### Opción B — Con el script Python (automatizado)

1. Instala Python: https://python.org
2. Instala dependencias:
   ```
   pip install pandas openpyxl
   ```
3. Coloca `actualizar_dashboard.py` y `BASE_LIMPIA.xlsx` en la carpeta del repositorio
4. Ejecuta:
   ```
   python actualizar_dashboard.py
   ```
5. Listo — sube automáticamente a GitHub y el dashboard se actualiza

## 🌐 Ver el dashboard

Una vez configurado GitHub Pages, el dashboard estará en:
```
https://TU_USUARIO.github.io/kielsa-dashboard/
```

## ⚙️ Configurar GitHub Pages (solo la primera vez)

1. Ve a tu repositorio → **Settings** → **Pages**
2. En "Source" selecciona **"Deploy from a branch"**
3. Selecciona la rama **`main`** y carpeta **`/ (root)`**
4. Haz clic en **Save**
5. En ~1 minuto aparece el enlace público

## 🔐 Seguridad

- El dashboard abre en **Modo Solo Vista** por defecto
- Solo el PIN `kielsa 2025` permite modificar datos desde el dashboard
- Los datos están en `datos.json` — son visibles para quien tenga el enlace
- Si necesitas datos privados, usa un repositorio **privado** con GitHub Pro

---
*Kielsa Farmacéutica · Control Interno de Campo | Inventarios Generales*
