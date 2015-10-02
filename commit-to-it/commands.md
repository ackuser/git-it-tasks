$ git status

Then add the file you just created to the files you'd like to commit (aka save) to change.

$ touch readme.txt

$ git add readme.txt

Finally, commit those changes to the repository's history with a short description of the updates.

$ git commit -m "<your commit message>"
Step: Make More Changes

Now add another line to readme.txt and save.

In terminal, you can view the difference between the file now and how it was at your last commit.

$ echo 'Hello World' >> readme.txt

$ git diff

Now with what you just learned above, commit this latest change.
