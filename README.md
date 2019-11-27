# scripts
scripts that I found useful for my work

## 2json:
A python script to convert a file with JSON contet into a better formatted, reading-friendly txt file.
```bash
usage: 2json [-h] -s input_file [-o output_file]

optional arguments:
  -h, --help            show this help message and exit
  -s input_file, --source input_file
                        The source file to be converted
  -o output_file, --output output_file
                        The output file to be stored. Default will be stored
                        as out.json
```

## up2mac
A shell script to upload a file to MAC
**_NOTE:_** The IP Address of the MAC should be avilable and stored in a file
```bash
Usage: up2mac <FILE> [REMOTE_FOLDER]
       <FILE> The file to upload to MAC
       [REMOTE_FOLDER] The remote directory to upload on MAC; if not given, will upload to Downloads
```

## viewjson
A python script to read JSON formatted HTTP respones from a URL
```bash
usage: viewjson [-h] url

positional arguments:
  url         The URL to read

optional arguments:
  -h, --help  show this help message and exit
```

## viewlog
A shell script to read larg log files from web
```bash
usage: viewlog <url>
```
