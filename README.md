# 03.02-challenge
This weeks challenge covers Javascript

## Description
The goal of this assignment was to ensure that the password generator worked correctly according to the instructions.
The issue that was found in the source code was that there was not a function that was called in the beginning of the 
code to ensure that the prompts ran upon clicking the generate button.


## Code Source

[source-code](../UNCC-VIRT-FSF-PT-07-2023-U-LOLC/03-JavaScript/02-Challenge/Main))

# Page Link



# View

[Webpage screenshot 1](./assets/images/finished-SS.png)


## Usage

This application can be used to generate a random password. The password can span from 8-128 characters in length.
The character set includes numbers, letters and special characters


## License

MIT License

Copyright (c) [2023] [Tyler J. Stubbs]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISINqG FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Features

button to kickoff a series of prompts
password generator based on prompt feedback


## Tests

The testing method for this application was to click the generate button. Upon clicking the generate
button, the prompts were then selected. I ran this test multiple times to ensure that only the prompts 
that were selected would show in the password generated (i.e. click ok to uppercase letters, lowercase letters but 
cancel when asked do I want special characters)