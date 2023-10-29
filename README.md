## Exploring Specialization in Llama Models

This repository is a derivative of the original [Lightning-AI implementation](https://github.com/Lightning-AI/lit-llama), tailored towards experimenting with the Llama model to achieve sub-domain expertise while operating within a constrained computational budget.

### Objective

The overarching aim of this project is to refine smaller Llama models, enabling them to morph into sub-domain experts. This metamorphosis is envisioned to occur without the necessity of a substantial computational budget, thereby fostering accessibility and efficiency.

### Proposed Strategies

The following methodologies are earmarked to drive the project towards its defined objective:

1. **Pretraining with LoRA Adapters:**
   - Utilize the Llama 7B model as the foundational model, enriching it with sub-domain-specific text.
   - Implement LoRA (Low-Rank Adaptation) during the pretraining phase to ensure the model can be efficiently trained and fine-tuned on consumer-grade GPUs, thereby bridging the gap between computational constraints and model performance.

2. **Knowledge Injection Experiments:**
   - Explore various knowledge injection techniques to imbue the model with a more profound understanding and robust handling of sub-domain queries.
   - The experiments aim to unearth effective strategies for enhancing the model’s capability in providing precise and insightful responses within the specified sub-domains.

### Experimentation Landscape

The realm of experimentation encapsulates:

- Delving into different pretraining techniques that could potentially bolster the model's expertise in specific sub-domains.
- Evaluating the efficacy of LoRA adapters in reducing the computational overhead without compromising the model’s competency.
- Investigating a myriad of knowledge injection methodologies to ascertain the most fruitful avenues for enriching the model's sub-domain acumen.

### Data
The data would be updated here soon.

### Keys
Contact @elotech47 for Neptune API token