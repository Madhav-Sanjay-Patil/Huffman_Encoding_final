# HuffmanCoder

A JavaScript implementation of **Huffman Coding** for file compression and decompression, using a custom binary heap for priority queue operations.

## 📌 Features
- **Compression**: Encodes text into a binary format using Huffman coding to reduce size.
- **Decompression**: Reconstructs the original text from the compressed data.
- **Binary Heap Integration**: Efficient frequency-based priority queue using a max-heap.
- **Custom Serialization**:
  - `stringify()` – Encodes the Huffman tree into a string for storage.
  - `destringify()` – Decodes the Huffman tree back into its structure.
- **Tree Display**: Visual representation of the Huffman tree with node connections.
- **Compression Stats**: Calculates and displays the compression ratio.


## ⚙️ How It Works
1. **Frequency Calculation** – Counts occurrences of each character.
2. **Heap Construction** – Inserts nodes into a max-heap by frequency (negative for max behavior).
3. **Tree Building** – Combines lowest-frequency nodes until one tree remains.
4. **Encoding** – Generates binary mappings for each character.
5. **Compression** – Converts binary string to byte characters with padding info.
6. **Decompression** – Rebuilds the tree and decodes the binary back to text.


## ⚙️ How It Works
1. **Frequency Calculation** – Counts occurrences of each character.
2. **Heap Construction** – Inserts nodes into a max-heap by frequency (negative for max behavior).
3. **Tree Building** – Combines lowest-frequency nodes until one tree remains.
4. **Encoding** – Generates binary mappings for each character.
5. **Compression** – Converts binary string to byte characters with padding info.
6. **Decompression** – Rebuilds the tree and decodes the binary back to text.
