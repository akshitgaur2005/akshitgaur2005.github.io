---
title: "Yudh Devlog #1"
date: 2024-08-14
# weight: 1
# aliases: ["/first"]
tags: ["devlog", "yudh"]
author: "Akshit Gaur"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Beginning a new project"
canonicalURL: ""
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/akshitgaur2005/akshitgaur2005.github.io/tree/main/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

# Yudh

Ask any student about starting a new project and the perils he has to face, the answers will definitely shock you (if you are not a student yourself). The hardest part is not where to copy it from 😉 rather what it should even be about!

What I have finally arrived at, is this. Although the discussion is still going on in the team if this should be made the project that we devote our time to (most don't seem to agree), I still find it cool enough that I have decided to work on it. The vision is still not clear enough to directly jump on to coding and considering there is no content here on this website and thus no viewers, I will use this platform to articulate my thoughts on the project.

## General information

So, Yudh (name not finalised yet) is going to be a battle simulator, where two AI's will field medieval/ancient armies and try to duke it out, Ajatshatru style!
The control of each and every troop will be in the hands to the said AI.

For example, let's say that their are two troop types, infantry and archers. So while infantry may have health of 100, damage of 50 and range of 1; archers may possess HP of 50, damage 25 but a range of 10. Further things that can be added are innumerous, movement speed, variablity or unpredictability of the attacks landing, etc can all be simulated.

This "game" will be grid based as I have no experience in game dev and grid based system seems simpler.

## What to do?

So, for now the things needed to implement are -

- Battleground - The main grid where fighting will take place. It should also contain functions to return state for the eventual training of the RL models, method to update the locations of the troops and all the constraints related to it.
- Troops - A general troop class and warfare system that is easily moddable.


Let's see hpw long can I "work" on it before inevitably abandoning it too!
