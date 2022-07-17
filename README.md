# Informatik-Anki

This is a repository with a collection of Anki decks for courses of B.Sc. Computer Science.

## Setup

### Anki Installation
This project uses the Anki addon CrowdAnki to serialize Anki packages to JSON, which is a better format for version control than .apkg.

In Anki click on:

- Tools > Add-ons > [Get Add-ons] > Code: 1788670778 > [OK]
- Restart Anki

### Importing Decks

To import a deck from the downloaded repository click:

- File > CrowdAnki: Import from disk > Select the folder containg the deck.json file > [OK]

### Contributing

In order to save changes on an edited deck you have to export it back to JSON. In Anki click on:

- File > Export... > Export Format: CrowdAnki JSON representation > [Export...] > Select the folder which contains the deck.json file

You then can commit and push the changes.  

More details about CrowdAnki:
[CrowdAnki About Page](https://ankiweb.net/shared/info/1788670778)
[CrowsAnki on Github](https://github.com/Stvad/CrowdAnki)
