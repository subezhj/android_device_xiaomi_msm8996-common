Treble TODO list:

-make general implementation
-port libinit_msm8996(init/) to work with treble(/vendor)
-make ConfigPanel,Doze and pocketmode compatible with AOSP APIs intead of Lineage APIs and move them to /vendor/apps
-make overlays as RRO and move them to vendor/overlay/
-run treble's official check-dep script to find violations between system<->vendor and fix violations (especially sed android.hidl.manager libs to libhidltransport.so)
-enable versioned_vndk(BOARD_VNDK_VERSION=current) with enabling temporarily BOARD_VNDK_RUNTIME_DISABLE:=true
-final goal: disable BOARD_VNDK_RUNTIME_DISABLE:=true to enable full-versioned-vndk treble