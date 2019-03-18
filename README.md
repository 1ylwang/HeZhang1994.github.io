# Personal Website Development

[![image](https://img.shields.io/badge/license-MIT-lightgrey.svg)]()
[![image](https://img.shields.io/badge/lagrange-html%20%7C%20css-blue.svg)]()
[![image](https://img.shields.io/badge/status-stable-brightgreen.svg)]()
[![image](https://img.shields.io/badge/build-passing-brightgreen.svg)]()

This is an **HTML-CSS** implementation of developing personal website with **GitHub.io**.

Many thanks to the [TEMPLATED](http://templated.co) for providing the source template in `SourceTemplate_privy/`.

## Description of Folders/Files.

- `audio/` - The folder that contains the audio used in website.

- `images/` - The folder that contains the pictures used in website.

- `default.css` - The CSS file that defines the characteristics of website.

- `index.html` - The HTML source file of home page.

- `hz***.html` - The HTML source file of child web pages.

- `baidu***.html` - The verification file of Baidu search engine.

- `google***.html` - The verification file of Google search engine.

## Configuration and Establishment

The following procedures for developing website are partly recapitulated from [GitHub Guide](https://pages.github.com/). For more information of `git`, see the detailed online [tutorial](https://chryswoods.com/beginning_git/) provided by Christopher Woods.

1. Configure GitHub client on your local computer.
```bash
$ git config --global user.email "xxx@xxx.xxx"
# Replace xxx@xxx.xxx with your GitHub registered email.
# E.g., $ git config --global user.email "hz@gmail.com".

$ git config --global user.name "aaa"
# Replace aaa with your GitHub user name.
# E.g., $ git config --global user.name "hz".
```

2. Create __aaa.github.io__ (public) repository on GitHub, where __aaa__ is your GitHub user name. You can use web page templates provided by GitHub now (see [here](https://blog.csdn.net/renfufei/article/details/37725057)), or continue the configuration and use other templates later.

3. Clone __aaa.github.io__ repository to your local computer.
```bash
$ git clone https://github.com/aaa/aaa.github.io
```

4. Add contents to the website (this will create the home page `index.html`).
```bash
$ cd aaa.github.io
~$ echo "Hello World" > index.html
~$ git add --all
~$ git commit -m "Initial commit"
~$ git push -u origin master
```

5. After a few minutes, open __https://aaa.github.io/__ on browser and you will see "Hello World" on the website.

6. Develop website by editing/creating `default.css`, `index.html`, and other HTML files.

## Verification of Website

Verifying your website on different search engines allows it to be retrieved by users through the Internet. Last updated: 01 Feb 2019.

### Google Search Engine

1. Open [Google Search Console](https://search.google.com/search-console/about) and log in with Google account.

2. Click top-left drop-down arrow and click "+ Add property".

3. Type __https://aaa.github.io__ in the input box of pop-up window and click "CONTINUE".

4. Download the verfication file `google***.html` and upload it to your GitHub.io repository.

5. Go back to the verification page. Wait a few minutes and click "VERIFY".

6. Complete verification on Google search engine!

### Baidu Search Engine

1. Open [Baidu Resource Platform](https://ziyuan.baidu.com/) and log in with Baidu account.

2. Click "Add Website" and complete user information (if required).

3. Type __https://aaa.github.io__ in the input box and click "NEXT".

4. Select website attribute (e.g., Information Technology).

5. Select verification method - document verification.

6. Download the verification file `baidu_verify***.html` and upload it to your GitHub.io repository.

7. Go back to the verification page. Wait a few minutes and click "COMPLETE VERIFICATION".

8. Complete verification on Baidu search engine!

## Useful Links

* Online HTML and CSS editor - [CodePen](https://codepen.io/)

* Online picture resizer - [Picresize](http://www.picresize.com/)

* Online picture format converter - [Online-Converter](https://www.online-convert.com/)

<br>

<i>Please star this repository if you found its content useful. Thank you very much. ^_^</i>

<i>如果该程序对您有帮助，请为该程序加星支持哈，非常感谢。^_^</i>

<i>Last updated: 18/03/2019</i>

