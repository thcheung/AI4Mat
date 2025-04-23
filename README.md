# AI4Mat
AI for Materials Science and Engineering

## Projects Overview

### FAIR Chemistry
- **Repository:** [facebookresearch/fairchem](https://github.com/facebookresearch/fairchem)
- **Summary:** FAIR Chemistry is the centralized repository of FAIR Chemistry’s data, models, demos, and application efforts across materials science and quantum chemistry. It offers:
  - **Pretrained models** integrated with the ASE (Atomic Simulation Environment) via an OCPCalculator interface.
  - Extensive tools for managing datasets, building custom chemistry pipelines, and rapid prototyping.
  - A unified API that streamlines research and deployment across computational chemistry applications.

### Materials Discovery: GNoME
- **Repository:** [google-deepmind/materials_discovery](https://github.com/google-deepmind/materials_discovery)
- **Summary:** Leverage the power of graph neural networks to uncover novel inorganic crystals!
  - Discover *over 520,000 materials* with unprecedented coverage, with detailed data descriptors, colabs, and visualization tools.
  - Models are optimized with a message-passing architecture, delivering state-of-the-art accuracy (down to ~21 meV/atom).
  - Extensive dataset summaries and pre-processing utilities enable you to jump right into materials discovery.

### MatterSim
- **Repository:** [microsoft/mattersim](https://github.com/microsoft/mattersim)
- **Summary:** MatterSim is a deep learning atomistic simulation tool designed to compute material properties efficiently under varying conditions (elements, temperatures, pressures):
  - **Pre-trained models:** Choose between a fast mini model (*MatterSim-v1.0.0-1M*) or a larger, more accurate version (*MatterSim-v1.0.0-5M*).
  - Seamless integration with ASE allows you to simulate materials instantly.
  - Built-in fine-tuning scripts and evaluation pipelines help adapt the simulation to custom datasets and property constraints.

### MatterGen
- **Repository:** [microsoft/mattergen](https://github.com/microsoft/mattergen)
- **Summary:** MatterGen is a pioneering generative model for designing novel inorganic material structures:
  - **Conditional generation:** Fine-tuned models let you steer the generated structures toward target property constraints (e.g., magnetic density, band gap).
  - Pre-trained checkpoints and adaptable training pipelines empower you to innovate and generate new materials.
  - Comprehensive training and fine-tuning scripts ensure you can optimize the model on custom datasets.
