BSD - Tested Hardware & Statistics (Desktops)
---------------------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestCoverage_VE](https://github.com/bsdhw/TestCoverage_VE)

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 7760

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Unknown       | Unknown                     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Unknown       | Unknown                     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| MSI           | Z87I                        | [570046969c](https://bsd-hardware.info/?probe=570046969c) | Dec 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Dell          | 08NPPY A00                  | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| PC Engines    | apu4                        | [7c8b9014b1](https://bsd-hardware.info/?probe=7c8b9014b1) | Nov 30, 2022 |
| PC Engines    | apu4                        | [dd39e91713](https://bsd-hardware.info/?probe=dd39e91713) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| Protectli     | FW6                         | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| Intel         | D54250WYK H13922-303        | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Lenovo        | MAHOBAY                     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| Unknown       | Unknown                     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| ACMA          | X8SIE                       | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| HP            | 8299                        | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| ACMA          | X8SIE                       | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Unknown       | Unknown                     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [28dd3a0b1b](https://bsd-hardware.info/?probe=28dd3a0b1b) | Nov 28, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | [35950045c6](https://bsd-hardware.info/?probe=35950045c6) | Nov 28, 2022 |
| Unknown       | Unknown                     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| Shuttle       | FS81                        | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| PC Engines    | apu6                        | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| ASUSTek       | H97-PLUS                    | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| YANYU         | R250                        | [0be0925e5b](https://bsd-hardware.info/?probe=0be0925e5b) | Nov 27, 2022 |
| ASRock        | X570 Pro4                   | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| Dell          | 09M8Y8 A02                  | [2299b7c270](https://bsd-hardware.info/?probe=2299b7c270) | Nov 27, 2022 |
| MSI           | H81M-P33                    | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| Acer          | Revo RN86                   | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| ASRock        | N68-S                       | [3813c8856e](https://bsd-hardware.info/?probe=3813c8856e) | Nov 27, 2022 |
| Protectli     | FW4B Ver                    | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Supermicro    | X10SRG-F                    | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| Unknown       | Unknown                     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | [ed6b1f75ae](https://bsd-hardware.info/?probe=ed6b1f75ae) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| ASRock        | J4125B-ITX                  | [ad497a63ac](https://bsd-hardware.info/?probe=ad497a63ac) | Nov 27, 2022 |
| HP            | 18E7                        | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Intel         | CRESCENTBAY                 | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [7c9df6da87](https://bsd-hardware.info/?probe=7c9df6da87) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [b87ed70877](https://bsd-hardware.info/?probe=b87ed70877) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Dell          | 0M017G A00                  | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Unknown       | Unknown                     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| Protectli     | FW6                         | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Protectli     | FW2B Ver                    | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [317231bad8](https://bsd-hardware.info/?probe=317231bad8) | Nov 25, 2022 |
| HP            | 3048h                       | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| Dell          | 0PTTT9 A01                  | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| ASRock        | H510M-HDV                   | [d2029ae805](https://bsd-hardware.info/?probe=d2029ae805) | Nov 25, 2022 |
| Unknown       | Unknown                     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Lenovo        | 1106A14 ThinkServer TS13... | [28aca8c985](https://bsd-hardware.info/?probe=28aca8c985) | Nov 25, 2022 |
| Gigabyte      | G31M-ES2C                   | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| HP            | 8055                        | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Unknown       | Unknown                     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Unknown       | Unknown                     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| Unknown       | Unknown                     | [c5562e1851](https://bsd-hardware.info/?probe=c5562e1851) | Nov 24, 2022 |
| MSI           | A320M-A PRO                 | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| ASRock Ind... | NUC-1240P                   | [75547bc09a](https://bsd-hardware.info/?probe=75547bc09a) | Nov 24, 2022 |
| Gigabyte      | E2500N                      | [64b937b551](https://bsd-hardware.info/?probe=64b937b551) | Nov 23, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [aa3c44499f](https://bsd-hardware.info/?probe=aa3c44499f) | Nov 23, 2022 |
| Gigabyte      | G31M-S2L                    | [d376385d80](https://bsd-hardware.info/?probe=d376385d80) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Unknown       | Unknown                     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | [b75d6c6581](https://bsd-hardware.info/?probe=b75d6c6581) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| Protectli     | FW4B                        | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| ASUSTek       | A55BM-K                     | [dc487b5779](https://bsd-hardware.info/?probe=dc487b5779) | Nov 23, 2022 |
| HP            | 3396                        | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| PC Engines    | apu6                        | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| PC Engines    | APU2                        | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| CncTion       | N5105-4L B0                 | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Intel         | H61                         | [689ebf0e57](https://bsd-hardware.info/?probe=689ebf0e57) | Nov 22, 2022 |
| Datto         | SSD                         | [08d401fa34](https://bsd-hardware.info/?probe=08d401fa34) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Gigabyte      | H81M-HD3                    | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Unknown       | Unknown                     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Apple         | PowerMac10,1                | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| Protectli     | FW4B Ver                    | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte      | H61M-S1                     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek       | P5KPL-VM-TWPC               | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | [98684b1d19](https://bsd-hardware.info/?probe=98684b1d19) | Nov 20, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| OEM           | 1.0                         | [a821818533](https://bsd-hardware.info/?probe=a821818533) | Nov 20, 2022 |
| MSI           | H81M-P33                    | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| HP            | 8054                        | [2c1e20c9e7](https://bsd-hardware.info/?probe=2c1e20c9e7) | Nov 20, 2022 |
| Hardkernel    | ODROID-H3                   | [ec7611edd1](https://bsd-hardware.info/?probe=ec7611edd1) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | [c226ac3d9b](https://bsd-hardware.info/?probe=c226ac3d9b) | Nov 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [5d3ccb6891](https://bsd-hardware.info/?probe=5d3ccb6891) | Nov 20, 2022 |
| CncTion       | N5105-4L B0                 | [449dcd1463](https://bsd-hardware.info/?probe=449dcd1463) | Nov 19, 2022 |
| Dell          | 09D2HH A00                  | [794fe8eb65](https://bsd-hardware.info/?probe=794fe8eb65) | Nov 19, 2022 |
| TOPFEEL       | H110D4-P1                   | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| Techvision    | TVI7309X B0                 | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| PC Engines    | apu6                        | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| HP            | 82FE 11                     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| ASRock        | N3150M                      | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Gigabyte      | H110TN                      | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| MSI           | Z97S SLI Krait Edition      | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| AZW           | U59                         | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| MSI           | X299 PRO                    | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2714f36aca](https://bsd-hardware.info/?probe=2714f36aca) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| HP            | 82B4                        | [d4badfa185](https://bsd-hardware.info/?probe=d4badfa185) | Nov 15, 2022 |
| ASUSTek       | P6T DELUXE V2               | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| HP            | 1998                        | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| PC Engines    | apu4                        | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | [4ebc5df17c](https://bsd-hardware.info/?probe=4ebc5df17c) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | [6e1273fdd6](https://bsd-hardware.info/?probe=6e1273fdd6) | Nov 15, 2022 |
| Dell          | 0WR7PY A03                  | [cecda8d045](https://bsd-hardware.info/?probe=cecda8d045) | Nov 14, 2022 |
| Shuttle       | FH61V                       | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| Dell          | 06D7TR A00                  | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Unknown       | Unknown                     | [b9994aa302](https://bsd-hardware.info/?probe=b9994aa302) | Nov 14, 2022 |
| MW            | GMLK-2_5G4L                 | [a678226171](https://bsd-hardware.info/?probe=a678226171) | Nov 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| ASUSTek       | H110I-PLUS                  | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Gigabyte      | J3455N-D3H                  | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| Protectli     | FW4B Ver                    | [80c0d775a7](https://bsd-hardware.info/?probe=80c0d775a7) | Nov 13, 2022 |
| HP            | 83E1                        | [689b01c121](https://bsd-hardware.info/?probe=689b01c121) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| HP            | 3397                        | [d087515b69](https://bsd-hardware.info/?probe=d087515b69) | Nov 13, 2022 |
| Unknown       | Unknown                     | [838256315e](https://bsd-hardware.info/?probe=838256315e) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| HP            | 8169                        | [e80c8a40a5](https://bsd-hardware.info/?probe=e80c8a40a5) | Nov 12, 2022 |
| Protectli     | FW4B Ver                    | [75b586fdfc](https://bsd-hardware.info/?probe=75b586fdfc) | Nov 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e5b3cb0bcd](https://bsd-hardware.info/?probe=e5b3cb0bcd) | Nov 12, 2022 |
| PC Engines    | APU2                        | [b92faf9ebb](https://bsd-hardware.info/?probe=b92faf9ebb) | Nov 12, 2022 |
| PC Engines    | APU2                        | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| Unknown       | Unknown                     | [817c69a4b0](https://bsd-hardware.info/?probe=817c69a4b0) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| MSI           | MS-9897                     | [2527ac44f4](https://bsd-hardware.info/?probe=2527ac44f4) | Nov 12, 2022 |
| Unknown       | Unknown                     | [790e616e22](https://bsd-hardware.info/?probe=790e616e22) | Nov 12, 2022 |
| Dell          | 06D7TR A00                  | [b8ee0562af](https://bsd-hardware.info/?probe=b8ee0562af) | Nov 12, 2022 |
| HP            | 8000 X4                     | [824d5f1ace](https://bsd-hardware.info/?probe=824d5f1ace) | Nov 12, 2022 |
| HP            | 83E1                        | [1760935c91](https://bsd-hardware.info/?probe=1760935c91) | Nov 12, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [54dd33114e](https://bsd-hardware.info/?probe=54dd33114e) | Nov 12, 2022 |
| Protectli     | FW6 Ver                     | [23a0c08442](https://bsd-hardware.info/?probe=23a0c08442) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| Unknown       | Unknown                     | [a2b2bb3a77](https://bsd-hardware.info/?probe=a2b2bb3a77) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| HP            | 1998                        | [e397526bac](https://bsd-hardware.info/?probe=e397526bac) | Nov 11, 2022 |
| HP            | 806A                        | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| MSI           | MS-B1831                    | [0db8392019](https://bsd-hardware.info/?probe=0db8392019) | Nov 11, 2022 |
| Lenovo        | ThinkServer RS140           | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| HP            | 1998                        | [6a38c36a3e](https://bsd-hardware.info/?probe=6a38c36a3e) | Nov 11, 2022 |
| Lenovo        | 30D9 No DPK                 | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| HP            | 18E9                        | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| ASRock        | J4005B-ITX                  | [554b92cae5](https://bsd-hardware.info/?probe=554b92cae5) | Nov 10, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| ASUSTek       | P5E-VM SE                   | [910dc6412e](https://bsd-hardware.info/?probe=910dc6412e) | Nov 10, 2022 |
| Unknown       | Unknown                     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Techvision    | TVI7309X B0                 | [d8030d23b0](https://bsd-hardware.info/?probe=d8030d23b0) | Nov 10, 2022 |
| Gigabyte      | B450M DS3H V2               | [686447d655](https://bsd-hardware.info/?probe=686447d655) | Nov 10, 2022 |
| BESSTAR Te... | TH50                        | [1300135627](https://bsd-hardware.info/?probe=1300135627) | Nov 10, 2022 |
| Cisco         | C170 A0                     | [3ba579a78c](https://bsd-hardware.info/?probe=3ba579a78c) | Nov 10, 2022 |
| AZW           | GK55                        | [d73ef4f4fc](https://bsd-hardware.info/?probe=d73ef4f4fc) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | [4bb9a9324b](https://bsd-hardware.info/?probe=4bb9a9324b) | Nov 10, 2022 |
| HP            | 843F                        | [23d8a9bda7](https://bsd-hardware.info/?probe=23d8a9bda7) | Nov 10, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [9e3a09a0b3](https://bsd-hardware.info/?probe=9e3a09a0b3) | Nov 10, 2022 |
| Protectli     | FW2B                        | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| HP            | 21B4 A01                    | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| Gigabyte      | J3455N-D3H                  | [f8e610e161](https://bsd-hardware.info/?probe=f8e610e161) | Nov 09, 2022 |
| Protectli     | FW6 Ver                     | [d75162607b](https://bsd-hardware.info/?probe=d75162607b) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| Intel         | SHARKBAY                    | [667abc6f38](https://bsd-hardware.info/?probe=667abc6f38) | Nov 09, 2022 |
| HP            | 1632                        | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| ASUSTek       | P8H77-I                     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | [a751c4e782](https://bsd-hardware.info/?probe=a751c4e782) | Nov 09, 2022 |
| Unknown       | Unknown                     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [5dcd51844e](https://bsd-hardware.info/?probe=5dcd51844e) | Nov 09, 2022 |
| Unknown       | Unknown                     | [47e6a4fa8b](https://bsd-hardware.info/?probe=47e6a4fa8b) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| Dell          | 0G261D A00                  | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Intel         | JSL MRD                     | [5800246e28](https://bsd-hardware.info/?probe=5800246e28) | Nov 08, 2022 |
| ASUSTek       | EX-H110M-V                  | [f9832b4966](https://bsd-hardware.info/?probe=f9832b4966) | Nov 08, 2022 |
| Google        | Zako                        | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| Dell          | 0F428D A00                  | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| Dell          | 0VD5HY A00                  | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| HP            | ProLiant ML310e Gen8        | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| ASUSTek       | A88XM-E                     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
| Unknown       | Unknown                     | [31ff384824](https://bsd-hardware.info/?probe=31ff384824) | Nov 07, 2022 |
| HP            | 8768 A                      | [c8a44e84c6](https://bsd-hardware.info/?probe=c8a44e84c6) | Nov 07, 2022 |
| Unknown       | Unknown                     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| PC Engines    | APU2                        | [4fda77e4ca](https://bsd-hardware.info/?probe=4fda77e4ca) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [70e257e360](https://bsd-hardware.info/?probe=70e257e360) | Nov 06, 2022 |
| Unknown       | Unknown                     | [fed7f55a01](https://bsd-hardware.info/?probe=fed7f55a01) | Nov 06, 2022 |
| HP            | 18E7                        | [6a80fc5241](https://bsd-hardware.info/?probe=6a80fc5241) | Nov 06, 2022 |
| Protectli     | VP2410                      | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [59b8857bba](https://bsd-hardware.info/?probe=59b8857bba) | Nov 06, 2022 |
| MSI           | H81M-P33                    | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Protectli     | FW6                         | [654e223853](https://bsd-hardware.info/?probe=654e223853) | Nov 06, 2022 |
| Unknown       | Unknown                     | [a33d1a4123](https://bsd-hardware.info/?probe=a33d1a4123) | Nov 06, 2022 |
| Supermicro    | X7SPA-HF                    | [66819692d5](https://bsd-hardware.info/?probe=66819692d5) | Nov 06, 2022 |
| Unknown       | Unknown                     | [6fb650e2e8](https://bsd-hardware.info/?probe=6fb650e2e8) | Nov 06, 2022 |
| Unknown       | Unknown                     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Unknown       | Unknown                     | [3771535d50](https://bsd-hardware.info/?probe=3771535d50) | Nov 06, 2022 |
| Dell          | OptiPlex 5050               | [cfd442a25d](https://bsd-hardware.info/?probe=cfd442a25d) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| Datto         | SSD                         | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Protectli     | FW4B Ver                    | [33eea3a422](https://bsd-hardware.info/?probe=33eea3a422) | Nov 05, 2022 |
| ASUSTek       | Z170-K                      | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Intel         | SHARKBAY                    | [80a31985d9](https://bsd-hardware.info/?probe=80a31985d9) | Nov 05, 2022 |
| ASUSTek       | Z97-A                       | [6a2b1c8105](https://bsd-hardware.info/?probe=6a2b1c8105) | Nov 05, 2022 |
| Intel         | CRESCENTBAY                 | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Protectli     | FW4C Ver                    | [71c0c846f1](https://bsd-hardware.info/?probe=71c0c846f1) | Nov 05, 2022 |
| Dell          | 05GD68 A00                  | [946c93ec7b](https://bsd-hardware.info/?probe=946c93ec7b) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | 213D A01                    | [f579ee6387](https://bsd-hardware.info/?probe=f579ee6387) | Nov 04, 2022 |
| ASRock        | H670M-ITX/ax                | [378889e1cd](https://bsd-hardware.info/?probe=378889e1cd) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Unknown       | Unknown                     | [4f58f89a6e](https://bsd-hardware.info/?probe=4f58f89a6e) | Nov 04, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| HP            | 82A2                        | [d83974a5ed](https://bsd-hardware.info/?probe=d83974a5ed) | Nov 03, 2022 |
| HP            | 339A                        | [a1e829d9d9](https://bsd-hardware.info/?probe=a1e829d9d9) | Nov 03, 2022 |
| Unknown       | 1.0                         | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| PC Engines    | apu4                        | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| AMD           | Inagua CRB                  | [5d27c08853](https://bsd-hardware.info/?probe=5d27c08853) | Nov 03, 2022 |
| ASRock        | G41M-VS3                    | [3021b8ee09](https://bsd-hardware.info/?probe=3021b8ee09) | Nov 03, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [7729ec0863](https://bsd-hardware.info/?probe=7729ec0863) | Nov 03, 2022 |
| ASUSTek       | H110M-CS/BR                 | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| Dell          | 05GD68 A00                  | [8e0c8344af](https://bsd-hardware.info/?probe=8e0c8344af) | Nov 03, 2022 |
| HP            | 843F                        | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| HP            | 339A                        | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Hardkernel    | ODROID-H2                   | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Gigabyte      | Z97X-UD5H                   | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRock        | G41M-VS3                    | [b6044fb84c](https://bsd-hardware.info/?probe=b6044fb84c) | Nov 02, 2022 |
| HP            | 8053                        | [92583639f6](https://bsd-hardware.info/?probe=92583639f6) | Nov 02, 2022 |
| HP            | 843F                        | [bba76c5ce6](https://bsd-hardware.info/?probe=bba76c5ce6) | Nov 02, 2022 |
| Unknown       | Unknown                     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| MSI           | B560M-A PRO                 | [ac1e500e91](https://bsd-hardware.info/?probe=ac1e500e91) | Nov 01, 2022 |
| ASRock        | H670M-ITX/ax                | [bb78d5d8ea](https://bsd-hardware.info/?probe=bb78d5d8ea) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| ASRock        | H110 Pro BTC+               | [fb24f0fa6e](https://bsd-hardware.info/?probe=fb24f0fa6e) | Nov 01, 2022 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | [f587ec97a4](https://bsd-hardware.info/?probe=f587ec97a4) | Nov 01, 2022 |
| Dell          | 05GD68 A00                  | [23483285a8](https://bsd-hardware.info/?probe=23483285a8) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6afa103d09](https://bsd-hardware.info/?probe=6afa103d09) | Oct 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Supermicro    | X10DRU-i+                   | [1ffd63a929](https://bsd-hardware.info/?probe=1ffd63a929) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| Unknown       | Unknown                     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Unknown       | Unknown                     | [c14a3eb06b](https://bsd-hardware.info/?probe=c14a3eb06b) | Oct 31, 2022 |
| Supermicro    | X7SPA-HF                    | [18b3b416ce](https://bsd-hardware.info/?probe=18b3b416ce) | Oct 31, 2022 |
| ASRock        | H110 Pro BTC+               | [20f2ab4251](https://bsd-hardware.info/?probe=20f2ab4251) | Oct 30, 2022 |
| Gigabyte      | Z68XP-UD3                   | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| MSI           | H81M-P33                    | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| Unknown       | J3160-4L                    | [e05d9b2d17](https://bsd-hardware.info/?probe=e05d9b2d17) | Oct 30, 2022 |
| HP            | 843B                        | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| maiyunda      | www.maiyunda.com            | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| ASRock        | H570M-ITX/ac                | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Unknown       | Unknown                     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| Unknown       | Unknown                     | [b8323aa325](https://bsd-hardware.info/?probe=b8323aa325) | Oct 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [02d617a604](https://bsd-hardware.info/?probe=02d617a604) | Oct 29, 2022 |
| Dell          | 0XCR8D A01                  | [a019244c85](https://bsd-hardware.info/?probe=a019244c85) | Oct 29, 2022 |
| Unknown       | Unknown                     | [3744629487](https://bsd-hardware.info/?probe=3744629487) | Oct 29, 2022 |
| Unknown       | Unknown                     | [9a12cd02f0](https://bsd-hardware.info/?probe=9a12cd02f0) | Oct 28, 2022 |
| YANYU         | R250                        | [f39d55e42d](https://bsd-hardware.info/?probe=f39d55e42d) | Oct 28, 2022 |
| Centerm       | GA690-2 2                   | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| MSI           | B360I GMAING PRO AC         | [7287c670f0](https://bsd-hardware.info/?probe=7287c670f0) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Protectli     | FW4B Ver                    | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| Unknown       | YL-J3160L4                  | [fa8d5e324b](https://bsd-hardware.info/?probe=fa8d5e324b) | Oct 27, 2022 |
| PC Engines    | APU2                        | [0c573848ce](https://bsd-hardware.info/?probe=0c573848ce) | Oct 27, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [16c226553c](https://bsd-hardware.info/?probe=16c226553c) | Oct 27, 2022 |
| Unknown       | Unknown                     | [4e01e68bb2](https://bsd-hardware.info/?probe=4e01e68bb2) | Oct 27, 2022 |
| Unknown       | Unknown                     | [9de7465e6e](https://bsd-hardware.info/?probe=9de7465e6e) | Oct 27, 2022 |
| Dell          | 0WMJ54 A01                  | [f89024b7be](https://bsd-hardware.info/?probe=f89024b7be) | Oct 27, 2022 |
| Protectli     | FW4B Ver                    | [766ee6f4eb](https://bsd-hardware.info/?probe=766ee6f4eb) | Oct 27, 2022 |
| CncTion       | N5105-4L B0                 | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| HP            | 82B4                        | [f3b7970068](https://bsd-hardware.info/?probe=f3b7970068) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Unknown       | Unknown                     | [a6d41c71fd](https://bsd-hardware.info/?probe=a6d41c71fd) | Oct 26, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | [f6df7bf1e8](https://bsd-hardware.info/?probe=f6df7bf1e8) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | [84502a19a0](https://bsd-hardware.info/?probe=84502a19a0) | Oct 26, 2022 |
| PC Engines    | APU2                        | [0677b5c196](https://bsd-hardware.info/?probe=0677b5c196) | Oct 25, 2022 |
| Dell          | 05XGC8 A01                  | [97947568ee](https://bsd-hardware.info/?probe=97947568ee) | Oct 25, 2022 |
| PC Engines    | apu1                        | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| PC Engines    | APU2                        | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| Acer          | Veriton X2610G              | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Unknown       | Unknown                     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [079830f938](https://bsd-hardware.info/?probe=079830f938) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2fa4641b0e](https://bsd-hardware.info/?probe=2fa4641b0e) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [09e5063724](https://bsd-hardware.info/?probe=09e5063724) | Oct 24, 2022 |
| Cisco         | ASA5515 A0                  | [3f20d7f9bb](https://bsd-hardware.info/?probe=3f20d7f9bb) | Oct 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [eea9a0bef3](https://bsd-hardware.info/?probe=eea9a0bef3) | Oct 24, 2022 |
| Intel         | DQ77MK AAG39642-500         | [0708c0f089](https://bsd-hardware.info/?probe=0708c0f089) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-305        | [5414062624](https://bsd-hardware.info/?probe=5414062624) | Oct 24, 2022 |
| Unknown       | YL-J3160L4                  | [746694bb1d](https://bsd-hardware.info/?probe=746694bb1d) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| ASUSTek       | P5BV-M                      | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [10ea57e48f](https://bsd-hardware.info/?probe=10ea57e48f) | Oct 23, 2022 |
| MSI           | H81M-P33                    | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| HP            | 843B                        | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Unknown       | 1.21                        | [f8a845fcda](https://bsd-hardware.info/?probe=f8a845fcda) | Oct 23, 2022 |
| Unknown       | Unknown                     | [89d0639a68](https://bsd-hardware.info/?probe=89d0639a68) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Cisco         | ASA5515 A0                  | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| Techvision    | TVI7309X B0                 | [af3a73431f](https://bsd-hardware.info/?probe=af3a73431f) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| HP            | 8719                        | [6bca1a0466](https://bsd-hardware.info/?probe=6bca1a0466) | Oct 22, 2022 |
| MW            | GMLK-2_5G4L                 | [172b2c53fe](https://bsd-hardware.info/?probe=172b2c53fe) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [947d061849](https://bsd-hardware.info/?probe=947d061849) | Oct 22, 2022 |
| ASRock        | B250M-HDV                   | [803b44339b](https://bsd-hardware.info/?probe=803b44339b) | Oct 22, 2022 |
| Intel         | D2500CC AAG81477-401        | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| MSI           | 890GXM-G65                  | [03c116d78f](https://bsd-hardware.info/?probe=03c116d78f) | Oct 22, 2022 |
| Alienware     | 0PGRP5 A01                  | [e34219da0f](https://bsd-hardware.info/?probe=e34219da0f) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | [ca0d187a0b](https://bsd-hardware.info/?probe=ca0d187a0b) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | [5b8c853c20](https://bsd-hardware.info/?probe=5b8c853c20) | Oct 22, 2022 |
| Acer          | Revo RN86                   | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | [f9ca8e5fdd](https://bsd-hardware.info/?probe=f9ca8e5fdd) | Oct 21, 2022 |
| Intel         | H67SL_VER1.2A               | [a469ad62a4](https://bsd-hardware.info/?probe=a469ad62a4) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| PC Engines    | APU2                        | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Protectli     | FW6 Ver                     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | [a47e59ad6b](https://bsd-hardware.info/?probe=a47e59ad6b) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | [eb9ffe08e7](https://bsd-hardware.info/?probe=eb9ffe08e7) | Oct 21, 2022 |
| Unknown       | Unknown                     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| Protectli     | FW6                         | [528ef94fb5](https://bsd-hardware.info/?probe=528ef94fb5) | Oct 21, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| ASRock        | B460M-ITX/ac                | [c1a691f99c](https://bsd-hardware.info/?probe=c1a691f99c) | Oct 20, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| PC Engines    | APU2                        | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Unknown       | Unknown                     | [1778396ba9](https://bsd-hardware.info/?probe=1778396ba9) | Oct 20, 2022 |
| Unknown       | Unknown                     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| Protectli     | FW6                         | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | [f3db09e0f0](https://bsd-hardware.info/?probe=f3db09e0f0) | Oct 19, 2022 |
| Supermicro    | X11SSL-F                    | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| Protectli     | FW4B                        | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| ASUSTek       | E35M1-I DELUXE              | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| Unknown       | Unknown                     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Iomega        | StorCenter Pro px2 SA       | [d4e8f25586](https://bsd-hardware.info/?probe=d4e8f25586) | Oct 18, 2022 |
| Protectli     | FW4B Ver                    | [c75bcb519e](https://bsd-hardware.info/?probe=c75bcb519e) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| ASUSTek       | N3050I-C                    | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| CncTion       | N5105-4L B0                 | [45d6590312](https://bsd-hardware.info/?probe=45d6590312) | Oct 18, 2022 |
| Dell          | 02K9CR A02                  | [a5cda6c49e](https://bsd-hardware.info/?probe=a5cda6c49e) | Oct 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [2e4cd910d7](https://bsd-hardware.info/?probe=2e4cd910d7) | Oct 17, 2022 |
| PC Engines    | apu4                        | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| NF541         | 1.0                         | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| Intel         | DH57DD AAE82022-202         | [01622a2528](https://bsd-hardware.info/?probe=01622a2528) | Oct 17, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [242e320350](https://bsd-hardware.info/?probe=242e320350) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2885a5ce85](https://bsd-hardware.info/?probe=2885a5ce85) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| HP            | 1588h                       | [e78a0308c7](https://bsd-hardware.info/?probe=e78a0308c7) | Oct 16, 2022 |
| Unknown       | Unknown                     | [4fd307fbb4](https://bsd-hardware.info/?probe=4fd307fbb4) | Oct 16, 2022 |
| Techvision    | TVI7309X B0                 | [f7d0616889](https://bsd-hardware.info/?probe=f7d0616889) | Oct 16, 2022 |
| HP            | 8719                        | [87efb126fc](https://bsd-hardware.info/?probe=87efb126fc) | Oct 16, 2022 |
| Dell          | 0200DY A02                  | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Hardkernel    | ODROID-H2                   | [77d3019212](https://bsd-hardware.info/?probe=77d3019212) | Oct 16, 2022 |
| Protectli     | FW4B                        | [57ae1d8cda](https://bsd-hardware.info/?probe=57ae1d8cda) | Oct 15, 2022 |
| Unknown       | Unknown                     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| HP            | 8169                        | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [76a1007c46](https://bsd-hardware.info/?probe=76a1007c46) | Oct 15, 2022 |
| Protectli     | FW6 Ver                     | [55967e02f6](https://bsd-hardware.info/?probe=55967e02f6) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | [bbd42243ae](https://bsd-hardware.info/?probe=bbd42243ae) | Oct 15, 2022 |
| Techvision    | TVI7309X B0                 | [b02dcbb7b5](https://bsd-hardware.info/?probe=b02dcbb7b5) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | [0e9ac1e935](https://bsd-hardware.info/?probe=0e9ac1e935) | Oct 15, 2022 |
| ASRock        | Q1900M                      | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | [73960ade29](https://bsd-hardware.info/?probe=73960ade29) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| AZW           | Green G1                    | [f6f16c5141](https://bsd-hardware.info/?probe=f6f16c5141) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| Supermicro    | X10SLL-F                    | [3b13ea475b](https://bsd-hardware.info/?probe=3b13ea475b) | Oct 14, 2022 |
| Dell          | 0WMJ54 A01                  | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | apu1                        | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Dell          | 00V62H A00                  | [17a6b61af7](https://bsd-hardware.info/?probe=17a6b61af7) | Oct 14, 2022 |
| Unknown       | Unknown                     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| PC Engines    | APU2                        | [856e29140e](https://bsd-hardware.info/?probe=856e29140e) | Oct 14, 2022 |
| PC Engines    | APU2                        | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| Unknown       | J3160-4L                    | [42c01a3aaf](https://bsd-hardware.info/?probe=42c01a3aaf) | Oct 13, 2022 |
| ASUSTek       | P5L-VM 1394                 | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| HP            | 260 G3 DM                   | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| Unknown       | Unknown                     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [0da821d451](https://bsd-hardware.info/?probe=0da821d451) | Oct 13, 2022 |
| Gigabyte      | J3455N-D3H                  | [9757e40c42](https://bsd-hardware.info/?probe=9757e40c42) | Oct 13, 2022 |
| Unknown       | Unknown                     | [763365591a](https://bsd-hardware.info/?probe=763365591a) | Oct 12, 2022 |
| ASUSTek       | H110M-PLUS                  | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| PC Engines    | APU2                        | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| Unknown       | YL-1900L4-V2                | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| HP            | 1589                        | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| Unknown       | Unknown                     | [7000ef7aeb](https://bsd-hardware.info/?probe=7000ef7aeb) | Oct 12, 2022 |
| Protectli     | FW4B                        | [2fd9fcda8e](https://bsd-hardware.info/?probe=2fd9fcda8e) | Oct 11, 2022 |
| ASUSTek       | P8Z68-V                     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| Unknown       | Unknown                     | [94915735cc](https://bsd-hardware.info/?probe=94915735cc) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| MW            | GMLK-2_5G4L                 | [ff2b9a916f](https://bsd-hardware.info/?probe=ff2b9a916f) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| ASUSTek       | H110M-CS/BR                 | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [2cba6fbbb7](https://bsd-hardware.info/?probe=2cba6fbbb7) | Oct 11, 2022 |
| ASRock        | B450M Pro4-F                | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| AZW           | U59                         | [8839497803](https://bsd-hardware.info/?probe=8839497803) | Oct 11, 2022 |
| Unknown       | Unknown                     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Dell          | 0HD5W2 A00                  | [4fb69eef28](https://bsd-hardware.info/?probe=4fb69eef28) | Oct 11, 2022 |
| Shuttle       | FH170                       | [8fd08beffa](https://bsd-hardware.info/?probe=8fd08beffa) | Oct 10, 2022 |
| PCWare        | IPMH81G1                    | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| NU941         | 1.0                         | [2690c2a8df](https://bsd-hardware.info/?probe=2690c2a8df) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [4c9069df20](https://bsd-hardware.info/?probe=4c9069df20) | Oct 10, 2022 |
| HP            | 1495                        | [cfa8ab5df3](https://bsd-hardware.info/?probe=cfa8ab5df3) | Oct 10, 2022 |
| ASRock        | J3355B-ITX                  | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| Clevo         | R130T                       | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| CncTion       | Jasper-4L B0                | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| Unknown       | Unknown                     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| Protectli     | FW1 Ver                     | [1015ef5e66](https://bsd-hardware.info/?probe=1015ef5e66) | Oct 09, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [e08e2ca6e0](https://bsd-hardware.info/?probe=e08e2ca6e0) | Oct 09, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| ASRock        | X399 Taichi                 | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [e595ade938](https://bsd-hardware.info/?probe=e595ade938) | Oct 09, 2022 |
| ASRock        | J4005B-ITX                  | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| MiTAC         | PH11CMI                     | [71802cdcad](https://bsd-hardware.info/?probe=71802cdcad) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [464739212c](https://bsd-hardware.info/?probe=464739212c) | Oct 08, 2022 |
| HP            | 339A                        | [7ad68046ce](https://bsd-hardware.info/?probe=7ad68046ce) | Oct 08, 2022 |
| HP            | 86FC MVB                    | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Soekris En... | net6501                     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Unknown       | Unknown                     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Unknown       | Unknown                     | [e76890ff26](https://bsd-hardware.info/?probe=e76890ff26) | Oct 08, 2022 |
| Unknown       | Unknown                     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| HP            | 18E7                        | [35e68316d8](https://bsd-hardware.info/?probe=35e68316d8) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M72e 3664AD9    | [f6fded284d](https://bsd-hardware.info/?probe=f6fded284d) | Oct 08, 2022 |
| Unknown       | Unknown                     | [e4e47282a9](https://bsd-hardware.info/?probe=e4e47282a9) | Oct 08, 2022 |
| Techvision    | TVI7309X B0                 | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Unknown       | Unknown                     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Intel         | SHARKBAY                    | [9d3eed2bec](https://bsd-hardware.info/?probe=9d3eed2bec) | Oct 07, 2022 |
| ASRockRack    | EP2C612D16FM                | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Unknown       | Unknown                     | [ad8b88d10b](https://bsd-hardware.info/?probe=ad8b88d10b) | Oct 07, 2022 |
| HP            | ProLiant MicroServer Gen... | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Dell          | 04YP6J A01                  | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| YANYU         | H67SL                       | [373902d38b](https://bsd-hardware.info/?probe=373902d38b) | Oct 07, 2022 |
| ASRock        | B75M R2.0                   | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Dell          | 0KYJ8C A02                  | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| ASRock        | B450M-HDV                   | [84300e7dcc](https://bsd-hardware.info/?probe=84300e7dcc) | Oct 07, 2022 |
| ADI Engine... | RCC-VE                      | [f6a9012bb2](https://bsd-hardware.info/?probe=f6a9012bb2) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | [7e24ab5841](https://bsd-hardware.info/?probe=7e24ab5841) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | [11e04b0c73](https://bsd-hardware.info/?probe=11e04b0c73) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Unknown       | Unknown                     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | apu1                        | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| PC Engines    | APU2                        | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| Unknown       | Unknown                     | [b889791d9f](https://bsd-hardware.info/?probe=b889791d9f) | Oct 06, 2022 |
| Protectli     | FW4B                        | [89a0375ecb](https://bsd-hardware.info/?probe=89a0375ecb) | Oct 06, 2022 |
| Protectli     | VP4650                      | [c9f3c90f23](https://bsd-hardware.info/?probe=c9f3c90f23) | Oct 06, 2022 |
| YANYU         | ITX-M9F VER:1.1             | [dcb1d22084](https://bsd-hardware.info/?probe=dcb1d22084) | Oct 06, 2022 |
| HP            | 8299                        | [e0f84d2500](https://bsd-hardware.info/?probe=e0f84d2500) | Oct 05, 2022 |
| MW            | GMLK-2_5G4L                 | [7eba59d7ca](https://bsd-hardware.info/?probe=7eba59d7ca) | Oct 05, 2022 |
| CncTion       | J4125-4L-I225               | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| Cisco         | ASA5515 A0                  | [bdda6913d3](https://bsd-hardware.info/?probe=bdda6913d3) | Oct 05, 2022 |
| Unknown       | Unknown                     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Dell          | 05GD68 A00                  | [ec799eed0c](https://bsd-hardware.info/?probe=ec799eed0c) | Oct 05, 2022 |
| PC Engines    | APU2                        | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |
| Dell          | 0WMJ54 A00                  | [541e5011d9](https://bsd-hardware.info/?probe=541e5011d9) | Oct 04, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Lenovo        | ThinkPad T60 2613CTO        | [cb649b809c](https://bsd-hardware.info/?probe=cb649b809c) | Oct 04, 2022 |
| ASRock        | Z370M-ITX/ac                | [e73c308b5f](https://bsd-hardware.info/?probe=e73c308b5f) | Oct 04, 2022 |
| HP            | 18E7                        | [ad345682d8](https://bsd-hardware.info/?probe=ad345682d8) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| MSI           | MS-B1831                    | [7cf04bb1f4](https://bsd-hardware.info/?probe=7cf04bb1f4) | Oct 04, 2022 |
| Unknown       | Unknown                     | [c3608a94b1](https://bsd-hardware.info/?probe=c3608a94b1) | Oct 04, 2022 |
| ASRock        | J3355M                      | [0240dbc2bb](https://bsd-hardware.info/?probe=0240dbc2bb) | Oct 04, 2022 |
| Techvision    | TVI7309X B0                 | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| Protectli     | FW4B                        | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [58def8d407](https://bsd-hardware.info/?probe=58def8d407) | Oct 03, 2022 |
| ASRock        | AM1H-ITX                    | [8123ab15ec](https://bsd-hardware.info/?probe=8123ab15ec) | Oct 03, 2022 |
| Unknown       | Unknown                     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| maiyunda      | www.maiyunda.com            | [d30234a34e](https://bsd-hardware.info/?probe=d30234a34e) | Oct 03, 2022 |
| IBM           | 9210MML                     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| Unknown       | Unknown                     | [02a9700c12](https://bsd-hardware.info/?probe=02a9700c12) | Oct 03, 2022 |
| Unknown       | Unknown                     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| Dell          | 04YP6J A02                  | [dacf88ac40](https://bsd-hardware.info/?probe=dacf88ac40) | Oct 02, 2022 |
| Unknown       | Unknown                     | [4e021d720f](https://bsd-hardware.info/?probe=4e021d720f) | Oct 02, 2022 |
| Unknown       | Unknown                     | [f2647037ec](https://bsd-hardware.info/?probe=f2647037ec) | Oct 02, 2022 |
| HPE           | ProLiant ML30 Gen10         | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| Biostar       | B450NH                      | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
| ECS           | H61H2-MV                    | [6f40caa9f8](https://bsd-hardware.info/?probe=6f40caa9f8) | Oct 02, 2022 |
| HP            | 8767 A                      | [9d98b3baa4](https://bsd-hardware.info/?probe=9d98b3baa4) | Oct 02, 2022 |
| Gigabyte      | C1037UN-EU                  | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| HP            | 212B                        | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| AAEON         | FWS-2350 V1.0               | [00cc54cbad](https://bsd-hardware.info/?probe=00cc54cbad) | Oct 01, 2022 |
| Unknown       | Unknown                     | [01566cd078](https://bsd-hardware.info/?probe=01566cd078) | Oct 01, 2022 |
| Protectli     | FW6 Ver                     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| Unknown       | Unknown                     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| AMI           | PICO PC                     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Shuttle       | FH61V                       | [305f06cd6a](https://bsd-hardware.info/?probe=305f06cd6a) | Oct 01, 2022 |
| Unknown       | Unknown                     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| Dell          | 0WMJ54 A01                  | [53dfc5844c](https://bsd-hardware.info/?probe=53dfc5844c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| Protectli     | FW4B Ver                    | [05651f8664](https://bsd-hardware.info/?probe=05651f8664) | Oct 01, 2022 |
| Dell          | 0PC5F7 A00                  | [376550557f](https://bsd-hardware.info/?probe=376550557f) | Sep 30, 2022 |
| Cisco         | ASA5512 A0                  | [5b31d03140](https://bsd-hardware.info/?probe=5b31d03140) | Sep 30, 2022 |
| Jingsha       | x79-P3 by xUz               | [6853ba1191](https://bsd-hardware.info/?probe=6853ba1191) | Sep 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | [c1c59c9d14](https://bsd-hardware.info/?probe=c1c59c9d14) | Sep 30, 2022 |
| Dell          | 0T10XW A01                  | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| Dell          | 0WMJ54 A01                  | [30cb759583](https://bsd-hardware.info/?probe=30cb759583) | Sep 30, 2022 |
| Gigabyte      | H510M H                     | [8ad31cc470](https://bsd-hardware.info/?probe=8ad31cc470) | Sep 29, 2022 |
| Intel         | CARLOW                      | [25b6d62332](https://bsd-hardware.info/?probe=25b6d62332) | Sep 29, 2022 |
| BESSTAR Te... | IB9                         | [eb0e449150](https://bsd-hardware.info/?probe=eb0e449150) | Sep 29, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [353008eb5e](https://bsd-hardware.info/?probe=353008eb5e) | Sep 29, 2022 |
| Biostar       | N68S3B                      | [24c8fcee9a](https://bsd-hardware.info/?probe=24c8fcee9a) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| ASRock        | B450M-HDV                   | [a3e25236fc](https://bsd-hardware.info/?probe=a3e25236fc) | Sep 28, 2022 |
| Unknown       | Unknown                     | [2926e2dc6f](https://bsd-hardware.info/?probe=2926e2dc6f) | Sep 28, 2022 |
| Biostar       | B450NH                      | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
| Unknown       | Unknown                     | [c3f8e853ef](https://bsd-hardware.info/?probe=c3f8e853ef) | Sep 28, 2022 |
| AMI           | MNHO-048                    | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Techvision    | TVI7309X B0                 | [441eb24fd2](https://bsd-hardware.info/?probe=441eb24fd2) | Sep 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [3234a0b453](https://bsd-hardware.info/?probe=3234a0b453) | Sep 28, 2022 |
| ASRock        | Z97 Professional            | [8936497eed](https://bsd-hardware.info/?probe=8936497eed) | Sep 27, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [390f4301dd](https://bsd-hardware.info/?probe=390f4301dd) | Sep 27, 2022 |
| MSI           | A520M-A PRO                 | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| Unknown       | Unknown                     | [16f6784862](https://bsd-hardware.info/?probe=16f6784862) | Sep 27, 2022 |
| Intel         | D34010WYK H14771-305        | [93e4627cc9](https://bsd-hardware.info/?probe=93e4627cc9) | Sep 27, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [a605b4582c](https://bsd-hardware.info/?probe=a605b4582c) | Sep 27, 2022 |
| ASRockRack    | X470D4U                     | [27a82e5fc8](https://bsd-hardware.info/?probe=27a82e5fc8) | Sep 27, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [3877787983](https://bsd-hardware.info/?probe=3877787983) | Sep 27, 2022 |
| ASRock        | X570M Pro4                  | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Protectli     | FW4B                        | [431bcb4425](https://bsd-hardware.info/?probe=431bcb4425) | Sep 27, 2022 |
| Intel         | DH87MC AAG74242-401         | [5e823b71da](https://bsd-hardware.info/?probe=5e823b71da) | Sep 27, 2022 |
| Supermicro    | X11SBA-LN4F                 | [4c7f997199](https://bsd-hardware.info/?probe=4c7f997199) | Sep 26, 2022 |
| Unknown       | Unknown                     | [69a8b9b8d9](https://bsd-hardware.info/?probe=69a8b9b8d9) | Sep 26, 2022 |
| Cisco         | ASA5515 A0                  | [7b1ba71a42](https://bsd-hardware.info/?probe=7b1ba71a42) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [cfcfd2a636](https://bsd-hardware.info/?probe=cfcfd2a636) | Sep 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | [cde2481e46](https://bsd-hardware.info/?probe=cde2481e46) | Sep 26, 2022 |
| Dell          | 0T10XW A02                  | [b8db4655e5](https://bsd-hardware.info/?probe=b8db4655e5) | Sep 26, 2022 |
| Dell          | 0KYJ8C A02                  | [12493c3802](https://bsd-hardware.info/?probe=12493c3802) | Sep 26, 2022 |
| ASRock        | 990FX Extreme3              | [68d99cffe1](https://bsd-hardware.info/?probe=68d99cffe1) | Sep 26, 2022 |
| Techvision    | TVI7309X B0                 | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| Dell          | 0TDG4V A00                  | [cc92be7e52](https://bsd-hardware.info/?probe=cc92be7e52) | Sep 25, 2022 |
| PC Engines    | APU2                        | [3fcc5e5ae2](https://bsd-hardware.info/?probe=3fcc5e5ae2) | Sep 25, 2022 |
| Techvision    | TVI7309X B0                 | [ae535b0b49](https://bsd-hardware.info/?probe=ae535b0b49) | Sep 25, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [83607fc711](https://bsd-hardware.info/?probe=83607fc711) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | [8f4900d0e6](https://bsd-hardware.info/?probe=8f4900d0e6) | Sep 25, 2022 |
| CncTion       | Jasper-4L B0                | [2998faa879](https://bsd-hardware.info/?probe=2998faa879) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [fe44242c3b](https://bsd-hardware.info/?probe=fe44242c3b) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [6e2d053e1c](https://bsd-hardware.info/?probe=6e2d053e1c) | Sep 25, 2022 |
| iEi           | SAE1 V1.04                  | [cc006e5c32](https://bsd-hardware.info/?probe=cc006e5c32) | Sep 25, 2022 |
| HP            | 3397                        | [8b019e6a96](https://bsd-hardware.info/?probe=8b019e6a96) | Sep 25, 2022 |
| ASRock        | 990FX Extreme3              | [c81d389fd2](https://bsd-hardware.info/?probe=c81d389fd2) | Sep 25, 2022 |
| Unknown       | Unknown                     | [9f998deaa4](https://bsd-hardware.info/?probe=9f998deaa4) | Sep 25, 2022 |
| Biostar       | N68S3B                      | [59bd37df63](https://bsd-hardware.info/?probe=59bd37df63) | Sep 25, 2022 |
| HP            | 8592                        | [898ce46c1f](https://bsd-hardware.info/?probe=898ce46c1f) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | [59886931c5](https://bsd-hardware.info/?probe=59886931c5) | Sep 24, 2022 |
| MSI           | A88XM-E45                   | [d9d06daa51](https://bsd-hardware.info/?probe=d9d06daa51) | Sep 24, 2022 |
| MSI           | Z490-A PRO                  | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| ASUSTek       | All Series                  | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| HP            | 18E7                        | [02ac7695d7](https://bsd-hardware.info/?probe=02ac7695d7) | Sep 24, 2022 |
| HP            | 339A                        | [fb436c3cc3](https://bsd-hardware.info/?probe=fb436c3cc3) | Sep 24, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8ed018c141](https://bsd-hardware.info/?probe=8ed018c141) | Sep 24, 2022 |
| ASUSTek       | Rampage II Extreme          | [eccb37382c](https://bsd-hardware.info/?probe=eccb37382c) | Sep 24, 2022 |
| YANYU         | H67SL                       | [5f5819ef11](https://bsd-hardware.info/?probe=5f5819ef11) | Sep 24, 2022 |
| Unknown       | Unknown                     | [8f42ff0969](https://bsd-hardware.info/?probe=8f42ff0969) | Sep 24, 2022 |
| Unknown       | Unknown                     | [95b1404339](https://bsd-hardware.info/?probe=95b1404339) | Sep 23, 2022 |
| TYAN Compu... | S5530WG2NR-LE-AKA           | [18c4588a0e](https://bsd-hardware.info/?probe=18c4588a0e) | Sep 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a0672c6af1](https://bsd-hardware.info/?probe=a0672c6af1) | Sep 23, 2022 |
| Unknown       | Unknown                     | [ffa40a08e8](https://bsd-hardware.info/?probe=ffa40a08e8) | Sep 23, 2022 |
| NITRINOnet    | M360RUS56                   | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5029142d61](https://bsd-hardware.info/?probe=5029142d61) | Sep 22, 2022 |
| Dell          | 042P49 A01                  | [13f6367ce8](https://bsd-hardware.info/?probe=13f6367ce8) | Sep 22, 2022 |
| Unknown       | Unknown                     | [b7bfcbef72](https://bsd-hardware.info/?probe=b7bfcbef72) | Sep 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Protectli     | FW4B Ver                    | [036004bbfe](https://bsd-hardware.info/?probe=036004bbfe) | Sep 22, 2022 |
| Unknown       | Unknown                     | [58b6d3d116](https://bsd-hardware.info/?probe=58b6d3d116) | Sep 21, 2022 |
| PC Engines    | APU                         | [a65b17ba04](https://bsd-hardware.info/?probe=a65b17ba04) | Sep 21, 2022 |
| HP            | 21D0                        | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| Unknown       | Unknown                     | [199ad16750](https://bsd-hardware.info/?probe=199ad16750) | Sep 21, 2022 |
| Dell          | 0HD5W2 A00                  | [6c169bdb6a](https://bsd-hardware.info/?probe=6c169bdb6a) | Sep 20, 2022 |
| MSI           | MS-B1831                    | [42f48d632c](https://bsd-hardware.info/?probe=42f48d632c) | Sep 20, 2022 |
| MW            | GMLK-2_5G4L                 | [37cafd59eb](https://bsd-hardware.info/?probe=37cafd59eb) | Sep 20, 2022 |
| Dell          | 02YRK5 A03                  | [2ec32e432d](https://bsd-hardware.info/?probe=2ec32e432d) | Sep 20, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [ca3b8f6b48](https://bsd-hardware.info/?probe=ca3b8f6b48) | Sep 20, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [3c74fc1690](https://bsd-hardware.info/?probe=3c74fc1690) | Sep 20, 2022 |
| Unknown       | Unknown                     | [8e55c8e637](https://bsd-hardware.info/?probe=8e55c8e637) | Sep 20, 2022 |
| HP            | 1495                        | [163ac0a58b](https://bsd-hardware.info/?probe=163ac0a58b) | Sep 20, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [c057b7ab09](https://bsd-hardware.info/?probe=c057b7ab09) | Sep 20, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [16479f1a2c](https://bsd-hardware.info/?probe=16479f1a2c) | Sep 20, 2022 |
| Unknown       | Unknown                     | [1ceba97eb9](https://bsd-hardware.info/?probe=1ceba97eb9) | Sep 20, 2022 |
| Intel         | SHARKBAY                    | [afbedcb189](https://bsd-hardware.info/?probe=afbedcb189) | Sep 20, 2022 |
| HP            | 21D0                        | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| Supermicro    | X9SCI/X9SCA                 | [1270203d0b](https://bsd-hardware.info/?probe=1270203d0b) | Sep 19, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [b394504429](https://bsd-hardware.info/?probe=b394504429) | Sep 19, 2022 |
| Foxconn       | G31MXP FAB:1.1              | [9d291758ef](https://bsd-hardware.info/?probe=9d291758ef) | Sep 19, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [393da0c00c](https://bsd-hardware.info/?probe=393da0c00c) | Sep 19, 2022 |
| HP            | ProLiant ML350p Gen8        | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [d1c81ef222](https://bsd-hardware.info/?probe=d1c81ef222) | Sep 19, 2022 |
| Gigabyte      | H61M-DS2V                   | [55f8e635b8](https://bsd-hardware.info/?probe=55f8e635b8) | Sep 19, 2022 |
| Dell          | 01TJ2K A02                  | [b34cf533f3](https://bsd-hardware.info/?probe=b34cf533f3) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-P                | [a2f56848a9](https://bsd-hardware.info/?probe=a2f56848a9) | Sep 19, 2022 |
| Lenovo        | ThinkStation D10 6493WEU    | [526e5eea0b](https://bsd-hardware.info/?probe=526e5eea0b) | Sep 18, 2022 |
| Supermicro    | A2SDi-TP8F                  | [db2194c9b9](https://bsd-hardware.info/?probe=db2194c9b9) | Sep 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [cad2b5fd02](https://bsd-hardware.info/?probe=cad2b5fd02) | Sep 18, 2022 |
| Gigabyte      | H81M-S1                     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| Intel         | D34010WYK H14771-305        | [e734b98922](https://bsd-hardware.info/?probe=e734b98922) | Sep 18, 2022 |
| MSI           | MS-B1831                    | [94a3d6891a](https://bsd-hardware.info/?probe=94a3d6891a) | Sep 18, 2022 |
| ECS           | H61H2-MV                    | [d2945c003e](https://bsd-hardware.info/?probe=d2945c003e) | Sep 18, 2022 |
| HP            | 213D A01                    | [6e8a38b6ca](https://bsd-hardware.info/?probe=6e8a38b6ca) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | [d027a503a5](https://bsd-hardware.info/?probe=d027a503a5) | Sep 18, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | [261f623516](https://bsd-hardware.info/?probe=261f623516) | Sep 18, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | [266ef0ca6a](https://bsd-hardware.info/?probe=266ef0ca6a) | Sep 18, 2022 |
| HP            | 18E7                        | [e999bdd87e](https://bsd-hardware.info/?probe=e999bdd87e) | Sep 17, 2022 |
| Unknown       | Unknown                     | [050c365fcd](https://bsd-hardware.info/?probe=050c365fcd) | Sep 17, 2022 |
| Intel         | D53427RKE G87971-403        | [aa00c60448](https://bsd-hardware.info/?probe=aa00c60448) | Sep 17, 2022 |
| Unknown       | Unknown                     | [af8f180c2c](https://bsd-hardware.info/?probe=af8f180c2c) | Sep 17, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a9da12dec0](https://bsd-hardware.info/?probe=a9da12dec0) | Sep 17, 2022 |
| CncTion       | N5105-4L B0                 | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Gigabyte      | H410M S2 V2                 | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [e0b8ceecae](https://bsd-hardware.info/?probe=e0b8ceecae) | Sep 16, 2022 |
| ASUSTek       | PRIME X570-P                | [9fc1f66fcc](https://bsd-hardware.info/?probe=9fc1f66fcc) | Sep 16, 2022 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [eb09d789de](https://bsd-hardware.info/?probe=eb09d789de) | Sep 16, 2022 |
| Unknown       | Unknown                     | [050dee62c1](https://bsd-hardware.info/?probe=050dee62c1) | Sep 16, 2022 |
| Intel BOXJ... | Unknown                     | [c28fe204f3](https://bsd-hardware.info/?probe=c28fe204f3) | Sep 16, 2022 |
| Intel BOXJ... | Unknown                     | [a900f3bc8b](https://bsd-hardware.info/?probe=a900f3bc8b) | Sep 16, 2022 |
| Unknown       | Unknown                     | [3b66741f97](https://bsd-hardware.info/?probe=3b66741f97) | Sep 16, 2022 |
| Unknown       | Unknown                     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| ASUSTek       | M5A88-M                     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Supermicro    | A2SDi-TP8F                  | [8c67aa0f6e](https://bsd-hardware.info/?probe=8c67aa0f6e) | Sep 15, 2022 |
| Techvision    | TVI7309X B0                 | [505feb51ca](https://bsd-hardware.info/?probe=505feb51ca) | Sep 15, 2022 |
| Gigabyte      | Z370P D3-CF                 | [10f0cfa344](https://bsd-hardware.info/?probe=10f0cfa344) | Sep 15, 2022 |
| Unknown       | Unknown                     | [7df7bc66e7](https://bsd-hardware.info/?probe=7df7bc66e7) | Sep 15, 2022 |
| Intel         | ChiefRiver                  | [5361453e6a](https://bsd-hardware.info/?probe=5361453e6a) | Sep 15, 2022 |
| Gigabyte      | H270-HD3-CF                 | [0157925fad](https://bsd-hardware.info/?probe=0157925fad) | Sep 15, 2022 |
| Dell          | 0R230R A00                  | [ad70ccea4d](https://bsd-hardware.info/?probe=ad70ccea4d) | Sep 15, 2022 |
| YANYU         | H67SL                       | [37ba00c2f3](https://bsd-hardware.info/?probe=37ba00c2f3) | Sep 15, 2022 |
| Intel         | DENLOW_WS                   | [7ec0e7257d](https://bsd-hardware.info/?probe=7ec0e7257d) | Sep 14, 2022 |
| AZW           | Green G1                    | [1ccd8f86b3](https://bsd-hardware.info/?probe=1ccd8f86b3) | Sep 14, 2022 |
| Protectli     | FW6                         | [23227c99a0](https://bsd-hardware.info/?probe=23227c99a0) | Sep 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | [13ec5a6f20](https://bsd-hardware.info/?probe=13ec5a6f20) | Sep 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7aa564bfb2](https://bsd-hardware.info/?probe=7aa564bfb2) | Sep 14, 2022 |
| ASUSTek       | H61M-K                      | [0ee299e989](https://bsd-hardware.info/?probe=0ee299e989) | Sep 14, 2022 |
| Dell          | 0FDY5C A00                  | [cce6101086](https://bsd-hardware.info/?probe=cce6101086) | Sep 14, 2022 |
| Protectli     | FW4B Ver                    | [58caab8946](https://bsd-hardware.info/?probe=58caab8946) | Sep 14, 2022 |
| ASUSTek       | Rampage II Extreme          | [924dc8e7e1](https://bsd-hardware.info/?probe=924dc8e7e1) | Sep 14, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [2b4cf189e9](https://bsd-hardware.info/?probe=2b4cf189e9) | Sep 14, 2022 |
| Techvision    | TVI7309X B0                 | [a444259756](https://bsd-hardware.info/?probe=a444259756) | Sep 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dc557f4385](https://bsd-hardware.info/?probe=dc557f4385) | Sep 14, 2022 |
| Unknown       | Unknown                     | [992ddc4118](https://bsd-hardware.info/?probe=992ddc4118) | Sep 14, 2022 |
| maiyunda      | www.maiyunda.com            | [cbc4aeb7be](https://bsd-hardware.info/?probe=cbc4aeb7be) | Sep 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | [e8848edf41](https://bsd-hardware.info/?probe=e8848edf41) | Sep 13, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| ASRock        | Q1900B-ITX                  | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| PC Engines    | APU2                        | [95ae240b55](https://bsd-hardware.info/?probe=95ae240b55) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| Protectli     | FW4B                        | [0553a226de](https://bsd-hardware.info/?probe=0553a226de) | Sep 13, 2022 |
| Dell          | 07WP95 A01                  | [98e67ff164](https://bsd-hardware.info/?probe=98e67ff164) | Sep 12, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [05b5d1e01a](https://bsd-hardware.info/?probe=05b5d1e01a) | Sep 12, 2022 |
| HP            | 18E7                        | [f09635a7ee](https://bsd-hardware.info/?probe=f09635a7ee) | Sep 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [2b4e2212dc](https://bsd-hardware.info/?probe=2b4e2212dc) | Sep 12, 2022 |
| HP            | 213D A01                    | [6354ddb4a8](https://bsd-hardware.info/?probe=6354ddb4a8) | Sep 12, 2022 |
| HP            | 8648                        | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Protectli     | FW4B                        | [0ccd9a9f2c](https://bsd-hardware.info/?probe=0ccd9a9f2c) | Sep 12, 2022 |
| HP            | 8054                        | [3385f78f9c](https://bsd-hardware.info/?probe=3385f78f9c) | Sep 12, 2022 |
| BESSTAR Te... | TH50                        | [71e53af7f9](https://bsd-hardware.info/?probe=71e53af7f9) | Sep 12, 2022 |
| Dell EMC      | VEP1425-V210-CPU A00        | [871a29677b](https://bsd-hardware.info/?probe=871a29677b) | Sep 12, 2022 |
| MSI           | H81M-E33                    | [b80a45410b](https://bsd-hardware.info/?probe=b80a45410b) | Sep 12, 2022 |
| HP            | 213D A01                    | [54288c6759](https://bsd-hardware.info/?probe=54288c6759) | Sep 11, 2022 |
| Intel         | S1200KP AAG34877-201        | [db5bbdec3c](https://bsd-hardware.info/?probe=db5bbdec3c) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| Unknown       | Unknown                     | [37588a8565](https://bsd-hardware.info/?probe=37588a8565) | Sep 11, 2022 |
| Unknown       | Unknown                     | [700e6ba6a9](https://bsd-hardware.info/?probe=700e6ba6a9) | Sep 11, 2022 |
| MSI           | H81M-E33                    | [66d179c5f4](https://bsd-hardware.info/?probe=66d179c5f4) | Sep 11, 2022 |
| ASUSTek       | P5Q-E                       | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Dell          | 0NW6H5 A00                  | [ce6906d604](https://bsd-hardware.info/?probe=ce6906d604) | Sep 10, 2022 |
| MSI           | A88XM-E45                   | [2df6d013e9](https://bsd-hardware.info/?probe=2df6d013e9) | Sep 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b2dc861f47](https://bsd-hardware.info/?probe=b2dc861f47) | Sep 10, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | [50ac5c0aaf](https://bsd-hardware.info/?probe=50ac5c0aaf) | Sep 10, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Maxtang       | BYT30                       | [90053990c3](https://bsd-hardware.info/?probe=90053990c3) | Sep 10, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [836927cf63](https://bsd-hardware.info/?probe=836927cf63) | Sep 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Dell          | 0KYJ8C A02                  | [7e8d44c688](https://bsd-hardware.info/?probe=7e8d44c688) | Sep 10, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | [0df35f9c64](https://bsd-hardware.info/?probe=0df35f9c64) | Sep 10, 2022 |
| ASUSTek       | PRIME X570-P                | [8eb8bf52d4](https://bsd-hardware.info/?probe=8eb8bf52d4) | Sep 10, 2022 |
| Intel         | DH87MC AAG74242-401         | [6b449e63d3](https://bsd-hardware.info/?probe=6b449e63d3) | Sep 10, 2022 |
| ASRock        | H81M-DGS                    | [3c2b784001](https://bsd-hardware.info/?probe=3c2b784001) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | [581219cbc5](https://bsd-hardware.info/?probe=581219cbc5) | Sep 09, 2022 |
| Gigabyte      | B450M DS3H V2               | [b1a126ce25](https://bsd-hardware.info/?probe=b1a126ce25) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| AZW           | Green G1                    | [b9e82f5157](https://bsd-hardware.info/?probe=b9e82f5157) | Sep 09, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | [1e62e2ea85](https://bsd-hardware.info/?probe=1e62e2ea85) | Sep 09, 2022 |
| Unknown       | Unknown                     | [1cd83a6904](https://bsd-hardware.info/?probe=1cd83a6904) | Sep 09, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| maiyunda      | www.maiyunda.com            | [8776541164](https://bsd-hardware.info/?probe=8776541164) | Sep 09, 2022 |
| Techvision    | TVI7309X B0                 | [4e393e3814](https://bsd-hardware.info/?probe=4e393e3814) | Sep 08, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [e082eca671](https://bsd-hardware.info/?probe=e082eca671) | Sep 08, 2022 |
| EPSON DIRE... | ST170E                      | [1ac571538d](https://bsd-hardware.info/?probe=1ac571538d) | Sep 08, 2022 |
| Unknown       | YL-J3060L2                  | [2210876ea3](https://bsd-hardware.info/?probe=2210876ea3) | Sep 08, 2022 |
| ASRockRack    | X470D4U2/1N1                | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| Unknown       | J3160-4L                    | [4db37ff154](https://bsd-hardware.info/?probe=4db37ff154) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | [1d81b77310](https://bsd-hardware.info/?probe=1d81b77310) | Sep 07, 2022 |
| Deciso        | Netboard A10 V2.1           | [6c88b88822](https://bsd-hardware.info/?probe=6c88b88822) | Sep 07, 2022 |
| Intel         | SYS-2USM03-6M01E            | [d4f98f18b9](https://bsd-hardware.info/?probe=d4f98f18b9) | Sep 07, 2022 |
| Protectli     | FW4B                        | [b934171c54](https://bsd-hardware.info/?probe=b934171c54) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | [3c3c40a10f](https://bsd-hardware.info/?probe=3c3c40a10f) | Sep 07, 2022 |
| Protectli     | VP2410 10                   | [f431032a32](https://bsd-hardware.info/?probe=f431032a32) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | [b803a767af](https://bsd-hardware.info/?probe=b803a767af) | Sep 06, 2022 |
| Pegatron      | IPM41-D3                    | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Intel         | J1900                       | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1495                        | [4ba1b5820e](https://bsd-hardware.info/?probe=4ba1b5820e) | Sep 06, 2022 |
| Dell          | 0200DY A02                  | [cd90f548c8](https://bsd-hardware.info/?probe=cd90f548c8) | Sep 06, 2022 |
| ASRock        | 4X4-4000 Series             | [00ee0319aa](https://bsd-hardware.info/?probe=00ee0319aa) | Sep 06, 2022 |
| Intel         | MAHOBAY                     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Unknown       | J3160-4L                    | [817b37c259](https://bsd-hardware.info/?probe=817b37c259) | Sep 06, 2022 |
| HP            | 1496                        | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| ASUSTek       | Rampage II Extreme          | [975b49af4a](https://bsd-hardware.info/?probe=975b49af4a) | Sep 05, 2022 |
| Unknown       | Unknown                     | [865dca4859](https://bsd-hardware.info/?probe=865dca4859) | Sep 05, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [3f5ad2f043](https://bsd-hardware.info/?probe=3f5ad2f043) | Sep 05, 2022 |
| Dell          | 0Y7WYT A00                  | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| PC Engines    | APU2                        | [1650d8c419](https://bsd-hardware.info/?probe=1650d8c419) | Sep 05, 2022 |
| PC Engines    | APU2                        | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| ASUSTek       | Rampage II Extreme          | [5a49c5aa98](https://bsd-hardware.info/?probe=5a49c5aa98) | Sep 05, 2022 |
| Protectli     | FW4B Ver                    | [91664c3bc1](https://bsd-hardware.info/?probe=91664c3bc1) | Sep 05, 2022 |
| CncTion       | N5105-4L                    | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| BESSTAR Te... | TH50                        | [734a8e61c4](https://bsd-hardware.info/?probe=734a8e61c4) | Sep 05, 2022 |
| HP            | 8719                        | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [34bc2f5c5b](https://bsd-hardware.info/?probe=34bc2f5c5b) | Sep 04, 2022 |
| Unknown       | Unknown                     | [c1967c7cf8](https://bsd-hardware.info/?probe=c1967c7cf8) | Sep 04, 2022 |
| Gigabyte      | GA-890FXA-UD5               | [3ee914e3a0](https://bsd-hardware.info/?probe=3ee914e3a0) | Sep 04, 2022 |
| MSI           | H81M-P33                    | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| Protectli     | FW4B Ver                    | [a769499d94](https://bsd-hardware.info/?probe=a769499d94) | Sep 04, 2022 |
| MSI           | A68HM-E33 V2                | [0f35d398cb](https://bsd-hardware.info/?probe=0f35d398cb) | Sep 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Protectli     | FW4B                        | [86a4422a0f](https://bsd-hardware.info/?probe=86a4422a0f) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Unknown       | Unknown                     | [4034fae93d](https://bsd-hardware.info/?probe=4034fae93d) | Sep 04, 2022 |
| AMD           | Inagua CRB                  | [de18cc5073](https://bsd-hardware.info/?probe=de18cc5073) | Sep 04, 2022 |
| Maxtang       | BYT30                       | [f5c34c7662](https://bsd-hardware.info/?probe=f5c34c7662) | Sep 03, 2022 |
| HP            | 1496                        | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [88d8df1e3a](https://bsd-hardware.info/?probe=88d8df1e3a) | Sep 03, 2022 |
| ASRock        | Z97 Killer                  | [fac5afc851](https://bsd-hardware.info/?probe=fac5afc851) | Sep 03, 2022 |
| ASRock        | X570S PG Riptide            | [37a7192776](https://bsd-hardware.info/?probe=37a7192776) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [72cdc4123c](https://bsd-hardware.info/?probe=72cdc4123c) | Sep 03, 2022 |
| Techvision    | TVI7309X B0                 | [9941ee7afb](https://bsd-hardware.info/?probe=9941ee7afb) | Sep 03, 2022 |
| ASRockRack    | C3558D4I-4L                 | [9beb572e0d](https://bsd-hardware.info/?probe=9beb572e0d) | Sep 03, 2022 |
| Lenovo        | ThinkCentre M70e 0833A29    | [b7c5b9a51d](https://bsd-hardware.info/?probe=b7c5b9a51d) | Sep 03, 2022 |
| ASRock        | X570S PG Riptide            | [0c17c8dc3b](https://bsd-hardware.info/?probe=0c17c8dc3b) | Sep 03, 2022 |
| AMD           | Larne CRB                   | [787a51fa78](https://bsd-hardware.info/?probe=787a51fa78) | Sep 03, 2022 |
| Dell          | 0WMJ54 A00                  | [39ee331ecb](https://bsd-hardware.info/?probe=39ee331ecb) | Sep 03, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [62946d2956](https://bsd-hardware.info/?probe=62946d2956) | Sep 03, 2022 |
| Unknown       | Unknown                     | [b2e4674180](https://bsd-hardware.info/?probe=b2e4674180) | Sep 03, 2022 |
| Intel         | DQ67EP AAG12529-307         | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| MW            | GMLK-2_5G4L                 | [bb379f7083](https://bsd-hardware.info/?probe=bb379f7083) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Unknown       | YL-E3845L4-V2               | [3082ae8ab3](https://bsd-hardware.info/?probe=3082ae8ab3) | Sep 02, 2022 |
| ASUSTek       | H81M-A                      | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [1e05b51bf1](https://bsd-hardware.info/?probe=1e05b51bf1) | Sep 02, 2022 |
| Protectli     | FW4B                        | [1e384b1cf6](https://bsd-hardware.info/?probe=1e384b1cf6) | Sep 02, 2022 |
| Intel         | CRESCENTBAY                 | [b0ad128162](https://bsd-hardware.info/?probe=b0ad128162) | Sep 02, 2022 |
| Gigabyte      | H270-HD3-CF                 | [ce9dc034c9](https://bsd-hardware.info/?probe=ce9dc034c9) | Sep 02, 2022 |
| MSI           | H410M-A PRO                 | [d71ca3999c](https://bsd-hardware.info/?probe=d71ca3999c) | Sep 02, 2022 |
| ASUSTek       | Rampage II Extreme          | [8575ceca09](https://bsd-hardware.info/?probe=8575ceca09) | Sep 02, 2022 |
| HP            | 213D A01                    | [5e8fa931ef](https://bsd-hardware.info/?probe=5e8fa931ef) | Sep 02, 2022 |
| Lenovo        | YangTianM6880N              | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Intel         | MAHOBAY                     | [1c24e80838](https://bsd-hardware.info/?probe=1c24e80838) | Sep 02, 2022 |
| Intel         | D34010WYK H14771-305        | [ab544a7950](https://bsd-hardware.info/?probe=ab544a7950) | Sep 02, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [73304d07bb](https://bsd-hardware.info/?probe=73304d07bb) | Sep 01, 2022 |
| Unknown       | DTB1168                     | [e924ba2a44](https://bsd-hardware.info/?probe=e924ba2a44) | Sep 01, 2022 |
| Unknown       | Unknown                     | [f2a26e2adc](https://bsd-hardware.info/?probe=f2a26e2adc) | Sep 01, 2022 |
| Unknown       | Unknown                     | [9f6f4424c2](https://bsd-hardware.info/?probe=9f6f4424c2) | Sep 01, 2022 |
| Jingsha       | x79-P3 by xUz               | [9148bf85ec](https://bsd-hardware.info/?probe=9148bf85ec) | Sep 01, 2022 |
| HP            | 1496                        | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| AAEON         | UP-APL01 V0.4               | [a8d73a9156](https://bsd-hardware.info/?probe=a8d73a9156) | Sep 01, 2022 |
| Unknown       | HX90                        | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Unknown       | Unknown                     | [b62a001fe9](https://bsd-hardware.info/?probe=b62a001fe9) | Sep 01, 2022 |
| ASRock        | H81M-ITX                    | [d26f88ae78](https://bsd-hardware.info/?probe=d26f88ae78) | Sep 01, 2022 |
| maiyunda      | www.maiyunda.com            | [721abbc383](https://bsd-hardware.info/?probe=721abbc383) | Sep 01, 2022 |
| Dell          | 07F37C A01                  | [53de9cce89](https://bsd-hardware.info/?probe=53de9cce89) | Sep 01, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Intel         | MAHOBAY                     | [78b1cb4ae5](https://bsd-hardware.info/?probe=78b1cb4ae5) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | [50fbb0435c](https://bsd-hardware.info/?probe=50fbb0435c) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | [200b8d381e](https://bsd-hardware.info/?probe=200b8d381e) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | [ebc79d7728](https://bsd-hardware.info/?probe=ebc79d7728) | Aug 31, 2022 |
| MW            | GMLK-2_5G4L                 | [63587e2fca](https://bsd-hardware.info/?probe=63587e2fca) | Aug 31, 2022 |
| ASUSTek       | EX-H110M-V                  | [35e6c8463a](https://bsd-hardware.info/?probe=35e6c8463a) | Aug 31, 2022 |
| Dell          | 0TP412                      | [3ac4a5aa72](https://bsd-hardware.info/?probe=3ac4a5aa72) | Aug 31, 2022 |
| Dell          | 0G261D A00                  | [c77b23d1a7](https://bsd-hardware.info/?probe=c77b23d1a7) | Aug 31, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [0563755b0d](https://bsd-hardware.info/?probe=0563755b0d) | Aug 31, 2022 |
| Unknown       | Unknown                     | [e8259494a3](https://bsd-hardware.info/?probe=e8259494a3) | Aug 31, 2022 |
| Intel         | DENLOW_WS                   | [40053c983b](https://bsd-hardware.info/?probe=40053c983b) | Aug 31, 2022 |
| HP            | 213D A01                    | [c495fb5448](https://bsd-hardware.info/?probe=c495fb5448) | Aug 30, 2022 |
| Unknown       | Unknown                     | [9422de47ab](https://bsd-hardware.info/?probe=9422de47ab) | Aug 30, 2022 |
| Gigabyte      | J1900N-D3V                  | [e2ad4d8035](https://bsd-hardware.info/?probe=e2ad4d8035) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | [d455ed153a](https://bsd-hardware.info/?probe=d455ed153a) | Aug 30, 2022 |
| Intel         | DENLOW_WS                   | [067a217959](https://bsd-hardware.info/?probe=067a217959) | Aug 30, 2022 |
| ASUSTek       | Maximus VIII HERO           | [a47c1e0c84](https://bsd-hardware.info/?probe=a47c1e0c84) | Aug 30, 2022 |
| Unknown       | Unknown                     | [98d9c506c9](https://bsd-hardware.info/?probe=98d9c506c9) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | [9d367a6989](https://bsd-hardware.info/?probe=9d367a6989) | Aug 30, 2022 |
| Unknown       | Unknown                     | [6bc59f4024](https://bsd-hardware.info/?probe=6bc59f4024) | Aug 30, 2022 |
| Protectli     | FW4B Ver                    | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| Unknown       | Unknown                     | [a01c1ad205](https://bsd-hardware.info/?probe=a01c1ad205) | Aug 29, 2022 |
| Gigabyte      | J1900N-D3V                  | [567bfe0b9f](https://bsd-hardware.info/?probe=567bfe0b9f) | Aug 29, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Dell          | 0NW6H5 A00                  | [8d047e7667](https://bsd-hardware.info/?probe=8d047e7667) | Aug 29, 2022 |
| Unknown       | Unknown                     | [411daea5f8](https://bsd-hardware.info/?probe=411daea5f8) | Aug 29, 2022 |
| MW            | GMLK-2_5G4L                 | [19e3294fe9](https://bsd-hardware.info/?probe=19e3294fe9) | Aug 29, 2022 |
| Acer          | FIH57                       | [78265cbc90](https://bsd-hardware.info/?probe=78265cbc90) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [4d7efd6aa6](https://bsd-hardware.info/?probe=4d7efd6aa6) | Aug 28, 2022 |
| Dell          | 0654JC A02                  | [07144a803b](https://bsd-hardware.info/?probe=07144a803b) | Aug 28, 2022 |
| Gigabyte      | H81M-DS2                    | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| Dell          | 00V62H A01                  | [e7dc9cc5ee](https://bsd-hardware.info/?probe=e7dc9cc5ee) | Aug 28, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [df3df2855b](https://bsd-hardware.info/?probe=df3df2855b) | Aug 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [72aaa26104](https://bsd-hardware.info/?probe=72aaa26104) | Aug 28, 2022 |
| ASUSTek       | PRIME X570-P                | [0f1eabf01e](https://bsd-hardware.info/?probe=0f1eabf01e) | Aug 27, 2022 |
| YANYU         | R250                        | [c4f1ec0d5b](https://bsd-hardware.info/?probe=c4f1ec0d5b) | Aug 27, 2022 |
| Intel         | CRESCENTBAY                 | [184a8697e9](https://bsd-hardware.info/?probe=184a8697e9) | Aug 27, 2022 |
| Intel         | CRESCENTBAY                 | [1765bd0426](https://bsd-hardware.info/?probe=1765bd0426) | Aug 27, 2022 |
| Gigabyte      | A320M-H-CF                  | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| MW            | GMLK-2_5G4L                 | [29d63f7027](https://bsd-hardware.info/?probe=29d63f7027) | Aug 27, 2022 |
| Gigabyte      | B365M DS3H                  | [0d7d7288c0](https://bsd-hardware.info/?probe=0d7d7288c0) | Aug 27, 2022 |
| Gigabyte      | B365M DS3H                  | [0a90c3c566](https://bsd-hardware.info/?probe=0a90c3c566) | Aug 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | [05bb23ae87](https://bsd-hardware.info/?probe=05bb23ae87) | Aug 26, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | [a480263c28](https://bsd-hardware.info/?probe=a480263c28) | Aug 26, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.7.7   | 201      | 3.21%   |
| helloSystem 0.7.0 | 174      | 2.78%   |
| OPNsense 21.1     | 170      | 2.72%   |
| OPNsense 21.7.1   | 167      | 2.67%   |
| OPNsense 21.1.5   | 167      | 2.67%   |
| OPNsense 22.1     | 166      | 2.65%   |
| OPNsense 21.7.3   | 166      | 2.65%   |
| OPNsense 22.7.4   | 161      | 2.57%   |
| OPNsense 20.7.8   | 159      | 2.54%   |
| OPNsense 21.1.3   | 148      | 2.36%   |
| OPNsense 22.1.6   | 138      | 2.2%    |
| OPNsense 22.1.8   | 137      | 2.19%   |
| OPNsense 21.1.4   | 129      | 2.06%   |
| OPNsense 22.1.10  | 125      | 2%      |
| OPNsense 22.7.6   | 124      | 1.98%   |
| helloSystem 0.5.0 | 115      | 1.84%   |
| OPNsense 21.1.1   | 111      | 1.77%   |
| OpenBSD 6.8       | 109      | 1.74%   |
| OPNsense 21.7.6   | 99       | 1.58%   |
| OPNsense 21.1.2   | 99       | 1.58%   |
| OPNsense 22.1.4   | 93       | 1.49%   |
| OPNsense 22.7     | 91       | 1.45%   |
| helloSystem 0.4.0 | 90       | 1.44%   |
| OPNsense 22.7.8   | 89       | 1.42%   |
| OPNsense 22.1.2   | 89       | 1.42%   |
| OPNsense 21.7.5   | 88       | 1.41%   |
| OPNsense 21.1.8   | 87       | 1.39%   |
| OPNsense 21.1.7   | 87       | 1.39%   |
| OPNsense 22.7.2   | 85       | 1.36%   |
| OPNsense 22.7.7   | 83       | 1.33%   |
| OPNsense 21.1.6   | 82       | 1.31%   |
| OPNsense 22.1.1   | 78       | 1.25%   |
| FreeBSD 13.0      | 77       | 1.23%   |
| OPNsense 22.1.7   | 76       | 1.21%   |
| FreeBSD 13.1      | 74       | 1.18%   |
| OPNsense 21.7     | 71       | 1.13%   |
| OPNsense 21.7.4   | 70       | 1.12%   |
| OPNsense 21.7.2   | 69       | 1.1%    |
| FreeBSD 12.2      | 65       | 1.04%   |
| OPNsense 22.1.9   | 64       | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 2962     | 62.01%  |
| FreeBSD     | 843      | 17.65%  |
| helloSystem | 456      | 9.55%   |
| OpenBSD     | 230      | 4.81%   |
| GhostBSD    | 71       | 1.49%   |
| NomadBSD    | 44       | 0.92%   |
| TrueNAS     | 35       | 0.73%   |
| NetBSD      | 35       | 0.73%   |
| pfSense     | 25       | 0.52%   |
| FreeNAS     | 24       | 0.5%    |
| MidnightBSD | 9        | 0.19%   |
| XigmaNAS    | 8        | 0.17%   |
| DragonFly   | 8        | 0.17%   |
| MyBee       | 7        | 0.15%   |
| HardenedBSD | 5        | 0.1%    |
| FuryBSD     | 5        | 0.1%    |
| ClonOS      | 3        | 0.06%   |
| Ting        | 2        | 0.04%   |
| PC-BSD      | 2        | 0.04%   |
| OS108       | 2        | 0.04%   |
| FuguIta     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 4620     | 97.59%  |
| arm64   | 45       | 0.95%   |
| i386    | 44       | 0.93%   |
| arm     | 8        | 0.17%   |
| evbarm  | 5        | 0.11%   |
| sparc64 | 3        | 0.06%   |
| powerpc | 2        | 0.04%   |
| octeon  | 2        | 0.04%   |
| macppc  | 2        | 0.04%   |
| armv7   | 2        | 0.04%   |
| riscv   | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Console          | 3546     | 73.69%  |
| helloDesktop     | 516      | 10.72%  |
| KDE5             | 150      | 3.12%   |
| XFCE             | 132      | 2.74%   |
| MATE             | 102      | 2.12%   |
| fvwm             | 86       | 1.79%   |
| Openbox          | 63       | 1.31%   |
| TWM              | 55       | 1.14%   |
| GNOME            | 55       | 1.14%   |
| i3               | 26       | 0.54%   |
| Cinnamon         | 11       | 0.23%   |
| Fluxbox          | 10       | 0.21%   |
| AwesomeWM        | 9        | 0.19%   |
| LXQt             | 6        | 0.12%   |
| LXDE             | 6        | 0.12%   |
| Enlightenment    | 6        | 0.12%   |
| Lumina           | 5        | 0.1%    |
| Window Maker     | 3        | 0.06%   |
| GNUstep          | 3        | 0.06%   |
| DWM              | 3        | 0.06%   |
| CDE              | 3        | 0.06%   |
| xfwm             | 2        | 0.04%   |
| xinitrc          | 1        | 0.02%   |
| Xfwm4            | 1        | 0.02%   |
| X-Cinnamon       | 1        | 0.02%   |
| spectrwm         | 1        | 0.02%   |
| Ratpoison        | 1        | 0.02%   |
| plasma           | 1        | 0.02%   |
| Picom            | 1        | 0.02%   |
| PekWM            | 1        | 0.02%   |
| Metacity (Marco) | 1        | 0.02%   |
| KWin             | 1        | 0.02%   |
| filer            | 1        | 0.02%   |
| CTWM             | 1        | 0.02%   |
| Compton          | 1        | 0.02%   |
| akonadi_newm     | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 3601     | 75.71%  |
| X11     | 1146     | 24.1%   |
| Wayland | 9        | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 3874     | 81.1%   |
| SLiM    | 566      | 11.85%  |
| SDDM    | 135      | 2.83%   |
| LightDM | 107      | 2.24%   |
| XDM     | 55       | 1.15%   |
| GDM     | 38       | 0.8%    |
| Ly      | 2        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 3496     | 72.49%  |
| en_US            | 708      | 14.68%  |
| C                | 359      | 7.44%   |
| ru_RU            | 93       | 1.93%   |
| de_DE            | 33       | 0.68%   |
| fr_FR            | 17       | 0.35%   |
| en_GB            | 14       | 0.29%   |
| es_ES            | 11       | 0.23%   |
| pt_BR            | 9        | 0.19%   |
| it_IT            | 7        | 0.15%   |
| en_AU            | 7        | 0.15%   |
| uk_UA            | 6        | 0.12%   |
| ja_JP            | 6        | 0.12%   |
| fi_FI            | 5        | 0.1%    |
| en_CA            | 5        | 0.1%    |
| zh_CN            | 4        | 0.08%   |
| el_GR            | 4        | 0.08%   |
| sv_SE            | 3        | 0.06%   |
| hu_HU            | 3        | 0.06%   |
| es_AR            | 3        | 0.06%   |
| tr_TR            | 2        | 0.04%   |
| ru_RU.KOI8-R     | 2        | 0.04%   |
| pl_PL            | 2        | 0.04%   |
| nb_NO            | 2        | 0.04%   |
| en_IE            | 2        | 0.04%   |
| zh_TW            | 1        | 0.02%   |
| sv_SE.US-ASCII   | 1        | 0.02%   |
| sl_SI            | 1        | 0.02%   |
| sk_SK            | 1        | 0.02%   |
| nl_NL            | 1        | 0.02%   |
| it_IT.ISO8859-15 | 1        | 0.02%   |
| fr_FR.US-ASCII   | 1        | 0.02%   |
| fi_FI.ISO8859-15 | 1        | 0.02%   |
| et_EE.US-ASCII   | 1        | 0.02%   |
| es_MX            | 1        | 0.02%   |
| es_ES.ISO8859-15 | 1        | 0.02%   |
| en_US.utf-8      | 1        | 0.02%   |
| en_US.ISO8859-1  | 1        | 0.02%   |
| en_GB.US-ASCII   | 1        | 0.02%   |
| en_DE            | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 3809     | 79.34%  |
| BIOS | 992      | 20.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 2723     | 56.13%  |
| Zfs     | 1748     | 36.03%  |
| Ffs     | 231      | 4.76%   |
| Cd9660  | 132      | 2.72%   |
| Hammer2 | 8        | 0.16%   |
| Unknown | 5        | 0.1%    |
| XXX     | 3        | 0.06%   |
| Nfs     | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 4219     | 88.39%  |
| MBR     | 477      | 9.99%   |
| Unknown | 70       | 1.47%   |
| BSD     | 7        | 0.15%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 567      | 11.98%  |
| Unknown                    | 508      | 10.73%  |
| Dell                       | 392      | 8.28%   |
| Hewlett-Packard            | 376      | 7.94%   |
| Gigabyte Technology        | 349      | 7.37%   |
| ASRock                     | 344      | 7.27%   |
| Intel                      | 276      | 5.83%   |
| PC Engines                 | 275      | 5.81%   |
| Protectli                  | 239      | 5.05%   |
| MSI                        | 213      | 4.5%    |
| Lenovo                     | 158      | 3.34%   |
| Supermicro                 | 150      | 3.17%   |
| Fujitsu                    | 106      | 2.24%   |
| Shuttle                    | 52       | 1.1%    |
| Acer                       | 38       | 0.8%    |
| Biostar                    | 35       | 0.74%   |
| HARDKERNEL                 | 28       | 0.59%   |
| ASRockRack                 | 27       | 0.57%   |
| MW                         | 26       | 0.55%   |
| BESSTAR Tech               | 26       | 0.55%   |
| Foxconn                    | 22       | 0.46%   |
| Deciso                     | 21       | 0.44%   |
| Pegatron                   | 19       | 0.4%    |
| AZW                        | 19       | 0.4%    |
| Techvision                 | 18       | 0.38%   |
| YANYU                      | 14       | 0.3%    |
| ShenZhen MinWin Technology | 14       | 0.3%    |
| Apple                      | 14       | 0.3%    |
| CheckPoint                 | 12       | 0.25%   |
| AAEON                      | 12       | 0.25%   |
| Seeed Studio               | 11       | 0.23%   |
| ECS                        | 11       | 0.23%   |
| Thomas-Krenn.AG            | 10       | 0.21%   |
| Cisco                      | 10       | 0.21%   |
| AMI                        | 10       | 0.21%   |
| Yanling                    | 9        | 0.19%   |
| SeeedStudio                | 9        | 0.19%   |
| NF541                      | 9        | 0.19%   |
| Inventec                   | 9        | 0.19%   |
| CncTion                    | 9        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 526      | 11.11%  |
| PC Engines APU2                | 133      | 2.81%   |
| Protectli FW4B                 | 98       | 2.07%   |
| Intel Q3XXG4-P V1.0            | 97       | 2.05%   |
| PC Engines apu4                | 90       | 1.9%    |
| Protectli FW6                  | 74       | 1.56%   |
| ASUS All Series                | 69       | 1.46%   |
| HP t620 PLUS Quad Core TC      | 46       | 0.97%   |
| Fujitsu FUTRO S920             | 41       | 0.87%   |
| Dell OptiPlex 9020             | 38       | 0.8%    |
| Dell OptiPlex 3020             | 30       | 0.63%   |
| MW GMLK-2_5G4L                 | 26       | 0.55%   |
| HARDKERNEL ODROID-H2           | 26       | 0.55%   |
| Dell OptiPlex 7010             | 25       | 0.53%   |
| Supermicro X9SCL/X9SCM         | 23       | 0.49%   |
| PC Engines APU                 | 20       | 0.42%   |
| HP ProLiant MicroServer Gen8   | 20       | 0.42%   |
| HP EliteDesk 800 G1 SFF        | 20       | 0.42%   |
| PC Engines APU3                | 19       | 0.4%    |
| Techvision TVI7309X            | 18       | 0.38%   |
| Protectli VP2410               | 17       | 0.36%   |
| Protectli FW2B                 | 15       | 0.32%   |
| HP ProDesk 600 G1 SFF          | 15       | 0.32%   |
| HP Compaq Elite 8300 SFF       | 15       | 0.32%   |
| Dell OptiPlex 790              | 15       | 0.32%   |
| Intel CRESCENTBAY              | 14       | 0.3%    |
| Dell OptiPlex 990              | 14       | 0.3%    |
| Dell OptiPlex 390              | 13       | 0.27%   |
| Dell OptiPlex 3010             | 13       | 0.27%   |
| HP ProLiant MicroServer        | 12       | 0.25%   |
| Supermicro X7SPA-HF            | 11       | 0.23%   |
| PC Engines apu1                | 11       | 0.23%   |
| Dell OptiPlex 3040             | 11       | 0.23%   |
| BESSTAR Tech X35G              | 11       | 0.23%   |
| AZW GK55                       | 11       | 0.23%   |
| ShenZhen MinWin MW-NANO-APL-4L | 10       | 0.21%   |
| Intel MAHOBAY                  | 10       | 0.21%   |
| HP EliteDesk 800 G2 SFF        | 10       | 0.21%   |
| HP Compaq Pro 6300 SFF         | 10       | 0.21%   |
| Gigabyte B450M DS3H            | 10       | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 526      | 11.11%  |
| Dell OptiPlex        | 283      | 5.98%   |
| PC Engines APU2      | 133      | 2.81%   |
| Lenovo ThinkCentre   | 111      | 2.34%   |
| ASUS PRIME           | 102      | 2.15%   |
| Protectli FW4B       | 98       | 2.07%   |
| Intel Q3XXG4-P       | 98       | 2.07%   |
| PC Engines apu4      | 90       | 1.9%    |
| HP Compaq            | 76       | 1.61%   |
| Protectli FW6        | 74       | 1.56%   |
| ASUS All             | 69       | 1.46%   |
| HP ProDesk           | 60       | 1.27%   |
| Fujitsu FUTRO        | 58       | 1.23%   |
| HP EliteDesk         | 55       | 1.16%   |
| HP ProLiant          | 54       | 1.14%   |
| HP t620              | 52       | 1.1%    |
| ASUS ROG             | 48       | 1.01%   |
| Dell Precision       | 41       | 0.87%   |
| ASUS TUF             | 41       | 0.87%   |
| MW GMLK-2            | 26       | 0.55%   |
| HARDKERNEL ODROID-H2 | 26       | 0.55%   |
| Fujitsu ESPRIMO      | 25       | 0.53%   |
| Supermicro X9SCL     | 23       | 0.49%   |
| Acer Aspire          | 23       | 0.49%   |
| Gigabyte X570        | 21       | 0.44%   |
| Dell PowerEdge       | 21       | 0.44%   |
| ASRock X570          | 21       | 0.44%   |
| PC Engines APU       | 20       | 0.42%   |
| Dell Inspiron        | 20       | 0.42%   |
| Deciso Netboard      | 20       | 0.42%   |
| PC Engines APU3      | 19       | 0.4%    |
| ASUS M5A78L-M        | 19       | 0.4%    |
| Techvision TVI7309X  | 18       | 0.38%   |
| Protectli VP2410     | 17       | 0.36%   |
| Protectli FW2B       | 15       | 0.32%   |
| Gigabyte B450M       | 15       | 0.32%   |
| Intel CRESCENTBAY    | 14       | 0.3%    |
| ASUS P8Z77-V         | 13       | 0.27%   |
| HP Slim              | 12       | 0.25%   |
| ASRock B450M         | 12       | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 613      | 12.95%  |
| 2019    | 516      | 10.9%   |
| 2020    | 446      | 9.42%   |
| 2016    | 444      | 9.38%   |
| 2014    | 392      | 8.28%   |
| 2021    | 358      | 7.56%   |
| 2013    | 324      | 6.84%   |
| 2012    | 260      | 5.49%   |
| 2017    | 254      | 5.37%   |
| 2011    | 226      | 4.77%   |
| 2015    | 192      | 4.06%   |
| 2022    | 165      | 3.49%   |
| 2010    | 162      | 3.42%   |
| 2009    | 128      | 2.7%    |
| Unknown | 101      | 2.13%   |
| 2008    | 80       | 1.69%   |
| 2007    | 41       | 0.87%   |
| 2006    | 14       | 0.3%    |
| 2004    | 6        | 0.13%   |
| 2005    | 5        | 0.11%   |
| 2003    | 3        | 0.06%   |
| 2002    | 2        | 0.04%   |
| 2001    | 2        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4734     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4357     | 92.04%  |
| Yes  | 377      | 7.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1664     | 34.49%  |
| 4.01-8.0        | 1126     | 23.34%  |
| 16.01-24.0      | 1011     | 20.96%  |
| 32.01-64.0      | 461      | 9.56%   |
| 2.01-3.0        | 181      | 3.75%   |
| 64.01-256.0     | 156      | 3.23%   |
| 24.01-32.0      | 65       | 1.35%   |
| 3.01-4.0        | 61       | 1.26%   |
| 0.51-1.0        | 39       | 0.81%   |
| 1.01-2.0        | 37       | 0.77%   |
| 0.01-0.5        | 17       | 0.35%   |
| More than 256.0 | 5        | 0.1%    |
| Unknown         | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 2517     | 51.05%  |
| 0.51-1.0    | 1393     | 28.26%  |
| 1.01-2.0    | 528      | 10.71%  |
| 2.01-3.0    | 113      | 2.29%   |
| 4.01-8.0    | 105      | 2.13%   |
| 3.01-4.0    | 82       | 1.66%   |
| 8.01-16.0   | 48       | 0.97%   |
| Unknown     | 42       | 0.85%   |
| 0           | 32       | 0.65%   |
| 16.01-24.0  | 25       | 0.51%   |
| 24.01-32.0  | 19       | 0.39%   |
| 32.01-64.0  | 17       | 0.34%   |
| 64.01-256.0 | 9        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 3182     | 65.2%   |
| 2      | 652      | 13.36%  |
| 0      | 347      | 7.11%   |
| 3      | 270      | 5.53%   |
| 4      | 182      | 3.73%   |
| 5      | 93       | 1.91%   |
| 6      | 58       | 1.19%   |
| 7      | 31       | 0.64%   |
| 8      | 14       | 0.29%   |
| 9      | 10       | 0.2%    |
| 10     | 9        | 0.18%   |
| 12     | 6        | 0.12%   |
| 14     | 4        | 0.08%   |
| 11     | 4        | 0.08%   |
| 17     | 3        | 0.06%   |
| 23     | 2        | 0.04%   |
| 21     | 2        | 0.04%   |
| 19     | 2        | 0.04%   |
| 13     | 2        | 0.04%   |
| 40     | 1        | 0.02%   |
| 27     | 1        | 0.02%   |
| 26     | 1        | 0.02%   |
| 22     | 1        | 0.02%   |
| 18     | 1        | 0.02%   |
| 16     | 1        | 0.02%   |
| 15     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3895     | 81.57%  |
| Yes       | 880      | 18.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4652     | 98.27%  |
| No        | 82       | 1.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3828     | 80.1%   |
| Yes       | 951      | 19.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4216     | 88.57%  |
| Yes       | 544      | 11.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1255     | 26.41%  |
| Germany      | 816      | 17.17%  |
| Russia       | 263      | 5.53%   |
| UK           | 190      | 4%      |
| Canada       | 186      | 3.91%   |
| France       | 183      | 3.85%   |
| Netherlands  | 124      | 2.61%   |
| Australia    | 118      | 2.48%   |
| Poland       | 107      | 2.25%   |
| Switzerland  | 101      | 2.13%   |
| Brazil       | 101      | 2.13%   |
| Austria      | 90       | 1.89%   |
| Italy        | 88       | 1.85%   |
| Spain        | 78       | 1.64%   |
| Sweden       | 75       | 1.58%   |
| China        | 64       | 1.35%   |
| Ukraine      | 51       | 1.07%   |
| Czechia      | 46       | 0.97%   |
| Finland      | 43       | 0.9%    |
| Hungary      | 41       | 0.86%   |
| Taiwan       | 39       | 0.82%   |
| Norway       | 38       | 0.8%    |
| Romania      | 36       | 0.76%   |
| Belgium      | 34       | 0.72%   |
| Japan        | 31       | 0.65%   |
| India        | 31       | 0.65%   |
| Denmark      | 30       | 0.63%   |
| Portugal     | 29       | 0.61%   |
| Indonesia    | 28       | 0.59%   |
| South Korea  | 24       | 0.51%   |
| New Zealand  | 24       | 0.51%   |
| Mexico       | 24       | 0.51%   |
| Greece       | 19       | 0.4%    |
| Thailand     | 18       | 0.38%   |
| South Africa | 18       | 0.38%   |
| Argentina    | 18       | 0.38%   |
| Bulgaria     | 16       | 0.34%   |
| Israel       | 14       | 0.29%   |
| Turkey       | 13       | 0.27%   |
| Lithuania    | 13       | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 85       | 1.62%   |
| Berlin            | 78       | 1.49%   |
| Vienna            | 48       | 0.92%   |
| Paris             | 42       | 0.8%    |
| Munich            | 41       | 0.78%   |
| Sydney            | 33       | 0.63%   |
| Hamburg           | 29       | 0.55%   |
| St Petersburg     | 24       | 0.46%   |
| Frankfurt am Main | 24       | 0.46%   |
| Cologne           | 24       | 0.46%   |
| Amsterdam         | 24       | 0.46%   |
| London            | 23       | 0.44%   |
| Denver            | 23       | 0.44%   |
| Zurich            | 22       | 0.42%   |
| Helsinki          | 21       | 0.4%    |
| Melbourne         | 20       | 0.38%   |
| Kyiv              | 20       | 0.38%   |
| Toronto           | 19       | 0.36%   |
| Chicago           | 19       | 0.36%   |
| Bucharest         | 19       | 0.36%   |
| Milan             | 17       | 0.32%   |
| Jakarta           | 17       | 0.32%   |
| Perth             | 16       | 0.31%   |
| Madrid            | 16       | 0.31%   |
| Warsaw            | 15       | 0.29%   |
| Seattle           | 15       | 0.29%   |
| New York          | 15       | 0.29%   |
| Stuttgart         | 14       | 0.27%   |
| Karlsruhe         | 14       | 0.27%   |
| Brooklyn          | 14       | 0.27%   |
| Brisbane          | 14       | 0.27%   |
| Rochester         | 13       | 0.25%   |
| Portland          | 13       | 0.25%   |
| Ottawa            | 13       | 0.25%   |
| Montreal          | 13       | 0.25%   |
| SГЈo Paulo      | 12       | 0.23%   |
| Stockholm         | 12       | 0.23%   |
| Singapore         | 12       | 0.23%   |
| Prague            | 12       | 0.23%   |
| Oslo              | 12       | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 859      | 1460   | 14.39%  |
| WDC                 | 849      | 1975   | 14.22%  |
| Seagate             | 706      | 1465   | 11.82%  |
| Kingston            | 496      | 712    | 8.31%   |
| Crucial             | 301      | 444    | 5.04%   |
| Toshiba             | 247      | 451    | 4.14%   |
| SanDisk             | 238      | 320    | 3.99%   |
| Transcend           | 232      | 344    | 3.89%   |
| Intel               | 202      | 342    | 3.38%   |
| Hoodisk             | 150      | 217    | 2.51%   |
| Phison              | 132      | 184    | 2.21%   |
| Hitachi             | 130      | 242    | 2.18%   |
| A-DATA Technology   | 112      | 163    | 1.88%   |
| China               | 95       | 132    | 1.59%   |
| HGST                | 78       | 175    | 1.31%   |
| OCZ                 | 58       | 76     | 0.97%   |
| SPCC                | 56       | 93     | 0.94%   |
| Protectli           | 49       | 79     | 0.82%   |
| PNY                 | 49       | 86     | 0.82%   |
| Micron Technology   | 47       | 80     | 0.79%   |
| SK hynix            | 43       | 59     | 0.72%   |
| Dogfish             | 39       | 59     | 0.65%   |
| Apacer              | 39       | 43     | 0.65%   |
| FORESEE             | 37       | 45     | 0.62%   |
| Corsair             | 37       | 62     | 0.62%   |
| BIWIN               | 34       | 48     | 0.57%   |
| Intenso             | 33       | 58     | 0.55%   |
| Hewlett-Packard     | 33       | 75     | 0.55%   |
| NVMe                | 30       | 42     | 0.5%    |
| Innodisk            | 28       | 32     | 0.47%   |
| Patriot             | 23       | 35     | 0.39%   |
| Maxtor              | 23       | 28     | 0.39%   |
| LITEONIT            | 23       | 26     | 0.39%   |
| Goodram             | 21       | 34     | 0.35%   |
| KingSpec            | 20       | 28     | 0.33%   |
| Silicon Motion      | 18       | 22     | 0.3%    |
| LITEON              | 18       | 25     | 0.3%    |
| Gigabyte Technology | 18       | 22     | 0.3%    |
| Plextor             | 16       | 26     | 0.27%   |
| OPENBSD             | 13       | 19     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Phison SATA SSD 16GB            | 74       | 1.11%   |
| Kingston SA400S37240G 240GB     | 72       | 1.08%   |
| Samsung SSD 850 EVO 250GB       | 66       | 0.99%   |
| Kingston SA400S37120G 120GB     | 60       | 0.9%    |
| Seagate ST500DM002-1BD142 500GB | 55       | 0.82%   |
| Kingston SUV500MS120G 120GB     | 55       | 0.82%   |
| Crucial CT240BX500SSD1 240GB    | 44       | 0.66%   |
| Samsung SSD 860 EVO 500GB       | 42       | 0.63%   |
| Samsung SSD 860 EVO 250GB       | 42       | 0.63%   |
| Hoodisk SSD 32GB                | 42       | 0.63%   |
| Transcend TS128GMSA230S 128GB   | 40       | 0.6%    |
| Hoodisk SSD 64GB                | 40       | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB  | 38       | 0.57%   |
| Hoodisk SSD 128GB               | 38       | 0.57%   |
| Toshiba DT01ACA100 1TB          | 36       | 0.54%   |
| Kingston SUV500MS240G 240GB     | 33       | 0.49%   |
| Crucial CT250MX500SSD1 250GB    | 32       | 0.48%   |
| Samsung SSD 850 EVO 500GB       | 30       | 0.45%   |
| Kingston SV300S37A120G 120GB    | 29       | 0.43%   |
| Crucial CT120BX500SSD1 120GB    | 28       | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB        | 26       | 0.39%   |
| BIWIN SSD 128GB                 | 25       | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB        | 24       | 0.36%   |
| Transcend TS64GMSA230S 64GB     | 23       | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB  | 23       | 0.34%   |
| Samsung SSD 860 EVO 1TB         | 22       | 0.33%   |
| Crucial CT500MX500SSD1 500GB    | 22       | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB  | 21       | 0.31%   |
| Samsung SSD 840 EVO 250GB       | 21       | 0.31%   |
| PNY CS900 120GB SSD             | 21       | 0.31%   |
| Kingston SKC600MS256G 256GB     | 21       | 0.31%   |
| China SATA SSD 16GB             | 21       | 0.31%   |
| WDC WD30EFRX-68EUZN0 3TB        | 20       | 0.3%    |
| Seagate ST3500418AS 500GB       | 20       | 0.3%    |
| Samsung SSD 840 EVO 120GB       | 20       | 0.3%    |
| Protectli 120GB mSATA           | 20       | 0.3%    |
| A-DATA SU650 120GB              | 20       | 0.3%    |
| Seagate ST2000DM008-2FR102 2TB  | 19       | 0.28%   |
| Seagate ST1000DM003-1ER162 1TB  | 19       | 0.28%   |
| Samsung SSD 870 EVO 250GB       | 19       | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 707      | 1672   | 34.27%  |
| Seagate                            | 688      | 1429   | 33.35%  |
| Toshiba                            | 205      | 383    | 9.94%   |
| Hitachi                            | 130      | 242    | 6.3%    |
| Samsung Electronics                | 111      | 157    | 5.38%   |
| HGST                               | 78       | 175    | 3.78%   |
| Maxtor                             | 23       | 28     | 1.11%   |
| Hewlett-Packard                    | 19       | 45     | 0.92%   |
| NVMe                               | 16       | 24     | 0.78%   |
| OPENBSD                            | 13       | 19     | 0.63%   |
| Fujitsu                            | 8        | 10     | 0.39%   |
| Apple                              | 7        | 10     | 0.34%   |
| Dell                               | 6        | 10     | 0.29%   |
| LSI                                | 4        | 7      | 0.19%   |
| HPE                                | 4        | 11     | 0.19%   |
| USB                                | 3        | 3      | 0.15%   |
| HPT                                | 3        | 35     | 0.15%   |
| Generic                            | 3        | 3      | 0.15%   |
| WD MediaMax                        | 2        | 5      | 0.1%    |
| StoreJet                           | 2        | 2      | 0.1%    |
| Multiple                           | 2        | 2      | 0.1%    |
| MaxDigital                         | 2        | 2      | 0.1%    |
| Lexar                              | 2        | 2      | 0.1%    |
| JetFlash                           | 2        | 2      | 0.1%    |
| IBM                                | 2        | 2      | 0.1%    |
| ASMT                               | 2        | 2      | 0.1%    |
| Adaptec                            | 2        | 2      | 0.1%    |
| SSDPR-CX                           | 1        | 1      | 0.05%   |
| SABRENT                            | 1        | 1      | 0.05%   |
| QUANTUM                            | 1        | 2      | 0.05%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.05%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.05%   |
| Product:                           | 1        | 1      | 0.05%   |
| MARVELL                            | 1        | 1      | 0.05%   |
| Intenso                            | 1        | 1      | 0.05%   |
| InnoLite                           | 1        | 1      | 0.05%   |
| IBM/Hitachi                        | 1        | 1      | 0.05%   |
| IBM-207x                           | 1        | 1      | 0.05%   |
| General                            | 1        | 1      | 0.05%   |
| ExcelStor Technology               | 1        | 4      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 585      | 950    | 17.31%  |
| Kingston            | 446      | 637    | 13.2%   |
| Crucial             | 262      | 396    | 7.75%   |
| SanDisk             | 236      | 315    | 6.98%   |
| Transcend           | 227      | 337    | 6.72%   |
| Intel               | 168      | 292    | 4.97%   |
| Hoodisk             | 149      | 216    | 4.41%   |
| WDC                 | 103      | 181    | 3.05%   |
| Phison              | 103      | 137    | 3.05%   |
| China               | 94       | 131    | 2.78%   |
| A-DATA Technology   | 93       | 126    | 2.75%   |
| OCZ                 | 58       | 76     | 1.72%   |
| Protectli           | 49       | 79     | 1.45%   |
| SPCC                | 46       | 78     | 1.36%   |
| PNY                 | 45       | 79     | 1.33%   |
| Micron Technology   | 42       | 72     | 1.24%   |
| Dogfish             | 39       | 59     | 1.15%   |
| Apacer              | 39       | 43     | 1.15%   |
| Toshiba             | 37       | 54     | 1.09%   |
| FORESEE             | 35       | 43     | 1.04%   |
| BIWIN               | 33       | 47     | 0.98%   |
| Intenso             | 32       | 57     | 0.95%   |
| Innodisk            | 28       | 32     | 0.83%   |
| Corsair             | 26       | 38     | 0.77%   |
| SK hynix            | 23       | 32     | 0.68%   |
| LITEONIT            | 23       | 26     | 0.68%   |
| Patriot             | 22       | 34     | 0.65%   |
| KingSpec            | 20       | 28     | 0.59%   |
| LITEON              | 17       | 24     | 0.5%    |
| GOODRAM             | 17       | 29     | 0.5%    |
| Plextor             | 14       | 20     | 0.41%   |
| Seagate             | 13       | 23     | 0.38%   |
| NVMe                | 13       | 16     | 0.38%   |
| ShiJi               | 11       | 20     | 0.33%   |
| Mushkin             | 10       | 12     | 0.3%    |
| Gigabyte Technology | 10       | 13     | 0.3%    |
| Kston               | 9        | 13     | 0.27%   |
| KingDian            | 9        | 16     | 0.27%   |
| Verbatim            | 7        | 7      | 0.21%   |
| Vaseky              | 7        | 10     | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 3061     | 5061   | 58.29%  |
| HDD  | 1599     | 4305   | 30.45%  |
| NVMe | 591      | 977    | 11.25%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4095     | 9366   | 87.39%  |
| NVMe | 591      | 977    | 12.61%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 3596     | 6046   | 72.57%  |
| 0.51-1.0        | 694      | 1246   | 14.01%  |
| 1.01-2.0        | 266      | 654    | 5.37%   |
| 3.01-4.0        | 153      | 427    | 3.09%   |
| 4.01-10.0       | 125      | 570    | 2.52%   |
| 2.01-3.0        | 91       | 306    | 1.84%   |
| 10.01-20.0      | 28       | 115    | 0.57%   |
| More than 100.0 | 1        | 1      | 0.02%   |
| 20.01-50.0      | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1865     | 38.02%  |
| 1-20           | 752      | 15.33%  |
| 251-500        | 709      | 14.45%  |
| 51-100         | 552      | 11.25%  |
| 21-50          | 512      | 10.44%  |
| 501-1000       | 308      | 6.28%   |
| 1001-2000      | 87       | 1.77%   |
| More than 3000 | 64       | 1.3%    |
| Unknown        | 30       | 0.61%   |
| 2001-3000      | 26       | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4316     | 88.46%  |
| 21-50          | 271      | 5.55%   |
| 51-100         | 100      | 2.05%   |
| 101-250        | 54       | 1.11%   |
| 251-500        | 31       | 0.64%   |
| Unknown        | 30       | 0.61%   |
| 501-1000       | 26       | 0.53%   |
| More than 3000 | 21       | 0.43%   |
| 1001-2000      | 19       | 0.39%   |
| 2001-3000      | 10       | 0.2%    |
| 0              | 1        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 23       | 36     | 2.79%   |
| Kingston SV300S37A120G 120GB        | 10       | 11     | 1.22%   |
| Seagate ST3500413AS 500GB           | 9        | 23     | 1.09%   |
| Seagate ST3500418AS 500GB           | 7        | 16     | 0.85%   |
| Kingston SV300S37A60G 64GB          | 7        | 9      | 0.85%   |
| WDC WD30EFRX-68EUZN0 3TB            | 6        | 18     | 0.73%   |
| Seagate ST3160815AS 160GB           | 6        | 7      | 0.73%   |
| Samsung Electronics HD501LJ 500GB   | 6        | 7      | 0.73%   |
| HGST HTS725050A7E630 500GB          | 6        | 12     | 0.73%   |
| Crucial CT275MX300SSD1 275GB        | 6        | 9      | 0.73%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5        | 12     | 0.61%   |
| Seagate ST380815AS 80GB             | 5        | 5      | 0.61%   |
| Samsung Electronics SSD 870 EVO 1TB | 5        | 9      | 0.61%   |
| Samsung Electronics HD161HJ 160GB   | 5        | 5      | 0.61%   |
| Kingston SMS200S360G 64GB           | 5        | 5      | 0.61%   |
| Kingston SMS200S3120G 120GB         | 5        | 6      | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB        | 4        | 4      | 0.49%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4        | 4      | 0.49%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4        | 8      | 0.49%   |
| Toshiba DT01ACA100 1TB              | 4        | 7      | 0.49%   |
| Seagate ST500LT012-1DG142 500GB     | 4        | 5      | 0.49%   |
| Seagate ST500LM021-1KJ152 500GB     | 4        | 4      | 0.49%   |
| Seagate ST500DM002-1BC142 500GB     | 4        | 4      | 0.49%   |
| Seagate ST3320418AS 320GB           | 4        | 5      | 0.49%   |
| Seagate ST320LT007-9ZV142 320GB     | 4        | 4      | 0.49%   |
| Seagate ST31000528AS 1TB            | 4        | 5      | 0.49%   |
| Seagate ST2000DL003-9VT166 2TB      | 4        | 12     | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4        | 5      | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 5      | 0.49%   |
| Samsung Electronics HD322HJ 320GB   | 4        | 4      | 0.49%   |
| Samsung Electronics HD103UJ 1TB     | 4        | 7      | 0.49%   |
| OCZ VERTEX3 120GB                   | 4        | 4      | 0.49%   |
| Intel SSDSA2M080G2GC 80GB           | 4        | 4      | 0.49%   |
| HGST HTS545032A7E380 320GB          | 4        | 4      | 0.49%   |
| Crucial CT525MX300SSD1 528GB        | 4        | 6      | 0.49%   |
| WDC WD6400AAKS-22A7B0 640GB         | 3        | 3      | 0.36%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 3        | 3      | 0.36%   |
| WDC WD30EFRX-68AX9N0 3TB            | 3        | 9      | 0.36%   |
| WDC WD20EARS-00MVWB0 2TB            | 3        | 3      | 0.36%   |
| WDC WD1600AAJS-75M0A0 160GB         | 3        | 3      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 199      | 302    | 25.35%  |
| WDC                 | 176      | 276    | 22.42%  |
| Samsung Electronics | 73       | 101    | 9.3%    |
| Hitachi             | 48       | 63     | 6.11%   |
| Kingston            | 44       | 56     | 5.61%   |
| Intel               | 40       | 55     | 5.1%    |
| Toshiba             | 37       | 62     | 4.71%   |
| Crucial             | 29       | 42     | 3.69%   |
| HGST                | 20       | 29     | 2.55%   |
| SanDisk             | 14       | 25     | 1.78%   |
| OCZ                 | 12       | 13     | 1.53%   |
| Maxtor              | 11       | 15     | 1.4%    |
| A-DATA Technology   | 10       | 15     | 1.27%   |
| SK hynix            | 7        | 11     | 0.89%   |
| Micron Technology   | 5        | 10     | 0.64%   |
| LITEON              | 5        | 6      | 0.64%   |
| Corsair             | 5        | 9      | 0.64%   |
| Apacer              | 5        | 5      | 0.64%   |
| Hewlett-Packard     | 4        | 8      | 0.51%   |
| VisionTek           | 3        | 7      | 0.38%   |
| Dogfish             | 3        | 8      | 0.38%   |
| BIWIN               | 3        | 5      | 0.38%   |
| Transcend           | 2        | 5      | 0.25%   |
| SPCC                | 2        | 4      | 0.25%   |
| MyDigitalSSD        | 2        | 4      | 0.25%   |
| KingDian            | 2        | 2      | 0.25%   |
| Intenso             | 2        | 2      | 0.25%   |
| XrayDisk            | 1        | 1      | 0.13%   |
| XPG                 | 1        | 1      | 0.13%   |
| WD MediaMax         | 1        | 3      | 0.13%   |
| V-GeN               | 1        | 1      | 0.13%   |
| Terabit             | 1        | 1      | 0.13%   |
| SMI                 | 1        | 1      | 0.13%   |
| Plextor             | 1        | 1      | 0.13%   |
| Phison              | 1        | 1      | 0.13%   |
| Netac               | 1        | 1      | 0.13%   |
| Mushkin             | 1        | 1      | 0.13%   |
| KingSpec            | 1        | 1      | 0.13%   |
| InnoLite            | 1        | 1      | 0.13%   |
| INDMEM              | 1        | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 198      | 301    | 37.08%  |
| WDC                  | 168      | 266    | 31.46%  |
| Hitachi              | 48       | 63     | 8.99%   |
| Samsung Electronics  | 46       | 58     | 8.61%   |
| Toshiba              | 33       | 58     | 6.18%   |
| HGST                 | 20       | 29     | 3.75%   |
| Maxtor               | 11       | 15     | 2.06%   |
| Hewlett-Packard      | 4        | 8      | 0.75%   |
| WD MediaMax          | 1        | 3      | 0.19%   |
| InnoLite             | 1        | 1      | 0.19%   |
| HPE                  | 1        | 3      | 0.19%   |
| Fujitsu              | 1        | 1      | 0.19%   |
| ExcelStor Technology | 1        | 2      | 0.19%   |
| Cactus               | 1        | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 494      | 809    | 66.58%  |
| SSD  | 243      | 349    | 32.75%  |
| NVMe | 5        | 10     | 0.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 2      | 7.69%   |
| WDC WD3200BPVT-16JJ5T0 320GB    | 1        | 1      | 7.69%   |
| WDC WD3200AAJS-00YZCA0 320GB    | 1        | 1      | 7.69%   |
| WDC WD20EARS-00MVWB0 2TB        | 1        | 1      | 7.69%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1        | 1      | 7.69%   |
| Toshiba MG05ACA800E 8TB         | 1        | 1      | 7.69%   |
| SK hynix SC308 SATA 256GB       | 1        | 1      | 7.69%   |
| Seagate ST3500418AS 500GB       | 1        | 1      | 7.69%   |
| Samsung Electronics HD204UI 2TB | 1        | 2      | 7.69%   |
| Maxtor 6E040L0 41GB             | 1        | 1      | 7.69%   |
| Kingston SV300S37A60G 64GB      | 1        | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB      | 1        | 1      | 7.69%   |
| Crucial M4-CT256M4SSD1 256GB    | 1        | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 38.46%  |
| Toshiba             | 1        | 1      | 7.69%   |
| SK hynix            | 1        | 1      | 7.69%   |
| Seagate             | 1        | 1      | 7.69%   |
| Samsung Electronics | 1        | 2      | 7.69%   |
| Maxtor              | 1        | 1      | 7.69%   |
| Kingston            | 1        | 1      | 7.69%   |
| HGST                | 1        | 1      | 7.69%   |
| Crucial             | 1        | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 3939     | 8816   | 81.3%   |
| Malfunc  | 719      | 1168   | 14.84%  |
| Detected | 174      | 344    | 3.59%   |
| Failed   | 13       | 15     | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3477     | 60.01%  |
| AMD                              | 1099     | 18.97%  |
| Samsung Electronics              | 239      | 4.12%   |
| ASMedia Technology               | 154      | 2.66%   |
| SanDisk                          | 97       | 1.67%   |
| Broadcom / LSI                   | 92       | 1.59%   |
| Marvell Technology Group         | 86       | 1.48%   |
| Phison Electronics               | 69       | 1.19%   |
| Silicon Motion                   | 57       | 0.98%   |
| Kingston Technology Company      | 54       | 0.93%   |
| Nvidia                           | 47       | 0.81%   |
| JMicron Technology               | 45       | 0.78%   |
| Micron/Crucial Technology        | 40       | 0.69%   |
| ADATA Technology                 | 22       | 0.38%   |
| SK hynix                         | 21       | 0.36%   |
| Silicon Image                    | 20       | 0.35%   |
| VIA Technologies                 | 19       | 0.33%   |
| Chelsio Communications           | 19       | 0.33%   |
| Adaptec                          | 13       | 0.22%   |
| Hewlett-Packard                  | 12       | 0.21%   |
| Seagate Technology               | 11       | 0.19%   |
| KIOXIA                           | 11       | 0.19%   |
| Toshiba                          | 10       | 0.17%   |
| Shenzhen Longsys Electronics     | 10       | 0.17%   |
| Realtek Semiconductor            | 8        | 0.14%   |
| Micron Technology                | 8        | 0.14%   |
| Areca Technology                 | 7        | 0.12%   |
| Integrated Technology Express    | 6        | 0.1%    |
| Silicon Integrated Systems [SiS] | 4        | 0.07%   |
| MAXIO Technology (Hangzhou)      | 4        | 0.07%   |
| Lite-On Technology               | 4        | 0.07%   |
| HighPoint Technologies           | 4        | 0.07%   |
| 3ware                            | 4        | 0.07%   |
| ULi Electronics                  | 3        | 0.05%   |
| Biwin Storage Technology         | 3        | 0.05%   |
| XenSource                        | 2        | 0.03%   |
| Transcend                        | 2        | 0.03%   |
| Solid State Storage Technology   | 2        | 0.03%   |
| Promise Technology               | 2        | 0.03%   |
| Unknown                          | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 687      | 10.17%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 366      | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 262      | 3.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 245      | 3.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 218      | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 206      | 3.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 204      | 3.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 173      | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 167      | 2.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 147      | 2.18%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 145      | 2.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 137      | 2.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 131      | 1.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 125      | 1.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 124      | 1.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 121      | 1.79%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 119      | 1.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 116      | 1.72%   |
| Intel SATA Controller [RAID mode]                                                       | 109      | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 97       | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 70       | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 69       | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 67       | 0.99%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 64       | 0.95%   |
| Unknown                                                                                 | 63       | 0.93%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 59       | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 59       | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 56       | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 53       | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 52       | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 52       | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 52       | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 48       | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 43       | 0.64%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 42       | 0.62%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 40       | 0.59%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 40       | 0.59%   |
| AMD FCH SATA Controller D                                                               | 38       | 0.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 37       | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 36       | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3944     | 68.46%  |
| IDE  | 788      | 13.68%  |
| NVMe | 663      | 11.51%  |
| RAID | 235      | 4.08%   |
| SAS  | 80       | 1.39%   |
| SCSI | 51       | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 3522     | 74.18%  |
| AMD      | 1148     | 24.18%  |
| ARM      | 52       | 1.1%    |
| Unknown  | 16       | 0.34%   |
| VIA      | 3        | 0.06%   |
| PowerPC  | 2        | 0.04%   |
| Sun      | 1        | 0.02%   |
| Research | 1        | 0.02%   |
| Motorola | 1        | 0.02%   |
| IBM      | 1        | 0.02%   |
| i        | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| AMD GX-412TC SOC                         | 243      | 5.06%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 137      | 2.85%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 135      | 2.81%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 80       | 1.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 60       | 1.25%   |
| Intel Celeron N5105 @ 2.00GHz            | 54       | 1.12%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 52       | 1.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 52       | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 51       | 1.06%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 47       | 0.98%   |
| Intel Atom CPU D525 @ 1.80GHz            | 44       | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 40       | 0.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 39       | 0.81%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 37       | 0.77%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 34       | 0.71%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 33       | 0.69%   |
| AMD Ryzen 5 3600 6-Core Processor        | 33       | 0.69%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 31       | 0.65%   |
| AMD G-T40E Processor                     | 31       | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 29       | 0.6%    |
| Intel Core i3-7100U CPU @ 2.40GHz        | 29       | 0.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 28       | 0.58%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 28       | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 26       | 0.54%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 26       | 0.54%   |
| Intel Core 2 Duo                         | 25       | 0.52%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 23       | 0.48%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 22       | 0.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 22       | 0.46%   |
| Intel Celeron J4115 CPU @ 1.80GHz        | 22       | 0.46%   |
| AMD FX-8350 Eight-Core Processor         | 22       | 0.46%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 21       | 0.44%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 21       | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz         | 21       | 0.44%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 21       | 0.44%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 20       | 0.42%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 20       | 0.42%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 20       | 0.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 19       | 0.4%    |
| Intel Core i3-4130 CPU @ 3.40GHz         | 19       | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 857      | 17.94%  |
| Intel Celeron           | 776      | 16.24%  |
| Intel Core i3           | 412      | 8.62%   |
| Intel Core i7           | 407      | 8.52%   |
| Intel Xeon              | 379      | 7.93%   |
| AMD GX                  | 373      | 7.81%   |
| Intel Atom              | 198      | 4.14%   |
| AMD Ryzen 5             | 147      | 3.08%   |
| Intel Pentium           | 134      | 2.8%    |
| AMD Ryzen 7             | 123      | 2.57%   |
| Other                   | 94       | 1.97%   |
| Intel Core 2 Duo        | 93       | 1.95%   |
| AMD FX                  | 80       | 1.67%   |
| Intel Core 2 Quad       | 59       | 1.23%   |
| AMD G                   | 50       | 1.05%   |
| ARM Cortex              | 47       | 0.98%   |
| AMD Ryzen 3             | 47       | 0.98%   |
| AMD Ryzen 9             | 45       | 0.94%   |
| Intel Pentium Dual-Core | 42       | 0.88%   |
| AMD Athlon              | 28       | 0.59%   |
| Intel Pentium 4         | 22       | 0.46%   |
| AMD Phenom II X4        | 22       | 0.46%   |
| Intel Pentium Gold      | 21       | 0.44%   |
| AMD Athlon 64 X2        | 19       | 0.4%    |
| Intel Pentium Silver    | 17       | 0.36%   |
| Intel Core 2            | 17       | 0.36%   |
| AMD Ryzen 5 PRO         | 17       | 0.36%   |
| AMD A10                 | 17       | 0.36%   |
| AMD A4                  | 15       | 0.31%   |
| AMD Ryzen Threadripper  | 14       | 0.29%   |
| Intel Core i9           | 13       | 0.27%   |
| AMD Turion II Neo       | 13       | 0.27%   |
| AMD Phenom II X6        | 12       | 0.25%   |
| AMD A8                  | 12       | 0.25%   |
| Intel Pentium Dual      | 11       | 0.23%   |
| Intel Genuine           | 11       | 0.23%   |
| AMD E                   | 11       | 0.23%   |
| Intel 686-class         | 9        | 0.19%   |
| AMD Opteron             | 8        | 0.17%   |
| AMD Athlon II X2        | 8        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2380     | 49.79%  |
| 2       | 1282     | 26.82%  |
| 8       | 246      | 5.15%   |
| Unknown | 237      | 4.96%   |
| 6       | 223      | 4.67%   |
| 12      | 135      | 2.82%   |
| 16      | 130      | 2.72%   |
| 1       | 60       | 1.26%   |
| 24      | 32       | 0.67%   |
| 32      | 18       | 0.38%   |
| 10      | 14       | 0.29%   |
| 3       | 7        | 0.15%   |
| 64      | 3        | 0.06%   |
| 48      | 3        | 0.06%   |
| 28      | 3        | 0.06%   |
| 14      | 3        | 0.06%   |
| 20      | 2        | 0.04%   |
| 36      | 1        | 0.02%   |
| 11      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4557     | 96.08%  |
| Unknown | 120      | 2.53%   |
| 2       | 63       | 1.33%   |
| 4       | 2        | 0.04%   |
| 8       | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3022     | 63.53%  |
| 2       | 1474     | 30.99%  |
| Unknown | 261      | 5.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 554      | 11.59%  |
| Haswell       | 538      | 11.26%  |
| Silvermont    | 380      | 7.95%   |
| IvyBridge     | 349      | 7.3%    |
| Puma          | 281      | 5.88%   |
| SandyBridge   | 273      | 5.71%   |
| Skylake       | 255      | 5.34%   |
| Unknown       | 207      | 4.33%   |
| Goldmont plus | 206      | 4.31%   |
| Penryn        | 181      | 3.79%   |
| Zen 2         | 139      | 2.91%   |
| Jaguar        | 121      | 2.53%   |
| Zen+          | 115      | 2.41%   |
| Bonnell       | 113      | 2.37%   |
| Goldmont      | 100      | 2.09%   |
| Zen           | 97       | 2.03%   |
| Piledriver    | 95       | 1.99%   |
| Broadwell     | 93       | 1.95%   |
| Core          | 91       | 1.9%    |
| CometLake     | 88       | 1.84%   |
| K10           | 77       | 1.61%   |
| Zen 3         | 74       | 1.55%   |
| Westmere      | 71       | 1.49%   |
| Nehalem       | 70       | 1.47%   |
| Bobcat        | 69       | 1.44%   |
| NetBurst      | 32       | 0.67%   |
| K8 Hammer     | 28       | 0.59%   |
| Excavator     | 17       | 0.36%   |
| TigerLake     | 15       | 0.31%   |
| Bulldozer     | 14       | 0.29%   |
| IceLake       | 11       | 0.23%   |
| Steamroller   | 10       | 0.21%   |
| P6            | 5        | 0.1%    |
| K10 Llano     | 5        | 0.1%    |
| Geode         | 3        | 0.06%   |
| K6            | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2692     | 61.17%  |
| AMD                                          | 765      | 17.38%  |
| Nvidia                                       | 663      | 15.06%  |
| ASPEED Technology                            | 131      | 2.98%   |
| Matrox Electronics Systems                   | 128      | 2.91%   |
| XGI Technology (eXtreme Graphics Innovation) | 8        | 0.18%   |
| VIA Technologies                             | 4        | 0.09%   |
| S3 Graphics                                  | 3        | 0.07%   |
| Silicon Integrated Systems [SiS]             | 2        | 0.05%   |
| Cirrus Logic                                 | 2        | 0.05%   |
| Tseng Labs                                   | 1        | 0.02%   |
| NVidia / SGS Thomson (Joint Venture)         | 1        | 0.02%   |
| 3DLabs                                       | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 280      | 6.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 214      | 4.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 196      | 4.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 158      | 3.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 150      | 3.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 149      | 3.34%   |
| Intel HD Graphics 530                                                                    | 138      | 3.1%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 131      | 2.94%   |
| Intel HD Graphics 620                                                                    | 113      | 2.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 105      | 2.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 90       | 2.02%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 76       | 1.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 74       | 1.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 71       | 1.59%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 69       | 1.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 66       | 1.48%   |
| Intel HD Graphics 630                                                                    | 66       | 1.48%   |
| Intel JasperLake [UHD Graphics]                                                          | 64       | 1.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 62       | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 61       | 1.37%   |
| Intel HD Graphics 500                                                                    | 60       | 1.35%   |
| Intel HD Graphics 610                                                                    | 56       | 1.26%   |
| Intel UHD Graphics 620                                                                   | 49       | 1.1%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 49       | 1.1%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 47       | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 42       | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 41       | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 40       | 0.9%    |
| Intel HD Graphics 5500                                                                   | 38       | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 35       | 0.79%   |
| Matrox Electronics Systems MGA G200EH                                                    | 31       | 0.7%    |
| AMD Kabini [Radeon HD 8330E]                                                             | 31       | 0.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 30       | 0.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28       | 0.63%   |
| Intel HD Graphics 6000                                                                   | 28       | 0.63%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 28       | 0.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 27       | 0.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27       | 0.61%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26       | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                               | 25       | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 2524     | 52.88%  |
| 1 x AMD                                  | 723      | 15.15%  |
| 1 x Nvidia                               | 612      | 12.82%  |
| Other                                    | 447      | 9.37%   |
| 1 x Matrox                               | 125      | 2.62%   |
| 1 x ASPEED                               | 123      | 2.58%   |
| 2 x Intel                                | 103      | 2.16%   |
| Intel + Nvidia                           | 39       | 0.82%   |
| Intel + AMD                              | 19       | 0.4%    |
| 2 x AMD                                  | 17       | 0.36%   |
| 1 x XGI                                  | 8        | 0.17%   |
| AMD + Nvidia                             | 5        | 0.1%    |
| 2 x Nvidia                               | 4        | 0.08%   |
| 1 x VIA                                  | 4        | 0.08%   |
| Intel + ASPEED                           | 4        | 0.08%   |
| 1 x S3 Graphics                          | 3        | 0.06%   |
| 1 x SiS                                  | 2        | 0.04%   |
| Nvidia + ASPEED                          | 2        | 0.04%   |
| 1 x Cirrus Logic                         | 2        | 0.04%   |
| AMD + ASPEED                             | 2        | 0.04%   |
| 1 x Tseng Labs                           | 1        | 0.02%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.02%   |
| Intel + Matrox                           | 1        | 0.02%   |
| AMD + Matrox                             | 1        | 0.02%   |
| 1 x 3DLabs                               | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3863     | 81.12%  |
| Unknown     | 493      | 10.35%  |
| Proprietary | 406      | 8.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4138     | 86.64%  |
| 1.01-2.0   | 190      | 3.98%   |
| 0.51-1.0   | 117      | 2.45%   |
| 3.01-4.0   | 109      | 2.28%   |
| 7.01-8.0   | 83       | 1.74%   |
| 0.01-0.5   | 60       | 1.26%   |
| 5.01-6.0   | 47       | 0.98%   |
| 2.01-3.0   | 17       | 0.36%   |
| 8.01-16.0  | 14       | 0.29%   |
| 4.01-5.0   | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 162      | 15.38%  |
| Dell                 | 145      | 13.77%  |
| Goldstar             | 127      | 12.06%  |
| Acer                 | 72       | 6.84%   |
| Hewlett-Packard      | 65       | 6.17%   |
| BenQ                 | 53       | 5.03%   |
| AOC                  | 53       | 5.03%   |
| Philips              | 52       | 4.94%   |
| Ancor Communications | 44       | 4.18%   |
| Iiyama               | 28       | 2.66%   |
| Lenovo               | 25       | 2.37%   |
| ViewSonic            | 23       | 2.18%   |
| LG Electronics       | 20       | 1.9%    |
| Sony                 | 18       | 1.71%   |
| ASUSTek Computer     | 17       | 1.61%   |
| NEC Computers        | 14       | 1.33%   |
| Eizo                 | 11       | 1.04%   |
| Fujitsu Siemens      | 10       | 0.95%   |
| Vizio                | 7        | 0.66%   |
| Toshiba              | 7        | 0.66%   |
| MSI                  | 7        | 0.66%   |
| Unknown              | 6        | 0.57%   |
| Idek Iiyama          | 5        | 0.47%   |
| Sceptre Tech         | 4        | 0.38%   |
| HannStar             | 4        | 0.38%   |
| Apple                | 4        | 0.38%   |
| Vestel Elektronik    | 3        | 0.28%   |
| Packard Bell         | 3        | 0.28%   |
| Mi                   | 3        | 0.28%   |
| Medion               | 3        | 0.28%   |
| LG Display           | 3        | 0.28%   |
| Insignia             | 3        | 0.28%   |
| Westinghouse         | 2        | 0.19%   |
| VIE                  | 2        | 0.19%   |
| RTK                  | 2        | 0.19%   |
| Panasonic            | 2        | 0.19%   |
| IOD                  | 2        | 0.19%   |
| HPN                  | 2        | 0.19%   |
| Gateway              | 2        | 0.19%   |
| AU Optronics         | 2        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 8        | 0.72%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 8        | 0.72%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                     | 8        | 0.72%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 6        | 0.54%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 5        | 0.45%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 4        | 0.36%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 4        | 0.36%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                     | 4        | 0.36%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                    | 4        | 0.36%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                     | 4        | 0.36%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch  | 4        | 0.36%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 4        | 0.36%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 3        | 0.27%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch  | 3        | 0.27%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 3        | 0.27%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch     | 3        | 0.27%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 3        | 0.27%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 3        | 0.27%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3        | 0.27%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 3        | 0.27%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch              | 3        | 0.27%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch      | 3        | 0.27%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 3        | 0.27%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                 | 3        | 0.27%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                     | 3        | 0.27%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                      | 3        | 0.27%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                     | 3        | 0.27%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 3        | 0.27%   |
| AOC 22V2WG5 AOC2202 1920x1080 480x270mm 21.7-inch                     | 3        | 0.27%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch | 3        | 0.27%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch               | 2        | 0.18%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch           | 2        | 0.18%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch           | 2        | 0.18%   |
| unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.18%   |
| Sony TV SNY9C01 1360x768                                              | 2        | 0.18%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                         | 2        | 0.18%   |
| Sony LCD Monitor TV XV 1920x1080                                      | 2        | 0.18%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 2        | 0.18%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 2        | 0.18%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 2        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 455      | 43.58%  |
| 1280x1024 (SXGA)   | 90       | 8.62%   |
| 3840x2160 (4K)     | 82       | 7.85%   |
| 2560x1440 (QHD)    | 79       | 7.57%   |
| 1920x1200 (WUXGA)  | 56       | 5.36%   |
| 1680x1050 (WSXGA+) | 44       | 4.21%   |
| 1440x900 (WXGA+)   | 42       | 4.02%   |
| 1600x900 (HD+)     | 33       | 3.16%   |
| 1366x768 (WXGA)    | 33       | 3.16%   |
| 3440x1440          | 20       | 1.92%   |
| Unknown            | 20       | 1.92%   |
| 2560x1080          | 18       | 1.72%   |
| 1360x768           | 11       | 1.05%   |
| 1024x768 (XGA)     | 10       | 0.96%   |
| 1600x1200          | 9        | 0.86%   |
| 1920x540           | 7        | 0.67%   |
| 3840x1080          | 6        | 0.57%   |
| 2560x1600          | 4        | 0.38%   |
| 2048x1152          | 3        | 0.29%   |
| 3840x1600          | 2        | 0.19%   |
| 3840x1200          | 2        | 0.19%   |
| 7680x2160          | 1        | 0.1%    |
| 5760x1256          | 1        | 0.1%    |
| 5760x1200          | 1        | 0.1%    |
| 5760x1080          | 1        | 0.1%    |
| 5120x1440          | 1        | 0.1%    |
| 3640x1920          | 1        | 0.1%    |
| 3600x1080          | 1        | 0.1%    |
| 3520x1200          | 1        | 0.1%    |
| 3360x1050          | 1        | 0.1%    |
| 3200x1080          | 1        | 0.1%    |
| 2806x900           | 1        | 0.1%    |
| 2648x1024          | 1        | 0.1%    |
| 2560x2520          | 1        | 0.1%    |
| 1400x1050          | 1        | 0.1%    |
| 1280x800 (WXGA)    | 1        | 0.1%    |
| 1280x720 (HD)      | 1        | 0.1%    |
| 11520x2160         | 1        | 0.1%    |
| 1024x600           | 1        | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 158      | 15.02%  |
| 21      | 144      | 13.69%  |
| 27      | 134      | 12.74%  |
| 19      | 111      | 10.55%  |
| Unknown | 110      | 10.46%  |
| 23      | 107      | 10.17%  |
| 31      | 45       | 4.28%   |
| 17      | 42       | 3.99%   |
| 18      | 34       | 3.23%   |
| 22      | 29       | 2.76%   |
| 34      | 23       | 2.19%   |
| 20      | 14       | 1.33%   |
| 15      | 9        | 0.86%   |
| 14      | 9        | 0.86%   |
| 40      | 7        | 0.67%   |
| 13      | 7        | 0.67%   |
| 29      | 6        | 0.57%   |
| 54      | 5        | 0.48%   |
| 42      | 5        | 0.48%   |
| 25      | 5        | 0.48%   |
| 16      | 5        | 0.48%   |
| 52      | 4        | 0.38%   |
| 32      | 4        | 0.38%   |
| 50      | 3        | 0.29%   |
| 41      | 3        | 0.29%   |
| 39      | 3        | 0.29%   |
| 28      | 3        | 0.29%   |
| 64      | 2        | 0.19%   |
| 49      | 2        | 0.19%   |
| 46      | 2        | 0.19%   |
| 37      | 2        | 0.19%   |
| 33      | 2        | 0.19%   |
| 26      | 2        | 0.19%   |
| 65      | 1        | 0.1%    |
| 57      | 1        | 0.1%    |
| 55      | 1        | 0.1%    |
| 48      | 1        | 0.1%    |
| 47      | 1        | 0.1%    |
| 43      | 1        | 0.1%    |
| 36      | 1        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 376      | 36.61%  |
| 401-500     | 279      | 27.17%  |
| Unknown     | 110      | 10.71%  |
| 601-700     | 69       | 6.72%   |
| 301-350     | 57       | 5.55%   |
| 351-400     | 47       | 4.58%   |
| 701-800     | 30       | 2.92%   |
| 1001-1500   | 23       | 2.24%   |
| 201-300     | 13       | 1.27%   |
| 801-900     | 12       | 1.17%   |
| 901-1000    | 10       | 0.97%   |
| 101-200     | 1        | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 643      | 64.04%  |
| 16/10   | 127      | 12.65%  |
| Unknown | 88       | 8.76%   |
| 5/4     | 79       | 7.87%   |
| 21/9    | 33       | 3.29%   |
| 4/3     | 20       | 1.99%   |
| 3/2     | 8        | 0.8%    |
| 32/9    | 4        | 0.4%    |
| 6/5     | 2        | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 365      | 35.3%   |
| 301-350        | 138      | 13.35%  |
| 151-200        | 135      | 13.06%  |
| Unknown        | 110      | 10.64%  |
| 351-500        | 79       | 7.64%   |
| 141-150        | 68       | 6.58%   |
| 251-300        | 60       | 5.8%    |
| 501-1000       | 27       | 2.61%   |
| More than 1000 | 18       | 1.74%   |
| 101-110        | 9        | 0.87%   |
| 81-90          | 7        | 0.68%   |
| 91-100         | 6        | 0.58%   |
| 121-130        | 4        | 0.39%   |
| 111-120        | 4        | 0.39%   |
| 131-140        | 2        | 0.19%   |
| 61-70          | 1        | 0.1%    |
| 1-40           | 1        | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 593      | 58.08%  |
| 101-120 | 221      | 21.65%  |
| Unknown | 110      | 10.77%  |
| 121-160 | 45       | 4.41%   |
| 161-240 | 34       | 3.33%   |
| 1-50    | 18       | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3756     | 78.69%  |
| 1     | 895      | 18.75%  |
| 2     | 109      | 2.28%   |
| 3     | 13       | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3400     | 53.43%  |
| Realtek Semiconductor           | 1888     | 29.67%  |
| Qualcomm Atheros                | 291      | 4.57%   |
| Broadcom                        | 265      | 4.16%   |
| IMC Networks                    | 38       | 0.6%    |
| Ralink Technology               | 37       | 0.58%   |
| Marvell Technology Group        | 34       | 0.53%   |
| Ralink                          | 33       | 0.52%   |
| Mellanox Technologies           | 33       | 0.52%   |
| D-Link System                   | 29       | 0.46%   |
| Chelsio Communications          | 24       | 0.38%   |
| TP-Link                         | 22       | 0.35%   |
| U-Blox                          | 17       | 0.27%   |
| VIA Technologies                | 16       | 0.25%   |
| American Megatrends             | 15       | 0.24%   |
| Aquantia                        | 14       | 0.22%   |
| Qualcomm Atheros Communications | 13       | 0.2%    |
| MediaTek                        | 13       | 0.2%    |
| Solarflare Communications       | 12       | 0.19%   |
| Huawei Technologies             | 11       | 0.17%   |
| 3Com                            | 11       | 0.17%   |
| Edimax Technology               | 9        | 0.14%   |
| ASUSTek Computer                | 8        | 0.13%   |
| Seeed Technology                | 7        | 0.11%   |
| Nvidia                          | 7        | 0.11%   |
| Emulex                          | 6        | 0.09%   |
| ZTE WCDMA Technologies MSM      | 5        | 0.08%   |
| Xiaomi                          | 5        | 0.08%   |
| Microchip Technology            | 5        | 0.08%   |
| ICS Advent                      | 5        | 0.08%   |
| Apple                           | 5        | 0.08%   |
| Samsung Electronics             | 4        | 0.06%   |
| Qualcomm                        | 4        | 0.06%   |
| Accton Technology               | 4        | 0.06%   |
| QLogic                          | 3        | 0.05%   |
| Davicom Semiconductor           | 3        | 0.05%   |
| Arduino SA                      | 3        | 0.05%   |
| ADMtek                          | 3        | 0.05%   |
| NetXen Incorporated             | 2        | 0.03%   |
| NetGear                         | 2        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1620     | 21.13%  |
| Intel I211 Gigabit Network Connection                                         | 805      | 10.5%   |
| Intel I210 Gigabit Network Connection                                         | 441      | 5.75%   |
| Intel 82574L Gigabit Network Connection                                       | 322      | 4.2%    |
| Intel I350 Gigabit Network Connection                                         | 246      | 3.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 241      | 3.14%   |
| Intel Ethernet Connection I217-LM                                             | 171      | 2.23%   |
| Intel 82583V Gigabit Network Connection                                       | 148      | 1.93%   |
| Intel Ethernet Controller I225-V                                              | 140      | 1.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 126      | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                             | 124      | 1.62%   |
| Intel 82576 Gigabit Network Connection                                        | 122      | 1.59%   |
| Intel 82580 Gigabit Network Connection                                        | 120      | 1.56%   |
| Intel Wi-Fi 6 AX200                                                           | 96       | 1.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 89       | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 87       | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                                         | 81       | 1.06%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 71       | 0.93%   |
| Intel 82579V Gigabit Network Connection                                       | 61       | 0.8%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 56       | 0.73%   |
| Intel Ethernet Connection I217-V                                              | 48       | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 45       | 0.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 44       | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 43       | 0.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 42       | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                          | 39       | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 38       | 0.5%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 34       | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 32       | 0.42%   |
| Intel Wireless 7260                                                           | 32       | 0.42%   |
| Intel Wireless 3165                                                           | 32       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                         | 32       | 0.42%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 32       | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 29       | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 28       | 0.37%   |
| Intel Ethernet Controller X550                                                | 27       | 0.35%   |
| Intel Ethernet Controller I226-V                                              | 27       | 0.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 27       | 0.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 25       | 0.33%   |
| Intel Ethernet Connection X553 1GbE                                           | 25       | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 368      | 36.8%   |
| Qualcomm Atheros                      | 206      | 20.6%   |
| Realtek Semiconductor                 | 182      | 18.2%   |
| Broadcom                              | 54       | 5.4%    |
| IMC Networks                          | 38       | 3.8%    |
| Ralink Technology                     | 37       | 3.7%    |
| Ralink                                | 33       | 3.3%    |
| TP-Link                               | 22       | 2.2%    |
| Qualcomm Atheros Communications       | 13       | 1.3%    |
| MediaTek                              | 11       | 1.1%    |
| Edimax Technology                     | 9        | 0.9%    |
| ASUSTek Computer                      | 8        | 0.8%    |
| NetGear                               | 2        | 0.2%    |
| D-Link System                         | 2        | 0.2%    |
| D-Link                                | 2        | 0.2%    |
| ZyXEL Communications                  | 1        | 0.1%    |
| Sitecom Europe                        | 1        | 0.1%    |
| Sierra Wireless                       | 1        | 0.1%    |
| Qcom                                  | 1        | 0.1%    |
| Mercucys                              | 1        | 0.1%    |
| Linksys                               | 1        | 0.1%    |
| Gemtek                                | 1        | 0.1%    |
| Dell                                  | 1        | 0.1%    |
| Belkin Components                     | 1        | 0.1%    |
| Atheros                               | 1        | 0.1%    |
| Accton Technology                     | 1        | 0.1%    |
| AboCom Systems                        | 1        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 96       | 9.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 45       | 4.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 38       | 3.77%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 34       | 3.38%   |
| Intel Wireless 7260                                             | 32       | 3.18%   |
| Intel Wireless 3165                                             | 32       | 3.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 29       | 2.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 28       | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 25       | 2.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 24       | 2.38%   |
| Intel Wireless-AC 9260                                          | 22       | 2.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 18       | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 18       | 1.79%   |
| Intel Wireless 7265                                             | 18       | 1.79%   |
| Intel Wireless 3160                                             | 18       | 1.79%   |
| Ralink RT5370 Wireless Adapter                                  | 17       | 1.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 17       | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 16       | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 16       | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 14       | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 12       | 1.19%   |
| Intel Centrino Advanced-N 6235                                  | 12       | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 12       | 1.19%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 11       | 1.09%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 11       | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 10       | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                 | 10       | 0.99%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 10       | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 8        | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 8        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 8        | 0.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 8        | 0.79%   |
| Intel Wireless 8265 / 8275                                      | 8        | 0.79%   |
| Intel Wireless 8260                                             | 8        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 8        | 0.79%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter              | 8        | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 7        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 7        | 0.7%    |
| Ralink RT5572 Wireless Adapter                                  | 7        | 0.7%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                       | 7        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 3259     | 58.48%  |
| Realtek Semiconductor             | 1801     | 32.32%  |
| Broadcom                          | 212      | 3.8%    |
| Qualcomm Atheros                  | 89       | 1.6%    |
| Marvell Technology Group          | 34       | 0.61%   |
| D-Link System                     | 25       | 0.45%   |
| Chelsio Communications            | 19       | 0.34%   |
| VIA Technologies                  | 16       | 0.29%   |
| American Megatrends               | 15       | 0.27%   |
| Aquantia                          | 14       | 0.25%   |
| Solarflare Communications         | 12       | 0.22%   |
| 3Com                              | 10       | 0.18%   |
| Nvidia                            | 7        | 0.13%   |
| Xiaomi                            | 5        | 0.09%   |
| ICS Advent                        | 5        | 0.09%   |
| Emulex                            | 5        | 0.09%   |
| Samsung Electronics               | 4        | 0.07%   |
| Qualcomm                          | 4        | 0.07%   |
| Apple                             | 4        | 0.07%   |
| QLogic                            | 3        | 0.05%   |
| Huawei Technologies               | 3        | 0.05%   |
| Davicom Semiconductor             | 3        | 0.05%   |
| ADMtek                            | 3        | 0.05%   |
| National Semiconductor            | 2        | 0.04%   |
| Digital Equipment                 | 2        | 0.04%   |
| Accton Technology                 | 2        | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.02%   |
| U.S. Robotics                     | 1        | 0.02%   |
| Tehuti Networks                   | 1        | 0.02%   |
| SysKonnect                        | 1        | 0.02%   |
| Sundance Technology Inc / IC Plus | 1        | 0.02%   |
| Standard Microsystems [SMC]       | 1        | 0.02%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.02%   |
| Silicom                           | 1        | 0.02%   |
| Oracle/SUN                        | 1        | 0.02%   |
| Novatel Wireless                  | 1        | 0.02%   |
| MYRICOM                           | 1        | 0.02%   |
| Microsoft                         | 1        | 0.02%   |
| MediaTek                          | 1        | 0.02%   |
| Google                            | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1620     | 24.9%   |
| Intel I211 Gigabit Network Connection                                         | 805      | 12.38%  |
| Intel I210 Gigabit Network Connection                                         | 441      | 6.78%   |
| Intel 82574L Gigabit Network Connection                                       | 322      | 4.95%   |
| Intel I350 Gigabit Network Connection                                         | 246      | 3.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 241      | 3.7%    |
| Intel Ethernet Connection I217-LM                                             | 171      | 2.63%   |
| Intel 82583V Gigabit Network Connection                                       | 148      | 2.28%   |
| Intel Ethernet Controller I225-V                                              | 140      | 2.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 126      | 1.94%   |
| Intel 82576 Gigabit Network Connection                                        | 122      | 1.88%   |
| Intel 82580 Gigabit Network Connection                                        | 120      | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                             | 115      | 1.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 89       | 1.37%   |
| Intel Ethernet Connection (2) I219-V                                          | 87       | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                                         | 81       | 1.25%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 71       | 1.09%   |
| Intel 82579V Gigabit Network Connection                                       | 61       | 0.94%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 56       | 0.86%   |
| Intel Ethernet Connection I217-V                                              | 48       | 0.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 44       | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 43       | 0.66%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 42       | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                          | 39       | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 32       | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 32       | 0.49%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 32       | 0.49%   |
| Intel Ethernet Controller X550                                                | 27       | 0.42%   |
| Intel Ethernet Controller I226-V                                              | 27       | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 27       | 0.42%   |
| Intel Ethernet Connection X553 1GbE                                           | 25       | 0.38%   |
| Intel Ethernet Connection (2) I218-V                                          | 24       | 0.37%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 23       | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 22       | 0.34%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 21       | 0.32%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 21       | 0.32%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 20       | 0.31%   |
| Intel 82575GB Gigabit Network Connection                                      | 19       | 0.29%   |
| Intel 82575EB Gigabit Network Connection                                      | 19       | 0.29%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 19       | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4652     | 80.82%  |
| WiFi     | 951      | 16.52%  |
| Unknown  | 100      | 1.74%   |
| Modem    | 53       | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4515     | 94.75%  |
| WiFi     | 240      | 5.04%   |
| Unknown  | 10       | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1056     | 21.95%  |
| 2     | 1039     | 21.59%  |
| 4     | 803      | 16.69%  |
| 3     | 759      | 15.77%  |
| 6     | 453      | 9.41%   |
| 5     | 380      | 7.9%    |
| 7     | 90       | 1.87%   |
| 0     | 75       | 1.56%   |
| 8     | 71       | 1.48%   |
| 9     | 31       | 0.64%   |
| 10    | 24       | 0.5%    |
| 12    | 8        | 0.17%   |
| 13    | 6        | 0.12%   |
| 11    | 5        | 0.1%    |
| 14    | 4        | 0.08%   |
| 16    | 3        | 0.06%   |
| 15    | 3        | 0.06%   |
| 20    | 2        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4169     | 85.03%  |
| Yes  | 734      | 14.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 307      | 55.32%  |
| Cambridge Silicon Radio         | 58       | 10.45%  |
| Realtek Semiconductor           | 38       | 6.85%   |
| IMC Networks                    | 30       | 5.41%   |
| Qualcomm Atheros Communications | 25       | 4.5%    |
| ASUSTek Computer                | 25       | 4.5%    |
| Broadcom                        | 22       | 3.96%   |
| Apple                           | 18       | 3.24%   |
| MediaTek                        | 8        | 1.44%   |
| Foxconn / Hon Hai               | 6        | 1.08%   |
| Lite-On Technology              | 5        | 0.9%    |
| Integrated System Solution      | 3        | 0.54%   |
| HTC (High Tech Computer)        | 2        | 0.36%   |
| TP-Link                         | 1        | 0.18%   |
| Qcom                            | 1        | 0.18%   |
| Micro Star International        | 1        | 0.18%   |
| Hewlett-Packard                 | 1        | 0.18%   |
| Edimax Technology               | 1        | 0.18%   |
| Dynex                           | 1        | 0.18%   |
| Dell                            | 1        | 0.18%   |
| Bluetooth Device                | 1        | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 90       | 16.19%  |
| Intel Bluetooth wireless interface                                   | 83       | 14.93%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 58       | 10.43%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 38       | 6.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 27       | 4.86%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 21       | 3.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 21       | 3.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 21       | 3.78%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip                 | 16       | 2.88%   |
| Intel AX201 Bluetooth                                                | 13       | 2.34%   |
| Intel AX210 Bluetooth                                                | 12       | 2.16%   |
| Realtek  Bluetooth Adapter                                           | 10       | 1.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 9        | 1.62%   |
| MediaTek Wireless_Device                                             | 8        | 1.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 8        | 1.44%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 8        | 1.44%   |
| IMC Networks Realtek Bluetooth Adapter                               | 7        | 1.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 7        | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 6        | 1.08%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 4        | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 4        | 0.72%   |
| ASUS Bluetooth Controller                                            | 4        | 0.72%   |
| ASUS ASUS USB-BT500                                                  | 4        | 0.72%   |
| Realtek  Bluetooth 4.0 Adapter                                       | 3        | 0.54%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter           | 3        | 0.54%   |
| Intel Intel Wireless Bluetooth                                       | 3        | 0.54%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 3        | 0.54%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 3        | 0.54%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 3        | 0.54%   |
| Realtek RTL8821A Bluetooth                                           | 2        | 0.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2        | 0.36%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 2        | 0.36%   |
| Lite-On Bluetooth USB Module                                         | 2        | 0.36%   |
| Integrated System Solution Bluetooth Device                          | 2        | 0.36%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 2        | 0.36%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 0.36%   |
| Broadcom HP Bluethunder                                              | 2        | 0.36%   |
| Broadcom Broadcom 20702 Bluetooth 4.0 Adapter                        | 2        | 0.36%   |
| Broadcom BCM2045 Bluetooth                                           | 2        | 0.36%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter              | 2        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2632     | 59.78%  |
| AMD                                          | 916      | 20.8%   |
| Nvidia                                       | 585      | 13.29%  |
| C-Media Electronics                          | 57       | 1.29%   |
| Creative Labs                                | 25       | 0.57%   |
| Logitech                                     | 22       | 0.5%    |
| Texas Instruments                            | 14       | 0.32%   |
| VIA Technologies                             | 10       | 0.23%   |
| SteelSeries ApS                              | 9        | 0.2%    |
| JMTek                                        | 8        | 0.18%   |
| Realtek Semiconductor                        | 6        | 0.14%   |
| Kingston Technology                          | 6        | 0.14%   |
| Yamaha                                       | 5        | 0.11%   |
| Sony                                         | 5        | 0.11%   |
| Focusrite-Novation                           | 5        | 0.11%   |
| Creative Technology                          | 5        | 0.11%   |
| BEHRINGER International                      | 5        | 0.11%   |
| Silicon Integrated Systems [SiS]             | 4        | 0.09%   |
| GN Netcom                                    | 4        | 0.09%   |
| Corsair                                      | 4        | 0.09%   |
| Blue Microphones                             | 4        | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.07%   |
| XMOS                                         | 3        | 0.07%   |
| Generalplus Technology                       | 3        | 0.07%   |
| Cambridge Silicon Radio                      | 3        | 0.07%   |
| ULi Electronics                              | 2        | 0.05%   |
| Trust                                        | 2        | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.05%   |
| Tenx Technology                              | 2        | 0.05%   |
| M-Audio                                      | 2        | 0.05%   |
| KTMicro                                      | 2        | 0.05%   |
| Google                                       | 2        | 0.05%   |
| Giga-Byte Technology                         | 2        | 0.05%   |
| FiiO Electronics Technology                  | 2        | 0.05%   |
| ESS Technology                               | 2        | 0.05%   |
| Ensoniq                                      | 2        | 0.05%   |
| Audio-Technica                               | 2        | 0.05%   |
| ASUSTek Computer                             | 2        | 0.05%   |
| Astro Gaming                                 | 2        | 0.05%   |
| ZOOM                                         | 1        | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 323      | 6.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 313      | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 213      | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 196      | 3.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 187      | 3.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 179      | 3.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 175      | 3.31%   |
| AMD FCH Azalia Controller                                                                         | 158      | 2.99%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 154      | 2.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 149      | 2.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 141      | 2.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 138      | 2.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 126      | 2.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 123      | 2.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 113      | 2.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 103      | 1.95%   |
| Intel Cannon Lake PCH cAVS                                                                        | 102      | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 102      | 1.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 97       | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 81       | 1.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 73       | 1.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 67       | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 66       | 1.25%   |
| Intel 8 Series HD Audio Controller                                                                | 66       | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 65       | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 64       | 1.21%   |
| Intel Jasper Lake HD Audio                                                                        | 64       | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 55       | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 52       | 0.98%   |
| Nvidia High Definition Audio Controller                                                           | 44       | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 40       | 0.76%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 40       | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 38       | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 36       | 0.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 36       | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 35       | 0.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 35       | 0.66%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 34       | 0.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 34       | 0.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 33       | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 733      | 15.19%  |
| Kingston                     | 713      | 14.77%  |
| Samsung Electronics          | 685      | 14.19%  |
| SK hynix                     | 502      | 10.4%   |
| Crucial                      | 484      | 10.03%  |
| Micron Technology            | 324      | 6.71%   |
| Corsair                      | 311      | 6.44%   |
| G.Skill                      | 229      | 4.75%   |
| Unknown                      | 120      | 2.49%   |
| Nanya Technology             | 60       | 1.24%   |
| Transcend                    | 54       | 1.12%   |
| A-DATA Technology            | 53       | 1.1%    |
| Unknown (ABCD)               | 50       | 1.04%   |
| Ramaxel Technology           | 48       | 0.99%   |
| Patriot                      | 46       | 0.95%   |
| Team                         | 45       | 0.93%   |
| Kimtigo                      | 26       | 0.54%   |
| Elpida                       | 24       | 0.5%    |
| Apacer                       | 23       | 0.48%   |
| Goodram                      | 17       | 0.35%   |
| Hewlett-Packard              | 15       | 0.31%   |
| PNY                          | 14       | 0.29%   |
| ATP                          | 14       | 0.29%   |
| Teikon                       | 11       | 0.23%   |
| Avant                        | 11       | 0.23%   |
| Timetec                      | 10       | 0.21%   |
| Toshiba                      | 9        | 0.19%   |
| Smart                        | 9        | 0.19%   |
| AMD                          | 9        | 0.19%   |
| Super Talent                 | 8        | 0.17%   |
| Tigo                         | 7        | 0.15%   |
| GeIL                         | 7        | 0.15%   |
| Silicon Power                | 6        | 0.12%   |
| Patriot Memory (PDP Systems) | 6        | 0.12%   |
| Innodisk                     | 6        | 0.12%   |
| Qimonda                      | 5        | 0.1%    |
| Kingmax                      | 5        | 0.1%    |
| Unknown (0x0C26)             | 4        | 0.08%   |
| Smart Modular                | 4        | 0.08%   |
| OCZ                          | 4        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown                                                           | 120      | 2.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 108      | 2.09%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 50       | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 32       | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 29       | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 28       | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 26       | 0.5%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 26       | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 26       | 0.5%    |
| Unknown RAM Module 8GB 1600MT/s                                   | 24       | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 24       | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 24       | 0.46%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 24       | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 22       | 0.43%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s             | 22       | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 21       | 0.41%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 21       | 0.41%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 21       | 0.41%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 20       | 0.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 19       | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 19       | 0.37%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 19       | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 18       | 0.35%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 18       | 0.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 17       | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                        | 16       | 0.31%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 16       | 0.31%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 15       | 0.29%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 15       | 0.29%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 15       | 0.29%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 15       | 0.29%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s             | 15       | 0.29%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 15       | 0.29%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s             | 15       | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 14       | 0.27%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 14       | 0.27%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 14       | 0.27%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s                 | 14       | 0.27%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 13       | 0.25%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 13       | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 2119     | 49.73%  |
| DDR4    | 1554     | 36.47%  |
| DDR2    | 204      | 4.79%   |
| Unknown | 194      | 4.55%   |
| SDRAM   | 83       | 1.95%   |
| LPDDR4  | 68       | 1.6%    |
| DDR     | 32       | 0.75%   |
| DRAM    | 3        | 0.07%   |
| RAM     | 2        | 0.05%   |
| LPDDR3  | 2        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2927     | 69.11%  |
| SODIMM       | 1221     | 28.83%  |
| Unknown      | 53       | 1.25%   |
| Row Of Chips | 16       | 0.38%   |
| RIMM         | 9        | 0.21%   |
| FB-DIMM      | 5        | 0.12%   |
| Chip         | 4        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 1608     | 35.16%  |
| 4096  | 1529     | 33.43%  |
| 2048  | 627      | 13.71%  |
| 16384 | 564      | 12.33%  |
| 1024  | 136      | 2.97%   |
| 32768 | 77       | 1.68%   |
| 512   | 24       | 0.52%   |
| 256   | 2        | 0.04%   |
| 128   | 2        | 0.04%   |
| 65536 | 1        | 0.02%   |
| 4092  | 1        | 0.02%   |
| 1556  | 1        | 0.02%   |
| 64    | 1        | 0.02%   |
| 32    | 1        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1317     | 29.16%  |
| 1333    | 751      | 16.63%  |
| 2400    | 547      | 12.11%  |
| 2667    | 348      | 7.7%    |
| 2133    | 304      | 6.73%   |
| 3200    | 299      | 6.62%   |
| 800     | 194      | 4.29%   |
| 667     | 133      | 2.94%   |
| Unknown | 98       | 2.17%   |
| 2666    | 97       | 2.15%   |
| 1066    | 75       | 1.66%   |
| 1867    | 47       | 1.04%   |
| 1067    | 40       | 0.89%   |
| 3600    | 38       | 0.84%   |
| 2933    | 37       | 0.82%   |
| 3000    | 31       | 0.69%   |
| 1866    | 30       | 0.66%   |
| 1334    | 27       | 0.6%    |
| 533     | 22       | 0.49%   |
| 400     | 21       | 0.46%   |
| 333     | 6        | 0.13%   |
| 65535   | 5        | 0.11%   |
| 3400    | 5        | 0.11%   |
| 2134    | 5        | 0.11%   |
| 1332    | 5        | 0.11%   |
| 1400    | 4        | 0.09%   |
| 1033    | 4        | 0.09%   |
| 3534    | 3        | 0.07%   |
| 5200    | 2        | 0.04%   |
| 2048    | 2        | 0.04%   |
| 1800    | 2        | 0.04%   |
| 933     | 2        | 0.04%   |
| 266     | 2        | 0.04%   |
| 133     | 2        | 0.04%   |
| 59392   | 1        | 0.02%   |
| 5354    | 1        | 0.02%   |
| 4133    | 1        | 0.02%   |
| 3733    | 1        | 0.02%   |
| 3500    | 1        | 0.02%   |
| 3333    | 1        | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 11       | 35.48%  |
| Hewlett-Packard       | 10       | 32.26%  |
| Seiko Epson           | 2        | 6.45%   |
| Lexmark International | 2        | 6.45%   |
| Ricoh                 | 1        | 3.23%   |
| QinHeng Electronics   | 1        | 3.23%   |
| Prolific Technology   | 1        | 3.23%   |
| Kyocera               | 1        | 3.23%   |
| Canon                 | 1        | 3.23%   |
| Apple                 | 1        | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Desktops | Percent |
|-------------------------------------------------------------------------------------------------------------------|----------|---------|
| Brother MFC-7360N                                                                                                 | 2        | 6.06%   |
| Brother HL-1430 Laser Printer                                                                                     | 2        | 6.06%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1        | 3.03%   |
| Seiko Epson Printer                                                                                               | 1        | 3.03%   |
| Ricoh SP 112                                                                                                      | 1        | 3.03%   |
| QinHeng CH340S                                                                                                    | 1        | 3.03%   |
| Prolific PL2305 Parallel Port                                                                                     | 1        | 3.03%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1        | 3.03%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1        | 3.03%   |
| Kyocera FS-1025MFP                                                                                                | 1        | 3.03%   |
| HP PNP Fax Null                                                                                                   | 1        | 3.03%   |
| HP LaserJet P3005                                                                                                 | 1        | 3.03%   |
| HP LaserJet 2200                                                                                                  | 1        | 3.03%   |
| HP LaserJet 1200                                                                                                  | 1        | 3.03%   |
| HP LaserJet 1012                                                                                                  | 1        | 3.03%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1        | 3.03%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1        | 3.03%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1        | 3.03%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1        | 3.03%   |
| HP HP Laser 107w                                                                                                  | 1        | 3.03%   |
| HP DeskJet 5850c                                                                                                  | 1        | 3.03%   |
| HP Color LaserJet CP1215                                                                                          | 1        | 3.03%   |
| Canon LBP2900                                                                                                     | 1        | 3.03%   |
| Brother MFC-L2685DW                                                                                               | 1        | 3.03%   |
| Brother MFC-J485DW                                                                                                | 1        | 3.03%   |
| Brother MFC-J200                                                                                                  | 1        | 3.03%   |
| Brother HL-L5200DW series                                                                                         | 1        | 3.03%   |
| Brother HL-L2310D series                                                                                          | 1        | 3.03%   |
| Brother HL-2030 Laser Printer                                                                                     | 1        | 3.03%   |
| Brother DCP-J100                                                                                                  | 1        | 3.03%   |
| Apple Gamesir-G3s 2.10                                                                                            | 1        | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 6        | 75%     |
| Seiko Epson     | 1        | 12.5%   |
| Hewlett-Packard | 1        | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                             | 3        | 37.5%   |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 12.5%   |
| HP ScanJet 5300c/5370c                                                              | 1        | 12.5%   |
| Canon CanoScan LIDE 25                                                              | 1        | 12.5%   |
| Canon CanoScan LiDE 220                                                             | 1        | 12.5%   |
| Canon CanoScan LiDE 210                                                             | 1        | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 57       | 42.86%  |
| Microdia                      | 15       | 11.28%  |
| Chicony Electronics           | 9        | 6.77%   |
| Z-Star Microelectronics       | 7        | 5.26%   |
| ARC International             | 5        | 3.76%   |
| Arkmicro Technologies         | 4        | 3.01%   |
| WCM_USB                       | 2        | 1.5%    |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 1.5%    |
| IMC Networks                  | 2        | 1.5%    |
| Hewlett-Packard               | 2        | 1.5%    |
| Generalplus Technology        | 2        | 1.5%    |
| Aveo Technology               | 2        | 1.5%    |
| YGTek                         | 1        | 0.75%   |
| Xiongmai                      | 1        | 0.75%   |
| Valve Software                | 1        | 0.75%   |
| Trust                         | 1        | 0.75%   |
| Suyin                         | 1        | 0.75%   |
| Sunplus Innovation Technology | 1        | 0.75%   |
| Sonix Technology              | 1        | 0.75%   |
| Silicon Motion                | 1        | 0.75%   |
| Ricoh                         | 1        | 0.75%   |
| Realtek Semiconductor         | 1        | 0.75%   |
| Quanta                        | 1        | 0.75%   |
| OmniVision Technologies       | 1        | 0.75%   |
| Novatek Microelectronics      | 1        | 0.75%   |
| Linux Foundation              | 1        | 0.75%   |
| Lenovo                        | 1        | 0.75%   |
| KYE Systems (Mouse Systems)   | 1        | 0.75%   |
| Huawei Technologies           | 1        | 0.75%   |
| HD WEBCAM                     | 1        | 0.75%   |
| Genesys Logic                 | 1        | 0.75%   |
| GEMBIRD                       | 1        | 0.75%   |
| Cubeternet                    | 1        | 0.75%   |
| Creative Technology           | 1        | 0.75%   |
| Alcor Micro                   | 1        | 0.75%   |
| A4Tech                        | 1        | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 14       | 10.53%  |
| Logitech HD Pro Webcam C920                    | 13       | 9.77%   |
| Logitech Webcam C310                           | 7        | 5.26%   |
| Logitech C922 Pro Stream Webcam                | 5        | 3.76%   |
| ARC International Camera                       | 5        | 3.76%   |
| Microdia Webcam Vitade AF                      | 3        | 2.26%   |
| Arkmicro USB2.0 PC CAMERA                      | 3        | 2.26%   |
| Z-Star Venus USB2.0 Camera                     | 2        | 1.5%    |
| Z-Star Integrated Camera                       | 2        | 1.5%    |
| WCM_USB WEB CAM                                | 2        | 1.5%    |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 1.5%    |
| Microdia HP Integrated Webcam                  | 2        | 1.5%    |
| Microdia FHD Webcam                            | 2        | 1.5%    |
| Microdia Camera                                | 2        | 1.5%    |
| Microdia ASUS USB2.0 Webcam                    | 2        | 1.5%    |
| Logitech Webcam C930e                          | 2        | 1.5%    |
| Logitech Webcam C170                           | 2        | 1.5%    |
| Logitech Labtec Webcam Pro                     | 2        | 1.5%    |
| Logitech HD Webcam C525                        | 2        | 1.5%    |
| Logitech C920 PRO HD Webcam                    | 2        | 1.5%    |
| Logitech C920 HD Pro Webcam                    | 2        | 1.5%    |
| Logitech C505 HD Webcam                        | 2        | 1.5%    |
| IMC Networks XHC Camera                        | 2        | 1.5%    |
| Generalplus GENERAL WEBCAM                     | 2        | 1.5%    |
| Z-Star Vega USB 2.0 Camera                     | 1        | 0.75%   |
| Z-Star Lenovo USB2.0 UVC Camera                | 1        | 0.75%   |
| Z-Star A4 TECH USB2.0 PC Camera J              | 1        | 0.75%   |
| YGTek Webcam                                   | 1        | 0.75%   |
| Xiongmai web camera                            | 1        | 0.75%   |
| Valve Software 3D Camera                       | 1        | 0.75%   |
| Trust Trust USB Camera                         | 1        | 0.75%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 0.75%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 0.75%   |
| Sonix FHD Webcam                               | 1        | 0.75%   |
| Silicon Motion 300k Pixel Camera               | 1        | 0.75%   |
| Ricoh USB2.0 Camera                            | 1        | 0.75%   |
| Realtek USB Video Device                       | 1        | 0.75%   |
| Quanta Realtek DMFT - RGB                      | 1        | 0.75%   |
| OmniVision Monitor Webcam                      | 1        | 0.75%   |
| Novatek HP High Definition 2MP Webcam          | 1        | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Validity Sensors           | 1        | 16.67%  |
| Upek                       | 1        | 16.67%  |
| STMicroelectronics         | 1        | 16.67%  |
| Shenzhen Goodix Technology | 1        | 16.67%  |
| DigitalPersona             | 1        | 16.67%  |
| AuthenTec                  | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 16.67%  |
| STMicroelectronics Fingerprint Reader                  | 1        | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                    | 1        | 16.67%  |
| DigitalPersona Fingerprint Reader                      | 1        | 16.67%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2239     | 46.15%  |
| 0     | 1889     | 38.93%  |
| 2     | 517      | 10.66%  |
| 3     | 150      | 3.09%   |
| 4     | 39       | 0.8%    |
| 5     | 14       | 0.29%   |
| 7     | 2        | 0.04%   |
| 6     | 2        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 2500     | 70.64%  |
| Net/wireless             | 333      | 9.41%   |
| Bluetooth                | 199      | 5.62%   |
| Firewire controller      | 136      | 3.84%   |
| Card reader              | 98       | 2.77%   |
| Sound                    | 88       | 2.49%   |
| Net/ethernet             | 68       | 1.92%   |
| Network                  | 65       | 1.84%   |
| Graphics card            | 29       | 0.82%   |
| Storage/raid             | 7        | 0.2%    |
| Storage/ata              | 6        | 0.17%   |
| Storage                  | 3        | 0.08%   |
| Dvb card                 | 3        | 0.08%   |
| Wireless                 | 1        | 0.03%   |
| Storage/ide              | 1        | 0.03%   |
| Modem                    | 1        | 0.03%   |
| Fingerprint reader       | 1        | 0.03%   |

