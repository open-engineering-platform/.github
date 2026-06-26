# Open Engineering Platform

An open platform for engineering investigations, games, performances, and intelligent characters.

The Open Engineering Platform (OEP) provides a common architectural foundation for building engineering systems.

Rather than creating isolated applications, OEP provides:

* a shared Kernel
* a shared Ontology
* multiple specialized Operating Systems
* reusable Capsules
* domain-specific Applications

This allows every project to share a common language while specializing in its own runtime behavior.

⸻

Architecture
```
Open Engineering Platform
│
├── Kernel
│
├── Ontology
│
├── Operating Systems
│
└── Applications
```
⸻

Kernel

The Kernel contains the universal runtime capabilities shared by every application.

Examples include:

* Observation
* Investigation
* Execution
* Evidence
* Events
* Messaging
* Workflow
* Memory
* Reporting
* Capsules

The Kernel intentionally contains only platform primitives.

⸻

Ontology

The Ontology defines the common language spoken throughout the platform.

Examples include:

* Character
* Story
* Journey
* Mission
* Investigation
* Space
* Scene
* System
* Finding
* Capability
* Relationship

Every operating system interprets these concepts according to its own domain while preserving interoperability.

⸻

Operating Systems

Operating Systems specialize the Kernel for different domains.

Detective Operating System (DOS)

The Detective Operating System investigates.

Core concepts include:

* Investigations
* Evidence
* Findings
* Hypotheses
* Verdicts
* Recommendations

Applications include:

* Code Smell Detectives
* Repository Detectives
* Architecture Detectives
* Dependency Detectives
* Cybersecurity Detectives
* Documentation Detectives
* Performance Detectives
* Quality Detectives
* Compliance Detectives

⸻

Game Operating System (GOS)

The Game Operating System manages gameplay.

Core concepts include:

* Players
* Boards
* Spaces
* Turns
* Cards
* Missions
* Scores
* Achievements

Applications include:

* Agility Games
* Future educational and engineering games

⸻

Runner Operating System (ROS)

The Runner Operating System orchestrates time-based execution.

Core concepts include:

* Timelines
* Cues
* Departments
* States
* Triggers
* Transitions
* Performances

Applications include:

* Show Runners
* PKI Runners
* Identity & Access Management Runners
* Future engineering runners

A conference presentation, software demonstration, deployment, or theatrical performance are all viewed as orchestrated performances.

⸻

Star Operating System (SOS)

The Star Operating System gives physical or virtual characters the ability to perform.

Core concepts include:

* Characters
* Motion
* Voice
* Emotion
* Sensors
* Actuators
* Projection
* Interaction

Applications include:

* PixStars
* Snowy Owl
* Anglepoise Lamp
* Future animatronic and virtual characters

⸻

Applications

Applications are concrete implementations built on one or more Operating Systems.

Examples include:
```
Detective Operating System
    ├── Code Smell Detectives
    ├── Repository Detectives
    ├── Architecture Detectives
    └── ...
Game Operating System
    └── Agility Games
Runner Operating System
    ├── Show Runners
    ├── PKI Runners
    ├── IAM Runners
    └── ...
Star Operating System
    ├── PixStars
    ├── Snowy Owl
    └── ...
```
Applications may combine multiple operating systems.

For example:

* A Code Smell Detective investigates software using the Detective Operating System while appearing as an animated character through the Star Operating System.
* PixStars performs through the Star Operating System while being orchestrated by the Runner Operating System.
* A PKI Runner presents a security demonstration using the Runner Operating System and may incorporate animated characters from the Star Operating System.

⸻

Capsules

Capsules provide reusable domain capabilities that can be plugged into any operating system.

Examples include:

* Characters
* Systems Thinking
* Storytelling
* Robotics
* Voice
* Vision
* Memory
* AI
* Simulation

Capsules extend platform capabilities without changing the Kernel.

⸻

Design Principles

The Open Engineering Platform follows several core principles:

* Shared vocabulary through Ontology
* Shared execution through the Kernel
* Specialization through Operating Systems
* Reuse through Capsules
* Composition over duplication
* Loose coupling
* Open by design
* Cloud-native architecture
* Kubernetes-first deployment
* Backstage-native engineering experience

⸻

Vision

The Open Engineering Platform is evolving into a platform where software engineering, systems thinking, investigations, games, performances, and intelligent characters all share the same architectural foundation.

Rather than building isolated solutions, we build reusable operating systems that speak a common language, enabling applications to collaborate, evolve, and compose naturally.

Together, they form an open ecosystem for engineering.
