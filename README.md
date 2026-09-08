# Bailey Bale And Pallet Trailer - Farming Simulator 22 Mod

## Overview

**FS22_Bailey_Bale_And_Pallet_Trailer** is a professional-grade mod for Farming Simulator 22 that introduces the Bailey Bale and Pallet Trailer, a versatile and essential piece of farm machinery designed for efficient transport of agricultural commodities. Developed by **Bolex Simulation**, this mod combines realistic physics, detailed 3D modeling, and comprehensive configuration options to enhance your farming simulation experience.

## Features

### Vehicle Specifications
- **Type**: Trailer (Can be attached to standard tractors and telehandlers)
- **Capacity**: Transports 11-20 bales or 15-30 pallets (depending on size)
- **Price**: $8,000
- **Mass**: 3,500 kg
- **Dimensions**: 3.5m width × 8m length
- **Lifetime**: 600 hours (in-game durability)

### Customization Options

The trailer offers extensive configuration possibilities to match your farm's aesthetic and operational needs:

#### Color Options
- **Bailey Green** - Classic Bailey brand green color
- **Chrome Black** - Modern sleek black finish
- **Chrome Night Blue** - Deep night blue metallic
- **Chrome Orange** - Vibrant orange accent
- **Matte Variants** - All colors available in matte finish for a more subdued appearance

#### Wheel/Tire Options
Multiple tire manufacturer options with optimized suspension settings:
- **Nokian TRI2 340/80R18** - Standard reliable choice with proven traction
- **Trelleborg TH400 340/80R18** - Premium performance option
- **Mitas TR09 320/80R18** - Alternative agro tire solution

#### Beacon/Warning Light Options
- **No Beacon** - Clean trailer appearance
- **Left Standard** - Single standard beacon on left side
- **Right Standard** - Single standard beacon on right side
- **Both Standard** - Dual standard beacons
- **Left LED** - Modern LED beacon on left
- **Right LED** - Modern LED beacon on right
- **Both LED** - Dual modern LED beacons

#### Design Options
- **Front Configuration** - Specific front design variant
- **Back Configuration** - Customizable rear design
- **Standard Design** - Default professional appearance

### Multiplayer Support
Full multiplayer compatibility enabled, allowing cooperative farming experiences with other players.

## Technical Details

### 3D Model & Graphics
- **High-Quality 3D Model**: `BPTrailer.i3d` with detailed geometry
- **Collision Shapes**: `BPTrailer.i3d.shapes` for realistic physics interaction
- **Texture Resolution**: Professional-grade DDS textures including:
  - Main trailer diffuse and normal maps
  - Decal textures for detailed branding
  - Specular/mask textures for realistic material rendering
  - Store display texture for in-game shop presentation
- **Brand Branding**: Authentic Bailey brand imagery and styling

### Configuration System
The mod utilizes XML-based configuration files:
- **modDesc.xml** - Mod metadata, version information, and store integration
- **BPTrailer.xml** - Vehicle specifications, physics, wheels, and visual properties
- **Brand Definition** - Bailey brand integration with custom branding

## Compatibility

### Game Requirements
- **Farming Simulator 22** (or compatible version as per mod version)
- **Description Version**: 67

### Optional Add-ons
- **Universal Autoload ModHub Add-on** (by loki_79 and ddewar) - Enables autoloading functionality for bales and pallets if desired

## Changelog

### Version 1.1.0.0
- Added LED beacon options for modern safety features
- Added matte color variants to all trailer color options
- Changed attacher type compatibility (now compatible with telehandlers in addition to tractors)
- Fixed collision issue with tension belts clipping through trailer body
- Minor bug fixes and stability improvements

## File Structure

```
├── BPTrailer.i3d                  # Main 3D model file
├── BPTrailer.i3d.shapes           # Collision shapes for physics
├── BPTrailer.xml                  # Vehicle configuration and specifications
├── modDesc.xml                    # Mod metadata and description
├── README.md                      # Documentation
├── brand_Bailey.dds               # Bailey brand logo/image
├── icon_BPTrailer.dds             # Mod icon for in-game display
├── store.dds                      # Store/shop preview image
└── textures/                      # Texture assets directory
    ├── bpt_normal.dds             # Normal map for surface details
    ├── bpt_vmask.dds              # Vertical mask/material properties
    ├── decals_diffuse.dds         # Decal diffuse textures
    └── decals_vmask.dds           # Decal mask textures
```

## Credits

**Developer**: Bolex Simulation

## Version

**Current Version**: 1.1.0.0

## Usage

Simply add this mod folder to your Farming Simulator 22 mods directory and enable it in-game. The Bailey Bale and Pallet Trailer will appear in the shop under the Bale Loaders category for $8,000.

## Notes

- This trailer is optimized for bale and pallet transportation, making it ideal for hay operations and general farm logistics
- The tension belt system has been refined to prevent clipping issues
- Autoload functionality is available as an optional enhancement through community add-ons
- All visual components are fully customizable through the in-game configuration menu
