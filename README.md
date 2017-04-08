# tte

tte (tiny text editor) is a terminal based text editor written in C from scratch, trying to be very minimalistic and dependency independent. 

This project was mainly created for educational purposes, so is very commented!

Thanks to [antirez](http://antirez.com) for inspiring me with his project `kilo`.

## Installation

### Compiling
```
git clone https://github.com/GrenderG/tte.git
cd tte/
make
sudo cp tte /usr/local/bin/
```

### One liner
```
sudo sh -c "curl -LJO https://github.com/GrenderG/tte/releases/download/0.0.1/tte -o /usr/local/bin/tte && chmod +x /usr/local/bin/tte"
```

## Usage
```
tte [file_name]
```
If you are planning to use special characters like (á, é, í, ó, ú, ¡, ¿, ...) you must use `ISO 8859-1` encoding in your terminal. See [this issue](https://github.com/GrenderG/tte/issues/2) for more info.

## Keybindings
```
Ctrl-Q : Exit
Ctrl-F : Search text (ESC, arrows and enter to interact once searching)
Ctrl-S : Save
```

## Current supported languages
* C (`*.c`, `*.h`)
* C++ (`*.cpp`, `*.hpp`, `*.cc`)
* Java (`*.java`)
* Bash (`*.sh`)
* Python (`*.py`)
* PHP (`*.php`)
* JavaScript (`*.js`, `*.jsx`)

## Images
![First screenshot](https://raw.githubusercontent.com/GrenderG/tte/master/images/scr_1.png)
