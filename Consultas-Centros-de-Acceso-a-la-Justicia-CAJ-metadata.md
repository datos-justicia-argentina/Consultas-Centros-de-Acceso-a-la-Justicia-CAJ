Consultas efectuadas en los Centros de Acceso a la Justicia -CAJ-
=================================================================

Este conjunto de datos contiene información relacionada a las consultas efectuadas en los Centros de Acceso a la Justicia –CAJ- que cuentan con sistema de gestión informático.

Características
---------------

-   **Fecha de Primera Publicación:** 28/06/2017

-   **Tags o Etiquetas:** CAJ, acceso a justicia, acceso a la justicia, asesoramiento jurídico, casas de justicia, justicia, vulnerable, consultas

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Acceso a la Justicia. Dirección Nacional de Acceso a la Justicia

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Acceso a la Justicia. Dirección Nacional de Acceso a la Justicia

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Acceso a la Justicia. Dirección Nacional de Acceso a la Justicia

-   **Grupo:** Acceso a Justicia

-   **Frecuencia de Actualización:** Cada medio año

Recursos disponibles
--------------------

### Consultas efectuadas en los Centros de Acceso a la Justicia -CAJ- AAAA semestre

-   **Nombre del archivo:** consultas-centros-acceso-justicia-AAAA-semetre.csv

-   **Descripción del contenido:** consultas realizadas en los Centros de Acceso a la Justicia que cuentan con sistema de gestión informático

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **id_consulta (int):** código de la consulta

-   **fecha_carga_consulta (date):** fecha de la carga de la consulta en el sistema informático

-   **hora_carga_consulta (date):** hora de la carga de la consulta en el sistema informático

-   **dependencia_id (int):** código del CAJ donde se realizó la consulta

-   **dependencia (string):** nombre del CAJ donde se realizó la consulta

-   **tipo_resolucion (string):** forma de resolución de la consulta

-   **tema (string):** descricpión del tema de la consulta

-   **subtemas_texto (string):** descricpión del subtema de la consulta

-   **naturaleza_consulta (string):** área que canalizó la consulta

-   **estado_consulta (string):** estado de la consulta

-   **persona_id (int):** código del consultante

-   **actividad_principal_consultante (string):** actividad principal del consultante

-   **como_llego_consultante (string):** forma en la que el consultante se enteró del CAJ

-   **fecha_nacimiento_consultante (date):** fecha de nacimiento del consultante

-   **genero_consultante (string):** género del consultante

-   **nivel_de_instruccion_consultante (string):** máximo nivel de instrucción alcanzado por el consultante

-   **atencion_salud_consultante (string):** tipo de cobertura de salud del consultante

-   **pais_consultante (string):** país de nacimiento del consultante

-   **provincia_consultante (string):** provincia de residencia del consultante

-   **id_intervencion (int):** código de la intervención

-   **tipo_intervencion (string):** descripción de la intervención

-   **etapa_intervencion (string):** estado de la intervención

-   **fecha_carga_intervencion (date):** fecha de la carga de la intervención

-   **hora_carga_intervencion (date):** hora en la que se cargó la intervención

-   **id_gestion (int):** código de la gestión

-   **fecha_carga_gestion (date):** fecha de la carga de la gestion

-   **hora_carga_gestion (date):** hora de la carga de la gestion

-   **tipo_gestion (string):** tipo de gestión

### Notas

La base de datos contiene información de las consultas en los CAJ que tienen cuentan con sistema de gestión informático, cuya implementación comenzó progresivamente desde mediados de julio de 2016.

El recorte de la información se realiza en base a la fecha de carga de la “consulta” en el CAJ. Una consulta en un CAJ puede derivar en más de una intervención. De la misma forma, cada intervención puede generar varias gestiones. No obstante, es posible que en el período que se presenta haya más gestiones e intervenciones que las publicadas, debido a que corresponden a “consultas” con carga anterior al período en cuestión.
