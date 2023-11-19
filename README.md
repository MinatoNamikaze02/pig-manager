# Pig Manager
A simple pretty printer for Pig Latin scripts because the default one looks really bad! Runs your pig commands for you, intercepts the output and prints it for you in a delightful manner.
<br />

## Installation
To install Pig Pretty Printer, simply use pip:
```bash
pip install pig-manager
```

## Usage
After installation, you can run pig-manager from the command line:
```
pig-manager -f <file> [options]
```

## Options
```
-f, --file_path: Path to the Pig script file.
-dl, --dump_log: Flag to dump error output.
-do, --dump_out: Flag to dump standard output.
-l, --dump_loc: Location to dump output and error files.
```

## Example
A sample of how pig-manager works:
```
pig_pretty_printer -f ./example_script.pig -dl -do -l ./logs
```

## License
This project is licensed under the MIT License.

## PS
if you have any ideas/issues, open a PR :)
