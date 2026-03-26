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
| S1001 | Service Resource | Service Resource | definition change |
| S2002 | Core Facility | Facility Core | rename and definition change |
| S3003 | Animal Facility | Research Animals Facility | rename and definition change |
| - | - | Animal Care Facility | Subclass of Animal Facility, deprecated because the level of detail is too specific |
| - | - | Animal Models Facility | Subclass of Animal Facility, deprecated because the level of detail is too specific |
| S3004 | Biosafety Level Facility | Biosafety Level Facility | definition change |
| S3005 | Cell Biology Facility | Cell Biology Facility | definition change |
| - | - | Cell Culture Facility | Subclass of Cell Biology Facility, deprecated because the level of detail is too specific |
| - | - | Cell Processing Clean Room Facility | Subclass of Cell Biology Facility, deprecated because the level of detail is too specific |
| - | - | Flow Cytometry Cell Sorting Facility | Subclass of Cell Biology Facility, deprecated because the level of detail is too specific |
| - | - | Gene Therapy Facility | Subclass of Cell Biology Facility, deprecated because the level of detail is too specific |
| - | - | Immune Monitoring Facility | Subclass of Cell Biology Facility, deprecated because the level of detail is too specific |
| - | - | Microscopy Facility | Subclass of Cell Biology Facility, deprecated because the level of detail is too specific |
| - | - | Stem Cell Therapy Facility | Subclass of Cell Biology Facility, deprecated because the level of detail is too specific |
| S3006 | Fabrication Facility | Fabrication Facility | definition change |
| S3007 | Imaging Facility | Imaging Facility | defintion change |
| S3008 | Molecular Biology Facility | Molecular Biology Facility | definition change |
| - | - | Biomolecular Interaction Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | Genomics Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | Metabolomics Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | Monoclonal Antibody Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | NMR Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | PCR Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | Proteomics Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | Radioisotopes Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| - | - | X-Ray Crystallography Facility | Subclass of Molecular Biology Facility, deprecated because the level of detail is too specific |
| S3009 | Physiology Facility | Physiology Facility | definition change |
| - | - | Cardiovascular Facility | Subclass of Physiology Facility, deprecated because the level of detail is too specific |
| - | - | Exercise Study Facility | Subclass of Physiology Facility, deprecated because the level of detail is too specific |
| - | - | Metabolism Facility | Subclass of Physiology Facility, deprecated because the level of detail is too specific |
| - | - | Neurological Facility | Subclass of Physiology Facility, deprecated because the level of detail is too specific |
| - | - | Nutrition Facility | Subclass of Physiology Facility, deprecated because the level of detail is too specific |
| - | - | Sleep Study Facility | Subclass of Physiology Facility, deprecated because the level of detail is too specific |
| S3010 | Tissue Organ Facility | Tissue Organ Facility | definition change |
| - | - | Biobank Facility | Subclass of Tissue Organ Facility, deprecated because the level of detail is too specific |
| - | - | Immunohistochemistry Facility | Subclass of Tissue Organ Facility, deprecated because the level of detail is too specific |
| - | - | Micro Dissection Facility | Subclass of Tissue Organ Facility, deprecated because the level of detail is too specific |
| - | - | Phlebotomy Facility | Subclass of Tissue Organ Facility, deprecated because the level of detail is too specific |
| - | - | Material Service | Subclass of Service Resource, deprecated because there is no clear difference to Core Facility |
| - | - | Antibody Production | Subclass of Material Service, deprecated because the level of detail is too specific |
| - | - | Biomaterial Manufacture | Subclass of Material Service, deprecated because the level of detail is too specific |
| - | - | Instrument Manufacture | Subclass of Material Service, deprecated because the level of detail is too specific |
| - | - | Pathology Laboratory Screening | Subclass of Material Service, deprecated because the level of detail is too specific |
| - | - | Reagent Manufacture | Subclass of Material Service, deprecated because the level of detail is too specific |
| S2011 | Data Management SR | - | new class added as subclass of Service Resource |
| - | - | Data Storage Service | Subclass of Service Resource, deprecated because it is included in Data Management SR |
| S2012 | Material Storage SR | Material Storage Service | definition change |
| S2013 | Regulatory Compliance SR | Regulatory Compliance Resource | definition change |
| - | - | Animal Compliance Resource | Subclass of Regulatory Compliance SR, deprecated because the level of detail is too specific |
| - | - | Conflict of Interest Resource | Subclass of Regulatory Compliance SR, deprecated because the level of detail is too specific |
| - | - | Environmental Health and Safety Resource | Subclass of Regulatory Compliance SR, deprecated because the level of detail is too specific |
| - | - | Human Embryonic Stem Cell Resource | Subclass of Regulatory Compliance SR, deprecated because the level of detail is too specific |
| - | - | Human Studies Compliance Resource | Subclass of Regulatory Compliance SR, deprecated because the level of detail is too specific |
| - | - | Intellectual Property Resource | Subclass of Regulatory Compliance SR, deprecated because the level of detail is too specific |
| - | - | Regulatory Policy Resource | Subclass of Regulatory Compliance SR, deprecated because the level of detail is too specific |
| S2014 | Technical Support SR | Technical Support | definition change |
| S3015 | Computational SR | Computational Service | change in hierarchy from Subclass of Service Resource to Subclass of Technical Support SR and definition change |
| - | - | Backup Archive Service | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Behavorial Analysis Service | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Biomaterial Analysis Service | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Data Computation Service | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Data Service | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Calendar Schedule and Resource Management | Subclass of Data Service, deprecated because Parentclass deprecated |
| - | - | Identity Management | Subclass of Data Service, deprecated because Parentclass deprecated |
| - | - | Authentication | Subclass of Identity Management, deprecated because Parentclass deprecated |
| - | - | Authorization | Subclass of Identity Management, deprecated because Parentclass deprecated |
| - | - | Disaster Recovery Service | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Grid Computing | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Hosting | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Computational Hosting | Subclass of Hosting, deprecated because Parentclass deprecated |
| - | - | Database Hosting | Subclass of Hosting, deprecated because Parentclass deprecated |
| - | - | Integrated Hosting | Subclass of Hosting, deprecated because Parentclass deprecated |
| - | - | Website Hosting | Subclass of Hosting, deprecated because Parentclass deprecated |
| - | - | Material Analysis Service | Subclass of Computational SR, deprecated because the level of detail is too specific |
| - | - | Network and Communication | Subclass of Computational SR, deprecated because the level of detail is too specific |
| S3016 | Repair SR | - | new class added as subclass of Technical Support SR |
| S2017 | Training SR | Training Service | definition change |
| - | - | Training Resource | Subclass of Resource, deprecated because there is no clear difference to Training SR |
| - | - | Certificate Program | Subclass of Training Resource, deprecated because the level of detail is too specific |
| - | - | Continuing Medical Education | Subclass of Training Resource, deprecated because the level of detail is too specific |
| - | - | Outreach Program | Subclass of Training Resource, deprecated because the level of detail is too specific |
| - | - | Seminar Service | Subclass of Training Resource, deprecated because the level of detail is too specific |
**ab hier @en ergänzen, in ttl, da super nervig in protege**


Deprecate classs from Software:
|  |  |  |  |
| - | - | Algorithm | Subclass of *Software*, deprecated because it is not a software |
| - | - | Graph Algorithm | Subclass of Algorithm, deprecated because Parentclass deprecated |
| - | - | Centrality Analysis | Subclass of Graph Algorithm, deprecated because Parentclass deprecated |
| - | - | Community Structure Analysis | Subclass of Graph Algorithm, deprecated because Parentclass deprecated |
| - | - | Graph Alignment | Subclass of Graph Algorithm, deprecated because Parentclass deprecated |
| - | - | Approximate Graph Alignment | Subclass of Graph Alignment, deprecated because Parentclass deprecated |
| - | - | Graph Analysis | Subclass of Graph Algorithm, deprecated because Parentclass deprecated |
| - | - | Image Algorithm | Subclass of Algorithm, deprecated because Parentclass deprecated |
| - | - | Computational Geometry | Subclass of Image Algorithm, deprecated because Parentclass deprecated |
| - | - | Feature Analysis | Subclass of Computational Geometry, deprecated because Parentclass deprecated |
| - | - | Pattern Recognition | Subclass of Computational Geometry, deprecated because Parentclass deprecated |
| - | - | Shape Analysis | Subclass of Computational Geometry, deprecated because Parentclass deprecated |
| - | - | Convolution | Subclass of Image Algorithm, deprecated because Parentclass deprecated |
| - | - | Fast Fourier Transform | Subclass of Image Algorithm, deprecated because Parentclass deprecated |
| - | - | Image Reconstruction | Subclass of Image Algorithm, deprecated because Parentclass deprecated |
| - | - | Numerical Method | Subclass of Algorithm, deprecated because Parentclass deprecated |
| - | - | Linear Algebra Tool | Subclass of Numerical Method, deprecated because Parentclass deprecated |
| - | - | Monte Carlo Simulation | Subclass of Numerical Method, deprecated because Parentclass deprecated |
| - | - | Numerical Integrator | Subclass of Numerical Method, deprecated because Parentclass deprecated |
| - | - | Optimizer | Subclass of Numerical Method, deprecated because Parentclass deprecated |
| - | - | PDE Solver | Subclass of Numerical Method, deprecated because Parentclass deprecated |
| - | - | Root Finder | Subclass of Numerical Method, deprecated because Parentclass deprecated |
| - | - | Searching Sorting and Indexing | Subclass of Algorithm, deprecated because Parentclass deprecated |
| - | - | Document Retrieval | Subclass of Searching Sorting and Indexing, deprecated because Parentclass deprecated |
| - | - | Mass Spectra Identification | Subclass of Searching Sorting and Indexing, deprecated because Parentclass deprecated |
| - | - | Sequence Alignment | Subclass of Searching Sorting and Indexing, deprecated because Parentclass deprecated |
| - | - | Statistical Algorithm | Subclass of Algorithm, deprecated because Parentclass deprecated |
| - | - | Hypothesis Testing Algorithm | Subclass of Statistical Algorithm, deprecated because Parentclass deprecated |
| - | - | Model Fitting Algorithm | Subclass of Statistical Algorithm, deprecated because Parentclass deprecated |
| - | - | Pattern Inference Algorithm | Subclass of Statistical Algorithm, deprecated because Parentclass deprecated |
| - | - | Symbolic and Analytic Model | Subclass of Algorithm, deprecated because Parentclass deprecated |
| - | - | Model with Closed Form Solution | Subclass of Symbolic and Analytic Model, deprecated because Parentclass deprecated |

under Data Analysis Software:
| - | - | Data Mining and Inference | Subclass of *Data Analysis Software*, deprecated because the level of detail is too specific |
| - | - | Inference from Data | Subclass of Data Mining and Inference, deprecated because Parentclass deprecated |
| - | - | Pattern and Motif Inference | Subclass of Inference from Data, deprecated because Parentclass deprecated |
| - | - | Signaling Network Reconstruction | Subclass of Inference from Data, deprecated because Parentclass deprecated |
| - | - | Information Retrieval | Subclass of Data Mining and Inference, deprecated because Parentclass deprecated |
| - | - | Text Mining | Subclass of Data Mining and Inference, deprecated because Parentclass deprecated |
| - | - | Knowledge Extraction | Subclass of Text Mining, deprecated because Parentclass deprecated |
| - | - | Statistical Text Analysis | Subclass of Text Mining, deprecated because Parentclass deprecated |
| - | - | Genomic Phenotypic Analysis | Subclass of *Data Analysis Software*, deprecated because the level of detail is too specific |
| - | - | Network Characterization | Subclass of Genomic Phenotypic Analysis, deprecated because Parentclass deprecated |
| - | - | Regulatory Signaling Network Reconstruction | Subclass of Genomic Phenotypic Analysis, deprecated because Parentclass deprecated |
| - | - | Sequence Annotation | Subclass of Genomic Phenotypic Analysis, deprecated because Parentclass deprecated |
| - | - | Sequence Similarity Searching | Subclass of Genomic Phenotypic Analysis, deprecated because Parentclass deprecated |
| - | - | **Natural Language Processing** | Subclass of *Data Analysis Software*, deprecated because the level of detail is too specific |
| - | - | Language Summarization | Subclass of Natural Language Processing, deprecated because Parentclass deprecated |
| - | - | Parsing | Subclass of Natural Language Processing, deprecated because Parentclass deprecated |
| - | - | Deep Parsing | Subclass of Parsing, deprecated because Parentclass deprecated |
| - | - | Document Structure Parsing | Subclass of Parsing, deprecated because Parentclass deprecated |
| - | - | Lexical Analysis | Subclass of Parsing, deprecated because Parentclass deprecated |
| - | - | Named Entity Normalization | Subclass of Parsing, deprecated because Parentclass deprecated |
| - | - | Named Entity Recognition | Subclass of Parsing, deprecated because Parentclass deprecated |
| - | - | Partial Parsing | Subclass of Parsing, deprecated because Parentclass deprecated |
| - | - | Sentence Splitting | Subclass of Parsing, deprecated because Parentclass deprecated |
| - | - | Phenotype Management | Subclass of *Data Analysis Software*, deprecated because the level of detail is too specific |
| - | - | Signal Processing | Subclass of *Data Analysis Software*, deprecated because the level of detail is too specific |
| - | - | Averaging and Agglomeration | Subclass of Signal Processing, deprecated because Parentclass deprecated |
| - | - | Data Normalization | Subclass of Signal Processing, deprecated because Parentclass deprecated |
| - | - | Outlier Detection and Removal | Subclass of Signal Processing, deprecated because Parentclass deprecated |
| - | - | Regularization and Smoothing | Subclass of Signal Processing, deprecated because Parentclass deprecated |
| - | - | Time Series Analysis | Subclass of Signal Processing, deprecated because Parentclass deprecated |
| - | - | Statistical Analysis | Subclass of *Data Analysis Software*, deprecated because the level of detail is too specific |
| - | - | Statistical Package | Subclass of Statistical Analysis, deprecated because Parentclass deprecated |

under Image Processing:
| - | - | Analysis of Gel-Electrophoresis | Subclass of *Image Processing*, deprecated because the level of detail is too specific |
| - | - | Atlas Generation | Subclass of *Image Processing*, deprecated because the level of detail is too specific |
| - | - | Cortical Modeling | Subclass of *Image Processing*, deprecated because the level of detail is too specific |
| - | - | Exploratory Data Analysis | Subclass of *Image Processing*, deprecated because the level of detail is too specific |
| - | - | Pre-Processing | Subclass of *Image Processing*, deprecated because the level of detail is too specific |
| - | - | Data Transform | Subclass of Pre-Processing, deprecated because Parentclass deprecated |
| - | - | Spectral Transform | Subclass of Data Transform, deprecated because Parentclass deprecated |
| - | - | Fourier Transform | Subclass of Spectral Transform, deprecated because Parentclass deprecated |
| - | - | Wavelet Transform | Subclass of Spectral Transform, deprecated because Parentclass deprecated |
| - | - | Filtering | Subclass of Pre-Processing, deprecated because Parentclass deprecated |
| - | - | Inhomogenity Correction | Subclass of Pre-Processing, deprecated because Parentclass deprecated |
| - | - | Skull Stripping | Subclass of Pre-Processing, deprecated because Parentclass deprecated |
| - | - | Registration | Subclass of *Image Processing*, deprecated because the level of detail is too specific |
| - | - | Segmentation | Subclass of *Image Processing*, deprecated because the level of detail is too specific |

under Data Transfer and Communication:
| - | - | Communication Interface | Subclass of *Data Transfer and Communication*, deprecated because the level of detail is too specific |
| - | - | Dissemination Vehicle | Subclass of *Data Transfer and Communication*, deprecated because the level of detail is too specific |
| - | - | Education | Subclass of Dissemination Vehicle, deprecated because Parentclass deprecated |
| - | - | Course Material | Subclass of Education, deprecated because Parentclass deprecated |
| - | - | Tutorial | Subclass of Education, deprecated because Parentclass deprecated |
| - | - | Web Posting | Subclass of Dissemination Vehicle, deprecated because Parentclass deprecated |
| - | - | News | Subclass of Web Posting, deprecated because Parentclass deprecated |
| - | - | Online Course | Subclass of Web Posting, deprecated because Parentclass deprecated |

under Data Integration and Interoperability Tool:
| - | - | Pipeline Manager | Subclass of *Data Integration and Interoperability Tool*, deprecated because the level of detail is too specific |
| - | - | Graphical Processing Workflow Environments | Subclass of Pipeline Manager, deprecated because Parentclass deprecated |
| - | - | Processing Pipeline | Subclass of Pipeline Manager, deprecated because Parentclass deprecated |
| - | - | Workbench | Subclass of *Data Integration and Interoperability Tool*, deprecated because the level of detail is too specific |

in Interactive Tool:
| - | - | Interactive Tool | Subclass of *Software*, deprecated because it is a feature and not a specification |
| - | - | Communication and Collaborative Work | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Data Editor | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Graphical Composition | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Interactive Network Analysis | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Interactive Web-Based Tool | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Bug Reporting | Subclass of Interactive Web-Based Tool, deprecated because Parentclass deprecated |
| - | - | Feature Request | Subclass of Interactive Web-Based Tool, deprecated because Parentclass deprecated |
| - | - | Mailing List | Subclass of Interactive Web-Based Tool, deprecated because Parentclass deprecated |
| - | - | Online Support | Subclass of Interactive Web-Based Tool, deprecated because Parentclass deprecated |
| - | - | Knowledge Mining and Capturing | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Software Development Resource | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Software Development Tool | Subclass of Software Development Resource, deprecated because Parentclass deprecated |
| - | - | Code Profiler | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Code Testing Framework | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Compiler | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Cross-Language Wrapping | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Cross-Plattform Tool | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Document Generation | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Documentation Generation | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Integration | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Application Programming Interface | Subclass of Integration, deprecated because Parentclass deprecated |
| - | - | Graphical Integration | Subclass of Integration, deprecated because Parentclass deprecated |
| - | - | Mapper | Subclass of Integration, deprecated because Parentclass deprecated |
| - | - | Resource Integration Component | Subclass of Integration, deprecated because Parentclass deprecated |
| - | - | Ontology Development and Management | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Data Annotation | Subclass of Ontology Development and Management, deprecated because Parentclass deprecated |
| - | - | Ontology Development | Subclass of Ontology Development and Management, deprecated because Parentclass deprecated |
| - | - | Ontology Diff and Alignment | Subclass of Ontology Development and Management, deprecated because Parentclass deprecated |
| - | - | Ontology Visualization | Subclass of Ontology Development and Management, deprecated because Parentclass deprecated |
| - | - | Programmatic Access | Subclass of Ontology Development and Management, deprecated because Parentclass deprecated |
| - | - | Web Access | Subclass of Ontology Development and Management, deprecated because Parentclass deprecated |
| - | - | Software Development Environment | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Source Control | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Testing Tools | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Version Source Control System | Subclass of Software Development Tool, deprecated because Parentclass deprecated |
| - | - | Software Engineering Tool | Subclass of Software Development Resource, deprecated because Parentclass deprecated |
| - | - | Visualization | Subclass of Interactive Tool, deprecated because Parentclass deprecated |
| - | - | Data Exploration | Subclass of Visualization, deprecated because Parentclass deprecated |
| - | - | Graph Viewer | Subclass of Visualization, deprecated because Parentclass deprecated |
| - | - | Hyperbolic Graph | Subclass of Graph Viewer, deprecated because Parentclass deprecated |
| - | - | Hierarchical Tree | Subclass of Hyperbolic Graph, deprecated because Parentclass deprecated |
| - | - | Heat Map | Subclass of Visualization, deprecated because Parentclass deprecated |
| - | - | Imaging | Subclass of Visualization, deprecated because Parentclass deprecated |
| - | - | Cross-Sectional Viewer | Subclass of Imaging, deprecated because Parentclass deprecated |
| - | - | Manifold Viewer | Subclass of Imaging, deprecated because Parentclass deprecated |
| - | - | Sequence Visualization | Subclass of Visualization, deprecated because Parentclass deprecated |
| - | - | Workbench | Subclass of Interactive Tool, deprecated because Parentclass deprecated |

under Modeling and Simulation:
| - | - | Finite Element Model | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
| - | - | Interaction Modeling | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
| - | - | Protein Interaction Modeling | Subclass of Interaction Modeling, deprecated because Parentclass deprecated |
| - | - | Mesh Model | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
| - | - | Numerical Model | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
| - | - | Physico-Chemical Model | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
| - | - | Cell Model | Subclass of Physico-Chemical Model, deprecated because Parentclass deprecated |
| - | - | Mechanical Simulation | Subclass of Physico-Chemical Model, deprecated because Parentclass deprecated |
| - | - | Contact Modelling | Subclass of Mechanical Simulation, deprecated because Parentclass deprecated |
| - | - | Continuum Method Simulation | Subclass of Mechanical Simulation, deprecated because Parentclass deprecated |
| - | - | Controllers | Subclass of Mechanical Simulation, deprecated because Parentclass deprecated |
| - | - | Meshing | Subclass of Mechanical Simulation, deprecated because Parentclass deprecated |
| - | - | Molecular Force Field Calculator | Subclass of Mechanical Simulation, deprecated because Parentclass deprecated |
| - | - | Multibody Dynamics | Subclass of Mechanical Simulation, deprecated because Parentclass deprecated |
| - | - | Molecular Model | Subclass of Physico-Chemical Model, deprecated because Parentclass deprecated |
...
| - | - | Network Interaction Model | Subclass of Physico-Chemical Model, deprecated because Parentclass deprecated |
| - | - | Physiological Model | Subclass of Physico-Chemical Model, deprecated because Parentclass deprecated |

| - | - | Random Number Simulation | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
| - | - | Structural Model | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
| - | - | Wavelet Model | Subclass of *Modeling and Simulation*, deprecated because the level of detail is too specific |
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








