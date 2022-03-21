# netlify-todo
Have used JavaScript to build a To-do List that stores completed and pending task lists. Implemented the background using particle-js and Bootstrap to align the view for Mobile and web layout. Stores the data in local storage and retrieves the data each time an update is made on to the list & news data with animation with logout in HTML file. Demo: https://ashwinrishipj.netlify.app/

## Project Details
* Login Screen: handles and validates user input emailId and password. we aren't connecting any backend service to validate. Have used Regex to validate in the javascript. Also, particles.Js handles in the background options.
* Home Screen: The home screen involves in handling to-do task, displaying in the news and weather updates. On each section the user can choose to naviagate using the side bar. Have used bootstrap to buid the css. All the News API and users todo list are stored in local cache memory to avoid redudancy and data security. Additionally, user can logout where the windows forward and backward options are blocked for user security.

## Run 

About cloning a repository

You can clone a repository from GitHub.com to your local computer to make it easier to fix merge conflicts, add or remove files, and push larger commits. When you clone a repository, you copy the repository from GitHub.com to your local machine.

Cloning a repository pulls down a full copy of all the repository data that GitHub.com has at that point in time, including all versions of every file and folder for the project. You can push your changes to the remote repository on GitHub.com, or pull other people's changes from GitHub.com. For more information, see "Using Git".

You can clone your existing repository or clone another person's existing repository to contribute to a project.
Cloning a repository

    On GitHub.com, navigate to the main page of the repository.

    Above the list of files, click Code. "Code" button

To clone the repository using HTTPS, under "Clone with HTTPS", click
. To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click . To clone a repository using GitHub CLI, click Use GitHub CLI, then click

. The clipboard icon for copying the URL to clone a repository

The clipboard icon for copying the URL to clone a repository with GitHub CLI

Open Git Bash.

Change the current working directory to the location where you want the cloned directory.

Type git clone, and then paste the URL you copied earlier.

$ git clone https://github.com/ashwinrishipj/netlify-todo

Press Enter to create your local clone.

$ git clone https://github.com/ashwinrishipj/netlify-todo
> Cloning into `Spoon-Knife`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.


