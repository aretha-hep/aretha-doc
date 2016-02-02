# aretha-doc

`aretha` is a prototype for a cloud-based service that streams simulated Monte-Carlo events. The main project website is found at GitHub at [github.com/aretha-hep](https://github.com/aretha-hep).

## the demo

[![aretha - demo](http://i.giphy.com/74FJ97GxqeHCg.gif)](http://www.youtube.com/watch?v=S5SkTXhdCng)


##introduction

In recent years, the idea of regarding computing infrastructure as a service has quickly changed the standard procedures among IT specialists to provision end deploy networked applications. Among others, Google and Amazon provide these IaaS (infrastructure as a Service) services that are the backbone of may resource intensive applications. This change in perspective on computing resources allows us to revisit the traditional \emph{modi operandi} within both the experimental and phenomenological high-energy physics communities. A main interface between these sub-field are the Monte-Carlo generators used to produce simulated particle collisions. Among the leading software products here are [SHERPA](https://sherpa.hepforge.org/trac/wiki/SherpaDownloads/Sherpa-2.2.0), [Herwig](https://herwig.hepforge.org), or [MadGraph](http://madgraph.hep.uiuc.edu/). Conventionally, these codes are used to produce collisions, that can be optionally written out in several standardized file formats, most often the [HepMC](http://lcgapp.cern.ch/project/simu/HepMC/) event format. These events are then, for example,  analyzed directly e.g. with tools such as [Rivet](http://rivet.hepforge.org) or used by high-energy physics experiments such as those at the LHC, to serve as input into the detector simulation to produce fully-simulated particles collisions, which can be then compared to data.

We are presenting a tool, to massively  scale the production of, and crucially, the real-time indexing and analysis of, these simulated events across infrastructure hosted by leading industry providers using a host of open-source technologies such as the Linux containerization technology [Docker](https://www.docker.com/), the distributed messaging system [ZeroMQ](http://zeromq.org/), the search server [elasticsearch](https://www.elastic.co/) as well as the visualization tool [Kibana](https://www.elastic.co/products/kibana)


