# Parallax Metrology

**Structure has geometry. Measure it.**

Wherever a system generates structure (an image model arranging visual mass, a language model producing text, tissue organizing under a microscope), that structure has geometry, and geometry can be measured without knowing what the output means. Parallax Metrology builds deterministic structural instruments: no model in the loop, same input, same output, every coordinate traceable to countable evidence.

## Open instruments

| | |
|---|---|
| **[visual-thinking-lens](https://github.com/parallaxmetrology/visual-thinking-lens)** | Where visual mass sits in an image, how it spreads, and whether a generator ever leaves its default. Python package, CLI, notebooks, agent skills. **[Try it in your browser →](https://parallaxmetrology.github.io/visual-thinking-lens/)** · or play **[Where's the weight?](https://parallaxmetrology.github.io/visual-thinking-lens/weight/)** |
| **[linguistic-kernel](https://github.com/parallaxmetrology/linguistic-kernel)** | The structure of text, especially model output: where an answer puts its weight, how it breathes, how it holds together, and when it's been cut off. Eight countable axes, no judge model. **[Play: Guess the Engine →](https://parallaxmetrology.github.io/linguistic-kernel/)** |
| **[inspection-coordinates](https://github.com/parallaxmetrology/inspection-coordinates)** | Fifteen physics-grounded coordinates for semiconductor inspection images (SEM, wafer maps, aerial). No training; matches the best classical descriptors on public benchmarks, reproducible in minutes. Process-monitoring pilots welcome. |
| **[spatial-kernel](https://github.com/parallaxmetrology/spatial-kernel)** | Is it really there? A deterministic two-view check of robot task outcomes on ordinary phone photos. A frontier robot VLM passed 10 of 18 printed decoys as real objects; the geometry caught all 10. **[Play: Real or printed? →](https://parallaxmetrology.github.io/spatial-kernel/)** |
| **[structural-topology-kernel](https://github.com/parallaxmetrology/structural-topology-kernel)** | Fifty training-free structural coordinates for microstructure images, with a matminer featurizer. 0.832 AUC on steel micrographs grouped by specimen (HOG 0.728); the classification, bainite and permeability results reproduce from shipped feature tables. |
| **[notan](https://github.com/parallaxmetrology/notan)** | The big light and dark shapes of a picture, read the way a painter squints, and which parts of it are built from value and which from colour. Texture-robust; nine test images with known answers ship with it. |
| **[notan-route](https://github.com/parallaxmetrology/notan-route)** | The order in which a picture's Notan masses lead from one to the next, and the transition field behind it: which masses lead to which, and the basins they drain into. A property of the mass map, with no claim about eyes; ten known-answer gates. |

More instruments (materials and others) will open here one at a time, each built the same way: faithful to its research notebooks, tested against them, and documented with what it *can't* see.

## Notes on method

- **[How image measures lie quietly](https://www.parallaxmetrology.com/how_measures_lie.html)** ([code](https://github.com/parallaxmetrology/how-measures-lie)): nineteen ways a hand-built image measure returns a plausible, wrong number without raising an error, each with a case, a live demonstration and the check that catches it.

## Get involved

- Measure something and share the fingerprint ([images](https://github.com/parallaxmetrology/visual-thinking-lens/discussions), [text](https://github.com/parallaxmetrology/linguistic-kernel/discussions), [robot scenes](https://github.com/parallaxmetrology/spatial-kernel/discussions)).
- Found a reading that's obviously wrong? That's the most useful report there is.
- Issues labeled `port` and `good first issue` are open doors.

[parallaxmetrology.com](https://www.parallaxmetrology.com) · [artistinfluencer.com](https://www.artistinfluencer.com)
