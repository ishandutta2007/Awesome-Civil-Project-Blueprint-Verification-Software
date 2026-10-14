# Awesome-Civil-Project-Blueprint-Verification-Software

# Top Civil Project Blueprint Verification Software Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Automated Clash Detection, Progress Verification & Plan-to-Site Comparison*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Civil Project Blueprint Verification**. These tools scan architectural plans, 3D models, and site photos to detect conflicting utility pipes, verify construction progress against designs, and catch errors before they become expensive rework.

**Examples** include OpenSpace, DroneDeploy, StructionSite, Buildots, Disperse, PlanGrid, Revizto, Procore, Cupix, and Fieldwire (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, IFC-based clash detection, and open construction verification — ideal for BIM coordinators, VDC engineers, and developers seeking transparent, vendor-independent project verification.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[OpenSpace](https://www.openspace.ai/)**  
  360° reality capture platform that automatically maps site photos to floor plans. Features progress tracking, issue documentation, and integration with Procore and other construction management systems.

- **[DroneDeploy](https://www.dronedeploy.com/)**  
  Drone mapping and reality capture platform for construction. Features aerial progress tracking, volumetrics, and site comparison against plans.

- **[StructionSite](https://www.structionsite.com/)**  
  360° documentation and progress tracking platform. Features walkthrough capture, plan overlay, and comparison of as-built conditions to design models.

- **[Buildots](https://www.buildots.com/)**  
  AI-powered progress tracking using 360° cameras mounted on hardhats. Automatically compares captured images to BIM models to detect deviations and delays.

- **[Disperse](https://www.disperse.io/)**  
  Construction progress verification platform using 360° imaging and AI analysis. Tracks site progress against schedule and detects deviations.

- **[PlanGrid (Autodesk)](https://www.plangrid.com/)**  
  Construction field management platform with drawing management, markup, and version comparison. Acquired by Autodesk.

- **[Revizto](https://revizto.com/)**  
  Integrated BIM collaboration platform with clash detection, issue tracking, and 2D/3D coordination.

- **[Procore](https://www.procore.com/)**  
  Construction management platform with document management, drawing comparison, and quality/safety modules.

- **[Cupix](https://www.cupix.com/)**  
  Digital twin platform creating 3D site models from 360° photos. Features virtual site walkthrough and progress comparison.

- **[Fieldwire](https://www.fieldwire.com/)**  
  Field management platform for construction with plan viewing, task management, and punch list tracking.

## Open-Source GitHub Projects

- **[IfcOpenShell](https://github.com/IfcOpenShell/IfcOpenShell)**  
  The foundational open-source library for IFC (Industry Foundation Classes) processing (LGPL-3.0). **1,649+ GitHub stars**. Supports IFC2X3, IFC4, and IFC4.3. Features **clash detection** via IfcClash module, model comparison, conversion to 10+ formats (DAE, GLB, OBJ, SVG), and integration with IDS, BCF, and bSDD. **The most mature open-source BIM library available**, developed since 2011 .

- **[IfcClash](https://github.com/IfcOpenShell/IfcOpenShell/tree/v0.9.0/src/ifcclash)**  
  CLI utility and library for clash detection on IFC models (LGPL-3.0). Clashes defined as clash sets with filters using IFC query syntax. **Supports intersection, collision, and clearance checks**. Configure group A vs group B (e.g., structure vs pipes). Tolerance parameter distinguishes touching from true intersection. Exports to BCF for issue management .

- **[IfcTester](https://github.com/IfcOpenShell/IfcOpenShell/tree/master/src/ifctester)**  
  IFC model auditing tool with Information Delivery Specification (IDS) support (LGPL-3.0). Validates models against IDS requirements for compliance checking .

- **[OpenConstructionERP](https://github.com/datadrivenconstruction/OpenConstructionERP)**  
  Open-source construction ERP (AGPL-3.0) with **multi-disciplinary BIM coordination and AI-assisted issue triage**. Features 3D BIM viewer with federated models, **clash detection** across federated models with clash matrix and BCF export, BOQ management, and 30+ regional standards . Includes floating AI chat with 17 typed tools for querying ERP database including BIM elements .

- **[Open-Field-Studio](https://github.com/OpenAEC-Foundation/Open-Field-Studio)**  
  Open-source field management with 3D BIM viewer (IFC upload via Three.js + web-ifc WASM), photo metadata with GPS coordinates for evidentiary value, and BCF 2.1 export importable in BIMcollab, Revit, and Solibri .

- **[INSPECT](https://fount.aucegypt.edu/etds/2680/)**  
  Open-source node-based framework for federated IFC processing and evaluation (Master's Thesis, AUC). Features **two-phase clash and clearance validation pipeline** using Bounding Volume Hierarchy (BVH) for broad-phase pruning followed by mesh-based narrow-phase evaluation with tolerance. Includes conversational multimodal LLM agent for natural language IFC validation .

- **[multi-utility-conflict-analysis](https://github.com/casondow/multi-utility-conflict-analysis)**  
  GIS-based utility asset management and **conflict-screening** case study (portfolio project). Demonstrates water, gas, and electric utility network modeling with valve isolation analysis, excavation conflict detection, and environmental screening. Built with Python, pandas, and D3 interactive web mapping .

- **[Gravity SDK](https://pypi.org/project/gravity-sdk/)**  
  Python SDK for contextual ad matching (not directly applicable to construction, but demonstrates integration patterns for external API services).

### Additional Strong Open-Source Options

- **[CloudCompare](https://www.cloudcompare.org/)** — 3D point cloud and mesh processing software (GPL-2.0) for comparing as-built scans to design models .
- **[Meshroom](https://github.com/alicevision/meshroom)** — Open-source photogrammetry pipeline (MPL-2.0) for 3D reconstruction from photos.
- **[MicMac](https://github.com/micmacIGN/micmac)** — Free open-source photogrammetry software (927 GitHub stars) for 3D modeling from images .
- **[OpenDroneMap](https://github.com/OpenDroneMap/ODM)** — Open-source toolkit for processing drone imagery into maps and 3D models.
- **[QGIS](https://github.com/qgis/QGIS)** — Open-source GIS (GPL-2.0) for utility conflict analysis and spatial data processing .
- **[GRASS GIS](https://github.com/OSGeo/grass)** — Open-source GIS for geospatial analysis .
- Community **n8n** workflows for clash detection alerting and BCF issue routing automation.

**Frameworks for building custom systems**: Combine **IfcOpenShell + IfcClash** for IFC-based clash detection with **INSPECT** for BVH-accelerated geometric reasoning, **OpenConstructionERP** for BIM coordination and BCF export, **CloudCompare** for point cloud comparison, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade blueprint verification platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Construction verification tools handling project data must comply with contractual requirements and data protection regulations (GDPR, CCPA, etc.).
- **Open-source clash detection is mature for IFC models but limited for photo-based verification.** IfcOpenShell and IfcClash provide production-grade geometric clash detection . Photo-based progress verification comparable to OpenSpace or Buildots requires computer vision pipelines that are not yet available as mature open-source projects.
- **IFC clash detection requires tolerance configuration.** Specifying a non-zero tolerance (e.g., 0.002m) distinguishes between elements merely touching (a GPO on a wall) versus truly intersecting (a pipe through a beam) . Without tolerance, results are noisy.
- **Clearance checks are slower than intersection checks.** Detecting when an element comes near another within a threshold works on non-manifold geometry but is the slowest clash type — typically used for pipes and ducts with insulation, structural openings, and equipment .
- Self-hosted open-source solutions require proper security hardening, IFC model management, and ongoing maintenance. Always validate clash detection results against project-specific coordination standards before issuing RFIs.

---

**Made for BIM coordinators, VDC engineers, construction managers, and developers building transparent project verification solutions.**  
Let's make Civil Project Blueprint Verification more open, data-driven, and clash-free.
