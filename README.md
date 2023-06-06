# LanguageIndex

<img src="https://komarev.com/ghpvc/?username=merwin-pli&label=Project%20Views-Github&color=0e75b6&style=flat" alt="darkmash-org" /> 


Dataset of most (all widely used + some others which are no longer used) programming languages.
It provides a basic description, if the language is OOP or not ,if it is statically or dynamically typed , information about the speed of the language, what it is mostly used for, the marketshare of the programming language and installation command for Linux (the command maynot work on all distributions), MacOS and Windows(some of the languages couldn't be installed using commandline on Windows hence are left null).

### warning 
This Index may containing wrong information , wrong/harmful installation commands and so on. This list have to be used with care.<br>
The list may not be complete and information which we werent able to get was set as null. <br>
The data was generated also with the help of tgpt.<br>
*It is under MIT license*<br>

### Contents of the file 
- Stored as Json
- Total number of languages - > 656
- If any info wasnt found it is set to null
- Structure :
```json
{
"lang_1" : {
"description" : "................",
"OOP" : "true / false (if its object oriented programming language)",
"type" : "statically typed / dynamically typed",
"speed" :  "very fast/fast/medium/slow",
"mostly_used_for" : "..............",
"market_share" : ".................",
"installation" : {
"windows" : "....",
"linux" : ".....",
"macOS": ".....",
       },
   },
}
```


### Downloading
Simple download from here.

```sh
git clone https://github.com/merwin-asm/LanguageIndex.git 
```

raw data  : https://raw.githubusercontent.com/merwin-asm/LanguageIndex/main/main.json

