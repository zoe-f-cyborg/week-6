# Week 6 Notes
- regex for inserting text at the beginning of a line:
    - search `(.+\>)` and replace with `[text]\1`
    - original regex I modified this from was `(.+\[text2]\>)`, which would insert [text] at the beginning of *only the lines with [text2]*

- https://datapraxis.github.io/sourcecaster/ as reference for wrangling text.
    - wget `for file in *.pdf; do pdftotext "$file" "${file%.*}.txt"; done` will duplicate all the .pdf files in a given directory into .txt, which allowed me to run the text files through the topic modelling tool. 
