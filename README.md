# Initializing files
```
git clone https://github.com/derveror/local_manifest.git -b akari_vic_qpr2 .repo/local_manifests
```
# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
