# COM-SOP-01 — Control de integración

Artefacto de auditoría; no forma parte del procedimiento oficial.

## A. Identificación

- Original: `00_ORIGINALES/COM-SOP-01-V1-2026 Gestión de Ofertas.docx`.
- SHA-256 original: `92b833eed7fc654d678ba2d34f64656e4879c9ca8623baa241c33ff875a6fda6`.
- Integrado: `02_APROBADOS_AUDITORIA_FINAL/COM-SOP-01-V1-2026_INTEGRADO.docx`.
- SHA-256 integrado: `c29d80c4b30a2b3fbb1ef095f73cc3909cbf1459e9c3a8e6343ab2590db10bc8`.
- Estado: **COM-SOP-01: integración aprobada**. Revisión independiente aprobada. Las observaciones visuales registradas en el QA no son pendientes de integración ni hallazgos transversales nuevos; se revisarán durante el peinado individual final.
- Commit de incorporación: commit dedicado que agrega el integrado y estos artefactos; su SHA se entrega al usuario y se recupera mediante `git log --diff-filter=A -- 01_INTEGRACION/COM-SOP-01-V1-2026_INTEGRADO.docx`.
- Base de decisiones: comparación aprobada y correcciones finales del usuario, incluido el paquete completo de autorización. No se aplicaron propuestas anteriores sustituidas.

## B. Comparación estructural

| Medida | Original | Integrado |
| --- | --- | --- |
| Párrafos del cuerpo, incluidas celdas | 1035 | 1038 |
| Tablas del cuerpo | 38 | 38 |
| Imágenes únicas del paquete | 1 | 1 |
| Comentarios Word | 8 | 8 |
| Secciones Word | 1 | 1 |
| Páginas renderizadas | 27 | 28 |

Se agregaron cuatro párrafos: declaración de fuente principal, regla de activación ordinaria/excepcional, campo Ubicación y deslinde del presupuesto técnico CTO. Se eliminó el párrafo que contenía únicamente «No aplica para licitaciones.». Diferencia neta: +3 párrafos. La otra oración eliminada pertenecía a un párrafo que se conserva. No se agregaron ni eliminaron filas, columnas o tablas.

La expansión de las definiciones, sistemas y matriz aumenta la ocupación del bloque inicial. Al conservar sus saltos manuales, el último punto de Faltas o incumplimientos pasa a una página propia (página 7), aumentando el total en una página. El resto de los saltos y la sección Word se conservan; no hubo reconstrucción ni cambio global de márgenes, tipografía o espaciado.

## C. Cambios individuales

P indica el ordinal del párrafo directo del cuerpo original, sin contar celdas. Los números de tabla citados corresponden a los captions fuente. Hay 28 operaciones de edición: 23 modificaciones de párrafos existentes (una consiste en eliminar una oración), cuatro adiciones y una eliminación de párrafo. En la relación siguiente se desglosa además el presupuesto CTA y la tramitología en dos filas separadas para facilitar su revisión individual.

| Ubicación | Tipo | Texto original | Texto integrado |
| --- | --- | --- | --- |
| Después del alcance (P014) | AGREGAR PÁRRAFO | [Párrafo inexistente] | COM-SOP-01-V1-2026 es la fuente principal del ciclo comercial y de la activación administrativa posterior a la formalización comercial. La configuración técnica de Construcción se rige por CTO-SOP-01-V1-2026 y la gestión documental detallada por GEN-SOP-05-V1-2026. |
| Tabla 2 — Control de Oficio | MODIFICAR | Archivo corporativo ubicado en el servidor (carpeta «Público») donde se lleva el consecutivo general de los documentos de la empresa y se asigna el número de oficio. [POR DEFINIR: ruta oficial del archivo Control de Oficio] | Archivo corporativo ubicado en el servidor, carpeta «Público», donde se lleva el consecutivo general de los documentos de la empresa y se asigna el número de oficio. La ubicación oficial es \\192.168.1.5\08 Publico\01 Ordenar\Control Oficio. |
| Tabla 2 — Activación administrativa | MODIFICAR | Preparación del proyecto tras la aceptación de la oferta (Excel, QBO, Mawi, expediente, comunicación y coordinación del primer cobro). No autoriza iniciar trabajos. | Fase ejecutada por el Asistente Administrativo después de la formalización comercial: oferta de servicios profesionales firmada para Consultoría o contrato constructivo firmado/formalizado para Construcción. Comprende la creación del cliente/proyecto en QBO, su importación y configuración administrativa inicial en Mawi, la habilitación documental correspondiente, la creación o transición del grupo de WhatsApp y las notificaciones internas aplicables. No autoriza por sí misma el inicio operativo en sitio. |
| P029 directo original | MODIFICAR | El envío y el seguimiento por canales de la empresa se realizan conforme a GEN-SOP-06-V1-2026 y a GEN-INS-01-V1-2026 (Reglas de Convivencia). [REFERIR AL PROCEDIMIENTO CORRESPONDIENTE] | El envío y el seguimiento por canales de la empresa se realizan conforme a GEN-SOP-06-V1-2026 y GEN-INS-01-V1-2026. |
| Sección 7 — Regla general | MODIFICAR | ⚠ Regla general:  Ningún proyecto puede iniciar operativamente sin la confirmación del pago inicial correspondiente. La aceptación de la oferta activa la preparación administrativa, no autoriza iniciar trabajos. | ⚠ Regla general:  Ningún proyecto puede iniciar operativamente sin la confirmación del pago inicial correspondiente. La formalización comercial —oferta de servicios profesionales firmada para Consultoría o contrato constructivo firmado/formalizado para Construcción— activa la preparación administrativa, no autoriza iniciar trabajos. |
| Tabla 6 — Control de Oficio | MODIFICAR | Archivo corporativo (carpeta «Público» del servidor) mediante el cual se asigna el número de oficio a los documentos de la empresa. [POR DEFINIR: ruta oficial del archivo Control de Oficio] | Archivo corporativo (carpeta «Público» del servidor) mediante el cual se asigna el número de oficio a los documentos de la empresa. Ubicación oficial: \\192.168.1.5\08 Publico\01 Ordenar\Control Oficio. |
| Tabla 6 — QBO | MODIFICAR | Sistema contable utilizado para crear proyectos tras la aprobación de la oferta o la firma del contrato. | Sistema contable utilizado para crear el cliente/proyecto tras la firma de la oferta de servicios profesionales para Consultoría o la firma/formalización del contrato constructivo para Construcción. |
| Tabla 6 — Mawi | MODIFICAR | Sistema de gestión de proyectos al que se importa el proyecto desde QBO tras la aceptación. No sustituye al Excel de seguimiento de ofertas comercial durante la negociación. | Sistema de gestión de proyectos al que se importa el proyecto desde QBO tras la formalización comercial. No sustituye al Excel de seguimiento de ofertas comercial durante la negociación. |
| P036 directo original | MODIFICAR | El Excel es la herramienta oficial de gestión y seguimiento comercial; el Control de Oficio administra el consecutivo corporativo; Word se utiliza para elaborar; el PDF es la versión oficial emitida; el servidor es el repositorio documental; el correo y WhatsApp son medios de comunicación y trazabilidad; y QBO y Mawi intervienen después de la aceptación, durante la activación administrativa. La información entre sistemas debe ser coherente y mantenerse actualizada. | El Excel es la herramienta oficial de gestión y seguimiento comercial; el Control de Oficio administra el consecutivo corporativo; Word se utiliza para elaborar; el PDF es la versión oficial emitida; el servidor es el repositorio documental; el correo y WhatsApp son medios de comunicación y trazabilidad; y QBO y Mawi intervienen después de la formalización comercial, durante la activación administrativa. La información entre sistemas debe ser coherente y mantenerse actualizada. |
| P039 directo original | MODIFICAR | CTA-SOP-01-V1-2026: Gestión de Proyectos de Consultoría en Mawi. | CTA-SOP-01-V1-2026: Gestión Interna de Proyectos de Consultoría en Mawi. |
| Tabla 7 — Activación administrativa / Valida (excepción) | MODIFICAR | Solo excepción | — |
| Tabla 7 — Activación administrativa / Suministran info | MODIFICAR | — | Gerencia Presidencial / Gerencia General / participantes de la gestión con el cliente que dispongan de la formalización comercial. Cuando Ingeniería haya liderado una licitación o venta especial, Ingeniería remite al Asistente Administrativo el Correo de Solicitud de Apertura. |
| Tabla 7 — Activación administrativa / Se informa a | MODIFICAR | Áreas / Dir. Adm.-Fin. | CTO: toda la empresa. CTA: Departamento de Consultoría y Departamento Administrativo-Financiero. |
| P228 directo original | MODIFICAR | Ante modificaciones, se procede conforme al punto (Modificaciones). | Ante modificaciones, se procede conforme al apartado «Modificaciones». |
| Después de habilitadores de activación (P280) | AGREGAR PÁRRAFO | [Párrafo inexistente] | En la gestión comercial ordinaria, una vez disponible para el Asistente Administrativo la formalización comercial correspondiente, este ejecuta la activación administrativa sin exigir un Correo de Solicitud de Apertura adicional. Cuando Ingeniería haya liderado la gestión comercial, por ejemplo en licitaciones o ventas especiales, Ingeniería envía al Asistente Administrativo el Correo de Solicitud de Apertura. |
| P285 directo original | MODIFICAR | Por definir: Correo de apertura y presentación de proyecto | Emisión del Correo de Confirmación de Mawi y Carpeta en Servidor, una vez completada la configuración administrativa inicial en Mawi y habilitada la carpeta correspondiente en el servidor. |
| P287 — WhatsApp durante activación | ELIMINAR PÁRRAFO | No aplica para licitaciones. | [Eliminado sin sustitución] |
| P290 directo original | MODIFICAR | Enviar el mensaje de bienvenida y presentación del equipo, adjuntando la oferta aprobada, el contrato (cuando aplique) y la información de las cuentas bancarias de AC Desarrollos. Si la oferta o el contrato se encuentran pendientes de firma, se deberá coordinar su formalización en ese mismo momento. | Enviar el mensaje de bienvenida y presentación del equipo, adjuntando la oferta aprobada, el contrato (cuando aplique) y la información de las cuentas bancarias de AC Desarrollos. |
| P303 directo original | MODIFICAR | Para poder crear el proyecto en Mawi, requisito necesario para registrar gastos e iniciar actividades en sitio, previamente deberán crearse el cliente y el proyecto en QBO. | Para importar el proyecto a Mawi y completar su configuración administrativa inicial, previamente deberán crearse el cliente y el proyecto en QBO. Esta activación administrativa no autoriza por sí misma el inicio operativo en sitio. |
| P321 directo original | MODIFICAR | Nombre del proyecto: deberá utilizarse la siguiente estructura: | Nombre del proyecto: deberá utilizarse la siguiente estructura, conforme a GEN-SOP-05-V1-2026: |
| P323 directo original | MODIFICAR | [Prefijo Dpto.] #[Consecutivo]-[Año] [Nombre del cliente] – [Nombre del proyecto] | Código – Cliente – Nombre base del proyecto |
| P331 directo original | MODIFICAR | Ejemplo: CTO #01-2026 Laura Gutiérrez – Remodelación de fachada | Ejemplo: CTO-122-2026 – Laura Gutiérrez – Remodelación de Fachada |
| P343 directo original | MODIFICAR | Solicitud de apertura de proyecto la realiza Gera o Génesis? En qué punto exactamente? La alerta de inicio no puede ser solamente el grupo de WA. | Notificación de la activación administrativa: una vez creado e importado el proyecto y completada su configuración administrativa inicial en Mawi, y habilitada la carpeta correspondiente en el servidor, el Asistente Administrativo emite el Correo de Confirmación de Mawi y Carpeta en Servidor a las áreas involucradas. Debe confirmar obligatoriamente: (1) proyecto creado/importado y configurado administrativamente en Mawi; y (2) carpeta del servidor habilitada. La mención de QBO es opcional. El grupo de WhatsApp no sustituye este correo. |
| Configuración Mawi — después de Uso (P349) | AGREGAR PÁRRAFO | [Párrafo inexistente] | Completar el campo «Ubicación» con la ubicación del proyecto. |
| P351 directo original | MODIFICAR | Para proyectos de Consultoría se debe indicar «Entrega AP», «Entrega PC» y «Entrega TR» con las fechas establecidas en oferta para anteproyecto, planos constructivos y tramitología, respectivamente. | Para proyectos de Consultoría se debe indicar «Entrega AP», «Entrega PC» y «Entrega TR» con las fechas establecidas en la oferta de servicios profesionales firmada para anteproyecto, planos constructivos y tramitología, respectivamente. |
| Después de Equipo General y P356, antes del deslinde CTA | AGREGAR PÁRRAFO | [Párrafo inexistente] | La carga del presupuesto técnico de obra corresponde al Departamento de Construcción y se rige por CTO-SOP-01-V1-2026. No corresponde al Asistente Administrativo. |
| P357 — presupuesto CTA / ID08 | MODIFICAR | Para proyectos de Consultoría, el Asistente Administrativo debe realizar la carga del presupuesto y de las tareas de tramitología en conformidad al CTA-SOP-01-V1-2026. | La carga del presupuesto de Consultoría en Mawi queda PROVISIONALMENTE asignada al Asistente Administrativo, pendiente de confirmación institucional del Hallazgo ID08. |
| P357 — deslinde de tramitología | MODIFICAR | Para proyectos de Consultoría, el Asistente Administrativo debe realizar la carga del presupuesto y de las tareas de tramitología en conformidad al CTA-SOP-01-V1-2026. | La configuración y carga de las tareas de tramitología corresponde al Departamento de Consultoría conforme a CTA-SOP-01-V1-2026 y no al Asistente Administrativo. |
| P389 directo original | MODIFICAR | •  Anexo C. Excel de seguimiento de ofertas — columnas de la sección 12. [POR DEFINIR: elaborar archivo] | •  Anexo C. Excel de seguimiento de ofertas — columnas de la Tabla 8. [POR DEFINIR: elaborar archivo] |

Las dos filas de P357 reproducen por separado las dos oraciones finales del mismo párrafo; el texto original se muestra completo en ambas para mantener su contexto. P290 conserva íntegra la instrucción de bienvenida y documentos y elimina únicamente la oración relativa a firmas pendientes.

## D. Ajustes de formato

No se aplicaron ajustes adicionales de formato. No fue necesario incorporar `w:cantSplit`: las filas modificadas de Tablas 2, 6 y 7 quedan completas en sus páginas. Se mantienen las propiedades de los párrafos y runs existentes, incluso sus resaltados fuente. Los cuatro párrafos añadidos reutilizan el formato nativo de los párrafos adyacentes compatibles. No se reordenaron ni renumeraron los apartados 6. Notificación y 7. Configuración.

## E. QA textual

Búsqueda sin distinguir mayúsculas/minúsculas en el texto del cuerpo integrado. Las coincidencias históricas en este control, dentro de «Texto original», no son contenido vigente del procedimiento.

| Término | Apariciones en integrado | Resultado |
| --- | --- | --- |
| Gera o Génesis | 0 | Sin residuo en el cuerpo integrado. |
| No aplica para licitaciones | 0 | Sin residuo en el cuerpo integrado. |
| [Prefijo Dpto.] | 0 | Sin residuo en el cuerpo integrado. |
| CTO #01-2026 | 0 | Sin residuo en el cuerpo integrado. |
| [POR DEFINIR: ruta oficial del archivo Control de Oficio] | 0 | Sin residuo en el cuerpo integrado. |
| punto (Modificaciones) | 0 | Sin residuo en el cuerpo integrado. |
| columnas de la sección 12 | 0 | Sin residuo en el cuerpo integrado. |
| [REFERIR AL PROCEDIMIENTO CORRESPONDIENTE] | 0 | Sin residuo en el cuerpo integrado. |
| Solo excepción | 0 | Sin residuo en el cuerpo integrado. |
| tareas de tramitología | 1 | Corresponden al Departamento de Consultoría, no al AA. |
| presupuesto | 8 | Se conservan usos comerciales; presupuesto CTO corresponde a Construcción y carga CTA al AA provisionalmente. |
| ID08 | 1 | Asignación del presupuesto CTA expresamente PROVISIONALMENTE; pendiente institucional. |
| VH-HIST-01 | 1 | Mismo número de apariciones y mismo contexto que en la fuente; preservado. |
| VH-HIST-02 | 2 | Mismo número de apariciones y mismo contexto que en la fuente; preservado. |
| VH-HIST-03 | 1 | Mismo número de apariciones y mismo contexto que en la fuente; preservado. |
| VH-HIST-04 | 1 | Mismo número de apariciones y mismo contexto que en la fuente; preservado. |
| VH-HIST-05 | 3 | Mismo número de apariciones y mismo contexto que en la fuente; preservado. |
| CORP-007 | 2 | Mismo número de apariciones y mismo contexto que en la fuente; preservado. |
| CORP-008 | 2 | Mismo número de apariciones y mismo contexto que en la fuente; preservado. |
| Manual Operativo del Asistente Administrativo | 1 | Referencia conservada con [POR DEFINIR: código y ubicación oficial]. |

Verificaciones adicionales:

- Ruta oficial de Control de Oficio: cuatro apariciones. Dos originales conservadas y dos sustituciones de marcadores pendientes.
- Nomenclatura y ejemplo aprobados presentes; no se elimina la explicación compatible de prefijos CTO/CTA.
- Configuración QBO y pasos completos de importación a Mawi conservados. No se asigna al AA creación directa en Mawi.
- Ubicación agregada; Etapa, Uso, fechas y Equipo General conservados, con fechas CTA expresamente conforme a oferta firmada.
- Fuente principal, formalización como disparador y excepción de Ingeniería presentes; no se inventó Departamento Comercial.
- Tabla 7: AA ejecuta; Valida = «—»; información y destinatarios corresponden exactamente a las decisiones aprobadas. No se creó fila ni RACI.
- La notificación confirma Mawi configurado y carpeta habilitada, exige completar ambas condiciones antes del envío y no admite sustituir el correo por WhatsApp. El orden físico 6 → 7 permanece.
- No se reprodujeron trámites, dependencias, MS Project/XML ni pasos técnicos CTA en el nuevo deslinde de tramitología.
- Referencia CTA con «Gestión Interna» corregida. Denominación fuente GEN-SOP-05 conservada.
- Anexo C remite a Tabla 8 y conserva [POR DEFINIR: elaborar archivo]. Modificaciones utiliza el título del apartado existente.
- Las notas preexistentes no autorizadas para eliminación y todos los comentarios permanecen; no se resolvieron por inferencia.

## F. QA visual

Renderizados con LibreOffice y Montserrat. Se revisaron todas las páginas 1–28 del integrado, y se cotejaron en el original los puntos de paginación y formato relevantes.

| Páginas del integrado | Elementos revisados | Resultado |
| --- | --- | --- |
| 1 | Portada, metadatos, versiones, objetivo, alcance y fuente principal | Legibles; contenido agregado dentro de márgenes. |
| 2–3 | Tabla 2, definiciones ampliadas y Tabla 3 | Definiciones modificadas completas y sin texto fuera de celdas. La tabla continúa en página 3. |
| 4–5 | Canales, regla de formalización, Tabla 6 y referencias | Ruta y sistemas legibles; filas modificadas completas. La fila no modificada de Excel continúa entre páginas 4 y 5. |
| 5–6 | Tabla 7 | Cinco columnas y diez filas preservadas. La fila de Activación queda completa y legible en página 6; crece verticalmente para contener el texto aprobado. |
| 6–7 | Faltas/incumplimientos | Texto preservado. La página 7 contiene únicamente el último punto, debido al crecimiento previo y al salto manual fuente. Se registra esta limitación de distribución visual. |
| 8–15 | Excel, 20 columnas, estados, SLA, proceso comercial, reuniones e insumos | Conservados y legibles; notas fuente intactas. |
| 16–19 | Elaboración, validación, envío, versiones, seguimiento, decisión y contrato | Referencia a Modificaciones corregida. Se conserva una anomalía preexistente: el «2.» del título de Validación aparece junto al recuadro anterior (original página 15 / integrado página 16). La página de cierre de contrato con una sola viñeta ya existía (original 18 / integrado 19). |
| 20–23 | Activación, expediente, QBO, importación, notificación, configuración y Equipo General | Incorporaciones legibles, pasos completos, orden 6/7 conservado, miembros sin cambios. Presupuesto CTO y provisionalidad CTA visibles; tramitología deslindada. |
| 24–26 | Cuentas por cobrar, registros, decisiones e indicadores | Contenido y fórmulas preservados; tablas legibles. |
| 27–28 | Sección 17, VH-HIST, Anexos A–D y firmas | Historial y advertencia de validación humana intactos; Anexo C corregido. La página con «Fin del documento» aislado ya existía (original 27 / integrado 28). |

No se observaron pérdidas de texto, imágenes, encabezados o pies, ni texto recortado en las celdas modificadas. No hay páginas totalmente vacías. Sí existen las páginas de baja ocupación y la anomalía de título especificadas arriba; por ello este QA no afirma que la maquetación esté lista para oficialización. No se alteraron saltos, estilos o tablas no afectadas para compactarlas. Las observaciones son de presentación, no decisiones nuevas de proceso.

La imagen única es el logotipo del encabezado y permanece idéntica. Los comentarios se verificaron mediante sus partes OOXML y anclajes, porque el PDF de revisión no muestra necesariamente las anotaciones de Word.

## G. Elementos preservados

Solo cambia `word/document.xml`. Todas las demás partes del ZIP son idénticas byte a byte, incluidos estilos, numeración, imagen, encabezado, pie, comentarios, relaciones y metadatos. Se comprobó que, al retirar las cuatro adiciones, reponer el párrafo eliminado y restituir los textos de los 23 párrafos intervenidos, el XML canónico coincide íntegramente con la fuente. Se verificaron también las propiedades de párrafos y runs intervenidos, que permanecen intactas.

Esto incluye las tablas no afectadas, dimensiones y celdas, comentarios y sus anclajes, metadatos y control de versiones, objetivo/alcance, Excel, reuniones, riesgos, Acompañante Comercial, pasos QBO/Mawi no afectados, Equipo General, cuentas por cobrar, cobro inicial, incumplimientos, indicadores, evidencias y anexos salvo la remisión aprobada de Anexo C. No se reconstruyó el documento.

VH-HIST-01, 03 y 04: una aparición cada uno; VH-HIST-02: dos; VH-HIST-05: tres. CORP-007 y CORP-008: dos apariciones cada uno. Se conservan la sección histórica, su estado pendiente de validación humana y las marcas de Anexos A, B y D. Anexo C sigue sin marca VH-HIST. No se armonizó VH-HIST-04 con el proceso vigente.

## H. Pendientes

- **ID08 — pendiente institucional:** responsable definitivo de la carga de presupuesto CTA; la asignación al AA permanece expresamente provisional.
- **ID12 — pendiente institucional:** código y ubicación oficial del Manual AA, y definición institucional sobre instructivo QBO independiente o capítulo del Manual AA. No se inventa ninguna de esas decisiones.
- Campos administrativos [POR DEFINIR], ubicaciones oficiales aún no resueltas de Excel, plantillas, ofertas y respaldos, elaboración/adjuntos de anexos y referencia CFIA: conservados.
- Información histórica VH-HIST: validación humana pendiente conforme a la fuente; no constituye política vigente.
- **[PENDIENTE DE PEINADO FINAL – notas y comentarios de borrador preexistentes en COM-SOP-01 que requieren depuración o decisión local antes de la oficialización]**. Incluye #Propuestas, #Qué información debe obtener, #E imprimir y archivar, compromisos escritos/AC Trabajo, estandarización del cobro, #Algo más, #Solo de consultoría, #Cómo mejorar el traslado de insumos, #o los dos, la duda sobre imprimir una oferta digital y comentarios Word 1, 2, 4 y 8. No es pendiente de integración; no es hallazgo transversal nuevo; no bloquea esta integración; no se resuelve por inferencia. Se revisará durante el peinado final individual de COM. Todos los comentarios permanecen intactos.

No surgió ningún **[NUEVO PENDIENTE DE INTEGRACIÓN]** relativo a decisiones o contenido. Modificaciones, la exclusión de licitaciones y la remisión de Anexo C quedaron resueltos según autorización. Las observaciones de paginación están registradas en F, sin cambiar el contenido aprobado.

No se modificaron los nueve originales ni los integrados aprobados de GEN-SOP-05, CAL-SOP-01 y GEN-SOP-06. No se avanzó a CTA-SOP-01.
