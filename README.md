# DCHM Ontology Model 
This repository contains resources related to the thesis "Metadata Assessment and Enrichment: FAIRification of the University of Groningen Library's Digital Collection of Historical Maps". The thesis focuses on the University of Groningen (UG) Library's Special Collection's Digital Collection of Historical Maps (DCHM) and aims to assess and enrich its metadata through the FAIR principles.

## Contents

-**Original Metadata Records**: The `metadata_record.xml` file is the original metadata records exported from the UG Library's CONTENTdm Administration. 

- **DCHM Metadata**: The `DCHM.csv` file contains the original metadata for the DCHM. This file is derived from the xml file. 

- **Conceptual Model**: The `conceptual_model` folder contains the ontology model developed for the UG Library's DCHM. This model includes the concepts used to structure the metadata of the historical maps in the digital collection.

- **RDF Implementation**: The `cartographical_heritage_ontology.rdf` file is an RDF implementation of the conceptual model. It represents metadata from 6 maps selected from the UG Library's DCHM, showcasing the most complete metadata available for these maps.

- **SPARQL Query Examples**: The `SPARQL.ipynb` Jupyter Notebook provides examples of SPARQL queries used to validate and query the RDF data based on the ontology model. These queries help demonstrate the utility and correctness of the implemented model.
