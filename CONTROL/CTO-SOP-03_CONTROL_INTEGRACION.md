# CTO-SOP-03 — Control de integración

Artefacto de auditoría; no forma parte del procedimiento oficial.

## A. Identificación y estado

**CTO-SOP-03: EN REVISIÓN – integración realizada.** Pendiente de revisión independiente y aprobación. No oficializado.

Fecha: 14/10/2026 (America/Costa_Rica).

Fuente exclusiva: `00_ORIGINALES/CTO-SOP-03-V1-2026 - Procedimiento de Comunicación Financiera de Proyectos de Construcción.docx`.

Salida: `01_INTEGRACION/CTO-SOP-03-V1-2026_INTEGRADO.docx`.

SHA-256 original: `fc8cfdd530454965fb59aa20b955670b2ba43f317c6853c5b2ee2b9508c19068`.

SHA-256 integrado: `a9dfaf9345ffc77eb663731b39385f7868f90426a93298b43636c7097dd7ff5b`.

Base Git: `707c60e56e9450846079b1ff3a03cbf72680cce5`. Commit de incorporación: el commit dedicado que añade este control y el integrado; se obtiene con `git log --diff-filter=A --format=%H -- 01_INTEGRACION/CTO-SOP-03-V1-2026_INTEGRADO.docx`. Se entrega su SHA en la respuesta, evitando una referencia circular dentro del propio commit.

Prevalecen las dos correcciones finales: eliminación de «Procesar el pago» de RACI sin sustituirla, y delimitación de Figura 3, introducción y caption al ciclo ordinario ≤ ₡1.000.000.

## B. Comparación estructural

| Elemento | Original | Integrado |
| --- | ---: | ---: |
| Párrafos cuerpo, incluidas celdas | 416 | 438 |
| Párrafos directos cuerpo | 209 | 214 |
| Párrafos con encabezados/pies/notas | 423 | 445 |
| Tablas cuerpo | 23 | 23 |
| Tablas encabezado/pie | 1 | 1 |
| Filas tablas cuerpo | 76 | 80 |
| Imágenes word/media | 5 | 5 |
| Comentarios Word | 0 | 0 |
| Secciones | 1 | 1 |
| Encabezados/pies | 2 | 2 |
| Páginas renderizadas | 21 | 22 |

Conteos OOXML. Párrafos totales incluyen los separadores/notas sin texto. Diferencia de cuerpo: cinco párrafos nuevos; cuatro filas RACI nuevas (+20 párrafos) y eliminación de la fila «Procesar el pago» (−5); una fila nueva de dos celdas en Anexo C (+2): total +22 párrafos. Filas: +3 netas en RACI y +1 en Anexo C. No se creó ninguna tabla. La RACI contiene encabezado + exactamente ocho actividades.

Las propiedades `tblPr` y `tblGrid`, incluidos anchos de columnas, permanecen idénticas en todas las tablas. Se modificaron celdas existentes y se clonaron filas compatibles; no se reconstruyeron tablas completas.

| Tabla OOXML (orden físico, no caption) | Filas original | Filas integrado | Columnas original/integrado |
| --- | ---: | ---: | --- |
| 1 | 7 | 7 | 4 / 4 |
| 2 | 10 | 10 | 2 / 2 |
| 3 | 8 | 8 | 2 / 2 |
| 4 | 6 | 9 | 5 / 5 |
| 5 | 2 | 2 | 4 / 4 |
| 6 | 1 | 1 | 1 / 1 |
| 7 | 2 | 2 | 4 / 4 |
| 8 | 1 | 1 | 1 / 1 |
| 9 | 4 | 4 | 4 / 4 |
| 10 | 1 | 1 | 2 / 2 |
| 11 | 1 | 1 | 2 / 2 |
| 12 | 1 | 1 | 2 / 2 |
| 13 | 1 | 1 | 1 / 1 |
| 14 | 2 | 2 | 4 / 4 |
| 15 | 1 | 1 | 1 / 1 |
| 16 | 4 | 4 | 3 / 3 |
| 17 | 1 | 1 | 1 / 1 |
| 18 | 2 | 2 | 4 / 4 |
| 19 | 5 | 5 | 4 / 4 |
| 20 | 1 | 1 | 2 / 2 |
| 21 | 4 | 4 | 2 / 2 |
| 22 | 7 | 8 | 2 / 2 |
| 23 | 4 | 4 | 2 / 2 |

Partes modificadas: únicamente `word/document.xml` y `word/media/image4.png`. Todas las demás partes tienen bytes idénticos, incluidos estilos, numeración, relaciones, encabezado, pie, configuración, notas y demás recursos gráficos. Se conservan las dimensiones y posición OOXML de las imágenes.

## C. Cambios individuales

P identifica párrafos directos del original, sin contar celdas. Tablas OOXML: orden físico. Cada celda modificada y cada fila nueva se identifica por separado.

| Ubicación | Tipo | Original | Integrado |
| --- | --- | --- | --- |
| Tabla OOXML 3, fila 3, columna 2 | MODIFICAR | Comunicar oportunamente el estado financiero del proyecto al Departamento Financiero; Mantener actualizada y vigente la información operativa del proyecto en los sistemas y archivos requeridos. | Comunicar oportunamente el estado financiero del proyecto al Departamento Financiero, notificar los pagos requeridos dentro de las ventanas autorizadas y aprobar previamente las horas y montos de mano de obra a ejecutar. Mantener actualizada y vigente la información operativa del proyecto en los sistemas y archivos requeridos. |
| Tabla OOXML 3, fila 7, columna 2 | MODIFICAR | Gestionar la información de costos de mano de obra del proyecto. | Gestionar la información de costos de mano de obra del proyecto y ejecutar el registro del gasto manual de mano de obra en Mawi, aplicando la guía técnica de PRO-SOP-01-V1-2026. |
| Tabla OOXML 3, fila 5, columna 2 | MODIFICAR | Autorizar excepciones en pagos y resolver asuntos escalados. | Resolver asuntos escalados y autorizar formalmente, de manera exclusiva, excepciones para procesar pagos fuera de lineamientos dentro del ciclo en curso. |
| Tabla 3 — Procesar el pago | ELIMINAR | Procesar el pago &#124; Departamento Financiero &#124; Gerencia General &#124; — &#124; Ingeniero de Proyecto |  |
| Tabla OOXML 4, fila 4, columna 1 | MODIFICAR | Notificar pagos dentro de la ventana lunes–miércoles | Notificar pagos ordinarios (≤ ₡1.000.000), a más tardar el jueves a las 12:00 md |
| Matriz RACI, fila nueva | AGREGAR |  | Notificar pagos mayores a ₡1.000.000, con al menos 1 semana de anticipación &#124; Ingeniero de Proyecto &#124; Gerencia de Proyectos &#124; — &#124; Departamento Financiero |
| Matriz RACI, fila nueva | AGREGAR |  | Notificar pagos de subcontratos, con al menos 2 semanas de anticipación en flujo de caja &#124; Ingeniero de Proyecto &#124; Gerencia de Proyectos &#124; — &#124; Departamento Financiero |
| Matriz RACI, fila nueva | AGREGAR |  | Autorizar excepción de pago fuera de lineamientos en el ciclo en curso &#124; — &#124; Gerencia General &#124; — &#124; Departamento Financiero / Ingeniero de Proyecto |
| Matriz RACI, fila nueva | AGREGAR |  | Registrar gasto manual de Mano de Obra en Mawi. Ref.: PRO-SOP-01-V1-2026 &#124; Recursos Humanos &#124; Ingeniero de Proyecto (aprueba horas y montos) &#124; — &#124; Departamento Financiero |
| Tabla OOXML 16, fila 2, columna 2 | MODIFICAR | Misma semana (lun–jue 12 md) | Hasta jueves 12:00 md de la misma semana |
| Tabla OOXML 16, fila 2, columna 3 | MODIFICAR | Se procesa dentro del ciclo de pagos en que se notifica. | Se procesa dentro del ciclo ordinario de esa semana cuando cumple el cierre. Incluye las OC generadas por Proveeduría el jueves AM que se notifiquen antes del corte. |
| Tabla OOXML 16, fila 3, columna 2 | MODIFICAR | 1 semana | Mínimo 1 semana |
| Tabla OOXML 16, fila 4, columna 2 | MODIFICAR | 2 semanas | Mínimo 2 semanas |
| P134 fuente | MODIFICAR | Pagos menores a ₡1.000.000: Se deben notificar al Departamento Financiero entre lunes y miércoles de cada semana. | Los pagos ordinarios de monto ≤ ₡1.000.000 deben notificarse al Departamento Financiero a más tardar el jueves a las 12:00 md para ingresar al ciclo ordinario de pagos de esa misma semana. |
| Después de 134 | AGREGAR |  | Las Órdenes de Compra generadas por Proveeduría los jueves por la mañana pueden ingresar al ciclo ordinario de esa misma semana siempre que la notificación correspondiente se complete antes del cierre del jueves a las 12:00 md. |
| P186 fuente | MODIFICAR | La Gerencia General dará seguimiento al caso y determinará si el pago se incluye en el ciclo de la semana en curso o se pospone hasta el siguiente ciclo de pagos. | El pago ordinario de monto ≤ ₡1.000.000 notificado después del jueves a las 12:00 md pasa al siguiente ciclo semanal ordinario. |
| Después de 186 | AGREGAR |  | El pago mayor a ₡1.000.000 notificado sin una semana de anticipación pasa al primer ciclo que permita cumplir la anticipación mínima de una semana. |
| Párrafo añadido | AGREGAR |  | El pago de subcontratos notificado sin dos semanas de anticipación pasa al primer ciclo que permita cumplir las dos semanas de anticipación. |
| Párrafo añadido | AGREGAR |  | La Gerencia General dará seguimiento al caso. Únicamente la Gerencia General puede autorizar formalmente que un pago fuera de lineamientos sea procesado dentro del ciclo en curso. |
| Después de 174 | AGREGAR |  | El Ingeniero de Proyecto aprueba previamente las horas y montos de mano de obra. Recursos Humanos registra el gasto manual correspondiente en Mawi conforme a PRO-SOP-01-V1-2026 y gestiona su incorporación a la Tabla de Pagos según el flujo vigente. |
| P122 fuente | MODIFICAR | En la siguiente figura se observa el flujo de la notificación de pagos del Departamento de Construcción. | En la siguiente figura se observa el flujo ordinario de notificación de pagos de monto ≤ ₡1.000.000 del Departamento de Construcción. |
| Figura 3 — caption | MODIFICAR | Figura 3. Pasos para la notificación de pagos al Departamento Financiero. | Figura 3. Pasos para la notificación de pagos ordinarios (≤ ₡1.000.000) al Departamento Financiero. |
| Tabla OOXML 22, fila 3, columna 2 | MODIFICAR | Notificar a Departamento Financiero, a través de Mawi, los pagos a incluir en la Tabla de Pagos con la debida anticipación según el monto | Notificar al Departamento Financiero, a través de Mawi, los pagos ordinarios (≤ ₡1.000.000) a más tardar el jueves a las 12:00 md. Las OC generadas el jueves AM pueden ingresar al ciclo de esa semana cuando cumplan el cierre. |
| Anexo C — fila nueva | AGREGAR |  | ☐ &#124; Notificar pagos mayores a ₡1.000.000 con al menos 1 semana de anticipación y pagos de subcontratos con al menos 2 semanas de anticipación en el flujo de caja. |
| Figura 3 — word/media/image4.png, título | MODIFICAR | FLUJO DE NOTIFICACIÓN DE PAGOS AL DEPARTAMENTO FINANCIERO | FLUJO DE NOTIFICACIÓN DE PAGOS ORDINARIOS (≤ ₡1.000.000) AL DEPARTAMENTO FINANCIERO |

## D. RACI final

Las cinco columnas nativas permanecen. No se añadieron asignaciones fuera del paquete.

| Actividad | Responsable | Aprueba | Consulta | Informa |
| --- | --- | --- | --- | --- |
| Comunicar la información financiera del proyecto | Ingeniero de Proyecto | Gerencia de Proyectos | — | Departamento Financiero |
| Evaluar el impacto financiero | Departamento Financiero | Gerencia General | Gerencia de Proyectos | Ingeniero de Proyecto |
| Notificar pagos ordinarios (≤ ₡1.000.000), a más tardar el jueves a las 12:00 md | Ingeniero de Proyecto | Gerencia de Proyectos | — | Departamento Financiero |
| Notificar pagos mayores a ₡1.000.000, con al menos 1 semana de anticipación | Ingeniero de Proyecto | Gerencia de Proyectos | — | Departamento Financiero |
| Notificar pagos de subcontratos, con al menos 2 semanas de anticipación en flujo de caja | Ingeniero de Proyecto | Gerencia de Proyectos | — | Departamento Financiero |
| Autorizar excepción de pago fuera de lineamientos en el ciclo en curso | — | Gerencia General | — | Departamento Financiero / Ingeniero de Proyecto |
| Gestionar órdenes de modificación y subcontratos | Ingeniero de Proyecto | Gerencia de Proyectos | — | Departamento Financiero / Gerencia General |
| Registrar gasto manual de Mano de Obra en Mawi. Ref.: PRO-SOP-01-V1-2026 | Recursos Humanos | Ingeniero de Proyecto (aprueba horas y montos) | — | Departamento Financiero |

«Procesar el pago» fue eliminado exclusivamente de la matriz. Las funciones de Finanzas de gestionar/procesar pagos permanecen en Tabla 2, sección 4.2 y flujo operativo.

## E. QA textual

Búsqueda de cadenas sin distinción de mayúsculas en el texto editable del documento; las imágenes se verifican separadamente. Los conteos no incluyen esta explicación ni la transcripción auxiliar de imágenes.

| Cadena | Coincidencias |
| --- | ---: |
| lunes–miércoles | 0 |
| lunes-miércoles | 0 |
| lunes y miércoles | 0 |
| entre lunes y miércoles | 0 |
| Misma semana (lun–jue 12 md) | 0 |
| jueves a las 12:00 md | 5 |
| ₡1.000.000 | 12 |
| 1 semana | 3 |
| 2 semanas | 3 |
| Procesar el pago | 0 |
| Autorizar excepción | 1 |
| Gerencia General | 10 |
| PRO-SOP-01-V1-2026 | 3 |
| gasto manual | 3 |
| B-Sides | 0 |
| B – Sides | 1 |
| Manual Operativo del Asistente Administrativo | 0 |

- Antigua ventana lunes–miércoles: cero. Reunión de los lunes, comprobantes de los lunes y textos gráficos legítimos conservados.
- Pagos ordinarios ≤ ₡1.000.000: jueves 12:00 md; OC del jueves AM incluidas si cumplen corte.
- Pagos mayores a ₡1.000.000: una semana; subcontratos: dos semanas. No se aplica la ventana ordinaria a estas categorías.
- Fuera de lineamientos: ordinario al siguiente ciclo semanal; especiales al primer ciclo que cumpla su anticipación. Excepción en ciclo actual exclusivamente por Gerencia General.
- Mano de obra: Ingeniero aprueba horas/montos; RRHH registra en Mawi conforme a PRO y gestiona Monday. No digitación asignada al Ingeniero.
- B-Sides conserva la grafía fuente «B – Sides» y aparece únicamente en ferreterías, no en Gastos Manuales.
- Manual Operativo del AA: cero. No se agrega sección de tarjetas ni pendiente local ID12.
- Anexo C: revisión financiera intacta, ventana ordinaria sustituida, nueva fila de anticipaciones especiales; cuatro controles restantes íntegros.
- Se comprobó cobertura de todos los nodos `w:t` del cuerpo/encabezado/pie/notas en la extracción. Fórmulas OMML se transcriben sin cambiar el DOCX. Se incluye transcripción separada del texto gráfico y los registros de texto del EMF histórico sin recalcular montos.

## F. QA gráfico

Se utilizó edición de imagen para obtener el título aprobado y se compuso únicamente un parche interior del recuadro del título sobre el PNG original. No se utilizó el cuerpo regenerado de la imagen. Comparación de píxeles: todos los píxeles fuera de x=125..1274, y=23..128 permanecen exactamente iguales. Se conserva el borde del recuadro original y toda la figura inferior: iconos, flechas, responsables, ventanas y textos. La región interior del título contiene la nueva tipografía y su fondo azul; no se afirma identidad de píxeles dentro de ese parche.

Dimensiones de image4: 1431 × 955 antes/después. Densidad PNG conservada: 86,61 píxeles/cm, aproximadamente 220 dpi. Título comprobado visualmente, incluidos ≤, ₡ y 1.000.000. No se agregaron plazos de 1/2 semanas a la imagen. Figura 3 legible en el render final, página 14.

| Recurso | SHA-256 original | SHA-256 integrado | Dimensiones y resolución |
| --- | --- | --- | --- |
| word/media/image1.png | `3a520bb540602f07603c2e6d2ff0883e7f30ec2de6ab769c6a91aedd09b57830` | `3a520bb540602f07603c2e6d2ff0883e7f30ec2de6ab769c6a91aedd09b57830` | [1076, 1461] → [1076, 1461]; dpi None → None |
| word/media/image2.png | `f9956e7f2356d0779ebb5d9d73840bbaaaf644fbfda640df6ddceeef542a1d91` | `f9956e7f2356d0779ebb5d9d73840bbaaaf644fbfda640df6ddceeef542a1d91` | [971, 1619] → [971, 1619]; dpi None → None |
| word/media/image3.png | `19f4d29b9e5f2c6086508414f1c6b41d17586fc10d726532e48244f7afa448b7` | `19f4d29b9e5f2c6086508414f1c6b41d17586fc10d726532e48244f7afa448b7` | [1216, 1294] → [1216, 1294]; dpi None → None |
| word/media/image4.png | `b5d030fbd21fdf4a58e59eb5a5fdd78d147b55669a60abdb4101e5025fb32f0f` | `424f163a7eeabca0ea8998142ddc1c121b84cb2dfbcc1bb021969c8e49ad2c3d` | [1431, 955] → [1431, 955]; dpi [219.9894, 219.9894] → [219.9894, 219.9894] |
| word/media/image5.emf | `8e6b900039dfb343cb2b76bd21c1eb591e9a7ddee739cb86855c4dcc8c5a857a` | `8e6b900039dfb343cb2b76bd21c1eb591e9a7ddee739cb86855c4dcc8c5a857a` | EMF vectorial; bounds [0, 0, 1188, 317]; marco 0,01 mm [0, 0, 21303, 5683]; sin DPI raster aplicable |

Ubicaciones: image1.png portada página 1; image2.png Figura 1 página final 7; image3.png Figura 2 página final 11; image4.png Figura 3 página final 14; image5.emf Anexo A página final 20. La correspondencia con páginas fuente es portada 1, Figura 1 en 6, Figura 3 en 13 y Anexo A en 19; la refluencia modifica páginas, no contenidos de los gráficos preservados.

**Ninguna imagen distinta de Figura 3 fue modificada.** image2.png, image3.png, portada y EMF de Anexo A son byte-idénticos.

## G. QA visual

Render original: 21 páginas. Render integrado: 22 páginas. Revisadas visualmente todas las páginas finales **1–22**, además de las imágenes originales e image4 final. La expansión de Tabla 2, RACI y textos aprobados redistribuye contenido. No se modificaron saltos, márgenes, anchos, estilos ni numeración para efectuar peinado.

- Páginas 1–3: portada, metadatos, objetivo, alcance, definiciones y sistemas preservados.
- Páginas 4–5: Tabla 2 y RACI legibles. Primera fila RACI continúa entre páginas 4 y 5 sin pérdida de texto; ocho actividades verificadas.
- Páginas 6–13: flujo y estados preservados; espacios amplios por la colocación de imágenes/saltos fuente. Figura 1 conserva caption en página siguiente. Figura 2 y caption quedan juntos en página 11 por refluencia, sin editar sus propiedades.
- Página 14: introducción, título gráfico y caption de Figura 3 delimitan los pagos ordinarios. No hay recorte ni deformación del gráfico.
- Páginas 15–17: Tabla 5, 3.2, 3.3, 3.6, OM y comprobantes revisados. Las obligaciones nuevas quedan legibles; desarrollo técnico de subcontratos idéntico.
- Páginas 18–19: 4.1 diferencia los tres destinos de pagos tardíos. Funciones de Finanzas intactas. Cuatro indicadores/fórmulas con OOXML idéntico. Recorte de fórmula de mano de obra preexistente conservado. El encabezado de la tabla ahora queda con sus filas por refluencia; el título 4.3 queda al final de página 18.
- Páginas 20–21: Anexo A y B intactos; Anexo C completo, con sus dos últimas filas en página 21. Página 21 de baja ocupación. La página fuente 20 sin cuerpo pasa a recibir la continuación de Anexo C; no se eliminó ningún salto para corregirla.
- Página 22: firmas y cierre fuente preservados.

No se detectaron desbordamientos nuevos ni páginas vacías nuevas. Se documentan continuaciones de tablas y baja ocupación, sin correcciones editoriales. La verificación geométrica no detectó palabras fuera del límite físico de página. No hubo pérdida de imágenes. Encabezado y pie conservados.

## H. Contenido preservado e IDs aplicados

Los nueve DOCX originales y los siete aprobados permanecen idénticos por SHA-256. Anexo A mantiene su recurso gráfico y su ubicación OOXML; Anexo B y tabla completa de cuatro indicadores son estructuralmente idénticos. Todos los párrafos directos no afectados y tablas no intervenidas conservan su serialización OOXML. Los cinco sistemas, ruta del Machote, metadatos, controles de 24 horas, información mínima, reunión semanal, Informe Semanal, OCS, OM, ferreterías, pagos cíclicos, comprobantes y revisión mensual se preservaron.

ID04 e ID10: ventana ordinaria jueves 12:00 md, enlace OC jueves AM y coherencia entre desarrollo, tablas, RACI, checklist y delimitación de Figura 3; anticipaciones especiales y potestad excepcional conservadas/precisadas conforme al paquete.

ID07: aprobación previa del Ingeniero de horas/montos; registro de mano de obra por RRHH en Mawi con guía PRO. B-Sides no se extiende a Gastos Manuales.

No se registra ID12 como pendiente local: Manual del AA ausente de fuente e integrado.

## I. Pendientes de peinado final — sin resolver

- [PENDIENTE DE PEINADO FINAL – revisar redacción del primer indicador: título y fórmula miden notificaciones tardías, mientras «Qué mide» dice notificaciones que cumplen los plazos; no modificar indicador ni fórmula sin validación]
- [PENDIENTE DE PEINADO FINAL – pie heredado «Departamento Aseguramiento de la Calidad — Uso interno»]
- [PENDIENTE DE PEINADO FINAL – captions de Figuras 1 y 2 separados de sus imágenes por salto de página]
- [PENDIENTE DE PEINADO FINAL – página fuente 20 sin contenido de cuerpo, con encabezado/pie, y distribución de espacios/saltos]
- [PENDIENTE DE PEINADO FINAL – encabezado de tabla de indicadores separado de sus filas entre páginas 17 y 18]
- [PENDIENTE DE PEINADO FINAL – recorte visual preexistente de la fórmula de mano de obra en la tabla de indicadores]
- [PENDIENTE DE PEINADO FINAL – erratas/espaciado fuente, como «proyecto.Es» en el alcance]

Se conservan literalmente los registros aprobados de observaciones fuente. Su ubicación/manifestación tras refluencia se explica en G; no se declara su resolución editorial. Revisar también continuaciones de tablas y baja ocupación final durante el peinado individual. No son nuevos hallazgos de integración.

## J. Resultado

**[NUEVO PENDIENTE DE INTEGRACIÓN]: ninguno.** La modificación exclusiva del título de Figura 3 fue técnicamente posible sin cambiar su cuerpo ni los demás recursos.

Pendiente de revisión independiente. Permanece en `01_INTEGRACION`, sin trasladar a aprobados. README: solo fila CTO-SOP-03 actualizada a EN REVISIÓN – integración realizada. No se avanzó a CTO-SOP-02.
