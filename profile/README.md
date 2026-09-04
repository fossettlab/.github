# Fossett Laboratory

Geospatial field methods, AI-driven analysis, and extended-reality
applications at Washington University in St. Louis.

<https://fossettlab.org>

## Immersive and extended reality

Geoscience visualization for HoloLens, mobile AR, and desktop. Several of these
are teaching tools; the rest are research and outreach demos.

### GeoXplorer

- [xr-geoxplorer](https://github.com/fossettlab/xr-geoxplorer) — unified
  HoloLens + iOS/Android explorer (Unity, MRTK2 + Photon + Azure Spatial
  Anchors). Actively developed.
- [xr-geoxplorer-mobile](https://github.com/fossettlab/xr-geoxplorer-mobile) —
  mobile-only branch on AR Foundation, published as
  `com.FossettLab.GeoXplorer`. Archived.

### Standalone applications

- [xr-crystalviewer](https://github.com/fossettlab/xr-crystalviewer) —
  crystal-structure viewer, HoloLens (teaching)
- [xr-meltcomplex](https://github.com/fossettlab/xr-meltcomplex) — magma phase
  diagrams, HoloLens (teaching)
- [xr-3d-phase-diagrams](https://github.com/fossettlab/xr-3d-phase-diagrams) —
  petrology phase-diagram interactive, desktop (teaching)
- [xr-virtual-earth-2](https://github.com/fossettlab/xr-virtual-earth-2) —
  geospatial viewer, HoloLens
- [xr-volcano-viewer](https://github.com/fossettlab/xr-volcano-viewer) —
  volcano visualization, HoloLens
- [xr-seismicity-viewer](https://github.com/fossettlab/xr-seismicity-viewer) —
  earthquake catalog viewer, HoloLens
- [xr-lro-asset-bundles](https://github.com/fossettlab/xr-lro-asset-bundles) —
  Lunar Reconnaissance Orbiter viewer, Apollo landing sites
- [xr-rover-traverse](https://github.com/fossettlab/xr-rover-traverse) — rover
  path and site visualization
- [xr-kilauea-sono](https://github.com/fossettlab/xr-kilauea-sono) — Kilauea
  DEM sonification, desktop
- [xr-dco-demo](https://github.com/fossettlab/xr-dco-demo) — Deep Carbon
  Observatory demo, HoloLens and WebGL
- [xr-intermediate-triggering](https://github.com/fossettlab/xr-intermediate-triggering)
  — networked HoloLens app, MRTK + Photon

## Imaging spectroscopy

Mineral and mine-waste mapping from spaceborne VSWIR imaging spectrometers,
built around Planet Tanager with NASA EMIT as an independent check.

- [tanager-spec](https://github.com/fossettlab/tanager-spec) — shared data
  layer: STAC ingest, QA masking, band utilities, spectral response
  simulation, reproducible sampling
- [tanager-isofit](https://github.com/fossettlab/tanager-isofit) — HDF5
  radiance to surface reflectance via ISOFIT atmospheric correction, validated
  against EMIT
- [tanager-minmap](https://github.com/fossettlab/tanager-minmap) — alteration
  mapping at Bingham Canyon and Goldfield, library-anchored screening

## Geospatial field methods

Field data collection and postprocessing: GNSS, total station, lidar,
photogrammetry, and the coordinate-system work that ties them together.

- [gnss-nlos-notebook](https://github.com/fossettlab/gnss-nlos-notebook) — flags
  non-line-of-sight GNSS signals with a random forest, then tests whether
  excluding them improves the position. Course material for EEPS 4684/5684,
  runs in Colab.

## Status

Apart from GeoXplorer, the XR projects were last in active development between
2017 and 2021 and are archived. Reviving any would need a Unity LTS upgrade and
an MRTK 2 to MRTK 3 or OpenXR migration. Repositories carry an `archived` topic
where that applies, so the topic list on each repository is the authoritative
status.

Some repositories are private and are not listed here.

## Vendor dependencies

Upstream projects these build on, linked rather than vendored:

- Azure Spatial Anchors samples → [Azure/azure-spatial-anchors-samples](https://github.com/Azure/azure-spatial-anchors-samples)
- Unity3DTiles → [NASA-AMMOS/Unity3DTiles](https://github.com/NASA-AMMOS/Unity3DTiles)
