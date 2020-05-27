# Types of Notebook

## Exploratory Notebooks
- MeSsY
- Can include error cells

## Subject Notebooks
- More polished
- Still trying things out / going down blind alleys / WIP
- Types
    - Data importing / cleaning
    - EDA
    - Modeling (later mods)
    - Other comparisons (if needed)
    - Viz - remember to write takeaway in markdown!

## Final notebook
- Most polished
- Geared toward empathy and naivety of reader
- Markdown and style for communication, not org.
- Straight run-through of analysis
- User should be able to replicate project by running cells one-by-one
- Organized by CPFORR
- Detailed markdown explanations at each section
    - Also for each step of analysis
- Include viz - w/ explanation of takeaway!

# Best Practices Within Books
- Markdown!
    - Every book includes a detailed written explanation at the very top outlining:
      - What book is doing
      - How book is organized
    - Sections and subsections
    - More subsections
    - Written explanations:
      - Why doing each small step of analysis
      - Results of such small steps 
      - How those results lead to next step you try/do
        
        
- **D**on’t **R**epeat **Y**ourself (DRY)
    - If you find yourself typing the same thing / copying & pasting:
        - Write a function
        - Make a loop
        - Make a new object
        - Some combo of the above
    - Write functions.  Step-by-step:
        - Once you complete a small task, put it into a function.
        - Small chunks.  Don’t over-engineer!
        - Once a “subsection” eg data cleaning is completed, wrap up small functions into one that runs them sequentially and runs “subsection” soup-to-nuts
- .py files
  - Put your functions in txt files w/ a .py extension when writing exploratory notebooks
  - Import them where needed into subject notebooks 
  - ```python
  from directory_structure_to_get_to_py_file.py_file import function1, function2
  ```
  - Don't forget to import every package needed for the functions at the top of the .py file

        
        

