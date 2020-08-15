# Playary Music for Franz

An unofficial Franz recipe for [Playary Music](https://app.playary.com/) a great Spotify alternative.

## Installing

### Windows

With git and PowerShell:

```sh
mkdir $env:APPDATA\Franz\recipes\dev\
git clone git@github.com:Retriev3r/franz-recipe-playary.git $env:APPDATA\Franz\recipes\dev\franz-recipe-playary
```

With Explorer:

1. Download the `franz-recipe-playary.zip` from github.  Extract it to its own folder (`franz-recipe-playary`).
2. Open `%appdata%/Franz/recipes/dev/`.  The `dev` folder may not exist, so go ahead and create it.
3. Copy the `franz-recipe-playary` folder into the plugins directory.
4. Reload Franz.

### Mac

```sh
mkdir ~/Library/Application\ Support/Franz/recipes/dev/
git clone git@github.com:Retriev3r/franz-recipe-playary.git ~/Library/Application\ Support/Franz/recipes/dev/franz-recipe-playary
```

### Linux

```sh
mkdir ~/.config/Franz/recipes/dev
git clone git@github.com:Retriev3r/franz-recipe-playary.git ~/.config/Franz/recipes/dev/franz-recipe-playary
```
