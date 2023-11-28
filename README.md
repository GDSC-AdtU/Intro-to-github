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
    </tbody>
</table>
