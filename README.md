# Quality Deliverables

### Table of Contents
[Link to deck from class here](https://docs.google.com/presentation/d/1MmJv-p2maB020MexdfuxM7JLsxSQamKjA1G_P_B-QqY/edit?usp=sharing)

[Examples](#Examples)

- [Markdown](#Markdown)
- [README](#README)
- [Notebooks](#Notebooks)
- [Viz](#Viz)
- [Deck](#Deck)

[Cheat Sheets](#Cheat-Sheets)
- [markdown](cheat_sheets/markdown_cheat_sheet.md)
- [README](cheat_sheets/readme_cheat_sheet.md)
- [notebook](cheat_sheets/notebook_cheat_sheet.md)
- [viz](cheat_sheets/viz_cheat_sheet.md)
- [deck](cheat_sheets/deck_cheat_sheet.md)

### Examples

#### Markdown
In the top level of this directory is a file called `grocery_class_md_example.md`, which contains the brief example of markdown gone over in class

In general,  
- #### section headings
- line breaks 
---
- [link to urls](https://giphy.com/gifs/dance-brad-pitt-workout-Y7O3LHmhllEk)
- [link to repos](https://github.com/learn-co-students/dsc-chi-quality-deliverables/tree/master/viz)
- links to files w/i repo directories (in the case below, a gif in the `viz` directory)

![link to viz](viz/markdown_link_example.gif)
- [links to subheadings](#README)
- *and* **stylized** ***text***

are the commands you'll want to have under your fingers.

Remember: both Jupyter Lab and Viz Code allow a Markdown Preview option that will render your markdown as you're typing. 

- for Jupyter Lab, control-click on the markdown file you're working in and select "Show Markdown Preview"

- [here are instructions for VS Code](https://code.visualstudio.com/docs/languages/markdown)


The github rendering of markdown is less robust than the ones in JL and VS Code, but for everything besides [LaTex code](https://gist.github.com/LKS90/252ac41bd4a173be35b0) (a more-robust markdown-esque language that renders math nicely) you probably won't run into any issues.

#### README
Besides the best practices outlined in the deck, there are two student-made examples of READMEs in the `quality deliverables` and `progressive_notebook_structure_example` directories.  Each doesn't adhere to best practices 100%, but they'll give you an idea to work off of instead of starting w/ a blank slate.

#### Notebooks
In the `progressive_notebook_structure_example` directory are three examples of using comments and markdown to structure your books as you work. `V1_Australia_rain.ipynb` contains no structure, and the notebooks beginning `V2` and `V3` contain progressivley more structure. 

`V1` is offered as an illustration of how frustrating it is to read books that aren't structured.  **This includes both the work of other people and your own work when you come back to it later**.  `V2` and `V3` are a little more structure than is necessary for an "exploratory" notebook, but are about right for "subject" notebooks (eg data cleaning, EDA, etc.) that are works-in-progress.

#### Viz
The files in the top-level `Viz` directory are straight-forwardly labeled from `viz_bad.png` to `viz_best.png`.  

`viz_better.png` represents something that's ok for noodling around in an exploratory notebook in order to check a quick illustration of something, but `viz_good.png` represents the minimum for a "quality visual" that should be in a README or a deck.

Remember that, when putting these graphics in a different application (like a deck), it's completely kosher to use those application's graphics capibilities to alter a viz' characteristics to make it more appealing.  For example, making the labels on a graph bigger in Google Sheets with a text box.

#### Deck

Located in the [deck from class](https://docs.google.com/presentation/d/1MmJv-p2maB020MexdfuxM7JLsxSQamKjA1G_P_B-QqY/edit?usp=sharing) are two example decks created by students.  They have the basic structure to go through but don't follow best practices.

Recall the basic structure for a deck:

- **Context**: What is the big question you are investigating? What do you imagine an answer might be that your analysis will provide evidence for?

- **Preview** - Give them enough to keep their interest throughout the more difficult parts of the presentation.

- **Familiarize dataset** - Where is the data from?  How many rows / features is it?  Share relevant parts of your EDA.

- **Outline the process** - How did you go about getting your results?

- **Results** - Help them understand how good your model is or why it isn’t great.

- **Real world application** - How did you answer your question above?  How can someone who is faced with that question in the real world use your analysis to make a decision or guide an action?  What sort of groups are able to use your analysis? 

Like notebooks and READMEs, decks are difficult to construct!  Practice makes perfect.


### Cheat Sheets

In the `cheat_sheets` [directory](https://github.com/learn-co-students/quality-deliverables-chi-seattle-051120/tree/master/cheat_sheets) are markdown files with the best practices from the deck gone over in  class.

[markdown](cheat_sheets/markdown_cheat_sheet.md)

[README](cheat_sheets/readme_cheat_sheet.md)

[notebook](cheat_sheets/notebook_cheat_sheet.md)

[viz](cheat_sheets/viz_cheat_sheet.md)

[deck](cheat_sheets/deck_cheat_sheet.md)