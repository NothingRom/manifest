NothingRom by Team Nothing Download the source

Please read the Nothing building instructions before proceeding.

Initialize:

Create the build directory :

$ mkdir ~/dev $ mkdir ~/dev/NothingRom $ cd ~/dev/NothingRom Init core trees without any device/kernel/vendor :

$ repo init -u https://github.com/NothingRom/android.git -b mm

$ repo sync

Start Building

After the sync is finished, please read the instructions from the Android site on how to build.

. build/envsetup.sh 

lunch

choose your build type in build number

make bacon -j8
