+++
title = "Verify my Digital Signature"
aliases = ["verify", "signed-message", "check"]
  name = "Palinuro"
+++

If you receive a digitally signed message from me, or from someone who claims to be me, this page will guide you to check whether the signature is valid or not.

Need to send me an encrypted message instead? visit the [Encrypt Page](../encrypt/).

## Sample Message:

The following is how a digitally signed message looks like. You can use it to test the signature verification systems described below.


```
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA512



hello, i am Lorenzo Faletra, trust whatever i say in this message
only if this signature is either valid and generated with my key.

also make sure this message was originally intended for you
and it has not been re-used on a different context to fool you.

consider my signatures valid only if applied on messages
containing explicit reference to their context to prevent
signature-reuse of short and generic messages.

this specific message is a sample that i made for my personal website
and, unless i change it, you should find the original content here
https://palinuro.dev/verify

every other use of this message should be considered invalid and suspicious.

-----BEGIN PGP SIGNATURE-----

iQIzBAEBCgAdFiEEWBedOTCXhoOq+BJIbsyHWWXressFAmCuN4kACgkQbsyHWWXr
essuORAAwAwuxtRUqVF2TpLxHOIN2omNamo8iLmGx1iV0HVAS79GJuFAfos5gH7w
IiYs+eOd4yZYLrJdoJGZCmDUySvtTM/A59daR8IISBYLYGheZN9qknUUe7WMkPNS
TooiJ48WhP2RwZ5IoGY3tOuLNwLmKKXKgv8c3OXtG7Yh+WNvsOcPdRclSrjRozdE
ZSKvMJs13t6ahiGlhp/WVbxlC8TS5e4Tyz46T+9jmJRxAzkORt4VFHVXH+fPq3GR
d8xXrBBXpIk8RYiP1wBg5o3mj7JxZftDQ1BnUXumXqxNGNbTXtAGeKVsrPFpcU3e
zkFEetnYaSzjrHen0rYFsVXlGc0cCZsSv2VEV58daDh7a1kVNiwBJ8HnVQ7ELAoc
p2/Yur0deatCoteBbMlV4yaHJ31sBY9iAUmnGsEeOO5VACq12r068y/94sODz39p
MBxosoH7GKrPyLOFa/zhb3GEPNiuKZyvB4CwdYXPJcdVaB2FzFtHFR44F3och5LR
MpUYRrwuTDGX8uwvsPagtud58UoJtWJAotwU0wfKx5wSM5eeP/znxD/6iMk34LHh
w6VF+qgWkBLA69JduXT8ovBBOaDvz58tMNHVHBPUkP+w0nQL8AGBVF1RBD30YKfe
cqf0INsi03HDXRs3Wf+Uofn/TqBOWUoJXjDB7fTl3dIHUY2y1AY=
=2BWe
-----END PGP SIGNATURE-----
```

# Method 1: Keybase
Keybase is the easiest platform to make cryptography accessible to everyone.
With keybase you can encrypt and decrypt messages using open protocols.

You can use the keybase website to check whether my digital signature is valid or not.

DOWNSIDES (for those who care): The website is hosted on Amazon AWS and the backend is not open source.

![Keybase encryption](../img/keybase-signature.jpg)

[Open Keybase verification page](https://keybase.io/verify#palinuro)


# Method 2: GPG
GNU Privacy Guard is the most advanced secure communication and signature software available, and uses the PGP standard, which is what i personally trust the most.

DOWNSIDES: It is very hard to use if your are not a techie

![GPG encryption](../img/gpg-signature.jpg)

STEPS

1. Get my GPG public key from [https://keybase.io/palinuro/pgp_keys.asc](https://keybase.io/palinuro/pgp_keys.asc)
2. Install the [official GPG client](https://gnupg.org/), or [another PGP client](https://www.openpgp.org/software/)
3. Import my key
4. Verify if the signature on my messages is valid
