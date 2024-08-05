# [additiveHeadingText]

Manufacturers should be aware and consider how AM machines handle data and metadata information. This knowledge is essential to protect unauthorized parties from obtaining build data and metadata residing on a machine prior to the machine’s disposal and retaining data/metadata determined to be of value to the organization.

To avoid network-related disruptions, it is common for high-end machines to store the entire build data (a sequence of build instructions) internally, before manufacturing starts. It is, however, not guaranteed that the build data (containing all details of the 3D printed parts) is deleted after the build is completed. 

Similarly, AM machines routinely store metadata. While it can vary across makes and models of AM machines, metadata typically includes information like credentials of operators who initiated build, build file name, build start and end time, success status , etc. Note that some vendors can have terms of service that authorize access and collection of the metadata.

<!--
Note that not every OEM will provide a way for customers to access/cleanse information before disposal. Neither might they be willing to disclose what information is stored where. A “reverse engineering” by the manufacturer will likely violate the EULA.
-->

Note that, when storage is managed by modern operating system, deletion of a file does not necessarily mean its erasure (that is, it can be recovered using either OS user interface or specialized software for the storage devices). Therefore, one or more build files alongside the metadata can be recoverable from AM machines. Disposal of AM machines without proper erasure might expose the retained data/metadata to unauthorized parties.

