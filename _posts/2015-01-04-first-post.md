---
layout: post
title: Google Tag Manager: An introduction
image: /img/hello\_world.jpeg
---

# Google Tagmanager

You know the drill: your or one of the other team members wants to change a small snippet of text, change the colour of a button or insert an image somewhere. Or a bit more complex: you want to insert a script from that neat tool you have just discovered. It seems so small, but IT says they should put it on their dev roadmap for the next half year. Too bad for you. You’re stuck and you’re not able to implement that great growth hack.

Now imagine for a moment that you could do this all by yourself as easy as copying and pasting the code onto your website without ever having to dig deep into the realms of your entire website’s code.

![][image-1]

## So what did you say?
The answer is Google Tagmanager. It’s is a free Tagmanagement solution from Google (no pun intended) that allows you to implement code fast on those parts of your website that you want. This can be as simple as implementing Google analytics to entire javascript. And all this through a much simpler interface than you would when actually hard coding stuff on your website.

So what is it?
1. A simple yet sophisticated code implementor.
2. A/B tester
3. Staging environment
4. Cookie and web data manager

Already interested?
![][image-2]

## Setting up Google Tagmanager
Getting started:
1. Create an account or login at tagmanager.google.com
2. Create a new container. This will be the part of your account covering your domain. 
3. You will receive a code snippet from the grandmasters at Google that should be implement on your site. If you’re using Wordpress, download and install [this plugin][1] and insert your account ID. Otherwise, add the custom HTML to your site’s header and body. This will be the last time you will ever have to take a look at your code. Unless you go to the dark side and start to like coding. But you’re the chosen one, so please don’t. 
4. Take an Ethiopian soy-latte coffee with an extra shot of maple syrup. You’re a Google Tagmanager Padawan now.

## How does it work?
Google Tagmanager consists of a few building blocks:

### Tags
These are the actual pieces of code that do stuff. This could be installing Google Analytics or inserting an email popup. 

### Triggers
That which make the tags fire (do its job, ie running a script). A trigger can be set to always fire or only in specific conditions such as “if url consists of …”.  In this way you can choose on which page a tag is active.

### Variables
Dynamic pieces of tags or triggers. These are partly pre-defined, such as the page url, but you can always add variables in order to store and combine multiple  tags and triggers. 

### The data layer
Data stored in your browser. This is where Sith Master Mark Zuckerberg hides his cookies, enabling him.. Well, don’t think about that. 

> Checking your code.
> In order to check whether you have installed Google Tag Manager in the right way, install [this Chrome Extension][2]. Now go to your website, click on the extension and hit enable. Once you refresh your site, you will see if GTM has been installed correctly. 



## Inserting your very first code snippet** Now that you’ve installed Google Tag Manager on your site, you can use it to insert your first code snippet. I will use Google Analytics as you’ll probably need this one anyway and Google has simplified this as much as possible for you.

**Go to tagmanager.google.com and click on “Add a new tag”**
![][image-3]

**Click on “Tag configuration”**
![][image-4]

**Choose “Universal Analytics”**
![][image-5]

**Click on “Triggering” and choose “All Pages”**
![][image-6]

**Hit “Save”**

** ##Next steps
You are now ready to begin your epic journey!

[1]:	https://wordpress.org/plugins/google-tag-manager/
[2]:	https://chrome.google.com/webstore/detail/tag-assistant-by-google/kejbdjndbnbjgmefkgdddjlbokphdefk

[image-1]:	https://media2.giphy.com/media/12NUbkX6p4xOO4/giphy.gif?cid=e1bb72ff5b50eb7f506741456fa304fa
[image-2]:	https://media3.giphy.com/media/MP1kygLQzjCve/giphy.gif?cid=e1bb72ff5b50edd26e65447963d3cab5
[image-3]:	/img/skitch4.png
[image-4]:	/img/skitch3.png
[image-5]:	/img/skitch2.png
[image-6]:	/img/skitch1.png