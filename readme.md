A demo of the problem currently encountered in the generation of sublime-syntax files.

The file "project.grammar" is used to generate "project.sublime-syntax" (via jtree toSublimeSyntaxFile method).

The "project.sublime-syntax" file provides highlighting for the "sample.project" file.

That file shows the basic problem--how do we change scopes as indentation changes?

Currently, I just have one global scope until I can figure it out.
