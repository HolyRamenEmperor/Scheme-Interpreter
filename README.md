# Scheme-Interpreter
In this project, I will develop an interpreter for a subset of the Scheme language. This is a CS61A project taken from https://cs61a.org/proj/scheme/. 
Throughout each of the important files listed below, functions with #BEGIN PROBLEM _ in .py files or ;; Problem _ in .scm files were written by me. All of the other code was provided by CS61A course staff. Regardless, a strong understanding of all the provided code was necessary in order to complete the implementation of this interpreter. 

# scheme_eval.py
scheme_eval.py evaluates a Scheme expression in the given environment. 
When evaluating a special form, scheme_eval.py redirects evaluation to an appropriate do_?_form _function found in scheme_forms.py. 

# scheme_apply.py
Applies a procedure to some arbitrary arguments.  This function has cases for the various types of procedures (builtin procedures, user-defined procedures, and so forth) that are implemented.

# scheme_classes.py
Defines environment frames and user-defined procedures such as Lambda and Mu procedures. 

# scheme_forms.py
Defines Scheme special forms.

# scheme_builtins.py
Defines various functions built into the standard library.

# scheme.py
Defines Input/Output behavior.
