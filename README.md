# MathMonster
This is a Math Quiz project that uses Flask for interfacing with a JSON file that has all the questions and answers.
It is self-host based. Get your math skills sharpened using this customizable Math Quiz.

## How to use it
First make sure you have the following installed:
- Git
- Latest Python
- A modern browser
And execute these commands in your User Home directory to start the backend of the app:
```
python -m pip install flask flask_cors
git clone https://github.com/Kishandharan/MathMonster.git
cd MathMonster
python api.py
```
Once you have gotten this working, open the "frontend.html" file in your browser.
If you want to customize the questions, stop the backend, close the frontend, edit the 
```questions``` section in the "questions.json" file to match your requirements. Also change the 
```cap``` field to match the number of questions under the ```questions``` section. Each ```{q: "",  a: ""}```
inside the ```questions``` section corresponds to a question. the ```q``` field inside questions represents
the question iteself, and the ```a``` field represents the correct answer
