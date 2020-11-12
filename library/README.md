P4.org application library

# Table of contents
   1. What is P4 Apps Library?
   2. Which applications are hosted?
   3. Artifacts to submit
   4. Submitting process

# 1. What is P4 Apps Library?
TNA has been opened, the need to create a library or "app store" for P4 code is higher. Apps WG has a repository, time to think about logistics.

Q1. what if the app requires a modification of Barefoot switch.p4, which is not open? A patch to switch.p4 can be shared?

A: having public version of switch.p4 and APIs is under discussion. Till then, we start from apps that don’t require switch.p4 integration.

Q2. What about non-p4 apps, such as INT implementation in DPDK or eBPF under a license different from Apache2 that P4.org uses?

A: we start from apps under Apache2.

# 2. Artifacts to submit
 required from each app
runnable P4 + control plane code, test script, document.

Document to specify Barefoot SDE version (in cast of TNA), an inventory of artifacts, and sufficient description to enable the artifacts to be exercised.
Vetting process: manual review at the beginning. Automatic integration with SDE and testing will be needed.



# 3. Submitting process

# 4. Maintenance
 
