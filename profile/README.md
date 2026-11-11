# Parallax Metrology

**Structure has geometry. Measure it.**

Wherever a system generates structure (an image model arranging visual mass, a language model producing text, tissue organizing under a microscope), that structure has geometry, and geometry can be measured without knowing what the output means. Parallax Metrology builds deterministic structural instruments: no model inside the measurement, same input, same output, every coordinate traceable to countable evidence. Where a benchmark result comes from a fitted readout on those coordinates (a classifier or regressor), the repository says which.

## Open instruments

| | |
|---|---|
| **[visual-thinking-lens](https://github.com/parallaxmetrology/visual-thinking-lens)** | Where visual mass sits in an image, how it spreads, and whether a generator ever leaves its default. Python package, CLI, notebooks, agent skills. **[Try it in your browser →](https://parallaxmetrology.github.io/visual-thinking-lens/)** · or play **[Where's the weight?](https://parallaxmetrology.github.io/visual-thinking-lens/weight/)** |
| **[linguistic-kernel](https://github.com/parallaxmetrology/linguistic-kernel)** | The structure of text, especially model output: where an answer puts its weight, how it breathes, how it holds together, and when it's been cut off. Eight countable axes, no judge model. **[Play: Guess the Engine →](https://parallaxmetrology.github.io/linguistic-kernel/)** |
| **[inspection-coordinates](https://github.com/parallaxmetrology/inspection-coordinates)** | Fifteen physics-grounded coordinates for semiconductor inspection images (SEM, wafer maps, aerial). No training; matches the best classical descriptors on public benchmarks, reproducible in minutes. Process-monitoring pilots welcome. |
| **[spatial-kernel](https://github.com/parallaxmetrology/spatial-kernel)** | Is it really there? A deterministic two-view check of robot task outcomes on ordinary phone photos. A frontier robot VLM passed 10 of 18 printed decoys as real objects; the geometry caught all 10. **[Play: Real or printed? →](https://parallaxmetrology.github.io/spatial-kernel/)** |
| **[structural-topology-kernel](https://github.com/parallaxmetrology/structural-topology-kernel)** | Fifty training-free structural coordinates for microstructure images, with a matminer featurizer. 0.832 AUC on steel micrographs grouped by specimen (HOG 0.728); the classification, bainite and permeability results reproduce from shipped feature tables. |
| **[parallax-core42](https://github.com/parallaxmetrology/parallax-core42)** | Forty-two named, deterministic measurements of an H&E histology patch, built to find the batch you didn't know you had: which named axes split a cohort by site, scanner or production route. On TCGA colorectal slides it separates three production routes (balanced accuracy 0.977 with a named LDA readout; the mis-scaled derivative slides stand apart without labels). Complements colour features, not a better classifier than plain texture; see 'How it compares'. |
| **[notan](https://github.com/parallaxmetrology/notan)** | The big light and dark shapes of a picture, read the way a painter squints, and which parts of it are built from value and which from colour. Texture-robust; nine test images with known answers ship with it. |
| **[notan-route](https://github.com/parallaxmetrology/notan-route)** | The order in which a picture's Notan masses lead from one to the next, and the transition field behind it: which masses lead to which, and the basins they drain into. A property of the mass map, with no claim about eyes; ten known-answer gates. |

More instruments (pathology and others) will open here one at a time, each built the same way: faithful to its research notebooks, tested against them, and documented with what it *can't* see.

## Notes on method

- **[How image measures lie quietly](https://www.parallaxmetrology.com/how_measures_lie.html)** ([code](https://github.com/parallaxmetrology/how-measures-lie)): nineteen ways a hand-built image measure returns a plausible, wrong number without raising an error, each with a case, a live demonstration and the check that catches it.
- **[he-checks](https://github.com/parallaxmetrology/he-checks)**: quiet failures in H&E pathology pipelines and datasets. A Macenko stain normaliser whose haematoxylin and eosin vectors collapse into one direction through an SVD sign convention (0.17° apart in our own TCGA work, about 14° once fixed), 25 TCGA colorectal slides whose stated pixel spacing is about 2× too fine (with their enlarged tiles in the Kather TCGA tile archive), and purple "blank glass" in every background tile of the CRC-VAL-HE-7K benchmark. Checks, a sign-safe estimator and the slide list.
- **PathoROB controls.** Run Gaussian and RGB controls on three published pathology benchmark designs to see how the sampling design affects the robustness index and what the lowest margins reveal. [Technical note](https://parallaxmetrology.com/pathorob-controls/) · [Code and reference scores](https://github.com/parallaxmetrology/pathorob-controls/releases/tag/v3.0.0)

## Also here

- **[structural-collocation](https://github.com/parallaxmetrology/structural-collocation)**: a study. Triple collocation on the geometry of the rain field (radar, GOES-16 infrared, IMERG microwave, gauges): which observer looks best depends on which three are compared, and shared error can be detected without ground truth.
- **[paint-mixing](https://github.com/parallaxmetrology/paint-mixing)**: a tool for painters. Kubelka–Munk mixing for the questions asked at the palette: what to add to a pile that is almost right, whether your tubes can reach a colour, and one shared palette for a value plan.
- **[shan-shui-inf](https://github.com/parallaxmetrology/shan-shui-inf)**: a play piece. A fork of [Lingdong Huang's {Shan, Shui}*](https://github.com/LingDong-/shan-shui-inf) infinite landscape scroll, drawn in learned hands (Shen Zhou, Shitao, Buson, Rembrandt, Van Gogh and more). Same seed, same landscape, different hand. **[Scroll it →](https://parallaxmetrology.com/shan-shui/)**

## Get involved

- Measure something and share the fingerprint ([images](https://github.com/parallaxmetrology/visual-thinking-lens/discussions), [text](https://github.com/parallaxmetrology/linguistic-kernel/discussions), [robot scenes](https://github.com/parallaxmetrology/spatial-kernel/discussions)).
- Found a reading that's obviously wrong? That's the most useful report there is.
- Issues labeled `port` and `good first issue` are open doors.

[parallaxmetrology.com](https://www.parallaxmetrology.com) · [artistinfluencer.com](https://www.artistinfluencer.com)
