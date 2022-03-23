# Overview
The project is based on the [FEII2016 challenge](https://ir.nist.gov/feiii/2016-challenge.html) and explores different Record Linkage techniques.

To learn more about the project see the [presentation](Presentation.pdf) and [report](Report.pdf).

## Team
- Christian Bernasconi 816423
- Marco Ripamonti 806785

## Project structure
- data: contains datasets and ground truths
- record_linkage.ipynb: notebook containig the code
- requirements.txt: packages required to run the notebook


## Install and run
This project uses python. To run the project you have to:
1. Navigate to the project folder
2. Create a virtual environment:

    `python -m venv venv`

3. Activate virtual environment:
    - Windows: 

    `./venv/scripts/activate`

    - Linux: 

    `/venv/bin/activate`

4. Install requirements:

    `pip install -r requirements.txt`

5. Run jupyter notebook:

    `jupyter notebook record_linkage.ipynb`

