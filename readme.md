# Cansin Varol

# This repo is a clone of https://github.com/nelaturuk/education_pathways.

# Activity 1:
<img width="495" alt="Screen Shot 2021-10-03 at 14 39 41" src="https://user-images.githubusercontent.com/48742114/135768131-c5b21868-9114-4b6e-841e-adcfd50cb179.png">

# Activity 2:
<img width="1553" alt="Screen Shot 2021-10-03 at 14 57 27" src="https://user-images.githubusercontent.com/48742114/135768200-33e79b02-2566-4b8d-b155-c700924799fe.png">

# Activity 3:
<img width="1143" alt="Screen Shot 2021-10-03 at 15 06 07" src="https://user-images.githubusercontent.com/48742114/135768225-24818a48-0bd3-4fba-8b4b-c4a9855195ca.png">

# Activity 4:
<img width="1680" alt="Screen Shot 2021-10-03 at 15 06 58" src="https://user-images.githubusercontent.com/48742114/135768245-fa735791-4a14-4946-886b-510bbc13166e.png">

# Activity 5:
Functional requirement: The application should have a Wishlist feature where users can add their preferred  courses and keep track of them easily.

Non-functional requirement: The application should be available and consistent, for example searching for ECE444 yields no results however searching for "software" has ECE444 as a result. Querying for the course code should show valid results.


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
