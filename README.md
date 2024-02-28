# Data-Engineering-Project-1TD169
## Group 13

Our selected dataset is the set of Reddit comments recommended in the project instructions: https://zenodo.org/records/1043504#.Wzt7PbhXryo 

(description: https://github.com/webis-de/webis-tldr-17-corpus?tab=readme-ov-file)

## TODO
First:
- Set up Spark cluster(s). 
- Look at the data (Reddit comments) and think of what research we want to do.

Then:
- Plan out the data research and write code for it.
- Run the analysis and note down results.
- Prepare contribution statement document.
- Present the results in the report (Graphs, images, explanations, etc)
- Write report.


## Git Guidelines

For any code changes, follow these steps:

(step 0: If you haven't already, clone the repository to your computer or vm)

### Setting up
1. Create a new branch from main and switch to it.
   
   `git branch EmanuelsExampleBranch main` (replace "EmanuelsExampleBranch" with whatever name you want for your branch.)

   `git switch EmanuelsExampleBranch`

2. Whenever you are working on your code, double check that you are on your new branch and not main.

   `git status` or `git branch`

3. Write your code.

### Merging
1. Make git track the files you've created or changed.

   `git add yourFile` Where "yourFile" is the full name of the file (pressing tab to autocomplete file names is useful)

2. Commit your code changes to that branch and write a commit message describing the code changes.

   `git commit -m "describe your code changes here"`
   
3. Push your code to your branch.
   
    `git push`

4. Add your code to the main branch by merging. First switch to the main branch.

    `git switch main`

    Then merge the branch you worked on into main.

    `git merge EmanuelsExampleBranch`

   Handle any potential merge conflicts as described here under "Steps to resolve a conflict": https://coderefinery.github.io/git-intro/conflicts/#id2

5. Your merge is complete! All your changes are now on the main branch and you can safely delete your branch. This command will only work if all your changes have been merged successfully into main.

   `git branch -d EmanuelsExampleBranch`

 #### Extra: How to add Co-authors to a commit
  Whenever you have worked together on some code, make sure to include multiple co-authors, so for the step where you write your commit you can instead write:

   ```
   git commit -m "describe your code changes here

   Co-Authored-By: Name <name@email.com>"
   ```
   where "Name" and "<name"email.com>" is their github name and email address. 

   To include multiple co-authors, you can instead write:


   ```
   git commit -m "describe your code changes here

   Co-Authored-By: Name <name@email.com>
   Co-Authored-By: Name <name@email.com>
   Co-Authored-By: Name <name@email.com>"
   ```
