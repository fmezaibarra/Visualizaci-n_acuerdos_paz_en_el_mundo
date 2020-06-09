# Visualización de categorías de acuerdos de paz, una visión mundial.

* Máster en Ciencia de Datos.
* Universitat Oberta de Catalunya.
* Consultor: Ignacio Javier Alcalde Perea.
* Fecha: Junio 9 de 2020

# Autor:
* Fernando Meza Ibarra (fer_meza@hotmail.com)

# Resumen:

A través de la visualización de datos podemos representar de forma gráfica la información y los datos de los acuerdos de paz y acuerdos de entendimiento firmados por diferentes países a nivel mundial. Mediante el uso de elementos visuales, como gráficos y mapas, la visualización de datos ofrece una manera accesible para detectar y comprender las tendencias, los valores atípicos y los patrones en los datos.

# Dataset:

Nombre del dataset:	pax_data_1823_agreements_Jan2020release.csv
Formato:	Archivo texto con valores separados por “comas” (csv)
Número de registros:	1832
Número de categorías:	255
Autores:	Bell, Christine, Sanja Badanjak, Juline Beujouan, Robert Forster, Tim Epple, Astrid Jamar, Kevin McNicholl, Sean Molloy, Kathryn Nash, Jan Pospisil, Robert Wilson, Laura Wise (2020). Libro de códigos PA-X, versión 3.
Bell, C. y Badanjak, S. (2019) Presentaron una nueva base de datos con acuerdos de paz,  en  el Journal of Peace Research , 56 (3)
Programa:	Political Settlements Research Programme, University of Edinburgh
Fuente:	Facultad de Derecho, Universidad de Edinburgh
Los datos referidos se encuentran disponibles en www.peaceagreements.org)

Licencia y términos de uso:	Acceder a https://creativecommons.org/licenses/by-nc-sa/4.0/

# Conociendo la estructura de información del Dataset

La información dentro del Dataset se estructurado en categorías y subcategorías, así:
 
* Grupos: Información de niños, jóvenes, personas con discapacidad, personas de la tercera edad, trabajadores migrantes, grupos raciales, grupos religiosos, pueblos indígenas, refugiados, desplazados, grupos sociales, otros.
* Género: Para información de género (mujeres y niñas, hombres y niños), además de información sobre orientación sexual y familia.
*	Definición de estado: aplica a la naturaleza del estado; configuración de estado; autodeterminación; referéndum; símbolos de estado; independencia / secesión; adhesión / unificación; límites fronterizos; disposiciones transfronterizas.
*	Gobernanza: instituciones políticas (nuevas, reformadas o temporales); Reforma Constitucional; Elecciones; Comisión Electoral; Reforma de partidos políticos; Sociedad Civil; Líderes tradicionales / religiosos; Administración Pública (servicios civiles).
*	Poder: Político, Territorial, Económico y Militar.
*	Derechos humanos e igualdad: Derechos Humanos / Estado de Derecho; Igualdad; Democracia; Medidas de Protección; Marco de Derechos Humanos; Derechos Civiles y Políticos; Derechos Socioeconómicos; Institución Nacional de Derechos Humanos; Instituciones Regionales o Internacionales de Derechos Humanos; Movilidad / Acceso; Procedimientos de Detención; Media y Comunicación; Ciudadanía.
*	Reforma del sector de la justicia: Reforma de la justicia penal y disposiciones de emergencia; Judicial y Tribunales; Prisiones y Detenciones; Leyes Tradicionales / Religiosas.
*	Reconstrucción Socioeconómica: Desarrollo o Reconstrucción Socioeconómica; Plan Económico Nacional; Recursos Naturales; Fondos Internacionales; Negocio; Impuestos; Bancos; Reforma Agraria; Derechos Pastorales / Nómadas; Patrimonio Cultural; Ambiente; Derechos de agua.
*	Sector de Seguridad:  Alto el fuego; Policía; Fuerzas Armadas; Servicios de Inteligencia; Fuerzas Rebeldes, de Oposición y Paramilitares; Retiro de fuerzas extranjeras; Corrupción; Criminalidad; Drogas y Terrorismo.
*	Justicia transicional: Amnistía / Perdón; Tribunales y cortes; Liberación de prisioneros; Víctimas; Desaparecidos; Reparación y Reconciliación.
*	Implementación: Firmantes de la ONU; Firmantes internacional; Acuerdos de Referéndum; Misiones Internacionales.
 
# Proceso de Visualización
Se utilizó al lenguaje de programación R, el cuál es un poderoso entorno en el cual podemos tratar datos y graficar.  Algunas características de este lenguaje son:

*	R al estar orientado a las estadísticas, proporciona un amplio abanico de herramientas.
*	Su gran capacidad gráfica, que permite generar gráficos con alta calidad, con sólo utilizar las algunas funciones.
*	R también puede usarse como herramienta de cálculo numérico y a la vez ser útil para la minería de datos.
*	R puede integrarse con distintas bases de datos y existen bibliotecas que facilitan su utilización desde lenguajes de programación interpretados como Perl, Python y Ruby. Y por supuesto existen proyectos que permiten utilizar R desde Java o .net de Microsoft.
*	Cuenta con un poderoso entorno de desarrollo llamado “R Studio” que es de uso gratuito.

En esta práctica se ha realizado un pre-procesado del Dataset, generamos un nuevo Dataset que nos permitirá utilizarlo como insumo en la fase de Visualización de datos, que es el paso próximo.
Para ello se utilizará “TABLEAU”, el cuál es una herramienta de visualización de datos potente, muy utilizada en el área de la Inteligencia de Negocios (más conocida como Business Intelligence).
TABLEAU simplifica los datos en bruto en un formato muy fácil de entender. La esencia de TABLEAU es simple y a la vez muy relevante: ayudar a las personas y empresas a ver y comprender todos sus datos a través de funciones simples como la de arrastrar y soltar, cualquier persona puede acceder y analizar de forma sencilla datos, e incluso, crear informes y compartir esta información con otros usuarios.

El set de datos ha sido generado a través del procesado que se realizó con ayuda del Lenguaje “R”, el cual nos ha dado el archivo resultante “paz.csv”.


# Contenido:  
 
* fmeza_M2.859_20192_PEC4.pdf : Archivo que consolida toda la práctica.
* FMeza_pax_all_agreements_data.Rmd: Archivo con código R Markdown.  
* pax_data_1823_agreements_Jan2020release.csv : Archivo descargado del repositorio de la Universidad de Edinburgh.
* paz_all_agreements_data.xlsx : Archivo inicial convertido a excel (también sirve como entrada de dattos a Tableau).
* paz.csv: Dataset después del pre-procesado, en formato CSV.
* Tableau-Paz.twb : Archivo generado por Tableau sobre la visualización.

Fin de Reademe.
