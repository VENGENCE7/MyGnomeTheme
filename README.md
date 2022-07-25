<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<div align=center><img src="https://user-images.githubusercontent.com/86911386/180775272-fbc231f8-5f5d-437a-8ea8-50de7d0841e5.png" height=200 width=200 ></div>


# MyGnomeTheme
Started with top panel only but will eventually create it for whole system.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#theme-image">Theme Image</a></li>
    <li><a href="#getting-started">Getting Started</a></li>        
        <ul>
            <li><a href="#install-gnome-tweaks">Install GNOME Tweaks</a></li>
            <li><a href="#enable-user-themes-extension">Enable User Themes Extension</a></li>
        </ul>
    <li><a href="#installation">Installation</a></li>
        <ul>
          <li><a href="#1-clone-the-repo">Clone The Repo</a></li>
          <li><a href="#2-download-and-extract">Download & Extract</a></li>
        </ul>
    <li><a href="#applying-the-theme">Applying the Theme</a></li>
  </ol>
</details>

<br/>

<!-- Theme Image -->
## Theme Image

![gnomeTheme](https://user-images.githubusercontent.com/86911386/180756164-776ee38b-3615-44fd-b29e-acd08f529339.png)


<!-- Getting Started -->
 ## Getting Started
 
Before you can change your GNOME theme, you have to install Tweaks and enable the user themes extension.

<!-- Install Gnome Tweaks -->
### Install GNOME Tweaks

+ You can find Tweaks in the GNOME Software Center, where you can install it quickly with just the click of a button.
 
+ If you prefer the command line, use your package manager. For instance, on Fedora or CentOS:

```
$ sudo dnf install gnome-tweaks 
```

On Debian or similar:

```
$ sudo apt install gnome-tweaks
```

<!-- Enable User Themes Extension -->
### Enable User Themes Extension

To enable the user themes extension:
- Add User Themes extension from <a href="https://extensions.gnome.org/extension/19/user-themes/">here</a> 
- Launch Tweaks and select Extensions. 
- Find **User themes** and click the slider to enable it.

<p align="right">(<a href="#top">Back to top</a>)</p>


<!-- Installations -->
## Installation
Can do either of the following


<!-- Clone the Repo -->
### 1: Clone the repo
+ Via https 
   ```sh
   git clone  https://github.com/VENGENCE7/MyGnomeTheme.git
   ```
+ Via Github CLI
   ```sh
    gh repo clone VENGENCE7/MyGnomeTheme
   ```
   
<!-- Via Terminal -->  
 ### In Terminal
When you download the theme, it comes compressed into a .tar.gz file. What you have to do is:

1. Run the terminal `Ctrl+Alt+T` or whatever is your shortcut.
2. Enter `cd ~ && mkdir .themes`
    This command will create a .themes folder in your personal folder. The dot is necessary
3. Enter `cp files_path ~/.themes`
    Replace files_path with the directory where are your zipped files. This command copy the compressed files into this folder.
4. Enter `cd ~/.themes && tar xvzf PACKAGENAME.tar.gz`
    Replace PACKAGENAME with the name of the file. This command will unzip the theme file into the new folder.
5. Enter **gnome-tweak-tool**

 <p align="right">(<a href="#top">Back to top</a>)</p>


<!-- Download and Extract -->
### 2: Download and Extract
 + Download the theme from <a href="https://github.com/VENGENCE7/MyGnomeTheme/releases/tag/MyGnomeTopPanel"> releases </a>.
 
<!-- Via File Explorer -->
### In File Explorer
 1. Create a &ensp; `.themes` &ensp; __folder__ in your personal directory.(**the '.' is important**)
 2. Add the extracted _MyGnomeTheme_ folder in it. 

 <p align="right">(<a href="#top">Back to top</a>)</p>
 
<!-- Apply Theme --> 
## Applying the Theme

To apply your new theme, go to the **_Appearance_** section in **_Tweaks_**.Here, you can select different options for each aspect of your desktop.

+ Go to **Shell** and choose `MyGnomeTheme`

 <p align="right">(<a href="#top">Back to top</a>)</p>
 
 
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/VENGENCE7/MyGnomeTheme.svg?style=for-the-badge
[contributors-url]: https://github.com/VENGENCE7/MyGnomeTheme/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/VENGENCE7/MyGnomeTheme.svg?style=for-the-badge
[forks-url]: https://github.com/VENGENCE7/MyGnomeTheme/network/members

[stars-shield]: https://img.shields.io/github/stars/VENGENCE7/MyGnomeTheme.svg?style=for-the-badge
[stars-url]: https://github.com/VENGENCE7/MyGnomeTheme/stargazers

[issues-shield]: https://img.shields.io/github/issues/VENGENCE7/MyGnomeTheme.svg?style=for-the-badge
[issues-url]: https://github.com/VENGENCE7/MyGnomeTheme/issues

[license-shield]: https://img.shields.io/github/license/VENGENCE7/MyGnomeTheme.svg?style=for-the-badge
[license-url]: https://github.com/VENGENCE7/MyGnomeTheme/blob/main/LICENSE


[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/bhavish-anand-2113a6206
