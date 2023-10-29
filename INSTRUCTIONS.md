---
title: Instructions
---

## Getting iA presentations onto GitHub

1. Go to GitHub Desktop and select `presentations` repo
1. Click the `Show in Finder` button
1. Create folder with name of presentation (use this format: first-day) in the `presentations` folder
1. In Presenter, Export HTML
	1. Save it to the folder you just created
	1. Rename `presentation.htm` to `index.htm`
1. In Presenter, Export Markdown and call it speaker-notes
	1. Change filename to `speaker-notes.md` (make sure to include .md)
	1. Uncheck box to copy local media
	1. BUT do rename the `media` folder to `images`
	1. Save it in same folder as HTML stuff
1. Go back to GitHub Desktop (where you'll see there are new files added)
1. Enter a "commit" message
1. Press `Commit to main` button
1. Press `Push origin` button
1. Click `View on GitHub` button and add to README.md by clicking the pencil icon and copying existing examples

## Cleaning up speaker notes pages for better display online

- Add page title (see example)
- Change Heading 1 elements to Heading 2
- Remove horizontal rules (`---`)
- Use 1 line break between paragraphs and images
- Remove line breaks between list items of the same list
- Add descriptions of photos (inside the brackets, e.g., `![description of photo here]`)