# Classical Cryptography
A selection of classical cryptographic techniques for use with the Latin alphabet. 

## Cipher List

* Polybius Square
  * Bifid
  * Trifid
  * Nihlist
* Caesar
* Playfair

## Example Usage

Perform a ROT13 cipher shift on a simple plaintext:
```
python3 crypto.py "HELLO WORLD" -c caesar -e -k 13
```
Decipher polybius coordinate numbers using a standard polybius square:
```
python3 crypto.py 23153131345234423114 -c polybius -d
```
Encrypt a plaintext using the key "HELLO" and a polybius square shifted with the keyword "WORLD":
```
python3 crypto.py HELLOWORLD -c nihlist -k HELLO -s WORLD
```
