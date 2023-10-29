## Tooling Setup Guide

- Download and watch guide video from Moodle: https://moodle.inholland.nl/course/view.php?id=21542&section=0&sectionid=658872#section-97
- Create an account on GitHub
- Create a repo called "web-markup"
- If your computer does not have Git, install it: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
  - If you are on a Mac, you can either install XCode (will take a long time) or install Brew and then use Brew to install Git.
- Install VS Code: https://code.visualstudio.com/
- Copy the URL from your GitHub repo and clone it in VS Code
- Add a file in the root of your project called index.html
- Use Emit command (!) to create a basic HTML page
- Add a message like "hello!" inside the page <body></body> tags
- Commit your code
- Push it to GitHub

If you are getting an error about username and email, not being defined, try running these commands in your terminal using your username and email:

git config --global user.name "Bob"
git config --global user.email "bob@example.com"

- Confirm that your page is appearing on GitHub
- In GitHub, go to settings -> pages
- Select the main branch for your deployment
- Look under actions and wait for the build to finish
- Go to your published page: https://[your github username].github.io/[your repo name]
