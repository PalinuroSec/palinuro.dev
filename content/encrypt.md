+++
title = "Encryption"
aliases = ["crypt", "encrypt"]
  name = "Palinuro"
+++

If you need to send me a confidential message, there are several ways you can do that safely.

Need to verify a digital signature from me? visit the [Verify Page](../verify) instead.


# Keybase
Keybase is an interesting company that offers a very easy to use platform to make cryptography accessible to everyone

DOWNSIDES: centralized platform hosted on Amazon AWS and proprietary backend (but fortunately open source clients)

![Keybase encryption](../img/keybase.jpg)

[Open Keybase encryption page](https://keybase.io/encrypt#palinuro)

# GPG
GNU Privacy Guard is the most advanced secure communication and signature software available, and uses the PGP standard, which is what i personally trust the most.

DOWNSIDES: it may be hard to use if your are not a tech guy

![GPG encryption](../img/gpg.jpg)

STEPS

1. Get my GPG public key from [https://deb.parrot.sh/misc/palinuro.gpg](https://deb.parrot.sh/misc/palinuro.gpg)
2. Install the [official GPG client](https://gnupg.org/), or [another PGP client](https://www.openpgp.org/software/)
3. Import my key
4. Encrypt your message using my key as target

# Protonmail and Tutanota
If you have a Protonmail or Tutanota account, it will automatically encrypt your message with my Protonmail or Tutanota keys

DOWNSIDES: it works only with protonmail->protonmail or tutanota->tutanota communications. The email protocol security is broken at its core, and inter-provider email exchange is NOT safe unless both parties use custom end-to-end encryption on top of it, with not-so-practical techniques as shown above

![Protonmail GPG encryption](../img/protonmail.jpg)


my accounts are:

* palinurosec@pm.me
* palinuro@tutanota.com

my @palinuro.dev emails are also hosted on protonmail (at least by now)


# Other methods

## Telegram Secret Chats

I use telegram a lot since it hosts many public communities that slowly replaced their IRC counterparts.

Telegram is fine for public conversation, but it is one of the worst pieces of software for private and confidential communication.

Anyways it supports **Secret Chats** with end-to-end encryption

DOWNSIDES: secret chats are optional, and the whole telegram experience is designed to push people into using the *default* unencrypted alternative. Moreover Telegram decided to adopt their very own cryptographic algorhythm, which is not considered a best-practice in the crypto world, and its strength is not the best one.

## Matrix / Riot Chats

Matrix is an open and federated chat protocol with very advanced features, and it is designed to replace xmpp, irc and other instant messaging systems and offer a common protocol for secure and encrypted communication.

DOWNSIDES: not as widely adopted as it deserves. Some of its clients don't implement the cryptographic parts properly, so make sure to use a client with good crypto implementation, like riot.im
