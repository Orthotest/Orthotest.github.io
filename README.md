## Creating a new research study

The files for research studies are located within the \_posts folder. Each branch of Orthopaedic Surgery has its own folder. Each research study is a markdown file. If you are unfamiliar with markdown, here is a handy [reference](https://help.github.com/articles/markdown-basics/).

To add a research study to the app, create a new file and save it in the appropriate subfolder within `_posts`. Use the following convention for filename: `YYYY-MM-DD-title.md`.

For example, to create a new study in sports medicine, you would create a new file with a filename like `2015-08-11-turf-toe.md` and save it in the `_posts/sports/` subdirectory.

To create content, within a text editor (Such as [Sublime Text](http://www.sublimetext.com/3) or [Atom](https://atom.io/)), copy all of the content from a previous study, and paste that in your new study document.

At the top of the page, update the YAML front matter. Layout should be post. The title should be whatever you choose. The category needs to match the name of the subdirectory. It should be either foot, hand, joints, pediatric, spine, sports, or trauma. If there are subsections within the category area, set 'tag' to the name of the subsection.

For example:

```
---
layout: post
title: Hallux Rigidus
category: foot
tag: foot
---
```

Continue updating the rest of the content of the document and delete any unused or unnecessary fields.

## Adding the new study to the app

After you've saved all of your changes, you need to update the app with the new content. In the Github desktop application, in the window where you see the changes that you've made, add a commit message describing your changes (ex. Added new study). Hit the "Commit" button to confirm your changes. Then, hit "Sync" in the upper-right hand corner. This uploads your changes to the Github repository where the app is hosted.   
