File Compressor using Huffman Coding
id	
K24-2500	Yahya Riaz Khan
K24-2582	Syed Afzaal Shah
Introduction
This project implements a File Compressor and Decompressor using Huffman Coding — a greedy algorithm that compresses data by assigning shorter binary codes to frequent characters and longer codes to rare ones. It demonstrates the practical use of data structures like trees, heaps, and maps in DSA.
Description
Read a text file and calculate the frequency of each character.
Build a Huffman Tree using a min-heap.
Generate binary Huffman codes for each character.
Encode and compress the file using these codes.
Store data for decompression and reconstruct the original file.
Display compression ratio and performance.
Data Structures Used
Data Structure	Use
Map	Store character frequencies
Min-Heap	Build Huffman Tree
Binary Tree	Represent encoding structure
String / Vector	Store Huffman codes
File Streams	Handle file I/O
