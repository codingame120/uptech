---
title: "What Is Termux How to Install It And First Steps After Installation" # Title of the blog post.
date: 2020-12-22T22:35:45+01:00 # Date of post creation.
description: "All about termux,how to install termux,what to do after installing termux." # Description used for search engine.
featured: true # Sets if post is a featured post, making it appear on the sidebar. A featured post won't be listed on the sidebar if it's the current page
draft: false # Sets whether to render this page. Draft of true will not be rendered.
toc: true # Controls if a table of contents should be generated for first-level links automatically.
# menu: main
featureImage: "/images/termux/termux.jpg" # Sets featured image on blog post.
thumbnail: "/images/termux/termux1.jpg" # Sets thumbnail image appearing inside card on homepage.
shareImage: "/images/termux/termux1.jpg" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories:
  - Technology
  - How To
tags:
  - Termux
  - Android
series:
  - Termux
---

<br/>
<br/>

## Introduction To Termux

TERMUX is a terminal emulator for Android system.
It means that you can access to the system on your phone through a terminal like on Linux, Windows or macOS.
Since Android is built on Linux, Termux use Unix-like commands.

Unfortunately app is not available for iphone.

Those who use Linux and macOS will be familiar with commands.  
For those who use Windows will be little unfamiliar since CMD ( Command Prompt ) use different commands.  
But it's a great way to start Learn Unix-like commands and CLI  
( Command Line Interface ).  
Which is important if you want to do hacking and/or cybersecurity.

But Termux is not only hacking tool.

It can be useful for programmers since it can run python scripts and other programming language on your phone.  
So it can be useful and for those who want to learn programming.

You can do different things in TERMUX like send SMS send emails surfing Web or play music and audio files which you can read in our post: [How to play music in Termux.](https://www.uptech.cf/post/how-to-play-music-in-termux/)

There is no need to root access on your phone to use Termux.  
But if your phone have android older than 7.0 you will have to use Termux Legacy which don't have all functionality as Termux for newer version of Android.

## Installation

You can download Termux app on [Google play](https://play.google.com/store/apps/details?id=com.termux) or [F-Droid](https://f-droid.org/en/packages/com.termux/) store.

[<img src="/images/termux/play.png">](https://play.google.com/store/apps/details?id=com.termux)
[<img src="/images/termux/fdroid.png">](https://f-droid.org/en/packages/com.termux/)

<br/>

## What To Do After Installing Termux

So now when we have installed Termux on our phone. We need to do a couple of things.

- Update and upgrade repositories
- Install git
- Give Termux storage permission

### Update and upgrade repositories

Which can be done using commands:

```
pkg update && pkg upgrade
```

 <br/>
 
### Install git

Which can be done using `package manager` and `install command`:

```
pkg install git
```

<br/>

### Give Termux storage permission

Which can be done in two ways.

1.  First is to go to `settings>>apps>>termux>>permissions` and enable Termux to access storage.

    <p align="center">

    <img src="/images/termux/tstorage1.jpg">

      </p>

2.  And second trough Termux command line. Which will work for **Android 6** and higher.

    Type command:

    ```
    termux-setup-storage
    ```

    You can check if Termux now have permission if `$HOME/STORAGE` folder is created.
    And if you have external storage (SD card) should check if app-private folder is created.
    Content of `$HOME/STORAGE` are symlinks to different storage folders.
    (e.g `~storage/music`)
    Standard folder for audio files.

<br/>

Now when you have set up Termux on your phone. You can start to explore play learn various different things with this interesting useful and very powerful app.

If you have any questions about Termux or suggestions, fell free to tell us in comments.

<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>
