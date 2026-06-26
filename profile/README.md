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

