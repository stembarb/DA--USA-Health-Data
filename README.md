# USA Health Data

## Table of Contents

* [Description](#description)
* [Tools & Dependencies](#tools)
* [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)

## Description

The aim of this project is to analyze USA health data. I have performed an exploratory analysis on data provided by [WHO](http://www.who.int/gho/en/).

## Tools & Dependencies

Datasets used in the project is freely accessible on [WHO](http://www.who.int/gho/en/) website. 

The data is stored in the `/datasets/` folder of the project files.

Analysis has been performed in the [Jupyter Notebook](http://jupyter.org/), using Python 3.x.  

## Installation

To run this project:
  
1. With python 3.x installed, create a virtual environment and activate it as shown:
  
```shell
  virtualenv -p python3 my_virtualenv
  source my_virtualenv/bin/activate
```
2. Clone this repository into your virtual environment:  

```shell
git clone https://github.com/BarbaraStempien/DA--USA-Health-Data.git
```
3. Install project dependencies:  

```shell
pip install -r DA--USA-Health-Data/requirements.txt
```
  
4. Open Jupter Notebook, and run the project.

## Contributing

I accept contributions. For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT License](LICENSE)

Copyright (c) 2018 Barbara Stempien

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
