# German Diceware Wordlist for Random Passphrases

**Work in Progress**

## Wait a minute, what are passphrases anyway?

A [Passphrase](https://en.wikipedia.org/wiki/Passphrase) is a passwords made
up of multiple words, such as:

    correct horse battery staple

This makes them easy to remember (for you) and hard to guess (for others):

[![xkcd: Password Strength](https://imgs.xkcd.com/comics/password_strength.png "xkcd: Password Strength")](https://xkcd.com/936)

## And what exactly is Diceware?

[Diceware](https://en.wikipedia.org/wiki/Diceware) is a method to generate
those passphrases using ordinary dice, invented by Arnold Reinhold.
You simply roll five dice to pick a random word from a Diceware wordlist until
you have enough words.
This repository provices such a list.

## Formats

The wordlist is available in these formats:

- `wordlist-german.txt`: original german wordlist with correct capitalization
- `wordlist-german-lowercase.txt`: lowercase version of the wordlist above
- `wordlist-german-diceware.txt`: the actual german diceware wordlist made from
  the lowercase wordlist

## Words

All included words have been manually checked and meet these conditions:

- 3 to 7 characters long
- contains english letters only (no german special characters like umlauts)
- a known noun, verb or adjective in its basic form
- office-friendly (not vulgar, offensive, religious or with negative
  connotations)
