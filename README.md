# ehr_xml
A pydantic data model of the clinical contents of the registry, with an XML output. XSD generated by Visual Studio.
Current version 0.3.

Roadmap:
- **0.1 Working proof of concept**
- **0.2 Input current working dictionary for registry**
- **0.3 Working XSD output**
- 0.35 XSD / XML with correct namespaces
- 0.4 Further consolidation with archetypes
- 0.41 Correct [a..b] boundeds + (not) required fields in XSD
- 0.5 Consolidation with existing Datamart Head & Neck evaluation + admission
- 0.51 Can use data model workflow to import XML from Datamart (for another repo)
- 0.6 Inclusion of other head & neck documents
- 0.7 Iteration towards common data model
- 0.8 Inclusion of Sarcoma, breast, ... and other ready tumor groups
- 0.9 Code / network tests
- 1.0 Production release