# DL-template

## Description
Good practice deep learning project starter, strongly inspired from <a href="https://github.com/ashleve/lightning-hydra-template"><img alt="Template" src="https://img.shields.io/badge/-Lightning--Hydra--Template-017F2F?style=flat&logo=github&labelColor=gray"></a>. It uses the following libraries:
- Pytorch (deep learning framework)
- Pytorch Lightning (Pytorch wrapper for flexible and scalable trainings)
- Hydra (configuration tool)
- Weight and biases (experiment logging framework)
- Poetry (package manager)

## Quickstart

### Requirements

- `conda=^4.10.3`
- `poetry=^1.1.6`. You can install it as written in [their doc](https://python-poetry.org/docs/).

### Environment and dependencies
```bash
conda create --name <package-name> python=3.8
conda activate <package-name>
poetry install
```

Training a model
```bash
# default
poetry run python run.py

# config update via command line
poetry run python run.py trainer.gpus=1
```
