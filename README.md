# Entre Bastidores — Ensayo teatral

Aplicación web sin backend. Abre `index.html` para la demo o publícala con GitHub Pages.

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub, por ejemplo `ensayo-teatral`.
2. Sube el archivo `index.html` a la raíz del repositorio.
3. Ve a **Settings → Pages**, selecciona **Deploy from a branch**, `main`, carpeta `/ (root)` y guarda.
4. La URL será `https://TU_USUARIO.github.io/ensayo-teatral/`.

## Notas

- La lectura de PDF usa PDF.js desde cdnjs y necesita Internet al importar los PDF. Los documentos se procesan localmente en el navegador.
- Solo reconoce de forma automática guiones cuyo diálogo se encabeza como `Personaje: texto`. No incluye OCR.
- El TTS utiliza `speechSynthesis` del navegador. Las voces disponibles dependen del dispositivo; prueba cada voz con ▶ antes del ensayo. En algunos navegadores móviles, la reproducción continua puede estar limitada por sus reglas de audio.
- No se suben ni almacenan PDF en servidor.
- La app espera a que el usuario pulse Continuar cada vez que termina su intervención.
