Repo init the manifest in your directory :

repo init -u git://github.com/omnirom-kumquat/manifest.git -b omnirom-kumqua
repo sync
. build/envsetup.sh
lunch X
make -Jx
