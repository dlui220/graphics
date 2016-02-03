#Computer Graphics Notes

**2/2/16**

*Image File Formats*

1. Types
   - Compressed
      - smaller
	  - png, jpg, gif
   - Uncompressed
      - no degradation
	  - raw pixel information
	  - tiff, bmp, raw
   - Lossy
      - loses original information
	  - not all compressed formats are lossy
      - jpg
   - Lossless
      - retains all data
	  - tiff, bmp, raw, png (compressed and lossless)
   - Raster
      - defined by a grid of pixels
	  - cannot be scaled up well
   - Vector
      - list of shapes in the image


2. Compression
   - **Run-length encoding**
      - 12 bytes: BBBBBRRRYYYY
	  - 6 bytes: 5B3R4Y
	  - *Only efficient when a lot of identical pixels are adjacent*
	  - 5 bytes: GYRYG
	  - 10 bytes: 1G1Y1R1Y1G
   


