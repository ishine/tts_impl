# tts_impl
[![pytorch](https://img.shields.io/badge/PyTorch_2.0+-ee4c2c?logo=pytorch&logoColor=white)](https://pytorch.org/get-started/locally/)
[![lightning](https://img.shields.io/badge/-Lightning_2.0+-792ee5?logo=pytorchlightning&logoColor=white)](https://pytorchlightning.ai/)
[![black](https://img.shields.io/badge/Code%20Style-Black-black.svg?labelColor=gray)](https://black.readthedocs.io/en/stable/)
[![isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![python](https://img.shields.io/badge/-Python_3.11-blue?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3119/)

pytorch implementation of speech synthesis methods

## Models
implemented: ✅  
work in progress: 🚧  

- Vocoders
    - HiFi-GAN ✅
    - NSF-HiFi-GAN ✅
    - ISTFTNet
    - WaveNeXt 🚧
    - Vocos 🚧
    - DDSP (Subtractive / Additive)
    - SoundStream
- TTS: Text to speech
    - VITS ✅
    - VITS2 🚧
    - JETS 🚧
    - FastSpeech
    - Diffusion TTS Models
    - Flow Matching TTS Modelss
- Aligner:
    - ForcedAlign ✅

## Installation
```sh
pip install git+https://github.com/uthree/tts_impl.git
```
or clone this repository,
```sh
pip install -e .
```

## type check / lint / test
- `pysen run format` : automatic formatting
- `pysen run lint` : linter
- `pytest` : test
- `codespell` : detect typos