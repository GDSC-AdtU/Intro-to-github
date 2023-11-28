# GDSC | Assam down town University

### Introduction to Git and Github

    This repo is maintained for the git & github workshop
    And for introducing Github workflows

<hr>

# First Contributions

This project aims to simplify and guide the way beginners make their first
contribution. If you are looking to make your first contribution, follow
the steps below.

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_

<img align="right" width="300" 
src="https://firstcontributions.github.io/assets/Readme/fork.png" 
alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this
page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" 
src="https://firstcontributions.github.io/assets/Readme/clone.png" 
alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub
account, open the forked repository, click on the code button and then
click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to
this repository (your fork of this project). See the previous steps to
obtain the url.

<img align="right" width="300" 
src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" 
alt="copy URL to clipboard" />

For example: 

```
git clone https://github.com/GDSC-AJCE/first-contribution.git
```

where `this-is-you` is your GitHub username. Here you're copying the
contents of the first-contributions repository on GitHub to your computer.

## Set the Origin and Upstream URL

By convention the url of the fork that you had created is called the `origin` and the url of the original repository is called the `upstream`

You need to add the `origin` url so that git knows where to push the changes you have made, something we will see on the later part of the tutorial.
And you need to add the `upstream` url so that everytime the original repository is updated you can sync the changes to your fork.

You can add the `origin` url using the `git remote add origin` command.

```
git remote add origin <the-url-of-your-fork>
```

For example:

```
git remote add origin https://github.com/<your-github-username>/Intro-to-github
```

Similarly you can add the `upstream` url using the `git remote add upstream` command.

```
git remote add upstream <the-url-of-the-original-repository>
```

For example:

```
git remote add upstream https://github.com/GDSC-AdtU/Intro-to-github
```

You can check if the URL are successfully added by using the `git remote -v` command.

```
git remote -v
```

The output should be:

## Create a branch

Change to the repository directory on your computer (if you are not
already there):

```
cd first-contributions
```

Now create a branch using the `git branch` command:

```
git branch <new-branch-name>
```

For example:

```
git branch alonzo-church
```

Now change the head to `new branch` from `main` branch using the `git checkout` command:

```
git checkout <new-branch-name>
```

For example:

```
git checkout alonzo-church
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it.
Don't add it at the beginning or end of the file. Put it anywhere in
between. Now, save the file.

<img align="right" width="450" 
src="https://firstcontributions.github.io/assets/Readme/git-status.png" 
alt="git status" />

If you go to the project directory and execute the command `git status`,
you'll see there are changes.

Add those changes to the branch you just created using the `git add`
command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin -u your-branch-name
```

replacing `your-branch-name` with the name of the branch you created
earlier.

<details>
<summary> <strong>If you get any errors while pushing, click 
here:</strong> </summary>

- ### Authentication Error
       <pre>remote: Support for password authentication was removed on
  August 13, 2021. Please use a personal access token instead.
  remote: Please see
  https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/
  for more information.
  fatal: Authentication failed for
  'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's
  tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
  on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull 
request` button. Click on that button.

<img style="float: right;" 
src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" 
alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" 
src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" 
alt="submit pull request" />

Soon we'll be merging all your changes into the main branch of this
project. You will get a notification email once the changes have been
merged.

# Contributors

Thank you to all the GDSC Members for their contribution ([:hugs:](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
    <tbody>
        <tr> 
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/101629997?v=4" width="100px;" alt="Ayan Masood"/>
                    <br />
                    <sub><b>Ayan Masood</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://media.licdn.com/dms/image/D4D03AQGzHi2tL-uk8Q/profile-displayphoto-shrink_400_400/0/1695542753811?e=1702512000&v=beta&t=Fgg6_jUD6-pIv77DvNb0XZiDByYrk9L0rZcb3Ps6WZs" width="100px;" alt="Kaustav Raj Kalita"/>
                    <br />
                    <sub><b>Kaustav Raj Kalita</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/74696516?v=4" width="100px;" alt="Krishna Moni Das"/>
                    <br />
                    <sub><b>Krishna Moni Das</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/44723456?v=4" width="100px;" alt="Debarchito Nath"/>
                    <br />
                    <sub><b>Debarchito Nath</b></sub>
                </a> 
            </td>          
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/148809189?v=4" width="100px;" alt="Rudra Pandiya "/>
                    <br />
                    <sub><b>Rudra Pandiya </b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/138845972?v=4" width="100px;" alt=" Sanjukta Das"/>
                    <br />
                    <sub><b>Sanjukta Das</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/95901704?v=4" width="100px;" alt="Pulung Brahma"/>
                    <br />
                    <sub><b>Pulung Brahma</b></sub>
                </a> 
            </td>
        </tr>
        <tr>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/116501911?v=4" width="100px;" alt="Sanchayita Sharma"/>
                    <br />
                    <sub><b>Sanchayita Sharma</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/145021715?v=4" width="100px;" alt="Abhishek Kumar Singh"/>
                    <br />
                    <sub><b>Abhishek Kumar Singh</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/145018091?v=4" width="100px;" alt="Cheangchang CH Momin"/>
                    <br />
                    <sub><b>Cheangchang CH Momin</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/67728391?v=4" width="100px;" alt="Devdeep Singha"/>
                    <br />
                    <sub><b>Devdeep Singha</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/145791642?v=4" width="100px;" alt="Samiron Lahon"/>
                    <br />
                    <sub><b> Samiron Lahon</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/151518244?v=4" width="100px;" alt="Dhritimaan Sahariah"/>
                    <br />
                    <sub><b>Dhritimaan Sahariah</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/126232551?v=4" width="100px;" alt="Binit Deb"/>
                    <br />
                    <sub><b>Binit Deb</b></sub>
                </a> 
            </td>
        </tr>
        <tr>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/147991063?s=400&u=761b1a96c22937a91bbb86095fb16ec053c107b0&v=4" width="100px;" alt="Md Sibgatullah"/>
                    <br />
                    <sub><b>Md Sibgatullah</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/145019195?v=4" width="100px;" alt="Deepayan Ghosh"/>
                    <br />
                    <sub><b>Deepayan Ghosh</b></sub>
                </a> 
            </td>
             <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/145262103?v=4" width="100px;" alt="Karan Bharadwaj"/>
                    <br />
                    <sub><b>Karan Bharadwaj</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/145043733?v=4" width="100px;" alt="Deb Mandal"/>
                    <br />
                    <sub><b>Deb Mandal</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/38580143?v=4" width="100px;" alt="Sudipta Kumar Sarkar"/>
                    <br />
                    <sub><b>Sudipta Kumar Sarkar</b></sub>
                </a>    
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/143537871?v=4" width="100px;" alt="Bungthoi Thoidingjam"/>
                    <br />
                    <sub><b>Bungthoi Thoidingjam</b></sub>
                </a>    
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/147859899?v=4" width="100px;" alt="Pubali Saikia"/>
                    <br />
                    <sub><b>Pubali Saikia</b></sub>
                </a> 
            </td>
        </tr>
        <tr>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/70031297?s=400&u=799c40225de3aa7d57b12b47b10d0f3fc2acc6c8&v=4" width="100px;" alt="Hrishikesh Bor Saikia"/>
                    <br />
                    <sub><b>Hrishikesh Bor Saikia</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/151512266?v=4" width="100px;" alt="Preeti Senapati"/>
                    <br />
                    <sub><b>Preeti Senapati</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/115531600?v=4" width="100px;" alt="Krishna Moni Das"/>
                    <br />
                    <sub><b>Briti Sonowal</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/147907382?v=4" width="100px;" alt="Nikita Borgohain"/>
                    <br />
                    <sub><b>Nikita Borgohain</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/112088836?v=4" width="100px;" alt="Preeti Das"/>
                    <br />
                    <sub><b>Preeti Das</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/151466617?v=4" width="100px;" alt="Prasanta Das"/>
                    <br />
                    <sub><b>Prasanta Das</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/151518768?s=96&v=4" width="100px;" alt="Himraj Gogoi"/>
                    <br />
                    <sub><b>Himraj Gogoi</b></sub>
                </a> 
            </td>
        </tr>
        <tr>
           <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/149225300?v=4" width="100px;" alt="Subhajit Roy"/>
                    <br />
                    <sub><b>Subhajit Roy</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/149225300?v=4" width="100px;" alt="Subhajit Roy"/>
                    <br />
                    <sub><b>Subhajit Roy</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/151513969?v=4" width="100px;" alt="Pritidipan Saha"/>
                    <br />
                    <sub><b>Pritidipan Saha</b></sub>
                </a> 
            </td>
           <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/91265097?v=4" width="100px;" alt="Prince Ch Boro"/>
                    <br />
                    <sub><b> Prince Ch Boro</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/147152979?v=4" width="100px;" alt="Mizanul Hoque"/>
                    <br />
                    <sub><b>Mizanul Hoque</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/147377758?v=4" width="100px;" alt="Sakanipaia Lyngdoh"/>
                    <br />
                    <sub><b>Sakanipaia Lyngdoh</b></sub>
                </a> 
            </td>
            <td align="center">
                <a href="https://github.com/GDSC-AdtU/Intro-to-github">
                    <img src="https://avatars.githubusercontent.com/u/151538648?v=4" width="100px;" alt="Naipha Loham"/>
                    <br />
                    <sub><b>Naipha Loham</b></sub>
                </a> 
            </td>
        </tr>
    </tbody>
</table>

