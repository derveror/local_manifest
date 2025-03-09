# Initializing files
```
git clone https://github.com/derveror/local_manifest.git -b rosy15 .repo/local_manifests
```
# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
# Clone kernel sources
```
git clone https://github.com/aepranata/kernel_xiaomi_rosy.git -b 15  --recurse-submodule kernel/xiaomi/rosy
```
# Clone clang-atiga
```
git clone https://gitlab.com/aepranata/atiga-clang.git -b 13.x prebuilts/clang/host/linux-x86/clang-atiga
```
