# HTML Forms

This repository (**repo**) was built to run through a step by step process to get familar with Forms and CSS. We will be using the following tools in this repo:
- Git using Terminal (Mac) or GitBash (Windows) - [Download](http://git-scm.com/downloads)
- Github.com
- SublimeText 3 Text Editor - <a href="http://www.sublimetext.com/3" target="_blank">Download</a>

The workflow outlined in the readme below will be utilized for every assignment/task/project for the course so understanding how and why is super important. If you have any questions please feel free to email instructors@learningfuze.com

### Assumptions we are making
- You have Git installed on your system. <a href="http://lmgtfy.com/?q=how+do+i+know+if+git+is+installed+on+my+computer" target="_blank">How do I know if git is installed?</a>
- You have read these Guides
	- [Why Git & Github](https://docs.google.com/document/d/1Kyrj_xEXGja4R_-syhBuoYLo53urUIL_YDNEi56Qi9w/pub)
	- [First Github Project](https://guides.github.com/activities/hello-world/)
	- [Understanding Github Flow](https://guides.github.com/introduction/flow/)
	- [Forking Projects](https://guides.github.com/activities/forking/)

## Saving the files locally

### Step 1 - Forking the Repo
- Fork this repo by clicking the "Fork" button located on the top right of this page
    <br><img src="https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/fork-circle.jpg?raw=true" height='75'>

### Step 2 - Opening Command Line & navigating to your sandbox
The below describes steps to open up the command line in on a OSX ([Mac](https://github.com/Learning-Fuze/git-workflow#mac)) or Windows ([PC](https://github.com/Learning-Fuze/git-workflow#windows)). On a Mac the application we will be using is **Terminal** and the application on windows is **Git Bash**. We will be opening up the sandbox folder in the command line. <a href="https://docs.google.com/document/d/1GYqDtY12-RgzrbbHzY7kqxpqP_y_X6c5sNKH9NLqMPM/pub" target="_blank">Where is my sandbox Folder?</a>.

#### Mac - Option 1 (Right Click)
- If you have not done so already, enable [Easy osx terminal window opening](https://github.com/Learning-Fuze/git-workflow/blob/osx_easy_terminal/osx_easy_terminal.md)
1. Go to a folder in your finder 
	- ![Folder](https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/sandbox-finder.jpg?raw=true) 
2. Right click on the folder and look for **Services** at the bottom. Then select the option **New Terminal Tab at Folder**
	- ![Folder](https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/new-terminal-tab-finder.jpg?raw=true)

##### Mac - Option 2 (Direct Terminal Access)
1. Press the command key and space bar
	- You should see the spotlight search appear
	- type in Terminal and hit enter
2. Type in `cd ` (which stands for change directory) then drag your folder into the terminal window
3. For a computer user of "test" the line would look like this
	- `cd /Users/test/Desktop/sandbox`
	- *You should see "test" replaced with your computer username*
4. Hit Enter

#### Windows
1. Open windows explorer to the sandbox folder
2. Right click and select "Git Bash" as shown in the image below
	<br><img src="https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/windows-git-bash-alt.jpg?raw=true" height="300">

### Step 3 - Cloning the repo
1. Type in the following into your command line 
	- `git clone https://github.com/[your-user-name]/html-forms.git` and hit enter. **Replace [your-user-name] with the your github username**
		- The **clone** command tells git to save the contents of the master branch onto your computer within the current directory.
		- **Note**
			- Using the command above will automatically create a directory with the same name as the Repo. In this example **html-forms**
			- The url after the word **clone** can be found in the right hand side panel of this page under the Settings link. You can click the button to the right of the url that will automatically copy this url for you
2. Then type `cd html-forms` and hit enter
- Leave your console window open, we will be using it again shortly.

#### Congratulations you have cloned the Github Repository

# Assignment
Build the **HTML** structure for these 3 forms within the 3 respecitve pages. Form1 should go into form1.html, Form 2 into form2.html, Form 3 into form3.html.

### Step 1 - Opening your html-forms directory

- Start SublimeText Editor application
- Open html-forms directory by clicking on File->Open
	- Select the html-forms folder under the sandbox folder on your desktop

### Step 2 - Add HTML form 1 elements

1. Open the form1.html file by clicking on the file name on the left hand side in SublimeText
2. Insert in HTML structure into the body tag that would duplicate the look of the image below. **Note** You should only have the HTML and no CSS yet. 
<a href="http://htmlpreview.github.io/?https://github.com/Learning-Fuze/html-forms/blob/scbowler/form1.html" target="_blank">Here is an example of how it may look</a>
3. View in the browser
	- Navigate to the html-forms folder
	- Right click on the form1.html file and select open with Chrome
4. Make sure all your elements are correctly showing up on the page

<img src="assets/form1.png" alt="Form 1 layout"> 

### Step 3 - Add HTML form 2 elements

1. Open the form2.html file by clicking on the file name on the left hand side in SublimeText
2. Insert in HTML structure into the body tag that would duplicate the look of the image below. **Note** You should only have the HTML and no CSS yet. 
<a href="http://htmlpreview.github.io/?https://github.com/Learning-Fuze/html-forms/blob/scbowler/form2.html" target="_blank">Here is an example of how it may look</a>
3. View in the browser
	- Navigate to the html-forms folder
	- Right click on the form2.html file and select open with Chrome
4. Make sure all your elements are correctly showing up on the page

<img src="assets/form2.png" alt="Form 2 layout">

### Step 2 - Add HTML form 3 elements

1. Open the form3.html file by clicking on the file name on the left hand side in SublimeText
2. Insert in HTML structure into the body tag that would duplicate the look of the image below. **Note** You should only have the HTML and no CSS yet. 
<a href="http://htmlpreview.github.io/?https://github.com/Learning-Fuze/html-forms/blob/scbowler/form3.html" target="_blank">Here is an example of how it may look</a>
3. View in the browser
	- Navigate to the html-forms folder
	- Right click on the form3.html file and select open with Chrome
4. Make sure all your elements are correctly showing up on the page

<img src="assets/form3.png" alt="Form 3 layout">

#### Good Job, lets now make sure we have it on Github


# Now What?
You may think that we are done there is nothing left to do because the task is complete but my question is. How does your Manager or Instructor know that you have completed the task Outlined for you? The answer is they don't. You only have the files locally and there for everyone else is left in the dark. We don't know if you have completed the task, we don't know if you have had any issues with the task.

### How do we address this?
We address the issue by allowing others to see our work through a centeralized Repo (Github.com).

### How do we get our files to Github?

The quick answer is by doing these steps in the command line

1. `git add .` - Add all files for staging
2. `git commit -m "Text describing what i'm commiting"` - Commit the files that were added (staged)
3. `git push origin master` - Push these files to a remote location (origin master)

*If you get an error like this `fatal: Not a git repository (or any of the parent directories): .git` you are probably not in the directory of the git repo. Make sure you changed directories outlined in the last bullet of* **Step 3 - Cloning the repo** 

### What do these steps above mean?

#### Step 1 - git add .
- `git add` is the command we use to stage files for a commit. This tells the `git commit` command which files we are saving together
- The **.** part of the command is used to tell git we want to add **all** files that have been changed or modified.
	- Other ways to add
		- `git add *` - same as `git add .`
		- `git add index.html` - only stages **index.html** for the next time you commit. This command will ignore all other changes made to other files.

#### Step 2 - git commit -m "message describing what i'm commiting"
- `git commit` is the command we use to commit the staged files to our local repo
- **-m** tells our commit command we want to add a message
- The text that is surounded by quotes is the message we want to add with our commit.
	- *A good commit message describes the functionality that was changed*. 
	- The files that were added/edited/deleted will be easy to find within the commit so no need to add the file names into the message

#### Step 3 - git push origin master
- `git push` is the command that takes our local repo and pushes the commits to a remote location
- **origin** describes the remote location. More about git remotes [here](http://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)
- **master** describes the branch you are pushing too. More about branching later but for now pushing to master will be the default

### Git Resources
- <a href="https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf" target="_blank">Git Cheat Sheet</a>
- <a href="http://rogerdudler.github.io/git-guide/" target="_blank">A simpe guide to gitHUb</a>
- <a href="http://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf" target="_blank">Download simple 'git cheat sheet'</a>

### After pushing your local branch you will see the changes on Github under your repository



