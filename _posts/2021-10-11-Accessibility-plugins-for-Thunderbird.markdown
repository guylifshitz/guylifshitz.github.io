---
layout: post
title:  " Thunderbird Accessibility"
date:   2021-10-11 22:34:29 +0300
categories: 
    - projects
    - hackathon
---
Built in a team during a Hackathon in Paris (La Nuit du Code Citoyen, October 2021), working with the accessibility non-profit [A.C.I.A.H.](https://aciah.xyz/){:target="_blank"}. We created a new accessibility plugin for Thunderbird, and updated an existing plugin to work with the newest version of Thunderbird. Worked on this with Max. 





### TabControl:
This Thunderbird extension aims at reducing the number of coexisting tabs during a session.

We keep track of currently opened mail tabs, in order to keep their number below a set value, 3 by default. This value can be changed in the addon's settings. When opening new mail tabs, additional tabs are closed, starting with the oldest.

[TabControl](https://addons.thunderbird.net/en-us/thunderbird/addon/tab-control/){:target="_blank"} ([source](https://github.com/maxjcohen/TabControl){:target="_blank"})

### DontRestoreTabsRevival:
This extension allows the user not to restore tabs at startup in Thundertbird.

[DontRestoreTabsRevival](https://addons.thunderbird.net/fr/thunderbird/addon/dontrestoretabsrevival/){:target="_blank"} ([source](https://github.com/guylifshitz/DontRestoreTabsRevival){:target="_blank"})


![An image of the final project]({{"assets/images/2021-10-11-Accessibility-plugins-for-Thunderbird/tab-control.png",  | relative_url }})

