# Intro to password hashing

## Define the term “hashing”.

Hashing is the process of converting data like a password, into a fixed-length string of characters using a mathematical function,

## Explain to a non-technical friend what a hash function does to a password.

A hash function is like a magical blender that turns your password into a unique, scrambled code, so even if someone gets the code, they can't figure out what your original password was.

# bcrypt overview

## What does it mean to ‘salt’ a password?

Salting a password is like adding extra secret spices to your secret recipe, making it even more unique and harder for anyone else to replicate or guess your original ingredients

## What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?

A hacker would need to gain access to the system or database where the salt strings are stored alongside the hashed passwords in order to find the salt string for your passwords.

References:

https://auth0.com/blog/hashing-passwords-one-way-road-to-security/

https://danboterhoven.medium.com/why-you-should-use-bcrypt-to-hash-passwords-af330100b861




