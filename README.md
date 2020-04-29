# pfx2pwd - Password protect pfx files

Apply password to pfx certificats using openssl

## Usage
```
usage: pfx2pwd [[-o output][-p password][-h help]] input

-o | --out-pfx		Output password protected pfx file. If not provided this will be pfx2pwd_<input>
-p | --password		Password for the output pfx file
--in-password		Password for the input pfx file
-h | --help		This help text
```
