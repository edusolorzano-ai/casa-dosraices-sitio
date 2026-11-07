# Paquete de imprenta, opción 1: Mediterránea

**Todas las medidas son supuestas. Confírmalas con su imprenta antes de mandar a producir.**

| Archivo (.svg y .pdf) | Pieza | Corte | Rebase | Uso |
|---|---|---|---|---|
| `tarjeta-croissant-frente` | Tarjeta croissant, frente | 120 × 66 mm | 3 mm | Forma de croissant, troquel a la medida |
| `tarjeta-croissant-vuelta` | Tarjeta croissant, vuelta | 120 × 66 mm | 3 mm | QR a casa-dosraices.com |
| `tarjeta-pan-de-muerto-frente` | Tarjeta pan de muerto, frente | 80 × 80 mm | 3 mm | Forma de pan de muerto, troquel a la medida |
| `tarjeta-pan-de-muerto-vuelta` | Tarjeta pan de muerto, vuelta | 80 × 80 mm | 3 mm | QR a casa-dosraices.com |
| `sticker-caja-redondo` | Sticker de caja, redondo | 60 × 60 mm | 3 mm | Sello de la tapa, 60 mm de diámetro |
| `sticker-caja-cierre` | Sticker de caja, cierre | 100 × 30 mm | 3 mm | Cruza la unión de la tapa |
| `etiqueta-larga` | Etiqueta larga | 160 × 35 mm | 3 mm | Charola o bolsa larga |
| `etiqueta-cuadrada` | Etiqueta cuadrada | 60 × 60 mm | 3 mm | Bolsa o caja chica |
| `etiqueta-colgante` | Etiqueta colgante | 50 × 90 mm | 3 mm | Perforación de 5 mm para el hilo |
| `bolsa-mariposa` | Croissant mariposa para bolsa | 140 × 77 mm | 3 mm | Se dobla al centro y se engrapa a la bolsa café |
| `bolsa-una-tinta` | Bolsa café, impresión a una tinta | 120 × 160 mm | no lleva | Directo sobre la bolsa, sin rebase; la tinta la elige la imprenta |
| `plantilla-acrilico` | Plantilla del sello en acrílico | 100 × 100 mm | no lleva | Corte y grabado láser, en espejo porque marca al presionar |

## Cómo está armado cada archivo
- El documento mide el corte más el rebase por lado; el fondo llena todo el documento.
- Capa `arte`: lo que se imprime. Letras convertidas a trazos, sin fuentes ni imágenes incrustadas.
- Capa `CutContour`, magenta `#FF00FF` de 0.1 mm: línea de corte. No se imprime.
- Capa `seguridad`, cian punteado: 3 mm hacia adentro del corte, solo en piezas rectangulares. No se imprime.
- Capa `pliegue`, verde: doblez y lugar de la grapa de la mariposa. No se imprime.
- La plantilla del acrílico trae sus propias capas `corte` y `grabado`.

## Antes de imprimir
1. **Color:** los PDF van en RGB, con los códigos de `paleta.txt`. Pide a la imprenta la conversión a CMYK o Pantone y una prueba de color; los tonos en papel no van a verse igual que en pantalla.
2. **Contacto:** «Contacto por confirmar» es un marcador en las vueltas de las dos tarjetas. Se cambia cuando Jorge y Eduardo confirmen el dato (PV-03 y PV-13 en `POR-VALIDAR.md`).
3. **QR:** lleva a `https://casa-dosraices.com`. Escanea una prueba impresa al tamaño final antes de tirar el lote.
4. **Mariposa:** forma, doblez y grapa son una interpretación de lo que pidieron en la junta; confírmalos con Karla y Jorge sobre una bolsa real.
5. **Acrílico:** el diámetro de 100 mm se confirma con quien lo corte y sobre una concha real.
