# MADICES 2: First pre-event meeting
- Date: 2023-12-11, 16:00 Europe/Berlin
- 18 people present.

## Agenda
1. Introductions by organisers (Matthew, Peter, Edan, Kevin)
2. Housekeeping:
    - Final dates: April 22nd - 25th
    - Final location: ZUSE Institute, Berlin
      
3. Quick rundown of the "Motivating questions":  
- What tools do we use to facilitate data interoperability:
    - Simon Stier: 2 problems:
      - getting everything into RDF,
      - limiting degrees of freedom within RDF
      - (several attendees indicated that they use RDF)
    - Nicolas Carpi: point of view of a web-app-developer
      - doesn't use RDF - tries to stay away from it
      - uses JSON-LD and ELN File Format
    - Matthew Evans:
      - bringing RDF experts in touch with people who don't use it / know how to use it would be useful for the workshop
    - Eibar Flores:
      - RDF might be a good infrastructure tool, but not useful for end-users
    - Samantha Pearman-Kanza:
      - value of RDF or JSON-LD depends on use case
    - Simon Stier:
      - nobody wants to touch XML if it's not necessary
      - RDF can be serialised into JSON-LD instead of XML
      - maybe a community standard would be a good outcome for 
    - Matthew Evans:
      - among those present, majority (~10) are not only working on data infrastructure, but also on producing data
        
- What format do we use for our metadata schemas? Is it a form of RDF? Is it ontologized?
    - Matthew Evans:
      - does anyone present use anything (extension etc.) they already know cannot be translated using/into RDF?
    - Samantha Pearman-Kanza:
      - main issue with XML is the bloat
    - Simon Stier:
      - one doesn't have to implement everything in RDF, partial adoption is useful
    - Matthew Evans:
      - having a data exchange format as a json
    - Giovanni Pizzi: Materials Cloud and AiiDA point of view:
      - AiiDA doesn't use RDF, but its adoption can be explored
      - linking of experimental & computational is crucial
      - Suggestion: What can be done in 3 days in person? What practical outcome can we achieve?
    - Eibar Flores:
      - Suggestion: Building a knowledge base - datasets, formats, metadata from multiple tools
    - Adam Laskowski: openBIS
      - RDF support is planned
    - Simon Stier: The ELN Consortium
      - good starting point, JSON-LD / RDF based
      - currently only very generic attributes
    - Pepe Marquez: FAIRmat / NOMAD
      - specific interfaces (with e.g. eLabFTW and openBIS) are being implemented
      - soft links to schemas
    - Jessica Nash: MolSSI
      - software interoperability as opposed to data interoperability
      - interested in integrating tools developed at MolSSI
    - Aleksandr Yakutovich: AiiDAlab
      - big challenge is organisation of (experimental) data - in any way!
      - interested in knowing what the best standards in data organisation are
    - Michael Liebau: NFDI4cat
      - goal: make all German catalysis data interoperable
      - ELNs are rarely used in catalysis
      - ontologies are developed, but 
      - connection points between softwares
    - Julia Schumann: FAIRmat
      - focus on catalysis data
      - allowing user-facing issues in NOMAD: searching catalysts, finding well performing ones, etc.
    - Carlo Pignedoli: Empa
      - combination of experiments and simulations
      - starting point in his lab is good provenance tracking of data
      - difficulty of connecting simulations to experiments - Why was what done? What sample is it related to?
    - Nicolas Carpi:
      - above are often requested features
      - automated ingestion into eLabFTW using a folder / S3 backend
      - export of eLabFTW entries using the .elab format - provides metadata to the raw data
      - ease of use!
    - Peter Kraus:
      - use case of catalysis
      - want to keep using my data pipeline but have it compatible with all ELNs using one api
    - Nicolas Carpi:
      - mentioned the metadataextractor.otc.coscine project
4. Summary from Matthew Evans's slides
