# Audit and selection notes

[Back to the case study](../README.md)

## Scope

The confirmed set contains House of Fireborn, Back to My Roots, and Organic Humanoid Head / MetalMask. Palm is excluded at the ownerâ€™s request. The two head pages describe overlapping material and are represented by one repository.

The audit recursively covered the supplied Fireborn process folder, chair screenshots, every folder in `playblast_files_folders_links.txt`, the project pages and their local asset folders. Review included movie metadata and sampled frames, numbered-sequence detection, sample comparisons with existing videos, and inspection of process screenshots.

## Evidence and exclusions

- The separate `REEL01_Knitting / SC030` branch contains cloth camera experiments, Vellum captures and six AVI files. It was audited, but no reliable attribution to these four projects was established; its footage is excluded from their narratives. This includes 425 MiB AVIs and numerous similar camera paths.
- Automata is outside the confirmed scope. Sparse numbered hero stills and separate clay viewpoints are not treated as animation.
- Repeated movie copies were identified by SHA-256. The Fireborn collection duplicates nine movies in the linked R&D directories; each selected movie is included once.
- The charcoal JPG batch matches its 93-frame AVI. The coating JPG batch matches its 136-frame movie. Existing movies were used, with delivery compression, rather than rebuilding these sequences.
- The incomplete `Viscosity_By_8.avi` cannot be decoded. Its numbered `.pic` batch was recoverable through Houdini `iconvert` and is included in the head repository.
- Movie frame rates are preserved. 24 fps is the documented review assumption for newly encoded image sequences, based on adjacent playblasts. No scene FPS was recovered directly.
- Masters, Houdini scenes and caches remain in their original locations. This repository is a process-media case study, not a reproducible simulation project.

## New sequence encodes

| Review | Original batch | Frames | FPS |
|---|---|---:|---:|
| [lava-render-cam2](../media/video/lava-render-cam2.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\SCENES\SC090\render\SH010\vray_SH010_cam2.{frame}.png` | 1â€“96 (96) | 24 |
| [lava-render-cam1-fragment](../media/video/lava-render-cam1-fragment.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\SCENES\SC090\render\SH010\New folder\vray_SH010_cam1.{frame}.png` | 1â€“16 (16) | 24 |
| [transformation-cam6](../media/video/transformation-cam6.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_Transformation_01\Transformation\playblast\PB_cam6\cam6.{frame}.png` | 39â€“121 (83) | 24 |
| [transformation-hq-cam17](../media/video/transformation-hq-cam17.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_Transformation_01\Transformation\playblast\PB_HQ_cam17\PB_cam6_HQ.{frame}.png` | 39â€“500 (462) | 24 |
| [erosion-psp0025](../media/video/erosion-psp0025.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_LiquidDrop_01\LiquidDrop\flip\psp0025\untitled{frame}.jpg` | 1â€“11 (11) | 24 |
| [erosion-scale-07x10](../media/video/erosion-scale-07x10.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_LiquidDrop_01\LiquidDrop\flip\psp0025_erosionscale07x10\untitled{frame}.jpg` | 1â€“11 (11) | 24 |
| [dust-particles-v1](../media/video/dust-particles-v1.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_Transformation_01\Transformation\flip\dust_particles\dust_part.{frame}.jpg` | 1â€“72 (72) | 24 |
| [dust-particles-v2](../media/video/dust-particles-v2.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_Transformation_01\Transformation\flip\dust_part_V2\dust_part.{frame}.jpg` | 1â€“72 (72) | 24 |
| [dust-particles-v3](../media/video/dust-particles-v3.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_Transformation_01\Transformation\flip\dust_part_V3\dust_part.{frame}.jpg` | 1â€“51 (51) | 24 |
| [dust-particles-v4](../media/video/dust-particles-v4.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_Transformation_01\Transformation\flip\dust_part_V4\dust_part.{frame}.jpg` | 1â€“72 (72) | 24 |
| [dust-particles-v5](../media/video/dust-particles-v5.mp4) | `D:\SELF\WORKING_FILES\REEL01_Metamask\REEL01_ANIMATION\A_PROJ\HOUD\R&D\HoudiniProjects\Metamask_Transformation_01\Transformation\flip\dust_part_V5\dust_part.{frame}.jpg` | 1â€“24 (24) | 24 |

## Delivery

H.264, yuv420p, fast-start MP4; source aspect ratio retained, up to 1920 Ã— 1080. Images are web delivery copies, resized only above 2800 pixels; larger PNGs in the head, chair and Palm archives use high-quality WebP compression. Most GIFs are 640 pixels wide; the noisy HQ transformation preview uses 480 pixels and 8 fps. Compression settings and file checksums are recorded in the manifest.

## Larger source files

| Source | Original | Delivery |
|---|---:|---:|
| `Acid_front_Melt.mov` | 54.31 MiB | [2.59 MiB](../media/video/acid-front-melt.mp4) |
| `Macro_Melt.mov` | 194.34 MiB | [5.15 MiB](../media/video/macro-melt.mp4) |
| `untitled.avi` | 326.96 MiB | [0.24 MiB](../media/video/charcoal-particle-playblast.mp4) |
| `Acid_Macro_Melt.mov` | 59.45 MiB | [2.23 MiB](../media/video/acid-macro-melt.mp4) |

## Added imagery

The source folders were re-inspected after 35 files were added. Earlier head shell/lighting captures were assigned to the combined head repository by subject, despite being placed in the Fireborn source folder. Foundry and structural reference images are clearly labeled as supplied references; they are not represented as original project renders. The foundry-concept filename labels that reference as AI-generated.
