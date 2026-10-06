# EL4601 — Proyecto 2: Sistema Fotovoltaico B100

Diseño normativo de una instalación solar fotovoltaica conectada a la red para
un módulo industrial del edificio B100 de InnovaPark, ubicado en El Coyol,
Alajuela, Costa Rica.

## Información académica

- **Institución:** Tecnológico de Costa Rica
- **Escuela:** Escuela de Ingeniería Electrónica
- **Curso:** EL-4601 Normalización Técnica para Electrónica
- **Centro académico:** Centro Académico de Alajuela
- **Tipo de proyecto:** Anteproyecto académico

## Integrantes

- María José Arias Jiménez — 2022234290
- Allan Arrieta Quirós — 2022085267
- Esteban Vargas Fernández — 2023395790

## Descripción

El proyecto presenta el diseño preliminar de una instalación solar fotovoltaica
destinada al autoconsumo de energía eléctrica en una cubierta industrial.

La propuesta contempla la distribución de módulos, configuración de cadenas,
selección del inversor, conductores, canalizaciones, protecciones, medios de
desconexión, puesta a tierra, monitoreo, señalización e interconexión con la
infraestructura eléctrica del edificio.

El diseño se desarrolló utilizando información pública del emplazamiento.
Cuando no existían datos del consumo eléctrico, capacidad estructural, corriente
de cortocircuito o configuración del tablero principal, se utilizaron supuestos
técnicos identificados expresamente en el informe.

## Configuración principal

| Parámetro | Selección |
|---|---|
| Potencia fotovoltaica instalada | 68,4 kWp |
| Cantidad de módulos | 144 |
| Módulo fotovoltaico | Trina Solar TSM-475NEG9R.28, 475 Wp |
| Configuración de cadenas | 9 strings de 16 módulos |
| Inversor | CPS SCA60KTL-DO/US-480 |
| Potencia nominal del inversor | 60 kW |
| Tensión de salida | 480 V, trifásica |
| Relación DC/AC | 1,14 |
| Desconexión rápida | 72 dispositivos APsmart RSD-D-15 |
| Sistema de montaje | S-5! PVKIT 2.0 |
| Modalidad | Autoconsumo conectado a la red |

## Contenido del repositorio

### Informe

La carpeta [`Informe`](Informe) contiene el documento técnico principal del
proyecto.

- [Informe del proyecto](Informe/Proyecto_Norma__2.pdf)

### Planos

La carpeta [`Planos`](Planos) contiene las exportaciones de los cinco planos y
el archivo editable de Draw.io.

- PV-01 — Emplazamiento.
- PV-02 — Cubierta y distribución de módulos.
- PV-03 — Ubicación de equipos y rutas eléctricas.
- PV-04 — Diagrama unifilar.
- PV-05 — Monitoreo y comunicación.
- `Planos_Fotovoltaicos_B100.drawio` — Archivo editable.

### Fichas técnicas

La carpeta [`Datasheets`](Datasheets) contiene las fichas técnicas de los
principales equipos y materiales seleccionados:

- Módulo Trina Solar TSM-475NEG9R.28.
- Inversor CPS SCA60KTL-DO/US-480.
- Dispositivo APsmart RSD-D-15.
- Sistema CPS FlexOM.
- Sistema de montaje S-5! PVKIT 2.0.
- Cable fotovoltaico Southwire.
- Conductores Southwire XHHW-2.
- Conectores Stäubli MC4-Evo 2.
- Interruptor Schneider Electric HJL36100U44X.
- Desconectador Eaton DH363URK.
- Protector contra sobretensiones Eaton SP1-480Y.

### Normativa

La carpeta [`Documentación`](Documentaci%C3%B3n) contiene un índice de las leyes,
reglamentos, normas técnicas y procedimientos institucionales considerados en
el proyecto.

No se almacenan copias no autorizadas de normas protegidas por derechos de
autor.

### Documentación

La carpeta [`Documentación`](Documentaci%C3%B3n) contiene el instructivo y
otros documentos públicos relacionados con el proyecto.

### Uso de inteligencia artificial

El archivo
[`Documentacion/registro_prompts.md`](Documentacion/registro_prompts.md)
documenta el uso de herramientas de inteligencia artificial durante el
desarrollo del proyecto.

La inteligencia artificial fue utilizada como apoyo para estructuración,
redacción preliminar, revisión de cálculos, búsqueda inicial de fuentes y
resolución de errores de LaTeX. Toda información técnica fue revisada por los
integrantes y contrastada con fuentes externas.

## Fuentes y criterios de verificación

El diseño se fundamentó en:

- Legislación costarricense sobre recursos energéticos distribuidos.
- Código Eléctrico de Costa Rica y NEC 2020.
- Procedimientos de interconexión del ICE.
- Regulación de ARESEP.
- Normas IEC, IEEE, NFPA y certificaciones UL.
- Fichas técnicas oficiales de los fabricantes.
- Información climática de NASA POWER, PVGIS y PVWatts.

## Limitaciones

Este trabajo corresponde a un anteproyecto académico y no constituye un diseño
constructivo.

Antes de una implementación real deberán verificarse, entre otros aspectos:

- Demanda y facturación eléctrica del inmueble.
- Configuración y capacidad del tablero principal.
- Corriente de cortocircuito disponible.
- Capacidad de alojamiento de la red.
- Estado y capacidad estructural de la cubierta.
- Distancias y recorridos eléctricos reales.
- Compatibilidad del perfil de cubierta con el sistema de montaje.
- Permisos y requisitos vigentes de la empresa distribuidora.
- Revisión y firma de profesionales autorizados.

## Aviso

Los documentos de este repositorio se publican exclusivamente con fines
académicos. No deben utilizarse directamente para construir, instalar,
energizar o modificar una instalación eléctrica real.
