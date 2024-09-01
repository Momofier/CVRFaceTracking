# CVR Factracking - Template

CVR Face Tracking Unity templates to be used with [VRCFaceTracking](https://github.com/benaclejames/VRCFaceTracking)

## Prerequisites

* Unity 2021
* [VRCFaceTracking Release 5.1.1](https://github.com/benaclejames/VRCFaceTracking/releases/5.1.1.0)
* Avatar with [SRanipal](https://docs.vrcft.io/docs/v4.0/category/intermediate), [ARKit (Perfect Sync)](https://arkit-face-blendshapes.com/), or [Unified Expressions](https://docs.vrcft.io/docs/tutorial-avatars/tutorial-avatars-extras/unified-blendshapes) face tracking shapekeys
* Face tracking animations are pointed to the ```Body``` skinned mesh render by default. If face tracking shapes are on a different skinned mesh render, you will need to change the component to rewrite animations clips prefix. For example if face tracking shapes are on ```Face``` mesh you will need to rewrite ```Body``` to ```Face```

## Setup 

1. Add/Import [SimpleAAS](https://github.com/NotAKidoS/SimpleAAS/releases)
2. Add/Import VRCFT Jerry's Templates from [Momo's VRCFT Templates Listing](https://github.com/Momofier/CVRFaceTracking)
3. Add face tracking prefab to your avatar located in ```Packages/VRCFT - Jerry's Templates/CVRPrefabs``` or ```Assets/
   * Uses the corresponding face tracking shapes prefab, if not sure look this [Face Tracking Spreadsheet](https://docs.google.com/spreadsheets/d/118jo960co3Mgw8eREFVBsaJ7z0GtKNr52IB4Bz99VTA/edit?usp=sharing)

[Detailed setup PDF guide](https://github.com/Adjerry91/VRCFaceTracking-Templates/blob/main/Packages/adjerry91.vrcft.templates/VRCFaceTracking%20Template%20Setup.pdf)

## Change Log
[VRCFT - Jerry's Template Change Log](https://github.com/Adjerry91/VRCFaceTracking-Templates/blob/main/Packages/adjerry91.vrcft.templates/CHANGELOG.md)

## Support

Post in ```#template-help``` for advance support on [Jerry's Face Tracking Discord](https://discord.gg/yQtTsVSqx8)

## Face Tracking Animation Tips:

* Modification to the thresholds may be needed for some animation sensitivity for different faces
* Driver, binary, and smooth layer require write defaults ON

This is a modification of the VRCFaceTracking Template and is a WIP Port of it to CVR. It will Still contain most the Files the Base has with some of them removed
# Some Noted Bugs:

* It's a Bit Sluggish on the Full Version(Should be fixed with Adjustments to the FT Smoothness Slider(Higher is Quicker))
* The Lite Version is Untested, but should work
