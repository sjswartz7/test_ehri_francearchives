# ehri_francearchives_test
Data integration tests for the EHRI portal from open license FranceArchives portal 

This repository contains information about integrating the open license metadata from the FranceArchives metadata portal into the European Holocaust Research Infrastructure (EHRI) metadata portal. This information was compiled as part of an internship at Kazerne Dossin working with the EHRI data integration team in Spring 2024. It is intended to serve as a guideline and adaptable starting point for the EHRI data integration team, including future volunteers or interns, who are interested in pursuing further EHRI portal data integration of metadata from the FranceArchives collections. 

The FranceArchives metadata portal aggregates millions of sources from archives across France. As part of this research into which collections would be relevant to the EHRI portal, an in-depth search was conducted on the site using keywords and FranceArchives themes. A collection is considered relevant to the EHRI portal if there is at least one folder about the Holocaust, which is understood broadly per the International Holocaust Remembrance Alliance [IHRA](https://holocaustremembrance.com/) standards.

As an open-license site, FranceArchives allows for reuse with attribution via an [Etalab open license](https://etalab.gouv.fr/licence-ouverte-open-licence). 

## The following documentation is included in this repository:

- A list of relevant collections, selected per the IHRA's broad standards that a file should have at least one collection about the Holocaust to be considered a Holocaust collection. This compilation was thoroughly researched on the FranceArchives site based primarily on keyword/site theme searches, grouped by finding aid

- A list of search terms used on the FranceArchives site, some of which overlap with the site's [themes](https://francearchives.gouv.fr/fr/subjects)

- Preliminary mapping for RiC-O to EAD via the ECT at the collection level, using one regional archive as a test case

## Forthcoming documentation includes: 

- Instructions for retrieving RiC-O metadata in RDF/XML at the collection level via a SPARQL endpoint on the FranceArchives website
  
- SPARQL queries previously used on the FranceArchives site. These are evolving and will be improved over time while working with the endpoint

- Attribution for FranceArchives added via XSLT
  
- OAI-PMH instructions for retrieving EAD metadata at the collection level and importing it to the EHRI portal
  
- URL sets for specific regional archives

- Individual archives' XSLT mappings for the OAI-PMH URL sets added to the EHRI portal's EAD Conversion Tool (ECT). These are in-progress and future XSLT will vary and need adaptation depending on the archive.

- Direct download instructions for more limited RDF/XML metadata (last-resort option, not recommended)
