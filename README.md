# Intro To Regex Cheat Sheet!
Here are some snippets to get started! 

| **Name**                   | **Info**                              | **Example**        |
|----------------------------|---------------------------------------|--------------------|
| Flags                      | g=global, I=insensitive               | /cat/gi            |
| letters                    | You know letters                      | /dog/              |
| digits                     | You know digits                       | /12/               |
| Character Set/Class        | Brackets                              | /[aeiou]/          |
| Negated Character Set      | Carrot and brackets                   | /[^aeiou]/         |
| O or more                  | *                                     | /a*/               |
| 1 or more                  | +                                     | /a+/               |
| 0 or 1                     | ?                                     | /a?/               |
| Start of string            | Carrot, no brackets                   | /^hi/              |
| End of string              | Dollar sign                           | /bye$/             |
| Quantifier exactly         | Braces, one number                    | /AH{10}/           |
| Quantifier at least X many | Braces, one number and comma          | /OH{3,}/           |
| Quantifier exact range     | Braces, two comma separated numbers   | /WO{2,4}W/         |
| Groups                     | Parens with optional pipe OR operator | /(my)\s(cat\|dog)/ |


## Special Characters 

| Character Class | Definition                    |
|-----------------|-------------------------------|
| [0-9]           | Any single digit              |
| [3-30]          | And number in range           |
| [a-z]           | Any lowercase letter          |
| [a-d]           | Any lowercase letter in range |
| [A-Z]           | Any uppercase letter          |
| [E-Q]           | Any uppercase letter          |
| [a-zA-Z]        | Any letter                    |
| \d              | Any single digit              |
| \D              | Any NON digit                 |
| \w              | Any alphanumeric (and _)      |
| \W              | Any NON alphanumeric          |
| \s              | Any whitespace character      |
| \S              | Any NON whitespace character  |
| \b              | Any work break                |
| \B              | Any NON word break            |
| .               | Any character at all          |
| \\.              | An escaped period             |
