
# PTAN

PTAN stands for PyTorch AgentNet -- reimplementation of
[AgentNet](https://github.com/yandexdataschool/AgentNet) library for
[PyTorch](http://pytorch.org/)


## Installation

From sources:
```bash
python setup.py install
```

From pypi:
```bash
pip install ptan
```

From github:
```bash
pip install pip install git+https://github.com/abbymark/gymnasium_compatible_ptan.git 
```

For poetry:
```bash
poetry add git+https://github.com/abbymark/gymnasium_compatible_ptan.git
```

## Requirements

* [PyTorch](http://pytorch.org/): version 1.1.0 is required
* [PyTorch Ignite](https://pytorch.org/ignite/): provides extra bindings for ignite
* [OpenAI Gym](https://gym.openai.com/): ```pip install gym gym[atari]```
* [Python OpenCV](https://pypi.org/project/opencv-python/): ```pip install opencv-python```
* [TensorBoardX](https://github.com/lanpa/tensorboardX): ```pip install tensorboardX```

### Note for [Anaconda Python](https://anaconda.org/anaconda/python) users

To run some of the samples, you will need these modules:
```bash
conda install pytorch torchvision -c pytorch
# pip install tensorboard-pytorch
pip install gymnasium
pip install gymgymnasium[atari]
pip install opencv-python
```

## Documentation

* [Ptan introduction](docs/intro.ipynb)

Random pieces of information

* `ExperienceSource` vs `ExperienceSourceFirstLast`: https://github.com/Shmuma/ptan/issues/17#issuecomment-489584115
