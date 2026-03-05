| BRO Identifier New | BRO Class New [v.5.0.0] | Old class [v.4.1.1] | change |
| ------------- | ------------- | -------------| ------------- |
| R0001 | Resource | Resource | definition change |
| F1001 | Financial Resource | Funding Resource | rename and definition change |
| F2002 | Internal FR | - | new class added as subclass of Financial Resource |
| F2003 | Third Party FR | - | new class added as subclass of Financial Resource |
| F3004 | Public FR | - | new class added as subclass of Third Party FR |
| F4005 | Federal FR | Federal Funding Resource | change in hierarchy from Subclass of Financial Resource to Subclass of Public FR and definition change |
| F4006 | International FR | - | new class added as subclass of Public FR |
| F4007 | State FR | State Funding Resource | change in hierarchy from Subclass of Financial Resource to Subclass of Public FR and definition change |
| F3008 | Private FR | Private Funding Resource | change in hierarchy from Subclass of Financial Resource to Subclass of Third Party FR and definition change |
| F4009 | Institutional FR | - | new class added as subclass of Private FR |
| F4010 | Personal FR | - | new class added as subclass of Private FR |
| I1001 | Information Resource | Information Resource | definition change |
| I2002 | Semi-Structured IR | Semi-Structured Knowledge Resource | rename and definition change |
| - | - | Atlas | Subclass of Semi-Structured Knowledge Resource, deprecated because the level of detail is too specific |
| - | - | Bibliographic Resource | Subclass of Semi-Structured Knowledge Resource, deprecated because the level of detail is too specific |
| I2003 | Structured IR | Structured Knowledge Resource | rename and definition change |
| I3004 | Computational Model IR | Computational Model | definition change |
| - | - | Dynamic Model | Subclass of Computational Model, deprecated because the level of detail is too specific |
| - | - | Network Model | Subclass of Computational Model, deprecated because the level of detail is too specific |
| - | - | Interaction Network | Subclass of Network Model, deprecated because the level of detail is too specific |
| - | - | Protein-Protein Interaction | Subclass of Interaction Network, deprecated because the level of detail is too specific |
| - | - | Volume Model Scene Data | Subclass of Computational Model, deprecated because the level of detail is too specific |
| I3005 | Database IR | Database | definition change |
| - | - | Knowledgebase | Subclass of Structured IR, deprecated because there is no clear difference to Database IR |
| I4006 | noSQL DB | Object Database | rename and definition change |
| - | - | XML Database | Subclass of Object Database, deprecated because the level of detail is too specific |
| I4007 | SQL DB | Relational Database | rename and definition change |
| I3008 | Ontology IR | Ontology | definition change |
| I3009 | Repository IR | - | new class added as subclass of Structured IR |
| I3010 | Structured File IR | Structured File | definition change |
| - | - | Delimited Table | Subclass of Structured File, deprecated because the level of detail is too specific |
| - | - | Flatfile Distribution | Subclass of Structured File, deprecated because the level of detail is too specific |
| - | - | RDF Data | Subclass of Structured File, deprecated because the level of detail is too specific |
| - | - | XML Data | Subclass of Structured File, deprecated because the level of detail is too specific |
| I2011 | Unstructured IR | Unstructured Knowledge Resource | rename and definition change |
| I3012 | Audio IR | - | new class added as subclass of Unstructured IR |
| I3013 | Image IR | Image | definition change |
| I4014 | Three D Image IR | Three D Image | definition change |
| I4015 | Two D Image IR | Two D Image | definition change |
| I3016 | Narrative IR | Narrative Resource | change in hierarchy from Subclass of Information Resource to Subclass of Unstructured IR and definition change |
| - | - | Book | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Conference Proceeding | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Experimental Protocol | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Government Publication | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Journal Article | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | License | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Paper | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Patent | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Personal Communication | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Report | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Software Technology Protocol | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Standard Specification | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Thesis | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | Website | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| - | - | White Paper | Subclass of Narrative Resource, deprecated because the level of detail is too specific |
| I4017 | Published IR | - | new class added as subclass of Narrative IR |
| I5018 | Peer-reviewed IR | - | new class added as subclass of Published IR |
| I5019 | Unreviewed IR | - | new class added as subclass of Published IR |
| I4020 | Unpublished IR | - | new class added as subclass of Narrative IR |
| I3021 | Video IR | - | new class added as subclass of Unstructured IR |
| - | - | Portal | Subclass of Information Resource, deprecated because there is no clear difference to Database IR |
| - | - | Data Resource | Subclass of Information Resource, deprecated because there is no clear difference between Data Resource and Information Resource |
| - | - | Clinical Care Data | Subclass of Data Resource, deprecated because it can be incorporated in the existing Subclasses of Information Resource |
| - | - | Aggregate Human Data | Subclass of Clinical Care Data, deprecated because Parentclass deprecated |
| - | - | Individual Human Data | Subclass of Clinical Care Data, deprecated because Parentclass deprecated |
| - | - | Clinical Research Data | Subclass of Data Resource, deprecated because it can be incorporated in the existing Subclasses of Information Resource |
| - | - | Molecular and Cellular Data | Subclass of Data Resource, deprecated because it can be incorporated in the existing Subclasses of Information Resource |
| - | - | Gene Expression | Subclass of Molecular and Cellular Data, deprecated because Parentclass deprecated |
| - | - | Molecular Interaction | Subclass of Molecular and Cellular Data, deprecated because Parentclass deprecated |
| - | - | Phenotypic Measurement | Subclass of Molecular and Cellular Data, deprecated because Parentclass deprecated |
| - | - | Protein Expression | Subclass of Molecular and Cellular Data, deprecated because Parentclass deprecated |
| M1001 | Material Resource | Material Resource | definition change |
| M2002 | Living MR | - | new class added as subclass of Material Resource |
| M3003 | Animal MR | - | new class added as subclass of Living MR |
| M4004 | Human MR | - | new class added as subclass of Animal MR |
| M3005 | Bacterial MR | - | new class added as subclass of Living MR |
| M3006 | Fungal MR | - | new class added as subclass of Living MR |
| M3007 | Plant MR | - | new class added as subclass of Living MR |
| M3008 | Viral MR | - | new class added as subclass of Living MR |
| M2009 | Non-living MR | - | new class added as subclass of Material Resource |
| P1001 | People Resource | People Resource | definition change |
| P2002 | Private PR | - | new class added as subclass of People Resource |
| P2003 | Professional PR | - | new class added as subclass of People Resource |
| P3004 | Administrative Expertise PR | - | new class added as subclass of Professional PR |
| P3005 | Clinical Expertise PR | - | new class added as subclass of Professional PR |
| P3006 | Data Management Expertise PR | - | new class added as subclass of Professional PR |
| P3007 | Document Writing Expertise PR | - | new class added as subclass of Professional PR |
| P3008 | Financial Expertise PR | Grant Preparation Expertise | change in hierarchy from Subclass of People Resource to Subclass of Professional PR and definition change |
| P3009 | Industrial Expertise PR | Industry Partnership Expertise | change in hierarchy from Subclass of People Resource to Subclass of Professional PR and definition change |
| P3010 | Research Expertise PR | - | new class added as subclass of Professional PR |
| P3011 | Software Development Expertise PR | - | new class added as subclass of Professional PR |
| - | - | Pharmacokinetics Pharmacodynamics Expertise | Subclass of Professional PR, deprecated because it was summed into Research Expertise PR (P3010) |
| - | - | Pharmacokinetics Pharmacodynamics Expertise | Subclass of Professional PR, deprecated because it was summed into Research Expertise PR (P3010) |
| - | - | Protocol Development Expertise | Subclass of Professional PR, deprecated because it was summed into Research Expertise PR (P3010) |
| - | - | Psychometrics Expertise | Subclass of Professional PR, deprecated because it was summed into Research Expertise PR (P3010) |
| - | - | Toxicology Expertise | Subclass of Professional PR, deprecated because it was summed into Research Expertise PR (P3010) |

**ab hier @en ergänzen, in ttl, da super nervig in protege**
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |








