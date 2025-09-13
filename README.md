# ec-luart-uiextension

This project provides various datetime ui objects for [LuaRT](https://www.luart.org/).
It has been designed to simplify and improve the creation of graphical user interfaces with the LuaRT ui module.

[![LuaRT 2.1.0](https://badgen.net/badge/LuaRT/2.1.0/blue)](https://github.com/samyeyo/LuaRT)

## Features

The module provides the following extension objects:

| Name | Description |
| --- | --- |
| DayLabel | Represents a label control that display a day. |
| DaynameLabel | Represents a label control that display a dayname. |
| DaynumberLabel | Represents a label control that display a daynumber. |
| MonthLabel | Represents a label control that display a month. |
| MonthnameLabel | Represents a label control that display a monthname. |
| MonthnumberLabel | Represents a label control that display a monthnumber. |
| WeeknumberLabel | Represents a label control that display a weeknumber. |
| YearLabel | Represents a label control that display a year. |

More detailed descriptions and usage examples can be found in the docs folder.

## Installation

1. Create a folder called "ecluart" in your application.
1. Copy the "uidatetime.lua" file into this folder.

```text
[application]
|
|----ecluart
|   |
|   |----uidatetime.lua
|   |----...
|
|----app.wlua
```

## Usage

The extension module can be loaded using the function *require()*:

```lua
local uidatetime = require("ecluart.uidatetime")  
```

## License

Copyright (c) 2023 by esferatec.
It is open source, released under the MIT License.
See full copyright notice in the LICENSE.md file.
