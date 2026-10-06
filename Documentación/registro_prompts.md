# Registro del uso de herramientas de inteligencia artificial

## Información general

- **Proyecto:** Diseño normativo de una instalación solar fotovoltaica para un módulo industrial del edificio B100 de InnovaPark.
- **Curso:** EL-4601 Normalización Técnica para Electrónica.
- **Institución:** Tecnológico de Costa Rica.
- **Herramienta utilizada:** ChatGPT, desarrollada por OpenAI.
- **Periodo de utilización:** Septiembre y octubre de 2026.

## Declaración de uso

Durante el desarrollo del proyecto se utilizó una herramienta de inteligencia
artificial generativa como apoyo para organizar información, estructurar el
informe, redactar borradores, revisar cálculos, localizar fuentes preliminares,
preparar diagramas y resolver errores de compilación en LaTeX.

Las respuestas de la herramienta no fueron consideradas fuentes normativas ni
sustituyeron las fichas técnicas de los fabricantes. Los datos utilizados en el
diseño fueron revisados por los integrantes del grupo y contrastados con normas,
documentos institucionales, fichas técnicas y fuentes climáticas.

Las formulaciones presentadas a continuación reúnen los principales prompts
utilizados. Algunas consultas similares fueron consolidadas para evitar
repeticiones innecesarias.

---

## P-01. Selección del emplazamiento

**Prompt representativo:**

> Busca un emplazamiento comercial o industrial real en Costa Rica que pueda
> documentarse utilizando información pública disponible en Internet y que sea
> apropiado para desarrollar el anteproyecto de una instalación fotovoltaica.

**Propósito:**  
Seleccionar un edificio que permitiera desarrollar el proyecto sin necesidad
de realizar una visita técnica.

**Resultado utilizado:**  
Se seleccionó un módulo industrial del edificio B100 de InnovaPark, ubicado en
El Coyol de Alajuela.

**Verificación:**  
La ubicación, fotografías, dimensiones y características generales se
contrastaron con la información pública de InnovaPark.

---

## P-02. Organización del informe

**Prompt representativo:**

> Propón una estructura completa para el informe del proyecto fotovoltaico en
> formato IEEE y genera los apartados necesarios en LaTeX.

**Propósito:**  
Organizar el documento y definir el orden de sus secciones.

**Resultado utilizado:**  
Se establecieron las secciones de descripción del emplazamiento, marco
normativo, selección de equipos, criterios de diseño, dimensionamiento,
diseño eléctrico, protecciones, monitoreo, planos, estimación energética,
presupuesto, verificación normativa, conclusiones y apéndices.

**Modificaciones realizadas:**  
El grupo agregó y reorganizó apartados de acuerdo con el instructivo del curso
y con la información disponible del edificio.

---

## P-03. Investigación normativa

**Prompt representativo:**

> Identifica las leyes, reglamentos, normas técnicas y requisitos de la empresa
> distribuidora aplicables a una instalación fotovoltaica conectada a la red en
> Costa Rica.

**Propósito:**  
Preparar el marco normativo del proyecto.

**Resultado utilizado:**  
Se identificaron la Ley N.° 10086, el Decreto Ejecutivo N.° 43879-MINAE, la
regulación de ARESEP, el Código Eléctrico de Costa Rica, los procedimientos del
ICE y normas técnicas internacionales aplicables.

**Verificación:**  
Las referencias se contrastaron con publicaciones del ICE, ARESEP, CFIA,
PGR, IEC, IEEE y NFPA.

---

## P-04. Selección de equipos

**Prompt representativo:**

> Investiga equipos comercialmente disponibles y propone una familia compatible
> de módulos, inversor, desconexión rápida, sistema de montaje, conductores,
> conectores, protecciones y monitoreo para el sistema fotovoltaico.

**Propósito:**  
Seleccionar los componentes principales del sistema.

**Resultado utilizado:**  
Se seleccionaron, entre otros componentes:

- Módulos Trina Solar TSM-475NEG9R.28.
- Inversor CPS SCA60KTL-DO/US-480.
- Dispositivos APsmart RSD-D-15.
- Sistema de montaje S-5! PVKIT 2.0.
- Conductores Southwire.
- Conectores Stäubli MC4-Evo 2.
- Protecciones Schneider Electric y Eaton.
- Sistema de monitoreo CPS FlexOM.

**Verificación:**  
Las características fueron comprobadas mediante fichas técnicas oficiales de
los fabricantes.

---

## P-05. Dimensionamiento del campo fotovoltaico

**Prompt representativo:**

> Dimensiona el campo fotovoltaico utilizando módulos de 475 W y un inversor
> trifásico de 60 kW. Verifica la cantidad de módulos, configuración de strings,
> distribución entre MPPT, tensión por temperatura, corriente y relación DC/AC.

**Propósito:**  
Determinar la configuración eléctrica del campo fotovoltaico.

**Resultado utilizado:**  

- 144 módulos de 475 Wp.
- Potencia instalada de 68,4 kWp.
- Nueve strings de 16 módulos.
- Distribución de tres strings por cada MPPT.
- Relación DC/AC aproximada de 1,14.

**Verificación:**  
Los resultados fueron comparados con los límites eléctricos indicados en las
fichas técnicas del módulo y del inversor.

---

## P-06. Diseño eléctrico en corriente continua y alterna

**Prompt representativo:**

> Desarrolla los cálculos preliminares de corriente, ampacidad, conductores,
> caída de tensión, canalizaciones, protecciones y desconexión para los lados
> de corriente continua y corriente alterna del sistema.

**Propósito:**  
Establecer los criterios eléctricos principales del anteproyecto.

**Resultado utilizado:**  
Se definieron conductores fotovoltaicos de cobre, conductores XHHW-2,
protecciones contra sobrecorriente, medios de desconexión y recorridos
preliminares de canalización.

**Limitación:**  
Las longitudes y recorridos se consideran preliminares porque no se dispone de
un levantamiento eléctrico completo del edificio.

---

## P-07. Protecciones, puesta a tierra y seguridad

**Prompt representativo:**

> Define los criterios de puesta a tierra, equipotencialización, protección
> contra sobretensiones, desconexión rápida, fallas de arco, rotulación y acceso
> para mantenimiento del sistema fotovoltaico.

**Propósito:**  
Desarrollar la sección de seguridad eléctrica.

**Resultado utilizado:**  
Se establecieron criterios para el conductor de puesta a tierra, unión de
estructuras metálicas, dispositivos de protección contra sobretensiones,
desconexión rápida y señalización de seguridad.

**Verificación:**  
Las decisiones se contrastaron con el Código Eléctrico de Costa Rica, NEC 2020,
manuales de fabricantes y normas complementarias.

---

## P-08. Recurso solar y producción energética

**Prompt representativo:**

> Estima el recurso solar y la generación mensual y anual de un sistema de
> 68,4 kWp ubicado en El Coyol de Alajuela. Documenta los supuestos y las
> pérdidas consideradas.

**Propósito:**  
Estimar la producción energética del sistema.

**Resultado utilizado:**  
Se preparó una estimación preliminar considerando irradiación, temperatura,
suciedad, orientación, sombreado, cableado, conversión y disponibilidad.

**Verificación:**  
Se emplearon como referencia NASA POWER, PVGIS y PVWatts.

---

## P-09. Planos y diagramas

**Prompt representativo:**

> Propón los planos y diagramas necesarios para representar la distribución de
> módulos, equipos, rutas de conductores, puesta a tierra, diagrama unifilar y
> sistema de monitoreo utilizando Draw.io.

**Propósito:**  
Preparar la documentación gráfica del sistema.

**Resultado utilizado:**  
Se elaboraron los siguientes planos:

- PV-01: Emplazamiento.
- PV-02: Cubierta y módulos.
- PV-03: Equipos y rutas.
- PV-04: Diagrama unifilar.
- PV-05: Monitoreo y comunicación.

**Modificaciones realizadas:**  
La distribución fue ajustada manualmente por el grupo según las imágenes y
dimensiones disponibles del edificio.

---

## P-10. Lista de materiales y presupuesto

**Prompt representativo:**

> Prepara una lista preliminar de materiales y un presupuesto académico para
> el sistema fotovoltaico seleccionado, indicando cantidades y limitaciones de
> los precios disponibles.

**Propósito:**  
Estimar los componentes y costos principales del proyecto.

**Resultado utilizado:**  
Se elaboró una lista de módulos, inversor, dispositivos de desconexión rápida,
montaje, conductores, conectores, protecciones, monitoreo y materiales de
instalación.

**Limitación:**  
Los precios son referencias preliminares y no constituyen una cotización
comercial.

---

## P-11. Revisión de LaTeX

**Prompt representativo:**

> Revisa los errores y advertencias de compilación de Overleaf y propone
> correcciones que no modifiquen el contenido técnico del documento.

**Propósito:**  
Corregir tablas, referencias, caracteres especiales, archivos bibliográficos,
imágenes y problemas de tiempo de compilación.

**Resultado utilizado:**  
Se corrigieron errores en tablas `tabularx`, referencias BibTeX, caracteres
especiales y configuración temporal de compilación en modo borrador.

---

## P-12. Revisión final y organización del repositorio

**Prompt representativo:**

> Revisa qué documentos deben almacenarse en el repositorio de GitHub y propone
> una estructura para el informe, planos editables, exportaciones, datasheets,
> normativa y registro del uso de inteligencia artificial.

**Propósito:**  
Organizar la documentación complementaria del proyecto.

**Resultado utilizado:**  
Se crearon carpetas para el informe, planos, fichas técnicas, normativa,
documentación del proyecto y registro del uso de inteligencia artificial.

---

## Responsabilidad académica

La herramienta de inteligencia artificial se utilizó únicamente como apoyo.
Los integrantes del grupo revisaron, modificaron y aprobaron el contenido
incluido en el informe. La responsabilidad sobre los cálculos, decisiones de
diseño, referencias y conclusiones corresponde exclusivamente al grupo.
