Jupyter notebook for deep neural network lecture for Ling 513 Speech Technology, winter 2020. To open in binder, click on the binder badge below.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/maetshju/ling_513_dnn_lecture/master?filepath=dnn_lecture.ipynb)

# Instructions for running the notebook locally

These instructions will assume you have [already installed Julia](https://julialang.org/downloads/). They will also default you to using the latest version. If you would like to use the conference version, you will have to change branches on this page (in the upper left corner) before downloading, or change branches using Git if you use Git to clone the repository.

1. Install the appropriate packages in Julia:

  ```julia
] add Flux Plots ProgressBars Random Statistics IJulia
```

  The "]" at the beginning means to press the "]" key to enter the package interface. Copying the whole line of code including the "]" in the Julia REPL console should automatically enter the package interface as well.

2. Download this repository. If you use Git, this can be done using `git clone https://github.com/maetshju/ling_513_dnn_lecture`. Otherwise, use the green "Clone or download" button at the upper right of the page.

3. Start a notebook in Julia. At the console interface:

  ```julia
using IJulia
notebook()
```

  Some information will be printed to the console, and a Jupyter notebook window will appear in your default web browser. If it asks you for a token, on a regular console (or CMD window on Windows), you will need to run `jupyter notebook list`, which will print out a URL with the token in it, which can be pasted into the webpage.

4. Use the Jupyter interface to find the corresponding "ipynb" files you downloaded as part of this repository. Clicking on them will open the notebooks, which you can then run from there.
