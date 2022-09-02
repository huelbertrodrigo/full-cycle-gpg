# full-cycle-gpg

Full Cycle - GPG Test

## Commands

List GPG keys

```
gpg --list-secret-key --keyid-form LONG
```

Generate GPG key

```
gpg --full-generate-key
```

Export public key

```
gpg --armor --export 0000000000000000
```

Git config

```
git config --global user.signingkey 0000000000000000
```

```
git config --global commit.gpgsign true
```

```
git config --global tag.gpgsign true
```

```
git config --global gpg.program "C:\Program Files (x86)\GnuPG\bin\gpg.exe"
```
