JOS-on-JOS
==========

JOS as a GUEST OS on JOS as a HOST OS using paravirtual hypervisor

Ran JOS operating system as GUEST on JOS operating system as HOST using a basic Para-Virtual Hypervisor.

Implemented the following kernel features for virtualization:-
• Guest OS bootstrapping, Extended Page Tables (EPTs), Hypercalls (ipc_send, ipc_receive, dummy memory_map for guest OS to boot).
These are implemented according to the instructions given on the course webpage (http://www3.cs.stonybrook.edu/~porter/courses/cse591/s14/lab1.html).

•	Modified existing Virtualization lab (CSE-591) code by merging HOST and GUEST separate code sources to single source using Preprocessor Directives and build script modifications (Makefiles).
