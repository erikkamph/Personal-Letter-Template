## Personal Letter Template
The template is split into four parts
1. main.tex
    1. Put includes in this file, comments explain
1. commands.tex
    1. Contains the header, the section and the example text shown
1. preamble.tex
    1. Contains usepackages that makes this look stylish and links work, put all other packages here
1. letters - folder
    1. Create your own letters here

## How to use this template:
1. Download a ```.zip````-file
1. Select "New Project"
1. Select "Upload Project"
1. Drag and drop or select the path to the downloaded ```.zip```-file

## Commands
command | # of arguments | argument | comment
--------|----------------|----------|--------
\\service or \\title | 1 | spontan or %title% | spontan meaning "Spontanansökan" and %title% being the title of the job ad
\\createheader | 8 | name, date of birth (yyyy-mm-dd), mail, phone, company contact name, company name, address, zip and city | Order is important, creates the 4 lines seen in the ```Personal_Letter_Template.pdf```
\\spontaneous | 6 | name, mail, phone, company name, address, zip and city | Creates the same as ```createheader```-command but without date of birth and name to contact person on the company
\\introduction | 7 | letter, x for the rest | The reason for x in 6 of 7 arguments is because you have to be creative and see the introduction first. Currently there is 3 introductions named a, b and c
\\final | 4 | letter, phone, email, name | Place an ending in the document, currently there are three which is selectable with the letters a, b and c
\\fragment | 1 | text | create a non-indented paragraph with automatic newline at the end
\\sign | 1 | name | like \\fsone to \\fsthree but without the paragraph before

Where there are a dash instead of a list of arguments follow the instruction on \\bsone for now, as you will have to use your own words in those commands. Where there are arguments just follow the arguments and everything will look nicer.