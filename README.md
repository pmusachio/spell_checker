# Spell Checker

## Description
- Spell checker applying NLP techniques with library NLTK

## Function
- Python code for Spell Checker in words (PT-BR) that have errors of only one letter (missing, remaining, inversion or accentuation)

| INput | OUTput |
| ------- | -------- |
| correct "word" | correct "Word" with the 1st letter capitalized |
| wrong "wotd"  with just one error | corrected "Word" |
| wrong "qotd" with several errors | "qotd" inserted + error warning |

## Library
- Only the NLTK library (Natural Language ToolKit) was used for the db processing, and for the construction of the spell checker I used the standard lib

## Database
- During the creation of the corrector, posts on the Alura website were used, the words found are used as "standard" for the corrector
