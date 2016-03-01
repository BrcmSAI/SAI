SAI
===
Broadcom SAI spec implementation software version 1.0

Overview
========
SAI is a OCP project in the networking projects sub category.
SAI provides a vendor-independent way of controlling the switching and
forwarding elements like ASICs, NPUs etc. in a generic way.
This software release is Broadcom's contribution to the open community of its
implementation of the SAI spec as specified on the SAI Github at
https://github.com/opencomputeproject/SAI.
This implementation enables any customer to be able to configure and control
the Broadcom switching ASICs as described by the SAI standard.
Broadcom's SAI implementation runs on top of the Opennsl library
available at: https://github.com/Broadcom-Switch/OpenNSL.
One can download the supported Opennsl library from:
https://github.com/Broadcom-Switch/OpenNSL/tree/master/bin
This SAI release supports the Broadcom TD2 switching ASIC.

Legal
=====
Please see LEGAL_TERMS for the use of and access of the Broadcom-Switch Page.

License
=======
Licenses for the software are available at the applicable level of the
software repository under the "LICENSE" file.

Building
========
This package depends upon OpenNSL 3.0.0.3.

To build SAI, change to the bin/s6000-x86-trident-deb80 directory.  Use the make
command to build the SAI shared library.

Note: The OpenNSL include files are assumed to be in
../opennsl/include (relative to the sai-1.0.0.0 directory).  If the
headers are in a different location, set the MAKE variable OPENNSL_INC
to point to that location.
