---
layout: single
title: "Deswik for Lewis' CSM3044 module"
permalink: /deswik/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/plainblue.png
  caption:
excerpt: 'Stuff to catch up on or hints you might have missed'
author: Peter Bennett
---

# Module Principles

* Listen to everything Lewis says. This will make your life a lot easier. Listen for his nuggets, he may not announce them, and they may be in lecture sessions as well as IT workshop sessions. Attendance will make your life much easier.
* Deswik is not spelt with a C. It is a proper noun, and should be capitalised.
* The University has both 2018.4 and 2019.1 versions of the suite installed. These are consecutive versions, and there are no major differences that we will need to know about.
* The design is to be created to the standard of a scoping or pre-feas study, not a definitive feasibility study, or short term design document. Your design does not need to be crazy detailed or crazy accurate.
* This module is not a Deswik module. It is a mine design module, and learning Deswik is the byproduct.
* Your file may have appeared as a blank canvas when you first opened it, but a lot of work was already put into this blank file to make your life easier, and to make best use of the available time
* **This page is not a blind walkthrough of the coursework, it is designed to be here to help you understand the processes you need to use. It will also direct you to the places in the official help where you can help yourself**
* **MScs and future years: Your project and parameters are different. This is for the AY 2019/2020 BEng mining course.**

# Deswik Basic Working Principles

* If you are stuck with a particular command or function, the official help files are incredibly detailed, well written, and easy to understand, even from a relatively basic understanding.
* Deswik is an incredibly extensive suite of software, and it is unlikely that any human being will ever use more than 20% of it, unless thay are actually working for Deswik. We will use the design functions of Deswik.CAD and scheduling functions of Deswik.Sched (the 'Scheduler'). To link these, we will use Deswik.IS (the 'Interactive Scheduler') - this is one of the Deswik suite's most powerful functions.
* There are usually multiple ways of achieving the same thing. Different mine sites will use different processes. Me and Lewis use different processes for the same thing.

## Pre-setup
1. User interface setup
2. File Management and linked schedule
3. Backup and save settings
## Steps so far
4. Importing geology and block model
    1. Import Datamine orebody wireframe
    2. Link Block Model
        1. Block model legend
        2. Cut-off grade block model filter
        3. Block model annotations
5. Creating ore drives
    1. Setting a horizontal working plane
    2. Drawing ore drive polylines
6. Creating level access drifts
    1. Drawing level access polylines
    2. Shortening level accesses to ore drives
7. Creating declines using the decline tool
    1. Importing surface topography
        1. Mapping images
    2. Creating construction lines
    3. Calculating decline geometry
    4. 40 metre standoff
    5. Using the decline tool
        1. Accessing the Burras Deeps
8. Direction of mining
    1. Reversing polylines
    2. Breaking polylines
9. Creating preliminary tunnel solids
    1. Creating attributes
        1. By filtering and selection
        2. By formula
    2. Linked Schedule and Densities
    3. Updating sections
10. Stoping
    1. Guide strings
        1. Importing datamine string
        2. Many strings
        3. Extending strings
    2. Setting a vertical plane
        1. Visual settings
    3. Stope Loops
## Tips and tricks

- Multiple views
- Most recent commands

## Useful information

- Image mapping points
- Keyboard shortcuts
    
# 1. User interface setup
When Deswik first opens on a PC, it will ask if you want to work in metric or imperial. Since we live in a civilised society, we will use metric.

On first open, Deswik will also only show the getting started toolbars. This does not give you quick access to many tools. For our purposes, we will require the **general** toolbars. 
- **Toolbars** are picture based sets of tools. These are found above and to the left and right of the workspace. These are completely customisable.
- **Menus** are text-based drop-downs. These are found at the top of the window. These may be more logically ordered, but take longer to navigate.
- **Dock Windows** are the windows within the interface that perform specific functions. Initially, three will be open. Layer Control (left), Output (bottom), and Properties (right). DO NOT CLOSE THESE THREE.

Many things can be found in both toolbars and menus, and often through keyboard shortcuts too. 

To enable the general toolbars, navigate through the menus to View \| Toolbars \| Show General. You should now have four rows of toolbars at the top of your workspace. Don't panic Mr Mainwaring, you'll gradually learn a fair number of the tools you can see. You can [rearrange](https://help.deswik.com/HelpContent/Deswik.Suite2019.1/content/deswiksuite/customizingmenusandtoolbars.htm#Moveatoolbar) toolbars if you need, but generally their original positions are good.

The interactive scheduler (Deswik.IS) should also be open while using Deswik.CAD. This can be opened through the menus by going Tools \| Deswik.IS (Interactive Scheduler). It will then appear on the left of your screen. For now, [stack this as a tab](https://help.deswik.com/HelpContent/Deswik.Suite2019.1/content/deswiksuite/managingdockwindows.htm#Dockawindowinanewposition) on the left pane over your Layer Control dock window.
# 2. File Management and linked schedule
Before opening your CAD file (orange icon), rename it to have your own name on it instead of Lewis'. Do the same to your schedule file (blue icon).

Because you have renamed your schedule, you will need to relink the two files. Find your IS dock window and click on **Project Options.** Select your newly-renamed schedule file.
# 3. Backup and save settings
Deswik has backup functionality. You may not know about this, but when you make a critical mistake 2 days before hand-in, you'll think its a god-send.

**Deswik will keep your backup files within your working folder, i.e. on your USB drive. Therefore, this will not save you if you lose your USB. My advice is to back your entire working folder up to another personal device regularly.**

To find backup settings, navigate through menus to Tools \| Options. In the options window, find the Backups tab. Here you can adjust the backup settings. The standard ones are quite good. You can also enable save reminders by checking the bottom checkbox, and set the frequency of these. These are a useful way to automatically remind yourself to save your work.

# 4. Importing geology and block model

Our geology data is supplied. As mining engineers, this will usually come from a geology department. Ours is from Lewis.

## 4.1. Import Datamine orebody wireframe

The wireframe is an outline of the orebody. It does not contain density or other attributes. It should be imported onto a layer under geology using File \| Import \| Datamine \| Wireframe. You may wish to make it semi-transparent, to help you see what is going on.

## 4.2. Link Block Model

The block model is our geological numerical data model. It is generated through difficult maths and diamond drillholes. In our case it contains data about grade, class, lode, and density. The lode attribute is unimportant, since we are only working on a single lode, lode "6". 

### 4.2.1. Block model legend
### 4.2.2. Cut-off grade block model filter
### 4.2.3. Block model annotations
5. Creating ore drives
    1. Setting a horizontal working plane
    2. Drawing ore drive polylines
6. Creating level access drifts
    1. Drawing level access polylines
    2. Shortening level accesses to ore drives
7. Creating declines using the decline tool
    1. Importing surface topography
        1. Mapping images
    2. Creating construction lines
    3. Calculating decline geometry
    4. 40 metre standoff
    5. Using the decline tool
        1. Accessing the Burras Deeps
8. Direction of mining
    1. Reversing polylines
    2. Breaking polylines
9. Creating preliminary tunnel solids
    1. Creating attributes
        1. By filtering and selection
        2. By formula
    2. Linked Schedule and Densities
    3. Updating sections
10. Stoping
    1. Guide strings
        1. Importing datamine string
        2. Many strings
        3. Extending strings
    2. Setting a vertical plane
        1. Visual settings
    3. Stope Loops

[Home](./../)
