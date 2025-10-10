# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit.

In a few brief paragraphs, use your chosen metaphor to explain:

- What a commit is
- How a commit is created (include the command-line syntax)
- Why commits are useful in version control.
- Why it is important to write descriptive clear messages in team settings.

### Response 1

When you’re working with lots of files while coding, you need a system to save specific versions of your project as you make progress. Without one, you’d have to depend on not making any serious mistakes that break your code, and if something went wrong, you wouldn’t be able to easily go back to when everything was working. This is where Git comes in, a version control system that helps you keep track of every successful version of your code.

A commit in Git is like saving your progress in a video game. It takes a snapshot of your project at a specific moment so you can return to it later for whatever reason. To make a commit, you first tell Git which files you want to save by using the terminal command: “git add .”.The “.” adds all the files you’ve changed. Then you actually save the snapshot with: “git commit -m” describe what you changed”. The message inside the quotes should explain what you did, like “Fixed login issue” or “Added contact form.” Once your changes are committed, they’re saved locally on your computer. To back them up online or share them with others, you push your commits to GitHub, which is a platform that stores your code and lets others collaborate with your permission. You do this with: “git push origin main” or replace “main” with whatever name your branch is. Once you do this, the version of the code you just committed is living remotely on GitHub.

Commits and GitHub are useful because they make it easy to track your progress, work with teammates, and fix mistakes without losing your work. And when working in a team, writing clear and descriptive commit messages is super important. It helps everyone understand what changed, why it changed, and keeps the whole project organized and professional.
