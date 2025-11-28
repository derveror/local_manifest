# Initializing files
```
git clone https://github.com/derveror/local_manifest.git -b 18.1_PLE .repo/local_manifests
```
# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
