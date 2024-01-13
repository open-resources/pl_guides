(authoring)=
# Creating a PrairieLearn question

There are three important files created for the PrairieLearn platform:

1. `info.json` : A `.json` file that contains metadata about the unique ID, tags, and whether it’s manually graded, auto-graded, or externally graded.

2. `question.html` : An `.html` file where you assemble your question using question elements, plus your own text, figures, etc.

3. `server.py` : The `.py` file is where you add logic and randomization to your question. Variables from server.py can be accessed within question.html using `{{ }}` (moustache templating). It contains all the import statements as well as the variables and correct answers defined in the code section. This tells PrairieLearn how to calculate the correct answer, what the question is, what the different variables are and how to randomise the questions.

```{dropdown} Structure of PrairieLearn and Creating a Question
    :class-container: sd-shadow-lg
    :color: primary
    :open:

<div class="container youtube">
<iframe class="responsive-iframe" src="https://player.vimeo.com/video/828510744?h=8756a6194a&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="PrairieLearn_tour"></iframe>
<script src="https://player.vimeo.com/api/player.js"></script>
</div>
```