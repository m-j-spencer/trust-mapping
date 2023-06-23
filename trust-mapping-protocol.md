# Trust Mapping Cyber Security Workshop Protocol

## Background and Motivation

### Introduction

All organisations depend on security practitioners to ensure good cyber security. In large organisations they may be members of a specialist security teams. In smaller organisations, they may work across IT, risk, and procurement. 

Security practitioners need technical expertise, but they also need to be good at navigating complex social landscapes. Confidence in the security of any system is a result of a complex web of communication, across divisions of labour, specialisms, allocations of responsibility, contractual relationships, regulatory relationships, spanning teams, organisations, sectors and markets.

Trust Mapping workshops are designed to **support practitioners’ development of socio-technical expertise**, by creating the opportunity for reflective learning: participants work together in the session to create a visualisation of the social relationships and distributions of knowledge and ignorance that they have to work with, and use it to examine issues and potential improvements in their practices and arrangements.

Like [Threat Modelling](https://www.threatmodelingmanifesto.org/) and [Blameless Retrospectives](https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf), Trust Mapping aims to empower teams to drive security improvements based on their situated knowledge of systems, processes and practices.

This document provides the protocol for running Trust Mapping workshops and a brief summary of the theoretical foundation upon which it is built. 

### Requirements

Trust Mapping workshops are facilitated sessions for 3-10 practitioners. They last 90 minutes and follow a structured process based on a set of bespoke prompt cards. No advance preparation is needed for participants. The facilitator (who may be a team member, or someone external brought in for this purpose) will need to familiarise themselves with this protocol and prepare the cards (templates can be found in this Github repository). The group will need a quiet space and a large whiteboard on which to draw during the session.

Trust Mapping was developed as part of an academic research project, in which the facilitator was also collecting data. Where the methodology is to be used in this manner, institutional review of research ethics should be a prerequisite.

## Protocol

### General principles

The facilitator should encourage the following behaviours throughout the session:
- No laptops or phones
- One person speaks at a time
- All participants listen and respond to the speaker
- Everyone gets the change to speak
- All participants are engaging with the visualisation (pointing, drawing, annotating)

The facilitator will lead the initial introductory discussion and the final wrap up and debrief. In the other sections of the workshop, facilitation should be lightweight and ‘hands off’, offering guidance, but allowing the prompt cards to provide the structure for the activity. 

### Introduction (15 minutes)

It is important that participants understand the purpose and structure of the workshop clearly at the beginning, and that they have the opportunity to ask questions of the facilitator.

An example introductory script is provided below:

---
*Welcome to the workshop. The goal of this Trust Mapping exercise is to help you think in a socio-technical way about what it means to ‘have assurance’ in technical products and systems. In other words, how do you know that the systems you care about in your day-to-day work are secure? Who do you depend on for your confidence? Who has access to crucial information, for instance about designs, vulnerabilities, audits and test results? How is information shared, transformed and interpreted? By drawing a collaborative visualisation, the aim of the workshop is to create an opportunity for you to reflect on things that are familiar, to prompt you to think a little differently, to learn from each other, and to generate some ideas about what are the important issues and where you might make improvements.*

*The workshop is structured using this deck of cards:*
- *We begin with the dark blue cards, which ask us to decide on a system of interest, which will be the thing we focus on for the whole session. It should be something you use, work with, or have some responsibility for. It could be software or hardware, custom made or packaged, old or new. We are looking for a product, system or technology that you all depend upon, and we will use the session to unpack where your confidence comes from and what kinds of actors and relationships are involved.*
- *The light blue cards are then used to build up our visualisation: they prompt us to create a map of the ‘actors’ who have access to different kinds of knowledge about the system (as designers, developers, implementers, accreditors, testers and so on). They might be individual people, teams, business functions, whole organisations; the concept of 'actor' we use is very flexible.*
- *Once we have most of the relevant actors on the board, we use the green cards to trace how knowledge and information relevant to the security of our system of interest is shared between these actors. This may be via texts, documents or reports that move as digital or physical artefacts, it could be word of mouth or even personal experience, moving around as people move or change jobs.*
- *We end up with an informal network diagram, with actors as nodes, and lines of communication as the edges that connect them. The orange cards then provide us with prompts to think critically about, for instance, which actors are trusted, which mistrusted, how information is interpreted, about the issues that affect you in this area and possible improvements that could be made.*

*One really important point to make about trust mapping is that there is no single ‘right’ answer; there is no definitive diagram we’re looking for. This is all about discussing and drawing how things look to you. You might not know who has access to, for instance, key architectural documentation. But that is something we can use the session to think through, marking uncertainty on the diagram with question marks, or mapping out organisational knowledge: who would know where that key documentation could be found?*

---

The facilitator should give participants an opportunity to ask questions. If the facilitator is taking notes for research data purposes, they should also ensure participants understand the procedures for pseudonymisation, fictionalisation and approval.

### System of interest - dark blue cards (15 minutes)

The two cards in this category can be dealt to the group together. Some input by the facilitator may be needed to help the group select a suitable system of interest. 

The result of this stage of the workshop will be a title on the board specifying the system of interest and the security claim most relevant to the group.

### Actors - light blue cards (15 minutes)

The facilitator should deal the cards in sequence. It may be helpful to reassure the group that some cards may generate multiple actors, others may be discarded without adding anything to the board, and that they are free to to add/remove/edit/move actors throughout the exercise. The speed of card dealing can be used to control how quickly this part of the task is accomplished.

There are no rules for how actors should be positioned in relation to each other; participants will tend to use spatial logics that are intuitive to them, clustering actors that make sense as 'near' or 'similar' to each other.

The result of this stage of the workshop will be a distribution of actor names across the board. 

### Flows - green cards (15 minutes)

The facilitator should deal all the green cards to the group, and ask them to pick the three most interesting to them for thinking about their system of interest. If multiple colours of pen are available, different colours may be used to differentiate between the flows.

The result of this stage is an informal network diagram, with lines and arrows connecting up actors.

### Analysis - orange cards (15 minutes)

A variety of prompts are provided in the orange category. It can be more productive to spend longer talking through the answer to a single card than attempt to work on many. The orange cards provide a range of options, and the facilitator may use discretion in selecting which is most relevant and dealing just that card to the group, or may provide the group with options from which to select. The group can be invited to annotate their diagram.

The result of this stage is an annotated network diagram.

### Wrap up and debrief (15 minutes)

The facilitator should wrap up, letting participants know that the workshop is coming to an end, and giving thanks to the group for their efforts. This last part of the workshop is focussed on reflections about exercise itself. There are two priorities:
- To gather feedback from each participant concerning what they liked about the session and what they thought could be improved
- To go around each member of the group, and collect together a list of actions that participants would like to take, or changes they would like to see, based on what has been discussed


## Theoretical Basis

Trust Mapping is motivated by a number of insights from social theory and methodology.

Trust Mapping builds on Donald Schön’s famous account of **reflective practice** as an important mode of expert learning (1983). The need to make cyber security practices repeatable and accountable leads to a tendency to emphasise the importance of decision making that is based on explicit formalised processes. However, security practitioners also rely heavily on their capacities to make intuitive judgements, to know for example when to adopt a more skeptical stance towards accepted knowledge, to ask further questions, to seek additional grounds for confidence. Such capacities are cultivated in use rather than learned from books, and can be enhanced through creating settings, such as Trust Mapping workshops, in which practitioners have the opportunity reflect upon their own understandings and intuitions.

The literature on **high reliability organisations** has become an important foundation for security practice, through DevOps and continuous delivery methodologies, as well as through the concept of 'safety cultures’ upon which ‘security cultures’ are often modelled (Kim et al. 2021). An important result has been the widespread recognition that organisational learning is crucial for maintaining a good organisational security posture. While frameworks (such as NIST or ISO) can provide a good starting point, security practice is highly context specific, and an overreliance on procedure can lead to a ‘drift into failure’ (Dekker & Pruchnicki 2014). As in other high reliability contexts, it is essential that security practitioners remain open minded, sensitised to new information and able to think creatively about improvements that could be made (Weick 1993). This requires an organisation that values diverse viewpoints, and that is able to avoid becoming locked in to a single restrictive mindset (such as the ‘production culture’ so consequential in the run up to the Challenger Space Shuttle disaster; Vaughan 1996). 

High reliability cyber security depends upon having **a rich toolkit of learning methodologies**, that enable organisations to promote diverse viewpoints, open-minded thinking, and to generate novel insights into emerging issues and possible improvements. Trust Mapping is designed to sit alongside existing and established methodologies such as the [Blameless Postmortem](https://www.etsy.com/codeascraft/blameless-postmortems) for learning from incidents, and [Creative Engagements](https://research.utwente.nl/en/publications/trespass-book-3-creative-engagements) for designing new security policies. All of these methodologies involve setting aside a special time and space for a facilited workshop in which dominant values (such as commerical and delivery priorities) can be temporarily put on hold, and other ways of interpreting what is going on can be voiced (for instance, narratives about trust, character, meaningfulness, civic value, wellbeing, etc), giving the opportunity for a broader palette of ideas to emerge, for dominant ideas to be challenged, and for learning on both personal and organisational levels.

These learning methodologies represent an emerging tradition within human-centred security that challenges the dominance of the rather paternalistic 'behavioural nudging' approach. They recognise that people are the source of the requisite variety crucial for maintaining security, rather than seeing people as a weakness that needs to be managed and manipulated. One of the most important sources for this broader thinking about the human in security has been the efforts of scholars in bringing techniques from **participatory design** into the world of security (for instance, Hall, Heath & Coles-Kemp 2015, Heath, Hall & Coles Kemp 2018). Participatory design requires ‘relational expertise’ (Dindler & Iversen 2014), the investment of the sector in skilled facilitators who are experienced in running workshops and creating the conditions for open communication. This is a very different skillset to the nudging paradigm, and one that requires investment: while such methodologies now form an established part of human-computer interaction (Harrison, Sengers & Tatar 2007), it is comparatively rare to see them included in cyber security courses and programmes.

While its aims are thus aligned with those of security learning methodologies more generally, Trust Mapping takes a particular angle on security practice, one that is informed by social worlds theory (Clarke & Star 2008) and Susan Leigh Star’s concept of **ill structured solutions** in distributed networks of collaboration (1989). Examining large scale scientific projects, involving many specialisms and fields, Star noted that the overarching challenge is not (as was often presumed) one of creating an overall consensus about results and the emerging project. Rather, the challenge is creating coordination between fields of work that may maintain entirely different viewpoints on what the research is all about. An ‘ill structured solution’ does not depend upon forcing all participants into a single frame of reference; instead it relies on objects that allow people to coordinate their work across boundaries (what Star called ‘boundary objects’). Trust Mapping is designed to help practitioners to appreciate the wider institutional ecology in which they work, the interacting frames of reference involved (those, for instance, of product developers, penetration testers, regulators, auditors), the ways in which coordination is achieved, and how this might be done better.


## Recognition and thanks

Trust Mapping was developed as part of the [Scaling Trust](https://warwick.ac.uk/fac/cross_fac/cim/research/scaling-trust) project, supported by UK Research and Innovation (grant number MR/S037373/1). 

This methodology was developed and piloted between 2022 and 2023 with the generous assistance of security practitioners at two large organisations whose feedback and insight was invaluable in refining the protocol.

Further thanks to the [Research Institute in Socio-Technical Cyber Security](https://riscs.org.uk/), who are supporting additional research into this methodology.

## References

- Clarke, A. E., & Star, S. L. (2008). The social worlds framework: A theory/methods package. *The handbook of science and technology studies*, 113-137.
- Dekker, S., & Pruchnicki, S. (2014). Drifting into failure: theorising the dynamics of disaster incubation. *Theoretical Issues in Ergonomics Science*, 15(6), 534-544.
- Dindler, C., & Iversen, O. S. (2014). Relational expertise in participatory design. In *Proceedings of the 13th Participatory Design Conference: Research Papers-Volume 1* (pp. 41-50).
- Hall, P., Heath, C., & Coles-Kemp, L. (2015). Critical visualization: a case for rethinking how we visualize risk and security. *Journal of cybersecurity*, 1(1), 93-108.
- Harrison, S., & Tatar, D. and Sengers, P.(2007). The three paradigms of HCI. In *Alt. Chi. Session at the SIGCHI Conference on Human Factors in Computing Systems San Jose, California* (pp. 1-18).
- Heath, C. P., Hall, P. A., & Coles-Kemp, L. (2018). Holding on to dissensus: Participatory interactions in security design. *Strategic Design Research Journal*, 11(2), 65-78.
- Kim, G., Humble, J., Debois, P., Willis, J., & Forsgren, N. (2021). *The DevOps handbook: How to create world-class agility, reliability, & security in technology organizations*. IT Revolution.
- Schön, D. A. (1983). *The Reflective Practitioner: How professionals think in action*. Routledge.
- Star, S. L. (1989). The structure of ill-structured solutions: Boundary objects and heterogeneous distributed problem solving. In *Distributed artificial intelligence* (pp. 37-54). Morgan Kaufmann.
- Vaughan, D. (1996). *The Challenger launch decision: Risky technology, culture, and deviance at NASA*. University of Chicago press.
- Weick, K. E. (1993). The Collapse of Sensemaking in Organizations: The Mann Gulch Disaster. *Administrative Science Quarterly*, 38(4).
