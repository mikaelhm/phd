Modal and Component-Based System Specifications
===
**By Mikael H. Møller at Department of Computer Science, Aalborg University.**

This repository contains my thesis, and the presentation used in the Ph.d. lecture (including sources).
The presentation can be accessed here: http://mikaelhm.github.io/phd


- Handed in:  September 9th, 2013.
- Defence and lecture: December 16th, 2013.

**Abstract:**
Formal methods are not always applicable in software system design processes. We aim at improving this by extending existing abstract modelling formalisms. The main problem is that existing system specification formalisms is not always capable of modelling the actual system behaviour and concepts at the required abstraction level. Furthermore, the existing frameworks often do not scale to larger and more complex software systems.

We study extensions of *Modal Transition Systems*(MTS), a system modelling framework that support system refinements. This is beneficial in the design process where the system is designed gradually from a loose specification into a complete system specification with a fixed implementation behaviour. 

Initially, we extend the MTS framework with a set of parameters that enable system designers to express persistency in their system models. Second, we extend the model with time and cost measures, that can then be used to analyse the implementation cost and average running cost. Early in a development process such analysis can assist the designers to keep their system within a given budget. Finally, we equip this extended MTS framework with a logic for expressing system requirements. This logic can be used by designers to verify whether their system model meet given requirements. In case, the system model  is parametrised it can also clarify for which configurations, the requirements will be met.

We also study communication properties in a component-based design approach. Component-based design is favourable when designing large and complex systems as it splits the system into communicating components. This gives a better overview, but causes a new problem, namely ensuring that the composition of the components is correct. We study a series of communication properties of asynchronously composed Petri nets and prove that these channel properties are preserved by asynchronous composition. This means that the modelling framework support incremental design. Furthermore, we prove that all the properties are decidable for our asynchronous I/O Petri nets.

Finally, we extend the asynchronous I/O Petri nets with modalities. This gives us a formal modelling framework with the advantages from MTS, where we can still reason about channel properties even during the refinement process. With all these results, we present a methodology for the specification of distributed systems that supports incremental design, encapsulation of components and stepwise refinement.

