# Multi-Band Blending

## Introduction

A Python implementation of multi-band blending.

## Dependencies

* Python 2.7+
* OpenCV 3.2.0

## Run

```
python multi_band_blending.py -f FIRST -s SECOND -o OVERLAP [-S SIGMA] [-l LEVELS]
```

```
  -h, --help            show this help message and exit
  -H, --half            option to blend the left half of the first image and
                        the right half of the second image
  -f FIRST, --first FIRST
                        path to the first (left) image
  -s SECOND, --second SECOND
                        path to the second (right) image
  -o OVERLAP, --overlap OVERLAP
                        width of the overlapped area between two images, even
                        number recommended
  -l LEVELS, --levels LEVELS
                        number of levels of multi-band blending, calculated
                        from image size if not provided
```

## References

http://pages.cs.wisc.edu/~csverma/CS766_09/ImageMosaic/imagemosaic.html

http://www.phototalks.idv.tw/academic/?p=1275

http://blog.csdn.net/real_myth/article/details/52343612

OpenCV samples: opencv/samples/python/lappyr.py
