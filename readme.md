# CARTE Education Pathways

Kieun Joshua Park

Note: This repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1 screenshot
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab5/blob/main/screenshots/Screen%20Shot%202021-10-13%20at%2011.20.05%20PM.png)

Screenshots with new css style
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab5/blob/styling-practice/screenshots/Screen%20Shot%202021-10-17%20at%2011.35.00%20PM.png)
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab5/blob/styling-practice/screenshots/Screen%20Shot%202021-10-17%20at%2011.35.51%20PM.png)
![Alt text](https://github.com/kjoshuapark/ECE444-F2021-Lab5/blob/styling-practice/screenshots/Screen%20Shot%202021-10-17%20at%2011.36.13%20PM.png)

We can see in the new design that the background colour of the webpage is a cyan-like colour which is accomplished in the background-color field for the body. The table of results looks better in many aspects. For example, the first row is shaded in a different colour from the other rows to distinguish it. The text also looks relatively cleaner mainly due to the table borders which did not exist before.

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
