# A02

Using Webstorm with Git and Github Instructions.
1. First Git must be installed.
    Go to the official site and head to the dowloads page.
   - Download the proper installer for the operating system whether it be Windows, MacOS or Linux
   - Follow the prompts provided by the installer using default settings unless you have other preferences
2. Next install Webstorm
   - Visit the official Jetbrains Webstorm dowload page
   - Select the operating system you run on and download the installer
   - Run the installer and use the default settings and complete the set up
   - Launch the Webstorm app
3. Configure Webstorm and Git to work together
   - Open Webstorm
   - Thenn navigate to file and the either settings or preferences
   - Go to version control and select Git
   - Ensure that Webstorm can detect Git
   - Test so that webstorm recognizes git
4. Cloning Repos(repositories) from github
   - Go to the repo
   - Click the green code button and copy either the https or ssh link (if using ssh you must generate a key using ssh-keygen command storing the public key in github's ssh key storage)
   - Go to file the new then project from version control in webestorm
   - Paste the link and select the folder then clone for the files to be downloaded
5. Git workflow
   - Edit your files as needed within the workspace
   - if ready to commit go to version control and commit with a descriptive message
   - The push the changes to github with version control
   - to fetch most recent changes use pull from version control to pull changes into the local branch
6. Git branches
   - Using version control brachs cana be made and switched into using the branch menu in the bottom right corner
   - they can be merged through version control git

Glossary
  Branch - A version of a project that operates parallel to the master brancnh which allows for isolated work without affecting the master branch's code
  Clone - A local copy of a repo from a remote source which is usually github
  Commit - Saved changes to a project with a descriptive message usually ready to be pushed
  Fetch - downloading data from a repo without merging
  GIT - version control system used to track source code changes
  Github - cloud based hosting service for git repos with collaboration and sharing
  Merge - combining changes among branches
  Merge conflict - Whenn merges can't be done due to incompatible changes
  Push - sending commit history with data to remote repo
  Pull - updating local branch with remote repo changes
  Remote - version of a repo hosted on a server like github
  Repository - project folder managed by git that contains all files, history and all branches
