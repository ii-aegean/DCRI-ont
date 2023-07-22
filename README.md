# Ontology for the decision-making of conservation and restoration intervention of Cultural Heritage

The ontology represents the expert’s knowledge related to the decision-making process of the conservation and restoration interventions (CnR-DM-I). It consists of three modules:
• DCRI ont, which directly imports CIDOC CRM [https://www.cidoc-crm.org/versions-of-the-cidoc-crm], CRMsci [https://cidoc-crm.org/crmsci/fm_releases], CIDOC CRM extension about typed properties and negative typed properties [https://github.com/linked-conservation-data/crmntp], and SKOS [https://www.w3.org/2009/08/skos-reference/skos.html] and extends them with classes and properties related to the CnR-DM-I domain. It includes all the necessary classes and properties for the representation of CnR-DM-I domain.
• DCRI voc, which directly imports SKOS and includes individuals which express types of different basic concepts of the CnR-DM-I domain (e.g., types of materials, types of CnR interventions, types of damages). While it has been developed in order to be used as part of the ontology, it can also be used independent of it, as a SKOS vocabulary for the CnR-DM-I domain.
• DCRI ont special, which directly imports DCRI ont and DCRI voc and indirectly imports CIDOC CRM, CRMsci, CIDOC CRM extension about typed properties and negative typed properties, and SKOS. This special module extends DCRI ont with classes and properties required for the case study. It also includes the individ-uals related to the case study which constitute the A-box knowledge of the model, i.e., the individuals of the different plans, supplies, options, intrinsic requirements.


DCRI ont IRI: http://w3id.org/dcri-ont
DCRI ont proposed prefix: dcri-ont
DCRI ont documentation:https://ii-aegean.github.io/dcri-ont-doc/

DCRI voc IRI: http://w3id.org/dcri-voc
DCRI voc proposed prefix: dcri-voc
DCRI voc documentation:https://ii-aegean.github.io/dcri-voc-doc/

DCRI ont special IRI: http://w3id.org/dcri-ont-spe
DCRI ont special proposed prefix: dcri-ont-spe
DCRI ont special:https://ii-aegean.github.io/dcri-ont-spe-doc/
---
