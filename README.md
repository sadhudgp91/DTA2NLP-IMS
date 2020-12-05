# DTA2NLP-IMS
Digital Textual Annotation and Analysis using Natural Language Processing

## Overview
Tagger output files for annotation purpose

Introduction: DTA2NLP is a python based application for text annotation and analysis.

It has two main components: 1. An annotation component that allows the user to annotate text 
							2. Analysis component that supports pattern analysis of text and annotations in combination through a data visualization technique based on Python and NLP. (ToDO)

## Workflow

DTA2NLP is an advanced annotation tool which can convert plain utf-8 text files to annotated JSON files for importing to CATMA application for further analysis. The tool is responsible for creating tokens and start-end indices. Differentiation between direct and indirect speech is possible through this tool. Color coding and automated text annotation can be done through this tool with state of the art NLP technologies. Through trained models in german and english, the tool can analyse texts for annotation. The model used is SPACY which is the industry standard state of the art NLP tool.

## Usage:

1. Clone this repo.
2. Create a new virtual environment in Python <pip install virtualenv, then python3 -m venv venv>
3. Activate this virtual environment and install spaCy:
   cd venv&nbsp;
   .\Scripts\activate&nbsp;
   pip install spacy&nbsp;
   Download the model: python -m spacy download de_core_news_sm
4. Run the annotate file using the sandmann.txt as input argument <python annotate.py sandmann.txt>
5. If everything works, you should be able to see the output file as: annotated_data.json

Some key features of this tool are:

Direct and Indirect speech annotation
Tokenize sentence start and end indices
Import output JSON files to CATMA for visual annotation
Show noun phrases and other parts of speech inside the visualization tool (visualization toDO)
Extract dependencies 

More on the way!!
