# loc

**loc** is a script for storing and switching working directories across sessions and terminals.

![loc_screenshot](https://user-images.githubusercontent.com/6997990/48280067-28a72680-e45b-11e8-8e03-d876c764619c.png)

## Usage

- `loc`: select and cd to a stored path
- `loc <path>`: store the given path and select and cd to a stored path

There also options for other operations:

```
loc [clear] [remove <path>] [add <path>] [go]
```

## Install

```bash
git clone https://github.com/MaanooAk/loc.git
cd loc
sudo make install
```

Additionally in order for the `cd` commands to work, an alias must be defined

```bash
alias loc=". loc"
```

### Dependencies

The script requires the [dmenu](https://tools.suckless.org/dmenu/) tool
