# Foreword
Name: Michael Zheng

This repo is a clone of https://github.com/nelaturuk/education_pathways

# ECE444 Lab 5 Submission

## ECE444 Lab 5 Screenshot (for Activity 1)
GitHub Repo Screenshot (after cloning from the Education Pathways Repo and updating the readme.md file):
![ECE444_Lab5_part1](https://user-images.githubusercontent.com/40171966/137639647-39c1eb34-0e18-4c4b-9b2e-beaedfc90ce8.png)

## ECE444 Lab 5 Screenshots (for Activities 2-5)
Home Page Screenshot:
![HomePageScreenshot](https://user-images.githubusercontent.com/40171966/137636325-8f899b93-064a-4779-9b0a-fa5ac4c2a217.png)

Results Page Form Screenshot:
![ResultsPage_form_screenshot](https://user-images.githubusercontent.com/40171966/137636332-908ef41e-2711-4bae-932b-b774fd1fb5a9.png)

Results Page Table Screenshot:
![ResultsPage_table_screenshot](https://user-images.githubusercontent.com/40171966/137636339-9b578a77-f33b-44df-8116-4230c4388f1b.png)

## ECE444 Lab 5 Activity 6

In comparing the new, revised, styled UI with the original UI, the new UI has a hierarchal structure that the original UI was lacking. The revised UI's hierarchy explicitly explains what each section of the webpage is meant for, and provides better overall organization of the presented information.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
