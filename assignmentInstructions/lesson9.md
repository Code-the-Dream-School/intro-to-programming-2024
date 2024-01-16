1. Get organized and write some code!
   - [ ] In your GitHub repository, if you have not yet merged your pull request from last week, merge your open lesson-8 pull request by going to the "Pull Requests" tab of your repository. Click on your open pull request, then click on the green 'Merge Pull Request" and confirm the merge. This will update your main branch with the work you did on your lesson-8 branch.
   - [ ] Open your code editor and, in the terminal, make sure you're on your main branch. If you're still on your lesson-8 branch, you can switch to your main branch by using the git command `git checkout main`.
   - [ ] Update your local main branch to include your lesson-8 work by pulling your changes from your GitHub repository main. Use the following git command in your terminal to do this: `git pull origin main`
   - [ ] Still in your terminal, create a new local branch to keep track of just the work you'll do for this assignment by running `git checkout -b lesson-9` in the terminal. Doing this also copies the lesson-8 work you merged to main and pulled to your local machine so now all your branches should be identical on your local machine.

2. Add "boilerplate" HTML code as a starting point that includes all the required elements and meta tags.  While copy and pasting is common practice, this week we want you to write all the boilerplate code from scratch so you understand the parts of it and what their functions are.  REMINDER: HTML uses code called "tags" and "elements". In HTML, an element consists of a "start tag", some content, and an "end tag".  So when describing the <title> element, for example, we're referring to this: `<title>Your Title</title>` Also, keep in mind some HTML elements are "self-closing", meaning that they have one tag that opens and closes at the same time (e.g. `<meta name="description" content="Your description" />`.  First let's define what type of document the browser will be reading.
   - [ ] Open your index.html file
   - [ ] Define the document type at the top of the file by typing in `<!DOCTYPE html>` on line 1.
   - [ ] Now wrap your Name, About, Experience, and Connect sections and their content that you built last week in an `<html>` element

3. The "head" of an HTML document contains all the page's meta information, such as title and description.  This information helps with web searches and displays the page title in the browser tab.
   - [ ] Before your name, but after the `<html>` opening tag, insert a `<head>` element.
   - [ ] Inside the <head> element, add a <title> element to title your webpage
   - [ ] Below your <title> element, add additional <meta> elements (at least two) from the meta elements you've learned about and/or find at this resource: [W3Schools HTML Head](https://www.w3schools.com/html/html_head.asp))

4. The "body" of an HTML document contains all the page's visible content.
   - [ ] After the closing </head> tag, begin the body of your page by adding the opening `<body>` element. 
   - [ ] Close the body of your page by adding the closing `</body>` element between your last social media link and the closing `</html>` tag
   - [ ] Make sure all of the content you wrote last week is wrapped in the `<body>` tags
   - [ ] If you did not use any HTML code last week, wrap your content in element tags now.  As a reminder you should have:
     - [ ] Name in an `h1` element
     - [ ] About in an `h2` element
     - [ ] The paragraph about you in a `p` element
     - [ ] Experience in an `h2` element
     - [ ] Your listed experiences in a `ul` element, with each individual item in a `li` element
     - [ ] Connect in an `h2` element
     - [ ] Your social media links in `a` elements, and you can also wrap them in `ul` and `li` tags if you wish

5. HTML describes the structure of a webpage using various semantic elements, such as: headings, paragraphs, lists, and more.
   - [ ] Wrap each of the About, Experience, and Connect sections in a `<section>` element.  You'll use this later when you style your webpage to stay organized and apply different style settings to each of the different settings.
   - [ ] Give each of these sections an "id" property with the same name as the section.  Example:  The About section would look like this:
```
<section id="About">
   <h2>About</h2>
      <p>This is a paragraph about me.  Here's more info about me.</p>
</section>
```
   - [ ] STRETCH GOAL (optional):  Feel free to use even more HTML elements by adding images, navigation menus, etc.

6. Once you've made the above changes to your html file, follow the below instructions to push a copy from your local machine like you did at the end of last assignment.  Make sure your code gets copied to GitHub by adding changes to staging, committing the staged changes, and pushing them from your local machine to GitHub:
   - [ ] Check the status of the changes you just made (editing the index.html file) by running `git status` in your terminal
   - [ ] Stage all your changes for commit by running `git add .` in your terminal
   - [ ] Run `git status` again to see how things have changed. You should get a response indicating changes staged for commit.
   - [ ] Create a commit message for reference. You can use a different message if you wish. Run `git commit -m "html boilerplate and html markup done"`
   - [ ] Push these changes to your GitHub repository from your local computer by running `git push`

7. Now let's make sure that lesson branch will be reviewed.
   - [ ] Go to your GitHub repository page in your web browser now, and you should see a "lesson-9 has a recent push" notice with a green "Compare & pull request" button. Click that button
   - [ ] Feel free to put notes to yourself or notes for your reviewer in the description (be sure you're including any questions to your reviewer in your assignment submission form though!) and click the green "Create pull request" button.
   - [ ] Copy the address of your pull request page (should look like `https://github.com/yourUsername/name-classname/pull/3`) and paste it into your assignment submission form.

8. What next?
   - If you're on track with class, wait to get feedback and/or the email notice that your assignment review is complete before confirming and merging your pull request to the main branch.
   - If you're behind or are working ahead:
     - if you're confident your work is accurate, merge your pull request and continue working through class.
     - if you're not sure about your work this week, schedule a 1:1 session with a mentor and review your work together before merging.
