# "repeat" command

Need to send something 1000 or more times and don't want to write script for it? Use my repeat command!

### Requirements

* Python >= 3.0

### Installation

Clone somewhere
```bash
git clone https://github.com/ffff00-korj/repeat
```
Copy somewhere in PATH. For example:
```bash
cp repeat/repeat ~/.local/bin/
```
Try repeat something
```bash
repeat 3 echo I repeat!
```
```
I repeat!
I repeat!
I repeat!
```

### Examples

#### Like a normal terminal utility (if you have /bin/python3)
```bash
repeat 3 echo Hello, World!
```
```
Hello, World!
Hello, World!
Hello, World!
```
#### Or with python
```bash
python3 repeat 3 echo Hello, World!
```
```
Hello, World!
Hello, World!
Hello, World!
```
#### Or on Windows

One of two should work
```bash
python repeat 3 echo Hello, World!
```
```bash
py repeat 3 echo Hello, World!
```
```
Hello, World!
Hello, World!
Hello, World!
```
#### Wrong usage
```bash
repeat echo Hello, World! 3
```
```
ERROR:root:first argument should be a number.
```
