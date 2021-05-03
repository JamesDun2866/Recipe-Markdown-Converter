
# Recipe MArkdown Converter for Chowdown Recipe Manager 

### Simple script designed to take a recipe paste/dump and turn it into a markdown recipe format for the chowdown recipe manager. 

To use this, paste a recipe into a notepad and insert the flags so the script knows where to split. These flags are TITLE, EXTRAS, DIRECTIONS And INGREDIENTS.

Source file you want to convert is opened in the first line of code change it to your text file.

Paste printed markdown into a notepad and save as a md file.

Errors: 
- Ingredients should be the last in order, the script will error if there is a newline under "INGREDIENTS" flag.
- If any of the flags are out of place script will error.
- If any flags are missing, script will error. 


Example:

Scenario: I want to convert a paper recipe from a book

- Take a photo and use Google lens to get the text of the image/scan and take the text. 
- Optional: Spellcheck and edit where required
- Paste into notepad and input flags
- Ensure file location is correct
- Run script
- Copy the markdown text and save to a new notepad file
- Save as "Recipe”.md
- Upload to chowdown
 
