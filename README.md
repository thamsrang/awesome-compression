## List of Compression Algorithms and its use case

### SMAZ
   The Smaz short string compression algorithm by Salvatore Sanfilippo.  
  __Use Case__
   - Smaz is a simple compression library suitable for compressing very short strings with 4 to 100 characters.  
   - This port currently only supports ASCII characters and will throw an exception when trying to compress non-ascii characters.  
  __Library__
   - [C](https://github.com/antirez/smaz)
   - [Java](https://github.com/RyanAD/jsmaz)
   - [Ruby](https://github.com/peterc/rsmaz)

###  Run-Length Encoding (RLE)
   Mainly when a single value is repeated for many times. As in the case of the presented data it is compressed to 80%, but "ababababab" would "compress" to 200% the original!
   
###  zlib/DEFLATE
   zlib compressed data are typically written with a gzip or a zlib wrapper.  

__Library__
- [C](https://github.com/madler/zlib)

### gzip
   gzip is a file format and a software application used for file compression and decompression. 

__Library__

### bzip2

__Library__


### brotli
   Brotli is a data format specification for data streams compressed with a specific combination of the general-purpose LZ77 lossless compression algorithm, Huffman coding and 2nd order context modelling.  
   Best for js and css files.

__Library__

### xz
   xz is a lossless compression program and file format which incorporates the LZMA/LZMA2 compression algorithms.These are the same compression formats used by the 7-Zip program and its command-line version p7zip. 

__Library__

### lzop
   lzop is a free software file compression tool which implements the LZO algorithm and is licensed under the GPL.

__Library__
- [C](https://www.lzop.org/)

## Bemchmarking 
