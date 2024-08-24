# DCHM Ontology Model 
This repository contains resources related to the thesis "Metadata Assessment and Enrichment: FAIRification of the University of Groningen Library's Digital Collection of Historical Maps". The thesis focuses on the University of Groningen (UG) Library's Special Collection's Digital Collection of Historical Maps (DCHM) and aims to assess and enrich its metadata through the FAIR principles.

## Contents

- **Original Metadata Records**: The `metadata_record.xml` file is the original metadata records exported from the UG Library's CONTENTdm Administration. 

- **DCHM Metadata**: The `DCHM.csv` file contains the original metadata for the DCHM. This file is derived from the xml file.

- **Data Processing & Analysis**: The `data_processing_analyzing.ipynb` file records some data processing and statistic analysis for metadata assessment. 

- **Conceptual Model**: The `conceptual_model` folder contains the ontology model developed for the UG Library's DCHM. This model includes the concepts used to structure the metadata of the historical maps in the digital collection.

- **RDF Implementation**: The `cartographical_heritage_ontology.rdf` file is an RDF implementation of the conceptual model. It represents metadata from 6 maps selected from the UG Library's DCHM, showcasing the most complete metadata available for these maps.

- **SPARQL Query Examples**: The `SPARQL.ipynb` Jupyter Notebook provides examples of SPARQL queries used to validate and query the RDF data based on the ontology model. These queries help demonstrate the utility and correctness of the implemented model.

- **SPARQL Endpoint**: You can access and query the RDF data through the following SPARQL endpoint: https://fuseki.devweb.rug.nl/#/dataset/DCHM/query.


- **Questionnaires**:
  - `questionnaire1.pdf` is the initial questionnaire with general questions.
  - `questionnaire2.pdf` is the second questionnaire with in-depth questions.

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). To view a copy of this license, see the [LICENSE.md](./LICENSE.md) file for details.
