# IPython/Jupyter Workshop at the NGCM Summer Academy

Materials for the IPython/Jupyter workshop at the Next-Generation Computational
Modeling Summer Academy:

-   2-day course
-   21 and 22 June 2016
-   At Southampton University, Boldrewood campus, 175/1025

Course URL: http://ngcm.soton.ac.uk/summer-academy/ipython.html

Teaching is from 10am to 6pm, broken up by half-hour tea breaks morning and
afternoon, and an hour lunch break. See
[the programme](http://ngcm.soton.ac.uk/summer-academy/programme.html) for
details.

## Course content

Jupyter and IPython provide tools for interactive and parallel computing that are
widely used in scientific computing. We will show some uses of IPython
for scientific applications, focusing on exciting recent developments,
web-based notebooks with code, graphics, and rich HTML.

Day 1: Core Jupyter and IPython

-   Notebook Basics
-   IPython - beyond plain python
-   Markdown Cells
-   Rich Display System
-   Introduction to Interactive Javascript Widgets
-   Customizing IPython - a condensed version

Day 2 morning: Interactivity and the Jupyter project

-   The architecture of interactive widgets
-   Developing custom widgets
-   Notebooks as documents: sharing and converting them
-   Beyond Python: the Jupyter architecture with Julia and R
-   JupyterHub: multiuser Jupyter environments

Day 2 afternoon: Parallel computing with IPython

-   Overview of the ipyparallel model
-   Controller and engines
-   Basics of remote execution
-   Direct vs task execution
-   Integration with MPI codes
-   Handling dependencies between tasks
-   Performance considerations


## Software Requirements

-   Python 3.x
-   Jupyter, including the Notebook and IPython. It should
    be available through the usual distribution channels, such as
    [Anaconda](http://continuum.io/downloads).
-   Your favorite text editor.
-   If you have trouble installing Anaconda, [this blog
    entry](http://www.southampton.ac.uk/~fangohr/blog/installation-of-python-spyder-numpy-sympy-scipy-pytest-matplotlib-via-anaconda.html)
    may help.
-   For the material related to `nbconvert`, the `pandoc` package, together with a  `latex` installation, would be useful.

To install the packages required for this course and the Pandas course
in a new environment with Anaconda, run:

```bash
conda create -n ngcm python=3 numpy scipy jupyter ipywidgets pandas matplotlib requests scikit-image sympy
```

Then, to use this environment, enter:

```bash
source activate ngcm
```

On Windows, this command is just `activate ngcm`.

## Checking your installation

You can download and run this
[version_check.py](https://github.com/jupyter/ngcm-tutorial/raw/master/version_check.py)
script, and execute it using `python version_check.py` to check
you have fulfilled the installation requirements.


## Required knowledge

-   Basic Python,
-   some vague notion of html would be great.


## The trainers

-   [Thomas Kluyver](http://cmg.soton.ac.uk/people/tk2e15/)
-   [MinRK](http://github.com/minrk)


## Infrastructure

-   [Etherpad](https://public.etherpad-mozilla.org/p/ngcm-2016-jupyter)
-   [Slack channel "ipython"](https://ngcmsummeracademy2016.slack.com/messages/ipython/)
