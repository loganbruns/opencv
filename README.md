### OpenCV: Open Source Computer Vision Library

[![Gittip](http://img.shields.io/gittip/OpenCV.png)](https://www.gittip.com/OpenCV/)

#### What this is?

This is a CentOS 7 build of OpenCV-3.0.0-beta-725

#### How was it built?

mkdir release
cd release
cmake -DBUILD_SHARED_LIBS=OFF -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local ..
make
make package
