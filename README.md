## Extension "FrNonMetricTraits" for RDFBones-O
This is an RDFBones extension for the documentation of non-metric traits. The 14 cranial and mandibular non-metric traits are a subset of the non-metric traits included in the data entry form used at Biological Anthropology Freiburg and described in Saunders & Rainey 2008. The English translations are according to the terminology of Hauser and DeStefano 1989. The traits included in FrNonMetricTraits were recorded for skulls from the Alexander Ecker Collection in order to deal with repatriation claims. For further information on the Alexander Ecker Collection cf. Kästner et al. 2011.

Furthermore, FrNonMetricTraits is enriched with detailed descriptions of the non-metric traits: the definitions from Hauser & DeStefano 1989 were added as descriptions to the assay specifications. Thus, FrNonMetricTraits is more than just a spreadsheet for data entry: FrNonMetricTraits documents the whole investigation process and thereby contributes to transparency and repeatability of anthropological investigations. 

## Wiki index
The FrNonMetricTraits wiki provides a thorough documentation of the ontology - you find it here: https://github.com/RDFBones/FrNonMetricTraits/wiki The structure of the FrNonMetricTraits ontology is based on the concept of RDFBones extensions first elaborated in the extension FrSexEst. The wiki covers the following topics:
* Anthropological background
* General structure of FrNonMetricTraits
* Investigation planning
     - Study design
* Study design execution
     - Specimen collection
     - Data collection
* Conclusion

## References
Hauser, G., & De Stefano, G. F. (1989). Epigenetic variants of the human skull.

Kästner, M., Ortolf, S., Rüdell, A., Möller, D., & Wittwer-Backofen, U. (2011). The Alexander Ecker Collection in Freiburg. Documenta Archaeobiologiae, 8, 275-284.

Katzenberg, M. A., & Saunders, S. R. (Eds.). (2008). Biological anthropology of the human skeleton. John Wiley & Sons.



For future development
* Add a secondary skeletal inventory which consists of non-metric traits so that inca bones can be recorded and selected as input of the specimen collection process instead of the Neurocranium which is in RDFBones-O an anatomical term and not a physical bone region
* The 'has characteristic' data property was defined exclusively for FrNonMetricTraits to relate integers to categorical (!) measurement data; there might be a more elegant solution
* The conclusion class is irrelevant for FrNonMetricTraits investigations but cannot be omitted due to the RDFBones software at the moment
* Cardinality restrictions could be used more often (for parts of study design execution and investigation, for instance) if the environment for the RDFBones software would evaluate them correctly
