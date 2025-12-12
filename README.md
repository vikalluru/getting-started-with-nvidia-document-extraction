# Getting Started with NVIDIA Document Extraction

This repository contains examples and notebooks for getting started with NVIDIA's document extraction and analysis tools, specifically focusing on the Nemotron Parse API.

## Contents

- **nemotron_parse_api_example.ipynb**: A Jupyter notebook that demonstrates how to:
    - Launch the NVIDIA Nemotron Parse NIM container.
    - Query the API with an image (using Python and `requests`).
    - Visualize the detected bounding boxes and layout analysis results.
- **nemotron_nano_12b_v2_vl_api_example.ipynb**: A Jupyter notebook that demonstrates how to:
    - Launch the Nemotron Nano 12B v2 VL NIM container.
    - Perform basic vision queries and text-only queries.
    - Use reasoning capabilities (`/think`) and handle streaming responses.
- **nemoretriever_ocr_v1_example.ipynb**: A Jupyter notebook that demonstrates how to:
    - Launch the Nemoretriever OCR v1 NIM container.
    - Send base64-encoded images for text extraction.
- **evaluate_nv_ingest.ipynb**: Notebook for evaluating NVIDIA Ingestion tools (if applicable).

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
- [NVIDIA Nemotron Nano 12B v2 VL API Documentation](https://docs.nvidia.com/nim/vision-language-models/latest/examples/nemotron-nano-12b-v2-vl/api.html)
- [NVIDIA Nemoretriever OCR v1 Documentation](https://build.nvidia.com/nvidia/nemoretriever-ocr-v1/deploy)
