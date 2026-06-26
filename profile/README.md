# Open Engineering Platform

An open platform for engineering investigations, games, performances, intelligent characters, and reusable engineering capabilities.

The Open Engineering Platform (OEP) provides a common architectural foundation for building engineering systems that share a common language while remaining independently evolvable.

Rather than creating isolated applications, OEP provides:

* a shared Kernel
* a shared Ontology
* specialized Operating Systems
* reusable Capsules
* intelligent AI Assistants
* composable Applications
* a common Product Model
* federated Systems of Record

Together these form an open engineering ecosystem where software, investigations, performances, games, and intelligent characters can evolve through a common architectural foundation.

⸻

Architecture

The Open Engineering Platform intentionally separates its architecture into multiple complementary dimensions.

Each dimension answers a different architectural question.

Together they provide a complete foundation for designing, planning, implementing, operating, and evolving engineering systems.
```
Open Engineering Platform
│
├── Architecture Dimensions
│   │
│   ├── Ontology
│   ├── Product Model
│   ├── Systems of Record
│   └── Runtime Architecture
│
├── Kernel
├── Ontology
├── Operating Systems
├── Capsules
├── AI Assistants
├── Applications
└── Systems of Record
```
⸻

Four Complementary Architecture Dimensions

The Open Engineering Platform intentionally separates four complementary architectural dimensions.

Each dimension answers a different architectural question.

Together they provide a complete foundation for building reusable engineering systems.

⸻

1. Ontology — What exists?

The Ontology defines the shared language of the platform.

Examples include:

* Character
* Story
* Journey
* Mission
* Investigation
* Space
* Scene
* System
* Capability
* Finding
* Relationship

Every Operating System interprets these concepts according to its own domain while preserving interoperability.

The Ontology provides semantic consistency across the entire ecosystem.

⸻

2. Product Model — How does it evolve?

The Product Model describes how engineering ideas evolve into working solutions.

Every Solution, Capsule, Character, and Operating System follows the same planning lifecycle.
```
Portfolio
│
└── Product
    │
    ├── Vision
    ├── Objectives
    ├── Roadmap
    ├── MVPs
    ├── Releases
    ├── Epics
    ├── Features
    ├── Stories
    └── Tasks
```
The Product Model is independent of implementation technology.

This allows engineering, robotics, games, performances, and investigations to evolve through a common planning process.

⸻

3. Systems of Record — Where is authoritative information maintained?

The Open Engineering Platform deliberately avoids centralizing every concern into one tool.

Instead, specialized platforms own specific responsibilities.
```
Platform	Responsibility
Craft.io	Product Management
GitHub	Engineering
Backstage	Software Catalog
Detective Operating System	Engineering Evidence
Kubernetes	Runtime
Crossplane	Infrastructure Provisioning
Identity & Access Management Runners	Identity
Documentation Repositories	Knowledge
MCP	AI Context Exchange
```
Every system owns one concern exceptionally well.

Rather than duplicating information, these systems collaborate through references, integrations, and shared identifiers.

⸻

4. Runtime Architecture — How does it execute?

The Runtime Architecture defines how software executes.

It consists of reusable runtime building blocks.
```
Kernel
↓
Operating Systems
↓
Capsules
↓
Applications
```
Each layer has a distinct responsibility.

The Kernel provides universal execution primitives.

Operating Systems specialize runtime behavior.

Capsules provide reusable capabilities.

Applications compose these capabilities into complete engineering solutions.

The Runtime Architecture is independent of both the Product Model and the Systems of Record.

⸻

How the Four Dimensions Work Together

The four dimensions complement one another.
```
                Open Engineering Platform
                    Ontology
                 (What exists?)
                          │
                  Product Model
              (How it evolves?)
                          │
               Systems of Record
      (Where authoritative information lives?)
                          │
               Runtime Architecture
           (How things execute?)
                          │
                Engineering Reality
```
For example:

* The Ontology defines what a Character, Detective, Runner, Capsule, or Investigation is.
* The Product Model defines how those concepts evolve through Objectives, MVPs, Releases, Features, and Stories.
* The Systems of Record determine where authoritative information is maintained, such as Craft.io for planning, GitHub for engineering, Backstage for software catalog information, and the Detective Operating System for engineering evidence.
* The Runtime Architecture defines how those concepts execute through the Kernel, Operating Systems, Capsules, and Applications.

Keeping these dimensions separate enables the platform to remain modular, extensible, and technology-independent.

⸻

Kernel

The Kernel contains the universal runtime capabilities shared by every Operating System and Application.

The Kernel intentionally remains minimal.

It contains only platform primitives that are universally useful across engineering domains.

Examples include:

* Observation
* Investigation
* Execution
* Events
* Messaging
* Workflow
* Memory
* Evidence
* Reporting
* Composition

The Kernel does not contain domain-specific behavior.

Instead, Operating Systems extend the Kernel with specialized capabilities while preserving a common execution model.

This separation allows every application in the Open Engineering Platform to share the same runtime foundation while evolving independently.



