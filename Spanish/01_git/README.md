# Basic Concepts

## Exercise 1

In this exercise we will learn the concepts
of fork, clone. We will also learn about a technology for creating slides that can be stored in github and viewed in any internet browser.

Open a ubuntu terminal and execute the following commands:
```
sudo apt update
sudo apt install git
```

Go to the url https://github.com and create a Github account.

Log in your account.

Go to the url https://github.com/hakimel/reveal.js and Fork the repository into your personal account

![][1]
**Figure 1.** Fork

Go to your forked repository and copy the https clone url. The ssh url allows you to perform actions in your repository without having to enter the password each time, we will explain later how to create an use a ssh key.

![][2]
**Figure 2.** Clone URL

Create a new folder called Repositories in your Documents folder

Do a git clone of the forked url
```
git clone https://github.com/d4n13lbc/reveal.js.git
```

![][3]
**Figure 3.** Git clone command output

Get into the reveal.js folder and open the index.html file in your favorite browser

```
cd reveal.js
firefox index.html
```

The forked repository already has a gh-pages branch, which allows you to expose the reposity content as a website
```
firefox https://d4n13lbc.github.io/reveal.js/#/1
```

![][4]
**Figure 4.** Example website

##  Activities
Check the reveal.js repository and do a presentation about another github open source project

[1]: images/0_fork.png
[2]: images/1_clone_url.png
[3]: images/2_git_clone.png
[4]: images/3_example_website.png

<!--
## Delete a Github repository
-->