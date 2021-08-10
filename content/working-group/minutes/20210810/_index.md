---
title: "openMobility Telco Aug 10th, 2021"
date: 2020-08-10T16:09:45+02:00
layout: "single"
description: ""
categories: []
keywords: []
slug: ""
aliases: []
toc: false
draft: false
---

# openMobility Telco (Aug 10th, 2021)

## Attendees

- Robert Hilbrich
- Christoph Sommer
- Ronald Nippold
- Michele Albano
- Yun-Pang Flötteröd
- Robert Protzmann
- Michael Plagge
- Giuliana Armellini
- Karl Schrab

## News from (Currently) Associated Projects

### Eclipse SUMO

- Next SUMO release: 1.10 on August 17, so we are now in a code freeze
- DLR starts working on supporting OSMP FMUs for simulator coupling: [OSMP](https://opensimulationinterface.github.io/osi-documentation/osi-sensor-model-packaging/doc/specification.html)
- SUMO User Conference 2021: 
  - Agenda is here: [Conference Link](https://www.eclipse.org/sumo/conference/)
  - it is free of charge, but **please register** (if you want to attend)
  - Maybe add the author and affiliation to the agenda as well
- Should we work on getting releases with MOSAIC more closely aligned? - Yes, desirable - also for veins!
  - Notify and include non-DLR SUMO users in code-freeze phase to incorporate feedback earlier
- Future of TraCI - will be discussed in the SUMO project in the coming months
- Where to go after the Fox UI toolkit?
  - Decoupling of UI and simulation logic could have positive or negative effects on the responsiveness

### Eclipse MOSAIC

- Improvements on communication simulator coupling
- ns3 version 3.34 update included in recent MOSAIC
- Omnet 6 migration is currently being looked at
- Internal improvements to battery and charging model and simulations (which are currently not in the essential version of MOSAIC)
- Release date is probably going to be in September 2021
- Continuing work with LIDAR and sensor data towards submicroscopic modeling
- libsumo soupling with Eclipse MOSAIC is now supported
- SUMO Bug: getLeader command is not yet implemented? (swift bug) --> Karl opens a new issue on GitHub on that

## Other News from the Attendees

- DLR plans to create a new Eclipse project for [TAPAS](https://github.com/dlr-vf/tapas)
  - TAPAS aims to provide realistic traffic demand
  - The new project will be within the purview of openMobility

## Real Work”

### Whitepaper: Survey or Landscape of Demand Generators for SUMO

- Current status overview by Ronald
- Teams are collaborating on Overleaf - due to holiday the work is progressing slowly
- Input is still welcome
- Work will restart in August

### Direction of openMobility for the Future

- Recent discussion around "profitablity" of working groups as they require a lot of effort for book keeping and administration
- Idea to discuss: Eclipse "Working Group light"
- Where should we proceed with openMobility?
- Two options for the nature of openMobility:
  a) openMobility is a place to build and start a community around the topics mobility (zero Budget, almost no infrastructure, no program plan, ...)
  b) openMobility should be a place to specifically work towards a common goal (with a program plan, a dedicated budget, ...)
- Open discussion will be continued in the next meeting

## Any other Business

- If the Eclipse wiki continues to be "readonly", we will publish the meeting minutes on the [openMobility website](openMobility.eclipse.org) from now on
- EclipseCon Oct 25-28 (virtual event)
  - Community Day on Monday Oct 25
  - Andy and I plan to have a session to introduce new users to the community, but also to connect with members of other working groups

## Next Meetings

- SUMO Demand Modelling Paper - Wed, August 11, 15-16 CEST
- Automotive PMC meeting - Wed, August 11, 16-17 CEST
- Next openMobility meeting: Oct 5, 14:00 CEST
