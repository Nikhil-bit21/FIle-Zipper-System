for compressing :
g++ encode.cpp main.cpp -o main {encode , main -> files to be executed } , {-o main -> (o)output file will be named as main } 
{to run that output file main you can use ./main}

to compressing something -> ./main inputFile.txt compressedFile.huf {name of file to be compressed with the extension of .txt , after compressing name of file with extension .huf}


for decompressing :
g++ decode.cpp main.cpp -o main

to decompress something -> ./main compressedFile.huf outputFile.txt {name of compressed file with extension .huf , file name after decompressing the compressed file with extension .txt}





