# Spacewalks

## Overview
Spacewalks is a Python analysis tool for researchers to generate visualisations
and statistical summaries of NASA's extravehicular activity datasets.

## Features
Key features of Spacewalks:

<<<<<<< HEAD
- Generates a CSV table of summary statistics of extravehicular activity crew sizes
- Generates a line plot to show the cumulative duration of space walks over time
=======
Throughout the lesson, course attendees learn and apply better research software practices — including elements of FAIR — as they work to improve the software project.

## Pre-requisites

Spacewalks was developed using Python version 3.12

<<<<<<< HEAD
To install and run Spacewalks you will need have Python >=3.12 
installed. You will also need the following libraries (minimum versions in brackets)

- [NumPy](https://www.numpy.org/) >=2.0.0 - Spacewalk's test suite uses NumPy's statistical functions
- [Matplotlib](https://matplotlib.org/stable/index.html) >=3.0.0  - Spacewalks uses Matplotlib to make plots
- [pytest](https://docs.pytest.org/en/8.2.x/#) >=8.2.0  - Spacewalks uses pytest for testing
- [pandas](https://pandas.pydata.org/) >= 2.2.0 - Spacewalks uses pandas for data frame manipulation 
=======
- Episode ["1. Course introduction"](https://carpentries-incubator.github.io/better-research-software/01-introduction.html) is not making changes to the software.
- Episode ["2. Better start with a software project"](https://carpentries-incubator.github.io/better-research-software/02-better-start-version-control.html) is starting from the [spacewalks.zip](./spacewalks.zip) archive.
- [Branch 03-reproducible-dev-environment](https://github.com/carpentries-incubator/bbrs-software-project/tree/03-reproducible-dev-environment/spacewalks) matches the code at the start of episode ["3. Reproducible software environments"](https://carpentries-incubator.github.io/better-research-software/03-reproducible-dev-environment.html)
- [Branch 04-code-readability](https://github.com/carpentries-incubator/bbrs-software-project/tree/04-code-readability/spacewalks) matches the code at the start of episode ["4. Code readability"](https://carpentries-incubator.github.io/better-research-software/04-code-readability.html)
- [Branch 05-code-structure](https://github.com/carpentries-incubator/bbrs-software-project/tree/05-code-structure/spacewalks) matches the code at the start of episode ["5. Code structure"](https://carpentries-incubator.github.io/better-research-software/05-code-structure.html)
- [Branch 06-code-correctness](https://github.com/carpentries-incubator/bbrs-software-project/tree/06-code-correctness/spacewalks) matches the code at the start of episode ["6. Code correctness"](https://carpentries-incubator.github.io/better-research-software/06-code-correctness.html)
- [Branch 07-software-documentation](https://github.com/carpentries-incubator/bbrs-software-project/tree/07-software-documentation/spacewalks) matches the code at the start of episode ["7. Software documentation"](https://carpentries-incubator.github.io/v-research-software/07-software-documentation)
- [Branch 08-open-collaboration](https://github.com/carpentries-incubator/bbrs-software-project/tree/08-open-collaboration/spacewalks) matches the code at the start of episode ["8. Open collaboration"](https://carpentries-incubator.github.io/better-research-software/08-open-collaboration.html)

**Finally, the better and improved code version of the software project as it is at the end of the lesson can be found in [the "final" branch](https://github.com/carpentries-incubator/bbrs-software-project/tree/final/spacewalks).**

## Installation instructions

- Clone the Spacewalks repository to your local machine using Git.
If you don't have Git installed, you can download it from the official Git website.

```
git clone https://github.com/your-repository-url/spacewalks.git
cd spacewalks
```

- Install the necessary dependencies:
```
python3 -m pip install pandas==2.2.2 matplotlib==3.8.4 numpy==2.0.0 pytest==7.4.2
```

- To ensure everything is working correctly, run the tests using Pytest.

```
python3 -m pytest
```

## Usage Example

To run an analysis using the eva_data_analysis.py script from the command line terminal,
launch the script using Python as follows:

```
# Usage Examples
python3 eva_data_analysis.py eva-data.json eva-data.csv
```

The first argument is path to the JSON data file.
The second argument is the path the CSV output file.
