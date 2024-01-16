1. Create a new repository in your GitHub account
   - [ ] Go to your GitHub page and click the Repositories tab
   - [ ] Click the green "New" button in the top right
   - [ ] Fill in the fields to give your repository a name (use your name-**_classname_** as the name example: `maria-santiago-haumea`) and description (example: portfolio project for Intro to Programming course with Code the Dream)
   - [ ] Be sure PUBLIC is selected and check the "Initialize this repository with: Add a README file" check box.
   - [ ] Click "Create Repository"

2. Clone your newly created repository from your GitHub account to your local computer
   - [ ] On the main Code page of your repository, click the green "Code" button
   - [ ] Make sure you have HTTPS selected (not SSH or GitHub CLI)
   - [ ] Click the copy button (two overlapping squares icon) to copy your repository address
   - [ ] Go to your IDE terminal or your computer terminal.  Make sure you're in the proper directory for where you want to create and store files for your work (ex. your Desktop or a CodeTheDream folder).  Then run `git clone <url>` where the <url> portion is the pasted address you copied in the last step.

3. Get organized and write some code!
   - [ ] Navigate into the directory you just cloned by running `cd <name-classname>` in the terminal where the <name-classname> portion is the name of your repository.
   - [ ] Create a new local branch to house just the work you'll do for this assignment by running `git checkout -b lesson-7` in the terminal
   - [ ] Open the README.md file in your code editor and add your full name.
   - [ ] Create a new file in your project directory (same level as your README.md file) and title it `index.html`

4. Make sure your code gets copied to GitHub by adding changes to staging, committing the staged changes, and pushing them from your local machine to GitHub.
   - [ ] Check the status of the changes you just made (editing the readme.md file and making a new index.html file) by running `git status` in your terminal
   - [ ] Stage all your changes for commit by running `git add .` in your terminal
   - [ ] Run `git status` again to see how things have changed.  You should get a response indicating changes staged for commit.
   - [ ] Create a commit message for reference.  Run `git commit -m "my first commit"`
   - [ ] Push these changes to your GitHub repository from your local computer by running `git push`
   - [ ] **NOTE:** if you get a "fatal: The current branch..." error message.  READ the message and follow the instructions in that message to confirm that you push your work to your GitHub account.

5. Now let's make sure that lesson branch will be reviewed.
   - [ ] Go to your GitHub repository page in your web browser now, and you should see a "lesson-7 has a recent push" notice with a green "Compare & pull request" button.  Click that button
   - [ ] Feel free to put notes to yourself or notes for your reviewer in the description (be sure you're including any questions to your reviewer in your assignment submission form though!) and click the green "Create pull request" button.
   - [ ] Copy the address of your pull request page (should look like `https://github.com/yourUsername/name-classname/pull/1`) and paste it into your assignment submission form.

6. What next?
   - If you're on track with class, wait to get feedback and/or the email notice that your assignment review is complete before confirming and merging your pull request to the main branch.
   - If you're behind or are working ahead:  
     - if you're confident your work is accurate, merge your pull request and continue working through class.
     - if you're not sure about your work this week, schedule a 1:1 session with a mentor and review your work together before merging.
