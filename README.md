# Flashcards
Text files containing flashcard entries for importing into Anki.

For more info about importing text files see [the Anki Docs](https://apps.ankiweb.net/docs/manual.html#importing-text-files]).

## Custom Note Types
  * Definition:
     * Field 1 - Term: A single term
	 * Field 2 - Def: A single phrase/sentence definition
	 * Field 3 - Ref: Reference information
  * Equation:
     * Field 1 - Name: The name of the equation
	 * Field 2 - Equation: The equation
	 * Field 3 - Notes: Additional information about the equation (meaning of variables, etc)
	 * Field 4 - Ref: Reference information
  * MathCloze:
     * Field 1 - Number: A number for Anki to match with
	 * Field 2 - Text: The text of the card, including clozes created with {{c#::XXX}}
	 * Field 3 - Ref: Reference information

## Etc
I use the cmr10 font type, which matches the default latex font. I have also found that MathJax looks much better than latex (for example, in-line latex doesn't handle symbols that extend below the line well). 
