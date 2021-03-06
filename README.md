# Madlibs Activity
For this activity, you will use what you've learned about git to work collaboratively as a classroom to fill out a couple Madlibs stories.

## How To Setup This Activity

1) Form a group with your neighbors. You should choose one person whose computer you will use. 

2) Make a Github account if you haven't already got one. This should be a personal account for the person whose computer is being used. We'll be using GitHub in our homework assignments this semester. You don't have to use identifying information when you create your account.

3) Fork the starter repository on Github. Forking means to make a copy of the code but attach it to your own Github repository so that you can make changes.
Technically you are "cloning" the starter repo. GitHub calls this "forking" because they add some other
bells and whistles on top. You should see a grey button at the top that says "fork"---that is what you want. If you need more information, look at [https://help.github.com/articles/fork-a-repo/](https://help.github.com/articles/fork-a-repo/)

4) Clone the repo to your development environment: your computer or Cloud9, if the instructor
set up a Cloud9 account for you. You can request one [here](https://forms.gle/trDFWsfgGZnCVtsy6).
 
5) Open the `index.html` file to see the app working on your computer. 

6) Take a look around at the files. Familiarize yourself where everything lives. 

5) Create new stories, verbs, nouns, adjectives, and adverbs! The instructor will likely
assign you to one of these. Checkout a new branch with a good name before you do your work. This will be a command like

```
git checkout -b kyle-new-verbs
```

Here, I named my branch "kyle-new-verbs". You should name yours something *different*, no spaces. E.g.
your branch name might be "jane-new-stories" or "rad-verbs-for-class-by-rachel".


7) Create a new file. You can also edit existing files, but that will make our merging harder! If you want to make a new file of verbs, you might make a file at
`/js/verbs/kyle-new-verbs.js` and in that file, add new verbs.

You should choose a name other than "kyle-new-verbs.js". 

8) Check your code works. Did you break the app? No? Great!

9) Commit your changes and share them

    First, take a look at the status of your work

    ```
    git status
    ```

    It should show what files are new and what files are changed. Now, you want
    to add the new files, try the `git add` command. You'll need to supply a file name.

    Once you've added your changes to the "staging area", you want to make a commit. This
    is a command like

    ```
    git commit -m "Added some verbs for class"
    ```

    Now, push your changes up to GitHub.

    ```
    git push origin BRANCHNAME
    ```

    where `BRANCHNAME` is the name of your branch.

10) Go to GitHub, find your fork and the new branch, then make a pull request

    Pull requests let you tell others about changes you've pushed to a repository on GitHub. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

    Click on the logo at right to get started.
    ![Starting the pull request](https://github.com/yale-cpsc-113/CPSC113-madlibs/blob/master/images/pull.png).
    Then, once you get to another page, click the blue link.
    ![Continuing the pull request](https://github.com/yale-cpsc-113/CPSC113-madlibs/blob/master/images/pull2.png)

    Finally, click the create button to checkout the commit.
    ![Finishing the pull request](https://github.com/yale-cpsc-113/CPSC113-madlibs/blob/master/images/pull3.png)
    If you need extra help, check this out [https://help.github.com/articles/using-pull-requests/](https://help.github.com/articles/using-pull-requests/) or just come see a TA.

11) The instructor will merge in everybody's work. 
