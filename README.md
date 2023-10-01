# Huffman Encoding and Decoding in C++
This C++ program demonstrates Huffman encoding and decoding. Huffman coding is a popular algorithm used for data compression. It works by assigning variable-length codes to input characters, with shorter codes for more frequent characters, to reduce the overall size of the data.

Usage
To use this program, follow these steps:

To encode a file named input.txt and save the encoded data to encoded.bin, use the following command:

```shell
./main.exe huffman input.ext encoded.ext
```
To decode the encoded.ext file and save the decoded data to decoded.txt, use the following command:

```shell
./main.exe huffman encoded.ext.hk decoded.ext.hd
```
## Implementation Details
* The program first reads the input file to determine character frequencies.
* It then builds a Huffman tree based on these frequencies.
* For encoding, it creates a mapping of characters to their Huffman codes.
* For decoding, it uses the Huffman tree to decode the encoded data.
* The encoded data is stored as binary data in the output file.

## File Structure
main.cpp: The main source code file that contains the Huffman encoding and decoding logic.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Author
[FO Latulip]
