# P2: xkcd style Password Generator

## Description
 This assignment involves building a web application which generates an xkcd style password using php,HTML and CSS. 

## Demo
  I will attend an in-person section with Katherine on Wednesday(Oct 8).

## Details for teaching team
* The word list is generated by scraping words from Paulnoll website.
* The script scraps words from online site the first time "generate password" request is made and saves it in a JSON file for subsequent           requests. The script re-generates the JSON file if more than fifteen days have elapsed since the last time words were extracted. This is to     ensure that the word-list includes recently added words to the website.
*  Depending on the form inputs, the script can generate "words" password with "symbols" and "number".
*  An option to input the number of symbols is provided in the form (which becomes visible only when the user selects the "Add a symbol"     checkbox).
*  Number and symbols are randomly picked from numbers and symbols array respectively and get randomly placed after any word in the      password.
*  Appropriate error messages are generated to alert the user to input the required missing inputs or to verify the type and size of textbox        inputs.
*  To further customize the password one can select the appropriate options for  case - Upper, Lower, Camel (by default) - and 
    seperator - Hyphen, Underscore, No Spaces (by default) to be used in the password.

## Live URL of the project
* [http://p2.dwa15-ng.me] (http://p2.dwa15-ng.me)

## Outside Code used
* Google Fonts
* Bootstrap [http://getbootstrap.com/](http://getbootstrap.com/)
* Paulnoll website to scrape words to generate a word list.
* jQuery

Thanks!
