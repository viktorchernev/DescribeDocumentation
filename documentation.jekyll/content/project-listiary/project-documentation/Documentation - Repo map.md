---
layout: page
title: Documentation - Repo map
permalink: /listiary/documentation/repo-map/
exclude: true
---
In this article we explain the structure of the Documentation repository - currently hosted under the name (DescribeDocumentation)[https://github.com/viktorchernev/DescribeDocumentation].   
<br>

### 1. Redundant

`/!redundant`  

The redundant directory here, as well as in other repositories in the Listiary and Describe projects, serves to keep archived back-up copies of all the other public repositories for the sake of redundancy and convenience. For example, you might be offline and only have that one repository, or you might have an archive of just one repository, but the `!redundant` directory got you covered. 

Basically, we could've made the decision to go with one repository for the whole project, but made the choice to have many repositories, but still have copies of the other repositories with each one.  
<br>


### 2. Work

`/!work`

The work folder contains old work files, and sometimes current work files. In this repository, where the work is done in the repository folders directly, the work folder serves more as a backup than anything else - back up of work in progress, without the need for a github commit, backup of work that could be needed later on. etc.  
<br>


### 3. Git

`/.git`

As expected, this is the git folder for the repository. Git uses it, and we don't really touch it.  
<br>


### 4. Drafts

`/drafts`  

Content is being created firstly here, and we have few folders here with different content.  
<br>


### 5. Markdown

`/documentation.markdown`  

Next, we turn our content to markdown - by adding proper lightweight formatting and front-matter. We can also skip the drafts and write markdown directly, if we wish. But while the drafts folder is a work folder, the markdown folder is one of a put-together website.  
<br>


### 6. Jekyll

`/documentation.jekyll`  

This is where we build our jekyll website. It contains config files, and folders part of our modified 'Minima' theme. We get the latest markdown version and put it in the 'content' sub-folder, and we use jekyll commands on the command line to build and test-serve the website.  
<br>


### 7. Html

`/documentation.html`  

This is the ready built static site. We get it from the jekyll folder `documentation.jekyll\_site` after we build the site and are happy with the result. We need to host it in order for the site to work properly, though.  
<br>


### 8. Github

`/documentation.github`  

This has nothing to do with the main website. Instead, it is the wiki in our git repositories - for now just the describe compiler has one.  
<br>


### 9. FILES

README.md - The readme of the repository.<br>
LICENSE.md - The AGPL-3.0 license wavier for the repository.<br>
MAP.md - This article.<br>

<br>
<br>

### Links
[Documentation Project](/listiary/documentation/home/)<br>
[Documentation - How to edit](/listiary/documentation/how-to/)<br>
[Back](/listiary/)