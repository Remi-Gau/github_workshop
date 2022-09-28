[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

# GitHub workshop

github workshop for GlimR 2022

Slides are available [here]()

This is tutorial on some of the basics of github that was used for a workshop at
the GlimR 2022 conference.

This scenario is written from the point of view of a new Github user Eskarina
Smith who has just created her github account with the username "GlimRrrrr"
(this may be a reference to the fact that talk like a pirate day was only a few
days ago).

This explains:

- version control a single file
- set up a landing page for your github profile
- how to build a website in 5 minutes
- have a first draft of your own webpage
- get a DOI for your code

## Single file

Sometimes you may only want to keep track of a code snippet

For this you can use GitHub gist

<!-- picture create Gist -->

this could for example be a personal cheat sheet of some useful commands

command to recursively gzip all nifti files in the current directory

```bash
find . -type f -name "*.nii" -exec gzip ();/
```

give a name to the file

do an update

## profile repo:

Most often you will want to keep track of several files and folders, so in this
case you will want to create a new repository.

In this case we will set up a repository that will help us create a more
welcoming page on our github profile

We will create a repository that has the same name as our user name.

<!-- picture new repository -->

GlimRrrr

Create repo: with default readme

Now we can edit the readme to make it a bit nicer

Click on the readme and on the edit button to start adding things into it.

Readme.md is a markdown file (mark up language like, hackmd for training)

Scroll down and commit the change.

<!-- add picture -->

You can now go browse the history of commits

See line added and removed

<!-- add picture -->

Go back to the github profile to see your new landing page

Adding a profile picture

Use one from this person does not exist

Add picture to readme

Show how to upload file

Commit by creating a branch

<!-- Show pull request and code review -->

improve your profile (awesome readme)

## turn into a website

add a `_config.yml`

list of possible themes

activate github pages

## create your academic wesbite

fork a template set up github pages add picture add bio, papers

use a paper generator to create a fake paper
