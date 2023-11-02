# CMPS 2200 Recitation 6

## Answers

**Name:**_____Alex Li ____________________

Place all written answers from `recitation-06.md` here for easier grading.

- **d. The trend is roughly incresing.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------

f1.txt    |    1340                 |        826       |0.616417
alice29.txt    |         1039353            |        676351        |0.650742
asyoulik.txt    |           876253          |          606448      |0.692092
grammar.lsp    |            26047         |        17356        |0.666333
fields.c    |              78050       |       56206         |0.720128

- **e. The expected cost of a Huffman encoding for the document is therefore proportional to the number of characters in the document, with the proportionality constant being the height **h** of the Huffman tree, or log⁡2(n)**
- 
  **It is consistant. For any document where all characters in Σ have the same frequency, the Huffman encoding will always produce the same structure of complete binary tree and thus the same cost per character.**
