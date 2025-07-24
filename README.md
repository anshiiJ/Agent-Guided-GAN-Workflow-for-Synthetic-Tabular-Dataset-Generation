# Agent-Guided Generative AI Workflow for Synthetic Tabular Dataset Generation
This project explores a modular, agent-based Generative AI pipeline that transforms natural language prompts into high-quality synthetic tabular datasets (CSV files). It combines rule-based logic, deep learning (CTGAN), and large language models to create structured datasets aligned with user-defined attributes like age distributions, income brackets, fairness constraints, and domain semantics.

## Key Features 

- **Text-to-Data Agentic Workflow** : Accepts a natural language prompt and generates a corresponding synthetic dataset.

- **Knowledge Extraction Agent** : Extracts relevant domain-specific rules and constraints from the input prompt using LLMs.

- **Seed Dataset Generator** : Creates an initial small dataset using rule-based logic or sampling strategies.

- **Data Synthesizer (CTGAN)** : Trains on the seed data to expand it into a large, statistically coherent synthetic dataset.

- **Fusion Techniques** : Supports hybrid approaches that blend rule-based and generative outputs.

- **Extensibility** : Designed to plug in other generators (e.g., Gaussian Copulas, LLM-based synthesis) for benchmarking and comparison.



## Example Use Cases

- Generate datasets for model prototyping where real data is inaccessible.

- Produce demographically balanced datasets based on constraints (e.g., “Generate a dataset with 40% females aged 20–30 earning over $50K”).

- Stress-test ML models with controlled distributions.

- Data augmentation for underrepresented categories.
