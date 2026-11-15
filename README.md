# lumsto-web

La web comercial de Lumsto, para **lumsto.com**. Separada de la app (`lumsto.app`, repositorio `Lumsto/lumsto`).

- Una sola página en HTML y CSS, sin programas que instalar: `index.html`.
- Logos en `marca/` (los mismos archivos de la app). Imágenes de la plataforma en `imagenes/`.
- **No mover, renombrar ni borrar** `marca/logo-color.png` ni `marca/logo-color.svg`: los mails de Auth0 los cargan desde `https://lumsto.com/marca/logo-color.png` y `https://lumsto.com/marca/logo-color.svg`. Esas direcciones no cambian nunca. Si cambia el logo, se reemplaza el archivo con el mismo nombre.
- Marca: grafito `#343536`, ámbar `#E8AA38` solo como acento, marfil `#F7F5F0`, Noto Sans, radio de 12 px, sin sombras.
- Para verla: abrir `index.html` en el navegador.
- Publicación: pendiente (Vercel, equipo Lumsto, con el dominio lumsto.com de Porkbun).
