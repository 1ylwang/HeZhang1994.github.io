# Personal Website Development using GitHub.io

This is the **HTML** implementation of developing my personal website. 

The source template (see [SourceTemplate_privy](https://github.com/HeZhang1994/HeZhang1994.github.io/tree/master/SourceTemplate_privy)) is forked from [TEMPLATED](http://templated.co).

# Files/Folders Description

* default.css - Define the structure, formats, and properties of webpage.

* index.html - Source code of home page of my website.

* hz***.html - Source code of subpages of my website.

* google***.html - Verfication file of Google search engine.

* baidu***.html - Verfication file of Baidu serach engine.

* /images - Pictures of designing my website.

# Configuration and Estabilishment

The following procedures are reposted from [https://pages.github.com/](https://pages.github.com/).

1. Configure GitHub client on your local computer by running commands on Terminal:
```bash
$ git config --global user.email "xxx@xxx.xxx"
# xxx@xxx.xxx is your register email on GitHub.
$ git config --global user.name "aaa"
# aaa is your user name on GitHub
```

2. Create __aaa.github.io__ (public) repository on GitHub, where __aaa__ is your user name！ You can use templates provided by GitHub now (see [here](https://blog.csdn.net/renfufei/article/details/37725057)). Or continue the following steps and use other templates.

3. Clone __aaa.github.io__ repository to your local computer by running command on Terminal:
```bash
$ git clone https://github.com/aaa/aaa.github.io
```

4. Add contents to your website by running commands on Terminal, which will create a root page (__index.html__):
```bash
$ cd aaa.github.io
$ echo "Hello World" > index.html
$ git add --all
$ git commit -m "Initial commit"
$ git push -u origin master
```

5. After a few minutes, open __https://aaa.github.io/__ on browser. You will see "Hello World" on your website.

6. Start adding a template (.css) to repository and editing __index.html__ or other files (.html) to develop your website!

# Verification of Website

Verify your website on different search engines allow your website to be noticed by other Internet users.

### Verify website on Google

1. Open [Google Search Console](https://search.google.com/search-console/about) and login with your Google account.

2. Click top-left dropdown arrow and "Add property".

3. Type __https://aaa.github.io__ in the pop-up window and click "CONTINUE".

4. Download the file named as "google***.html" and upload to your GitHub repository.

5. Go back to the verification page. Wait a few minutes and click "VERIFY".

6. Verification on Google is completed!

### Verify website on Baidu

1. Open [Baidu Resource Platform](https://ziyuan.baidu.com/) and login with your Baidu account.

tbc...
