# Developer Flow Dashboard

This project generates reports on flow metric from a given GitHub repo using the Github API.

## Prerequisits

- Install [Python 3](https://www.python.org/downloads/) if needed
- Install [VSCode](https://code.visualstudio.com/) if needed
- (Optional but recommended) install [Conda](https://www.anaconda.com/products/distribution)

## Getting Started

1. Clone repo `git clone https://github.com/bmcilw1/dev-flow-dashboard.git`
2. Install Requirements

   - (Optional) Use [Conda](https://www.anaconda.com/products/distribution) or [Virtualenv](https://virtualenv.pypa.io/en/latest/installation.html) to separate dependencies from your main Python environment

   ```bash
   pip install -r requirements.txt
   ```

3. Clear output of all cells, restart runner, and run all code cells in [Data Collection](./Github_Data_Collection.ipynb) in VSCode
4. Clear output of all cells, restart runner, and run all code cells in [Flow Dashboard](./Flow_Dashboard.ipynb) in VSCode
5. Save changes to notebook runs and output files generated
6. Push data from the updated run to a branch
7. Evaluate data

## Maintainers

Author: [Brian McIlwain](mailto:technicallyemployed@gmail.com)
