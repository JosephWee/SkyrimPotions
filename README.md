# Skyrim Potions
This is a simple Python program for generating "Elder Scrolls Skyrim V: Skyrim" potion recipes.

## Input Files
The following CSV files are sample input files required by the program:
1. Alchemy Ingredients - Standard.csv
2. Alchemy Ingredients - Creation Club.csv

These files contains the list of Standard and Creation Club Ingredients respectively.
Each file consist of 7 columns:
1. ID - Unique Hexadecimal String ID of the ingredient
2. Name - Name of the ingredient
3. Effect1 - 1st alchemical effect of the ingredient
4. Effect2 - 2nd alchemical effect of the ingredient
5. Effect3 - 3rd alchemical effect of the ingredient
6. Effect4 - 4th alchemical effect of the ingredient
7. Description - Brief description of ingredient, can be left blank if not available

The following JSON file is the actual input file required by the program:
1. effects.json - A JSON file consisting of all available alchemical effects

## Output Files
The following JSON file is a sample output of the program:
1. recipes.json - JSON file containing potion recipes with the desired effects