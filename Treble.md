### Treble TODO list:

- Vendor-move remaining blobs (both gemini and msm8996-common)
- Hex edit blobs to use /vendor path instead of /system path
- Vendor-move vendor_lineage parts
- Port libinit_msm8996(init/) to work with treble(/vendor)
- Fix https://github.com/Project-Treble-Mi5/android_device_xiaomi_msm8996-common/blob/lineage-16.0/configpanel/src/org/lineageos/settings/device/KeyHandler.java#L62

#### Final goal:

- Remove BOARD_VNDK_RUNTIME_DISABLE:=true definition to enable full-versioned-vndk treble
