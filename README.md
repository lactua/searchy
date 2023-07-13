# searchy
Searchy is a python package that allows you to use google search from your terminal

# Installation
```
python -m pip install searchy
```

# Usage
```
searchy [-h] [--tld TLD] [--lang LANG] [--tbs TBS] [--safe {on,off}]
               [--num NUM]
               query

positional arguments:
  query            Google Search query

options:
  -h, --help       show this help message and exit
  --tld TLD        Top level domain
  --lang LANG      Results language
  --tbs TBS        Time limits ("qdr:(h/d/m)")
  --safe {on,off}  Safe search (on/off)
  --num NUM        Result count
```
