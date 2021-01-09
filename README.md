# Book_Recommendation_System

## Introduction

This project was created as the final project of the "Models of Reasonings" signature. It is a book recommendation system developed with SWI-Prolog. The books are from a Kaggle database [https://www.kaggle.com/jealousleopard/goodreadsbooks].

## How to use

Install the SWI-Prolog tool:

* https://www.swi-prolog.org/download/stable

Open a terminal and write:

```
$ swipl "book_system.pl"
```

After run the program type:

```
$ start.
```


A few observations:

* Always write a dot (.) after input data
* Always use lower case
* The system is not extremely robust yet (future task), so remember to input the correct information

## Usage example

The follow sequence was obtained from the screen of the terminal:

```
?- start.
Expert System - Book Recommender
Please answer questions below
It helps to find books for your preference

   What is your name?
|: igoraltvidal.

   Which gender do you identify yourself?
1. male
2. female
3. other
|: male.

   How much time do you have?
1. Little
2. Medium
3. Many
|: little.

   Do you prefer top ranked books?
1. top_ranked_book
2. normal_ranked_book
|: top_ranked_book.

   How old you prefer the books?
1. new
2. normal
3. old
|: normal.

   What kind of book would you like to read?
1. scientific_or_technology
2. narrative
|: narrative.

   Do you enjoy learning about the cultures of different civizaltion?
1. no
2. yes
|: yes.

   What about the histories of a fictional universe?
1. not_interested
2. i_like_it
|: i_like_it.

You should read this book:
The Story of Salt
true .
```

