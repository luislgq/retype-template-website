# This is a template to create your own Retype website.

Retype is an  generator that builds a website based on simple text files, and thanks to github actions and github pages you can have your own site running in just a few minutes. I personally use my retype website as a companion to my CV, but it can be used for a any number of projects. 


# How to create your own Retype Website. 

Creating a retype website with my template is extremly simple, the only thing you need is a github account and some basic git knowledge (Even though you can do all of this from the UI!). 

1. Create a new github organization (Settings >> Your Organizations >> New Organization)
2. On this [github](https://github.com/luislgq/retypetemplatewebsite) click on ["Use this template"](https://github.com/luislgq/retypetemplatewebsite/generate). Under "Owner" select the new organization you have created, then name your repository. The repository name must follow this structure: websitename.github.io. Any other structure will not work.
4. Go to the settings of your newly created repo and in "Pages" change the "Source Branch" from **"main"** to **"retype"**
5. Now on the top bar of your menu go to **"Actions"** where you should see the following running job: **"pages build and deployment #1"**.
6. Once this job has stop running you can find your website in the following link https://yourwebsitename.github.io (The URL matches the name of your repo created on the second step) 
7. Now you can create new pages and edit the existing ones. You can do this from the terminal or directly from the Github UI. 

# How to edit MD pages.

A MD file is a text file that uses a Markdown language that provides with formatting options to the text. By example writing two asterist before and after a word (like this: \*\*text**) will turn the text into bold  **text**. For more information on how to use MD please see a basic guide [here](https://www.markdownguide.org/basic-syntax/). When using retype your MD files should start like this: 

\---
icon: iconname

order: 100 

label: Title of the page 

\---

Retype will sorth the pages you create, in a descending order depending on the **"order"** value. Each page can have a small icon, the names of the **"icon"** can be found [here](https://octicons-primer.vercel.app/octicons/). The  **"label"** provides us with the title of the page, the name of the file does not matter, only what we set as the label. 

Other than this, retype allows a great deal of customization, from tables to code containers. I strongly suggest browsing their website for a complete list of [Retype's](https://retype.com/) capabilities.


