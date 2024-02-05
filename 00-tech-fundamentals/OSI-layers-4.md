### Layer 4 - TCP and UDP

TCP 
* Slower, but reliable
* Introduces **segments** 
  * Specific to TCP and placed (encapsulated) in packets
  * Segments themselves dont have IPs, the packets provide the addressing
  * Segments contain sequence numbers which are unique ways of identifying a segment

* Connection is chopped into segments which are contained in the L3 packets 
* Even if a segment is damaged, it can be retransmitted and segments will continue 

UDP
* Faster, less reliable

TCP and UDP both run on top of IPs