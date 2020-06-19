# Todoist Colors

Color aliases for Todoist API. Look [here](https://developer.todoist.com/sync/v8/#miscellaneous) for more details. For strange colors we used [this](http://chir.ag/projects/name-that-color/#158FAD) web resource.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```
pip install todoist-colors
```

## Usage

```
# Access specific color -> int mapping
import todoist_colors
todoist_colors.RED

# or a single dict w/ all the mappings
import todoist_colors
for name, value in todoist_colors.colors.items():
...     print("{} => {}".format(name, value))
... 
HIBISCUS => 30
RED => 31
ORANGE => 32
YELLOW => 33
EARLS_GREEN => 34
LIGHT_GREEN => 35
GREEN => 36
DOWNY => 37
EASTERN_BLUE => 38
DODGER_BLUE => 39
CORNFLOWER => 40
BLUE => 41
VIOLET => 42
PURPLE => 43
LIGHT_ROSE => 44
ROSE => 45
MONA_LISA => 46
GRAY => 47
LIGHT_GRAY => 48
SORREL_BROWN => 49
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](./LICENSE.md)
