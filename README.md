# emacs_cpp_completion
C/C++ code completion with emacs using Irony and GTAGS

Blog Post: http://cachestocaches.com/2015/8/c-completion-emacs/

This repository includes two sets of files. The first, `cpp_completion.el` contains the emacs lisp configuration file required to install/activate the packages within emacs. Include this file in your `~/.emacs.d/` folder, and then put `(load-file "~/.emacs.d/cpp_config.cpp")` in your `init.el`. The other files are extremely simple example source files for checking that the code completion is working correctly. They include a `main.cpp` file, and a couple of other files, `rect.cpp` and `rect.hpp`, which define a simple class definition for testing.

The details of how to properly use the code provided in this repository, and to fully activate Irony and GTAGS, can be found [in this blog post](http://cachestocaches.com/2015/8/c-completion-emacs/).