# 9-things
9 things I learned about GitHub after becoming a GitHubber

BTW, check out my daily Git(Hub) Tip of the Day series at https://saraford.net already in progress!

### 1. Pull Requests are the **start** of a conversation; not a final submission
  - You can have discussions like you have on Issues called **Conversation**
  - You can **comment** on any line and have discussions on that line
	- You can still edit your code submissions to a pull request by updating the branch.

**Demo**  
  - E.g. https://github.com/saraford/your-moment-of-github-zen/pull/4/files
  - Show associated branch 
	
### 2. GitHub.com Keyboard Shortcuts
	
**Demo**
  - Press '?' and enjoy!

### 3. How to not check in your email in your commits (Part 1)

  - First, you'll need to tell **GitHub** to keep your email address private in Settings - Email - Keep my email address private
  - Next, you'll need to tell **Git** to keep your email address private. There are two ways to go about this: First is via Command Line

**Demo**
  - Go to Settings - Email - Keep my email address private
  - Go to command line and set the `git config --global user.email "username@users.noreply.github.com"`

### 4. GitHub Desktop (How to not check in your email in comments Part 2)

  - [GitHub Desktop](https://desktop.github.com/) is your new best friend of the day.
  - it handles 2FA
  - it handles authentication using your favorite shell (cmd, Git Bash, PowerShell) via Git Shell
  - Offers a GUI for github repositories, but you don't have to use it. However, you **do** want to use Git Shell, which opens your favorite shell.
  
**Demo**
  - Launch GitHub Desktop opened to a repo that has at least one branch to show visualization
  - Go to Gear - Options to set your email and your shell preference
  - Launch Git Shell

### 5. Readmes display at the bottom of a repo, aka you can use the GitHub UI for editing, creating branches, etc.

  - Readmes come from files called Readme, not special UI provided by GitHub. 
  - You can click "Add new file", type in readme, commit file by adding to a branch (or directly on master). 
  - By adding to a branch you can preview your readme under the repo list of files and/or issue a PR for others to review 
  - P.S. A Pull Request is also how you do a merge if you are the only developer on a repo

**Demo**
  - Click "Add new file", type in readme, commit file by adding to a branch (or directly on master). 

### 6. How to add a license

 - In many open source ecosystems, the metadata about projects is contained in the files themselves.
 - For longest time I was looking for an "Add License" button on GitHub.com

**Demo**
  - Add new file - type in License and you'll see options on the far right dropdown to use existing or template
  - or you can ignore the dropdown and write whatever you want in the license
  
### 7. GitHub Pages 

 - You can create a homepage for your repo, e.g. open live writer 
   - homepage: openlivewriter.org
   - repo: https://github.com/OpenLiveWriter/OpenLiveWriter.Github.io
 - You can also create a website for your username on github
	
**Demo**
 - https://github.com/saraford-tips/random-example
 - First, create a gh-pages branch
 - Go to random example, Settings - GitHub Pages
 - Choose Source = Master, Choose a theme

### 8. Gists

 - Share code snippets publicly or privately (via link)

**Demo**
 - https://gist.github.com/
 - https://gist.github.com/saraford-tips/e16d5582377bd4e2e46e9ead725ae0d2
 
### 9. Visual Studio plugin
  
 - We have a GitHub Extension for Visual Studio - https://visualstudio.github.com/
 - We're pulling in (no pun intended) pull requests workflows inside VS (okay small pun intended)
 
**Demo**
 - Open a cloned project, e.g. let's go meta and open the VS extension itself, since it is open source https://github.com/editor-tools/VisualStudio
 - Show Pull Requests tab
 - Click a pull request link
 - and there was much rejoicing!
 
