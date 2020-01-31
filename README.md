g. gambino

01/31/2020

Introduction

The goal of this exercise is to create a product to highlight the prediction algorithm that you have built and to provide an interface that can be accessed by others. For this project you must submit:

A Shiny app that takes as input a phrase (multiple words) in a text box input and outputs a prediction of the next word.
A slide deck consisting of no more than 5 slides created with R Studio Presenter pitching the algorithm and app.


Data set was down loaded following the course instruction.

After loading data into R, it was created a corpus and cleaned removing punctuation, links, white space, numbers and all kinds of special characters.

This corpus was then tokenized in a database called n-grams, after this procedure It was aggregated in a  bi-,tri- and quadgram term frequency matrices have been transferred into frequency dictionaries.

The result about this working method is the shinyapp that predict the next word in connection with the text input by a user.

We have two programs: server.R and ui.R
The server.R loads the N-gram from my GitHub account
The ui.R receives text input from user.
The server.R will process the input and the next word predicted is then stored as output$textOut
The text output is the next predicted word in the sentence

Links
Final project submission (Shiny App): https://ggambino.shinyapps.io/preditive_words/

Final project submission (Presentation): https://rpubs.com/joe116/570492

Source code files available on GitHub: https://github.com/joe1161/Data-Science-Capstone-Project
