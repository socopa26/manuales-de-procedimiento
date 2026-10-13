# PRO-SOP-01 — Control de integración

Artefacto de auditoría; no forma parte del procedimiento oficial.

## A. Identificación y estado

**PRO-SOP-01: EN REVISIÓN – integración realizada.** Pendiente de revisión independiente y aprobación de la integración. No oficializado.

Fecha: 09/10/2026 (America/Costa_Rica).

Fuente exclusiva: `00_ORIGINALES/PRO-SOP-01-V1-2026 - Procedimiento de Gestión de Compras y Abastecimiento.docx`.

Salida: `01_INTEGRACION/PRO-SOP-01-V1-2026_INTEGRADO.docx`.

Base Git: `09c4faa2ab3d7dc42ad917101061c0f174f67ffe`. La incorporación se identifica mediante el commit dedicado que introduce este archivo y el integrado: `git log --diff-filter=A --format=%H -- 01_INTEGRACION/PRO-SOP-01-V1-2026_INTEGRADO.docx`. Su SHA se entrega al usuario.

Se aplican la comparación consolidada y las correcciones finales de diagramas expresamente aprobadas. La confirmación de ausencia de descripción de versión prevalece sobre el paquete inicial: no se agregó «Versión inicial (borrador).» ni tabla de control de versiones.

SHA-256 original: `19c66a2025552f49763610f07ec7edb9037434073f46b883d79883b2297bb56e`.

SHA-256 integrado: `c2694f8905519e61959adea5b70fa7851ffea0e59bdec6677a23168bafd0b5f3`.

## B. Comparación estructural

| Elemento | Original | Integrado |
| --- | ---: | ---: |
| Párrafos del cuerpo, incluidas celdas y recuadros | 467 | 504 |
| Párrafos directos del cuerpo | 211 | 220 |
| Párrafos de cuerpo, encabezado y pie | 472 | 509 |
| Tablas del cuerpo | 20 | 20 |
| Tablas de cuerpo, encabezado y pie | 21 | 21 |
| Archivos de imagen en word/media | 4 | 4 |
| Referencias a imágenes (DrawingML/VML) | 5 | 5 |
| Comentarios Word | 0 | 0 |
| Secciones Word | 1 | 1 |
| Páginas renderizadas | 23 | 23 |

Método: conteo OOXML de párrafos `w:p` (incluidas celdas y textos de recuadros), tablas `w:tbl` y secciones `w:sectPr`. Hay 20 tablas en el cuerpo y una tabla adicional en el encabezado. Se distinguen cuatro archivos gráficos de cinco referencias DrawingML/VML: la duplicidad fuente de image3.png no se eliminó. No hay comentarios Word.

Diferencias de párrafos: nueve párrafos nuevos del desarrollo + 25 párrafos en cinco nuevas filas de RACI + tres párrafos en una fila nueva de Registros = 37. El cuerpo pasa de 467 a 504. No se eliminaron párrafos; solo se sustituyó el texto de una celda existente de Tabla 5. Se conservan las 23 páginas, aunque la expansión redistribuye el contenido y algunos saltos de tabla.

Partes del paquete con bytes diferentes: `word/document.xml`, `word/media/image2.png` y `word/media/image3.png`. Todas las demás partes permanecen idénticas, incluyendo encabezado, pie, estilos, numeración, relaciones, configuración y propiedades documentales. El DOCX se editó sobre su estructura existente, sin reconstrucción ni guardado desde PDF.

## C. Cambios ejecutados individualmente

Los P identifican párrafos directos del cuerpo original, excluidas las celdas. Las páginas de los diagramas se mantienen en 6 y 7 tras el render. Cada fila nueva se enumera individualmente y conserva el número nativo de columnas.

| Ubicación | Tipo | Texto original | Texto integrado |
| --- | --- | --- | --- |
| Alcance — tercera exclusión, después de P016 | AGREGAR PÁRRAFO | [Párrafo inexistente] | La gestión e interlocución directa de garantías postventa con clientes, reguladas por CAL-SOP-01-V1-2025. |
| Alcance — interfaz con Garantías, después de P018 | AGREGAR PÁRRAFO | [Párrafo inexistente] | Interfaz con Garantías: La participación de Proveeduría durante la atención de garantías se limita al soporte logístico interno requerido para materiales de reparación, suministros de bodega, alquileres de equipo, limpiezas y retiro de escombros, conforme a las solicitudes internas correspondientes. Proveeduría no gestiona ni toma decisiones sobre garantías y no participa en grupos de WhatsApp directos con clientes. |
| Ventana de pedidos — enlace financiero, después de P069 | AGREGAR PÁRRAFO | [Párrafo inexistente] | Ventana financiera de compras: Las Órdenes de Compra generadas por Proveeduría los jueves por la mañana pueden ingresar al ciclo ordinario de pagos de esa misma semana si cumplen el cierre financiero del jueves a las 12:00 md, aplicable a pagos ordinarios ≤ ₡1.000.000. El régimen financiero completo se rige por CTO-SOP-03-V1-2026. |
| Cotización y compra — después de recuadro BODEGA AC DESARROLLOS | AGREGAR PÁRRAFO | [Inexistente] | Para materiales retirados de bodega, Proveeduría registra el despacho y la imputación del costo hacia la línea presupuestaria del proyecto beneficiario en Mawi, utilizando «BODEGA AC DESARROLLOS» como proveedor cuando corresponda, sin requerir factura electrónica. |
| 3.4 — fuente principal | AGREGAR PÁRRAFO | [Inexistente] | PRO-SOP-01-V1-2026 se establece como la fuente principal para la guía técnica y la distribución de responsabilidades de Gastos Manuales en Mawi. |
| 3.4 — Mano de obra / planillas | AGREGAR PÁRRAFO | [Inexistente] | Mano de obra / planillas: El Ingeniero de Proyecto aprueba previamente las horas y montos; Recursos Humanos (RRHH) ejecuta el registro del gasto manual en Mawi. |
| 3.4 — Trámites CTA | AGREGAR PÁRRAFO | [Inexistente] | Trámites y comprobantes institucionales CTA: El Departamento de Consultoría registra en Mawi los gastos y comprobantes derivados de sus propios trámites institucionales, incluidos cuando corresponda aranceles o pagos al Registro Nacional. |
| 3.4 — Tarjetas corporativas | AGREGAR PÁRRAFO | [Inexistente] | Tarjetas corporativas y gastos administrativos: El Departamento Financiero realiza el cierre y conciliación, verifica el monto autorizado y registra/asigna en Mawi los gastos administrativos efectuados mediante tarjetas corporativas, incluidos peajes y otros gastos menores cuando se paguen mediante este mecanismo. |
| 3.4 — Material de bodega | AGREGAR PÁRRAFO | [Inexistente] | Material retirado de bodega: Proveeduría registra el despacho y la imputación del costo del material retirado de bodega al proyecto correspondiente en Mawi. |
| Tabla 3 — Registrar gasto manual de Mano de Obra en Mawi | AGREGAR FILA | [Inexistente] | Registrar gasto manual de Mano de Obra en Mawi &#124; Recursos Humanos &#124; Ingeniero de Proyecto (aprueba horas y montos) &#124; — &#124; — |
| Tabla 3 — Registrar gasto manual de Trámites CTA en Mawi | AGREGAR FILA | [Inexistente] | Registrar gasto manual de Trámites CTA en Mawi &#124; Consultoría &#124; — &#124; — &#124; — |
| Tabla 3 — Registrar gasto manual de Tarjetas corporativas en Mawi | AGREGAR FILA | [Inexistente] | Registrar gasto manual de Tarjetas corporativas en Mawi &#124; Departamento Financiero &#124; — &#124; — &#124; — |
| Tabla 3 — Registrar gasto manual de Materiales de Bodega en Mawi | AGREGAR FILA | [Inexistente] | Registrar gasto manual de Materiales de Bodega en Mawi &#124; Proveeduría &#124; — &#124; — &#124; — |
| Tabla 3 — Coordinar soporte logístico e insumos para Garantías (Ref: CAL-SOP-01-V1-2025) | AGREGAR FILA | [Inexistente] | Coordinar soporte logístico e insumos para Garantías (Ref: CAL-SOP-01-V1-2025) &#124; Proveeduría &#124; — &#124; — &#124; — |
| Tabla 5 — ¿Se emitió factura electrónica? / Tratamiento | MODIFICAR | Si no, el Departamento Financiero impacta el presupuesto mediante creación de un gasto directo o se comunica con el proveedor. | Si no, el registro del gasto manual en Mawi corresponde a RRHH para mano de obra, Consultoría para trámites CTA, Departamento Financiero para tarjetas corporativas y Proveeduría para material de bodega, conforme al apartado «Creación de gastos manuales». El Departamento Financiero se comunica con el proveedor cuando corresponda. |
| Tabla 7 — Gastos Manuales en Mawi | AGREGAR FILA | [Inexistente] | Gastos Manuales en Mawi &#124; Mawi / QBO &#124; RRHH (mano de obra), Consultoría (trámites CTA), Departamento Financiero (tarjetas corporativas) y Proveeduría (material de bodega) |
| word/media/image2.png — página fuente 6, recuadro paso 4 | MODIFICAR TEXTO GRÁFICO | Tratamiento de excepciones: Notas de crédito y pagos sin factura. | Tratamiento especial: notas de crédito y gastos sin factura. Los gastos sin factura se registran según el responsable definido en el apartado 3.4. |
| word/media/image2.png — página fuente 6, título paso 5 | MODIFICAR TEXTO GRÁFICO | GESTIÓN DE EXCEPCIONES | GESTIÓN DE NOTAS DE CRÉDITO |
| word/media/image2.png — página fuente 6, responsable paso 4 | MODIFICAR TEXTO GRÁFICO | RESPONSABLE: Proveeduría / Contabilidad | RESPONSABLE: Proveeduría |
| word/media/image3.png — página fuente 7, recuadro paso 1 | MODIFICAR TEXTO GRÁFICO | Para alquileres, solicitar con mínimo 2 días de anticipación. | Para alquileres: solicitar con mínimo 1 semana de anticipación. |
| word/media/image3.png — página fuente 7, recuadro paso 4 | MODIFICAR TEXTO GRÁFICO | Si no hay factura, finanzas crea un gasto directo. La OC de bodega no incluye factura. | Si no hay factura, el gasto se registra en Mawi según el responsable definido en el apartado 3.4. La OC de bodega no incluye factura. |
| word/media/image3.png — página fuente 7, responsable paso 4 | MODIFICAR TEXTO GRÁFICO | RESPONSABLE: Proveeduría / Contabilidad | RESPONSABLE: Proveeduría |

No se efectuaron modificaciones adicionales de contenido ni correcciones de peinado. Las cinco nuevas filas de Tabla 3 se clonaron de una fila compatible de cinco columnas. La nueva fila de Tabla 7 se clonó de una fila compatible de tres columnas, sin alterar la fila Facturas. No se aplicaron `w:cantSplit`, nuevos saltos, cambios de anchos de columnas ni ajustes de tipografía en el Word.

## D. QA textual

| Búsqueda en texto editable | Coincidencias | Resultado |
| --- | ---: | --- |
| fuente principal | 1 | Resultado esperado |
| fuente única | 0 | Resultado esperado |
| Versión inicial (borrador). | 0 | Resultado esperado |
| CAL-SOP-01-V1-2025 | 2 | Resultado esperado |
| jueves a las 12:00 md | 1 | Resultado esperado |
| ≤ ₡1.000.000 | 1 | Resultado esperado |
| Recursos Humanos (RRHH) ejecuta el registro | 1 | Resultado esperado |
| El Departamento de Consultoría registra en Mawi | 1 | Resultado esperado |
| El Departamento Financiero realiza el cierre y conciliación | 1 | Resultado esperado |
| Proveeduría registra el despacho | 2 | Resultado esperado |
| Gastos Manuales en Mawi | 2 | Resultado esperado |
| Si no, el Departamento Financiero impacta el presupuesto | 0 | Resultado esperado |
| conforme al punto 2.5 | 1 | Conservado por instrucción de peinado |
| requisitos generales del punto 1.1 | 1 | Conservado por instrucción de peinado |
| PRO-SOP-03-V1-2026 | 1 | Conservado por instrucción de peinado |
| FIN-INS-01-V1-2026 | 1 | Conservado por instrucción de peinado |

Verificaciones específicas:

- Ventana operativa de pedidos: lunes/miércoles AM; cotización lunes/miércoles PM; pedidos martes/jueves AM; facturas martes/jueves PM. Texto y gráfico horario conservados, sin sustituirlos por reglas financieras.
- Enlace financiero: jueves AM → cierre jueves 12:00 md para pagos ordinarios ≤ ₡1.000.000. No se agregaron regímenes de >₡1.000.000, subcontratos ni traslados de ciclos.
- PRO identificado como fuente principal, no única, de Gastos Manuales (decisión resuelta ID07).
- Distribución explícita: RRHH para mano de obra con aprobación previa del Ingeniero de horas/montos; Consultoría para trámites CTA; Finanzas para tarjetas corporativas; Proveeduría para bodega.
- Tabla 3: cinco filas agregadas, sin aprobadores/consultados/informados inventados; única aprobación nueva: Ingeniero de Proyecto sobre horas y montos.
- Tabla 7: fila Facturas idéntica al original, incluido B-Sides. Nueva fila Gastos Manuales independiente y sin B-Sides.
- Garantías: exclusión de gestión/interlocución con clientes y soporte logístico interno de Proveeduría, sin chats directos de clientes; referencia CAL-SOP-01-V1-2025.
- Versión 01, fecha 12/06/2026, autor, involucrados y campos de aprobación fuente intactos; no se agregó descripción de versión.
- Objetivo, nueve definiciones y cuatro indicadores sin cambios.

La extracción `PRO-SOP-01_TEXTO_INTEGRADO.md` conserva todos los párrafos, listas, tablas, celdas combinadas, recuadros, encabezado y pie. Se comprobó la cobertura de todos los nodos de texto de esas partes. Incluye transcripciones separadamente identificadas del texto de imágenes, sin convertirlas en texto normativo nuevo. El horario EMF se transcribe por filas/columnas desde sus registros de texto; los recuadros superpuestos de Word se reproducen también y las alternativas/duplicidades fuente se identifican sin eliminarlas.

## E. QA gráfico y hashes

Se modificaron exclusivamente dos archivos gráficos. Se conservaron sus dimensiones en píxeles y sus dimensiones, posiciones, recortes y referencias OOXML en Word. Se revisó el texto completo de ambas imágenes comparándolo con la fuente, con OCR como comprobación auxiliar y revisión visual de los seis bloques. El resto del contenido gráfico se conserva visualmente; no se afirma identidad de píxeles dentro de los dos PNG editados.

| Archivo | SHA-256 original | SHA-256 integrado | Dimensiones / resultado |
| --- | --- | --- | --- |
| `word/media/image1.png` | `950bef36cae76327912afec13b967ce7c1adfe2bbed7779f0077e09d5c08f71a` | `950bef36cae76327912afec13b967ce7c1adfe2bbed7779f0077e09d5c08f71a` | 1085 × 1450; Bytes idénticos |
| `word/media/image2.png` | `3e33388ef5f3a65ba414e63287b66d42e2e7d9e60deefa64164c3894f161247e` | `fce4427a35f2de665447b78601b6eb1e0d31ed6f51ee084ac01d9a9a702ba762` | 953 × 1651; Modificado conforme a autorización |
| `word/media/image3.png` | `5cc7b88dac54a30eb5186da90dbd3df972cbf4c02592efe2c1dca5a292e450b2` | `0d2de30316f9b5800e365bfe982264de6188fdde7209e2ffe068657daae20c28` | 979 × 1607; Modificado conforme a autorización |
| `word/media/image4.emf` | `2cbfac1f1043e7d70a350f3c33b469ce3d8d53933ab2ada6620be6407b52cb13` | `2cbfac1f1043e7d70a350f3c33b469ce3d8d53933ab2ada6620be6407b52cb13` | EMF vectorial; Bytes idénticos |

| Verificación gráfica | Resultado |
| --- | --- |
| image2.png, paso 4: responsable | RESPONSABLE: Proveeduría |
| image2.png, recuadro paso 4 | Tratamiento especial: notas de crédito y gastos sin factura. Los gastos sin factura se registran según el responsable definido en el apartado 3.4. |
| image2.png, título paso 5 | GESTIÓN DE NOTAS DE CRÉDITO |
| image2.png, responsable paso 5 | Proveeduría / Contabilidad, conservado |
| image3.png, recuadro paso 1 | Para alquileres: solicitar con mínimo 1 semana de anticipación. |
| image3.png, recuadro paso 4 | Si no hay factura, el gasto se registra en Mawi según el responsable definido en el apartado 3.4. La OC de bodega no incluye factura. |
| image3.png, responsable paso 4 | RESPONSABLE: Proveeduría |
| Ambos diagramas, asignación conjunta Proveeduría / Contabilidad en paso 4 | Cero apariciones; permanece válidamente en notas de crédito |
| Mínimo 2 días para alquileres | Cero apariciones en los diagramas integrados |
| Atribución genérica de todos los gastos sin factura a Finanzas | Eliminada; remisión al apartado 3.4 |
| Flujo automático posterior hacia QBO | Conservado |
| image1.png e image4.emf | Bytes idénticos; portada y horario no modificados |

Los textos antiguos en la columna «Texto original» del control son trazabilidad histórica, no contenido vigente del DOCX.

## F. QA visual del render

Renderizados original e integrado completos mediante LibreOffice: 23 páginas cada uno. Revisadas todas las páginas, con ampliación de las páginas afectadas y los diagramas.

| Páginas del integrado | Revisión | Resultado |
| --- | --- | --- |
| 1–2 | Portada y metadatos | Conservados; sin pérdida de portada ni cambios en datos fuente. |
| 3–5 | Alcance, Garantías, definiciones y responsabilidades | Exclusión e interfaz legibles. La expansión desplaza la última definición a página 4 y parte de una fila de responsabilidades a página 5, sin pérdida de texto. |
| 6–7 | Diagramas | Correcciones legibles; conservados seis pasos, figuras y flujo QBO. Permanece la disposición/duplicidad fuente en página 7. |
| 8–10 | Horario y enlace financiero | Horario fuente intacto; enlace financiero añadido legible en página 9. |
| 11–14 | Validación, cotización, bodega, entrega y alquileres | Nota nueva de bodega legible; resto del contenido no afectado conservado. |
| 15–18 | Facturación, sincronización, gastos manuales, notas de crédito y pagos | Responsables añadidos en 16–17; guía y campos completos; remisiones editoriales pendientes conservadas. |
| 19–20 | Tabla 3 y matriz de actividades | Cinco nuevas filas de cinco columnas legibles. Caption de Tabla 3 continúa en página 20 sin corregir su título heredado. |
| 20–21 | Tabla 5 e indicadores | Celda modificada continúa entre páginas 20–21, sin recorte/pérdida textual. Indicadores intactos. |
| 22 | Tabla 7 | Facturas y Gastos Manuales separados; fila nueva completa y legible. |
| 23 | Firmas y cierre | Conservados. |

No se detectaron nuevos desbordamientos de texto, superposiciones de celdas ni páginas completamente en blanco. Se conservan las páginas fuente de baja ocupación y la numeración general. Hay continuaciones de tablas/filas y un caption separado por paginación; no se afirma ausencia absoluta de divisiones entre páginas. No se corrigió paginación o estilo por iniciativa propia.

Los encabezados/pies heredados y la duplicidad/superposición gráfica siguen presentes deliberadamente como peinado final. Las formas/dibujos y sus posiciones OOXML son idénticos. No se reubicaron ni eliminaron imágenes o sus instancias. El bloque inferior de image2 conserva la disposición/corte fuente. Las imágenes editadas tienen las mismas dimensiones y se mantienen en el mismo espacio del Word.

## G. Elementos preservados

- Los nueve originales y los cinco DOCX aprobados se compararon byte por byte con Git HEAD antes del commit: idénticos.
- 466 de los 467 párrafos originales conservan íntegramente su árbol OOXML. El único párrafo original modificado corresponde a la celda de Tabla 5 autorizada; las demás intervenciones son adiciones.
- Propiedades/rejillas de las 20 tablas idénticas. Todas las filas originales de Tablas 3 y 7 intactas. Las demás tablas no afectadas, incluido el horario/recuadros y firmas, intactas.
- Estilos, numeración, saltos, sección, propiedades de página, encabezado/pie, relaciones y partes no afectadas: bytes idénticos.
- La guía técnica Mawi, compras, solicitudes, horarios, cotizaciones, OC, alquileres, recepciones, notas de crédito, facturas, sincronización, pagos como interfaz, matrices compatibles e indicadores se preservan.
- No se creó tabla de control de versiones, nueva estructura RACI ni responsabilidades no respaldadas.
- No se modificaron los pendientes de peinado ni se avanzó a CTO-SOP-01.

## H. Pendientes

### Revisión independiente

Pendiente de revisión independiente y aprobación de esta integración. El DOCX permanece en `01_INTEGRACION`.

### Peinado final — no corregidos

[PENDIENTE DE PEINADO FINAL – descripción de versión no presente en el documento fuente; no agregar sin validación documental]

[PENDIENTE DE PEINADO FINAL – encabezado/pie preexistente no correspondiente a PRO-SOP-01; corregir antes de oficialización]

[PENDIENTE DE PEINADO FINAL – caption de Tabla 3 heredado de gestión financiera de proyectos]

[PENDIENTE DE PEINADO FINAL – remisión interna a punto 2.5 en tratamiento de notas de crédito]

[PENDIENTE DE PEINADO FINAL – remisión interna a punto 1.1 en requisitos para el envío de facturas a Mawi]

[PENDIENTE DE PEINADO FINAL – validación documental de PRO-SOP-03-V1-2026 y FIN-INS-01-V1-2026; no sustituir códigos por inferencia]

[PENDIENTE DE PEINADO FINAL – anomalía visual/duplicidad de diagramas en la estructura fuente; no corregida durante integración]

Estos asuntos no son pendientes de integración ni nuevos hallazgos transversales. No se agregaron fechas, firmas, aprobaciones o metadatos faltantes. El ID07 se incorpora conforme a la distribución ya resuelta; no se reabre.

### Nuevos pendientes de integración

Ninguno. Las diferencias de alquileres y responsabilidades gráficas quedaron resueltas mediante los textos expresamente aprobados.
