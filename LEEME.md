# Nelgi: cómo ponerlo en línea (gratis)

Nelgi necesita estar en una dirección **https** para usar el micrófono. Estas son dos formas gratuitas de publicarlo. Con la primera tardas unos 5 minutos.

## Opción 1: Netlify (la más fácil, desde una computadora)

1. En la computadora, descomprime `nelgi.zip`. Te queda una carpeta `nelgi` con `index.html` y los íconos.
2. Entra a https://app.netlify.com/signup y crea una cuenta gratis (puedes usar tu cuenta de Google).
3. Ve a https://app.netlify.com/drop y arrastra la carpeta `nelgi` completa a la página.
4. En unos segundos Netlify te da una dirección como `https://algo-raro-123.netlify.app`. En **Site configuration → Change site name** la puedes cambiar a algo como `nelgi-huberth`.
5. Abre esa dirección en **Chrome** en tu celular.

## Opción 2: GitHub Pages

1. Crea una cuenta en https://github.com y luego un repositorio nuevo **público**, por ejemplo `nelgi`.
2. Toca **Add file → Upload files** y sube todos los archivos de la carpeta (no la carpeta en sí).
3. Ve a **Settings → Pages**. En "Branch" elige `main` y `/ (root)` y guarda.
4. En uno o dos minutos queda en `https://TU-USUARIO.github.io/nelgi/`.

## En el celular (Chrome, Android)

1. Abre la dirección de Nelgi en Chrome.
2. Pega tu clave de Gemini. La consigues gratis en https://aistudio.google.com/apikey con **Create API key**.
3. Toca **Probar micrófono** y acepta el permiso. Luego toca **Probar voz**.
4. En el menú ⋮ de Chrome elige **Agregar a pantalla principal** (o **Instalar app**). Nelgi queda como un ícono más, a pantalla completa.

## Si algo no funciona

- **No se escucha la voz:** quita el modo silencio y sube el volumen de multimedia. En Android, ve a Ajustes → Sistema → Idioma → Salida de texto a voz y elige "Speech Services by Google". Dentro de esa opción puedes descargar voces en inglés (Estados Unidos) de mejor calidad.
- **El micrófono no responde:** toca el candado junto a la dirección → Permisos → Micrófono → Permitir. El reconocimiento de voz de Chrome necesita internet y la app de Google instalada y actualizada.
- **"Llegaste al límite gratis":** el plan gratis de Gemini tiene un límite de mensajes por minuto y por día. Espera un momento, o en ⚙️ Ajustes elige otro modelo (los "flash-lite" suelen tener más cupo).
- **Tu clave:** se guarda solo en tu teléfono. No compartas el enlace con la clave ya puesta en otro dispositivo, y si alguna vez se filtra, bórrala en AI Studio y crea otra.

## Para actualizar Nelgi más adelante

Reemplaza los archivos (Netlify: arrastra la carpeta otra vez en **Deploys**; GitHub: sube los archivos nuevos). Tu progreso y tus palabras guardadas se mantienen en el teléfono.
