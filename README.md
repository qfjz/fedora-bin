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
gpg --import qfjz.gpg
gpg --verify starship.sig

gpg: Good signature from "qfjz-sign" [unknown]
```
