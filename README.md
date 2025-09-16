# 📱 Xiaomi Garnet Vendor Files


## 🚀 Installation Guide

This repository contains proprietary files that are typically integrated into an Android Open Source Project (AOSP) or custom ROM source tree. Follow these steps to set up the vendor files for your build environment:

1.  **Navigate to Your AOSP Source Directory**:
    ```bash
    cd /path/to/your/aosp/source
    ```

2.  **Clone the Repository**:
    Clone this repository into the `vendor/xiaomi/garnet` path within your AOSP source tree.
    ```bash
    git clone https://github.com/sudo-joaopuser/proprietary_vendor_xioami_garnet vendor/xiaomi/garnet


### Building Your ROM

After setting up your device tree and vendor files, you can proceed with the standard AOSP build process:

```bash
source build/envsetup.sh
lunch lineage_garnet-userdebug
mka bacon # To build the ROM
```

## 🤝 Credits
* AdarshGrewall
* Omar (Coptain)
