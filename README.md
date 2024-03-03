# RATPy: Reactor Analysis Toolkit in Python

## Overview

RATPy (Reactor Analysis Toolkit in Python) is an open-source Python project developed within a graduate-level workshop aimed at promoting best practices in Python project development and engineering. RATPy provides a comprehensive toolkit for analyzing nuclear reactor simulation outputs from various codes, such as Serpent, SAMPSON, and RELAP. Designed to be both a practical tool for professionals in nuclear engineering and an educational resource, RATPy emphasizes the application of software development best practices, including project structuring, collaborative coding, and quality assurance.

## Educational Objectives

RATPy aims to meld theoretical knowledge with practical application across both nuclear reactor analysis and software engineering, with key educational objectives that include:

- **Best Practice Guidelines:** Highlighting the importance of clean code, comprehensive documentation, effective version control, thorough testing, and continuous integration.
- **Collaborative Development:** Encouraging a culture of contributions, peer reviews, and shared learning within the community.
- **Interdisciplinary Skill Development:** Combining principles from nuclear engineering with software development practices to foster a versatile skill set.

## Features

RATPy is equipped with an array of features designed for the nuanced analysis of nuclear reactor simulations:

- **Data Parsing and Standardization:** Tools for parsing and normalizing output data from various simulation codes.
- **Visualization:** Advanced visualization capabilities for graphical representation of simulation data.
- **Comparative Analysis:** Features to compare simulation results across different codes and reactor models.

## Getting Started

To get started with RATPy, you will need a Python environment prepared. RATPy is compatible with Python 3.6 and newer versions. The project uses Poetry for dependency management and package handling, streamlining the installation process.

1. **Installation of Poetry:**

If you haven't installed Poetry yet, follow the instructions on the [Poetry website](https://python-poetry.org/docs/#installation) to set it up on your system.

2. **Clone the Repository:**

```bash
git clone https://github.com/YourUsername/RATPy.git
cd RATPy
```

3. **Install Dependencies with Poetry:**

```bash
poetry install
```

This command creates a virtual environment and installs all the necessary dependencies within it, as defined in the `pyproject.toml` file.

4. **Activate the Virtual Environment:**

```bash
poetry shell
```

This command activates the virtual environment, allowing you to run RATPy and its associated tools.

## Best Practices

RATPy adheres to a set of best practices to ensure the project's quality and sustainability:

- **Code Reviews:** All contributions undergo peer review to maintain a high standard of code quality and consistency.
- **Comprehensive Documentation:** Every feature is accompanied by detailed documentation and examples to ensure ease of use and accessibility.
- **Testing:** A robust suite of tests is maintained to ensure the reliability and stability of RATPy across different versions and updates.

## License

RATPy is released under the MIT License, providing broad permissions to use, modify, and distribute the software. For more details, see the [LICENSE](LICENSE) file.
