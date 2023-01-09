## How to compile

compile: gcc -o arcd arcd_stream.c arcd.c arcd.h adaptive_model.c adaptive_model.h

## How to encode
./arcd <-e testdata1 | tee encode
## How to decode
./arcd <-d encode | tee decode