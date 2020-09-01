# DRW2CAD3D
Generate 3D models from 2D drawings

DRW2CAD3D is a deep learning model that takes in 2D drawings as input and converts them into a 3D CAD model that can be exported in Standard exchange format STEP or STL. It uses an image captioning architecture to generate an intermediate domain specific language which is later converted to CAD software specific macros.

## Why is it important?
As a mechanical engineer, I have sometimes asked CAD designers to manually create a 3D CAD model of some electronic components from its datasheet. I launched this project to automate this process so CAD designers can really concentrate on their real job of creating CAD design of their products in developement. 

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

