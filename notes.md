# Week 6 Notes
- regex for inserting text at the beginning of a line:
    - search `(.+\>)` and replace with `[text]\1`
    - original regex I modified this from was `(.+\[text2]\>)`, which would insert [text] at the beginning of *only the lines with [text2]*
