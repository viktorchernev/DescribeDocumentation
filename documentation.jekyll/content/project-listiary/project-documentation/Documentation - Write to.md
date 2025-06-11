---
layout: page
title: Documentation - How to edit
permalink: /listiary/documentation/how-to/
exclude: true
---
<br>
The Documentation project is the project tasked with creating and managing a documentation website for the Describe Markup Language, the Listiary wiki, and all the related - child or satellite projects. The result is the very same documentation you are reading at the moment - originally hosted at [documentation.listiary.net](https://documentation.listiary.net/).  

In this article, we will see how to add, edit and publish articles to the documentation website.  
<br>


### 1. Turn text article drafts to markdown, suitable for Jekyll

The first step would be to prepare a text draft of the article - refine it, spell check it, etc. But once this is done, the next step is to turn the article to a suitable markdown.  
<br>
To turn plain text to a markdown syntax, suitable for our project and following our conventions you must simply follow few basic rules:  

• Manage new lines strategically and chech for the result with a markdown render-er. Check other articles already done. (Use two spaces after the end of a paragraph. `<br>` tags can help here too)<br>
• Write links as `[link text](https://link-url.com/)`<br>
• Write headings with `#` signs - `### Subtitle` or `## Title` e.g.<br>
• Escape code with backtick - ``` ` ```.<br>
• Markdown can contain HTML directly. Use HTML spans with style property to colorize and decorate text, when needed<br>
• it can be more reliable than markdown, and is more flexible.<br>

To turn markdown files Jekyll suitable for our project, you must add the Jekyll front matter. It is a text that we add at the beginning of each markdown file. It shall look like this:

```
---
layout: page
title: Radiowatch - FAQ
permalink: /listiary/radiowatch/faq/
exclude: true
---
```
<br>


### 2. Build Jekyll documentation

Go to the folder containing the jekyll dir - `\DescribeCompiler.jekyll`,<br>
Adjust values in `_config.yml` if needed.
	
Copy the prepared markdown files/directories to the `content` subfolder,<br>
Copy the index to the main folder as well, making sure that the permalink on that version is commented - `# permalink:`,<br>
<br>
_Run Jekyll_ <br>
In cmd, cd to the jekyll dir - `cd "PATH_HERE\DescribeCompiler.jekyll"`,<br>
Run `bundle install`,<br>
Run `bundle exec jekyll -v` if you want to test,<br>
Run `bundle exec jekyll clean`,<br>
Run `bundle install`,<br>
Run `bundle exec jekyll serve`,<br>

_View result_ <br>
Check result on localhost - `http://127.0.0.1:4000/`,<br>
`Ctrl+V` then `Y` then `Y` to stop server later;<br>

_Check stuff_ <br>
Check if ruby installed: `ruby -v`<br>
Check if Jekyll installed: `jekyll -v`<br>
Install Jekyll:<br>
`gem update --system`<br>
`gem install jekyll bundler`<br>
`jekyll -v`<br>


_Commands_ <br>
`jekyll new @website --force` <br>
`cd @website` <br>
`bundle exec jekyll serve` <br>
`bundle exec jekyll serve --draft` <br>
<br>

_Jekyll folder_ <br>
gem environment - `C:\Ruby32-x64\lib\ruby\gems\3.2.0\gems`
gems - `C:\Ruby32-x64\lib\ruby\gems\3.2.0\gems\jekyll-4.3.3\lib`
<br>

_Ready sites_ <br>
`C:\Users\Viktor Chernev\Desktop\World-Describe\Website\WorldInLists-Documentation\ver_blog`<br><br><br>


### 3. Get the HTML version

The `\DescribeCompiler.jekyll\_site` folder contains the HTML version of the website after serving it in the previous step. We simply copy all the contents to `\DescribeCompiler.html`, after deleting the contents of the folder.  
<br>
That is our host-able site. We can go ahead and use FileZilla to upload it, but keep in mind that it won't work properly as a `file://` on a local host, without being served.<br><br><br>


### I. Modify the minima theme

We will not need to do this every time, but I include it, just in case something goes wrong with our setup, and we need to set up from scratch.
<br>

We are applying a few small modifications to the preinstalled minima theme before we use it, and we are doing that by copying some of the sub-folders of the theme to our Jekyll folder, so that they might take precedence for our project but not affect other projects, and also, we don't loose the changes when we update the minima theme.
<br>

A) In the main CSS file, the first media query says - `@media screen and (max-width: 600px) {` - we want to remove the second part and leave it as `@media screen {`.
This is the query that makes the navbar into a hamburger button, and by modifying it like that, we make sure it remains a hamburger button for any screen sizes, not only on mobile devices. To do that, we find our installation of the minima theme - which is just a ruby gem, residing in `C:\Ruby32-x64\lib\ruby\gems\3.2.0\gems`, copy the `_sass` folder to our project, open the "_layout.scss" file and replace `@include media-query($on-palm)` with `@media screen`. We copy the folder to our project so that this version is always loaded from here.

B) We do some modification to the ruby logic in `_includes/header.html`. 
The example below shows that we are using the custom front matter variable `exclude` to exclude any pages where it is set to true.
We also manually added the links we want included in the nav-bar.
It looks like this:

```
<div class="trigger">
    <a class="page-link" href="/language/how-to-write/">Language Home</a>
    <a class="page-link" href="/language/how-to-compile/">Compiler Home</a>
    <a class="page-link" href="/language/reference/">Tech Reference</a>
    <a class="page-link" href="/language/">About Describe</a>
    <a class="page-link" href="/listiary/">About Listiary</a>
    <a class="page-link" href="https://library.listiary.com/">Describe Library</a>
    <a class="page-link" href="/language/site-map/">Site Map</a>
  {%- for path in page_paths -%}
    {%- assign my_page = site.pages | where: "path", path | first -%}
    {%- if my_page and my_page.exclude != true -%}
      {%- if my_page.title -%}
        <a class="page-link" href="{{ my_page.url | relative_url }}">{{ my_page.title | escape }}</a>
      {%- endif -%}
    {%- endif -%}
  {%- endfor -%}
</div>
``` 

C) Gray header/footer - We want to add `style="background-color: #ccc;"` CSS in header.html - here `<header style="background-color: #ccc;" class="site-header" role="banner">` and here `<nav style="background-color: #ccc;" class="site-nav">`, and in footer.html - here `<footer style="background-color: #ccc;" class="site-footer h-card">`.
<br>
<br>

### Links
[Documentation Project](/listiary/documentation/home/)<br>
[Documentation - Repo map](/listiary/documentation/repo-map/)<br>
[Back](/listiary/)