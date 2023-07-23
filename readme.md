<br/>
<p align="center">
  <h3 align="center">
    FastAPI Project
  </h3>

  <p align="center">
    Learn Dependency Injection and Inversion of Control in FastAPI by Building Online Recipe System Prototype
    <br/>
  </p>
</p>

<p align="center">
  <p align="center">
    <img src="https://img.shields.io/github/downloads/dzalhaqi/fastapi-fastapi-orm-cqrs-fitness-management-system/total"/>
    <img src="https://img.shields.io/github/contributors/dzalhaqi/fastapi-fastapi-orm-cqrs-fitness-management-system?color=dark-green"/>
    <img src="https://img.shields.io/github/forks/dzalhaqi/fastapi-fastapi-orm-cqrs-fitness-management-system?style=social"/>
    <img src="https://img.shields.io/github/issues/dzalhaqi/fastapi-fastapi-orm-cqrs-fitness-management-system"/>
    <img src="https://img.shields.io/github/license/dzalhaqi/fastapi-fastapi-orm-cqrs-fitness-management-system"/>
  </p>
</p>

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Description](#description)
  - [Preview API Docs (using Redocly)](#preview-api-docs-using-redocly)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About The Project

### Description
The application prototype developed is named the "Fitness Club Management System," which specifically addresses membership and gym fitness operations. This prototype encompasses various modules, namely administration, membership, class management, and attendance, all of which rely on a PostgreSQL database to store data. What sets this application apart is its incorporation of four distinct database connectivity methods, each configured using different Object-Relational Mapping (ORM) variations, offering users a range of choices for their own applications. Additionally, the prototype serves as a simple FastAPI application, designed to facilitate a focused understanding of essential aspects like data modeling, data persistency, and query building.

### Preview API Docs (using Redocly)



## Built With

Application deployed is build with **Python** using **FastAPI** library 

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* python

for Windows OS
```sh
python --version 
```

for Unix Based OS (Linux, MacOS, etc)
```sh
python3 --version 
```

* git

```sh
git --version 
```

> note: if you don't have python installed, you can download it [here](https://www.python.org/downloads/) and if you don't have git installed, you can download it [here](https://git-scm.com/downloads)

### Installation

1. Clone the repo

```sh
git clone https://github.com/Dzalhaqi/fastapi-fastapi-orm-cqrs-fitness-management-system.git
```

2. Create python environment

```sh
python -m venv env
```

3. Activate python environment

* for Windows OS
```sh
env\Scripts\activate
```

* for Unix Based OS (Linux, MacOS, etc)
```sh
source env/bin/activate
```

4. Install python library

```sh
pip install -r requirements.txt
```

5. Run the FastAPI server with uvicorn (default port 8000)

```sh
uvicorn main:app --reload
```

## License

Distributed under the MIT License. See [LICENSE](https://github.com/dzalhaqi/pa-mlops/blob/main/LICENSE.md) for more information.

## Acknowledgements

* [Muhammad Dzalhaqi](https://github.com/dzalhaqi/)
