# Develp Personal Website

This is the **HTML** implementation of developing personal academic website with GitHub.io.

The source template (see [SourceTemplate_privy](https://github.com/HeZhang1994/HeZhang1994.github.io/tree/master/SourceTemplate_privy)) is forked from [TEMPLATED](http://templated.co).

# Files/Folders Description

* default.css - Define the structure, formats, and properties of webpage.

* index.html - Source code of home page on my website.

* hz***.html - Source code of subpages on my website.

* google***.html - Verfication file of Google search engine.

* baidu***.html - Verfication file of Baidu serach engine.

* /images - Pictures of designing my website.

# Configuration and Estabilishment

The following procedures are partly reposted from [https://pages.github.com/](https://pages.github.com/).

1. Configure GitHub client on local computer by executing commands on Terminal:
```bash
$ git config --global user.email "xxx@xxx.xxx"
# xxx@xxx.xxx is your registered email on GitHub.
$ git config --global user.name "aaa"
# aaa is your user name on GitHub
```

2. Create __aaa.github.io__ (public) repository on GitHub, where __aaa__ is also your user name！You can use webpage templates provided by GitHub now (see [here](https://blog.csdn.net/renfufei/article/details/37725057)), or continue the following steps and use other templates later.

3. Clone __aaa.github.io__ repository to your local computer by executing command on Terminal:
```bash
$ git clone https://github.com/aaa/aaa.github.io
```

4. Add contents to your website by executing commands on Terminal (this will create the root page __index.html__):
```bash
$ cd aaa.github.io
~$ echo "Hello World" > index.html
~$ git add --all
~$ git commit -m "Initial commit"
~$ git push -u origin master
```

5. After a few minutes, open __https://aaa.github.io/__ on browser and see "Hello World" on your website.

6. Develop website by editing templates (.css), index.html, and other files (.html) on GitHub.io repository.

# Verification of Website

Verifying your website on different search engines allows website to be noticed by users through Internet.

### Verify website on Google

1. Open [Google Search Console](https://search.google.com/search-console/about) and login with Google account.

2. Click top-left dropdown arrow and click "+ Add property".

3. Type __https://aaa.github.io__ in the input box of pop-up window and click "CONTINUE".

4. Download the file called "google***.html" and upload it to your GitHub.io repository.

5. Go back to the verification page. Wait a few minutes and click "VERIFY".

6. Complete verification on Google search engine!

### Verify website on Baidu

1. Open [Baidu Resource Platform](https://ziyuan.baidu.com/) and login with Baidu account.

2. Click "Add Website" and complete user information (if required).

3. Type __https://aaa.github.io__ in the input box and click "NEXT".

4. Select website attribute (e.g., information technology).

5. Select verification method - document verifiction.

6. Download the file named as "baidu_verify***.html" and upload to your GitHub.io repository.

7. Go back to the verification page. Wait a few minutes and click "COMPLETE VERIFICATION".

8. Complete verifiction on Baidu search engine!

# Useful Links

* Online HTML and CSS editor - [CodePen](https://codepen.io/)

* Online picture resizer - [Picresize](http://www.picresize.com/)
