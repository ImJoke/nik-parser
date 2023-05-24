# Installing
```sh
git clone https://github.com/ImJoke/nik-parser
mv nik-parser/nik_parse.py .
rm -rf nik-parser
```
# Usage
```sh
python nik_parse.py -n <nik>
```
# Example
```sh
python nik_parse.py -n 1234567891234567
```
# Help output
```sh
$ python parse_nik.py --help
usage: nik_parse.py [-h] -n NIK

NIK Parser

options:
  -h, --help         show this help message and exit
  -n NIK, --nik NIK  Nomor Induk Kependudukan
 ```
# Supported version
 - Python ≥ 3.x.x
# TODO
- [ ] Recreate this code (more better)
# References
- [bachors](https://github.com/bachors/nik_parse.js "Modified from bachors")
