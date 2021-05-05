# Flask-Quiz  

This app covers an introduction to Flask through creating x3 html files that call data from a dedicated local json database. All x3 html files extend from `base.html` file. 


Python file `run.py` includes the following;

- json & os imports
- Import Flask, session, render_template, flash, request, redirect and url_for packages from Flask library
- environment variable to enable secure code
- maximum attempts & high score variables
- route decorators for the following;
    - `index` homepage
    - `new_game` new game session, to include player id, score, riddle number and riddle attempts
    - `riddle` main code structure for generating a riddle


***

<div align="center">
<img src="static/img/flask-quiz.png">
</div>