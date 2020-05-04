# NHS Digital

This REPO is for the DEMO for NHS Digital. It holds the files that were provided by NHS and conversions to EDG graphs.
There is a dependency on the FHIR REPO content.

The Terminology Solution shall be able to handle, as a minimum, the following Code Systems (including their related ValueSets and ConceptMaps):
 •  SNOMED CT – including historical versions, - Bayer and bioportal indicate 10.5M.
 •  ICD10 – including historical versions -  I have it some where, need to find. 70K codes. Let’s say 1M
 •  OPCS4 – all versions - downloaded spreadsheets, 11K codes, a handful of values for each. Estimate 100K.
 •  READ codes (V2, V3 and CTV3) – including historical versions - downloaded, but conversion will take time, have text files. https://bioportal.bioontology.org/ontologies/RCD/?p=summary lists 140K READ v3 codes and 88K v2. This is a thesaurus with minimal amount of data. Estimate 1.5M.
 •  NICIP codes – including historical versions - downloaded spreadsheets, estimate 500K
 •  dm+d – including historical versions - I got access to data from https://isd.digital.nhs.uk/trud3/user/authenticated/group/0/pack/6/subpack/24/releases. Can’t estimate the size. It is all in XML. This is a directory of drugs. Assume to be similar to RxNorm.
 •  All published FHIR CodeSystems, and ValueSets and ConceptMaps (https://fhir.nhs.uk/ , https://fhir.hl7.org.uk/) - 341 code sets, a code set is like a reference dataset or an enumeration, majority with less than 10 values, but there are a few like languages and job roles that have up to 1K values. 4 triples per value. 100K is probably a generous estimate, but I only did sampling.
 •  Organisational Data – including historical versions - downloaded, it is in XML, need help estimating size.
 •  All Data Dictionary reference data and national codes – including historical versions (https://www.datadictionary.nhs.uk/ ) - asked a question, need help in estimating.
 •  UCUM (Unified Codes for Units of Measure) - I downloaded a table from https://www.cdisc.org/kb/article/ucum-and-cdisc-codelists, estimate under 200K
 •  Human Phenotype Ontology - 330K (edited) 
