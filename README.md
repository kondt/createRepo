# How to create repository and connect to Github
## Prerequisites
   * git is installed on computer
   * Configure **git global settings** by configuring *username*, *email* and main branch as *main*
   * Create a personal access token on Github.com
   * [Optional] set personal access token as an environment varaible

## Create the repository
   * Create a directory
   * Go into the  directory
   * Type `git init`
   * Create some files with some code (usually start with a README.md)
   * Type `git add nameOfFiles` *Tip: seperate the files by spaces*
   * Type `git commit -m "Commit message"`

## Connect repository to GitHub.com
   * Go to github.com
   * log into your account
   * Click the new repository button in top-right the the new repository button
       * Optionally you can initialize repository with README.md and license but I don't
   * Click "Create repository" button

In terminal, follow the second set of instructions, "Push as existing repository..."
   * Copy and paste the line which says
       * `git remote add origin https://github.com/username/new_repo`
   * Edit the command pasted by *adding* your personal token between / and github.com
   * Add the **@** symbol between personal token and github.com the command should look like so:
       * `git remote add origin https://<personal-token>@github.com/username/new_repo`
   * Type `git push -u origin main` 
