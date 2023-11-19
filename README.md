# Pig Manager
A simple pretty printer for Pig Latin scripts because the default one looks really bad! Runs your pig commands for you, intercepts the output and prints it for you in a delightful manner.
<br />
**feel free to raise issues**

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
<img width="244" alt="Screenshot 2023-11-20 at 1 08 03 AM" src="https://github.com/MinatoNamikaze02/pig-manager/assets/85065053/d801d375-cb97-4659-8f88-33611f8b9b7d">

## License
This project is licensed under the MIT License.
