# ddrumPlus-utils

A simple set of tools to build EPROM sample images for the Clavia ddrum Plus! drum synthesizer

## Tools :
 - ddrumff : the ddrum File Formater, takes a .wav file and outputs a binary file you have to "pack" with ddrumimg
 - ddrumimg :  the ddrum image builder, takes four ddrum binary files and "packs" them into an EPROM image
  
## Usage :
 - ddrumff [inputFile] [outputFile]
    - converts only the first 8192 samples of the input .wav file to ddrum plus! sample format
  
 - ddrumimg [inputFile1] [inputFile2] [inputFile3] [inputFile4] [outputFile-
    - packs the four input sample files into an EPROM image ready to be flashed to a memory chip

## Dependencies :
 - python3

## Notes :
 - these tools have not been checked with real hardware yet...
