# Otterbein Crawler


## Docker

This is a docker container for python 3 and scrapy all the initial libraries are installed by the container

- python3
- python3-dev
- python3-distribute
- python-pip
- ipython
- selenium
- pyvirtualdisplay
- AWS python sdk
- beautifulsoup
- requests
- libffi
- libxml2-dev
- libxslt-dev
- lib32z1-dev
- libssl-dev
- scrapy
- scrapyjs

### build

` docker build -t scrapy ` Builds the docker image

### run

` docker run -v ~/otter_scrapy:/opt/dev -it scrapy /bin/bash`

This comand runs the image you just built and then opens a bash terminal inside the container

To run in the backgroud run
`docker run -v ~/otter_scrapy:/opt/dev -d scrapy`

Then attach to the container

```docker attact scrapy```