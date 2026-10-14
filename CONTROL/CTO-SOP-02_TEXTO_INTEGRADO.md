# CTO-SOP-02 — Texto integrado

Artefacto de auditoría; no forma parte del procedimiento oficial. Fuente: `01_INTEGRACION/CTO-SOP-02-V1-2026_INTEGRADO.docx`. Extracción textual fiel en orden del documento. Las etiquetas de tablas y columnas son auxiliares, no texto añadido al procedimiento. Se conservan todas las filas, incluso las vacías; las celdas combinadas aparecen una sola vez. Se conservan numeraciones y modelos fuente sin corregirlos. Los saltos de párrafo dentro de celdas se representan mediante `<br>`.

## Cuerpo

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 1; archivo image1.png; véase caption o título contiguo]

PROCEDIMIENTO DE PRESENTACIÓN DE INFORMES DE PROYECTOS

Manual de Procedimientos

Departamento de Construcción

### Tabla 01 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 |
| --- | --- | --- | --- |
| Procedimiento | Presentación de Informes de Proyecto |  |  |
| Código | CTO-SOP-02-V1-2026 |   Versión |   01 |
| Fecha de elaboración | 20/03/2026 |   Fecha de aprobación |   03/04/2026 |
| Elaborado por | Pablo Rodríguez Mora |  |  |
| Autorizado por | Daniela Bolaños Quirós |  |  |
| Involucrados | Departamento de Construcción, Gerencia General, Departamento Financiero |  |  |

[Celdas combinadas: fila 1, columnas 2–4; fila 4, columnas 2–4; fila 5, columnas 2–4; fila 6, columnas 2–4. Texto reproducido una sola vez.]

Objetivo

Establecer el formato para la generación, análisis y presentación de los Informes de Proyecto, basados en la metodología de Valor Ganado (Earned Value Management, EVM), con el fin de medir objetivamente el desempeño de los proyectos constructivos en costo y plazo, detectar tempranamente desviaciones, estimar el costo y la fecha probable de finalización, y soportar la toma de decisiones sobre datos verificables.

Sistemas oficiales de control y gestión

El proceso de informes opera sobre un conjunto de sistemas y archivos oficiales que deben mantenerse coherentes y actualizados en todo momento:

• Plantilla Oficial de Informes de Proyecto: Archivo Excel oficial para elaborar el Informe 0 y los informes semanales. Contiene las hojas “Informe 0” (línea base) e “Informe” (corte semanal). Sus fórmulas calculan automáticamente valores propios de la metodología EVM, así como los semáforos de estado del proyecto, a partir de la información ingresada por el Ingeniero de Proyecto.

• Mawi (módulo de Presupuesto en “Control Financiero”): sistema oficial de gestión de proyectos. El Costo Real (AC) corresponde al monto facturado a la fecha de corte y se extrae directamente del módulo de Presupuesto.

Es un requisito mantener la coherencia entre estos sistemas, garantizando consistencia entre:

• Lo planificado y proyectado en el Informe 0 y la realidad operativa-financiera.

• Lo dispuesto en el Informe Semanal y lo ejecutado en campo (avance físico).

• Los gastos reales y el valor reflejado en Mawi (AC).

• Lo proyectado en la sección de flujo de caja del Informe Semanal y el flujo de caja de la empresa custodiado por el Departamento Financiero.

Información documental de referencia

La gestión y presentación de informes de proyecto se deriva del uso de los siguientes archivos o sistemas:

• Archivo «01 Machote Oficial de Informes de Proyecto (En Limpio)»: ubicado en &#92;&#92;192.168.1.5&#92;03 Proyectos&#92;Actual&#92;ADMINISTRACION PROYECTOS&#92;Machotes Oficiales Informes de Proyecto EVM.

• Cronograma, presupuesto aprobado, oferta constructiva final y contrato firmado por el cliente, conforme a CTO-SOP-01-V1-2026.

• Órdenes de modificación firmadas y actualizadas en Mawi.

• Bitácoras de inspección y registros de avance físico de obra.

• GEN-SOP-05-V1-2026 — Gestión de Expedientes, para el resguardo e identificación documental del informe.

• CTO-SOP-03-V1-2026 — Comunicación Financiera de Proyectos de Construcción, para la coordinación y validación del flujo de caja con el Departamento Financiero.

La metodología EVM aplicada en este procedimiento se rige por las definiciones y fórmulas del PMBOK® del Project Management Institute (PMI). El cronograma, el presupuesto y la oferta del proyecto definen la línea base; cualquier modificación posterior debe estar respaldada por una orden de cambio aprobada por el cliente y reflejarse en el Informe 0 con previa autorización del Gerente de Proyectos.

Alcance

Este procedimiento aplica para todo proyecto constructivo de AC Desarrollos, desde la aprobación de la oferta constructiva hasta la emisión del Informe de cierre del Proyecto. Es decir, cubre todo proyecto activo por la empresa, sin excepción. Es de aplicación obligatoria para el Departamento de Construcción, y articula las interfaces de información con Gerencia General, Finanzas, y, cuando corresponda, con el cliente.

Canal oficial de revisión y entrega de informes

La reunión semanal de proyectos constituye el espacio oficial de presentación y análisis del informe a nivel de departamento. Posterior a dicha reunión, el envío formal a Gerencia General y al Departamento Financiero del informe revisado se realizará por correo electrónico, agregando todas las observaciones y análisis pertinentes que expliquen los resultados de los indicadores de desempeño y el flujo de caja proyectado. 

Flujo General del proceso

El siguiente diagrama resume la secuencia completa del proceso: elaboración, emisión y aprobación del Informe 0 antes del inicio de las labores constructivas en sitio, seguimiento periódico semanal, presentación en reunión de proyectos y envío formal a Gerencia General y Finanzas. Cada etapa se desarrolla en detalle en las siguientes secciones de este manual.

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 2; archivo image2.png; véase caption o título contiguo]

Figura 1. Flujo general del procedimiento de presentación de Informes de Proyecto

Ante cualquier duda sobre cómo actuar en una situación específica, se recomienda consultar el diagrama para ubicarse en el proceso y luego dirigirse a la sección correspondiente.

Responsables del proceso

Los roles y responsabilidades principales que intervienen en el proceso de gestión de informes son:

### Tabla 02 — orden OOXML

| Columna 1 | Columna 2 |
| --- | --- |
| Rol | Función principal |
| Analista de Procesos | Detecta, registra y notifica incumplimientos y desviaciones al procedimiento. Detectar oportunidades de mejora y diseño del proceso. |
| Ingeniero de Proyecto | Elabora el Informe 0; ejecuta el seguimiento semanal del proyecto; calcula y verifica los indicadores EVM; redacta el análisis técnico; prepara el informe y lo presenta en la reunión de proyectos. |
| Gerente de Proyectos | Aprueba el Informe 0 y autoriza sus modificaciones; revisa y valida los informes periódicos; aprueba los planes de acción; interviene cuando el proyecto entra en estado de riesgo o crítico. |
| Gerencia General | Recibe el informe formal posterior a la reunión de proyectos; toma decisiones estratégicas con base en la información reportada. |
| Finanzas / Administración | Recibe la actualización del flujo de caja; valida la confiabilidad del Costo Real (AC) registrado en Mawi cuando exista duda razonable; comunica eventos relevantes de facturación. |

Tabla 1. Función principal de los participantes del proceso

La asignación detallada de responsabilidades por actividad clave del procedimiento se resume en la siguiente Matriz RACI:

### Tabla 03 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 | Columna 5 |
| --- | --- | --- | --- | --- |
| Actividad clave del procedimiento | Responsable | Aprueba | Consultar | Informar |
| Elaboración del Informe 0 | Ing. de Proyecto | Gerente de Proyectos | — | Gerencia General, Dpto. Financiero |
| Elaboración del Informe Semanal | Ing. de Proyecto | Gerente de Proyectos | — | — |
| Presentación del informe (reunión) | Ing. de Proyecto | Gerente de Proyectos | — | Equipo de Dpto. Construcción |
| Envío formal del informe | Ing. de Proyecto | Gerente de Proyectos | — | Gerencia General, Finanzas |

Tabla 2. Matriz de roles y responsabilidades del proceso

<!-- Párrafo sin texto -->

Faltas o incumplimientos

Se considera incumplimiento o desviación toda acción u omisión que contravenga lo establecido en este procedimiento y que afecte la confiabilidad de la información de los proyectos constructivos o del flujo de caja, así como la toma de decisiones por parte de Gerencia General.

Se consideran, entre otros, los siguientes casos:

• No enviar el Informe Semanal vigente y actualizado los días viernes de cada semana, sin previa justificación.

• Inconsistencias entre la ejecución operativa real, los avances físicos reportados y la información presentada en el informe.

• No emitir el Informe 0 antes del inicio de las labores constructivas en sitio o modificarlo sin autorización formal del Gerente de Proyectos o sin orden de modificación aprobada.

• No comunicar al Departamento Financiero las actualizaciones del flujo de caja o la proyección de la semana siguiente.

• Incluir interpretaciones subjetivas, errores de cálculo o de redacción que dificulten el entendimiento del Informe Semanal.

Todo incumplimiento dará lugar, según su naturaleza, causa, alcance e impacto, a la adopción de una o más de las siguientes acciones:

• Notificación formal por correo.

• Corrección inmediata por parte del personal responsable.

• Implementación de acciones correctivas y/o preventivas.

• Revisión por la Gerencia de Proyectos.

• Escalamiento a la Gerencia General.

• Evaluación y eventual aplicación de medidas administrativas o disciplinarias en casos graves, reiterados o críticos.

<!-- Párrafo sin texto -->

### Tabla 04 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 |
| --- | --- | --- | --- |
| 1  |  | Elaboración del Informe 0 (Línea Base) |  |
|  | Responsable: Ingeniero de Proyecto |  |  |

[Celdas combinadas: fila 1, columnas 1–2; fila 2, columnas 2–4. Texto reproducido una sola vez.]

El Informe 0 es la línea base del proyecto y, por tanto, insumo fundamental de los informes semanales. Se deben cumplir los siguientes aspectos:

• El Informe 0 debe estar emitido y aprobado antes del inicio de las labores constructivas en sitio y enviarse por correo electrónico antes de dicho inicio (ver 1.4).

• Una vez emitido, solo podrá ser modificado por Gerencia de Proyectos en respuesta a órdenes de modificación aprobadas por el cliente o casos excepcionales debidamente justificados.

1.1 Información manual requerida para el Informe 0

En la hoja denominada “Informe 0” de la plantilla oficial, el Ingeniero de Proyecto debe consolidar la siguiente información manualmente:

En la sección superior (ver Anexo A):

• Título del proyecto.

• Fecha de inicio.

• Lista de la secuencia de actividades constructivas.

• Presupuesto por actividad constructiva.

• Cantidad de semanas del proyecto, dispuestas en horizontal.

• Representación, en cronograma, del avance porcentual esperado por actividad en las semanas correspondientes.

En la sección inferior (ver Anexo B):

• Proyecciones de materiales, mano de obra, subcontratos y costos indirectos.

1.2  Cálculos automáticos del Informe 0

Una vez ingresados la información del punto 1.1 la plantilla calcula automáticamente las siguientes filas, considerando las actividades y semanas del proyecto (ver Anexo B).

• Presupuesto al finalizar (BAC): Valor total del proyecto correspondiente a la suma de los presupuestos de todas las actividades del proyecto.

• Avance planificado por periodo: Porcentaje del BAC que se espera ejecutar físicamente durante un solo periodo.

• Avance planificado acumulado: Porcentaje acumulado del BAC planificado para haberse ejecutado físicamente a la fecha de corte.

• Valor planeado por periodo: Equivalente económico del avance planificado por periodo. Representa el costo presupuestado del trabajo programado para ejecutarse en ese periodo.

• Valor planeado acumulado (PV): Suma acumulada de los valores planeados a la fecha de corte. Representa el costo presupuestado del trabajo que debería haberse ejecutado a esa fecha. Referencia principal para informes semanales.

Nota: Avance (%) y Valores planeados (PV) representan la misma información, pero uno es expresado en términos porcentuales y el otro, en términos monetarios.

1.3 Validaciones críticas en el Informe 0

Antes de emitir el Informe 0, el Ingeniero de Proyecto debe verificar:

• Que la columna de verificación ubicada al final del cronograma no se muestre en color rojo, lo cual indicaría que la actividad no totaliza un 100% de avance y deberá de corregirse (ver Anexo C).

• Que la duración total del proyecto y el BAC visualizado en la plantilla oficial coincidan con la oferta constructiva, contrato firmado por el cliente y/o las órdenes de modificación aprobadas.

• Que las proyecciones de materiales, mano de obra, subcontratos y costos indirectos mantengan coherencia con la información presupuestaria del proyecto, utilizando los totales de la columna ubicada al final del cronograma (ver Anexo D).

1.4  Envío y manejo del Informe 0

Una vez finalizado y revisado, el Informe 0 deberá ser emitido y manejado conforme a los siguientes lineamientos:

• El Gerente de Proyectos es quien valida y aprueba la información plasmada en el Informe 0, autorizando su envío.

• El Ingeniero de Proyecto es el responsable de verificar que la información contenida en el informe sea consistente con el cronograma y presupuesto aprobado, los documentos contractuales, y los aspectos técnicos y financieros de la ejecución esperada en la obra.

• El Informe 0 debe enviarse, previo al inicio de las labores constructivas en sitio, formalmente por correo electrónico al Departamento Financiero y a la Gerencia General, conforme a CTO-SOP-01-V1-2026. Asimismo, una copia del Informe 0 debe quedar cargada en el módulo «Documentos» del proyecto en Mawi y resguardada en la carpeta digital correspondiente del servidor, conforme a GEN-SOP-05-V1-2026.

• La información del flujo de caja incluida en el Informe 0 será considerada la base oficial de proyección financiera del proyecto, contra la cual el Departamento Financiero comparará el Informe Semanal, según CTO-SOP-03-V1-2026.

• Cualquier ajuste posterior al Informe 0 debe contar con su debida justificación y ser comunicado a Gerencia General y Departamento Financiero. Esto aplica para órdenes de modificación, variaciones significativas o cualquier otro cambio que afecte la planificación financiera del proyecto, con el fin de mantener actualizado su flujo de caja.

<!-- Párrafo sin texto -->

### Tabla 05 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 |
| --- | --- | --- | --- |
| 2  |  | Actualización del Informe Semanal |  |
|  | Responsable: Ingeniero de Proyecto |  |  |

[Celdas combinadas: fila 1, columnas 1–2; fila 2, columnas 2–4. Texto reproducido una sola vez.]

<!-- Párrafo sin texto -->

En la plantilla oficial, la hoja denominada “Informe” corresponde al Informe Semanal que debe ser presentado semanalmente por el Ingeniero de Proyecto. Para su correcta elaboración, el Ingeniero debe aplicar los siguientes aspectos.

2.1   Manejo del cronograma

El Informe Semanal debe reflejar, en cada entrega, el avance físico a la fecha de corte (ver punto 2.2) pero también la proyección del avance esperado para cada periodo con base en el Informe 0. Por esta razón, el primer paso es:

• Copiar y pegar el cronograma del Informe 0 en la hoja del Informe Semanal.

• Utilizarlo como base para la verificación a la fecha de corte y la proyección del avance esperado para los próximos periodos, hasta la culminación del proyecto. 

2.2 Verificación del avance físico

1.1 

En la sección de cronograma del Informe Semanal se debe:

• Determinar el porcentaje de avance de valor ganado de las actividades en curso a la fecha de corte, tal y como se observa en la siguiente imagen. Es relevante que el Ingeniero de Proyecto respalde estos datos con bitácoras de inspección (fotografías).

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 3; archivo image3.png; véase caption o título contiguo]

Figura 2. Captura de la hoja “Informe” mostrando las columnas de actualización del porcentaje de avance por actividad

• Revisar la columna de verificación ubicada en el extremo derecho de la hoja, que suma los porcentajes por periodo de cada actividad, y los identifica, mediante colores, según su estado: pendiente, en proceso o finalizado. 

2.3 Registro de costo actual (AC)

• El AC del proyecto se extrae del módulo “Control Financiero” en Mawi y corresponde al monto facturado hasta la fecha de corte (ver Anexo E).

• Este dato contempla únicamente los gastos reales, por lo tanto, los gastos que aún no hayan sido asociados a una factura no se verán reflejados en el valor mostrado por el sistema, sino en “Monto comprometido”.

• Cuando exista incertidumbre sobre la confiabilidad del AC mostrado en sistema, se recomienda validar el dato en conjunto con Finanzas y/o Administración antes de su incorporación al informe.

2.4  Actualización del flujo de caja para Departamento Financiero

El Ingeniero de Proyecto debe actualizar la sección del flujo de caja, (ver Anexo F) con las proyecciones de materiales, mano de obra, subcontratos y costos indirectos, así como las proyecciones de los ingresos del cliente, y debe indicar, en la sección de “Anotaciones para Departamento Financiero” (ver Anexo H):

• Si las proyecciones de cada partida se mantienen, para la semana entrante, conforme al Informe 0.

• Si no es así, debe comentar los motivos de manera que el Departamento Financiero pueda comprender, validar y ajustar el flujo de caja.

Nota: El Departamento Financiero detecta desviaciones y compara contra las proyecciones financieras y el Informe 0.

2.5  Cálculos automáticos del Informe Semanal

El archivo ejecuta automáticamente los siguientes cálculos una vez que los insumos de los puntos 2.1 y 2.2 han sido ejecutados. Las fórmulas se muestran en el anexo G. 

Asimismo, el Ingeniero de Proyecto debe verificar la coherencia de los resultados.

• Valor ganado por periodo: Equivalente económico del avance físico real ejecutado durante un solo periodo. Representa el valor presupuestado del trabajo efectivamente ejecutado en ese periodo.

• Valor ganado acumulado (EV): Suma acumulada de los valores ganados a la fecha de corte. Representa el valor presupuestado del trabajo efectivamente ejecutado a esa fecha.

• Avance real por periodo: Porcentaje del BAC efectivamente ejecutado físicamente durante un solo periodo, con base en el progreso real de las actividades del proyecto.

• Avance real acumulado: Porcentaje acumulado del BAC efectivamente ejecutado físicamente a la fecha de corte. Representa el avance físico real total del proyecto a esa fecha.

2.6 Métricas del Earned Value Management (EVM)

• Diferencia de costo (CV = EV – AC): Indicador que mide la diferencia entre el valor ganado y el costo actual incurrido a la fecha de corte. Permite identificar si el proyecto se encuentra por encima o por debajo del costo presupuestado para el trabajo ejecutado.

• Diferencia de cronograma (SV = EV – PV): Indicador que mide la variación entre el valor ganado acumulado y el valor planeado acumulado, a la fecha de corte. Permite cuantificar el adelanto o atraso del proyecto respecto al cronograma planificado, en términos económicos.

• Índice de Desempeño del Costo (CPI = EV / AC): Indicador de eficiencia del costo que relaciona el valor ganado acumulado con el costo actual del proyecto a la fecha de corte. Permite evaluar qué tan eficientemente se están utilizando los recursos económicos del proyecto, determinando cuánto valor presupuestado se obtiene por cada unidad monetaria invertida. Un CPI mayor a 1 indica un desempeño favorable, mientras que un valor menor a 1 refleja que el costo actual supera el valor del avance real obtenido en sitio.

• Índice de Desempeño del Cronograma (SPI = EV / PV): Indicador de eficiencia del cronograma que relaciona el valor ganado acumulado con el valor planeado acumulado del Informe 0. Permite evaluar el nivel de cumplimiento del avance planificado inicialmente, cuantificando el grado de alentado o atraso respecto a la planificación inicial. Un SPI mayor a 1 indica un avance superior al programado, mientras que un valor menor a 1 refleja atrasos en la ejecución respecto al cronograma base del proyecto.

• Estimación al Finalizar (EAC = BAC / CPI): Proyección del costo total estimado del proyecto al momento de su finalización, calculada con base en el desempeño del costo de un periodo específico. Permite estimar el costo final esperado si se mantiene la tendencia de ejecución observada.

2.7 Estados del Proyecto según CPI y SPI

La plantilla oficial despliega automáticamente el estado general del proyecto a partir de la evaluación combinada de los indicadores SPI (cronograma) y CPI (costo), tal y como se ve en la siguiente imagen. Esto estados permiten identificar fácilmente el estado del proyecto y determinar la necesidad de análisis o acciones correctivas.<br>Un índice superior a uno (1) indica que el proyecto está favorablemente por encima de lo planificado, mientras que, si es menor, se encuentra por debajo. 

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 4; archivo image4.png; véase caption o título contiguo]

Figura 3. Rangos de CPI / SPI y su interpretación

Nota: El Gerente de Proyectos podrá establecer umbrales distintos de acuerdo al nivel de control requerido para el proyecto.

Un índice mayor a 1.25 representa una alerta por holgura, debido a que corresponde a valores atípicos dentro del comportamiento esperado del cronograma o del costo. Estos alertan de posibles inconsistencias en la información del sistema, registros incorrectos, error humano, riesgos en sitio u otras discrepancias que deben ser revisadas y corregidas.

2.8 Interpretación técnica de los indicadores

Los indicadores obtenidos en el Informe Semanal constituyen la base para el análisis técnico del desempeño del proyecto y deben utilizarse como una herramienta de evaluación, seguimiento y toma de decisiones.

Cuando un indicador se encuentre en estado amarillo o rojo, el Ingeniero de Proyecto debe incluir, en la sección final del Informe Semanal (ver Anexo H) un análisis técnico que permita interpretar las desviaciones identificadas y las condiciones que la explican y engloban.

Este análisis debe ser claro, integral, conciso, y objetivo, relacionando los resultados de los indicadores con el contexto real, técnico, operativo, financiero y/o contractual de del proyecto, evitando interpretaciones genéricas, aisladas o sesgadas.

Como mínimo, este análisis debe considerar los siguientes aspectos:

• Desviación detectada: Identificación de la desviación existente y de la partida o dimensión afectada, ya sea tiempo, costo, alcance, mano de obra, materiales, subcontratos u otros componentes relevantes del proyecto.

• Punto específico de afectación: Identificación de las actividades, frentes de trabajo, sectores o procesos donde se evidencia el impacto de la desviación.

• Causa raíz del problema: Determinación de las condiciones, situaciones o decisiones que causaron la desviación identificada.

• Impacto esperado sobre el proyecto: Evaluación de las consecuencias esperadas sobre el cronograma, costos, productividad, flujo de caja, hitos de entrega o cualquier otro elemento relevante para el desempeño del proyecto.

• Medidas preventivas o correctivas propuestas: Definición de las acciones requeridas para mitigar las causas identificadas, reducir el impacto generado/esperado y restablecer el desempeño esperado del proyecto.

Algunos ejemplos de puntos relevantes de análisis que pueden considerarse cuando resulten aplicables son los siguientes:

• Relación entre costos incurridos y avance físico ejecutado.

• Compras anticipadas o variaciones de precios.

• Decremento en el rendimiento o cantidad de personal.

• Órdenes de modificación, ampliaciones o cambios de alcance que afecten la línea base.

• Actividades críticas.

• Etapa actual y condiciones particulares del proyecto.

• Análisis de tendencias respecto a periodos anteriores.

• Consideración de costos proyectados por partida contra saldo disponible.

• Restricciones técnicas, operativas, contractuales o externas.

Para una mayor claridad sobre el análisis requerido, consultar la figura 4, la cual ilustra un ejemplo práctico basado en un caso real.

2.9 Plan de Acción

Tal y como se observa en la Figura 3, cuando un indicador se encuentra en estado amarillo o rojo (o cuando el Gerente de Proyectos lo considere necesario), el Ingeniero de Proyecto deberá elaborar un plan de acción preventivo o correctivo orientado a restablecer el control del proyecto.

Todo plan de acción debe:

• Atender las causas raíz de la desviación.

• Mitigar el impacto del problema.

• Establecer medidas específicas, responsables, acciones y plazos de ejecución que solucionen los inconvenientes.

• Definir criterios de seguimiento, control y verificación.

El plazo para la elaboración e implementación del plan será definido por el Gerente de Proyectos según la criticidad del caso.

La fase preventiva o correctiva se considera finalizada cuando:

• Los indicadores retornen a los rangos aceptables establecidos, o;

• El gerente de Proyectos autorice formalmente el levantamiento del plan de acción.

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 5; archivo image5.png; véase caption o título contiguo]

Figura 4. Caso real de análisis técnico de Informe Semanal

### Tabla 06 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 |
| --- | --- | --- | --- |
| 3  |  | Presentación y envío del Informe Semanal |  |
|  | Responsable: Ingeniero de Proyecto<br>Participa: Departamento de Construcción |  |  |

[Celdas combinadas: fila 1, columnas 1–2; fila 2, columnas 2–4. Texto reproducido una sola vez.]

Como paso final, el Informe Semanal debe ser:

• Presentado, comentado y revisado por el equipo en la reunión semanal del Departamento de Construcción.

• Corregido (si es necesario) atendiendo a las observaciones del equipo y el Gerente de Proyectos.

• Autorizado por el Gerente de Proyectos para su envío formal, los días viernes, a Gerencia General y al Departamento Financiero.

3.1 Presentación en reunión de proyectos

En la reunión semanal de proyectos se debe efectuar la presentación, análisis y revisión del Informe Semanal a nivel departamental, con el objetivo de evaluar el desempeño del proyecto, identificar restricciones y coordinar las acciones necesarias para asegurar el cumplimiento de la planificación.

La exposición del Ingeniero de Proyecto debe ser integral, objetiva y apoyada en información verificable.

Como mínimo, durante la reunión deberán abordarse los siguientes aspectos:

• Estado general del proyecto y desempeño de los indicadores. 

• Desviaciones relevantes en costo, cronograma o productividad. 

• Restricciones, interferencias o condiciones que afecten continuidad del flujo de trabajo. 

• Actividades críticas y pendientes. 

• Riesgos operativos, financieros o contractuales identificados. 

• Necesidades de coordinación entre áreas involucradas. 

• Acciones preventivas o correctivas requeridas. 

• Definición de responsables, compromisos y fechas de seguimiento. 

• Situaciones que requieran retroalimentación, apoyo o escalamiento. 

Las acciones y compromisos definidos durante la reunión deben quedar claramente identificados para su respectivo seguimiento.

3.2 Envío formal del Informe Semanal

Tras la reunión y la validación por parte del Gerente de Proyectos, el Ingeniero de Proyecto debe realizar el envío formal del informe por correo electrónico a Gerencia General y al Departamento Financiero, anexando todas las observaciones pertinentes en conformidad al presente procedimiento. 

<!-- Párrafo sin texto -->

### Tabla 07 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 |
| --- | --- | --- | --- |
| 4 |  | Control del proceso |  |
|  | Responsable: Gerente de Proyectos, Analista de Procesos |  |  |

[Celdas combinadas: fila 1, columnas 1–2; fila 2, columnas 2–4. Texto reproducido una sola vez.]

4.1 Auditorías de control

El correcto cumplimiento de este procedimiento debe verificarse de manera periódica, con el fin de medir los indicadores de calidad de la gestión de informes y asegurar la coherencia entre los sistemas oficiales del proyecto. La frecuencia mínima de revisión y control del proceso será mensual.

### Tabla 08 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 |
| --- | --- | --- | --- |
| Punto de control | Qué verificar | Evidencia esperada | Posible desviación |
| Informe 0 emitido | Existe Informe 0 emitido antes del inicio de las labores constructivas en sitio y aprobado por Gerente de Proyectos. | Correo de envío del Informe 0 con plantilla machote adjunta. Informe 0 cargado en Mawi / servidor según GEN-SOP-05-V1-2026. | Inicio de las labores constructivas en sitio sin Informe 0 emitido. |
| Frecuencia semanal | Informe semanal emitido y presentado en reunión de proyectos. | Acta o registro de reunión semanal y correo de envío. | Periodos sin informe emitido o sin presentación. |
| Avance físico | Porcentajes de avance respaldados por bitácoras de inspección. | Bitácoras de inspección. | Avances no respaldados o discrepancias con campo. |
| Costo real (AC) | AC extraído de Mawi a la fecha de corte. | Captura/registro de Mawi referenciado en el informe. | AC con datos no validados. |
| Análisis técnico | Análisis presente y consistente cuando SPI o CPI están en amarillo o rojo. | Sección de análisis del informe con causas, impacto y plan de acción. | Análisis omitido o genérico ante estados amarillo/rojo. |
| Coordinación con Finanzas | Actualización del flujo de caja comunicada formalmente a Finanzas conforme a CTO-SOP-03-V1-2026. | Sección de anotaciones, flujo de caja e ingresos completadas adecuadamente | Variaciones no comunicadas o flujo desactualizado. |
| Coherencia entre sistemas | Avance físico, AC en Mawi, flujo de caja y datos del informe son consistentes. | Conciliación documentada entre sistemas. | Datos divergentes entre Mawi, plantilla y flujo de caja. |

Tabla 3. Controles del proceso

4.2 Indicadores de desempeño del proceso

Los siguientes indicadores permiten evaluar objetivamente el desempeño del proceso de gestión de informes. Están diseñados para calcularse a partir de los registros de envío del informe semanal, las actas de reunión de proyectos y las auditorías de control:

### Tabla 09 — orden OOXML

| Columna 1 | Columna 2 | Columna 3 | Columna 4 |
| --- | --- | --- | --- |
| Indicador | Qué mide | Utilización | Cálculo |
| Cumplimiento de emisión del informe semanal | Proporción de semanas activas con informe emitido y presentado dentro del plazo. | Evaluar la disciplina de reporte del proyecto. | <!-- Párrafo sin texto --><br>(Semanas con informe) / (Total de semanas activas) x100 |
| Desviación de costo y plazo | Desviación promedio CPI y SPI de los proyectos activos en el periodo. | Evaluar la salud agregada del portafolio. | Promedio de CPI y SPI de los proyectos activos. |

Tabla 4. Indicadores de desempeño

<!-- Párrafo sin texto -->

<!-- Párrafo sin texto -->

### Tabla 10 — orden OOXML

| Columna 1 | Columna 2 |
| --- | --- |
| 5 | Anexos |

<!-- Párrafo sin texto -->

A. Actividades y cronograma — Informe 0

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 6; archivo image6.emf; véase caption o título contiguo]

[Captura del cronograma del Informe 0 — Planificación inicial del Ingeniero de Proyecto]

B. Sección inferior — Informe 0

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 7; archivo image7.emf; véase caption o título contiguo]

[Captura de la columna de verificación de la plantilla, donde la celda se marca en rojo cuando la suma de los avances no corresponde a 100%.]

C. Verificación de porcentajes de actividades

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 8; archivo image8.png; véase caption o título contiguo]

[Captura de la columna de verificación de la plantilla, donde la celda se marca en rojo cuando la suma de los avances no corresponde a 100%.]

D. Verificación de totales — Informe 0 

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 9; archivo image9.png; véase caption o título contiguo]

[Captura del módulo de Presupuesto en Mawi, con la etiqueta de Costo Real (AC) facturado a la fecha de corte — “Total de Gastos”.]

E. Costo actual (AC) en Mawi

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 10; archivo image10.png; véase caption o título contiguo]

[Captura del módulo de Presupuesto en Mawi, con la etiqueta de Costo Real (AC) facturado a la fecha de corte — “Total de Gastos”.]

F. Flujo de cajaFlujo de cajaProyección de Flujo de Caja, Cálculos Automáticos y Métricas — Informe Semanal

Cálculos y métricasCálculos y métricas

[IMAGEN CONSERVADA – cuerpo, aparición 11; archivo image11.emf; véase caption o título contiguo]

[Captura de la sección de proyección de flujo de caja (materiales, mano de obra, subcontratos, costos indirectos, pagos del cliente) — insumo enviado a Finanzas. Y de campos cálculos y métricas del Informe — Automáticos y manuales.]

G. Fórmulas de los cálculos automáticos para el Informe Semanal

<!-- Párrafo sin texto -->

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 12; archivo image12.png; véase caption o título contiguo]

H. Campos del Informe Semanal

<!-- Párrafo sin texto -->

[IMAGEN CONSERVADA – cuerpo, aparición 13; archivo image13.png; véase caption o título contiguo]

[Captura de la sección final del Informe Semanal – Campos para análisis técnico del Ingeniero de Proyecto.]

<!-- Párrafo sin texto -->

Habiendo leído lo anterior, las partes firman en señal de conformidad. 

<!-- Párrafo sin texto -->

### Tabla 11 — orden OOXML

| Columna 1 | Columna 2 |
| --- | --- |
| <!-- Párrafo sin texto --><br>• &#9;Gerardo Acuña Cárdenas | &#9;<br>• &#9;Daniela Bolaños Quirós&#9; |
| &#9;<br>&#9;<br>&#9;<br>• &#9;Gerardo Acuña Cook | &#9;<br>&#9;<br>&#9;<br>• &#9;Jazmín Madrigal Vásquez |
| &#9;<br>&#9;<br>&#9;<br>• &#9;Ana Emilia Mora Chaves | &#9;<br>&#9;<br>&#9;<br>• &#9;Deiver Rodríguez Vega |

<!-- Párrafo sin texto -->

— Fin del documento —

## word/header1.xml — contenido documental y campos almacenados

### Tabla 12 — orden OOXML

| Columna 1 | Columna 2 |
| --- | --- |
| Procedimiento de Presentación de Informes de Proyecto | CTO-SOP-02-V1-2026 |

## word/footer1.xml — contenido documental y campos almacenados

&#9;Dpto. Construcción / Gestión de Proyectos — Uso interno&#9;Pág. 1

[Los campos del pie reproducen los valores almacenados en el DOCX. El número de páginas renderizadas se consigna en el control de integración. Se conservan el encabezado y el pie fuente. No hay comentarios Word.]
