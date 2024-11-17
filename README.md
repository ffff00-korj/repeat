# "repeat" command

Need to send something 1000 or more times and don't want to write script for it? Use my repeat command!

### Requirements

* Python 3.*

### Installation
```bash
# clone
git clone https://github.com/ffff00-korj/repeat
# copy somewhere in PATH. For example:
cp repeat/repeat ~/.local/bin/
# try repeat something
repeat 3 "I repeat!"
I repeat!
I repeat!
I repeat!
# DONE!
```
### Examples

#### Like a normal terminal utility (if you have /bin/python3)
```bash
./repeat 3 "echo Hello, World!"
Hello, World!
Hello, World!
Hello, World!
```
#### Or with python
```bash
python3 ./repeat 3 "echo Hello, World!"
Hello, World!
Hello, World!
Hello, World!
```
#### Wrong usage
```bash
./repeat "echo Hello, World!" 3
ERROR:root:first argument should be a number.
```
