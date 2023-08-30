# Changelog
This file will log all noteworthy changes to the echo3D Unity SDK package.

## [1.1.5] Aug 2023
- Fix bug when loading by project key without entry IDs

## [1.1.4] Aug 2023
- Fix bug caused by conflict in package name

## [1.1.3] Jul 2023
- Fix bug with shaders in URP projects

## [1.1.2] Jun 2023
- Fixed a bug where replacing an asset on the console caused a runtime exception instead of replacing the asset in Unity

## [1.1.1] - Mar 2023
- Fixed a bug that caused model initialization to fail in HDRP and URP projects

## [1.1.0] - Mar 2023
- Fixed a bug that caused metadata updates to not apply to objects when metadata was cleared
- Updates to the way realtime messages are sent and received to increase reliability


## [1.0.0] - Aug 2022
- A wave of new features, fixes and updates:
- - Updated support to Unity 2020.3 LTS and newer
- - Updated SDK dependencies
- - Updated various deprecated code bits
- - Revised debug logging to enable via script define ECHO_DEBUG
- - Split old echo3D.cs script to improve developer ergonomics, ease of future updates and performance
- - New Echo3DService script and prefab
- - New Echo3DHologram script
- - New Echo3DGlobals script
- - New Echo3DUtils script 
- - New Editor scripts for custom Echo3DHologram inspector view and updated all tooltips
- - Experimental Editor Preview feature to load holograms in Edit mode (before pressing play)
- - Removed Newtonsoft JSON package (included by default in new Unity projects)
- - Added query-only and custom query behavior as 'Advanced' feature for Echo3DHologram script
- - Adjusted RemoteTransformation.cs to only apply transformations when metadata exists (Previously applied defaults even without metadata)
- - Added Ignore Model Transforms and Disable Remote Transformation settings for hologram script
- - Added directive to automatically withold socket activity in WebGL builds
- - Added more helpful debug errors for common issues
- - Fixed many bugs