* OpenCore EFI hackintosh BigSur kllisre x79p

- xeon 2696 v2
- 16gb ddr3 ecc samsung
- 8gb ddr3 ecc kllisre/samsung
- Nvidia gtx 970 pny (only dvi works durign instalation)
- ssd sata liteon 256gb

* using EFI base ivy bridge [Olarila](https://www.olarila.com/topic/25111-hackintosh-efi-folders-with-opencore-mod/).

* using USB tool box to build usb kext [usb tool box] (https://github.com/USBToolBox/tool/releases/tag/0.2).
	** usb 2.0 does not work without usb tool box mapping, and usb 3.0 works just with flashdrive  

* using GenSMBIOS with arg MacPro 6.1 "lixeirinha" [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).

* using ProperTree to edit config.plist. use clear snapshot to write news add kexts.

* using boot-args "ipc_control_port_options=0 amfi_get_out_of_my_way=0x1 ngfxcompat=1 ngfxgl=1 nvda_drv_vrl=1 -v npci=0x3000 -no_compat_check"

* using balenaEtcher to flash Big Sur ISO
