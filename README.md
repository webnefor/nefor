# nefor
The tool can crypt file

-m: regime mode: [encrypt & decrypt]

-f: entering file: [target.exe]

-t: entering trash of file: (in developing)

-k: your password to crypt: [12345]

-h: HELP

How to compile:

    cmake . && cmake --build .
  
example for encrypting:

    ./nefor -f target.exe -t target.exe -k 12345 -m encrypt 

example for decrypting:

    ./nefor -f target.exe -t target.exe -k 12345 -m decrypt

    
