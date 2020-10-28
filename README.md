# A Level Resources
This is a collection of all the flashcards and files I created during my A-levels. They have been mostly untouched since my A-levels. I have made them open to share after receiving many requests.

## Table of Contents
- [Downloading the Files](#downloading-the-files)
- [Reporting Issues](#reporting-issues)
- [Contributing](#contributing)
  * [Setting up GitHub](#setting-up-github)
  * [Loading the Flashcards into Anki](#loading-the-flashcards-into-anki)
  * [Exporting the Flashcards from Anki](#exporting-the-flashcards-from-anki)
  * [Making a Pull Request](#making-a-pull-request)
- [Roadmap](#roadmap)

## Downloading the Files
You can find the download page under [releases](https://github.com/RehmanAmjad/a-level-resources/releases) on the right hand side of the page. Make sure you download the latest release by pressing the first  `Source code` button on the page. You can then extract the folder and files and get studying!

Be sure to bookmark the releases page and check it regularly for updates (or make a GitHub account and watch this repository by pressing the `Watch` button on the top right).

## Reporting Issues
If you find any mistakes in any notes or flashcards then either make a GitHub account and create and issue under the issues tab of this repository or email me at ` ra570 (at) cam.ac.uk`.

## Contributing
I would be overjoyed if anyone reading this could help improve this collection (whether that be by correcting errors, adding extra detail, or anything else!) To do so, I would suggest following these steps.

### Setting up GitHub
1. Create a GitHub account and learn the basics (you can watch a comprehensive introduction [here](https://www.youtube.com/watch?v=RGOj5yH7evk)).
2. Fork this repository by pressing the button in the top right.
3. Download [GitHub Desktop](https://desktop.github.com/) and clone the forked repository onto your local machine.
4. Switch to the `dev` branch using GitHub Desktop.

### Loading the Flashcards into Anki
1. Download [CrowdAnki](https://ankiweb.net/shared/info/1788670778) onto your desktop version of Anki (requires v2.1).
2. Import the subject flashcards into Anki by either going to `File > Import` and selecting relevant `.apkg` file or by going to `File > CrowdAnki:Import from disk` and selecting the folder containing the `.json` file in the subject folder.
3. You're all set to use and make changes to the flashcards!

### Exporting the Flashcards from Anki
_OCR Chemistry will be used as an example here._

1. Press the gear icon next to the deck (which must have the same name and structure as when you originally imported it) and press `Export`.
2. Set the `Export format` to `CrowdAnki JSON representation (*directory)` and make sure it includes the media and tags.
3. Select the `OCR Chemistry` to export it there. This will create an new folder with the same name as the deck (ie, `Chemistry`)
4. Delete the existing `CrowdAnki` folder and rename the new `Chemistry` to `CrowdAnki`.

### Making a Pull Request
1. Once you have exported all your changes. Use GitHub desktop to scan for changes and commit them all to the `dev` branch of your forked repository with an appropiate summary and description of changes.
2. Go to the `Pull requests` tab of your forked repository on GitHub and press `New pull request` in the top right.
3. Ensure the `base repository` is this (`RehmanAmjad/a-level-resources`) and its branch is `dev` and the `head repository` is yours and the branch is your `dev`. You should be able to see a summary of the changes if you scroll down.
4. Press `Create pull request` and make an appropiate title and write a description of all the changes you made across all your commits.
5. Press `Create pull request` and wait for me to have a look at it. It should now appear under the pull requests tab of this repository.

Congratulations 🎉 you just contributed and made these resources so much better! If I ever meet you in person then I will buy you a coffee (or any other beverage). 

_Note that if you're confident with JSON then you can edit the JSON files directy rather than making importing into Anki, making changes, then exporting. Just be sure to check that it can still be imported after you have made the changes._

## Roadmap
### Phase 1 - make Anki only
_To avoid having to manage two versions of the same flashcard, one in word document form and another in Anki form (which have fallen out of sync slightly), we need to delete the word document form but keep the PDF's._

1. Wait for [PDF Glossary Exporter](https://ankiweb.net/shared/info/1334168683) to come out for Anki 2.1.
2. Tag all cards corresponding to the specification.
3. Move cards into seperate decks according to the specification.
4. Export each module in the specification as a seperate PDF.
5. Delete all the Word documents.

### Phase 2 - continual improvements
Look through a few flashcards on Anki every weekend and make small improvements.
