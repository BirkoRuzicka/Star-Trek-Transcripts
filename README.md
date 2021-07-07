# StarTrek-Transcripts
Dialogue transcripts of Star Trek series, cleaned, one JSON, for TOS, TAS, TNG, DS9, VOY, ENT, DIS, PIC

This database is also available on Kaggle: www.kaggle.com/dataset/21193888400f89d64dfb1a349c8b116697bebe427e9a61d113e88cff414f09e5

I scraped the data from http://chakoteya.net with the owner's permission. The code I wrote for scraping and cleaning the text is included in this repository:

The code was carefully designed to account for variance in the link structure between the series. The cleaning pipeline fixes minor issues with formatting, and removes superfluous line breaks, stage instructions, and context comments, and neatly separates the text so that each dialogue line is assigned to the character.

The JSON file contains nested dictionaries of this structure:

![](https://github.com/BirkoRuzicka/Star-Trek-Transcripts/blob/main/json_structure.png)


