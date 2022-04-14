# MIMIC-III-With-Semantic-Enrichment
Complementary files for the MIMIC-III data set, with the patient's information semantic annotated to target ontologies.

On the work (https://github.com/Jeffreylin0925/MIMIC-III_ICU_Readmission_Analysis), the authors make a patient-oriented set, where each patient, based on the MIMIC-III data set, has all the instances that describe the stay. Our work, performs a semantic enrichment of the information, resulting is a richer data set where each patient not only has the instances that describe the stay, buy also has annotations for the ontologies that best describe the information. Providing interconnectivity and access to the relations and hierarchies of the instances. With this, our new files that enrich the patient's information will be shown here. 

Additionally, and based on this semantically enriched information’s, embeddings are made for each prediction scenario desired. These can be couples with the semantically enriched information and replace the original embeddings on the (https://github.com/Jeffreylin0925/MIMIC-III_ICU_Readmission_Analysis).

This set is structured as such:
  - The folders correspond to the patient's ID on the MIMIC-III data set, and ca be obtained running the code on https://github.com/Jeffreylin0925/MIMIC-III_ICU_Readmission_Analysis.
  - Each patient’s folder as files that contain the enriched information for each set of features of the MIMIC-III, as well as files to make predictions according to an ICU stay timeline.
  - The embeddings folders have the files needed for the different predictions scenarios. These scenarios are named on the folders that contain the embeddings and are to be used together with the proper annotations.
