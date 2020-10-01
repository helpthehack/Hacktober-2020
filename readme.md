[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/godslayer201/Hacktober-2020)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


# First Contribution

- Thinking about doing an open source contribution?
- Don't know where to start or how to do?
- Looking for a simple repository to help you to get started?

Then look no further, we have created this repository to help you to get started.

## Just for the instruction!

<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

If you don't have git installed in your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "URL you just copied"
```

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository in GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd Contributors
```

Now create a branch using the `git checkout` command:

```
git checkout -b <first-timers-only>
```

For example:

```
git checkout -b add-muhammad
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Contributors list"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

Now if you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Soon, I'll be merging all your pull requests into the master branch of this project. You will get a notification email once the changes have been merged.

##Another method

Step #1: Register for Hacktoberfest

You need a GitHub account. If you don’t have one yet, you can create one for free in just a few minutes.

Then go to the Hacktoberfest registration page and follow the instructions. It only takes a moment.
Step #2: Learn how to make a pull request

Pull requests are a way of contributing your code changes to an open source project. They use a tool called Git, which runs on a social coding platform called GitHub.

GitHub is the center of the open source universe, and is home to projects like Linux and React.js.

It can take months for developers to get good enough to contribute to some of these projects. But the freeCodeCamp community has made it easy for absolute beginners to contribute to our open source project.

You can contribute to freeCodeCamp right in your browser on GitHub. You don’t need to install anything on your computer. You don’t even need to know a programming language. You just need to choose an article you want to help improve.

Here’s a short gif showing how you can do this:
A Gif showing how to make an open source contribution to an article, right in your browser.

The steps are:

    Explore the freeCodeCamp repository and choose an article you want to help improve.
    Open that folder’s index.md file by double-clicking it.
    Click the pen symbol in the upper right-hand corner to edit it.
    Make your changes to it. You can check out this basic Markdown cheat-sheet if you want to see how to add images or videos. You don’t even need to know HTML.
    Scroll down and describe your changes in the commit message.
    Make sure the “Create a new branch for this commit and start a pull request” radio button is selected.
    Click “Commit Changes.”
    On the next page, click “Create Pull Request.”
    Read the checklist to make sure you’ve done everything, and check the checkboxes, then submit.

We will run some automatic tests to make sure your changes didn’t break anything. Then one of our maintainers will give you feedback on your article. Once everything looks good, we’ll merge your pull request.

We will eventually deploy your contribution to freeCodeCamp.org, where millions of people can read and reference it.

Contributing to freeCodeCamp is a good way to ease into contributing to open source. You can also join our contributor chat room to hang out with other contributors and ask questions.

Also, we recently translated the entire freeCodeCamp curriculum into several major world languages.
A freeCodeCamp coding challenge in Spanish

If you speak any of these languages, you can help improve our translations. This is another way to open GitHub pull requests and earn a Hacktoberfest shirt.

In addition to English, we have translated freeCodeCamp’s full curriculum into:

    Arabic
    Chinese
    Portuguese
    Russian
    Spanish

We’ve also translated more than 4,000 guide articles on various programming topics:

    Arabic
    Chinese
    Portuguese
    Russian
    Spanish

Soon these languages will be live on freeCodeCamp.org, and each will have its own forum, too.

Every month, millions of people use the English language version of freeCodeCamp. We anticipate millions of people using these other language versions, too. So any improvements you can make to these translations will help a lot of people.
Step #3: OK — now make 4 more pull requests

You can make four more pull requests to freeCodeCamp, or whatever open source project you want. Here’s a more detailed guide to contributing to open source, if you’re feeling adventurous.
Step #4: Check and see whether you’ve qualified

Once you’ve signed up for Hacktoberfest, you can check your progress on the Hacktoberfest website.
I’ve earned my Hacktoberfest shirt.
Step #5: Wait for your Hacktoberfest 2018 shirt to arrive in the mail

In past years, shirts have arrived in November or December, depending on how far you live from San Francisco.

The Digital Ocean team should eventually contact you asking for your shirt size and shipping address. (Keep in mind they are shipping 10,000+ shirts so this process will take a while.) And yes, they will ship internationally for free.

## Contributors

Thank you to all the contributors who help in making this project better !

