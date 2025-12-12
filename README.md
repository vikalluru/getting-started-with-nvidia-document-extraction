# Getting Started with NVIDIA Document Extraction

This repository contains examples and notebooks for getting started with NVIDIA's document extraction and analysis tools, specifically focusing on the Nemotron Parse API.

## Contents

- **nemotron_parse_api_example.ipynb**: A Jupyter notebook that demonstrates how to:
    - Launch the NVIDIA Nemotron Parse NIM container.
    - Query the API with an image (using Python and `requests`).
    - Visualize the detected bounding boxes and layout analysis results.
- **evaluate_nv_ingest.ipynb**: Notebook for evaluating NVIDIA Ingestion tools (if applicable).
- **standalone_model_evaluation.ipynb**: Notebook for standalone model evaluation.

## Prerequisites

- **NVIDIA GPU**: Access to an NVIDIA GPU is required to run the NIM containers.
- **Docker**: For running the NIM containers.
- **NVIDIA NGC Account**: To pull the NIM images.
- **Python 3.8+**: For running the notebooks and scripts.

## Usage

1. **Launch the NIM Container**: Follow the instructions in `nemotron_parse_api_example.ipynb` to launch the `nvidia-nemotron-parse` container.
2. **Install Dependencies**:
   ```bash
   pip install openai pillow requests
   ```
3. **Run the Notebooks**: Open the desired notebook in Jupyter Lab or Notebook and execute the cells.

## References

- [NVIDIA Nemotron Parse API Documentation](https://docs.nvidia.com/nim/vision-language-models/latest/examples/nemotron-parse/api.html)
