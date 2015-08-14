## Creating a new research study

The files for research studies are located within the \_posts folder. Each branch of Orthopaedic Surgery has its own folder. Each research study is a markdown file. If you are unfamiliar with markdown, here is a handy [reference](https://help.github.com/articles/markdown-basics/).

To add a research study to the app, create a new file and save it in the appropriate subfolder within `_posts`. Use the following convention for filename: `YYYY-MM-DD-title.md`.

For example, to create a new study in sports medicine, you would create a new file with a filename like `2015-08-11-turf-toe.md` and save it in the `_posts/sports/` subdirectory.

To create content, within a text editor (Such as [Sublime Text](http://www.sublimetext.com/3) or [Atom](https://atom.io/)), copy all of the content from a previous study, and paste that in your new study document.

At the top of the page, update the YAML front matter. Layout should be post. The title should be whatever you choose. The category needs to match the name of the subdirectory (valid categories are listed below).

For example:

```
---
layout: post
title: Hallux Rigidus
category: foot
---
```

Continue updating the rest of the content of the document and delete any unused or unnecessary fields.

#### Current categories (categories)

- foot
- hand
- pediatrics
- recon
- spine
- sports
- trauma

## Adding the new study to the app

After you've saved all of your changes, you need to update the app with the new content. In the Github desktop application, in the window where you see the changes that you've made, add a commit message describing your changes (ex. "Added new study"). Hit the "Commit" button to confirm your changes. Then, hit "Sync" in the upper-right hand corner. This uploads your changes to the Github repository where the app is hosted.  

## Editing an existing study

In the Github application, click "Sync" to make sure that your local copy of the files matches the remote repository. In your text editor, select the file you wish to edit and make any desired changes. After you've finished, save the file, then return to the Github application. Add a commit message and hit the "Commit" button to confirm your changes. Click "Sync" to copy those changes to the Github repository.

## Removing an existing study

In order to remove a study from the app, first go to the Github application. Hit "Sync" to make sure your local copy matches the remote copy. Then, delete the study file that you wish to remove. It will be a `.md` file within the `_posts/category` folder. For example, if you wanted to delete a file in the Foot & Ankle category, you would go to the `_posts/foot/` folder and delete the file with the name matching the research study.

Once the file is deleted, return to the Github application. Write a commit message and hit "Commit" to confirm your changes, then hit "Sync" to copy those changes to the Github repository. 
