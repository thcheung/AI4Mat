 # AI4Mat
AI for Materials Science and Engineering
## Materials Discovery
### Information Extraction
* **Text analysis**: AI algorithms can extract relevant information from large texts, such as research papers, patents, or scientific articles.
* **Material property extraction**: AI can analyze text data to extract material properties, such as chemical composition, crystal structure, and physical properties.
* **Knowledge graph construction**: AI can build knowledge graphs by extracting relationships between materials, their properties, and application areas.
### Molecular Generation
* **Generative models**: AI-generated molecular structures can be used to design new materials with specific properties.
* **Molecular similarity analysis**: AI algorithms can analyze existing molecules and predict the characteristics of similar compounds, which can lead to the identification of new materials with desired properties.
* **Structure-property relationships**: AI can learn patterns between molecular structure and material properties, enabling the prediction of material behavior.
### Property Prediction
* **Predictive modeling**: LLMs can be trained on large datasets of existing materials to predict their properties, such as mechanical strength, thermal conductivity, or electrical conductivity.
* **Material property prediction**: AI algorithms can analyze molecular structures and predict material properties, enabling the identification of new materials with desired characteristics.
### Synthesis Planning
* **Route prediction**: AI can optimize synthesis routes by predicting the most efficient sequence of steps required to produce a specific material.
* **Reaction prediction**: LLMs can predict reaction conditions, such as temperature, pressure, and catalyst requirements, to achieve the desired product yield and purity.
* **Process optimization**: AI algorithms can analyze data from various sources, including laboratory experiments, computational simulations, and industrial processes, to optimize synthesis conditions.
## Projects Overview
### FAIR Chemistry
- **Repository:** [facebookresearch/fairchem](https://github.com/facebookresearch/fairchem)
- **Summary:** FAIR Chemistry is the centralized repository of FAIR Chemistry’s data, models, demos, and application efforts across materials science and quantum chemistry. It offers:
  - **Pretrained models** integrated with the ASE (Atomic Simulation Environment) via an OCPCalculator interface.
  - Extensive tools for managing datasets, building custom chemistry pipelines, and rapid prototyping.
  - A unified API that streamlines research and deployment across computational chemistry applications.
### MatterSim
- **Repository:** [microsoft/mattersim](https://github.com/microsoft/mattersim)
- **Summary:** MatterSim is a deep learning atomistic simulation tool designed to compute material properties efficiently under varying conditions (elements, temperatures, pressures):
  - **Pre-trained models:** Choose between a fast mini model (*MatterSim-v1.0.0-1M*) or a larger, more accurate version (*MatterSim-v1.0.0-5M*).
  - Seamless integration with ASE allows you to simulate materials instantly.
  - Built-in fine-tuning scripts and evaluation pipelines help adapt the simulation to custom datasets and property constraints.
### MatterGen
- **Repository:** [microsoft/mattergen](https://github.com/microsoft/mattergen)
- **Summary:** MatterGen is a pioneering generative model for designing novel inorganic material structures:
  - **Conditional generation**: Fine-tuned models let you steer the generated structures toward target property constraints (e.g., magnetic density, band gap).
  - Pre-trained checkpoints and adaptable training pipelines empower you to innovate and generate new materials.
  - Comprehensive training and fine-tuning scripts ensure you can optimize the model on custom datasets.
