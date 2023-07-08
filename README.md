# Machine Learning with Elixir and Livebook

A repo for exploring machine learning with Elixir and Livebook.  The included docker-compose file will
start up a Docker container running the latest version of Livebook.  Data will be synced to the local
`notebooks` directory.  

See below for links to many notebooks that can be imported and opened from the Livebook UI.  


## Elixir Libraries

### Nx
[Nx](https://github.com/elixir-nx/nx/tree/main/nx) - Numerical Elixir, "a multi-dimensional tensors library for Elixir with multi-staged compilation to the CPU/GPU"

[Official notebooks for Nx](https://github.com/elixir-nx/nx/tree/main/nx/guides)

### Scholar
[Scholar](https://github.com/elixir-nx/scholar) - Traditional machine learning tools built on top of Nx, including classification, regression, and clustering

[Official notebooks for Scholar](https://github.com/elixir-nx/scholar/tree/main/notebooks)

### Axon
[Axon](https://github.com/elixir-nx/axon) - Uses Nx for building neural networks in Elixir.  Includes high-level API's for creating and training models

[Official notebooks for Axon](https://github.com/elixir-nx/axon/tree/main/notebooks)

### Bumblebee
[Bumblebee](https://github.com/elixir-nx/bumblebee) - provides pre-trained Neural Network models on top of Axon

[Official notebooks for Bumblebee](https://github.com/elixir-nx/bumblebee/tree/main/notebooks)

[Example Phoenix integrations](https://github.com/elixir-nx/bumblebee/tree/main/examples/phoenix)

### Explorer
[Explorer](https://github.com/elixir-explorer/explorer) - tool for exploring one-dimensional data and two-dimensional dataframes 

[Official notebooks for Explorer](https://github.com/elixir-explorer/explorer/tree/main/notebooks)

### EXLA
[EXLA](https://hexdocs.pm/exla/EXLA.html) - Google's XLA compiler/backend for Nx.  Supports just-in-time compilation for GPU and TPU



## Vocabulary

* model - "In general, any mathematical construct that processes input data and returns output" [(reference)](https://developers.google.com/machine-learning/glossary#model)
* neural networks - A model containing at least one hidden layer.  The input is passed through each layer before generating an output. [(reference)](https://developers.google.com/machine-learning/glossary#neural-network)
* machine learning - a program or system that uses input data to train a model so that it can make useful predictions about new data [(reference)](https://developers.google.com/machine-learning/glossary#machine-learning)
* GPU - graphics processing unit
* TPU - tensor processing unit


## Elixir-Related Articles

* [Axon: Deep Learning in Elixir](https://seanmoriarity.com/2021/04/08/axon-deep-learning-in-elixir/) - April 2021
* [Elixir and Machine Learning: Nx v0.1 released!](https://dashbit.co/blog/elixir-and-machine-learning-nx-v0.1) - January 2022
* [Nx for Absolute Beginners](https://dockyard.com/blog/2022/03/15/nx-for-absolute-beginners) - March 2022
* [LiveBook inside Hugging Face Spaces](https://news.livebook.dev/livebook-inside-hugging-face-spaces-3LQaRi) - March 2023


## General Machine Learning Reference

* [Google Machine Learning Glossary](https://developers.google.com/machine-learning/glossary)
* [Google Machine Learning Courses](https://developers.google.com/machine-learning)