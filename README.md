# Serpent
This project's goal is to implement the Serpent cipher (one of the AES contest competitors) in Python.\
Serpent is a symmetric key block cipher consisting of 32 rounds.\
Single block has a size of 128 bits and the key can be 128, 192 or 256 bits long.

# Status
Finished and closed

# Usage 

Main goal of the project was to implement a signle block encryption and decryption.\
That's why the plain text input has to be exactly 128 bits long.\
Supports text and key in UTF, hex and binary by using corresponding flag.

```
python Serpent.py [-h] (-e | -d) [-tb | -tx] [-ku | -kb] text key

encrypts/decrypts passed text with given key using Serpent Cipher

positional arguments:
  text                text to encrypt/decrypt (default format: UTF)
  key                 key (default format: hexadecimal)

options:
  -h, --help          show this help message and exit
  -e, --encrypt       encryption mode
  -d, --decrypt       decryption mode
  -tb, --text_binary  indicates that text is in binary format
  -tx, --text_hex     indicates that text is in hexadecimal format
  -ku, --key_utf      indicates that key is in UTF format
  -kb, --key_binary   indicates that key is in binary format
```


## Collaborators
Miłosz Kutyła ([GitHub](https://github.com/mkutyla))

Jakub Ossowski ([GitHub](https://github.com/bilevcik))

## Background info
- [ ] [Offical website](https://www.cl.cam.ac.uk/~rja14/serpent.html)
- [ ] [Specification](https://www.cl.cam.ac.uk/~rja14/Papers/serpent.pdf)
- [ ] [Wikipedia page](https://en.wikipedia.org/wiki/Serpent_(cipher))
