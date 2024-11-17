# "repeat" command

Need to send something 1000 or more times and don't want to write script for it? Use my repeat command!

### Requirements

* Python 3.*

### Examples

#### Like a normal terminal utility
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
#### Won't work. Argument are positional
```bash
./repeat "echo Hello, World!" 3
ERROR:root:first argument should be a number.
```
