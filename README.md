# Flashcards
Text files containing flashcard entries for importing into Anki. All files are semicolon delimited.

For more info about importing text files see [the Anki Docs](https://apps.ankiweb.net/docs/manual.html#importing-text-files]).
When importing, I typically use the setting `Update existing notes when first field matches`. This preserves the history of notes that I have edited. I also check the `Allow html` box so I can use basic html in the notes. This is mostly for creating newlines with `<br>`.

## Custom Note Types
I use the following custom types of notes. For any new notes, I think the MathCloze type is the best, the notes look cleaner and emphasize only the essential information for memorization. All of the deck files in this repository should end with `_NoteType.deck` to keep importing easy. 
  * MathCloze:
     * Field 1 - Number: A number for Anki to match with
	 * Field 2 - Text: The text of the card, including clozes created with {{c#::XXX}}
	 * Field 3 - Ref: Reference information
  * Definition:
     * Field 1 - Term: A single term
	 * Field 2 - Def: A single phrase/sentence definition
	 * Field 3 - Ref: Reference information
  * Equation:
     * Field 1 - Name: The name of the equation
	 * Field 2 - Equation: The equation
	 * Field 3 - Notes: Additional information about the equation (meaning of variables, etc)
	 * Field 4 - Ref: Reference information

## Etc
I use the cmr10 font type, which matches the default latex font. I have also found that MathJax looks much better than latex (for example, in-line latex doesn't handle symbols that extend below the line well). 

## Images
Images can be imported automatically from `.deck` files by using an html tag `<img src=".png">` and allowing html on the import. Anki looks for the images in `~/.local/share/Anki2/Jacob/collection.media`. I copy images there from the `images` folder in this repository to mantain a backup.
