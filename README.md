# mss-sbi-project
Repository for the Manchester Summer School 2025 data science project on Sites of Biological Interest in Greater Manchester.

This project is built using Jupyter Book and deployed with GitHub Pages.

The link to the deployed website is here: https://chrissoderberg-ons.github.io/mss-sbi-project

## Contributing guidance

To contribute to this project:

1. Fork the repository
2. `git clone` to clone the repository to your local machine
3. Create a Python virtual environment and install the dependencies via `pip install -r requirements.txt`
4. Add your virtual environment to IPython so that you can develop in Jupyter Notebooks / JupyterLab: `ipython kernel install --name=<env name>`
5. Make your local modifications and check you can build the book using `jupyter-book build sbi-analysis`
6. Commit and push your changes to the remote
7. Open a pull request to merge your changes

## Important documentation

- [GeoPandas](https://geopandas.org/)
- [Git](https://git-scm.com/)
- [GitHub](https://docs.github.com/en/get-started)
- [Jupyter](https://docs.jupyter.org/)
- [JupyterBook](https://jupyterbook.org/)
- [Shapely](https://shapely.readthedocs.io/)

## Data sources

- [GMCA - Identified supply of housing, industrial/warehousing and offices 2024 in Greater Manchester](https://www.data.gov.uk/dataset/16fa3096-3716-4d6f-94eb-877a1e7751fa/identified-supply-of-housing-industrial-warehousing-and-offices-2024-in-greater-manchester)
- [GMEU - Sites of Biological Importance in Greather Manchester](https://www.data.gov.uk/dataset/81cbf1a0-6304-470c-ade8-60272be0d219/sites-of-biological-importance-sbi-in-greater-manchester)
- [ONS Open Geography Portal - Administrative Boundaries](https://geoportal.statistics.gov.uk)