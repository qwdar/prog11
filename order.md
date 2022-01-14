1)go to dependes
 cd ./dependes
2)give execution rules
 chmod +x ./*
make
 sudo make
3)go to root derectory
 cd ../
4)give execution rules
 chmod +x ./*
5)change directory to share
 cd ./share
6) give chmod +x ./* 
7)go to root directory and issue:
./autogen.sh # or sudo bash autogen.sh

./configure --disable-dependency-tracking --enable-tests=no --with-gui=auto --without-miniupnpc --enable-glibc-back-compat --prefix=$PWD/depends/x86_64-pc-linux-gnu LDFLAGS="-static-libstdc++"

make check










#####################################################################################################################################
./configure --with-incompatible-bdb --with-gui=auto
make check


./configure --prefix=$PWD/depends/aarch64-linux-gnu --enable-glibc-back-compat --enable-reduce-exports LDFLAGS=-static-libstdc++

./configure --prefix=$PWD/depends/arm-linux-gnueabihf --enable-glibc-back-compat --enable-reduce-exports LDFLAGS=-static-libstdc++
make HOST=arm-linux-gnueabihf

./configure --prefix=$PWD/depends/x86_64-pc-linux-gnu --enable-glibc-back-compat --enable-reduce-exports LDFLAGS=-static-libstdc++


./configure --disable-dependency-tracking --enable-tests=no --with-gui=auto --without-miniupnpc --enable-glibc-back-compat --prefix=$PWD/depends/x86_64-pc-linux-gnu LDFLAGS="-static-libstdc++"





https://download.qt.io/archive/qt/5.9/5.9.7/qt-opensource-linux-x64-5.9.7.run

chmod +x qt-opensource-linux-x64-5.9.7.run

./qt-opensource-linux-x64-5.9.7.run
