# qqscript

## What is it?

__qqscript__ is a system for quick entry of non-letter characters on
mobile devices. Character is entered by entering `qq` then two
letters of mnemonic code. That saves the typer the pain of switching to the additional layouts on a mobile
keyboard.

Mobile keyboards are small and for typing the text with lots of non-alphabetic characters or digits you have to 
switch to numeric or special characters keyboard. To save time and context-switching qqscript allows you to type
`qq` and then two-letter mnemonic sequence for non-alphabetic characters. `qq` is very unlikely to occur in natural
English text or programming code, and `q` is conveniently located in the top-left corner.

Digits may be entered by typing qq and then two letters that graphically resemble the digit. From 0 to 9 these letters are
__oizehsgtbj__. You use lowercase letters for entry, but to memorize letters you may find it more onvenient to
remember capital letters __OIZENHSGTBJ__. So for example to enter `7` you type `qqtt`.

Special characters can be entered using two letters of a mnemonic. Sometimes it is first two letters of the character name
(e.g. `qqam` for `&`, "ampersand") or two first letters of the composite name (`qqrc` for `}`, right curly bracket) or well-known
mnemonic from html (`qqlt` for `<`, "less than") etc.

## Installation

Currently qqscript is just a proof of concept and is contained in single HTML file that you can open in the browser. Substitution is
performed in the text area by a single JavaScript function and is specified by a dictionary of substitutions.
