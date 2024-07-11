# CPSC 210 - Software Construction

Each term we would like to allocate a few TAs to help us develop some randomized questions on PrairieLearn for three ultimate goals:

1. Develop an infrastructure for question development between terms
1. Move to a frequent testing paradigm in CPSC 210 (4 or 5 quizzes vs. 2 midterms)
1. Allow for self-reservation quizzes in the CBTF (quizzes run over a multi-day window to give students different questions)

## Training

To start developing questions on PrairieLearn requires a bit of setup, reading, and watching videos.
We have started developing some resources for this since it is a fairly involved process.
[Here is a link to the training resources]:

### Suggested Order of the Training

- 1. "[What is PrairieLearn](https://firas.moosvi.com/oer/pl_guides/content/pl/intro.html)" Section
	- Tour of PrairieLearn (video: ~30 mins - watch at 1.5x speed)
	- Structure of PrairieLearn (video: ~3.5 mins)

- 1. "[Question Development](https://firas.moosvi.com/oer/pl_guides/content/authoring/creating_q.html)" Section
	- Creating a PrairieLearn question (video: ~15 mins)
	- Tips for Randomizing Questions (reading)
	- Randomization Framework (reading)

- 1. "[Local PrairieLearn course development (Docker)](https://firas.moosvi.com/oer/pl_guides/content/pl_docker/preparation.html)" Section
	- Preparation (reading)
	- Forking a PrairieLearn course for local development (reading)
	- PrairieLearn Course Development on Docker (reading)

## Check-in with Instructors in the `#prairielearn` Slack channel

At this point, once you're confident you've got things setup, please let us know.
Ideally you'd finish up to here before our first meeting together.

## Next Steps

### Look at some Documentation

- [pl-question-panel element](https://prairielearn.readthedocs.io/en/latest/elements/#pl-question-panel-element)
- [pl-answer-panel element](https://prairielearn.readthedocs.io/en/latest/elements/#pl-answer-panel-element)
- [pl-checkbox element](https://prairielearn.readthedocs.io/en/latest/elements/#pl-checkbox-element)
- [pl-dropdown element](https://prairielearn.readthedocs.io/en/latest/elements/#pl-dropdown-element)
- [pl-multiple-choice element](https://prairielearn.readthedocs.io/en/latest/elements/#pl-multiple-choice-element)
- [pl-number-input](https://prairielearn.readthedocs.io/en/latest/elements/#pl-number-input-element)
- [pl-string-input elements](https://prairielearn.readthedocs.io/en/latest/elements/#pl-string-input-element)
- [Review Mustached Syntax](https://mustache.github.io/mustache.5.html)

### Explore existing questions in the CPSC 210 course

For your convenience, relevant questions have been moved into this directory: `questions/2023W1/midterm1`
For TAs working on questions for "Part 1" (multiple choice, checkbox, drop downs, fill in the blanks) of the Midterms/Exams, you should explore those questions.
For TAs working on questions for "Part 2" (Workspaces and autograded questions) of the Midterms/Exams, you should explore questions from both Part 1 and Part 2.

TAs working on questions for Part 2 will need some additional training and instruction, which will be provided at a later date.

### Create a new multiple choice question

Your first task after going through the training is to create a fully randomized multiple choice question from scratch.
You should thoroughly test the question locally in a Docker environment, in your own course (IND 100).
Once you're ready for us to take a look at your course, submit a Pull Request in this repository to add it into the correct directory (for e.g., `cpsc210-instructors/questions/2023W2/practice/your_question`).

That's it! Thanks for making it this far!

## Feedback

If you have suggestions or clarification requests for the [instructions](https://firas.moosvi.com/oer/pl_guides/content/pl_docker/preparation.html) (particularly the Docker guide), please feel free to let me know, or even better, submit a Pull Request [in the repo](https://github.com/open-resources/pl_guides)!