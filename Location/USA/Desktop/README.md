BSD in USA - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for BSD in USA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3628

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Cisco         | ASA5525 A0                  | [f6eb14f059](https://bsd-hardware.info/?probe=f6eb14f059) | Nov 06, 2023 |
| Unknown       | Unknown                     | [8b1079a297](https://bsd-hardware.info/?probe=8b1079a297) | Nov 06, 2023 |
| Dell          | 05XGC8 A01                  | [9e054bbcb2](https://bsd-hardware.info/?probe=9e054bbcb2) | Nov 06, 2023 |
| CncTion       | N6000-4L B0                 | [7ee545bad3](https://bsd-hardware.info/?probe=7ee545bad3) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| MSI           | H81M-P33                    | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| Dell          | 0XHGV1 A00                  | [ab650cfab8](https://bsd-hardware.info/?probe=ab650cfab8) | Nov 05, 2023 |
| Unknown       | Unknown                     | [2a768a9f63](https://bsd-hardware.info/?probe=2a768a9f63) | Nov 05, 2023 |
| Unknown       | Unknown                     | [5d0e537b3e](https://bsd-hardware.info/?probe=5d0e537b3e) | Nov 05, 2023 |
| HP            | ProLiant ML10               | [43badefe76](https://bsd-hardware.info/?probe=43badefe76) | Nov 05, 2023 |
| Dell          | 0XCR8D A03                  | [cc58b2f58f](https://bsd-hardware.info/?probe=cc58b2f58f) | Nov 05, 2023 |
| Dell          | 00V62H A00                  | [0b678c5e33](https://bsd-hardware.info/?probe=0b678c5e33) | Nov 04, 2023 |
| Techvision    | TVI7309X B0                 | [90a26f497a](https://bsd-hardware.info/?probe=90a26f497a) | Nov 04, 2023 |
| HP            | 18E4                        | [479b255034](https://bsd-hardware.info/?probe=479b255034) | Nov 03, 2023 |
| Protectli     | FW6                         | [2dc16f3849](https://bsd-hardware.info/?probe=2dc16f3849) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | [db0f05f919](https://bsd-hardware.info/?probe=db0f05f919) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | [b729c4137a](https://bsd-hardware.info/?probe=b729c4137a) | Nov 03, 2023 |
| CWWK          | MINIPC-G12                  | [4fd9e1d707](https://bsd-hardware.info/?probe=4fd9e1d707) | Nov 02, 2023 |
| Unknown       | Unknown                     | [f1e1a3e8c8](https://bsd-hardware.info/?probe=f1e1a3e8c8) | Nov 02, 2023 |
| MW            | GMLK-2_5G4L                 | [ff78edaee6](https://bsd-hardware.info/?probe=ff78edaee6) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [224cc728f5](https://bsd-hardware.info/?probe=224cc728f5) | Nov 02, 2023 |
| Dell          | 0XCR8D A02                  | [f9df1890fa](https://bsd-hardware.info/?probe=f9df1890fa) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [83c8ab8d4b](https://bsd-hardware.info/?probe=83c8ab8d4b) | Nov 02, 2023 |
| Protectli     | VP2420                      | [7621eb7370](https://bsd-hardware.info/?probe=7621eb7370) | Nov 01, 2023 |
| Shuttle       | FS61                        | [24158fbe17](https://bsd-hardware.info/?probe=24158fbe17) | Oct 31, 2023 |
| Shuttle       | FS61                        | [2efb16a5f4](https://bsd-hardware.info/?probe=2efb16a5f4) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| CheckPoint    | T-110-00                    | [970671ce27](https://bsd-hardware.info/?probe=970671ce27) | Oct 31, 2023 |
| Gigabyte      | H370M D3H-CF                | [6b2553e06c](https://bsd-hardware.info/?probe=6b2553e06c) | Oct 30, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [da2fa90c43](https://bsd-hardware.info/?probe=da2fa90c43) | Oct 30, 2023 |
| Dell          | 0KP561                      | [cd0ae50eb0](https://bsd-hardware.info/?probe=cd0ae50eb0) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | [10d46f39aa](https://bsd-hardware.info/?probe=10d46f39aa) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | [5995fa3115](https://bsd-hardware.info/?probe=5995fa3115) | Oct 30, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [9567268d28](https://bsd-hardware.info/?probe=9567268d28) | Oct 30, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [709f8e1566](https://bsd-hardware.info/?probe=709f8e1566) | Oct 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [b60083ef1f](https://bsd-hardware.info/?probe=b60083ef1f) | Oct 28, 2023 |
| ASRock        | H370M-ITX/ac                | [ace25d235f](https://bsd-hardware.info/?probe=ace25d235f) | Oct 28, 2023 |
| HP            | 2AF7                        | [a45659c9d2](https://bsd-hardware.info/?probe=a45659c9d2) | Oct 28, 2023 |
| Unknown       | Unknown                     | [3e99a14af3](https://bsd-hardware.info/?probe=3e99a14af3) | Oct 28, 2023 |
| Dell          | 09WH54 A01                  | [a012c0e1c9](https://bsd-hardware.info/?probe=a012c0e1c9) | Oct 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | [03ef00fab1](https://bsd-hardware.info/?probe=03ef00fab1) | Oct 27, 2023 |
| Unknown       | Unknown                     | [7a9e2d88ed](https://bsd-hardware.info/?probe=7a9e2d88ed) | Oct 27, 2023 |
| Dell          | 0M5DCD A00                  | [f8ae786555](https://bsd-hardware.info/?probe=f8ae786555) | Oct 27, 2023 |
| Shenzhen M... | AHBNB OEM                   | [8a1a0cdc32](https://bsd-hardware.info/?probe=8a1a0cdc32) | Oct 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [233d4d3b64](https://bsd-hardware.info/?probe=233d4d3b64) | Oct 26, 2023 |
| Unknown       | Unknown                     | [f06cbf02dc](https://bsd-hardware.info/?probe=f06cbf02dc) | Oct 25, 2023 |
| Protectli     | FW6 Ver                     | [66f5010f59](https://bsd-hardware.info/?probe=66f5010f59) | Oct 24, 2023 |
| Protectli     | FW6                         | [9ba0e874f4](https://bsd-hardware.info/?probe=9ba0e874f4) | Oct 24, 2023 |
| Unknown       | Unknown                     | [b42465c967](https://bsd-hardware.info/?probe=b42465c967) | Oct 23, 2023 |
| Techvision    | TVI7309X B0                 | [2424acbde7](https://bsd-hardware.info/?probe=2424acbde7) | Oct 23, 2023 |
| Supermicro    | X10SLM-F                    | [8e622421c6](https://bsd-hardware.info/?probe=8e622421c6) | Oct 23, 2023 |
| HP            | 3397                        | [2c004318d4](https://bsd-hardware.info/?probe=2c004318d4) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | [6aea1130aa](https://bsd-hardware.info/?probe=6aea1130aa) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | [3a4d822cfc](https://bsd-hardware.info/?probe=3a4d822cfc) | Oct 22, 2023 |
| MSI           | H81M-P33                    | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| Protectli     | FW6 Ver                     | [e12093f6bd](https://bsd-hardware.info/?probe=e12093f6bd) | Oct 22, 2023 |
| HP            | 8054                        | [71b61dc284](https://bsd-hardware.info/?probe=71b61dc284) | Oct 21, 2023 |
| Techvision    | TVI7309X B0                 | [48bb0077c3](https://bsd-hardware.info/?probe=48bb0077c3) | Oct 20, 2023 |
| Protectli     | FW4A Ver                    | [d40c67f9ca](https://bsd-hardware.info/?probe=d40c67f9ca) | Oct 20, 2023 |
| Dell          | 0HD5W2 A01                  | [3f7a4e2865](https://bsd-hardware.info/?probe=3f7a4e2865) | Oct 20, 2023 |
| Gigabyte      | B85M-DS3H                   | [bd9d649fb6](https://bsd-hardware.info/?probe=bd9d649fb6) | Oct 19, 2023 |
| Unknown       | Unknown                     | [94f0b39689](https://bsd-hardware.info/?probe=94f0b39689) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [26a1b95e16](https://bsd-hardware.info/?probe=26a1b95e16) | Oct 19, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [6f6f1bf009](https://bsd-hardware.info/?probe=6f6f1bf009) | Oct 18, 2023 |
| CncTion       | J4125-4L-I225               | [d8114642f5](https://bsd-hardware.info/?probe=d8114642f5) | Oct 18, 2023 |
| Dell          | 0YXT71 A00                  | [1bf1c3b807](https://bsd-hardware.info/?probe=1bf1c3b807) | Oct 18, 2023 |
| AZW           | EQ                          | [0d647b68a6](https://bsd-hardware.info/?probe=0d647b68a6) | Oct 18, 2023 |
| AZW           | EQ                          | [71f6a16f5a](https://bsd-hardware.info/?probe=71f6a16f5a) | Oct 18, 2023 |
| HP            | 8299                        | [b4ba6a7e52](https://bsd-hardware.info/?probe=b4ba6a7e52) | Oct 18, 2023 |
| CncTion       | N5105-4L B0                 | [0f18316a17](https://bsd-hardware.info/?probe=0f18316a17) | Oct 18, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [3dffc4d445](https://bsd-hardware.info/?probe=3dffc4d445) | Oct 18, 2023 |
| HP            | 8299                        | [8da92e01e0](https://bsd-hardware.info/?probe=8da92e01e0) | Oct 17, 2023 |
| ASUSTek       | X99-A/USB                   | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| Dell          | 00V62H A00                  | [8ff0ba4fcb](https://bsd-hardware.info/?probe=8ff0ba4fcb) | Oct 16, 2023 |
| Intel         | DH55TC AAE70932-206         | [745b988354](https://bsd-hardware.info/?probe=745b988354) | Oct 15, 2023 |
| Dell          | 0WR7PY A03                  | [128323ada4](https://bsd-hardware.info/?probe=128323ada4) | Oct 15, 2023 |
| Techvision    | TVI7309X B0                 | [bf66ef021e](https://bsd-hardware.info/?probe=bf66ef021e) | Oct 15, 2023 |
| MSI           | H81M-P33                    | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| Protectli     | VP4650                      | [9c073eb854](https://bsd-hardware.info/?probe=9c073eb854) | Oct 15, 2023 |
| Gigabyte      | Z68AP-D3                    | [ca5e8cfb2b](https://bsd-hardware.info/?probe=ca5e8cfb2b) | Oct 15, 2023 |
| Protectli     | VP2410                      | [aaffd45671](https://bsd-hardware.info/?probe=aaffd45671) | Oct 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| ASUSTek       | PRIME Z690-P                | [95653dd42d](https://bsd-hardware.info/?probe=95653dd42d) | Oct 13, 2023 |
| Protectli     | FW4C                        | [16326174bb](https://bsd-hardware.info/?probe=16326174bb) | Oct 13, 2023 |
| Dell          | 02YYK5 A00                  | [b57183cbb0](https://bsd-hardware.info/?probe=b57183cbb0) | Oct 13, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [30f97615e6](https://bsd-hardware.info/?probe=30f97615e6) | Oct 13, 2023 |
| Unknown       | Unknown                     | [9145630ed9](https://bsd-hardware.info/?probe=9145630ed9) | Oct 12, 2023 |
| Pegatron      | 2AD5                        | [cdc40fe6a3](https://bsd-hardware.info/?probe=cdc40fe6a3) | Oct 11, 2023 |
| Dell          | 08WKV3 A00                  | [67379c4768](https://bsd-hardware.info/?probe=67379c4768) | Oct 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | [3aa38e5b1f](https://bsd-hardware.info/?probe=3aa38e5b1f) | Oct 10, 2023 |
| AZW           | EQ                          | [ea7e5029de](https://bsd-hardware.info/?probe=ea7e5029de) | Oct 10, 2023 |
| Unknown       | Unknown                     | [89d680cba1](https://bsd-hardware.info/?probe=89d680cba1) | Oct 09, 2023 |
| HP            | 1497                        | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| Gigabyte      | H470M DS3H                  | [80e01e48bf](https://bsd-hardware.info/?probe=80e01e48bf) | Oct 09, 2023 |
| ASRock        | Z690M Phantom Gaming 4      | [20ff855aec](https://bsd-hardware.info/?probe=20ff855aec) | Oct 08, 2023 |
| Unknown       | Unknown                     | [a64ed6b5d1](https://bsd-hardware.info/?probe=a64ed6b5d1) | Oct 08, 2023 |
| MSI           | H81M-P33                    | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| Unknown       | Unknown                     | [bb66634f7c](https://bsd-hardware.info/?probe=bb66634f7c) | Oct 08, 2023 |
| MSI           | Aspen                       | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Intel         | CRESCENTBAY                 | [fb6d008bfc](https://bsd-hardware.info/?probe=fb6d008bfc) | Oct 06, 2023 |
| Intel         | QHSW02                      | [e0d4a273f5](https://bsd-hardware.info/?probe=e0d4a273f5) | Oct 06, 2023 |
| HP            | 8056                        | [7516a37588](https://bsd-hardware.info/?probe=7516a37588) | Oct 06, 2023 |
| Win elemen... | M600                        | [da4e03cd91](https://bsd-hardware.info/?probe=da4e03cd91) | Oct 05, 2023 |
| Win elemen... | M600                        | [27492e0298](https://bsd-hardware.info/?probe=27492e0298) | Oct 04, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [17406f5021](https://bsd-hardware.info/?probe=17406f5021) | Oct 04, 2023 |
| Protectli     | FW4C                        | [671429444f](https://bsd-hardware.info/?probe=671429444f) | Oct 04, 2023 |
| Supermicro    | A2SDi-TP8F                  | [1792df4520](https://bsd-hardware.info/?probe=1792df4520) | Oct 04, 2023 |
| HP            | 83E2                        | [dbb1010907](https://bsd-hardware.info/?probe=dbb1010907) | Oct 03, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Unknown       | Unknown                     | [cab6cdb306](https://bsd-hardware.info/?probe=cab6cdb306) | Oct 02, 2023 |
| Protectli     | VP2420                      | [c77ef1792c](https://bsd-hardware.info/?probe=c77ef1792c) | Oct 02, 2023 |
| Protectli     | VP46xx                      | [4985863bd8](https://bsd-hardware.info/?probe=4985863bd8) | Oct 01, 2023 |
| MSI           | H81M-P33                    | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | [f97e242e6b](https://bsd-hardware.info/?probe=f97e242e6b) | Oct 01, 2023 |
| Win elemen... | M600                        | [b5caabfd31](https://bsd-hardware.info/?probe=b5caabfd31) | Oct 01, 2023 |
| Win elemen... | M600                        | [7a1378a001](https://bsd-hardware.info/?probe=7a1378a001) | Oct 01, 2023 |
| Win elemen... | M600                        | [93cc6a1173](https://bsd-hardware.info/?probe=93cc6a1173) | Oct 01, 2023 |
| Gigabyte      | H470M DS3H                  | [604bce28c1](https://bsd-hardware.info/?probe=604bce28c1) | Sep 30, 2023 |
| Win elemen... | M600                        | [abc175c93b](https://bsd-hardware.info/?probe=abc175c93b) | Sep 30, 2023 |
| Win elemen... | M600                        | [5b7606e786](https://bsd-hardware.info/?probe=5b7606e786) | Sep 30, 2023 |
| Acer          | F672CR R01-B1               | [2008598c7e](https://bsd-hardware.info/?probe=2008598c7e) | Sep 29, 2023 |
| Unknown       | Unknown                     | [6ed3c7314d](https://bsd-hardware.info/?probe=6ed3c7314d) | Sep 29, 2023 |
| HP            | 0B54h D                     | [55122a1908](https://bsd-hardware.info/?probe=55122a1908) | Sep 29, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [8a4596eefa](https://bsd-hardware.info/?probe=8a4596eefa) | Sep 27, 2023 |
| Intel         | DENLOW_REFRESH_WS           | [9ca318e043](https://bsd-hardware.info/?probe=9ca318e043) | Sep 27, 2023 |
| HP            | 8055                        | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| Unknown       | Unknown                     | [a77db6c46a](https://bsd-hardware.info/?probe=a77db6c46a) | Sep 25, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [6153909c9e](https://bsd-hardware.info/?probe=6153909c9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | [5232e5837b](https://bsd-hardware.info/?probe=5232e5837b) | Sep 25, 2023 |
| CncTion       | N4505-4L B0                 | [5880a22b30](https://bsd-hardware.info/?probe=5880a22b30) | Sep 25, 2023 |
| Protectli     | VP4630                      | [d5c0fe73ef](https://bsd-hardware.info/?probe=d5c0fe73ef) | Sep 24, 2023 |
| MSI           | H81M-P33                    | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| Intel         | DQ77KB AAG40294-401         | [be147f7ff1](https://bsd-hardware.info/?probe=be147f7ff1) | Sep 24, 2023 |
| Protectli     | VP2420                      | [8644c80a4a](https://bsd-hardware.info/?probe=8644c80a4a) | Sep 24, 2023 |
| Protectli     | FW6 Ver                     | [d8ccddab5a](https://bsd-hardware.info/?probe=d8ccddab5a) | Sep 23, 2023 |
| Unknown       | Unknown                     | [3e1ef4a73c](https://bsd-hardware.info/?probe=3e1ef4a73c) | Sep 23, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [8386219e8f](https://bsd-hardware.info/?probe=8386219e8f) | Sep 22, 2023 |
| Dell          | 0HD5W2 A01                  | [5478cff8a7](https://bsd-hardware.info/?probe=5478cff8a7) | Sep 21, 2023 |
| Premio        | BlueCat XMB3 00C            | [423687627b](https://bsd-hardware.info/?probe=423687627b) | Sep 21, 2023 |
| Protectli     | FW4C Ver                    | [eae9f87345](https://bsd-hardware.info/?probe=eae9f87345) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | [6ee2f45613](https://bsd-hardware.info/?probe=6ee2f45613) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | [34bffe0ed1](https://bsd-hardware.info/?probe=34bffe0ed1) | Sep 20, 2023 |
| Intel         | Q3XXG4-P V1.0               | [60a616adf4](https://bsd-hardware.info/?probe=60a616adf4) | Sep 20, 2023 |
| Shenzhen M... | RPBNB                       | [07698e61c2](https://bsd-hardware.info/?probe=07698e61c2) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [0fe1aab1d8](https://bsd-hardware.info/?probe=0fe1aab1d8) | Sep 19, 2023 |
| Protectli     | VP2420                      | [c4599cac13](https://bsd-hardware.info/?probe=c4599cac13) | Sep 19, 2023 |
| Unknown       | Unknown                     | [0a9c074970](https://bsd-hardware.info/?probe=0a9c074970) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | [5e7775568c](https://bsd-hardware.info/?probe=5e7775568c) | Sep 18, 2023 |
| Inventec      | DQ Class A02                | [e6e705b7cf](https://bsd-hardware.info/?probe=e6e705b7cf) | Sep 18, 2023 |
| Advantech     | NAMB-3250 A102-1            | [143c5f73fc](https://bsd-hardware.info/?probe=143c5f73fc) | Sep 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [31455b0d33](https://bsd-hardware.info/?probe=31455b0d33) | Sep 17, 2023 |
| Unknown       | Unknown                     | [31cf5dc87d](https://bsd-hardware.info/?probe=31cf5dc87d) | Sep 16, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [a054400ef6](https://bsd-hardware.info/?probe=a054400ef6) | Sep 16, 2023 |
| Dell          | 02YYK5 A00                  | [a2d011d2d7](https://bsd-hardware.info/?probe=a2d011d2d7) | Sep 16, 2023 |
| MW            | GMLK-2_5G4L                 | [d36ff6181c](https://bsd-hardware.info/?probe=d36ff6181c) | Sep 15, 2023 |
| Unknown       | Unknown                     | [3fcc5727d3](https://bsd-hardware.info/?probe=3fcc5727d3) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Protectli     | FW4B Ver                    | [9790cd72bc](https://bsd-hardware.info/?probe=9790cd72bc) | Sep 15, 2023 |
| Dell          | OptiPlex 3020               | [dfb6cce27d](https://bsd-hardware.info/?probe=dfb6cce27d) | Sep 14, 2023 |
| ASRock        | J1900D2Y                    | [2084583d47](https://bsd-hardware.info/?probe=2084583d47) | Sep 14, 2023 |
| ASRock        | J3455M                      | [f9809dfb0f](https://bsd-hardware.info/?probe=f9809dfb0f) | Sep 13, 2023 |
| Dell          | 04YP6J A02                  | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| Dell          | 02YYK5 A00                  | [ae320bd7de](https://bsd-hardware.info/?probe=ae320bd7de) | Sep 13, 2023 |
| HP            | 212B                        | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| Protectli     | FW4B Ver                    | [984a64677e](https://bsd-hardware.info/?probe=984a64677e) | Sep 13, 2023 |
| ASRockRack    | X470D4U                     | [b0cd1ce0f4](https://bsd-hardware.info/?probe=b0cd1ce0f4) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| MW            | GMLK-2_5G4L                 | [7923196f55](https://bsd-hardware.info/?probe=7923196f55) | Sep 11, 2023 |
| MSI           | A520M-A PRO                 | [8b541c71a9](https://bsd-hardware.info/?probe=8b541c71a9) | Sep 11, 2023 |
| Unknown       | Unknown                     | [6610a56ab4](https://bsd-hardware.info/?probe=6610a56ab4) | Sep 11, 2023 |
| Unknown       | Unknown                     | [ccc62ac366](https://bsd-hardware.info/?probe=ccc62ac366) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | [525ed7878c](https://bsd-hardware.info/?probe=525ed7878c) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | [0131f46755](https://bsd-hardware.info/?probe=0131f46755) | Sep 10, 2023 |
| AZW           | EQ                          | [c6f83de1e4](https://bsd-hardware.info/?probe=c6f83de1e4) | Sep 10, 2023 |
| MSI           | H81M-P33                    | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Unknown       | QGLK03                      | [42ea8dfb44](https://bsd-hardware.info/?probe=42ea8dfb44) | Sep 10, 2023 |
| CWWK          | CW-AD4L-N V1                | [52764da7d8](https://bsd-hardware.info/?probe=52764da7d8) | Sep 10, 2023 |
| Supermicro    | X10SLM-F                    | [332a3f8516](https://bsd-hardware.info/?probe=332a3f8516) | Sep 09, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Unknown       | Unknown                     | [8579d5fa0d](https://bsd-hardware.info/?probe=8579d5fa0d) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | [7ea278ed7a](https://bsd-hardware.info/?probe=7ea278ed7a) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | [331f3de91a](https://bsd-hardware.info/?probe=331f3de91a) | Sep 09, 2023 |
| Unknown       | Unknown                     | [ee507594a0](https://bsd-hardware.info/?probe=ee507594a0) | Sep 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | [07d197cf04](https://bsd-hardware.info/?probe=07d197cf04) | Sep 09, 2023 |
| Unknown       | Unknown                     | [2e51c11ed2](https://bsd-hardware.info/?probe=2e51c11ed2) | Sep 08, 2023 |
| Unknown       | Unknown                     | [480823e372](https://bsd-hardware.info/?probe=480823e372) | Sep 08, 2023 |
| Dell          | 0NC2VH A01                  | [122601f717](https://bsd-hardware.info/?probe=122601f717) | Sep 08, 2023 |
| AZW           | MINI S 10                   | [4580cb5481](https://bsd-hardware.info/?probe=4580cb5481) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | [aaeb12b1c6](https://bsd-hardware.info/?probe=aaeb12b1c6) | Sep 08, 2023 |
| Protectli     | VP2420                      | [2a8eb1b056](https://bsd-hardware.info/?probe=2a8eb1b056) | Sep 08, 2023 |
| Unknown       | Unknown                     | [fa747c859f](https://bsd-hardware.info/?probe=fa747c859f) | Sep 08, 2023 |
| Intel         | MAHOBAY                     | [a3e54e7628](https://bsd-hardware.info/?probe=a3e54e7628) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | [eff74e8df0](https://bsd-hardware.info/?probe=eff74e8df0) | Sep 07, 2023 |
| Dell          | 05XGC8 A01                  | [7c0acfa5b9](https://bsd-hardware.info/?probe=7c0acfa5b9) | Sep 07, 2023 |
| Unknown       | Unknown                     | [94d9b19ade](https://bsd-hardware.info/?probe=94d9b19ade) | Sep 07, 2023 |
| Lenovo        | 0B98401 PRO                 | [4397f70291](https://bsd-hardware.info/?probe=4397f70291) | Sep 06, 2023 |
| AZW           | MINI S 10                   | [2daf516a05](https://bsd-hardware.info/?probe=2daf516a05) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [3af68f2594](https://bsd-hardware.info/?probe=3af68f2594) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | [ec3e0338eb](https://bsd-hardware.info/?probe=ec3e0338eb) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | [84d768ee15](https://bsd-hardware.info/?probe=84d768ee15) | Sep 05, 2023 |
| Intel         | Q3XXG4-P V1.0               | [3fb536ecce](https://bsd-hardware.info/?probe=3fb536ecce) | Sep 05, 2023 |
| ASUSTek       | H97I-PLUS                   | [e92272bb87](https://bsd-hardware.info/?probe=e92272bb87) | Sep 05, 2023 |
| Supermicro    | X11SSH-F                    | [bff90e93d0](https://bsd-hardware.info/?probe=bff90e93d0) | Sep 05, 2023 |
| Unknown       | Unknown                     | [a4796e8170](https://bsd-hardware.info/?probe=a4796e8170) | Sep 04, 2023 |
| Dell          | 0NC2VH A01                  | [8cc0358a69](https://bsd-hardware.info/?probe=8cc0358a69) | Sep 04, 2023 |
| CWWK          | CW-AD4L-N V1                | [dd32d9d4e1](https://bsd-hardware.info/?probe=dd32d9d4e1) | Sep 04, 2023 |
| Unknown       | Unknown                     | [7d95befe6e](https://bsd-hardware.info/?probe=7d95befe6e) | Sep 04, 2023 |
| Intel         | S1200KP AAG34877-201        | [1b07865ce7](https://bsd-hardware.info/?probe=1b07865ce7) | Sep 04, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| Gigabyte      | A520I AC                    | [58e061f420](https://bsd-hardware.info/?probe=58e061f420) | Sep 03, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| MSI           | PRO Z790-P WIFI             | [fe53c55492](https://bsd-hardware.info/?probe=fe53c55492) | Sep 03, 2023 |
| MSI           | H81M-P33                    | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| Unknown       | Unknown                     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Dell          | 08NPPY A00                  | [1ae33cfe72](https://bsd-hardware.info/?probe=1ae33cfe72) | Sep 02, 2023 |
| ASRock        | J3455M                      | [762d4d9370](https://bsd-hardware.info/?probe=762d4d9370) | Sep 02, 2023 |
| Dell          | 0XCR8D A00                  | [b89126c9d9](https://bsd-hardware.info/?probe=b89126c9d9) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Unknown       | Unknown                     | [94487109c2](https://bsd-hardware.info/?probe=94487109c2) | Sep 01, 2023 |
| Shuttle       | FS77U                       | [149a8a1437](https://bsd-hardware.info/?probe=149a8a1437) | Sep 01, 2023 |
| Dell          | 0YXT71 A02                  | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| Foxconn       | nT-A3000 series FAB         | [d9f360b4fe](https://bsd-hardware.info/?probe=d9f360b4fe) | Aug 31, 2023 |
| Dell          | 0WR7PY A02                  | [2557e04cf5](https://bsd-hardware.info/?probe=2557e04cf5) | Aug 31, 2023 |
| Biostar       | A68N-5545                   | [b2a1070e2d](https://bsd-hardware.info/?probe=b2a1070e2d) | Aug 31, 2023 |
| CWWK          | CW-AD4L-N V1                | [363a27fb74](https://bsd-hardware.info/?probe=363a27fb74) | Aug 31, 2023 |
| Infoblox      | IB-810                      | [34c0fa6bec](https://bsd-hardware.info/?probe=34c0fa6bec) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | [259a7ec99d](https://bsd-hardware.info/?probe=259a7ec99d) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | [20946147de](https://bsd-hardware.info/?probe=20946147de) | Aug 30, 2023 |
| Unknown       | Unknown                     | [8cfa60050b](https://bsd-hardware.info/?probe=8cfa60050b) | Aug 30, 2023 |
| Supermicro    | A1SRi-2758F                 | [c8b4f33fb1](https://bsd-hardware.info/?probe=c8b4f33fb1) | Aug 30, 2023 |
| Biostar       | A68N-5545                   | [c90edbc46a](https://bsd-hardware.info/?probe=c90edbc46a) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | [a84c23941d](https://bsd-hardware.info/?probe=a84c23941d) | Aug 27, 2023 |
| Protectli     | FW6                         | [37b744ff79](https://bsd-hardware.info/?probe=37b744ff79) | Aug 27, 2023 |
| MSI           | H81M-P33                    | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | [21e958a05d](https://bsd-hardware.info/?probe=21e958a05d) | Aug 26, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [bf289c5941](https://bsd-hardware.info/?probe=bf289c5941) | Aug 26, 2023 |
| HP            | 8299                        | [77a077cb11](https://bsd-hardware.info/?probe=77a077cb11) | Aug 26, 2023 |
| Pegatron      | 2ACD                        | [c20fcb2b2f](https://bsd-hardware.info/?probe=c20fcb2b2f) | Aug 26, 2023 |
| Inventec      | Z CLASS A02                 | [8d7f83c319](https://bsd-hardware.info/?probe=8d7f83c319) | Aug 24, 2023 |
| MW            | GMLK-2_5G4L                 | [d07ade15d2](https://bsd-hardware.info/?probe=d07ade15d2) | Aug 23, 2023 |
| MSI           | PRO B550-VC                 | [005e9c7b4c](https://bsd-hardware.info/?probe=005e9c7b4c) | Aug 23, 2023 |
| AZW           | EQ                          | [a43bd92291](https://bsd-hardware.info/?probe=a43bd92291) | Aug 23, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [1fcc80636d](https://bsd-hardware.info/?probe=1fcc80636d) | Aug 22, 2023 |
| Techvision    | TVI7309X B0                 | [ff55eb5161](https://bsd-hardware.info/?probe=ff55eb5161) | Aug 22, 2023 |
| Protectli     | FW4B                        | [6041b7e153](https://bsd-hardware.info/?probe=6041b7e153) | Aug 21, 2023 |
| Intel         | JSL MRD                     | [0f3ef76fb8](https://bsd-hardware.info/?probe=0f3ef76fb8) | Aug 21, 2023 |
| Cisco         | ASA5525 A0                  | [7c88ca29f7](https://bsd-hardware.info/?probe=7c88ca29f7) | Aug 21, 2023 |
| ASUSTek       | B85M-G R2.0                 | [3941ce5fae](https://bsd-hardware.info/?probe=3941ce5fae) | Aug 21, 2023 |
| ASRock        | X570M Pro4                  | [c03bc6fa91](https://bsd-hardware.info/?probe=c03bc6fa91) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| Unknown       | Unknown                     | [e57d2d76d2](https://bsd-hardware.info/?probe=e57d2d76d2) | Aug 21, 2023 |
| Unknown       | J3160-4L                    | [cf30fa594f](https://bsd-hardware.info/?probe=cf30fa594f) | Aug 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | [e6bfadb400](https://bsd-hardware.info/?probe=e6bfadb400) | Aug 21, 2023 |
| Inventec      | Z CLASS A02                 | [3194978ea5](https://bsd-hardware.info/?probe=3194978ea5) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| MSI           | 990FXA-GD80                 | [70c65a5a34](https://bsd-hardware.info/?probe=70c65a5a34) | Aug 20, 2023 |
| Unknown       | Unknown                     | [3296816fc1](https://bsd-hardware.info/?probe=3296816fc1) | Aug 20, 2023 |
| ASRock        | H110M-STX                   | [5c819b9ff1](https://bsd-hardware.info/?probe=5c819b9ff1) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [1b53079f34](https://bsd-hardware.info/?probe=1b53079f34) | Aug 19, 2023 |
| Protectli     | FW1 Ver                     | [8b49278bbd](https://bsd-hardware.info/?probe=8b49278bbd) | Aug 19, 2023 |
| Supermicro    | A1SRi-2758F                 | [c9c0312302](https://bsd-hardware.info/?probe=c9c0312302) | Aug 19, 2023 |
| Protectli     | FW2B Ver                    | [b200aabc73](https://bsd-hardware.info/?probe=b200aabc73) | Aug 18, 2023 |
| Unknown       | Unknown                     | [f7c887c84f](https://bsd-hardware.info/?probe=f7c887c84f) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Dell          | 0GY6Y8 A00                  | [e982da98d2](https://bsd-hardware.info/?probe=e982da98d2) | Aug 18, 2023 |
| MSI           | MS-7721                     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| MSI           | MS-7721                     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Unknown       | Unknown                     | [3521bed0e8](https://bsd-hardware.info/?probe=3521bed0e8) | Aug 18, 2023 |
| Unknown       | QSKL01                      | [b768029249](https://bsd-hardware.info/?probe=b768029249) | Aug 18, 2023 |
| ASRock        | B660M Steel Legend          | [c50e637bc2](https://bsd-hardware.info/?probe=c50e637bc2) | Aug 18, 2023 |
| Supermicro    | A1SRi-2758F                 | [71fff01c39](https://bsd-hardware.info/?probe=71fff01c39) | Aug 18, 2023 |
| Protectli     | FW4B                        | [880c0c7069](https://bsd-hardware.info/?probe=880c0c7069) | Aug 18, 2023 |
| HP            | 1495                        | [556a339a7e](https://bsd-hardware.info/?probe=556a339a7e) | Aug 17, 2023 |
| Unknown       | Unknown                     | [a574d1cce5](https://bsd-hardware.info/?probe=a574d1cce5) | Aug 17, 2023 |
| Unknown       | Unknown                     | [20348d2f47](https://bsd-hardware.info/?probe=20348d2f47) | Aug 17, 2023 |
| Unknown       | YL-E3854L4-V2               | [6b85b4a31c](https://bsd-hardware.info/?probe=6b85b4a31c) | Aug 16, 2023 |
| MSI           | PRO Z790-P WIFI             | [fcb3075158](https://bsd-hardware.info/?probe=fcb3075158) | Aug 16, 2023 |
| Unknown       | Unknown                     | [e457a41b4a](https://bsd-hardware.info/?probe=e457a41b4a) | Aug 16, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | [3b5ddbcb06](https://bsd-hardware.info/?probe=3b5ddbcb06) | Aug 16, 2023 |
| CncTion       | J4125-4L-I225               | [269cfa2253](https://bsd-hardware.info/?probe=269cfa2253) | Aug 16, 2023 |
| CWWK          | CW-AD4L-N V1                | [f710821a92](https://bsd-hardware.info/?probe=f710821a92) | Aug 16, 2023 |
| HP            | 18E7                        | [3c24defdf8](https://bsd-hardware.info/?probe=3c24defdf8) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| Unknown       | Unknown                     | [86c4d1f8cf](https://bsd-hardware.info/?probe=86c4d1f8cf) | Aug 15, 2023 |
| Gigabyte      | G41M-ES2L                   | [30c58f7403](https://bsd-hardware.info/?probe=30c58f7403) | Aug 15, 2023 |
| PC Engines    | APU2                        | [c11fdc1cf9](https://bsd-hardware.info/?probe=c11fdc1cf9) | Aug 15, 2023 |
| Unknown       | Unknown                     | [99fd3696dd](https://bsd-hardware.info/?probe=99fd3696dd) | Aug 15, 2023 |
| AZW           | EQ                          | [5393736ae4](https://bsd-hardware.info/?probe=5393736ae4) | Aug 15, 2023 |
| Protectli     | FW4B Ver                    | [dbbd82bd80](https://bsd-hardware.info/?probe=dbbd82bd80) | Aug 15, 2023 |
| MSI           | B360M BAZOOKA               | [472c17f992](https://bsd-hardware.info/?probe=472c17f992) | Aug 15, 2023 |
| Dell          | 08NPPY A00                  | [aba7b573c1](https://bsd-hardware.info/?probe=aba7b573c1) | Aug 14, 2023 |
| MSI           | 990FXA-GD80                 | [169da97c61](https://bsd-hardware.info/?probe=169da97c61) | Aug 14, 2023 |
| Protectli     | FW4B                        | [417b740320](https://bsd-hardware.info/?probe=417b740320) | Aug 14, 2023 |
| Dell          | 0HY9JP A00                  | [c09110c605](https://bsd-hardware.info/?probe=c09110c605) | Aug 13, 2023 |
| Protectli     | VP2420                      | [b4bed593e9](https://bsd-hardware.info/?probe=b4bed593e9) | Aug 13, 2023 |
| Protectli     | VP2420                      | [b81c163920](https://bsd-hardware.info/?probe=b81c163920) | Aug 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| Dell          | 02YYK5 A00                  | [fecdfd45c7](https://bsd-hardware.info/?probe=fecdfd45c7) | Aug 13, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [9d53e56e92](https://bsd-hardware.info/?probe=9d53e56e92) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | [deb4e10cd2](https://bsd-hardware.info/?probe=deb4e10cd2) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | [947caf3be1](https://bsd-hardware.info/?probe=947caf3be1) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | [e21c4e8012](https://bsd-hardware.info/?probe=e21c4e8012) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | [2b24029c25](https://bsd-hardware.info/?probe=2b24029c25) | Aug 12, 2023 |
| HP            | 8265                        | [cefac793c7](https://bsd-hardware.info/?probe=cefac793c7) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | [41f42269dc](https://bsd-hardware.info/?probe=41f42269dc) | Aug 12, 2023 |
| Protectli     | FW6 Ver                     | [edc2f0f879](https://bsd-hardware.info/?probe=edc2f0f879) | Aug 12, 2023 |
| Protectli     | FW4C Ver                    | [519987ec57](https://bsd-hardware.info/?probe=519987ec57) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | [2ee5b48d5c](https://bsd-hardware.info/?probe=2ee5b48d5c) | Aug 12, 2023 |
| Unknown       | Unknown                     | [e310e0d309](https://bsd-hardware.info/?probe=e310e0d309) | Aug 11, 2023 |
| HP            | 8054                        | [05cae0efcc](https://bsd-hardware.info/?probe=05cae0efcc) | Aug 11, 2023 |
| HP            | 8055                        | [d686196496](https://bsd-hardware.info/?probe=d686196496) | Aug 11, 2023 |
| HP            | 1495                        | [7591160534](https://bsd-hardware.info/?probe=7591160534) | Aug 11, 2023 |
| Shuttle       | FH270                       | [8b697be8be](https://bsd-hardware.info/?probe=8b697be8be) | Aug 11, 2023 |
| Unknown       | Unknown                     | [fdd28fbae2](https://bsd-hardware.info/?probe=fdd28fbae2) | Aug 10, 2023 |
| MSI           | B360M BAZOOKA               | [4b0b4b88a7](https://bsd-hardware.info/?probe=4b0b4b88a7) | Aug 10, 2023 |
| Gigabyte      | X570 UD                     | [d4b7006d24](https://bsd-hardware.info/?probe=d4b7006d24) | Aug 10, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | [6a275811b8](https://bsd-hardware.info/?probe=6a275811b8) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | [877307aa80](https://bsd-hardware.info/?probe=877307aa80) | Aug 09, 2023 |
| Premio        | BlueCat XMB3 00C            | [76abf23a1f](https://bsd-hardware.info/?probe=76abf23a1f) | Aug 08, 2023 |
| Dell          | 08NPPY A00                  | [c0884d7f16](https://bsd-hardware.info/?probe=c0884d7f16) | Aug 08, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [c54bdb8e4b](https://bsd-hardware.info/?probe=c54bdb8e4b) | Aug 08, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | [87810aceef](https://bsd-hardware.info/?probe=87810aceef) | Aug 08, 2023 |
| PC Engines    | apu4                        | [bb7ad49154](https://bsd-hardware.info/?probe=bb7ad49154) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [d880905ae7](https://bsd-hardware.info/?probe=d880905ae7) | Aug 07, 2023 |
| Intel         | SHARKBAY                    | [2a8896bb78](https://bsd-hardware.info/?probe=2a8896bb78) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [5b58edb60b](https://bsd-hardware.info/?probe=5b58edb60b) | Aug 07, 2023 |
| Unknown       | Unknown                     | [16e7763338](https://bsd-hardware.info/?probe=16e7763338) | Aug 07, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [19e34e504c](https://bsd-hardware.info/?probe=19e34e504c) | Aug 07, 2023 |
| PC Engines    | apu4                        | [57e0cc469e](https://bsd-hardware.info/?probe=57e0cc469e) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | [c05ddd6998](https://bsd-hardware.info/?probe=c05ddd6998) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | [4836027efd](https://bsd-hardware.info/?probe=4836027efd) | Aug 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [ec37cc1ba1](https://bsd-hardware.info/?probe=ec37cc1ba1) | Aug 07, 2023 |
| ZOTAC         | Unknown                     | [415f49b491](https://bsd-hardware.info/?probe=415f49b491) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [d2ba7bbf34](https://bsd-hardware.info/?probe=d2ba7bbf34) | Aug 06, 2023 |
| Dell          | 0KWVT8 A03                  | [d203b32a8f](https://bsd-hardware.info/?probe=d203b32a8f) | Aug 06, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | [5a87146725](https://bsd-hardware.info/?probe=5a87146725) | Aug 06, 2023 |
| MSI           | H81M-P33                    | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| Acer          | Aspire TC-330               | [4d3de96309](https://bsd-hardware.info/?probe=4d3de96309) | Aug 05, 2023 |
| HP            | 843F                        | [d192efba82](https://bsd-hardware.info/?probe=d192efba82) | Aug 05, 2023 |
| Unknown       | Unknown                     | [0f6e0d9566](https://bsd-hardware.info/?probe=0f6e0d9566) | Aug 05, 2023 |
| Protectli     | FW4B Ver                    | [8446d61b81](https://bsd-hardware.info/?probe=8446d61b81) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | [36d63888b2](https://bsd-hardware.info/?probe=36d63888b2) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | [bee8eb05f2](https://bsd-hardware.info/?probe=bee8eb05f2) | Aug 04, 2023 |
| Protectli     | VP4650                      | [94d2d08a9d](https://bsd-hardware.info/?probe=94d2d08a9d) | Aug 04, 2023 |
| ASRock        | 4X4-4000 Series             | [da7d5e31aa](https://bsd-hardware.info/?probe=da7d5e31aa) | Aug 03, 2023 |
| Gigabyte      | X570 UD                     | [2bef587ef1](https://bsd-hardware.info/?probe=2bef587ef1) | Aug 03, 2023 |
| Unknown       | Unknown                     | [803f6b50b3](https://bsd-hardware.info/?probe=803f6b50b3) | Aug 03, 2023 |
| Unknown       | Unknown                     | [91dd6813a1](https://bsd-hardware.info/?probe=91dd6813a1) | Aug 03, 2023 |
| ASRock        | 4X4-4000 Series             | [d896138d30](https://bsd-hardware.info/?probe=d896138d30) | Aug 03, 2023 |
| HP            | 1495                        | [551688d163](https://bsd-hardware.info/?probe=551688d163) | Aug 03, 2023 |
| Shuttle       | FH270                       | [92c45a20de](https://bsd-hardware.info/?probe=92c45a20de) | Aug 02, 2023 |
| Dell          | 08NPPY A00                  | [249d4620d2](https://bsd-hardware.info/?probe=249d4620d2) | Aug 02, 2023 |
| ASRock        | B660-ITX                    | [c218c3c4d4](https://bsd-hardware.info/?probe=c218c3c4d4) | Aug 02, 2023 |
| Protectli     | VP2410 10                   | [3d653ab54c](https://bsd-hardware.info/?probe=3d653ab54c) | Aug 02, 2023 |
| Dell          | 0WR7PY A01                  | [54388809cd](https://bsd-hardware.info/?probe=54388809cd) | Aug 02, 2023 |
| ASRock        | B550M Steel Legend          | [ffc50e224c](https://bsd-hardware.info/?probe=ffc50e224c) | Aug 01, 2023 |
| Supermicro    | X7SPA-H                     | [de44613a90](https://bsd-hardware.info/?probe=de44613a90) | Aug 01, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [bdb1c85615](https://bsd-hardware.info/?probe=bdb1c85615) | Aug 01, 2023 |
| CWWK          | CW-AD4L-N V1                | [9cf0b7fe7c](https://bsd-hardware.info/?probe=9cf0b7fe7c) | Aug 01, 2023 |
| AZW           | EQ                          | [24d56ab18f](https://bsd-hardware.info/?probe=24d56ab18f) | Aug 01, 2023 |
| ASRockRack    | X470D4U                     | [f26504cb5b](https://bsd-hardware.info/?probe=f26504cb5b) | Jul 31, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [c045012233](https://bsd-hardware.info/?probe=c045012233) | Jul 31, 2023 |
| Protectli     | FW6                         | [aa7b970016](https://bsd-hardware.info/?probe=aa7b970016) | Jul 31, 2023 |
| Protectli     | FW1 Ver                     | [1d6213fd35](https://bsd-hardware.info/?probe=1d6213fd35) | Jul 30, 2023 |
| MSI           | H81M-P33                    | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| Premio        | BlueCat XMB3 00C            | [c453573c71](https://bsd-hardware.info/?probe=c453573c71) | Jul 30, 2023 |
| Dell          | 05XGC8 A01                  | [38310a9c5e](https://bsd-hardware.info/?probe=38310a9c5e) | Jul 30, 2023 |
| HP            | 213D A01                    | [802a71b9f6](https://bsd-hardware.info/?probe=802a71b9f6) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | [fc2a96cc75](https://bsd-hardware.info/?probe=fc2a96cc75) | Jul 29, 2023 |
| Dell          | 0HD5W2 A00                  | [ce83168854](https://bsd-hardware.info/?probe=ce83168854) | Jul 29, 2023 |
| Dell          | 05XGC8 A01                  | [06e6afb4f1](https://bsd-hardware.info/?probe=06e6afb4f1) | Jul 28, 2023 |
| HP            | 18E4                        | [6a0ce7d626](https://bsd-hardware.info/?probe=6a0ce7d626) | Jul 28, 2023 |
| Techvision    | TVI7309X B0                 | [088f599199](https://bsd-hardware.info/?probe=088f599199) | Jul 28, 2023 |
| Dell          | 0NC2VH A01                  | [1595ce505c](https://bsd-hardware.info/?probe=1595ce505c) | Jul 28, 2023 |
| Unknown       | Unknown                     | [836d435712](https://bsd-hardware.info/?probe=836d435712) | Jul 28, 2023 |
| Unknown       | Unknown                     | [6d6a8cb863](https://bsd-hardware.info/?probe=6d6a8cb863) | Jul 28, 2023 |
| Dell          | 0KWVT8 A03                  | [fccf22f7a7](https://bsd-hardware.info/?probe=fccf22f7a7) | Jul 27, 2023 |
| Unknown       | Unknown                     | [9d078811ba](https://bsd-hardware.info/?probe=9d078811ba) | Jul 27, 2023 |
| Unknown       | Unknown                     | [dbb7d95d59](https://bsd-hardware.info/?probe=dbb7d95d59) | Jul 27, 2023 |
| Unknown       | Unknown                     | [7841057467](https://bsd-hardware.info/?probe=7841057467) | Jul 27, 2023 |
| Protectli     | VP2420                      | [87d17e77a8](https://bsd-hardware.info/?probe=87d17e77a8) | Jul 26, 2023 |
| CONTEC        | G1/EMB-CV1/iD2550           | [34f5c817fb](https://bsd-hardware.info/?probe=34f5c817fb) | Jul 26, 2023 |
| Dell          | 0NC2VH A01                  | [103e75cb64](https://bsd-hardware.info/?probe=103e75cb64) | Jul 25, 2023 |
| HP            | 339A                        | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | [11ee31d0b3](https://bsd-hardware.info/?probe=11ee31d0b3) | Jul 24, 2023 |
| HP            | 1495                        | [3ddc49b877](https://bsd-hardware.info/?probe=3ddc49b877) | Jul 24, 2023 |
| Unknown       | Unknown                     | [bbae253aa2](https://bsd-hardware.info/?probe=bbae253aa2) | Jul 23, 2023 |
| HP            | 1495                        | [9de7021e50](https://bsd-hardware.info/?probe=9de7021e50) | Jul 23, 2023 |
| Protectli     | VP2420                      | [7f388b0128](https://bsd-hardware.info/?probe=7f388b0128) | Jul 23, 2023 |
| MSI           | H81M-P33                    | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| Premio        | BlueCat XMB3 00C            | [974c8673b7](https://bsd-hardware.info/?probe=974c8673b7) | Jul 23, 2023 |
| Techvision    | TVI7309X B0                 | [a2f320b278](https://bsd-hardware.info/?probe=a2f320b278) | Jul 23, 2023 |
| Unknown       | Unknown                     | [4d91799b3c](https://bsd-hardware.info/?probe=4d91799b3c) | Jul 23, 2023 |
| PC Engines    | APU2                        | [e02df69b63](https://bsd-hardware.info/?probe=e02df69b63) | Jul 23, 2023 |
| Unknown       | Unknown                     | [fb0affa930](https://bsd-hardware.info/?probe=fb0affa930) | Jul 23, 2023 |
| Intel         | S1200KP AAG34877-201        | [26d7c98e18](https://bsd-hardware.info/?probe=26d7c98e18) | Jul 22, 2023 |
| Unknown       | Unknown                     | [36ccde4a75](https://bsd-hardware.info/?probe=36ccde4a75) | Jul 22, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [89f4d8e6a0](https://bsd-hardware.info/?probe=89f4d8e6a0) | Jul 22, 2023 |
| Unknown       | Unknown                     | [267063ed35](https://bsd-hardware.info/?probe=267063ed35) | Jul 22, 2023 |
| Dell          | 00V62H A00                  | [db56801c55](https://bsd-hardware.info/?probe=db56801c55) | Jul 21, 2023 |
| Unknown       | QGLK03                      | [d7396cc0e8](https://bsd-hardware.info/?probe=d7396cc0e8) | Jul 21, 2023 |
| Shuttle       | FX48 V10                    | [c0ac40d196](https://bsd-hardware.info/?probe=c0ac40d196) | Jul 21, 2023 |
| HP            | 3397                        | [c6d7ddd8e8](https://bsd-hardware.info/?probe=c6d7ddd8e8) | Jul 19, 2023 |
| Protectli     | FW4B Ver                    | [5b3f040896](https://bsd-hardware.info/?probe=5b3f040896) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| Intel         | HURONRIVER                  | [b7f28022b2](https://bsd-hardware.info/?probe=b7f28022b2) | Jul 19, 2023 |
| HP            | 1495                        | [174216c4d3](https://bsd-hardware.info/?probe=174216c4d3) | Jul 18, 2023 |
| Dell          | 0WMJ54 A01                  | [fe07363baa](https://bsd-hardware.info/?probe=fe07363baa) | Jul 18, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [13985f2c0c](https://bsd-hardware.info/?probe=13985f2c0c) | Jul 18, 2023 |
| Lenovo        | ThinkServer TS140           | [b5f034579d](https://bsd-hardware.info/?probe=b5f034579d) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [93dd663d57](https://bsd-hardware.info/?probe=93dd663d57) | Jul 16, 2023 |
| ASUSTek       | H97M-E                      | [82bc9b32bd](https://bsd-hardware.info/?probe=82bc9b32bd) | Jul 16, 2023 |
| Unknown       | Unknown                     | [a0b045dfd2](https://bsd-hardware.info/?probe=a0b045dfd2) | Jul 15, 2023 |
| HP            | 1495                        | [7756cc81eb](https://bsd-hardware.info/?probe=7756cc81eb) | Jul 15, 2023 |
| PC Engines    | APU2                        | [167d51d317](https://bsd-hardware.info/?probe=167d51d317) | Jul 14, 2023 |
| HP            | 8055                        | [1274fc1b5e](https://bsd-hardware.info/?probe=1274fc1b5e) | Jul 14, 2023 |
| Protectli     | VP2420                      | [26957c4a08](https://bsd-hardware.info/?probe=26957c4a08) | Jul 14, 2023 |
| HP            | 8299                        | [5874bc1020](https://bsd-hardware.info/?probe=5874bc1020) | Jul 14, 2023 |
| Protectli     | FW6                         | [f337c2d283](https://bsd-hardware.info/?probe=f337c2d283) | Jul 13, 2023 |
| PC Engines    | APU2                        | [a1af1a8c1d](https://bsd-hardware.info/?probe=a1af1a8c1d) | Jul 13, 2023 |
| ASUSTek       | STRIX H270I GAMING          | [f1899c02c1](https://bsd-hardware.info/?probe=f1899c02c1) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| Dell          | 02YYK5 A00                  | [32b118286e](https://bsd-hardware.info/?probe=32b118286e) | Jul 13, 2023 |
| Unknown       | Unknown                     | [c580a701d0](https://bsd-hardware.info/?probe=c580a701d0) | Jul 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4ec99c1909](https://bsd-hardware.info/?probe=4ec99c1909) | Jul 12, 2023 |
| Unknown       | Unknown                     | [7e735a2b8f](https://bsd-hardware.info/?probe=7e735a2b8f) | Jul 12, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [d13984b682](https://bsd-hardware.info/?probe=d13984b682) | Jul 12, 2023 |
| Techvision    | TVI7309X B0                 | [3658cb969a](https://bsd-hardware.info/?probe=3658cb969a) | Jul 11, 2023 |
| Hardkernel    | ODROID-H3                   | [63f0cba062](https://bsd-hardware.info/?probe=63f0cba062) | Jul 10, 2023 |
| Unknown       | Unknown                     | [fe3184dd5b](https://bsd-hardware.info/?probe=fe3184dd5b) | Jul 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [a24f2cca34](https://bsd-hardware.info/?probe=a24f2cca34) | Jul 10, 2023 |
| PC Engines    | apu4                        | [8f0a65309f](https://bsd-hardware.info/?probe=8f0a65309f) | Jul 10, 2023 |
| HP            | 8299                        | [9cfe218328](https://bsd-hardware.info/?probe=9cfe218328) | Jul 10, 2023 |
| PC Engines    | apu4                        | [b82b8da585](https://bsd-hardware.info/?probe=b82b8da585) | Jul 10, 2023 |
| AZW           | EQ                          | [46754d358b](https://bsd-hardware.info/?probe=46754d358b) | Jul 10, 2023 |
| AZW           | EQ                          | [3f38b7c248](https://bsd-hardware.info/?probe=3f38b7c248) | Jul 10, 2023 |
| Protectli     | VP2420                      | [83135eaeca](https://bsd-hardware.info/?probe=83135eaeca) | Jul 10, 2023 |
| HP            | 802E                        | [298896b37a](https://bsd-hardware.info/?probe=298896b37a) | Jul 09, 2023 |
| Unknown       | QCML03                      | [63a27fdd5b](https://bsd-hardware.info/?probe=63a27fdd5b) | Jul 09, 2023 |
| Intel         | DH55TC AAE70932-206         | [bbfc2c35b1](https://bsd-hardware.info/?probe=bbfc2c35b1) | Jul 09, 2023 |
| MSI           | H81M-P33                    | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | [264f689c35](https://bsd-hardware.info/?probe=264f689c35) | Jul 09, 2023 |
| Unknown       | Unknown                     | [7395b234bc](https://bsd-hardware.info/?probe=7395b234bc) | Jul 09, 2023 |
| Acer          | Aspire XC-830               | [b121db09fb](https://bsd-hardware.info/?probe=b121db09fb) | Jul 09, 2023 |
| Protectli     | FW1 Ver                     | [f5844f1fbd](https://bsd-hardware.info/?probe=f5844f1fbd) | Jul 09, 2023 |
| Protectli     | VP2410 10                   | [75f3eb7e81](https://bsd-hardware.info/?probe=75f3eb7e81) | Jul 08, 2023 |
| Unknown       | Unknown                     | [80eb767d39](https://bsd-hardware.info/?probe=80eb767d39) | Jul 08, 2023 |
| HP            | 3397                        | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Unknown       | Unknown                     | [a780f8f8ad](https://bsd-hardware.info/?probe=a780f8f8ad) | Jul 08, 2023 |
| Unknown       | Unknown                     | [273d642ff6](https://bsd-hardware.info/?probe=273d642ff6) | Jul 08, 2023 |
| Unknown       | Unknown                     | [b07e2a5b47](https://bsd-hardware.info/?probe=b07e2a5b47) | Jul 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | [2100c4c1d0](https://bsd-hardware.info/?probe=2100c4c1d0) | Jul 07, 2023 |
| HP            | 1495                        | [3e7cdee510](https://bsd-hardware.info/?probe=3e7cdee510) | Jul 07, 2023 |
| Lenovo        | ThinkCentre M81 7518E1U     | [2c818e6169](https://bsd-hardware.info/?probe=2c818e6169) | Jul 06, 2023 |
| AZW           | EQ                          | [158f9680b5](https://bsd-hardware.info/?probe=158f9680b5) | Jul 06, 2023 |
| Protectli     | FW4B Ver                    | [fd8e3ee5d6](https://bsd-hardware.info/?probe=fd8e3ee5d6) | Jul 06, 2023 |
| HP            | 8265                        | [c0f867283f](https://bsd-hardware.info/?probe=c0f867283f) | Jul 06, 2023 |
| Protectli     | FW4B Ver                    | [45dd8f839f](https://bsd-hardware.info/?probe=45dd8f839f) | Jul 06, 2023 |
| Dell          | 0WR7PY A01                  | [6a32c3663b](https://bsd-hardware.info/?probe=6a32c3663b) | Jul 05, 2023 |
| Unknown       | Unknown                     | [4060a343aa](https://bsd-hardware.info/?probe=4060a343aa) | Jul 05, 2023 |
| Dell          | 0J3C2F A02                  | [a97b53bcf5](https://bsd-hardware.info/?probe=a97b53bcf5) | Jul 05, 2023 |
| Dell          | 0NW6H5 A00                  | [2ac2980803](https://bsd-hardware.info/?probe=2ac2980803) | Jul 05, 2023 |
| Protectli     | FW4B                        | [b73a26aa23](https://bsd-hardware.info/?probe=b73a26aa23) | Jul 05, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [529a30afc2](https://bsd-hardware.info/?probe=529a30afc2) | Jul 04, 2023 |
| MW            | GMLK-2_5G4L                 | [8a446692ce](https://bsd-hardware.info/?probe=8a446692ce) | Jul 04, 2023 |
| Intel         | Q3XXG4-P V1.0               | [5838cc1cac](https://bsd-hardware.info/?probe=5838cc1cac) | Jul 04, 2023 |
| Protectli     | FW4B Ver                    | [37fd6c7e30](https://bsd-hardware.info/?probe=37fd6c7e30) | Jul 04, 2023 |
| Protectli     | FW4B Ver                    | [dc56a8a565](https://bsd-hardware.info/?probe=dc56a8a565) | Jul 04, 2023 |
| Dell          | 0WR7PY A01                  | [d1662eef0f](https://bsd-hardware.info/?probe=d1662eef0f) | Jul 04, 2023 |
| Intel         | CRESCENTBAY                 | [d919ca6b12](https://bsd-hardware.info/?probe=d919ca6b12) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e212a51c70](https://bsd-hardware.info/?probe=e212a51c70) | Jul 03, 2023 |
| Protectli     | FW4C Ver                    | [3b591d1374](https://bsd-hardware.info/?probe=3b591d1374) | Jul 03, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [c265c181c2](https://bsd-hardware.info/?probe=c265c181c2) | Jul 03, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [4a7a333c20](https://bsd-hardware.info/?probe=4a7a333c20) | Jul 02, 2023 |
| MSI           | H81M-P33                    | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [496439b2aa](https://bsd-hardware.info/?probe=496439b2aa) | Jul 02, 2023 |
| Gigabyte      | MSQ87TN-00                  | [276b7100a2](https://bsd-hardware.info/?probe=276b7100a2) | Jul 01, 2023 |
| Gigabyte      | F2A68HM-H                   | [7cce12e9cf](https://bsd-hardware.info/?probe=7cce12e9cf) | Jul 01, 2023 |
| Protectli     | FW4A Ver                    | [997c72b98d](https://bsd-hardware.info/?probe=997c72b98d) | Jul 01, 2023 |
| Protectli     | FW6 Ver                     | [61c7be6541](https://bsd-hardware.info/?probe=61c7be6541) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Protectli     | FW6 Ver                     | [5c6f36540d](https://bsd-hardware.info/?probe=5c6f36540d) | Jun 29, 2023 |
| Protectli     | VP2420                      | [950ff902c2](https://bsd-hardware.info/?probe=950ff902c2) | Jun 29, 2023 |
| Intel         | DQ67SW AAG12527-310         | [5b272b02cb](https://bsd-hardware.info/?probe=5b272b02cb) | Jun 29, 2023 |
| HP            | 8055                        | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| Dell          | 0NW6H5 A00                  | [0cdc2b47b2](https://bsd-hardware.info/?probe=0cdc2b47b2) | Jun 29, 2023 |
| HP            | 8595                        | [e1a82ff0c5](https://bsd-hardware.info/?probe=e1a82ff0c5) | Jun 29, 2023 |
| Unknown       | Unknown                     | [41e020bc03](https://bsd-hardware.info/?probe=41e020bc03) | Jun 29, 2023 |
| Intel         | MAHOBAY                     | [4053bc358e](https://bsd-hardware.info/?probe=4053bc358e) | Jun 29, 2023 |
| Dell          | 0NC2VH A01                  | [d5a7320a8a](https://bsd-hardware.info/?probe=d5a7320a8a) | Jun 28, 2023 |
| HP            | 339A                        | [b08e1fc092](https://bsd-hardware.info/?probe=b08e1fc092) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | [bc448a4c10](https://bsd-hardware.info/?probe=bc448a4c10) | Jun 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [489b7b6bae](https://bsd-hardware.info/?probe=489b7b6bae) | Jun 26, 2023 |
| Unknown       | Unknown                     | [cd3b925f27](https://bsd-hardware.info/?probe=cd3b925f27) | Jun 26, 2023 |
| Gigabyte      | C1037UN                     | [fccc3f4b80](https://bsd-hardware.info/?probe=fccc3f4b80) | Jun 26, 2023 |
| AZW           | EQ                          | [c410cd5c1c](https://bsd-hardware.info/?probe=c410cd5c1c) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [dc937eee63](https://bsd-hardware.info/?probe=dc937eee63) | Jun 25, 2023 |
| MSI           | H81M-P33                    | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| Unknown       | Unknown                     | [32e290d370](https://bsd-hardware.info/?probe=32e290d370) | Jun 25, 2023 |
| Protectli     | FW6 Ver                     | [6210e8f0bc](https://bsd-hardware.info/?probe=6210e8f0bc) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | [93213fc931](https://bsd-hardware.info/?probe=93213fc931) | Jun 24, 2023 |
| Dell          | 0Y7WYT A00                  | [a931ed9f0a](https://bsd-hardware.info/?probe=a931ed9f0a) | Jun 23, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [b6916f61a8](https://bsd-hardware.info/?probe=b6916f61a8) | Jun 23, 2023 |
| AZW           | EQ                          | [8a85da80b2](https://bsd-hardware.info/?probe=8a85da80b2) | Jun 23, 2023 |
| CWWK          | CW-AD4L-N V1                | [b7ca7c7195](https://bsd-hardware.info/?probe=b7ca7c7195) | Jun 22, 2023 |
| Unknown       | Unknown                     | [f73625157c](https://bsd-hardware.info/?probe=f73625157c) | Jun 22, 2023 |
| Protectli     | VP2410                      | [94e2177a56](https://bsd-hardware.info/?probe=94e2177a56) | Jun 22, 2023 |
| Dell          | 0NW6H5 A00                  | [7d3a60d628](https://bsd-hardware.info/?probe=7d3a60d628) | Jun 22, 2023 |
| Techvision    | TVI7309X B0                 | [178a67ff39](https://bsd-hardware.info/?probe=178a67ff39) | Jun 21, 2023 |
| Dell          | 0NC2VH A01                  | [f094606e8f](https://bsd-hardware.info/?probe=f094606e8f) | Jun 21, 2023 |
| Hardkernel    | ODROID-H3                   | [8f550b0d75](https://bsd-hardware.info/?probe=8f550b0d75) | Jun 21, 2023 |
| BESSTAR Te... | TH50                        | [efc396837c](https://bsd-hardware.info/?probe=efc396837c) | Jun 21, 2023 |
| Techvision    | TVI7309X B0                 | [12d57aa9d9](https://bsd-hardware.info/?probe=12d57aa9d9) | Jun 21, 2023 |
| CWWK          | CW-AD4L-N V1                | [a09d71cc14](https://bsd-hardware.info/?probe=a09d71cc14) | Jun 21, 2023 |
| HP            | 802E                        | [595a5d4f60](https://bsd-hardware.info/?probe=595a5d4f60) | Jun 21, 2023 |
| Unknown       | Unknown                     | [d0c184ae86](https://bsd-hardware.info/?probe=d0c184ae86) | Jun 20, 2023 |
| Techvision    | TVI7309X B0                 | [1fa198f78d](https://bsd-hardware.info/?probe=1fa198f78d) | Jun 19, 2023 |
| Intel         | CRESCENTBAY                 | [e8c8da464a](https://bsd-hardware.info/?probe=e8c8da464a) | Jun 19, 2023 |
| Dell          | 07F37C A01                  | [16e5a062a2](https://bsd-hardware.info/?probe=16e5a062a2) | Jun 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| HP            | 83E9                        | [23ec260317](https://bsd-hardware.info/?probe=23ec260317) | Jun 16, 2023 |
| Unknown       | Unknown                     | [a6d5232f75](https://bsd-hardware.info/?probe=a6d5232f75) | Jun 16, 2023 |
| Unknown       | Unknown                     | [06754d9e71](https://bsd-hardware.info/?probe=06754d9e71) | Jun 15, 2023 |
| Dell          | 08NPPY A00                  | [8586467924](https://bsd-hardware.info/?probe=8586467924) | Jun 15, 2023 |
| MW            | GMLK-2_5G4L                 | [3274745a08](https://bsd-hardware.info/?probe=3274745a08) | Jun 15, 2023 |
| Protectli     | VP2420                      | [82ecf3a046](https://bsd-hardware.info/?probe=82ecf3a046) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [33b64d3084](https://bsd-hardware.info/?probe=33b64d3084) | Jun 13, 2023 |
| Dell          | 02YYK5 A00                  | [0dc0eab687](https://bsd-hardware.info/?probe=0dc0eab687) | Jun 13, 2023 |
| Pegatron      | 2AD5                        | [751e307940](https://bsd-hardware.info/?probe=751e307940) | Jun 13, 2023 |
| HP            | 213D A01                    | [2a6603c79a](https://bsd-hardware.info/?probe=2a6603c79a) | Jun 12, 2023 |
| Dell          | 0D28YY A00                  | [9f14962984](https://bsd-hardware.info/?probe=9f14962984) | Jun 11, 2023 |
| MSI           | H81M-P33                    | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| Protectli     | FW6 Ver                     | [3f8a97d0e7](https://bsd-hardware.info/?probe=3f8a97d0e7) | Jun 11, 2023 |
| Intel         | S1200KP AAG34877-201        | [39eba90e6a](https://bsd-hardware.info/?probe=39eba90e6a) | Jun 10, 2023 |
| Gigabyte      | C1037UN                     | [d8f7cea73b](https://bsd-hardware.info/?probe=d8f7cea73b) | Jun 10, 2023 |
| Intel         | S1200KP AAG34877-201        | [ec04f3f6d5](https://bsd-hardware.info/?probe=ec04f3f6d5) | Jun 10, 2023 |
| Protectli     | FW4B Ver                    | [af56081a76](https://bsd-hardware.info/?probe=af56081a76) | Jun 10, 2023 |
| Protectli     | FW6 Ver                     | [6cc2f54681](https://bsd-hardware.info/?probe=6cc2f54681) | Jun 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [7d23d1c91f](https://bsd-hardware.info/?probe=7d23d1c91f) | Jun 09, 2023 |
| PC Engines    | APU2                        | [24545e8f90](https://bsd-hardware.info/?probe=24545e8f90) | Jun 09, 2023 |
| Dell          | 0YXT71 A02                  | [e42082ba89](https://bsd-hardware.info/?probe=e42082ba89) | Jun 09, 2023 |
| MSI           | MS-7360                     | [f54096f3e5](https://bsd-hardware.info/?probe=f54096f3e5) | Jun 08, 2023 |
| ASUSTek       | M11AD                       | [7ffef5814d](https://bsd-hardware.info/?probe=7ffef5814d) | Jun 07, 2023 |
| MW            | GMLK-2_5G4L                 | [54c23902c7](https://bsd-hardware.info/?probe=54c23902c7) | Jun 07, 2023 |
| Pegatron      | 2AD5                        | [e50d3f9b86](https://bsd-hardware.info/?probe=e50d3f9b86) | Jun 06, 2023 |
| Dell          | 0NC2VH A01                  | [0b9ad8d7d8](https://bsd-hardware.info/?probe=0b9ad8d7d8) | Jun 06, 2023 |
| HP            | 843F                        | [57b6c258ad](https://bsd-hardware.info/?probe=57b6c258ad) | Jun 06, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [e07bfb044b](https://bsd-hardware.info/?probe=e07bfb044b) | Jun 06, 2023 |
| HP            | 212B                        | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| MW            | GMLK-2_5G4L                 | [e137b3e686](https://bsd-hardware.info/?probe=e137b3e686) | Jun 05, 2023 |
| HP            | 339A                        | [74f857c400](https://bsd-hardware.info/?probe=74f857c400) | Jun 05, 2023 |
| MSI           | H81M-P33                    | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| HP            | 802E                        | [2af6f8a101](https://bsd-hardware.info/?probe=2af6f8a101) | Jun 04, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [cf05481728](https://bsd-hardware.info/?probe=cf05481728) | Jun 04, 2023 |
| HP            | 805A                        | [3ad8551330](https://bsd-hardware.info/?probe=3ad8551330) | Jun 04, 2023 |
| Protectli     | FW4B Ver                    | [0f5b2ad316](https://bsd-hardware.info/?probe=0f5b2ad316) | Jun 03, 2023 |
| Unknown       | Unknown                     | [ffb4544d8c](https://bsd-hardware.info/?probe=ffb4544d8c) | Jun 03, 2023 |
| Protectli     | FW6 Ver                     | [a42fcbbc12](https://bsd-hardware.info/?probe=a42fcbbc12) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | [538e16bf08](https://bsd-hardware.info/?probe=538e16bf08) | Jun 03, 2023 |
| AAEON         | FWS-2360 V1.0               | [bcb707d6d0](https://bsd-hardware.info/?probe=bcb707d6d0) | Jun 02, 2023 |
| Unknown       | Unknown                     | [2702f3486a](https://bsd-hardware.info/?probe=2702f3486a) | Jun 02, 2023 |
| ASRockRack    | X570D4U-2L2T                | [4cada5d71b](https://bsd-hardware.info/?probe=4cada5d71b) | Jun 02, 2023 |
| Unknown       | Unknown                     | [09b74995b7](https://bsd-hardware.info/?probe=09b74995b7) | Jun 02, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [2348a2736e](https://bsd-hardware.info/?probe=2348a2736e) | Jun 02, 2023 |
| Unknown       | Unknown                     | [a3bc187a6b](https://bsd-hardware.info/?probe=a3bc187a6b) | Jun 02, 2023 |
| HP            | 805A                        | [b50fd38c94](https://bsd-hardware.info/?probe=b50fd38c94) | Jun 01, 2023 |
| Intel         | Q3XXG4-P V1.0               | [ef66603fb9](https://bsd-hardware.info/?probe=ef66603fb9) | Jun 01, 2023 |
| ASRock        | FM2A78M-ITX+                | [aecc8b1372](https://bsd-hardware.info/?probe=aecc8b1372) | Jun 01, 2023 |
| Dell          | 05XGC8 A01                  | [c40e01cab3](https://bsd-hardware.info/?probe=c40e01cab3) | Jun 01, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [8b0669a87d](https://bsd-hardware.info/?probe=8b0669a87d) | May 31, 2023 |
| HP            | 802E                        | [2b1f2776cd](https://bsd-hardware.info/?probe=2b1f2776cd) | May 31, 2023 |
| Gigabyte      | C1037UN                     | [7502577edc](https://bsd-hardware.info/?probe=7502577edc) | May 31, 2023 |
| CWWK          | CW-AD4L-N V1                | [d5a2882e49](https://bsd-hardware.info/?probe=d5a2882e49) | May 31, 2023 |
| Unknown       | Unknown                     | [f6643f3b06](https://bsd-hardware.info/?probe=f6643f3b06) | May 31, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c7f2f78173](https://bsd-hardware.info/?probe=c7f2f78173) | May 31, 2023 |
| Gigabyte      | C1037UN                     | [79e0162b9c](https://bsd-hardware.info/?probe=79e0162b9c) | May 30, 2023 |
| Intel         | S1200KP AAG34877-201        | [b264e962d0](https://bsd-hardware.info/?probe=b264e962d0) | May 30, 2023 |
| Dell          | 00V62H A01                  | [7d2e30807a](https://bsd-hardware.info/?probe=7d2e30807a) | May 30, 2023 |
| Protectli     | FW6 Ver                     | [21bad05407](https://bsd-hardware.info/?probe=21bad05407) | May 29, 2023 |
| Intel         | SKYBAY                      | [86747c5b22](https://bsd-hardware.info/?probe=86747c5b22) | May 29, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [a12b5d1715](https://bsd-hardware.info/?probe=a12b5d1715) | May 29, 2023 |
| Intel         | JSL MRD                     | [6fa703d206](https://bsd-hardware.info/?probe=6fa703d206) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Intel         | JSL MRD                     | [fc7970abd1](https://bsd-hardware.info/?probe=fc7970abd1) | May 28, 2023 |
| PC Engines    | APU2                        | [4c27451012](https://bsd-hardware.info/?probe=4c27451012) | May 28, 2023 |
| PC Engines    | APU2                        | [6b276a70c5](https://bsd-hardware.info/?probe=6b276a70c5) | May 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [3560dcfedc](https://bsd-hardware.info/?probe=3560dcfedc) | May 27, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [2caaa9f6cf](https://bsd-hardware.info/?probe=2caaa9f6cf) | May 27, 2023 |
| ASRock        | H270M-ITX/ac                | [69aaebd77e](https://bsd-hardware.info/?probe=69aaebd77e) | May 27, 2023 |
| Unknown       | Unknown                     | [0918049f45](https://bsd-hardware.info/?probe=0918049f45) | May 27, 2023 |
| Intel         | S1200KP AAG34877-201        | [5bf84ec376](https://bsd-hardware.info/?probe=5bf84ec376) | May 27, 2023 |
| Protectli     | FW6                         | [f7626db73e](https://bsd-hardware.info/?probe=f7626db73e) | May 27, 2023 |
| ASUSTek       | Z97-E/USB                   | [dbda738a56](https://bsd-hardware.info/?probe=dbda738a56) | May 27, 2023 |
| Dell          | 051FJ8 A02                  | [d0d211e4e7](https://bsd-hardware.info/?probe=d0d211e4e7) | May 27, 2023 |
| ChangWang     | CW56-58                     | [b6b902639c](https://bsd-hardware.info/?probe=b6b902639c) | May 27, 2023 |
| Dell          | 051FJ8 A02                  | [8ba976666f](https://bsd-hardware.info/?probe=8ba976666f) | May 27, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [19c6226530](https://bsd-hardware.info/?probe=19c6226530) | May 26, 2023 |
| Protectli     | VP2420                      | [2b716b3dd3](https://bsd-hardware.info/?probe=2b716b3dd3) | May 26, 2023 |
| Protectli     | FW4B Ver                    | [90b4ae806f](https://bsd-hardware.info/?probe=90b4ae806f) | May 25, 2023 |
| HP            | 8299                        | [14a7b5fc70](https://bsd-hardware.info/?probe=14a7b5fc70) | May 24, 2023 |
| Unknown       | Unknown                     | [a9d20f955e](https://bsd-hardware.info/?probe=a9d20f955e) | May 24, 2023 |
| Dell          | 0NC2VH A01                  | [572d966731](https://bsd-hardware.info/?probe=572d966731) | May 24, 2023 |
| ASUSTek       | PRIME A520M-A II            | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| Supermicro    | X8SIL                       | [21823c6dbd](https://bsd-hardware.info/?probe=21823c6dbd) | May 22, 2023 |
| Unknown       | Unknown                     | [b5e5e8e2cc](https://bsd-hardware.info/?probe=b5e5e8e2cc) | May 21, 2023 |
| MSI           | H81M-P33                    | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | [7c28bf2d83](https://bsd-hardware.info/?probe=7c28bf2d83) | May 20, 2023 |
| Gigabyte      | X570 UD                     | [5576c293d8](https://bsd-hardware.info/?probe=5576c293d8) | May 20, 2023 |
| ASUSTek       | Z87M-PLUS                   | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| ASUSTek       | Z97-E/USB                   | [484774ff19](https://bsd-hardware.info/?probe=484774ff19) | May 19, 2023 |
| HP            | 18E7                        | [477f3d4c80](https://bsd-hardware.info/?probe=477f3d4c80) | May 19, 2023 |
| Shuttle       | FH270                       | [95b532312a](https://bsd-hardware.info/?probe=95b532312a) | May 18, 2023 |
| Supermicro    | X7SBL                       | [b5ba4ba0e8](https://bsd-hardware.info/?probe=b5ba4ba0e8) | May 18, 2023 |
| Protectli     | FW4C                        | [a8252edc71](https://bsd-hardware.info/?probe=a8252edc71) | May 18, 2023 |
| HP            | 8299                        | [6d2f149a51](https://bsd-hardware.info/?probe=6d2f149a51) | May 18, 2023 |
| Techvision    | TVI7309X B0                 | [c4546c2b83](https://bsd-hardware.info/?probe=c4546c2b83) | May 17, 2023 |
| MW            | GMLK-2_5G4L                 | [39516c2e91](https://bsd-hardware.info/?probe=39516c2e91) | May 16, 2023 |
| MSI           | Z170A PC MATE               | [9c08a669ab](https://bsd-hardware.info/?probe=9c08a669ab) | May 16, 2023 |
| MSI           | Z170A PC MATE               | [75a9fd684a](https://bsd-hardware.info/?probe=75a9fd684a) | May 16, 2023 |
| MSI           | H81TI                       | [798ddd2aa1](https://bsd-hardware.info/?probe=798ddd2aa1) | May 16, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| MW            | GMLK-2_5G4L                 | [bc475b9528](https://bsd-hardware.info/?probe=bc475b9528) | May 15, 2023 |
| Protectli     | FW6 Ver                     | [ea9ff40bdb](https://bsd-hardware.info/?probe=ea9ff40bdb) | May 14, 2023 |
| ASRock        | 4X4-V1000                   | [189073c58e](https://bsd-hardware.info/?probe=189073c58e) | May 14, 2023 |
| HP            | 8054                        | [1ffc97728a](https://bsd-hardware.info/?probe=1ffc97728a) | May 14, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [cb87f3725f](https://bsd-hardware.info/?probe=cb87f3725f) | May 14, 2023 |
| MSI           | H81M-P33                    | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| Protectli     | FW1 Ver                     | [824016ccf0](https://bsd-hardware.info/?probe=824016ccf0) | May 14, 2023 |
| Dell          | 0MGK50 A01                  | [4222f2f8a5](https://bsd-hardware.info/?probe=4222f2f8a5) | May 13, 2023 |
| Unknown       | N4000                       | [48742290f1](https://bsd-hardware.info/?probe=48742290f1) | May 13, 2023 |
| Dell          | 0PC5F7 A02                  | [b22c9a0cdf](https://bsd-hardware.info/?probe=b22c9a0cdf) | May 13, 2023 |
| Unknown       | Unknown                     | [00a94d98fb](https://bsd-hardware.info/?probe=00a94d98fb) | May 13, 2023 |
| Unknown       | Unknown                     | [2e9d95aed5](https://bsd-hardware.info/?probe=2e9d95aed5) | May 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | [1daa68fb84](https://bsd-hardware.info/?probe=1daa68fb84) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [a477479a00](https://bsd-hardware.info/?probe=a477479a00) | May 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [de9fcd9543](https://bsd-hardware.info/?probe=de9fcd9543) | May 13, 2023 |
| Dell          | 02YYK5 A00                  | [71e4a5f1ec](https://bsd-hardware.info/?probe=71e4a5f1ec) | May 13, 2023 |
| BCM Advanc... | MX81HV/MX81H 10             | [f58c8bdd86](https://bsd-hardware.info/?probe=f58c8bdd86) | May 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| Biostar       | H61MGC                      | [001611da7e](https://bsd-hardware.info/?probe=001611da7e) | May 12, 2023 |
| Unknown       | YL-J3160L4                  | [fc9a0ecef6](https://bsd-hardware.info/?probe=fc9a0ecef6) | May 12, 2023 |
| JHZD          | BQM5                        | [6b32c22615](https://bsd-hardware.info/?probe=6b32c22615) | May 12, 2023 |
| JHZD          | BQM5                        | [fbbaf0b924](https://bsd-hardware.info/?probe=fbbaf0b924) | May 11, 2023 |
| Protectli     | FW6 Ver                     | [fc8375381d](https://bsd-hardware.info/?probe=fc8375381d) | May 11, 2023 |
| ASRock        | H370M-ITX/ac                | [1e9cfaf845](https://bsd-hardware.info/?probe=1e9cfaf845) | May 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [834174a5a8](https://bsd-hardware.info/?probe=834174a5a8) | May 11, 2023 |
| HP            | 1588h                       | [f1d543fb77](https://bsd-hardware.info/?probe=f1d543fb77) | May 11, 2023 |
| Protectli     | FW6 Ver                     | [f76a340f4a](https://bsd-hardware.info/?probe=f76a340f4a) | May 11, 2023 |
| Protectli     | FW6                         | [37432c6de1](https://bsd-hardware.info/?probe=37432c6de1) | May 10, 2023 |
| Dell          | 0Y7WYT A00                  | [89abd9548b](https://bsd-hardware.info/?probe=89abd9548b) | May 10, 2023 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [42b97c3277](https://bsd-hardware.info/?probe=42b97c3277) | May 10, 2023 |
| Dell          | 0NV0M7 A01                  | [72cdd452c8](https://bsd-hardware.info/?probe=72cdd452c8) | May 10, 2023 |
| Intel         | Q3XXG4-P V1.0               | [3359e9a10e](https://bsd-hardware.info/?probe=3359e9a10e) | May 10, 2023 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [df84be1ef9](https://bsd-hardware.info/?probe=df84be1ef9) | May 10, 2023 |
| ASUSTek       | P10S-E Series               | [37451da8a7](https://bsd-hardware.info/?probe=37451da8a7) | May 08, 2023 |
| Dell          | 040DDP A01                  | [d5fa48cd90](https://bsd-hardware.info/?probe=d5fa48cd90) | May 07, 2023 |
| MSI           | H81M-P33                    | [55cfed4de4](https://bsd-hardware.info/?probe=55cfed4de4) | May 07, 2023 |
| ASUSTek       | P5Q-E                       | [0cb51a327e](https://bsd-hardware.info/?probe=0cb51a327e) | May 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7e41914431](https://bsd-hardware.info/?probe=7e41914431) | May 07, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | [733c921923](https://bsd-hardware.info/?probe=733c921923) | May 07, 2023 |
| Dell          | 0HD5W2 A01                  | [a583770abc](https://bsd-hardware.info/?probe=a583770abc) | May 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f2ea102ee1](https://bsd-hardware.info/?probe=f2ea102ee1) | May 06, 2023 |
| ASRock        | X570 PG Velocita            | [46925c3dda](https://bsd-hardware.info/?probe=46925c3dda) | May 06, 2023 |
| AZW           | MINI S 10                   | [123024f70d](https://bsd-hardware.info/?probe=123024f70d) | May 06, 2023 |
| Dell          | 0Y7WYT A00                  | [dfb339020a](https://bsd-hardware.info/?probe=dfb339020a) | May 06, 2023 |
| Dell          | 0NV0M7 A01                  | [85256a78f6](https://bsd-hardware.info/?probe=85256a78f6) | May 05, 2023 |
| Unknown       | Unknown                     | [2002ddd198](https://bsd-hardware.info/?probe=2002ddd198) | May 05, 2023 |
| Protectli     | VP2420                      | [3fcbd494fc](https://bsd-hardware.info/?probe=3fcbd494fc) | May 05, 2023 |
| Supermicro    | X11SCV-Q                    | [7a6949713d](https://bsd-hardware.info/?probe=7a6949713d) | May 05, 2023 |
| CWWK          | MINIPC-G12                  | [f2ab15324b](https://bsd-hardware.info/?probe=f2ab15324b) | May 05, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [bdd112ce9b](https://bsd-hardware.info/?probe=bdd112ce9b) | May 05, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [982f87fd4d](https://bsd-hardware.info/?probe=982f87fd4d) | May 05, 2023 |
| Dell          | 0F6X5P A00                  | [ba619e879e](https://bsd-hardware.info/?probe=ba619e879e) | May 04, 2023 |
| GoWin Solu... | R86S                        | [a1274a9d0c](https://bsd-hardware.info/?probe=a1274a9d0c) | May 04, 2023 |
| Intel         | DQ77KB AAG81483-501         | [38f47bf53f](https://bsd-hardware.info/?probe=38f47bf53f) | May 04, 2023 |
| Protectli     | FW6 Ver                     | [5e30b0e6b1](https://bsd-hardware.info/?probe=5e30b0e6b1) | May 04, 2023 |
| Unknown       | Unknown                     | [c430ceb253](https://bsd-hardware.info/?probe=c430ceb253) | May 04, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [31c9c606ab](https://bsd-hardware.info/?probe=31c9c606ab) | May 04, 2023 |
| Unknown       | QSKL01                      | [4277dc49d0](https://bsd-hardware.info/?probe=4277dc49d0) | May 04, 2023 |
| Dell          | 0252PH A04                  | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| HP            | 82B4                        | [1bcefd3823](https://bsd-hardware.info/?probe=1bcefd3823) | May 02, 2023 |
| Dell          | 0T7D40 A00                  | [83ccb5ff07](https://bsd-hardware.info/?probe=83ccb5ff07) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3f089673e0](https://bsd-hardware.info/?probe=3f089673e0) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [396d7f268c](https://bsd-hardware.info/?probe=396d7f268c) | May 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a59b6fc6dc](https://bsd-hardware.info/?probe=a59b6fc6dc) | Apr 30, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [2cc6521d1f](https://bsd-hardware.info/?probe=2cc6521d1f) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| MSI           | H81M-P33                    | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b922b7925](https://bsd-hardware.info/?probe=2b922b7925) | Apr 30, 2023 |
| HP            | 83E1                        | [d3e5e9a563](https://bsd-hardware.info/?probe=d3e5e9a563) | Apr 30, 2023 |
| Dell          | 00V62H A00                  | [ad97036f62](https://bsd-hardware.info/?probe=ad97036f62) | Apr 29, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | [dbdb6539fb](https://bsd-hardware.info/?probe=dbdb6539fb) | Apr 29, 2023 |
| Protectli     | FW4C Ver                    | [29ecd63e1e](https://bsd-hardware.info/?probe=29ecd63e1e) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [9495b45b30](https://bsd-hardware.info/?probe=9495b45b30) | Apr 28, 2023 |
| Protectli     | VP2420                      | [b980175f4f](https://bsd-hardware.info/?probe=b980175f4f) | Apr 28, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [f6200a69eb](https://bsd-hardware.info/?probe=f6200a69eb) | Apr 28, 2023 |
| NCR           | Richmond BIOS.6.0           | [e41e1e5c70](https://bsd-hardware.info/?probe=e41e1e5c70) | Apr 28, 2023 |
| Protectli     | FW4B Ver                    | [ef3774c8f2](https://bsd-hardware.info/?probe=ef3774c8f2) | Apr 28, 2023 |
| Protectli     | VP2420                      | [8b2758be02](https://bsd-hardware.info/?probe=8b2758be02) | Apr 27, 2023 |
| HP            | 8299                        | [f26926526d](https://bsd-hardware.info/?probe=f26926526d) | Apr 27, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [9d15e108e6](https://bsd-hardware.info/?probe=9d15e108e6) | Apr 27, 2023 |
| Dell          | 0252PH A04                  | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| HP            | 83EE                        | [b5a00cabd1](https://bsd-hardware.info/?probe=b5a00cabd1) | Apr 26, 2023 |
| Unknown       | Unknown                     | [ece1b6bacb](https://bsd-hardware.info/?probe=ece1b6bacb) | Apr 26, 2023 |
| HP            | 859B                        | [357ef27be4](https://bsd-hardware.info/?probe=357ef27be4) | Apr 26, 2023 |
| HP            | 82B4                        | [58c58b6a82](https://bsd-hardware.info/?probe=58c58b6a82) | Apr 26, 2023 |
| HP            | 8056                        | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| AZW           | EQ                          | [8dd15b5070](https://bsd-hardware.info/?probe=8dd15b5070) | Apr 26, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6efffdce00](https://bsd-hardware.info/?probe=6efffdce00) | Apr 25, 2023 |
| ASUSTek       | P10S-E Series               | [e6d1a90732](https://bsd-hardware.info/?probe=e6d1a90732) | Apr 25, 2023 |
| HP            | 83E1                        | [865bd9b84e](https://bsd-hardware.info/?probe=865bd9b84e) | Apr 25, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | [b56e27db28](https://bsd-hardware.info/?probe=b56e27db28) | Apr 25, 2023 |
| Dell          | 0NV0M7 A01                  | [601f819826](https://bsd-hardware.info/?probe=601f819826) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cf0771c3a2](https://bsd-hardware.info/?probe=cf0771c3a2) | Apr 25, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | [02d2e2ea42](https://bsd-hardware.info/?probe=02d2e2ea42) | Apr 25, 2023 |
| HP            | 18E7                        | [777359d3c1](https://bsd-hardware.info/?probe=777359d3c1) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| Protectli     | FW4C Ver                    | [39d17845fb](https://bsd-hardware.info/?probe=39d17845fb) | Apr 24, 2023 |
| AZW           | EQ                          | [fe3205803d](https://bsd-hardware.info/?probe=fe3205803d) | Apr 24, 2023 |
| ASRock        | X370 Pro4                   | [9678198b3b](https://bsd-hardware.info/?probe=9678198b3b) | Apr 24, 2023 |
| Dell          | 0NV0M7 A01                  | [280ab26f33](https://bsd-hardware.info/?probe=280ab26f33) | Apr 24, 2023 |
| Supermicro    | A1SRi-2758F                 | [750e44f983](https://bsd-hardware.info/?probe=750e44f983) | Apr 24, 2023 |
| MW            | GMLK-2_5G4L                 | [b3a756536a](https://bsd-hardware.info/?probe=b3a756536a) | Apr 23, 2023 |
| MSI           | H81M-P33                    | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| Protectli     | VP2410 10                   | [463567a3e6](https://bsd-hardware.info/?probe=463567a3e6) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | [dab120ab36](https://bsd-hardware.info/?probe=dab120ab36) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [50ff0c14dd](https://bsd-hardware.info/?probe=50ff0c14dd) | Apr 22, 2023 |
| PC Engines    | apu1                        | [9838a040ba](https://bsd-hardware.info/?probe=9838a040ba) | Apr 22, 2023 |
| PC Engines    | apu1                        | [6e3df79f6d](https://bsd-hardware.info/?probe=6e3df79f6d) | Apr 22, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | [631a166cee](https://bsd-hardware.info/?probe=631a166cee) | Apr 22, 2023 |
| Protectli     | FW4B Ver                    | [f241a78410](https://bsd-hardware.info/?probe=f241a78410) | Apr 22, 2023 |
| HP            | 82B4                        | [35360c7568](https://bsd-hardware.info/?probe=35360c7568) | Apr 22, 2023 |
| Unknown       | Unknown                     | [66614019db](https://bsd-hardware.info/?probe=66614019db) | Apr 22, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [9b975ac704](https://bsd-hardware.info/?probe=9b975ac704) | Apr 22, 2023 |
| PC Engines    | APU                         | [c4238a76d1](https://bsd-hardware.info/?probe=c4238a76d1) | Apr 21, 2023 |
| PC Engines    | APU                         | [ae3ce982fe](https://bsd-hardware.info/?probe=ae3ce982fe) | Apr 21, 2023 |
| HP            | 83F2                        | [1ff683e02b](https://bsd-hardware.info/?probe=1ff683e02b) | Apr 20, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [6f85c5453c](https://bsd-hardware.info/?probe=6f85c5453c) | Apr 20, 2023 |
| GoWin Solu... | R86S                        | [5e94539f7f](https://bsd-hardware.info/?probe=5e94539f7f) | Apr 20, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [94507dfaf6](https://bsd-hardware.info/?probe=94507dfaf6) | Apr 20, 2023 |
| MW            | GMLK-2_5G4L                 | [24162b26be](https://bsd-hardware.info/?probe=24162b26be) | Apr 20, 2023 |
| PC Engines    | APU3                        | [110d848c38](https://bsd-hardware.info/?probe=110d848c38) | Apr 19, 2023 |
| Protectli     | FW4B Ver                    | [d727bd2723](https://bsd-hardware.info/?probe=d727bd2723) | Apr 19, 2023 |
| Dell          | 05XGC8 A01                  | [d89f79132d](https://bsd-hardware.info/?probe=d89f79132d) | Apr 19, 2023 |
| HP            | 8299                        | [a9e845749a](https://bsd-hardware.info/?probe=a9e845749a) | Apr 19, 2023 |
| Intel         | Q3XXG4-P V1.0               | [c626643f89](https://bsd-hardware.info/?probe=c626643f89) | Apr 18, 2023 |
| HP            | 8055                        | [83ecb873fe](https://bsd-hardware.info/?probe=83ecb873fe) | Apr 18, 2023 |
| AZW           | EQ                          | [c9fe4601ec](https://bsd-hardware.info/?probe=c9fe4601ec) | Apr 18, 2023 |
| PC Engines    | APU2                        | [5d714a9c0d](https://bsd-hardware.info/?probe=5d714a9c0d) | Apr 18, 2023 |
| Gigabyte      | A520M DS3H AC               | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| ASRock        | B250M-HDV                   | [3608477e76](https://bsd-hardware.info/?probe=3608477e76) | Apr 16, 2023 |
| MSI           | H81M-P33                    | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Techvision    | TVI7309X B0                 | [4110309ccc](https://bsd-hardware.info/?probe=4110309ccc) | Apr 16, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [773b28fbc7](https://bsd-hardware.info/?probe=773b28fbc7) | Apr 16, 2023 |
| ASUSTek       | P5BV-E                      | [f134ff34ba](https://bsd-hardware.info/?probe=f134ff34ba) | Apr 15, 2023 |
| Techvision    | TVI7309X B0                 | [3b0562fe2a](https://bsd-hardware.info/?probe=3b0562fe2a) | Apr 15, 2023 |
| MW            | GMLK-2_5G4L                 | [4127e0b00d](https://bsd-hardware.info/?probe=4127e0b00d) | Apr 15, 2023 |
| Protectli     | FW6                         | [15753be1b9](https://bsd-hardware.info/?probe=15753be1b9) | Apr 15, 2023 |
| MW            | GMLK-2_5G4L                 | [e665283e47](https://bsd-hardware.info/?probe=e665283e47) | Apr 15, 2023 |
| ASRockRack    | C226M WS                    | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| MSI           | Z87-G41 PC Mate             | [3958a90c04](https://bsd-hardware.info/?probe=3958a90c04) | Apr 13, 2023 |
| MW            | GMLK-2_5G4L                 | [93632f99ad](https://bsd-hardware.info/?probe=93632f99ad) | Apr 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| Dell          | 02YYK5 A00                  | [3f95d84c6f](https://bsd-hardware.info/?probe=3f95d84c6f) | Apr 13, 2023 |
| ECS           | Z77H2-AX                    | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| Dell          | 03NVJ6 A00                  | [128489e571](https://bsd-hardware.info/?probe=128489e571) | Apr 12, 2023 |
| HP            | 212B                        | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6622d21ee9](https://bsd-hardware.info/?probe=6622d21ee9) | Apr 12, 2023 |
| Supermicro    | C7SIM-Q                     | [dca54cc956](https://bsd-hardware.info/?probe=dca54cc956) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | [f44190a72a](https://bsd-hardware.info/?probe=f44190a72a) | Apr 11, 2023 |
| Protectli     | FW4B Ver                    | [c9d3e3ccd9](https://bsd-hardware.info/?probe=c9d3e3ccd9) | Apr 11, 2023 |
| Protectli     | FW4C Ver                    | [14e9a37e55](https://bsd-hardware.info/?probe=14e9a37e55) | Apr 11, 2023 |
| Dell          | 04JGCK A01                  | [5eb06957e2](https://bsd-hardware.info/?probe=5eb06957e2) | Apr 10, 2023 |
| Dell          | 04JGCK A01                  | [43e509c47b](https://bsd-hardware.info/?probe=43e509c47b) | Apr 10, 2023 |
| MSI           | H81M-P33                    | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| HP            | 212B                        | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0e9cae4351](https://bsd-hardware.info/?probe=0e9cae4351) | Apr 09, 2023 |
| GoWin Solu... | R86S                        | [6b448c285b](https://bsd-hardware.info/?probe=6b448c285b) | Apr 08, 2023 |
| Dell          | 02YYK5 A01                  | [c4cb33b0a1](https://bsd-hardware.info/?probe=c4cb33b0a1) | Apr 08, 2023 |
| Protectli     | FW6 Ver                     | [7525421240](https://bsd-hardware.info/?probe=7525421240) | Apr 08, 2023 |
| HP            | 83EF                        | [56fd6177cd](https://bsd-hardware.info/?probe=56fd6177cd) | Apr 07, 2023 |
| HP            | 83F2                        | [40a4bc3252](https://bsd-hardware.info/?probe=40a4bc3252) | Apr 06, 2023 |
| PC Engines    | APU2                        | [83b404b047](https://bsd-hardware.info/?probe=83b404b047) | Apr 06, 2023 |
| Dell          | 0WMJ54 A01                  | [ea48bd3665](https://bsd-hardware.info/?probe=ea48bd3665) | Apr 06, 2023 |
| Intel         | MAHOBAY                     | [bae6bb22e0](https://bsd-hardware.info/?probe=bae6bb22e0) | Apr 06, 2023 |
| Dell          | 05GD68 A00                  | [00cc70100d](https://bsd-hardware.info/?probe=00cc70100d) | Apr 06, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [eb5e28d965](https://bsd-hardware.info/?probe=eb5e28d965) | Apr 05, 2023 |
| Unknown       | Unknown                     | [3e06c6010d](https://bsd-hardware.info/?probe=3e06c6010d) | Apr 05, 2023 |
| Dell          | 0KWVT8 A03                  | [05465e4575](https://bsd-hardware.info/?probe=05465e4575) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | [6a4aceff9b](https://bsd-hardware.info/?probe=6a4aceff9b) | Apr 04, 2023 |
| Unknown       | Unknown                     | [3fdf1c8c26](https://bsd-hardware.info/?probe=3fdf1c8c26) | Apr 04, 2023 |
| CWWK          | MINIPC-G4                   | [ece70e8117](https://bsd-hardware.info/?probe=ece70e8117) | Apr 04, 2023 |
| Protectli     | FW4C                        | [b0d1010d58](https://bsd-hardware.info/?probe=b0d1010d58) | Apr 04, 2023 |
| Dell          | 0HD5W2 A00                  | [43c6f94486](https://bsd-hardware.info/?probe=43c6f94486) | Apr 04, 2023 |
| MW            | GMLK-2_5G4L                 | [61ab7d478c](https://bsd-hardware.info/?probe=61ab7d478c) | Apr 03, 2023 |
| Gigabyte      | X570 UD                     | [e0b56a9911](https://bsd-hardware.info/?probe=e0b56a9911) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | [1d4b3bd94f](https://bsd-hardware.info/?probe=1d4b3bd94f) | Apr 03, 2023 |
| HP            | 212B                        | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | [6b05bd9d53](https://bsd-hardware.info/?probe=6b05bd9d53) | Apr 03, 2023 |
| MSI           | H81M-P33                    | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| HP            | 82A2                        | [92fb7830a2](https://bsd-hardware.info/?probe=92fb7830a2) | Apr 02, 2023 |
| ASUSTek       | Z97-E/USB                   | [0ce88445bf](https://bsd-hardware.info/?probe=0ce88445bf) | Apr 02, 2023 |
| Sun           | SUNW,T5140                  | [a285e4f43a](https://bsd-hardware.info/?probe=a285e4f43a) | Apr 02, 2023 |
| Protectli     | VP2410                      | [8eda4d8e3d](https://bsd-hardware.info/?probe=8eda4d8e3d) | Apr 01, 2023 |
| Dell          | 0N4YC8 A00                  | [bd01e6e577](https://bsd-hardware.info/?probe=bd01e6e577) | Apr 01, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | [b41b088f96](https://bsd-hardware.info/?probe=b41b088f96) | Apr 01, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [31ed779fdc](https://bsd-hardware.info/?probe=31ed779fdc) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| HP            | 1495                        | [a916ab2122](https://bsd-hardware.info/?probe=a916ab2122) | Mar 31, 2023 |
| Intel         | DENLOW_REFRESH_WS           | [1285cbe6ca](https://bsd-hardware.info/?probe=1285cbe6ca) | Mar 31, 2023 |
| Protectli     | FW4B Ver                    | [cc6e076383](https://bsd-hardware.info/?probe=cc6e076383) | Mar 31, 2023 |
| Gigabyte      | X570 UD                     | [a71a4da74b](https://bsd-hardware.info/?probe=a71a4da74b) | Mar 31, 2023 |
| Foxconn       | nT-A3000 series FAB         | [c13f32c492](https://bsd-hardware.info/?probe=c13f32c492) | Mar 30, 2023 |
| Inventec      | Z CLASS A02                 | [c654ef10d6](https://bsd-hardware.info/?probe=c654ef10d6) | Mar 30, 2023 |
| Protectli     | FW4B Ver                    | [27d9a92cda](https://bsd-hardware.info/?probe=27d9a92cda) | Mar 30, 2023 |
| Unknown       | Unknown                     | [44da021f65](https://bsd-hardware.info/?probe=44da021f65) | Mar 29, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [dc06ff6076](https://bsd-hardware.info/?probe=dc06ff6076) | Mar 29, 2023 |
| ASRock        | B550M Steel Legend          | [06a2d12cbe](https://bsd-hardware.info/?probe=06a2d12cbe) | Mar 29, 2023 |
| Supermicro    | C7SIM-Q                     | [47ce885e13](https://bsd-hardware.info/?probe=47ce885e13) | Mar 29, 2023 |
| ASRock        | H510M-HVS R2.0              | [38a784fcd8](https://bsd-hardware.info/?probe=38a784fcd8) | Mar 29, 2023 |
| Unknown       | Unknown                     | [723e81c698](https://bsd-hardware.info/?probe=723e81c698) | Mar 29, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [3895705bbd](https://bsd-hardware.info/?probe=3895705bbd) | Mar 29, 2023 |
| Apple         | Mac-F221BEC8                | [b2a2fc8fe6](https://bsd-hardware.info/?probe=b2a2fc8fe6) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [2c6fc04801](https://bsd-hardware.info/?probe=2c6fc04801) | Mar 29, 2023 |
| Unknown       | Unknown                     | [c6c33779dc](https://bsd-hardware.info/?probe=c6c33779dc) | Mar 29, 2023 |
| HP            | 18E7                        | [f83e0bbd69](https://bsd-hardware.info/?probe=f83e0bbd69) | Mar 28, 2023 |
| BESSTAR Te... | UM700                       | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| Protectli     | FW4B                        | [17c0040b42](https://bsd-hardware.info/?probe=17c0040b42) | Mar 28, 2023 |
| HP            | 8054                        | [6c82269548](https://bsd-hardware.info/?probe=6c82269548) | Mar 27, 2023 |
| HP            | 213D A01                    | [d5efcf6e96](https://bsd-hardware.info/?probe=d5efcf6e96) | Mar 27, 2023 |
| ASUSTek       | Z97-E/USB                   | [e5a3f523a6](https://bsd-hardware.info/?probe=e5a3f523a6) | Mar 27, 2023 |
| WeiBu         | ADL-N Prod                  | [1d0a4ac0a1](https://bsd-hardware.info/?probe=1d0a4ac0a1) | Mar 27, 2023 |
| WeiBu         | ADL-N Prod                  | [91759ff33b](https://bsd-hardware.info/?probe=91759ff33b) | Mar 27, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0eab0142d5](https://bsd-hardware.info/?probe=0eab0142d5) | Mar 26, 2023 |
| CWWK          | MINIPC-G4                   | [06e3c70f23](https://bsd-hardware.info/?probe=06e3c70f23) | Mar 26, 2023 |
| CWWK          | MINIPC-G4                   | [8f47736c3b](https://bsd-hardware.info/?probe=8f47736c3b) | Mar 26, 2023 |
| ChangWang     | CW56-58                     | [39410cb2dd](https://bsd-hardware.info/?probe=39410cb2dd) | Mar 26, 2023 |
| MSI           | H81M-P33                    | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| ASRock        | H510M-HVS R2.0              | [3db3c8f002](https://bsd-hardware.info/?probe=3db3c8f002) | Mar 26, 2023 |
| Dell          | 0HD5W2 A01                  | [284c499b74](https://bsd-hardware.info/?probe=284c499b74) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | [2634ccb935](https://bsd-hardware.info/?probe=2634ccb935) | Mar 26, 2023 |
| Acer          | Aspire XC-830               | [bc1cc29291](https://bsd-hardware.info/?probe=bc1cc29291) | Mar 26, 2023 |
| Acer          | Aspire XC-830               | [2affd2540a](https://bsd-hardware.info/?probe=2affd2540a) | Mar 26, 2023 |
| CheckPoint    | T-110-00                    | [eecf6b8096](https://bsd-hardware.info/?probe=eecf6b8096) | Mar 25, 2023 |
| Protectli     | FW4B                        | [3c333bad9c](https://bsd-hardware.info/?probe=3c333bad9c) | Mar 25, 2023 |
| Unknown       | Unknown                     | [c7c5a8ae97](https://bsd-hardware.info/?probe=c7c5a8ae97) | Mar 25, 2023 |
| Hardkernel    | ODROID-H3                   | [312a9b3461](https://bsd-hardware.info/?probe=312a9b3461) | Mar 25, 2023 |
| ASUSTek       | Z97-E/USB                   | [9aa3b17016](https://bsd-hardware.info/?probe=9aa3b17016) | Mar 25, 2023 |
| HP            | 8055                        | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | [56c12d6bf6](https://bsd-hardware.info/?probe=56c12d6bf6) | Mar 24, 2023 |
| ASUSTek       | Z97-E/USB                   | [e9cbfc666b](https://bsd-hardware.info/?probe=e9cbfc666b) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | [e99acbbc10](https://bsd-hardware.info/?probe=e99acbbc10) | Mar 24, 2023 |
| HP            | 3397                        | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M910q 10MVCT... | [5459ed9c31](https://bsd-hardware.info/?probe=5459ed9c31) | Mar 22, 2023 |
| Dell          | 0WWJRX A00                  | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Protectli     | FW4C Ver                    | [73ecb1afc1](https://bsd-hardware.info/?probe=73ecb1afc1) | Mar 22, 2023 |
| ASRock        | B450M Pro4                  | [e2d0aa1444](https://bsd-hardware.info/?probe=e2d0aa1444) | Mar 22, 2023 |
| Protectli     | FW4B Ver                    | [c2546b211b](https://bsd-hardware.info/?probe=c2546b211b) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| NF596         | 1.0                         | [9de0fd33a4](https://bsd-hardware.info/?probe=9de0fd33a4) | Mar 22, 2023 |
| Protectli     | VP2410 10                   | [491f4cc780](https://bsd-hardware.info/?probe=491f4cc780) | Mar 22, 2023 |
| ASRock        | B460M-HDV                   | [e1ee6d8a11](https://bsd-hardware.info/?probe=e1ee6d8a11) | Mar 22, 2023 |
| ASRockRack    | E3C236D2I                   | [e407119ecf](https://bsd-hardware.info/?probe=e407119ecf) | Mar 22, 2023 |
| ASRockRack    | E3C236D2I                   | [0854f96185](https://bsd-hardware.info/?probe=0854f96185) | Mar 21, 2023 |
| ASRock        | X570M Pro4                  | [e405ff5adf](https://bsd-hardware.info/?probe=e405ff5adf) | Mar 21, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [7bac9347ec](https://bsd-hardware.info/?probe=7bac9347ec) | Mar 21, 2023 |
| Techvision    | TVI7309X B0                 | [8d84f81be3](https://bsd-hardware.info/?probe=8d84f81be3) | Mar 21, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| Silicom       | 80300-0134-g01              | [3cd6c5ba13](https://bsd-hardware.info/?probe=3cd6c5ba13) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [10f3485393](https://bsd-hardware.info/?probe=10f3485393) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| Unknown       | Unknown                     | [91b5500917](https://bsd-hardware.info/?probe=91b5500917) | Mar 19, 2023 |
| MSI           | H81M-P33                    | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| Protectli     | FW4B Ver                    | [317c44acd2](https://bsd-hardware.info/?probe=317c44acd2) | Mar 19, 2023 |
| Datto         | SSD                         | [40831257b2](https://bsd-hardware.info/?probe=40831257b2) | Mar 19, 2023 |
| HP            | 212B                        | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [4e1fe3a676](https://bsd-hardware.info/?probe=4e1fe3a676) | Mar 18, 2023 |
| HP            | 18E7                        | [d3b280214a](https://bsd-hardware.info/?probe=d3b280214a) | Mar 18, 2023 |
| Unknown       | QD-CMU01                    | [c6ddfac225](https://bsd-hardware.info/?probe=c6ddfac225) | Mar 18, 2023 |
| Protectli     | FW6                         | [f24f1a8a3e](https://bsd-hardware.info/?probe=f24f1a8a3e) | Mar 17, 2023 |
| Unknown       | Unknown                     | [daaa6c0069](https://bsd-hardware.info/?probe=daaa6c0069) | Mar 17, 2023 |
| Protectli     | FW4B                        | [fd65403ca2](https://bsd-hardware.info/?probe=fd65403ca2) | Mar 17, 2023 |
| HP            | 3397                        | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| Unknown       | Unknown                     | [d0a9398982](https://bsd-hardware.info/?probe=d0a9398982) | Mar 16, 2023 |
| Unknown       | Unknown                     | [19fc3562d9](https://bsd-hardware.info/?probe=19fc3562d9) | Mar 16, 2023 |
| Silicom       | 80300-0134-g01              | [228e446ed5](https://bsd-hardware.info/?probe=228e446ed5) | Mar 15, 2023 |
| Dell          | 0M9KCM A00                  | [27a1ab8450](https://bsd-hardware.info/?probe=27a1ab8450) | Mar 15, 2023 |
| Dell          | 078NPM A00                  | [234e8a451a](https://bsd-hardware.info/?probe=234e8a451a) | Mar 14, 2023 |
| ASUSTek       | Pro B550M-C                 | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Gigabyte      | H370M D3H-CF                | [8025ea3b29](https://bsd-hardware.info/?probe=8025ea3b29) | Mar 14, 2023 |
| Protectli     | FW4C Ver                    | [6b260b1da3](https://bsd-hardware.info/?probe=6b260b1da3) | Mar 14, 2023 |
| Intel         | HURONRIVER                  | [06f89fc17d](https://bsd-hardware.info/?probe=06f89fc17d) | Mar 14, 2023 |
| Lenovo        | 0B98401 PRO                 | [4e27c68fa1](https://bsd-hardware.info/?probe=4e27c68fa1) | Mar 14, 2023 |
| Google        | Panther                     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Unknown       | Unknown                     | [51bc37434e](https://bsd-hardware.info/?probe=51bc37434e) | Mar 13, 2023 |
| Intel         | QHSW02                      | [ccfc6d4abf](https://bsd-hardware.info/?probe=ccfc6d4abf) | Mar 13, 2023 |
| Intel         | QHSW02                      | [b56a128e7e](https://bsd-hardware.info/?probe=b56a128e7e) | Mar 13, 2023 |
| MSI           | Z87-G41 PC Mate             | [f1dc71b749](https://bsd-hardware.info/?probe=f1dc71b749) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| MSI           | Z87-G41 PC Mate             | [8f819aa5b0](https://bsd-hardware.info/?probe=8f819aa5b0) | Mar 13, 2023 |
| HP            | 8056                        | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| HP            | 18E7                        | [a5f169c741](https://bsd-hardware.info/?probe=a5f169c741) | Mar 13, 2023 |
| Dell          | 02YYK5 A00                  | [82ec8cfd3b](https://bsd-hardware.info/?probe=82ec8cfd3b) | Mar 13, 2023 |
| HP            | 1495                        | [840b4864ab](https://bsd-hardware.info/?probe=840b4864ab) | Mar 13, 2023 |
| Unknown       | Unknown                     | [1bff43fa4b](https://bsd-hardware.info/?probe=1bff43fa4b) | Mar 13, 2023 |
| Unknown       | Unknown                     | [2b318d15c4](https://bsd-hardware.info/?probe=2b318d15c4) | Mar 13, 2023 |
| Protectli     | FW4B Ver                    | [a81fd51eee](https://bsd-hardware.info/?probe=a81fd51eee) | Mar 13, 2023 |
| HP            | 213D A01                    | [7021648a32](https://bsd-hardware.info/?probe=7021648a32) | Mar 13, 2023 |
| Lenovo        | SHARKBAY SDK0K17763 WIN ... | [c9279ce424](https://bsd-hardware.info/?probe=c9279ce424) | Mar 13, 2023 |
| Dell          | 02YYK5 A01                  | [fe42d48be1](https://bsd-hardware.info/?probe=fe42d48be1) | Mar 13, 2023 |
| GoWin Solu... | R86S                        | [44f983da74](https://bsd-hardware.info/?probe=44f983da74) | Mar 12, 2023 |
| Dell          | 0WMJ54 A00                  | [8a41ff57c2](https://bsd-hardware.info/?probe=8a41ff57c2) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| ASRock        | 4X4-V1000                   | [f0582d78bf](https://bsd-hardware.info/?probe=f0582d78bf) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | [38af3096a6](https://bsd-hardware.info/?probe=38af3096a6) | Mar 12, 2023 |
| Dell          | 0KYJ8C A02                  | [53fa01007b](https://bsd-hardware.info/?probe=53fa01007b) | Mar 12, 2023 |
| Dell          | 02YYK5 A01                  | [69db0ac0a4](https://bsd-hardware.info/?probe=69db0ac0a4) | Mar 12, 2023 |
| Unknown       | Unknown                     | [83fa5b5a27](https://bsd-hardware.info/?probe=83fa5b5a27) | Mar 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| OPNsense 23.1.11 | 92       | 3.29%   |
| OPNsense 21.7.7  | 67       | 2.4%    |
| OPNsense 22.7.10 | 63       | 2.25%   |
| OPNsense 23.1    | 58       | 2.08%   |
| OPNsense 23.1.7  | 56       | 2%      |
| OPNsense 21.7.3  | 56       | 2%      |
| OPNsense 22.1.10 | 54       | 1.93%   |
| OPNsense 23.1.5  | 52       | 1.86%   |
| OPNsense 23.7.1  | 51       | 1.82%   |
| OPNsense 22.7.4  | 51       | 1.82%   |
| OPNsense 21.1.5  | 49       | 1.75%   |
| OPNsense 22.1    | 47       | 1.68%   |
| OPNsense 23.1.1  | 46       | 1.65%   |
| OPNsense 20.7.8  | 46       | 1.65%   |
| OPNsense 21.7.1  | 45       | 1.61%   |
| OPNsense 22.1.8  | 44       | 1.57%   |
| OPNsense 21.1.3  | 43       | 1.54%   |
| OPNsense 23.7.3  | 42       | 1.5%    |
| OPNsense 23.1.6  | 41       | 1.47%   |
| OPNsense 21.1.4  | 40       | 1.43%   |
| OPNsense 23.1.9  | 39       | 1.4%    |
| OPNsense 22.7.8  | 38       | 1.36%   |
| OPNsense 21.1    | 38       | 1.36%   |
| OPNsense 21.1.8  | 37       | 1.32%   |
| OPNsense 23.7    | 35       | 1.25%   |
| OPNsense 23.7.7  | 34       | 1.22%   |
| OPNsense 22.7.11 | 34       | 1.22%   |
| OPNsense 22.1.6  | 34       | 1.22%   |
| OPNsense 22.1.2  | 34       | 1.22%   |
| OPNsense 22.7.6  | 33       | 1.18%   |
| OPNsense 23.1.3  | 32       | 1.14%   |
| OPNsense 22.7.7  | 32       | 1.14%   |
| OPNsense 22.7.9  | 31       | 1.11%   |
| OPNsense 22.1.4  | 31       | 1.11%   |
| OPNsense 21.1.1  | 30       | 1.07%   |
| OPNsense 21.7.6  | 29       | 1.04%   |
| OPNsense 23.7.4  | 28       | 1%      |
| OPNsense 23.1.4  | 28       | 1%      |
| OPNsense 22.7.2  | 28       | 1%      |
| OPNsense 21.1.7  | 28       | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 1436     | 74.21%  |
| FreeBSD     | 236      | 12.2%   |
| helloSystem | 116      | 5.99%   |
| OpenBSD     | 41       | 2.12%   |
| GhostBSD    | 23       | 1.19%   |
| NomadBSD    | 17       | 0.88%   |
| pfSense     | 15       | 0.78%   |
| FreeNAS     | 14       | 0.72%   |
| MidnightBSD | 13       | 0.67%   |
| TrueNAS     | 9        | 0.47%   |
| NetBSD      | 5        | 0.26%   |
| XigmaNAS    | 2        | 0.1%    |
| OS108       | 2        | 0.1%    |
| HardenedBSD | 2        | 0.1%    |
| MyBee       | 1        | 0.05%   |
| FuryBSD     | 1        | 0.05%   |
| DragonFly   | 1        | 0.05%   |
| ClonOS      | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 1900     | 98.86%  |
| i386    | 9        | 0.47%   |
| arm64   | 9        | 0.47%   |
| powerpc | 3        | 0.16%   |
| sparc64 | 1        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 1607     | 82.24%  |
| helloDesktop  | 126      | 6.45%   |
| XFCE          | 40       | 2.05%   |
| KDE5          | 36       | 1.84%   |
| MATE          | 32       | 1.64%   |
| TWM           | 27       | 1.38%   |
| GNOME         | 21       | 1.07%   |
| Openbox       | 20       | 1.02%   |
| fvwm          | 18       | 0.92%   |
| i3            | 11       | 0.56%   |
| Cinnamon      | 4        | 0.2%    |
| Lumina        | 3        | 0.15%   |
| Enlightenment | 3        | 0.15%   |
| Picom         | 2        | 0.1%    |
| Xfwm4         | 1        | 0.05%   |
| Window Maker  | 1        | 0.05%   |
| Fluxbox       | 1        | 0.05%   |
| DWM           | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1614     | 83.5%   |
| X11     | 318      | 16.45%  |
| Wayland | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1686     | 87.09%  |
| SLiM    | 148      | 7.64%   |
| LightDM | 37       | 1.91%   |
| SDDM    | 30       | 1.55%   |
| XDM     | 23       | 1.19%   |
| GDM     | 12       | 0.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 1595     | 81.17%  |
| en_US           | 198      | 10.08%  |
| C               | 146      | 7.43%   |
| en              | 13       | 0.66%   |
| fr_FR           | 5        | 0.25%   |
| fr              | 4        | 0.2%    |
| ru_RU           | 1        | 0.05%   |
| en_US.utf-8     | 1        | 0.05%   |
| en_US.ISO8859-1 | 1        | 0.05%   |
| en_GB           | 1        | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 1704     | 87.07%  |
| BIOS | 253      | 12.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 1086     | 54.63%  |
| Zfs     | 819      | 41.2%   |
| Ffs     | 41       | 2.06%   |
| Cd9660  | 40       | 2.01%   |
| Hammer2 | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1812     | 93.26%  |
| MBR     | 117      | 6.02%   |
| Unknown | 11       | 0.57%   |
| BSD     | 3        | 0.15%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell                       | 259      | 13.48%  |
| Protectli                  | 224      | 11.65%  |
| Unknown                    | 222      | 11.55%  |
| Hewlett-Packard            | 178      | 9.26%   |
| ASUSTek Computer           | 162      | 8.43%   |
| Intel                      | 106      | 5.52%   |
| ASRock                     | 105      | 5.46%   |
| Supermicro                 | 102      | 5.31%   |
| Gigabyte Technology        | 85       | 4.42%   |
| MSI                        | 74       | 3.85%   |
| Lenovo                     | 66       | 3.43%   |
| PC Engines                 | 39       | 2.03%   |
| Techvision                 | 26       | 1.35%   |
| AZW                        | 19       | 0.99%   |
| MW                         | 15       | 0.78%   |
| Biostar                    | 13       | 0.68%   |
| Acer                       | 13       | 0.68%   |
| CWWK                       | 12       | 0.62%   |
| Shuttle                    | 10       | 0.52%   |
| ASRockRack                 | 10       | 0.52%   |
| Seeed Studio               | 9        | 0.47%   |
| Apple                      | 9        | 0.47%   |
| Foxconn                    | 8        | 0.42%   |
| Hardkernel                 | 7        | 0.36%   |
| Fujitsu                    | 7        | 0.36%   |
| CheckPoint                 | 7        | 0.36%   |
| AAEON                      | 6        | 0.31%   |
| SeeedStudio                | 5        | 0.26%   |
| IceWhale Technology        | 5        | 0.26%   |
| CncTion                    | 5        | 0.26%   |
| Cisco                      | 5        | 0.26%   |
| BESSTAR Tech               | 5        | 0.26%   |
| TYAN Computer              | 4        | 0.21%   |
| ShenZhen MinWin Technology | 4        | 0.21%   |
| Pegatron                   | 4        | 0.21%   |
| GoWin Solution             | 4        | 0.21%   |
| Google                     | 4        | 0.21%   |
| Win element                | 3        | 0.16%   |
| Silicom                    | 3        | 0.16%   |
| MiTAC                      | 3        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Unknown                     | 225      | 11.71%  |
| Protectli FW4B              | 74       | 3.85%   |
| Protectli FW6               | 62       | 3.23%   |
| Intel Q3XXG4-P V1.0         | 41       | 2.13%   |
| Dell OptiPlex 9020          | 27       | 1.4%    |
| Techvision TVI7309X         | 26       | 1.35%   |
| Dell OptiPlex 3020          | 25       | 1.3%    |
| HP t620 PLUS Quad Core TC   | 24       | 1.25%   |
| ASUS All Series             | 23       | 1.2%    |
| Supermicro X9SCL/X9SCM      | 21       | 1.09%   |
| PC Engines APU2             | 19       | 0.99%   |
| Dell OptiPlex 7010          | 19       | 0.99%   |
| Protectli VP2410            | 15       | 0.78%   |
| PC Engines apu4             | 15       | 0.78%   |
| MW GMLK-2_5G4L              | 15       | 0.78%   |
| Protectli FW2B              | 13       | 0.68%   |
| Dell OptiPlex 990           | 13       | 0.68%   |
| Dell OptiPlex 7040          | 13       | 0.68%   |
| Protectli FW4C              | 12       | 0.62%   |
| Protectli VP2420            | 11       | 0.57%   |
| Protectli FW1               | 11       | 0.57%   |
| HP EliteDesk 800 G3 SFF     | 11       | 0.57%   |
| HP EliteDesk 800 G1 SFF     | 11       | 0.57%   |
| Dell OptiPlex 3040          | 10       | 0.52%   |
| Intel Nobilis               | 9        | 0.47%   |
| HP Compaq Elite 8300 SFF    | 9        | 0.47%   |
| Dell OptiPlex 9010          | 9        | 0.47%   |
| Dell OptiPlex 790           | 9        | 0.47%   |
| Dell OptiPlex 390           | 9        | 0.47%   |
| HP ProDesk 600 G1 SFF       | 8        | 0.42%   |
| Dell OptiPlex 7020          | 8        | 0.42%   |
| Protectli FW6E              | 7        | 0.36%   |
| Protectli FW6D              | 7        | 0.36%   |
| HP EliteDesk 800 G2 SFF     | 7        | 0.36%   |
| HP Compaq 8200 Elite SFF PC | 7        | 0.36%   |
| CWWK CW-AD4L-N V1           | 7        | 0.36%   |
| AZW GK55                    | 7        | 0.36%   |
| ASUS TUF GAMING X570-PLUS   | 7        | 0.36%   |
| Supermicro X7SPA-HF         | 6        | 0.31%   |
| Protectli FW4A              | 6        | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 225      | 11.71%  |
| Dell OptiPlex       | 206      | 10.72%  |
| Protectli FW4B      | 74       | 3.85%   |
| Protectli FW6       | 62       | 3.23%   |
| HP EliteDesk        | 48       | 2.5%    |
| Lenovo ThinkCentre  | 47       | 2.45%   |
| Intel Q3XXG4-P      | 42       | 2.19%   |
| HP ProDesk          | 30       | 1.56%   |
| ASUS ROG            | 29       | 1.51%   |
| ASUS PRIME          | 27       | 1.4%    |
| Techvision TVI7309X | 26       | 1.35%   |
| HP t620             | 26       | 1.35%   |
| HP Compaq           | 25       | 1.3%    |
| ASUS TUF            | 24       | 1.25%   |
| ASUS All            | 23       | 1.2%    |
| Supermicro X9SCL    | 21       | 1.09%   |
| PC Engines APU2     | 19       | 0.99%   |
| Dell Inspiron       | 18       | 0.94%   |
| Dell Precision      | 17       | 0.88%   |
| Protectli VP2410    | 15       | 0.78%   |
| PC Engines apu4     | 15       | 0.78%   |
| MW GMLK-2           | 15       | 0.78%   |
| ASRock X570         | 15       | 0.78%   |
| Protectli FW2B      | 13       | 0.68%   |
| Protectli FW4C      | 12       | 0.62%   |
| Protectli VP2420    | 11       | 0.57%   |
| Protectli FW1       | 11       | 0.57%   |
| Intel Nobilis       | 9        | 0.47%   |
| Acer Aspire         | 9        | 0.47%   |
| HP Slim             | 8        | 0.42%   |
| Protectli FW6E      | 7        | 0.36%   |
| Protectli FW6D      | 7        | 0.36%   |
| Lenovo IdeaCentre   | 7        | 0.36%   |
| HP Pavilion         | 7        | 0.36%   |
| Gigabyte X570       | 7        | 0.36%   |
| CWWK CW-AD4L-N      | 7        | 0.36%   |
| AZW GK55            | 7        | 0.36%   |
| Supermicro X7SPA-HF | 6        | 0.31%   |
| Protectli FW4A      | 6        | 0.31%   |
| MSI MS-7721         | 6        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 265      | 13.79%  |
| 2022    | 202      | 10.51%  |
| 2019    | 200      | 10.41%  |
| 2016    | 168      | 8.74%   |
| 2021    | 152      | 7.91%   |
| 2014    | 143      | 7.44%   |
| 2020    | 126      | 6.56%   |
| 2013    | 113      | 5.88%   |
| 2011    | 101      | 5.25%   |
| 2012    | 93       | 4.84%   |
| 2017    | 92       | 4.79%   |
| 2015    | 67       | 3.49%   |
| 2023    | 60       | 3.12%   |
| 2010    | 45       | 2.34%   |
| 2008    | 29       | 1.51%   |
| Unknown | 28       | 1.46%   |
| 2009    | 24       | 1.25%   |
| 2007    | 8        | 0.42%   |
| 2006    | 2        | 0.1%    |
| 2004    | 2        | 0.1%    |
| 2003    | 1        | 0.05%   |
| 2001    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1922     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1826     | 95.01%  |
| Yes  | 96       | 4.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 722      | 36.48%  |
| 16.01-24.0      | 529      | 26.73%  |
| 4.01-8.0        | 277      | 14%     |
| 32.01-64.0      | 266      | 13.44%  |
| 64.01-256.0     | 84       | 4.24%   |
| 24.01-32.0      | 38       | 1.92%   |
| 2.01-3.0        | 36       | 1.82%   |
| 3.01-4.0        | 9        | 0.45%   |
| 0.51-1.0        | 8        | 0.4%    |
| 1.01-2.0        | 5        | 0.25%   |
| 0.01-0.5        | 4        | 0.2%    |
| More than 256.0 | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 863      | 42.83%  |
| 0.51-1.0    | 656      | 32.56%  |
| 1.01-2.0    | 314      | 15.58%  |
| 2.01-3.0    | 50       | 2.48%   |
| 4.01-8.0    | 39       | 1.94%   |
| 3.01-4.0    | 27       | 1.34%   |
| 8.01-16.0   | 19       | 0.94%   |
| 16.01-24.0  | 11       | 0.55%   |
| Unknown     | 10       | 0.5%    |
| 32.01-64.0  | 8        | 0.4%    |
| 24.01-32.0  | 8        | 0.4%    |
| 64.01-256.0 | 5        | 0.25%   |
| 0           | 5        | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1380     | 68.93%  |
| 2      | 244      | 12.19%  |
| 0      | 154      | 7.69%   |
| 3      | 83       | 4.15%   |
| 4      | 42       | 2.1%    |
| 5      | 30       | 1.5%    |
| 6      | 20       | 1%      |
| 7      | 13       | 0.65%   |
| 8      | 7        | 0.35%   |
| 9      | 6        | 0.3%    |
| 10     | 5        | 0.25%   |
| 12     | 3        | 0.15%   |
| 11     | 3        | 0.15%   |
| 21     | 2        | 0.1%    |
| 17     | 2        | 0.1%    |
| 14     | 2        | 0.1%    |
| 40     | 1        | 0.05%   |
| 26     | 1        | 0.05%   |
| 22     | 1        | 0.05%   |
| 19     | 1        | 0.05%   |
| 18     | 1        | 0.05%   |
| 13     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1544     | 79.22%  |
| Yes       | 405      | 20.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1906     | 99.17%  |
| No        | 16       | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1536     | 78.97%  |
| Yes       | 409      | 21.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1667     | 86.02%  |
| Yes       | 271      | 13.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| USA     | 1922     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Denver         | 35       | 1.62%   |
| Seattle        | 33       | 1.53%   |
| New York       | 27       | 1.25%   |
| Chicago        | 24       | 1.11%   |
| Austin         | 22       | 1.02%   |
| Brooklyn       | 21       | 0.97%   |
| Portland       | 20       | 0.93%   |
| Los Angeles    | 18       | 0.84%   |
| Grand Rapids   | 17       | 0.79%   |
| Dallas         | 17       | 0.79%   |
| Columbus       | 17       | 0.79%   |
| Atlanta        | 16       | 0.74%   |
| Rochester      | 15       | 0.7%    |
| Houston        | 14       | 0.65%   |
| Springfield    | 13       | 0.6%    |
| Phoenix        | 13       | 0.6%    |
| Oakland        | 13       | 0.6%    |
| Mountain View  | 13       | 0.6%    |
| Ypsilanti      | 12       | 0.56%   |
| San Francisco  | 12       | 0.56%   |
| Pittsburgh     | 11       | 0.51%   |
| Raleigh        | 10       | 0.46%   |
| Minneapolis    | 10       | 0.46%   |
| Fort Worth     | 10       | 0.46%   |
| San Antonio    | 9        | 0.42%   |
| Philadelphia   | 9        | 0.42%   |
| Orlando        | 9        | 0.42%   |
| Oklahoma City  | 9        | 0.42%   |
| Milwaukee      | 9        | 0.42%   |
| Miami          | 9        | 0.42%   |
| Jacksonville   | 9        | 0.42%   |
| Charlotte      | 9        | 0.42%   |
| San Jose       | 8        | 0.37%   |
| Salem          | 8        | 0.37%   |
| Indianapolis   | 8        | 0.37%   |
| Boston         | 8        | 0.37%   |
| Tucson         | 7        | 0.32%   |
| Tampa          | 7        | 0.32%   |
| Silver Spring  | 7        | 0.32%   |
| Salt Lake City | 7        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 383      | 841    | 16.37%  |
| WDC                 | 286      | 983    | 12.23%  |
| Seagate             | 225      | 594    | 9.62%   |
| Kingston            | 186      | 263    | 7.95%   |
| Crucial             | 115      | 174    | 4.92%   |
| SanDisk             | 90       | 120    | 3.85%   |
| Intel               | 87       | 195    | 3.72%   |
| Transcend           | 69       | 132    | 2.95%   |
| Toshiba             | 68       | 115    | 2.91%   |
| Hoodisk             | 64       | 90     | 2.74%   |
| Protectli           | 63       | 101    | 2.69%   |
| China               | 53       | 68     | 2.27%   |
| Phison              | 47       | 76     | 2.01%   |
| A-DATA Technology   | 47       | 75     | 2.01%   |
| PNY                 | 45       | 66     | 1.92%   |
| SK hynix            | 43       | 61     | 1.84%   |
| SPCC                | 40       | 80     | 1.71%   |
| Hitachi             | 40       | 96     | 1.71%   |
| Dogfish             | 26       | 47     | 1.11%   |
| BIWIN               | 24       | 39     | 1.03%   |
| HGST                | 23       | 70     | 0.98%   |
| Team                | 19       | 37     | 0.81%   |
| Hewlett-Packard     | 18       | 46     | 0.77%   |
| Micron Technology   | 16       | 21     | 0.68%   |
| OCZ                 | 14       | 22     | 0.6%    |
| FORESEE             | 14       | 23     | 0.6%    |
| Silicon Motion      | 12       | 19     | 0.51%   |
| Fanxiang            | 12       | 15     | 0.51%   |
| Apacer              | 11       | 14     | 0.47%   |
| NVMe                | 9        | 15     | 0.38%   |
| Mushkin             | 9        | 15     | 0.38%   |
| Corsair             | 9        | 36     | 0.38%   |
| KIOXIA              | 8        | 14     | 0.34%   |
| KingSpec            | 8        | 12     | 0.34%   |
| Patriot             | 7        | 8      | 0.3%    |
| Lexar               | 7        | 8      | 0.3%    |
| Innodisk            | 7        | 9      | 0.3%    |
| CWDISK              | 7        | 8      | 0.3%    |
| Zheino              | 6        | 11     | 0.26%   |
| LITEON              | 6        | 9      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Hoodisk SSD 32GB                | 28       | 1.08%   |
| Kingston SUV500MS240G 240GB     | 23       | 0.89%   |
| Seagate ST500DM002-1BD142 500GB | 22       | 0.85%   |
| Samsung SSD 850 EVO 250GB       | 22       | 0.85%   |
| Samsung SSD 860 EVO 500GB       | 20       | 0.77%   |
| Kingston SUV500MS120G 120GB     | 20       | 0.77%   |
| Kingston SA400S37240G 240GB     | 20       | 0.77%   |
| Protectli 120GB mSATA           | 19       | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB  | 18       | 0.69%   |
| Samsung SSD 860 EVO 250GB       | 18       | 0.69%   |
| Hoodisk SSD 128GB               | 18       | 0.69%   |
| BIWIN SSD 128GB                 | 18       | 0.69%   |
| Kingston SA400S37120G 120GB     | 17       | 0.66%   |
| Samsung SSD 860 EVO 1TB         | 16       | 0.62%   |
| PNY CS900 120GB SSD             | 16       | 0.62%   |
| Samsung SSD 850 EVO 500GB       | 15       | 0.58%   |
| WDC WD800JD-75MSA3 80GB         | 14       | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB    | 14       | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB        | 13       | 0.5%    |
| Samsung SSD 870 EVO 500GB       | 13       | 0.5%    |
| Kingston SV300S37A120G 120GB    | 13       | 0.5%    |
| Crucial CT250MX500SSD1 250GB    | 13       | 0.5%    |
| Toshiba DT01ACA100 1TB          | 11       | 0.42%   |
| SPCC Solid State Disk 128GB     | 11       | 0.42%   |
| Protectli 64GB mSATA            | 11       | 0.42%   |
| Protectli 240GB mSATA           | 11       | 0.42%   |
| Phison Sabrent 1TB              | 11       | 0.42%   |
| Hoodisk SSD 64GB                | 11       | 0.42%   |
| Transcend TS128GMSA230S 128GB   | 10       | 0.39%   |
| Kingston SKC600MS256G 256GB     | 10       | 0.39%   |
| Crucial CT240BX500SSD1 240GB    | 10       | 0.39%   |
| China SATA SSD 120GB            | 10       | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB  | 9        | 0.35%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 9        | 0.35%   |
| Samsung SSD 980 500GB           | 9        | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB    | 8        | 0.31%   |
| Transcend TS64GMSA230S 64GB     | 8        | 0.31%   |
| Seagate ST4000DM000-1F2168 4TB  | 8        | 0.31%   |
| Seagate ST250DM000-1BD141 250GB | 8        | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB  | 8        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 226      | 852    | 37.54%  |
| Seagate                            | 218      | 578    | 36.21%  |
| Toshiba                            | 52       | 93     | 8.64%   |
| Hitachi                            | 39       | 95     | 6.48%   |
| HGST                               | 23       | 70     | 3.82%   |
| Samsung Electronics                | 8        | 9      | 1.33%   |
| Maxtor                             | 4        | 7      | 0.66%   |
| Hewlett-Packard                    | 4        | 14     | 0.66%   |
| Apple                              | 4        | 5      | 0.66%   |
| NVMe                               | 3        | 7      | 0.5%    |
| Lexar                              | 3        | 3      | 0.5%    |
| HPE                                | 2        | 7      | 0.33%   |
| Fujitsu                            | 2        | 2      | 0.33%   |
| Adaptec                            | 2        | 2      | 0.33%   |
| WD MediaMax                        | 1        | 3      | 0.17%   |
| QUANTUM                            | 1        | 2      | 0.17%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.17%   |
| Memorex                            | 1        | 1      | 0.17%   |
| MaxDigital                         | 1        | 1      | 0.17%   |
| MARVELL                            | 1        | 1      | 0.17%   |
| LSI                                | 1        | 4      | 0.17%   |
| IBM-ESXS                           | 1        | 1      | 0.17%   |
| IBM-207x                           | 1        | 1      | 0.17%   |
| HPT                                | 1        | 8      | 0.17%   |
| ExcelStor Technology               | 1        | 4      | 0.17%   |
| ASMT                               | 1        | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 257      | 582    | 18.92%  |
| Kingston            | 167      | 242    | 12.3%   |
| Crucial             | 89       | 140    | 6.55%   |
| SanDisk             | 88       | 114    | 6.48%   |
| Transcend           | 68       | 131    | 5.01%   |
| Protectli           | 63       | 101    | 4.64%   |
| Hoodisk             | 63       | 89     | 4.64%   |
| Intel               | 61       | 154    | 4.49%   |
| China               | 53       | 68     | 3.9%    |
| PNY                 | 41       | 62     | 3.02%   |
| A-DATA Technology   | 39       | 60     | 2.87%   |
| WDC                 | 32       | 64     | 2.36%   |
| SPCC                | 28       | 65     | 2.06%   |
| Dogfish             | 26       | 47     | 1.91%   |
| BIWIN               | 24       | 39     | 1.77%   |
| SK hynix            | 22       | 27     | 1.62%   |
| Phison              | 19       | 26     | 1.4%    |
| OCZ                 | 14       | 22     | 1.03%   |
| FORESEE             | 13       | 22     | 0.96%   |
| Micron Technology   | 12       | 15     | 0.88%   |
| Toshiba             | 11       | 16     | 0.81%   |
| Apacer              | 11       | 14     | 0.81%   |
| Team                | 8        | 24     | 0.59%   |
| KingSpec            | 8        | 12     | 0.59%   |
| Mushkin             | 7        | 12     | 0.52%   |
| Innodisk            | 7        | 9      | 0.52%   |
| Hewlett-Packard     | 7        | 12     | 0.52%   |
| Zheino              | 6        | 11     | 0.44%   |
| Seagate             | 6        | 11     | 0.44%   |
| Patriot             | 6        | 7      | 0.44%   |
| CWDISK              | 6        | 7      | 0.44%   |
| Corsair             | 6        | 11     | 0.44%   |
| ShiJi               | 5        | 6      | 0.37%   |
| NVMe                | 5        | 7      | 0.37%   |
| LITEON              | 5        | 8      | 0.37%   |
| Intenso             | 5        | 11     | 0.37%   |
| Vaseky              | 4        | 4      | 0.29%   |
| Plextor             | 4        | 6      | 0.29%   |
| MyDigitalSSD        | 4        | 6      | 0.29%   |
| LITEONIT            | 4        | 7      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1220     | 2357   | 58.4%   |
| HDD  | 483      | 1772   | 23.12%  |
| NVMe | 386      | 693    | 18.48%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1532     | 4129   | 79.87%  |
| NVMe | 386      | 693    | 20.13%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1304     | 2437   | 72.77%  |
| 0.51-1.0   | 246      | 549    | 13.73%  |
| 1.01-2.0   | 103      | 308    | 5.75%   |
| 4.01-10.0  | 48       | 413    | 2.68%   |
| 3.01-4.0   | 46       | 195    | 2.57%   |
| 2.01-3.0   | 31       | 120    | 1.73%   |
| 10.01-20.0 | 14       | 107    | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 814      | 40.64%  |
| 251-500        | 368      | 18.37%  |
| 51-100         | 200      | 9.99%   |
| 21-50          | 199      | 9.94%   |
| 501-1000       | 183      | 9.14%   |
| 1-20           | 167      | 8.34%   |
| 1001-2000      | 42       | 2.1%    |
| More than 3000 | 19       | 0.95%   |
| Unknown        | 6        | 0.3%    |
| 2001-3000      | 5        | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1804     | 90.65%  |
| 21-50          | 101      | 5.08%   |
| 51-100         | 37       | 1.86%   |
| 101-250        | 18       | 0.9%    |
| 251-500        | 10       | 0.5%    |
| Unknown        | 6        | 0.3%    |
| More than 3000 | 5        | 0.25%   |
| 501-1000       | 4        | 0.2%    |
| 2001-3000      | 2        | 0.1%    |
| 1001-2000      | 2        | 0.1%    |
| 0              | 1        | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 8        | 12     | 2.97%   |
| Seagate ST3500418AS 500GB             | 4        | 11     | 1.49%   |
| Kingston SV300S37A120G 120GB          | 4        | 4      | 1.49%   |
| Crucial CT275MX300SSD1 275GB          | 4        | 7      | 1.49%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3        | 3      | 1.12%   |
| Seagate ST2000DM008-2FR102 2TB        | 3        | 3      | 1.12%   |
| Seagate ST1000DM003-9YN162 1TB        | 3        | 7      | 1.12%   |
| Kingston SV300S37A60G 64GB            | 3        | 3      | 1.12%   |
| WDC WD5000AAKX-001CA0 500GB           | 2        | 4      | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 9      | 0.74%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.74%   |
| WDC WD2001FASS-00W2B0 2TB             | 2        | 3      | 0.74%   |
| WDC WD1600AAJS-75M0A0 160GB           | 2        | 2      | 0.74%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.74%   |
| SK hynix SC210 mSATA 256GB            | 2        | 3      | 0.74%   |
| Seagate ST500LT012-1DG142 500GB       | 2        | 3      | 0.74%   |
| Seagate ST3500413AS 500GB             | 2        | 10     | 0.74%   |
| Seagate ST31000528AS 1TB              | 2        | 2      | 0.74%   |
| Seagate ST2000DL001-9VT156 2TB        | 2        | 2      | 0.74%   |
| Samsung Electronics SSD 950 PRO 256GB | 2        | 2      | 0.74%   |
| Samsung Electronics SSD 850 EVO 500GB | 2        | 2      | 0.74%   |
| MyDigitalSSD SB2 256GB                | 2        | 4      | 0.74%   |
| Kingston SUV400S37120G 120GB          | 2        | 3      | 0.74%   |
| Kingston SNS4151S316G 16GB            | 2        | 3      | 0.74%   |
| Kingston SMS200S360G 64GB             | 2        | 2      | 0.74%   |
| Kingston SMS200S3120G 120GB           | 2        | 2      | 0.74%   |
| Intel SSDSA2M120G2GC 120GB            | 2        | 2      | 0.74%   |
| Hitachi HUA722020ALA330 2TB           | 2        | 4      | 0.74%   |
| Hitachi HTS725032A9A364 320GB         | 2        | 2      | 0.74%   |
| HGST HTS725050A7E630 500GB            | 2        | 2      | 0.74%   |
| Crucial CT512M550SSD1 512GB           | 2        | 5      | 0.74%   |
| Crucial CT240M500SSD1 240GB           | 2        | 3      | 0.74%   |
| Crucial CT1050MX300SSD4 1TB           | 2        | 2      | 0.74%   |
| Apacer 32GB SATA Flash Drive          | 2        | 2      | 0.74%   |
| Apacer 16GB SATA Flash Drive          | 2        | 3      | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB          | 1        | 1      | 0.37%   |
| WDC WD80EDAZ-11TA3A0 8TB              | 1        | 4      | 0.37%   |
| WDC WD6400AAKS-00A7B0 640GB           | 1        | 1      | 0.37%   |
| WDC WD60EFAX-68SHWN0 6TB              | 1        | 2      | 0.37%   |
| WDC WD6003FZBX-00K5WB0 6TB            | 1        | 1      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 57       | 101    | 22.09%  |
| WDC                  | 48       | 81     | 18.6%   |
| Kingston             | 23       | 27     | 8.91%   |
| Samsung Electronics  | 17       | 24     | 6.59%   |
| Crucial              | 15       | 22     | 5.81%   |
| Intel                | 14       | 16     | 5.43%   |
| Hitachi              | 13       | 18     | 5.04%   |
| Toshiba              | 11       | 11     | 4.26%   |
| SanDisk              | 8        | 10     | 3.1%    |
| SK hynix             | 7        | 10     | 2.71%   |
| HGST                 | 6        | 6      | 2.33%   |
| Apacer               | 4        | 5      | 1.55%   |
| OCZ                  | 3        | 3      | 1.16%   |
| Maxtor               | 3        | 6      | 1.16%   |
| LITEON               | 3        | 4      | 1.16%   |
| SPCC                 | 2        | 4      | 0.78%   |
| PNY                  | 2        | 2      | 0.78%   |
| MyDigitalSSD         | 2        | 4      | 0.78%   |
| A-DATA Technology    | 2        | 2      | 0.78%   |
| WD MediaMax          | 1        | 3      | 0.39%   |
| VisionTek            | 1        | 1      | 0.39%   |
| Transcend            | 1        | 4      | 0.39%   |
| Phison               | 1        | 1      | 0.39%   |
| Patriot              | 1        | 1      | 0.39%   |
| Micron Technology    | 1        | 1      | 0.39%   |
| LITEONIT             | 1        | 3      | 0.39%   |
| KingDian             | 1        | 1      | 0.39%   |
| KeepData             | 1        | 1      | 0.39%   |
| INDMEM               | 1        | 1      | 0.39%   |
| HPE                  | 1        | 3      | 0.39%   |
| Hewlett-Packard      | 1        | 4      | 0.39%   |
| Fujitsu              | 1        | 1      | 0.39%   |
| ExcelStor Technology | 1        | 2      | 0.39%   |
| EDGE                 | 1        | 1      | 0.39%   |
| Dogfish              | 1        | 5      | 0.39%   |
| Corsair              | 1        | 1      | 0.39%   |
| BIWIN                | 1        | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 57       | 101    | 39.86%  |
| WDC                  | 47       | 80     | 32.87%  |
| Hitachi              | 13       | 18     | 9.09%   |
| Toshiba              | 9        | 9      | 6.29%   |
| HGST                 | 6        | 6      | 4.2%    |
| Samsung Electronics  | 3        | 3      | 2.1%    |
| Maxtor               | 3        | 6      | 2.1%    |
| WD MediaMax          | 1        | 3      | 0.7%    |
| HPE                  | 1        | 3      | 0.7%    |
| Hewlett-Packard      | 1        | 4      | 0.7%    |
| Fujitsu              | 1        | 1      | 0.7%    |
| ExcelStor Technology | 1        | 2      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 137      | 236    | 54.58%  |
| SSD  | 112      | 153    | 44.62%  |
| NVMe | 2        | 2      | 0.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD3200L 320GB                          | 1        | 1      | 12.5%   |
| SK hynix SC308 SATA 256GB                  | 1        | 1      | 12.5%   |
| Seagate ST3500418AS 500GB                  | 1        | 2      | 12.5%   |
| Samsung Electronics SSD 970 EVO Plus 500GB | 1        | 1      | 12.5%   |
| Samsung Electronics PM981 NVMe 256GB       | 1        | 1      | 12.5%   |
| Samsung Electronics HD204UI 2TB            | 1        | 2      | 12.5%   |
| Kingston SA2000M8500G 500GB                | 1        | 2      | 12.5%   |
| Intel SSDSC2KB019T8 1.9TB                  | 1        | 2      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 37.5%   |
| WDC                 | 1        | 1      | 12.5%   |
| SK hynix            | 1        | 1      | 12.5%   |
| Seagate             | 1        | 2      | 12.5%   |
| Kingston            | 1        | 2      | 12.5%   |
| Intel               | 1        | 2      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1629     | 4327   | 84.36%  |
| Malfunc  | 247      | 391    | 12.79%  |
| Detected | 47       | 92     | 2.43%   |
| Failed   | 8        | 12     | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 1518     | 60.6%   |
| AMD                                     | 344      | 13.73%  |
| Samsung Electronics                     | 150      | 5.99%   |
| SanDisk                                 | 69       | 2.75%   |
| ASMedia Technology                      | 55       | 2.2%    |
| Phison Electronics                      | 49       | 1.96%   |
| Broadcom / LSI                          | 43       | 1.72%   |
| Silicon Motion                          | 41       | 1.64%   |
| Marvell Technology Group                | 32       | 1.28%   |
| Micron/Crucial Technology               | 26       | 1.04%   |
| SK hynix                                | 22       | 0.88%   |
| MAXIO Technology (Hangzhou)             | 19       | 0.76%   |
| Kingston Technology Company             | 19       | 0.76%   |
| JMicron Technology                      | 15       | 0.6%    |
| Chelsio Communications                  | 14       | 0.56%   |
| Realtek Semiconductor                   | 10       | 0.4%    |
| Nvidia                                  | 9        | 0.36%   |
| KIOXIA                                  | 9        | 0.36%   |
| Adaptec                                 | 7        | 0.28%   |
| ADATA Technology                        | 6        | 0.24%   |
| Seagate Technology                      | 5        | 0.2%    |
| Micron Technology                       | 5        | 0.2%    |
| Toshiba                                 | 4        | 0.16%   |
| Shenzhen Longsys Electronics            | 4        | 0.16%   |
| VIA Technologies                        | 3        | 0.12%   |
| Silicon Image                           | 3        | 0.12%   |
| Hosin Global Electronics                | 3        | 0.12%   |
| Solid State Storage Technology          | 2        | 0.08%   |
| Silicon Integrated Systems [SiS]        | 2        | 0.08%   |
| Shenzhen Unionmemory Information System | 2        | 0.08%   |
| Lite-On Technology                      | 2        | 0.08%   |
| HighPoint Technologies                  | 2        | 0.08%   |
| Hewlett-Packard                         | 2        | 0.08%   |
| Union Memory (Shenzhen)                 | 1        | 0.04%   |
| Transcend                               | 1        | 0.04%   |
| Solidigm                                | 1        | 0.04%   |
| O2 Micro                                | 1        | 0.04%   |
| Innodisk                                | 1        | 0.04%   |
| Broadcom                                | 1        | 0.04%   |
| Biwin Storage Technology                | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 225      | 7.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 157      | 5.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 119      | 4.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 116      | 4.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 101      | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 97       | 3.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 95       | 3.34%   |
| Intel SATA Controller [RAID mode]                                                       | 81       | 2.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 77       | 2.71%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 72       | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 65       | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 63       | 2.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 60       | 2.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 48       | 1.69%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 48       | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 47       | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 40       | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 38       | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                                  | 38       | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 35       | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 26       | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 26       | 0.92%   |
| Phison E12 NVMe Controller                                                              | 25       | 0.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 24       | 0.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 23       | 0.81%   |
| Unknown                                                                                 | 22       | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 0.74%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 20       | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 19       | 0.67%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 19       | 0.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 19       | 0.67%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 18       | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18       | 0.63%   |
| Intel Elkhart Lake SATA AHCI                                                            | 18       | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18       | 0.63%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 18       | 0.63%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 17       | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 17       | 0.6%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 17       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1664     | 67.07%  |
| NVMe | 440      | 17.73%  |
| IDE  | 188      | 7.58%   |
| RAID | 122      | 4.92%   |
| SAS  | 42       | 1.69%   |
| SCSI | 25       | 1.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 1550     | 80.52%  |
| AMD      | 361      | 18.75%  |
| ARM      | 6        | 0.31%   |
| Unknown  | 3        | 0.16%   |
| IBM      | 2        | 0.1%    |
| NXP      | 1        | 0.05%   |
| Motorola | 1        | 0.05%   |
| i        | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 82       | 4.19%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 76       | 3.88%   |
| Intel Celeron N5105 @ 2.00GHz            | 65       | 3.32%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 42       | 2.15%   |
| AMD GX-412TC SOC                         | 35       | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 32       | 1.63%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 32       | 1.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 27       | 1.38%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 27       | 1.38%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 24       | 1.23%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 24       | 1.23%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 23       | 1.17%   |
| Intel N100                               | 21       | 1.07%   |
| Intel Atom CPU D525 @ 1.80GHz            | 20       | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 19       | 0.97%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 18       | 0.92%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 17       | 0.87%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 16       | 0.82%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 16       | 0.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 15       | 0.77%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 15       | 0.77%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 14       | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 14       | 0.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 14       | 0.72%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 14       | 0.72%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 13       | 0.66%   |
| Intel Pentium CPU J3710 @ 1.60GHz        | 13       | 0.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 13       | 0.66%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 12       | 0.61%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 12       | 0.61%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 12       | 0.61%   |
| AMD Ryzen 7 5700G with Radeon Graphics   | 12       | 0.61%   |
| AMD Ryzen 7 2700 Eight-Core Processor    | 12       | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 11       | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 11       | 0.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 11       | 0.56%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 11       | 0.56%   |
| Intel Celeron J6412 @ 2.00GHz            | 11       | 0.56%   |
| AMD Ryzen 7 5800X 8-Core Processor       | 11       | 0.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 11       | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 419      | 21.54%  |
| Intel Celeron           | 376      | 19.33%  |
| Intel Core i7           | 203      | 10.44%  |
| Intel Xeon              | 156      | 8.02%   |
| Intel Core i3           | 140      | 7.2%    |
| Other                   | 83       | 4.27%   |
| Intel Atom              | 80       | 4.11%   |
| AMD Ryzen 7             | 72       | 3.7%    |
| AMD GX                  | 70       | 3.6%    |
| AMD Ryzen 5             | 56       | 2.88%   |
| Intel Pentium           | 40       | 2.06%   |
| AMD Ryzen 9             | 26       | 1.34%   |
| AMD FX                  | 23       | 1.18%   |
| Intel Core 2 Duo        | 18       | 0.93%   |
| Intel Pentium Silver    | 15       | 0.77%   |
| AMD Ryzen 3             | 14       | 0.72%   |
| AMD A10                 | 13       | 0.67%   |
| Intel Core 2 Quad       | 12       | 0.62%   |
| AMD Phenom II X4        | 10       | 0.51%   |
| AMD Athlon              | 9        | 0.46%   |
| Intel Core i9           | 8        | 0.41%   |
| AMD Ryzen 5 PRO         | 7        | 0.36%   |
| AMD A8                  | 7        | 0.36%   |
| Intel Pentium Dual-Core | 6        | 0.31%   |
| ARM Cortex              | 6        | 0.31%   |
| AMD G                   | 6        | 0.31%   |
| AMD Ryzen Threadripper  | 5        | 0.26%   |
| AMD Phenom II X6        | 5        | 0.26%   |
| AMD Opteron             | 5        | 0.26%   |
| AMD A6                  | 5        | 0.26%   |
| AMD A4                  | 5        | 0.26%   |
| Intel Pentium 4         | 4        | 0.21%   |
| Intel Core 2            | 4        | 0.21%   |
| Intel Pentium Gold      | 3        | 0.15%   |
| Intel 686-class         | 3        | 0.15%   |
| AMD E2                  | 3        | 0.15%   |
| AMD Athlon 64 X2        | 3        | 0.15%   |
| Intel Pentium D         | 2        | 0.1%    |
| Intel Genuine           | 2        | 0.1%    |
| AMD Sempron             | 2        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1114     | 57.19%  |
| 2       | 396      | 20.33%  |
| 8       | 103      | 5.29%   |
| 6       | 95       | 4.88%   |
| 16      | 74       | 3.8%    |
| 12      | 64       | 3.29%   |
| Unknown | 49       | 2.52%   |
| 24      | 15       | 0.77%   |
| 32      | 12       | 0.62%   |
| 1       | 10       | 0.51%   |
| 10      | 6        | 0.31%   |
| 14      | 3        | 0.15%   |
| 48      | 2        | 0.1%    |
| 3       | 2        | 0.1%    |
| 64      | 1        | 0.05%   |
| 28      | 1        | 0.05%   |
| 20      | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1878     | 97.61%  |
| 2       | 25       | 1.3%    |
| Unknown | 19       | 0.99%   |
| 8       | 1        | 0.05%   |
| 4       | 1        | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1249     | 64.51%  |
| 2       | 635      | 32.8%   |
| Unknown | 52       | 2.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 249      | 12.78%  |
| Haswell       | 226      | 11.6%   |
| Unknown       | 190      | 9.75%   |
| Silvermont    | 176      | 9.03%   |
| Skylake       | 135      | 6.93%   |
| IvyBridge     | 133      | 6.83%   |
| SandyBridge   | 101      | 5.18%   |
| Goldmont plus | 101      | 5.18%   |
| Zen 3         | 54       | 2.77%   |
| Broadwell     | 52       | 2.67%   |
| Zen 2         | 51       | 2.62%   |
| Zen+          | 47       | 2.41%   |
| Puma          | 40       | 2.05%   |
| Jaguar        | 40       | 2.05%   |
| CometLake     | 40       | 2.05%   |
| Bonnell       | 39       | 2%      |
| Piledriver    | 35       | 1.8%    |
| Penryn        | 32       | 1.64%   |
| Zen           | 29       | 1.49%   |
| Nehalem       | 29       | 1.49%   |
| Goldmont      | 27       | 1.39%   |
| K10           | 22       | 1.13%   |
| Core          | 21       | 1.08%   |
| Westmere      | 17       | 0.87%   |
| TigerLake     | 12       | 0.62%   |
| Bobcat        | 11       | 0.56%   |
| Steamroller   | 10       | 0.51%   |
| NetBurst      | 8        | 0.41%   |
| Excavator     | 8        | 0.41%   |
| K8 Hammer     | 7        | 0.36%   |
| K10 Llano     | 2        | 0.1%    |
| Bulldozer     | 2        | 0.1%    |
| P6            | 1        | 0.05%   |
| Geode         | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1257     | 66.79%  |
| AMD                                          | 298      | 15.83%  |
| Nvidia                                       | 199      | 10.57%  |
| ASPEED Technology                            | 73       | 3.88%   |
| Matrox Electronics Systems                   | 49       | 2.6%    |
| XGI Technology (eXtreme Graphics Innovation) | 4        | 0.21%   |
| Silicon Integrated Systems [SiS]             | 2        | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 130      | 6.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 116      | 6.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 101      | 5.29%   |
| Intel HD Graphics 530                                                                    | 96       | 5.03%   |
| Intel JasperLake [UHD Graphics]                                                          | 85       | 4.45%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 73       | 3.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 68       | 3.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 64       | 3.35%   |
| Intel HD Graphics 620                                                                    | 61       | 3.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 53       | 2.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 47       | 2.46%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 44       | 2.3%    |
| Intel HD Graphics 630                                                                    | 38       | 1.99%   |
| Intel UHD Graphics 620                                                                   | 33       | 1.73%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 30       | 1.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 28       | 1.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 28       | 1.47%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 26       | 1.36%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 25       | 1.31%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 24       | 1.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24       | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 24       | 1.26%   |
| Intel HD Graphics 610                                                                    | 23       | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23       | 1.2%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 20       | 1.05%   |
| Intel HD Graphics 5500                                                                   | 19       | 0.99%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 18       | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 17       | 0.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16       | 0.84%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13       | 0.68%   |
| Intel HD Graphics 6000                                                                   | 13       | 0.68%   |
| Intel HD Graphics 500                                                                    | 12       | 0.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10       | 0.52%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 9        | 0.47%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 0.47%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 8        | 0.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8        | 0.42%   |
| AMD RS780L [Radeon 3000]                                                                 | 8        | 0.42%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8        | 0.42%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 8        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 1205     | 61.99%  |
| 1 x AMD         | 279      | 14.35%  |
| 1 x Nvidia      | 177      | 9.1%    |
| Other           | 89       | 4.58%   |
| 1 x ASPEED      | 70       | 3.6%    |
| 1 x Matrox      | 47       | 2.42%   |
| 2 x Intel       | 30       | 1.54%   |
| Intel + Nvidia  | 15       | 0.77%   |
| 2 x AMD         | 8        | 0.41%   |
| Intel + AMD     | 5        | 0.26%   |
| 1 x XGI         | 4        | 0.21%   |
| AMD + Nvidia    | 4        | 0.21%   |
| 2 x Nvidia      | 3        | 0.15%   |
| 1 x SiS         | 2        | 0.1%    |
| Intel + ASPEED  | 2        | 0.1%    |
| Nvidia + ASPEED | 1        | 0.05%   |
| Intel + 2 x AMD | 1        | 0.05%   |
| AMD + Matrox    | 1        | 0.05%   |
| AMD + ASPEED    | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1724     | 89.05%  |
| Proprietary | 111      | 5.73%   |
| Unknown     | 101      | 5.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1762     | 90.82%  |
| 1.01-2.0   | 48       | 2.47%   |
| 3.01-4.0   | 33       | 1.7%    |
| 7.01-8.0   | 28       | 1.44%   |
| 0.51-1.0   | 25       | 1.29%   |
| 0.01-0.5   | 17       | 0.88%   |
| 5.01-6.0   | 14       | 0.72%   |
| 8.01-16.0  | 10       | 0.52%   |
| 2.01-3.0   | 2        | 0.1%    |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 55       | 19.71%  |
| Goldstar             | 33       | 11.83%  |
| Acer                 | 33       | 11.83%  |
| Samsung Electronics  | 32       | 11.47%  |
| Hewlett-Packard      | 19       | 6.81%   |
| Ancor Communications | 16       | 5.73%   |
| AOC                  | 10       | 3.58%   |
| ASUSTek Computer     | 9        | 3.23%   |
| Vizio                | 8        | 2.87%   |
| Lenovo               | 8        | 2.87%   |
| ViewSonic            | 6        | 2.15%   |
| LG Electronics       | 6        | 2.15%   |
| BenQ                 | 5        | 1.79%   |
| Sceptre Tech         | 4        | 1.43%   |
| Apple                | 4        | 1.43%   |
| Sony                 | 3        | 1.08%   |
| Philips              | 3        | 1.08%   |
| MSI                  | 3        | 1.08%   |
| Insignia             | 3        | 1.08%   |
| Westinghouse         | 2        | 0.72%   |
| Wacom                | 1        | 0.36%   |
| unknown              | 1        | 0.36%   |
| SHI                  | 1        | 0.36%   |
| SGT                  | 1        | 0.36%   |
| RS                   | 1        | 0.36%   |
| Pioneer Electronic   | 1        | 0.36%   |
| NEC Computers        | 1        | 0.36%   |
| Lenovo Group Limited | 1        | 0.36%   |
| Impression           | 1        | 0.36%   |
| Hitachi              | 1        | 0.36%   |
| HannStar             | 1        | 0.36%   |
| Gateway              | 1        | 0.36%   |
| Envision             | 1        | 0.36%   |
| Chimei Innolux       | 1        | 0.36%   |
| AU Optronics         | 1        | 0.36%   |
| ASRock               | 1        | 0.36%   |
| Unknown              | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch               | 5        | 1.68%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch | 3        | 1.01%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                     | 3        | 1.01%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                   | 3        | 1.01%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                   | 3        | 1.01%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch        | 3        | 1.01%   |
| Sony TV SNY9C01 1360x768                                            | 2        | 0.67%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch   | 2        | 0.67%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch   | 2        | 0.67%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch    | 2        | 0.67%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                | 2        | 0.67%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch          | 2        | 0.67%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch           | 2        | 0.67%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                   | 2        | 0.67%   |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                  | 2        | 0.67%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch               | 2        | 0.67%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch        | 2        | 0.67%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                  | 2        | 0.67%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch    | 2        | 0.67%   |
| Acer X183H ACR006A 1366x768 410x230mm 18.5-inch                     | 2        | 0.67%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                   | 2        | 0.67%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                   | 2        | 0.67%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch          | 1        | 0.34%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch        | 1        | 0.34%   |
| Wacom One 13 WAC1070 1920x1080 290x170mm 13.2-inch                  | 1        | 0.34%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                | 1        | 0.34%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch              | 1        | 0.34%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                   | 1        | 0.34%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                 | 1        | 0.34%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                 | 1        | 0.34%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                  | 1        | 0.34%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                 | 1        | 0.34%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                 | 1        | 0.34%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch               | 1        | 0.34%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 480x270mm 21.7-inch       | 1        | 0.34%   |
| ViewSonic N2635w-3M VSC1B24 1360x768 580x330mm 26.3-inch            | 1        | 0.34%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch         | 1        | 0.34%   |
| ViewSonic LCD Monitor VSCDC2E 1920x1080 480x270mm 21.7-inch         | 1        | 0.34%   |
| ViewSonic LCD Monitor VA1938 Series                                 | 1        | 0.34%   |
| unknown LCD Monitor Dell SE2717H/HX 1920x1080                       | 1        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 105      | 38.32%  |
| 2560x1440 (QHD)    | 25       | 9.12%   |
| 3840x2160 (4K)     | 24       | 8.76%   |
| 1920x1200 (WUXGA)  | 17       | 6.2%    |
| 1280x1024 (SXGA)   | 15       | 5.47%   |
| 1680x1050 (WSXGA+) | 13       | 4.74%   |
| 1600x900 (HD+)     | 10       | 3.65%   |
| 3440x1440          | 9        | 3.28%   |
| 2560x1080          | 9        | 3.28%   |
| 1366x768 (WXGA)    | 9        | 3.28%   |
| 1440x900 (WXGA+)   | 8        | 2.92%   |
| 1360x768           | 6        | 2.19%   |
| 1024x768 (XGA)     | 5        | 1.82%   |
| Unknown            | 5        | 1.82%   |
| 2560x1600          | 3        | 1.09%   |
| 3840x1080          | 2        | 0.73%   |
| 1600x1200          | 2        | 0.73%   |
| 5760x1080          | 1        | 0.36%   |
| 4640x1080          | 1        | 0.36%   |
| 3840x1600          | 1        | 0.36%   |
| 3520x1080          | 1        | 0.36%   |
| 2806x900           | 1        | 0.36%   |
| 1920x540           | 1        | 0.36%   |
| 1024x600           | 1        | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 50       | 17.86%  |
| 27      | 38       | 13.57%  |
| Unknown | 31       | 11.07%  |
| 31      | 25       | 8.93%   |
| 21      | 23       | 8.21%   |
| 19      | 23       | 8.21%   |
| 23      | 20       | 7.14%   |
| 34      | 13       | 4.64%   |
| 22      | 9        | 3.21%   |
| 17      | 8        | 2.86%   |
| 18      | 6        | 2.14%   |
| 29      | 4        | 1.43%   |
| 20      | 4        | 1.43%   |
| 14      | 4        | 1.43%   |
| 15      | 3        | 1.07%   |
| 13      | 3        | 1.07%   |
| 64      | 2        | 0.71%   |
| 42      | 2        | 0.71%   |
| 52      | 1        | 0.36%   |
| 49      | 1        | 0.36%   |
| 41      | 1        | 0.36%   |
| 39      | 1        | 0.36%   |
| 37      | 1        | 0.36%   |
| 35      | 1        | 0.36%   |
| 32      | 1        | 0.36%   |
| 28      | 1        | 0.36%   |
| 26      | 1        | 0.36%   |
| 25      | 1        | 0.36%   |
| 16      | 1        | 0.36%   |
| 9       | 1        | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 101      | 37.27%  |
| 401-500     | 57       | 21.03%  |
| 601-700     | 33       | 12.18%  |
| Unknown     | 31       | 11.44%  |
| 701-800     | 14       | 5.17%   |
| 301-350     | 12       | 4.43%   |
| 201-300     | 7        | 2.58%   |
| 351-400     | 5        | 1.85%   |
| 1001-1500   | 4        | 1.48%   |
| 801-900     | 3        | 1.11%   |
| 901-1000    | 3        | 1.11%   |
| 101-200     | 1        | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 159      | 61.15%  |
| 16/10   | 33       | 12.69%  |
| Unknown | 28       | 10.77%  |
| 21/9    | 17       | 6.54%   |
| 5/4     | 12       | 4.62%   |
| 4/3     | 7        | 2.69%   |
| 6/5     | 2        | 0.77%   |
| 32/9    | 1        | 0.38%   |
| 3/2     | 1        | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 82       | 29.71%  |
| 351-500        | 42       | 15.22%  |
| 301-350        | 40       | 14.49%  |
| Unknown        | 31       | 11.23%  |
| 151-200        | 27       | 9.78%   |
| 251-300        | 19       | 6.88%   |
| 141-150        | 14       | 5.07%   |
| 501-1000       | 6        | 2.17%   |
| 101-110        | 4        | 1.45%   |
| More than 1000 | 3        | 1.09%   |
| 81-90          | 2        | 0.72%   |
| 121-130        | 2        | 0.72%   |
| 111-120        | 2        | 0.72%   |
| 71-80          | 1        | 0.36%   |
| 1-40           | 1        | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 159      | 60.92%  |
| 101-120 | 44       | 16.86%  |
| Unknown | 31       | 11.88%  |
| 121-160 | 12       | 4.6%    |
| 161-240 | 11       | 4.21%   |
| 1-50    | 4        | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1662     | 85.76%  |
| 1     | 237      | 12.23%  |
| 2     | 33       | 1.7%    |
| 3     | 6        | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 1636     | 62.13%  |
| Realtek Semiconductor           | 588      | 22.33%  |
| Qualcomm Atheros                | 100      | 3.8%    |
| Broadcom                        | 94       | 3.57%   |
| Mellanox Technologies           | 37       | 1.41%   |
| Ralink Technology               | 23       | 0.87%   |
| Chelsio Communications          | 16       | 0.61%   |
| IMC Networks                    | 15       | 0.57%   |
| U-Blox                          | 13       | 0.49%   |
| Ralink                          | 11       | 0.42%   |
| Solarflare Communications       | 9        | 0.34%   |
| Aquantia                        | 9        | 0.34%   |
| MediaTek                        | 7        | 0.27%   |
| Marvell Technology Group        | 7        | 0.27%   |
| D-Link System                   | 7        | 0.27%   |
| Seeed Technology                | 6        | 0.23%   |
| TP-Link                         | 4        | 0.15%   |
| American Megatrends             | 4        | 0.15%   |
| Sequans Communications          | 3        | 0.11%   |
| Novatel Wireless                | 3        | 0.11%   |
| Emulex                          | 3        | 0.11%   |
| VIA Technologies                | 2        | 0.08%   |
| Qualcomm Atheros Communications | 2        | 0.08%   |
| Linksys                         | 2        | 0.08%   |
| ICS Advent                      | 2        | 0.08%   |
| Edimax Technology               | 2        | 0.08%   |
| Belkin Components               | 2        | 0.08%   |
| Apple                           | 2        | 0.08%   |
| Accton Technology               | 2        | 0.08%   |
| 3Com                            | 2        | 0.08%   |
| ZyXEL Communications            | 1        | 0.04%   |
| Xiaomi                          | 1        | 0.04%   |
| Tehuti Networks                 | 1        | 0.04%   |
| Silicom                         | 1        | 0.04%   |
| Sierra Wireless                 | 1        | 0.04%   |
| Pulse-Eight                     | 1        | 0.04%   |
| Oracle/SUN                      | 1        | 0.04%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.04%   |
| Nvidia                          | 1        | 0.04%   |
| NetXen Incorporated             | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 482      | 14.41%  |
| Intel I211 Gigabit Network Connection                                         | 284      | 8.49%   |
| Intel I210 Gigabit Network Connection                                         | 165      | 4.93%   |
| Intel Ethernet Controller I225-V                                              | 149      | 4.45%   |
| Intel 82574L Gigabit Network Connection                                       | 133      | 3.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 130      | 3.89%   |
| Intel I350 Gigabit Network Connection                                         | 120      | 3.59%   |
| Intel Ethernet Connection I217-LM                                             | 102      | 3.05%   |
| Intel Ethernet Controller I226-V                                              | 101      | 3.02%   |
| Intel 82583V Gigabit Network Connection                                       | 86       | 2.57%   |
| Intel 82580 Gigabit Network Connection                                        | 80       | 2.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 74       | 2.21%   |
| Intel 82576 Gigabit Network Connection                                        | 65       | 1.94%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 65       | 1.94%   |
| Intel Ethernet Connection (2) I219-LM                                         | 57       | 1.7%    |
| Intel Wi-Fi 6 AX200                                                           | 50       | 1.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 50       | 1.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 49       | 1.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 46       | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                          | 34       | 1.02%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 23       | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                         | 23       | 0.69%   |
| Intel 82575EB Gigabit Network Connection                                      | 21       | 0.63%   |
| Intel Ethernet Controller X550                                                | 20       | 0.6%    |
| Intel 82579V Gigabit Network Connection                                       | 20       | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 19       | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                          | 18       | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 17       | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                         | 17       | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 16       | 0.48%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 15       | 0.45%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 15       | 0.45%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 15       | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 14       | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 14       | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 14       | 0.42%   |
| Intel Wireless 3165                                                           | 14       | 0.42%   |
| Intel Ethernet Controller I225-LM                                             | 14       | 0.42%   |
| Intel Ethernet Connection (2) I218-V                                          | 14       | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 12       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 195      | 45.45%  |
| Qualcomm Atheros                | 84       | 19.58%  |
| Realtek Semiconductor           | 58       | 13.52%  |
| Ralink Technology               | 23       | 5.36%   |
| Broadcom                        | 20       | 4.66%   |
| IMC Networks                    | 15       | 3.5%    |
| Ralink                          | 11       | 2.56%   |
| MediaTek                        | 7        | 1.63%   |
| TP-Link                         | 4        | 0.93%   |
| Qualcomm Atheros Communications | 2        | 0.47%   |
| Edimax Technology               | 2        | 0.47%   |
| Belkin Components               | 2        | 0.47%   |
| ZyXEL Communications            | 1        | 0.23%   |
| Sierra Wireless                 | 1        | 0.23%   |
| Linksys                         | 1        | 0.23%   |
| D-Link System                   | 1        | 0.23%   |
| D-Link                          | 1        | 0.23%   |
| ASUSTek Computer                | 1        | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 50       | 11.55%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 19       | 4.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 17       | 3.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16       | 3.7%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 15       | 3.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14       | 3.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 14       | 3.23%   |
| Intel Wireless 3165                                            | 14       | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12       | 2.77%   |
| Intel Wireless-AC 9260                                         | 12       | 2.77%   |
| Intel Wireless 7265                                            | 10       | 2.31%   |
| Intel Wireless 7260                                            | 10       | 2.31%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 10       | 2.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9        | 2.08%   |
| Ralink RT5370 Wireless Adapter                                 | 8        | 1.85%   |
| Intel Wireless 8260                                            | 8        | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7        | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6        | 1.39%   |
| Ralink RT5572 Wireless Adapter                                 | 6        | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6        | 1.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 1.39%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6        | 1.39%   |
| Intel Wireless 3160                                            | 5        | 1.15%   |
| Intel Centrino Wireless-N 2230                                 | 5        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4        | 0.92%   |
| Ralink MT7601U Wireless Adapter                                | 4        | 0.92%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 4        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4        | 0.92%   |
| Intel Wireless 8265 / 8275                                     | 4        | 0.92%   |
| Intel CNVi: Wi-Fi                                              | 4        | 0.92%   |
| Intel Centrino Wireless-N 105                                  | 4        | 0.92%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 4        | 0.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4        | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3        | 0.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 3        | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 1583     | 68.56%  |
| Realtek Semiconductor         | 560      | 24.25%  |
| Broadcom                      | 76       | 3.29%   |
| Qualcomm Atheros              | 18       | 0.78%   |
| Chelsio Communications        | 14       | 0.61%   |
| Solarflare Communications     | 9        | 0.39%   |
| Aquantia                      | 8        | 0.35%   |
| Marvell Technology Group      | 7        | 0.3%    |
| D-Link System                 | 6        | 0.26%   |
| American Megatrends           | 4        | 0.17%   |
| Novatel Wireless              | 3        | 0.13%   |
| Emulex                        | 3        | 0.13%   |
| VIA Technologies              | 2        | 0.09%   |
| ICS Advent                    | 2        | 0.09%   |
| 3Com                          | 2        | 0.09%   |
| Xiaomi                        | 1        | 0.04%   |
| Tehuti Networks               | 1        | 0.04%   |
| Silicom                       | 1        | 0.04%   |
| Oracle/SUN                    | 1        | 0.04%   |
| OnePlus Technology (Shenzhen) | 1        | 0.04%   |
| Nvidia                        | 1        | 0.04%   |
| National Semiconductor        | 1        | 0.04%   |
| Linksys                       | 1        | 0.04%   |
| Insyde Software               | 1        | 0.04%   |
| Apple                         | 1        | 0.04%   |
| ADMtek                        | 1        | 0.04%   |
| Accton Technology             | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 482      | 17.03%  |
| Intel I211 Gigabit Network Connection                                         | 284      | 10.03%  |
| Intel I210 Gigabit Network Connection                                         | 165      | 5.83%   |
| Intel Ethernet Controller I225-V                                              | 149      | 5.26%   |
| Intel 82574L Gigabit Network Connection                                       | 133      | 4.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 130      | 4.59%   |
| Intel I350 Gigabit Network Connection                                         | 120      | 4.24%   |
| Intel Ethernet Connection I217-LM                                             | 102      | 3.6%    |
| Intel Ethernet Controller I226-V                                              | 101      | 3.57%   |
| Intel 82583V Gigabit Network Connection                                       | 86       | 3.04%   |
| Intel 82580 Gigabit Network Connection                                        | 80       | 2.83%   |
| Realtek RTL8125 2.5GbE Controller                                             | 71       | 2.51%   |
| Intel 82576 Gigabit Network Connection                                        | 65       | 2.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 65       | 2.3%    |
| Intel Ethernet Connection (2) I219-LM                                         | 57       | 2.01%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 50       | 1.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 49       | 1.73%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 46       | 1.62%   |
| Intel Ethernet Connection (2) I219-V                                          | 34       | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                                         | 23       | 0.81%   |
| Intel 82575EB Gigabit Network Connection                                      | 21       | 0.74%   |
| Intel Ethernet Controller X550                                                | 20       | 0.71%   |
| Intel 82579V Gigabit Network Connection                                       | 20       | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                          | 18       | 0.64%   |
| Intel Ethernet Connection (5) I219-LM                                         | 17       | 0.6%    |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 15       | 0.53%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 15       | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 14       | 0.49%   |
| Intel Ethernet Controller I225-LM                                             | 14       | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                          | 14       | 0.49%   |
| Intel Ethernet Connection I217-V                                              | 12       | 0.42%   |
| Intel Ethernet Connection X553 1GbE                                           | 11       | 0.39%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 11       | 0.39%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11       | 0.39%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 10       | 0.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9        | 0.32%   |
| Intel Ethernet Connection I354                                                | 9        | 0.32%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 9        | 0.32%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 8        | 0.28%   |
| Intel 82575GB Gigabit Network Connection                                      | 8        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1905     | 79.57%  |
| WiFi     | 410      | 17.13%  |
| Unknown  | 57       | 2.38%   |
| Modem    | 22       | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1860     | 96.32%  |
| WiFi     | 64       | 3.31%   |
| Unknown  | 7        | 0.36%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 452      | 22.9%   |
| 2     | 363      | 18.39%  |
| 3     | 326      | 16.51%  |
| 1     | 257      | 13.02%  |
| 6     | 239      | 12.11%  |
| 5     | 193      | 9.78%   |
| 7     | 52       | 2.63%   |
| 8     | 35       | 1.77%   |
| 9     | 18       | 0.91%   |
| 10    | 11       | 0.56%   |
| 0     | 11       | 0.56%   |
| 11    | 4        | 0.2%    |
| 16    | 3        | 0.15%   |
| 15    | 3        | 0.15%   |
| 14    | 2        | 0.1%    |
| 13    | 2        | 0.1%    |
| 12    | 2        | 0.1%    |
| 20    | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1556     | 77.11%  |
| Yes  | 462      | 22.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 170      | 61.15%  |
| Realtek Semiconductor           | 27       | 9.71%   |
| Qualcomm Atheros Communications | 14       | 5.04%   |
| Cambridge Silicon Radio         | 13       | 4.68%   |
| ASUSTek Computer                | 11       | 3.96%   |
| Broadcom                        | 10       | 3.6%    |
| Apple                           | 10       | 3.6%    |
| IMC Networks                    | 7        | 2.52%   |
| MediaTek                        | 6        | 2.16%   |
| Lite-On Technology              | 5        | 1.8%    |
| TP-Link                         | 1        | 0.36%   |
| Ralink                          | 1        | 0.36%   |
| Primax Electronics              | 1        | 0.36%   |
| Dynex                           | 1        | 0.36%   |
| Corsair                         | 1        | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 43       | 15.41%  |
| Intel Bluetooth wireless interface                          | 42       | 15.05%  |
| Intel Wireless-AC 3168 Bluetooth                            | 20       | 7.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 20       | 7.17%   |
| Intel AX210 Bluetooth                                       | 14       | 5.02%   |
| Intel AX201 Bluetooth                                       | 14       | 5.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 13       | 4.66%   |
| Realtek Bluetooth Adapter                                   | 11       | 3.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 10       | 3.58%   |
| Realtek  Bluetooth 4.2 Adapter                              | 9        | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 8        | 2.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 7        | 2.51%   |
| MediaTek RZ608 Bluetooth Adapter                            | 6        | 2.15%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 6        | 2.15%   |
| Realtek Bluetooth 4.2 Adapter                               | 5        | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3        | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3        | 1.08%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2        | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2        | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2        | 0.72%   |
| Lite-On Bluetooth USB Module                                | 2        | 0.72%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 0.72%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 2        | 0.72%   |
| Broadcom 20702 Bluetooth 4.0 Adapter                        | 2        | 0.72%   |
| ASUS USB-BT500                                              | 2        | 0.72%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 2        | 0.72%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2        | 0.72%   |
| ASUS Bluetooth USB module                                   | 2        | 0.72%   |
| ASUS Bluetooth Controller                                   | 2        | 0.72%   |
| Apple Bluetooth Host Controller                             | 2        | 0.72%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1        | 0.36%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                 | 1        | 0.36%   |
| Realtek Bluetooth 4.0 Adapter                               | 1        | 0.36%   |
| Ralink RT3290 Bluetooth                                     | 1        | 0.36%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1        | 0.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1        | 0.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1        | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.36%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 0.36%   |
| Lite-On Atheros AR9462 Bluetooth 4.0 + HS                   | 1        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1180     | 65.16%  |
| AMD                                          | 353      | 19.49%  |
| Nvidia                                       | 176      | 9.72%   |
| C-Media Electronics                          | 34       | 1.88%   |
| Creative Labs                                | 13       | 0.72%   |
| SteelSeries ApS                              | 6        | 0.33%   |
| Texas Instruments                            | 4        | 0.22%   |
| Logitech                                     | 4        | 0.22%   |
| Blue Microphones                             | 4        | 0.22%   |
| Corsair                                      | 3        | 0.17%   |
| Yamaha                                       | 2        | 0.11%   |
| Realtek Semiconductor                        | 2        | 0.11%   |
| Razer USA                                    | 2        | 0.11%   |
| Google                                       | 2        | 0.11%   |
| Creative Technology                          | 2        | 0.11%   |
| ASUSTek Computer                             | 2        | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.06%   |
| XMOS                                         | 1        | 0.06%   |
| VIA Technologies                             | 1        | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.06%   |
| Tenx Technology                              | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.06%   |
| Quanta                                       | 1        | 0.06%   |
| Nektar                                       | 1        | 0.06%   |
| LG Electronics                               | 1        | 0.06%   |
| KORG                                         | 1        | 0.06%   |
| Kingston Technology                          | 1        | 0.06%   |
| Hewlett-Packard                              | 1        | 0.06%   |
| Harman                                       | 1        | 0.06%   |
| Genesys Logic                                | 1        | 0.06%   |
| Focusrite-Novation                           | 1        | 0.06%   |
| Dell                                         | 1        | 0.06%   |
| Cirrus Logic                                 | 1        | 0.06%   |
| Cambridge Silicon Radio                      | 1        | 0.06%   |
| AudioQuest                                   | 1        | 0.06%   |
| Astro Gaming                                 | 1        | 0.06%   |
| Apple                                        | 1        | 0.06%   |
| AKAI  Professional M.I.                      | 1        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 152      | 6.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 141      | 6.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 111      | 5.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 89       | 4.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 87       | 3.94%   |
| Intel Jasper Lake HD Audio                                                                        | 85       | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 80       | 3.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 79       | 3.58%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 65       | 2.95%   |
| AMD FCH Azalia Controller                                                                         | 62       | 2.81%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 60       | 2.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 59       | 2.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 59       | 2.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 55       | 2.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 42       | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 42       | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 41       | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 34       | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 33       | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 33       | 1.5%    |
| Intel Broadwell-U Audio Controller                                                                | 33       | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 33       | 1.5%    |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 26       | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 25       | 1.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 25       | 1.13%   |
| Intel 8 Series HD Audio Controller                                                                | 24       | 1.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23       | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 20       | 0.91%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 18       | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 18       | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 18       | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 15       | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 15       | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 14       | 0.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 14       | 0.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 14       | 0.63%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 13       | 0.59%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13       | 0.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13       | 0.59%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 12       | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Electronics                     | 312      | 14.97%  |
| Crucial                                 | 275      | 13.2%   |
| SK hynix                                | 256      | 12.28%  |
| Kingston                                | 213      | 10.22%  |
| Micron Technology                       | 188      | 9.02%   |
| Unknown                                 | 186      | 8.93%   |
| G.Skill                                 | 138      | 6.62%   |
| Corsair                                 | 120      | 5.76%   |
| Unknown                                 | 63       | 3.02%   |
| Team                                    | 53       | 2.54%   |
| Patriot                                 | 25       | 1.2%    |
| Ramaxel Technology                      | 23       | 1.1%    |
| Nanya Technology                        | 22       | 1.06%   |
| Unknown (ABCD)                          | 21       | 1.01%   |
| A-DATA Technology                       | 21       | 1.01%   |
| PNY                                     | 19       | 0.91%   |
| Transcend                               | 14       | 0.67%   |
| Kimtigo                                 | 13       | 0.62%   |
| Timetec                                 | 10       | 0.48%   |
| Silicon Power                           | 9        | 0.43%   |
| Super Talent                            | 7        | 0.34%   |
| Innodisk                                | 6        | 0.29%   |
| Elpida                                  | 6        | 0.29%   |
| Avant                                   | 6        | 0.29%   |
| SK_Hynix                                | 5        | 0.24%   |
| Silicon Power Computer & Communications | 5        | 0.24%   |
| Sesame                                  | 4        | 0.19%   |
| GeIL                                    | 4        | 0.19%   |
| Toshiba                                 | 3        | 0.14%   |
| Ramsta                                  | 3        | 0.14%   |
| Patriot Memory (PDP Systems)            | 3        | 0.14%   |
| Mushkin                                 | 3        | 0.14%   |
| Vasekey                                 | 2        | 0.1%    |
| Unknown (AB)                            | 2        | 0.1%    |
| Neo Forza                               | 2        | 0.1%    |
| J&A Information                         | 2        | 0.1%    |
| GSkill                                  | 2        | 0.1%    |
| CSX                                     | 2        | 0.1%    |
| Apacer                                  | 2        | 0.1%    |
| Wodposit                                | 1        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 63       | 2.87%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 21       | 0.96%   |
| Unknown RAM Module 8GB 1600MT/s                                | 20       | 0.91%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 17       | 0.77%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 17       | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 16       | 0.73%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 15       | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 14       | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 14       | 0.64%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 12       | 0.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 12       | 0.55%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s          | 11       | 0.5%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 10       | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 10       | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 10       | 0.46%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s           | 10       | 0.46%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 10       | 0.46%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 10       | 0.46%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 9        | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 9        | 0.41%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 9        | 0.41%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 9        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 8        | 0.36%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s            | 8        | 0.36%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                     | 8        | 0.36%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 8        | 0.36%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 8        | 0.36%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 8        | 0.36%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s            | 8        | 0.36%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s          | 8        | 0.36%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 8        | 0.36%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 8        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 7        | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 7        | 0.32%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s          | 7        | 0.32%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s           | 7        | 0.32%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 7        | 0.32%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s          | 7        | 0.32%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 7        | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 6        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 810      | 44.38%  |
| DDR3         | 803      | 44%     |
| Unknown      | 57       | 3.12%   |
| DDR2         | 53       | 2.9%    |
| DDR5         | 35       | 1.92%   |
| LPDDR4       | 34       | 1.86%   |
| SDRAM        | 21       | 1.15%   |
| DDR          | 9        | 0.49%   |
| LPDDR5       | 1        | 0.05%   |
| LPDDR3       | 1        | 0.05%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1182     | 65.23%  |
| SODIMM       | 573      | 31.62%  |
| Unknown      | 37       | 2.04%   |
| Row Of Chips | 14       | 0.77%   |
| RIMM         | 5        | 0.28%   |
| FB-DIMM      | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 823      | 42.29%  |
| 4096  | 540      | 27.75%  |
| 16384 | 294      | 15.11%  |
| 2048  | 168      | 8.63%   |
| 32768 | 84       | 4.32%   |
| 1024  | 31       | 1.59%   |
| 512   | 5        | 0.26%   |
| 65536 | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 594      | 30.59%  |
| 2400    | 255      | 13.13%  |
| 3200    | 213      | 10.97%  |
| 1333    | 211      | 10.87%  |
| 2667    | 164      | 8.44%   |
| 2133    | 164      | 8.44%   |
| 800     | 57       | 2.94%   |
| 2666    | 44       | 2.27%   |
| 4800    | 30       | 1.54%   |
| 3600    | 29       | 1.49%   |
| 667     | 29       | 1.49%   |
| 3000    | 27       | 1.39%   |
| 1066    | 24       | 1.24%   |
| Unknown | 19       | 0.98%   |
| 1867    | 16       | 0.82%   |
| 1067    | 13       | 0.67%   |
| 2933    | 11       | 0.57%   |
| 1334    | 9        | 0.46%   |
| 1866    | 7        | 0.36%   |
| 533     | 6        | 0.31%   |
| 5600    | 4        | 0.21%   |
| 6400    | 2        | 0.1%    |
| 4267    | 2        | 0.1%    |
| 4000    | 2        | 0.1%    |
| 1400    | 2        | 0.1%    |
| 4133    | 1        | 0.05%   |
| 3534    | 1        | 0.05%   |
| 3333    | 1        | 0.05%   |
| 2866    | 1        | 0.05%   |
| 1639    | 1        | 0.05%   |
| 1033    | 1        | 0.05%   |
| 400     | 1        | 0.05%   |
| 266     | 1        | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 2        | 28.57%  |
| Brother Industries    | 2        | 28.57%  |
| Prolific Technology   | 1        | 14.29%  |
| Lexmark International | 1        | 14.29%  |
| Apple                 | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                                            | 1        | 12.5%   |
| Lexmark International Lexmark MS710 Print                                | 1        | 12.5%   |
| HP PNP Fax Null                                                          | 1        | 12.5%   |
| HP LaserJet 1012                                                         | 1        | 12.5%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1        | 12.5%   |
| Brother MFC-L2685DW                                                      | 1        | 12.5%   |
| Brother MFC-J485DW                                                       | 1        | 12.5%   |
| Apple Gamesir-G3s 2.10                                                   | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2        | 66.67%  |
| HP ScanJet 5300c/5370c                                                              | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 20       | 47.62%  |
| Microdia                      | 5        | 11.9%   |
| Sunplus Innovation Technology | 3        | 7.14%   |
| WCM_USB                       | 2        | 4.76%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 4.76%   |
| Generalplus Technology        | 2        | 4.76%   |
| Chicony Electronics           | 2        | 4.76%   |
| Xiongmai                      | 1        | 2.38%   |
| Suyin                         | 1        | 2.38%   |
| Quanta                        | 1        | 2.38%   |
| Lenovo                        | 1        | 2.38%   |
| Arkmicro Technologies         | 1        | 2.38%   |
| ARC International             | 1        | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 6        | 14.29%  |
| Logitech HD Pro Webcam C920                    | 6        | 14.29%  |
| Microdia Webcam Vitade AF                      | 3        | 7.14%   |
| Logitech C922 Pro Stream Webcam                | 3        | 7.14%   |
| WCM_USB WEB CAM                                | 2        | 4.76%   |
| Sunplus USB 2.0 Camera                         | 2        | 4.76%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 4.76%   |
| Logitech Webcam C310                           | 2        | 4.76%   |
| Generalplus HD Webcam                          | 2        | 4.76%   |
| Xiongmai web camera                            | 1        | 2.38%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 2.38%   |
| Sunplus hama C-600 Pro Webcam                  | 1        | 2.38%   |
| Quanta Realtek DMFT RGB                        | 1        | 2.38%   |
| Microdia Ltd., USB  Live camera                | 1        | 2.38%   |
| Microdia Camera                                | 1        | 2.38%   |
| Logitech HD Webcam C615                        | 1        | 2.38%   |
| Logitech HD Webcam C525                        | 1        | 2.38%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 2.38%   |
| Lenovo Integrated Camera                       | 1        | 2.38%   |
| Chicony Ltd., HP 0.3MP Webcam                  | 1        | 2.38%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 2.38%   |
| Arkmicro USB 2.0 PC CAMERA                     | 1        | 2.38%   |
| ARC International Camera                       | 1        | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 1     | 1001     | 50.63%  |
| 0     | 607      | 30.7%   |
| 2     | 265      | 13.4%   |
| 3     | 82       | 4.15%   |
| 4     | 18       | 0.91%   |
| 7     | 2        | 0.1%    |
| 6     | 1        | 0.05%   |
| 5     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 1178     | 71.7%   |
| Net/wireless             | 139      | 8.46%   |
| Bluetooth                | 116      | 7.06%   |
| Firewire controller      | 60       | 3.65%   |
| Sound                    | 37       | 2.25%   |
| Net/ethernet             | 35       | 2.13%   |
| Card reader              | 33       | 2.01%   |
| Network                  | 29       | 1.77%   |
| Graphics card            | 8        | 0.49%   |
| Storage/raid             | 6        | 0.37%   |
| Storage/ata              | 1        | 0.06%   |
| Dvb card                 | 1        | 0.06%   |

