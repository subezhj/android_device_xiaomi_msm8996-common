### Treble TODO list:

- Vendor-move remaining blobs (both gemini and msm8996-common)
- Hex edit blobs to use /vendor path instead of /system path
- Vendor-move vendor_lineage parts
- Port libinit_msm8996(init/) to work with treble(/vendor)
- Make ConfigPanel,Doze and pocketmode compatible with AOSP APIs intead of Lineage APIs and move them to /vendor/apps
- Make overlays as RRO and move them to vendor/overlay/

#### Final goal:

- Remove BOARD_VNDK_RUNTIME_DISABLE:=true definition to enable full-versioned-vndk treble
