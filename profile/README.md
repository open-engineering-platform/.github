# Open Engineering Platform

Open standards, APIs, contracts, CRDs, and SDKs for engineering worlds, activities, skills, missions, agents, detectives, and control planes.

⸻

Vision

Open Engineering Platform (OEP) provides the shared foundation for building Kubernetes-native engineering platforms.

OEP defines the common language used by systems such as:

* Detective Operating System
* Agility Game
* Repository World
* Repository Skills
* Repository Activities
* Future engineering platforms

OEP does not execute missions.

OEP defines the APIs, contracts, schemas, and Kubernetes resources that make mission execution possible.

⸻

Core Principle

Define once.

Implement everywhere.

A concept shared by multiple platforms belongs in Open Engineering Platform.

⸻

Platform Architecture
```
Applications
│
├── Code Smell Detective
├── Architecture Detective
├── Dependency Detective
├── Cybersecurity Detective
├── PixStars
├── PKIStars
└── Future Applications
│
▼
Runtime Platforms
│
├── Detective Operating System
└── Agility Game
│
▼
Domain Platforms
│
├── Repository World
├── Repository Skills
└── Repository Activities
│
▼
Open Engineering Platform
```
⸻

Kubernetes Native by Design

Open Engineering Platform adopts Kubernetes as its primary platform abstraction.

Core concepts are represented as Kubernetes resources.

Examples:
```
kind: World
kind: Skill
kind: Activity
kind: Mission
kind: Detective
kind: Detector
kind: CaseFile
```
These resources form the API surface of the platform.

⸻

Crossplane First

Open Engineering Platform embraces Crossplane from the beginning.

Crossplane enables the platform to define:

* Custom Resources
* Compositions
* Control Planes
* Declarative APIs

The platform is designed around reconciliation rather than orchestration.

⸻

Core Concepts

Worlds

Worlds model environments.

Examples:

* Repository World
* GitHub World
* Kubernetes World
* Terraform World
* Azure World

⸻

Skills

Skills model reusable capabilities.

Examples:

* Repository Reader
* Code Navigation
* Dependency Analysis
* Reporting

⸻

Activities

Activities model events occurring within worlds.

Examples:

* Commit Pushed
* Pull Request Opened
* Pull Request Merged
* Release Published

⸻

Missions

Missions describe goals.

Examples:

* Analyze Repository
* Review Pull Request
* Validate Deployment

⸻

Detectives

Detectives investigate missions.

Examples:

* Code Smell Detective
* Architecture Detective
* Dependency Detective

⸻

Detectors

Detectors generate evidence.

Examples:

* God Object Detector
* Dependency Detector
* Security Detector

⸻

Case Files

Case Files contain investigation results.

⸻

Repositories

Foundation

* contracts
* crds
* schemas
* sdk-kotlin
* sdk-python
* architecture

⸻

Technology Strategy

Kotlin Multiplatform

Primary platform language.

Used for:

* Contracts
* SDKs
* Controllers
* Runtime integrations
* Shared models

⸻

Python

Primary analysis language.

Used for:

* Detectors
* AI integrations
* Experimental analysis engines

⸻

Kubernetes

Primary runtime platform.

⸻

Crossplane

Primary control plane framework.

⸻

Relationship to Detective Operating System

Detective Operating System is a Kubernetes-native control plane built on Open Engineering Platform.

DOS implements the APIs defined by OEP.

⸻

Relationship to Agility Game

Agility Game is a gameplay platform built on Open Engineering Platform.

Agility Game consumes the same APIs while interpreting them through game mechanics.

⸻

Long-Term Goal

Create an ecosystem of interoperable engineering platforms built upon a shared set of Kubernetes-native APIs and contracts.

The goal is not a single platform.

The goal is a shared language that allows many platforms to evolve independently while remaining compatible.
