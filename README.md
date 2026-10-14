# Awesome-Civil-Project-Blueprint-Verification-Software

## Top Civil Project Blueprint Verification Software Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Automated Clash Detection, Progress Verification & Plan-to-Site Comparison*  

**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Civil Project Blueprint Verification**. These tools scan architectural plans, 3D models, and site photos to detect conflicting utility pipes, verify construction progress against designs, and catch errors before they become expensive rework.

**Open-source emphasis**: This section features active projects for self-hosting, IFC-based clash detection, point cloud verification, photogrammetry, and open construction verification — ideal for BIM coordinators, VDC engineers, and developers seeking transparent, vendor-independent project verification.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Sector Overview & Market Dynamics

The global construction management and reality verification software sector is estimated at **$10.8B to $11.7B in 2025** and projected to reach **$12B+ in 2026**, growing at a CAGR of ~9–10%. The sector remains **moderately to highly fragmented** rather than winner-take-all: while enterprise titans like Autodesk and Procore command broad workflow hubs, hundreds of specialized point-solution vendors thrive in 360° reality capture, AI computer vision progress auditing, and automated geometric clash detection.

---

## SaaS/Hosted Platforms

The table below lists leading commercial platforms, sorted in descending order by estimated company size (market capitalization, private valuation, or acquisition enterprise value).

| Product | Company Size / Valuation | Starting Pricing | Free Tier / Trial Limits | Key Verification Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Autodesk Build](https://www.autodesk.com/products/autodesk-build/overview)** *(formerly PlanGrid)* | **~$49B Market Cap** *(NASDAQ: ADSK; $7.2B FY26 Revenue)* | **$67/user/month** (Build Essentials billed annually) or **$117/user/month** (Build Unlimited) | **30-day free trial**; full platform access, no credit card required | 2D/3D sheet comparison, plan version markup, automated clash issue tracking via Autodesk Construction Cloud |
| **[Procore](https://www.procore.com/)** | **~$8.0B Market Cap** *(NYSE: PCOR; $1.3B FY25 Revenue)* | **~$375/month** (~$4,500/year base tier scaled by Annual Construction Volume) | **14-day guided proof-of-concept trial** upon sales request; no permanent free tier | Comprehensive drawing overlay & revision comparison, BIM coordination, quality/safety discrepancy tracking |
| **[OpenSpace](https://www.openspace.ai/)** | **~$902M Valuation** *(Series D; acquired Disperse)* | **~$833/month** (~$10,000/year minimum contract based on Annual Construction Volume) | **No permanent free tier**; interactive sandbox demo and project evaluation pilots available on request | Automated 360° site walk mapping to 2D floor plans & BIM; AI-driven progress tracking (OpenSpace Track) |
| **[DroneDeploy](https://www.dronedeploy.com/)** *(incl. StructionSite)* | **$845M Acquisition Value** *(Acquired by Procore in 2026)* | **$349/month** ($4,188/year billed annually for Individual Plan) | **14-day free trial**; aerial mapping, 360 walkthroughs, demo data access, no credit card required | Aerial drone photogrammetry, automated cut/fill volume inspection, 360° interior walkthrough alignment to BIM |
| **[Buildots](https://www.buildots.com/)** | **~$1.0B Valuation** *(Valued near $1B after $130M Series C round in 2026)* | **Custom quote** (contracts scale per project duration, typically starting at ~$2,500–$5,000/project/month) | **No permanent free tier or self-serve free trial**; scheduled live pilot/custom sandbox demonstration | Hardhat-mounted 360° AI tracking comparing site progress directly against BIM schedules and trade models |
| **[Fieldwire](https://www.fieldwire.com/)** *(by Hilti)* | **Acquired for $300M** *(Acquired by Hilti Group)* | **$39/user/month** (Pro plan billed annually) or $54/user/month billed monthly | **Free forever plan**: max 5 users, up to 3 projects, and limit of 100 sheets total | Blueprint viewing and version comparison, on-site task allocation, punch-list clash verification |
| **[Cupix](https://www.cupix.com/)** | **~$156M Valuation** *($39M Series C funding)* | **$24/month** (Basic paid workspace tier; scales up to $190/mo for larger capacities) | **Free forever tier** (limited to 1 workspace, 3 GB storage, 3D tour viewer) + **30-day full-feature trial** | CupixWorks 3D digital twin spatial intelligence, 360° plan-to-scan deviation analysis, coordinate mesh overlay |
| **[Revizto](https://revizto.com/)** | **~$30M Annual Revenue** *(Private, bootstrapped growth)* | **Custom quote** (structured enterprise tier, historically starting at ~$5,000/year for team pools) | **Free local viewer** (Revizto Viewer application forever free for inspection); cloud sync requires pilot demo | Issue tracking, federated model clash detection, BCF collaboration, 2D/3D coordination on mobile/desktop |

---

## Open-Source GitHub Projects

The table below lists open-source projects for blueprint verification, IFC geometric validation, point-cloud comparison, and spatial clash analysis. The list is sorted in descending order by GitHub star count, with badges linking directly to each repository's stargazers page.

| Repository | Stars | License | Description & Role in Verification |
| :--- | :--- | :--- | :--- |
| **[FreeCAD](https://github.com/FreeCAD/FreeCAD)** | [![Stars](https://img.shields.io/github/stars/FreeCAD/FreeCAD?style=social&color=white)](https://github.com/FreeCAD/FreeCAD/stargazers) | LGPL-2.0-or-later | General-purpose parametric 3D CAD modeler with dedicated BIM and Arch workbenches. Capable of importing IFC models, checking geometrical intersections, and validating structural elements against design blueprints. |
| **[QGIS](https://github.com/qgis/QGIS)** | [![Stars](https://img.shields.io/github/stars/qgis/QGIS?style=social&color=white)](https://github.com/qgis/QGIS/stargazers) | GPL-2.0-or-later | Enterprise-grade Geographic Information System (GIS) used for geospatial utility conflict detection, civil topography verification, underground right-of-way easement validation, and cadastral blueprint overlays. |
| **[Meshroom](https://github.com/alicevision/meshroom)** | [![Stars](https://img.shields.io/github/stars/alicevision/meshroom?style=social&color=white)](https://github.com/alicevision/meshroom/stargazers) | MPL-2.0 | 3D photogrammetry pipeline based on AliceVision framework. Converts construction site survey photos and drone sweeps into detailed 3D textured surface meshes to compare as-built reality against initial blueprints. |
| **[OpenDroneMap (ODM)](https://github.com/OpenDroneMap/ODM)** | [![Stars](https://img.shields.io/github/stars/OpenDroneMap/ODM?style=social&color=white)](https://github.com/OpenDroneMap/ODM/stargazers) | GPL-3.0 | Open-source drone photogrammetry and mapping engine. Generates geo-referenced orthophotos, digital elevation models (DEM), and 3D point clouds from aerial site captures to inspect site grading against civil plans. |
| **[Potree](https://github.com/potree/potree)** | [![Stars](https://img.shields.io/github/stars/potree/potree?style=social&color=white)](https://github.com/potree/potree/stargazers) | BSD-2-Clause | High-performance WebGL-based point cloud renderer for large LiDAR scans. Allows web-based coordinate slicing, volumetric measuring, and visual inspection of as-built point clouds overlaid on blueprints. |
| **[CloudCompare](https://github.com/CloudCompare/CloudCompare)** | [![Stars](https://img.shields.io/github/stars/CloudCompare/CloudCompare?style=social&color=white)](https://github.com/CloudCompare/CloudCompare/stargazers) | GPL-2.0 | Essential 3D point cloud and triangular mesh processing tool. Features point-to-mesh geometric comparison algorithms to detect millimeter-level deviations between as-built laser scans and design models. |
| **[IfcOpenShell](https://github.com/IfcOpenShell/IfcOpenShell)** | [![Stars](https://img.shields.io/github/stars/IfcOpenShell/IfcOpenShell?style=social&color=white)](https://github.com/IfcOpenShell/IfcOpenShell/stargazers) | LGPL-3.0 | The foundational open-source library and toolkit for IFC processing. Features the **IfcClash** module for intersection, collision, and clearance checks, and **IfcTester** for auditing models against Information Delivery Specifications (IDS). |
| **[PDAL](https://github.com/PDAL/PDAL)** | [![Stars](https://img.shields.io/github/stars/PDAL/PDAL?style=social&color=white)](https://github.com/PDAL/PDAL/stargazers) | BSD-3-Clause | Point Data Abstraction Library for translating, filtering, and processing point cloud datasets (LAS/LAZ, E57). Crucial for preparing raw LiDAR scans for automated geometric variance screening. |
| **[GRASS GIS](https://github.com/OSGeo/grass)** | [![Stars](https://img.shields.io/github/stars/OSGeo/grass?style=social&color=white)](https://github.com/OSGeo/grass/stargazers) | GPL-2.0-or-later | Geospatial processing system capable of digital terrain modeling, hydrological surface analysis, and infrastructure alignment clash auditing against civil design blueprints. |
| **[OpenConstructionERP](https://github.com/datadrivenconstruction/OpenConstructionERP)** | [![Stars](https://img.shields.io/github/stars/datadrivenconstruction/OpenConstructionERP?style=social&color=white)](https://github.com/datadrivenconstruction/OpenConstructionERP/stargazers) | AGPL-3.0 | Construction management ERP with multi-disciplinary 3D BIM coordination, federated model clash matrices, BCF issue exporting, and AI database querying for blueprint verification. |
| **[That Open Engine Components](https://github.com/ThatOpen/engine_components)** | [![Stars](https://img.shields.io/github/stars/ThatOpen/engine_components?style=social&color=white)](https://github.com/ThatOpen/engine_components/stargazers) | Mozilla Public License 2.0 | Modular Web-BIM engine (formerly IFC.js components) for building browser-based BIM coordination apps, real-time IFC model slicing, property querying, and geometric clash highlighting. |
| **[MicMac](https://github.com/micmacIGN/micmac)** | [![Stars](https://img.shields.io/github/stars/micmacIGN/micmac?style=social&color=white)](https://github.com/micmacIGN/micmac/stargazers) | CeCILL-B | Scientific-grade open-source photogrammetry suite developed by the French National Institute of Geographic and Forest Information (IGN), delivering high-precision 3D reconstruction for site verification. |
| **[buildingSMART BCF-XML](https://github.com/buildingSMART/BCF-XML)** | [![Stars](https://img.shields.io/github/stars/buildingSMART/BCF-XML?style=social&color=white)](https://github.com/buildingSMART/BCF-XML/stargazers) | MIT | The official XML/REST schema repository for the BIM Collaboration Format (BCF). Standardizes how blueprint clashes, geometric discrepancies, and verification issues are communicated across tools. |
| **[Open-Field-Studio](https://github.com/OpenAEC-Foundation/Open-Field-Studio)** | [![Stars](https://img.shields.io/github/stars/OpenAEC-Foundation/Open-Field-Studio)](https://github.com/OpenAEC-Foundation/Open-Field-Studio/stargazers) | MIT | Open-source field inspection platform with 3D BIM viewer (web-ifc WASM), geo-tagged photo verification, and BCF 2.1 export for reconciling site photos with design models. |
| **[multi-utility-conflict-analysis](https://github.com/casondow/multi-utility-conflict-analysis)** | [![Stars](https://img.shields.io/github/stars/casondow/multi-utility-conflict-analysis)](https://github.com/casondow/multi-utility-conflict-analysis/stargazers) | MIT | GIS utility asset management and conflict-screening framework analyzing water, gas, and electric networks for excavation and clearance clashes. |

---

### Key Specialized Sub-modules & Frameworks

- **[IfcClash](https://github.com/IfcOpenShell/IfcOpenShell/tree/v0.9.0/src/ifcclash)** — Sub-module of IfcOpenShell for automated IFC clash detection with tolerance and clearance filters. Exports directly to BCF.
- **[IfcTester](https://github.com/IfcOpenShell/IfcOpenShell/tree/master/src/ifctester)** — Sub-module of IfcOpenShell for automated compliance auditing against Information Delivery Specifications (IDS).
- **[INSPECT](https://fount.aucegypt.edu/etds/2680/)** — Academic open-source framework utilizing Bounding Volume Hierarchy (BVH) broad-phase pruning and mesh narrow-phase tolerance evaluation for federated IFC models.

---

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

---

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Construction verification tools handling project data must comply with contractual requirements and data protection regulations (GDPR, CCPA, etc.).
- **Open-source clash detection is mature for IFC models but limited for photo-based verification.** IfcOpenShell and IfcClash provide production-grade geometric clash detection. Photo-based progress verification comparable to OpenSpace or Buildots requires computer vision pipelines that are not yet available as mature open-source projects.
- **IFC clash detection requires tolerance configuration.** Specifying a non-zero tolerance (e.g., 0.002m) distinguishes between elements merely touching versus truly intersecting.
- **Clearance checks are slower than intersection checks.** Detecting when an element comes near another within a threshold works on non-manifold geometry but is the slowest clash type.
- Self-hosted open-source solutions require proper security hardening, IFC model management, and ongoing maintenance. Always validate clash detection results against project-specific coordination standards before issuing RFIs.

---

**Made for BIM coordinators, VDC engineers, construction managers, and developers building transparent project verification solutions.**  
Let's make Civil Project Blueprint Verification more open, data-driven, and clash-free.
