# GEN-SOP-06 — Control de integración

Artefacto de auditoría; no forma parte del procedimiento oficial.

## A. Identificación

- Original: `00_ORIGINALES/GEN-SOP-06-V1-2026 Gestión de Grupos de WhatsApp.docx`.
- SHA-256 original: `884dcbb641d8cd51e3e0561e4d7683a0821e84b8347f91b88b0a1abffa857dba`.
- Integrado: `02_APROBADOS_AUDITORIA_FINAL/GEN-SOP-06-V1-2026_INTEGRADO.docx`.
- SHA-256 integrado: `486d812e6b5bc14113d3344443ebb861736f4a4cfe72462e5f68dac1cddc79f8`.
- Estado: **GEN-SOP-06: integración aprobada**. Revisión independiente aprobada.
- Commit de incorporación: el commit dedicado que introduce este DOCX y estos artefactos; su SHA se entrega al usuario y puede recuperarse mediante `git log --diff-filter=A -- 01_INTEGRACION/GEN-SOP-06-V1-2026_INTEGRADO.docx`.

## B. Comparación estructural

| Medida | Original | Integrado |
| --- | --- | --- |
| Párrafos del cuerpo, incluidas celdas | 320 | 324 |
| Tablas del cuerpo | 18 | 18 |
| Imágenes únicas del paquete | 2 | 2 |
| Secciones Word | 1 | 1 |
| Páginas renderizadas | 13 | 13 |

Los cuatro párrafos nuevos corresponden a la declaración de fuente principal, la distinción del acuse formal de garantías y las referencias CTO y CAL. No se agregaron filas ni tablas. Las dos imágenes son los datos de pago y el logotipo; se conservaron sus bytes. La distribución del contenido cambia localmente, manteniendo 13 páginas en el renderizado con LibreOffice y Montserrat.

## C. Cambios individuales

P indica el ordinal del párrafo directo del cuerpo original, sin contar celdas. Los números OOXML identifican las tablas en su orden físico; se indica también el caption nativo cuando corresponde. Se registran 16 operaciones textuales: 12 sustituciones de párrafo y 4 adiciones. Cada fila reproduce el texto anterior y el integrado completo de la operación, sin resumirlo.

| Ubicación | Tipo de cambio | Texto original | Texto integrado |
| --- | --- | --- | --- |
| Después del alcance y del salto existente P017, antes de Definiciones | AGREGAR PÁRRAFO | [Párrafo inexistente] | GEN-SOP-06-V1-2026 es la fuente principal para la apertura, administración, participantes y normas de los grupos de WhatsApp. Los aspectos especializados se rigen por los procedimientos correspondientes: CAL-SOP-01-V1-2025 regula el proceso formal de garantías; COM-SOP-01-V1-2026 regula la formalización comercial que activa el grupo; y GEN-SOP-05-V1-2026 regula el expediente documental. |
| P139 directo original | MODIFICAR | •  Tiempos máximos de respuesta: Toda consulta recibida durante el horario laboral deberá ser atendida, o al menos acusada de recibirlo, en un plazo máximo de una hora por el colaborador responsable. | •  Tiempos máximos de respuesta: Toda consulta o mensaje recibido de un cliente durante el horario laboral deberá ser atendido, o al menos recibir un acuse de recibido operativo en el chat, en un plazo máximo de 1 hora durante horario laboral por el colaborador responsable. |
| Tiempos de atención, inmediatamente después de P139 original | AGREGAR PÁRRAFO | [Párrafo inexistente] | En la etapa de Garantías, este acuse de recibido operativo en WhatsApp confirma la recepción del mensaje en el chat, pero constituye un hito independiente del acuse de recibo formal del proceso de garantía, que cuenta con un plazo máximo de 1 día hábil conforme a CAL-SOP-01-V1-2025. El acuse de recibido operativo no sustituye al acuse de recibo formal. |
| P140 directo original | MODIFICAR | •  Ausencia o indisponibilidad del responsable: Cuando el responsable de atender una consulta no se encuentre disponible, el Asistente Administrativo deberá responder dentro del plazo establecido, de acuerdo al punto 1.3. | •  Ausencia o indisponibilidad del responsable: Cuando el responsable de atender una consulta no se encuentre disponible, el Asistente Administrativo deberá responder dentro del plazo establecido. |
| P146 directo original | MODIFICAR | Los grupos de WhatsApp con clientes se crean cuando exista una aprobación comercial formalizada de una oferta, de conformidad con lo establecido en el procedimiento COM-01-V1-2026 Gestión de Ofertas. | Los grupos de WhatsApp con clientes se crean cuando exista una aprobación comercial formalizada de una oferta, de conformidad con lo establecido en el procedimiento COM-SOP-01-V1-2026 Gestión de Ofertas. |
| P149 directo original | MODIFICAR | •  Construcción: el grupo se crea cuando el cliente contrata directamente un proyecto constructivo. Cuando el proyecto provenga de la etapa de Consultoría, el grupo deberá transicionar a la etapa de Construcción, ajustando su nombre, participantes y, adjuntando el mensaje del punto X.X. | •  Construcción: el grupo se crea cuando el cliente contrata directamente un proyecto constructivo. Cuando el proyecto provenga de la etapa de Consultoría, el grupo deberá transicionar a la etapa de Construcción, ajustando su nombre y participantes. |
| P150 directo original | MODIFICAR | •  Garantía: cuando finalice el proyecto constructivo y se realice la entrega formal, el grupo deberá transicionar a la etapa de Garantía, quedando destinado exclusivamente al seguimiento de asuntos relacionados con garantías y atención postventa. Se debe adjuntar el mensaje del punto X.X, explicando el procedimiento para el reporte de garantías. | •  Garantía: cuando finalice el proyecto constructivo y se realice la entrega formal, el grupo deberá transicionar a la etapa de Garantía, quedando destinado exclusivamente al seguimiento de asuntos relacionados con garantías y atención postventa. En esta etapa participa obligatoriamente el rol de Aseguramiento de la Calidad, ejercido por el Ingeniero responsable de la obra o por el ingeniero reasignado conforme a CAL-SOP-01-V1-2025. Proveeduría queda totalmente excluida de este y de cualquier otro grupo directo con clientes. La atención y comunicación del proceso formal de garantía se regirán por CAL-SOP-01-V1-2025. |
| Tabla 4 (OOXML 14), Garantía, participantes: párrafo 3 | MODIFICAR | Integrantes del Departamento de Construcción (Gerente de Proyectos e Ingeniero de Proyecto) | Gerente de Proyectos |
| Tabla 4 (OOXML 14), Garantía, participantes: párrafo 4; exclusión de Proveeduría e identificación de AQ | MODIFICAR | Encargado de Proveeduría. | Aseguramiento de la Calidad, ejercido ordinariamente por el Ingeniero de Proyecto responsable de la obra o por el ingeniero reasignado conforme a CAL-SOP-01-V1-2025 |
| P164 directo original | MODIFICAR | •  AC Garantías: utilizado para la coordinación interna y seguimiento de garantías. Participan el personal de Ingeniería y el encargado de Proveeduría, según corresponda, con el fin de brindar acompañamiento técnico y coordinar las acciones requeridas. | •  AC Garantías: grupo interno utilizado para la coordinación operativa de postventa entre Aseguramiento de la Calidad (ejercido por el Ingeniero responsable de la obra o por el ingeniero reasignado conforme a CAL-SOP-01-V1-2025) y Proveeduría. Proveeduría participa en este grupo interno únicamente cuando corresponda o cuando se requiera su apoyo logístico para materiales de reparación, suministros de bodega, alquileres de equipo, limpiezas y retiro de escombros. Este grupo se mantiene como un canal exclusivamente interno, sin presencia del cliente. |
| P176 directo original | MODIFICAR | •  Incluir única y exclusivamente a los participantes necesarios de acuerdo al punto 4.2. | •  Incluir única y exclusivamente a los participantes necesarios conforme al apartado «Criterios para incluir participantes». |
| P178 directo original | MODIFICAR | •  Gestionar el cierre o archivo cuando el grupo deje de ser necesario (punto 4.5). | •  Gestionar el cierre o archivo cuando el grupo deje de ser necesario (ver apartado «Tratamiento para el cierre de grupos»). |
| Tabla 3 (OOXML 4), Gerencia, responsabilidad | MODIFICAR | Valida las excepciones y los casos sensibles (ver sección 16). | Valida las excepciones y los casos sensibles (ver apartado «Consultas que requieren validación previa»). |
| P038 directo original | MODIFICAR | •  CTA-SOP-01-V1-2026 Gestión de Proyectos de Consultoría en Mawi. | •  CTA-SOP-01-V1-2026 Gestión Interna de Proyectos de Consultoría en Mawi. |
| Documentación relacionada; nueva referencia CAL, después de CTO y antes del Manual AA | AGREGAR PÁRRAFO | [Párrafo inexistente] | •  CAL-SOP-01-V1-2025 Gestión de Garantías. |
| Documentación relacionada; nueva referencia CTO, después de CTA | AGREGAR PÁRRAFO | [Párrafo inexistente] | •  CTO-SOP-01-V1-2026 Gestión Integral de Proyectos Constructivos. |

## D. Formato y colocación del contenido agregado

| Ubicación | Ajuste | Antes | Después |
| --- | --- | --- | --- |
| Tabla 4 — Garantía; tabla OOXML 14, fila 4 | Impedir división de la fila entre páginas | Fila dividida entre páginas 10 y 11 en la primera revisión | `w:cantSplit` activado; fila completa en página 11; texto, columnas y dimensiones conservados |

Se ajustó exclusivamente el espaciado de dos párrafos vacíos contiguos al final de Grupos internos (P169 y P170 del original), manteniendo ambos párrafos y el salto manual existente. El traslado íntegro de la fila de Garantía provocaba que estos separadores desbordaran a una página vacía; el ajuste local elimina ese desbordamiento, sin cambiar texto, tablas ni saltos.

| Ubicación | Ajuste | Antes | Después |
| --- | --- | --- | --- |
| P169 — párrafo vacío posterior al recuadro Regla General | Espaciado local | Posterior 60 twips; interlineado automático 254 | Posterior 0; interlineado exacto 20 twips (1 pt) |
| P170 — párrafo del salto manual previo a Creación, apertura y cierre | Espaciado local | Posterior 200 twips; interlineado automático 276 | Posterior 0; interlineado exacto 20 twips (1 pt); salto conservado |

La declaración de fuente principal se incorporó después del alcance, a continuación del salto de página ya existente y antes de Definiciones. Se conserva ese salto sin moverlo ni eliminarlo. Esta colocación evita una página adicional casi vacía. Se conservaron los estilos y propiedades nativas de los párrafos usados para las adiciones. No se normalizaron resaltados, numeración ni modelos; los resaltados que se ven en las sustituciones proceden de los runs de la fuente.

## E. QA textual

Búsqueda sin distinguir mayúsculas/minúsculas, sobre el texto editable del DOCX integrado:

| Término | Apariciones | Evaluación |
| --- | --- | --- |
| X.X | 0 | Sin residuo vigente. |
| COM-01-V1-2026 | 0 | Sin residuo vigente. |
| sección 16 | 0 | Sin residuo vigente. |
| punto 1.3 | 0 | Sin residuo vigente. |
| punto 4.2 | 0 | Sin residuo vigente. |
| punto 4.5 | 0 | Sin residuo vigente. |
| Encargado de Proveeduría | 0 | Sin residuo vigente. |
| personal de Ingeniería | 0 | Sin residuo vigente. |
| fuente única | 0 | Sin residuo vigente. |
| 1 hora | 1 | Regla general operativa durante horario laboral. |
| 1 día hábil | 1 | Acuse formal de CAL, independiente del operativo. |
| CAL-SOP-01-V1-2025 | 7 | Referencias oficiales en fuente principal, tiempos, Garantía, participantes, AC Garantías y documentación relacionada. |
| Manual Operativo del Asistente Administrativo | 1 | Referencia nativa con [POR DEFINIR: código oficial], conservada. |

Se verificó que la fila de Garantía contiene WhatsApp empresarial, Gerencia General, Gerente de Proyectos y Aseguramiento de la Calidad con la identificación aprobada. Proveeduría no figura como participante en ninguna etapa de la Tabla 4. La exclusión general queda expresa en la descripción de Garantía.

AC Garantías contiene exactamente la redacción aprobada, con Proveeduría condicionada a la necesidad de apoyo logístico y sin presencia del cliente. Se conservaron AC Proveeduría, Proyectos AC y los demás grupos internos legítimos. No se aplicó eliminación masiva de términos.

Los dos X.X se resolvieron conforme a las correcciones autorizadas. Las remisiones a Criterios para incluir participantes, Tratamiento para el cierre de grupos y Consultas que requieren validación previa usan títulos existentes, sin inventar numeración. Las menciones antiguas en la columna «Texto original» de este control son historial, no contenido vigente del procedimiento.

## F. QA visual

Se renderizaron y revisaron todas las páginas 1–13. Se verificaron metadatos y tablas iniciales (1–2), documentación relacionada (3), WhatsApp empresarial y modelos (4–7), tiempos de atención (8–9), transición y participantes (10–11) y reglas de creación/cierre (12–13).

La Tabla 4 conserva sus dos columnas, sus cuatro filas y su formato; la fila completa de Garantía pasa a página 11 por el ajuste autorizado. El párrafo ampliado de AC Garantías permanece completo y legible en página 11. No hay texto fuera de celdas ni filas afectadas cortadas. Se conservaron ambas imágenes, encabezado, pie y saltos fuente; no se detectaron páginas en blanco anormales ni pérdida de contenido. La paginación final permanece en 13 páginas.

## G. Elementos preservados

Solo cambió `word/document.xml` dentro del paquete DOCX. Todas las demás partes son idénticas byte a byte: imágenes, estilos, numeración, encabezado, pie, relaciones y demás recursos. Al retirar los cuatro párrafos agregados, restituir los doce párrafos modificados retirar el único `w:cantSplit` incorporado y restituir el espaciado de los dos párrafos vacíos identificados, el XML canónico coincide íntegramente con el original. También se verificó la conservación de propiedades de párrafo y de formato de runs de los párrafos sustituidos.

Por tanto, permanecen intactos los metadatos, la descripción literal del control de versiones, el objetivo y alcance originales, las nueve definiciones, las responsabilidades generales salvo la remisión autorizada de Gerencia, los lineamientos, los modelos institucionales, los otros grupos internos y todas las reglas no afectadas. La documentación relacionada conserva su ubicación y numeración fuente. No se inventaron nombres, códigos, rutas, responsabilidades ni instrucciones QBO. No se creó RACI ni ninguna tabla nueva.

## H. Pendientes

- **ID12 — pendiente institucional:** se conserva `Manual Operativo del Asistente Administrativo: [POR DEFINIR: código oficial].` No se define código, denominación definitiva, ubicación oficial ni instrucción QBO independiente.
- Campos administrativos `[POR DEFINIR]`: conservados sin completar.
- **[PENDIENTE DE PEINADO FINAL – modelo 10.7 contiene nombres propios pese a la regla general «sin nombres reales»]**. No es pendiente de integración; no es hallazgo transversal; se atenderá durante el peinado/QA final. Los modelos permanecen intactos durante esta integración.

No surgió ningún **[NUEVO PENDIENTE DE INTEGRACIÓN]**. Se conservaron los saltos de numeración y numeraciones repetidas fuente para el peinado final. No se modificaron GEN-SOP-05 ni CAL-SOP-01; no se avanzó a COM-SOP-01.
