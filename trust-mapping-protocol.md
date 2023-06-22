# Trust Mapping

## Background and Motivation

### Introduction

All organisations depend on security practitioners to ensure good cyber security. In large organisations these may be members of a specialist security teams. In smaller organisations, they may work across IT, risk, operations and procurement. 

Security practitioners need technical expertise, but they also need to be good at navigating the complex social landscapes of organisations, business functions, divisions of labour and allocations of responsibility that are unique to their context of work.

Trust Mapping workshops last 90 minutes and follow a structured process based on a set of bespoke prompt cards. The sessions are designed to **support practitioners’ development of socio-technical expertise**, by creating the opportunity for reflective learning: participants work together in the session to create a visualisation of the social relationships and distributions of knowledge and ignorance that they have to work with, and use it to examine issues and potential improvements in their practices and arrangements.

Like [Threat Modelling](https://www.threatmodelingmanifesto.org/) and [Blameless Retrospectives](https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf) Trust Mapping aims to empower teams to drive security improvements based on their situated knowledge of systems, processes and actual practices.

This document provides the protocol for running Trust Mapping workshops. 

### Requirements

Trust Mapping workshops are facilitated sessions for 3-10 practitioners. No advance preparation is needed for participants. The facilitator (who may be a team member, or someone external brought in for this purpose) will need to familiarise themselves with this protocol and prepare the cards (templates can be found in this Github repository). The group will need a quiet space and a large whiteboard on which to draw during the session.

Trust Mapping was developed as part of an academic research project, in which the facilitator was also a researcher. Where the methodology is to be used in this manner, with research outputs, institutional review of research ethics should be a prerequisite, and appropriate procedures put in place for participants’ informed consent.

## Protocol

### General principles

The facilitator should try to encourage the following behaviours throughout the session:
- No laptops or phones
- One person speaks at a time
- All participants listen and respond to the speaker
- Everyone gets the change to speak
- All participants are engaging with the visualisation (pointing, drawing, annotating)

The facilitator will lead the initial introductory discussion and the final wrap up and debrief. In the other sections of the workshop, facilitation should be lightweight and ‘hands off’, offering guidance, but leaving it to the group to decide how they want to approach the task. There is no ‘right way’ to complete the exercise; different teams will work in different ways; the goal is to focus on exploring the relationships the system of interest.

### Introduction (15 minutes)

It is important the participants understand the purpose and structure of the workshop clearly at the beginning, and that they have the opportunity to ask questions of the facilitator.

An example script is provided below:

‘''
{
Welcome to the workshop. The goal of this Trust Mapping exercise is to help you think in a socio-technical way about what it means to ‘have assurance’ in technical products and systems: in other words how you know that the systems you care about in your day-to-day work are secure. The exercise is designed to create an opportunity for you to reflect on things that are very familiar, and hopefully to think a little differently, to learn from each other, and to generate some ideas about what are the important issues and how you might make improvements.

The workshop is structured using this deck of cards:
- We begin with the dark blue, which ask us to decide on a product of interest, which will be the thing we focus on for the whole session. It should be something you use or work with, and its security should matter to you. It could be software or hardware, custom made or packaged, bought or made. We are looking for a product, system or technology that you all depend upon, and we will use the session to unpack where that confidence comes from and what kinds of actors and relationships are involved.
- The light blue cards are then used them to start our visualisation: they prompt us to create a map of the ‘actors’ who know about it (as designers, developers, implementers, accreditors, and so on). They might be individual people, teams, business functions, whole organisations.
- Once we have most of the relevant actors on the board, we use the green cards to trace how knowledge and information relevant to the security of our system of interest is shared between these actors (this may be via texts, documents or reports that move as digital or physical artefacts, word of mouth or even personal experience shared via the movement of people). 
- We end up with an informal network diagram, with actors as nodes, and communication as the edges that connect them. The orange cards then provide us with prompts to think critically about, for instance, which actors are trusted, which mistrusted, about the issues that affect us and possible improvements that could be made.
One really important point to make about trust mapping is that there is no single ‘right’ answer; there is no definitive diagram we’re looking for. This is all about discussing and drawing how things look to you. You might not know who has access to, for instance, key architectural documentation. But that is something we can use the session to think through, marking uncertainty on the diagram with question marks, or mapping out organisational knowledge: who would know where that key documentation could be found.

}

‘''

Before beginning, the facilitator should give participants an opportunity to ask questions. If the facilitator is taking notes for research data purposes, they should also use this opportunity to ensure participants understand the procedures for pseudonymisation, fictionalisation and approval.

### System of interest (15 minutes)

The two cards in this category can be dealt to the group together. Some input by the facilitator may be needed to help the group select a suitable system of interest. 

### Actors (15 minutes)

Deal the cards in sequence, and reassure the group: some cards may generate multiple actors, others may be discarded without adding anything to the board. The facilitator should use the speed of card dealing to control how quickly this part of the task is accomplished.

### Flows (15 minutes)

Deal all the green cards to the group, and ask them to pick the three most interesting to them for thinking about this system of interest. If multiple colours of pen are available, these colours may be used to differentiate between the flows.

### Critique (15 minutes)

A variety of prompts are provided in the orange category. It is often more productive to spend longer talking through the answer to a single card than attempt to work on many. The orange cards provide a range of options, and the facilitator may use discretion in selecting which is most relevant, or may provide the group with the choice.

### Wrap up and debrief (15 minutes)

The facilitator should wrap up by giving thanks to the group. This last part of the workshop is focussed on reflections about exercise itself. There are two priorities:
- To gather feedback from each participant concerning what they liked about the session and what they thought could be improved
- To go around each member of the group, and collect together a list of actions that participants would like to take, or changes they would like to see, based on what has been discussed


## Theoretical Background

Trust Mapping is motivated by a number of insights from social theory and methodology.

Trust Mapping builds on Donald Schön’s famous account of **reflective practice** as an important mode of expert learning (1983). The need to make cyber security practices repeatable and accountable leads to a tendency to emphasise the importance of decision making that is based on explicit formalised processes. However, security practitioners also rely heavily on their capacities to make intuitive judgements, to know for example when to adopt a more skeptical stance towards accepted knowledge, to ask further questions, to seek additional grounds for confidence. Such capacities are cultivated in use rather than learned from books, and can be enhanced through creating settings, such as Trust Mapping workshops in which practitioners have the opportunity reflect upon their own understandings and intuitions.

The literature on **high reliability organisations** has become an important foundation for security practice, through DevOps and continuous delivery methodologies, as well as through the concept of 'safety cultures’ upon which ‘security cultures’ are often modelled (Kim et al. 2021). It is widely recognised that organisational learning is crucial for maintaining a good organisational security posture. While frameworks (such as NIST or ISO) can provide a good starting point, security practice is highly context specific, and an overreliance on procedure can lead to a ‘drift into failure’ (Dekker & Pruchnicki 2014). As in other high reliability contexts, it is essential that security practitioners remain open minded, sensitised to new information and able to think creatively about improvements that could be made (Weick 1993). This requires an organisation that values diverse viewpoints, and that is able to avoid becoming locked in to a single restrictive mindset (such as the ‘production culture’ so consequential in the run up to the Challenger Space Shuttle disaster; Vaughan 1996). 

Trust Mapping is intended to be part of an growing **toolkit of learning methodologies** for security, that enable organisations to promote diverse viewpoints, open-minded thinking, and to generate novel insights into emerging issues and possible improvements. Other such methodologies include the [Blameless Postmortem](https://www.etsy.com/codeascraft/blameless-postmortems) for learning from incidents, and [Creative Engagements](https://research.utwente.nl/en/publications/trespass-book-3-creative-engagements) for designing new security policies. In each of these methodologies, a space is created in which the usually dominant values (such as commerical and delivery priorities) are temporarily set aside, and other ways of interpreting what is going on in the organisation are encouraged (for instance, narratives about trust, meaningfulness, civic value, or wellbeing) and juxtaposed.

One of the most important contributing factors to the emergence of these learning-focused methodologies is the efforts of scholars to bring techniques from **participatory design** into the world of security (for instance, Hall, Heath & Coles-Kemp 2015, Heath, Hall & Coles Kemp 2018). Participatory design does require new kinds of ‘relational expertise’ (Dindler & Iversen 2014), the investment of the sector in skilled facilitators who are experienced in running workshops and ensuring that learning can take place within them. While such skills are not usually a core part of a conventional computer science and engineering education, a broad trend of research in human-computer interaction, growing in influence over the past two decades has emphasised situated action, partial perspectives and meaning construction (Harrison, Sengers & Tatar 2007).

While its aims are thus aligned with influential ideas of learning, reliability and participation, the specific form of the Trust Mapping exercise is informed by social worlds theory (Clarke & Star 2008) and in particular Susan Leigh Star’s concept of **ill structured solutions** in distributed networks (1989). Examining large scale scientific research, involving multiple specialisms and fields, Star noted that the overarching challenge is not (as was often presumed) one of creating an overall consensus about results and the emerging project. Rather, the challenge is creating coordination between fields of work that may maintain different viewpoints on what the research is all about, throughout the process. An ‘ill structured solution’ does not depend upon forcing all participants into a single frame of reference; instead it relies on objects that allow people to coordinate their work across boundaries (what Star called ‘boundary objects’). Trust Mapping is designed to help practitioners to appreciate the wider institutional ecology in which they work, the interacting frames of reference involved (those, for instance, of product developers, penetration testers, regulators, auditors), the ways in which coordination is achieved, and how that might be done better.


## Funder recognition

Trust Mapping was developed as part of the [Scaling Trust](https://warwick.ac.uk/fac/cross_fac/cim/research/scaling-trust) project, supported by UK Research and Innovation (grant number MR/S037373/1).

## References

Clarke, A. E., & Star, S. L. (2008). The social worlds framework: A theory/methods package. *The handbook of science and technology studies*, 3(0), 113-137.
Dekker, S., & Pruchnicki, S. (2014). Drifting into failure: theorising the dynamics of disaster incubation. *Theoretical Issues in Ergonomics Science*, 15(6), 534-544.
Dindler, C., & Iversen, O. S. (2014). Relational expertise in participatory design. In *Proceedings of the 13th Participatory Design Conference: Research Papers-Volume 1* (pp. 41-50).
Hall, P., Heath, C., & Coles-Kemp, L. (2015). Critical visualization: a case for rethinking how we visualize risk and security. *Journal of cybersecurity*, 1(1), 93-108.
Harrison, S., & Tatar, D. and Sengers, P.(2007). The three paradigms of HCI. In *Alt. Chi. Session at the SIGCHI Conference on Human Factors in Computing Systems San Jose, California* (pp. 1-18).
Heath, C. P., Hall, P. A., & Coles-Kemp, L. (2018). Holding on to dissensus: Participatory interactions in security design. *Strategic Design Research Journal*, 11(2), 65-78.
Kim, G., Humble, J., Debois, P., Willis, J., & Forsgren, N. (2021). *The DevOps handbook: How to create world-class agility, reliability, & security in technology organizations*. IT Revolution.
Schön, D. A. (1983). *The Reflective Practitioner: How professionals think in action*. Routledge.
Star, S. L. (1989). The structure of ill-structured solutions: Boundary objects and heterogeneous distributed problem solving. In *Distributed artificial intelligence* (pp. 37-54). Morgan Kaufmann.
Vaughan, D. (1996). *The Challenger launch decision: Risky technology, culture, and deviance at NASA*. University of Chicago press.
Weick, K. E. (1993). The Collapse of Sensemaking in Organizations: The Mann Gulch Disaster. *Administrative Science Quarterly*, 38(4).
