[README.md](https://github.com/user-attachments/files/33517765/README.md)
# Bee-hind the Brand · web

Web estática para GitHub Pages: HTML y CSS, un script mínimo para enviar los formularios con Web3Forms, sin cookies y sin cargar nada de Google.

## 1. Subirla a GitHub (sin instalar nada)

1. Cuenta `beehindthebrand` con verificación en dos pasos y, en *Settings → Emails*, activa **Keep my email address private**.
2. Repositorio **público** llamado exactamente `beehindthebrand.github.io`.
3. **Add file → Upload files** y arrastra **el contenido** de esta carpeta (no la carpeta ni el zip).
4. **Commit changes**.
5. **Settings → Pages → Deploy from a branch**, rama `main`, carpeta `/ (root)`.
6. En uno o dos minutos estará en `https://beehindthebrand.github.io`.

## 2. Antes de publicar (imprescindible)

| Qué | Dónde | Notas |
| --- | --- | --- |
| `REEMPLAZAR-ACCESS-KEY-WEB3FORMS` | `index.html`, 2 veces | Tu clave de Web3Forms (apartado 3) |
| `[DIRECCIÓN POSTAL]` | `privacidad.html`, `aviso-legal.html`, `condiciones.html` | Obligatoria por la LSSI |
| `[PAGOS…]` y `[EMAIL…]` | `privacidad.html`, apartado 6 | Pon cómo cobras y, si mandas newsletters, con qué herramienta. Borra lo que no uses |
| `[MÉTODO DE PAGO…]` | `condiciones.html`, apartado 4 | Bizum, transferencia o enlace de pago |
| Plazos de 48 h y 72 h | `condiciones.html` | Son una propuesta: cámbialos si prefieres otros |
| Precio «15 €, IVA incluido» | `index.html` (hero, ticket, FAQ) y `condiciones.html` | Confirma con tu gestor si lleva IVA |
| Usuario de Instagram | `index.html` (3 sitios) | Ahora apunta a `instagram.com/beehindthebrand` |

Los textos legales son un **borrador**: que los revise tu gestor o asesor legal. He usado tu NIF y `natalia@localgrow.es`, los mismos del consentimiento de imagen.

## 3. Activar los formularios (Web3Forms)

1. En [web3forms.com](https://web3forms.com) escribe el email donde quieres recibir las solicitudes y te llega la **access key**.
2. Pégala en los dos formularios de `index.html`.
3. Con la web ya publicada, haz una prueba de cada formulario.
4. **RGPD:** acepta su acuerdo de encargo del tratamiento (DPA) y entra cada cierto tiempo en su panel a **borrar los envíos antiguos** (según su política de privacidad, los guardan hasta 3 años). La política de privacidad dice que lo haces.

Plan gratuito: 250 envíos al mes y un solo email de destino. La clave es pública por diseño; contra el spam hay un campo trampa. Si añades hCaptcha, entran scripts de terceros y habrá que revisar las cookies.

## 4. Cada encuentro nuevo

1. **Ticket del encuentro** (`index.html`, sección `#encuentro`): fecha, lugar, plazas y precio.
2. **Hero**: la lista de datos bajo los botones.
3. **FAQ «¿Cuánto cuesta?»** si cambia el precio.
4. **Local secreto**: hasta 3 días antes, deja «Un local secreto…». El día que lo desveles, pon el nombre y la localidad (bueno para el SEO local).
5. **Datos estructurados del evento**: en el `<head>` hay un bloque `Event` comentado. Rellénalo con fecha, hora y dirección y quita las marcas `<!--` y `-->`. Así Google puede mostrar el encuentro en sus resultados.
6. Cuando esté lleno, cambia el botón por «Apúntate a la lista de espera».

## 5. Cuando compres el dominio

1. *Settings → Pages → Custom domain*: escribe el dominio.
2. En el proveedor del dominio, añade los registros DNS que indica GitHub.
3. Activa **Enforce HTTPS**.
4. Sustituye `https://beehindthebrand.github.io` por el dominio en `index.html`, `robots.txt` y `sitemap.xml`.
5. Crea un email con el dominio (por ejemplo `hola@beehindthebrand.com`) y cámbialo en las páginas legales si quieres separar Bee-hind de LocalGrow.

## 6. SEO local: siguientes pasos

- **Versión en catalán** (`/ca/`): en Tarragona es la mejora de SEO local con más impacto. Habría que añadir `hreflang` en las dos versiones.
- **Una página por encuentro** (`/encuentros/…`) con el local, la localidad, fotos y la crónica. Pide al anfitrión que la enlace desde su web o su ficha de Google: son enlaces locales de calidad.
- **Enlaces de entrada**: perfil de Instagram, LinkedIn de Natalia y LocalGrow, y webs de los miembros («Soy abeja de Bee-hind»).
- **Google Business Profile**: sin local fijo, de momento no lo recomiendo.

## 7. Marca

Colores, tipografías y logo salen del sistema de diseño de Bee-hind. Las fuentes Bricolage Grotesque y DM Sans van en `fonts/` con su licencia OFL. Regla del panal: hexágonos en crema sobre miel.
