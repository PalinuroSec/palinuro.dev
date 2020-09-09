+++
title = "Verify a signed message"
aliases = ["verify", "signed-message", "check"]
  name = "Palinuro"
+++

if you received a digitally signed message from me, or from someone who claims to be me, tese are the steps to verify if my message is valid.

Need to send me an encrypted message? visit the [Crypt Page](../encrypt) instead.

## Example signed message from my key:
```
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

hello, i am Lorenzo Faletra, trust whatever i say in this message
only if this signature is either valid and generated with my key.

also make sure this message was originally intended for you
and it is not being re-used by someone to fool you.

consider my signatures valid only if applied on messages
containing explicit reference to their context to prevent
signature-reuse of short and generic messages

this specific message is a sample that i made for my personal website
and, unless i change it, you should find the original content here
https://palinuro.dev/verify

every other use of this message should be considered invalid and suspicious
-----BEGIN PGP SIGNATURE-----

iQIzBAEBCAAdFiEEWBedOTCXhoOq+BJIbsyHWWXressFAl78dV4ACgkQbsyHWWXr
esuPvRAAssPYX6RjVH6hCBbChvfr20GKv8QIyKoQlC8SBnFZtayMRCTz1gETgHe0
mvJaVx6gFZkSe53VdANgk62zhBxbNIML70E9wH8SwGbLCLgTcvsBRbFDqB9jdjiz
rQL+gnIlJ//4oN+wnDy3fh39celYVcm3ZVkJVwJ/ceVKOZVEhdYndTP7K5dtV3mZ
82RZA9oVuGDj8nd0X3YRnYGBhv1oOJaVbIZi6tlI2ZC76TW6UFmkuXvdJJMhMuHF
3A5wOGBXBlm5zEuenHwNNvGMJcqclY+QIvqHLkoCZwOdK5EcReziH3W+I++RayxO
9T44ME8c1/up0QdN9pG7hsPIxGjiUktagQqH/9LqgnAmsmZBVpssedgDqar4KTM6
VdqJkUbvCtJuDM7O2gTZdxcd6AA3+z6X8h6cQ/K1LChodC72SlwRn9Y5zueUUkjh
yH/+0Z2uw/dxm91yeaipZeskleIEYWHFCulQv8FTUh0G1KKtn7GMtZvoZvVw7r+W
u5M8GH8jyv1ecUpyyDEPfYD3LolTvbqhydmyT6e5IBooj9hbKKRctNTGv+sw3pG2
CNshvDD+VRLdL9rh4XiAZLpkNVAKYSLVfixPPAOmg300bHzh5nJ+mfS40HXIpwTu
BQl5mF0/RWiu8zJ73PoiivLNfzPDvloqR63HHaOefY0wcqrxUpk=
=kbAk
-----END PGP SIGNATURE-----
```

# Keybase
Keybase is an interesting company that offers a very easy to use platform to make cryptography accessible to everyone

DOWNSIDES: centralized platform hosted on Amazon AWS and proprietary backend (but fortunately open source clients)

![Keybase encryption](../img/keybase-signature.jpg)

[Open Keybase verification page](https://keybase.io/verify#palinuro)


# GPG
GNU Privacy Guard is the most advanced secure communication and signature software available, and uses the PGP standard, which is what i personally trust the most.

DOWNSIDES: it may be hard to use if your are not a tech guy

![GPG encryption](../img/gpg-signature.jpg)

STEPS

1. Get my GPG public key from [https://deb.parrot.sh/misc/palinuro.gpg](https://deb.parrot.sh/misc/palinuro.gpg)
2. Install the [official GPG client](https://gnupg.org/), or [another PGP client](https://www.openpgp.org/software/)
3. Import my key
4. Verify if the signature on my messages is valid