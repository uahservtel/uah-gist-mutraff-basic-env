# B-ENV, Basic working environment for researchers and students

This is a reference working environment where you can create your developments using:
* python virtual environments
* python scientific analysis environments

You should use this package as follows:
* Check supported platforms
* Follow the QuickStart Guide
* Check the learning guide.
* Create your onw developments.
* Do your experiments and check results.

## Contact info
This environment is part of the MUTRAFF traffic research project developed at the *[GIST Research Group (Telematic Services Engineering Group](https://portal.uah.es/portal/page/portal/grupos_de_investigacion/49/Presentacion/QuienesSomos)* at *[Universidad de Alcala](http://www.uah.es)* developed by:
* Prof. Dr. Miguel Angel Lopez Carmona. Traffic Group Leader. [Contact](mailto://miguellopez.carmona@uah.es)
* Phd. Alvaro Paricio Garcia. MUTRAFF Traffic Researcher [Contact](mailto://alvaro.paricio@uah.es).

## Supported Platforms

This environment has been tested succesfully in the following platforms:
* Linux CentOS.6 x64
* OS X Darwin x64 (MAC)
* Windows 7

If you port the environment to a new platform, we will kindly appreciate your contribution.

## License and Use Terms

All rights belong to its creators. No total or partial distribution is allowed
without previous written consent.

All the software integrated is licensed as stated in their disclaimers. Please read them carefully ans follow their instrucitions.

## Installation and Setup

Install the related python packages as described in [Installation Pre-Requisites](./BASTRA_INSTALLATION_REQUISITES.md).

To install B-Env, you have to downkload it from the repository:
```
$ git clone https://github.com/uahservtel/uah-gist-mutraff-basic-env.git
$ cd uah-gist-mutraff-basic-env
```
You will find the "sample.py" simulator and the run scripts as described in the QuickStart Guide.

### Create and configure your python 2.7 environment

Create a python 2.7 environment:
```
$ pyenv install 2.7.10
```


### Create and configure your python 3.5 environment

Create a python 3.5 environment:
```
$ pyenv install 3.5.2
```

## QuickStart


## Directory structure

The project follows a directory structure that MUST be followed:
* bin : any runtime script such as start, stop, clean, configure, etc. See the [bin README](bin/README.md) for more info.
* libs: python code libraries See the [libs README](libs/README.md) for more info.
* tools : include here any additional that your project generates. See the [tools README](tools/README.md) for more info.
* scenes : include here any scenario with input data required for your experiments. See the [scenes README](scenes/README.md) for more info.
* experiments :  See the [experiments README](experiments/README.md) for more info.
* notebooks : python scientific notebooks for experiments research. Refer to Anaconda. See the [notebooks README](notebooks/README.md) for more info.
* docs : project documentation. See the [docs README](docs/README.md) for more info.

