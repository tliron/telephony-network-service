Telephony Network Service
=========================

This example of a multi-cluster network service comprises a VNF (Virtualized Network Function), a
CNF (Containerized, or Cloud-native Network Function), and a PNF (Physical Network Function).

It provides an end-to-end telephony service based on [Asterisk PBX](https://www.asterisk.org/) 
between a central site and an edge site. An SIP/RTP trunk is set up on a data plane, which is
implemented as simple routing for demonstration purposes, but could be extended to a full-blown
SD-WAN. The result is that SIP phones connected to either site can all call each other.

A [TOSCA](https://www.oasis-open.org/committees/tosca/)-ochestrated version of this is included as
an example for [Turandot](https://turandot.puccini.cloud/examples/telephony-network-service/).
