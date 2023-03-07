README!
Hello Rick, here's my readme!

# About the Project
This is a midterm project I was given last semester to complete. It's a shoe store which some basic functionality

# Navigating the Repo
Pretty standard stuff. No nested files, all on root folder. 


# Developer Guidelines
Always comment your code
Never merge into main without doing a PR
Never develop directly on main branch.

# Testing
Unit/regression testing will be implemented soon. In the meantime just be diligent! 

# Build and Deploy Project
1. Create github project with .io at end of repository name -> this will prompt github to create a static webserver for the website
2. Populate repo with your code. 
3. Under GitHub Repository/Settings, Click on pages, and enable the pages service.
4. The webserver will spin up your website, click on the link that will be provided: https://mmckay8984.github.io/mmckay_midterm.github.io/

# Reader About
Future Enhancements/bugs:
We'll use JIRA to track the progress, and cut respective tickets for enhancement.

# User About
TO use the app, just click on the link: https://mmckay8984.github.io/mmckay_midterm.github.io/

#  “Demonstrate Understanding of Version control”
- An article, note, etc. that describes how code will be controlled (i.e. test vs.
production)
So I placed a workflow file here that fires on PR to main branch. https://github.com/Mmckay8984/mmckay_midterm.github.io/tree/main/.github/workflows
This workflow file actually deploys the app to Azure. I took down the Server due to college security reasons. Regardless, if a PR is successfull (which can include
code reviews, code/secret scanning, test builds,) the app would deploy to azure cloud.

o Make ONE change to the code for a sample “post install” change
Changed price: see commit below:
https://github.com/Mmckay8984/mmckay_midterm.github.io/commit/9f8d65fdbae337c9ba7e0b70aeb20bed994662af
o Highlight “Commits” where you made at least one (1) CHANGE or modification
https://github.com/Mmckay8984/mmckay_midterm.github.io/commit/9f8d65fdbae337c9ba7e0b70aeb20bed994662af

o (BONUS) If you can walk through the process to implement this change
GitHub automatically updates the change on the webserver. Done!



