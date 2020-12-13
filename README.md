# Simple Bash Write script

This is a simple bash script for taking input from a file or a pipe (stdin), and write it to an output file.  
It's meant to show how you would handle command line options with getopts.

## Usage

```
bash-write <options> <path to input file> --output <path to output file>

Options:

--help|-h     Shows usage and a list of options
--output|-o   Required. Accepts a filename as argument, writes the data onto that file
--debug|-d    Prints every line before executing it, useful for when something unexpected happens
--force|-f    If output file already exists, overwrite it, THIS WILL DELETE ALL DATA ON THE OUTPUT FILE!
```

## License
[GNU General Public License v3.0](https://github.com/granitba/simple-bash-write/blob/master/LICENSE)
