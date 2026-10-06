# CAL-SOP-01 — Control de integración

Artefacto de auditoría; no forma parte del procedimiento oficial.

## A. Identificación y estado

- Original: `00_ORIGINALES/Manual de Procedimientos Gestión de Garantías CAL-SOP-01-V1-2025.docx`.
- SHA-256 original: `1f681d44f0591b7095bd0e2c87a5babf25658277233315fc06af5480edf0bc30`.
- Integrado: `01_INTEGRACION/CAL-SOP-01-V1-2025_INTEGRADO.docx`.
- SHA-256 integrado: `a028e16bde2bc73de1f1215dd84a6d5e0ec751f902f8cfe2e5ff55484921c90e`.
- Estado: **EN REVISIÓN – integración realizada**. Revisión independiente pendiente.
- Commit de incorporación: el commit dedicado que introduce este archivo y el DOCX; identificable mediante `git log --diff-filter=A -- 01_INTEGRACION/CAL-SOP-01-V1-2025_INTEGRADO.docx`. Su SHA se entrega al usuario. No se añade una segunda modificación para insertar un SHA autorreferente.

## B. Comparación estructural

| Medida | Original | Integrado |
| --- | --- | --- |
| Párrafos del cuerpo, incluidas celdas | 536 | 553 |
| Párrafos directos fuera de tablas | 330 | 338 |
| Tablas del cuerpo | 22 | 22 |
| Imágenes únicas del paquete | 9 | 9 |
| Secciones Word | 1 | 1 |
| Páginas renderizadas | 27 | 29 |

La diferencia de 17 párrafos corresponde a 8 párrafos directos agregados y 9 párrafos de celdas dentro de tres filas nuevas en las Tablas 2, 3 y 4. No se creó ninguna tabla. El contenido adicional y los tres ajustes de indivisibilidad de filas explican la paginación. Renderizado con LibreOffice y fuentes Montserrat.

## C. Modificaciones individuales de contenido

Las ubicaciones P corresponden a párrafos directos del original; las ubicaciones de tablas siguen el orden OOXML indicado cuando corresponde. Cada sustitución se registra por separado, incluso cuando dos afectan al mismo párrafo. Los textos originales/integrados siguientes son los fragmentos efectivamente sustituidos; las adiciones muestran su contenido completo.

| Ubicación | Tipo de cambio | Texto original | Texto integrado |
| --- | --- | --- | --- |
| Párrafo directo original P022 | MODIFICAR | todo reclamo de garantía recibido por la empresa | todo reclamo de garantía de obras entregadas recibido por la empresa |
| Alcance; después de P022 original | AGREGAR PÁRRAFO | [Párrafo inexistente] | CAL-SOP-01-V1-2025 es la fuente principal operativa para la gestión de garantías/postventa de obras entregadas. GEN-SOP-05-V1-2026 regula la custodia y el expediente; GEN-SOP-06-V1-2026 regula la administración y las reglas generales de los grupos de WhatsApp; PRO-SOP-01-V1-2026 regula el soporte logístico y abastecimiento; y CTO-SOP-01-V1-2026 regula la transición desde el cierre de obra hacia postventa. |
| Párrafo directo original P026 | MODIFICAR | Mawi (módulo de órdenes de cambio del PROYECTO #01 Mantenimiento y Reparaciones) | Mawi (módulo de órdenes de cambio de Proyecto 01 – Mantenimiento y Reparaciones) |
| Sistemas oficiales; después de P026 original | AGREGAR PÁRRAFO | [Párrafo inexistente] | Proyecto 01 – Mantenimiento y Reparaciones es un proyecto especial preexistente en el que permanecen centralizados los costos de las garantías que procedan. También puede contener determinadas reparaciones menores; CAL-SOP-01-V1-2025 regula específicamente las garantías/postventa de obras entregadas y no gobierna todas las reparaciones menores existentes en ese proyecto. |
| Canal oficial; después de P036 original | AGREGAR PÁRRAFO | [Párrafo inexistente] | La administración y las reglas generales del grupo se rigen por GEN-SOP-06-V1-2026. En el grupo del cliente participa obligatoriamente Aseguramiento de la Calidad, función ejercida por el Ingeniero de Proyecto responsable de la obra o por el ingeniero reasignado conforme a este procedimiento. Proveeduría no participa en grupos de WhatsApp directos con clientes; cuando sea necesario, su participación se limita a grupos internos como AC Garantías para coordinación logística. |
| Párrafo directo original P037 | MODIFICAR | Importante: Si no existe grupo, Aseguramiento de la Calidad debe crearlo, agregar al cliente y al personal correspondiente y explicar la finalidad del mismo. | Importante: Si no existe grupo, Aseguramiento de la Calidad debe crearlo conforme a GEN-SOP-06-V1-2026, agregar al cliente y al personal correspondiente, sin incluir a Proveeduría, y explicar la finalidad del mismo. |
| Tabla OOXML 03, fila original 3, columna 2 | MODIFICAR | Responsable integral del proceso: comunicación, recepción, registro, evaluación, seguimiento, reparación, verificación y cierre | Responsable integral del proceso de postventa: comunicación, recepción, registro, diagnóstico/evaluación, seguimiento, coordinación y supervisión de reparaciones, verificación y cierre. Esta función es ejercida ordinariamente por el mismo Ingeniero de Proyecto responsable de la obra que ejecutó el proyecto. La reasignación a otro ingeniero es excepcional y solo procede si el Ingeniero responsable dejó la empresa o se encuentra no disponible; la gestiona Gerencia de Proyectos. |
| Tabla OOXML 03, fila original 4, columna 2 | MODIFICAR | Aprueba órdenes de cambio en Mawi; consulta en casos de escalamiento técnico o comercial; supervisa y audita el proceso; Atender restricciones con garantías | Aprueba órdenes de cambio en Mawi; consulta en casos de escalamiento técnico o comercial; supervisa y audita el proceso; Atender restricciones con garantías. Gerencia de Proyectos gestiona la reasignación excepcional del Ingeniero responsable cuando este dejó la empresa o se encuentra no disponible. |
| Tabla 2 — nueva fila Proveeduría, después de Ingeniería | AGREGAR FILA | [Fila inexistente] | Columna 1: Proveeduría<br>Columna 2: Soporte exclusivamente logístico interno, cuando corresponda: compra de materiales, retiro/suministro de materiales de bodega, alquiler de equipos, limpiezas y retiro de residuos/escombros, conforme a PRO-SOP-01-V1-2026. No decide la procedencia de garantías, no administra el caso, no dirige técnicamente la reparación y no participa en grupos de WhatsApp directos con clientes. |
| Tabla OOXML 03, fila original 6, columna 1 | MODIFICAR | Subcontratistas y mano de obra | Maestro de Obra, cuadrillas/mano de obra y Subcontratistas |
| Tabla OOXML 03, fila original 6, columna 2 | MODIFICAR | Ejecutan reparaciones en los casos que les sean atribuidos | Ejecutan las reparaciones físicas que les sean atribuidas, cuando aplique, bajo coordinación y supervisión de Aseguramiento de la Calidad. |
| 1.1 — recuadro de canal oficial (tabla OOXML 5) | MODIFICAR | Importante: Si no existe grupo, Aseguramiento de la Calidad debe crearlo, agregar al cliente y al personal correspondiente y explicar la finalidad del mismo. | Importante: Si no existe grupo, Aseguramiento de la Calidad debe crearlo conforme a GEN-SOP-06-V1-2026, agregar al cliente y al personal correspondiente, sin incluir a Proveeduría, y explicar la finalidad del mismo. |
| Párrafo directo original P062 | MODIFICAR | Se reciba el reclamo de garantía y se dé el acuse de recibo. | Se reciba el reclamo de garantía y se emitan, como hitos separados, el acuse operativo en WhatsApp y el acuse de recibo formal. |
| Párrafo directo original P070 | MODIFICAR | seis (6) | siete (7) |
| Tabla OOXML 06, fila original 3, columna 1 | MODIFICAR | Acuse de recibo | Acuse de recibo formal |
| Tabla OOXML 06, fila original 3, columna 2 | MODIFICAR | 2 días hábiles post- reclamo del cliente | Máximo 1 día hábil post-reclamo |
| Tabla OOXML 06, fila original 3, columna 3 | MODIFICAR | Confirmar que el reclamo fue recibido y que el caso fue abierto para su atención. | Confirmar que el reclamo fue recibido, que se abrió el caso para análisis técnico y que continuará la evaluación/inspección correspondiente. |
| Tabla OOXML 06, fila original 5, columna 2 | MODIFICAR | 3 días hábiles post-visita | Máximo 3 días hábiles post-visita |
| Tabla OOXML 06, fila original 6, columna 2 | MODIFICAR | 3 días hábiles desde último contacto | Cada 3 días hábiles en casos activos |
| Tabla 3 — nueva fila Acuse operativo en WhatsApp, después de Respuesta general | AGREGAR FILA | [Fila inexistente] | Columna 1: Acuse operativo en WhatsApp<br>Columna 2: Máximo 1 hora durante horario laboral<br>Columna 3: Responder o confirmar operativamente la lectura del mensaje en el grupo oficial conforme a GEN-SOP-06-V1-2026. No constituye la apertura formal del caso. |
| 1.3 — título nuevo sin letra, antes de 1.3.A | AGREGAR PÁRRAFO | [Párrafo inexistente] | Acuse operativo en WhatsApp |
| 1.3 — explicación del acuse operativo, antes de 1.3.A | AGREGAR PÁRRAFO | [Párrafo inexistente] | Aplica: Al recibir un mensaje del cliente relacionado con una garantía, se debe responder o confirmar operativamente su lectura en el grupo oficial en un máximo de 1 hora durante horario laboral, conforme a GEN-SOP-06-V1-2026. Este acuse no constituye la apertura formal del caso y no sustituye la respuesta sustantiva general del mismo día ni el acuse de recibo formal. |
| Párrafo directo original P079 | MODIFICAR | Acuse de recibo | Acuse de recibo formal |
| Párrafo directo original P080 | MODIFICAR | Aplica: Cuando el cliente presenta un nuevo reclamo o reporta formalmente una situación que requiere apertura y análisis del caso. Se debe responder en un plazo de 2 días hábiles. | Aplica: Cuando el cliente presenta un nuevo reclamo o reporta formalmente una situación que requiere apertura y análisis del caso. Se debe emitir el acuse de recibo formal en un plazo máximo de 1 día hábil posterior al reclamo. |
| Párrafo directo original P083 | MODIFICAR | Indicación de que el caso fue abierto para atención y análisis. | Indicación de que el caso fue abierto para análisis técnico. |
| Párrafo directo original P084 | MODIFICAR | Referencia a la próxima gestión prevista. | Indicación de que continuará la evaluación/inspección correspondiente. |
| Párrafo directo original P122 | MODIFICAR | Al recibir el reclamo, el responsable debe: | Al recibir el reclamo, el Ingeniero de Proyecto responsable de la obra, actuando como Aseguramiento de la Calidad, o el ingeniero formalmente reasignado por Gerencia de Proyectos conforme a este procedimiento, debe: |
| 2.1 — paso nuevo antes del acuse formal (P123 original) | AGREGAR PÁRRAFO | [Párrafo inexistente] | Emitir el acuse operativo en WhatsApp en un máximo de 1 hora durante horario laboral, conforme a GEN-SOP-06-V1-2026. Este acuse no constituye la apertura formal del caso. |
| Párrafo directo original P123 | MODIFICAR | Brindar un acuse de recibo al cliente (ver punto 1.3.B). | Brindar el acuse de recibo formal al cliente en un máximo de 1 día hábil posterior al reclamo (ver punto 1.3.B). |
| Párrafo directo original P155 | MODIFICAR | Si el caso procede, corresponde realizar la apertura de la orden de cambio en Mawi para gestionar todos los costos relacionados al caso en atención. Para ello, el responsable deberá: | Si el caso procede, corresponde realizar la apertura de la orden de cambio en Mawi para gestionar todos los costos relacionados al caso en atención. Para ello, el Ingeniero de Proyecto responsable de la obra, actuando como Aseguramiento de la Calidad, o el ingeniero formalmente reasignado conforme a este procedimiento, deberá: |
| Párrafo directo original P156 | MODIFICAR | Dirigirse al “PROYECTO #01 Mantenimiento y Reparaciones”. | Dirigirse a Proyecto 01 – Mantenimiento y Reparaciones, proyecto especial preexistente. |
| 2.4 — coordinación logística, después de P164 original | AGREGAR PÁRRAFO | [Párrafo inexistente] | Los materiales, compras, retiro/suministro de bodega, alquileres y demás apoyo logístico que correspondan se coordinan con Proveeduría conforme a PRO-SOP-01-V1-2026. |
| Párrafo directo original P192 | MODIFICAR | El encargado de garantías no deberá ejecutar directamente las reparaciones, salvo en casos excepcionales debidamente justificados. | Aseguramiento de la Calidad, función ejercida por el Ingeniero de Proyecto responsable de la obra o por el ingeniero formalmente reasignado conforme a este procedimiento, no deberá ejecutar directamente las reparaciones, salvo en casos excepcionales debidamente justificados. |
| Párrafo directo original P192 | MODIFICAR | el encargado de garantías deberá proceder de la siguiente manera: | Aseguramiento de la Calidad deberá proceder de la siguiente manera: |
| Párrafo directo original P195 | MODIFICAR | Delegar la ejecución y retirarse del sitio para continuar con sus labores operativas. | Delegar la ejecución física al Maestro de Obra, cuadrillas/mano de obra o Subcontratistas, manteniendo Aseguramiento de la Calidad la coordinación, supervisión y verificación de los trabajos. |
| 3.2 — paso nuevo después de delegación P195 original | AGREGAR PÁRRAFO | [Párrafo inexistente] | Solicitar a Proveeduría los materiales necesarios, conforme a PRO-SOP-01-V1-2026. |
| Párrafo directo original P281 | MODIFICAR | Guardar en la sección correspondiente del AMPO del proyecto documentos relevantes generados durante el proceso, tales como informes, fotografías, evidencias o mensajes importantes.  | Guardar en la sección correspondiente del AMPO del proyecto documentos relevantes generados durante el proceso, tales como informes, fotografías, evidencias o mensajes importantes. La custodia documental del AMPO en Proyectos Garantía se rige por GEN-SOP-05-V1-2026. |
| Párrafo directo original P282 | MODIFICAR | Verificar que los costos fueron correctamente asociados a la orden de cambio correspondiente en Mawi. | Verificar que los costos fueron correctamente asociados a la orden de cambio correspondiente en Mawi, dentro de Proyecto 01 – Mantenimiento y Reparaciones. |
| Tabla OOXML 19, fila original 3, columna 1 | MODIFICAR | Acuse de recibo | Acuse de recibo formal |
| Tabla OOXML 19, fila original 3, columna 2 | MODIFICAR | Enviado dentro del plazo de 2 días hábiles | Emitido en máximo 1 día hábil posterior al reclamo |
| Tabla OOXML 19, fila original 3, columna 3 | MODIFICAR | Mensaje en WhatsApp con fecha | Mensaje/registro formal de apertura |
| Tabla OOXML 19, fila original 3, columna 4 | MODIFICAR | Acuse tardío o inexistente | Acuse formal tardío o inexistente |
| Tabla OOXML 19, fila original 5, columna 2 | MODIFICAR | Orden de cambio creada adecuadamente | Orden de cambio creada adecuadamente y activa en Proyecto 01 – Mantenimiento y Reparaciones |
| Tabla OOXML 19, fila original 5, columna 3 | MODIFICAR | Orden de cambio en Mawi con código equivalente al consecutivo de la orden | Orden de cambio en Proyecto 01 – Mantenimiento y Reparaciones, con código equivalente al consecutivo de la orden |
| Tabla OOXML 19, fila original 7, columna 4 | MODIFICAR | Último contacto con más de 3 días sin mensaje (en rojo) | Último contacto con más de 3 días hábiles sin mensaje (en rojo) |
| Tabla OOXML 19, fila original 9, columna 2 | MODIFICAR | Costos imputados correctamente | Costos imputados correctamente a la Orden de Cambio correspondiente dentro de Proyecto 01 – Mantenimiento y Reparaciones |
| Tabla OOXML 19, fila original 9, columna 3 | MODIFICAR | OC refleja todos los costos operativos de la garantía | La Orden de Cambio correspondiente dentro de Proyecto 01 refleja todos los costos operativos de la garantía |
| Tabla OOXML 19, fila original 11, columna 2 | MODIFICAR | Archivo contiene documentos del caso | Archivo contiene los documentos del caso; la ubicación y custodia documental del AMPO se mantienen conforme a GEN-SOP-05-V1-2026, incluida su ubicación en «Proyectos Garantía» cuando corresponda. |
| Tabla 4 — nueva fila Acuse operativo en WhatsApp, después de Registro inicial | AGREGAR FILA | [Fila inexistente] | Columna 1: Acuse operativo en WhatsApp<br>Columna 2: Enviado en máximo 1 hora durante horario laboral<br>Columna 3: Mensaje en el grupo oficial conforme a GEN-SOP-06-V1-2026<br>Columna 4: Falta de acuse operativo dentro del plazo |
| Párrafo directo original P300 | MODIFICAR | Módulo de Órdenes de Cambio en Proyecto #01 Mantenimiento y Reparaciones | Módulo de Órdenes de Cambio en Proyecto 01 – Mantenimiento y Reparaciones |

## D. Ajustes exclusivamente de formato

| Ubicación | Tipo de cambio | Texto original | Texto integrado |
| --- | --- | --- | --- |
| Tabla 4 (OOXML 19), fila Costos en Mawi, fila integrada 10 | FORMATO | Fila divisible entre páginas; contenido sin cambios | w:cantSplit activado; contenido sin cambios |
| Tabla 3 — Acuse de recibo formal; tabla OOXML 6, fila integrada 4 | FORMATO | Fila divisible entre páginas; contenido sin cambios | w:cantSplit activado; contenido sin cambios |
| 1.3.E — recuadro del ejemplo de seguimiento; tabla OOXML 11, fila integrada 1 | FORMATO | Fila divisible entre páginas; contenido sin cambios | w:cantSplit activado; contenido sin cambios |

## E. Elementos preservados

Se compararon todas las partes del ZIP: únicamente cambió `word/document.xml`. Estilos, numeración, relaciones, nueve imágenes, diagramas, encabezados, pies y demás partes permanecen idénticos byte a byte. En el cuerpo, al retirar las adiciones y restituir los fragmentos autorizados y las tres propiedades de formato, la comparación OOXML canónica coincide con el original. Se conservan tablas y dimensiones de columnas, saltos de página y sección, anexos, dashboard, rutas y contenido no afectado. Metadatos, involucrados, indicadores y sus fórmulas, objetivo y marco normativo permanecen intactos. No se creó RACI, anexo, control de versiones ni campo Año. No se modificó ningún DOCX original ni GEN-SOP-05.

## F. QA textual

| Término buscado | Apariciones en texto editable |
| --- | --- |
| 2 días hábiles | 0 |
| encargado de garantías | 1 |
| retirarse del sitio | 0 |
| RACI | 0 |
| Proveeduría | 6 |
| Proyecto 01 | 9 |
| 1 hora | 4 |
| 1 día hábil | 4 |
| 3 días hábiles | 9 |
| casos excepcionales debidamente justificados | 1 |

Residuos examinados individualmente:

- **«2 días hábiles»**: ninguna aparición en texto editable; una aparición gráfica en Figura 1, página 3, `word/media/image2.png`, asociada a recepción/acuse. Incompatible con el nuevo acuse formal de máximo 1 día hábil. Se conserva por la instrucción de no modificar diagramas; pendiente explícito abajo.
- **«encargado de garantías»**: una aparición editable en 2.1, párrafo 213 del cuerpo integrado incluyendo celdas: «Este reporte debe ser realizado o, en su defecto, remitido por el encargado de garantías, al canal oficial de comunicación.» Es contenido fuente fuera de las reglas modificadas de 3.2; válido por la identificación del rol en Tabla 2 y la regla de recepción, sin reinterpretación adicional. No permanece en las reglas modificadas de 3.2.
- **«retirarse del sitio»**: ninguna aparición editable ni residuo visual identificado.

Se verificaron el rol integral de Aseguramiento de la Calidad, el mismo Ingeniero de Proyecto de la obra y la reasignación por salida/no disponibilidad gestionada por Gerencia de Proyectos; Ingeniería consultiva y Proveeduría exclusivamente logística interna, excluida de chats con clientes. La ejecución física se delega a Maestro de Obra, cuadrillas/mano de obra o Subcontratistas, conservando coordinación, supervisión y verificación. Se conservan la excepción debidamente justificada y el umbral de más de una (1) hora.

El texto editable distingue acuse operativo máximo 1 hora laboral, respuesta general el mismo día, acuse formal máximo 1 día hábil, resultados máximo 3 días hábiles post-visita y seguimiento cada 3 días hábiles en casos activos. Proyecto 01 mantiene la centralización de costos y órdenes de cambio, como proyecto especial preexistente; CAL no se extiende a todas sus reparaciones menores. Los pasos nativos de Mawi se conservaron sin inventar pasos nuevos.

## G. QA visual

Se renderizaron y revisaron **todas las páginas 1–29** del integrado, comparando las páginas afectadas con el original de 27 páginas. Las filas nuevas de Tablas 2, 3 y 4 respetan el formato y número de columnas nativos. Se conservaron imágenes, diagramas, dashboard, anexos, encabezados y pies. No se detectaron páginas en blanco anormales; la paginación es razonable para el contenido incorporado.

Los únicos ajustes visuales realizados son los tres `w:cantSplit` individualizados en D, para impedir cortes internos de filas. No alteran textos ni dimensiones. Las tablas afectadas no presentan deformaciones ni texto nuevo fuera de sus celdas.

**Limitación visual preexistente:** en Tabla 5 de indicadores, dos fórmulas se recortan en el renderizado dentro del límite derecho de la celda. Se observa también en el original, página 22; en el integrado está en página 23. Se verificó que el OOXML de indicadores/fórmulas permanece idéntico. No se alteró, dada la instrucción de conservar indicadores. Por ello no se afirma ausencia global de recorte; no se atribuye a la integración ni se inventa un cambio de contenido.

## H. Pendientes

1. Revisión independiente de la integración de CAL-SOP-01.
2. **[NUEVO PENDIENTE DE INTEGRACIÓN] — Figura 1, página 3:** el plazo gráfico «2 días hábiles» junto al acuse requiere una decisión/autorización específica para actualizar el diagrama y representar correctamente la distinción entre acuse operativo y formal. No se corrigió por inferencia; la imagen permanece idéntica al original.

La limitación de renderizado de indicadores se registra en G para decisión de revisión, sin modificar los indicadores ni convertirla en un hallazgo de proceso. No se resolvieron pendientes institucionales de otros procedimientos. CAL permanece en `01_INTEGRACION`; no se avanzó a GEN-SOP-06.
