# CTO-SOP-01 — Control de integración

Artefacto de auditoría; no forma parte del procedimiento oficial.

## A. Identificación y estado

**CTO-SOP-01: EN REVISIÓN – integración realizada.** Revisión independiente y aprobación del integrado pendientes. No oficializado.

Fecha: 13/10/2026 (America/Costa_Rica).

Fuente exclusiva: `00_ORIGINALES/CTO-SOP-01-V1-2026_Gestion_Integral_Proyectos_Constructivos_Versión definitiva....docx`.

Salida: `01_INTEGRACION/CTO-SOP-01-V1-2026_INTEGRADO.docx`.

SHA-256 original: `14379f39f17f0fef5a3773c15d61233636dbcdcb2172244cf872145a8a78fa88`.

SHA-256 integrado: `75ee8ceb4cc15be90debb71ea5573fedda5dc73c9bf81cc0163d35ef691f3715`.

Base Git: `53718f402d1f26ab3301220cf15bceb2cbdd0ea4`. El commit de incorporación es el commit dedicado que introduce este control y el DOCX; se identifica mediante `git log --diff-filter=A --format=%H -- 01_INTEGRACION/CTO-SOP-01-V1-2026_INTEGRADO.docx` y se entrega en la respuesta. No se inserta un SHA autorreferente dentro del mismo commit.

Se aplican la comparación aprobada, las tres correcciones finales y la autorización expresa de integración. Prevalecen la eliminación operativa completa de Contabilidad Externa, la eliminación del campo «área» sin reasignación y la secuencia explícita QBO → importación/configuración administrativa inicial en Mawi.

## B. Comparación estructural

| Elemento | Original | Integrado |
| --- | ---: | ---: |
| Párrafos cuerpo, incluidas celdas | 1268 | 1278 |
| Párrafos directos cuerpo | 908 | 910 |
| Párrafos con encabezados/pies/notas | 1281 | 1291 |
| Tablas cuerpo | 21 | 21 |
| Tablas encabezado/pie | 1 | 1 |
| Filas tablas cuerpo | 119 | 120 |
| Imágenes word/media | 0 | 0 |
| Comentarios Word | 0 | 0 |
| Secciones | 1 | 1 |
| Encabezados/pies | 2 | 2 |
| Páginas renderizadas | 52 | 52 |

Conteos OOXML, no estimaciones visuales. Los párrafos totales incluyen ocho párrafos de separadores/notas sin texto, además del cuerpo y encabezados/pies. La extracción registra todos los párrafos del cuerpo y contenido textual documental de encabezados, pies y notas; no convierte los separadores vacíos en contenido.

Diferencia: seis párrafos directos añadidos y cuatro eliminados (+2); eliminación de una fila de dos celdas en Tabla 2 (−2 párrafos); dos filas nuevas de cinco celdas en RACI (+10). Resultado neto: +10 párrafos de cuerpo y +1 fila de tablas. No se creó ninguna tabla. Las dos filas nuevas se clonaron de una fila RACI compatible conservando sus propiedades de fila/celda/párrafo y formato de texto; se retiró únicamente la fila autorizada de Contabilidad externa. No se reconstruyeron tablas completas.

Se conservaron exactamente las propiedades `tblPr` y `tblGrid` de las 21 tablas, incluidos los anchos de columnas. Columnas y filas, por orden físico OOXML (no por caption):

| Tabla OOXML | Filas original | Filas integrado | Columnas original/integrado |
| --- | ---: | ---: | --- |
| 1 | 1 | 1 | 2 / 2 |
| 2 | 1 | 1 | 8 / 8 |
| 3 | 1 | 1 | 2 / 2 |
| 4 | 7 | 7 | 4 / 4 |
| 5 | 25 | 25 | 2 / 2 |
| 6 | 15 | 14 | 2 / 2 |
| 7 | 1 | 1 | 2 / 2 |
| 8 | 1 | 1 | 1 / 1 |
| 9 | 1 | 1 | 1 / 1 |
| 10 | 2 | 2 | 4 / 4 |
| 11 | 2 | 2 | 4 / 4 |
| 12 | 1 | 1 | 2 / 2 |
| 13 | 13 | 15 | 5 / 5 |
| 14 | 9 | 9 | 5 / 5 |
| 15 | 7 | 7 | 2 / 2 |
| 16 | 5 | 5 | 3 / 3 |
| 17 | 8 | 8 | 3 / 3 |
| 18 | 2 | 2 | 6 / 6 |
| 19 | 12 | 12 | 2 / 2 |
| 20 | 4 | 4 | 2 / 2 |
| 21 | 1 | 1 | 2 / 2 |

Única parte OOXML modificada: `word/document.xml`. Todas las demás partes conservan bytes idénticos: estilos, numeración, relaciones, configuración, encabezado, pie, notas y propiedades del paquete. No existen imágenes en `word/media/` ni comentarios Word. El espacio reservado a Figura 1 sigue pendiente; no se inventó un diagrama.

## C. Cambios individuales

P identifica el número del párrafo directo original, excluidas las celdas. Las tablas OOXML se numeran por orden del archivo, incluyendo las tres tablas preliminares. Una fila por intervención y una por cada celda modificada; las dos filas RACI nuevas se muestran completas.

| Ubicación | Tipo | Original | Integrado |
| --- | --- | --- | --- |
| P452 fuente | MODIFICAR | GEN-SOP-04-V1-2026: Procedimiento para manejo de Expedientes Físicos y AMPO | GEN-SOP-05-V1-2026: Gestión de Expedientes. |
| P453 fuente | MODIFICAR | CAL-SOP-01-V1-2026: Procedimiento de Gestión de Garantías | CAL-SOP-01-V1-2025: Gestión de Garantías. |
| P456 fuente | MODIFICAR | Manual Operativo de Asistente Administrativo: Pendiente de ubicación. | Manual Operativo del Asistente Administrativo: [POR DEFINIR: código oficial] |
| Tabla 1 — AMPO | MODIFICAR | Expediente físico oficial del proyecto constructivo, en el que se archiva y mantiene actualizada toda la documentación relevante, gestionado conforme al procedimiento GEN-SOP-04-V1-2026. | Expediente físico oficial del proyecto constructivo, en el que se archiva y mantiene actualizada toda la documentación relevante, gestionado conforme al procedimiento GEN-SOP-05-V1-2026. |
| Tabla OOXML 6, fila 5, columna 2 | MODIFICAR | Crear y entregar el AMPO completamente actualizado, administrar los grupos de WhatsApp del proyecto, elaborar la oferta constructiva en coordinación con Gerencia General y llevar el control de versiones documentales. | Responsable de la activación administrativa (creación del cliente/proyecto en QBO e importación y configuración administrativa inicial del proyecto en Mawi, habilitación de carpetas en servidor y creación del grupo de WhatsApp), conforme al procedimiento COM-SOP-01-V1-2026 y a la regla de datos maestros de GEN-SOP-05-V1-2026. |
| Tabla OOXML 6, fila 3, columna 2 | MODIFICAR | Responsable de la gestión integral del proyecto desde su inicio hasta su cierre: control de costo, cronograma, calidad, alcance, materiales, contractual, documental, comunicación y seguridad en sitio. | Responsable de la gestión integral del proyecto desde su inicio hasta su cierre: control de costo, cronograma, calidad, alcance, materiales, contractual, documental, comunicación y seguridad en sitio. Asume la Configuración Técnica de Obra en Mawi tras la activación administrativa realizada por el Asistente Administrativo. |
| Tabla OOXML 6, fila 9, columna 2 | MODIFICAR | Recibir la información financiera del proyecto, coordinar con la Contabilidad externa y el Departamento de Construcción la apertura y el cierre del proyecto en QBO y Mawi. | Recibir la información financiera del proyecto y coordinar con el Departamento de Construcción el cierre financiero y administrativo del proyecto. |
| Tabla OOXML 6, fila 14, columna 2 | MODIFICAR | Realizar inspecciones en obra, acompañamientos técnicos y consulta el Manual de Mantenimiento al momento de recibir una garantía. | Rol responsable de la atención e interlocución de garantías de postventa tras la entrega de la obra, ejercido ordinariamente por el mismo Ingeniero de Proyecto que ejecutó la construcción o por el ingeniero reasignado cuando el responsable original no se encuentre disponible, conforme a CAL-SOP-01-V1-2025. |
| Tabla 2 — Contabilidad externa (outsourcing) | ELIMINAR | Contabilidad externa (outsourcing) &#124; Realizar la apertura y el cierre del cliente y del proyecto en QBO conforme a lo indicado por el Departamento Administrativo. |  |
| Después de 509 | AGREGAR |  | Cuando un proyecto proveniente de Consultoría continúe a Construcción, se crea un proyecto CTO nuevo e independiente en QBO y se importa a Mawi, conservando el mismo cliente y nombre base y utilizando su propio código CTO conforme a GEN-SOP-05-V1-2026. |
| Después de 531 | AGREGAR |  | La entrega técnica de Consultoría se realiza conforme a CTA-SOP-01-V1-2026. |
| P541 fuente | MODIFICAR | Expediente del proyecto para ser trasladado a AMPO en conformidad al procedimiento GEN-SOP-04-V1-2026. | Expediente del proyecto para ser trasladado a AMPO en conformidad al procedimiento GEN-SOP-05-V1-2026. |
| P545 fuente | MODIFICAR | Al recibir la solicitud del cliente, se debe notificar al Asistente Administrativo para la creación de archivos acorde a GEN-SOP-04-V1-2026. | Al recibir la solicitud del cliente, se debe notificar al Asistente Administrativo para la creación de archivos acorde a GEN-SOP-05-V1-2026. |
| P612 fuente | MODIFICAR | Crear el AMPO del proyecto conforme al Manual Operativo de Asistente Administrativo, ingresando la documentación preexistente del expediente y la información generada en el traslado a Construcción (ofertas constructivas entregadas al cliente, contrato, anotaciones, documentos bancarios, etc.). | Crear el AMPO del proyecto conforme a GEN-SOP-05-V1-2026, ingresando la documentación preexistente del expediente y la información generada en el traslado a Construcción (ofertas constructivas entregadas al cliente, contrato, anotaciones, documentos bancarios, etc.). |
| P628 fuente | MODIFICAR | Envío de correo de Solicitud de Apertura de Proyecto | Correo de Alineación del Proyecto |
| P630 fuente | MODIFICAR | El Gerente de Proyectos debe enviar el correo de Solicitud de Apertura de Proyecto para alinear a todas las áreas de la empresa y para que el Departamento Administrativo-Financiero solicite a la Contabilidad externa la apertura del cliente y del proyecto en QBO. El correo debe incluir: | Una vez formalizada la venta comercial y ejecutada la activación administrativa por el Asistente Administrativo conforme a COM-SOP-01-V1-2026, la Gerencia de Proyectos o el Ingeniero de Proyecto emite el Correo de Alineación del Proyecto antes de iniciar los trabajos en sitio, con el fin de coordinar la planificación técnica, presupuesto, logística y demás requerimientos de inicio. |
| Después de 630 | AGREGAR |  | Cuando Ingeniería haya liderado directamente la gestión comercial, por ejemplo en licitaciones o ventas especiales, y el proyecto aún no haya sido creado, este correo funciona además como Solicitud de Apertura dirigida al Asistente Administrativo para que ejecute la activación administrativa conforme a COM-SOP-01-V1-2026. |
| Párrafo añadido | AGREGAR |  | El correo debe incluir: |
| P641 fuente | MODIFICAR | Activación del proyecto en Mawi | Configuración Técnica de Obra en Mawi |
| P642 fuente | MODIFICAR | Responsable: Gerente de Proyectos / Ingeniero de Proyecto | Responsable: Ingeniero de Proyecto |
| P643 fuente | MODIFICAR | Una vez que la Contabilidad externa haya creado el proyecto en QBO, el Gerente de Proyectos debe activar el proyecto en Mawi mediante las siguientes acciones: | Una vez que el Asistente Administrativo haya completado la importación y configuración administrativa inicial del proyecto en Mawi conforme a COM-SOP-01-V1-2026, el Ingeniero de Proyecto ejecuta la Configuración Técnica de Obra. |
| P644 fuente | ELIMINAR | Importar proyectos desde la Configuración General en “Integraciones”. |  |
| P646 fuente | ELIMINAR | Editar la información general del proyecto; seleccionar “Construcción” en “Etapa” para poder visualizar el proyecto mediante los filtros de etapa. Asimismo, ingresar área, fecha de ingreso y finalización, código, ubicación y uso. |  |
| P647 fuente | ELIMINAR | Agregar al personal de AC Desarrollos a un solo equipo llamado General, seleccionando su rol en el proyecto de acuerdo a la configuración general de roles de usuarios. |  |
| P645 fuente | MODIFICAR | Subir presupuesto definitivo del proyecto (si no, no permite realizar órdenes de compra) | Cargar/ajustar el Presupuesto Definitivo de Obra (si no, no permite realizar órdenes de compra). |
| Después de 645 | AGREGAR |  | Establecer las Fechas Objetivo operativas. |
| P649 fuente | MODIFICAR | Cuando al cliente se le van a enviar documentos por medio de Mawi (Submittals, Órdenes de Modificación, RFIs, bitácoras, archivos cargados en carpetas o simplemente reportería), se debe crear el cliente desde el directorio y vincularlo al proyecto.  | Crear/vincular al cliente en el Directorio de Mawi únicamente cuando el tipo de cliente/proyecto requiera trazabilidad formal de documentos, aprobaciones o comunicaciones. El Directorio de Mawi es opcional, no obligatorio para todo proyecto. |
| P849 fuente | MODIFICAR | Conformar y archivar el expediente físico y digital completo del proyecto, incorporando ordenadamente los documentos elaborados, recibidos, entregados y gestionados durante su ejecución y cierre, asegurando su trazabilidad, confiabilidad y disponibilidad. | Conformar y archivar el expediente físico y digital completo del proyecto, incorporando ordenadamente los documentos elaborados, recibidos, entregados y gestionados durante su ejecución y cierre, asegurando su trazabilidad, confiabilidad y disponibilidad, conforme a GEN-SOP-05-V1-2026. |
| P877 fuente | MODIFICAR | Confirmar con todas las áreas involucradas y con la Contabilidad externa que no existan actividades, documentos, montos u obligaciones pendientes. | Confirmar con todas las áreas involucradas, incluido el Departamento Administrativo-Financiero, que no existan actividades, documentos, montos u obligaciones pendientes. |
| P888 fuente | MODIFICAR | El Ingeniero de Proyecto deberá gestionar la recepción, apertura, diagnóstico, seguimiento y cierre de las garantías, conforme a los lineamientos establecidos en el manual CAL-SOP-01-V1-2026, asegurando la trazabilidad del proceso y la comunicación oportuna con las partes involucradas. | La atención técnica de postventa —recepción, diagnóstico/evaluación, coordinación, seguimiento, supervisión, verificación y cierre— se rige por CAL-SOP-01-V1-2025. |
| P889 fuente | ELIMINAR | Cuando el Ingeniero de Proyecto no se encuentre en la empresa o no esté disponible para atender una garantía, el Departamento de Construcción deberá asignar y trasladar el reclamo a otro ingeniero con la capacidad técnica y disponibilidad necesarias para gestionarlo. |  |
| Después de 888 | AGREGAR |  | Tras la entrega formal documentada mediante el Acta de Recepción, la transición del expediente/AMPO a la etapa de garantía se realiza conforme a GEN-SOP-05-V1-2026. |
| Tabla OOXML 13, fila 6, columna 1 | MODIFICAR | Activación en Mawi y QBO | Activación administrativa (creación del cliente/proyecto en QBO, importación y configuración administrativa inicial en Mawi, servidor y WhatsApp). Referencia: COM-SOP-01-V1-2026 / GEN-SOP-05-V1-2026 |
| Tabla OOXML 13, fila 6, columna 2 | MODIFICAR | Gerente de Proyectos | Asistente Administrativo (R) |
| Tabla OOXML 13, fila 6, columna 3 | MODIFICAR | Gerente de Proyectos | — |
| Tabla OOXML 13, fila 6, columna 4 | MODIFICAR | Admin. / Financiero, Contabilidad externa | — |
| Tabla OOXML 13, fila 6, columna 5 | MODIFICAR | Construcción | — |
| Matriz RACI, fila nueva | AGREGAR |  | Configuración Técnica de Obra en Mawi (PPTO técnico, Fechas Objetivo, Materiales) &#124; Área de Construcción (Ingeniero de Proyecto / Gerente de Proyectos) (R) &#124; — &#124; — &#124; — |
| Matriz RACI, fila nueva | AGREGAR |  | Atención de Garantías de Postventa. Referencia: CAL-SOP-01-V1-2025 &#124; Aseguramiento de la Calidad (R, ejercido por el Ingeniero de Proyecto responsable o el ingeniero reasignado) &#124; — &#124; — &#124; — |
| Tabla OOXML 14, fila 5, columna 1 | MODIFICAR | Activación del proyecto | Activación administrativa y alineación del proyecto |
| Tabla OOXML 14, fila 5, columna 3 | MODIFICAR | Asistente Administrativo / Gerente de Proyectos | Asistente Administrativo (activación administrativa) / Gerente de Proyectos o Ingeniero de Proyecto (alineación) |
| Tabla OOXML 14, fila 5, columna 4 | MODIFICAR | AMPO creado, proyecto en Mawi y QBO, correo de apertura | AMPO creado; cliente/proyecto creado en QBO e importado y configurado administrativamente en Mawi conforme a COM-SOP-01-V1-2026 y GEN-SOP-05-V1-2026; Correo de Alineación del Proyecto. |
| Tabla OOXML 15, fila 4, columna 2 | MODIFICAR | Sin el presupuesto definitivo no se permiten órdenes de compra; debe cargarse en la activación. | Sin el presupuesto definitivo no se permiten órdenes de compra; debe cargarse en la Configuración Técnica de Obra en Mawi. |
| Tabla OOXML 17, fila 2, columna 1 | MODIFICAR | Informe 0 | Informe 0 — CTO-SOP-02-V1-2026 |
| Tabla OOXML 17, fila 3, columna 1 | MODIFICAR | Informes semanales de proyecto | Informes semanales de proyecto — CTO-SOP-02-V1-2026 |
| Tabla OOXML 17, fila 4, columna 3 | MODIFICAR | AMPO / Servidor interno | AMPO / Servidor interno, conforme a GEN-SOP-05-V1-2026 |
| Tabla OOXML 17, fila 8, columna 3 | MODIFICAR | AMPO / Servidor interno | AMPO / Servidor interno, conforme a GEN-SOP-05-V1-2026 |
| Tabla OOXML 17, fila 7, columna 3 | MODIFICAR | AMPO / Mawi | AMPO conforme a GEN-SOP-05-V1-2026 / Mawi |

La frase «El correo debe incluir:» se conserva en un párrafo separado tras los dos nuevos párrafos rectores. Los diez elementos fuente permanecen idénticos. La nueva regla CTA→CTO precede la introducción de la lista de solicitudes; la referencia CTA precede la introducción de entregables. Se empleó formato de párrafo compatible y, en las filas nuevas, se conservó la negrita nativa de la primera columna. No se aplicaron cambios de anchos, tipografía, saltos o estilos a contenido fuente no afectado.

## D. QA textual — tratamiento separado

Búsqueda sin distinción de mayúsculas por cadena/subcadena en OOXML. «área», «Etapa», «Ubicación» y «Uso» pueden aparecer legítimamente en otros contextos; sus conteos no implican obligaciones de configuración técnica. La delimitación se realiza por el inicio formal original, no por un corte arbitrario del texto extraído.

| Término | Procedimiento formal (p. 14–52) | Preliminar (p. 1–13) |
| --- | ---: | ---: |
| GEN-SOP-04-V1-2026 | 0 | 0 |
| CAL-SOP-01-V1-2026 | 0 | 0 |
| Contabilidad externa | 0 | 0 |
| Solicitud de Apertura de Proyecto | 0 | 0 |
| Activación del proyecto en Mawi | 0 | 0 |
| Importar proyectos desde | 0 | 0 |
| área | 26 | 6 |
| Etapa | 12 | 2 |
| Ubicación | 5 | 4 |
| Uso | 2 | 1 |
| Equipo General | 0 | 0 |
| Configuración Técnica de Obra | 5 | 0 |
| Correo de Alineación del Proyecto | 3 | 0 |
| GEN-SOP-05-V1-2026 | 14 | 0 |
| CAL-SOP-01-V1-2025 | 4 | 0 |
| CTA-SOP-01-V1-2026 | 1 | 0 |

Resultados:

- Cero GEN-SOP-04-V1-2026, CAL-SOP-01-V1-2026 y Contabilidad externa en el procedimiento formal.
- Cero títulos antiguos «Solicitud de Apertura de Proyecto» y «Activación del proyecto en Mawi». La expresión abreviada «Solicitud de Apertura» se conserva exclusivamente en la excepción comercial aprobada de Ingeniería.
- Cero instrucciones «Importar proyectos desde» y «ingresar área» en el bloque técnico. Etapa, Ubicación, Uso, fechas administrativas, código y Equipo General se retiraron de dicho bloque sin asignar el campo área a otro rol.
- Las apariciones generales de áreas, etapas, ubicación y uso no se sustituyeron: corresponden a alcance, áreas empresariales, datos del proyecto, ubicaciones de registros y otros contenidos nativos. No hay obligación residual de ingresar el campo área en Mawi.
- AA: creación en QBO e importación/configuración administrativa inicial en Mawi. Secuencia reflejada en Tabla 2, correo, párrafo técnico, transición CTA→CTO, RACI y Entradas/Salidas. No se agregó creación independiente en Mawi.
- Construcción: Presupuesto Definitivo, Fechas Objetivo, Control de Materiales con remitentes/receptores fuente y Directorio opcional por trazabilidad formal.
- Proyecto CTO nuevo e independiente con cliente/nombre base conservados y código propio; entrega técnica referida a CTA01. Sin conversión histórica ni reutilización de código CTA.
- Garantía remitida a CAL2025; plazo fuente intacto y transición documental conforme a GEN05. Sin nueva evidencia de Proyecto 01.
- Referencias documentales actualizadas únicamente en el procedimiento formal. Manual del AA sin código ni ubicación inventados.
- Once pendientes fuente conservados literalmente. Indicadores CPI/SPI y remisión CTO02 intactos.
- Extracción textual completa verificada contra todos los nodos `w:t` de cuerpo, encabezado, pie y notas. Tablas completas con todas las filas/columnas y señalización de celdas combinadas. No hay imágenes que requieran transcripción.

## E. Elementos preservados e IDs

Los nueve originales y seis DOCX aprobados permanecen idénticos por SHA-256. Se verificó identidad OOXML de todos los párrafos directos no afectados, tablas completas no afectadas, filas RACI compatibles y roles no intervenidos de Tabla 2. No se perdió contenido operativo no autorizado. Metadatos, control de cambios, firmas pendientes, objetivo, alcance, definiciones no afectadas, sistemas, lista del correo, WhatsApp, Informe 0, ejecución, indicadores, cierres no afectados y entregables posteriores se preservaron.

**ID01, ID02 e ID03 — aplicación conjunta del paquete aprobado:** deslinde de activación administrativa/configuración técnica, gobernanza de datos maestros y proyecto CTO independiente, y coherencia de referencias/roles de postventa. Se registran los tres identificadores solicitados sin reconstruir ni inventar títulos o una correspondencia individual de la matriz histórica de hallazgos, que no forma parte de este paquete.

**ID12 — pendiente institucional conservado:** código y ubicación oficial del Manual Operativo del AA y definición documental QBO. El pendiente fuente 03 permanece literal en el DOCX y queda vinculado a ID12 en este control. No se agrega un instructivo independiente.

## F. QA visual

Render LibreOffice: original 52 páginas; integrado 52 páginas. Revisadas visualmente las páginas **1–52**, con ampliación de las incorporaciones y matrices afectadas. Se comprobó además que no existen palabras fuera del límite de página ni páginas vacías nuevas.

- Páginas 1–13: todos sus elementos OOXML son idénticos y las imágenes rasterizadas del render son idénticas píxel a píxel. No se eliminaron instrucciones, notas, tablas, saltos ni contenido preliminar. El procedimiento formal sigue comenzando en página 14.
- Páginas 14–22: portada/metadatos, referencias, definiciones y roles legibles. La Tabla 2 continúa entre páginas 19–20 sin pérdida de texto.
- Páginas 23–30: proyecto independiente, entrega técnica CTA, expediente, correo y configuración técnica legibles. Lista de diez elementos del correo íntegra. La disposición fuente del Directorio como párrafo se mantiene.
- Páginas 31–43: ejecución y cierres preservados; referencia GEN05 y confirmación con Administrativo-Financiero integradas. Resaltados amarillos preexistentes conservados.
- Páginas 44–49: garantías, RACI, entradas/salidas, riesgos, indicadores y evidencias revisados. Las filas ampliadas continúan entre páginas: activación RACI 44–45, activación Entradas/Salidas 46–47 y presupuesto/riesgos 47–48. Son continuaciones de fila con texto completo, no recortes con pérdida. Se conservan los anchos nativos, que producen particiones de palabras en columnas estrechas. No se forzaron ajustes de peinado.
- Páginas 50–52: control de cambios, once pendientes y firmas completos. Página 52 de baja ocupación ya existente. También permanecen espacios amplios por disposición/saltos fuente, entre ellos páginas 13 y 22, y espacio libre en página 49 tras los registros.
- Encabezados y pies conservados. Ninguna imagen perdida (0 original / 0 integrado). No se detectaron desbordamientos ni texto truncado nuevo atribuible a la integración. La oración truncada fuente sigue registrada como peinado.

No se aplicaron correcciones editoriales o de paginación. Los únicos ajustes locales durante preparación del render fueron emplear el formato nativo de párrafo para la referencia CTA añadida y mantener el formato de texto de la fila modelo en las dos nuevas filas RACI; no se alteraron propiedades de contenido no afectado. La numeración fuente, incluidas sus anomalías, permanece intacta.

## G. Pendientes de peinado final — no corregidos

- [PENDIENTE DE PEINADO FINAL – material preliminar preexistente anterior al procedimiento formal (notas internas e instrucciones de revisión, páginas fuente 1–13); revisar y depurar antes de oficialización]
- [PENDIENTE DE PEINADO FINAL – pie heredado «Departamento Aseguramiento de la Calidad — Uso interno»]
- [PENDIENTE DE PEINADO FINAL – repetición de «Finaliza con» en alcance]
- [PENDIENTE DE PEINADO FINAL – caption «Tabla 5» del control de cambios; revisar coherencia de numeración]
- [PENDIENTE DE PEINADO FINAL – texto truncado «Coordinar, supervisar y dar seguimiento al cronograma, la ruta crítica, las actividades constructivas y.»]
- [PENDIENTE DE PEINADO FINAL – anomalías tipográficas fuente «corrección.,» y «quipo»]
- [PENDIENTE DE PEINADO FINAL – numeración visual fuente «31» y «32» en bandas de Ingreso y Activación / Ejecución y Control; secuencias alfabéticas continuadas entre subsecciones]
- [PENDIENTE DE PEINADO FINAL – resaltados amarillos preexistentes en preparación anticipada del cierre]
- [PENDIENTE DE PEINADO FINAL – continuaciones de filas, particiones de palabras en columnas estrechas y páginas de baja ocupación; revisar en QA final sin modificar ahora]

Estos puntos no son pendientes de integración ni hallazgos transversales nuevos.

## H. Once pendientes fuente conservados

Transcripción completa de la tabla fuente, conservada sin cambios en el integrado:

| Ubicación | Decisión requerida |
| --- | --- |
| Flujo del proceso (Figura 1) — [PENDIENTE DE VALIDACIÓN 01] | Elaborar e incorporar el diagrama de flujo del proceso de gestión integral de proyectos, alineado con las etapas del procedimiento. |
| Indicadores de desempeño / Ejecución y control — [PENDIENTE DE VALIDACIÓN 02] | Definir los rangos aceptables de CPI y SPI en el procedimiento CTO-SOP-02-V1-2026. |
| Activación del Proyecto, creación del AMPO — [PENDIENTE DE VALIDACIÓN 03] | Confirmar el código y la denominación oficial del “Manual Operativo de Asistente Administrativo”. |
| Roles del procedimiento — [PENDIENTE DE VALIDACIÓN 04] | Confirmar si “Gerencia Presidencial” corresponde a “Gerencia General” o a un rol distinto, y unificar su denominación en el cuerpo del procedimiento y en la Tabla 2. |
| Matriz RACI / Ingeniero Residente — [PENDIENTE DE VALIDACIÓN 05] | Definir la participación del Ingeniero Residente en la matriz RACI y su articulación con las funciones del Ingeniero de Proyecto; el rol se describe en la Tabla 2 pero no interviene explícitamente en las actividades. |
| Documentos de cierre — [PENDIENTE DE VALIDACIÓN 06] | Definir el responsable de la elaboración o gestión de cada entregable de cierre (Manual de Mantenimiento, Planos As Built, Certificación de Obra Construida, entre otros). |
| Cierre financiero y administrativo — [PENDIENTE DE VALIDACIÓN 07] | Definir si el cierre debe incluir trámites regulatorios o institucionales (por ejemplo, cierres municipales, CFIA o servicios públicos) y su responsable. |
| Retenciones / Control financiero — [PENDIENTE DE VALIDACIÓN 08] | Definir quién controla, registra y solicita la liberación de las retenciones contractuales. |
| Gestión de riesgos — [PENDIENTE DE VALIDACIÓN 09] | Formalizar la matriz de gestión de riesgos (identificación, valoración, tratamiento y responsable) como anexo del procedimiento. |
| Alcance del procedimiento — [PENDIENTE DE VALIDACIÓN 10] | Desarrollar el tratamiento de los proyectos ejecutados por administración, definiendo sus particularidades de control de costos, facturación y documentación. |
| Control de cambios del documento — [PENDIENTE DE VALIDACIÓN 11] | Completar el cuadro de control de cambios con la versión, la fecha, la revisión y la aprobación correspondientes a la presente actualización (integración de observaciones del equipo). |

Los pendientes fuente no se reclasifican ni resuelven por inferencia. CPI/SPI sigue remitido a CTO-SOP-02-V1-2026. No se añadió un diagrama ni matriz de riesgos nueva siguiendo las instrucciones preliminares.

## I. Resultado y siguiente control

**[NUEVO PENDIENTE DE INTEGRACIÓN]: ninguno.** Contabilidad Externa en cierre y campo área quedaron resueltos por las instrucciones finales, aplicadas sin inventar responsables.

Pendiente de revisión independiente del integrado. Permanece en `01_INTEGRACION`; no se trasladó a aprobados. No se avanzó a CTO-SOP-03 ni se modificó otro DOCX. README: únicamente la fila CTO-SOP-01 cambia a EN REVISIÓN – integración realizada.
