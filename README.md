
# How to create a pull request in GitHub

#### First thing first, <br/>install Git Bash on your computer , then follow below :smile::smile::smile:

1. The next step is to fork a repo, say mine below :wink: <br/> <br/> <br/>
![Image of repo](https://github.com/Kartik-Ganiga/images/blob/main/repo.png)
click on the Fork button in the top-right corner.
<br/>
Once there, click on the  **Fork**  button in the top-right corner. This creates a new copy of my demo repo under **your GitHub user account** with a URL like <br/>

`https://github.com/<YourUserName>/lottery-solidity`

2. clone the repo by opening the terminal on your computer and running the command <br/>
`git clone  https://github.com/<YourUserName>/lottery-solidity`

3. Once the repo is cloned, you need to do two things:

 - Create a new branch by issuing the command:<br/>
 `git checkout  -b  new_branch` <br/>
- Create a new remote for the upstream repo with the command:<br/>
`git remote  add upstream https://github.com/Kartik-Ganiga/lottery-solidity` <br/>

"*upstream repo*" refers to the original repo you created using **fork**<br/>

4. **Now you can make changes to the code in your local machine**. The following code creates a new branch, makes an arbitrary change, and pushes it to **new_branch**:<br/>

    $ git checkout  -b new_branch

Switched to a new branch ‘new_branch’<br>

    $ git status
    $ git add  <your file name>
    or
    $ git add .
    $ git commit  -S  -m  "Adding a file to new_branch"
    $ git push  -u origin new_branch
 
5. Once you push the changes to your repo, the **Compare & pull request** button will appear in GitHub.<br/><br/>
 ![enter image description here](https://github.com/Kartik-Ganiga/images/blob/main/PR.png)

6. Click it and you'll be taken to this screen:<br/><br/>
![enter image description here](https://github.com/Kartik-Ganiga/images/blob/main/PR%20issue.png)

Open a pull request by clicking the **Create pull request** button.
Here using #issueNumber you can link your Pull Request ( PR ) to the respective gitHub issues 

Happy coding :sunglasses::robot::smiley::smiley::smiley::smiley:
