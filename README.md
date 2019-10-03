# PNG Fixer

This project has been made to learn about the PNG Format. It is by no mean robust, and the code is complete garbage.

However, it may be used to help and assist in forensics CTF challenges. Currently, it automatically fixes the PNG magic bytes, chunk length and CRC. When a typo is encountered in a chunk type field, it prompts the user to enter the correct value.

## Usage

The project runs in python 3. It can be run as follows :

    python3 png_fixer.py corrupted.png output.png
