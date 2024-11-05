# `lshw`

```bash
syenasweta
    description: Notebook
    product: 42763KU
    vendor: LENOVO
    version: ThinkPad W520
    serial: R9PFND0
    width: 64 bits
    capabilities: smbios-2.6 dmi-2.6 smp vsyscall32
    configuration: administrator_password=disabled chassis=notebook family=ThinkPad W520 power-on_password=disabled uuid=a13b6081-51d8-11cb-81d6-a4deda156946
  *-core
       description: Motherboard
       product: 42763KU
       vendor: LENOVO
       physical id: 0
       version: Not Available
       serial: 1ZKBX26C2ED
       slot: Not Available
     *-cpu
          description: CPU
          product: Intel(R) Core(TM) i7-2760QM CPU @ 2.40GHz
          vendor: Intel Corp.
          physical id: 1
          bus info: cpu@0
          version: 6.42.7
          serial: Not Supported by CPU
          slot: CPU
          size: 1216MHz
          capacity: 3500MHz
          width: 64 bits
          clock: 100MHz
          capabilities: lm fpu fpu_exception wp vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ht tm pbe syscall nx rdtscp x86-64 constant_tsc arch_perfmon pebs bts nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq dtes64 monitor ds_cpl vmx smx est tm2 ssse3 cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic popcnt tsc_deadline_timer aes xsave avx lahf_lm epb pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid xsaveopt dtherm ida arat pln pts md_clear flush_l1d cpufreq
          configuration: cores=4 enabledcores=4 microcode=47 threads=8
        *-cache:0
             description: L1 cache
             physical id: 2
             slot: L1-Cache
             size: 64KiB
             capacity: 64KiB
             capabilities: synchronous internal write-through data
             configuration: level=1
        *-cache:1
             description: L2 cache
             physical id: 3
             slot: L2-Cache
             size: 256KiB
             capacity: 256KiB
             capabilities: synchronous internal write-through data
             configuration: level=2
        *-cache:2
             description: L3 cache
             physical id: 4
             slot: L3-Cache
             size: 6MiB
             capacity: 6MiB
             capabilities: synchronous internal write-back unified
             configuration: level=3
     *-memory
          description: System Memory
          physical id: 5
          slot: System board or motherboard
          size: 8GiB
        *-bank:0
             description: SODIMM DDR3 Synchronous 1067 MHz (0.9 ns)
             product: SNY1333S9-2G-ELFE
             vendor: Kingston
             physical id: 0
             serial: 663B2057
             slot: ChannelA-DIMM0
             size: 2GiB
             width: 64 bits
             clock: 1067MHz (0.9ns)
        *-bank:1
             description: SODIMM DDR3 Synchronous 1067 MHz (0.9 ns)
             product: M471B5673GB0-CH9
             vendor: 0000
             physical id: 1
             serial: 0B1225C2
             slot: ChannelA-DIMM1
             size: 2GiB
             width: 64 bits
             clock: 1067MHz (0.9ns)
        *-bank:2
             description: SODIMM DDR3 Synchronous 1067 MHz (0.9 ns)
             product: EBJ21UE8BDS0-AE-F
             vendor: Elpida
             physical id: 2
             serial: 5A151864
             slot: ChannelB-DIMM0
             size: 2GiB
             width: 64 bits
             clock: 1067MHz (0.9ns)
        *-bank:3
             description: SODIMM DDR3 Synchronous 1067 MHz (0.9 ns)
             product: EBJ21UE8BDS0-AE-F
             vendor: Elpida
             physical id: 3
             serial: 5A151861
             slot: ChannelB-DIMM1
             size: 2GiB
             width: 64 bits
             clock: 1067MHz (0.9ns)
     *-firmware
          description: BIOS
          vendor: LENOVO
          physical id: f
          version: 8BET66WW (1.46 )
          date: 06/14/2018
          size: 128KiB
          capacity: 8MiB
          capabilities: pci pnp upgrade shadowing cdboot bootselect edd int13floppy720 int5printscreen int9keyboard int14serial int17printer int10video acpi usb biosbootspecification
     *-pci
          description: Host bridge
          product: 2nd Generation Core Processor Family DRAM Controller
          vendor: Intel Corporation
          physical id: 100
          bus info: pci@0000:00:00.0
          version: 09
          width: 32 bits
          clock: 33MHz
        *-pci:0
             description: PCI bridge
             product: Xeon E3-1200/2nd Generation Core Processor Family PCI Express Root Port
             vendor: Intel Corporation
             physical id: 1
             bus info: pci@0000:00:01.0
             version: 09
             width: 32 bits
             clock: 33MHz
             capabilities: pci pm msi pciexpress normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:26 ioport:5000(size=4096) memory:f0000000-f10fffff ioport:c0000000(size=301989888)
           *-display
                description: VGA compatible controller
                product: GF108GLM [Quadro 1000M]
                vendor: NVIDIA Corporation
                physical id: 0
                bus info: pci@0000:01:00.0
                version: a1
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress vga_controller bus_master cap_list rom
                configuration: driver=nouveau latency=0
                resources: irq:37 memory:f0000000-f0ffffff memory:c0000000-cfffffff memory:d0000000-d1ffffff ioport:5000(size=128) memory:f1080000-f10fffff
           *-multimedia
                description: Audio device
                product: GF108 High Definition Audio Controller
                vendor: NVIDIA Corporation
                physical id: 0.1
                bus info: pci@0000:01:00.1
                logical name: card1
                logical name: /dev/snd/controlC1
                logical name: /dev/snd/hwC1D0
                logical name: /dev/snd/hwC1D1
                logical name: /dev/snd/hwC1D2
                logical name: /dev/snd/hwC1D3
                logical name: /dev/snd/pcmC1D3p
                logical name: /dev/snd/pcmC1D7p
                logical name: /dev/snd/pcmC1D8p
                logical name: /dev/snd/pcmC1D9p
                version: a1
                width: 32 bits
                clock: 33MHz
                capabilities: pm msi pciexpress cap_list
                configuration: driver=snd_hda_intel latency=0
                resources: irq:17 memory:f1000000-f1003fff
              *-input:0
                   product: HDA NVidia HDMI/DP,pcm=3
                   physical id: 0
                   logical name: input11
                   logical name: /dev/input/event14
              *-input:1
                   product: HDA NVidia HDMI/DP,pcm=7
                   physical id: 1
                   logical name: input13
                   logical name: /dev/input/event16
              *-input:2
                   product: HDA NVidia HDMI/DP,pcm=8
                   physical id: 2
                   logical name: input14
                   logical name: /dev/input/event18
              *-input:3
                   product: HDA NVidia HDMI/DP,pcm=9
                   physical id: 3
                   logical name: input20
                   logical name: /dev/input/event19
        *-display
             description: VGA compatible controller
             product: 2nd Generation Core Processor Family Integrated Graphics Controller
             vendor: Intel Corporation
             physical id: 2
             bus info: pci@0000:00:02.0
             logical name: /dev/fb0
             version: 09
             width: 64 bits
             clock: 33MHz
             capabilities: msi pm vga_controller bus_master cap_list rom fb
             configuration: depth=32 driver=i915 latency=0 resolution=1600,900
             resources: irq:38 memory:f1400000-f17fffff memory:e0000000-efffffff ioport:6000(size=64) memory:c0000-dffff
        *-communication:0
             description: Communication controller
             product: 6 Series/C200 Series Chipset Family MEI Controller #1
             vendor: Intel Corporation
             physical id: 16
             bus info: pci@0000:00:16.0
             version: 04
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi bus_master cap_list
             configuration: driver=mei_me latency=0
             resources: irq:39 memory:f3a25000-f3a2500f
        *-communication:1
             description: Serial controller
             product: 6 Series/C200 Series Chipset Family KT Controller
             vendor: Intel Corporation
             physical id: 16.3
             bus info: pci@0000:00:16.3
             version: 04
             width: 32 bits
             clock: 66MHz
             capabilities: pm msi 16550 cap_list
             configuration: driver=serial latency=0
             resources: irq:19 ioport:60b0(size=8) memory:f3a2c000-f3a2cfff
        *-network
             description: Ethernet interface
             product: 82579LM Gigabit Network Connection (Lewisville)
             vendor: Intel Corporation
             physical id: 19
             bus info: pci@0000:00:19.0
             logical name: enp0s25
             version: 04
             serial: 3c:97:0e:05:81:41
             capacity: 1Gbit/s
             width: 32 bits
             clock: 33MHz
             capabilities: pm msi bus_master cap_list ethernet physical tp 10bt 10bt-fd 100bt 100bt-fd 1000bt-fd autonegotiation
             configuration: autonegotiation=on broadcast=yes driver=e1000e driverversion=6.1.0-26-amd64 firmware=0.13-3 latency=0 link=no multicast=yes port=twisted pair
             resources: irq:27 memory:f3a00000-f3a1ffff memory:f3a2b000-f3a2bfff ioport:6080(size=32)
        *-usb:0
             description: USB controller
             product: 6 Series/C200 Series Chipset Family USB Enhanced Host Controller #2
             vendor: Intel Corporation
             physical id: 1a
             bus info: pci@0000:00:1a.0
             version: 04
             width: 32 bits
             clock: 33MHz
             capabilities: pm debug ehci bus_master cap_list
             configuration: driver=ehci-pci latency=0
             resources: irq:16 memory:f3a2a000-f3a2a3ff
           *-usbhost
                product: EHCI Host Controller
                vendor: Linux 6.1.0-26-amd64 ehci_hcd
                physical id: 1
                bus info: usb@1
                logical name: usb1
                version: 6.01
                capabilities: usb-2.00
                configuration: driver=hub slots=3 speed=480Mbit/s
              *-usb
                   description: USB hub
                   product: Integrated Rate Matching Hub
                   vendor: Intel Corp.
                   physical id: 1
                   bus info: usb@1:1
                   version: 0.00
                   capabilities: usb-2.00
                   configuration: driver=hub slots=6 speed=480Mbit/s
                 *-usb:0
                      description: Mouse
                      product: Logitech USB Optical Mouse
                      vendor: Logitech
                      physical id: 2
                      bus info: usb@1:1.2
                      logical name: input21
                      logical name: /dev/input/event20
                      logical name: /dev/input/mouse2
                      version: 72.00
                      capabilities: usb-2.00 usb
                      configuration: driver=usbhid maxpower=100mA speed=2Mbit/s
                 *-usb:1 UNCLAIMED
                      description: Generic USB device
                      product: Biometric Coprocessor
                      vendor: UPEK
                      physical id: 3
                      bus info: usb@1:1.3
                      version: 0.02
                      capabilities: usb-1.01
                      configuration: maxpower=100mA speed=12Mbit/s
                 *-usb:2
                      description: Bluetooth wireless interface
                      product: Broadcom Bluetooth Device
                      vendor: Broadcom Corp
                      physical id: 4
                      bus info: usb@1:1.4
                      version: 7.48
                      serial: 7CE9D3DBD208
                      capabilities: bluetooth usb-2.00
                      configuration: driver=btusb speed=12Mbit/s
                 *-usb:3
                      description: Video
                      product: Integrated Camera: Integrated C
                      vendor: Chicony Electronics Co., Ltd.
                      physical id: 6
                      bus info: usb@1:1.6
                      logical name: input12
                      logical name: /dev/input/event9
                      version: 8.54
                      capabilities: usb-2.00 usb
                      configuration: driver=uvcvideo maxpower=200mA speed=480Mbit/s
        *-multimedia
             description: Audio device
             product: 6 Series/C200 Series Chipset Family High Definition Audio Controller
             vendor: Intel Corporation
             physical id: 1b
             bus info: pci@0000:00:1b.0
             logical name: card0
             logical name: /dev/snd/controlC0
             logical name: /dev/snd/hwC0D0
             logical name: /dev/snd/hwC0D1
             logical name: /dev/snd/pcmC0D0c
             logical name: /dev/snd/pcmC0D0p
             version: 04
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi pciexpress bus_master cap_list
             configuration: driver=snd_hda_intel latency=0
             resources: irq:40 memory:f3a20000-f3a23fff
           *-input:0
                product: HDA Digital PCBeep
                physical id: 0
                logical name: input15
                logical name: /dev/input/event11
                capabilities: pci
           *-input:1
                product: HDA Intel PCH Mic
                physical id: 1
                logical name: input16
                logical name: /dev/input/event12
           *-input:2
                product: HDA Intel PCH Dock Mic
                physical id: 2
                logical name: input17
                logical name: /dev/input/event13
           *-input:3
                product: HDA Intel PCH Dock Headphone
                physical id: 3
                logical name: input18
                logical name: /dev/input/event15
           *-input:4
                product: HDA Intel PCH Headphone
                physical id: 4
                logical name: input19
                logical name: /dev/input/event17
        *-pci:1
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 1
             vendor: Intel Corporation
             physical id: 1c
             bus info: pci@0000:00:1c.0
             version: b4
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode cap_list
             configuration: driver=pcieport
             resources: irq:16 ioport:2000(size=4096) memory:bfa00000-bfbfffff ioport:bfc00000(size=2097152)
        *-pci:2
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 2
             vendor: Intel Corporation
             physical id: 1c.1
             bus info: pci@0000:00:1c.1
             version: b4
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:17 memory:f3900000-f39fffff
           *-network
                description: Wireless interface
                product: Centrino Advanced-N 6205 [Taylor Peak]
                vendor: Intel Corporation
                physical id: 0
                bus info: pci@0000:03:00.0
                logical name: wlp3s0
                version: 34
                serial: 8c:70:5a:bf:eb:30
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress bus_master cap_list ethernet physical wireless
                configuration: broadcast=yes driver=iwlwifi driverversion=6.1.0-26-amd64 firmware=18.168.6.1 6000g2a-6.ucode ip=192.168.135.48 latency=0 link=yes multicast=yes wireless=IEEE 802.11
                resources: irq:41 memory:f3900000-f3901fff
        *-pci:3
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 4
             vendor: Intel Corporation
             physical id: 1c.3
             bus info: pci@0000:00:1c.3
             version: b4
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:19 ioport:4000(size=4096) memory:f3100000-f38fffff ioport:f1800000(size=8388608)
        *-pci:4
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 5
             vendor: Intel Corporation
             physical id: 1c.4
             bus info: pci@0000:00:1c.4
             version: b4
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:16 ioport:3000(size=4096) memory:f2900000-f30fffff ioport:f2000000(size=8388608)
           *-generic
                description: MMC Host
                product: MMC/SD Host Controller
                vendor: Ricoh Co Ltd
                physical id: 0
                bus info: pci@0000:0d:00.0
                logical name: mmc0
                version: 08
                width: 32 bits
                clock: 33MHz
                capabilities: msi pm pciexpress bus_master cap_list
                configuration: driver=sdhci-pci latency=0
                resources: irq:16 memory:f2901000-f29010ff
           *-firewire
                description: FireWire (IEEE 1394)
                product: R5C832 PCIe IEEE 1394 Controller
                vendor: Ricoh Co Ltd
                physical id: 0.3
                bus info: pci@0000:0d:00.3
                version: 04
                width: 32 bits
                clock: 33MHz
                capabilities: msi pm pciexpress ohci bus_master cap_list
                configuration: driver=firewire_ohci latency=0
                resources: irq:19 memory:f2900000-f29007ff
        *-pci:5
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 7
             vendor: Intel Corporation
             physical id: 1c.6
             bus info: pci@0000:00:1c.6
             version: b4
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:18 memory:f2800000-f28fffff
           *-usb
                description: USB controller
                product: uPD720200 USB 3.0 Host Controller
                vendor: NEC Corporation
                physical id: 0
                bus info: pci@0000:0e:00.0
                version: 04
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi msix pciexpress xhci bus_master cap_list
                configuration: driver=xhci_hcd latency=0
                resources: irq:18 memory:f2800000-f2801fff
              *-usbhost:0
                   product: xHCI Host Controller
                   vendor: Linux 6.1.0-26-amd64 xhci-hcd
                   physical id: 0
                   bus info: usb@2
                   logical name: usb2
                   version: 6.01
                   capabilities: usb-2.00
                   configuration: driver=hub slots=2 speed=480Mbit/s
              *-usbhost:1
                   product: xHCI Host Controller
                   vendor: Linux 6.1.0-26-amd64 xhci-hcd
                   physical id: 1
                   bus info: usb@4
                   logical name: usb4
                   version: 6.01
                   capabilities: usb-3.00
                   configuration: driver=hub slots=2 speed=5000Mbit/s
        *-usb:1
             description: USB controller
             product: 6 Series/C200 Series Chipset Family USB Enhanced Host Controller #1
             vendor: Intel Corporation
             physical id: 1d
             bus info: pci@0000:00:1d.0
             version: 04
             width: 32 bits
             clock: 33MHz
             capabilities: pm debug ehci bus_master cap_list
             configuration: driver=ehci-pci latency=0
             resources: irq:23 memory:f3a29000-f3a293ff
           *-usbhost
                product: EHCI Host Controller
                vendor: Linux 6.1.0-26-amd64 ehci_hcd
                physical id: 1
                bus info: usb@3
                logical name: usb3
                version: 6.01
                capabilities: usb-2.00
                configuration: driver=hub slots=3 speed=480Mbit/s
              *-usb
                   description: USB hub
                   product: Integrated Rate Matching Hub
                   vendor: Intel Corp.
                   physical id: 1
                   bus info: usb@3:1
                   version: 0.00
                   capabilities: usb-2.00
                   configuration: driver=hub slots=8 speed=480Mbit/s
        *-isa
             description: ISA bridge
             product: QM67 Express Chipset LPC Controller
             vendor: Intel Corporation
             physical id: 1f
             bus info: pci@0000:00:1f.0
             version: 04
             width: 32 bits
             clock: 33MHz
             capabilities: isa bus_master cap_list
             configuration: driver=lpc_ich latency=0
             resources: irq:0
           *-pnp00:00
                product: PnP device PNP0c01
                physical id: 0
                capabilities: pnp
                configuration: driver=system
           *-pnp00:01
                product: PnP device PNP0c02
                physical id: 1
                capabilities: pnp
                configuration: driver=system
           *-pnp00:02
                product: PnP device PNP0b00
                physical id: 2
                capabilities: pnp
                configuration: driver=rtc_cmos
           *-pnp00:03
                product: PnP device PNP0303
                physical id: 3
                capabilities: pnp
                configuration: driver=i8042 kbd
           *-pnp00:04
                product: PnP device LEN0015
                physical id: 4
                capabilities: pnp
                configuration: driver=i8042 aux
           *-pnp00:05
                product: PnP device SMO1200
                physical id: 5
                capabilities: pnp
                configuration: driver=tpm_tis
        *-sata
             description: SATA controller
             product: 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller
             vendor: Intel Corporation
             physical id: 1f.2
             bus info: pci@0000:00:1f.2
             logical name: scsi0
             logical name: scsi1
             version: 04
             width: 32 bits
             clock: 66MHz
             capabilities: sata msi pm ahci_1.0 bus_master cap_list emulated
             configuration: driver=ahci latency=0
             resources: irq:36 ioport:60a8(size=8) ioport:60bc(size=4) ioport:60a0(size=8) ioport:60b8(size=4) ioport:6060(size=32) memory:f3a28000-f3a287ff
           *-disk
                description: ATA Disk
                product: INTEL SSDSC2BF18
                physical id: 0
                bus info: scsi@0:0.0.0
                logical name: /dev/sda
                version: LSTi
                serial: CVDA337502ZW1802GN
                size: 167GiB (180GB)
                capabilities: gpt-1.00 partitioned partitioned:gpt
                configuration: ansiversion=5 guid=1f96ed62-9ae6-420a-b4fd-024328c56ef5 logicalsectorsize=512 sectorsize=4096
              *-volume:0 UNCLAIMED
                   description: Windows FAT volume
                   vendor: mkfs.fat
                   physical id: 1
                   bus info: scsi@0:0.0.0,1
                   version: FAT32
                   serial: 6321-4880
                   size: 1046MiB
                   capacity: 1047MiB
                   capabilities: boot fat initialized
                   configuration: FATs=2 filesystem=fat
              *-volume:1
                   description: EFI partition
                   vendor: Linux
                   physical id: 2
                   bus info: scsi@0:0.0.0,2
                   logical name: /dev/sda2
                   logical name: /boot
                   version: 1.0
                   serial: d2c0c002-f241-42b0-af17-17a02c1c57f2
                   size: 1049MiB
                   capabilities: extended_attributes large_files ext2 initialized
                   configuration: filesystem=ext2 label=boot lastmountpoint=/boot modified=2024-11-05 15:02:39 mount.fstype=ext2 mount.options=rw,relatime mounted=2024-11-05 15:02:39 state=mounted
              *-volume:2
                   description: LVM Physical Volume
                   vendor: Linux
                   physical id: 3
                   bus info: scsi@0:0.0.0,3
                   logical name: /dev/sda3
                   serial: ARaZ05-c2nA-7Zr6-pKWn-z24p-9U37-D14TsZ
                   size: 165GiB
                   capabilities: multi lvm2
           *-cdrom
                description: DVD-RAM writer
                product: DVD RW AD-7740H
                vendor: Optiarc
                physical id: 1
                bus info: scsi@1:0.0.0
                logical name: /dev/cdrom
                logical name: /dev/sr0
                version: 1.S0
                capabilities: removable audio cd-r cd-rw dvd dvd-r dvd-ram
                configuration: ansiversion=5 status=nodisc
        *-serial
             description: SMBus
             product: 6 Series/C200 Series Chipset Family SMBus Controller
             vendor: Intel Corporation
             physical id: 1f.3
             bus info: pci@0000:00:1f.3
             version: 04
             width: 64 bits
             clock: 33MHz
             configuration: driver=i801_smbus latency=0
             resources: irq:18 memory:f3a24000-f3a240ff ioport:efa0(size=32)
  *-battery
       product: 42T4799
       vendor: SANYO
       physical id: 1
       slot: Rear
       capacity: 93240mWh
       configuration: voltage=11.1V
  *-input:0
       product: AT Translated Set 2 keyboard
       physical id: 2
       logical name: input0
       logical name: /dev/input/event0
       logical name: input0::capslock
       logical name: input0::numlock
       logical name: input0::scrolllock
       capabilities: i8042
  *-input:1
       product: ThinkPad Extra Buttons
       physical id: 3
       logical name: input10
       logical name: /dev/input/event10
       capabilities: platform
  *-input:2
       product: Lid Switch
       physical id: 4
       logical name: input2
       logical name: /dev/input/event1
       capabilities: platform
  *-input:3
       product: Sleep Button
       physical id: 5
       logical name: input3
       logical name: /dev/input/event2
       capabilities: platform
  *-input:4
       product: Power Button
       physical id: 6
       logical name: input4
       logical name: /dev/input/event3
       capabilities: platform
  *-input:5
       product: SynPS/2 Synaptics TouchPad
       physical id: 7
       logical name: input5
       logical name: /dev/input/event6
       logical name: /dev/input/mouse0
       capabilities: i8042
  *-input:6
       product: Video Bus
       physical id: 8
       logical name: input6
       logical name: /dev/input/event4
       capabilities: platform
  *-input:7
       product: Video Bus
       physical id: 9
       logical name: input7
       logical name: /dev/input/event5
       capabilities: platform
  *-input:8
       product: TPPS/2 IBM TrackPoint
       physical id: a
       logical name: input8
       logical name: /dev/input/event7
       logical name: /dev/input/mouse1
       capabilities: i8042
  *-input:9
       product: PC Speaker
       physical id: b
       logical name: input9
       logical name: /dev/input/event8
       capabilities: isa
```
