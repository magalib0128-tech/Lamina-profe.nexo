# Lente DIA · Profe Nexo en realidad aumentada

Enfocás la lámina impresa con la cámara del celular y Profe Nexo (docente digital ficticio creado con IA) aparece en 3D sobre el papel y habla.
Proyecto DIA, Didáctica con IA · IA al Colorado.

## Archivos
| Archivo | Para qué sirve |
|---|---|
| `index.html` | La página de realidad aumentada (MindAR + Three.js). |
| `proyecto.json` | Configuración que lee `index.html`: lámina, marcador, modelo 3D, voz y texto. |
| `lamina-profe-nexo.png` | Lámina A4 (2480×3508 px, 300 dpi). Es también el marcador. |
| `lamina-profe-nexo-A4.pdf` | La misma lámina lista para imprimir en A4. |
| `lamina-profe-nexo.mind` | Marcador ya compilado a partir de la lámina. |
| `profe-nexo.glb` | Figura 3D de Profe Nexo (con boca, cabeza y brazos animables). |

## Imprimir
- Imprimí `lamina-profe-nexo-A4.pdf` en A4, al 100 % (sin «ajustar a página»), en papel mate si podés.
- No la dobles ni la plastifiques con brillo: los reflejos dificultan el reconocimiento.
- No cambies la imagen: si la modificás, hay que volver a compilar el marcador.

## Publicar en GitHub Pages
1. Creá un repositorio público nuevo (por ejemplo `lente-dia`).
2. Subí **todos** los archivos de esta carpeta (Add file > Upload files > Commit changes).
3. Settings > Pages > Deploy from a branch > `main` / `/ (root)` > Save.
4. Abrí `https://TU_USUARIO.github.io/lente-dia/` desde el celular. La cámara solo funciona con https.

## Usar
1. Tocá «Activar la cámara» y aceptá el permiso.
2. Enfocá la lámina completa, con buena luz.
3. Cuando aparezca Profe Nexo, tocá «Escuchar a Profe Nexo».
4. «Posición» cambia cómo se ve: inclinada (recomendada), mesa o pared.

## Notas
- La voz es la del dispositivo (gratis, sin créditos). Si no tiene voz en español, Profe Nexo mueve la boca sin sonido. En Windows se instala en Configuración > Hora e idioma > Voz.
- Si falta `lamina-profe-nexo.mind`, la página compila el marcador sola desde el PNG (tarda un minuto).
- La página no guarda ni envía imágenes de la cámara.
- Profe Nexo es un personaje ficticio creado con IA, no una persona real.
