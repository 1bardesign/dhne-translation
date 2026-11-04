# Translating Dice Have No Eyes

Hello!

Thank you for your interest in helping to translate [Dice Have No Eyes](https://store.steampowered.com/app/4535880/Dice_Have_No_Eyes/)!

If a tsv for your language does not exist, create one as part of your submission. Submissions are only accepted through pull requests here on github, as that allows tracking ownership.

## File Organisation

The game translations are packaged to a large tsv file merged from the contents of this repository.

tsv files can be modified by applications such as microsoft excel, google sheets, onlyoffice, openoffice, libreoffice and many other spreadsheet editors.

There are several important files:

- `meta.tsv` - the configuration file for what languages are present; includes their iso 639 language code, an english language string and a native language string representing the name of the language, which are both displayed in the application.
- `en.tsv` - the "source of truth" - used as a template for new translations
- `translators.tsv` - a list of everyone to credit, by language code.

There is also one tsv file per language in this repository, to make it easier to merge translation work across languages and avoid merge conflicts. The `en.tsv` file should be taken as a template for a newly supported language, and a new line added to `meta.tsv`. This can all be done as one pull request for convenience.

## Coordination

For moment to moment contact, discord is probably best. You can find the discord invite link in-game from the title screen (it's ommitted here on github to reduce spam). Issues can be opened here for longer form conversations if need be.

## Licensing

you warrant that any work submitted is your own, and allow the text provided to be distributed and sold as part of Dice Have No Eyes.

## Credit

Please fill in a line (one per translator) in translators.tsv. If a translator worked on multiple codes, comma separate the codes like `en,fr,jp`

If your work is accepted, your provided details will be shown as part of the game credits based on the contents of this file.

Details must be appropriate for general audiences, so if you choose to be identified by a handle, it should not contain profanity.