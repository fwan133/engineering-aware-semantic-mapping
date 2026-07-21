# Engineering-aware Semantic Mapping of Constrained Urban Streets for 3D Swept Path Analysis in MiC Logistics

This repository presents the study **“Engineering-aware Semantic Mapping of Constrained Urban Streets for 3D Swept Path Analysis in Modular Integrated Construction Logistics.”**

The study focuses on generating clean, geometrically consistent, and semantically informative 3D street models for clearance-critical transport planning in **constrained urban streets**.

![Graphical abstract](figures/graphical_abstract/framework.svg)

## Why constrained urban streets?

Oversized modular integrated construction (MiC) modules must often pass through narrow, cluttered, and dynamic urban environments. Typical challenges include:

- narrow intersections with limited turning space;
- roundabouts with complex lateral constraints;
- low-clearance overpasses with critical vertical restrictions;
- occlusion and interference from vehicles, pedestrians, vegetation, and roadside objects.

These conditions make conventional street modeling difficult and motivate a dedicated mapping workflow for **constrained urban streets**.

## Proposed framework

The framework consists of three modules:

1. **Portable mapping system and data acquisition**  
   A customized handheld mobile mapping system (H-MMS) and scenario-oriented acquisition strategies support synchronized LiDAR, camera, and IMU data collection in constrained urban streets.

2. **Loop-closure-integrated geometric mapping (LC-GMM)**  
   An accuracy-oriented geometric mapping workflow estimates globally consistent LiDAR poses and reconstructs geometrically reliable 3D street models under occlusion and moving-object interference.

3. **Engineering-aware semantic modeling and refinement (EA-SMM)**  
   Image-based semantic modeling, Bayesian multi-view fusion, and class-specific refinement generate point-wise semantic labels, remove transient objects, and preserve collision-relevant structures.

## Study scenarios

The framework was evaluated in three representative constrained urban street scenarios in Hong Kong:

- Narrow intersection
- Roundabout
- Low-clearance overpass

## Application

The resulting semantic 3D street models support 3D swept path analysis by combining geometric clearance assessment with object-level semantic interpretation for MiC transport route planning.

## Repository status

This repository currently serves as a public project page for presenting and promoting the study. Code, data, and additional research materials may be added in future updates.

## Citation

The complete citation will be added after publication.

## Contact

**Feng Wang**  
Department of Civil Engineering  
The University of Hong Kong
