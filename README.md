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

set up node-nvm manager

install node manager: nvm
```
sudo apt install curl
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
nvm --version
nvm install 16.14.0
node --version
npm --version
```
