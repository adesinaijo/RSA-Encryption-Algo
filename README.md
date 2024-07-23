# RSA Encryption Demo

This project demonstrates the implementation of RSA encryption and decryption using Python. The code includes functions for generating RSA keys, encrypting and decrypting messages, and encoding/decoding messages.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
  - [extended_euclid](#extended_euclid)
  - [extended_euclid_iterative](#extended_euclid_iterative)
  - [modinv](#modinv)
  - [rsa_gen_public_private_keys](#rsa_gen_public_private_keys)
  - [rsa_encrypt](#rsa_encrypt)
  - [rsa_decrypt](#rsa_decrypt)
  - [encode](#encode)
  - [decode](#decode)
  - [is_prime](#is_prime)
  - [gen_big_prime_less_than](#gen_big_prime_less_than)
  - [have_fun_rsa](#have_fun_rsa)
  - [split_into_smaller_messages](#split_into_smaller_messages)


## Installation

No special installation is required. Just ensure you have Python 3.x installed on your system.

## Usage

To run the RSA encryption demo, simply execute the script. For example:

```bash
python rsa_demo.py

The script will encode, encrypt, decrypt, and decode a sample message.
Functions
extended_euclid

python

def extended_euclid(a, b):

Recursive implementation of the Extended Euclidean Algorithm. Returns the greatest common divisor of a and b, and the coefficients of Bézout's identity.
extended_euclid_iterative

python

def extended_euclid_iterative(a, b):

Iterative implementation of the Extended Euclidean Algorithm. Returns the greatest common divisor of a and b, and the coefficients of Bézout's identity.
modinv

python

def modinv(a, m):

Calculates the modular inverse of a modulo m using the Extended Euclidean Algorithm.
rsa_gen_public_private_keys# RSA Encryption Demo

This project demonstrates the implementation of RSA encryption and decryption using Python. The code includes functions for generating RSA keys, encrypting and decrypting messages, and encoding/decoding messages.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
  - [extended_euclid](#extended_euclid)
  - [extended_euclid_iterative](#extended_euclid_iterative)
  - [modinv](#modinv)
  - [rsa_gen_public_private_keys](#rsa_gen_public_private_keys)
  - [rsa_encrypt](#rsa_encrypt)
  - [rsa_decrypt](#rsa_decrypt)
  - [encode](#encode)
  - [decode](#decode)
  - [is_prime](#is_prime)
  - [gen_big_prime_less_than](#gen_big_prime_less_than)
  - [have_fun_rsa](#have_fun_rsa)
  - [split_into_smaller_messages](#split_into_smaller_messages)
- [License](#license)

## Installation

No special installation is required. Just ensure you have Python 3.x installed on your system.

## Usage

To run the RSA encryption demo, simply execute the script. For example:

```bash
python rsa_demo.py

The script will encode, encrypt, decrypt, and decode a sample message.
Functions
extended_euclid

python

def extended_euclid(a, b):

Recursive implementation of the Extended Euclidean Algorithm. Returns the greatest common divisor of a and b, and the coefficients of Bézout's identity.
extended_euclid_iterative

python

def extended_euclid_iterative(a, b):

Iterative implementation of the Extended Euclidean Algorithm. Returns the greatest common divisor of a and b, and the coefficients of Bézout's identity.
modinv

python

def modinv(a, m):

Calculates the modular inverse of a modulo m using the Extended Euclidean Algorithm.
rsa_gen_public_private_keys

python

def rsa_gen_public_private_keys(p, q):

Generates RSA public and private keys given two prime numbers p and q.
rsa_encrypt

python

def rsa_encrypt(message, n, e):

Encrypts a message using RSA encryption with public key (n, e).
rsa_decrypt

python

def rsa_decrypt(encrypted, n, d):

Decrypts a message using RSA decryption with private key (n, d).
encode

python

def encode(message):

Encodes a message into a numeric format suitable for RSA encryption.
decode

python

def decode(int_message):

Decodes a numeric format back into the original message.
is_prime

python

def is_prime(n, verbose=False):

Checks if a number n is prime. If verbose is set to True, prints additional information.
gen_big_prime_less_than

python

def gen_big_prime_less_than(upper_bound):

Generates a large prime number less than upper_bound.
have_fun_rsa

python

def have_fun_rsa(upper_bound, message):

Main function to demonstrate RSA encryption and decryption. Generates primes, keys, encodes the message, and handles encryption and decryption.
split_into_smaller_messages

python

def split_into_smaller_messages(message, n):

Splits a large message into smaller parts suitable for RSA encryption.


python

def rsa_gen_public_private_keys(p, q):

Generates RSA public and private keys given two prime numbers p and q.
rsa_encrypt

python

def rsa_encrypt(message, n, e):

Encrypts a message using RSA encryption with public key (n, e).
rsa_decrypt

python

def rsa_decrypt(encrypted, n, d):

Decrypts a message using RSA decryption with private key (n, d).
encode

python

def encode(message):

Encodes a message into a numeric format suitable for RSA encryption.
decode

python

def decode(int_message):
# RSA Encryption Demo

This project demonstrates the implementation of RSA encryption and decryption using Python. The code includes functions for generating RSA keys, encrypting and decrypting messages, and encoding/decoding messages.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
  - [extended_euclid](#extended_euclid)
  - [extended_euclid_iterative](#extended_euclid_iterative)
  - [modinv](#modinv)
  - [rsa_gen_public_private_keys](#rsa_gen_public_private_keys)
  - [rsa_encrypt](#rsa_encrypt)
  - [rsa_decrypt](#rsa_decrypt)
  - [encode](#encode)
  - [decode](#decode)
  - [is_prime](#is_prime)
  - [gen_big_prime_less_than](#gen_big_prime_less_than)
  - [have_fun_rsa](#have_fun_rsa)
  - [split_into_smaller_messages](#split_into_smaller_messages)
- [License](#license)

## Installation

No special installation is required. Just ensure you have Python 3.x installed on your system.

## Usage

To run the RSA encryption demo, simply execute the script. For example:

```bash
python rsa_demo.py

The script will encode, encrypt, decrypt, and decode a sample message.
Functions
extended_euclid

python

def extended_euclid(a, b):

Recursive implementation of the Extended Euclidean Algorithm. Returns the greatest common divisor of a and b, and the coefficients of Bézout's identity.
extended_euclid_iterative

python

def extended_euclid_iterative(a, b):

Iterative implementation of the Extended Euclidean Algorithm. Returns the greatest common divisor of a and b, and the coefficients of Bézout's identity.
modinv

python

def modinv(a, m):

Calculates the modular inverse of a modulo m using the Extended Euclidean Algorithm.
rsa_gen_public_private_keys

python

def rsa_gen_public_private_keys(p, q):

Generates RSA public and private keys given two prime numbers p and q.
rsa_encrypt

python

def rsa_encrypt(message, n, e):

Encrypts a message using RSA encryption with public key (n, e).
rsa_decrypt

python

def rsa_decrypt(encrypted, n, d):

Decrypts a message using RSA decryption with private key (n, d).
encode

python

def encode(message):

Encodes a message into a numeric format suitable for RSA encryption.
decode

python

def decode(int_message):

Decodes a numeric format back into the original message.
is_prime

python

def is_prime(n, verbose=False):

Checks if a number n is prime. If verbose is set to True, prints additional information.
gen_big_prime_less_than

python

def gen_big_prime_less_than(upper_bound):

Generates a large prime number less than upper_bound.
have_fun_rsa

python

def have_fun_rsa(upper_bound, message):

Main function to demonstrate RSA encryption and decryption. Generates primes, keys, encodes the message, and handles encryption and decryption.
split_into_smaller_messages

python

def split_into_smaller_messages(message, n):

Splits a large message into smaller parts suitable for RSA encryption.

Decodes a numeric format back into the original message.
is_prime

python

def is_prime(n, verbose=False):

Checks if a number n is prime. If verbose is set to True, prints additional information.
gen_big_prime_less_than

python

def gen_big_prime_less_than(upper_bound):

Generates a large prime number less than upper_bound.
have_fun_rsa

python

def have_fun_rsa(upper_bound, message):

Main function to demonstrate RSA encryption and decryption. Generates primes, keys, encodes the message, and handles encryption and decryption.
split_into_smaller_messages

python

def split_into_smaller_messages(message, n):

Splits a large message into smaller parts suitable for RSA encryption.
