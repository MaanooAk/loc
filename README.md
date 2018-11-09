# loc

**loc** is a script for storing and switching working directories across sessions and terminals.

## Usage

- `loc`: select and cd to a stored path
- `loc <path>`: store the given path and select and cd to a stored path

There also options for other operations:

```
loc [clear] [remove <path>] [add <path>] [go]
```

## Install

```
git clone https://github.com/MaanooAk/loc.git
cd loc
sudo make install
```

Additionally in order for the `cd` commands to work, an alias must be defined

```
alias loc=". loc"
```

### Dependecies

The script requeires the [dmenu](https://tools.suckless.org/dmenu/) tool
