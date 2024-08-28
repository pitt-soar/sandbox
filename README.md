# Sandbox

This exercise assumes you know the necessary commands and actions. Before you do this exercise, please go through [MIT's missing semester](https://missing.csail.mit.edu/2020/version-control/) or [the contributing guide](https://github.com/pitt-soar/URC/blob/main/CONTRIBUTING.md) or [video Git and GitHub Tutorial for Beginners](https://www.youtube.com/watch?v=tRZGeaHPoaw) or [Learn Git Branching](https://learngitbranching.js.org/). All of these guides should work fine. If you have any issues, contact Nick Ferguson.

## The Exercise

The sandbox repository is set up exactly like the main URC repository. You will not be able to directly commit into the main branch, this is by design. **Below are the abstract steps that you need to go through, this exercise assumes that you know and understand all of the essential git commands ([see this](https://github.com/pitt-soar/URC/blob/main/CONTRIBUTING.md#commands)).**

1. If you haven't already, create a GitHub account
2. Setup git using SSH with this [guide](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/GitHub-SSH-Key-Setup-Config-Ubuntu-Linux) if you haven't already
3. Create a new branch through GitHub (aside: when creating new branches, you need to do `git fetch` to be able to access the branch on your local machine)
4. Clone the repository onto your local machine
5. Enter the branch you just created
6. Since this part is not a part of the git experience, I will be less abstract
    1. Create a new text file with your username (you can do this with `touch {insert username here}.txt` or through the GUI)
    2. Open the text file in your favorite editor and put your name, major, and interests ([example](https://github.com/pitt-soar/sandbox/blob/main/n-f9.txt)).
    3. Save the file
7. Add your changes to a new commit
8. Stage your commit
9. Save/push your changes from your local machine to GitHub
10. Now go back to GitHub, and go to the pull requests tab ([top of this page](https://github.com/pitt-soar/sandbox/))
11. Create a new pull request with your branch
12. Assign either Nick (n-f9) or Alex (Alexander-Kwasinski) as a reviewer, and wait for one of us to approve the pull request
13. After acceptance, merge the pull request
14. Congrats! Now view the main branch and see the file you have contributed, this is the process for adding your code to the main branch of URC
