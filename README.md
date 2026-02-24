# Password Generator

A simple Python program that generates secure passwords based on user preferences.

## Features
- Generate multiple passwords
- Custom password length
- Optional inclusion of:
  - digits (0–9)
  - lowercase letters (a–z)
  - uppercase letters (A–Z)
  - symbols (!#$%&*+-=?@^_)
- Option to exclude ambiguous characters (il1Lo0O)

## How it works
1. The user selects password settings.
2. The program builds a pool of allowed characters.
3. Passwords are generated randomly using the selected character set.
