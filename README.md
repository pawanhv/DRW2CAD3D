# LoRaAlert
Generate alert messages by looking at images from a surveillance camera using deep learning algorithms and later send message through LoRa Networks.

One of the biggest drawbacks of LoRa network is its bandwidth and sending images through LoRa is practically not feasable. 

LoRaAlert is a deep learning model that takes in images as input and converts them into a text message that can be exported and later broadcasted through low bandwith networks like LoRa. It uses an image captioning architecture to generate an intermediate domain specific language which is later converted to Human understandable language.

Note: This project is meant as a proof-of-concept; the model isn't built to generalize to the variability of images as seen in real  situations, and currently only simple use-cases are implemented.

For detailed capabilities of this code refer to the documentation.

## Setup
### Prerequisites

- Python 3 (not compatible with python 2)
- pip

### Install dependencies

```sh
pip install -r requirements.txt
```

