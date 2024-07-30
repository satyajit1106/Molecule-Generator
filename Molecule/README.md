# Molecule Icon Generator

Welcome to the Molecule Icon Generator! This application allows you to create customizable molecular icons using SMILES notation, molecule files, and other chemical identifiers. This project leverages Streamlit for the interactive web app interface and integrates the Google Gemini API to fetch and analyze molecular data.

## Features

- **Multiple Input Types:** Supports molecule input via name, SMILES, CAS number, InChI, InChIKey, and file uploads (SDF, MOL2, PDB).
- **Customization:** Customize molecular icons with various colors, sizes, and emoji representations.
- **Integration with Google Gemini API:** Leverages the API to fetch and analyze molecular data.
- **Export Options:** Generate and download molecule icons in various formats.

## Requirements

- Python 3.7 or higher
- Streamlit
- RDKit
- Cirpy
- Requests

| Streamlit | RDKit | CIRpy | Python | Git |
|-----------|-------|-------|--------|-----|
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/streamlit/streamlit-original.svg" title="Streamlit" alt="Streamlit" width="55" height="55"/> | <img src="https://cdn-icons-png.flaticon.com/512/682/682172.png" title="RDKit" alt="RDKit" width="55" height="55"/> | <img src="https://cdn-icons-png.flaticon.com/512/6523/6523724.png" title="CIRpy" alt="CIRpy" width="55" height="55"/> | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" title="Python" alt="Python" width="55" height="55"/> | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" title="Git" alt="Git" width="55" height="55"/> |

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/molecule-icon-generator.git
    cd molecule-icon-generator
    ```

2. **Create and activate a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the Molecule Icon Generator application locally, use the following command:

```bash
streamlit run app.py
