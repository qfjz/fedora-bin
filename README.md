# fedora-bin

System: Fedora Linux 40

- chezmoi-2.49.1
- joshuto-0.9.8
- lazygit-0.42.0
- lf-r32
- starship-1.19.0

Weryfikacja plików binarnych za pomocą klucza PGP

- Nazwa: qfjz-sign
- Fingerprint: 9A22 DB48 1E21 A7D0 0855  D9BC FDCF 7EF2 02C9 9D13
- ID: fdcf7ef202c99d13

Pobranie klucza

```
gpg --keyserver keyserver.ubuntu.com --receive-keys fdcf7ef202c99d13
```

Import i weryfikacja

```
gpg --import qfjz.gpg
gpg --verify starship.sig

gpg: Good signature from "qfjz-sign" [unknown]
```
