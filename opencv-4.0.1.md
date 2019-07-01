# opencv 4.0.1 install 
source : https://www.learnopencv.com/install-opencv-4-on-ubuntu-18-04
source : https://webnautes.tistory.com/1186

# error-solveOpenCV-4.0.1  fatal error: boostdesc_binboost_128.i: No such file or directory

source :   https://dhhwang89.tistory.com/15

### boostdesc

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/34e4206aef44d50e6bbcd0ab06354b52e7466d26/boostdesc_lbgm.i > 0ae0675534aa318d9668f2a179c2a052-boostdesc_lbgm.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/34e4206aef44d50e6bbcd0ab06354b52e7466d26/boostdesc_bgm.i > 0ea90e7a8f3f7876d450e4149c97c74f-boostdesc_bgm.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/34e4206aef44d50e6bbcd0ab06354b52e7466d26/boostdesc_binboost_064.i > 202e1b3e9fec871b04da31f7f016679f-boostdesc_binboost_064.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/34e4206aef44d50e6bbcd0ab06354b52e7466d26/boostdesc_bgm_bi.i > 232c966b13651bd0e46a1497b0852191-boostdesc_bgm_bi.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/34e4206aef44d50e6bbcd0ab06354b52e7466d26/boostdesc_bgm_hd.i > 324426a24fa56ad9c5b8e3e0b3e5303e-boostdesc_bgm_hd.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/34e4206aef44d50e6bbcd0ab06354b52e7466d26/boostdesc_binboost_128.i > 98ea99d399965c03d555cef3ea502a0b-boostdesc_binboost_128.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/34e4206aef44d50e6bbcd0ab06354b52e7466d26/boostdesc_binboost_256.i >  e6dcfa9f647779eb1ce446a8d759b6ea-boostdesc_binboost_256.i

 

### vgg

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/fccf7cd6a4b12079f73bbfb21745f9babcd4eb1d/vgg_generated_120.i >  151805e03568c9f490a5e3a872777b75-vgg_generated_120.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/fccf7cd6a4b12079f73bbfb21745f9babcd4eb1d/vgg_generated_64.i >  7126a5d9a8884ebca5aea5d63d677225-vgg_generated_64.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/fccf7cd6a4b12079f73bbfb21745f9babcd4eb1d/vgg_generated_80.i >  7cd47228edec52b6d82f46511af325c5-vgg_generated_80.i

wget https://raw.githubusercontent.com/opencv/opencv_3rdparty/fccf7cd6a4b12079f73bbfb21745f9babcd4eb1d/vgg_generated_48.i >  e8d0dcd54d1bcfdc29203d011a797179-vgg_generated_48.i

source: 

https://dhhwang89.tistory.com/15

# In file included from /home/boumsoo/opencv/opencv-4.0.1/modules/python/src2/cv2.cpp:109:0:

/home/boumsoo/opencv/opencv-4.0.1/build/modules/python_bindings_generator/pyopencv_generated_include.h:21:10: fatal error: opencv2/quality/qualitybase.hpp: No such file or directory

include "opencv2/quality/qualitybase.hpp"

    cd ..
    python ./modules/python/src2/gen2.py ./build/modules/python_bindings_generator ./build/modules/python_bindings_generator/headers.txt
    cd build
    sudo make install...

source : https://stackoverflow.com/questions/52353883/opencv-installation-error-no-such-file-or-directory-pyopencv-generated-include


