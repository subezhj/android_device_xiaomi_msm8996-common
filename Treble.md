Treble TODO list:

-sed android.hidl.manager dependent libs to use libhidltransport.so
-port libinit_msm8996(init/) to work with treble(/vendor)
-make ConfigPanel,Doze and pocketmode compatible with AOSP APIs intead of Lineage APIs and move them to /vendor/apps
-make overlays as RRO and move them to vendor/overlay/

Final goal: remove BOARD_VNDK_RUNTIME_DISABLE:=true definition to enable full-versioned-vndk treble
