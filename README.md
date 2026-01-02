# Initializing files
```
git clone https://github.com/derveror/local_manifest.git -b udc_suzuran_qpr3 .repo/local_manifests
```
# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
