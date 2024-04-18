# ID.AM-01

## Statement{.section .statement}
Inventories of hardware managed by the organization are maintained

## Additive Manufacturing Guidance{.section .additive}
A physical inventory for AM systems should include  each machine's 
configuration including any optional components/features as well as supporting 
equipment such as sensors/monitoring setups, and instruments/tools used for 
configuring/calibrating the system. Further, any physical components that may 
be reused/recycled in the process should be tracked along with their process 
history (temperature, specific builds, post processing, etc.). For example, 
material left in a machine may be degraded by sitting at an elevated 
temperature for an extended period outside of fabrication. If confidentiality 
is a concern, the waste stream should also be tracked. As a forensic example, 
a discarded build surface can contain information about part geometry or 
process settings that may be sensitive.

### {.example .ex}
Maintain inventories for all types of hardware, 
including IT, IoT, OT, and mobile devices
<!-- Concrete AM-specific examples: AM machine, controller, HMI,
sensors not part of the machine itself, environmental sensors.
Question: what is in the system vs. external to the system?
Joel: boundary between IT and OT is more topological than functional. E.g., HMI
is an IT workstation but it's part of OT in that it's on the OT subnet. 
"Examples of AM h/w include..." -->

### {.example .ex}
Constantly monitor networks to detect new hardware and automatically update 
inventories