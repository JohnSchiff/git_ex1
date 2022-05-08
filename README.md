# git_ex1

# 1. Copy `07_git_exercises/basics.sh` from our shared repo into your newly created repo, in project root directory, add and commit it. Run it by `./basics.sh`  
 
cp  C:/Users/yehunathan/PycharmProjects/DevOpsJan22/07_git_exercises/init.sh basics.sh

#2. In branch `main`, create a file called `abc.txt` containing the text `1` in it

echo 1 > abc.txt


# (3. What is the color of file `abc.txt` in Pycharm's Project view?)

Red

# (4. Add the file to the index &#40;What is the color now?&#41; and commit the changes &#40;it's recommended to use `git status` in between steps&#41;)

 git add . abc.txt 
it turns green
# (5. Append the line `2` to the end of `abc.txt` to change the state of this file in the working tree)

# (6. What is the color of file `abc.txt` in Pycharm's Project view?)

 # (7. What is the command to show changes between the working tree to branch `main`?)

 # (8. Why does `git diff --staged` print nothing?)

 # (9. Why does `git diff master` print error?)

 # (11. What does `git diff` print? why?)

# (12. What is the command to show changes between the index and branch `main`?)

# (13. Append the line `3` to the end of `abc.txt` to change the state of this file in the working tree)

# (14. Would `git diff --staged` and `git diff main` commands print the same output? why?)

 # (15. Why does `abc.txt` appear twice in the output of `git status`? )

# (16. **Unstage** the changes in your index and working tree &#40;don't commit the changes&#41;)
