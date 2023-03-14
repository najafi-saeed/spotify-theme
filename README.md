![Spotify Light Theme](https://i.imgur.com/oD05z1b.png "Spotify Light Theme")

# Spotify Light Theme
Although most of the **Spotify** users in the idea center have asked to **add a light theme to Spotify**, but so far the color of this app is still **dark**.
With the description of this repository, you can **add a light theme** or any type of theme to the web version of this famous application. You can even **create your own custom spotify theme** by changing a few color variables. Let's do it.

**Table of Contents**

- [Features](#features)

- [How to use?](#how-to-use)

- [How to customize?](#how-to-customize)

- [Screenshots](#screenshots)

## Features

- Several themes for Spotify including light themes
- Just with pure CSS and without changing the structure of Spotify
- Easy customization with support for CSS variables
- The ability to create your own custom theme just by changing a few color variables.

## How to use?

1) First, you need to install a browser extension in order to inject CSS to the site you visit. you can use `User JavaScript and CSS` extension for Google Chrome. [Download and install here](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en "Download and install here").

| Browser        | Extension   |
| ------------ | ------------ |
|  [![Google Chrome](https://www.google.com/chrome/static/images/chrome-logo-m100.svg "Google Chrome")](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en "Google Chrome") | [![User JavaScript and CSS](https://lh3.googleusercontent.com/1TSw8ZPwr2VvUZlY1cbAPOWo5cisrfpazmTpfGH4YWGTLCJLUq23LMSKuS5ee-bBP5C0GL8wsbpV9iQ9zLEQ6Dv8Vw=w128-h128-e365-rj-sc0x00ffffff "User JavaScript and CSS")](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en "User JavaScript and CSS")  |

2) Then open the [Spotify website](https://open.spotify.com/ "Spotify website") and click on the extension and click `Add New` button.

![](https://i.ibb.co/hMm6YxJ/image.png)

3) Now, in the CSS section, you should copy or import the theme css code.

![](https://i.ibb.co/M2XcZrj/image.png)

4) Go to the [theme folder](https://github.com/najafi-saeed/spotify-theme/tree/development/themes "folder") and choose your theme `themes/CHOOSE_THEME` and copy its css codes here and click on yellow save button. 

If you want to get repository updates automatically, you can use `Jsdelivr CDN` to load theme CSS file with this structure:

<pre>@import "https://cdn.jsdelivr.net/gh/najafi-saeed/spotify-theme/themes/<b>theme-folder</b>/<b>theme-file</b>.css";</pre>

for example you can copy:
```
@import "https://cdn.jsdelivr.net/gh/najafi-saeed/spotify-theme/themes/light-theme/light-theme.css";
```

5) Refresh Spotify site and enjoy your new theme.

## How to customize?
You can easily customize a theme by overwriting some CSS variables.

![](https://i.ibb.co/c3fV8Bj/image.png)

All CSS variables are listed here. You just need to copy them at the end of your file. Of course, if you master CSS, you can make more specialized changes.

```
:root {
    --background-color: #fff;
    --text-color: #333;
    --text-color-muted: #999;
    --border-color: #e5e5e5;
	
    --primary-color: #18a2ff;
    --primary-color-hover: #115bbb;
    --muted-color: #ebfaff;
    --muted-color-hover: #c9f4fe;
	
    --topbar-background: rgba(255, 255, 255, 0.7);
    --topbar-blur: 10px;
    --home-hero-background: linear-gradient(rgba(255, 255, 255, .7) 0, var(--muted-color-hover) 80%);
    --leftbar-background: var(--muted-color);
    --playingbar-background: rgba(24,162,255, 0.85);
    --playingbar-blur: 5px;
	
    --primary-button-background: var(--primary-color);
    --primary-button-background-hover: var(--primary-color-hover);
    --primary-button-text: #fff;
    --primary-button-text-hover: #fff;
    --primary-button-border: 0px solid var(--primary-button-background);
    --primary-button-border-hover: 0px solid var(--primary-button-background-hover);
	
    --secondary-button-background: rgba(0, 0, 0, 0.35);
    --secondary-button-background-hover: rgba(0, 0, 0, 0.7);
    --secondary-button-text: #fff;
    --secondary-button-text-hover: #fff;
    --secondary-button-border: 0px solid var(--secondary-button-background);
    --secondary-button-border-hover: 0px solid var(--secondary-button-background);
	
    --scrollbar-track-color: #eee;
    --scrollbar-handle-color: #c7c7c7;
    --scrollbar-handle-active-color: #999;
}
```
| Basic Light Theme  |  ![](https://i.imgur.com/oD05z1b.png)  |
| :------------: | :------------: |
| **Customized Theme** | ![](https://i.imgur.com/XhM6ezX.png)  |

## Screenshots

Here you can see some screenshots of the application pages. Really nice! The Blur effect has made the pages much more beautiful.

| <br> ![](https://i.imgur.com/3ZVMZk1.png) Artist Page  | <br> ![](https://i.imgur.com/yd7dT1a.png) Artist Page  |
| :------------: | :------------: |
| <br> ![](https://i.imgur.com/rDAROdJ.png) Playlist Page  | <br>  ![](https://i.imgur.com/081S3TN.png) Playlist Page |
|  <br> ![](https://i.imgur.com/i0qgXgE.png) Playlist Page | <br> ![](https://i.imgur.com/ZlJremU.png) Search Page/ Albums |
| <br> ![](https://i.imgur.com/7QI84bD.png) Lyric Page | <br> ![](https://i.imgur.com/qDOvkqD.png) Discography Section |
| <br> ![](https://i.imgur.com/6qlBOf6.png) Search Page / Recent searches |  <br> ![](https://i.imgur.com/iATbZSe.png) Album Page |
