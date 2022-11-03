BSD in Germany - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

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

Total: 2019

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Hardkernel    | ODROID-H2                   | Desktop     | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [09cb46f6bf](https://bsd-hardware.info/?probe=09cb46f6bf) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [af6807035f](https://bsd-hardware.info/?probe=af6807035f) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| Sophos        | SG                          | Firewall    | [03633cdc2e](https://bsd-hardware.info/?probe=03633cdc2e) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| Acer          | JM11-MS                     | Notebook    | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [484e5520b7](https://bsd-hardware.info/?probe=484e5520b7) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| PC Engines    | apu1                        | Desktop     | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [0e2cd201d0](https://bsd-hardware.info/?probe=0e2cd201d0) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [0d6e868d9c](https://bsd-hardware.info/?probe=0d6e868d9c) | Oct 24, 2022 |
| Sophos        | SG                          | Firewall    | [bb50acf083](https://bsd-hardware.info/?probe=bb50acf083) | Oct 24, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| Dell          | Latitude 5591               | Notebook    | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Alienware     | m15                         | Notebook    | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Sophos        | UTM                         | Firewall    | [bae9180e3f](https://bsd-hardware.info/?probe=bae9180e3f) | Oct 22, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| Sophos        | SG                          | Firewall    | [a8593e1424](https://bsd-hardware.info/?probe=a8593e1424) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Protectli     | FW6                         | Desktop     | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [8c6555d6be](https://bsd-hardware.info/?probe=8c6555d6be) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | Desktop     | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [7024873a21](https://bsd-hardware.info/?probe=7024873a21) | Oct 17, 2022 |
| NF541         | 1.0                         | Desktop     | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [885bf4ef1e](https://bsd-hardware.info/?probe=885bf4ef1e) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [4fbe0156a8](https://bsd-hardware.info/?probe=4fbe0156a8) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| Sophos        | XG                          | Firewall    | [e80ccac6ff](https://bsd-hardware.info/?probe=e80ccac6ff) | Oct 15, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [27d7eb468e](https://bsd-hardware.info/?probe=27d7eb468e) | Oct 14, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [99c0387102](https://bsd-hardware.info/?probe=99c0387102) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [ecdab22807](https://bsd-hardware.info/?probe=ecdab22807) | Oct 08, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [231a0f9ce0](https://bsd-hardware.info/?probe=231a0f9ce0) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| CncTion       | J4125-4L-I225               | Desktop     | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| Sophos        | SG                          | Firewall    | [44ca915943](https://bsd-hardware.info/?probe=44ca915943) | Oct 05, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [724c70cfa3](https://bsd-hardware.info/?probe=724c70cfa3) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Neousys Te... | NVS-5000 Rev. A3            | Server      | [49d9f0e06a](https://bsd-hardware.info/?probe=49d9f0e06a) | Oct 04, 2022 |
| Sophos        | XG                          | Firewall    | [4b62b03461](https://bsd-hardware.info/?probe=4b62b03461) | Oct 03, 2022 |
| Protectli     | FW4B                        | Desktop     | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| AMI           | PICO PC                     | Desktop     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [6f95477df3](https://bsd-hardware.info/?probe=6f95477df3) | Sep 30, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [eb0e449150](https://bsd-hardware.info/?probe=eb0e449150) | Sep 29, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Sophos        | SG                          | Firewall    | [6511e9620b](https://bsd-hardware.info/?probe=6511e9620b) | Sep 28, 2022 |
| ASRock        | Z97 Professional            | Desktop     | [8936497eed](https://bsd-hardware.info/?probe=8936497eed) | Sep 27, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [a605b4582c](https://bsd-hardware.info/?probe=a605b4582c) | Sep 27, 2022 |
| Sophos        | SG                          | Firewall    | [fdd950a5e8](https://bsd-hardware.info/?probe=fdd950a5e8) | Sep 26, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [2998faa879](https://bsd-hardware.info/?probe=2998faa879) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | Desktop     | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| ASUSTek       | P9D-X Series                | Server      | [3494695f54](https://bsd-hardware.info/?probe=3494695f54) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [59ff2014e5](https://bsd-hardware.info/?probe=59ff2014e5) | Sep 25, 2022 |
| Intel         | S1200SP H57532-210          | Server      | [ab6e70abca](https://bsd-hardware.info/?probe=ab6e70abca) | Sep 25, 2022 |
| Supermicro    | X8DT3                       | Server      | [eda1df037b](https://bsd-hardware.info/?probe=eda1df037b) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | Desktop     | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | Notebook    | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [6e2d053e1c](https://bsd-hardware.info/?probe=6e2d053e1c) | Sep 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8ed018c141](https://bsd-hardware.info/?probe=8ed018c141) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a0672c6af1](https://bsd-hardware.info/?probe=a0672c6af1) | Sep 23, 2022 |
| Sophos        | UTM                         | Firewall    | [fe6cf3c1ab](https://bsd-hardware.info/?probe=fe6cf3c1ab) | Sep 22, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [495b0dfebd](https://bsd-hardware.info/?probe=495b0dfebd) | Sep 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [036004bbfe](https://bsd-hardware.info/?probe=036004bbfe) | Sep 22, 2022 |
| PC Engines    | APU                         | Desktop     | [a65b17ba04](https://bsd-hardware.info/?probe=a65b17ba04) | Sep 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [37acdfe51c](https://bsd-hardware.info/?probe=37acdfe51c) | Sep 20, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [3c74fc1690](https://bsd-hardware.info/?probe=3c74fc1690) | Sep 20, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [c057b7ab09](https://bsd-hardware.info/?probe=c057b7ab09) | Sep 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [80e1559386](https://bsd-hardware.info/?probe=80e1559386) | Sep 19, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [393da0c00c](https://bsd-hardware.info/?probe=393da0c00c) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a2f56848a9](https://bsd-hardware.info/?probe=a2f56848a9) | Sep 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cad2b5fd02](https://bsd-hardware.info/?probe=cad2b5fd02) | Sep 18, 2022 |
| Sophos        | XG                          | Firewall    | [e8aca06194](https://bsd-hardware.info/?probe=e8aca06194) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [d027a503a5](https://bsd-hardware.info/?probe=d027a503a5) | Sep 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [55c82d4dd0](https://bsd-hardware.info/?probe=55c82d4dd0) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [af8f180c2c](https://bsd-hardware.info/?probe=af8f180c2c) | Sep 17, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a9da12dec0](https://bsd-hardware.info/?probe=a9da12dec0) | Sep 17, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [9fc1f66fcc](https://bsd-hardware.info/?probe=9fc1f66fcc) | Sep 16, 2022 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [eb09d789de](https://bsd-hardware.info/?probe=eb09d789de) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [3b66741f97](https://bsd-hardware.info/?probe=3b66741f97) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [5361453e6a](https://bsd-hardware.info/?probe=5361453e6a) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | Notebook    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e8848edf41](https://bsd-hardware.info/?probe=e8848edf41) | Sep 13, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [d3ee67f09b](https://bsd-hardware.info/?probe=d3ee67f09b) | Sep 13, 2022 |
| HP            | 18E7                        | Desktop     | [f09635a7ee](https://bsd-hardware.info/?probe=f09635a7ee) | Sep 12, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [66e543ee47](https://bsd-hardware.info/?probe=66e543ee47) | Sep 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [2b4e2212dc](https://bsd-hardware.info/?probe=2b4e2212dc) | Sep 12, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [71e53af7f9](https://bsd-hardware.info/?probe=71e53af7f9) | Sep 12, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [32e9f95095](https://bsd-hardware.info/?probe=32e9f95095) | Sep 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [37588a8565](https://bsd-hardware.info/?probe=37588a8565) | Sep 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [836927cf63](https://bsd-hardware.info/?probe=836927cf63) | Sep 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8eb8bf52d4](https://bsd-hardware.info/?probe=8eb8bf52d4) | Sep 10, 2022 |
| Sophos        | SG                          | Firewall    | [0213c8bb69](https://bsd-hardware.info/?probe=0213c8bb69) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [3c2b784001](https://bsd-hardware.info/?probe=3c2b784001) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [581219cbc5](https://bsd-hardware.info/?probe=581219cbc5) | Sep 09, 2022 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [c25d3df4e2](https://bsd-hardware.info/?probe=c25d3df4e2) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [6130d9c1d0](https://bsd-hardware.info/?probe=6130d9c1d0) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [1d81b77310](https://bsd-hardware.info/?probe=1d81b77310) | Sep 07, 2022 |
| Intel         | SYS-2USM03-6M01E            | Desktop     | [d4f98f18b9](https://bsd-hardware.info/?probe=d4f98f18b9) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b803a767af](https://bsd-hardware.info/?probe=b803a767af) | Sep 06, 2022 |
| Sophos        | SG                          | Firewall    | [4b393a08cd](https://bsd-hardware.info/?probe=4b393a08cd) | Sep 06, 2022 |
| CncTion       | N5105-4L                    | Desktop     | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [734a8e61c4](https://bsd-hardware.info/?probe=734a8e61c4) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [c1967c7cf8](https://bsd-hardware.info/?probe=c1967c7cf8) | Sep 04, 2022 |
| CompuLab      | fitlet                      | Mini pc     | [9772776314](https://bsd-hardware.info/?probe=9772776314) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [72cdc4123c](https://bsd-hardware.info/?probe=72cdc4123c) | Sep 03, 2022 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [b7c5b9a51d](https://bsd-hardware.info/?probe=b7c5b9a51d) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [1e05b51bf1](https://bsd-hardware.info/?probe=1e05b51bf1) | Sep 02, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [b0ad128162](https://bsd-hardware.info/?probe=b0ad128162) | Sep 02, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [43a7b45df6](https://bsd-hardware.info/?probe=43a7b45df6) | Sep 01, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [ebedb51d2f](https://bsd-hardware.info/?probe=ebedb51d2f) | Aug 31, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c77b23d1a7](https://bsd-hardware.info/?probe=c77b23d1a7) | Aug 31, 2022 |
| Intel         | DENLOW_WS                   | Desktop     | [067a217959](https://bsd-hardware.info/?probe=067a217959) | Aug 30, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [df3df2855b](https://bsd-hardware.info/?probe=df3df2855b) | Aug 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0f1eabf01e](https://bsd-hardware.info/?probe=0f1eabf01e) | Aug 27, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [184a8697e9](https://bsd-hardware.info/?probe=184a8697e9) | Aug 27, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [1765bd0426](https://bsd-hardware.info/?probe=1765bd0426) | Aug 27, 2022 |
| Sophos        | SG                          | Firewall    | [2d90401126](https://bsd-hardware.info/?probe=2d90401126) | Aug 26, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [10ca365b40](https://bsd-hardware.info/?probe=10ca365b40) | Aug 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [3465c46b7d](https://bsd-hardware.info/?probe=3465c46b7d) | Aug 26, 2022 |
| PC Engines    | APU2                        | Desktop     | [97da53ff14](https://bsd-hardware.info/?probe=97da53ff14) | Aug 25, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [a760a87c5d](https://bsd-hardware.info/?probe=a760a87c5d) | Aug 25, 2022 |
| ASRock        | AD2550-ITX                  | Desktop     | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Dell          | 012KND A00                  | Mini pc     | [8ca6b71124](https://bsd-hardware.info/?probe=8ca6b71124) | Aug 22, 2022 |
| Deciso        | Netboard A20                | Notebook    | [164274c6b4](https://bsd-hardware.info/?probe=164274c6b4) | Aug 22, 2022 |
| HP            | 82B4                        | Desktop     | [5e07fc9831](https://bsd-hardware.info/?probe=5e07fc9831) | Aug 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [7d059d1d0a](https://bsd-hardware.info/?probe=7d059d1d0a) | Aug 22, 2022 |
| Supermicro    | X10SBA-LA                   | Server      | [5a733d841d](https://bsd-hardware.info/?probe=5a733d841d) | Aug 22, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [b32f197fe9](https://bsd-hardware.info/?probe=b32f197fe9) | Aug 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [92bff81bb5](https://bsd-hardware.info/?probe=92bff81bb5) | Aug 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [ccdff6fbea](https://bsd-hardware.info/?probe=ccdff6fbea) | Aug 20, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [295fc511a6](https://bsd-hardware.info/?probe=295fc511a6) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | Notebook    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [1a666e04d4](https://bsd-hardware.info/?probe=1a666e04d4) | Aug 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [8eb0c6ffbe](https://bsd-hardware.info/?probe=8eb0c6ffbe) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fb02323793](https://bsd-hardware.info/?probe=fb02323793) | Aug 19, 2022 |
| Inventec      | Z CLASS A02                 | Desktop     | [290a94a907](https://bsd-hardware.info/?probe=290a94a907) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | Desktop     | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Sophos        | SG                          | Firewall    | [bed863a141](https://bsd-hardware.info/?probe=bed863a141) | Aug 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [2c0bb11a7b](https://bsd-hardware.info/?probe=2c0bb11a7b) | Aug 17, 2022 |
| Sophos        | UTM                         | Firewall    | [b70e2c4189](https://bsd-hardware.info/?probe=b70e2c4189) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e67200aee1](https://bsd-hardware.info/?probe=e67200aee1) | Aug 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef2a61855a](https://bsd-hardware.info/?probe=ef2a61855a) | Aug 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e23ed854ed](https://bsd-hardware.info/?probe=e23ed854ed) | Aug 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [70ae301a10](https://bsd-hardware.info/?probe=70ae301a10) | Aug 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [90612a700d](https://bsd-hardware.info/?probe=90612a700d) | Aug 14, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [6c697b3312](https://bsd-hardware.info/?probe=6c697b3312) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [6e7e782b00](https://bsd-hardware.info/?probe=6e7e782b00) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [3d46e0eace](https://bsd-hardware.info/?probe=3d46e0eace) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [c961cea235](https://bsd-hardware.info/?probe=c961cea235) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| Dell          | 012KND A00                  | Mini pc     | [557cf9cb1b](https://bsd-hardware.info/?probe=557cf9cb1b) | Aug 12, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [5ceace59c1](https://bsd-hardware.info/?probe=5ceace59c1) | Aug 12, 2022 |
| Sophos        | SG                          | Firewall    | [96d3e064b2](https://bsd-hardware.info/?probe=96d3e064b2) | Aug 12, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [d06e05c67a](https://bsd-hardware.info/?probe=d06e05c67a) | Aug 12, 2022 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [3de3724488](https://bsd-hardware.info/?probe=3de3724488) | Aug 12, 2022 |
| HP            | 82B4                        | Desktop     | [d3fd85a7b6](https://bsd-hardware.info/?probe=d3fd85a7b6) | Aug 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fe8deedda3](https://bsd-hardware.info/?probe=fe8deedda3) | Aug 11, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d3f51a01b1](https://bsd-hardware.info/?probe=d3f51a01b1) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [80e867e04c](https://bsd-hardware.info/?probe=80e867e04c) | Aug 10, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [afca16a0bd](https://bsd-hardware.info/?probe=afca16a0bd) | Aug 09, 2022 |
| NF541         | 1.0                         | Desktop     | [dcde0e7a44](https://bsd-hardware.info/?probe=dcde0e7a44) | Aug 09, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| ASUSTek       | F6A                         | Notebook    | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| HP            | 8103 A01                    | Mini pc     | [720f185f7b](https://bsd-hardware.info/?probe=720f185f7b) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [64768cfe88](https://bsd-hardware.info/?probe=64768cfe88) | Aug 07, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [75ffbbae85](https://bsd-hardware.info/?probe=75ffbbae85) | Aug 07, 2022 |
| HP            | 18E4                        | Desktop     | [7408fe969c](https://bsd-hardware.info/?probe=7408fe969c) | Aug 07, 2022 |
| HP            | 213D A01                    | Desktop     | [383712cf94](https://bsd-hardware.info/?probe=383712cf94) | Aug 06, 2022 |
| HP            | 213D A01                    | Desktop     | [e28886f86e](https://bsd-hardware.info/?probe=e28886f86e) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [9e69d3a39f](https://bsd-hardware.info/?probe=9e69d3a39f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [e68fb8c88e](https://bsd-hardware.info/?probe=e68fb8c88e) | Aug 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [b36e9a7b2e](https://bsd-hardware.info/?probe=b36e9a7b2e) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [ae62a89080](https://bsd-hardware.info/?probe=ae62a89080) | Aug 05, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [69214b0c79](https://bsd-hardware.info/?probe=69214b0c79) | Aug 04, 2022 |
| PC Engines    | apu4                        | Desktop     | [2ae838d489](https://bsd-hardware.info/?probe=2ae838d489) | Aug 02, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [0b2d0398cd](https://bsd-hardware.info/?probe=0b2d0398cd) | Aug 01, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f2590dea4b](https://bsd-hardware.info/?probe=f2590dea4b) | Aug 01, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [d50ffab1cc](https://bsd-hardware.info/?probe=d50ffab1cc) | Aug 01, 2022 |
| ASUSTek       | P5W64 WS Pro                | Desktop     | [f05a901a30](https://bsd-hardware.info/?probe=f05a901a30) | Aug 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [f891511390](https://bsd-hardware.info/?probe=f891511390) | Jul 30, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [0d0b0c3f9e](https://bsd-hardware.info/?probe=0d0b0c3f9e) | Jul 29, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [6cac72ef69](https://bsd-hardware.info/?probe=6cac72ef69) | Jul 28, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7cc4f8754f](https://bsd-hardware.info/?probe=7cc4f8754f) | Jul 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fa1e69b519](https://bsd-hardware.info/?probe=fa1e69b519) | Jul 27, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [91165a8899](https://bsd-hardware.info/?probe=91165a8899) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9df3c644b9](https://bsd-hardware.info/?probe=9df3c644b9) | Jul 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fd67eb14ae](https://bsd-hardware.info/?probe=fd67eb14ae) | Jul 26, 2022 |
| ZOTAC         | Unknown                     | Desktop     | [2f701b55fc](https://bsd-hardware.info/?probe=2f701b55fc) | Jul 25, 2022 |
| Sophos        | SG                          | Firewall    | [8e461fa0e9](https://bsd-hardware.info/?probe=8e461fa0e9) | Jul 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [8830b5ba19](https://bsd-hardware.info/?probe=8830b5ba19) | Jul 24, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [37ce098399](https://bsd-hardware.info/?probe=37ce098399) | Jul 23, 2022 |
| Sophos        | UTM                         | Firewall    | [4ba42eb6db](https://bsd-hardware.info/?probe=4ba42eb6db) | Jul 23, 2022 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [df31840a7e](https://bsd-hardware.info/?probe=df31840a7e) | Jul 22, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [8f910e599b](https://bsd-hardware.info/?probe=8f910e599b) | Jul 21, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [48854ed05e](https://bsd-hardware.info/?probe=48854ed05e) | Jul 21, 2022 |
| Biostar       | J4105NHU                    | Desktop     | [1b6748d4f7](https://bsd-hardware.info/?probe=1b6748d4f7) | Jul 19, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [4b0bdf58dd](https://bsd-hardware.info/?probe=4b0bdf58dd) | Jul 18, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [e3461d0ff8](https://bsd-hardware.info/?probe=e3461d0ff8) | Jul 17, 2022 |
| Supermicro    | A2SAP-HA                    | Desktop     | [27c6228555](https://bsd-hardware.info/?probe=27c6228555) | Jul 17, 2022 |
| YANYU         | H87SL VER:1.3               | Desktop     | [fda62409ee](https://bsd-hardware.info/?probe=fda62409ee) | Jul 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| PC Engines    | APU3                        | Desktop     | [2b20f47024](https://bsd-hardware.info/?probe=2b20f47024) | Jul 15, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [747bebe8d4](https://bsd-hardware.info/?probe=747bebe8d4) | Jul 14, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [2a52f27ffe](https://bsd-hardware.info/?probe=2a52f27ffe) | Jul 13, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [be86d81d29](https://bsd-hardware.info/?probe=be86d81d29) | Jul 13, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [75132f9078](https://bsd-hardware.info/?probe=75132f9078) | Jul 13, 2022 |
| ASRock        | Z97 Professional            | Desktop     | [c1c177fbb0](https://bsd-hardware.info/?probe=c1c177fbb0) | Jul 12, 2022 |
| HP            | 1790                        | Desktop     | [bc5988d764](https://bsd-hardware.info/?probe=bc5988d764) | Jul 11, 2022 |
| NF541         | 1.0                         | Desktop     | [00cab93f40](https://bsd-hardware.info/?probe=00cab93f40) | Jul 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [e42f50fe0f](https://bsd-hardware.info/?probe=e42f50fe0f) | Jul 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [b0380fb22c](https://bsd-hardware.info/?probe=b0380fb22c) | Jul 09, 2022 |
| Supermicro    | X11SCH-F                    | Server      | [1ad1a2496b](https://bsd-hardware.info/?probe=1ad1a2496b) | Jul 08, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [e7d923f138](https://bsd-hardware.info/?probe=e7d923f138) | Jul 07, 2022 |
| Shuttle       | DS437                       | Notebook    | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | Notebook    | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Supermicro    | X11SCH-LN4F                 | Server      | [db74ee9bf8](https://bsd-hardware.info/?probe=db74ee9bf8) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [71efa2b0b9](https://bsd-hardware.info/?probe=71efa2b0b9) | Jul 06, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [342ef61cdc](https://bsd-hardware.info/?probe=342ef61cdc) | Jul 05, 2022 |
| NF541S        | 1.0                         | Desktop     | [937fe3af39](https://bsd-hardware.info/?probe=937fe3af39) | Jul 04, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c8a69b3805](https://bsd-hardware.info/?probe=c8a69b3805) | Jul 04, 2022 |
| Sophos        | SG                          | Firewall    | [d293fb6146](https://bsd-hardware.info/?probe=d293fb6146) | Jul 03, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Sophos        | SG                          | Firewall    | [13a5a5972e](https://bsd-hardware.info/?probe=13a5a5972e) | Jul 03, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [907e22dbb6](https://bsd-hardware.info/?probe=907e22dbb6) | Jul 03, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [40c8fdfafa](https://bsd-hardware.info/?probe=40c8fdfafa) | Jul 02, 2022 |
| HP            | 213D A01                    | Desktop     | [21af8c270f](https://bsd-hardware.info/?probe=21af8c270f) | Jul 01, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [adaa197bf6](https://bsd-hardware.info/?probe=adaa197bf6) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [35f24d802a](https://bsd-hardware.info/?probe=35f24d802a) | Jun 30, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e8f496791d](https://bsd-hardware.info/?probe=e8f496791d) | Jun 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [8e6519f26f](https://bsd-hardware.info/?probe=8e6519f26f) | Jun 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [85c0c08d91](https://bsd-hardware.info/?probe=85c0c08d91) | Jun 29, 2022 |
| ASRock        | N3700M                      | Desktop     | [3896fd5bc2](https://bsd-hardware.info/?probe=3896fd5bc2) | Jun 29, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [28928d9ad4](https://bsd-hardware.info/?probe=28928d9ad4) | Jun 28, 2022 |
| Intel         | S5500BC E25124-452          | Server      | [801632fa6f](https://bsd-hardware.info/?probe=801632fa6f) | Jun 27, 2022 |
| Supermicro    | X10SBAA                     | Server      | [588a497894](https://bsd-hardware.info/?probe=588a497894) | Jun 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7fcdb93a4b](https://bsd-hardware.info/?probe=7fcdb93a4b) | Jun 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [8ab4302d97](https://bsd-hardware.info/?probe=8ab4302d97) | Jun 26, 2022 |
| Sophos        | SG                          | Firewall    | [3c15c394b7](https://bsd-hardware.info/?probe=3c15c394b7) | Jun 26, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a8b0c828f8](https://bsd-hardware.info/?probe=a8b0c828f8) | Jun 26, 2022 |
| PC Engines    | APU2                        | Desktop     | [3e4fbe09f1](https://bsd-hardware.info/?probe=3e4fbe09f1) | Jun 26, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [ce4dc5e6ab](https://bsd-hardware.info/?probe=ce4dc5e6ab) | Jun 25, 2022 |
| MSI           | MS-B120                     | Mini pc     | [aa27c1dfd0](https://bsd-hardware.info/?probe=aa27c1dfd0) | Jun 25, 2022 |
| Biostar       | J4105NHU                    | Desktop     | [9419973ba0](https://bsd-hardware.info/?probe=9419973ba0) | Jun 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ab15560f42](https://bsd-hardware.info/?probe=ab15560f42) | Jun 25, 2022 |
| Dell          | 04JN2K A09                  | Server      | [ff8f57ee67](https://bsd-hardware.info/?probe=ff8f57ee67) | Jun 25, 2022 |
| Dell          | 0H5N7P A02                  | Server      | [7713da37a9](https://bsd-hardware.info/?probe=7713da37a9) | Jun 25, 2022 |
| Sophos        | SG                          | Firewall    | [532927ba49](https://bsd-hardware.info/?probe=532927ba49) | Jun 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6c72a0dca7](https://bsd-hardware.info/?probe=6c72a0dca7) | Jun 24, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [bfcc8f1f66](https://bsd-hardware.info/?probe=bfcc8f1f66) | Jun 24, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [af1a9cf253](https://bsd-hardware.info/?probe=af1a9cf253) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [18f9e5bf9c](https://bsd-hardware.info/?probe=18f9e5bf9c) | Jun 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [de9163945f](https://bsd-hardware.info/?probe=de9163945f) | Jun 23, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [e8f3acf486](https://bsd-hardware.info/?probe=e8f3acf486) | Jun 23, 2022 |
| PC Engines    | apu4                        | Desktop     | [d7e6f088d0](https://bsd-hardware.info/?probe=d7e6f088d0) | Jun 22, 2022 |
| Supermicro    | A2SDi-LN4F                  | Desktop     | [72860a723c](https://bsd-hardware.info/?probe=72860a723c) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [62a2455a8b](https://bsd-hardware.info/?probe=62a2455a8b) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [fb1ffe9c0d](https://bsd-hardware.info/?probe=fb1ffe9c0d) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [24b47422c7](https://bsd-hardware.info/?probe=24b47422c7) | Jun 22, 2022 |
| MSI           | B85M-E45                    | Desktop     | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| ASUSTek       | H110T                       | Desktop     | [a4a51d110b](https://bsd-hardware.info/?probe=a4a51d110b) | Jun 20, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c499767b0](https://bsd-hardware.info/?probe=5c499767b0) | Jun 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [c9303dab91](https://bsd-hardware.info/?probe=c9303dab91) | Jun 19, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [b576f09eec](https://bsd-hardware.info/?probe=b576f09eec) | Jun 17, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [60df3db3ab](https://bsd-hardware.info/?probe=60df3db3ab) | Jun 16, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [29a05b66f3](https://bsd-hardware.info/?probe=29a05b66f3) | Jun 15, 2022 |
| Sophos        | UTM                         | Firewall    | [7d81c953d5](https://bsd-hardware.info/?probe=7d81c953d5) | Jun 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [b7540c1e4a](https://bsd-hardware.info/?probe=b7540c1e4a) | Jun 14, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [7626993227](https://bsd-hardware.info/?probe=7626993227) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [1cc180ad27](https://bsd-hardware.info/?probe=1cc180ad27) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [36f6b6f077](https://bsd-hardware.info/?probe=36f6b6f077) | Jun 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [96c3b75436](https://bsd-hardware.info/?probe=96c3b75436) | Jun 11, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [bf1e373f8a](https://bsd-hardware.info/?probe=bf1e373f8a) | Jun 10, 2022 |
| HP            | 806A                        | Desktop     | [c3051ac63e](https://bsd-hardware.info/?probe=c3051ac63e) | Jun 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [23d5c4d92d](https://bsd-hardware.info/?probe=23d5c4d92d) | Jun 10, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [cf146946d3](https://bsd-hardware.info/?probe=cf146946d3) | Jun 09, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | Desktop     | [26375bae48](https://bsd-hardware.info/?probe=26375bae48) | Jun 08, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [fd96faf8aa](https://bsd-hardware.info/?probe=fd96faf8aa) | Jun 08, 2022 |
| HP            | 18E4                        | Desktop     | [d63cd86fb5](https://bsd-hardware.info/?probe=d63cd86fb5) | Jun 08, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [37a918bd43](https://bsd-hardware.info/?probe=37a918bd43) | Jun 08, 2022 |
| MSI           | B85M-E45                    | Desktop     | [10e7bbf38a](https://bsd-hardware.info/?probe=10e7bbf38a) | Jun 08, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [d42b40d22c](https://bsd-hardware.info/?probe=d42b40d22c) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | Notebook    | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [6c9ccc6963](https://bsd-hardware.info/?probe=6c9ccc6963) | Jun 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [ad2b0dd980](https://bsd-hardware.info/?probe=ad2b0dd980) | Jun 06, 2022 |
| Sophos        | UTM                         | Firewall    | [c6b9f29f41](https://bsd-hardware.info/?probe=c6b9f29f41) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [d8cd85e3d7](https://bsd-hardware.info/?probe=d8cd85e3d7) | Jun 05, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [b98e41f6a4](https://bsd-hardware.info/?probe=b98e41f6a4) | Jun 05, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [02dce569c9](https://bsd-hardware.info/?probe=02dce569c9) | Jun 04, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [6a0c054bdd](https://bsd-hardware.info/?probe=6a0c054bdd) | Jun 04, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [a3023b3f39](https://bsd-hardware.info/?probe=a3023b3f39) | Jun 04, 2022 |
| HP            | 806A                        | Desktop     | [cc091ee2e2](https://bsd-hardware.info/?probe=cc091ee2e2) | Jun 03, 2022 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [467d85355c](https://bsd-hardware.info/?probe=467d85355c) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [4294ad5419](https://bsd-hardware.info/?probe=4294ad5419) | Jun 01, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [26f2eb61de](https://bsd-hardware.info/?probe=26f2eb61de) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [2da72109a6](https://bsd-hardware.info/?probe=2da72109a6) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ad9772ac7](https://bsd-hardware.info/?probe=9ad9772ac7) | May 31, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fa3ea36bad](https://bsd-hardware.info/?probe=fa3ea36bad) | May 31, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [6beacad396](https://bsd-hardware.info/?probe=6beacad396) | May 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef87e699fb](https://bsd-hardware.info/?probe=ef87e699fb) | May 30, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [7152e4b816](https://bsd-hardware.info/?probe=7152e4b816) | May 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95234abead](https://bsd-hardware.info/?probe=95234abead) | May 28, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [3fa863fea9](https://bsd-hardware.info/?probe=3fa863fea9) | May 27, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [0e21a1eeb0](https://bsd-hardware.info/?probe=0e21a1eeb0) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [cdddbb5d23](https://bsd-hardware.info/?probe=cdddbb5d23) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [7a47fcd920](https://bsd-hardware.info/?probe=7a47fcd920) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a5446262b3](https://bsd-hardware.info/?probe=a5446262b3) | May 27, 2022 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [04a06df827](https://bsd-hardware.info/?probe=04a06df827) | May 27, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [fadb382a5a](https://bsd-hardware.info/?probe=fadb382a5a) | May 26, 2022 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [66f9070856](https://bsd-hardware.info/?probe=66f9070856) | May 23, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [e9e497fc7b](https://bsd-hardware.info/?probe=e9e497fc7b) | May 22, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [b05a8f6ed8](https://bsd-hardware.info/?probe=b05a8f6ed8) | May 22, 2022 |
| Biostar       | J4105NHU                    | Desktop     | [88b74aaf3b](https://bsd-hardware.info/?probe=88b74aaf3b) | May 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f04f129625](https://bsd-hardware.info/?probe=f04f129625) | May 22, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| ZOTAC         | ZBOX-ID18                   | Mini pc     | [26b6fef8c6](https://bsd-hardware.info/?probe=26b6fef8c6) | May 21, 2022 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [c1da3a6a28](https://bsd-hardware.info/?probe=c1da3a6a28) | May 21, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [063d483b50](https://bsd-hardware.info/?probe=063d483b50) | May 20, 2022 |
| HP            | 339A                        | Desktop     | [e6a9b68262](https://bsd-hardware.info/?probe=e6a9b68262) | May 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [042f6c0b45](https://bsd-hardware.info/?probe=042f6c0b45) | May 19, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [24d2bf3524](https://bsd-hardware.info/?probe=24d2bf3524) | May 19, 2022 |
| Dell          | 08V001 A03                  | Server      | [c34d5c2be3](https://bsd-hardware.info/?probe=c34d5c2be3) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [ea6146e013](https://bsd-hardware.info/?probe=ea6146e013) | May 19, 2022 |
| Supermicro    | A2SDi-LN4F                  | Desktop     | [acc4101dc1](https://bsd-hardware.info/?probe=acc4101dc1) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [1b218204b8](https://bsd-hardware.info/?probe=1b218204b8) | May 18, 2022 |
| MSI           | B85M-E45                    | Desktop     | [83ab25156c](https://bsd-hardware.info/?probe=83ab25156c) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [e13c8baa2d](https://bsd-hardware.info/?probe=e13c8baa2d) | May 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [b8579c7f84](https://bsd-hardware.info/?probe=b8579c7f84) | May 17, 2022 |
| IBM           | 00KC500                     | Server      | [7f8395e815](https://bsd-hardware.info/?probe=7f8395e815) | May 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [98b4dea15a](https://bsd-hardware.info/?probe=98b4dea15a) | May 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8c2f853975](https://bsd-hardware.info/?probe=8c2f853975) | May 17, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [311c32e56e](https://bsd-hardware.info/?probe=311c32e56e) | May 17, 2022 |
| Supermicro    | X11SCL-IF                   | Server      | [94ff07cdd9](https://bsd-hardware.info/?probe=94ff07cdd9) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c071b686c2](https://bsd-hardware.info/?probe=c071b686c2) | May 15, 2022 |
| MSI           | MS-7C82                     | Desktop     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [6974f0958e](https://bsd-hardware.info/?probe=6974f0958e) | May 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4fad520626](https://bsd-hardware.info/?probe=4fad520626) | May 14, 2022 |
| ASRock        | E350M1                      | Desktop     | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | Desktop     | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| Sophos        | UTM                         | Firewall    | [fec90c3d92](https://bsd-hardware.info/?probe=fec90c3d92) | May 13, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [54a5041cdf](https://bsd-hardware.info/?probe=54a5041cdf) | May 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [faec798f5c](https://bsd-hardware.info/?probe=faec798f5c) | May 11, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [8cdb309c2e](https://bsd-hardware.info/?probe=8cdb309c2e) | May 11, 2022 |
| Dell          | 0PRWNC A05                  | Server      | [0b239c3286](https://bsd-hardware.info/?probe=0b239c3286) | May 11, 2022 |
| HP            | 213D A01                    | Desktop     | [89955ba84f](https://bsd-hardware.info/?probe=89955ba84f) | May 11, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [0ca5685ce0](https://bsd-hardware.info/?probe=0ca5685ce0) | May 10, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [70c9fd07ac](https://bsd-hardware.info/?probe=70c9fd07ac) | May 09, 2022 |
| HP            | 82A1                        | Desktop     | [34cb091e26](https://bsd-hardware.info/?probe=34cb091e26) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Sophos        | SG                          | Firewall    | [9e16039d35](https://bsd-hardware.info/?probe=9e16039d35) | May 06, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [dc534266df](https://bsd-hardware.info/?probe=dc534266df) | May 06, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [4a4e45585d](https://bsd-hardware.info/?probe=4a4e45585d) | May 06, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [52b6c326c8](https://bsd-hardware.info/?probe=52b6c326c8) | May 05, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [7fd31252a2](https://bsd-hardware.info/?probe=7fd31252a2) | May 04, 2022 |
| friendlyel... | nanopi-r4s                  | Desktop     | [3db2ec8973](https://bsd-hardware.info/?probe=3db2ec8973) | May 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [b96fd74ab0](https://bsd-hardware.info/?probe=b96fd74ab0) | May 03, 2022 |
| Sophos        | XG                          | Firewall    | [19b1a90a3c](https://bsd-hardware.info/?probe=19b1a90a3c) | May 03, 2022 |
| Sophos        | SG                          | Firewall    | [5109c6e2e4](https://bsd-hardware.info/?probe=5109c6e2e4) | May 03, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [14d02a8209](https://bsd-hardware.info/?probe=14d02a8209) | May 03, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [3997ff79e4](https://bsd-hardware.info/?probe=3997ff79e4) | May 03, 2022 |
| Sophos        | XG                          | Firewall    | [bec4979a46](https://bsd-hardware.info/?probe=bec4979a46) | May 03, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [e4c8d6c787](https://bsd-hardware.info/?probe=e4c8d6c787) | May 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5e8168a980](https://bsd-hardware.info/?probe=5e8168a980) | Apr 30, 2022 |
| Sophos        | SG                          | Firewall    | [ca2608d67f](https://bsd-hardware.info/?probe=ca2608d67f) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| OEM           | 1.0                         | Desktop     | [36e78ab638](https://bsd-hardware.info/?probe=36e78ab638) | Apr 29, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [54fe9e7529](https://bsd-hardware.info/?probe=54fe9e7529) | Apr 29, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [22b192afca](https://bsd-hardware.info/?probe=22b192afca) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| Sophos        | SG                          | Firewall    | [dd94f9dfe6](https://bsd-hardware.info/?probe=dd94f9dfe6) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0750e29d3c](https://bsd-hardware.info/?probe=0750e29d3c) | Apr 27, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [920eae6f2e](https://bsd-hardware.info/?probe=920eae6f2e) | Apr 27, 2022 |
| Sophos        | SG                          | Firewall    | [92a32f4608](https://bsd-hardware.info/?probe=92a32f4608) | Apr 27, 2022 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [c36f9d6c1d](https://bsd-hardware.info/?probe=c36f9d6c1d) | Apr 26, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [637c28d728](https://bsd-hardware.info/?probe=637c28d728) | Apr 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2a8ebfdb92](https://bsd-hardware.info/?probe=2a8ebfdb92) | Apr 25, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [86c4af7ca4](https://bsd-hardware.info/?probe=86c4af7ca4) | Apr 25, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6afa33e8f8](https://bsd-hardware.info/?probe=6afa33e8f8) | Apr 24, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [1ce660f88e](https://bsd-hardware.info/?probe=1ce660f88e) | Apr 24, 2022 |
| Lenovo        | B570 1068FQG                | Notebook    | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| PC Engines    | apu4                        | Desktop     | [ae39e5adc0](https://bsd-hardware.info/?probe=ae39e5adc0) | Apr 22, 2022 |
| ASRock        | X79 Extreme6/GB             | Desktop     | [cd85d68dcd](https://bsd-hardware.info/?probe=cd85d68dcd) | Apr 21, 2022 |
| CheckPoint    | T-140-00                    | Desktop     | [8e2c861ecf](https://bsd-hardware.info/?probe=8e2c861ecf) | Apr 19, 2022 |
| CheckPoint    | T-140-00                    | Desktop     | [8f0c5b5334](https://bsd-hardware.info/?probe=8f0c5b5334) | Apr 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [47ddf6b2bd](https://bsd-hardware.info/?probe=47ddf6b2bd) | Apr 19, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [7a591def91](https://bsd-hardware.info/?probe=7a591def91) | Apr 19, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8d7236247d](https://bsd-hardware.info/?probe=8d7236247d) | Apr 18, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [9ff2cbdcf1](https://bsd-hardware.info/?probe=9ff2cbdcf1) | Apr 18, 2022 |
| Supermicro    | X11SCL-IF                   | Server      | [9a63b99387](https://bsd-hardware.info/?probe=9a63b99387) | Apr 18, 2022 |
| Supermicro    | A2SDi-2C-HLN4F              | Server      | [3ac63aed2d](https://bsd-hardware.info/?probe=3ac63aed2d) | Apr 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [0914d63c72](https://bsd-hardware.info/?probe=0914d63c72) | Apr 16, 2022 |
| Sophos        | SG                          | Firewall    | [cdf2f7cd49](https://bsd-hardware.info/?probe=cdf2f7cd49) | Apr 16, 2022 |
| Supermicro    | M11SDV-4C-LN4F              | Server      | [e398b10cea](https://bsd-hardware.info/?probe=e398b10cea) | Apr 15, 2022 |
| Sophos        | UTM                         | Firewall    | [00731ba6eb](https://bsd-hardware.info/?probe=00731ba6eb) | Apr 15, 2022 |
| AMI           | Intel                       | Notebook    | [db87d63d35](https://bsd-hardware.info/?probe=db87d63d35) | Apr 15, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [d045a4acad](https://bsd-hardware.info/?probe=d045a4acad) | Apr 14, 2022 |
| Intel         | NUC7JYB J67967-402          | Mini pc     | [e94a3a5a08](https://bsd-hardware.info/?probe=e94a3a5a08) | Apr 14, 2022 |
| AMI           | Intel                       | Notebook    | [8dc710d126](https://bsd-hardware.info/?probe=8dc710d126) | Apr 14, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [0aa324c0d5](https://bsd-hardware.info/?probe=0aa324c0d5) | Apr 14, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3365444265](https://bsd-hardware.info/?probe=3365444265) | Apr 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [4ec1e3548c](https://bsd-hardware.info/?probe=4ec1e3548c) | Apr 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [efb76ec7fe](https://bsd-hardware.info/?probe=efb76ec7fe) | Apr 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad14582532](https://bsd-hardware.info/?probe=ad14582532) | Apr 13, 2022 |
| Intel         | D53427RKE G87971-403        | Desktop     | [1a1de076c7](https://bsd-hardware.info/?probe=1a1de076c7) | Apr 13, 2022 |
| Dell          | Latitude E6440              | Notebook    | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5f2a882529](https://bsd-hardware.info/?probe=5f2a882529) | Apr 11, 2022 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [752f962123](https://bsd-hardware.info/?probe=752f962123) | Apr 10, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e2aa6d2b4d](https://bsd-hardware.info/?probe=e2aa6d2b4d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| PC Engines    | APU2                        | Desktop     | [ae2d120c7c](https://bsd-hardware.info/?probe=ae2d120c7c) | Apr 10, 2022 |
| Shuttle       | DS10U                       | Desktop     | [7d5919eb2b](https://bsd-hardware.info/?probe=7d5919eb2b) | Apr 10, 2022 |
| Sophos        | SG                          | Firewall    | [53ba75464f](https://bsd-hardware.info/?probe=53ba75464f) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [6835aa43e3](https://bsd-hardware.info/?probe=6835aa43e3) | Apr 09, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [2f24f06f29](https://bsd-hardware.info/?probe=2f24f06f29) | Apr 08, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [8b21109cd4](https://bsd-hardware.info/?probe=8b21109cd4) | Apr 08, 2022 |
| MSI           | MS-7369                     | Desktop     | [25f2161cac](https://bsd-hardware.info/?probe=25f2161cac) | Apr 08, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [44327ad768](https://bsd-hardware.info/?probe=44327ad768) | Apr 07, 2022 |
| Supermicro    | H12SSW-iN                   | Server      | [2e389db2dd](https://bsd-hardware.info/?probe=2e389db2dd) | Apr 07, 2022 |
| HP            | 213D A01                    | Desktop     | [3f6e05c14d](https://bsd-hardware.info/?probe=3f6e05c14d) | Apr 07, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [3271551472](https://bsd-hardware.info/?probe=3271551472) | Apr 06, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [9ffa0cc352](https://bsd-hardware.info/?probe=9ffa0cc352) | Apr 06, 2022 |
| Dell          | Precision M4800             | Notebook    | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [69304a74cc](https://bsd-hardware.info/?probe=69304a74cc) | Apr 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [4cf896e25a](https://bsd-hardware.info/?probe=4cf896e25a) | Apr 06, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [90663f7aa0](https://bsd-hardware.info/?probe=90663f7aa0) | Apr 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [64d42b9c5f](https://bsd-hardware.info/?probe=64d42b9c5f) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| HP            | 213D A01                    | Desktop     | [238d8bbcde](https://bsd-hardware.info/?probe=238d8bbcde) | Apr 04, 2022 |
| PC Engines    | APU2                        | Desktop     | [69cb42c07b](https://bsd-hardware.info/?probe=69cb42c07b) | Apr 02, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1bdaf4bb77](https://bsd-hardware.info/?probe=1bdaf4bb77) | Apr 01, 2022 |
| HP            | 3396                        | Desktop     | [7a60daeaef](https://bsd-hardware.info/?probe=7a60daeaef) | Apr 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [9b6f9eac6f](https://bsd-hardware.info/?probe=9b6f9eac6f) | Apr 01, 2022 |
| PC Engines    | APU                         | Desktop     | [c71152505f](https://bsd-hardware.info/?probe=c71152505f) | Apr 01, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [3df6a01030](https://bsd-hardware.info/?probe=3df6a01030) | Mar 31, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5ea7eaeb0](https://bsd-hardware.info/?probe=b5ea7eaeb0) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Sophos        | XG                          | Firewall    | [59d01ec60e](https://bsd-hardware.info/?probe=59d01ec60e) | Mar 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c597fb4337](https://bsd-hardware.info/?probe=c597fb4337) | Mar 29, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [0542f7a16d](https://bsd-hardware.info/?probe=0542f7a16d) | Mar 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [4383e28183](https://bsd-hardware.info/?probe=4383e28183) | Mar 29, 2022 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [36896a719d](https://bsd-hardware.info/?probe=36896a719d) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [a4382a2a0b](https://bsd-hardware.info/?probe=a4382a2a0b) | Mar 29, 2022 |
| ASRock        | X79 Extreme6/GB             | Desktop     | [0646607953](https://bsd-hardware.info/?probe=0646607953) | Mar 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [a35c56ca36](https://bsd-hardware.info/?probe=a35c56ca36) | Mar 28, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [f09a26de6f](https://bsd-hardware.info/?probe=f09a26de6f) | Mar 27, 2022 |
| Sophos        | UTM                         | Firewall    | [6362bd5137](https://bsd-hardware.info/?probe=6362bd5137) | Mar 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [19ff042007](https://bsd-hardware.info/?probe=19ff042007) | Mar 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [92b08cda4a](https://bsd-hardware.info/?probe=92b08cda4a) | Mar 26, 2022 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [9e5d1c9daa](https://bsd-hardware.info/?probe=9e5d1c9daa) | Mar 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [da94141898](https://bsd-hardware.info/?probe=da94141898) | Mar 26, 2022 |
| PC Engines    | apu4                        | Desktop     | [d95599aa97](https://bsd-hardware.info/?probe=d95599aa97) | Mar 25, 2022 |
| Unknown       | Unknown                     | Firewall    | [55b930eb8f](https://bsd-hardware.info/?probe=55b930eb8f) | Mar 25, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [190fe4d13f](https://bsd-hardware.info/?probe=190fe4d13f) | Mar 24, 2022 |
| Supermicro    | X10SLM-F                    | Server      | [4ade9fbcf8](https://bsd-hardware.info/?probe=4ade9fbcf8) | Mar 24, 2022 |
| MSI           | MS-A6221 100                | Desktop     | [ba62f48990](https://bsd-hardware.info/?probe=ba62f48990) | Mar 23, 2022 |
| PC Engines    | APU3                        | Desktop     | [0a68bdf721](https://bsd-hardware.info/?probe=0a68bdf721) | Mar 23, 2022 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [e0a7c6b62f](https://bsd-hardware.info/?probe=e0a7c6b62f) | Mar 23, 2022 |
| Supermicro    | X11SCL-IF                   | Server      | [0d1efa6544](https://bsd-hardware.info/?probe=0d1efa6544) | Mar 23, 2022 |
| Notebook      | N13xWU                      | Notebook    | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | Notebook    | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Lenovo        | ThinkPad Yoga 460 20ELS1... | Convertible | [c216d655ae](https://bsd-hardware.info/?probe=c216d655ae) | Mar 22, 2022 |
| PC Engines    | apu4                        | Desktop     | [4f2d362dd2](https://bsd-hardware.info/?probe=4f2d362dd2) | Mar 22, 2022 |
| Dell          | Latitude E6500              | Notebook    | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | Notebook    | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [f30a0c8dd5](https://bsd-hardware.info/?probe=f30a0c8dd5) | Mar 22, 2022 |
| Deciso        | Netboard A20                | Notebook    | [8ded6d9af6](https://bsd-hardware.info/?probe=8ded6d9af6) | Mar 21, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [82c6ad104b](https://bsd-hardware.info/?probe=82c6ad104b) | Mar 21, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [6ceff4eca1](https://bsd-hardware.info/?probe=6ceff4eca1) | Mar 21, 2022 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [3df56777e3](https://bsd-hardware.info/?probe=3df56777e3) | Mar 21, 2022 |
| Supermicro    | A1SRi-2758F                 | Mini pc     | [afbf43e038](https://bsd-hardware.info/?probe=afbf43e038) | Mar 20, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | Notebook    | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | Notebook    | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [c81d79bbe7](https://bsd-hardware.info/?probe=c81d79bbe7) | Mar 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f41d89a7e9](https://bsd-hardware.info/?probe=f41d89a7e9) | Mar 17, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [7aac0f4b94](https://bsd-hardware.info/?probe=7aac0f4b94) | Mar 16, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [aa18c11016](https://bsd-hardware.info/?probe=aa18c11016) | Mar 16, 2022 |
| Thomas-Kre... | P9A-I/C2750/4L              | Firewall    | [e2d107e38a](https://bsd-hardware.info/?probe=e2d107e38a) | Mar 16, 2022 |
| HP            | 8299                        | Desktop     | [6876d2d37d](https://bsd-hardware.info/?probe=6876d2d37d) | Mar 16, 2022 |
| PC Engines    | APU2                        | Desktop     | [6ea85fac4f](https://bsd-hardware.info/?probe=6ea85fac4f) | Mar 15, 2022 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [2c65cbd768](https://bsd-hardware.info/?probe=2c65cbd768) | Mar 15, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [73726dfe1a](https://bsd-hardware.info/?probe=73726dfe1a) | Mar 15, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [2c002dc6a8](https://bsd-hardware.info/?probe=2c002dc6a8) | Mar 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [c2b8c7eebb](https://bsd-hardware.info/?probe=c2b8c7eebb) | Mar 14, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [23faf80bfe](https://bsd-hardware.info/?probe=23faf80bfe) | Mar 14, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [6d6b13abf9](https://bsd-hardware.info/?probe=6d6b13abf9) | Mar 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [f9045f060a](https://bsd-hardware.info/?probe=f9045f060a) | Mar 13, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [d60b00e2c6](https://bsd-hardware.info/?probe=d60b00e2c6) | Mar 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [8152ca0911](https://bsd-hardware.info/?probe=8152ca0911) | Mar 13, 2022 |
| Gigabyte      | N3150ND3V                   | Desktop     | [382a3e1fbb](https://bsd-hardware.info/?probe=382a3e1fbb) | Mar 12, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [592ff80875](https://bsd-hardware.info/?probe=592ff80875) | Mar 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [b8303d5089](https://bsd-hardware.info/?probe=b8303d5089) | Mar 12, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [5c8df4dcad](https://bsd-hardware.info/?probe=5c8df4dcad) | Mar 10, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [045fa8357e](https://bsd-hardware.info/?probe=045fa8357e) | Mar 10, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| NF541         | 1.0                         | Desktop     | [fc2b2bb98d](https://bsd-hardware.info/?probe=fc2b2bb98d) | Mar 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [3ee10c1ab2](https://bsd-hardware.info/?probe=3ee10c1ab2) | Mar 09, 2022 |
| Koloe         | X58                         | Desktop     | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [fea4a692a9](https://bsd-hardware.info/?probe=fea4a692a9) | Mar 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [e89b377c53](https://bsd-hardware.info/?probe=e89b377c53) | Mar 08, 2022 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [bc73c8dc68](https://bsd-hardware.info/?probe=bc73c8dc68) | Mar 08, 2022 |
| Intel         | DENLOW_WS                   | Desktop     | [bab9d9dd6d](https://bsd-hardware.info/?probe=bab9d9dd6d) | Mar 08, 2022 |
| AEWIN         | CB-7979                     | Notebook    | [ec1e865bbd](https://bsd-hardware.info/?probe=ec1e865bbd) | Mar 07, 2022 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [e3698a706b](https://bsd-hardware.info/?probe=e3698a706b) | Mar 07, 2022 |
| Koloe         | X58                         | Desktop     | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| Intel         | DX79TO AAG28805-401         | Desktop     | [431b37f050](https://bsd-hardware.info/?probe=431b37f050) | Mar 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f8801c62bc](https://bsd-hardware.info/?probe=f8801c62bc) | Mar 05, 2022 |
| CheckPoint    | T-110-00                    | Desktop     | [ecbdeaf92b](https://bsd-hardware.info/?probe=ecbdeaf92b) | Mar 05, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [8ae57434a2](https://bsd-hardware.info/?probe=8ae57434a2) | Mar 03, 2022 |
| Gigabyte      | N3150ND3V                   | Desktop     | [bdf7beae56](https://bsd-hardware.info/?probe=bdf7beae56) | Mar 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ea5f9680c5](https://bsd-hardware.info/?probe=ea5f9680c5) | Mar 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f5eef026f2](https://bsd-hardware.info/?probe=f5eef026f2) | Mar 02, 2022 |
| Dell          | 08V001 A03                  | Server      | [6039440ce8](https://bsd-hardware.info/?probe=6039440ce8) | Mar 02, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [8611347484](https://bsd-hardware.info/?probe=8611347484) | Mar 02, 2022 |
| Protectli     | VP2410                      | Desktop     | [880c57201a](https://bsd-hardware.info/?probe=880c57201a) | Mar 01, 2022 |
| Supermicro    | A2SDi-LN4F                  | Desktop     | [b10f6655d9](https://bsd-hardware.info/?probe=b10f6655d9) | Mar 01, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [2d1bf5a79a](https://bsd-hardware.info/?probe=2d1bf5a79a) | Mar 01, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [df62b83093](https://bsd-hardware.info/?probe=df62b83093) | Feb 28, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [a7e26ec0f5](https://bsd-hardware.info/?probe=a7e26ec0f5) | Feb 27, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [1e8ac02926](https://bsd-hardware.info/?probe=1e8ac02926) | Feb 26, 2022 |
| AAEON         | FWS-2280 V1.0               | Desktop     | [9fba128986](https://bsd-hardware.info/?probe=9fba128986) | Feb 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [a771f78447](https://bsd-hardware.info/?probe=a771f78447) | Feb 26, 2022 |
| PC Engines    | apu4                        | Desktop     | [74c708a6cf](https://bsd-hardware.info/?probe=74c708a6cf) | Feb 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [2bbb963d9f](https://bsd-hardware.info/?probe=2bbb963d9f) | Feb 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [c559dbe233](https://bsd-hardware.info/?probe=c559dbe233) | Feb 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e9bf3549fe](https://bsd-hardware.info/?probe=e9bf3549fe) | Feb 24, 2022 |
| Sophos        | UTM                         | Firewall    | [49c7a56907](https://bsd-hardware.info/?probe=49c7a56907) | Feb 24, 2022 |
| PC Engines    | apu4                        | Desktop     | [ed16e6ac1f](https://bsd-hardware.info/?probe=ed16e6ac1f) | Feb 24, 2022 |
| YANYU         | M9F baytrail                | Desktop     | [3804d3fb1d](https://bsd-hardware.info/?probe=3804d3fb1d) | Feb 24, 2022 |
| ASUSTek       | P11C-I Series               | Desktop     | [f768f45dc2](https://bsd-hardware.info/?probe=f768f45dc2) | Feb 23, 2022 |
| Sophos        | UTM                         | Firewall    | [516b85a53e](https://bsd-hardware.info/?probe=516b85a53e) | Feb 22, 2022 |
| BESSTAR Te... | JB9                         | Desktop     | [e788cec5f5](https://bsd-hardware.info/?probe=e788cec5f5) | Feb 22, 2022 |
| Dell          | Latitude 5591               | Notebook    | [d4d653fba8](https://bsd-hardware.info/?probe=d4d653fba8) | Feb 22, 2022 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [7e87ceea76](https://bsd-hardware.info/?probe=7e87ceea76) | Feb 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e55cb672b2](https://bsd-hardware.info/?probe=e55cb672b2) | Feb 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [db8e4dc1f5](https://bsd-hardware.info/?probe=db8e4dc1f5) | Feb 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [9a280f5e25](https://bsd-hardware.info/?probe=9a280f5e25) | Feb 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0ea56ed26f](https://bsd-hardware.info/?probe=0ea56ed26f) | Feb 19, 2022 |
| BESSTAR Te... | JB9                         | Desktop     | [7df0c12efe](https://bsd-hardware.info/?probe=7df0c12efe) | Feb 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [883cf2382b](https://bsd-hardware.info/?probe=883cf2382b) | Feb 17, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [1e54f9ca54](https://bsd-hardware.info/?probe=1e54f9ca54) | Feb 17, 2022 |
| ASRock        | 4X4-R1000                   | Desktop     | [c25f53782a](https://bsd-hardware.info/?probe=c25f53782a) | Feb 17, 2022 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [98a6e928d3](https://bsd-hardware.info/?probe=98a6e928d3) | Feb 17, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [f1892cd12c](https://bsd-hardware.info/?probe=f1892cd12c) | Feb 17, 2022 |
| YANYU         | M9F baytrail                | Desktop     | [a568d8241d](https://bsd-hardware.info/?probe=a568d8241d) | Feb 16, 2022 |
| ASUSTek       | P11C-M Series               | Desktop     | [459ff0f748](https://bsd-hardware.info/?probe=459ff0f748) | Feb 16, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [db0e0dbb14](https://bsd-hardware.info/?probe=db0e0dbb14) | Feb 16, 2022 |
| Gigabyte      | C246M-WU4-CF                | Desktop     | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cb2ab6f97a](https://bsd-hardware.info/?probe=cb2ab6f97a) | Feb 15, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [4980cae3eb](https://bsd-hardware.info/?probe=4980cae3eb) | Feb 15, 2022 |
| Sophos        | UTM                         | Firewall    | [03a19078c1](https://bsd-hardware.info/?probe=03a19078c1) | Feb 14, 2022 |
| Sophos        | SG                          | Firewall    | [80702937ff](https://bsd-hardware.info/?probe=80702937ff) | Feb 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [53ec9f2960](https://bsd-hardware.info/?probe=53ec9f2960) | Feb 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | Notebook    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [d3d818c49f](https://bsd-hardware.info/?probe=d3d818c49f) | Feb 13, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [038b174183](https://bsd-hardware.info/?probe=038b174183) | Feb 13, 2022 |
| HP            | ProLiant DL380 G6           | Server      | [7e329c839e](https://bsd-hardware.info/?probe=7e329c839e) | Feb 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [923aba4efb](https://bsd-hardware.info/?probe=923aba4efb) | Feb 12, 2022 |
| AOpen         | i67QMx-DV R1.00TS2 55MP6... | Desktop     | [c3b6cdf519](https://bsd-hardware.info/?probe=c3b6cdf519) | Feb 12, 2022 |
| CheckPoint    | T-140-00                    | Desktop     | [e41ba68aa2](https://bsd-hardware.info/?probe=e41ba68aa2) | Feb 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [64cb6534ff](https://bsd-hardware.info/?probe=64cb6534ff) | Feb 11, 2022 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [9cf5790022](https://bsd-hardware.info/?probe=9cf5790022) | Feb 11, 2022 |
| Supermicro    | X11SBA-LN4FA                | Desktop     | [e547e2343a](https://bsd-hardware.info/?probe=e547e2343a) | Feb 10, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [18df27c327](https://bsd-hardware.info/?probe=18df27c327) | Feb 10, 2022 |
| MiTAC         | 5033                        | Notebook    | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| ZOTAC         | ZBOX-MI623/MI643 Rev.00     | Mini pc     | [3a72557967](https://bsd-hardware.info/?probe=3a72557967) | Feb 09, 2022 |
| Supermicro    | X10SBA-LA                   | Server      | [9972006bf4](https://bsd-hardware.info/?probe=9972006bf4) | Feb 09, 2022 |
| Unknown       | Q2XX V1.0                   | Desktop     | [1e3cfd4559](https://bsd-hardware.info/?probe=1e3cfd4559) | Feb 09, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [5a614c6238](https://bsd-hardware.info/?probe=5a614c6238) | Feb 08, 2022 |
| Sophos        | XG                          | Firewall    | [335e21cbaf](https://bsd-hardware.info/?probe=335e21cbaf) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [aff2852632](https://bsd-hardware.info/?probe=aff2852632) | Feb 07, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [619b239937](https://bsd-hardware.info/?probe=619b239937) | Feb 07, 2022 |
| ASRock        | Q1900M                      | Desktop     | [1bb0094772](https://bsd-hardware.info/?probe=1bb0094772) | Feb 07, 2022 |
| Fujitsu       | D3544-Sx S26361-D3544-Sx... | Desktop     | [e279b10250](https://bsd-hardware.info/?probe=e279b10250) | Feb 07, 2022 |
| PC Engines    | apu4                        | Desktop     | [1bde386ab2](https://bsd-hardware.info/?probe=1bde386ab2) | Feb 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [0eb520b964](https://bsd-hardware.info/?probe=0eb520b964) | Feb 06, 2022 |
| ASRock        | Q1900M                      | Desktop     | [1840d289c9](https://bsd-hardware.info/?probe=1840d289c9) | Feb 06, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [2764fb2282](https://bsd-hardware.info/?probe=2764fb2282) | Feb 06, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [5b1ca4533f](https://bsd-hardware.info/?probe=5b1ca4533f) | Feb 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d38089ced](https://bsd-hardware.info/?probe=8d38089ced) | Feb 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [12e979c82a](https://bsd-hardware.info/?probe=12e979c82a) | Feb 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [2a3867a849](https://bsd-hardware.info/?probe=2a3867a849) | Feb 06, 2022 |
| Unknown       | Q2XX V1.0                   | Desktop     | [633ad33c05](https://bsd-hardware.info/?probe=633ad33c05) | Feb 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [8454a78fb4](https://bsd-hardware.info/?probe=8454a78fb4) | Feb 05, 2022 |
| Intel         | S1200BTL E98681-353         | Server      | [d1ca9353b9](https://bsd-hardware.info/?probe=d1ca9353b9) | Feb 05, 2022 |
| CheckPoint    | T-140-00                    | Desktop     | [92af3888c0](https://bsd-hardware.info/?probe=92af3888c0) | Feb 04, 2022 |
| CheckPoint    | T-110-00                    | Desktop     | [65f271c2c8](https://bsd-hardware.info/?probe=65f271c2c8) | Feb 04, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [d0c6e027a0](https://bsd-hardware.info/?probe=d0c6e027a0) | Feb 04, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [4cf0ffcbf6](https://bsd-hardware.info/?probe=4cf0ffcbf6) | Feb 04, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [0d9e3c927f](https://bsd-hardware.info/?probe=0d9e3c927f) | Feb 04, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [45d4853cd4](https://bsd-hardware.info/?probe=45d4853cd4) | Feb 03, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [5c5acbbb42](https://bsd-hardware.info/?probe=5c5acbbb42) | Feb 02, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [6d1223c3d1](https://bsd-hardware.info/?probe=6d1223c3d1) | Feb 02, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [b0af5d8891](https://bsd-hardware.info/?probe=b0af5d8891) | Feb 02, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2337ada02](https://bsd-hardware.info/?probe=c2337ada02) | Feb 02, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [faff4c7609](https://bsd-hardware.info/?probe=faff4c7609) | Feb 01, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [8485be3985](https://bsd-hardware.info/?probe=8485be3985) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [82d9df0427](https://bsd-hardware.info/?probe=82d9df0427) | Feb 01, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [ecaeff1a79](https://bsd-hardware.info/?probe=ecaeff1a79) | Feb 01, 2022 |
| BESSTAR Te... | JB9                         | Desktop     | [8f1ac8e4bc](https://bsd-hardware.info/?probe=8f1ac8e4bc) | Jan 31, 2022 |
| Supermicro    | X11SBA-LN4FA                | Desktop     | [d040ad4922](https://bsd-hardware.info/?probe=d040ad4922) | Jan 31, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [67a2a6ba3e](https://bsd-hardware.info/?probe=67a2a6ba3e) | Jan 31, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [1c6453e2e4](https://bsd-hardware.info/?probe=1c6453e2e4) | Jan 31, 2022 |
| PC Engines    | APU3                        | Desktop     | [b03f53313d](https://bsd-hardware.info/?probe=b03f53313d) | Jan 31, 2022 |
| PC Engines    | apu4                        | Desktop     | [1f02497c18](https://bsd-hardware.info/?probe=1f02497c18) | Jan 30, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [b90289bdfa](https://bsd-hardware.info/?probe=b90289bdfa) | Jan 30, 2022 |
| GPD           | G1621-02                    | Notebook    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| SIEMENS       | A5E38156881 RS-AE           | Desktop     | [d1d16a420e](https://bsd-hardware.info/?probe=d1d16a420e) | Jan 30, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [b27a7274cf](https://bsd-hardware.info/?probe=b27a7274cf) | Jan 30, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [292cb706a0](https://bsd-hardware.info/?probe=292cb706a0) | Jan 30, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [74c01cf184](https://bsd-hardware.info/?probe=74c01cf184) | Jan 30, 2022 |
| PC Engines    | APU2                        | Desktop     | [f65e5a625b](https://bsd-hardware.info/?probe=f65e5a625b) | Jan 30, 2022 |
| CheckPoint    | T-120-00                    | Desktop     | [8777e1a17d](https://bsd-hardware.info/?probe=8777e1a17d) | Jan 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cee618086f](https://bsd-hardware.info/?probe=cee618086f) | Jan 29, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [540757d1b7](https://bsd-hardware.info/?probe=540757d1b7) | Jan 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [0a504f17ee](https://bsd-hardware.info/?probe=0a504f17ee) | Jan 29, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [adb4b0f727](https://bsd-hardware.info/?probe=adb4b0f727) | Jan 29, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [eeb7cd8aa9](https://bsd-hardware.info/?probe=eeb7cd8aa9) | Jan 28, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [9c73c01062](https://bsd-hardware.info/?probe=9c73c01062) | Jan 28, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [ba4865faf2](https://bsd-hardware.info/?probe=ba4865faf2) | Jan 28, 2022 |
| PC Engines    | apu1                        | Desktop     | [33819c7652](https://bsd-hardware.info/?probe=33819c7652) | Jan 27, 2022 |
| HP            | 17E2                        | Mini pc     | [fcb0a5ff87](https://bsd-hardware.info/?probe=fcb0a5ff87) | Jan 27, 2022 |
| Supermicro    | A2SDi-LN4F                  | Desktop     | [38f999c445](https://bsd-hardware.info/?probe=38f999c445) | Jan 27, 2022 |
| HP            | 18E4                        | Desktop     | [67080049c6](https://bsd-hardware.info/?probe=67080049c6) | Jan 27, 2022 |
| HP            | 213D A01                    | Desktop     | [659a73beac](https://bsd-hardware.info/?probe=659a73beac) | Jan 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [6831896a2b](https://bsd-hardware.info/?probe=6831896a2b) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [c9f915399a](https://bsd-hardware.info/?probe=c9f915399a) | Jan 25, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [6ca20b88e7](https://bsd-hardware.info/?probe=6ca20b88e7) | Jan 25, 2022 |
| MSI           | GT75VR 7RF                  | Notebook    | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [f4e3c83813](https://bsd-hardware.info/?probe=f4e3c83813) | Jan 24, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [7c53db72f9](https://bsd-hardware.info/?probe=7c53db72f9) | Jan 24, 2022 |
| Biostar       | J4105NHU                    | Desktop     | [8513067567](https://bsd-hardware.info/?probe=8513067567) | Jan 24, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [9ad0c66586](https://bsd-hardware.info/?probe=9ad0c66586) | Jan 23, 2022 |
| HP            | 8648                        | Desktop     | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| HP            | 8103 A01                    | Mini pc     | [e55bb9f973](https://bsd-hardware.info/?probe=e55bb9f973) | Jan 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [8597e1c1e4](https://bsd-hardware.info/?probe=8597e1c1e4) | Jan 22, 2022 |
| Dell          | VEP-4600-V910 0PDG1JA02     | Desktop     | [63699d431a](https://bsd-hardware.info/?probe=63699d431a) | Jan 21, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [52f4bdd7d0](https://bsd-hardware.info/?probe=52f4bdd7d0) | Jan 21, 2022 |
| Supermicro    | X10DRiB                     | Server      | [b4999ca89f](https://bsd-hardware.info/?probe=b4999ca89f) | Jan 21, 2022 |
| Dell          | 0NNNCT A01                  | Desktop     | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Sophos        | SG                          | Firewall    | [4dbab1cdde](https://bsd-hardware.info/?probe=4dbab1cdde) | Jan 21, 2022 |
| Dell          | Latitude E6540              | Notebook    | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | Notebook    | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Unknown       | PICO PC                     | Desktop     | [70dca31596](https://bsd-hardware.info/?probe=70dca31596) | Jan 19, 2022 |
| ASUSTek       | AT5NM10-I                   | Desktop     | [dea1ec292d](https://bsd-hardware.info/?probe=dea1ec292d) | Jan 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [64105513c3](https://bsd-hardware.info/?probe=64105513c3) | Jan 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [9c34dd06dc](https://bsd-hardware.info/?probe=9c34dd06dc) | Jan 18, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [a188e2d1bc](https://bsd-hardware.info/?probe=a188e2d1bc) | Jan 17, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [b315e32645](https://bsd-hardware.info/?probe=b315e32645) | Jan 17, 2022 |
| HP            | ProLiant DL160 Gen9         | Server      | [f91d50ab48](https://bsd-hardware.info/?probe=f91d50ab48) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [92ee8c8c45](https://bsd-hardware.info/?probe=92ee8c8c45) | Jan 17, 2022 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [5e980b75bc](https://bsd-hardware.info/?probe=5e980b75bc) | Jan 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [face78ad45](https://bsd-hardware.info/?probe=face78ad45) | Jan 16, 2022 |
| Acer          | TravelMate 8481TG           | Notebook    | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [010c0f9489](https://bsd-hardware.info/?probe=010c0f9489) | Jan 15, 2022 |
| HP            | ProLiant DL160 Gen9         | Server      | [afafc15a7b](https://bsd-hardware.info/?probe=afafc15a7b) | Jan 15, 2022 |
| Supermicro    | X11SCM-LN8F                 | Server      | [bffb7756e2](https://bsd-hardware.info/?probe=bffb7756e2) | Jan 14, 2022 |
| Sophos        | SG                          | Firewall    | [b3eb53964e](https://bsd-hardware.info/?probe=b3eb53964e) | Jan 14, 2022 |
| OEM           | 1.0                         | Desktop     | [2bc6be75f3](https://bsd-hardware.info/?probe=2bc6be75f3) | Jan 13, 2022 |
| Protectli     | VP2410                      | Desktop     | [4dd1b9065c](https://bsd-hardware.info/?probe=4dd1b9065c) | Jan 13, 2022 |
| PC Engines    | APU2                        | Desktop     | [b1f37f5ec0](https://bsd-hardware.info/?probe=b1f37f5ec0) | Jan 12, 2022 |
| SIEMENS       | A5E38156881 RS-AE           | Desktop     | [9940cdeaae](https://bsd-hardware.info/?probe=9940cdeaae) | Jan 12, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [0da2a93271](https://bsd-hardware.info/?probe=0da2a93271) | Jan 11, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [20834b9ab3](https://bsd-hardware.info/?probe=20834b9ab3) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [e95a3dd5ec](https://bsd-hardware.info/?probe=e95a3dd5ec) | Jan 10, 2022 |
| PC Engines    | apu1                        | Desktop     | [1d0acc276d](https://bsd-hardware.info/?probe=1d0acc276d) | Jan 10, 2022 |
| HP            | 17E2                        | Mini pc     | [d394a8bcc5](https://bsd-hardware.info/?probe=d394a8bcc5) | Jan 10, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5de4d8c93e](https://bsd-hardware.info/?probe=5de4d8c93e) | Jan 09, 2022 |
| HP            | 3397                        | Desktop     | [7740208542](https://bsd-hardware.info/?probe=7740208542) | Jan 09, 2022 |
| Sophos        | SG                          | Firewall    | [82177170e4](https://bsd-hardware.info/?probe=82177170e4) | Jan 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [7c49bc84a7](https://bsd-hardware.info/?probe=7c49bc84a7) | Jan 08, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [db01451a9c](https://bsd-hardware.info/?probe=db01451a9c) | Jan 08, 2022 |
| Sophos        | UTM                         | Firewall    | [fab7b9a634](https://bsd-hardware.info/?probe=fab7b9a634) | Jan 08, 2022 |
| ASRock        | Q1900M                      | Desktop     | [c10bf0783b](https://bsd-hardware.info/?probe=c10bf0783b) | Jan 08, 2022 |
| MSI           | GT75VR 7RF                  | Notebook    | [cca6cc3c0b](https://bsd-hardware.info/?probe=cca6cc3c0b) | Jan 07, 2022 |
| HP            | 213D A01                    | Desktop     | [b11b8d0a83](https://bsd-hardware.info/?probe=b11b8d0a83) | Jan 06, 2022 |
| Supermicro    | X11SCM-LN8F                 | Server      | [f9101a24aa](https://bsd-hardware.info/?probe=f9101a24aa) | Jan 06, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [8a79b30384](https://bsd-hardware.info/?probe=8a79b30384) | Jan 05, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [f0aeeb7f3c](https://bsd-hardware.info/?probe=f0aeeb7f3c) | Jan 05, 2022 |
| Dell          | 0MN1TX A03                  | Desktop     | [89308fe374](https://bsd-hardware.info/?probe=89308fe374) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| ZOTAC         | ZBOXNANO-ID67/ID68/ID69     | Mini pc     | [9bcbd09882](https://bsd-hardware.info/?probe=9bcbd09882) | Jan 04, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [83610f9295](https://bsd-hardware.info/?probe=83610f9295) | Jan 03, 2022 |
| Dell          | Latitude 3400               | Notebook    | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4979175779](https://bsd-hardware.info/?probe=4979175779) | Jan 01, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | Notebook    | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [5d8397efae](https://bsd-hardware.info/?probe=5d8397efae) | Dec 31, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [00a423476f](https://bsd-hardware.info/?probe=00a423476f) | Dec 31, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [a5cc2ac2e5](https://bsd-hardware.info/?probe=a5cc2ac2e5) | Dec 30, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [447f2bd30c](https://bsd-hardware.info/?probe=447f2bd30c) | Dec 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c45cd1b45](https://bsd-hardware.info/?probe=1c45cd1b45) | Dec 29, 2021 |
| Advantech     | SYS-2USM02-6M01E            | Desktop     | [6952d74233](https://bsd-hardware.info/?probe=6952d74233) | Dec 29, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| ASUSTek       | AT5NM10-I                   | Desktop     | [07903fe3b2](https://bsd-hardware.info/?probe=07903fe3b2) | Dec 28, 2021 |
| NEXCOM        | NSA3110 B                   | Desktop     | [213dc9c3ef](https://bsd-hardware.info/?probe=213dc9c3ef) | Dec 28, 2021 |
| Intel         | DQ67OW AAG12528-310         | Desktop     | [7a41b1560b](https://bsd-hardware.info/?probe=7a41b1560b) | Dec 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [a3bbd9d497](https://bsd-hardware.info/?probe=a3bbd9d497) | Dec 28, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [e8ea8ca2d4](https://bsd-hardware.info/?probe=e8ea8ca2d4) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [8081818610](https://bsd-hardware.info/?probe=8081818610) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [ad85192939](https://bsd-hardware.info/?probe=ad85192939) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| Sophos        | UTM                         | Firewall    | [cbbe4c292d](https://bsd-hardware.info/?probe=cbbe4c292d) | Dec 25, 2021 |
| Advantech     | SYS-2USM02-6M01E            | Desktop     | [11ac580b34](https://bsd-hardware.info/?probe=11ac580b34) | Dec 25, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [2197e2ef44](https://bsd-hardware.info/?probe=2197e2ef44) | Dec 24, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [ea002bb42a](https://bsd-hardware.info/?probe=ea002bb42a) | Dec 24, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [e6a780468e](https://bsd-hardware.info/?probe=e6a780468e) | Dec 23, 2021 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [1008aaa183](https://bsd-hardware.info/?probe=1008aaa183) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Sophos        | XG                          | Firewall    | [35f890b945](https://bsd-hardware.info/?probe=35f890b945) | Dec 21, 2021 |
| Intel         | NUC7JYB J67969-400          | Mini pc     | [5f657bdb2a](https://bsd-hardware.info/?probe=5f657bdb2a) | Dec 20, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [510b7cb091](https://bsd-hardware.info/?probe=510b7cb091) | Dec 19, 2021 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [7e2700c4da](https://bsd-hardware.info/?probe=7e2700c4da) | Dec 19, 2021 |
| MSI           | G41M-P25                    | Desktop     | [841cce11e6](https://bsd-hardware.info/?probe=841cce11e6) | Dec 19, 2021 |
| PC Engines    | APU                         | Desktop     | [a80dfddf5d](https://bsd-hardware.info/?probe=a80dfddf5d) | Dec 19, 2021 |
| PC Engines    | APU                         | Desktop     | [062a321fcc](https://bsd-hardware.info/?probe=062a321fcc) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [a684bd3927](https://bsd-hardware.info/?probe=a684bd3927) | Dec 18, 2021 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [2c117a5a05](https://bsd-hardware.info/?probe=2c117a5a05) | Dec 18, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [02d347af7f](https://bsd-hardware.info/?probe=02d347af7f) | Dec 17, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7daf32eb4f](https://bsd-hardware.info/?probe=7daf32eb4f) | Dec 17, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [9e0ffaee60](https://bsd-hardware.info/?probe=9e0ffaee60) | Dec 17, 2021 |
| Jetway        | 1.0                         | Desktop     | [da30ee0b65](https://bsd-hardware.info/?probe=da30ee0b65) | Dec 17, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [eb69483087](https://bsd-hardware.info/?probe=eb69483087) | Dec 17, 2021 |
| Sophos        | SG                          | Firewall    | [14bc5a144f](https://bsd-hardware.info/?probe=14bc5a144f) | Dec 16, 2021 |
| ASRock        | J5005-ITX                   | Desktop     | [8da08352a2](https://bsd-hardware.info/?probe=8da08352a2) | Dec 16, 2021 |
| PC Engines    | apu4                        | Desktop     | [3b69286939](https://bsd-hardware.info/?probe=3b69286939) | Dec 16, 2021 |
| Sophos        | XG                          | Firewall    | [0108191dec](https://bsd-hardware.info/?probe=0108191dec) | Dec 15, 2021 |
| Sophos        | XG                          | Firewall    | [3403234de3](https://bsd-hardware.info/?probe=3403234de3) | Dec 15, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [cd29b33f3b](https://bsd-hardware.info/?probe=cd29b33f3b) | Dec 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [aa872042e3](https://bsd-hardware.info/?probe=aa872042e3) | Dec 15, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [146a32975f](https://bsd-hardware.info/?probe=146a32975f) | Dec 14, 2021 |
| ASUSTek       | 1005P                       | Notebook    | [4c43bd561f](https://bsd-hardware.info/?probe=4c43bd561f) | Dec 14, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [34ba809dc2](https://bsd-hardware.info/?probe=34ba809dc2) | Dec 14, 2021 |
| Intel         | SharkBay Platform           | Notebook    | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [e77489ad74](https://bsd-hardware.info/?probe=e77489ad74) | Dec 14, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [cc25ac7ea0](https://bsd-hardware.info/?probe=cc25ac7ea0) | Dec 13, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [0dd02a3ddf](https://bsd-hardware.info/?probe=0dd02a3ddf) | Dec 13, 2021 |
| Supermicro    | A2SDi-2C-HLN4F              | Server      | [92977964d1](https://bsd-hardware.info/?probe=92977964d1) | Dec 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [170ca711c2](https://bsd-hardware.info/?probe=170ca711c2) | Dec 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [8c3ba89ddd](https://bsd-hardware.info/?probe=8c3ba89ddd) | Dec 12, 2021 |
| Sophos        | UTM                         | Firewall    | [1072acecfd](https://bsd-hardware.info/?probe=1072acecfd) | Dec 12, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [88467fcb17](https://bsd-hardware.info/?probe=88467fcb17) | Dec 11, 2021 |
| CheckPoint    | T-120-00                    | Desktop     | [39b54429ed](https://bsd-hardware.info/?probe=39b54429ed) | Dec 11, 2021 |
| ASUSTek       | AT5NM10-I                   | Desktop     | [99395ceca8](https://bsd-hardware.info/?probe=99395ceca8) | Dec 10, 2021 |
| Acer          | RevoOne RL85                | Desktop     | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | Notebook    | [0b6ab3ba1b](https://bsd-hardware.info/?probe=0b6ab3ba1b) | Dec 09, 2021 |
| PC Engines    | APU2                        | Desktop     | [4f7fed5b1e](https://bsd-hardware.info/?probe=4f7fed5b1e) | Dec 09, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [51a0e11a8e](https://bsd-hardware.info/?probe=51a0e11a8e) | Dec 09, 2021 |
| NU591         | 1.0                         | Desktop     | [4294dc97ee](https://bsd-hardware.info/?probe=4294dc97ee) | Dec 08, 2021 |
| PC Engines    | APU2                        | Desktop     | [dd0f74fd49](https://bsd-hardware.info/?probe=dd0f74fd49) | Dec 08, 2021 |
| Lex           | Pineview-D                  | Desktop     | [6cdb060f85](https://bsd-hardware.info/?probe=6cdb060f85) | Dec 08, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [041d4640ec](https://bsd-hardware.info/?probe=041d4640ec) | Dec 08, 2021 |
| Dell          | Precision M4300             | Notebook    | [08fe78379d](https://bsd-hardware.info/?probe=08fe78379d) | Dec 08, 2021 |
| Intel         | D34010WYK H14771-304        | Desktop     | [49e201295e](https://bsd-hardware.info/?probe=49e201295e) | Dec 08, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [320af631dc](https://bsd-hardware.info/?probe=320af631dc) | Dec 08, 2021 |
| Sophos        | XG                          | Firewall    | [09b35133c9](https://bsd-hardware.info/?probe=09b35133c9) | Dec 07, 2021 |
| Deciso        | Netboard A20                | Notebook    | [593d123f0c](https://bsd-hardware.info/?probe=593d123f0c) | Dec 07, 2021 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [c301b3f8f3](https://bsd-hardware.info/?probe=c301b3f8f3) | Dec 06, 2021 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [0b875499eb](https://bsd-hardware.info/?probe=0b875499eb) | Dec 06, 2021 |
| MSI           | G41M-P25                    | Desktop     | [c123efb259](https://bsd-hardware.info/?probe=c123efb259) | Dec 06, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [35b01f0f56](https://bsd-hardware.info/?probe=35b01f0f56) | Dec 05, 2021 |
| Sophos        | XG                          | Firewall    | [d2e102174c](https://bsd-hardware.info/?probe=d2e102174c) | Dec 05, 2021 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [0908aa7f42](https://bsd-hardware.info/?probe=0908aa7f42) | Dec 04, 2021 |
| PC Engines    | apu4                        | Desktop     | [044ab6e8f7](https://bsd-hardware.info/?probe=044ab6e8f7) | Dec 04, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | Notebook    | [b1377872cd](https://bsd-hardware.info/?probe=b1377872cd) | Dec 03, 2021 |
| ZOTAC         | ZBOX-CI321NANO              | Mini pc     | [f3e8035461](https://bsd-hardware.info/?probe=f3e8035461) | Dec 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [b30e9d3491](https://bsd-hardware.info/?probe=b30e9d3491) | Dec 03, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [13491e4533](https://bsd-hardware.info/?probe=13491e4533) | Dec 03, 2021 |
| Dell          | 01V648 A02                  | Server      | [376ad93033](https://bsd-hardware.info/?probe=376ad93033) | Dec 01, 2021 |
| ASUSTek       | P8B-M Series                | Server      | [1347f15b56](https://bsd-hardware.info/?probe=1347f15b56) | Nov 30, 2021 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [733cb90db6](https://bsd-hardware.info/?probe=733cb90db6) | Nov 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [5d1a3bbfe3](https://bsd-hardware.info/?probe=5d1a3bbfe3) | Nov 30, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [f9eb65c467](https://bsd-hardware.info/?probe=f9eb65c467) | Nov 30, 2021 |
| PC Engines    | APU2                        | Desktop     | [9d8179e835](https://bsd-hardware.info/?probe=9d8179e835) | Nov 30, 2021 |
| Shuttle       | DS437                       | Notebook    | [b5d1bcffdb](https://bsd-hardware.info/?probe=b5d1bcffdb) | Nov 29, 2021 |
| Shuttle       | DH370                       | Desktop     | [1bb8118acd](https://bsd-hardware.info/?probe=1bb8118acd) | Nov 29, 2021 |
| ASRock        | H570M-ITX/ac                | Desktop     | [015b50de55](https://bsd-hardware.info/?probe=015b50de55) | Nov 29, 2021 |
| ASRockRack    | X570D4I-2T                  | Desktop     | [7e937017e8](https://bsd-hardware.info/?probe=7e937017e8) | Nov 29, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [090f75c486](https://bsd-hardware.info/?probe=090f75c486) | Nov 28, 2021 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [d5adfcc6da](https://bsd-hardware.info/?probe=d5adfcc6da) | Nov 28, 2021 |
| PC Engines    | apu4                        | Desktop     | [ecf1eda1a7](https://bsd-hardware.info/?probe=ecf1eda1a7) | Nov 28, 2021 |
| PC Engines    | APU2                        | Desktop     | [93d5a9f80b](https://bsd-hardware.info/?probe=93d5a9f80b) | Nov 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [d4146fde77](https://bsd-hardware.info/?probe=d4146fde77) | Nov 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [5b6fe36e9f](https://bsd-hardware.info/?probe=5b6fe36e9f) | Nov 27, 2021 |
| Shuttle       | DS437                       | Notebook    | [687fc514ba](https://bsd-hardware.info/?probe=687fc514ba) | Nov 27, 2021 |
| Shuttle       | DS437                       | Notebook    | [e65a62f5a5](https://bsd-hardware.info/?probe=e65a62f5a5) | Nov 27, 2021 |
| Fujitsu       | D3402-B2 S26361-D3402-B2    | Desktop     | [d7adca8cac](https://bsd-hardware.info/?probe=d7adca8cac) | Nov 27, 2021 |
| MSI           | MS-9899 11                  | Desktop     | [8fa11e9966](https://bsd-hardware.info/?probe=8fa11e9966) | Nov 27, 2021 |
| ASRock        | 775i945GZ                   | Desktop     | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [d42bf7df26](https://bsd-hardware.info/?probe=d42bf7df26) | Nov 25, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [18fea5f65d](https://bsd-hardware.info/?probe=18fea5f65d) | Nov 24, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [6b5b37db47](https://bsd-hardware.info/?probe=6b5b37db47) | Nov 24, 2021 |
| Unknown       | YL-J1900L4-V2               | Desktop     | [62b059e980](https://bsd-hardware.info/?probe=62b059e980) | Nov 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [47b9ef1995](https://bsd-hardware.info/?probe=47b9ef1995) | Nov 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [8a14d605ba](https://bsd-hardware.info/?probe=8a14d605ba) | Nov 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [716ff29660](https://bsd-hardware.info/?probe=716ff29660) | Nov 21, 2021 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Desktop     | [fe64c7bb21](https://bsd-hardware.info/?probe=fe64c7bb21) | Nov 21, 2021 |
| Gigabyte      | MX33-BS1-V1                 | Server      | [bd71d84cf2](https://bsd-hardware.info/?probe=bd71d84cf2) | Nov 21, 2021 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [fd00b64a4c](https://bsd-hardware.info/?probe=fd00b64a4c) | Nov 21, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [ce24594597](https://bsd-hardware.info/?probe=ce24594597) | Nov 21, 2021 |
| Alienware     | m15                         | Notebook    | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| ASRock        | Z170 OC Formula             | Desktop     | [afc55af8dc](https://bsd-hardware.info/?probe=afc55af8dc) | Nov 20, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [773774770a](https://bsd-hardware.info/?probe=773774770a) | Nov 20, 2021 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [58befdd80b](https://bsd-hardware.info/?probe=58befdd80b) | Nov 19, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [dc97551c6f](https://bsd-hardware.info/?probe=dc97551c6f) | Nov 19, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | Notebook    | [d8628f80c0](https://bsd-hardware.info/?probe=d8628f80c0) | Nov 19, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [7263f34697](https://bsd-hardware.info/?probe=7263f34697) | Nov 19, 2021 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [09480528a6](https://bsd-hardware.info/?probe=09480528a6) | Nov 17, 2021 |
| Shuttle       | DS437                       | Notebook    | [0dc3d4619e](https://bsd-hardware.info/?probe=0dc3d4619e) | Nov 17, 2021 |
| PC Engines    | apu4                        | Desktop     | [ec71343e71](https://bsd-hardware.info/?probe=ec71343e71) | Nov 17, 2021 |
| Dell          | 05YDCW A01                  | Desktop     | [435e4bef92](https://bsd-hardware.info/?probe=435e4bef92) | Nov 16, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a1b5a42cc1](https://bsd-hardware.info/?probe=a1b5a42cc1) | Nov 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e83cc2a4e7](https://bsd-hardware.info/?probe=e83cc2a4e7) | Nov 16, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [1e96a8e633](https://bsd-hardware.info/?probe=1e96a8e633) | Nov 16, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [4b1a5f0ab0](https://bsd-hardware.info/?probe=4b1a5f0ab0) | Nov 15, 2021 |
| PC Engines    | APU                         | Desktop     | [092ef089e7](https://bsd-hardware.info/?probe=092ef089e7) | Nov 14, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Lex           | Pineview-D                  | Desktop     | [ad05a6ff99](https://bsd-hardware.info/?probe=ad05a6ff99) | Nov 14, 2021 |
| HP            | 0A58h                       | Desktop     | [779ae4c4f5](https://bsd-hardware.info/?probe=779ae4c4f5) | Nov 13, 2021 |
| PC Engines    | APU2                        | Desktop     | [32a291cf82](https://bsd-hardware.info/?probe=32a291cf82) | Nov 13, 2021 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [f3df627d3e](https://bsd-hardware.info/?probe=f3df627d3e) | Nov 13, 2021 |
| Supermicro    | A2SDi-2C-HLN4F              | Server      | [5fd53f5d52](https://bsd-hardware.info/?probe=5fd53f5d52) | Nov 13, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [9268d91d01](https://bsd-hardware.info/?probe=9268d91d01) | Nov 13, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [4401dfa800](https://bsd-hardware.info/?probe=4401dfa800) | Nov 12, 2021 |
| Dell          | 01V648 A02                  | Server      | [d2ab8dc303](https://bsd-hardware.info/?probe=d2ab8dc303) | Nov 12, 2021 |
| NF841         | 1.0                         | Desktop     | [b1c784d41a](https://bsd-hardware.info/?probe=b1c784d41a) | Nov 11, 2021 |
| BESSTAR Te... | UM340 V1.0                  | Desktop     | [a14a31115f](https://bsd-hardware.info/?probe=a14a31115f) | Nov 10, 2021 |
| Shuttle       | DH470                       | Desktop     | [9db52efae6](https://bsd-hardware.info/?probe=9db52efae6) | Nov 09, 2021 |
| PC Engines    | APU2                        | Desktop     | [e02c6cd460](https://bsd-hardware.info/?probe=e02c6cd460) | Nov 09, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [ad0e7916b8](https://bsd-hardware.info/?probe=ad0e7916b8) | Nov 09, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [27c22e7539](https://bsd-hardware.info/?probe=27c22e7539) | Nov 08, 2021 |
| Shuttle       | FH61R                       | Desktop     | [a231590743](https://bsd-hardware.info/?probe=a231590743) | Nov 07, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7e27b1bc46](https://bsd-hardware.info/?probe=7e27b1bc46) | Nov 07, 2021 |
| BESSTAR Te... | GB7                         | Mini pc     | [ec34265ef9](https://bsd-hardware.info/?probe=ec34265ef9) | Nov 07, 2021 |
| BESSTAR Te... | GB7                         | Mini pc     | [cbb2b06d05](https://bsd-hardware.info/?probe=cbb2b06d05) | Nov 07, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | Notebook    | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| MSI           | MS-9899 11                  | Desktop     | [87e3cf51e8](https://bsd-hardware.info/?probe=87e3cf51e8) | Nov 06, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| Intel         | D2500CC AAG81477-400        | Desktop     | [d72502a707](https://bsd-hardware.info/?probe=d72502a707) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | Notebook    | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| Unknown       | Hardkernel ODROID-N2        | Desktop     | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| ASRock        | H570M-ITX/ac                | Desktop     | [0eacc5ecb8](https://bsd-hardware.info/?probe=0eacc5ecb8) | Nov 05, 2021 |
| Shuttle       | XS35V3                      | Desktop     | [0d40b0f9eb](https://bsd-hardware.info/?probe=0d40b0f9eb) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | Notebook    | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| CheckPoint    | PB-05-00                    | Firewall    | [faab411c33](https://bsd-hardware.info/?probe=faab411c33) | Nov 03, 2021 |
| BESSTAR Te... | U820                        | Notebook    | [3bd9cd5b98](https://bsd-hardware.info/?probe=3bd9cd5b98) | Nov 03, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [bec9a0c92f](https://bsd-hardware.info/?probe=bec9a0c92f) | Nov 03, 2021 |
| Acer          | Aspire X3990                | Desktop     | [3d2d538b68](https://bsd-hardware.info/?probe=3d2d538b68) | Nov 02, 2021 |
| Medion        | MS-7728                     | Desktop     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z360                | Notebook    | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| BESSTAR Te... | U820                        | Notebook    | [1a39d8a6e3](https://bsd-hardware.info/?probe=1a39d8a6e3) | Nov 02, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [b488be90bf](https://bsd-hardware.info/?probe=b488be90bf) | Nov 02, 2021 |
| Apple         | MacBookAir5,1               | Notebook    | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [7539eb5fc7](https://bsd-hardware.info/?probe=7539eb5fc7) | Oct 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [4ed65ba418](https://bsd-hardware.info/?probe=4ed65ba418) | Oct 30, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [feed581ab2](https://bsd-hardware.info/?probe=feed581ab2) | Oct 30, 2021 |
| Sophos        | SG                          | Firewall    | [26b1c5fe8f](https://bsd-hardware.info/?probe=26b1c5fe8f) | Oct 30, 2021 |
| Sophos        | SG                          | Firewall    | [b2b6315b35](https://bsd-hardware.info/?probe=b2b6315b35) | Oct 29, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [d80d739506](https://bsd-hardware.info/?probe=d80d739506) | Oct 28, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [4f53f8feed](https://bsd-hardware.info/?probe=4f53f8feed) | Oct 28, 2021 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [d2b7af2b7d](https://bsd-hardware.info/?probe=d2b7af2b7d) | Oct 27, 2021 |
| Dell          | 03X6X0 A00                  | Server      | [c350bfa241](https://bsd-hardware.info/?probe=c350bfa241) | Oct 27, 2021 |
| PC Engines    | APU2                        | Desktop     | [523db771da](https://bsd-hardware.info/?probe=523db771da) | Oct 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [e0fdc6e80c](https://bsd-hardware.info/?probe=e0fdc6e80c) | Oct 26, 2021 |
| Beckhoff A... | CX51x0 G3                   | Desktop     | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1                   | Desktop     | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [eeb1efdd74](https://bsd-hardware.info/?probe=eeb1efdd74) | Oct 25, 2021 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [dc389f7eea](https://bsd-hardware.info/?probe=dc389f7eea) | Oct 24, 2021 |
| Dell          | 09T7VV A02                  | Server      | [a6f0d2f328](https://bsd-hardware.info/?probe=a6f0d2f328) | Oct 24, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Dell          | 09T7VV A02                  | Server      | [54ef87169b](https://bsd-hardware.info/?probe=54ef87169b) | Oct 24, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [f004879c80](https://bsd-hardware.info/?probe=f004879c80) | Oct 24, 2021 |
| Acer          | Aspire X3990                | Desktop     | [5bb633147c](https://bsd-hardware.info/?probe=5bb633147c) | Oct 23, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [51ab552166](https://bsd-hardware.info/?probe=51ab552166) | Oct 23, 2021 |
| ASRock        | 4X4-V1000                   | Desktop     | [dad41d7334](https://bsd-hardware.info/?probe=dad41d7334) | Oct 22, 2021 |
| HP            | 18E7                        | Desktop     | [bc3f111ee4](https://bsd-hardware.info/?probe=bc3f111ee4) | Oct 22, 2021 |
| ZOTAC         | ZBOX-RI323NANO              | Mini pc     | [d8343dc26f](https://bsd-hardware.info/?probe=d8343dc26f) | Oct 22, 2021 |
| Foxconn       | 45CS                        | Desktop     | [a6c12cc8dd](https://bsd-hardware.info/?probe=a6c12cc8dd) | Oct 20, 2021 |
| PC Engines    | APU                         | Desktop     | [e650814990](https://bsd-hardware.info/?probe=e650814990) | Oct 19, 2021 |
| Supermicro    | X11SCH-LN4F                 | Server      | [eb0dc0b18e](https://bsd-hardware.info/?probe=eb0dc0b18e) | Oct 19, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [8d7a4f8aec](https://bsd-hardware.info/?probe=8d7a4f8aec) | Oct 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [d8a6d0daf3](https://bsd-hardware.info/?probe=d8a6d0daf3) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Unknown       | YL-J1900L4-V2               | Desktop     | [160efd232c](https://bsd-hardware.info/?probe=160efd232c) | Oct 17, 2021 |
| AOpen         | i67QMx-DV R1.00TS2 55MP6... | Desktop     | [c5a904869c](https://bsd-hardware.info/?probe=c5a904869c) | Oct 16, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [34d35b4b64](https://bsd-hardware.info/?probe=34d35b4b64) | Oct 16, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | Notebook    | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| Dell          | Inspiron 3493               | Notebook    | [ed41c18cfc](https://bsd-hardware.info/?probe=ed41c18cfc) | Oct 16, 2021 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [925e585345](https://bsd-hardware.info/?probe=925e585345) | Oct 16, 2021 |
| AOpen         | D1007 0BBB                  | Desktop     | [c774c3d39f](https://bsd-hardware.info/?probe=c774c3d39f) | Oct 15, 2021 |
| Sophos        | SG                          | Firewall    | [adab446130](https://bsd-hardware.info/?probe=adab446130) | Oct 14, 2021 |
| PC Engines    | APU                         | Desktop     | [92830ddc69](https://bsd-hardware.info/?probe=92830ddc69) | Oct 14, 2021 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [b88f2a42ed](https://bsd-hardware.info/?probe=b88f2a42ed) | Oct 14, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [97ee657402](https://bsd-hardware.info/?probe=97ee657402) | Oct 11, 2021 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [f842095195](https://bsd-hardware.info/?probe=f842095195) | Oct 11, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [be42957ecd](https://bsd-hardware.info/?probe=be42957ecd) | Oct 10, 2021 |
| ASRock        | A520M-ITX/ac                | Desktop     | [847d5b709c](https://bsd-hardware.info/?probe=847d5b709c) | Oct 10, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [8092d9074e](https://bsd-hardware.info/?probe=8092d9074e) | Oct 09, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8919eb9ecf](https://bsd-hardware.info/?probe=8919eb9ecf) | Oct 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [93783e754a](https://bsd-hardware.info/?probe=93783e754a) | Oct 08, 2021 |
| ASRock        | J4125B-ITX                  | Desktop     | [53fd304513](https://bsd-hardware.info/?probe=53fd304513) | Oct 07, 2021 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [105614d0b7](https://bsd-hardware.info/?probe=105614d0b7) | Oct 07, 2021 |
| Intel         | NUC9i5QNB K49247-403        | Mini pc     | [fc0aea9e0b](https://bsd-hardware.info/?probe=fc0aea9e0b) | Oct 06, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 65        | 3.89%   |
| OPNsense 21.1     | 64        | 3.83%   |
| OPNsense 21.1.5   | 56        | 3.36%   |
| OPNsense 22.1     | 54        | 3.24%   |
| OPNsense 20.7.8   | 54        | 3.24%   |
| OPNsense 21.7.3   | 52        | 3.12%   |
| OPNsense 21.7.1   | 51        | 3.06%   |
| OPNsense 21.1.3   | 45        | 2.7%    |
| OPNsense 21.7.6   | 43        | 2.58%   |
| OPNsense 21.1.2   | 43        | 2.58%   |
| OPNsense 22.7.4   | 42        | 2.52%   |
| OPNsense 22.1.8   | 42        | 2.52%   |
| OPNsense 21.1.1   | 42        | 2.52%   |
| OPNsense 22.7.6   | 40        | 2.4%    |
| OPNsense 22.1.6   | 40        | 2.4%    |
| OPNsense 21.1.4   | 39        | 2.34%   |
| helloSystem 0.4.0 | 34        | 2.04%   |
| OpenBSD 6.8       | 28        | 1.68%   |
| OPNsense 22.1.9   | 26        | 1.56%   |
| OPNsense 22.1.10  | 26        | 1.56%   |
| OPNsense 22.1.1   | 26        | 1.56%   |
| OPNsense 21.7.5   | 26        | 1.56%   |
| OPNsense 21.1.7   | 26        | 1.56%   |
| OPNsense 22.1.4   | 24        | 1.44%   |
| OPNsense 22.1.2   | 24        | 1.44%   |
| helloSystem 0.7.0 | 22        | 1.32%   |
| OPNsense 22.7.2   | 21        | 1.26%   |
| OPNsense 22.7     | 21        | 1.26%   |
| OPNsense 21.1.8   | 21        | 1.26%   |
| OPNsense 21.1.6   | 21        | 1.26%   |
| helloSystem 0.5.0 | 19        | 1.14%   |
| OPNsense 21.7.4   | 18        | 1.08%   |
| OPNsense 21.7.2   | 18        | 1.08%   |
| OPNsense 22.1.7   | 17        | 1.02%   |
| FreeBSD 13.0      | 17        | 1.02%   |
| OPNsense 21.7     | 15        | 0.9%    |
| FreeBSD 13.1      | 14        | 0.84%   |
| OPNsense 22.7.1   | 13        | 0.78%   |
| OpenBSD 6.7       | 13        | 0.78%   |
| FreeBSD 12.2      | 13        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 915       | 68.75%  |
| FreeBSD     | 186       | 13.97%  |
| helloSystem | 97        | 7.29%   |
| OpenBSD     | 62        | 4.66%   |
| GhostBSD    | 31        | 2.33%   |
| NomadBSD    | 20        | 1.5%    |
| TrueNAS     | 5         | 0.38%   |
| NetBSD      | 5         | 0.38%   |
| MyBee       | 3         | 0.23%   |
| HardenedBSD | 2         | 0.15%   |
| PC-BSD      | 1         | 0.08%   |
| FuryBSD     | 1         | 0.08%   |
| FreeNAS     | 1         | 0.08%   |
| DragonFly   | 1         | 0.08%   |
| ClonOS      | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 1294      | 98.18%  |
| i386    | 10        | 0.76%   |
| arm64   | 9         | 0.68%   |
| arm     | 3         | 0.23%   |
| sparc64 | 1         | 0.08%   |
| macppc  | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1016      | 75.82%  |
| helloDesktop  | 106       | 7.91%   |
| MATE          | 45        | 3.36%   |
| fvwm          | 38        | 2.84%   |
| XFCE          | 27        | 2.01%   |
| KDE5          | 27        | 2.01%   |
| TWM           | 17        | 1.27%   |
| Openbox       | 17        | 1.27%   |
| GNOME         | 16        | 1.19%   |
| AwesomeWM     | 9         | 0.67%   |
| i3            | 7         | 0.52%   |
| LXQt          | 2         | 0.15%   |
| LXDE          | 2         | 0.15%   |
| Fluxbox       | 2         | 0.15%   |
| Enlightenment | 2         | 0.15%   |
| Cinnamon      | 2         | 0.15%   |
| Picom         | 1         | 0.07%   |
| iwm           | 1         | 0.07%   |
| GNUstep       | 1         | 0.07%   |
| filer         | 1         | 0.07%   |
| Compton       | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1031      | 77.93%  |
| X11     | 291       | 22%     |
| Wayland | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1095      | 81.78%  |
| SLiM    | 134       | 10.01%  |
| LightDM | 38        | 2.84%   |
| SDDM    | 29        | 2.17%   |
| XDM     | 21        | 1.57%   |
| GDM     | 18        | 1.34%   |
| Ly      | 4         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 1041      | 77.69%  |
| en_US            | 131       | 9.78%   |
| C                | 80        | 5.97%   |
| de_DE            | 72        | 5.37%   |
| en_GB            | 8         | 0.6%    |
| de_DE.ISO8859-1  | 3         | 0.22%   |
| pl_PL            | 1         | 0.07%   |
| en_IE            | 1         | 0.07%   |
| en_DE            | 1         | 0.07%   |
| en_CA            | 1         | 0.07%   |
| de_DE.ISO8859-15 | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1113      | 83.81%  |
| BIOS | 215       | 16.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 834       | 62.1%   |
| Zfs     | 430       | 32.02%  |
| Ffs     | 62        | 4.62%   |
| Cd9660  | 16        | 1.19%   |
| Hammer2 | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1202      | 90.72%  |
| MBR     | 105       | 7.92%   |
| Unknown | 17        | 1.28%   |
| BSD     | 1         | 0.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 142       | 10.77%  |
| Lenovo              | 100       | 7.59%   |
| Supermicro          | 97        | 7.36%   |
| PC Engines          | 91        | 6.9%    |
| Dell                | 79        | 5.99%   |
| Hewlett-Packard     | 74        | 5.61%   |
| ASUSTek Computer    | 69        | 5.24%   |
| Fujitsu             | 67        | 5.08%   |
| Intel               | 65        | 4.93%   |
| Sophos              | 55        | 4.17%   |
| ASRock              | 53        | 4.02%   |
| Gigabyte Technology | 43        | 3.26%   |
| MSI                 | 37        | 2.81%   |
| ZOTAC               | 36        | 2.73%   |
| BESSTAR Tech        | 32        | 2.43%   |
| AMI                 | 27        | 2.05%   |
| Apple               | 22        | 1.67%   |
| Shuttle             | 15        | 1.14%   |
| Protectli           | 15        | 1.14%   |
| Deciso              | 14        | 1.06%   |
| Acer                | 14        | 1.06%   |
| HARDKERNEL          | 13        | 0.99%   |
| Thomas-Krenn.AG     | 10        | 0.76%   |
| AWOW                | 10        | 0.76%   |
| CheckPoint          | 7         | 0.53%   |
| ASRockRack          | 7         | 0.53%   |
| TUXEDO              | 6         | 0.46%   |
| NF541               | 6         | 0.46%   |
| IBM                 | 6         | 0.46%   |
| Biostar             | 6         | 0.46%   |
| CncTion             | 5         | 0.38%   |
| Beckhoff Automation | 5         | 0.38%   |
| NEXCOM              | 4         | 0.3%    |
| CompuLab            | 4         | 0.3%    |
| Sony                | 3         | 0.23%   |
| Notebook            | 3         | 0.23%   |
| Medion              | 3         | 0.23%   |
| Lex                 | 3         | 0.23%   |
| Foxconn             | 3         | 0.23%   |
| Advantech           | 3         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 146       | 11.08%  |
| PC Engines APU2                                   | 45        | 3.41%   |
| Supermicro Super Server                           | 34        | 2.58%   |
| PC Engines apu4                                   | 29        | 2.2%    |
| Sophos SG                                         | 28        | 2.12%   |
| Fujitsu FUTRO S920                                | 21        | 1.59%   |
| AMI Aptio CRB                                     | 17        | 1.29%   |
| Intel Q3XXG4-P V1.0                               | 15        | 1.14%   |
| Sophos UTM                                        | 14        | 1.06%   |
| Sophos XG                                         | 13        | 0.99%   |
| HARDKERNEL ODROID-H2                              | 12        | 0.91%   |
| ZOTAC ZBOX-CI327NANO-GS-01                        | 10        | 0.76%   |
| BESSTAR Tech X35G                                 | 9         | 0.68%   |
| PC Engines APU3                                   | 8         | 0.61%   |
| PC Engines APU                                    | 8         | 0.61%   |
| Dell PowerEdge R210 II                            | 8         | 0.61%   |
| ZOTAC ZBOX-CI329NANO                              | 7         | 0.53%   |
| Supermicro A1SAi                                  | 7         | 0.53%   |
| Protectli FW6                                     | 7         | 0.53%   |
| HP ProLiant MicroServer Gen8                      | 7         | 0.53%   |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server  | 6         | 0.46%   |
| Protectli FW4B                                    | 6         | 0.46%   |
| NF541 1.0                                         | 6         | 0.46%   |
| HP t620 PLUS Quad Core TC                         | 6         | 0.46%   |
| BESSTAR Tech GK41                                 | 6         | 0.46%   |
| AWOW PC BOX                                       | 6         | 0.46%   |
| Thomas-Krenn.AG LES network+                      | 5         | 0.38%   |
| Deciso Netboard A20                               | 5         | 0.38%   |
| NEXCOM ASG                                        | 4         | 0.3%    |
| MSI MS-7816                                       | 4         | 0.3%    |
| Fujitsu FUTRO S930                                | 4         | 0.3%    |
| Deciso Netboard A10 V2                            | 4         | 0.3%    |
| ASUS M5A78L-M/USB3                                | 4         | 0.3%    |
| ZOTAC ZBOX-CI323NANO                              | 3         | 0.23%   |
| Thomas-Krenn.AG LES network 6L                    | 3         | 0.23%   |
| Supermicro X8SIL                                  | 3         | 0.23%   |
| Supermicro X7SPA-HF                               | 3         | 0.23%   |
| Supermicro X10SLH-F/X10SLM+-F                     | 3         | 0.23%   |
| Supermicro 1HE Intel Single-CPU RI1102H-XE Server | 3         | 0.23%   |
| Shuttle DS437                                     | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 146       | 11.08%  |
| Lenovo ThinkPad            | 67        | 5.08%   |
| PC Engines APU2            | 45        | 3.41%   |
| Supermicro Super           | 34        | 2.58%   |
| Fujitsu FUTRO              | 32        | 2.43%   |
| PC Engines apu4            | 29        | 2.2%    |
| Sophos SG                  | 28        | 2.12%   |
| Dell OptiPlex              | 26        | 1.97%   |
| HP ProLiant                | 23        | 1.75%   |
| Dell PowerEdge             | 21        | 1.59%   |
| AMI Aptio                  | 17        | 1.29%   |
| Dell Latitude              | 16        | 1.21%   |
| Supermicro 1HE             | 15        | 1.14%   |
| Intel Q3XXG4-P             | 15        | 1.14%   |
| Sophos UTM                 | 14        | 1.06%   |
| Sophos XG                  | 13        | 0.99%   |
| Lenovo ThinkCentre         | 12        | 0.91%   |
| Hardkernel ODROID-H2       | 12        | 0.91%   |
| HP Compaq                  | 11        | 0.83%   |
| ZOTAC ZBOX-CI327NANO-GS-01 | 10        | 0.76%   |
| Deciso Netboard            | 10        | 0.76%   |
| ASUS PRIME                 | 10        | 0.76%   |
| HP ProDesk                 | 9         | 0.68%   |
| Fujitsu LIFEBOOK           | 9         | 0.68%   |
| BESSTAR Tech X35G          | 9         | 0.68%   |
| ASUS TUF                   | 9         | 0.68%   |
| Thomas-Krenn.AG LES        | 8         | 0.61%   |
| PC Engines APU3            | 8         | 0.61%   |
| PC Engines APU             | 8         | 0.61%   |
| Fujitsu PRIMERGY           | 8         | 0.61%   |
| Fujitsu ESPRIMO            | 8         | 0.61%   |
| ZOTAC ZBOX-CI329NANO       | 7         | 0.53%   |
| Supermicro A1SAi           | 7         | 0.53%   |
| Protectli FW6              | 7         | 0.53%   |
| HP t620                    | 7         | 0.53%   |
| Protectli FW4B             | 6         | 0.46%   |
| NF541 1.0                  | 6         | 0.46%   |
| Dell Precision             | 6         | 0.46%   |
| BESSTAR Tech GK41          | 6         | 0.46%   |
| AWOW PC                    | 6         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 179       | 13.58%  |
| 2020    | 173       | 13.13%  |
| 2019    | 131       | 9.94%   |
| 2021    | 130       | 9.86%   |
| 2016    | 119       | 9.03%   |
| 2017    | 94        | 7.13%   |
| 2014    | 94        | 7.13%   |
| 2013    | 73        | 5.54%   |
| 2011    | 59        | 4.48%   |
| 2012    | 57        | 4.32%   |
| 2015    | 55        | 4.17%   |
| 2010    | 41        | 3.11%   |
| 2022    | 34        | 2.58%   |
| 2009    | 31        | 2.35%   |
| 2008    | 18        | 1.37%   |
| Unknown | 16        | 1.21%   |
| 2007    | 7         | 0.53%   |
| 2006    | 4         | 0.3%    |
| 2003    | 2         | 0.15%   |
| 2002    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 785       | 59.56%  |
| Notebook       | 212       | 16.08%  |
| Mini pc        | 122       | 9.26%   |
| Server         | 120       | 9.1%    |
| Firewall       | 58        | 4.4%    |
| All in one     | 8         | 0.61%   |
| Convertible    | 7         | 0.53%   |
| System on chip | 6         | 0.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1217      | 92.34%  |
| Yes  | 101       | 7.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 487       | 36.51%  |
| 4.01-8.0        | 317       | 23.76%  |
| 16.01-24.0      | 285       | 21.36%  |
| 32.01-64.0      | 101       | 7.57%   |
| 2.01-3.0        | 58        | 4.35%   |
| 64.01-256.0     | 40        | 3%      |
| 3.01-4.0        | 12        | 0.9%    |
| 24.01-32.0      | 11        | 0.82%   |
| 0.51-1.0        | 9         | 0.67%   |
| 1.01-2.0        | 7         | 0.52%   |
| 0.01-0.5        | 4         | 0.3%    |
| More than 256.0 | 2         | 0.15%   |
| 0               | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 755       | 55.6%   |
| 0.51-1.0    | 395       | 29.09%  |
| 1.01-2.0    | 107       | 7.88%   |
| 2.01-3.0    | 28        | 2.06%   |
| 4.01-8.0    | 21        | 1.55%   |
| 3.01-4.0    | 17        | 1.25%   |
| 0           | 9         | 0.66%   |
| 8.01-16.0   | 8         | 0.59%   |
| Unknown     | 7         | 0.52%   |
| 16.01-24.0  | 5         | 0.37%   |
| 24.01-32.0  | 3         | 0.22%   |
| 64.01-256.0 | 2         | 0.15%   |
| 32.01-64.0  | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 987       | 73.38%  |
| 2      | 162       | 12.04%  |
| 0      | 97        | 7.21%   |
| 3      | 41        | 3.05%   |
| 4      | 26        | 1.93%   |
| 5      | 9         | 0.67%   |
| 6      | 8         | 0.59%   |
| 8      | 5         | 0.37%   |
| 7      | 5         | 0.37%   |
| 9      | 2         | 0.15%   |
| 14     | 1         | 0.07%   |
| 11     | 1         | 0.07%   |
| 10     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1119      | 84.58%  |
| Yes       | 204       | 15.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1288      | 97.72%  |
| No        | 30        | 2.28%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 908       | 68.53%  |
| Yes       | 417       | 31.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1066      | 80.27%  |
| Yes       | 262       | 19.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 1318      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 126       | 8.81%   |
| Munich            | 59        | 4.13%   |
| Hamburg           | 50        | 3.5%    |
| Frankfurt am Main | 36        | 2.52%   |
| Cologne           | 33        | 2.31%   |
| Stuttgart         | 24        | 1.68%   |
| Karlsruhe         | 17        | 1.19%   |
| Hanover           | 13        | 0.91%   |
| Dresden           | 13        | 0.91%   |
| Bonn              | 13        | 0.91%   |
| Nuremberg         | 11        | 0.77%   |
| Ludwigsburg       | 11        | 0.77%   |
| Dortmund          | 11        | 0.77%   |
| Bielefeld         | 11        | 0.77%   |
| Leipzig           | 10        | 0.7%    |
| Falkenstein       | 10        | 0.7%    |
| Heidelberg        | 9         | 0.63%   |
| Bochum            | 9         | 0.63%   |
| Wiesbaden         | 8         | 0.56%   |
| Tamm              | 8         | 0.56%   |
| Reutlingen        | 8         | 0.56%   |
| Potsdam           | 8         | 0.56%   |
| Paderborn         | 8         | 0.56%   |
| Halle             | 8         | 0.56%   |
| Chemnitz          | 8         | 0.56%   |
| Wernigerode       | 7         | 0.49%   |
| Mannheim          | 7         | 0.49%   |
| Kiel              | 7         | 0.49%   |
| Darmstadt         | 7         | 0.49%   |
| Ulm               | 6         | 0.42%   |
| Siegen            | 6         | 0.42%   |
| Krefeld           | 6         | 0.42%   |
| Kassel            | 6         | 0.42%   |
| Heilbronn         | 6         | 0.42%   |
| Habichtswald      | 6         | 0.42%   |
| Erlangen          | 6         | 0.42%   |
| Bremen            | 6         | 0.42%   |
| Braunschweig      | 6         | 0.42%   |
| Bedburg           | 6         | 0.42%   |
| Wuppertal         | 5         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 253       | 383    | 17.23%  |
| WDC                 | 133       | 229    | 9.06%   |
| Transcend           | 123       | 157    | 8.38%   |
| Kingston            | 101       | 162    | 6.88%   |
| Intel               | 90        | 135    | 6.13%   |
| Crucial             | 88        | 121    | 5.99%   |
| Seagate             | 85        | 146    | 5.79%   |
| SanDisk             | 84        | 114    | 5.72%   |
| Toshiba             | 52        | 92     | 3.54%   |
| Phison              | 37        | 53     | 2.52%   |
| Intenso             | 30        | 46     | 2.04%   |
| Hitachi             | 30        | 50     | 2.04%   |
| Hoodisk             | 28        | 44     | 1.91%   |
| HGST                | 28        | 55     | 1.91%   |
| A-DATA Technology   | 26        | 30     | 1.77%   |
| China               | 22        | 26     | 1.5%    |
| Micron Technology   | 21        | 35     | 1.43%   |
| NVMe                | 20        | 33     | 1.36%   |
| FORESEE             | 17        | 23     | 1.16%   |
| ATP                 | 16        | 19     | 1.09%   |
| OCZ                 | 14        | 19     | 0.95%   |
| SPCC                | 12        | 17     | 0.82%   |
| Hewlett-Packard     | 11        | 15     | 0.75%   |
| Corsair             | 9         | 15     | 0.61%   |
| Apple               | 8         | 8      | 0.54%   |
| Patriot             | 7         | 9      | 0.48%   |
| Innodisk            | 7         | 7      | 0.48%   |
| Dogfish             | 7         | 9      | 0.48%   |
| Apacer              | 7         | 9      | 0.48%   |
| SK hynix            | 6         | 7      | 0.41%   |
| Fujitsu             | 6         | 6      | 0.41%   |
| Verbatim            | 4         | 5      | 0.27%   |
| TCSUNBOW            | 4         | 5      | 0.27%   |
| PNY                 | 4         | 4      | 0.27%   |
| LITEONIT            | 4         | 5      | 0.27%   |
| LITEON              | 4         | 4      | 0.27%   |
| Kston               | 4         | 5      | 0.27%   |
| KIOXIA              | 4         | 4      | 0.27%   |
| Team                | 3         | 3      | 0.2%    |
| Plextor             | 3         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Phison SATA SSD 16GB             | 31        | 2.01%   |
| Transcend TS128GMSA230S 128GB    | 21        | 1.36%   |
| Samsung SSD 850 EVO 250GB        | 17        | 1.1%    |
| Kingston SA400S37120G 120GB      | 17        | 1.1%    |
| Samsung SSD 860 EVO 500GB        | 14        | 0.91%   |
| Samsung SSD 840 EVO 250GB        | 13        | 0.84%   |
| Crucial CT240BX500SSD1 240GB     | 12        | 0.78%   |
| Transcend TS64GMSA230S 64GB      | 11        | 0.71%   |
| Transcend TS256GMSA230S 256GB    | 11        | 0.71%   |
| Crucial CT120BX500SSD1 120GB     | 11        | 0.71%   |
| China SATA SSD 16GB              | 11        | 0.71%   |
| Kingston SUV500MS120G 120GB      | 10        | 0.65%   |
| Hoodisk SSD 128GB                | 10        | 0.65%   |
| FORESEE 128GB SSD                | 10        | 0.65%   |
| Transcend TS128GMSA370 128GB     | 9         | 0.58%   |
| SanDisk SSD PLUS 120GB           | 9         | 0.58%   |
| SanDisk SDSSDA120G 120GB         | 9         | 0.58%   |
| Samsung SSD 870 EVO 250GB        | 9         | 0.58%   |
| WDC WD40EFRX-68N32N0 4TB         | 8         | 0.52%   |
| Samsung SSD 850 EVO 500GB        | 8         | 0.52%   |
| Samsung SSD 840 EVO 120GB        | 8         | 0.52%   |
| Crucial CT500MX500SSD1 500GB     | 8         | 0.52%   |
| Transcend TS32GSSD370S 32GB      | 7         | 0.45%   |
| Transcend TS32GMSA370 32GB       | 7         | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB   | 7         | 0.45%   |
| Samsung SSD 840 PRO Series 256GB | 7         | 0.45%   |
| Kingston SA400S37240G 240GB      | 7         | 0.45%   |
| Kingston OM8PDP3512B-A01 512GB   | 7         | 0.45%   |
| Hoodisk SSD 64GB                 | 7         | 0.45%   |
| Hoodisk SSD 256GB                | 7         | 0.45%   |
| Crucial CT250MX500SSD1 250GB     | 7         | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB   | 6         | 0.39%   |
| Samsung SSD 960 EVO 250GB        | 6         | 0.39%   |
| Samsung SSD 860 EVO 250GB        | 6         | 0.39%   |
| Samsung SSD 850 PRO 256GB        | 6         | 0.39%   |
| Kingston SV300S37A60G 64GB       | 6         | 0.39%   |
| Intenso SSD 128GB                | 6         | 0.39%   |
| Intel SSDSC2KG240G8 240GB        | 6         | 0.39%   |
| HP RAID 1(1+0) 2TB               | 6         | 0.39%   |
| WDC WD2503ABYX-01WERA1 256GB     | 5         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 102       | 187    | 30.18%  |
| Seagate             | 81        | 140    | 23.96%  |
| Toshiba             | 33        | 55     | 9.76%   |
| Hitachi             | 29        | 46     | 8.58%   |
| HGST                | 28        | 55     | 8.28%   |
| Samsung Electronics | 16        | 21     | 4.73%   |
| NVMe                | 14        | 25     | 4.14%   |
| Hewlett-Packard     | 10        | 13     | 2.96%   |
| Fujitsu             | 6         | 6      | 1.78%   |
| OPENBSD             | 3         | 3      | 0.89%   |
| LSILOGIC            | 2         | 5      | 0.59%   |
| LSI                 | 2         | 2      | 0.59%   |
| JetFlash            | 2         | 2      | 0.59%   |
| WD MediaMax         | 1         | 2      | 0.3%    |
| Product:            | 1         | 1      | 0.3%    |
| Maxtor              | 1         | 1      | 0.3%    |
| Intenso             | 1         | 1      | 0.3%    |
| IBM/Hitachi         | 1         | 1      | 0.3%    |
| IBM                 | 1         | 1      | 0.3%    |
| Generic             | 1         | 1      | 0.3%    |
| General             | 1         | 1      | 0.3%    |
| ASMT                | 1         | 1      | 0.3%    |
| Apple               | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 184       | 273    | 18.87%  |
| Transcend           | 117       | 150    | 12%     |
| SanDisk             | 84        | 114    | 8.62%   |
| Crucial             | 84        | 115    | 8.62%   |
| Intel               | 80        | 120    | 8.21%   |
| Kingston            | 79        | 123    | 8.1%    |
| Phison              | 36        | 52     | 3.69%   |
| Intenso             | 29        | 45     | 2.97%   |
| Hoodisk             | 28        | 44     | 2.87%   |
| A-DATA Technology   | 25        | 28     | 2.56%   |
| China               | 22        | 26     | 2.26%   |
| WDC                 | 18        | 19     | 1.85%   |
| Micron Technology   | 16        | 28     | 1.64%   |
| FORESEE             | 15        | 21     | 1.54%   |
| OCZ                 | 14        | 19     | 1.44%   |
| ATP                 | 14        | 14     | 1.44%   |
| Toshiba             | 12        | 16     | 1.23%   |
| SPCC                | 10        | 14     | 1.03%   |
| Innodisk            | 7         | 7      | 0.72%   |
| Dogfish             | 7         | 9      | 0.72%   |
| Apple               | 7         | 7      | 0.72%   |
| Apacer              | 7         | 9      | 0.72%   |
| Patriot             | 6         | 8      | 0.62%   |
| Corsair             | 6         | 10     | 0.62%   |
| NVMe                | 5         | 6      | 0.51%   |
| Verbatim            | 4         | 5      | 0.41%   |
| TCSUNBOW            | 4         | 5      | 0.41%   |
| LITEONIT            | 4         | 5      | 0.41%   |
| LITEON              | 4         | 4      | 0.41%   |
| Kston               | 4         | 5      | 0.41%   |
| Team                | 3         | 3      | 0.31%   |
| Seagate             | 3         | 5      | 0.31%   |
| PNY                 | 3         | 3      | 0.31%   |
| Plextor             | 3         | 3      | 0.31%   |
| MEMXPRO             | 3         | 4      | 0.31%   |
| SK hynix            | 2         | 3      | 0.21%   |
| Protectli           | 2         | 3      | 0.21%   |
| Mushkin             | 2         | 2      | 0.21%   |
| Leven               | 2         | 4      | 0.21%   |
| KingDian            | 2         | 6      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 907       | 1365   | 67.04%  |
| HDD  | 283       | 571    | 20.92%  |
| NVMe | 163       | 254    | 12.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1102      | 1936   | 87.11%  |
| NVMe | 163       | 254    | 12.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 997       | 1500   | 82.06%  |
| 0.51-1.0        | 112       | 176    | 9.22%   |
| 1.01-2.0        | 53        | 109    | 4.36%   |
| 3.01-4.0        | 24        | 80     | 1.98%   |
| 4.01-10.0       | 13        | 23     | 1.07%   |
| 2.01-3.0        | 12        | 36     | 0.99%   |
| 10.01-20.0      | 3         | 11     | 0.25%   |
| More than 100.0 | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 569       | 41.99%  |
| 1-20           | 192       | 14.17%  |
| 251-500        | 191       | 14.1%   |
| 21-50          | 153       | 11.29%  |
| 51-100         | 149       | 11%     |
| 501-1000       | 64        | 4.72%   |
| More than 3000 | 13        | 0.96%   |
| 1001-2000      | 10        | 0.74%   |
| Unknown        | 9         | 0.66%   |
| 2001-3000      | 5         | 0.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1224      | 90.2%   |
| 21-50          | 60        | 4.42%   |
| 51-100         | 25        | 1.84%   |
| 101-250        | 19        | 1.4%    |
| Unknown        | 9         | 0.66%   |
| 251-500        | 7         | 0.52%   |
| 1001-2000      | 5         | 0.37%   |
| 501-1000       | 4         | 0.29%   |
| More than 3000 | 2         | 0.15%   |
| 2001-3000      | 2         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 3         | 5      | 2.36%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2         | 7      | 1.57%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 2         | 4      | 1.57%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2         | 4      | 1.57%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2         | 2      | 1.57%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2         | 2      | 1.57%   |
| Seagate ST9320325AS 320GB                    | 2         | 2      | 1.57%   |
| Seagate ST3160318AS 160GB                    | 2         | 2      | 1.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 1.57%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 2         | 4      | 1.57%   |
| Samsung Electronics HD501LJ 500GB            | 2         | 2      | 1.57%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2         | 4      | 1.57%   |
| Kingston SMS200S360G 64GB                    | 2         | 2      | 1.57%   |
| Intenso SSD SATAIII 120GB                    | 2         | 2      | 1.57%   |
| Intel SSDSC2CT180A3 180GB                    | 2         | 2      | 1.57%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 1.57%   |
| Hitachi HTS543232L9SA02 320GB                | 2         | 3      | 1.57%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 1.57%   |
| HGST HTS541010A7E630 1TB                     | 2         | 3      | 1.57%   |
| Crucial CT275MX300SSD1 275GB                 | 2         | 2      | 1.57%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 1         | 1      | 0.79%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1         | 3      | 0.79%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 0.79%   |
| WDC WD3000BLFS-60YBU2 304GB                  | 1         | 2      | 0.79%   |
| WDC WD2503ABYX-01WERA1 256GB                 | 1         | 2      | 0.79%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1         | 1      | 0.79%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 0.79%   |
| WDC WD1600AAJS-08L7A0 160GB                  | 1         | 1      | 0.79%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1         | 1      | 0.79%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1         | 1      | 0.79%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 1         | 5      | 0.79%   |
| Toshiba MQ02ABD100H 1TB                      | 1         | 4      | 0.79%   |
| Toshiba MK2018GAP 20GB                       | 1         | 1      | 0.79%   |
| SMI SSD DISK 120GB                           | 1         | 1      | 0.79%   |
| Seagate ST9500620NS 500GB                    | 1         | 1      | 0.79%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 0.79%   |
| Seagate ST9250827AS 250GB                    | 1         | 2      | 0.79%   |
| Seagate ST9160310AS 160GB                    | 1         | 2      | 0.79%   |
| Seagate ST6000DM003-2CY186 6TB               | 1         | 1      | 0.79%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 26     | 17.32%  |
| WDC                 | 18        | 32     | 14.17%  |
| Intel               | 12        | 13     | 9.45%   |
| Kingston            | 11        | 16     | 8.66%   |
| Hitachi             | 11        | 16     | 8.66%   |
| Samsung Electronics | 9         | 12     | 7.09%   |
| Crucial             | 8         | 13     | 6.3%    |
| SanDisk             | 6         | 9      | 4.72%   |
| HGST                | 6         | 8      | 4.72%   |
| Toshiba             | 5         | 12     | 3.94%   |
| Micron Technology   | 4         | 6      | 3.15%   |
| Intenso             | 3         | 3      | 2.36%   |
| A-DATA Technology   | 3         | 4      | 2.36%   |
| OCZ                 | 2         | 2      | 1.57%   |
| Corsair             | 2         | 4      | 1.57%   |
| Apacer              | 2         | 2      | 1.57%   |
| SMI                 | 1         | 1      | 0.79%   |
| Maxtor              | 1         | 1      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 26     | 34.38%  |
| WDC                 | 17        | 31     | 26.56%  |
| Hitachi             | 11        | 16     | 17.19%  |
| HGST                | 6         | 8      | 9.38%   |
| Samsung Electronics | 4         | 5      | 6.25%   |
| Toshiba             | 2         | 5      | 3.13%   |
| Maxtor              | 1         | 1      | 1.56%   |
| Fujitsu             | 1         | 1      | 1.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 62        | 87     | 49.6%   |
| HDD  | 62        | 93     | 49.6%   |
| NVMe | 1         | 1      | 0.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Micron Technology 1100_MTFDDAV256TBN 256GB | 1         | 1      | 33.33%  |
| Kingston SV300S37A60G 64GB                 | 1         | 1      | 33.33%  |
| Intel SSDSC2BW120H6 120GB                  | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Micron Technology | 1         | 1      | 33.33%  |
| Kingston          | 1         | 1      | 33.33%  |
| Intel             | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1108      | 1929   | 86.29%  |
| Malfunc  | 123       | 181    | 9.58%   |
| Detected | 50        | 77     | 3.89%   |
| Failed   | 3         | 3      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1003      | 65.38%  |
| AMD                              | 241       | 15.71%  |
| Samsung Electronics              | 77        | 5.02%   |
| Broadcom / LSI                   | 34        | 2.22%   |
| SanDisk                          | 25        | 1.63%   |
| Kingston Technology Company      | 21        | 1.37%   |
| ASMedia Technology               | 18        | 1.17%   |
| Phison Electronics               | 13        | 0.85%   |
| Marvell Technology Group         | 12        | 0.78%   |
| Nvidia                           | 11        | 0.72%   |
| Hewlett-Packard                  | 10        | 0.65%   |
| Toshiba                          | 9         | 0.59%   |
| Silicon Motion                   | 6         | 0.39%   |
| SK hynix                         | 5         | 0.33%   |
| Micron Technology                | 5         | 0.33%   |
| KIOXIA                           | 5         | 0.33%   |
| Micron/Crucial Technology        | 4         | 0.26%   |
| ATP ELECTRONICS                  | 4         | 0.26%   |
| Unknown                          | 4         | 0.26%   |
| VIA Technologies                 | 3         | 0.2%    |
| Silicon Image                    | 3         | 0.2%    |
| Shenzhen Longsys Electronics     | 3         | 0.2%    |
| Adaptec                          | 3         | 0.2%    |
| 3ware                            | 3         | 0.2%    |
| ULi Electronics                  | 2         | 0.13%   |
| ADATA Technology                 | 2         | 0.13%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Seagate Technology               | 1         | 0.07%   |
| Realtek Semiconductor            | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| Integrated Technology Express    | 1         | 0.07%   |
| Enmotus                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 159       | 9.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 92        | 5.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 88        | 5.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 74        | 4.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 55        | 3.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 53        | 3.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 48        | 2.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 47        | 2.7%    |
| AMD FCH SATA Controller [IDE mode]                                               | 41        | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 39        | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 36        | 2.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 34        | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 34        | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 33        | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 32        | 1.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 28        | 1.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 23        | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 22        | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 22        | 1.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 22        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 1.26%   |
| Unknown                                                                          | 22        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 20        | 1.15%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 18        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 18        | 1.03%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 17        | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 17        | 0.98%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 17        | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 16        | 0.92%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 16        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 0.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 0.92%   |
| AMD 400 Series Chipset SATA Controller                                           | 16        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 14        | 0.8%    |
| Intel SATA Controller [RAID mode]                                                | 13        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 12        | 0.69%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 11        | 0.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 11        | 0.63%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 10        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1102      | 69.88%  |
| NVMe | 190       | 12.05%  |
| IDE  | 188       | 11.92%  |
| RAID | 81        | 5.14%   |
| SAS  | 11        | 0.7%    |
| SCSI | 5         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1049      | 79.47%  |
| AMD     | 255       | 19.32%  |
| ARM     | 12        | 0.91%   |
| VIA     | 1         | 0.08%   |
| Sun     | 1         | 0.08%   |
| PowerPC | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                          | 82        | 6.18%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 31        | 2.34%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 30        | 2.26%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 22        | 1.66%   |
| Intel Celeron CPU N3450 @ 1.10GHz         | 21        | 1.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 14        | 1.06%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 14        | 1.06%   |
| Intel Xeon CPU D-1518 @ 2.20GHz           | 13        | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 12        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz         | 12        | 0.9%    |
| Intel Celeron J4105 CPU @ 1.50GHz         | 12        | 0.9%    |
| Intel Atom CPU D525 @ 1.80GHz             | 12        | 0.9%    |
| Intel Atom CPU C3558 @ 2.20GHz            | 12        | 0.9%    |
| Intel Core i5-6500 CPU @ 3.20GHz          | 11        | 0.83%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 11        | 0.83%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 10        | 0.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 9         | 0.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 9         | 0.68%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9         | 0.68%   |
| Intel Atom CPU C2558 @ 2.40GHz            | 9         | 0.68%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 9         | 0.68%   |
| AMD G-T40E Processor                      | 9         | 0.68%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 8         | 0.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz         | 8         | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz         | 8         | 0.6%    |
| Intel Core i3-7100U CPU @ 2.40GHz         | 8         | 0.6%    |
| Intel Celeron N4100 CPU @ 1.10GHz         | 8         | 0.6%    |
| Intel Celeron J4115 CPU @ 1.80GHz         | 8         | 0.6%    |
| Intel Celeron CPU N3160 @ 1.60GHz         | 8         | 0.6%    |
| Intel Celeron                             | 8         | 0.6%    |
| Intel Atom CPU N450 @ 1.66GHz             | 8         | 0.6%    |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz       | 7         | 0.53%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 7         | 0.53%   |
| Intel CPU Version                         | 7         | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz          | 7         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz         | 7         | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 7         | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz         | 7         | 0.53%   |
| Intel Celeron N5105 @ 2.00GHz             | 7         | 0.53%   |
| AMD GX-420CA SOC with Radeon HD Graphics  | 7         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 237       | 17.9%   |
| Intel Core i5           | 227       | 17.15%  |
| Intel Xeon              | 133       | 10.05%  |
| AMD GX                  | 123       | 9.29%   |
| Intel Core i7           | 113       | 8.53%   |
| Intel Core i3           | 106       | 8.01%   |
| Intel Atom              | 98        | 7.4%    |
| Other                   | 33        | 2.49%   |
| Intel Pentium           | 32        | 2.42%   |
| Intel Core 2 Duo        | 24        | 1.81%   |
| AMD Ryzen 7             | 23        | 1.74%   |
| AMD Ryzen 5             | 22        | 1.66%   |
| Intel Pentium Silver    | 15        | 1.13%   |
| AMD G                   | 15        | 1.13%   |
| AMD FX                  | 14        | 1.06%   |
| ARM Cortex              | 10        | 0.76%   |
| AMD EPYC                | 9         | 0.68%   |
| Intel Core 2 Quad       | 8         | 0.6%    |
| Intel Pentium Gold      | 7         | 0.53%   |
| Intel Pentium Dual-Core | 7         | 0.53%   |
| AMD Ryzen Embedded      | 7         | 0.53%   |
| AMD Ryzen 5 PRO         | 5         | 0.38%   |
| AMD Ryzen 3             | 5         | 0.38%   |
| AMD Ryzen 9             | 4         | 0.3%    |
| Intel Xeon Silver       | 3         | 0.23%   |
| Intel Xeon Gold         | 3         | 0.23%   |
| Intel Genuine           | 3         | 0.23%   |
| Intel Core 2            | 3         | 0.23%   |
| AMD Turion II Neo       | 3         | 0.23%   |
| AMD Ryzen 7 PRO         | 3         | 0.23%   |
| AMD Athlon 64 X2        | 3         | 0.23%   |
| Intel Pentium M         | 2         | 0.15%   |
| Intel Pentium Dual      | 2         | 0.15%   |
| Intel Pentium 4         | 2         | 0.15%   |
| AMD Ryzen Threadripper  | 2         | 0.15%   |
| AMD E                   | 2         | 0.15%   |
| AMD Athlon Dual Core    | 2         | 0.15%   |
| AMD A4                  | 2         | 0.15%   |
| AMD A10                 | 2         | 0.15%   |
| Intel Xeon Bronze       | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 659       | 49.85%  |
| 2       | 414       | 31.32%  |
| 8       | 70        | 5.3%    |
| Unknown | 53        | 4.01%   |
| 6       | 43        | 3.25%   |
| 16      | 30        | 2.27%   |
| 12      | 23        | 1.74%   |
| 1       | 21        | 1.59%   |
| 32      | 4         | 0.3%    |
| 128     | 1         | 0.08%   |
| 36      | 1         | 0.08%   |
| 24      | 1         | 0.08%   |
| 20      | 1         | 0.08%   |
| 10      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1256      | 95.15%  |
| 2       | 41        | 3.11%   |
| Unknown | 23        | 1.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 758       | 57.42%  |
| 2       | 501       | 37.95%  |
| Unknown | 61        | 4.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 188       | 14.22%  |
| Silvermont    | 124       | 9.38%   |
| Haswell       | 117       | 8.85%   |
| Puma          | 100       | 7.56%   |
| Skylake       | 84        | 6.35%   |
| Goldmont plus | 75        | 5.67%   |
| IvyBridge     | 74        | 5.6%    |
| Goldmont      | 67        | 5.07%   |
| SandyBridge   | 57        | 4.31%   |
| Penryn        | 48        | 3.63%   |
| Unknown       | 47        | 3.56%   |
| Broadwell     | 44        | 3.33%   |
| Bonnell       | 41        | 3.1%    |
| Westmere      | 29        | 2.19%   |
| Zen           | 28        | 2.12%   |
| Jaguar        | 26        | 1.97%   |
| Core          | 24        | 1.82%   |
| Zen+          | 21        | 1.59%   |
| Zen 2         | 21        | 1.59%   |
| Bobcat        | 18        | 1.36%   |
| Piledriver    | 14        | 1.06%   |
| Nehalem       | 14        | 1.06%   |
| CometLake     | 13        | 0.98%   |
| IceLake       | 10        | 0.76%   |
| TigerLake     | 8         | 0.61%   |
| Zen 3         | 6         | 0.45%   |
| K8 Hammer     | 6         | 0.45%   |
| NetBurst      | 4         | 0.3%    |
| Bulldozer     | 4         | 0.3%    |
| P6            | 3         | 0.23%   |
| K10           | 3         | 0.23%   |
| Steamroller   | 2         | 0.15%   |
| Geode         | 1         | 0.08%   |
| Excavator     | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 801       | 65.07%  |
| AMD                                          | 144       | 11.7%   |
| Nvidia                                       | 110       | 8.94%   |
| ASPEED Technology                            | 110       | 8.94%   |
| Matrox Electronics Systems                   | 62        | 5.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.08%   |
| VIA Technologies                             | 1         | 0.08%   |
| Trident Microsystems                         | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 110       | 8.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 4.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 53        | 4.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 52        | 4.16%   |
| Intel HD Graphics 500                                                                    | 46        | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40        | 3.2%    |
| Intel HD Graphics 620                                                                    | 38        | 3.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 2.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 2.32%   |
| Intel HD Graphics 530                                                                    | 28        | 2.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 2.24%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 26        | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 2%      |
| Intel UHD Graphics 620                                                                   | 24        | 1.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 24        | 1.92%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 23        | 1.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.6%    |
| Intel HD Graphics 5500                                                                   | 18        | 1.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 1.2%    |
| Matrox Electronics Systems MGA G200EH                                                    | 14        | 1.12%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 14        | 1.12%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 14        | 1.12%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 13        | 1.04%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 12        | 0.96%   |
| Intel JasperLake [UHD Graphics]                                                          | 12        | 0.96%   |
| Intel HD Graphics 630                                                                    | 12        | 0.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 12        | 0.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.72%   |
| Intel HD Graphics 510                                                                    | 9         | 0.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 9         | 0.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.72%   |
| AMD Renoir                                                                               | 9         | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.72%   |
| AMD ES1000                                                                               | 9         | 0.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 701       | 53.03%  |
| Other                    | 138       | 10.44%  |
| 1 x AMD                  | 135       | 10.21%  |
| 1 x ASPEED               | 99        | 7.49%   |
| 1 x Nvidia               | 79        | 5.98%   |
| 1 x Matrox               | 61        | 4.61%   |
| 2 x Intel                | 56        | 4.24%   |
| Intel + Nvidia           | 28        | 2.12%   |
| Intel + ASPEED           | 10        | 0.76%   |
| Intel + AMD              | 5         | 0.38%   |
| AMD + Nvidia             | 3         | 0.23%   |
| 2 x AMD                  | 1         | 0.08%   |
| 1 x XGI                  | 1         | 0.08%   |
| 1 x VIA                  | 1         | 0.08%   |
| 1 x Trident Microsystems | 1         | 0.08%   |
| 1 x SiS                  | 1         | 0.08%   |
| Nvidia + ASPEED          | 1         | 0.08%   |
| Intel + Matrox           | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1109      | 83.76%  |
| Unknown     | 158       | 11.93%  |
| Proprietary | 57        | 4.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1246      | 93.68%  |
| 1.01-2.0   | 28        | 2.11%   |
| 0.01-0.5   | 19        | 1.43%   |
| 3.01-4.0   | 14        | 1.05%   |
| 7.01-8.0   | 8         | 0.6%    |
| 0.51-1.0   | 7         | 0.53%   |
| 5.01-6.0   | 4         | 0.3%    |
| 2.01-3.0   | 4         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 34        | 12.64%  |
| AU Optronics            | 33        | 12.27%  |
| Samsung Electronics     | 27        | 10.04%  |
| Goldstar                | 17        | 6.32%   |
| Dell                    | 17        | 6.32%   |
| Apple                   | 16        | 5.95%   |
| Chimei Innolux          | 15        | 5.58%   |
| BenQ                    | 15        | 5.58%   |
| Lenovo                  | 13        | 4.83%   |
| BOE                     | 9         | 3.35%   |
| Ancor Communications    | 9         | 3.35%   |
| Eizo                    | 7         | 2.6%    |
| Acer                    | 7         | 2.6%    |
| Iiyama                  | 6         | 2.23%   |
| Hewlett-Packard         | 6         | 2.23%   |
| NEC Computers           | 4         | 1.49%   |
| LG Electronics          | 4         | 1.49%   |
| AOC                     | 4         | 1.49%   |
| Sharp                   | 3         | 1.12%   |
| PANDA                   | 3         | 1.12%   |
| InfoVision              | 2         | 0.74%   |
| HannStar                | 2         | 0.74%   |
| Fujitsu Siemens         | 2         | 0.74%   |
| WYT                     | 1         | 0.37%   |
| TRU                     | 1         | 0.37%   |
| Toshiba                 | 1         | 0.37%   |
| Philips                 | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| Mi                      | 1         | 0.37%   |
| Medion                  | 1         | 0.37%   |
| LTM                     | 1         | 0.37%   |
| LG Philips              | 1         | 0.37%   |
| JDI                     | 1         | 0.37%   |
| Idek Iiyama             | 1         | 0.37%   |
| Chi Mei Optoelectronics | 1         | 0.37%   |
| Belinea                 | 1         | 0.37%   |
| ASUSTek Computer        | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 4         | 1.44%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 3         | 1.08%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 3         | 1.08%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 3         | 1.08%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 3         | 1.08%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 3         | 1.08%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 2         | 0.72%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch    | 2         | 0.72%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch         | 2         | 0.72%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch          | 2         | 0.72%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 2         | 0.72%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 0.72%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 0.72%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 2         | 0.72%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 2         | 0.72%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 2         | 0.72%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 2         | 0.72%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch         | 2         | 0.72%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                 | 2         | 0.72%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 2         | 0.72%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                 | 2         | 0.72%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                    | 2         | 0.72%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 2         | 0.72%   |
| Dell LCD Monitor U2412M 3840x1200                                    | 2         | 0.72%   |
| Dell LCD Monitor U2412M                                              | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 0.72%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                 | 2         | 0.72%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 2         | 0.72%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                    | 2         | 0.72%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                    | 2         | 0.72%   |
| BenQ GL2450H BNQ78A6 1920x1080 530x300mm 24.0-inch                   | 2         | 0.72%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                    | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch        | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch       | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 2         | 0.72%   |
| AOC U3277WB AOC3277 3840x2160 700x390mm 31.5-inch                    | 2         | 0.72%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch    | 2         | 0.72%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                 | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 98        | 36.57%  |
| 1366x768 (WXGA)    | 44        | 16.42%  |
| 3840x2160 (4K)     | 21        | 7.84%   |
| 2560x1440 (QHD)    | 21        | 7.84%   |
| 1920x1200 (WUXGA)  | 18        | 6.72%   |
| 1680x1050 (WSXGA+) | 10        | 3.73%   |
| 1280x800 (WXGA)    | 10        | 3.73%   |
| 1280x1024 (SXGA)   | 9         | 3.36%   |
| 1600x900 (HD+)     | 7         | 2.61%   |
| 1440x900 (WXGA+)   | 7         | 2.61%   |
| 3440x1440          | 4         | 1.49%   |
| 2560x1080          | 3         | 1.12%   |
| Unknown            | 3         | 1.12%   |
| 3840x1200          | 2         | 0.75%   |
| 3200x1800 (QHD+)   | 2         | 0.75%   |
| 1024x768 (XGA)     | 2         | 0.75%   |
| 720x1280           | 1         | 0.37%   |
| 3600x1080          | 1         | 0.37%   |
| 3000x2000          | 1         | 0.37%   |
| 2880x1800          | 1         | 0.37%   |
| 2880x1620          | 1         | 0.37%   |
| 2560x1600          | 1         | 0.37%   |
| 1920x540           | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 52        | 19.4%   |
| 15      | 40        | 14.93%  |
| 24      | 34        | 12.69%  |
| 27      | 31        | 11.57%  |
| 12      | 23        | 8.58%   |
| Unknown | 14        | 5.22%   |
| 23      | 13        | 4.85%   |
| 21      | 12        | 4.48%   |
| 22      | 6         | 2.24%   |
| 17      | 6         | 2.24%   |
| 14      | 6         | 2.24%   |
| 11      | 6         | 2.24%   |
| 34      | 5         | 1.87%   |
| 19      | 5         | 1.87%   |
| 31      | 3         | 1.12%   |
| 20      | 3         | 1.12%   |
| 32      | 2         | 0.75%   |
| 25      | 2         | 0.75%   |
| 46      | 1         | 0.37%   |
| 39      | 1         | 0.37%   |
| 18      | 1         | 0.37%   |
| 16      | 1         | 0.37%   |
| 6       | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 28.84%  |
| 501-600     | 74        | 27.72%  |
| 201-300     | 53        | 19.85%  |
| 401-500     | 22        | 8.24%   |
| Unknown     | 14        | 5.24%   |
| 351-400     | 9         | 3.37%   |
| 601-700     | 8         | 3%      |
| 701-800     | 7         | 2.62%   |
| 801-900     | 1         | 0.37%   |
| 101-200     | 1         | 0.37%   |
| 1001-1500   | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 180       | 70.31%  |
| 16/10   | 45        | 17.58%  |
| Unknown | 13        | 5.08%   |
| 5/4     | 6         | 2.34%   |
| 21/9    | 5         | 1.95%   |
| 4/3     | 3         | 1.17%   |
| 3/2     | 3         | 1.17%   |
| 6/5     | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 48        | 17.91%  |
| 81-90          | 46        | 17.16%  |
| 301-350        | 31        | 11.57%  |
| 91-100         | 29        | 10.82%  |
| 61-70          | 23        | 8.58%   |
| 251-300        | 18        | 6.72%   |
| Unknown        | 14        | 5.22%   |
| 101-110        | 12        | 4.48%   |
| 71-80          | 11        | 4.1%    |
| 351-500        | 10        | 3.73%   |
| 151-200        | 10        | 3.73%   |
| 51-60          | 6         | 2.24%   |
| 121-130        | 4         | 1.49%   |
| 141-150        | 2         | 0.75%   |
| 501-1000       | 2         | 0.75%   |
| 1-40           | 1         | 0.37%   |
| 131-140        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 87        | 33.08%  |
| 121-160       | 77        | 29.28%  |
| 101-120       | 51        | 19.39%  |
| 161-240       | 25        | 9.51%   |
| Unknown       | 14        | 5.32%   |
| More than 240 | 8         | 3.04%   |
| 1-50          | 1         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1071      | 80.53%  |
| 1     | 230       | 17.29%  |
| 2     | 27        | 2.03%   |
| 3     | 2         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1044      | 57.71%  |
| Realtek Semiconductor             | 416       | 23%     |
| Broadcom                          | 107       | 5.91%   |
| Qualcomm Atheros                  | 86        | 4.75%   |
| IMC Networks                      | 14        | 0.77%   |
| Marvell Technology Group          | 11        | 0.61%   |
| Ericsson Business Mobile Networks | 10        | 0.55%   |
| Ralink Technology                 | 9         | 0.5%    |
| AMD                               | 9         | 0.5%    |
| Edimax Technology                 | 8         | 0.44%   |
| Ralink                            | 7         | 0.39%   |
| Mellanox Technologies             | 7         | 0.39%   |
| D-Link System                     | 7         | 0.39%   |
| TP-Link                           | 6         | 0.33%   |
| Nvidia                            | 6         | 0.33%   |
| American Megatrends               | 6         | 0.33%   |
| U-Blox                            | 4         | 0.22%   |
| MediaTek                          | 4         | 0.22%   |
| IBM                               | 3         | 0.17%   |
| Google                            | 3         | 0.17%   |
| Emulex                            | 3         | 0.17%   |
| Aquantia                          | 3         | 0.17%   |
| Sierra Wireless                   | 2         | 0.11%   |
| Samsung Electronics               | 2         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.11%   |
| NetXen Incorporated               | 2         | 0.11%   |
| ICS Advent                        | 2         | 0.11%   |
| Huawei Technologies               | 2         | 0.11%   |
| Hewlett-Packard                   | 2         | 0.11%   |
| Dell                              | 2         | 0.11%   |
| Chelsio Communications            | 2         | 0.11%   |
| ASUSTek Computer                  | 2         | 0.11%   |
| Xiaomi                            | 1         | 0.06%   |
| ULi Electronics                   | 1         | 0.06%   |
| SysKonnect                        | 1         | 0.06%   |
| Standard Microsystems [SMC]       | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.06%   |
| Oculus VR                         | 1         | 0.06%   |
| National Semiconductor            | 1         | 0.06%   |
| Micro Star International          | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 362       | 16.15%  |
| Intel I211 Gigabit Network Connection                                         | 232       | 10.35%  |
| Intel I210 Gigabit Network Connection                                         | 194       | 8.66%   |
| Intel I350 Gigabit Network Connection                                         | 94        | 4.19%   |
| Intel 82574L Gigabit Network Connection                                       | 62        | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 53        | 2.37%   |
| Intel 82583V Gigabit Network Connection                                       | 31        | 1.38%   |
| Intel 82576 Gigabit Network Connection                                        | 30        | 1.34%   |
| Intel 82580 Gigabit Network Connection                                        | 29        | 1.29%   |
| Intel Wireless 3165                                                           | 26        | 1.16%   |
| Intel Wi-Fi 6 AX200                                                           | 26        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                             | 24        | 1.07%   |
| Intel Wireless 7265                                                           | 24        | 1.07%   |
| Intel Ethernet Controller I225-V                                              | 23        | 1.03%   |
| Intel Ethernet Connection I217-LM                                             | 22        | 0.98%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 22        | 0.98%   |
| Intel Wireless 8265 / 8275                                                    | 20        | 0.89%   |
| Intel Ethernet Connection I219-LM                                             | 19        | 0.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 19        | 0.85%   |
| Intel Ethernet Connection X553 1GbE                                           | 18        | 0.8%    |
| Intel Ethernet Connection I354                                                | 18        | 0.8%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 18        | 0.8%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 17        | 0.76%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 16        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 16        | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 15        | 0.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 14        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                          | 14        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                         | 14        | 0.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 13        | 0.58%   |
| Intel Wireless 8260                                                           | 13        | 0.58%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 13        | 0.58%   |
| Intel Wireless 7260                                                           | 12        | 0.54%   |
| Intel Wireless 3160                                                           | 12        | 0.54%   |
| Intel Ethernet Controller X550                                                | 12        | 0.54%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 12        | 0.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 12        | 0.54%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 11        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11        | 0.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 240       | 53.45%  |
| Qualcomm Atheros                | 75        | 16.7%   |
| Realtek Semiconductor           | 43        | 9.58%   |
| Broadcom                        | 35        | 7.8%    |
| IMC Networks                    | 14        | 3.12%   |
| Ralink Technology               | 9         | 2%      |
| Edimax Technology               | 8         | 1.78%   |
| Ralink                          | 7         | 1.56%   |
| TP-Link                         | 6         | 1.34%   |
| MediaTek                        | 4         | 0.89%   |
| Sierra Wireless                 | 2         | 0.45%   |
| Qualcomm Atheros Communications | 2         | 0.45%   |
| ASUSTek Computer                | 2         | 0.45%   |
| Micro Star International        | 1         | 0.22%   |
| Dell                            | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                             | 26        | 5.74%   |
| Intel Wi-Fi 6 AX200                                             | 26        | 5.74%   |
| Intel Wireless 7265                                             | 24        | 5.3%    |
| Intel Wireless 8265 / 8275                                      | 20        | 4.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 16        | 3.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 15        | 3.31%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 14        | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 13        | 2.87%   |
| Intel Wireless 8260                                             | 13        | 2.87%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 13        | 2.87%   |
| Intel Wireless 7260                                             | 12        | 2.65%   |
| Intel Wireless 3160                                             | 12        | 2.65%   |
| Intel Centrino Ultimate-N 6300                                  | 10        | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 8         | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 8         | 1.77%   |
| Intel Wireless-AC 9260                                          | 8         | 1.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 7         | 1.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 7         | 1.55%   |
| Intel Centrino Advanced-N 6235                                  | 7         | 1.55%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 7         | 1.55%   |
| Broadcom BCM4321 802.11a/b/g/n                                  | 7         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 6         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 6         | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 5         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 5         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 5         | 1.1%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 5         | 1.1%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                       | 4         | 0.88%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 4         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 4         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 4         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 4         | 0.88%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 4         | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 4         | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller          | 4         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 3         | 0.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 3         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 3         | 0.66%   |
| Ralink RT5572 Wireless Adapter                                  | 3         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                  | 3         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 916       | 62.14%  |
| Realtek Semiconductor       | 403       | 27.34%  |
| Broadcom                    | 80        | 5.43%   |
| Qualcomm Atheros            | 14        | 0.95%   |
| Marvell Technology Group    | 11        | 0.75%   |
| AMD                         | 9         | 0.61%   |
| Nvidia                      | 6         | 0.41%   |
| American Megatrends         | 6         | 0.41%   |
| D-Link System               | 4         | 0.27%   |
| IBM                         | 3         | 0.2%    |
| Google                      | 3         | 0.2%    |
| Emulex                      | 3         | 0.2%    |
| Aquantia                    | 3         | 0.2%    |
| Samsung Electronics         | 2         | 0.14%   |
| ICS Advent                  | 2         | 0.14%   |
| Xiaomi                      | 1         | 0.07%   |
| SysKonnect                  | 1         | 0.07%   |
| Standard Microsystems [SMC] | 1         | 0.07%   |
| National Semiconductor      | 1         | 0.07%   |
| JMicron Technology          | 1         | 0.07%   |
| Insyde Software             | 1         | 0.07%   |
| Digital Equipment           | 1         | 0.07%   |
| Davicom Semiconductor       | 1         | 0.07%   |
| Apple                       | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 362       | 20.77%  |
| Intel I211 Gigabit Network Connection                                         | 232       | 13.31%  |
| Intel I210 Gigabit Network Connection                                         | 194       | 11.13%  |
| Intel I350 Gigabit Network Connection                                         | 94        | 5.39%   |
| Intel 82574L Gigabit Network Connection                                       | 62        | 3.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 53        | 3.04%   |
| Intel 82583V Gigabit Network Connection                                       | 31        | 1.78%   |
| Intel 82576 Gigabit Network Connection                                        | 30        | 1.72%   |
| Intel 82580 Gigabit Network Connection                                        | 29        | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                             | 24        | 1.38%   |
| Intel Ethernet Controller I225-V                                              | 23        | 1.32%   |
| Intel Ethernet Connection I217-LM                                             | 22        | 1.26%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 22        | 1.26%   |
| Intel Ethernet Connection I219-LM                                             | 19        | 1.09%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 19        | 1.09%   |
| Intel Ethernet Connection X553 1GbE                                           | 18        | 1.03%   |
| Intel Ethernet Connection I354                                                | 18        | 1.03%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 18        | 1.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 17        | 0.98%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 16        | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                          | 14        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 14        | 0.8%    |
| Intel Ethernet Controller X550                                                | 12        | 0.69%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 12        | 0.69%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 12        | 0.69%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 11        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11        | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 10        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                          | 10        | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                          | 10        | 0.57%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 10        | 0.57%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 10        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                      | 9         | 0.52%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 9         | 0.52%   |
| Intel Ethernet Connection I217-V                                              | 8         | 0.46%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 7         | 0.4%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 7         | 0.4%    |
| Intel 82579V Gigabit Network Connection                                       | 7         | 0.4%    |
| Nvidia MCP79 Ethernet                                                         | 6         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1288      | 73.68%  |
| WiFi     | 417       | 23.86%  |
| Unknown  | 27        | 1.54%   |
| Modem    | 16        | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1236      | 87.6%   |
| WiFi     | 165       | 11.69%  |
| Unknown  | 9         | 0.64%   |
| Modem    | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 347       | 26.09%  |
| 4     | 240       | 18.05%  |
| 3     | 215       | 16.17%  |
| 1     | 157       | 11.8%   |
| 6     | 154       | 11.58%  |
| 5     | 88        | 6.62%   |
| 8     | 57        | 4.29%   |
| 10    | 23        | 1.73%   |
| 7     | 16        | 1.2%    |
| 0     | 16        | 1.2%    |
| 12    | 7         | 0.53%   |
| 9     | 7         | 0.53%   |
| 14    | 2         | 0.15%   |
| 11    | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1100      | 80.53%  |
| Yes  | 266       | 19.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 148       | 55.64%  |
| Qualcomm Atheros Communications | 21        | 7.89%   |
| IMC Networks                    | 21        | 7.89%   |
| Apple                           | 21        | 7.89%   |
| Broadcom                        | 20        | 7.52%   |
| Realtek Semiconductor           | 10        | 3.76%   |
| ASUSTek Computer                | 7         | 2.63%   |
| Foxconn / Hon Hai               | 4         | 1.5%    |
| MediaTek                        | 3         | 1.13%   |
| Lite-On Technology              | 3         | 1.13%   |
| Dell                            | 2         | 0.75%   |
| Cambridge Silicon Radio         | 2         | 0.75%   |
| Alps Electric                   | 2         | 0.75%   |
| Micro Star International        | 1         | 0.38%   |
| Hewlett-Packard                 | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                         | 70        | 26.22%  |
| Intel AX200 Bluetooth                                      | 29        | 10.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)             | 20        | 7.49%   |
| Intel Centrino Bluetooth Wireless Transceiver              | 9         | 3.37%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                | 9         | 3.37%   |
| Broadcom BCM2045B (BDC-2.1)                                | 8         | 3%      |
| Apple Bluetooth Host Controller                            | 8         | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                   | 7         | 2.62%   |
| Intel Wireless-AC 3168 Bluetooth                           | 7         | 2.62%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip       | 6         | 2.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                       | 6         | 2.25%   |
| Realtek  Bluetooth 4.2 Adapter                             | 5         | 1.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                      | 5         | 1.87%   |
| Intel AX201 Bluetooth                                      | 5         | 1.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                 | 5         | 1.87%   |
| Qualcomm Atheros AR9462 Bluetooth                          | 3         | 1.12%   |
| MediaTek Wireless_Device                                   | 3         | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                           | 3         | 1.12%   |
| IMC Networks Bluetooth Radio                               | 3         | 1.12%   |
| ASUS ASUS USB-BT500                                        | 3         | 1.12%   |
| Realtek  Bluetooth Adapter                                 | 2         | 0.75%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                    | 2         | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                     | 2         | 0.75%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE        | 2         | 0.75%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)            | 2         | 0.75%   |
| Intel AX210 Bluetooth                                      | 2         | 0.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 2         | 0.75%   |
| Broadcom BCM2045 Bluetooth                                 | 2         | 0.75%   |
| Apple Bluetooth USB Host Controller                        | 2         | 0.75%   |
| Apple Bluetooth HCI                                        | 2         | 0.75%   |
| Apple Apple Broadcom Built-in Bluetooth                    | 2         | 0.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                    | 1         | 0.37%   |
| Realtek RTL8821A Bluetooth                                 | 1         | 0.37%   |
| Realtek RTL8723B Bluetooth                                 | 1         | 0.37%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE       | 1         | 0.37%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth              | 1         | 0.37%   |
| Qualcomm Atheros Bluetooth                                 | 1         | 0.37%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter | 1         | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth                          | 1         | 0.37%   |
| Micro Star International MS-6970 BToes Bluetooth adapter   | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 705       | 71.5%   |
| AMD                                          | 159       | 16.13%  |
| Nvidia                                       | 76        | 7.71%   |
| C-Media Electronics                          | 10        | 1.01%   |
| Logitech                                     | 5         | 0.51%   |
| Texas Instruments                            | 4         | 0.41%   |
| GN Netcom                                    | 4         | 0.41%   |
| JMTek                                        | 3         | 0.3%    |
| VIA Technologies                             | 2         | 0.2%    |
| Creative Labs                                | 2         | 0.2%    |
| Corsair                                      | 2         | 0.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.1%    |
| ZOOM                                         | 1         | 0.1%    |
| Yamaha                                       | 1         | 0.1%    |
| ULi Electronics                              | 1         | 0.1%    |
| Trust                                        | 1         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 1         | 0.1%    |
| Native Instruments                           | 1         | 0.1%    |
| M-Audio                                      | 1         | 0.1%    |
| Lenovo                                       | 1         | 0.1%    |
| Kingston Technology                          | 1         | 0.1%    |
| ESS Technology                               | 1         | 0.1%    |
| Creative Technology                          | 1         | 0.1%    |
| AudioQuest                                   | 1         | 0.1%    |
| Audient                                      | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 87        | 7.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 64        | 5.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 57        | 4.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 44        | 3.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 43        | 3.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 39        | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 38        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 38        | 3.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 36        | 3.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 34        | 2.94%   |
| AMD FCH Azalia Controller                                                                         | 34        | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 34        | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 2.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 30        | 2.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 30        | 2.59%   |
| Intel 8 Series HD Audio Controller                                                                | 30        | 2.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 25        | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 2.07%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 1.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 22        | 1.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 18        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 1.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 1.3%    |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 1.21%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 1.12%   |
| Intel Jasper Lake HD Audio                                                                        | 12        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 0.69%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 7         | 0.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 0.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 247       | 19.06%  |
| Unknown                      | 198       | 15.28%  |
| Kingston                     | 167       | 12.89%  |
| Crucial                      | 135       | 10.42%  |
| SK hynix                     | 129       | 9.95%   |
| Micron Technology            | 99        | 7.64%   |
| G.Skill                      | 65        | 5.02%   |
| Corsair                      | 46        | 3.55%   |
| Unknown (ABCD)               | 32        | 2.47%   |
| Transcend                    | 24        | 1.85%   |
| Unknown                      | 24        | 1.85%   |
| A-DATA Technology            | 19        | 1.47%   |
| ATP                          | 17        | 1.31%   |
| Nanya Technology             | 14        | 1.08%   |
| Ramaxel Technology           | 13        | 1%      |
| Hewlett-Packard              | 9         | 0.69%   |
| Apacer                       | 7         | 0.54%   |
| Toshiba                      | 6         | 0.46%   |
| Elpida                       | 6         | 0.46%   |
| Patriot                      | 3         | 0.23%   |
| Kimtigo                      | 3         | 0.23%   |
| Innodisk                     | 3         | 0.23%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 2         | 0.15%   |
| Tigo                         | 2         | 0.15%   |
| Teikon                       | 2         | 0.15%   |
| Shenzhen Jinge Information   | 2         | 0.15%   |
| PNY                          | 2         | 0.15%   |
| HPE                          | 2         | 0.15%   |
| Avant                        | 2         | 0.15%   |
| 019400B300CE                 | 2         | 0.15%   |
| Unknown (7F7F7F94FFFFFFFF)   | 1         | 0.08%   |
| Unknown (0x0C26)             | 1         | 0.08%   |
| Unknown (00000000FFFF)       | 1         | 0.08%   |
| Team                         | 1         | 0.08%   |
| TakeMS                       | 1         | 0.08%   |
| Super Talent                 | 1         | 0.08%   |
| SK_Hynix                     | 1         | 0.08%   |
| Qimonda                      | 1         | 0.08%   |
| Kingmax                      | 1         | 0.08%   |
| Hyundai lnc                  | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 32        | 2.35%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 32        | 2.35%   |
| Unknown                                                           | 24        | 1.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 10        | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 9         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 9         | 0.66%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s                | 9         | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 8         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 8         | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 8         | 0.59%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 8         | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 7         | 0.51%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 7         | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 7         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 7         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s             | 7         | 0.51%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 7         | 0.51%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s              | 7         | 0.51%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s             | 7         | 0.51%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s             | 7         | 0.51%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s             | 7         | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 6         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 6         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                        | 6         | 0.44%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 6         | 0.44%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s              | 6         | 0.44%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 6         | 0.44%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s             | 6         | 0.44%   |
| ATP RAM AW12P6438BLK0S 4GB DIMM DDR3 1600MT/s                     | 6         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                          | 5         | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 5         | 0.37%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 5         | 0.37%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s             | 5         | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 5         | 0.37%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s             | 5         | 0.37%   |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.37%   |
| Unknown RAM X4C08QD8BNTDSE-7-TO 8GB DIMM DDR4 2667MT/s            | 4         | 0.29%   |
| Unknown RAM Module 4GB DIMM SDRAM                                 | 4         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                        | 4         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 4         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 572       | 48.35%  |
| DDR4    | 442       | 37.36%  |
| DDR2    | 65        | 5.49%   |
| LPDDR4  | 44        | 3.72%   |
| Unknown | 26        | 2.2%    |
| SDRAM   | 18        | 1.52%   |
| DDR     | 8         | 0.68%   |
| LPDDR3  | 6         | 0.51%   |
| RAM     | 1         | 0.08%   |
| DRAM    | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 588       | 49.96%  |
| SODIMM       | 563       | 47.83%  |
| Row Of Chips | 19        | 1.61%   |
| Chip         | 3         | 0.25%   |
| Unknown      | 3         | 0.25%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 440       | 35.48%  |
| 4096  | 405       | 32.66%  |
| 16384 | 177       | 14.27%  |
| 2048  | 164       | 13.23%  |
| 1024  | 28        | 2.26%   |
| 32768 | 19        | 1.53%   |
| 512   | 4         | 0.32%   |
| 256   | 2         | 0.16%   |
| 65536 | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 349       | 28.17%  |
| 2400    | 179       | 14.45%  |
| 1333    | 177       | 14.29%  |
| 2667    | 123       | 9.93%   |
| 3200    | 86        | 6.94%   |
| 2133    | 68        | 5.49%   |
| 667     | 48        | 3.87%   |
| 800     | 44        | 3.55%   |
| Unknown | 27        | 2.18%   |
| 2666    | 21        | 1.69%   |
| 1867    | 20        | 1.61%   |
| 1066    | 20        | 1.61%   |
| 1334    | 17        | 1.37%   |
| 1067    | 14        | 1.13%   |
| 1866    | 11        | 0.89%   |
| 2933    | 10        | 0.81%   |
| 3000    | 8         | 0.65%   |
| 3600    | 4         | 0.32%   |
| 533     | 4         | 0.32%   |
| 65535   | 1         | 0.08%   |
| 4267    | 1         | 0.08%   |
| 3534    | 1         | 0.08%   |
| 2600    | 1         | 0.08%   |
| 1419    | 1         | 0.08%   |
| 1033    | 1         | 0.08%   |
| 975     | 1         | 0.08%   |
| 400     | 1         | 0.08%   |
| 333     | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 42.86%  |
| Ricoh               | 1         | 14.29%  |
| QinHeng Electronics | 1         | 14.29%  |
| Prolific Technology | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother MFC-7360N             | 2         | 28.57%  |
| Ricoh SP 112                  | 1         | 14.29%  |
| QinHeng CH340S                | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| HP HP LaserJet P2035 HP Print | 1         | 14.29%  |
| Brother HL-L2310D series      | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 66.67%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 46        | 31.94%  |
| Acer                                   | 15        | 10.42%  |
| Microdia                               | 10        | 6.94%   |
| Suyin                                  | 9         | 6.25%   |
| Realtek Semiconductor                  | 9         | 6.25%   |
| IMC Networks                           | 9         | 6.25%   |
| Lite-On Technology                     | 7         | 4.86%   |
| Sunplus Innovation Technology          | 6         | 4.17%   |
| Logitech                               | 6         | 4.17%   |
| Lenovo                                 | 4         | 2.78%   |
| Apple                                  | 4         | 2.78%   |
| Alcor Micro                            | 4         | 2.78%   |
| Syntek                                 | 2         | 1.39%   |
| ARC International                      | 2         | 1.39%   |
| Z-Star Microelectronics                | 1         | 0.69%   |
| Trust                                  | 1         | 0.69%   |
| Tripath Technology                     | 1         | 0.69%   |
| Silicon Motion                         | 1         | 0.69%   |
| Ricoh                                  | 1         | 0.69%   |
| Quanta                                 | 1         | 0.69%   |
| Pixart Imaging                         | 1         | 0.69%   |
| Luxvisions Innotech Limited            | 1         | 0.69%   |
| Intel                                  | 1         | 0.69%   |
| Cubeternet                             | 1         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 22        | 15.17%  |
| Acer Integrated Camera                   | 8         | 5.52%   |
| IMC Networks Integrated Camera           | 5         | 3.45%   |
| Microdia Integrated Webcam               | 4         | 2.76%   |
| Lite-On Integrated Camera                | 4         | 2.76%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 4         | 2.76%   |
| Chicony HD Webcam                        | 4         | 2.76%   |
| Chicony FJ Camera                        | 4         | 2.76%   |
| Suyin RGBIR Camera                       | 3         | 2.07%   |
| Realtek Realtek USB2.0 PC Camera         | 3         | 2.07%   |
| Realtek Integrated_Webcam_HD             | 3         | 2.07%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.38%   |
| Logitech Webcam C270                     | 2         | 1.38%   |
| Logitech C920 HD Pro Webcam              | 2         | 1.38%   |
| Lite-On Realtek PC Camera                | 2         | 1.38%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 1.38%   |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 1.38%   |
| Chicony HP HD Webcam [Fixed]             | 2         | 1.38%   |
| Chicony HD WebCam (Acer)                 | 2         | 1.38%   |
| Chicony Chicony USB2.0 Camera            | 2         | 1.38%   |
| ARC International Camera                 | 2         | 1.38%   |
| Apple FaceTime HD Camera (Built-in)      | 2         | 1.38%   |
| Alcor Micro USB 2.0 Web Camera           | 2         | 1.38%   |
| Acer SunplusIT Integrated Camera         | 2         | 1.38%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.69%   |
| Trust Trust USB Camera                   | 1         | 0.69%   |
| Tripath PC Camera                        | 1         | 0.69%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.69%   |
| Syntek EasyCamera                        | 1         | 0.69%   |
| Suyin Sony Visual Communication Camera   | 1         | 0.69%   |
| Suyin Integrated Webcam                  | 1         | 0.69%   |
| Suyin HP Webcam-101                      | 1         | 0.69%   |
| Suyin HP Integrated Webcam               | 1         | 0.69%   |
| Suyin Asus Integrated Webcam             | 1         | 0.69%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.69%   |
| Sunplus Integrated_Webcam_FHD            | 1         | 0.69%   |
| Sunplus Integrated Camera                | 1         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]             | 1         | 0.69%   |
| Sunplus Asus Webcam                      | 1         | 0.69%   |
| Silicon Motion WebCam SCB-0385N          | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 36.36%  |
| Synaptics                  | 10        | 18.18%  |
| Upek                       | 9         | 16.36%  |
| AuthenTec                  | 5         | 9.09%   |
| LighTuning Technology      | 3         | 5.45%   |
| Broadcom                   | 3         | 5.45%   |
| STMicroelectronics         | 2         | 3.64%   |
| Shenzhen Goodix Technology | 2         | 3.64%   |
| Next Biometrics            | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 8         | 14.55%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 7         | 12.73%  |
| Validity Sensors Synaptics WBDI                                              | 6         | 10.91%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 4         | 7.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.45%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 3.64%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 3.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 3.64%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 3.64%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 3.64%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 3.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 3.64%   |
| Unknown                                                                      | 2         | 3.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.82%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.82%   |
| Synaptics product 0x00be                                                     | 1         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.82%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 1.82%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 1.82%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 1.82%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.82%   |
| AuthenTec AES1600                                                            | 1         | 1.82%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 506       | 37.48%  |
| 1     | 486       | 36%     |
| 2     | 200       | 14.81%  |
| 3     | 97        | 7.19%   |
| 4     | 45        | 3.33%   |
| 5     | 14        | 1.04%   |
| 7     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 718       | 59.39%  |
| Net/wireless             | 120       | 9.93%   |
| Bluetooth                | 115       | 9.51%   |
| Card reader              | 98        | 8.11%   |
| Fingerprint reader       | 46        | 3.8%    |
| Firewire controller      | 34        | 2.81%   |
| Sound                    | 22        | 1.82%   |
| Net/ethernet             | 18        | 1.49%   |
| Network                  | 13        | 1.08%   |
| Graphics card            | 13        | 1.08%   |
| Modem                    | 4         | 0.33%   |
| Storage/ide              | 2         | 0.17%   |
| Storage                  | 2         | 0.17%   |
| Storage/raid             | 1         | 0.08%   |
| Storage/nvme             | 1         | 0.08%   |
| Storage/ata              | 1         | 0.08%   |
| Dvb card                 | 1         | 0.08%   |

