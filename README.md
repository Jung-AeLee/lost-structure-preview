# LOST — Data-Driven Particle Field Framework

This repository provides a structural preview of the LOST framework.
The complete commercial package is available separately.

A JavaScript particle engine refactored from an original ActionScript architecture.
Designed to demonstrate frame-owned time and coefficient-based interpretation in real-time systems.

This is not a visual effect template.
It is a structural experiment in data ownership and engine boundaries.

Microphone (Input devices) doesn’t create time.
It is only sampled within it.

The loop owns time.
The system owns interpretation.

------------

## Core Principles

- No module owns time except the frame loop.

- Media does not transport narrative time.

- Sound is not a playback state — it is injected amplitude.

- Color is not decoration — it is a computational coordinate.

- State is replaced by framed conditions and recorded history.

------------

## Architecture

```
flowchart TB

EngineStage["EngineStage (Frame Owner)"]
StageLost["StageLost (Assembler)"]
VideoTransport["VideoTransport (Media Time Owner)"]
AudioInput["AudioInput (Amplitude Source)"]
ParticleSystem["Particle System (Data Entity Field)"]
Renderer["Renderer (Projection Layer)"]

EngineStage ==> StageLost
VideoTransport ==> StageLost
AudioInput ==> StageLost

StageLost ==> ParticleSystem
StageLost ==> Renderer

classDef heavy fill:#fff,stroke:#000,stroke-width:4px;
class EngineStage,VideoTransport heavy;

linkStyle default stroke-width:3px;
```

## What This Framework Demonstrates

- Frame-owned time architecture

- Ratio-based interpretation instead of state branching

- Object pooling with structural reset

- Particle history as framed state (not state machine)

- Replaceable renderer layer (Bitmap / GPU-ready)

------------

## Folder Structure

```
src/
│
├── engine/
│
├── particle/
│
├── library/
│
├── media/
│
├── render/
│
└── color/

index.html
```

Modular and replaceable.

------------

## Quick Start

```
npx server .
```

or

```
npm install
npm run dev
```

Open in browser (ES Module required).

------------

## Use Cases

- Generative media systems

- Data-driven installations

- Audio-reactive visual systems

- Engine boundary experimentation

- Educational architecture examples

## License

This repository is released under the LOST Preview License.
See LICENSE file for details.

------------

## Related Work

Engine Scope — Beyond Patterns
Available on Google Books.

```text
LOST Preview License
Copyright (c) 2026 Jung-Ae Lee

This repository is provided for architectural demonstration and educational purposes only.

Permission is granted to:
- View and study the source code.
- Modify the code for personal, non-commercial experimentation.
- Use the code for educational reference.

The following are NOT permitted without explicit written permission:
- Commercial redistribution of this repository or its derivatives.
- Resale of the source code in whole or in part.
- Use of this repository as a production-ready commercial product.
- Republishing the code as part of another commercial framework or engine.

This repository represents a structural preview of the LOST framework.

The production-ready distributed version,
including optimized performance modules,
audio integration layers,
and extended renderer implementations,
is released separately under a commercial license.

For commercial licensing inquiries:
Contact: postinsight@naver.com

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

------------

## Distribution Model

This repository exposes the architectural structure of LOST for reference purposes.

The production-ready package — including demos, optimized modules, audio integration, performance enhancements, and additional commercial features — is distributed separately.

The commercial distribution contains modules and optimizations that are not included in this repository.


