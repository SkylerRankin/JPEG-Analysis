# JPEG Decoding
This notebook explores the mechanisms and algorithms at play behind one of the most widely used image file formats. By parsing the file byte by byte, and using a specification reference, we can interpret all of the information stored in the file, and generate the corresponding image without a pre-built image viewer. The primary reference used will be the [International Telecommunication Union Recommendation T.81](https://www.w3.org/Graphics/JPEG/itu-t81.pdf).

All functions are wrtiten using Python with diagrams and full explanations to accompany them. The following are some of the decoding steps dicussed in the notebook:
- Segment Parsing
- Huffman Decoding
- Quantization
- MCU Building

## Usage
With `Jupyter` installed, download `jpeg_decoding.ipynb`, and in its directory run
```sh
> jupyter notebook jpeg_decoding.ipynb
```
The project is also available in pdf format.