# C++ Style Guide
## Table of contents:
1.  [Naming](#Naming)
    1.  [Variable names](#Variable-names)
    2.  [Function names](#Function-names)
    3.  [Constants](#Constants)
    4.  [Type names](#Type-names)
    5.  [File names](#File-names)
2.  [Formatting](#Formatting)
    1.  [Spaces vs. Tabs](#Spaces-vs.-Tabs)

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
All uppercase with underscoresw:
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
