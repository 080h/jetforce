<h1 align="center">Jetforce</h1>

<p align="center">An experimental python server for the new, under development Gemini Protocol.</p>

<p align="center">Learn more about Project Gemini <a href="https://gopher.commons.host/gopher://zaibatsu.circumlunar.space/1/~solderpunk/gemini">here</a>.</p>

<p align="center"><img alt="rocket launch" src="resources/rocket.jpg"/></p>

<p align="center">
  <a href="https://pypi.python.org/pypi/jetforce/">
    <img alt="pypi" src="https://img.shields.io/pypi/v/jetforce.svg?label=version"/>
  </a>
  <a href="https://github.com/michael-lazar/jetforce/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-FFSL%20v1-informational.svg">
  </a>
  <a href="https://github.com/psf/black">
    <img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg">
  </a>
  <a href="https://saythanks.io/to/michael-lazar">
    <img alt="say-thanks" src="https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg"/>
  </a>
</p>

## Features

- A modern python codebase with type hinting and black formatting.
- A built-in static file server with support for gemini directory files.
- Lightweight, single-file framework with zero dependencies.
- Supports concurrent connections using an asynchronous event loop.
- Extendable - loosely implements the [WSGI](https://en.wikipedia.org/wiki/Web_Server_Gateway_Interface) server/application pattern.

## Installation

Requires Python 3.7+ and OpenSSL. The latest release of Jetforce can be downloaded from [PyPI](https://pypi.org/project/Jetforce/):

```bash
$ pip install jetforce
```

Or, you can download the repository and run the script directly:

```bash
$ git clone https://github.com/michael-lazar/jetforce
$ cd jetforce
$ ./jetforce.py
```
