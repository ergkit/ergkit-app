# Getting started

Assuming you've installed Xcode, cloned this repository and are sitting in its root directory, here's one way to get what you need on Mac:

```bash
brew install nodenv
nodenv init
echo 'eval "$(nodenv init -)"' >> ~/.profile
nodenv install 12.3.1
npm install -g expo-cli
nodenv rehash
expo start
```
