# Ploigos Reference Applications - PGP Public Keys

Purpose of this repository is a makeshift public key repository for all the public keys
used on the SOPS encrypted config files in the various repositories in https://github.com/ploigos-reference-apps.

## Use

```bash
gpg --import pgp-public-keys/*
gpg --import pgp-public-keys/robots/*
```

## Adding Your Key

If you feel you need access to decrypt the SOPS encrypted config files in https://github.com/ploigos-reference-apps then do a pull request to this repository with your public key. If you dont know why you would need that power, then you probably don't need it.
