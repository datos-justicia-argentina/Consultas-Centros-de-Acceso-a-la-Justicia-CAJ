Consultas efectuadas en los Centros de Acceso a la Justicia -CAJ-
=================================================================

Este conjunto de datos contiene información relacionada a las consultas efectuadas en los Centros de Acceso a la Justicia –CAJ- que cuentan con sistema de gestión informático.

http://datos.jus.gob.ar/dataset/consultas-efectuadas-en-los-centros-de-acceso-a-la-justicia

Características
---------------

-   **Fecha de Primera Publicación:** 28/06/2017

-   **Tags o Etiquetas:** CAJ, acceso a justicia, acceso a la justicia, asesoramiento jurídico, casas de justicia, justicia, vulnerables, consultas

-   **Organización:** Ministerio de Justicia. Subsecretaría de Acceso a la Justicia. Dirección Nacional de Promoción y Fortalecimiento para el Acceso a la Justicia

-   **Autor:** Ministerio de Justicia. Subsecretaría de Acceso a la Justicia. Dirección Nacional de Promoción y Fortalecimiento para el Acceso a la Justicia

-   **Responsable:** Ministerio de Justicia. Subsecretaría de Acceso a la Justicia. Dirección Nacional de Promoción y Fortalecimiento para el Acceso a la Justicia

-   **Grupo:** Acceso a Justicia

-   **Frecuencia de Actualización:** Cada medio año

Recursos disponibles
--------------------

### Consultas efectuadas en los Centros de Acceso a la Justicia -CAJ- AAAA semestre 9

-   **Nombre del archivo:** consultas-centros-acceso-justicia-AAAA-semetre-9.csv

-   **Descripción del contenido:** detalle de las consultas realizadas en los Centros de Acceso a la Justicia que cuentan con sistema de gestión informático correspondientes al semestre 9 del año AAAA. Semestre 9: Toma valores 1 y 2 (1 para referenciar el primer semestre del año y 2 para el segundo semestre del año).

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** consultas efectuadas en los CAJ desde julio de 2016 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **consulta_id (int):** identificador único de la consulta

-   **consulta_fecha_carga (date):** fecha y hora de la carga de la consulta en el sistema informático

-   **dependencia_id (int):** identificador único de la dependencia

-   **dependencia_descripcion (string):** nombre del CAJ donde se realizó la consulta

-   **resolucion_tipo (string):** forma de resolución de la consulta. Toma los valores "INTERNA" y "EXTERNA"

-   **tema (string):** descricpión del tema de la consulta

-   **subtemas (string):** descricpión del o los subtemas de la consulta

-   **consulta_tipo (string):** tipo de consulta. Se relaciona con el área del CAJ que la canalizó

-   **consulta_estado (string):** estado de la consulta. Toma los valores "Finalizada", "Derivada a otro CAJ", "En Trámite"

-   **consultante_id (int):** identificador único del consultante

-   **consultante_actividad_principal (string):** actividad principal del consultante

-   **consultante_como_llego (string):** forma en la que el consultante se enteró de la existencia o los servicios que prestaba el CAJ

-   **consultante_fecha_nacimiento (date):** fecha de nacimiento del consultante

-   **consultante_genero (string):** género del consultante

-   **consultante_nivel_instruccion (string):** máximo nivel de instrucción alcanzado por el consultante

-   **consultante_atencion_salud (string):** tipo de cobertura de salud del consultante

-   **consultante_pais (string):** país de nacimiento del consultante

-   **consultante_provincia (string):** provincia de residencia del consultante

-   **intervencion_id (int):** identificador único de la intervención

-   **intervencion_tipo (string):** descripción del de intervención realizada

-   **intervencion_estado (string):** estado de la intervención

-   **intervencion_fecha_carga (date):** fecha y hora de la carga de la intervención

-   **gestion_id (int):** identificador único de la gestión

-   **gestion_fecha_carga (date):** fecha y hora de de la carga de la gestion

-   **gestion_tipo (string):** tipo de gestión

-   **consultante_pais_indec_id (string):** código de país donde está situado el CAJ, según la codificación de provincia implementada por INDEC (hasta 05/2019 nombre campo consultante_pais_id)

-   **consultante_provincia_id (string):** código de provincia donde está situado el CAJ, según la codificación de provincia implementada por INDEC (hasta 05/2019 nombre campo consultante_provincia_indec_id)

### Consultas efectuadas en los Centros de Acceso a la Justicia -CAJ- AAAA

-   **Nombre:** consultas-centros-acceso-justicia-AAAA.zip

-   **Descripción del contenido:** archivo comprimido correspondiente al año AAAA con los archivos publicados en el portal datos.jus.gob.ar durante dicho año

-   **Formato:** ZIP

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

La base de datos contiene información de las consultas en los CAJ que tienen cuentan con sistema de gestión informático, cuya implementación comenzó progresivamente desde mediados de julio de 2016.

El recorte de la información se realiza en base a la fecha de carga de la “consulta” en el CAJ. Una consulta en un CAJ puede derivar en más de una intervención. De la misma forma, cada intervención puede generar varias gestiones. No obstante, es posible que en el período que se presenta haya más gestiones e intervenciones que las publicadas, debido a que corresponden a “consultas” con carga anterior al período en cuestión.

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 482 del Ministerio de Justicia](http://datos.jus.gob.ar/resoluciones/RESOL-2017-482-APN-MJ.pdf), del 26 de Junio de 2017.
