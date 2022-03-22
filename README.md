# Coding the Matrix

## Use the [initial commit](https://github.com/PeterJSims/CodingTheMatrix/tree/initial_files) for an organized collection of Klein's files 

### Notes and work through Klein's linear algebra book Coding the Matrix

---

### Klein's guide for file submission:

To get your work graded,

-   download the appropriate stencil file into the `matrix` directory,
-   edit it to include answers to whichever problems you choose,
-   make sure you can import it into Python without error,
-   test your solutions, and
-   finally submit problems from a given stencil by using the following command from a console or shell or Command Prompt:

> `python3 submit.py` <stencil filename>

For example, to submit solutions to problems appearing in the chapter *The Function*, edit `The_Function.py`, and then use the command

> `python3 submit.py The_Function.py`

Note that these commands are executed not from within the Python REPL, but within a console or shell or Command Prompt.

More about `submit`
-------------------

The `submit` script asks for your username. This can be anything you like. When you submit a correct answer, the script stores a "receipt" in a subdirectory `receipts` of your `matrix` directory, specifying your username, the data, and the identifier of the problem you solved.

To avoid having to give your username each time you run the `submit` script, you can create a file `profile.txt` in your `matrix` directory with the following line in it:

> `USERNAME philipklein`

where "philipklein" is replaced with your chosen username. Later I will write about other features of the `submit` script. In particular, we plan to have a leaderboard; you will be able to request that your successful submits be reported to the leaderboard.

