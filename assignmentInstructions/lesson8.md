1. Get organized and write some code!
   - [ ] In your GitHub repository, if you have not yet merged your pull request from last week, merge your open lesson-7 pull request by going to the "Pull Requests" tab of your repository.  Click on your open pull request, then click on the green 'Merge Pull Request" and confirm the merge.  This will update your main branch with the work you did on your lesson-7 branch.
   - [ ] Open your code editor and, in the terminal, make sure you're on your main branch.  If you're still on your lesson-7 branch, you can switch to your main branch by using the git command `git checkout main`.  
   - [ ] Update your local main branch to include your lesson-7 work by pulling your changes from your GitHub repository main.  Use the following git command in your terminal to do this: `git pull origin main`
   - [ ] Still in your terminal, create a new local branch to keep track of just the work you'll do for this assignment by running `git checkout -b lesson-8` in the terminal.  Doing this also copies the lesson-7 work you merged to main and pulled to your local machine so now all your branches should be identical on your local machine.

2. Open your index.html file.  For the following instructions you do not need to use HTML notation yet.  We'll cover HTML next week.  If you have already learned HTML, you can add your code now if you like.  Notations of what type of elements the items should be are in parentheses after the instructions.
   - [ ] Type your name on line 1 (h1)
   - [ ] Below your name, add the phrase "About" (h2)
   - [ ] Add a paragraph below that and share a few sentences about yourself (p)
   - [ ] Under the paragraph about yourself, add the phrase "Experience" (h2)
   - [ ] Under that create a list of places you've worked or projects you've worked on (ul / li)
   - [ ] Under your list add the phrase "Connect" (h2)
   - [ ] Below that, insert links to your email, github, and any social media profiles (LinkedIn, Twitter, Instagram, etc) you would like (a / can also put them in a ul / li if you wish)

3. Once you've made the above changes to your html file, follow the below instructions to push a copy from your local machine like you did at the end of last assignment.  Make sure your code gets copied to GitHub by adding changes to staging, committing the staged changes, and pushing them from your local machine to GitHub:
   - [ ] Check the status of the changes you just made (editing the index.html file) by running `git status` in your terminal
   - [ ] Stage all your changes for commit by running `git add .` in your terminal
   - [ ] Run `git status` again to see how things have changed.  You should get a response indicating changes staged for commit.
   - [ ] Create a commit message for reference.  You can use a different message if you wish.  Run `git commit -m "about, experience, connect sections added"`
   - [ ] Push these changes to your GitHub repository from your local computer by running `git push`

4. Now let's make sure that lesson branch will be reviewed.
   - [ ] Go to your GitHub repository page in your web browser now, and you should see a "lesson-8 has a recent push" notice with a green "Compare & pull request" button.  Click that button
   - [ ] Feel free to put notes to yourself or notes for your reviewer in the description (be sure you're including any questions to your reviewer in your assignment submission form though!) and click the green "Create pull request" button.
   - [ ] Copy the address of your pull request page (should look like `https://github.com/yourUsername/name-classname/pull/2`) and paste it into your assignment submission form.

5. What next?
   - If you're on track with class, wait to get feedback and/or the email notice that your assignment review is complete before confirming and merging your pull request to the main branch.
   - If you're behind or are working ahead:  
     - if you're confident your work is accurate, merge your pull request and continue working through class.
     - if you're not sure about your work this week, schedule a 1:1 session with a mentor and review your work together before merging.
