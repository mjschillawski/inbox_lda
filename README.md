# I Fought The LDA and The LDA Won

Topic Modeling My Inbox: LDA Lightning Talk for General Assembly's Data Science Immersive

Michael Schillawski

Data Science Immersive, General Assembly, 9 March 2018

## Table of Contents

- [Repository Contents](#repository-contents) - Description of this repository's contents
- [Project Overview](#project-overview) - Summary of the project's goals
- [Data Description](#data-description) - Description of dataset
- [Project Concepts](#project-concepts) - Skills and concepts demonstrated

## Repository Contents

| FILENAME |  DESCRIPTION |
|:---------:|:-----------:|
| [README](./README.md) | Project description |
| [message_parse.ipynb](https://github.com/mjschillawski/inbox_lda/blob/master/message_parse.ipynb) | Jupyter notebook which does LDA on emails |
| [Presentation Deck](https://docs.google.com/open?id=1g1cCqZGQqu2SHiHcFdMWwqYxrccE6LnJBHSmEIm6rok) | Slide deck |
| | |
| [blog](https://github.com/mjschillawski/inbox_lda/tree/master/blog) | |
| [clean_subjects3.pickle](https://github.com/mjschillawski/inbox_lda/blob/master/blog/clean_subjects3.pickle) | extracted email texts|
| [cleaned.pickle](https://github.com/mjschillawski/inbox_lda/blob/master/blog/cleaned.pickle) | cleaned email texts|
| [corpus3.pickle](https://github.com/mjschillawski/inbox_lda/blob/master/blog/corpus3.pickle) | LDA corpus |
| [dictionary3.pickle](https://github.com/mjschillawski/inbox_lda/blob/master/blog/dictionary3.pickle) | LDA dictionary |
| [lda3.pickle](https://github.com/mjschillawski/inbox_lda/blob/master/blog/lda3.pickle) | LDA model 
| | |
| [archive](https://github.com/mjschillawski/inbox_lda/tree/master/archive)| Working files |
| [LICENSE](https://github.com/mjschillawski/inbox_lda/blob/master/LICENSE) | License for this project |
| [.gitignore](./.gitignore) | gitignore file |

## Project Overview

I gave a 15 minute presentation on Latent Dirichlet Allocation (LDA): how it works, what it's useful for, its limitations, etc. I illustrated LDA with a concrete example by topic modeling emails from my Gmail inbox. I downloaded the Gmail data archive, extracted messages from their mailbox format, and parsed the body of the email before applying LDA.

## Data Description

The corpus was drawn from one label in my Gmail inbox, specifically blog emails. I downloaded my data archive and performed topic modeling on the email bodies.

## Project Concepts

Latent dirichlet allocation; natural language processing; mailbox; email extraction.