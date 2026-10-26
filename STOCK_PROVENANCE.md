# Stock refresh provenance

Source: Xiaomi 14T OS3.0.303.0.WNERUXM fastboot archive
`degas_ru_global_images_OS3.0.303.0.WNERUXM_20260811.0000.00_16.0_ru_ccf2257d38.tgz`.

41 missing native dependencies were added from this ROM. 1,374 listed inputs
were refreshed and extraction fixups applied, including the rebased IMS APK
patch. 384 existing compatibility inputs absent from this dump were retained;
these have not been verified on hardware. Generated build files were recreated
with LineageOS lineage-23.2 extract-utils.

Firmware images match this archive. The old preloader and logo remain as
unreferenced repository files and are excluded from the generated OTA list.

Use with the matching device and kernel changes. Full Android/Soong compilation,
VINTF checking and device boot testing remain required.
