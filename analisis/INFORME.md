# Análisis de los dos tomos de *Genaro Berón de Astrada: el héroe olvidado*

## Alcance y método

Se revisaron las 132 capturas PNG de los dos tomos (58 del primero y 74 del segundo), en orden cronológico de captura. Se extrajo texto mediante OCR en español y se contrastaron las portadas, índices, comienzos y finales de capítulos, fichas editoriales y referencias. El OCR es una ayuda de búsqueda: contiene errores de lectura y texto de la interfaz de Google Play Libros. Las capturas muestran páginas dobles, por lo que **el número de captura no equivale al número de página del libro**.

Los originales visuales se conservaron. El inventario JSON registra la ruta original, la nueva ruta, el tamaño y la huella SHA-256 de cada PNG. `mapa_renombres.csv` permite localizar cualquier captura por su nombre anterior. Los archivos `tomo_1_ocr.md` y `tomo_2_ocr.md` contienen la extracción sin corrección editorial.

## Qué contiene cada tomo

| Tomo | Datos de la edición visibles | Recorrido narrativo |
| --- | --- | --- |
| 1, *El héroe olvidado* | Orlando Ramón Barboza; publicación de mayo de 2024; ISBN 978-631-00-3965-7; ficha que declara 115 páginas. | Marco de Jeremías y su padre; infancia, orfandad, trabajo y formación de Genaro; regreso a Corrientes, servicio militar, logia, gobernación y conflicto institucional con Rosas. Cierra con el legado y el regreso al diálogo familiar. |
| 2, *Cuando elegir cuesta la vida* | Orlando Ramón Barboza, Edgar Alberto Aranda, Héctor Ezequiel Barboza, Orlando Gabriel Barboza y Alfonzo Nicolás Rubianes Gravier; © 2025; ISBN 978-631-01-3084-2; ficha que declara 125 páginas. | Retoma el marco familiar y se concentra en 1838–1839: disputa por la organización constitucional y el comercio, movilización correntina, Pago Largo, represión posterior y memoria. Termina con dos partes de epílogo, referencias históricas y nota de los autores. |

El segundo tomo desarrolla el desenlace que el primero anuncia. En ambos, la historia familiar sirve para acercar el relato a lectores jóvenes. La oposición entre autonomía provincial y concentración de poder, y la pregunta por el costo de sostener una convicción, articulan la serie. El primer tomo privilegia la formación moral del protagonista; el segundo incorpora escenas de guerra, consecuencias para las familias y un debate explícito sobre la memoria histórica.

## Guía de lectura por capturas

**Tomo 1.** Capturas 001–007: cubierta, ficha, índice, prólogo e introducción. 008–018: capítulos 1–5, desde la infancia hasta la partida a Buenos Aires. 019–030: capítulos 6–11, regreso, servicio, primeros combates, ayuda a Corrientes y logia. 031–044: capítulos 12–16, investidura, programa constitucional y respuesta de Rosas. 045–054: capítulos 17–21, debate legislativo, proclamación y legado. 055–058: capítulo final y nota biográfica.

**Tomo 2.** Capturas 001–010: ficha, síntesis, prólogo, puente con el primer tomo, índice e introducción. 011–026: capítulos 1–4, negociación, bloqueo económico, reacción de Rosas y decisión legislativa. 027–041: capítulos 5–7, movilización, marcha y batalla de Pago Largo. 042–055: capítulos 8–9, violencia posterior, ocupación y persecución de la familia; incluyen referencias. 056–071: dos partes del epílogo, con la transmisión familiar de la memoria y un debate político; incluyen referencias. 072–074: nota de los autores, firmas y contracubierta.

## Hallazgos editoriales y de archivo

1. **Capturas redundantes.** El mismo texto aparece en los pares 013/014, 015/016, 017/018, 031/032 y 037/038 del tomo 1; 046/047, 058/061 y 060/062 del tomo 2. Algunas imágenes difieren por posición o elementos de la interfaz. Se mantuvieron todas para no perder detalles visuales. Antes de producir una versión final conviene escoger la mejor captura de cada par.
2. **Interfaz superpuesta.** Muchas imágenes del tomo 2 muestran una vista previa y una etiqueta de navegación del epílogo en la esquina inferior derecha, aun cuando se está leyendo otro capítulo. Algo similar ocurre con la etiqueta del capítulo 21 en varias capturas del tomo 1. Esos rótulos pasan al OCR y pueden ocultar texto real. No deben tomarse como títulos ni como prueba de paginación.
3. **Capturas de pantalla como fuente.** Los PNG incluyen barras del lector y grandes márgenes, y ocupan alrededor de 156 MiB en conjunto. Son útiles como respaldo visual, pero el archivo EPUB o PDF original sería mejor fuente para una edición, búsqueda fiable, citas y control de páginas. No se encontró tal archivo en estas carpetas.
4. **Diferencia entre narración y documento.** La ficha del tomo 1 dice expresamente que usa diálogos ficticios. El segundo incorpora apartados de “Referencias Históricas” y una nota que lo describe como narración fiel en lo esencial. Para uso docente o histórico conviene marcar qué escenas y diálogos son recreación y vincular cada afirmación factual con una fuente precisa. El primer tomo no presenta un aparato de referencias comparable al segundo.
5. **Citas por revisar.** En el tomo 2 se mencionan obras, artículos, documentos y páginas, especialmente en las capturas 049, 054, 060/062 y 070. Hay fuentes concretas, pero no una bibliografía unificada. Conviene verificar transcripciones, fechas, páginas y alcance de afirmaciones delicadas antes de citarlas como hechos establecidos. Este análisis no realizó cotejo contra los documentos históricos originales.
6. **Continuidad editorial.** En el epílogo del tomo 2, Gabriel aparece “con sus veinte años” (captura 056), mientras la nota de autores lo presenta con 24 (captura 072). Podría tratarse de edades correspondientes a momentos narrativos distintos; el texto no lo aclara. También se repite el encabezado “Nota de los autores” en la captura 072. Son puntos concretos para revisar en una próxima edición.
7. **Errores propios del OCR.** Se leen, por ejemplo, “Il” o “11” por “II” y letras extrañas en nombres y títulos. La extracción no debe publicarse como transcripción corregida sin una revisión página por página.

## Organización aplicada y siguiente paso recomendado

Se corrigieron los nombres de las dos carpetas y se renombraron los 132 PNG con el patrón `t1_001_portada.png` / `t2_037_capitulo-07.png`: tomo, secuencia de captura y sección. La secuencia evita ordenar por las horas del sistema o por la etiqueta errónea del lector. Se conservó la relación completa entre nombres anteriores y nuevos.

Para una siguiente fase editorial, conseguir los EPUB/PDF de origen permitiría verificar la continuidad y las páginas, eliminar capturas redundantes con seguridad y producir un texto corregido. Si solo existen estas imágenes, el trabajo prioritario sería recapturar las páginas tapadas por la vista previa del lector y revisar manualmente el OCR contra cada imagen.
