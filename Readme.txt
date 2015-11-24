To initialize your local repository, use this command:

repo init -u https://github.com/Ant-Droid/android_manifest.git -b 600
Then to sync source, use this command:

repo sync
After syncing is done, use these commands to build:

For UserDebug Builds
1.) . build/envsetup.sh
2.) brunch xxxx    xxxx= device name aka shamu

For User Builds
1.) . build/envsetup.sh
2.) breakfast
3.) Pick Device
4.) mka bacon
