# Datasets

List of datasets, either acquired from OTS products, or produced during Subdense. It is useful to 1) register their identifiers in the project 2) give access to Subdense-specific metadata related to these datasets. Such metadata either or in this file beneath the dataset identifiers, or they are in a dedicated file with the identifier as file name and the extension md. 


*******

1. [FR-STR-FUA-Evolution-2011-21](#FR-STR-FUA-Evolution-2011-21)
2. [DE-DOR-FUA-Evolution-2011-21](#DE-DOR-FUA-Evolution-2011-21)
3. [UK-LIV-FUA-Evolution-2011-21](#UK-LIV-FUA-Evolution-2011-21)
4. [FR-STR-FUA-Building-2011](#FR-STR-FUA-Building-2011)
5. [FR-STR-FUA-Building-2021](#FR-STR-FUA-Building-2021)
6. [GHS_POP_ALLCSR_2020_reduced](#GHS_POP_ALLCSR_2020_reduced)
7. [Dataset naming policy](#Dataset-naming-policy)
8. [Dataset description template](#Dataset-description-template)
*******

## FR-STR-FUA-Evolution-2011-21
* Building evolution data computed from BDTopo on the functional area of the city Strasbourg between 2011 and 2021
* Provenance : described in detail in [the process](/Processes/ComputeBuildingEvolution/ComputeBuildingEvolution.md)
* Usage : used to portray Building Evolution Maps in order to show where changes are happening. Described in detail [here](/Maps/Maps.md)
* Distribution : open licence, can be shared within the consortium through our specific ftp, will be shared more widely through a research data platform to be identified within Subdense research data management plan)

## DE-DOR-FUA-Building-Evolution-2011-21
* Building evolution data computed from ATKIS Building data on the functional area of the city Dortmund between 2011 and 2021
* Provenance : described in detail in [the process](/Processes/ComputeBuildingEvolution/ComputeBuildingEvolution.md)
* Usage : used to portray Building Evolution Maps in order to show where changes are happening. Described in detail [here](/Maps/Maps.md)
* Distribution : not open licence

## UK-LIV-FUA-Building-Evolution-2011-21
* Building evolution data computed from OSMasterMap on the functional area of the city Liverpool between 2011 and 2021
* Provenance : described in detail in [the process](/Processes/ComputeBuildingEvolution/ComputeBuildingEvolution.md)
* Usage : used to portray Building Evolution Maps in order to show where changes are happening. Described in detail [here](/Maps/Maps.md)
* Distribution : not open licence

## FR-STR-FUA-Building-2011
* Building data from BDTopo on the functional area of the city Strasbourg in 2011
* Provenance : the generic process is described here [the process](/Processes/DataPreProcessing/PreProcessing.md). For this dataset, the downloaded departments are : La Moselle (57), Le Haut-Rhin (68) et Le Bas-Rhin (67).
* Usage : used to derive Evolution data between 2011 and 2021
* Distribution : open licence, can be shared within the consortium through our specific ftp, will be shared more widely through a research data platform to be identified within Subdense research data management plan)

## FR-STR-FUA-Building-2021
* Building data from BDTopo on the functional area of the city Strasbourg in 2021
* Provenance : described in detail in [the process](/Processes/DataPreProcessing/PreProcessing.md). For this dataset, the downloaded departments are : La Moselle (57), Le Haut-Rhin (68) et Le Bas-Rhin (67).
* Usage : used to derive Evolution data between 2011 and 2021
* Distribution : open licence, can be shared within the consortium through our specific ftp, will be shared more widely through a research data platform to be identified within Subdense research data management plan)

## GHS_POP_ALLCSR_2020_reduced
* **Provenance**: data from GHSL-UCDB, application of process CreateGHS_POP_2020_ALLCSR_reduced, cropped with DeliminateStudyArea and filtered to "perc_inside" >= 0.2
* **Usages**: use as input for cluster analysis
* [**How to cite**](https://ghsl.jrc.ec.europa.eu/datasets.php): Schiavina M., Freire S., Carioli A., MacManus K. (2023): GHS-POP R2023A - GHS population grid multitemporal (1975-2030).European Commission, Joint Research Centre (JRC) PID: http://data.europa.eu/89h/2ff68a52-5b5b-4a22-8f40-c41da8332cfe, doi:10.2905/2FF68A52-5B5B-4A22-8F40-C41DA8332CFE

## Dataset-naming-policy
The name of the dataset is a set of characterstrings attached with "_". 
Characterstrings : 
* area : DE-FKF (Frankfurt), DE-DOR (Dortmundt), FR-STR (Strasbourg), FR-TLS (Toulouse), UK-LVP (Liverpool), UK-BSL (Bristol) or ALLCSR (all case study regions)
* specific area : FUA for functional area, or Name of a focused place within city   
* theme or type of content : Buildings (for building), Evolutions (for data that describe evolutions), ... //to be extended with new strings when new themes are added
* YYYY, MM : in digits, possibly two dates if it is an evolution
* Id : specific additional characters to distinguish different datasets when necessary
    
The identifier of the dataset is used to name the dataset files (or zip repository) and to name the eventual dedicated metadata file for Subdense-specific metadata associated to the dataset. A dataset is considered the same resource even if it is enriched or corrected during the project. It keeps the same identifier, but the modifications are documented in its provenance property.
    
## Dataset-description-template
* A specific description template is proposed adapted to SUBDENSE dashboard workflows. It is not intended to replace existing model to describe geographical datasets but to complement them to adress SUBDENSE specific requirements
* **Provenance** : Textual description of how the datasets was acquired or produced, preferably referring to processes that are described on the dashboard.  This description can get enriched while the dataset is revised and improved (quality check and so on).
* **Usages** : References to datasets, maps, hypothesis (papers) that have been produced with this dataset
* **Feedback** : Comments related to the dataset, interpretation, identification of quality issues and so on
* **Distribution** : how to access the data

