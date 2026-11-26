# iOPS — Intelligent Operated Power System

**iOPS-RnD** is the GitHub home for the **iOPS — Intelligent Operated Power System** research and development initiative.

iOPS brings together R&D activities, open-source software, synthetic power-system models, data, specifications and shared knowledge supporting the development of intelligent and reliable power-system operation.

The initiative focuses on how power-system engineering, information modelling, semantic technologies, advanced analytics and artificial intelligence can be combined to support the **control room of tomorrow**.

## Focus areas

iOPS activities include:

- power-system analysis and simulation;
- operational decision support;
- Common Information Model (CIM) and standards-based interoperability;
- semantic technologies and knowledge graphs;
- AI and natural-language interaction with power-system information;
- Wide Area Monitoring, Protection and Control (WAMPAC);
- PMU and high-resolution measurement data;
- data quality, validation and conformity assessment;
- DataOps, ModelOps and SchemaOps;
- synthetic and open power-system models;
- digital twins and integration of engineering, asset and operational information.

iOPS is an **umbrella R&D initiative**, not a single project. Individual projects, software components and research assets have their own repositories and lifecycles.

## R&D projects

### [Talk2PowerSystem](https://github.com/statnett/Talk2PowerSystem)

Talk2PowerSystem investigates how knowledge graphs and Large Language Models can allow engineers and applications to interact with CIM-based power-system information using natural language while maintaining traceability, explainability and alignment with industry standards.

The project provides an important technical foundation for several subsequent iOPS activities.

*Status: closed. Hosted by Statnett.*

Related repositories include:

- [`Talk2PowerSystem`](https://github.com/statnett/Talk2PowerSystem) — project documentation, datasets, demonstrations and integration;
- [`Talk2PowerSystem_LLM`](https://github.com/statnett/Talk2PowerSystem_LLM) — Large Language Model and AI components;
- [`Talk2PowerSystem_UI`](https://github.com/statnett/Talk2PowerSystem_UI) — user-interface components.

### Talk2PowerSystem Phase 2

Phase 2 continues the Talk2PowerSystem work. It is planned to be hosted within iOPS-RnD, either by moving the existing repositories or by starting new ones.

*Status: active. Continues [Talk2PowerSystem](https://github.com/statnett/Talk2PowerSystem).*

### [p-SWAMP](https://lfenergy.org/projects/p-swamp/)

**Power Stability Wide Area Monitoring Protection (p-SWAMP)** provides an open and extensible R&D environment for future Wide Area Monitoring, Protection and Control innovation.

The project combines PMU-based monitoring, power-system analysis, advanced decision support and technologies developed through related iOPS activities.

p-SWAMP is maintained through its own project organisation while forming part of the wider iOPS R&D ecosystem. A fork within iOPS-RnD is under consideration.

*Status: active. Hosted by LF Energy. Draws on results from [Talk2PowerSystem](https://github.com/statnett/Talk2PowerSystem).*

Related repositories include:

- `p-SWAMP` (planned) — fork of p-SWAMP within iOPS-RnD, under consideration.

### [INNO4GRID](https://inno4grid.eu/)

INNO4GRID investigates new approaches for power-system supervision and operation, including the use of PMU information, grid-state information and intelligent decision support.

INNO4GRID builds on technology and concepts developed through Talk2PowerSystem and related iOPS activities.

*Status: active. Hosted by the INNO4GRID consortium. Draws on results from [Talk2PowerSystem](https://github.com/statnett/Talk2PowerSystem).*

## Shared research assets

### [Nordic44](https://github.com/statnett/Nordic44)

Nordic44 is a synthetic model of the Nordic high-voltage transmission system represented using the IEC Common Information Model (CIM).

It supports research, interoperability testing, simulation, model validation and demonstrations without exposing operationally sensitive grid information.

The synthetic-model work is evolving towards the next generation of shared Nordic research models within iOPS.

### Nordic-SO

Shared synthetic power-system model, replacing Nordic44.

### resources

The `resources` repository contains information and material intended to be reused across iOPS projects, including:

- common architecture and concepts;
- standards and interoperability guidance;
- reusable diagrams;
- documentation templates;
- examples and demonstrations;
- common data and metadata conventions;
- research and training material;
- iOPS branding and presentation material.

Project-specific information remains in the individual project repositories.

## Shared software and tooling

Several reusable open-source components support more than one iOPS activity.

### [KGraphPy](https://github.com/statnett/KGraphPy)

Python tooling for standards-based knowledge graphs, with particular support for CIM/CGMES data handling, RDF, dataset packaging, metadata and DataOps/ModelOps workflows.

### [KGVerifyPy](https://github.com/statnett/KGVerifyPy)

Python tooling for validation of standards-based knowledge graphs, including SHACL-based validation and validation workflows for CIM/CGMES and related semantic models.

Additional reusable libraries and tools may be moved into or developed directly within the `iOPS-RnD` organisation as the initiative evolves.

## Repository organisation

The intended structure is:

``` text
iOPS-RnD/
│
├── .github
│     Organisation profile and common GitHub community files
│
├── resources                     [PRIVATE]
│     Shared information and reusable resources
│
├── management                    [PRIVATE]
│     iOPS programme coordination and protected information
│
├── Talk2PowerSystem Phase 2 (name to be decided) [PLANNED]
│
├── p-SWAMP                       [PLANNED]
│     fork of p-SWAMP within iOPS-RnD, under consideration
│
└── future R&D projects and shared components
```

Not every project associated with iOPS needs to be hosted directly within this organisation. Projects may have their own GitHub organisations, consortium repositories or other governance arrangements while still collaborating within the iOPS ecosystem.

## Open by design

A key objective of iOPS is to make research results, synthetic data, specifications and reusable software openly available whenever possible.

Open resources make it possible to:

- reproduce research results;
- collaborate across organisations and projects;
- test interoperability;
- provide realistic examples without exposing protected grid information;
- reuse results in subsequent R&D projects;
- engage vendors, universities, research institutes and other system operators.

Information that is operationally sensitive, commercially protected, partner-confidential or otherwise unsuitable for publication is kept outside the public repositories.

## Standards and interoperability

iOPS favours established and open standards wherever practical.

Important technologies and standards include:

- IEC Common Information Model — IEC 61970, IEC 61968 and IEC 62325;
- CGMES and Network Code CIM profiles;
- RDF, RDFS and related semantic-web technologies;
- SHACL;
- JSON-LD;
- SPARQL;
- DCAT;
- PROV-O;
- GeoSPARQL;
- IEC 61850;
- relevant BIM and IFC standards.

The goal is not to create an iOPS-specific information ecosystem, but to demonstrate how existing and emerging standards can be combined in practical power-system R&D.

## Collaboration

iOPS is intended as a collaborative environment.

Individual repositories define their own contribution requirements, governance and licences. Shared organisation-level contribution and security guidance is maintained through the `.github` repository.

Researchers, system operators, universities, technology providers and open-source communities are encouraged to reuse the public results and participate through the relevant project repositories.

## About the name

**iOPS** stands for **Intelligent Operated Power System**.

`iOPS-RnD` is the GitHub organisation used for the research and development activities associated with the iOPS initiative.
