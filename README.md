# German Diceware Wordlist for Random Passphrases

**Work in Progress**

## What are passphrases anyway?

A [Passphrase](https://en.wikipedia.org/wiki/Passphrase) is a password made
up of multiple words, such as:

    correct horse battery staple

Passphrases are excellent passwords because they are easy to remember (for you)
and hard to guess (for others):

[![xkcd: Password Strength](https://imgs.xkcd.com/comics/password_strength.png "xkcd: Password Strength")](https://xkcd.com/936)

## How are passphrases created?

A strong passphrase consists of *randomly* selected words.
**So do not make up the words yourself, since those words might not be as random
as you think!**
Using words like the names of family members, your partner, pet, hobby, etc.
are easy to guess for others and will result in insecure passphrases.

A better approach is to use a **passphrase generator**.
Another method to generate random passphrases is
[Diceware](https://en.wikipedia.org/wiki/Diceware), invented by
[Arnold Reinhold](https://theworld.com/~reinhold/diceware.html):
You simply roll five dice to pick a random word from a Diceware wordlist.
Repeat this process until you have the desired number of words.

In either case you need a wordlist.

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
