
# Cryptonic by pwners

A tool written in python3 for encrypting and decrypting plain text or file using a randomly generated key.



## Features

- Encrypt plain text or any kind of files
- Cannot decrypt text or files without keys
- Need the same key to encrypt and decrypt
- Super secure with AES keys


## Installation

Install Cryptonic

```bash
  git clone https://github.com/Luc1f3r-5705/Cryptonic
  cd Cryptonic
  sudo pip3 install -r requirements.txt
  sudo chmod +x cryptonic.py
  python3 cryptonic.py --help
```
    
## Usage/Examples

Generate a key:

```bash
  python3 cryptonic.py -kN demo
```
Encrypt a plain text using that key:

```bash
  python3 cryptonic.py -kF keys/demo -eT 'Hello WOrld'
```
Encrypt a file using that key:

```bash
  python3 cryptonic.py -kF keys/demo -eF 'demo.txt'
```
Decrypt the encrypted text using the same key:

```bash
  python3 cryptonic.py -kF keys/demo -dT 'gAAAAABi2DK-KFtugLTbvuxDXS-NsUgGN-h1p0ZzYWCgw3wfWGuX8VXYpJ6wThCGVWd9DpyByf8U0_1YtIYAEqoDTfWp6pkpOQ=='
```
Decrypt the encrypted file using the same key:

```bash
  python3 cryptonic.py -kF keys/demo -dF 'demo.txt'
```

## Authors

- [@luc1f3r](https://www.github.com/Luc1f3r-5707)




## 🚀 About Me
I don't know.

