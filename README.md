## Ingest-Artifacts

This repo was created solely to store artifacts generated during the process of ingesting Dipper sources, as data is explored, modeled, transformed, and quality-assured. All issues and discussion realted to source data ingest should continue to live in the [main Dipper repo](https://github.com/monarch-initiative/dipper). 

In Ingest-Artifact repo here, each Dipper data source  will have its own directory to hold the following types of developer artifacts and documentation:  
  
 - _**Source Data Views:**_  Curated subsets or cleaned versions of source data that facilitate exploration and QA.
 - _**Python Notebooks:**_   Sharable, public notebooks set up for programmatic exploration of source data to be consumed by Dipper, or for QA of transformed Dipper outputs.
- _**Developer Cmaps:**_   Standardized diagrams that specify a target data model for a particular source, along with informal transform specifications for mapping source data to the target model.
 - _**Dipper test.ttl files:**_  Slim versions of each transformed data set that holds selected subset of records for QA and testing purposes.
 - _**Test Query Sets:**_   SPARQL or Cypher query sets used for exploration and QA of Dipper outputs. 
 - _**Public Documentation:**_  Draft versions of data model diagrams scoped for public consumption.
 
 -----------
 
 At present, certain ingest-related artifacts live elsewhere in the Dipper ecosystem. These include:
 - **Data QA Logs**: Google Docs used to track in-the-weeds developer exchanges about data testing and QA for a given source - currently live [here](https://drive.google.com/drive/u/0/folders/0ByKzIoedGeqJVHlxY0x5QXRVT0U).
 - **Term Translation Tables**: Text documents that hold all source-to-target concept and IRI mappings used to convert data for a given source - currently live in the main Dipper repo [here](https://github.com/monarch-initiative/dipper/tree/master/translationtable).
 - **Unit tests**: Automated scripts to test specific aspects of Dipper outputs. These will also live in the main dipper repo.
