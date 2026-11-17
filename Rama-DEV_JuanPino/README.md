# AA3_EV11_Auth – Autenticación con Supabase (MVC)

Proyecto web (HTML/CSS/JS) con login, registro y cierre de sesión usando Supabase Auth.

## Estructura MVC
- `app/models/` – conexión a Supabase y funciones de autenticación
- `app/controllers/` – lógica de login/registro y protección de páginas
- `app/views/auth/login.html` – vista de inicio de sesión y registro
- `dashboard.html`, `perfil.html`, `productos.html` – páginas protegidas

## Configuración
1. Copia `config/config.example.js` a `config/config.js`.
2. Pega tu `SUPABASE_URL` y `SUPABASE_ANON_KEY` (Supabase → Project Settings → API).
3. Abre `index.html` con Live Server (VS Code) o desde XAMPP (`htdocs`).

`config/config.js` está en `.gitignore` y no se sube al repositorio.
