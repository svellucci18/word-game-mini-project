## What functions do we need

When we click start
    - timer starts counting down DONE
    - ability `addEventListener.("keydown",function)`
        - if letter is correct it will appear in the word.
        - loop through until all letters have been typed.

Game end conditions
    - timer ends
    - word is guessed

## Variables to declare

Array with all of the words

Generating the words
1) grab a word from an array ``var words = []`` Line 20
2) convert the word into its own array ``var word = []``
    look up method for deconstructing an array into letters
3) create a new mirror array: randomly erase letters from that word
    Math.random
    exchange the letter with an underscore
4) Display the word

Guessing the words
1) `addEventListener.("keydown",function)`
    if letter is correct
        exchange the underscore with the letter
        loop through until all letters have been typed.

