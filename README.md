# go-interpreter

## About go-interpreter

This project was made following and learning with https://interpreterbook.com/ by the great Thorsten Ball.

go-interpreter is a personal and learn focused project, it's objective is to gain more in depth knowledge about GO and how interpreters work:
* How to build a REPL.
* How to structure a GO project.
* Set basics rules about a "new" programming language.
* How to tokenize, parse and evaluate strings.
* How to setup environments to save variables.
* How to make different variables work.
* Know how ASTs work inside an interpreter.

### Built with

[![Go][Go]][Go-url]


## Features

This project is built for the monkey programming language that has:
      	    __,__
   .--.  .-"     "-.  .--.
  / .. \/  .-. .-.  \/ .. \
 | |  '|  /   Y   \  |'  | |
 | \   \  \ 0 | 0 /  /   / |
  \ '- ,\.-"""""""-./, -' /
   ''-' /_   ^ ^   _\ '-''
       |  \._   _./  |
       \   \ '~' /   /
        '._ '-=-' _.'
           '-----'

- C-like syntax
- variable binding
- integers, booleans, arrays and hash map.
- first-class and higher-order functions.
- Simple CLI interface


## Installation

Make sure you have **Go 1.22+** installed.

```bash
git clone https://github.com/AgustinPagotto/go-interpreter.git
cd go-interpreter
go build -o go-interpreter .
  ```
## Usage

Basic command sintax
```bash
./go-interpreter
  ```
This will present to you a prompt where you can define variables, make calculations and much more!!

### Examples

```bash
>> let h = [1,2,3,4]
>> h
[1, 2, 3, 4]
>> h[1]
2
```

```bash
>> let a = {1:"hello",2:15};
>> a
{1:hello,2:15}
>> a[1]
hello
>> a[2]
15
```


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Go-url]: https://go.dev/
[Go]: https://img.shields.io/badge/golang-00ADD8?&style=plastic&logo=go&logoColor=white
[sqlite-url]: https://sqlite.org/
[sqlite]: https://img.shields.io/badge/SQLite-07405E?style=flat&compact=true&logo=sqlite&logoColor=white


