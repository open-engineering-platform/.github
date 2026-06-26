# Open Engineering Platform

An open platform for engineering investigations, games, performances, intelligent characters, and reusable engineering capabilities.

The Open Engineering Platform (OEP) provides a common architectural foundation for building engineering systems that share a common language while remaining independently evolvable.

Rather than building isolated applications, OEP provides:

* a shared Kernel
* a shared Ontology
* specialized Operating Systems
* reusable Capsules
* composable Applications
* a common Product Model
* federated Systems of Record

Together these form a platform where engineering, investigations, storytelling, performances, and intelligent characters can evolve as a coherent ecosystem.

⸻

Architecture

The Open Engineering Platform consists of several complementary layers.
```
Open Engineering Platform
│
├── Architecture Models
│
├── Kernel
│
├── Ontology
│
├── Operating Systems
│
├── Capsules
│
└── Applications
```
Each layer answers a different architectural question.

The Kernel defines execution.

The Ontology defines meaning.

Operating Systems specialize behavior.

Capsules provide reusable capabilities.

Applications deliver end-user value.

The Architecture Models connect all of these through common planning and governance.

⸻

Three Complementary Architecture Models

The Open Engineering Platform intentionally separates three complementary architectural models.

Each model answers a different question.

Together they provide a complete foundation for designing, building, evolving, governing, and operating engineering systems.

1. Ontology Model — What exists?

The Ontology defines the shared vocabulary of the platform.

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

Every Operating System interprets these concepts according to its own domain while preserving interoperability.

The Ontology provides semantic consistency across the entire platform.

⸻

2. Product Model — How does it evolve?

The Product Model describes how ideas become working software.
```
Portfolio
│
└── Product
    │
    ├── Vision
    ├── Objectives
    ├── Roadmap
    ├── Releases
    ├── Epics
    ├── Features
    ├── Stories
    └── Tasks
```
Every Solution, Capsule, Character, and Operating System evolves through this shared planning model.

The Product Model is independent of implementation technology.

⸻

3. Systems of Record Model — Where is the truth maintained?

The platform deliberately distributes responsibility across specialized systems.

Each system owns one concern exceptionally well.
```
System	Responsibility
Craft.io	Product Management
GitHub	Source Code & Engineering
Backstage	Software Catalog
Detective Operating System	Engineering Evidence
Kubernetes	Runtime
Crossplane	Infrastructure Provisioning
Identity & Access Management Runners	Identity
Documentation	Knowledge
MCP	AI Context Exchange
```
Rather than centralizing all information into one platform, the Open Engineering Platform federates specialized Systems of Record around a common Ontology and Product Model.

⸻

How the Three Models Work Together
```
                Open Engineering Platform
                    Ontology Model
                 (What things are)
                          │
                          ▼
                   Product Model
          (How things are planned)
                          │
                          ▼
               Systems of Record
        (Where authoritative information lives)
                          │
                          ▼
                 Engineering Reality
```
For example:

* The Ontology defines what a Character, Capsule, Runner, Detective, or Investigation is.
* The Product Model defines how those concepts evolve through MVPs, Releases, Features, and Stories.
* The Systems of Record define where authoritative information is maintained, such as Craft.io for planning, GitHub for engineering, Backstage for software catalog information, and Detective Operating System for engineering evidence.

Separating these concerns keeps the platform modular, extensible, and technology-independent.

⸻

Kernel 

The Kernel contains the universal runtime capabilities shared by every application.

It intentionally contains only platform primitives.

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
* Capsule Management

Every Operating System extends the Kernel without modifying its fundamental behavior.

⸻

Ontology

The Ontology provides the common language spoken throughout the platform.

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

This common vocabulary enables interoperability across products while allowing every Operating System to specialize these concepts for its own domain.

⸻

## Operating Systems

Operating Systems specialize the Kernel for different domains.

Each Operating System shares the same Kernel and Ontology while introducing domain-specific runtime behavior.

Operating Systems are independent, reusable, and composable.

Applications may use one or many Operating Systems simultaneously.

⸻

Detective Operating System (DOS)

The Detective Operating System specializes in engineering investigations.

Its purpose is to transform observations into evidence-based recommendations.

Core concepts include:

* Investigations
* Evidence
* Findings
* Hypotheses
* Verdicts
* Recommendations
* Reports
* Repository Analysis

Typical applications include:
```
Detective Operating System
├── Code Smell Detectives
├── Repository Detectives
├── Architecture Detectives
├── Dependency Detectives
├── Cybersecurity Detectives
├── Documentation Detectives
├── Performance Detectives
├── Quality Detectives
└── Compliance Detectives
```
Every Detective specializes in a specific engineering discipline while sharing the same investigation model.

⸻

Game Operating System (GOS)

The Game Operating System provides reusable gameplay capabilities.

Rather than building games individually, reusable mechanics become platform capabilities.

Core concepts include:

* Players
* Boards
* Worlds
* Spaces
* Cards
* Missions
* Journeys
* Scores
* Achievements
* Progress

Applications include:
```
Game Operating System
├── Agility Game
├── Educational Games
├── Learning Simulations
└── Future Engineering Games
```
The Game Operating System transforms engineering activities into interactive learning experiences.

⸻

Runner Operating System (ROS)

The Runner Operating System orchestrates time-based execution.

Anything that unfolds over time can be represented as a Runner.

Examples include:

* conference presentations
* engineering demonstrations
* theatrical performances
* deployment pipelines
* PKI demonstrations
* educational workshops

Core concepts include:

* Timelines
* Cues
* Departments
* States
* Triggers
* Events
* Synchronization
* Performances

Applications include:
```
Runner Operating System
├── Show Runners
├── PKI Runners
├── Identity & Access Management Runners
├── Deployment Runners
└── Future Engineering Runners
```
The Runner Operating System coordinates events without knowing their domain-specific meaning.

⸻

Star Operating System (SOS)

The Star Operating System gives physical and virtual characters the ability to perform.

Rather than focusing on robotics alone, it provides reusable capabilities for any character-driven experience.

Core concepts include:

* Characters
* Motion
* Voice
* Emotion
* Sensors
* Actuators
* Projection
* Interaction
* Animation
* Presence

Applications include:
```
Star Operating System
├── PixStars
├── Anglepoise Lamp
├── Snowy Owl
├── Code Smell Detective
└── Future Characters
```
The Star Operating System allows Characters to evolve independently from the products that use them.

⸻

Applications

Applications combine one or more Operating Systems to solve specific problems.

Examples include:
```
Detective Operating System
    ├── Code Smell Detectives
    ├── Repository Detectives
    ├── Architecture Detectives
    └── ...
Game Operating System
    ├── Agility Game
    └── ...
Runner Operating System
    ├── Show Runners
    ├── PKI Runners
    ├── IAM Runners
    └── ...
Star Operating System
    ├── PixStars
    ├── Snowy Owl
    ├── Anglepoise Lamp
    └── ...
```
Applications are composed rather than inherited.

Examples include:

Code Smell Detective

Uses:

* Detective Operating System
* Star Operating System

The Detective investigates repositories while appearing as an animated character.

⸻

PixStars

Uses:

* Star Operating System
* Runner Operating System

PixStars performs as an intelligent character while synchronized through Show Runners.

⸻

Agility Game

Uses:

* Game Operating System
* Detective Operating System

Players investigate engineering challenges while progressing through gameplay mechanics.

⸻

PKI Runner

Uses:

* Runner Operating System
* Star Operating System

A technical presentation is orchestrated as a performance and may include intelligent characters explaining PKI concepts.

⸻

Capsules

Capsules provide reusable engineering capabilities that can be shared across Operating Systems and Applications.

Unlike Operating Systems, Capsules are optional.

They extend the platform without modifying the Kernel.

Examples include:
```
Capsules
├── Character
├── Systems Thinking
├── Story
├── Robotics
├── Voice
├── Vision
├── Memory
├── Artificial Intelligence
├── Simulation
├── Identity
├── Documentation
└── Future Capsules
```
A single Capsule may be reused by many Applications.

For example, the Character Capsule may be consumed by:

* PixStars
* Code Smell Detective
* Snowy Owl
* Future educational characters

⸻

Composition

The Open Engineering Platform encourages composition over duplication.

Example:
```
PixStars
├── Star Operating System
├── Runner Operating System
├── Character Capsule
├── Story Capsule
├── Voice Capsule
└── Systems Thinking Capsule
```
Every capability is developed once and reused wherever appropriate.

⸻

Federated Systems of Record

The Open Engineering Platform deliberately separates ownership of information.

Each platform specializes in one responsibility.
```
Craft.io
        Product Planning
GitHub
        Engineering
Backstage
        Software Catalog
Detective Operating System
        Engineering Evidence
Crossplane
        Infrastructure
Kubernetes
        Runtime
Documentation
        Knowledge
MCP
        AI Context Exchange
```
Rather than copying information between systems, they collaborate through references, integrations, and shared identifiers.

This architecture minimizes duplication while maximizing traceability.

⸻

Design Principles

The Open Engineering Platform follows several guiding principles.

Shared Meaning

Every solution speaks the same architectural language.

⸻

Shared Execution

Operating Systems build upon a common Kernel.

⸻

Specialization

Operating Systems specialize rather than duplicate behavior.

⸻

Reuse

Reusable capabilities are packaged as Capsules.

⸻

Composition

Applications compose capabilities rather than reimplement them.

⸻

Loose Coupling

Every subsystem evolves independently.

⸻

Evidence-Driven Engineering

Engineering decisions are supported by investigations rather than assumptions.

⸻

Product-Centric Planning

Solutions evolve through a shared Product Model independent of implementation technology.

⸻

Federated Ownership

Every System of Record owns one concern exceptionally well.

⸻

AI-Native

AI assistants operate from shared context while preserving human accountability.

⸻

Vision

The Open Engineering Platform is evolving into an open ecosystem where engineering investigations, systems thinking, games, performances, intelligent characters, and reusable platform capabilities share a common architectural foundation.

Rather than building isolated software products, the platform enables the creation of reusable Operating Systems, Capsules, and Applications that speak a common language and evolve through a shared Product Model.

By separating meaning (Ontology), planning (Product Model), and ownership (Federated Systems of Record), the platform remains modular, extensible, and technology-independent while supporting collaboration between people, software systems, intelligent characters, and AI assistants.

Together, these elements form an open engineering ecosystem where solutions can be composed, investigated, performed, and continuously improved through shared architecture and evidence-based evolution.

___
