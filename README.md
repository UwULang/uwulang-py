# UwULang

The best programming language to take over the world

- π - increment
- π - decrement
- π- go right
- π- go left
- π₯Ί- print char
- π³- get char
- π₯΄- random short
- π- jump to π‘if curr == 0
- π‘- jump back to π if curr != 0

\*definitely not just [brainfuck](https://esolangs.org/wiki/Brainfuck) with extended functionality that you can use [uwufier](https://github.com/Zeyu-Li/uwufier) conversion tool

## Try it Out

Running it by first building it in c with `make` or just use `gcc src/main.c -Wall -std=c99 -o uwulang`. Once you have the binary, if you provide a file as the first arg, it will take the contents of the file and run UwULang on it ie. `./uwulang test/hellOwOrld.uwu`. Otherwise if you provide no args, it will take input from standard in and run UwULang on it.

### Hello World

Print Hello World to the console

```uwu
ππππππππππππππππππππππππππππππππππ‘ππππππππππππ‘πππ‘πππ₯Ίπππππ₯Ίππππππππ₯Ίπ₯Ίππππ₯Ίπππ₯Ίπππ₯Ίππ₯Ίππππ₯Ίπππππππ₯Ίπππππππππ₯Ίππππ₯Ίππππ₯Ί
```

### First 10000 square numbers

Print the first 10000 square numbers

```uwu
ππππππππππππππ‘πππππππππππ‘ππππππππππππππ‘ππππππππππππ‘ππππππ‘ππππππ‘πππππππππ‘ππππππππππ‘πππππππππππππππππππππ‘πππ₯Ίππππππππππ‘ππ‘πππππππππππππππ‘ππππππππππππππππ‘ππππππππππππππππππ‘ππππππ‘π‘πππππππ‘ππ‘ππππ‘ππππ‘
```

## Conversion

If you want to convert bf files to UwU files, note the conversion script in `./pseudocode` does not work, use the [Golang version](https://github.com/Zeyu-Li/uwufier) instead

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
