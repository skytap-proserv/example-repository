# EXAMPLE REPOSITORY

This is an example repository.  Every piece of code that we create when building solutions for our customers must land here so that we can archive it and reuse it for other solutions.  There is no sense in reinventing the wheel!

Each piece of code should live in an individual repository, and **must contain** a README file.  The README should describe the code, it's use and discuss any options.  Nobody should have to look any further than this file to understand how your code works.

## Sanitize your repository

     ________________________
    < Protect our customers! >
     ------------------------
            \   ^__^
             \  (oo)\_______
                (__)\       )\/\
                    ||----w |
                    ||     ||


Your repository **must not contain** any mention any reference to our individual customers.  Nor should the repository contain any secrets such as:

- API keys
- usernames
- passwords
- other sensitive data

You must not use the above in committed code, commit messages, filenames, etc.

If you like to use git during your development, keep in mind that any sensitive data that gets committed, no matter how temporary, is a part of the public repository **forever**.  If you do this, you must take your version 1.0 code, move it to a new repository, and pust that repository to GitHub.

## Code Style
- Code should be written in such a way that it is descrete, and callable from other code.  Code functions are to be encouraged.  (Python users should think in terms of modules)
- Code should be well documented using appropriate inline comments and docstrings.

## Code Review
Code should be reviewed by another member of the PS team, ideally by one who has not been involved -- If others cannot see what your code is supposed to do, it needs to be better documented.  Additionally each repository should have a README file that at minimum discusses the problem that the code is trying to solve, and explains what inputs the code requires.



If you have any questions, talk to Bill.
