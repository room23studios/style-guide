# C++ Style Guide
## Table of contents:
1.  [Naming](#naming)
    1.  [Variable names](#variable-names)
    2.  [Function names](#function-names)
    3.  [Constants](#constants)
    4.  [Type names](#type-names)
    5.  [File names](#file-names)
2.  [Formatting](#formatting)
    1.  [Spaces vs. Tabs](#spaces-vs-tabs)

## Naming
### Variable names
For variables, we use camelCase:
```c++
int gold;
int healthPoints;
string reallyLongVariableNameM8;
string datBoi;  // o shit waddup
// etc...
```

### Function names
Like a variable: camelCase:
```c++
bool toBeOrNotToBe();
int getQuantityOfDeadMemes();
```

### Constants
All uppercase with underscores:
```c++
const int WINDOW_WIDTH = 640, WINDOW_HEIGHT = 480;
const int DAYS_IN_A_WEEK = 7;
```

###Type names
For type names we use Pascal case:
```cpp
class MyNewClass;
struct Vector2f;
enum CharacterClass;
// etc...
```

###File names
Filenames should be all lowercase and can include underscores:
```
foo_bar.cpp
```

##Formatting
###Spaces vs. Tabs
Tabs for indentation (4 spaces width), spaces for aligning.

```c++
if (q || p) {
    cout << "a string";
}
```
