# Template
Template for applications in Java

### how to make git use ssh to push your files

- Generating the key ( Linux )

```sh
ssh-keygen -t ed25519 -C "carnegiejunior@gmail.com" -f ~/.ssh/carnegie_ed25519
```
```sh
eval "$(ssh-agent -s)"
```
```sh
ssh-add ~/.ssh/id_ed25519
```

```sh
cat ~/.ssh/carnegie_ed25519.pub
```

- Testing the connection
```sh
ssh -vT git@github.com
```
