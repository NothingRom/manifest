NothingRom by Team Nothing Download the source

I will be using PureNexus Repo as my starting base. all credits to Nate Beans and his team.
This will just be my version of the rom.

Please read the Nothing building instructions before proceeding.

Initialize:

Create the build directory :

$ mkdir ~/dev $ mkdir ~/dev/NothingRom $ cd ~/dev/NothingRom 

$ repo init -u https://github.com/NothingRom/manifest.git -b mm

$ repo sync

Start Building

After the sync is finished, please read the instructions from the Android site on how to build.

. build/envsetup.sh 

lunch

choose your build type in build number

make bacon -j8
