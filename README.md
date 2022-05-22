## Kitty config

### Installation

1. Clone this Repo (**Recommended**)
```
git clone https://github.com/aprakash/kitty.git ~/.config/
```

2. Choose a theme and create a symlink:

```
cd ~/.config/kitty
ln -s ./kitty/themes/Floraverse.conf ~/.config/kitty/theme.conf
```

3. Add this line to your kitty.conf configuration file:
```
include ./theme.conf
```

#### Change theme using:
```
kitty +kitten themes
```
