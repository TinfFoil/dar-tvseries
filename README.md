# Creating a corpus of subtitles for the analysis of medical dramas

This repository contains the software created in the context of the project *NEAD framework. A systemic approach to contemporary serial product. The medical drama case*. 

## Contents 

1. [Episode_data_preparation.ipynb](https://github.com/TinfFoil/dar_tvseries/blob/main/episode_data_preparation.ipynb): description of the approach followed to align the subtitles with the corresponding segments.
2. [Season_data_preparation.ipynb](https://github.com/TinfFoil/dar_tvseries/blob/main/season_data_preparation.ipynb): an example of how the alignment works on larger amounts of data.
3. [Data_preprocessing.ipynb](https://github.com/TinfFoil/dar_tvseries/blob/main/data_preprocessing.ipynb): preprocessing the data from season_data_preparation.ipynb.
4. [Report.pdf](https://github.com/TinfFoil/dar_tvseries/blob/main/report.pdf): written report about the activities carried out during the internship. 

## Usage

All files are in Jupyter notebook format and can be opened directly in Google Colab or executed locally. The expected input files are specified at the beginning of each notebook. When executing the software, an input box will appear asking the user for the path of the files. In the case of *episode_data_preparation.ipynb* and *season_data_preparation.ipynb*, the user is also given the option of exporting the data in Excel format.

## Updates

Mar 2, 2023: Fixed some issues with encoding.

Mar 4, 2023: Added a [new version](https://github.com/TinfFoil/dar_tvseries/blob/main/season_data_preparation_v2.ipynb) of season_data_preparation.ipynb that supports unique identifiers.
