# HuffmanEncoding
The purpose of this project is to use huffman encoding in file compression or decompression.



File compression compacts the contents of a file (or bunch of files, as when you turn in a zip file of this homework) to save disk space and transfer time. Some compression schemes (like jpeg for images) are lossy, in that they throw away information. Other compression schemes (like zip) are lossless — you get back exactly what you put in, but it's just stored in a more compact manner.

One of the earliest schemes for lossless file compression was invented by Huffman (as a term project!). Instead of using 7 bits to encode each character, as ASCII does, it uses a variable-length encoding of characters. Frequently occurring characters get shorter code words than infrequently occurring ones. (A code word is the sequence of 0's and 1's used to encode the character.)

Huffman encoding gives the smallest possible fixed encoding of a file. A fixed encoding means that a given letter is represented by the same code wherever it appears in the file. Some more recent schemes that do better than Huffman's are adaptive, which means that how a letter is encoded changes as the file is processed.


Extra class has a module that uses only one tree to compress and decompress. Boundary cases are included as screenshots to prove the code works in every instance. I compressed and decompressed the US Constitution!
