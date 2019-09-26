# Atom-OS Project 2019 #

[![Download Atom-OS Project](https://img.shields.io/sourceforge/dt/atom-os-project.svg)](https://sourceforge.net/projects/atom-os-project/files/latest/download)

<p align="center"> 
<img src="https://github.com/iamsaalim/manifest/blob/ten/snippets/Atomlogo.png" > 
</p>


### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Atom-OS-Project/manifest -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
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
