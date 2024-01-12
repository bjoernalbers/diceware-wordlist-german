# German Diceware Wordlist for Random Passphrases

## What are passphrases anyway?

A [Passphrase](https://en.wikipedia.org/wiki/Passphrase) is a password made
up of multiple words, such as:

    correct horse battery staple

Passphrases are excellent passwords because they are easy to remember (for you)
and hard to guess (for others):

[![xkcd: Password Strength](https://imgs.xkcd.com/comics/password_strength.png "xkcd: Password Strength")](https://xkcd.com/936)

## Why you need a wordlist

A strong passphrase consists of *randomly* selected words.
However, if you make up the words yourself, those words might not be as random
as you think.
Using words like the name of your spouse, dog, soccer club or favourite boy
band, are easy to guess for others and will result in insecure passphrases.

To create truly random and therefore secure passphrases, you should use either
a *passphrase generator* or
[Diceware](https://theworld.com/~reinhold/diceware.html).
Both methods require a list of words to pick words from.
A typical diceware wordlist consists of 6^5 = 7,776 words.

## About this wordlist

This repository provides a list of **7,776 german words** in these formats:

- [wordlist-german.txt](wordlist-german.txt): original german wordlist with correct capitalization
- [wordlist-german-lowercase.txt](wordlist-german-lowercase.txt): lowercase version of the wordlist above
- [wordlist-german-diceware.txt](wordlist-german-diceware.txt): the actual german diceware wordlist made from
  the lowercase wordlist

Each word has been manually checked to be **familiar and office-friendly**
(not vulgar, offensive, religious or with negative connotations).
The words also meet these formal conditions:

- 4 to 8 characters long
- contains english letters only (no german special characters like umlauts)
- a known noun, verb or adjective in its basic form

## Where do all those words come from?

All words have been taken from the digital german dictionary
[DWDS](https://www.dwds.de/):

> DWDS – Digitales Wörterbuch der deutschen Sprache.
> Das Wortauskunftssystem zur deutschen Sprache in Geschichte und Gegenwart,
> hrsg. v. d. Berlin-Brandenburgischen Akademie der Wissenschaften,
> <https://www.dwds.de/>, abgerufen am 17.01.2022.
