# CAF ANDROID-9.0.0 #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/inderpreetsinghb/caf_platform_manifest -b LA.UM.7.6.2.r1-08100-89xx.0

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```
