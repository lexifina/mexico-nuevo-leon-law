# Nuevo León: law history in git

The law of the State of Nuevo León (Estado Libre y Soberano de Nuevo León, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-nle/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

191 ordenamientos with 2089 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE NUEVO LEON | 213 | as first published, then each reform: 16 December 1917 to 7 July 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE NUEVO LEON | 119 | as first published, then each reform: 6 July 1935 to 27 June 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES DEL ESTADO DE NUEVO LEON | 82 | as first published, then each reform: 3 February 1973 to 11 June 2022 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE NUEVO LEON | 35 | as first published, then each reform: 1 January 1985 to 14 January 2023 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE NUEVO LEON | 215 | as first published, then each reform: 26 March 1990 to 16 June 2026 |
| `ley-ambiental/` | LEY AMBIENTAL DEL ESTADO DE NUEVO LEON | 46 | as first published, then each reform: 13 September 2005 to 11 May 2025 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia-e/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA, ESTADO DE NUEVO LEON | 45 | as first published, then each reform: 21 September 2007 to 14 December 2025 |
| `ley-de-administracion-financiera/` | LEY DE ADMINISTRACION FINANCIERA PARA EL ESTADO DE NUEVO LEON | 16 | as first published, then each reform: 19 November 1994 to 1 January 2019 |
| `ley-de-adquisiciones-arrendamientos-y-contratacion-de-servic/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y CONTRATACION DE SERVICIOS DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 25 June 2013 to 1 July 2023 |
| `ley-de-agua-potable-y-saneamiento/` | LEY DE AGUA POTABLE Y SANEAMIENTO PARA EL ESTADO DE NUEVO LEON | 10 | as first published, then each reform: 4 October 1997 to 12 October 2023 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE NUEVO LEON | 1 | as first published: 21 November 2022 |
| `ley-de-aparceria-agricola/` | LEY DE APARCERIA AGRICOLA DEL ESTADO DE NUEVO LEON | 1 | as first published: 2 February 2021 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE NUEVO LEON | 1 | as first published: 5 November 2019 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO PARA EL ESTADO DE NUEVO LEON | 11 | as first published, then each reform: 27 November 2017 to 10 March 2026 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE NUEVO LEON | 1 | as first published: 11 July 2010 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 1 January 2020 to 26 November 2022 |
| `ley-de-ciencia-tecnologia-e-innovacion/` | LEY DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE NUEVO LEON | 7 | as first published, then each reform: 22 December 2020 to 23 May 2026 |
| `ley-de-coordinacion-hacendaria/` | LEY DE COORDINACION HACENDARIA DEL ESTADO DE NUEVO LEON | 7 | as first published, then each reform: 1 January 2016 to 6 June 2023 |
| `ley-de-copropiedades-rurales/` | LEY DE COPROPIEDADES RURALES | 1 | as first published: 20 July 2000 |
| `ley-de-defensoria-publica/` | LEY DE DEFENSORIA PUBLICA PARA EL ESTADO DE NUEVO LEON | 9 | as first published, then each reform: 7 April 2009 to 17 August 2021 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE NUEVO LEON | 6 | as first published, then each reform: 8 February 2009 to 12 October 2023 |
| `ley-de-desarrollo-rural-integral-sustentable/` | LEY DE DESARROLLO RURAL INTEGRAL SUSTENTABLE DEL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 1 January 2009 to 8 November 2025 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE NUEVO LEON | 16 | as first published, then each reform: 17 October 2006 to 5 May 2026 |
| `ley-de-educacion-del-estado/` | LEY DE EDUCACION DEL ESTADO | 48 | as first published, then each reform: 17 October 2000 to 28 April 2026 |
| `ley-de-emergencia-policial-reglamentaria-de-la-fraccion-xvii/` | LEY DE EMERGENCIA POLICIAL, REGLAMENTARIA DE LA FRACCION XVIII DEL ARTICULO 85 DE LA CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE NUEVO LEON | 1 | as first published: 30 October 2010 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA RECEPCION PARA EL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 6 February 2020 to 20 January 2024 |
| `ley-de-expropiacion-por-causa-de-utilidad-publica/` | LEY DE EXPROPIACION POR CAUSA DE UTILIDAD PUBLICA | 2 | as first published, then each reform: 14 December 1938 to 29 March 1994 |
| `ley-de-fiscalizacion-superior/` | LEY DE FISCALIZACION SUPERIOR DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 23 September 2011 to 1 January 2022 |
| `ley-de-fomento-a-la-inversion-y-al-empleo/` | LEY DE FOMENTO A LA INVERSION Y AL EMPLEO PARA EL ESTADO DE NUEVO LEON | 14 | as first published, then each reform: 18 November 2017 to 30 September 2025 |
| `ley-de-fomento-a-la-micro-pequena-y-mediana-empresa/` | LEY DE FOMENTO A LA MICRO, PEQUEÑA Y MEDIANA EMPRESA PARA EL ESTADO DE NUEVO LEON | 16 | as first published, then each reform: 18 November 2017 to 3 November 2025 |
| `ley-de-fomento-a-las-actividades-agropecuarias/` | LEY DE FOMENTO A LAS ACTIVIDADES AGROPECUARIAS DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 29 December 1977 to 22 November 2025 |
| `ley-de-fomento-al-turismo/` | LEY DE FOMENTO AL TURISMO DEL ESTADO DE NUEVO LEON | 6 | as first published, then each reform: 3 March 2007 to 21 May 2026 |
| `ley-de-fomento-de-la-sociedad-civil-organizada/` | LEY DE FOMENTO DE LA SOCIEDAD CIVIL ORGANIZADA PARA EL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 18 June 2022 to 27 June 2026 |
| `ley-de-fomento-para-la-construccion-de-edificios-de-estacion/` | LEY DE FOMENTO, PARA LA CONSTRUCCION DE EDIFICIOS DE ESTACIONAMIENTO DE VEHICULOS | 4 | as first published, then each reform: 1 January 1981 to 25 December 2010 |
| `ley-de-gobierno-municipal/` | LEY DE GOBIERNO MUNICIPAL DEL ESTADO DE NUEVO LEON | 18 | as first published, then each reform: 31 October 2015 to 8 November 2025 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO, NUEVO LEON | 64 | as first published, then each reform: 1 January 1975 to 26 January 2023 |
| `ley-de-hacienda-para-los-municipios/` | LEY DE HACIENDA PARA LOS MUNICIPIOS DEL ESTADO DE NUEVO LEON | 67 | as first published, then each reform: 1 January 1975 to 25 January 2023 |
| `ley-de-indulto/` | LEY DE INDULTO PARA EL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 10 December 1969 to 29 October 2010 |
| `ley-de-infraestructura-fisica-educativa-y-deportiva-de-nuevo/` | LEY DE INFRAESTRUCTURA FISICA EDUCATIVA Y DEPORTIVA DE NUEVO LEON | 5 | as first published, then each reform: 15 September 2012 to 29 March 2025 |
| `ley-de-ingresos-de-los-municipios/` | LEY DE INGRESOS DE LOS MUNICIPIOS DEL ESTADO DE NUEVO LEON PARA EL EJERCICIO FISCAL 2025 | 2 | as first published, then each reform: 17 February 2025 to 14 May 2025 |
| `ley-de-instituciones-asistenciales-publicas-y-privadas-para/` | LEY DE INSTITUCIONES ASISTENCIALES PUBLICAS Y PRIVADAS PARA LAS PERSONAS ADULTAS MAYORES EN EL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 21 March 2015 to 29 October 2022 |
| `ley-de-instituciones-asistenciales-que-tienen-bajo-su-guarda/` | LEY DE INSTITUCIONES ASISTENCIALES QUE TIENEN BAJO SU GUARDA, CUSTODIA O AMBAS A NIÑAS, NIÑOS Y ADOLESCENTES EN EL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 6 July 2011 to 22 February 2025 |
| `ley-de-juicio-politico/` | LEY DE JUICIO POLITICO DEL ESTADO DE NUEVO LEON | 1 | as first published: 24 April 2021 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA PARA EL ESTADO Y MUNICIPIOS DE NUEVO LEON - ANTES LEY DE JUSTICIA ADMINISTRATIVA PARA EL ESTADO DE NUEVO LEON - | 25 | as first published, then each reform: 21 February 1997 to 3 October 2026 |
| `ley-de-justicia-civica/` | LEY DE JUSTICIA CIVICA PARA EL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 25 January 2023 to 13 June 2026 |
| `ley-de-la-beneficencia-privada/` | LEY DE LA BENEFICENCIA PRIVADA PARA EL ESTADO DE NUEVO LEON | 8 | as first published, then each reform: 3 January 1984 to 31 December 2020 |
| `ley-de-la-comision-estatal-de-derechos-humanos/` | LEY DE LA COMISION ESTATAL DE DERECHOS HUMANOS DEL ESTADO DE NUEVO LEON -- ANTES LEY QUE CREA LA COMISION ESTATAL DE DERECHOS HUMANOS -- | 10 | as first published, then each reform: 29 December 1992 to 10 December 2022 |
| `ley-de-la-corporacion-para-el-desarrollo-agropecuario-de-nue/` | LEY DE LA CORPORACION PARA EL DESARROLLO AGROPECUARIO DE NUEVO LEON | 4 | as first published, then each reform: 15 December 2003 to 25 December 2010 |
| `ley-de-la-corporacion-para-el-desarrollo-turistico-de-nuevo/` | LEY DE LA CORPORACION PARA EL DESARROLLO TURISTICO DE NUEVO LEON | 3 | as first published, then each reform: 26 February 2004 to 25 December 2010 |
| `ley-de-la-institucion-policial-estatal-fuerza-civil-nuevo-le/` | LEY DE LA INSTITUCION POLICIAL ESTATAL FUERZA CIVIL, NUEVO LEON | 5 | as first published, then each reform: 20 January 2013 to 16 April 2026 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD PARA EL ESTADO DE NUEVO LEON | 22 | as first published, then each reform: 28 July 2008 to 16 January 2025 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores-en-el-es/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES EN EL ESTADO DE NUEVO LEON | 26 | as first published, then each reform: 8 January 2005 to 30 September 2025 |
| `ley-de-los-derechos-de-las-personas-indigenas-y-afromexicana/` | LEY DE LOS DERECHOS DE LAS PERSONAS INDIGENAS Y AFROMEXICANAS EN EL ESTADO DE NUEVO LEON -- ANTES LEY DE LOS DERECHOS INDIGENAS EN EL ESTADO DE NUEVO LEON -- | 4 | as first published, then each reform: 23 June 2012 to 17 January 2026 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES PARA EL ESTADO DE NUEVO LEON | 25 | as first published, then each reform: 28 November 2015 to 8 November 2025 |
| `ley-de-mecanismos-alternativos-para-la-solucion-de-controver/` | LEY DE MECANISMOS ALTERNATIVOS PARA LA SOLUCION DE CONTROVERSIAS PARA EL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 13 January 2017 to 31 December 2020 |
| `ley-de-movilidad-sostenible-de-accesibilidad-y-seguridad-via/` | LEY DE MOVILIDAD SOSTENIBLE, DE ACCESIBILIDAD Y SEGURIDAD VIAL PARA EL ESTADO DE NUEVO LEON -- ANTES LEY DE MOVILIDAD SOSTENIBLE Y ACCESIBILIDAD PARA EL ESTADO DE NUEVO LEON -- | 21 | as first published, then each reform: 9 January 2020 to 23 May 2026 |
| `ley-de-nomenclatura/` | LEY DE NOMENCLATURA DEL ESTADO Y MUNICIPIOS DE NUEVO LEON | 1 | as first published: 28 November 2020 |
| `ley-de-obras-publicas/` | LEY DE OBRAS PUBLICAS PARA EL ESTADO Y MUNICIPIOS DE NUEVO LEON | 8 | as first published, then each reform: 1 January 1998 to 31 December 2020 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE NUEVO LEON | 1 | as first published: 9 November 2016 |
| `ley-de-pensiones-para-los-servidores-publicos-en-el-estado-d/` | LEY DE PENSIONES PARA LOS SERVIDORES PUBLICOS EN EL ESTADO DE NUEVO LEON | 1 | as first published: 27 December 1933 |
| `ley-de-pensiones-seguro-de-vida-y-otros-beneficios-a-los-vet/` | LEY DE PENSIONES, SEGURO DE VIDA Y OTROS BENEFICIOS A LOS VETERANOS DE LA REVOLUCION | 2 | as first published, then each reform: 27 December 1950 to 19 November 1977 |
| `ley-de-planeacion-estrategica/` | LEY DE PLANEACION ESTRATEGICA DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 18 January 2014 to 9 June 2020 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-y-de/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 29 January 2022 to 15 November 2025 |
| `ley-de-prevencion-social-de-la-violencia-y-la-delincuencia-c/` | LEY DE PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA CON PARTICIPACION CIUDADANA DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 1 June 2016 to 28 February 2026 |
| `ley-de-prevencion-y-atencion-integral-de-la-violencia-famili/` | LEY DE PREVENCION Y ATENCION INTEGRAL DE LA VIOLENCIA FAMILIAR EN EL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 16 February 2006 to 1 March 2022 |
| `ley-de-profesiones/` | LEY DE PROFESIONES DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 26 July 1984 to 3 December 2024 |
| `ley-de-propiedad-en-condominio-de-inmuebles/` | LEY DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 3 May 2017 to 12 October 2023 |
| `ley-de-proteccion-a-la-salud-bucal/` | LEY DE PROTECCION A LA SALUD BUCAL PARA EL ESTADO DE NUEVO LEON. | 1 | as first published: 22 November 2022 |
| `ley-de-proteccion-al-parto-humanizado-y-a-la-maternidad-dign/` | LEY DE PROTECCION AL PARTO HUMANIZADO Y A LA MATERNIDAD DIGNA DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 21 November 2019 to 29 May 2025 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE NUEVO LEON | 12 | as first published, then each reform: 22 January 1997 to 16 June 2026 |
| `ley-de-proteccion-contra-incendios-y-materiales-peligrosos/` | LEY DE PROTECCION CONTRA INCENDIOS Y MATERIALES PELIGROSOS DEL ESTADO DE NUEVO LEON | 1 | as first published: 1 February 1997 |
| `ley-de-proteccion-contra-la-exposicion-al-humo-del-tabaco/` | LEY DE PROTECCION CONTRA LA EXPOSICION AL HUMO DEL TABACO DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 15 June 2013 to 28 April 2026 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE NUEVO LEON | 1 | as first published: 12 December 2019 |
| `ley-de-proteccion-y-bienestar-animal-para-la-sustentabilidad/` | LEY DE PROTECCION Y BIENESTAR ANIMAL PARA LA SUSTENTABILIDAD DEL ESTADO DE NUEVO LEON | 16 | as first published, then each reform: 29 September 2016 to 27 June 2025 |
| `ley-de-proteccion-y-fomento-apicola/` | LEY DE PROTECCION Y FOMENTO APICOLA DEL ESTADO DE NUEVO LEON | 1 | as first published: 30 January 2020 |
| `ley-de-remuneraciones-de-los-servidores-publicos/` | LEY DE REMUNERACIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 21 September 2007 to 1 January 2009 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO Y MUNICIPIOS DE NUEVO LEON | 5 | as first published, then each reform: 1 August 2013 to 29 September 2023 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE NUEVO LEON | 7 | as first published, then each reform: 8 June 2019 to 3 October 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL PARA EL ESTADO DE NUEVO LEON | 9 | as first published, then each reform: 9 May 2018 to 28 April 2026 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA PARA EL ESTADO DE NUEVO LEON | 7 | as first published, then each reform: 26 July 2007 to 23 April 2026 |
| `ley-de-seguridad-publica/` | LEY DE SEGURIDAD PUBLICA PARA EL ESTADO DE NUEVO LEON | 38 | as first published, then each reform: 23 September 2008 to 16 June 2026 |
| `ley-de-senalamientos-viales/` | LEY DE SEÑALAMIENTOS VIALES PARA EL ESTADO DE NUEVO LEON | 6 | as first published, then each reform: 22 August 2009 to 10 October 2025 |
| `ley-de-sociedades-mutualistas/` | LEY DE SOCIEDADES MUTUALISTAS DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 9 June 1949 to 3 November 1984 |
| `ley-de-tierras-ociosas/` | LEY DE TIERRAS OCIOSAS | 1 | as first published: 3 February 1937 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE NUEVO LEON | 11 | as first published, then each reform: 2 July 2016 to 16 April 2022 |
| `ley-de-victimas/` | LEY DE VICTIMAS DEL ESTADO DE NUEVO LEON | 6 | as first published, then each reform: 7 December 2013 to 27 January 2022 |
| `ley-del-catastro/` | LEY DEL CATASTRO | 34 | as first published, then each reform: 19 January 1964 to 31 December 2020 |
| `ley-del-derecho-a-la-alimentacion-adecuada-y-combate-contra/` | LEY DEL DERECHO A LA ALIMENTACION ADECUADA Y COMBATE CONTRA EL DESPERDICIO DE ALIMENTOS PARA EL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 18 November 2017 to 26 January 2023 |
| `ley-del-fondo-testamentario-del-maestro/` | LEY DEL FONDO TESTAMENTARIO DEL MAESTRO | 1 | as first published: 30 November 1935 |
| `ley-del-instituto-de-evaluacion-educativa-de-nuevo-leon/` | LEY DEL INSTITUTO DE EVALUACION EDUCATIVA DE NUEVO LEON | 4 | as first published, then each reform: 30 December 2005 to 25 December 2010 |
| `ley-del-instituto-de-la-vivienda-de-nuevo-leon/` | LEY DEL INSTITUTO DE LA VIVIENDA DE NUEVO LEON | 4 | as first published, then each reform: 24 December 2003 to 25 December 2010 |
| `ley-del-instituto-de-seguridad-y-servicios-sociales-de-los-t/` | LEY DEL INSTITUTO DE SEGURIDAD Y SERVICIOS SOCIALES DE LOS TRABAJADORES DEL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 30 July 2020 to 24 June 2023 |
| `ley-del-instituto-estatal-de-cultura-fisica-y-deporte/` | LEY DEL INSTITUTO ESTATAL DE CULTURA FISICA Y DEPORTE, DEL ESTADO DE NUEVO LEON | 11 | as first published, then each reform: 24 December 2003 to 8 November 2025 |
| `ley-del-instituto-estatal-de-la-juventud/` | LEY DEL INSTITUTO ESTATAL DE LA JUVENTUD | 12 | as first published, then each reform: 24 December 2003 to 1 November 2025 |
| `ley-del-instituto-estatal-de-las-mujeres-nuevo-leon/` | LEY DEL INSTITUTO ESTATAL DE LAS MUJERES, NUEVO LEON | 8 | as first published, then each reform: 17 December 2003 to 11 March 2021 |
| `ley-del-instituto-estatal-de-seguridad-publica/` | LEY DEL INSTITUTO ESTATAL DE SEGURIDAD PUBLICA | 3 | as first published, then each reform: 15 December 2008 to 25 December 2010 |
| `ley-del-instituto-registral-y-catastral/` | LEY DEL INSTITUTO REGISTRAL Y CATASTRAL DEL ESTADO DE NUEVO LEON | 6 | as first published, then each reform: 1 January 2011 to 25 January 2024 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE NUEVO LEON | 10 | as first published, then each reform: 27 December 1983 to 18 January 2025 |
| `ley-del-patrimonio-cultural/` | LEY DEL PATRIMONIO CULTURAL DEL ESTADO DE NUEVO LEON | 14 | as first published, then each reform: 24 December 1991 to 22 December 2025 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 11 July 1996 to 11 March 2021 |
| `ley-del-registro-civil/` | LEY DEL REGISTRO CIVIL PARA EL ESTADO DE NUEVO LEON | 10 | as first published, then each reform: 10 April 2008 to 27 June 2026 |
| `ley-del-servicio-civil/` | LEY DEL SERVICIO CIVIL DEL ESTADO DE NUEVO LEON | 27 | as first published, then each reform: 29 June 1948 to 15 November 2025 |
| `ley-del-servicio-profesional-de-carrera-de-la-auditoria-supe/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA DE LA AUDITORIA SUPERIOR DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 23 March 2012 to 18 January 2025 |
| `ley-del-servicio-profesional-electoral/` | LEY DEL SERVICIO PROFESIONAL ELECTORAL | 2 | as first published, then each reform: 3 December 1998 to 31 July 2008 |
| `ley-del-sistema-estatal-anticorrupcion/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION PARA EL ESTADO DE NUEVO LEON | 8 | as first published, then each reform: 7 July 2017 to 7 September 2022 |
| `ley-electoral/` | LEY ELECTORAL PARA EL ESTADO DE NUEVO LEON | 7 | as first published, then each reform: 8 July 2014 to 30 May 2023 |
| `ley-en-materia-de-desaparicion-y-busqueda-de-personas/` | LEY EN MATERIA DE DESAPARICION Y BUSQUEDA DE PERSONAS PARA EL ESTADO DE NUEVO LEON | 1 | as first published: 1 January 2023 |
| `ley-estatal-de-salud/` | LEY ESTATAL DE SALUD, DEL ESTADO DE NUEVO LEON | 61 | as first published, then each reform: 13 December 1988 to 30 December 2025 |
| `ley-estatal-del-deporte-nuevo-leon/` | LEY ESTATAL DEL DEPORTE, NUEVO LEON | 12 | as first published, then each reform: 18 November 1993 to 23 October 2025 |
| `ley-ganadera/` | LEY GANADERA DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 17 May 1994 to 8 December 2007 |
| `ley-ingresos/` | LEY INGRESOS DEL ESTADO DE NUEVO LEON PARA EL EJERCICIO FISCAL 2025 | 2 | as first published, then each reform: 18 February 2025 to 1 January 2026 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA PARA EL ESTADO DE NUEVO LEON | 1 | as first published: 4 October 2021 |
| `ley-organica-de-la-fiscalia-general-de-justicia/` | LEY ORGANICA DE LA FISCALIA GENERAL DE JUSTICIA DEL ESTADO DE NUEVO LEON | 10 | as first published, then each reform: 7 December 2017 to 16 June 2026 |
| `ley-organica-de-la-universidad-autonoma-de-nuevo-leon/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE NUEVO LEON | 2 | as first published, then each reform: 7 June 1971 to 26 October 2023 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 10 September 2022 to 26 May 2026 |
| `ley-organica-del-hospital-universitario-dr-jose-eleuterio-go/` | LEY ORGANICA DEL HOSPITAL UNIVERSITARIO "DR. JOSE ELEUTERIO GONZALEZ" | 2 | as first published, then each reform: 30 January 1955 to 3 November 1984 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE NUEVO LEON | 17 | as first published, then each reform: 9 February 1999 to 21 May 2022 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE NUEVO LEON | 54 | as first published, then each reform: 11 September 1992 to 25 May 2026 |
| `ley-organica-para-el-servicio-de-transportes-rusticos-y-urba/` | LEY ORGANICA PARA EL SERVICIO DE TRANSPORTES RUSTICOS Y URBANOS | 1 | as first published: 8 June 1932 |
| `ley-organica-que-crea-la-escuela-normal-superior/` | LEY ORGANICA QUE CREA LA ESCUELA NORMAL SUPERIOR DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 4 November 1961 to 4 June 1967 |
| `ley-para-el-impulso-desarrollo-y-promocion-de-la-industria-c/` | LEY PARA EL IMPULSO, DESARROLLO Y PROMOCION DE LA INDUSTRIA CINEMATOGRAFICA Y AUDIOVISUAL DEL ESTADO DE NUEVO LEON | 1 | as first published: 24 October 2024 |
| `ley-para-el-reconocimiento-al-merito-civico-presea-estado-de/` | LEY PARA EL RECONOCIMIENTO AL MERITO CIVICO "PRESEA ESTADO DE NUEVO LEON" | 3 | as first published, then each reform: 8 November 2007 to 12 November 2011 |
| `ley-para-incentivar-la-denuncia-de-actos-de-corrupcion-de-se/` | LEY PARA INCENTIVAR LA DENUNCIA DE ACTOS DE CORRUPCION DE SERVIDORES PUBLICOS DEL ESTADO DE NUEVO LEON | 1 | as first published: 30 June 2013 |
| `ley-para-la-administracion-de-bienes-asegurados-decomisados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS, DECOMISADOS O ABANDONADOS DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 24 December 2014 to 18 January 2025 |
| `ley-para-la-atencion-proteccion-e-inclusion-de-las-personas/` | LEY PARA LA ATENCION, PROTECCION E INCLUSION DE LAS PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA, Y OTRAS CONDICIONES DE LA NEURODIVERSIDAD PARA EL ESTADO DE NUEVO LEON | 1 | as first published: 1 July 2023 |
| `ley-para-la-conservacion-y-proteccion-del-arbolado-urbano/` | LEY PARA LA CONSERVACION Y PROTECCION DEL ARBOLADO URBANO DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 28 July 2012 to 1 November 2025 |
| `ley-para-la-construccion-y-rehabilitacion-de-pavimentos/` | LEY PARA LA CONSTRUCCION Y REHABILITACION DE PAVIMENTOS DEL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 10 December 2009 to 29 May 2021 |
| `ley-para-la-deteccion-y-tratamiento-oportuno-e-integral-del/` | LEY PARA LA DETECCION Y TRATAMIENTO OPORTUNO E INTEGRAL DEL CANCER EN LA INFANCIA Y LA ADOLESCENCIA DEL ESTADO DE NUEVO LEON | 1 | as first published: 7 October 2023 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE NUEVO LEON | 12 | as first published, then each reform: 27 December 2011 to 29 May 2025 |
| `ley-para-la-integracion-del-acervo-bibliografico-en-el-estad/` | LEY PARA LA INTEGRACION DEL ACERVO BIBLIOGRAFICO EN EL ESTADO DE NUEVO LEON | 1 | as first published: 27 December 2005 |
| `ley-para-la-mejora-regulatoria-y-la-simplificacion-administr/` | LEY PARA LA MEJORA REGULATORIA Y LA SIMPLIFICACION ADMINISTRATIVA DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 19 January 2017 to 11 June 2022 |
| `ley-para-la-prevencion-y-combate-al-abuso-del-alcohol-y-de-r/` | LEY PARA LA PREVENCION Y COMBATE AL ABUSO DEL ALCOHOL Y DE REGULACION PARA SU VENTA Y CONSUMO PARA EL ESTADO DE NUEVO LEON | 9 | as first published, then each reform: 19 May 2011 to 31 December 2020 |
| `ley-para-la-promocion-de-valores-y-cultura-de-la-legalidad/` | LEY PARA LA PROMOCION DE VALORES Y CULTURA DE LA LEGALIDAD DEL ESTADO DE NUEVO LEON | 8 | as first published, then each reform: 24 March 2007 to 8 November 2025 |
| `ley-para-la-proteccion-de-los-derechos-de-las-personas-con-d/` | LEY PARA LA PROTECCION DE LOS DERECHOS DE LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE NUEVO LEON | 12 | as first published, then each reform: 4 July 2014 to 18 January 2025 |
| `ley-para-la-proteccion-de-personas-que-intervienen-en-el-pro/` | LEY PARA LA PROTECCION DE PERSONAS QUE INTERVIENEN EN EL PROCEDIMIENTO PENAL DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 24 December 2014 to 18 January 2025 |
| `ley-para-la-proteccion-apoyo-y-promocion-de-la-lactancia-mat/` | LEY PARA LA PROTECCION, APOYO Y PROMOCION DE LA LACTANCIA MATERNA DEL ESTADO DE NUEVO LEON | 1 | as first published: 21 January 2016 |
| `ley-para-prevenir-la-obesidad-y-el-sobrepeso-en-el-estado-y/` | LEY PARA PREVENIR LA OBESIDAD Y EL SOBREPESO EN EL ESTADO Y MUNICIPIOS DE NUEVO LEON | 3 | as first published, then each reform: 24 January 2015 to 27 October 2022 |
| `ley-para-prevenir-y-eliminar-la-discriminacion-en-el-estado/` | LEY PARA PREVENIR Y ELIMINAR LA DISCRIMINACION EN EL ESTADO DE NUEVO LEON | 12 | as first published, then each reform: 18 May 2017 to 4 May 2026 |
| `ley-para-prevenir-atender-y-erradicar-el-acoso-y-la-violenci/` | LEY PARA PREVENIR, ATENDER Y ERRADICAR EL ACOSO Y LA VIOLENCIA ESCOLAR DEL ESTADO DE NUEVO LEON | 7 | as first published, then each reform: 2 July 2013 to 22 December 2025 |
| `ley-para-prevenir-atender-combatir-y-erradicar-la-trata-de-p/` | LEY PARA PREVENIR, ATENDER, COMBATIR Y ERRADICAR LA TRATA DE PERSONAS EN EL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 31 July 2010 to 17 January 2023 |
| `ley-para-regular-el-acceso-vial-y-mejorar-la-seguridad-de-lo/` | LEY PARA REGULAR EL ACCESO VIAL Y MEJORAR LA SEGURIDAD DE LOS VECINOS EN EL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 28 January 2015 to 13 January 2022 |
| `ley-para-regular-el-uso-de-la-via-publica-en-el-ejercicio-de/` | LEY PARA REGULAR EL USO DE LA VIA PUBLICA EN EL EJERCICIO DE LA ACTIVIDAD COMERCIAL | 2 | as first published, then each reform: 3 February 1994 to 25 December 2010 |
| `ley-que-crea-al-organismo-publico-descentralizado-denominado/` | LEY QUE CREA AL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO INSTITUTO DEL AGUA DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 16 August 2006 to 25 December 2010 |
| `ley-que-crea-el-colegio-de-bachilleres-militarizado-general/` | LEY QUE CREA EL COLEGIO DE BACHILLERES MILITARIZADO "GENERAL MARIANO ESCOBEDO" DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 17 January 2019 to 5 November 2022 |
| `ley-que-crea-el-colegio-de-educacion-profesional-tecnica/` | LEY QUE CREA EL COLEGIO DE EDUCACION PROFESIONAL TECNICA DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 30 December 1998 to 14 January 2012 |
| `ley-que-crea-el-consejo-estatal-de-adopciones/` | LEY QUE CREA EL CONSEJO ESTATAL DE ADOPCIONES | 8 | as first published, then each reform: 10 February 1996 to 27 April 2017 |
| `ley-que-crea-el-consejo-para-la-cultura-y-las-artes-de-nuevo/` | LEY QUE CREA EL CONSEJO PARA LA CULTURA Y LAS ARTES DE NUEVO LEON | 10 | as first published, then each reform: 7 June 1995 to 8 November 2025 |
| `ley-que-crea-el-fondo-para-la-proteccion-infantil-en-el-esta/` | LEY QUE CREA EL FONDO PARA LA PROTECCION INFANTIL EN EL ESTADO | 1 | as first published: 20 August 1947 |
| `ley-que-crea-el-instituto-de-capacitacion-y-educacion-para-e/` | LEY QUE CREA EL INSTITUTO DE CAPACITACION Y EDUCACION PARA EL TRABAJO DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 11 March 2021 to 29 November 2025 |
| `ley-que-crea-el-instituto-de-control-vehicular/` | LEY QUE CREA EL INSTITUTO DE CONTROL VEHICULAR DEL ESTADO DE NUEVO LEON | 24 | as first published, then each reform: 2 December 2005 to 27 June 2026 |
| `ley-que-crea-el-instituto-de-investigacion-innovacion-y-estu/` | LEY QUE CREA EL INSTITUTO DE INVESTIGACION, INNOVACION Y ESTUDIOS DE POSGRADO PARA LA EDUCACION DEL ESTADO DE NUEVO LEON | 1 | as first published: 28 June 2012 |
| `ley-que-crea-el-organismo-publico-descentralizado-de-partici/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DE PARTICIPACION CIUDADANA DENOMINADO CORPORACION PARA EL DESARROLLO DE LA ZONA FRONTERIZA DE NUEVO LEON | 1 | as first published: 22 July 2005 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO "RED ESTATAL DE AUTOPISTAS DE NUEVO LEON" | 5 | as first published, then each reform: 10 September 1988 to 25 December 2010 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-2/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO "SISTEMA DE CAMINOS DE NUEVO LEON" | 2 | as first published, then each reform: 30 January 1989 to 25 December 2010 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-3/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO COLEGIO DE ESTUDIOS CIENTIFICOS Y TECNOLOGICOS DEL ESTADO DE NUEVO LEON, CECyTENL. | 2 | as first published, then each reform: 12 May 1994 to 20 May 2003 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-4/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO MUSEO DE HISTORIA MEXICANA | 2 | as first published, then each reform: 2 August 1994 to 25 December 2010 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-5/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO PARQUE FUNDIDORA | 2 | as first published, then each reform: 10 July 2006 to 19 September 2009 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-6/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO PARQUES Y VIDA SILVESTRE DE NUEVO LEON | 4 | as first published, then each reform: 5 September 2006 to 25 December 2010 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-7/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO SISTEMA DE EDUCACION CIENTIFICA Y TECNOLOGICA DEL ESTADO DE NUEVO LEON "SECYT" | 1 | as first published: 11 May 1994 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-8/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO SISTEMA DE RADIO Y TELEVISION DE NUEVO LEON | 2 | as first published, then each reform: 17 May 2018 to 14 May 2025 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-9/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO SISTEMA DE TRANSPORTE COLECTIVO "METRORREY" | 4 | as first published, then each reform: 10 November 1987 to 25 December 2010 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado-10/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO SISTEMA INTEGRAL PARA EL MANEJO ECOLOGICO Y PROCESAMIENTO DE DESECHOS- ANTES SISTEMA METROPOLITANO DE PROCESAMIENTO DE DESECHOS SOLIDOS | 5 | as first published, then each reform: 2 June 1987 to 25 December 2010 |
| `ley-que-crea-el-organismo-publico-descentralizado-operadora/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO OPERADORA DE SERVICIOS TURISTICOS DE NUEVO LEON | 3 | as first published, then each reform: 8 December 1977 to 14 October 1993 |
| `ley-que-crea-el-organismo-publico-descentralizado-servicios/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO SERVICIOS DE SALUD DE NUEVO LEON | 1 | as first published: 19 December 1996 |
| `ley-que-crea-el-patronato-universitario/` | LEY QUE CREA EL PATRONATO UNIVERSITARIO | 1 | as first published: 19 December 1950 |
| `ley-que-crea-el-registro-estatal-de-asesores-inmobiliarios/` | LEY QUE CREA EL REGISTRO ESTATAL DE ASESORES INMOBILIARIOS DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 1 January 2017 to 31 December 2020 |
| `ley-que-crea-la-escuela-para-padres-madres-o-quienes-ejerzan/` | LEY QUE CREA LA ESCUELA PARA PADRES, MADRES O QUIENES EJERZAN LA TUTELA, GUARDA O CUSTODIA DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 24 April 2021 to 1 March 2025 |
| `ley-que-crea-la-medalla-de-honor-fray-servando-teresa-de-mie/` | LEY QUE CREA LA MEDALLA DE HONOR "FRAY SERVANDO TERESA DE MIER" DEL H. CONGRESO DEL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 3 December 2015 to 13 June 2026 |
| `ley-que-crea-la-medalla-de-honor-mauricio-fernandez-garza-de/` | LEY QUE CREA LA MEDALLA DE HONOR "MAURICIO FERNANDEZ GARZA" DEL H. CONGRESO DEL ESTADO DE NUEVO LEON | 1 | as first published: 20 September 2025 |
| `ley-que-crea-la-unidad-de-integracion-educativa-de-nuevo-leo/` | LEY QUE CREA LA UNIDAD DE INTEGRACION EDUCATIVA DE NUEVO LEON | 3 | as first published, then each reform: 4 June 1992 to 27 October 2020 |
| `ley-que-crea-la-universidad-de-ciencias-de-la-seguridad/` | LEY QUE CREA LA UNIVERSIDAD DE CIENCIAS DE LA SEGURIDAD DEL ESTADO DE NUEVO LEON | 5 | as first published, then each reform: 16 April 2011 to 18 January 2025 |
| – | – | 2 | as first published, then each reform: 30 November 2010 to 30 January 2025 |
| – | – | 1 | as first published: 1 March 2016 |
| `ley-que-crea-la-universidad-tecnologica-bilingue-franco-mexi/` | LEY QUE CREA LA UNIVERSIDAD TECNOLOGICA BILINGÜE FRANCO MEXICANA DE NUEVO LEON | 1 | as first published: 4 June 2019 |
| `ley-que-crea-la-universidad-tecnologica-cadereyta-nuevo-leon/` | LEY QUE CREA LA UNIVERSIDAD TECNOLOGICA CADEREYTA, NUEVO LEON | 2 | as first published, then each reform: 3 June 2010 to 1 March 2016 |
| `ley-que-crea-la-universidad-tecnologica-gral-mariano-escobed/` | LEY QUE CREA LA UNIVERSIDAD TECNOLOGICA GRAL. MARIANO ESCOBEDO | 3 | as first published, then each reform: 1 October 1998 to 25 December 2010 |
| `ley-que-crea-la-universidad-tecnologica-linares/` | LEY QUE CREA LA UNIVERSIDAD TECNOLOGICA LINARES DEL ESTADO DE NUEVO LEON | 1 | as first published: 3 June 2010 |
| `ley-que-crea-la-universidad-tecnologica-santa-catarina/` | LEY QUE CREA LA UNIVERSIDAD TECNOLOGICA SANTA CATARINA | 3 | as first published, then each reform: 1 October 1998 to 25 December 2010 |
| `ley-que-crea-las-juntas-de-mejoramiento-moral-civico-y-mater/` | LEY QUE CREA LAS JUNTAS DE MEJORAMIENTO MORAL, CIVICO Y MATERIAL EN EL ESTADO DE NUEVO LEON | 4 | as first published, then each reform: 23 December 1953 to 3 November 1984 |
| `ley-que-crea-las-juntas-de-mejoras-materiales-en-el-estado/` | LEY QUE CREA LAS JUNTAS DE MEJORAS MATERIALES EN EL ESTADO | 1 | as first published: 5 June 1940 |
| `ley-que-crea-una-institucion-publica-descentralizada-con-per/` | LEY QUE CREA UNA INSTITUCION PUBLICA DESCENTRALIZADA CON PERSONALIDAD JURIDICA PROPIA Y CON DOMICILIO EN LA CIUDAD DE MONTERREY QUE SE DENOMINARA "SERVICIOS DE AGUA Y DRENAJE DE MONTERREY" | 10 | as first published, then each reform: 10 May 1956 to 25 January 2023 |
| `ley-que-regula-el-procedimiento-de-emision-de-la-declaratori/` | LEY QUE REGULA EL PROCEDIMIENTO DE EMISION DE LA DECLARATORIA DE AUSENCIA POR DESAPARICION EN EL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 28 May 2015 to 21 November 2019 |
| `ley-que-regula-el-uso-de-vehiculos-recreativos-todo-terreno/` | LEY QUE REGULA EL USO DE VEHICULOS RECREATIVOS TODO TERRENO EN ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 26 January 2019 to 12 March 2019 |
| `ley-que-regula-la-ejecucion-de-las-sanciones-penales/` | LEY QUE REGULA LA EJECUCION DE LAS SANCIONES PENALES | 13 | as first published, then each reform: 31 July 1994 to 11 July 2013 |
| `ley-que-regula-la-expedicion-de-licencias-para-conducir/` | LEY QUE REGULA LA EXPEDICION DE LICENCIAS PARA CONDUCIR DEL ESTADO DE NUEVO LEON | 12 | as first published, then each reform: 1 January 2006 to 27 June 2026 |
| `ley-que-regula-las-caracteristicas-uso-y-difusion-del-escudo/` | LEY QUE REGULA LAS CARACTERISTICAS, USO Y DIFUSION DEL ESCUDO DEL ESTADO DE NUEVO LEON | 3 | as first published, then each reform: 11 July 1996 to 18 October 2025 |
| `ley-reglamentaria-del-articulo-95-de-la-constitucion-politic/` | LEY REGLAMENTARIA DEL ARTICULO 95 DE LA CONSTITUCION POLITICA DEL ESTADO DE NUEVO LEON | 1 | as first published: 17 December 2014 |
| `ley-reglamentaria-del-registro-publico-de-la-propiedad-y-del/` | LEY REGLAMENTARIA DEL REGISTRO PUBLICO DE LA PROPIEDAD Y DEL COMERCIO PARA EL ESTADO DE NUEVO LEON | 7 | as first published, then each reform: 23 January 1972 to 3 July 2018 |
| `ley-sobre-el-sistema-estatal-de-asistencia-social/` | LEY SOBRE EL SISTEMA ESTATAL DE ASISTENCIA SOCIAL DEL ESTADO DE NUEVO LEON | 17 | as first published, then each reform: 13 December 1988 to 10 May 2025 |
| `ley-sobre-gobierno-electronico-y-fomento-al-uso-de-las-tecno/` | LEY SOBRE GOBIERNO ELECTRONICO Y FOMENTO AL USO DE LAS TECNOLOGIAS DE LA INFORMACION DEL ESTADO DE NUEVO LEON | 2 | as first published, then each reform: 4 July 2013 to 26 July 2013 |
| `ley-sobre-proteccion-a-la-agricultura/` | LEY SOBRE PROTECCION A LA AGRICULTURA | 1 | as first published: 22 May 1929 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Monterrey, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 0 days after publication, the state rule SCJN cites.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
