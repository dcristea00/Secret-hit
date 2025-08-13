# Secret Hitler – Distribuidor de Roles

Sitio estático para repartir roles de *Secret Hitler* según el número de jugadores.

## Publicación rápida con GitHub Pages

1. Crea un repositorio en GitHub (por ejemplo: `secret-hitler-roles`).
2. Sube **todos** los archivos de este ZIP a la raíz del repositorio.
3. Ve a **Settings → Pages**.
   - *Build and deployment*: **Deploy from a branch**
   - *Branch*: `main` / **root**
4. Guarda y espera a que aparezca la URL. ¡Listo!

### Personalización de dominio (opcional)
- Renombra el archivo `CNAME.example` a `CNAME` y escribe tu dominio dentro.
- Apunta tu dominio con un CNAME a `tu-usuario.github.io`.
- Espera la propagación DNS (puede tardar algo).

## Estructura
- `index.html` – la app completa.
- `.nojekyll` – evita que GitHub Pages procese Jekyll (no es necesario build).
- `CNAME.example` – ejemplo para dominio propio.
- `README.md` – este archivo con instrucciones.