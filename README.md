# Women In Data Science ATX - 👻 Making GitHub Less Scary

This is the Jupyter Notebook and playground repository for an October, 2017, presentation about git and GitHub to the Austin meetup group [Women in Data Science](https://www.meetup.com/Women-in-Data-Science-ATX/).

## Audience

The audience for this talk has some experience with git but not with complex workflows like rebasing and cherry-picking. This presentation imagines you usually follow a strict recipe of commands, and if at any point it deviates from that recipe, it would be easier to delete everything and start from scratch.

This workshop will give you alternatives to setting it all on fire.

## Viewing this Notebook

GitHub does a nice job of rendering Jupyter Notebooks, but even better, go to [the `.ipynb` file in GitHub](https://github.com/scichelli/wids-github/blob/master/Making%20GitHub%20Less%20Scary.ipynb) and use the theta-looking icon in the top right to open the notebook in `nbviewer`.

## Repo for Exercises

Use the [exercises repo](https://github.com/scichelli/wids-github-exercises) for modifying files and executing git commands, without getting conflicts from _this_ repo's tracking of the Notebook file you are using.

## Using this Notebook

Clone this repo to get your own local copy of the Notebook (see the "Fork and Clone" section of the notebook). You need to have git, python 3, and jupyter notebook installed. Invoke the notebook with the command `jupyter notebook` when you are in the directory for this repo.

The notebook takes advantage of the `%%bash` "magic" command (a feature of Jupyter Notebook) to invoke commands in the bash shell on your system. If you want to try typing the `git` commands at the git bash command prompt, leave out the `%%bash` part.

When viewing locally, don't bother invoking the first code block, with the `HTML()` python method, because that sets the font to a large size for presenting.

Within the Notebook are commands to clone the [exercises repo](https://github.com/scichelli/wids-github-exercises), so once you have the Notebook, it will guide you through getting the other repo.

## Meetup Slides

[Women In Data Science ATX October Meeting](https://docs.google.com/presentation/d/1WoxCvqB-XEZWLwHkjF0MsHrMd66A-b3f9b-Md6RLm9Y/)
