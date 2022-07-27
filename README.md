# speedstarscompiler

`speedstarscompiler` is a bytecode serializer developed by `speedstarkawaii`, which compiles lua scripts into `luau bytecode`, then it gets decompiled from `luau_load`.

When you type a script for example -> `print'Hi'` it will be converted into hex-like bytecode which then is ran by the `luau_load` function and then spawned by `spawn`.

# how to use this?

compile in **release, x86** (usually takes about 30 seconds to compile).

pipe name is 'speedstar' which can be **changed** in the main cpp file.

thank you for the compiler -> https://github.com/roblox/luau/
