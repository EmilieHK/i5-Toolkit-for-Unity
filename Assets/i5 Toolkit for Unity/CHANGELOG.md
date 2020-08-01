# Changelog

This document keeps track of the changes between versions of the toolkit.

## [Unreleased]

### Breaking Changes
- The IService interface now requires a BaseServiceManager in the Initialize method.
  To update, just replace `Initialize(ServiceManager owner)` with `Initialize(BaseServiceManager owner)` in your services.

## 1.0.1 (2020-07-02)

### Fixed
- Gizmo copy procedure now works on package installations

## 1.0.0 (2020-06-30)

### Added
- API for constructing procedural geometry, materials and fetching textures
- ObjImporter for importing .obj files and .mtl files from the Web
- Tool for creating extruded rectangles with rounded edges, e.g. for UI elements
- Object Pool for reusing resources
- GameObject spawners that support
  - Spawning multiple objects
  - Spawn limits
  - Managing spawned objects
- Scene documentation objects
- Utilities
  - Function for adding a component or getting an existing instance on a given GameObject
  - Functions for parsing space separated numbers to Vector2 or Vector3
  - Editor function for getting the path of the package
- Extensions for converting Vector2 and Vector3 to Color objects and vice versa
- Unit tests for the added modules
- Example scenes for the added modules
- Package logo and icons for the added modules
- Readme with setup instructions
- Changelog
- Package license
- Assembly definition files to structure the package
- JSON file for the package description