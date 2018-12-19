### sublime3-settings
---
#### Remove Sublime Text 3 User folder
```
rm -rf ln -s ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```

#### Then
```
mkdir -p ~/.dotfiles/sublime/
git clone https://github.com/kodelint/sublime3-settings.git User
ln -s ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User ~/.dotfiles/sublime/User
```
#### Restart Sublime
