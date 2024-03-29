+++
title = "Encryption"
aliases = ["crypt", "encrypt"]
  name = "Palinuro"
+++

If you need to send me a confidential message, there are several ways you can safely do that.

Need to verify my digital signature? visit the [Verify Page](../verify/) instead.


# [Keybase](https://keybase.io/encrypt#palinuro) - the simple way
Keybase is the easiest platform to make cryptography accessible to everyone.
With keybase you can encrypt and decrypt messages using open protocols.

You can use the keybase website to encrypt a message with my key and send me the encrypted message however you want, even by email, text message or by publicly publishing it on your facebook wall, and only i will be able to decrypt and read its content.

DOWNSIDES (for those who care): The website is hosted on Amazon AWS and the backend is not open source.

![Keybase encryption](../img/keybase.jpg)

## Steps
1. [Open My Keybase encryption page](https://keybase.io/encrypt#palinuro)
2. Write your message
3. Encrypt it
4. Send me the encrypted message via email, text message, or wherever you want.



# GPG - the hard way
GNU Privacy Guard is the most advanced secure communication and signature software available, and uses the PGP standard, which is what i personally trust the most.

DOWNSIDES: It is very hard to use if your are not a techie

![GPG encryption](../img/gpg.jpg)

## Steps

1. Get my GPG public key from [https://keybase.io/palinuro/pgp_keys.asc](https://keybase.io/palinuro/pgp_keys.asc)
2. Install the [official GPG client](https://gnupg.org/), or [another PGP client](https://www.openpgp.org/software/)
3. Import my key
4. Encrypt your message using my key as target


# Protonmail and Tutanota
If you have a Protonmail or Tutanota account, you can send me encrypted messages by using my Prontonmail and Tutanota email accounts.

my accounts are:

* palinurosec@pm.me
* palinuro@tutanota.com

my @palinuro.dev and @palinuro.me emails are also hosted on protonmail (at least by now)

DOWNSIDES: it works only with protonmail->protonmail or tutanota->tutanota communications. The email protocol security is broken at its core, and inter-provider email exchange is NOT safe unless both sides use custom end-to-end encryption on top of it, with not-so-practical techniques as shown above

![Protonmail GPG encryption](../img/protonmail.jpg)

## Steps

If you have received an encrypted email from my Protonmail or Tutanota accounts, please follow the step below

1. Follow the link in your email
2. Use the password we have agreed on, or call me to get one.


# Other methods

## Signal

I use Signal for quick and secure confidential messages, audio and video calls.

Signal is an amazing alternative to Telegram and WhatsApp. It does encryption right and it is one of the best communication applications developed so far.

DOWNSIDES: You can only text me on Signal if you have my phone number (which i don't give out very easily).


## Telegram Secret Chats

I use telegram a lot since it hosts many public communities that slowly replaced their IRC counterparts.

Telegram is fine for public conversation, but it is one of the worst pieces of software for private and confidential communication.

Anyways it supports **Secret Chats** with end-to-end encryption

DOWNSIDES: secret chats are optional, and the whole telegram experience is designed to push people into using the *default* unencrypted alternative. Moreover Telegram decided to adopt their very own cryptographic algorhythm, which is not considered a best-practice in the crypto world, and its strength is not the best one.
