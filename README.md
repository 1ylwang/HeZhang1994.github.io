# Personal Website Development

This is the HTML5 implementation of developing my personal website. 

The source template (see SourceTemplate_privy) is forked from [TEMPLATED](http://templated.co).

# Description

* default.css - Define the structure, formats, and properties of webpage.

* index.html - Source code of home page of my website.

* hz***.html - Source code of subpages of my website.

* google***.html - Verfication file of Google search console.

* baidu***.html - Verfication file of Baidu serach console.

* /images - Source pictures of designing my website.

# Configuration

The following procedures are reposted from [https://pages.github.com/](https://pages.github.com/).

1. Run the following commands on your local computer to configure GitHub client:
```bash
$ git config --global user.email "xxx@xxx.xxx"
# xxx@xxx.xxx is your register email on GitHub.
$ git config --global user.name "aaa"
# aaa is your user name on GitHub
```

2. Create __aaa.github.io__ (public) repository on GitHub, where __aaa__ is your user name. You can use templates provided by GitHub (see [here](https://blog.csdn.net/renfufei/article/details/37725057)). Or continue the following procedures and try other templates.

3. Clone __aaa.github.io__ repository to your local computer by run the following command on Terminal:
```bash
$ git clone https://github.com/aaa/aaa.github.io
```

4. Add content to your website by run the following commands on Terminal:
```bash
$ cd aaa.github.io
$ echo "Hello World" > index.html
$ git add --all
$ git commit -m "Initial commit"
$ git push -u origin master
```

5. After a few minutes, open __https://aaa.github.io/__ on browser, you will see "Hello World" on your website.

6. Now add a template (.css) and start to edit __index.html__ and other files (.html) to design your website!
