# Setup-Linux

set up git-ssh
```
ssh-keygen -t ed25519 -C "thanhphan10397@gmail.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

cat ~/.ssh/id_ed25519.pub
Then select and copy the contents of the id_ed25519.pub file, and paste to
New SSH key on github setting
```
