# Classification of Real-Time papers
## History of this repo

This repository contains an effort to classify papers which appeared at real-time conferences.

I did it in 2013 and kept it updated for a couple of years. Some collegues demonstrated some interest on this classification. So now I'm sharing it, open to contributions and help.

## Methodology

All papers published in [IEEE Real-Time Systems Symposium (RTSS)](http://www.rtss.org/) from 1990 to 2015 are classified.

Each paper is assigned a vector of weights with sum equal to 1.

Each weight corresponds to the relation of the paper to the sub-areas listed below:
- APP: real-time applications, use cases (automotive, avionics, etc.)
- CTRL: real-time and control, cyber-physical systems (CPS)
- MIX-CRIT: mixed-criticality systems
- LANG: real-time languages and specifications
- FORMAL: formal methods and verification
- POWER: power/temperature aware real-time systems
- DESIGN: combinatorial optimization
- WSN: wireless sensor networks, Internet of Things (IoT)
- DISTR: distributed systems, fault-tolerance, synchronization
- RES: QoS/resource management
- M_SCHED: multiprocessor/multicore scheduling
- 1_SCHED: single processor scheduling
- NETW: real-time networks
- OS: operating systems, I/O, resource sharing
- WCET: worst-case execution time analysis
- HW: hardware support

The choice of the above classification was hard. It responded to many, possibly conflicting goals, including:
- the necessity to visually render the trends in a human readable form
- the aim of capturing long-term trends
Something different was possible. As always.


METHODOLOGY (maybe some text should go in the PREAMBLE)

All papers published at RTSS since 1990 were classified. The classification of a paper was made by assigning a tag, representing the research area, and a weight to the tag measuring how much the paper belongs to that area. The sum of the weights assigned to each paper is one. To ease a graphical representation, the reported data is filtered.

NOTE

If you want to put my name on it "the classification is made by Enrico Bini ..." I'm fine. I have nothing against not in favour. Up to you, the TC chair, or the Executive Committee.

