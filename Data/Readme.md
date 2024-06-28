
# Identification and Description of data sources and data sets 

- Datasources.docx : list of datasources, with a specific name to be used throughout the dashboard and specific description items relevant to Subdense. A datasource can be described in a specific file but all data sources must be registered on the list with their identifier to be used throughout the dashboard. For a given source, like for exemple french BDTopo, german GeoBASIS or british MasterMap, we don't create different items for the different versions. The possible differences from one version to another are described in the datasource description. The standard metadata are not duplicated on the dashboard but the link to access them is indicated.
  
- Datasets.docx : list of datasets, with a specific name to be used throughout the dashboard and specific description relevant to Subdense. Not all datasets need to be registered but only these who need to have a unique identifier. 

- Description content  : in the description of Datasources and datasets, we don't duplicate existing metadata but rather focus on additional description relevant to the dashboard processes. This is similar to the readme file that some research data repository suggest to add to dataset.  



# Discussion

## Folder organisation

**Question: what should be the main organisation here? By data provider? data type? Data users?**

 - [JR (IGN) - 20230228] I started with data provider - we can add more hierarchical levels?
 - [BB(IGN)] Distinguish datasources and datasets at first and then we'll see
 - [BB(IGN)] At this stage, keep it simple and human readable (and also machine readable when possible) so reference all datasets and all datasources on the files Datasets.md and Datasources.md, in whatever order, and mention the place of the description if it is in another folder.  

## Metadata and pointers

 - [JR (IGN) - 20230228] Do we try to uniformise data pointers and some metadata? In the spirit of the collaborative dashboard, this should be rather free - but it may cause problems for automatic processing.
 - [BB(IGN)] Let us adopt a common policy to name and identify stuffs, also provide templates for suggested metadata but let it be free text and then "knowledge graph" specialists will analyse and see how to generate more formal metadata


