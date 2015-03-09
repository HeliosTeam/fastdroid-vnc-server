mkdir -f build
export INSTALLDIR=~/workbench/gcc-4.8.2/arm
export PATH=$INSTALLDIR/bin:$PATH
export TARGETMACH=arm-none-linux-gnueabi
export BUILDMACH=i686-pc-linux-gnu
export CROSS=/home/kevin/Working/ElinkMe/android-ndk-r10d/toolchains/arm-linux-androideabi-4.9/prebuilt/linux-x86_64
export CC=${CROSS}/bin/arm-linux-androideabi-gcc
export LD=${CROSS}/bin/arm-linux-androideabi-ld
export AS=${CROSS}/bin/arm-linux-androideabi-as
export AR=${CROSS}/bin/arm-linux-androideabi-ar
./configure --prefix=${CROSS} 
