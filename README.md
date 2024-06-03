# Lua-Vectors

This is a simple Lua library for working with two dimensional vectors. I built this for use in my own projects, and will add to it as I go.

## Usage
To use the library, copy the [Vector.lua](Vector.lua) file into the same directory as the script that needs it, then use the require function to pull it in:
```lua
require(Vector)
```

To create a new vector, use the new function:
```lua
local v = Vector:new(x, y)
```

To compute the dot product of two vectors, use the Dot_Product function:
```lua
Vector.Dot_Product(vector1, vector2)
```

There are also functions to normalize the vector, get the magnitude, and convert it into a table:
```lua
local magnitude = v:magnitude()
local normalVector = v:normalize()
local tableVector = v:to_table()
```
