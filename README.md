# nodo_CTCI
Nodo de investigadores para la adopción de la Ciencia Abierta


## Fuentes de datos

### 1. DataInnovación 
[Portafolio_Innovación](/data/portafolio_innova.xlsx): Datos obtenidos desde el portal de datos de InnovaChile CORFO. Los datos se actualizan periodicamente y el trabajo realizado está en base a los últimos datos obtenibles al dia 04/10/2021.
### 2. DataEmprendimiento
[Portafolio_Emprendimiento](/data/portafolio_empren.xlsx): Datos extraidos manualmente de la plataforma DataEmprendimiento de CORFO, filtrado para obtener datos de emprendimientos con foco en desarrollo de I+D. Los datos provienen de tres fuentes principales: las postulaciones de los proyectos, las encuestas de seguimiento anual y datos públicos de otras instituciones del Estado. 
### 3. INAPI
Mediante el módulo de datos Abiertos del Instituto Nacional de Propiedad Industrial de Chile es posible acceder a datos de marcas y patentes. Se extraen datos de solicitud y registros de patentes para contraste y obtención de indicadores para el trabajo de mesas.
- [Patentes_Solicitadas](/data/INAPI/Applications): Solicitudes presentadas desde el año 2009 hasta la actualidad, contiene patentes, modelos de utilidad y diseños industriales presentados en Chile en este periodo.
- [Patentes_Registradas](/data/INAPI/Registers): Patentes registradas desde el año 2009 hasta la actualidad, contiene registros de patentes, modelos de utilidad y diseños industriales registrados en chile durante este periodo.
### 4. INE
El Instituto Nacional de Estadística mediante su plataforma web REDATAM, nos presenta los resultados obtenidos de los ultimos censos de población y vivienda, pudiendo caracterizar los datos a extraer en frecuencias, listados y cruces, además de obtener estadisticas básicas e indicadores de población.
- [Doctorados](/data/Doctorados.xlsx): Datos obtenidos por cruce de las variables de personas residencia habitual vs nivel del curso más alto aprobado (filtro = Doctorado).
- [Promedio_Escolaridad_por_Edades](/data/promedio_escolaridad_por_edades(divison_provincial).xlsx): Datos obtenidos por cruce de variables de personas Edades quinquenales vs promedio de años de escolaridad, con segmentación de área (rural/urbano) y por provincias de las regiones de la macrozona centro-sur.
### 5. ANID
La Agencia Nacional de Investigación y Desarrollo pone a disposición de las y los usuarios vínculos a información clave para la toma de decisiones, como bases de datos colaborativas y estadísticas. El [repositorio de la ANID](https://github.com/ANID-GITHUB?tab=repositories) presenta distintas bases de datos de actualizaciones anuales, una vez cerrado el año administrativo.
- [BDH_Proyectos](/data/ANID/BDH_Proyectos.csv): contiene la información disponible de proyectos adjudicados por la Agencia (antes del 2020, CONICYT) desde el año 1982 hasta el 2020, con fecha de corte al 31 de diciembre del 2020. Cada fila representa una iniciativa adjudicada, y cada columna un campo que lo caracteriza.
- [Postulaciones](/data/ANID/POSTULACIONES_2016_2020.csv): Esta base de datos de postulaciones es una consolidación de resultados de concursos, cuyas postulaciones ingresan o no a través del Sistema de Postulación en Línea (SPL) de la Agencia. En aquellos casos en que las postulaciones no ingresan por SPL, se levanta el registro administrativo al menos para las postulaciones adjudicadas, por lo cual en algunas convocatorias sólo se encuentra el detalle de postulaciones adjudicadas y no el de todas las postulaciones recibidas.

