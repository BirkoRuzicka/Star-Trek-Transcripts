# StarTrek-Transcripts
Dialogue transcripts of Star Trek series, cleaned, one JSON, for TOS, TAS, TNG, DS9, VOY, ENT, DIS, PIC

For those not immersed in Star Trek abbreviations, this means:
* Star Trek: The Original Series (complete)
* Star Trek: The Animated Series (complete)
* Star Trek: The Next Generation (complete)
* Star Trek: Deep Space 9 (complete)
* Star Trek: Voyager (complete)
* Star Trek: Enterprise (complete)
* Star Trek: Discovery (seasons 1-3)
* Star Trek: Picard (season 1)

This database is also available on Kaggle: [Star Trek Dialogue Transcripts on Kaggle.com](www.kaggle.com/dataset/21193888400f89d64dfb1a349c8b116697bebe427e9a61d113e88cff414f09e5)

The code I wrote for scraping the data from http://chakoteya.net (with the owner's permission) and cleaning the text is included in this repository: [StarTrek_webscraping.py](https://github.com/BirkoRuzicka/Star-Trek-Transcripts/blob/main/StarTrek_webscraping.py). It was carefully designed to account for variance in the link structure between the series. The cleaning pipeline fixes minor issues with formatting, and removes superfluous line breaks, stage instructions, and context comments, and neatly separates the text so that each dialogue line is assigned to the character.

The JSON file contains nested dictionaries of this structure:

![](https://github.com/BirkoRuzicka/Star-Trek-Transcripts/blob/main/json_structure.png)

Using this data, I performed an in-depth analysis of dialogue distribution by gender across all series ([link to the repository](https://github.com/BirkoRuzicka/Star-Trek-Dialogue-Analysis)).


