# House of Fireborn

**Houdini simulation and look development. Maison d’Atelier.**

![Portfolio — fireborn material and lava](media/portfolio/fireborn-material-and-lava.webp)

## RBD Simulation

[![Pot with breaking RBD charcoal — watch the full playblast](media/gif/charcoal-particle-playblast.gif)](media/video/charcoal-particle-playblast.mp4)

**[▶ Watch the pot and breaking RBD charcoal — full playblast](media/video/charcoal-particle-playblast.mp4)**

RBD breakup tests for the charcoal pot. The timing matters here: the pieces need weight, even when the shot is short.

<table>
<tr><td width="50%"><img src="media/images/charcoal-pot-surface-study.webp" width="100%" alt="Charcoal pot surface study — Screenshot 2024-09-24 232632"></td><td width="50%"><img src="media/images/charcoal-pot-render.webp" width="100%" alt="Charcoal pot render — Screenshot 2024-09-28 014609"></td></tr>
</table>

## References

<table>
<tr>
<td width="50%"><img src="media/images/reference-foundry-pour.jpg" width="100%" alt="Molten metal pour reference"></td>
<td width="50%"><img src="media/images/reference-forging.jpg" width="100%" alt="Forging reference: glowing metal under a hammer"></td>
</tr>
<tr>
<td valign="top"><sub>Photograph: <a href="https://www.machinedesign.com/materials/article/21832007/cast-iron-and-wrought-iron-whats-the-difference" rel="nofollow">Jatuporn79 / Dreamstime, reproduced by Machine Design</a>.</sub></td>
<td valign="top"><sub>Forging reference via <a href="https://i.pinimg.com/564x/7c/4c/3b/7c4c3b2222d3bab97a16f58c42c5c9fb.jpg" rel="nofollow">Pinterest</a>; original photographer and publication unverified.</sub></td>
</tr>
</table>

![AI-generated foundry inspiration: glowing pour into a vessel](media/images/reference-foundry-concept.jpg)

<sub>Source: <a href="https://thumbs.dreamstime.com/b/br%C3%BBler-du-m%C3%A9tal-fondu-jaune-coulant-dans-une-grande-cuve-en-atelier-de-l-industrie-la-fonderie-cr%C3%A9%C3%A9-avec-ai-g%C3%A9n%C3%A9ratif-272049859.jpg" rel="nofollow">Dreamstime</a>, image 272049859. AI-generated illustration; contributor unverified.</sub>

## 01 / Fluid Simulation

Viscosity tests for the metal transformation. A little drag gives the motion a heavier, more satisfying feel.

![Liquid, surface and smoke in Houdini](media/images/houdini-liquid-surface.webp)

![Houdini transformation geometry — Screenshot 2024-12-07 235036](media/images/houdini-transformation-2024-12-07.webp)

![Goldsmith still progression](media/gif/goldsmith-still-progression.gif)

<a href="media/video/triangle-viscosity-0-1.mp4">Triangle test: viscosity 0-1</a> · <a href="media/video/triangle-viscosity-1.mp4">viscosity 1</a> · <a href="media/video/triangle-viscosity-2.mp4">viscosity 2</a> · <a href="media/video/triangle-viscosity-2-finer-test.mp4">finer test</a>

## 02 / Erosion Tests

![PB_cam6 transformation playblast — full sequence at natural speed](media/gif/transformation-cam6.gif)

![Liquid and erosion diagnostic](media/gif/liquid-and-erosion.gif)

<a href="media/video/liquid-and-erosion.mp4">Liquid + geometry</a> · <a href="media/video/acid-erosion-front.mp4">erosion front</a> · <a href="media/video/acid-erosion-top.mp4">top</a> · <a href="media/video/erosion-side-view.mp4">side</a> · <a href="media/video/liquid-erosion-back.mp4">back contact</a>

<table>
<tr><td width="50%"><img src="media/gif/acid-erosion-front.gif" width="100%" alt="Acid erosion — front camera"></td><td width="50%"><img src="media/gif/acid-front-melt.gif" width="100%" alt="Acid front melt"></td></tr>
<tr><td><sub>Acid_erosion_FrontCam.mov — GIF playback</sub></td><td><sub>Acid_front_Melt.mov — GIF playback</sub></td></tr>
<tr><td width="50%"><img src="media/gif/front-melt-v2.gif" width="100%" alt="Front melt — second version"></td><td width="50%"><img src="media/gif/viscous-mask.gif" width="100%" alt="MetalMask viscous test"></td></tr>
<tr><td><sub>front_Melt_2.mov — GIF playback</sub></td><td><sub>MetalMask_Viscuous.mov — GIF playback</sub></td></tr>
</table>

![Macro melt](media/gif/macro-melt.gif)

The erosion and liquid passes are tested separately before judging the combined motion. Close-ups are unforgiving, so the breakup needs to hold up at that scale.

<a href="media/video/front-melt-v1.mp4">Front melt v1</a> · <a href="media/video/front-melt-v2.mp4">front melt v2</a> · <a href="media/video/acid-front-melt.mp4">acid/front melt</a> · <a href="media/video/macro-melt.mp4">macro melt</a> · <a href="media/video/acid-macro-melt.mp4">acid macro</a>

![Goldsmith skull and smoke — frame 1796](media/images/Crown_goldsmith_stills_00001796.webp)

## 03 / Camera Tests

![Transformation close view](media/gif/transformation-hq-cam17.gif)

Camera tests for the transformation. The close view is where the small folds and surface detail really earn their place.

<a href="media/video/transformation-cam6.mp4">Camera 6 review</a> · <a href="media/video/transformation-hq-cam17.mp4">HQ camera 17 review</a>

<a href="media/video/erosion-psp0025.mp4">Base fragment</a> · <a href="media/video/erosion-scale-07x10.mp4">erosion-scale fragment</a>

## 04 / Particle and Smoke Simulation

![Particle pass v4](media/gif/dust-particles-v4.gif)

Five particle passes to compare timing and density. Too much activity competes with the main transformation.

<a href="media/video/dust-particles-v1.mp4">v1</a> · <a href="media/video/dust-particles-v2.mp4">v2</a> · <a href="media/video/dust-particles-v3.mp4">v3</a> · <a href="media/video/dust-particles-v4.mp4">v4</a> · <a href="media/video/dust-particles-v5.mp4">v5</a>

![Smoke in the Houdini render view](media/images/houdini-smoke-render.webp)

Smoke tests in Houdini. The quieter moments around the skull are some of the strongest shots.

<a href="media/video/acid-smoke-test.mp4">Smoke test</a>

## 05 / Charcoal Look Development

![Intermediate lava camera 2](media/gif/lava-render-cam2.gif)

Render tests for the charcoal scene, comparing the internal glow with the dark outer material.

<a href="media/video/lava-render-cam2.mp4">Camera 2 — complete available batch</a> · <a href="media/video/lava-render-cam1-fragment.mp4">camera 1 — 16-frame fragment</a>

## 06 / Shading and Lighting

<table>
<tr><td width="50%"><img src="media/images/Crown_goldsmith_stills_00000522.webp" width="100%" alt="Goldsmith flower still — frame 522"></td><td width="50%"><img src="media/gif/final-liquid-gold.gif" width="100%" alt="Final liquid gold"></td></tr>
<tr><td width="50%"><img src="media/gif/final-lava-front.gif" width="100%" alt="Final lava"></td><td width="50%"><img src="media/images/final-gold-skull.webp" width="100%" alt="Gold skull and smoke"></td></tr>
</table>

<table>
<tr><td width="50%"><img src="media/gif/goldsmith-closeup-flower-v03.gif" width="100%" alt="Crown Goldsmith Closeup Flower Clip V03"></td><td width="50%"><img src="media/gif/goldsmith-infection-mask-v06.gif" width="100%" alt="Crown Goldsmith Infectionk Mask Clip V06"></td></tr>
<tr><td><sub>Goldsmith flower closeup — V03</sub></td><td><sub>Goldsmith mask — V06</sub></td></tr>
</table>

![Sc050 Sh010 — material closeup](media/gif/sc050-sh010.gif)

The gold works best when the highlights have room to fall away. That restraint gives the shots their mood.

<a href="media/video/final-gold-skull.mp4">Gold skull film</a> · <a href="media/video/final-liquid-gold.mp4">liquid gold</a> · <a href="media/video/final-lava-front.mp4">lava front</a> · <a href="media/video/final-lava-profile.mp4">lava profile</a>

## 07 / Color Correction

Final grading in DaVinci Resolve, including HDR adjustments and Film Look Creator tests.

![DaVinci Resolve charcoal-pot edit](media/images/resolve-edit-2026-08-04.webp)

![DaVinci Resolve skull color grade](media/images/resolve-grade-2026-08-18.webp)

![DaVinci Resolve gold material look development](media/images/resolve-look-2026-07-31.webp)

## Files

[Media](docs/media-index.md) · [Source notes](docs/media-manifest.json) · [Archive details](docs/audit-notes.md)

---

![Portfolio — fireborn cover](media/portfolio/fireborn-cover.webp)

