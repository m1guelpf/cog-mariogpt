# MarioGPT: Generating Super Mario Levels with Language Models
[![Replicate](https://replicate.com/m1guelpf/mario-gpt/badge)](https://replicate.com/m1guelpf/mario-gpt) 


This repository contains a modified version of the [MarioGPT source code](https://github.com/shyamsn97/mario-gpt), which adds support for token streaming. It's packaged as a [Cog model](https://github.com/replicate/cog) to be run on [Replicate](https://replicate.com).

## Usage

First, make sure you've got the [latest version of Cog](https://github.com/replicate/cog#install) installed.

Build the container image:

```sh
cog build
```

Now you can run predictions on the model:

```sh
cog predict -i "prompt=many pipes, many enemies, some blocks, high elevation"
```

## Acknowledgments

```bibtex
@misc{https://doi.org/10.48550/arxiv.2302.05981,
  doi = {10.48550/ARXIV.2302.05981},
  url = {https://arxiv.org/abs/2302.05981},
  author = {Sudhakaran, Shyam and González-Duque, Miguel and Glanois, Claire and Freiberger, Matthias and Najarro, Elias and Risi, Sebastian},
  keywords = {Artificial Intelligence (cs.AI), Computation and Language (cs.CL), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {MarioGPT: Open-Ended Text2Level Generation through Large Language Models},
  publisher = {arXiv},
  year = {2023},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
