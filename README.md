# Huffman Coding Python Implementation

This Python implementation of Huffman Coding is based on the explanation provided in the YouTube video: [Huffman Coding Python Implementation](https://youtu.be/JCOph23TQTY) and the accompanying blog article by [Bhrigu Srivastava](https://bhrigu.me/blog/2017/01/17/huffman-coding-python-implementation/).

## Overview

Huffman Coding is a compression algorithm that assigns variable-length codes to input characters based on their frequencies, with more frequent characters receiving shorter codes. This implementation includes `compress` and `decompress` functions.

## Demo Video and Blog Article

- [YouTube Video](https://youtu.be/JCOph23TQTY)
- [Blog Article](https://bhrigu.me/blog/2017/01/17/huffman-coding-python-implementation/)

## Getting Started

Follow these steps to test and run the program:

1. Save or clone this repository.
2. The repository includes a sample text file of size 715kB.
3. Run the Python code `useHuffman.py` to compress and decompress the sample file.
   - Open your terminal and run: `python3 useHuffman.py`
4. The above command will perform compression and decompression on the `sample.txt` file provided. Both the compressed and decompressed files will be present at the same location.
5. To run the code for compression of any other text file, edit the `path` variable in the `useHuffman.py` file.

**Note:** For now, the `decompress()` function is to be called from the same object from which the `compress()` function was called, as the encoding information is stored in the data members of the object only.

## Example Usage

```python
# Import the HuffmanCoding class
from huffman_coding import HuffmanCoding

# Create an instance of HuffmanCoding
huffman = HuffmanCoding()

# Compress the input file
huffman.compress("sample.txt")

# Decompress the compressed file
huffman.decompress()





Creadit to @https://github.com/bhrigu123/huffman-coding
