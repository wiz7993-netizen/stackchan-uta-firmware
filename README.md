# stackchan-uta-firmware

OTA distribution binaries for a custom StackChan (xiaozhi-esp32 fork) firmware.
The device checks a version pointer at boot and downloads the app image listed there.
Flash layout: app-only image, write at 0x20000 (OTA slot compatible).

- xiaozhi-v2.2.8.bin — md5 2e942edd35b955f34c9aea815c20086b
