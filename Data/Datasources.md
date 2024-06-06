# Datasources 

List of datasources potentially relevant for the dashboard, and associated comments  

*******
 1. [BDTOPO-FR](#BDTOPO-FR)
 2. [EUBUCCO](#EUBUCCO)
 3. [GEOBASIS-DE](#GEOBASIS-DE)
 4. [GHSL UCDB](#GHSL-UCDB)
 5. [OPENZOOM-UK](#OPENZOOM-UK)
 6. [OSM](#OSM)
 7. [OSMASTERMAP-UK](#OSMASTERMAP-UK)
 8. [OSNGD-UK](#OSNGD-UK)
 9. [OCS-GE2-FR](#OCS-GE2-FR)
 10. [Datasource naming policy](#Datasource-naming-policy)
 11. [Datasource description template](#Datasource-description-template)
*******

## BDTOPO-FR 
* **Building** :
  * Conceptual model "	Construction au-dessus du sol qui est utilisée pour abriter des humains, des animaux, des objets, pour la production de biens économiques ou pour la prestation de services et qui se réfère à toute structure construite ou érigée de façon permanente sur son site.", cf https://geoservices.ign.fr/bd-topor-explorer-descriptif-de-contenu
  * representation : classe Batiment 
* **Available Metadata and Documentation** :
  * Standard ISO19139 metadata : 
  * BD TOPO® | Géoservices (ign.fr), french, a fine description of content is available in french through an interactive interface : https://geoservices.ign.fr/bd-topor-explorer-descriptif-de-contenu
  * Documentation of evolutions :
  * Additional metadata : there are additional metadata that are specific to communes or to departement and which are relevant to SUBDENSE, their fine description is https://geoservices.ign.fr/sites/default/files/2023-01/DL_vecteur.pdf pp.14-16 
* **Retrieving Building Data on Temporal and Spatial scope of interest** :
  * Data can be downloaded either on whole France, or regions or departements. A download is associated to a set of metadata that is generic to BDTopo product.
* **Feedback** :  

## EUBUCCO
* **Documentation** : https://docs.eubucco.com/ 
* * **Feedback** : EUBUCCO is a scientific database of individual building footprints for 200+ million buildings across the 27 European Union countries and Switzerland, together with three main attributes – building type, height and construction year – included for respectively 45%, 74%, 24% of the buildings. EUBUCCO is composed of 50 open government datasets and OpenStreetMap that have been collected, harmonized and partly validated. 

## GEOBASIS-DE
* **Documentation** for buildings on national level: https://gdz.bkg.bund.de/index.php/default/digitale-geodaten/sonstige-geodaten/amtliche-hausumringe-deutschland-hu-de.html

## GHSL-UCDB
* Global Human Settlement Layer Urban Center Database, https://ghsl.jrc.ec.europa.eu/
* **Documentation**  https://ghsl.jrc.ec.europa.eu/degurbaDefinitions.php 

## OPENZOOM-UK
* **Documentation** : https://beta.ordnancesurvey.co.uk/products/os-open-zoomstack , english
* **Feedback** : Analysis and quotation of documentation relevant to SUBDENSE : 
https://www.ordnancesurvey.co.uk/documents/os-open-zoomstack-technical-specification.pdf?_gl=1*1jxmav3*_ga*NzE3NjU4MTY0LjE2ODEzNjk5Mjk.*_ga_59ZBN7DVBG*MTY4MTM2OTkyOS4xLjAuMTY4MTM2OTkyOS42MC4wLjA.&_ga=2.2835769.808952103.1681369930-717658164.1681369929 , p5 : “Generalised building footprints at both local and district resolutions. The local buildings have a unique identifier which can be used to style features distinctly.
The identifier will not be persistent between product versions and therefore there
will be no change history information for a feature.”

## OSM 

## OSMASTERMAP-UK
* **Documentation** : https://beta.ordnancesurvey.co.uk/products/os-mastermap-topography-layer 
* **Feedback** : Analysis and quotation of documentation relevant to SUBDENSE : 
Schema : geometries bear the themes. A building is a TopographicArea. 
“Attribute: TOID or gml:id
Definition: The unique topographic reference number. It consists of the letters ‘osgb’ followed by
thirteen or sixteen digits. The TOID must always be retained / stored in its entirety and any leading
zeros on the TOID are retained to permit linking of the feature to other OS MasterMap products”
“Attribute: changeHistory
Definition: Information about the change history of a feature that comprises the reason for the change and the date for this change. Each feature may have numerous change history records, and these are ordered chronologically. A complex attribute.”

## OSNGD-UK
* **Documentation** : https://www.ordnancesurvey.co.uk/business-government/new-data-access-methods?_gl=1*13idjk8*_ga*NzE3NjU4MTY0LjE2ODEzNjk5Mjk.*_ga_59ZBN7DVBG*MTY4MTM2OTkyOS4xLjEuMTY4MTM3MDIxNy41OS4wLjA.&_ga=2.81454110.808952103.1681369930-717658164.1681369929
* **Feedback** : this is an integration of OS data product into a unified product associated with user friendly web services to select relevant data.

## OCS-GE2-FR

## Datasource-naming-policy
* Using the source usual name and add then -UK, -FR, -DE if the product is specific to a given country

