# fedora-bin

System: Fedora Linux 40

- chezmoi-2.49.1
- joshuto-0.9.8
- lazygit-0.42.0
- lf-r32
- skim-0.10.4
- starship-1.19.0

Weryfikacja plików binarnych za pomocą klucza PGP

```
curl -o qfjz.gpg https://github.com/qfjz.gpg
```

lub

```
curl -o qfjz.gpg "https://keyserver.ubuntu.com/pks/lookup?op=get&search=0xfdcf7ef202c99d13"
```

Klucz można też wyszukać używając nazwy `qfjz-sign`

- https://keyserver.ubuntu.com/pks/lookup?search=qfjz-sign&fingerprint=on&op=index

```
gpg --import qfjz.gpg
gpg --verify starship.sig

gpg: Good signature from "qfjz-sign" [unknown]
```
