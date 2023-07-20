# Image-Compression-using-Quad-Trees

This library implements an image compression algorithm that is based on quadtrees. It can radically reduce the size of images while still preserving detail.

Features:
1.Compressing images and rendering the simplified version
2.Encoding the compressed data to a compact binary representation
3.Decoding the binary and reconstructing the image

The algorithm works by starting with an empty image and incrementally adding detail where it is important. At the beginning the compressed image is filled with the average color of the original image. Then, it recursively subdivides the regions that have the most detail into 4 quads that each have the average color of the area they represent in the original image.
