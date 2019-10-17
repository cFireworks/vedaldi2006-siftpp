# SIFT算法详解
[SIFT算法详解](https://cloud.tencent.com/developer/article/1343067)

# SIFT++ Fork

This is a fork of [SIFT++](http://www.robots.ox.ac.uk/~vedaldi/code/siftpp.html), a lightweight C++ implementation of the SIFT detector and descriptor, written by [Andrea Vedaldi](http://www.robots.ox.ac.uk/~vedaldi).

The original README can be found in `README.txt`. **See also `NOTICE.txt`**

## Usage

For compiling, use CMake (`sudo apt-get install cmake`):

    $ git clone https://github.com/davidstutz/vedaldi2006-siftpp.git
    $ cd vedaldi2006-siftpp
    $ cmake .
    $ make
    # Run sift on the provided example image:
    $ ./sift --verbose --output data/img3 --save-gss data/img3.pgm

All options can be seen in `sift-driver.cpp`; all keypoint descriptors will be saved to `data/img3.key`.

## License

For license information see `NOTICE.txt`. **Note that permission to use, modify and distribute SIFT++ is only granted for educational and research purposes!** Further, note that a patent has been issued for the SIFT algorithm (quoted from [http://www.robots.ox.ac.uk/~vedaldi/code/siftpp.html](http://www.robots.ox.ac.uk/~vedaldi/code/siftpp.html)):

> This software embodies a method for which the following patent has been issued: "Method and apparatus for identifying scale invariant features in an image and use of same for locating an object in an image," David G. Lowe, US Patent 6,711,293 (March 23, 2004). Provisional application filed March 8, 1999. Asignee: The University of British Columbia.
