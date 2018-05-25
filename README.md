# YubiKey Git Commit Signature Demo

This is just a simple demo

# How to sign your code via YubiKey

1. Generate a GPG key on your YubiKey
2. Tell git about your GPG key
   `git config --global user.signingkey <my key id>`
3. enable commit signing by default
   `config --global commit.gpgsign true`
4. Profit!
