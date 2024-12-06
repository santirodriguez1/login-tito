# Proyecto: Sistema de Login y Registro con Dark Mode

Este proyecto es una aplicación web sencilla que permite a los usuarios registrarse, iniciar sesión y gestionar sus datos utilizando `LocalStorage` como base de datos simulada. Además, incluye un botón para alternar entre **modo claro** y **modo oscuro**.

## Funcionalidades Principales

1. **Pantalla Principal (Login):**

   - Permite iniciar sesión con un usuario y contraseña registrados.
   - Valida credenciales contra los datos almacenados en `LocalStorage`.
   - Redirige a una pantalla placeholder (`404`) en caso de inicio exitoso.
   - Incluye un botón para redirigir a la pantalla de registro.
   - **Dark Mode**: Botón para alternar entre modo claro y oscuro.

2. **Pantalla de Registro:**

   - Permite a los usuarios crear una cuenta con:
     - Nombre de usuario.
     - Contraseña (con confirmación).
   - Valida que los campos no estén vacíos.
   - Verifica que las contraseñas coincidan.
   - Garantiza que el nombre de usuario sea único.
   - Guarda los datos en `LocalStorage`.

3. **Pantalla Placeholder (404):**

   - Muestra un mensaje de error simulando una sección no disponible.
   - Incluye un botón de "Logout" para volver al login.

4. **Dark Mode:**
   - Al hacer clic en el botón, el diseño de la página cambia entre temas claro y oscuro.
   - La preferencia del usuario se guarda en `localStorage` y persiste al recargar la página.

---

## Tecnologías Utilizadas

- **HTML:** Para la estructura de las páginas.
- **CSS:** Para el estilo visual.
- **Bootstrap:** Para un diseño moderno y responsivo.
- **Bootstrap Icons:** Para los íconos de usuario, contraseña y el botón de dark mode.
- **JavaScript:** Para la lógica, validaciones y gestión de datos.

---

## Validaciones Incluidas

### Pantalla de Registro:

- Campos no vacíos.
- Contraseñas coincidentes.
- Usuario único (sin repetición).

### Pantalla de Login:

- Usuario y contraseña válidos según datos registrados.

---

## Capturas de Pantalla

### Login

> ![Login](/img/capturas/screen-1.png)

### Registro

> ![Registro](/img/capturas/screen-2.png)

### 404

> ![404](/img/capturas/screen-3.png)

### Modo Oscuro

> ![Modo Oscuro](/img/capturas/screen-4.png)

---

## Notas

- **Persistencia del Dark Mode:** El estado del modo oscuro se guarda en `localStorage` para que se mantenga entre recargas.

---

## Autor

Proyecto desarrollado por **Santino Rodriguez** en **HTML, CSS y JavaScript**.

---
