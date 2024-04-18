# ID.AM-02

## Statement{.section .statement}
Inventories of software, services, and systems managed by the organization are 
maintained

## Additive Manufacturing Guidance{.section .additive}
A software inventory catalogs the origin, components, location, use, 
maintenance status, update policy, and responsible party of each software 
deployment within the AM workflow. Because software is a significant part of 
any system’s attack surface, this inventory provides an important source of 
information when assessing security risks, defining security policy, and 
responding to incidents. Depending on the environment, representative 
entries for the AM context might list CAD/CAM applications, toolpath 
generators (i.e. slicers, etc.), device firmware, operating systems, data 
storage, process simulation, job management, and QC software, among others. 
Users will add a new inventory entry for each new piece of software that is 
deployed into the workflow. Asset identification tools and vendor SBOMs will 
inform this initial entry, while periodic automated scans and audits will 
ensure entry’s accuracy through regular updates. The inventory should 
interface with the data flow diagrams in ID.AM-3 to yield a complete 
account of the AM workflow’s communication.

### {.example .ex}
Maintain inventories for all types of software and services, including 
commercial-off-the-shelf, open-source, custom applications, API services, 
and cloud-based applications and services

### {.example .ex}
Constantly monitor all platforms, including containers and virtual machines, 
for software and service inventory changes

### {.example .ex}
Maintain an inventory of the organization's systems