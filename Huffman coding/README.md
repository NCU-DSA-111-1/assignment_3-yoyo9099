## How to compile

compile: gcc -o huffman huffcode.c huffman.c huffman.h

## How to encode
./huffman -i testdata1 -o encode -c
## How to decode
./huffman -i encode -o decode -d

