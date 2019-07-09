## List of Compression Algorithms and its use case

### SMAZ
   The Smaz short string compression algorithm by Salvatore Sanfilippo.
   This port currently only supports ASCII characters and will throw an exception when trying to compress non-ascii characters.
   Smaz is a simple compression library suitable for compressing very short strings with 4 to 100 characters.  
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



## Bemchmarking 
