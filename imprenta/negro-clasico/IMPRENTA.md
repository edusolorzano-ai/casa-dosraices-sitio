# Paquete de imprenta: Negro clásico

**Todas las medidas son supuestas. Confírmalas con su imprenta antes de mandar a producir.**

| Archivo (.svg y .pdf) | Pieza | Corte | Rebase | Uso |
|---|---|---|---|---|
| `tarjeta-croissant-frente` | Tarjeta croissant, frente | 120 × 66 mm | 3 mm | Troquel con forma de croissant |
| `tarjeta-croissant-vuelta` | Tarjeta croissant, vuelta | 120 × 66 mm | 3 mm | QR a casa-dosraices.com |
| `tarjeta-pan-de-muerto-frente` | Tarjeta pan de muerto, frente | 80 × 80 mm | 3 mm | Troquel con forma de pan de muerto |
| `tarjeta-pan-de-muerto-vuelta` | Tarjeta pan de muerto, vuelta | 80 × 80 mm | 3 mm | QR a casa-dosraices.com |
| `tarjeta-rol-frente` | Tarjeta rol, frente | 70 × 70 mm | 3 mm | Troquel redondo con el rol |
| `tarjeta-rol-vuelta` | Tarjeta rol, vuelta | 70 × 70 mm | 3 mm | QR a casa-dosraices.com |
| `sticker-caja-redondo` | Sticker de caja, redondo | 60 × 60 mm | 3 mm | Sello dorado de la tapa, 60 mm |
| `sticker-caja-cierre` | Sticker de caja, cierre | 100 × 30 mm | 3 mm | Cruza la unión de la tapa |
| `etiqueta-larga` | Etiqueta larga | 160 × 35 mm | 3 mm | Charola o bolsa larga |
| `etiqueta-cuadrada` | Etiqueta cuadrada | 60 × 60 mm | 3 mm | Bolsa o caja chica |
| `etiqueta-colgante` | Etiqueta colgante | 50 × 90 mm | 3 mm | Perforación de 5 mm para el hilo |
| `bolsa-mariposa` | Croissant mariposa para bolsa | 140 × 77 mm | 3 mm | Se dobla al centro y se engrapa a la bolsa café |
| `bolsa-una-tinta` | Bolsa café, a una tinta | 120 × 160 mm | no lleva | Directo sobre la bolsa, sin rebase |
| `plantilla-acrilico` | Plantilla del sello en acrílico | 100 × 100 mm | no lleva | Corte láser. 14 puentes de 1.1 mm sostienen los huecos de las letras |

Además: `zona-segura-instagram.svg` para la foto de perfil, `caja.svg` como idea de caja y `post-instagram.svg`.

## Cómo está armado cada archivo
- El documento mide el corte más el rebase por lado; el fondo llena todo el documento.
- Capa `arte`: lo que se imprime. Letras a trazos, sin fuentes ni imágenes incrustadas.
- Capa `CutContour`, magenta `#FF00FF` de 0.1 mm: línea de corte. No se imprime.
- Capa `seguridad`, cian punteado: 3 mm hacia adentro del corte en piezas rectangulares. No se imprime.
- Capa `pliegue`, verde: doblez y grapa de la mariposa. No se imprime.
- La plantilla del acrílico trae capas `contorno` y `corte`; es de lectura normal, no va en espejo.

## Antes de imprimir
1. **Color:** los PDF van en RGB, con los códigos de `paleta.txt`. Pide a la imprenta la conversión a CMYK o Pantone y una prueba de color.
2. **Contacto:** las vueltas llevan «WhatsApp 443 360 2049», tomado de su Instagram. Confírmalo antes de imprimir (PV-03 y PV-13).
3. **QR:** lleva a `https://casa-dosraices.com`. Escanea una prueba impresa al tamaño final.
4. **Mariposa:** forma, doblez y grapa son una interpretación de lo que pidieron en la junta; confírmalos sobre una bolsa real.
5. **Acrílico:** los trazos finos del logo se engrosaron poco para que se puedan cortar; confirma diámetro y grosor mínimo con quien lo corte, sobre una concha real.
