## Node.js & Rails 4 Dockerfile


This repository contains **Dockerfile** of [Node.js](http://nodejs.org/) & [Rails 4](http://rubyonrails.org/) for [Docker](https://www.docker.io/) published to the public [Docker Registry](https://index.docker.io/).


### Dependencies

* [glesage/ruby211](https://index.docker.io/u/glesage/ruby211)


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [build](https://index.docker.io/u/glesage/nodejs-rails4/) from public [Docker Registry](https://index.docker.io/): `docker pull glesage/nodejs-rails4`


### Usage

    docker run -i -t glesage/nodejs+rails4 bash