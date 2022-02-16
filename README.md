# A03
Part 1: Webstorm Tutorial
1. You will have to download Webstorm from: 
https://www.jetbrains.com/student/  
*Webstorm is an integrated development environment for JavaScript and related technologies*
2. On the Jet Brains website, you will need to create an account using your university email in order to obtain a license to use Webstorm for free. 
3. You will recieve an email confirmation in order to confirm your account and obtain your license. 
4. Click tools at the top of the the Jet Brains page and it should list all tools available. Click on Webstorm and it will give you the option to download. Click it
5. Make sure you are downloading the most recent version to avoid any problems or bugs.
6. Once you download Webstorms to your Mac, you will have to drag the download into your applications in order to begin running it.Then it will automatically add the download to your trash bin once you have done that successfully. 
7. Once Webstorm has finished installing, click the application.
8. It gives you the option to begin using your license. It will then ask you to activate it. Choose the option to activate the license using account.
9.  Once you click activate, it will take you back to the Jet Brains website. Log in with your log in credentials then it will automatically activate your license and informs you to exit out and return back to Webstorm.
10.  The application should have updated from there listing the expiration of your license. Click close once you have verified that you license is working. This will bring you to Webstorm homepage to begin working on a project. 
11. Next, you must install Git as a Local Program so you will not have to constantly program on Github. The link to the download is: https://git-scm.com/downloads
12. The git website will recognize your device and give you the newest version to download. A computer screen will show the newest version and give you option to "Download *version* for *processing system*". Click it. 
13.  Once you click that button, at the top of the screen it will state "Download for *processing system*" for example, "Download for macOS"
14.  There are several options for installing Git on your processing family. *Note that any non-source distributions are provided by third parties, and may not be up to date with the latest source release.
15.  For my MacOS, I decided to use Homebrew in order to install Git. 
16.  First, you will have to click the hypherlinked word for homebrew or follow this link: https://brew.sh/
17.  From there, you will see a mug at the top of the screen showing that you are about to install Homebrew. Homebrew is used as a missing package manager for macOS or Linux.
18.  Under "Install Homebrew" you will copy the script /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)". Then open the macOS Terminal and paste it into the Terminal. Hit return. 
19.  The script explains what it will do then pauses before it does it. Click return.
20.  Once it finishes installing, it will state it is complete and give you the option to explore Homebrew. 
21.  From there, you will return back to the git "Download for MacOS" page and copy the script $ sudo port install git and paste into the terminal and run the terminal.
22.  It wil then complete the install of git.
23.  To check the version of git on the terminal, enter the following command into your terminal: git --version.
24.  It shall state the version of git installed on your Mac. 
25. Next, you must create a Github account using the following link: https://git-scm.com/downloads
26. Github is a code hosting platform for version control and collaboration.
27. The directions are pretty straight forward. So once you create your Github account, return back to Webstorm. From there, you must connect your Github with Webstorm.
28. In Webstorm for the Mac, on the right top corner, you will click "Webstorm" a drop down menu will appear. Click preferences. 
29. Select version control, that will drop a second drop down then click git.
30. Git is a DevOps tool used for source code management.
31. You must enter the path to the git executable.
32. Usually, it automatically finds the path for you BUT, if that does not work, reopen terminal and type in the command: which git. In this case it will automatically provide you with the path. 
33. Copy and paste the command line into the path box, then click "Test" on the right. 
34. If everything is done correctly, it will show you your latest version of Git so you are good to go!
35. Next you must add github password to webstorm.
36. You do this by selecting "Appearance and Behaivor" from the large drop down menu. Then it will open a smaller drop down menu which you will then click "System Settings". Once you click that, "Passwords" should be your first option. Click it.
37. On the page, switch the bubble from "In native Keychain" to "In keypass". There should already be a path provided for you so you do not need to worry about this. Just click ok and close.
38. Next we must create a Repository on GitHub. Repositories are used for a central file storage location. In this case, we use repositories in GitHub in order to track changes to source code, resolve change conflicts between contributors, and more. 
39. Once you are logged into your Github account, click on the "+" sign in the upper right corner of the screen. 
40. Choose "Create New repository"
41. You will want to make sure the repository is public and to always add the readme file. Come up with a name for your first repository and click "Create".
42. Next, you will want to create a repository from Webstorm. 
43. Select "VCS" at the top of your Webstorm application then click "Import into Version Control"
44. From the webstorm select VCS, select checkot from version control, then Git
45. Enter your Github repository name
46. Enter your local path name; this may be automatically filled in.
47. Next, we will create a webstorm file. At the top you will create file, then HTML, then HTML 5, then Stylesheet
48. You will then add to Git dialog open, this adds to the local file system
49. You will then click commit. 
50. From there, you will click VCS, then Git, the Push.
51. Your file should now appear on Github.
52. We then have to set up Github Pages.
53. You will click settings, then check the repository name.
54. You will then select the "Master branch" and you should note the published URL.
55. Copy the Github.io URL into a browser and then post the URL into Canvas.

Resources: 
https://ajahne.github.io/blog/tools/2018/06/11/how-to-upgrade-git-mac.html
https://stackoverflow.com/questions/32661484/os-x-cant-start-git-usr-bin-git-probably-the-path-to-git-executable-is-not
https://techterms.com/definition/repository#:~:text=In%20software%20development%2C%20a%20repository,be%20accessed%20by%20multiple%20users.

Part 2: Glossary

**Branch**: a unique set of code changes with a unique name and an independent line of development.

**Clone**: To duplicate or download a repository fro Github/Git to your local machine.

**Commit**: An individual change to a file or several files. When you make a commit to save your work, Git creates a unique ID that allows you to keep record of the specific changes committed along with who made them and when.

**Fetch**: You are adding changes from the remote repository to your local working branch without committing them.

**GIT**: a DevOps tool used for source code management.

**Github**: a code hosting platform for version control and collaboration.

**Merge**: It takes the changes from one branch (in the same repository), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line.

**Merge Conflict**: A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

**Push**: To send your committed changes to a remote repsotitory on GitHub. 

**Pull**: Refers to when you are fetching in changes and merging them. 

**Remote**: This is the version of a repository or branch that is hosted on a server - Github.

**Repository**: They are easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

Reference:
https://docs.github.com/en/get-started/quickstart/github-glossary
