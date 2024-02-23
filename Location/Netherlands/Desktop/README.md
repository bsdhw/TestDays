BSD in Netherlands - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

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

Total: 360

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU2                        | [70927f49d1](https://bsd-hardware.info/?probe=70927f49d1) | Feb 12, 2024 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [7f4338cdd1](https://bsd-hardware.info/?probe=7f4338cdd1) | Feb 10, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [ba3543c2a6](https://bsd-hardware.info/?probe=ba3543c2a6) | Feb 06, 2024 |
| Dell          | 0M5DCD A00                  | [1ce2ca36bf](https://bsd-hardware.info/?probe=1ce2ca36bf) | Feb 04, 2024 |
| SolidRun      | CEX7 Platform               | [ae1a4bcbae](https://bsd-hardware.info/?probe=ae1a4bcbae) | Jan 23, 2024 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [dced74ec00](https://bsd-hardware.info/?probe=dced74ec00) | Jan 22, 2024 |
| SolidRun      | CEX7 Platform               | [d876c335eb](https://bsd-hardware.info/?probe=d876c335eb) | Jan 21, 2024 |
| Protectli     | FW4C                        | [2c1c42d709](https://bsd-hardware.info/?probe=2c1c42d709) | Jan 14, 2024 |
| JHZD          | BQM6                        | [da3f533607](https://bsd-hardware.info/?probe=da3f533607) | Jan 12, 2024 |
| PC Engines    | APU2                        | [a382f94e4c](https://bsd-hardware.info/?probe=a382f94e4c) | Jan 11, 2024 |
| PC Engines    | APU2                        | [59c447670f](https://bsd-hardware.info/?probe=59c447670f) | Jan 11, 2024 |
| Unknown       | Unknown                     | [f2dc1aea59](https://bsd-hardware.info/?probe=f2dc1aea59) | Jan 09, 2024 |
| Protectli     | FW6                         | [ec96e60da6](https://bsd-hardware.info/?probe=ec96e60da6) | Jan 09, 2024 |
| CWWK          | CW-J6-6L                    | [f4b8232caf](https://bsd-hardware.info/?probe=f4b8232caf) | Jan 07, 2024 |
| ASRock        | N100DC-ITX                  | [221546eb8c](https://bsd-hardware.info/?probe=221546eb8c) | Jan 05, 2024 |
| Intel         | Q3XXG4-P V1.0               | [02a64e7c07](https://bsd-hardware.info/?probe=02a64e7c07) | Jan 04, 2024 |
| Unknown       | Unknown                     | [cd6ce65004](https://bsd-hardware.info/?probe=cd6ce65004) | Dec 29, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [321e9d7328](https://bsd-hardware.info/?probe=321e9d7328) | Dec 20, 2023 |
| Techvision    | TVI7309X B0                 | [fe741ca47c](https://bsd-hardware.info/?probe=fe741ca47c) | Dec 17, 2023 |
| Dell          | 05XGC8 A00                  | [b453da5223](https://bsd-hardware.info/?probe=b453da5223) | Dec 12, 2023 |
| Unknown       | Unknown                     | [37499be816](https://bsd-hardware.info/?probe=37499be816) | Dec 11, 2023 |
| AAEON         | FWS-2362 V1.0               | [a58d1df175](https://bsd-hardware.info/?probe=a58d1df175) | Dec 10, 2023 |
| HP            | 82A2                        | [688675d8ea](https://bsd-hardware.info/?probe=688675d8ea) | Dec 10, 2023 |
| Dell          | 05XGC8 A00                  | [b193b5141c](https://bsd-hardware.info/?probe=b193b5141c) | Dec 07, 2023 |
| Protectli     | FW4C                        | [d14bbfd96c](https://bsd-hardware.info/?probe=d14bbfd96c) | Dec 05, 2023 |
| Dell          | 0NW6H5 A00                  | [d9c6d21d10](https://bsd-hardware.info/?probe=d9c6d21d10) | Dec 05, 2023 |
| Protectli     | FW4B                        | [a92d9762ce](https://bsd-hardware.info/?probe=a92d9762ce) | Dec 04, 2023 |
| HP            | ProLiant ML350p Gen8        | [24f4b0ec7e](https://bsd-hardware.info/?probe=24f4b0ec7e) | Nov 24, 2023 |
| Unknown       | Unknown                     | [00ad304a82](https://bsd-hardware.info/?probe=00ad304a82) | Nov 24, 2023 |
| HP            | 21D0                        | [d03aa6a73b](https://bsd-hardware.info/?probe=d03aa6a73b) | Nov 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | [829f20c667](https://bsd-hardware.info/?probe=829f20c667) | Nov 23, 2023 |
| Shuttle       | XH310V2                     | [524f7be8b5](https://bsd-hardware.info/?probe=524f7be8b5) | Nov 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | [cb6ef0498c](https://bsd-hardware.info/?probe=cb6ef0498c) | Nov 22, 2023 |
| HP            | 82A2                        | [11985512b1](https://bsd-hardware.info/?probe=11985512b1) | Nov 08, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | [e3852e0a81](https://bsd-hardware.info/?probe=e3852e0a81) | Nov 05, 2023 |
| ASUSTek       | PRIME B250M-A               | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| ASUSTek       | PRIME B250M-A               | [534dc363f2](https://bsd-hardware.info/?probe=534dc363f2) | Oct 30, 2023 |
| PC Engines    | APU2                        | [78e2f0b5e4](https://bsd-hardware.info/?probe=78e2f0b5e4) | Oct 30, 2023 |
| AAEON         | FWS-2362 V1.0               | [cddea934bd](https://bsd-hardware.info/?probe=cddea934bd) | Oct 30, 2023 |
| Dell          | 0JP3NX A01                  | [937bf733c5](https://bsd-hardware.info/?probe=937bf733c5) | Oct 28, 2023 |
| ASRock        | N100DC-ITX                  | [888d7c9d18](https://bsd-hardware.info/?probe=888d7c9d18) | Oct 28, 2023 |
| Unknown       | Unknown                     | [648234b9c2](https://bsd-hardware.info/?probe=648234b9c2) | Oct 09, 2023 |
| Hardkernel    | ODROID-H3                   | [dc147098c6](https://bsd-hardware.info/?probe=dc147098c6) | Oct 08, 2023 |
| HP            | 82B4                        | [daaf49e002](https://bsd-hardware.info/?probe=daaf49e002) | Oct 06, 2023 |
| Dell          | 0M5DCD A00                  | [c7e64c0893](https://bsd-hardware.info/?probe=c7e64c0893) | Sep 19, 2023 |
| Dell          | 0HD5W2 A00                  | [6857d78d0b](https://bsd-hardware.info/?probe=6857d78d0b) | Sep 12, 2023 |
| HP            | 8105                        | [ea4f88787c](https://bsd-hardware.info/?probe=ea4f88787c) | Sep 10, 2023 |
| HP            | 8105                        | [0e45394704](https://bsd-hardware.info/?probe=0e45394704) | Sep 10, 2023 |
| Unknown       | Unknown                     | [35e9ee2a00](https://bsd-hardware.info/?probe=35e9ee2a00) | Sep 07, 2023 |
| Dell          | 0NW6H5 A00                  | [8109e9f43f](https://bsd-hardware.info/?probe=8109e9f43f) | Aug 29, 2023 |
| SolidRun      | CEX7 Platform               | [b83ebfd33b](https://bsd-hardware.info/?probe=b83ebfd33b) | Aug 29, 2023 |
| Unknown       | Unknown                     | [0de8fccd23](https://bsd-hardware.info/?probe=0de8fccd23) | Aug 27, 2023 |
| SolidRun      | CEX7 Platform               | [4d51e18ce4](https://bsd-hardware.info/?probe=4d51e18ce4) | Aug 25, 2023 |
| Intel         | DQ67SW AAG12527-310         | [f07be9b690](https://bsd-hardware.info/?probe=f07be9b690) | Aug 24, 2023 |
| Advantech     | SYS-2USM02-6M01E            | [dd02b9879d](https://bsd-hardware.info/?probe=dd02b9879d) | Aug 20, 2023 |
| CncTion       | N5105-4L-I226 B0            | [40f2ba2800](https://bsd-hardware.info/?probe=40f2ba2800) | Aug 18, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [ad77aba442](https://bsd-hardware.info/?probe=ad77aba442) | Aug 15, 2023 |
| Dell          | 0NW6H5 A00                  | [b05547dfb4](https://bsd-hardware.info/?probe=b05547dfb4) | Aug 13, 2023 |
| ASRock        | IMB-195                     | [7b5a73b87e](https://bsd-hardware.info/?probe=7b5a73b87e) | Aug 09, 2023 |
| Unknown       | Unknown                     | [080c931545](https://bsd-hardware.info/?probe=080c931545) | Jul 31, 2023 |
| Supermicro    | X7SLA                       | [c9a39071d0](https://bsd-hardware.info/?probe=c9a39071d0) | Jul 31, 2023 |
| Techvision    | TVI7309X B0                 | [e06b70a370](https://bsd-hardware.info/?probe=e06b70a370) | Jul 29, 2023 |
| MW            | GMLK-2_5G4L                 | [c9ecdb6ecc](https://bsd-hardware.info/?probe=c9ecdb6ecc) | Jul 28, 2023 |
| Unknown       | Unknown                     | [468f7385c9](https://bsd-hardware.info/?probe=468f7385c9) | Jul 25, 2023 |
| ASRock        | J4205-ITX                   | [90fc3f8e29](https://bsd-hardware.info/?probe=90fc3f8e29) | Jul 23, 2023 |
| Techvision    | TVI7309X B0                 | [154660fa30](https://bsd-hardware.info/?probe=154660fa30) | Jul 21, 2023 |
| Dell          | 0VRWRC A00                  | [abec149182](https://bsd-hardware.info/?probe=abec149182) | Jul 17, 2023 |
| MW            | GMLK-2_5G4L                 | [a99b1233cf](https://bsd-hardware.info/?probe=a99b1233cf) | Jul 15, 2023 |
| Protectli     | VP46xx                      | [516324d248](https://bsd-hardware.info/?probe=516324d248) | Jul 13, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [08b0409497](https://bsd-hardware.info/?probe=08b0409497) | Jul 12, 2023 |
| Unknown       | Unknown                     | [19bec52055](https://bsd-hardware.info/?probe=19bec52055) | Jul 12, 2023 |
| Dell          | 0M5DCD A00                  | [0723a0cf95](https://bsd-hardware.info/?probe=0723a0cf95) | Jul 11, 2023 |
| Protectli     | FW2B Ver                    | [e0746e5253](https://bsd-hardware.info/?probe=e0746e5253) | Jul 10, 2023 |
| Shuttle       | FH110                       | [e68f7ffbf9](https://bsd-hardware.info/?probe=e68f7ffbf9) | Jul 06, 2023 |
| Unknown       | Unknown                     | [e0dd332586](https://bsd-hardware.info/?probe=e0dd332586) | Jul 05, 2023 |
| Intel         | Q3XXG4-P V1.0               | [3e8f4fb0a8](https://bsd-hardware.info/?probe=3e8f4fb0a8) | Jun 29, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [96917bdb04](https://bsd-hardware.info/?probe=96917bdb04) | Jun 26, 2023 |
| Unknown       | Unknown                     | [18da718e9e](https://bsd-hardware.info/?probe=18da718e9e) | Jun 26, 2023 |
| Gigabyte      | H610I DDR4                  | [dea4808206](https://bsd-hardware.info/?probe=dea4808206) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6172c8b66f](https://bsd-hardware.info/?probe=6172c8b66f) | Jun 22, 2023 |
| ASRock        | H110M-ITX                   | [1180da18fb](https://bsd-hardware.info/?probe=1180da18fb) | Jun 22, 2023 |
| Unknown       | Unknown                     | [29313e36c9](https://bsd-hardware.info/?probe=29313e36c9) | Jun 18, 2023 |
| Unknown       | Unknown                     | [2cc06a4553](https://bsd-hardware.info/?probe=2cc06a4553) | Jun 18, 2023 |
| CWWK          | CW-J6-6L                    | [a380503321](https://bsd-hardware.info/?probe=a380503321) | Jun 11, 2023 |
| HP            | 18E7                        | [6daf82289e](https://bsd-hardware.info/?probe=6daf82289e) | Jun 07, 2023 |
| HP            | 18E7                        | [4ca0d96863](https://bsd-hardware.info/?probe=4ca0d96863) | Jun 03, 2023 |
| HP            | 18E7                        | [5ab1548fe9](https://bsd-hardware.info/?probe=5ab1548fe9) | May 26, 2023 |
| HP            | 18E7                        | [a4d64c1a5e](https://bsd-hardware.info/?probe=a4d64c1a5e) | May 23, 2023 |
| HP            | 18E7                        | [f6986c366c](https://bsd-hardware.info/?probe=f6986c366c) | May 22, 2023 |
| Dell          | 0M5DCD A00                  | [9e1f65bb29](https://bsd-hardware.info/?probe=9e1f65bb29) | May 18, 2023 |
| Dell          | 08NPPY A00                  | [c27d2cfe8b](https://bsd-hardware.info/?probe=c27d2cfe8b) | May 15, 2023 |
| MW            | GMLK-2_5G4L                 | [40b5182f45](https://bsd-hardware.info/?probe=40b5182f45) | May 15, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [819076e07f](https://bsd-hardware.info/?probe=819076e07f) | May 14, 2023 |
| Unknown       | Unknown                     | [d678e62c0c](https://bsd-hardware.info/?probe=d678e62c0c) | May 14, 2023 |
| MW            | GMLK-2_5G4L                 | [7b02526ba4](https://bsd-hardware.info/?probe=7b02526ba4) | May 14, 2023 |
| MW            | GMLK-2_5G4L                 | [488a5022ca](https://bsd-hardware.info/?probe=488a5022ca) | May 12, 2023 |
| Dell          | 0HD5W2 A00                  | [5e5f24af1f](https://bsd-hardware.info/?probe=5e5f24af1f) | May 10, 2023 |
| MW            | GMLK-2_5G4L                 | [deb6e3ffa7](https://bsd-hardware.info/?probe=deb6e3ffa7) | May 10, 2023 |
| Unknown       | Unknown                     | [8b403d4350](https://bsd-hardware.info/?probe=8b403d4350) | May 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | [52110244c4](https://bsd-hardware.info/?probe=52110244c4) | May 07, 2023 |
| ASRock        | H110M-ITX                   | [5526aa67e8](https://bsd-hardware.info/?probe=5526aa67e8) | May 07, 2023 |
| Intel         | D54250WYK H13922-303        | [f9366e2ccc](https://bsd-hardware.info/?probe=f9366e2ccc) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [779f5f8827](https://bsd-hardware.info/?probe=779f5f8827) | Apr 30, 2023 |
| Intel         | D54250WYK H13922-303        | [4539fe8a93](https://bsd-hardware.info/?probe=4539fe8a93) | Apr 18, 2023 |
| ASUSTek       | P8H67-M EVO                 | [9d189f3b10](https://bsd-hardware.info/?probe=9d189f3b10) | Apr 18, 2023 |
| ASUSTek       | PRIME X299-A II             | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| CWWK          | CW-J6-6L                    | [b89912af4b](https://bsd-hardware.info/?probe=b89912af4b) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | [ab8a1de878](https://bsd-hardware.info/?probe=ab8a1de878) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | [d3756c5ab8](https://bsd-hardware.info/?probe=d3756c5ab8) | Apr 09, 2023 |
| HP            | 18E7                        | [b9e5e9a352](https://bsd-hardware.info/?probe=b9e5e9a352) | Apr 05, 2023 |
| Protectli     | VP4650                      | [685cfdf67f](https://bsd-hardware.info/?probe=685cfdf67f) | Apr 05, 2023 |
| Acer          | Aspire TC-780               | [9691b30e4d](https://bsd-hardware.info/?probe=9691b30e4d) | Apr 01, 2023 |
| ASRockRack    | X470D4U                     | [675bcfa82d](https://bsd-hardware.info/?probe=675bcfa82d) | Mar 29, 2023 |
| HP            | 2820h                       | [58d6933119](https://bsd-hardware.info/?probe=58d6933119) | Mar 26, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | [1ffbf45d40](https://bsd-hardware.info/?probe=1ffbf45d40) | Mar 19, 2023 |
| CNCTION-IA... | Unknown                     | [ba5de75eaa](https://bsd-hardware.info/?probe=ba5de75eaa) | Mar 19, 2023 |
| ASUSTek       | P6X58D-E                    | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Dell EMC      | VEP1425-V210-CPU A00        | [6faf4aed53](https://bsd-hardware.info/?probe=6faf4aed53) | Mar 11, 2023 |
| HP            | 3031h                       | [7324a71ceb](https://bsd-hardware.info/?probe=7324a71ceb) | Feb 23, 2023 |
| HP            | 3398                        | [186e63e8fe](https://bsd-hardware.info/?probe=186e63e8fe) | Feb 15, 2023 |
| Hardkernel    | ODROID-H2                   | [f63a5598d7](https://bsd-hardware.info/?probe=f63a5598d7) | Feb 14, 2023 |
| HP            | 3031h                       | [cbbf836268](https://bsd-hardware.info/?probe=cbbf836268) | Feb 13, 2023 |
| Dell          | 0WMJ54 A01                  | [e0eac39f4a](https://bsd-hardware.info/?probe=e0eac39f4a) | Feb 10, 2023 |
| Techvision    | TVI7309X B0                 | [a726812ab6](https://bsd-hardware.info/?probe=a726812ab6) | Feb 09, 2023 |
| Dell          | 0WMJ54 A01                  | [7d6cfe5543](https://bsd-hardware.info/?probe=7d6cfe5543) | Feb 04, 2023 |
| Gigabyte      | B150-HD3P-CF                | [fb5a559634](https://bsd-hardware.info/?probe=fb5a559634) | Feb 03, 2023 |
| PC Engines    | APU2                        | [2679b3584d](https://bsd-hardware.info/?probe=2679b3584d) | Jan 30, 2023 |
| CncTion       | J4125-4L-I225               | [65ee58e34e](https://bsd-hardware.info/?probe=65ee58e34e) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | [88e42156af](https://bsd-hardware.info/?probe=88e42156af) | Jan 28, 2023 |
| CNCTION-IA... | Unknown                     | [b639f4670e](https://bsd-hardware.info/?probe=b639f4670e) | Jan 27, 2023 |
| AAEON         | UP-APL01 V0.4               | [8537ac75a1](https://bsd-hardware.info/?probe=8537ac75a1) | Jan 26, 2023 |
| ASRock        | X299E-ITX/ac                | [0b7dacf902](https://bsd-hardware.info/?probe=0b7dacf902) | Jan 25, 2023 |
| Dell          | 0HD5W2 A00                  | [6b1a9b8d00](https://bsd-hardware.info/?probe=6b1a9b8d00) | Jan 21, 2023 |
| PC Engines    | APU2                        | [172844bd8b](https://bsd-hardware.info/?probe=172844bd8b) | Jan 21, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | [9805fe9459](https://bsd-hardware.info/?probe=9805fe9459) | Jan 13, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | [1ec6c3acf2](https://bsd-hardware.info/?probe=1ec6c3acf2) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| Shuttle       | FH110                       | [3759d77a05](https://bsd-hardware.info/?probe=3759d77a05) | Dec 29, 2022 |
| Advantech     | UNO-2483G-474AE             | [d453f64b4f](https://bsd-hardware.info/?probe=d453f64b4f) | Dec 29, 2022 |
| Shuttle       | FH110                       | [be457c2796](https://bsd-hardware.info/?probe=be457c2796) | Dec 27, 2022 |
| MW            | GMLK-2_5G4L                 | [8d3ab2cab5](https://bsd-hardware.info/?probe=8d3ab2cab5) | Dec 27, 2022 |
| Shuttle       | FH110                       | [a194756b95](https://bsd-hardware.info/?probe=a194756b95) | Dec 25, 2022 |
| ASUSTek       | PRIME H410M-A               | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Unknown       | Unknown                     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Lenovo        | MAHOBAY                     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Unknown       | Unknown                     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| HP            | 8719                        | [6bca1a0466](https://bsd-hardware.info/?probe=6bca1a0466) | Oct 22, 2022 |
| HP            | 8719                        | [87efb126fc](https://bsd-hardware.info/?probe=87efb126fc) | Oct 16, 2022 |
| NU941         | 1.0                         | [2690c2a8df](https://bsd-hardware.info/?probe=2690c2a8df) | Oct 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | [58def8d407](https://bsd-hardware.info/?probe=58def8d407) | Oct 03, 2022 |
| Unknown       | Unknown                     | [4e021d720f](https://bsd-hardware.info/?probe=4e021d720f) | Oct 02, 2022 |
| Unknown       | Unknown                     | [050c365fcd](https://bsd-hardware.info/?probe=050c365fcd) | Sep 17, 2022 |
| Dell          | 0R230R A00                  | [ad70ccea4d](https://bsd-hardware.info/?probe=ad70ccea4d) | Sep 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [13ec5a6f20](https://bsd-hardware.info/?probe=13ec5a6f20) | Sep 14, 2022 |
| Dell EMC      | VEP1425-V210-CPU A00        | [871a29677b](https://bsd-hardware.info/?probe=871a29677b) | Sep 12, 2022 |
| Intel         | Q3XXG4-P V1.0               | [88d8df1e3a](https://bsd-hardware.info/?probe=88d8df1e3a) | Sep 03, 2022 |
| MSI           | H410M-A PRO                 | [d71ca3999c](https://bsd-hardware.info/?probe=d71ca3999c) | Sep 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | [05bb23ae87](https://bsd-hardware.info/?probe=05bb23ae87) | Aug 26, 2022 |
| Dell          | PowerEdge R620              | [66db9eb745](https://bsd-hardware.info/?probe=66db9eb745) | Aug 25, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [5280e7a6d2](https://bsd-hardware.info/?probe=5280e7a6d2) | Aug 18, 2022 |
| Cisco         | ASA5512 A0                  | [9ac038fe9d](https://bsd-hardware.info/?probe=9ac038fe9d) | Aug 17, 2022 |
| PC Engines    | APU2                        | [beb01b4e9c](https://bsd-hardware.info/?probe=beb01b4e9c) | Aug 06, 2022 |
| HP            | 8266                        | [a204146221](https://bsd-hardware.info/?probe=a204146221) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Gigabyte      | H310M S2H                   | [03d0919731](https://bsd-hardware.info/?probe=03d0919731) | Jul 29, 2022 |
| Deciso        | Netboard A10                | [3f548f31e3](https://bsd-hardware.info/?probe=3f548f31e3) | Jul 25, 2022 |
| Intel         | Q3XXG4-P V1.0               | [6daa6d0060](https://bsd-hardware.info/?probe=6daa6d0060) | Jul 24, 2022 |
| Protectli     | FW4B                        | [b1ac4ad0dd](https://bsd-hardware.info/?probe=b1ac4ad0dd) | Jul 18, 2022 |
| Pegatron      | 2AB5                        | [d48d3e4777](https://bsd-hardware.info/?probe=d48d3e4777) | Jul 05, 2022 |
| Protectli     | FW4B                        | [c4e6db8739](https://bsd-hardware.info/?probe=c4e6db8739) | Jul 03, 2022 |
| ASRock        | X300M-STX                   | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| ASRock        | Z77 Pro4-M                  | [4be827d8fe](https://bsd-hardware.info/?probe=4be827d8fe) | Jun 01, 2022 |
| MW            | GMLK-2_5G4L                 | [5893942a80](https://bsd-hardware.info/?probe=5893942a80) | May 30, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Pegatron      | 2AB5                        | [5cc0eb3e94](https://bsd-hardware.info/?probe=5cc0eb3e94) | May 11, 2022 |
| Unknown       | Unknown                     | [66432302a4](https://bsd-hardware.info/?probe=66432302a4) | May 07, 2022 |
| PC Engines    | APU2                        | [26be7dfcb8](https://bsd-hardware.info/?probe=26be7dfcb8) | Apr 28, 2022 |
| PC Engines    | APU2                        | [4405a65be4](https://bsd-hardware.info/?probe=4405a65be4) | Apr 28, 2022 |
| PC Engines    | APU2                        | [3fe99889aa](https://bsd-hardware.info/?probe=3fe99889aa) | Apr 26, 2022 |
| Unknown       | Unknown                     | [095a279c7b](https://bsd-hardware.info/?probe=095a279c7b) | Apr 25, 2022 |
| Gigabyte      | X570 AORUS PRO              | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| HP            | 1998                        | [4f15447536](https://bsd-hardware.info/?probe=4f15447536) | Apr 18, 2022 |
| Unknown       | Unknown                     | [f58e088df2](https://bsd-hardware.info/?probe=f58e088df2) | Apr 16, 2022 |
| Protectli     | FW6D                        | [e79304e1dc](https://bsd-hardware.info/?probe=e79304e1dc) | Apr 07, 2022 |
| Gigabyte      | B560M D3H                   | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASRock        | H61DE/S3                    | [00183a69ec](https://bsd-hardware.info/?probe=00183a69ec) | Apr 05, 2022 |
| Biostar       | H61MGV3                     | [1ef10e5e36](https://bsd-hardware.info/?probe=1ef10e5e36) | Apr 03, 2022 |
| PC Engines    | apu4                        | [618b2c7955](https://bsd-hardware.info/?probe=618b2c7955) | Mar 27, 2022 |
| Hardkernel    | ODROID-H2                   | [a1700b0347](https://bsd-hardware.info/?probe=a1700b0347) | Mar 21, 2022 |
| Deciso        | Netboard A10 V2.1           | [671c66ca19](https://bsd-hardware.info/?probe=671c66ca19) | Mar 21, 2022 |
| Protectli     | FW4B                        | [5323027ba0](https://bsd-hardware.info/?probe=5323027ba0) | Mar 13, 2022 |
| Gigabyte      | J1900N-D3V                  | [ec336ddab4](https://bsd-hardware.info/?probe=ec336ddab4) | Mar 08, 2022 |
| Unknown       | Unknown                     | [c91c5fe588](https://bsd-hardware.info/?probe=c91c5fe588) | Mar 03, 2022 |
| Supermicro    | M11SDV-8C-LN4F              | [e4f7f31828](https://bsd-hardware.info/?probe=e4f7f31828) | Feb 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | [74f28d34fd](https://bsd-hardware.info/?probe=74f28d34fd) | Feb 27, 2022 |
| Dell          | 0R230R A00                  | [f3444924fd](https://bsd-hardware.info/?probe=f3444924fd) | Feb 17, 2022 |
| Dell          | 0R230R A00                  | [91870de9fe](https://bsd-hardware.info/?probe=91870de9fe) | Feb 06, 2022 |
| MSI           | H81I                        | [fe3a834f0b](https://bsd-hardware.info/?probe=fe3a834f0b) | Feb 05, 2022 |
| MW            | GMLK-2_5G4L                 | [f785bcb17a](https://bsd-hardware.info/?probe=f785bcb17a) | Feb 04, 2022 |
| MW            | GMLK-2_5G4L                 | [96436a1882](https://bsd-hardware.info/?probe=96436a1882) | Feb 03, 2022 |
| Dell          | 0R230R A00                  | [cb50949dca](https://bsd-hardware.info/?probe=cb50949dca) | Jan 28, 2022 |
| ASUSTek       | PRIME H410M-A               | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | [04afa3aa4f](https://bsd-hardware.info/?probe=04afa3aa4f) | Jan 23, 2022 |
| ASUSTek       | PRIME H410M-A               | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| MSI           | H61I-E35 V2/W8              | [8ae05f9d72](https://bsd-hardware.info/?probe=8ae05f9d72) | Jan 05, 2022 |
| XtReAmEr      | Unknown                     | [bd1315aa70](https://bsd-hardware.info/?probe=bd1315aa70) | Jan 04, 2022 |
| Unknown       | Unknown                     | [0efa2c0531](https://bsd-hardware.info/?probe=0efa2c0531) | Dec 31, 2021 |
| Unknown       | Unknown                     | [79370c33df](https://bsd-hardware.info/?probe=79370c33df) | Dec 28, 2021 |
| Unknown       | Unknown                     | [c5e31aaf52](https://bsd-hardware.info/?probe=c5e31aaf52) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | [30aab74fbc](https://bsd-hardware.info/?probe=30aab74fbc) | Dec 24, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [69bf80f0c6](https://bsd-hardware.info/?probe=69bf80f0c6) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | [ef0dcfaccf](https://bsd-hardware.info/?probe=ef0dcfaccf) | Dec 20, 2021 |
| Gigabyte      | X570 AORUS PRO              | [17cad87a0d](https://bsd-hardware.info/?probe=17cad87a0d) | Dec 19, 2021 |
| PC Engines    | apu4                        | [f72343bec1](https://bsd-hardware.info/?probe=f72343bec1) | Dec 19, 2021 |
| Unknown       | Unknown                     | [cd27dd3e2b](https://bsd-hardware.info/?probe=cd27dd3e2b) | Dec 17, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fd05f5bf41](https://bsd-hardware.info/?probe=fd05f5bf41) | Dec 11, 2021 |
| HP            | 8105                        | [e38c91e91e](https://bsd-hardware.info/?probe=e38c91e91e) | Dec 11, 2021 |
| HP            | 8105                        | [0b923d55bc](https://bsd-hardware.info/?probe=0b923d55bc) | Dec 11, 2021 |
| Protectli     | FW6D                        | [33731d5933](https://bsd-hardware.info/?probe=33731d5933) | Dec 11, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [5dbff17614](https://bsd-hardware.info/?probe=5dbff17614) | Dec 06, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | [646ca92a69](https://bsd-hardware.info/?probe=646ca92a69) | Dec 06, 2021 |
| Alienware     | 01NYPT A00                  | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| Lenovo        | MAHOBAY                     | [b77016bee5](https://bsd-hardware.info/?probe=b77016bee5) | Nov 25, 2021 |
| ASRock        | IMB-195                     | [58e7426808](https://bsd-hardware.info/?probe=58e7426808) | Nov 24, 2021 |
| HP            | 339A                        | [a123d76249](https://bsd-hardware.info/?probe=a123d76249) | Nov 19, 2021 |
| HP            | 1497                        | [24a8d1bb7a](https://bsd-hardware.info/?probe=24a8d1bb7a) | Nov 17, 2021 |
| PC Engines    | APU                         | [ca05f41685](https://bsd-hardware.info/?probe=ca05f41685) | Nov 16, 2021 |
| Dell          | 0R230R A00                  | [c2c6cf4b4d](https://bsd-hardware.info/?probe=c2c6cf4b4d) | Nov 16, 2021 |
| Unknown       | Unknown                     | [c473c704a9](https://bsd-hardware.info/?probe=c473c704a9) | Nov 14, 2021 |
| Unknown       | Unknown                     | [ec7dfabb51](https://bsd-hardware.info/?probe=ec7dfabb51) | Nov 12, 2021 |
| Protectli     | FW4B                        | [cb7b87cd57](https://bsd-hardware.info/?probe=cb7b87cd57) | Nov 09, 2021 |
| Unknown       | Unknown                     | [f80c884b6f](https://bsd-hardware.info/?probe=f80c884b6f) | Oct 31, 2021 |
| Gigabyte      | J1900N-D3V                  | [e4958e59b0](https://bsd-hardware.info/?probe=e4958e59b0) | Oct 29, 2021 |
| Unknown       | YL-J3160L4                  | [bc4b7f33d5](https://bsd-hardware.info/?probe=bc4b7f33d5) | Oct 25, 2021 |
| Supermicro    | M11SDV-8C-LN4F              | [54c792ac8a](https://bsd-hardware.info/?probe=54c792ac8a) | Oct 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [67e62d9dd3](https://bsd-hardware.info/?probe=67e62d9dd3) | Oct 11, 2021 |
| Unknown       | Unknown                     | [b3b0308132](https://bsd-hardware.info/?probe=b3b0308132) | Oct 02, 2021 |
| Intel         | CRESCENTBAY                 | [712bbd0635](https://bsd-hardware.info/?probe=712bbd0635) | Sep 29, 2021 |
| Protectli     | FW6D                        | [ee70d4b2fe](https://bsd-hardware.info/?probe=ee70d4b2fe) | Sep 25, 2021 |
| MSI           | H61I-E35 V2/W8              | [359cb66936](https://bsd-hardware.info/?probe=359cb66936) | Sep 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1afa203e69](https://bsd-hardware.info/?probe=1afa203e69) | Sep 22, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Shuttle       | XH310V2                     | [f37b485384](https://bsd-hardware.info/?probe=f37b485384) | Sep 19, 2021 |
| Unknown       | Unknown                     | [ba40cc9f75](https://bsd-hardware.info/?probe=ba40cc9f75) | Sep 17, 2021 |
| Intel         | SHARKBAY                    | [70d35afae8](https://bsd-hardware.info/?probe=70d35afae8) | Sep 15, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | [0510213747](https://bsd-hardware.info/?probe=0510213747) | Aug 30, 2021 |
| Unknown       | YL-J3160L4                  | [b3a20bafca](https://bsd-hardware.info/?probe=b3a20bafca) | Aug 29, 2021 |
| Unknown       | YL-J3160L4                  | [03e08762a6](https://bsd-hardware.info/?probe=03e08762a6) | Aug 27, 2021 |
| Shuttle       | DH370                       | [dea088a5bd](https://bsd-hardware.info/?probe=dea088a5bd) | Aug 20, 2021 |
| Protectli     | FW4B                        | [ab6695bb0b](https://bsd-hardware.info/?probe=ab6695bb0b) | Aug 18, 2021 |
| HP            | 213D A01                    | [6e52020062](https://bsd-hardware.info/?probe=6e52020062) | Aug 10, 2021 |
| Shuttle       | DH370                       | [6d81fef4fb](https://bsd-hardware.info/?probe=6d81fef4fb) | Aug 09, 2021 |
| Unknown       | Unknown                     | [164b888dbe](https://bsd-hardware.info/?probe=164b888dbe) | Aug 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [a6de85de91](https://bsd-hardware.info/?probe=a6de85de91) | Jul 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1e337fe131](https://bsd-hardware.info/?probe=1e337fe131) | Jul 29, 2021 |
| Unknown       | Unknown                     | [dd66bc21f6](https://bsd-hardware.info/?probe=dd66bc21f6) | Jul 27, 2021 |
| Unknown       | Unknown                     | [b7edcfabb6](https://bsd-hardware.info/?probe=b7edcfabb6) | Jul 25, 2021 |
| PC Engines    | apu4                        | [027bbc5028](https://bsd-hardware.info/?probe=027bbc5028) | Jul 14, 2021 |
| HP            | 18E9                        | [7bac3be335](https://bsd-hardware.info/?probe=7bac3be335) | Jun 29, 2021 |
| Dell EMC      | VEP1425-V210-CPU A00        | [ad34d48259](https://bsd-hardware.info/?probe=ad34d48259) | Jun 27, 2021 |
| Dell          | 0WR7PY A02                  | [ad5db0563f](https://bsd-hardware.info/?probe=ad5db0563f) | Jun 26, 2021 |
| Intel         | Q3XXG4-P V1.0               | [ee8a47b051](https://bsd-hardware.info/?probe=ee8a47b051) | Jun 17, 2021 |
| HP            | 3397                        | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| MSI           | B85M-P33 V2                 | [0633d1c78e](https://bsd-hardware.info/?probe=0633d1c78e) | Jun 10, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [db12a78352](https://bsd-hardware.info/?probe=db12a78352) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| Inventec      | R CLASS A02                 | [b621aeaac3](https://bsd-hardware.info/?probe=b621aeaac3) | May 30, 2021 |
| Gigabyte      | B85-HD3                     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| Dell          | 0200DY A02                  | [fcbfbc2dfa](https://bsd-hardware.info/?probe=fcbfbc2dfa) | May 25, 2021 |
| Unknown       | YL-J3160L4                  | [8448df79cd](https://bsd-hardware.info/?probe=8448df79cd) | May 21, 2021 |
| Unknown       | YL-J3160L4                  | [594c0438a0](https://bsd-hardware.info/?probe=594c0438a0) | May 21, 2021 |
| Shuttle       | FH87                        | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| Dell          | 0FJ030                      | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [d5277ad9e1](https://bsd-hardware.info/?probe=d5277ad9e1) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [63b1980830](https://bsd-hardware.info/?probe=63b1980830) | Apr 30, 2021 |
| HP            | 1998                        | [f6b53096d4](https://bsd-hardware.info/?probe=f6b53096d4) | Apr 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | [a90eea4001](https://bsd-hardware.info/?probe=a90eea4001) | Apr 27, 2021 |
| HP            | 1497                        | [26724735db](https://bsd-hardware.info/?probe=26724735db) | Apr 24, 2021 |
| HP            | 1998                        | [051c63e153](https://bsd-hardware.info/?probe=051c63e153) | Apr 24, 2021 |
| ASRock        | J4105-ITX                   | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| HP            | 1998                        | [7207f742d6](https://bsd-hardware.info/?probe=7207f742d6) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [634521b082](https://bsd-hardware.info/?probe=634521b082) | Apr 07, 2021 |
| Unknown       | Unknown                     | [15e5f7932e](https://bsd-hardware.info/?probe=15e5f7932e) | Apr 06, 2021 |
| PC Engines    | apu4                        | [06a59860a8](https://bsd-hardware.info/?probe=06a59860a8) | Apr 04, 2021 |
| Dell          | 0200DY A02                  | [060ebba6d2](https://bsd-hardware.info/?probe=060ebba6d2) | Mar 30, 2021 |
| MSI           | H410M-A PRO                 | [88f2766975](https://bsd-hardware.info/?probe=88f2766975) | Mar 27, 2021 |
| Shuttle       | FS310                       | [6514807d96](https://bsd-hardware.info/?probe=6514807d96) | Mar 25, 2021 |
| ASRock        | Z77 Pro4-M                  | [b8f568202d](https://bsd-hardware.info/?probe=b8f568202d) | Mar 22, 2021 |
| HP            | ProLiant DL360 Gen9         | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| iEi           | E452 V1.00                  | [b5665d0df2](https://bsd-hardware.info/?probe=b5665d0df2) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | [6e0891ce80](https://bsd-hardware.info/?probe=6e0891ce80) | Mar 17, 2021 |
| ASRock        | Z490M-ITX/ac                | [ee59c99fe4](https://bsd-hardware.info/?probe=ee59c99fe4) | Mar 15, 2021 |
| Unknown       | YL-J3160L4                  | [359c03f28d](https://bsd-hardware.info/?probe=359c03f28d) | Mar 12, 2021 |
| HP            | 18E9                        | [cc435f4cd1](https://bsd-hardware.info/?probe=cc435f4cd1) | Mar 10, 2021 |
| Unknown       | Unknown                     | [2093895427](https://bsd-hardware.info/?probe=2093895427) | Mar 10, 2021 |
| Pegatron      | 2AB5                        | [f30a9505dd](https://bsd-hardware.info/?probe=f30a9505dd) | Mar 07, 2021 |
| Unknown       | Unknown                     | [2abc226441](https://bsd-hardware.info/?probe=2abc226441) | Mar 05, 2021 |
| Unknown       | Unknown                     | [60e0b1d346](https://bsd-hardware.info/?probe=60e0b1d346) | Mar 04, 2021 |
| Unknown       | Unknown                     | [db37dfcbf3](https://bsd-hardware.info/?probe=db37dfcbf3) | Mar 02, 2021 |
| MSI           | H410M-A PRO                 | [64bf9eb4cf](https://bsd-hardware.info/?probe=64bf9eb4cf) | Mar 01, 2021 |
| MSI           | H410M-A PRO                 | [eacaff1fff](https://bsd-hardware.info/?probe=eacaff1fff) | Feb 28, 2021 |
| Unknown       | YL-J3160L4                  | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| ASRock        | Z490M-ITX/ac                | [9901302790](https://bsd-hardware.info/?probe=9901302790) | Feb 27, 2021 |
| Dell          | 00V62H A00                  | [441133db7f](https://bsd-hardware.info/?probe=441133db7f) | Feb 24, 2021 |
| Unknown       | Unknown                     | [1008505c8a](https://bsd-hardware.info/?probe=1008505c8a) | Feb 23, 2021 |
| MSI           | H410M-A PRO                 | [7d9e05b2fd](https://bsd-hardware.info/?probe=7d9e05b2fd) | Feb 21, 2021 |
| MSI           | H410M-A PRO                 | [408ba48f1f](https://bsd-hardware.info/?probe=408ba48f1f) | Feb 21, 2021 |
| Unknown       | Unknown                     | [6c0a1e1154](https://bsd-hardware.info/?probe=6c0a1e1154) | Feb 20, 2021 |
| Supermicro    | X8SIL                       | [6318953f01](https://bsd-hardware.info/?probe=6318953f01) | Feb 18, 2021 |
| Supermicro    | X9SCL/X9SCM                 | [a57dba0cb2](https://bsd-hardware.info/?probe=a57dba0cb2) | Feb 16, 2021 |
| Dell          | 0T7D40 A01                  | [301fc86371](https://bsd-hardware.info/?probe=301fc86371) | Feb 15, 2021 |
| Protectli     | FW2B Ver                    | [57ca4c3cac](https://bsd-hardware.info/?probe=57ca4c3cac) | Feb 15, 2021 |
| Unknown       | Unknown                     | [994b94b7f5](https://bsd-hardware.info/?probe=994b94b7f5) | Feb 13, 2021 |
| ASUSTek       | P5Q-PRO                     | [9ff4167171](https://bsd-hardware.info/?probe=9ff4167171) | Feb 12, 2021 |
| PC Engines    | apu4                        | [67e0b30093](https://bsd-hardware.info/?probe=67e0b30093) | Feb 05, 2021 |
| PC Engines    | apu4                        | [d4b1d0ae99](https://bsd-hardware.info/?probe=d4b1d0ae99) | Feb 03, 2021 |
| PC Engines    | APU                         | [91da54ca8c](https://bsd-hardware.info/?probe=91da54ca8c) | Feb 02, 2021 |
| Dell          | 0T7D40 A01                  | [1f5bf7092c](https://bsd-hardware.info/?probe=1f5bf7092c) | Feb 01, 2021 |
| Inventec      | VXC Class A02               | [22d0861af3](https://bsd-hardware.info/?probe=22d0861af3) | Jan 29, 2021 |
| Unknown       | Unknown                     | [f4b460a5e4](https://bsd-hardware.info/?probe=f4b460a5e4) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | [8c298fa5bf](https://bsd-hardware.info/?probe=8c298fa5bf) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | [6127d635de](https://bsd-hardware.info/?probe=6127d635de) | Jan 27, 2021 |
| Unknown       | Unknown                     | [f76df86f03](https://bsd-hardware.info/?probe=f76df86f03) | Jan 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | [881d50fc9e](https://bsd-hardware.info/?probe=881d50fc9e) | Jan 26, 2021 |
| ASRock        | Z490M-ITX/ac                | [97fd3d11e8](https://bsd-hardware.info/?probe=97fd3d11e8) | Jan 25, 2021 |
| ASRock        | Z490M-ITX/ac                | [2577292fe1](https://bsd-hardware.info/?probe=2577292fe1) | Jan 25, 2021 |
| Inventec      | R CLASS A02                 | [545854fcfd](https://bsd-hardware.info/?probe=545854fcfd) | Jan 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5b00abed29](https://bsd-hardware.info/?probe=5b00abed29) | Jan 23, 2021 |
| Intel         | CRESCENTBAY                 | [f8e3f072fc](https://bsd-hardware.info/?probe=f8e3f072fc) | Jan 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | [3c0683ff11](https://bsd-hardware.info/?probe=3c0683ff11) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5d556cc47f](https://bsd-hardware.info/?probe=5d556cc47f) | Jan 22, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [4b2e64662e](https://bsd-hardware.info/?probe=4b2e64662e) | Jan 21, 2021 |
| Unknown       | Unknown                     | [951a898a3f](https://bsd-hardware.info/?probe=951a898a3f) | Jan 21, 2021 |
| Unknown       | Unknown                     | [a1b0841493](https://bsd-hardware.info/?probe=a1b0841493) | Jan 21, 2021 |
| ASRock        | Z77 Pro4-M                  | [064e82b131](https://bsd-hardware.info/?probe=064e82b131) | Jan 21, 2021 |
| ASRockRack    | EPC612D4U-8R                | [617694f591](https://bsd-hardware.info/?probe=617694f591) | Dec 19, 2020 |
| ASRock        | B360 Pro4                   | [05d3ab8d4b](https://bsd-hardware.info/?probe=05d3ab8d4b) | Oct 29, 2020 |
| ASUSTek       | H110I-PLUS                  | [57ecc0c410](https://bsd-hardware.info/?probe=57ecc0c410) | Oct 29, 2020 |
| HPE           | ProLiant MicroServer Gen... | [3cebf4d7db](https://bsd-hardware.info/?probe=3cebf4d7db) | Oct 29, 2020 |
| ASRockRack    | EPC612D4U-8R                | [b9ecd0e2b3](https://bsd-hardware.info/?probe=b9ecd0e2b3) | Oct 29, 2020 |
| Dell          | Precision WorkStation T7... | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| Gigabyte      | Z97-D3H-CF                  | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Dell          | PowerEdge R620              | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| Gigabyte      | MQLP7AP-00                  | [07036eab43](https://bsd-hardware.info/?probe=07036eab43) | May 28, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | [85bebeaea0](https://bsd-hardware.info/?probe=85bebeaea0) | May 25, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | [9fea968a19](https://bsd-hardware.info/?probe=9fea968a19) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| OPNsense 23.1.11 | 13       | 4.35%   |
| OPNsense 23.7.9  | 10       | 3.34%   |
| OPNsense 23.1.7  | 10       | 3.34%   |
| OPNsense 23.1    | 9        | 3.01%   |
| OPNsense 23.1.5  | 8        | 2.68%   |
| OPNsense 21.7.7  | 8        | 2.68%   |
| OPNsense 23.7.10 | 7        | 2.34%   |
| OPNsense 21.1.1  | 7        | 2.34%   |
| OPNsense 20.7.8  | 7        | 2.34%   |
| OPNsense 23.7.7  | 6        | 2.01%   |
| OPNsense 21.7.5  | 6        | 2.01%   |
| OPNsense 21.7.3  | 6        | 2.01%   |
| OPNsense 21.7.2  | 6        | 2.01%   |
| OPNsense 21.7.1  | 6        | 2.01%   |
| OPNsense 21.1.2  | 6        | 2.01%   |
| OPNsense 23.7.11 | 5        | 1.67%   |
| OPNsense 23.1.9  | 5        | 1.67%   |
| OPNsense 22.7.4  | 5        | 1.67%   |
| OPNsense 22.1.6  | 5        | 1.67%   |
| OPNsense 21.1.7  | 5        | 1.67%   |
| OPNsense 21.1.3  | 5        | 1.67%   |
| OPNsense 21.1    | 5        | 1.67%   |
| OpenBSD 6.8      | 5        | 1.67%   |
| FreeBSD 13.0     | 5        | 1.67%   |
| OPNsense 23.7.2  | 4        | 1.34%   |
| OPNsense 23.7.1  | 4        | 1.34%   |
| OPNsense 22.1.4  | 4        | 1.34%   |
| OPNsense 22.1.10 | 4        | 1.34%   |
| OPNsense 21.1.5  | 4        | 1.34%   |
| OpenBSD 7.1      | 4        | 1.34%   |
| OPNsense 23.7.3  | 3        | 1%      |
| OPNsense 23.1.10 | 3        | 1%      |
| OPNsense 22.7.2  | 3        | 1%      |
| OPNsense 22.7.11 | 3        | 1%      |
| OPNsense 22.7.10 | 3        | 1%      |
| OPNsense 22.7    | 3        | 1%      |
| OPNsense 22.1.1  | 3        | 1%      |
| OPNsense 22.1    | 3        | 1%      |
| OPNsense 21.7.8  | 3        | 1%      |
| OPNsense 21.7.6  | 3        | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 156      | 74.29%  |
| FreeBSD     | 27       | 12.86%  |
| OpenBSD     | 12       | 5.71%   |
| helloSystem | 8        | 3.81%   |
| NomadBSD    | 2        | 0.95%   |
| GhostBSD    | 2        | 0.95%   |
| pfSense     | 1        | 0.48%   |
| NetBSD      | 1        | 0.48%   |
| HardenedBSD | 1        | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 199      | 96.6%   |
| arm64 | 6        | 2.91%   |
| i386  | 1        | 0.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 179      | 85.24%  |
| helloDesktop | 14       | 6.67%   |
| KDE5         | 5        | 2.38%   |
| XFCE         | 2        | 0.95%   |
| GNOME        | 2        | 0.95%   |
| fvwm         | 2        | 0.95%   |
| xinitrc      | 1        | 0.48%   |
| Openbox      | 1        | 0.48%   |
| MATE         | 1        | 0.48%   |
| LXQt         | 1        | 0.48%   |
| i3           | 1        | 0.48%   |
| Fluxbox      | 1        | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 183      | 88.83%  |
| X11     | 22       | 10.68%  |
| Wayland | 1        | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 185      | 88.94%  |
| SLiM    | 9        | 4.33%   |
| SDDM    | 6        | 2.88%   |
| LightDM | 4        | 1.92%   |
| XDM     | 2        | 0.96%   |
| GDM     | 2        | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 169      | 79.72%  |
| C       | 21       | 9.91%   |
| en_US   | 17       | 8.02%   |
| nl_NL   | 2        | 0.94%   |
| fr_FR   | 2        | 0.94%   |
| de_DE   | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 178      | 85.99%  |
| BIOS | 29       | 14.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 116      | 53.21%  |
| Zfs    | 87       | 39.91%  |
| Ffs    | 12       | 5.5%    |
| Cd9660 | 3        | 1.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 186      | 89.86%  |
| MBR     | 19       | 9.18%   |
| Unknown | 2        | 0.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 30       | 14.56%  |
| Dell                | 24       | 11.65%  |
| Hewlett-Packard     | 21       | 10.19%  |
| Intel               | 15       | 7.28%   |
| ASRock              | 14       | 6.8%    |
| Gigabyte Technology | 12       | 5.83%   |
| ASUSTek Computer    | 11       | 5.34%   |
| PC Engines          | 9        | 4.37%   |
| Protectli           | 7        | 3.4%    |
| Supermicro          | 5        | 2.43%   |
| Shuttle             | 5        | 2.43%   |
| Techvision          | 4        | 1.94%   |
| MSI                 | 4        | 1.94%   |
| Lenovo              | 4        | 1.94%   |
| Fujitsu             | 4        | 1.94%   |
| MW                  | 3        | 1.46%   |
| Inventec            | 3        | 1.46%   |
| Deciso              | 3        | 1.46%   |
| ASRockRack          | 3        | 1.46%   |
| Hardkernel          | 2        | 0.97%   |
| CncTion             | 2        | 0.97%   |
| Advantech           | 2        | 0.97%   |
| AAEON               | 2        | 0.97%   |
| XtReAmEr            | 1        | 0.49%   |
| SolidRun            | 1        | 0.49%   |
| Sapphire            | 1        | 0.49%   |
| Pegatron            | 1        | 0.49%   |
| NU941               | 1        | 0.49%   |
| JHZD                | 1        | 0.49%   |
| iEi                 | 1        | 0.49%   |
| IceWhale Technology | 1        | 0.49%   |
| HPE                 | 1        | 0.49%   |
| Dell EMC            | 1        | 0.49%   |
| CWWK                | 1        | 0.49%   |
| CNCTION-IAF         | 1        | 0.49%   |
| Cisco               | 1        | 0.49%   |
| Biostar             | 1        | 0.49%   |
| AMI                 | 1        | 0.49%   |
| Alienware           | 1        | 0.49%   |
| Acer                | 1        | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 31       | 15.05%  |
| Intel Q3XXG4-P V1.0               | 11       | 5.34%   |
| Dell PowerEdge R620               | 5        | 2.43%   |
| Techvision TVI7309X               | 4        | 1.94%   |
| PC Engines APU2                   | 4        | 1.94%   |
| PC Engines apu4                   | 3        | 1.46%   |
| MW GMLK-2_5G4L                    | 3        | 1.46%   |
| Fujitsu FUTRO S920                | 3        | 1.46%   |
| Dell OptiPlex 7040                | 3        | 1.46%   |
| PC Engines APU                    | 2        | 0.97%   |
| Inventec VXC Class                | 2        | 0.97%   |
| HP ProDesk 400 G2.5 SFF           | 2        | 0.97%   |
| HP EliteDesk 800 G1 SFF           | 2        | 0.97%   |
| Gigabyte X570 AORUS PRO           | 2        | 0.97%   |
| Dell OptiPlex 7050                | 2        | 0.97%   |
| Dell OptiPlex 390                 | 2        | 0.97%   |
| Dell OptiPlex 3050                | 2        | 0.97%   |
| ASRockRack X470D4U                | 2        | 0.97%   |
| Supermicro X9SCL/X9SCM            | 1        | 0.49%   |
| Supermicro X8SIL                  | 1        | 0.49%   |
| Supermicro X7SLA                  | 1        | 0.49%   |
| Supermicro AS -E301-9D-8CN4       | 1        | 0.49%   |
| Supermicro AS -5019D-FTN4         | 1        | 0.49%   |
| SolidRun CEX7 Platform            | 1        | 0.49%   |
| Shuttle XH310V2                   | 1        | 0.49%   |
| Shuttle XH110                     | 1        | 0.49%   |
| Shuttle SH87R                     | 1        | 0.49%   |
| Shuttle DH370                     | 1        | 0.49%   |
| Shuttle DH310                     | 1        | 0.49%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044 | 1        | 0.49%   |
| Protectli VP46xx                  | 1        | 0.49%   |
| Protectli VP4650                  | 1        | 0.49%   |
| Protectli FW6D                    | 1        | 0.49%   |
| Protectli FW6                     | 1        | 0.49%   |
| Protectli FW4C                    | 1        | 0.49%   |
| Protectli FW4B                    | 1        | 0.49%   |
| Protectli FW2B                    | 1        | 0.49%   |
| Pegatron h8-1102nl                | 1        | 0.49%   |
| NU941 1.0                         | 1        | 0.49%   |
| MSI MS-7C89                       | 1        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 31       | 15.05%  |
| Dell OptiPlex       | 17       | 8.25%   |
| Intel Q3XXG4-P      | 11       | 5.34%   |
| HP ProDesk          | 8        | 3.88%   |
| HP Compaq           | 5        | 2.43%   |
| Dell PowerEdge      | 5        | 2.43%   |
| ASUS PRIME          | 5        | 2.43%   |
| Techvision TVI7309X | 4        | 1.94%   |
| PC Engines APU2     | 4        | 1.94%   |
| HP EliteDesk        | 4        | 1.94%   |
| PC Engines apu4     | 3        | 1.46%   |
| MW GMLK-2           | 3        | 1.46%   |
| Fujitsu FUTRO       | 3        | 1.46%   |
| Deciso Netboard     | 3        | 1.46%   |
| Supermicro AS       | 2        | 0.97%   |
| PC Engines APU      | 2        | 0.97%   |
| Inventec VXC        | 2        | 0.97%   |
| HP ProLiant         | 2        | 0.97%   |
| Gigabyte X570       | 2        | 0.97%   |
| ASRockRack X470D4U  | 2        | 0.97%   |
| Supermicro X9SCL    | 1        | 0.49%   |
| Supermicro X8SIL    | 1        | 0.49%   |
| Supermicro X7SLA    | 1        | 0.49%   |
| SolidRun CEX7       | 1        | 0.49%   |
| Shuttle XH310V2     | 1        | 0.49%   |
| Shuttle XH110       | 1        | 0.49%   |
| Shuttle SH87R       | 1        | 0.49%   |
| Shuttle DH370       | 1        | 0.49%   |
| Shuttle DH310       | 1        | 0.49%   |
| Sapphire EDGE-FT1M1 | 1        | 0.49%   |
| Protectli VP46xx    | 1        | 0.49%   |
| Protectli VP4650    | 1        | 0.49%   |
| Protectli FW6D      | 1        | 0.49%   |
| Protectli FW6       | 1        | 0.49%   |
| Protectli FW4C      | 1        | 0.49%   |
| Protectli FW4B      | 1        | 0.49%   |
| Protectli FW2B      | 1        | 0.49%   |
| Pegatron h8-1102nl  | 1        | 0.49%   |
| NU941 1.0           | 1        | 0.49%   |
| MSI MS-7C89         | 1        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 26       | 12.62%  |
| 2018    | 24       | 11.65%  |
| 2022    | 18       | 8.74%   |
| 2020    | 18       | 8.74%   |
| 2019    | 16       | 7.77%   |
| 2014    | 16       | 7.77%   |
| 2021    | 13       | 6.31%   |
| 2013    | 11       | 5.34%   |
| 2011    | 11       | 5.34%   |
| 2023    | 10       | 4.85%   |
| 2017    | 10       | 4.85%   |
| 2015    | 9        | 4.37%   |
| 2012    | 5        | 2.43%   |
| 2009    | 5        | 2.43%   |
| 2008    | 5        | 2.43%   |
| Unknown | 5        | 2.43%   |
| 2010    | 3        | 1.46%   |
| 2006    | 1        | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 206      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 192      | 93.2%   |
| Yes  | 14       | 6.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 75       | 35.55%  |
| 16.01-24.0      | 50       | 23.7%   |
| 4.01-8.0        | 39       | 18.48%  |
| 32.01-64.0      | 19       | 9%      |
| 64.01-256.0     | 10       | 4.74%   |
| 2.01-3.0        | 7        | 3.32%   |
| 3.01-4.0        | 3        | 1.42%   |
| More than 256.0 | 2        | 0.95%   |
| 24.01-32.0      | 2        | 0.95%   |
| 1.01-2.0        | 2        | 0.95%   |
| 0.51-1.0        | 2        | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 105      | 49.07%  |
| 0.51-1.0   | 70       | 32.71%  |
| 1.01-2.0   | 17       | 7.94%   |
| 4.01-8.0   | 7        | 3.27%   |
| 2.01-3.0   | 5        | 2.34%   |
| 8.01-16.0  | 4        | 1.87%   |
| 3.01-4.0   | 2        | 0.93%   |
| 32.01-64.0 | 1        | 0.47%   |
| 24.01-32.0 | 1        | 0.47%   |
| 0          | 1        | 0.47%   |
| Unknown    | 1        | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 151      | 71.56%  |
| 2      | 24       | 11.37%  |
| 0      | 12       | 5.69%   |
| 3      | 7        | 3.32%   |
| 4      | 6        | 2.84%   |
| 5      | 4        | 1.9%    |
| 7      | 2        | 0.95%   |
| 17     | 1        | 0.47%   |
| 15     | 1        | 0.47%   |
| 12     | 1        | 0.47%   |
| 10     | 1        | 0.47%   |
| 6      | 1        | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 183      | 88.41%  |
| Yes       | 24       | 11.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 201      | 97.1%   |
| No        | 6        | 2.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 84.13%  |
| Yes       | 33       | 15.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 91.35%  |
| Yes       | 18       | 8.65%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Netherlands | 206      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Amsterdam           | 34       | 13.77%  |
| Rotterdam           | 8        | 3.24%   |
| Zeist               | 4        | 1.62%   |
| The Hague           | 4        | 1.62%   |
| Poortugaal          | 4        | 1.62%   |
| Hoofddorp           | 4        | 1.62%   |
| Zaandam             | 3        | 1.21%   |
| Veenendaal          | 3        | 1.21%   |
| Utrecht             | 3        | 1.21%   |
| Ospel               | 3        | 1.21%   |
| Maastricht          | 3        | 1.21%   |
| Hengelo             | 3        | 1.21%   |
| Heerlen             | 3        | 1.21%   |
| Heemskerk           | 3        | 1.21%   |
| Groningen           | 3        | 1.21%   |
| Breda               | 3        | 1.21%   |
| Barneveld           | 3        | 1.21%   |
| Amersfoort          | 3        | 1.21%   |
| Almere Stad         | 3        | 1.21%   |
| Vlaardingen         | 2        | 0.81%   |
| Valkenswaard        | 2        | 0.81%   |
| Tilburg             | 2        | 0.81%   |
| Tiel                | 2        | 0.81%   |
| Steenbergen         | 2        | 0.81%   |
| Sint Pancras        | 2        | 0.81%   |
| Roosendaal          | 2        | 0.81%   |
| Ridderkerk          | 2        | 0.81%   |
| Papendrecht         | 2        | 0.81%   |
| Oostzaan            | 2        | 0.81%   |
| Nieuwegein          | 2        | 0.81%   |
| Naaldwijk           | 2        | 0.81%   |
| Leiden              | 2        | 0.81%   |
| IJsselstein         | 2        | 0.81%   |
| Helmond             | 2        | 0.81%   |
| Eindhoven           | 2        | 0.81%   |
| Ede                 | 2        | 0.81%   |
| Dordrecht           | 2        | 0.81%   |
| Delft               | 2        | 0.81%   |
| Dedemsvaart         | 2        | 0.81%   |
| Alphen aan den Rijn | 2        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 49       | 82     | 20.16%  |
| Kingston            | 24       | 33     | 9.88%   |
| Crucial             | 22       | 39     | 9.05%   |
| WDC                 | 21       | 61     | 8.64%   |
| Transcend           | 14       | 25     | 5.76%   |
| Seagate             | 13       | 43     | 5.35%   |
| Hoodisk             | 9        | 13     | 3.7%    |
| Toshiba             | 6        | 22     | 2.47%   |
| SanDisk             | 6        | 6      | 2.47%   |
| Hewlett-Packard     | 6        | 19     | 2.47%   |
| OCZ                 | 5        | 7      | 2.06%   |
| Intel               | 5        | 8      | 2.06%   |
| HGST                | 5        | 9      | 2.06%   |
| Gigabyte Technology | 5        | 6      | 2.06%   |
| Phison              | 4        | 5      | 1.65%   |
| Dell                | 4        | 8      | 1.65%   |
| China               | 4        | 8      | 1.65%   |
| ShiJi               | 3        | 4      | 1.23%   |
| LITEON              | 3        | 4      | 1.23%   |
| Hitachi             | 3        | 5      | 1.23%   |
| FORESEE             | 3        | 6      | 1.23%   |
| Silicon Motion      | 2        | 3      | 0.82%   |
| Protectli           | 2        | 6      | 0.82%   |
| PNY                 | 2        | 2      | 0.82%   |
| Kston               | 2        | 6      | 0.82%   |
| A-DATA Technology   | 2        | 2      | 0.82%   |
| VICKTER             | 1        | 1      | 0.41%   |
| StoreJet            | 1        | 1      | 0.41%   |
| SPCC                | 1        | 1      | 0.41%   |
| Patriot             | 1        | 2      | 0.41%   |
| ORICO               | 1        | 1      | 0.41%   |
| OPENBSD             | 1        | 1      | 0.41%   |
| NVMe                | 1        | 1      | 0.41%   |
| NETAPP              | 1        | 4      | 0.41%   |
| Mushkin             | 1        | 1      | 0.41%   |
| Maxtor              | 1        | 1      | 0.41%   |
| LITEONIT            | 1        | 3      | 0.41%   |
| KeepData            | 1        | 1      | 0.41%   |
| Intenso             | 1        | 3      | 0.41%   |
| Innodisk            | 1        | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 10       | 3.75%   |
| Kingston SUV500MS120G 120GB      | 5        | 1.87%   |
| Kingston SKC600MS256G 256GB      | 4        | 1.5%    |
| Hoodisk SSD 128GB                | 4        | 1.5%    |
| Dell PERC H710 282GB             | 4        | 1.5%    |
| Crucial CT120BX500SSD1 120GB     | 4        | 1.5%    |
| Transcend TS128GMSA230S 128GB    | 3        | 1.12%   |
| Samsung SSD 850 EVO 500GB        | 3        | 1.12%   |
| Samsung SSD 850 EVO 120GB        | 3        | 1.12%   |
| Crucial M4-CT128M4SSD2 128GB     | 3        | 1.12%   |
| Crucial CT250MX500SSD1 250GB     | 3        | 1.12%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 1.12%   |
| China SATA SSD 16GB              | 3        | 1.12%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.75%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.75%   |
| Transcend TS32GSSD370S 32GB      | 2        | 0.75%   |
| Transcend TS256GMSA452T2 256GB   | 2        | 0.75%   |
| Transcend TS256GMSA230S 256GB    | 2        | 0.75%   |
| Samsung SSD 980 500GB            | 2        | 0.75%   |
| Samsung SSD 970 EVO Plus 2TB     | 2        | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.75%   |
| Samsung SSD 970 EVO 1TB          | 2        | 0.75%   |
| Samsung SSD 850 PRO 128GB        | 2        | 0.75%   |
| Samsung SSD 840 Series 120GB     | 2        | 0.75%   |
| OCZ TRION150 120GB               | 2        | 0.75%   |
| LITEON CS1-SP16-11 M.2 2242 16GB | 2        | 0.75%   |
| Kston SSD 128GB                  | 2        | 0.75%   |
| Kingston SA400S37240G 240GB      | 2        | 0.75%   |
| Kingston SA400S37120G 120GB      | 2        | 0.75%   |
| Hoodisk SSD 64GB                 | 2        | 0.75%   |
| Hoodisk SSD 32GB                 | 2        | 0.75%   |
| HGST HTS725050A7E630 500GB       | 2        | 0.75%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB | 2        | 0.75%   |
| Crucial CT480M500SSD1 480GB      | 2        | 0.75%   |
| WDC WDS500G1X0E-00AFY0 500GB     | 1        | 0.37%   |
| WDC WDS250G2B0A-00SM50 250GB     | 1        | 0.37%   |
| WDC WDS240G2G0B-00EPW0 240GB     | 1        | 0.37%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 1        | 0.37%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1        | 0.37%   |
| WDC WD8003FFBX-68B9AN0 8TB       | 1        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 52     | 28.81%  |
| Seagate             | 13       | 43     | 22.03%  |
| Samsung Electronics | 5        | 8      | 8.47%   |
| HGST                | 5        | 9      | 8.47%   |
| Hewlett-Packard     | 4        | 17     | 6.78%   |
| Dell                | 4        | 8      | 6.78%   |
| Toshiba             | 3        | 15     | 5.08%   |
| Hitachi             | 3        | 5      | 5.08%   |
| StoreJet            | 1        | 1      | 1.69%   |
| OPENBSD             | 1        | 1      | 1.69%   |
| NVMe                | 1        | 1      | 1.69%   |
| Maxtor              | 1        | 1      | 1.69%   |
| HPE                 | 1        | 4      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 35       | 53     | 23.65%  |
| Kingston            | 20       | 29     | 13.51%  |
| Crucial             | 19       | 32     | 12.84%  |
| Transcend           | 13       | 24     | 8.78%   |
| Hoodisk             | 9        | 13     | 6.08%   |
| SanDisk             | 6        | 6      | 4.05%   |
| OCZ                 | 5        | 7      | 3.38%   |
| Intel               | 4        | 7      | 2.7%    |
| China               | 4        | 8      | 2.7%    |
| LITEON              | 3        | 4      | 2.03%   |
| FORESEE             | 3        | 6      | 2.03%   |
| WDC                 | 2        | 4      | 1.35%   |
| ShiJi               | 2        | 3      | 1.35%   |
| Protectli           | 2        | 6      | 1.35%   |
| PNY                 | 2        | 2      | 1.35%   |
| Phison              | 2        | 2      | 1.35%   |
| Kston               | 2        | 6      | 1.35%   |
| VICKTER             | 1        | 1      | 0.68%   |
| Toshiba             | 1        | 3      | 0.68%   |
| Patriot             | 1        | 2      | 0.68%   |
| ORICO               | 1        | 1      | 0.68%   |
| NETAPP              | 1        | 4      | 0.68%   |
| Mushkin             | 1        | 1      | 0.68%   |
| LITEONIT            | 1        | 3      | 0.68%   |
| KeepData            | 1        | 1      | 0.68%   |
| Intenso             | 1        | 3      | 0.68%   |
| Innodisk            | 1        | 1      | 0.68%   |
| Hewlett-Packard     | 1        | 1      | 0.68%   |
| Gigabyte Technology | 1        | 1      | 0.68%   |
| BAITITON            | 1        | 2      | 0.68%   |
| Apacer              | 1        | 2      | 0.68%   |
| Advantech           | 1        | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 139      | 239    | 61.5%   |
| HDD  | 49       | 165    | 21.68%  |
| NVMe | 38       | 61     | 16.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 172      | 404    | 81.9%   |
| NVMe | 38       | 61     | 18.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 156      | 271    | 79.19%  |
| 0.51-1.0   | 19       | 51     | 9.64%   |
| 3.01-4.0   | 9        | 22     | 4.57%   |
| 1.01-2.0   | 6        | 10     | 3.05%   |
| 4.01-10.0  | 6        | 45     | 3.05%   |
| 10.01-20.0 | 1        | 5      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 104      | 47.93%  |
| 51-100         | 30       | 13.82%  |
| 251-500        | 26       | 11.98%  |
| 1-20           | 22       | 10.14%  |
| 21-50          | 14       | 6.45%   |
| 501-1000       | 11       | 5.07%   |
| 1001-2000      | 5        | 2.3%    |
| More than 3000 | 2        | 0.92%   |
| 2001-3000      | 2        | 0.92%   |
| Unknown        | 1        | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 189      | 89.15%  |
| 21-50    | 11       | 5.19%   |
| 51-100   | 4        | 1.89%   |
| 101-250  | 3        | 1.42%   |
| 251-500  | 2        | 0.94%   |
| 501-1000 | 2        | 0.94%   |
| Unknown  | 1        | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Crucial CT480M500SSD1 480GB               | 2        | 3      | 7.41%   |
| WDC WD2500BEKT-75PVMT0 250GB              | 1        | 1      | 3.7%    |
| ShiJi SSD 32GB                            | 1        | 2      | 3.7%    |
| Seagate ST500LT012-9WS142 500GB           | 1        | 2      | 3.7%    |
| Seagate ST3360320AS 360GB                 | 1        | 1      | 3.7%    |
| Seagate ST3160318AS 160GB                 | 1        | 4      | 3.7%    |
| SanDisk SDSSDP064G 64GB                   | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 870 EVO 1TB       | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 850 EVO mSATA 1TB | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 850 EVO 1TB       | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 840 Series 120GB  | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 840 EVO 120GB     | 1        | 1      | 3.7%    |
| Samsung Electronics HD322HJ 320GB         | 1        | 1      | 3.7%    |
| Samsung Electronics HD161GJ 160GB         | 1        | 1      | 3.7%    |
| Samsung Electronics HD103SJ 1TB           | 1        | 2      | 3.7%    |
| Kingston SMS200S3120G 120GB               | 1        | 1      | 3.7%    |
| Kingston SA400S37240G 240GB               | 1        | 1      | 3.7%    |
| Intel SSDSC2BA200G3T 200GB                | 1        | 4      | 3.7%    |
| HPE MM1000GBKAL 1TB                       | 1        | 4      | 3.7%    |
| Hitachi HTS543232A7A384 320GB             | 1        | 1      | 3.7%    |
| Hitachi HDS723015BLA642 1.5TB             | 1        | 3      | 3.7%    |
| HGST HTS725050A7E630 500GB                | 1        | 1      | 3.7%    |
| HGST HDN726060ALE614 6TB                  | 1        | 2      | 3.7%    |
| Hewlett-Packard FB160C4081 160GB          | 1        | 2      | 3.7%    |
| Crucial CT128MX100SSD1 128GB              | 1        | 2      | 3.7%    |
| A-DATA Technology SX7000NP 128GB          | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 9      | 26.92%  |
| Seagate             | 3        | 7      | 11.54%  |
| Crucial             | 3        | 5      | 11.54%  |
| Kingston            | 2        | 2      | 7.69%   |
| Hitachi             | 2        | 4      | 7.69%   |
| HGST                | 2        | 3      | 7.69%   |
| WDC                 | 1        | 1      | 3.85%   |
| ShiJi               | 1        | 2      | 3.85%   |
| SanDisk             | 1        | 1      | 3.85%   |
| Intel               | 1        | 4      | 3.85%   |
| HPE                 | 1        | 4      | 3.85%   |
| Hewlett-Packard     | 1        | 2      | 3.85%   |
| A-DATA Technology   | 1        | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 7      | 23.08%  |
| Samsung Electronics | 3        | 4      | 23.08%  |
| Hitachi             | 2        | 4      | 15.38%  |
| HGST                | 2        | 3      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| HPE                 | 1        | 4      | 7.69%   |
| Hewlett-Packard     | 1        | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 25     | 50%     |
| SSD  | 11       | 19     | 45.83%  |
| NVMe | 1        | 1      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Samsung Electronics MZVLW256HEHP-00000 256GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 180      | 409    | 86.12%  |
| Malfunc  | 22       | 45     | 10.53%  |
| Detected | 6        | 10     | 2.87%   |
| Failed   | 1        | 1      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 161      | 61.22%  |
| AMD                         | 33       | 12.55%  |
| Samsung Electronics         | 15       | 5.7%    |
| Phison Electronics          | 10       | 3.8%    |
| Broadcom / LSI              | 9        | 3.42%   |
| ASMedia Technology          | 9        | 3.42%   |
| Silicon Motion              | 5        | 1.9%    |
| Micron/Crucial Technology   | 5        | 1.9%    |
| SanDisk                     | 3        | 1.14%   |
| Marvell Technology Group    | 3        | 1.14%   |
| Kingston Technology Company | 3        | 1.14%   |
| Toshiba                     | 2        | 0.76%   |
| Hewlett-Packard             | 2        | 0.76%   |
| Realtek Semiconductor       | 1        | 0.38%   |
| JMicron Technology          | 1        | 0.38%   |
| Chelsio Communications      | 1        | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21       | 7.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 4.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 4.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 11       | 3.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 3.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8        | 2.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8        | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.79%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 7        | 2.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7        | 2.44%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 2.44%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 2.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 2.09%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 5        | 1.74%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 1.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 1.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.39%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 4        | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4        | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4        | 1.39%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 4        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.05%   |
| Intel unknown                                                                           | 3        | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.05%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3        | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.7%    |
| Intel Elkhart Lake SATA AHCI                                                            | 2        | 0.7%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.7%    |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 2        | 0.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 180      | 71.15%  |
| NVMe | 41       | 16.21%  |
| IDE  | 14       | 5.53%   |
| RAID | 12       | 4.74%   |
| SAS  | 5        | 1.98%   |
| SCSI | 1        | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 165      | 80.1%   |
| AMD    | 35       | 16.99%  |
| ARM    | 5        | 2.43%   |
| NXP    | 1        | 0.49%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz         | 7        | 3.38%   |
| AMD GX-412TC SOC                         | 7        | 3.38%   |
| Intel Celeron N5105 @ 2.00GHz            | 6        | 2.9%    |
| Intel N100                               | 5        | 2.42%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 5        | 2.42%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 5        | 2.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 4        | 1.93%   |
| Intel Core i7-2600K CPU @ 3.40GHz        | 3        | 1.45%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 3        | 1.45%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 3        | 1.45%   |
| ARM Cortex-A72 r0p3                      | 3        | 1.45%   |
| AMD G-T56N Processor                     | 3        | 1.45%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz       | 2        | 0.97%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz       | 2        | 0.97%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 2        | 0.97%   |
| Intel Core i7-5550U CPU @ 2.00GHz        | 2        | 0.97%   |
| Intel Core i7-2600 CPU @ 3.40GHz         | 2        | 0.97%   |
| Intel Core i5-8600 CPU @ 3.10GHz         | 2        | 0.97%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 2        | 0.97%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 2        | 0.97%   |
| Intel Core i5-4690 CPU @ 3.50GHz         | 2        | 0.97%   |
| Intel Core i5-4590T CPU @ 2.00GHz        | 2        | 0.97%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 2        | 0.97%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 2        | 0.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 2        | 0.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 2        | 0.97%   |
| Intel Core i5-10400 CPU @ 2.90GHz        | 2        | 0.97%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 2        | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GH          | 2        | 0.97%   |
| Intel Core 2 Duo                         | 2        | 0.97%   |
| Intel Celeron J6413 @ 1.80GHz            | 2        | 0.97%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 2        | 0.97%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 2        | 0.97%   |
| ARM Cortex-A53 r0p4                      | 2        | 0.97%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 2        | 0.97%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 2        | 0.97%   |
| AMD G-T40E Processor                     | 2        | 0.97%   |
| AMD EPYC 3251 8-Core Processor           | 2        | 0.97%   |
| NXP Cortex-A72                           | 1        | 0.48%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Intel Core i5        | 58       | 28.02%  |
| Intel Celeron        | 28       | 13.53%  |
| Intel Core i7        | 16       | 7.73%   |
| AMD GX               | 15       | 7.25%   |
| Intel Core i3        | 14       | 6.76%   |
| Intel Xeon           | 13       | 6.28%   |
| Other                | 12       | 5.8%    |
| Intel Atom           | 8        | 3.86%   |
| Intel Pentium        | 7        | 3.38%   |
| Intel Core 2 Duo     | 5        | 2.42%   |
| ARM Cortex           | 5        | 2.42%   |
| AMD G                | 5        | 2.42%   |
| AMD Ryzen 7          | 4        | 1.93%   |
| Intel Pentium Gold   | 3        | 1.45%   |
| AMD Ryzen 5          | 3        | 1.45%   |
| Intel Pentium Silver | 2        | 0.97%   |
| Intel Core i9        | 2        | 0.97%   |
| AMD EPYC             | 2        | 0.97%   |
| Intel Pentium 4      | 1        | 0.48%   |
| AMD Ryzen 9          | 1        | 0.48%   |
| AMD Ryzen 7 PRO      | 1        | 0.48%   |
| AMD Ryzen 3          | 1        | 0.48%   |
| AMD E                | 1        | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 106      | 51.46%  |
| 2       | 58       | 28.16%  |
| 6       | 12       | 5.83%   |
| 12      | 8        | 3.88%   |
| Unknown | 7        | 3.4%    |
| 16      | 6        | 2.91%   |
| 8       | 4        | 1.94%   |
| 10      | 2        | 0.97%   |
| 1       | 2        | 0.97%   |
| 18      | 1        | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 196      | 95.15%  |
| 2       | 5        | 2.43%   |
| Unknown | 5        | 2.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 121      | 58.45%  |
| 2       | 79       | 38.16%  |
| Unknown | 7        | 3.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 25       | 12.08%  |
| KabyLake      | 24       | 11.59%  |
| Haswell       | 22       | 10.63%  |
| Skylake       | 21       | 10.14%  |
| SandyBridge   | 15       | 7.25%   |
| Silvermont    | 11       | 5.31%   |
| Broadwell     | 11       | 5.31%   |
| Puma          | 10       | 4.83%   |
| IvyBridge     | 8        | 3.86%   |
| CometLake     | 8        | 3.86%   |
| Goldmont plus | 7        | 3.38%   |
| Goldmont      | 6        | 2.9%    |
| Bobcat        | 6        | 2.9%    |
| Zen 2         | 5        | 2.42%   |
| Penryn        | 5        | 2.42%   |
| Jaguar        | 5        | 2.42%   |
| Zen           | 4        | 1.93%   |
| Bonnell       | 4        | 1.93%   |
| Zen 3         | 2        | 0.97%   |
| Westmere      | 2        | 0.97%   |
| Nehalem       | 2        | 0.97%   |
| Zen+          | 1        | 0.48%   |
| NetBurst      | 1        | 0.48%   |
| K8 Hammer     | 1        | 0.48%   |
| Excavator     | 1        | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 136      | 72.73%  |
| AMD                        | 22       | 11.76%  |
| Nvidia                     | 13       | 6.95%   |
| Matrox Electronics Systems | 10       | 5.35%   |
| ASPEED Technology          | 6        | 3.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                                    | 16       | 8.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12       | 6.38%   |
| Intel JasperLake [UHD Graphics]                                                          | 8        | 4.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 4.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 3.72%   |
| Intel HD Graphics 5500                                                                   | 6        | 3.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 3.19%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 3.19%   |
| Matrox Electronics Systems G200eR2                                                       | 5        | 2.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 2.66%   |
| Intel HD Graphics 6000                                                                   | 5        | 2.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 2.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 2.66%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 5        | 2.66%   |
| Intel HD Graphics 630                                                                    | 4        | 2.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4        | 2.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 2.13%   |
| Intel HD Graphics 620                                                                    | 3        | 1.6%    |
| Intel HD Graphics 610                                                                    | 3        | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 1.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.06%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 1.06%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2        | 1.06%   |
| Intel HD Graphics 500                                                                    | 2        | 1.06%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 2        | 1.06%   |
| Intel Comet Lake UHD Graphics                                                            | 2        | 1.06%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2        | 1.06%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2        | 1.06%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2        | 1.06%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2        | 1.06%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2        | 1.06%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 1.06%   |
| Nvidia TU117GLM [Quadro T400 Mobile]                                                     | 1        | 0.53%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.53%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.53%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.53%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.53%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 129      | 62.62%  |
| 1 x AMD        | 22       | 10.68%  |
| Other          | 21       | 10.19%  |
| 1 x Nvidia     | 11       | 5.34%   |
| 1 x Matrox     | 10       | 4.85%   |
| 1 x ASPEED     | 6        | 2.91%   |
| 2 x Intel      | 5        | 2.43%   |
| Intel + Nvidia | 2        | 0.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 177      | 85.92%  |
| Unknown     | 22       | 10.68%  |
| Proprietary | 7        | 3.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 195      | 94.2%   |
| 7.01-8.0   | 5        | 2.42%   |
| 1.01-2.0   | 4        | 1.93%   |
| 3.01-4.0   | 1        | 0.48%   |
| 0.51-1.0   | 1        | 0.48%   |
| 0.01-0.5   | 1        | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Iiyama              | 5        | 25%     |
| Samsung Electronics | 4        | 20%     |
| Goldstar            | 3        | 15%     |
| Dell                | 3        | 15%     |
| ViewSonic           | 1        | 5%      |
| Sony                | 1        | 5%      |
| Philips             | 1        | 5%      |
| Fujitsu Siemens     | 1        | 5%      |
| ASUSTek Computer    | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ViewSonic LCD Monitor VX3276-QHD 2560x1440                              | 1        | 5%      |
| Sony TV SNYC901 1920x1080                                               | 1        | 5%      |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch    | 1        | 5%      |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch    | 1        | 5%      |
| Samsung Electronics SA300/350/360 SAM07D5 1920x1080 530x300mm 24.0-inch | 1        | 5%      |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch       | 1        | 5%      |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch                 | 1        | 5%      |
| Iiyama PLE2607WS IVM5608 1920x1080 550x340mm 25.5-inch                  | 1        | 5%      |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                 | 1        | 5%      |
| Iiyama PL2740HS IVM6662 1920x1080 600x340mm 27.2-inch                   | 1        | 5%      |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                    | 1        | 5%      |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                   | 1        | 5%      |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch             | 1        | 5%      |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 5%      |
| Goldstar 34GK950F GSM7727 3440x1440 800x330mm 34.1-inch                 | 1        | 5%      |
| Fujitsu Siemens L19-1 FUS07DB 1280x1024 380x300mm 19.1-inch             | 1        | 5%      |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                      | 1        | 5%      |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                       | 1        | 5%      |
| Dell U2311H DELA060 1920x1080 510x290mm 23.1-inch                       | 1        | 5%      |
| ASUSTek Computer VG259 AUS25A6 1920x1080 540x300mm 24.3-inch            | 1        | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 45%     |
| 2560x1440 (QHD)    | 4        | 20%     |
| 3840x2160 (4K)     | 2        | 10%     |
| 3440x1440          | 2        | 10%     |
| 1680x1050 (WSXGA+) | 1        | 5%      |
| 1600x1200          | 1        | 5%      |
| 1280x1024 (SXGA)   | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 20%     |
| 24      | 4        | 20%     |
| 34      | 2        | 10%     |
| 23      | 2        | 10%     |
| Unknown | 2        | 10%     |
| 31      | 1        | 5%      |
| 25      | 1        | 5%      |
| 22      | 1        | 5%      |
| 21      | 1        | 5%      |
| 20      | 1        | 5%      |
| 19      | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 55%     |
| 401-500     | 3        | 15%     |
| 701-800     | 2        | 10%     |
| Unknown     | 2        | 10%     |
| 601-700     | 1        | 5%      |
| 351-400     | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 65%     |
| 21/9    | 2        | 10%     |
| 16/10   | 2        | 10%     |
| 5/4     | 1        | 5%      |
| 4/3     | 1        | 5%      |
| Unknown | 1        | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 35%     |
| 301-350        | 4        | 20%     |
| 351-500        | 3        | 15%     |
| 251-300        | 2        | 10%     |
| 151-200        | 2        | 10%     |
| Unknown        | 2        | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 50%     |
| 101-120 | 5        | 25%     |
| 121-160 | 2        | 10%     |
| Unknown | 2        | 10%     |
| 161-240 | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 184      | 89.32%  |
| 1     | 21       | 10.19%  |
| 2     | 1        | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 171      | 63.57%  |
| Realtek Semiconductor    | 58       | 21.56%  |
| Qualcomm Atheros         | 12       | 4.46%   |
| Broadcom                 | 10       | 3.72%   |
| IMC Networks             | 3        | 1.12%   |
| TP-Link                  | 2        | 0.74%   |
| Ralink                   | 2        | 0.74%   |
| Mellanox Technologies    | 2        | 0.74%   |
| Marvell Technology Group | 2        | 0.74%   |
| U-Blox                   | 1        | 0.37%   |
| Ralink Technology        | 1        | 0.37%   |
| Huawei Technologies      | 1        | 0.37%   |
| Hewlett-Packard          | 1        | 0.37%   |
| Edimax Technology        | 1        | 0.37%   |
| Chelsio Communications   | 1        | 0.37%   |
| ADMtek                   | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 53       | 16.67%  |
| Intel I211 Gigabit Network Connection                                         | 35       | 11.01%  |
| Intel I210 Gigabit Network Connection                                         | 21       | 6.6%    |
| Intel I350 Gigabit Network Connection                                         | 20       | 6.29%   |
| Intel 82574L Gigabit Network Connection                                       | 15       | 4.72%   |
| Intel Ethernet Controller I225-V                                              | 13       | 4.09%   |
| Intel Ethernet Controller I226-V                                              | 12       | 3.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10       | 3.14%   |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 2.52%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 1.57%   |
| Intel Wi-Fi 6 AX200                                                           | 4        | 1.26%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 1.26%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.94%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 0.94%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 0.94%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.94%   |
| Intel 82575GB Gigabit Network Connection                                      | 3        | 0.94%   |
| Intel 82575EB Gigabit Network Connection                                      | 3        | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.94%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 2        | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2        | 0.63%   |
| Intel Wireless 3165                                                           | 2        | 0.63%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.63%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 0.63%   |
| Intel 82580 Gigabit Network Connection                                        | 2        | 0.63%   |
| Intel 82567V-3 Gigabit Network Connection                                     | 2        | 0.63%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 2        | 0.63%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 2        | 0.63%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.31%   |
| TP-Link M7350 4G Mi-Fi Router                                                 | 1        | 0.31%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.31%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                        | 1        | 0.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 38.24%  |
| Qualcomm Atheros      | 9        | 26.47%  |
| Realtek Semiconductor | 3        | 8.82%   |
| IMC Networks          | 3        | 8.82%   |
| Ralink                | 2        | 5.88%   |
| TP-Link               | 1        | 2.94%   |
| Ralink Technology     | 1        | 2.94%   |
| Edimax Technology     | 1        | 2.94%   |
| Broadcom              | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                         | 4        | 11.76%  |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter             | 2        | 5.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 2        | 5.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 2        | 5.88%   |
| Intel Wireless 3165                                                         | 2        | 5.88%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                        | 2        | 5.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1        | 2.94%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                      | 1        | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 2.94%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 2.94%   |
| Ralink RT2800 802.11n PCI                                                   | 1        | 2.94%   |
| Ralink RT2500 Wireless 802.11bg                                             | 1        | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1        | 2.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1        | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 2.94%   |
| Intel Wireless 8265 / 8275                                                  | 1        | 2.94%   |
| Intel Wireless 3160                                                         | 1        | 2.94%   |
| Intel Raptor Lake PCH CNVi WiFi                                             | 1        | 2.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1        | 2.94%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 1        | 2.94%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 2.94%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 1        | 2.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 166      | 69.46%  |
| Realtek Semiconductor    | 56       | 23.43%  |
| Broadcom                 | 9        | 3.77%   |
| Qualcomm Atheros         | 3        | 1.26%   |
| Marvell Technology Group | 2        | 0.84%   |
| TP-Link                  | 1        | 0.42%   |
| Chelsio Communications   | 1        | 0.42%   |
| ADMtek                   | 1        | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 53       | 19%     |
| Intel I211 Gigabit Network Connection                                          | 35       | 12.54%  |
| Intel I210 Gigabit Network Connection                                          | 21       | 7.53%   |
| Intel I350 Gigabit Network Connection                                          | 20       | 7.17%   |
| Intel 82574L Gigabit Network Connection                                        | 15       | 5.38%   |
| Intel Ethernet Controller I225-V                                               | 13       | 4.66%   |
| Intel Ethernet Controller I226-V                                               | 12       | 4.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 10       | 3.58%   |
| Intel Ethernet Connection (2) I219-V                                           | 8        | 2.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8        | 2.87%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 1.79%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 4        | 1.43%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 4        | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3        | 1.08%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3        | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 1.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 3        | 1.08%   |
| Intel 82583V Gigabit Network Connection                                        | 3        | 1.08%   |
| Intel 82576 Gigabit Network Connection                                         | 3        | 1.08%   |
| Intel 82575GB Gigabit Network Connection                                       | 3        | 1.08%   |
| Intel 82575EB Gigabit Network Connection                                       | 3        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3        | 1.08%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2        | 0.72%   |
| Intel Ethernet Connection X553 1GbE                                            | 2        | 0.72%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 0.72%   |
| Intel 82580 Gigabit Network Connection                                         | 2        | 0.72%   |
| Intel 82567V-3 Gigabit Network Connection                                      | 2        | 0.72%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 2        | 0.72%   |
| TP-Link M7350 4G Mi-Fi Router                                                  | 1        | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.36%   |
| Intel Ethernet Controller I219-V                                               | 1        | 0.36%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                     | 1        | 0.36%   |
| Intel Ethernet Connection I218-V                                               | 1        | 0.36%   |
| Intel Ethernet Connection I218-LM                                              | 1        | 0.36%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 201      | 84.1%   |
| WiFi     | 33       | 13.81%  |
| Unknown  | 4        | 1.67%   |
| Modem    | 1        | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 192      | 97.96%  |
| WiFi     | 4        | 2.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 54       | 25.96%  |
| 2     | 47       | 22.6%   |
| 3     | 31       | 14.9%   |
| 1     | 29       | 13.94%  |
| 6     | 18       | 8.65%   |
| 5     | 17       | 8.17%   |
| 0     | 5        | 2.4%    |
| 9     | 2        | 0.96%   |
| 8     | 2        | 0.96%   |
| 7     | 2        | 0.96%   |
| 12    | 1        | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 170      | 78.7%   |
| Yes  | 46       | 21.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 63.16%  |
| Cambridge Silicon Radio         | 4        | 21.05%  |
| TP-Link                         | 1        | 5.26%   |
| Realtek Semiconductor           | 1        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 5        | 26.32%  |
| Intel AX200 Bluetooth                               | 4        | 21.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 21.05%  |
| TP-Link Bluetooth 5.0 USB Adapter                   | 1        | 5.26%   |
| Realtek Bluetooth Adapter                           | 1        | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1        | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5.26%   |
| Intel AX201 Bluetooth                               | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 131      | 75.29%  |
| AMD                                          | 27       | 15.52%  |
| Nvidia                                       | 11       | 6.32%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.57%   |
| VIA Technologies                             | 1        | 0.57%   |
| Steinberg Soft-und Hardware                  | 1        | 0.57%   |
| Creative Labs                                | 1        | 0.57%   |
| Corsair                                      | 1        | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13       | 6.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12       | 5.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11       | 5.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10       | 4.74%   |
| Intel 200 Series PCH HD Audio                                                                     | 10       | 4.74%   |
| Intel Broadwell-U Audio Controller                                                                | 9        | 4.27%   |
| Intel Jasper Lake HD Audio                                                                        | 8        | 3.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8        | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7        | 3.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6        | 2.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6        | 2.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6        | 2.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6        | 2.84%   |
| AMD FCH Azalia Controller                                                                         | 5        | 2.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5        | 2.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4        | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 1.9%    |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 4        | 1.9%    |
| AMD Wrestler HDMI Audio                                                                           | 4        | 1.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 1.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4        | 1.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3        | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 1.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 1.42%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3        | 1.42%   |
| Intel 8 Series HD Audio Controller                                                                | 3        | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2        | 0.95%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2        | 0.95%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 2        | 0.95%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2        | 0.95%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 0.47%   |
| VIA Technologies USB Audio Device                                                                 | 1        | 0.47%   |
| Steinberg Soft-und Hardware MI4                                                                   | 1        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 35       | 16.83%  |
| Samsung Electronics | 28       | 13.46%  |
| SK hynix            | 25       | 12.02%  |
| Corsair             | 23       | 11.06%  |
| Crucial             | 20       | 9.62%   |
| Unknown             | 18       | 8.65%   |
| Micron Technology   | 17       | 8.17%   |
| G.Skill             | 6        | 2.88%   |
| Kimtigo             | 5        | 2.4%    |
| Transcend           | 4        | 1.92%   |
| Unknown (ABCD)      | 3        | 1.44%   |
| Teikon              | 3        | 1.44%   |
| Apacer              | 3        | 1.44%   |
| tigo                | 2        | 0.96%   |
| Ramaxel Technology  | 2        | 0.96%   |
| Patriot             | 2        | 0.96%   |
| Nanya Technology    | 2        | 0.96%   |
| Unknown             | 2        | 0.96%   |
| Unknown (AB)        | 1        | 0.48%   |
| Unknown (07FB)      | 1        | 0.48%   |
| Toshiba             | 1        | 0.48%   |
| Team                | 1        | 0.48%   |
| HPE                 | 1        | 0.48%   |
| Hewlett-Packard     | 1        | 0.48%   |
| GOODRAM             | 1        | 0.48%   |
| A-DATA Technology   | 1        | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 5        | 2.29%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 3        | 1.38%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 3        | 1.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 3        | 1.38%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s         | 3        | 1.38%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s        | 3        | 1.38%   |
| Unknown RAM Module 8GB 1600MT/s                              | 2        | 0.92%   |
| tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                 | 2        | 0.92%   |
| Teikon RAM TMTS8G58DFRBFEN-16 8GB SODIMM DDR3 1600MT/s       | 2        | 0.92%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 0.92%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s         | 2        | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2        | 0.92%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2133MT/s         | 2        | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2        | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2        | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2        | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2        | 0.92%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s          | 2        | 0.92%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.92%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2        | 0.92%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2400MT/s           | 2        | 0.92%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 2        | 0.92%   |
| G.Skill RAM F4-3200C22-8GRS 8GB SODIMM DDR4 3200MT/s         | 2        | 0.92%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 2        | 0.92%   |
| Crucial RAM CT102464BA160B.M16 8GB DIMM DDR3 1600MT/s        | 2        | 0.92%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s      | 2        | 0.92%   |
| Apacer RAM 37352E4138334331 2GB SODIMM DDR3 1333MT/s         | 2        | 0.92%   |
| Unknown                                                      | 2        | 0.92%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s          | 1        | 0.46%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1        | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                    | 1        | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1        | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                   | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 0.46%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR4 1600MT/s             | 1        | 0.46%   |
| Unknown (07FB) RAM GSA8G4SCL156P-21 8GB SODIMM DDR4 2133MT/s | 1        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 82       | 45.05%  |
| DDR3    | 78       | 42.86%  |
| DDR2    | 8        | 4.4%    |
| DDR5    | 4        | 2.2%    |
| Unknown | 4        | 2.2%    |
| LPDDR4  | 3        | 1.65%   |
| SDRAM   | 1        | 0.55%   |
| LPDDR5  | 1        | 0.55%   |
| DDR     | 1        | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 102      | 56.04%  |
| SODIMM       | 77       | 42.31%  |
| Unknown      | 2        | 1.1%    |
| Row Of Chips | 1        | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 90       | 45.92%  |
| 4096  | 54       | 27.55%  |
| 16384 | 25       | 12.76%  |
| 2048  | 21       | 10.71%  |
| 32768 | 3        | 1.53%   |
| 1024  | 3        | 1.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 57       | 29.69%  |
| 1333    | 25       | 13.02%  |
| 2400    | 22       | 11.46%  |
| 2133    | 21       | 10.94%  |
| 2667    | 17       | 8.85%   |
| 3200    | 16       | 8.33%   |
| 3000    | 5        | 2.6%    |
| 2666    | 5        | 2.6%    |
| 800     | 5        | 2.6%    |
| 4800    | 3        | 1.56%   |
| 667     | 3        | 1.56%   |
| 2933    | 2        | 1.04%   |
| Unknown | 2        | 1.04%   |
| 6400    | 1        | 0.52%   |
| 5200    | 1        | 0.52%   |
| 3600    | 1        | 0.52%   |
| 3400    | 1        | 0.52%   |
| 1867    | 1        | 0.52%   |
| 1866    | 1        | 0.52%   |
| 1067    | 1        | 0.52%   |
| 1066    | 1        | 0.52%   |
| 533     | 1        | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Sonix Technology | 1        | 50%     |
| Logitech         | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Sonix FHD Webcam            | 1        | 50%     |
| Logitech HD Pro Webcam C920 | 1        | 50%     |

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
| 1     | 121      | 57.35%  |
| 0     | 62       | 29.38%  |
| 2     | 25       | 11.85%  |
| 3     | 3        | 1.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 137      | 83.03%  |
| Bluetooth                | 10       | 6.06%   |
| Net/wireless             | 8        | 4.85%   |
| Net/ethernet             | 3        | 1.82%   |
| Card reader              | 3        | 1.82%   |
| Storage/ata              | 1        | 0.61%   |
| Storage                  | 1        | 0.61%   |
| Graphics card            | 1        | 0.61%   |
| Firewire controller      | 1        | 0.61%   |

