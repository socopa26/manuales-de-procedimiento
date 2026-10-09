# CTA-SOP-01 — Control de integración

Artefacto de auditoría; no forma parte del procedimiento oficial.

## A. Identificación y estado

**CTA-SOP-01: integración aprobada.** Revisión independiente aprobada para la fase de integración. No oficializado.

Fecha de integración: 09/10/2026 (America/Costa_Rica).

Fuente exclusiva: `00_ORIGINALES/CTA-SOP-01-V1-2026 Gestión Interna de Proyectos de Consultoría en Mawi - BORRADOR REORGANIZADO PARA VALIDACIÓN.docx`.

Salida: `01_INTEGRACION/CTA-SOP-01-V1-2026_INTEGRADO.docx`.

Base Git: `98f32d9597b9f450013dbbc8aede95f9098b7699`. La incorporación del integrado y estos artefactos corresponde al commit dedicado que contiene este archivo. Puede identificarse con `git log --diff-filter=A --format=%H -- 01_INTEGRACION/CTA-SOP-01-V1-2026_INTEGRADO.docx`.

Decisiones aplicadas: comparación aprobada y las cuatro correcciones finales, ratificadas en la autorización de integración. Ninguna ampliación sustantiva de alcance.

SHA-256 original: `3f972a0c5b22297ed72b85f3fe6f5f2bc5c06b658e2709c944a4577a3f14ea39`.

SHA-256 integrado: `e056beadac4c7f5bcc6f3c4ec237f838cfa81d43c5e61a3862e1e59371cf58d9`.

## B. Comparación estructural

| Elemento | Original | Integrado |
| --- | ---: | ---: |
| Párrafos del cuerpo, incluidas celdas | 580 | 584 |
| Párrafos directos del cuerpo | 283 | 282 |
| Párrafos de cuerpo y pie | 583 | 587 |
| Tablas del cuerpo | 21 | 21 |
| Tablas de cuerpo y pie | 22 | 22 |
| Imágenes incorporadas | 0 | 0 |
| Comentarios Word | 0 | 0 |
| Secciones Word | 1 | 1 |
| Páginas renderizadas | 19 | 21 |

Método: conteo OOXML; párrafos `w:p`, tablas `w:tbl`, secciones `w:sectPr`, imágenes incorporadas en `word/media/`. La tabla del pie es adicional a las 21 tablas del cuerpo. No existen comentarios Word ni imágenes incorporadas; los recuadros y bandas de sección son tablas/texto, no imágenes.

Diferencias: se agregan nueve párrafos directos y se eliminan diez, de modo que 283 pasan a 282. La nueva fila de Presupuesto aporta cinco párrafos de celda: total del cuerpo 580 → 584. Se mantiene la tabla existente, sin columnas nuevas. El pie conserva sus tres párrafos y una tabla. El crecimiento de texto y las filas ampliadas producen 19 → 21 páginas con los saltos fuente conservados.

Única parte OOXML con bytes distintos: `word/document.xml`. Todas las demás partes del paquete son idénticas, incluyendo estilos, numeración, pie, configuración, relaciones y propiedades documentales. No se hizo una conversión PDF → DOCX ni se guardó el DOCX mediante el renderizador.

## C. Cambios ejecutados individualmente

Los identificadores P corresponden a los párrafos directos del cuerpo original, excluyendo celdas. Las columnas de tablas se identifican según su posición nativa. En cada modificación de párrafo se muestra el texto completo anterior y posterior; las propiedades y segmentos de formato se conservan.

| Ubicación | Tipo | Texto original | Texto integrado |
| --- | --- | --- | --- |
| P014 directo original | MODIFICAR | El procedimiento inicia con la aceptación y firma de la oferta de servicios profesionales y la autorización para crear o activar el proyecto por parte del cliente o de los encargados de la gestión con el cliente. Finaliza con el traslado o cierre del proyecto en Mawi. La gestión documental del expediente se realizará conforme a lo establecido en el procedimiento [REFERIR AL PROCEDIMIENTO CORRESPONDIENTE: GEN-SOP-05]. | El procedimiento inicia con la aceptación y firma de la oferta de servicios profesionales y la autorización para crear o activar el proyecto por parte del cliente o de los encargados de la gestión con el cliente. Finaliza con el traslado o cierre del proyecto en Mawi. La gestión documental del expediente se realizará conforme a lo establecido en el procedimiento GEN-SOP-05-V1-2026. |
| Tabla 3 — AA / responsabilidad | MODIFICAR | Crea el cliente y el proyecto en QBO conforme a COM-SOP-01-V1-2026 Gestión de Ofertas; importa el proyecto a Mawi; ejecuta o apoya la configuración administrativa inicial que le asigne el procedimiento; verifica que el proyecto quede correctamente identificado; da seguimiento administrativo; escala inconsistencias cuando corresponda. | Crea el cliente y el proyecto en QBO conforme a COM-SOP-01-V1-2026; importa el proyecto a Mawi; ejecuta la configuración administrativa inicial del proyecto (Etapa, Ubicación, Uso, fechas AP/PC/TR y Equipo General); ejecuta de forma PROVISIONAL la carga del presupuesto de Consultoría en Mawi, pendiente de confirmación institucional del ID08; verifica la correcta identificación del proyecto; da seguimiento administrativo y escala inconsistencias cuando corresponda. |
| Tabla 3 — Consultoría / responsabilidad | MODIFICAR | Mantiene actualizados los atributos y las tareas; actualiza avances y fechas; registra observaciones; comunica bloqueos; brinda la información necesaria para el seguimiento financiero; identifica correctamente los gastos y facturas relacionados con sus proyectos; identifica correctamente las tareas requeridas para el avance tramitológico según el proyecto. | Es responsable de la configuración integral de las tareas de tramitología en Mawi, incluyendo la determinación de trámites aplicables, dependencias, fechas restrictivas, depuración de la plantilla de Microsoft Project e importación del archivo XML; mantiene actualizados los atributos y tareas; registra avances; comunica bloqueos; brinda información para el seguimiento financiero; identifica los gastos y facturas relacionados con sus proyectos; y realiza la entrega técnica necesaria para la transición a Construcción. |
| P040 directo original | MODIFICAR | El Asistente Administrativo ejecuta la activación de acuerdo al procedimiento COM-SOP-01-V1-2026 Gestión de Ofertas, la cual consiste en los siguientes cuatro (4) pasos: | El Asistente Administrativo ejecuta la activación de acuerdo al procedimiento COM-SOP-01-V1-2026 Gestión de Ofertas, la cual consiste en los siguientes cinco (5) pasos: |
| P041 directo original | MODIFICAR | Crea el grupo de WhatsApp, indicando al Departamento Administrativo-Financiero y al Departamento de Consultoría el inicio operativo del proyecto, una vez formalizada la firma y el primer cobro. | Gestiona la creación o transición del grupo de WhatsApp conforme a GEN-SOP-06-V1-2026 y comunica al Departamento Administrativo-Financiero y al Departamento de Consultoría la activación administrativa del proyecto. El inicio operativo queda condicionado al cumplimiento del pago inicial correspondiente conforme a COM-SOP-01-V1-2026. |
| P044 directo original | MODIFICAR | Importa los proyectos desde Mawi. | Importa el proyecto desde QBO a Mawi. |
| Identificación — campos administrativos, después de P049 | AGREGAR PÁRRAFO | [Párrafo inexistente] | El Asistente Administrativo configura la Etapa «Consultoría», Ubicación, Uso y las fechas «Entrega AP», «Entrega PC» y «Entrega TR», conforme a la oferta de servicios profesionales firmada. |
| P051 directo original | MODIFICAR | Esta configuración solamente puede ser realizada por un usuario con el rol de «Gerente de Proyectos». Lo realiza el Asistente Administrativo acorde a COM-SOP-01-V1-2026. | Esta configuración solamente puede ser realizada por un usuario con el rol de «Gerente de Proyectos». El Asistente Administrativo configura el Equipo «General» acorde a COM-SOP-01-V1-2026. |
| P053 directo original | MODIFICAR | Permite la sincronización con QBO. #Definir si la realiza el Departamento de Consultoría o el AA. | Permite la sincronización con QBO. La carga del presupuesto de Consultoría en Mawi se asigna PROVISIONALMENTE al Asistente Administrativo, pendiente de confirmación institucional del Hallazgo ID08. |
| P056 directo original | MODIFICAR | #Definir si la realiza el Departamento de Consultoría o el AA. | El Departamento de Consultoría es responsable de la configuración integral de las tareas de tramitología en Mawi, incluyendo la determinación de trámites aplicables, dependencias y fechas restrictivas, la depuración de la plantilla de Microsoft Project y la importación del archivo XML. |
| Tramitología — nota condicional AA (P070) | ELIMINAR | #Si se determina que lo sube el AA, agregar filtro de Consultoría: Verificar cuáles trámites proceden, cuáles no, y si hay dependencias o fechas restrictivas. | [Eliminado] |
| Después de tabla de atributos | AGREGAR | [Inexistente] | El valor «6. En Construcción» de Fase Consultoría es opcional, a criterio del Departamento de Consultoría, exclusivamente cuando ya existe un proyecto CTO nuevo e independiente activo y hay un traslape temporal durante el cual CTA mantiene pendientes por completar. Este atributo no convierte ni renombra el proyecto CTA como CTO. |
| P159 directo original | MODIFICAR | Asegurarse de que las herramientas reflejen la situación operativa y financiera real de cada proyecto, conforme al procedimiento COM-01-V1-2026 Gestión de Ofertas, sección 6 Seguimiento de cuentas por cobrar de Consultoría. | Asegurarse de que las herramientas reflejen la situación operativa y financiera real de cada proyecto, conforme al procedimiento COM-SOP-01-V1-2026 Gestión de Ofertas, sección 6 «Seguimiento de cuentas por cobrar de Consultoría». |
| Traslado — nota de borrador (P243) | ELIMINAR | #Incorporar aquí una lista de lo que CTO necesita a nivel de entregables de CTA. Establecer estos lineamientos. | [Eliminado] |
| Transición CTA → CTO, después de P244 | AGREGAR PÁRRAFO | [Párrafo inexistente] | CTA y CTO son proyectos independientes por departamento. Cuando un proyecto CTA continúa a Construcción, se crea un proyecto CTO nuevo e independiente en QBO y se importa a Mawi, conservando el mismo cliente y nombre base y utilizando su propio código CTO conforme a GEN-SOP-05-V1-2026. No se debe renombrar CTA como CTO, convertir el proyecto CTA existente, reutilizar el mismo código ni realizar reconversión histórica. Idealmente, CTA debe cerrarse antes de iniciar CTO. Si existe un traslape excepcional, CTA permanece abierto hasta completar todos sus pendientes por completar; puede utilizarse opcionalmente «6. En Construcción», a criterio de Consultoría, y CTO opera simultáneamente bajo su código independiente. |
| P245 directo original | MODIFICAR | El Asistente Administrativo debe: | Para la transición administrativa y documental, el Asistente Administrativo debe: |
| P249 directo original | MODIFICAR | Crear el proyecto en QBO e importarlo a Mawi, conforme al procedimiento COM-SOP-01-V1-2026. | Crear el nuevo proyecto CTO independiente en QBO, importarlo a Mawi y ejecutar su configuración administrativa inicial, conforme al procedimiento COM-SOP-01-V1-2026. |
| P250 directo original | MODIFICAR | Previo al traslado, el Departamento de Consultoría debe: | Para la entrega técnica, previo al traslado, el Departamento de Consultoría debe: |
| Listado técnico, después de P255 | AGREGAR PÁRRAFO | [Párrafo inexistente] | Entregar la memoria técnica del proyecto al Departamento de Construcción. |
| Tabla 7 — Tramitología / columna 1 | MODIFICAR | Archivo XML de tareas importado | Plantilla MS Project / archivo XML importado a Mawi |
| Tabla 7 — Tramitología / columna 2 | MODIFICAR | POR DEFINIR | Departamento de Consultoría |
| Tabla 7 — Tramitología / columna 5 | MODIFICAR | Cargar la tramitología aplicable | Carga de tareas de tramitología y fechas restrictivas aplicables |
| Tabla 7 — Transición / columna 1 | MODIFICAR | Evidencia de transición a Construcción | Evidencia de entrega técnica y transición a Construcción |
| Tabla 7 — Transición / columna 2 | MODIFICAR | Asistente Administrativo | Departamento de Consultoría (entrega técnica) / Asistente Administrativo (transición administrativa y documental) |
| Tabla 7 — Transición / columna 5 | MODIFICAR | Documentar la transición | Documentar la entrega técnica de Consultoría y la creación del nuevo proyecto CTO independiente. Idealmente, CTA se cierra antes de iniciar CTO; excepcionalmente, puede existir un traslape temporal mientras CTA mantiene pendientes por completar. |
| Tabla 7 — Presupuesto CTA / fila nueva de cinco columnas | AGREGAR FILA | [Inexistente] | Presupuesto de Consultoría cargado &#124; Asistente Administrativo (asignación PROVISIONAL, pendiente de confirmación del ID08) &#124; Al cargar el presupuesto de Consultoría &#124; Mawi · Presupuesto &#124; Registrar el presupuesto de Consultoría y permitir la sincronización con QBO |
| Tabla 8 — Traslado CTA → CTO / Condición | MODIFICAR | ¿Continúa el mismo proyecto? | ¿El proyecto CTA continúa a Construcción? |
| Tabla 8 — Traslado CTA → CTO / Control | MODIFICAR | Aplicar la ruta 1 o la ruta 2 según el criterio definido | Crear un proyecto CTO nuevo e independiente en QBO e importarlo a Mawi, conservando el mismo cliente y nombre base y utilizando su propio código CTO conforme a GEN-SOP-05-V1-2026. |
| Tabla 8 — Proyecto CTO independiente / Condición | MODIFICAR | ¿Se crea un proyecto nuevo? | ¿Se creó el nuevo proyecto CTO con su código independiente? |
| Tabla 8 — Proyecto CTO independiente / Control | MODIFICAR | Crear desde QBO e importar; verificar pendientes | Verificar la creación del nuevo proyecto CTO en QBO y su importación a Mawi. Idealmente, cerrar CTA antes de iniciar CTO; si existe un traslape excepcional, mantener CTA abierto hasta completar todos sus pendientes por completar y CTO activo bajo su código independiente. |
| Tabla 8 — Proyecto atrasado / Control | MODIFICAR | Escalar conforme a la sección 16 | Escalar y dar seguimiento mediante Mawi o medios oficiales. |
| P269 directo original | MODIFICAR | •  Procedimiento/instructivo específico para crear clientes y proyectos en QBO. [PENDIENTE DE DEFINICIÓN INTERNA] | •  Definición institucional del procedimiento/instructivo QBO o su incorporación al Manual del AA — ID12. |
| P277 directo original | MODIFICAR | •  Ubicación oficial de la plantilla Microsoft Project de tramitología. [POR DEFINIR] | •  Ubicación oficial de la plantilla Microsoft Project de tramitología: [POR DEFINIR]. |
| Sección 25 — P270 | ELIMINAR | •  Inclusión permanente de «SEMANA ENTREGA» en la vista maestra. [POR VALIDAR] | [Eliminado] |
| Sección 25 — P271 | ELIMINAR | •  Eventos de Mawi que eventualmente habiliten o alerten sobre cobros. [PROPUESTA FUTURA PARA VALIDACIÓN] | [Eliminado] |
| Sección 25 — P272 | ELIMINAR | •  Método oficial para que Consultoría comunique a Proveeduría el proyecto correspondiente a una factura. [PENDIENTE DE DEFINICIÓN INTERNA] | [Eliminado] |
| Sección 25 — P273 | ELIMINAR | •  Uso de tareas/etiquetas de Mawi para esa comunicación. [PROPUESTA PARA VALIDACIÓN] | [Eliminado] |
| Sección 25 — P274 | ELIMINAR | •  Criterio para elegir entre trasladar el mismo proyecto CTA → CTO o crear un proyecto CTO independiente. [PENDIENTE DE DEFINICIÓN INTERNA] | [Eliminado] |
| Sección 25 — P275 | ELIMINAR | •  Módulo exacto de Mawi para el registro de gastos directos. [POR VALIDAR] | [Eliminado] |
| Sección 25 — P276 | ELIMINAR | •  Periodicidad o tratamiento definitivo de los pagos relacionados con la póliza INS. [POR VALIDAR] | [Eliminado] |
| Sección 25 — P278 | ELIMINAR | •  Solicitud a proveedores para incluir el nombre/identificador del proyecto en la factura. [PROPUESTA PARA VALIDACIÓN] | [Eliminado] |
| Sección 25 — encabezado institucionales | AGREGAR | [Inexistente] | Pendientes institucionales |
| Sección 25 — ID08 | AGREGAR | [Inexistente] | •  Confirmación definitiva del responsable de cargar el presupuesto CTA en Mawi — ID08. |
| Sección 25 — Manual AA | AGREGAR | [Inexistente] | •  Código/ubicación oficial del Manual Operativo del AA — ID12. |
| Sección 25 — encabezado locales | AGREGAR | [Inexistente] | Pendientes documentales locales |
| Sección 25 — plantilla Presupuesto | AGREGAR | [Inexistente] | •  Ubicación oficial de la plantilla de Presupuesto: [POR DEFINIR]. |

No se aplicaron ajustes de formato adicionales ni `w:cantSplit`. La fila nueva se clonó de una fila compatible de la Tabla 7, conservando las cinco columnas, propiedades de celda, anchos, bordes y estilos. La numeración automática del paso 1 se conservó; no se añadió un segundo «1.» literal.

## D. QA textual

Búsqueda en el contenido textual OOXML del integrado, con revisión de contexto:

| Término buscado | Coincidencias | Resultado |
| --- | ---: | --- |
| [REFERIR AL PROCEDIMIENTO CORRESPONDIENTE: GEN-SOP-05] | 0 | Ausencia esperada confirmada |
| cuatro (4) pasos | 0 | Ausencia esperada confirmada |
| Importa los proyectos desde Mawi | 0 | Ausencia esperada confirmada |
| inicio operativo del proyecto, una vez formalizada la firma y el primer cobro | 0 | Ausencia esperada confirmada |
| #Definir si la realiza el Departamento de Consultoría o el AA | 0 | Ausencia esperada confirmada |
| #Si se determina que lo sube el AA | 0 | Ausencia esperada confirmada |
| COM-01-V1-2026 | 0 | Ausencia esperada confirmada |
| sección 16 | 0 | Ausencia esperada confirmada |
| ¿Continúa el mismo proyecto? | 0 | Ausencia esperada confirmada |
| ¿Se crea un proyecto nuevo? | 0 | Ausencia esperada confirmada |
| ruta 1 o la ruta 2 | 0 | Ausencia esperada confirmada |
| #Incorporar aquí una lista | 0 | Ausencia esperada confirmada |
| ID08 | 4 | Presencia esperada confirmada |
| ID12 | 2 | Presencia esperada confirmada |
| XX/08/2026 | 1 | Presencia esperada confirmada |
| [POR DEFINIR: ubicación oficial de la plantilla de Presupuesto] | 1 | Presencia esperada confirmada |
| [POR DEFINIR: ubicación oficial de la plantilla Microsoft Project de tramitología] | 1 | Presencia esperada confirmada |
| [PROPUESTA: solicitar a SETENA | 1 | Presencia esperada confirmada |

Se conservan exactamente la propuesta completa SETENA/GeoTec/EMECSA, las once definiciones y los nueve indicadores. Las prohibiciones de convertir/renombrar CTA o realizar reconversión histórica son texto válido de la regla aprobada, no alternativas operativas. La referencia a cuatro componentes de configuración permanece válida; se corrigió exclusivamente la enumeración de cinco pasos de activación.

La configuración de tramitología corresponde íntegramente a Consultoría. El presupuesto es PROVISIONAL para AA, sin resolver ID08. Activación administrativa e inicio operativo condicionado al pago quedan diferenciados en el paso 1.

La extracción Markdown incluye todos los párrafos del cuerpo y pie, las 21 tablas del cuerpo y la tabla del pie, celdas combinadas identificadas, listas con numeración y recuadros. Se verificó la cobertura de todos los nodos de texto. Los campos del pie muestran su valor almacenado en el DOCX; el PDF actualiza el total a 21, sin cambiar el DOCX.

## E. Elementos preservados

- Nueve originales y cuatro DOCX aprobados: verificados byte por byte contra Git antes de la integración; sin cambios.
- Metadatos, involucrados, control de versiones, `XX/08/2026`, «Versión inicial aprobada.» y campos administrativos `[POR DEFINIR]` preservados.
- Objetivo, once definiciones, catálogo de siete fases, tabla maestra, reuniones, tareas técnicas, modificaciones, notas de cobro, ficha económica, Excel, gastos, INS, Municipalidad, Registro Nacional, cierre y nueve indicadores preservados salvo las intervenciones expresamente registradas.
- 544 párrafos originales conservan su árbol OOXML íntegro. Los restantes 36 corresponden exactamente a 26 modificaciones y diez eliminaciones registradas; no se detectaron modificaciones ajenas al registro.
- Propiedades de tablas y rejillas de columnas idénticas; se mantiene la estructura nativa. Propiedades de párrafo y runs de los párrafos modificados preservadas; solo cambian texto y atributos de espacio necesarios.
- Estilos, numeración, saltos fuente, sección, pie, relaciones y demás partes no afectadas preservados. La fuente no tiene encabezado independiente ni imágenes incorporadas.
- No se creó RACI, no se inventaron rutas, fechas o códigos, ni se avanzó a PRO-SOP-01.

## F. Pendientes vigentes

### Estado de revisión de integración

Revisión independiente y aprobación del integrado: aprobadas. Ubicación actual: `02_APROBADOS_AUDITORIA_FINAL/CTA-SOP-01-V1-2026_INTEGRADO.docx`. Los pendientes institucionales, documentales locales y de peinado, así como las observaciones visuales conservadas, no son pendientes de integración ni nuevos hallazgos transversales.

### Institucionales

- ID08: confirmación definitiva del responsable de cargar el presupuesto CTA en Mawi. AA continúa PROVISIONALMENTE.
- ID12: código y ubicación oficial del Manual Operativo del AA.
- ID12: definición institucional del procedimiento/instructivo QBO o incorporación al Manual del AA. No se adoptó ninguna alternativa.

### Documentales locales

- Ubicación oficial de la plantilla de Presupuesto: `[POR DEFINIR]`.
- Ubicación oficial de la plantilla Microsoft Project de tramitología: `[POR DEFINIR]`.
- Campos administrativos `[POR DEFINIR]` preservados para formalización.

### Peinado final

[PENDIENTE DE PEINADO FINAL – fecha fuente XX/08/2026 pendiente de formalización documental]

[PENDIENTE DE PEINADO FINAL – propuesta preexistente sobre inclusión del nombre/identificador del proyecto en facturas de proveedores; requiere decisión local antes de oficialización]

Ambos no son pendientes de integración, no son hallazgos transversales y no bloquean la integración. La propuesta sobre proveedores permanece intacta en el desarrollo, no se convierte en obligación y se revisará durante el peinado final individual de CTA. Su viñeta equivalente en la Sección 25 se eliminó conforme a aprobación.

Nuevos pendientes de integración: ninguno. Las referencias COM incorrecta y sección 16 quedaron corregidas según autorización.

## G. QA visual

Renderizados mediante LibreOffice: original completo, páginas 1–19; integrado completo, páginas 1–21. Revisión visual de todas las páginas mediante imágenes renderizadas, con ampliación de las zonas afectadas.

| Zona | Páginas del integrado | Resultado |
| --- | --- | --- |
| Identificación, control y alcance | 1 | Metadatos y colores fuente conservados; referencia GEN05 corregida. |
| Definiciones y Tabla 3 | 2–3 | Texto de roles legible, sin desbordamiento. La fila AA continúa entre páginas, como ya ocurría en el original. |
| Sistemas y lineamientos | 3–4 | Referencias y pendientes visibles; pie correcto. |
| Activación y presupuesto | 5 | Cinco pasos, distinción administrativa/operativa y presupuesto provisional legibles. |
| Tramitología y Fase Consultoría | 6–7 | Doce pasos y catálogo intactos; aclaración opcional legible. La última fila de atributos continúa en página 7 sin pérdida textual. |
| Tabla maestra y seguimiento | 7–11 | Contenido conservado. Página 8 de baja ocupación por crecimiento previo y salto fuente al siguiente bloque. |
| Cuentas por cobrar | 12–13 | Referencia COM corregida y flujo financiero conservado. |
| Gastos | 13–15 | Propuesta sobre proveedores intacta; flujos y recuadros conservados. |
| Transición CTA → CTO | 16–17 | Independencia, pendientes amplios, deslinde y memoria técnica legibles. Página 17 de baja ocupación por continuación de listado y salto fuente a Anexos. |
| Tabla 7 | 18–19 | Nueva fila de cinco columnas con formato nativo; tramitología y transición completas. |
| Tabla 8 | 19–20 | Controles corregidos legibles; fila de gasto reembolsable continúa entre páginas sin pérdida. |
| Indicadores | 20–21 | Nueve indicadores intactos; una celda continúa entre páginas, comportamiento de división de filas también presente en el original. |
| Sección 25, control de cambios y firmas | 21 | Dos grupos de pendientes y cinco viñetas finales; campos y firmas conservados. |

No se detectaron texto fuera de celdas, superposiciones, deformaciones de columnas ni páginas completamente en blanco. Las tablas pueden continuar entre páginas y algunas filas se dividen; esto se documenta, no se presenta como ausencia absoluta de cortes. La paginación de 21 páginas responde a la expansión autorizada conservando los saltos fuente. Las páginas 8 y 17 de baja ocupación y las continuaciones de filas se dejan para valoración en el peinado visual individual, sin constituir un nuevo hallazgo de proceso ni pendiente de integración.

El pie permanece correcto en todas las páginas y muestra el número actual y total renderizado. Los resaltados heredados de los segmentos reemplazados se preservan, sin limpieza estilística. No hay imágenes que pudieran perderse. Ajustes de formato durante el renderizado: ninguno; no se utilizó `w:cantSplit` ni se alteraron saltos, márgenes, tamaños, columnas o numeración.
