# Handsketch3D
Generate 3D models from hand-drawn sketches

Handsketch3D is a deep learning model that takes in hand-drawn sketches as input and converts them into a 3D model that can be exported in Standard exchange format STEP or STL. It uses an image captioning architecture to generate an intermediate domain specific language which is later converted to CAD software specific macros.

Note: This project is meant as a proof-of-concept; the model isn't (yet) built to generalize to the variability of sketches seen in actual use case, and thus its performance relies on sketches resembling the core dataset.

For detailed capabilities of this code refer to the documentation.

## Setup
### Prerequisites

- Python 3 (not compatible with python 2)
- pip

### Install dependencies

```sh
pip install -r requirements.txt
```

