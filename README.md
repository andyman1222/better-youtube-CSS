# better-youtube-CSS
Google's latest changes to Youtube have made an absolutely awful UI experience, especially on average display PCs. Every change they make seems to make everything unnecessarily bigger and more bloated.

Luckily, this is all CSS changes, and there are tools in web browsers to override the CSS of any webpage. 

## Why?

**Why does Google change their website CSS every 6 months?** I have no clue.

**Why make this repo?** Because I am sick and tired of Google changing their UI every 6 months (figuratively, but it is obsessive). It serves no practical purpose and retracts from the user experience of their platform. Youtube isn't the only platform suspectible to this- for instance, the google docs suite bypasses some of the CSS changes I've made across all sites, so I'm stuck with rounded corners on the site.

**Why these changes?** Because Google's CSS adds a ton of wasted space, whether in the form of the rounded corners, or whitespace, or larger fonts. I have large monitors with my desktop, not a little phone screen, so I want the screen real estate to be utilized more than what Google (and most modern websites) tend to waste.

**Why is Google's CSS so bad?** In general, their websites' HTML is bad- heavily bloated. Just right click -> inspect element, and scroll around at how much HTML code makes up the site. But more importantly, take a look at an element's styling (which can be done easily in Firefox, looking at the right menu next to the site code)- tons of variables, manual positioning and manual sizing, which suggest that they could provide settings to configure all of this, but they don't. A lot of these CSS properties I found can be improved and in fact look better with simpler CSS properties such as flexbox.

## Is this for me?

Not every visual style is for everyone. I believe it should be a necessity for user experience and accessibility, to provide the means to customize any interface to the user's preferences. You are welcome to take these changes and use them as-is, or modify them to your liking, or even branch this code and share your own CSS changes.

## Repository layout

before/after folders show screenshots of before and after applying the changes, including the main page, a video being played, and the comments section. Don't judge me by my video recommendations pls...

Root of the repo contains all the .css files needed to change the look:

* **universal.css**: this is my own personal preference, of removing rounded corners across all websites. You can apply the css to youtube specifically, or to all websites like I do, or ignore it, it's your choice

* **dark theme.css**: contains color changes to make a true black (often called OLED) theme across the platform

* **better player.css**: contains the adjustments made to the video player

## Goals of these changes

* Create a true black theme, which doesn't hide or make difficult to see, any existing functionality on the platform

* Fix the player to reduce the overall size of the controls of a video, and in general better utilize the space available, while making the controls still easy to use, regardless of the screen resolution or size

* Replace manual positioning, manual scaling, and other bloated CSS properties with properties based on more automatic values, such as automatically anchoring the controls to the bottom of the parent element

* Using Youtube Redux, fix the homescreen, comments, and other elements of the website as a whole, to remove bloated advertisement services such as Shorts and minigames, so that my experience can emphasize recommending videos, utilizing the space available on my display to best show recommendations

## How to apply the layout

**Prerequisite (recommended)**: I use the extension known as *Youtube Redux*, by omniZero. This plugin does a lot to improve the layout, in particular of the main page, and re-adding the dislike counter, but it has its own limitations and didn't provide all the settings I wanted. I highly recommend setting up this plugin first, as the screenshots use this plugin.

**Applying the CSS**: use the *Stylebot* extension, or a similar extension which may let you apply CSS to any webpage. Whatever extension you choose, simply add a rule for *\*.youtube.com*, copy and paste any of the CSS styling, and click save. With Stylebot, changes apply as soon as I clicked save.

## Issues and contributions

There are notable issues with the CSS- check the issues tab for info, or report your own issues there. Please report issues only if there is a visually incorrect problem, such as cut off text or missing icons.

Please feel free to submit pull requests, as I cannot guarantee I'll keep updating this. If it's functional, I'm more likely going to keep things as-is even if something isn't visually correct. I have my own work to worry about so fixing Youtube isn't a fulltime job for myself.

You are welcome to fork this repository to make your own changes, and submit a pull request, if you think your own changes contribute to the overall goals specified here. If your changes do not align with my preferences I will reject it, but you can still share your own changes as you choose. Please note the Apache 2.0 license applied to this repo.

## Support

Looking to thank me with a donation? I have a game dev company, Quantonium looking to build a community of players for our game, The Laser Games. You can help by checking out [shop.quantonium.net](shop.quantonium.net) for a monthly membership and other items to purchase, which can help myself and the game's development.

Looking to discuss CSS, youtube, The Laser Games, or this repository? Join the [QuantoniumDiscord](discord.quantonium.net)!

Note: this repository is owned by myself, Andy Herbert, and not the company; I am not creating this repository for-profit, or as a component of my company. Discussion about this on the discord server is encouraged for general discussion, however the server promoted is a function of the company and is subject to the policies of the company towards the server. This repository represents the views and opinion of Andy Herbert, not of Quantonium LLC.

lease change this section if you wish to share your own fork of this repo, unless you really want to support my company.
