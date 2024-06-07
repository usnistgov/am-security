## ID.AM-03
### Supplemental Guidance {processing-role=resource-only audience=general}
Data flow diagrams help a manufacturer understand the flow of data between networked components. Documenting data flows enables organizations to understand the expected behavior of their networks. This understanding of how devices communicate assists with troubleshooting as well as response and recovery activities. This information can be leveraged during forensic activities or used for analysis to identify anomalies.

Network architecture documentation tools help a manufacturer identify, document, and diagram the interconnections between networked devices, corporate networks, and other external connections. 
A comprehensive understanding of the interconnections within the environment is critical for the successful deployment of cybersecurity controls. This information is equally important for effective network monitoring.  

### OT-Specific Recommendations and Guidance {processing-role=resource-only audience=ot}
Organizations should consider the impact of the use of automated data flow mapping tools that use active scanning or require network monitoring tools (e.g., in-line network probes) on OT systems. Impacts could be due to the nature of the information, the volume of network traffic, or the momentary disconnection of manufacturing system components from the network. Consider using data flow mapping tools that utilize these methods during planned downtime.

Network architecture documentation tools that use automated topology discovery technologies can only capture details from IP-based networked devices. Many OT environments contain isolated systems, components, or systems connected on non-IP networks. The OT environment may not be technically capable of using automated network architecture documentation tools, and manual processes may be required to document these components.

Asset owners may also want to consider how automated scanning activities may potentially impact the OT system by testing automation tools in a non-production environment. Based on testing results, asset owners should consider utilizing automated OT network architecture documentation tools during planned downtime.  

Organizations may also want to consider physically inspecting OT network connections or analyzing network logs to document the OT network architecture, especially if the network is not large or complicated. Incorporating OT network activity monitoring may help organizations identify the addition or removal of devices within the environment between planned scanning activities.  