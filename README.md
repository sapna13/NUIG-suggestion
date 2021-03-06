# NUIG-suggestion
Predicts whether a given text contains a suggestion or not. Given text can be a tweet or a sentence.

## REQUIREMENTS

This package requires python3.5, rest of the requirements are listed in the requirement file.

## INSTALLATION

Run: 
suggestionAPI.py

## USAGE

http://localhost:5000/api/?algo=SuggestionMiningDL&i=type%20your%20text%20here

in your browser, where text can be a sentence or a tweet. 
The service should return 'suggestion' or 'non-suggestion'

## CREDITS (citations if available)

The neural network based classifier has been implemented using the deep learning library KERAS [site](https://keras.io).


## ACKNOWLEDGEMENT

This development has been partially funded by the European Union through the MixedEmotions Project (project number H2020 655632), as part of the `RIA ICT 15 Big data and Open Data Innovation and take-up` programme.

![MixedEmotions](https://raw.githubusercontent.com/MixedEmotions/MixedEmotions/master/img/me.png) 

![EU](https://raw.githubusercontent.com/MixedEmotions/MixedEmotions/master/img/H2020-Web.png)

http://ec.europa.eu/research/participants/portal/desktop/en/opportunities/index.html




# Senpy Plugins

## Installing


First, install senpy from source or through pip:

    pip install senpy


## Running

Run with:

    git clone https://github.com/gsi-upm/senpy-plugins-community.git
    python -m senpy --port 5000 -f . 
