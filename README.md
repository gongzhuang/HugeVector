# HugeVector
when we process large scale point cloud files,we use std::vector to store points. but the memory of compute is limited. so we decide to build
a new type of vector that based on std::vector but can store their data in disk file when the size of data is too large to store in memory.
when the size of data is under limition number , the behavoir of the vector is the same of std::vector.
we keep the same interface as std vector ,so you can replace std vector anywhere with HigeVector.
