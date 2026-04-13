# 🎓 CENFOTUR Cajamarca 2026
## Sistema de Aprendizaje · Costos, Presupuesto y Finanzas en Turismo

---

## 📁 Estructura del proyecto

```
/
├── index.html                        ← HUB principal (este es la entrada)
├── sesion1_cajamarca_landing.html
├── sesion2_landing.html
├── sesion3_landing.html
├── sesion4_landing.html
├── sesion5_cajamarca_landing.html
├── sesion6_landing.html
├── sesion7_landing.html
├── sesion8_landing_final.html
└── README.md
```

---

## 🚀 Publicar en GitHub Pages (paso a paso)

### Paso 1 — Crear repositorio en GitHub
1. Entra a [github.com](https://github.com) con tu cuenta
2. Haz clic en **"New repository"** (botón verde)
3. Ponle el nombre: `cenfotur-cajamarca-2026`
4. Selecciona **Public**
5. Haz clic en **"Create repository"**

### Paso 2 — Subir los archivos
1. En la página del repositorio, haz clic en **"uploading an existing file"**
2. Arrastra TODOS los archivos HTML de esta carpeta
3. Haz clic en **"Commit changes"**

### Paso 3 — Activar GitHub Pages
1. Ve a **Settings** (en tu repositorio)
2. Busca la sección **"Pages"** en el menú lateral izquierdo
3. En "Branch", selecciona **main** y carpeta **/ (root)**
4. Haz clic en **Save**
5. Espera 2-3 minutos

### Paso 4 — Tu URL pública
Tu HUB estará disponible en:
```
https://TU_USUARIO.github.io/cenfotur-cajamarca-2026/
```

---

## 🔐 Contraseña de administrador

La contraseña actual es: **`cenfotur2026`**

Para cambiarla, abre `index.html` y busca esta línea:
```javascript
const ADMIN_PASS = 'cenfotur2026';
```
Cambia el texto dentro de las comillas por tu nueva contraseña.

---

## ⚙️ Cómo activar sesiones (modo admin)

1. Abre el HUB en el navegador
2. Haz clic en **⚙ Admin** (esquina superior derecha)
3. Ingresa tu contraseña
4. Para cada sesión, haz clic en el botón para cambiar su estado:
   - 🔒 **Bloqueado** → el alumno no puede verla
   - ● **Activo** → aparece disponible con botón dorado
   - ✓ **Hecho** → marcada como completada
5. Haz clic en **"Guardar y cerrar"**

> **Nota:** El estado se guarda en el navegador del administrador.
> Para compartirlo con alumnos, actualiza el estado inicial en el código
> (busca `sessionState` en el JS) o usa el sistema de URL que puede
> implementarse en una versión futura.

---

## 📱 Compatible con
- Chrome, Firefox, Safari, Edge
- Móviles y tablets
- GitHub Pages (gratis, sin servidor)
