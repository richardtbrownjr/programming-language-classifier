Start

In General:
The Jupyter Notebook App can be launched by clicking on the Jupyter Notebook icon installed by Anaconda in the start menu (Windows) or by typing in a terminal (cmd on Windows):

jupyter notebook
This will launch a new browser window (or a new tab) showing the Notebook Dashboard, a sort of control panel that allows (among other things) to select which notebook to open.

When started, the Jupyter Notebook App can access only files within its start-up folder (including any sub-folder). If you store the notebook documents in a subfolder of your user folder no configuration is necessary. Otherwise, you need to choose a folder which will contain all the notebooks and set this as the Jupyter Notebook App start-up folder.

programming-language-classifier.ipynb can be open in a web browser for viewing.


Description

Programming-language-classifier reviews code snippets predicts which programming language code snippet comes from.  The classifier understands the varied syntax of programming languages:
C (.gcc, .c)
C#
Common Lisp (.sbcl)
Clojure
Haskell
Java
JavaScript
OCaml
Perl
PHP (.hack, .php)
Python
Ruby (.jruby, .yarv)
Scala
Scheme (.racket)

First the programming loads and reads training data.  Next it trains on a sample of said data.  Then the classifier if given a series of tests that see how well it predicts programming language.
