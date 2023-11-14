BSD - Tested Hardware & Statistics
----------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

OS-specific reports: [FreeBSD](/Dist/FreeBSD), [GhostBSD](/Dist/GhostBSD), [helloSystem](/Dist/helloSystem), [NetBSD](/Dist/NetBSD), [NomadBSD](/Dist/NomadBSD), [OpenBSD](/Dist/OpenBSD), [OPNsense](/Dist/OPNsense), [pfSense](/Dist/pfSense), [TrueNAS](/Dist/TrueNAS).

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/bsdhw/TestDays_VE)

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

Total: 19383

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Cisco         | ASA5525 A0                  | Desktop     | [f6eb14f059](https://bsd-hardware.info/?probe=f6eb14f059) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b1079a297](https://bsd-hardware.info/?probe=8b1079a297) | Nov 06, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [4c874fa8af](https://bsd-hardware.info/?probe=4c874fa8af) | Nov 06, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [3ca7f9b6d1](https://bsd-hardware.info/?probe=3ca7f9b6d1) | Nov 06, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [9d467272c3](https://bsd-hardware.info/?probe=9d467272c3) | Nov 06, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [9e054bbcb2](https://bsd-hardware.info/?probe=9e054bbcb2) | Nov 06, 2023 |
| Dell          | 0M788G A07                  | Server      | [a404997d9d](https://bsd-hardware.info/?probe=a404997d9d) | Nov 06, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [7ee545bad3](https://bsd-hardware.info/?probe=7ee545bad3) | Nov 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [b4c8864cef](https://bsd-hardware.info/?probe=b4c8864cef) | Nov 06, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [456fe0a275](https://bsd-hardware.info/?probe=456fe0a275) | Nov 06, 2023 |
| HP            | 3031h                       | Desktop     | [a38d555974](https://bsd-hardware.info/?probe=a38d555974) | Nov 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [a01a7d9576](https://bsd-hardware.info/?probe=a01a7d9576) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [70e36de90e](https://bsd-hardware.info/?probe=70e36de90e) | Nov 05, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [4fe0f6ef5e](https://bsd-hardware.info/?probe=4fe0f6ef5e) | Nov 05, 2023 |
| BESSTAR Te... | VB9                         | All in one  | [e750d16fb3](https://bsd-hardware.info/?probe=e750d16fb3) | Nov 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [a217880b63](https://bsd-hardware.info/?probe=a217880b63) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [456d5ad8bf](https://bsd-hardware.info/?probe=456d5ad8bf) | Nov 05, 2023 |
| TYAN Compu... | S5517                       | Desktop     | [5545281cd4](https://bsd-hardware.info/?probe=5545281cd4) | Nov 05, 2023 |
| Shuttle       | FS61                        | Desktop     | [1ed38ceb8c](https://bsd-hardware.info/?probe=1ed38ceb8c) | Nov 05, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [bdc4fdaf9c](https://bsd-hardware.info/?probe=bdc4fdaf9c) | Nov 05, 2023 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [9de790eac0](https://bsd-hardware.info/?probe=9de790eac0) | Nov 05, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Dell          | 0MD99X A12                  | Server      | [c137d2d6da](https://bsd-hardware.info/?probe=c137d2d6da) | Nov 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [c69e655a86](https://bsd-hardware.info/?probe=c69e655a86) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [97f4527aab](https://bsd-hardware.info/?probe=97f4527aab) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a820d6364](https://bsd-hardware.info/?probe=1a820d6364) | Nov 05, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [ab650cfab8](https://bsd-hardware.info/?probe=ab650cfab8) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a768a9f63](https://bsd-hardware.info/?probe=2a768a9f63) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [5d0e537b3e](https://bsd-hardware.info/?probe=5d0e537b3e) | Nov 05, 2023 |
| HP            | ProLiant ML10               | Desktop     | [43badefe76](https://bsd-hardware.info/?probe=43badefe76) | Nov 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [ef59e0f80d](https://bsd-hardware.info/?probe=ef59e0f80d) | Nov 05, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [7653a1705b](https://bsd-hardware.info/?probe=7653a1705b) | Nov 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [ea78913e4c](https://bsd-hardware.info/?probe=ea78913e4c) | Nov 05, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e3852e0a81](https://bsd-hardware.info/?probe=e3852e0a81) | Nov 05, 2023 |
| HP            | 83EE                        | Desktop     | [1ab86be61a](https://bsd-hardware.info/?probe=1ab86be61a) | Nov 05, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [cc58b2f58f](https://bsd-hardware.info/?probe=cc58b2f58f) | Nov 05, 2023 |
| HP            | 213D A01                    | Desktop     | [e7de264f61](https://bsd-hardware.info/?probe=e7de264f61) | Nov 05, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [d95762a0c0](https://bsd-hardware.info/?probe=d95762a0c0) | Nov 04, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [38b5f3b9ad](https://bsd-hardware.info/?probe=38b5f3b9ad) | Nov 04, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a8aad4a386](https://bsd-hardware.info/?probe=a8aad4a386) | Nov 04, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [ccb4fc0598](https://bsd-hardware.info/?probe=ccb4fc0598) | Nov 04, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [86aa07c0ae](https://bsd-hardware.info/?probe=86aa07c0ae) | Nov 04, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| Supermicro    | X10SLM+-LN4F                | Server      | [ed0fb62285](https://bsd-hardware.info/?probe=ed0fb62285) | Nov 04, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [d3e438ea78](https://bsd-hardware.info/?probe=d3e438ea78) | Nov 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [0b678c5e33](https://bsd-hardware.info/?probe=0b678c5e33) | Nov 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [90a26f497a](https://bsd-hardware.info/?probe=90a26f497a) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| LG Electro... | 16UD70R-G.AX59B             | Notebook    | [a7df4f645f](https://bsd-hardware.info/?probe=a7df4f645f) | Nov 04, 2023 |
| HP            | 18E4                        | Desktop     | [479b255034](https://bsd-hardware.info/?probe=479b255034) | Nov 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [25d85a53af](https://bsd-hardware.info/?probe=25d85a53af) | Nov 03, 2023 |
| PC Engines    | apu1                        | Desktop     | [3b8272286a](https://bsd-hardware.info/?probe=3b8272286a) | Nov 03, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [368366454f](https://bsd-hardware.info/?probe=368366454f) | Nov 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [790368b718](https://bsd-hardware.info/?probe=790368b718) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [f6a8d5dbad](https://bsd-hardware.info/?probe=f6a8d5dbad) | Nov 03, 2023 |
| Dell          | 0Y2V0C A03                  | Desktop     | [5c7de92bb3](https://bsd-hardware.info/?probe=5c7de92bb3) | Nov 03, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [e6927b5eb8](https://bsd-hardware.info/?probe=e6927b5eb8) | Nov 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [13eb07060d](https://bsd-hardware.info/?probe=13eb07060d) | Nov 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [c877a467bb](https://bsd-hardware.info/?probe=c877a467bb) | Nov 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [b85acbe43d](https://bsd-hardware.info/?probe=b85acbe43d) | Nov 03, 2023 |
| Protectli     | FW6                         | Desktop     | [2dc16f3849](https://bsd-hardware.info/?probe=2dc16f3849) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [db0f05f919](https://bsd-hardware.info/?probe=db0f05f919) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [b729c4137a](https://bsd-hardware.info/?probe=b729c4137a) | Nov 03, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [c639de5323](https://bsd-hardware.info/?probe=c639de5323) | Nov 03, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [8473035148](https://bsd-hardware.info/?probe=8473035148) | Nov 03, 2023 |
| HP            | 213D A01                    | Desktop     | [da7d91889e](https://bsd-hardware.info/?probe=da7d91889e) | Nov 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [018805dc37](https://bsd-hardware.info/?probe=018805dc37) | Nov 03, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [1859b56be4](https://bsd-hardware.info/?probe=1859b56be4) | Nov 02, 2023 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [d4298a293f](https://bsd-hardware.info/?probe=d4298a293f) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b038d8a95d](https://bsd-hardware.info/?probe=b038d8a95d) | Nov 02, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [538444f1d2](https://bsd-hardware.info/?probe=538444f1d2) | Nov 02, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [d52347dd3d](https://bsd-hardware.info/?probe=d52347dd3d) | Nov 02, 2023 |
| Lenovo        | 312D SDK0L22692 WIN 3306... | Mini pc     | [c958c2b087](https://bsd-hardware.info/?probe=c958c2b087) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [40c18e28da](https://bsd-hardware.info/?probe=40c18e28da) | Nov 02, 2023 |
| IBM           | FWA-3211 A102               | Server      | [8c4e5effec](https://bsd-hardware.info/?probe=8c4e5effec) | Nov 02, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [4fd9e1d707](https://bsd-hardware.info/?probe=4fd9e1d707) | Nov 02, 2023 |
| HP            | ProLiant DL320e Gen8        | Server      | [5494a05301](https://bsd-hardware.info/?probe=5494a05301) | Nov 02, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [59372d06e0](https://bsd-hardware.info/?probe=59372d06e0) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [dd3612a38f](https://bsd-hardware.info/?probe=dd3612a38f) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [11b5e187fc](https://bsd-hardware.info/?probe=11b5e187fc) | Nov 02, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e977a38199](https://bsd-hardware.info/?probe=e977a38199) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [691338cb44](https://bsd-hardware.info/?probe=691338cb44) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [c6610a58ac](https://bsd-hardware.info/?probe=c6610a58ac) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [743d5aec59](https://bsd-hardware.info/?probe=743d5aec59) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [a539a38ec1](https://bsd-hardware.info/?probe=a539a38ec1) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [f1e1a3e8c8](https://bsd-hardware.info/?probe=f1e1a3e8c8) | Nov 02, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ff78edaee6](https://bsd-hardware.info/?probe=ff78edaee6) | Nov 02, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [a4175476a0](https://bsd-hardware.info/?probe=a4175476a0) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [224cc728f5](https://bsd-hardware.info/?probe=224cc728f5) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [a5bf30aeac](https://bsd-hardware.info/?probe=a5bf30aeac) | Nov 02, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [f9df1890fa](https://bsd-hardware.info/?probe=f9df1890fa) | Nov 02, 2023 |
| Dell          | 0M788G A07                  | Server      | [3d5a1fc986](https://bsd-hardware.info/?probe=3d5a1fc986) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [83c8ab8d4b](https://bsd-hardware.info/?probe=83c8ab8d4b) | Nov 02, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3e55355c4b](https://bsd-hardware.info/?probe=3e55355c4b) | Nov 02, 2023 |
| Sophos        | SG                          | Firewall    | [24994d8e2f](https://bsd-hardware.info/?probe=24994d8e2f) | Nov 02, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [8d3cf4e648](https://bsd-hardware.info/?probe=8d3cf4e648) | Nov 01, 2023 |
| Dell          | Precision 7720              | Notebook    | [cc321f8dea](https://bsd-hardware.info/?probe=cc321f8dea) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [3499447096](https://bsd-hardware.info/?probe=3499447096) | Nov 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [7077dec0a1](https://bsd-hardware.info/?probe=7077dec0a1) | Nov 01, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [2fcac7d927](https://bsd-hardware.info/?probe=2fcac7d927) | Nov 01, 2023 |
| Shuttle       | NC10U                       | Desktop     | [8a3fd4b3ee](https://bsd-hardware.info/?probe=8a3fd4b3ee) | Nov 01, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [7e2bda9790](https://bsd-hardware.info/?probe=7e2bda9790) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c83541e4d](https://bsd-hardware.info/?probe=4c83541e4d) | Nov 01, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [2fab5b5adf](https://bsd-hardware.info/?probe=2fab5b5adf) | Nov 01, 2023 |
| Protectli     | VP2420                      | Desktop     | [7621eb7370](https://bsd-hardware.info/?probe=7621eb7370) | Nov 01, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8004cade7b](https://bsd-hardware.info/?probe=8004cade7b) | Nov 01, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [270b4170ef](https://bsd-hardware.info/?probe=270b4170ef) | Nov 01, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [03fa12a885](https://bsd-hardware.info/?probe=03fa12a885) | Nov 01, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [ade254cf11](https://bsd-hardware.info/?probe=ade254cf11) | Nov 01, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [7e40f68fc3](https://bsd-hardware.info/?probe=7e40f68fc3) | Nov 01, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [f93d5865b8](https://bsd-hardware.info/?probe=f93d5865b8) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d7f1c60cfb](https://bsd-hardware.info/?probe=d7f1c60cfb) | Nov 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [5b6e9f8808](https://bsd-hardware.info/?probe=5b6e9f8808) | Oct 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a63df656e](https://bsd-hardware.info/?probe=1a63df656e) | Oct 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [fc605c1909](https://bsd-hardware.info/?probe=fc605c1909) | Oct 31, 2023 |
| Unknown       | QGLK03                      | Desktop     | [f51b216549](https://bsd-hardware.info/?probe=f51b216549) | Oct 31, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [db40304707](https://bsd-hardware.info/?probe=db40304707) | Oct 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [87e3260963](https://bsd-hardware.info/?probe=87e3260963) | Oct 31, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [a688954dd5](https://bsd-hardware.info/?probe=a688954dd5) | Oct 31, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [c60aeb219e](https://bsd-hardware.info/?probe=c60aeb219e) | Oct 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [b9d895ba2b](https://bsd-hardware.info/?probe=b9d895ba2b) | Oct 31, 2023 |
| HP            | 8299                        | Desktop     | [e3bdac8945](https://bsd-hardware.info/?probe=e3bdac8945) | Oct 31, 2023 |
| Shuttle       | FS61                        | Desktop     | [24158fbe17](https://bsd-hardware.info/?probe=24158fbe17) | Oct 31, 2023 |
| Shuttle       | FS61                        | Desktop     | [2efb16a5f4](https://bsd-hardware.info/?probe=2efb16a5f4) | Oct 31, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | Notebook    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| CheckPoint    | T-110-00                    | Desktop     | [970671ce27](https://bsd-hardware.info/?probe=970671ce27) | Oct 31, 2023 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [6b2553e06c](https://bsd-hardware.info/?probe=6b2553e06c) | Oct 30, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [41c4097002](https://bsd-hardware.info/?probe=41c4097002) | Oct 30, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ac76a862f8](https://bsd-hardware.info/?probe=ac76a862f8) | Oct 30, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [da2fa90c43](https://bsd-hardware.info/?probe=da2fa90c43) | Oct 30, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cac29f9a35](https://bsd-hardware.info/?probe=cac29f9a35) | Oct 30, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [ebdc124789](https://bsd-hardware.info/?probe=ebdc124789) | Oct 30, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [534dc363f2](https://bsd-hardware.info/?probe=534dc363f2) | Oct 30, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [959b5f0be7](https://bsd-hardware.info/?probe=959b5f0be7) | Oct 30, 2023 |
| Dell          | 0KP561                      | Desktop     | [cd0ae50eb0](https://bsd-hardware.info/?probe=cd0ae50eb0) | Oct 30, 2023 |
| Sophos        | SG                          | Firewall    | [f9c46ab5cb](https://bsd-hardware.info/?probe=f9c46ab5cb) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [10d46f39aa](https://bsd-hardware.info/?probe=10d46f39aa) | Oct 30, 2023 |
| PC Engines    | APU2                        | Desktop     | [78e2f0b5e4](https://bsd-hardware.info/?probe=78e2f0b5e4) | Oct 30, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [7c9445a8f2](https://bsd-hardware.info/?probe=7c9445a8f2) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5995fa3115](https://bsd-hardware.info/?probe=5995fa3115) | Oct 30, 2023 |
| Shuttle       | DS437                       | Notebook    | [45c2e3460c](https://bsd-hardware.info/?probe=45c2e3460c) | Oct 30, 2023 |
| YANYU         | M9F baytrail                | Desktop     | [746772e77b](https://bsd-hardware.info/?probe=746772e77b) | Oct 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [c7e5f79b34](https://bsd-hardware.info/?probe=c7e5f79b34) | Oct 30, 2023 |
| AZW           | EQ                          | Desktop     | [034b060507](https://bsd-hardware.info/?probe=034b060507) | Oct 30, 2023 |
| AAEON         | FWS-2362 V1.0               | Desktop     | [cddea934bd](https://bsd-hardware.info/?probe=cddea934bd) | Oct 30, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [9567268d28](https://bsd-hardware.info/?probe=9567268d28) | Oct 30, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| Dell          | 01PXF9 A00                  | Mini pc     | [c292bb52df](https://bsd-hardware.info/?probe=c292bb52df) | Oct 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [a96d602ef7](https://bsd-hardware.info/?probe=a96d602ef7) | Oct 29, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [ba44d23972](https://bsd-hardware.info/?probe=ba44d23972) | Oct 29, 2023 |
| Yanling       | YL-KBR6L Ver:1.01           | Desktop     | [bdc7be2258](https://bsd-hardware.info/?probe=bdc7be2258) | Oct 29, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [709f8e1566](https://bsd-hardware.info/?probe=709f8e1566) | Oct 29, 2023 |
| Intel         | ChiefRiver D                | Desktop     | [8467546a46](https://bsd-hardware.info/?probe=8467546a46) | Oct 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f6542c47d](https://bsd-hardware.info/?probe=1f6542c47d) | Oct 29, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [bb195148f7](https://bsd-hardware.info/?probe=bb195148f7) | Oct 29, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| ASRock        | G31M-S                      | Desktop     | [d0d58ceb87](https://bsd-hardware.info/?probe=d0d58ceb87) | Oct 29, 2023 |
| Protectli     | VP2410                      | Desktop     | [7fb31eb814](https://bsd-hardware.info/?probe=7fb31eb814) | Oct 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6aee98fb1a](https://bsd-hardware.info/?probe=6aee98fb1a) | Oct 29, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [dcfbd591f5](https://bsd-hardware.info/?probe=dcfbd591f5) | Oct 29, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [e69fadd7a8](https://bsd-hardware.info/?probe=e69fadd7a8) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [873104973c](https://bsd-hardware.info/?probe=873104973c) | Oct 29, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ec852f7037](https://bsd-hardware.info/?probe=ec852f7037) | Oct 29, 2023 |
| JHZD          | BQM6                        | Desktop     | [d54e6cd1fd](https://bsd-hardware.info/?probe=d54e6cd1fd) | Oct 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [b688e6b635](https://bsd-hardware.info/?probe=b688e6b635) | Oct 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c774066857](https://bsd-hardware.info/?probe=c774066857) | Oct 28, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [07f64c00f4](https://bsd-hardware.info/?probe=07f64c00f4) | Oct 28, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [937bf733c5](https://bsd-hardware.info/?probe=937bf733c5) | Oct 28, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [2df22c840a](https://bsd-hardware.info/?probe=2df22c840a) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [fc42f6db17](https://bsd-hardware.info/?probe=fc42f6db17) | Oct 28, 2023 |
| ASUSTek       | MINIPC PN53-G               | Desktop     | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [b60083ef1f](https://bsd-hardware.info/?probe=b60083ef1f) | Oct 28, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ace25d235f](https://bsd-hardware.info/?probe=ace25d235f) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [49d23c8fda](https://bsd-hardware.info/?probe=49d23c8fda) | Oct 28, 2023 |
| ASRock        | N100DC-ITX                  | Desktop     | [888d7c9d18](https://bsd-hardware.info/?probe=888d7c9d18) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [a133633304](https://bsd-hardware.info/?probe=a133633304) | Oct 28, 2023 |
| HP            | 1825                        | Desktop     | [8a0a258efc](https://bsd-hardware.info/?probe=8a0a258efc) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | Notebook    | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [9508bd06f5](https://bsd-hardware.info/?probe=9508bd06f5) | Oct 28, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [ff58ecae1d](https://bsd-hardware.info/?probe=ff58ecae1d) | Oct 28, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [6448ed1b12](https://bsd-hardware.info/?probe=6448ed1b12) | Oct 28, 2023 |
| IGEL Techn... | D220                        | Desktop     | [3478db91ef](https://bsd-hardware.info/?probe=3478db91ef) | Oct 28, 2023 |
| HP            | 2AF7                        | Desktop     | [a45659c9d2](https://bsd-hardware.info/?probe=a45659c9d2) | Oct 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e99a14af3](https://bsd-hardware.info/?probe=3e99a14af3) | Oct 28, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [73160cea1d](https://bsd-hardware.info/?probe=73160cea1d) | Oct 28, 2023 |
| Intel         | NUC11TNBi3 M11908-500       | Mini pc     | [72634e7285](https://bsd-hardware.info/?probe=72634e7285) | Oct 28, 2023 |
| YanRay Tec... | B1904                       | Desktop     | [7d194ae12b](https://bsd-hardware.info/?probe=7d194ae12b) | Oct 28, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c2a5fe4d38](https://bsd-hardware.info/?probe=c2a5fe4d38) | Oct 28, 2023 |
| Dell          | PowerEdge T110 II           | Desktop     | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [a012c0e1c9](https://bsd-hardware.info/?probe=a012c0e1c9) | Oct 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [03ef00fab1](https://bsd-hardware.info/?probe=03ef00fab1) | Oct 27, 2023 |
| Protectli     | FW4B                        | Desktop     | [23c31e7f9f](https://bsd-hardware.info/?probe=23c31e7f9f) | Oct 27, 2023 |
| Intel         | JSL MRD                     | Desktop     | [328c764941](https://bsd-hardware.info/?probe=328c764941) | Oct 27, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [5d64d42233](https://bsd-hardware.info/?probe=5d64d42233) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [7a9e2d88ed](https://bsd-hardware.info/?probe=7a9e2d88ed) | Oct 27, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | Desktop     | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [c3c0c1e21b](https://bsd-hardware.info/?probe=c3c0c1e21b) | Oct 27, 2023 |
| Fujitsu       | D3314-E1 S26361-D3314-E1    | Desktop     | [2cde7906c1](https://bsd-hardware.info/?probe=2cde7906c1) | Oct 27, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [424c33d278](https://bsd-hardware.info/?probe=424c33d278) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [51102e3f0d](https://bsd-hardware.info/?probe=51102e3f0d) | Oct 27, 2023 |
| Fujitsu       | D3314-A1 S26361-D3314-A1    | Desktop     | [d005339b5f](https://bsd-hardware.info/?probe=d005339b5f) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [a88541d6a6](https://bsd-hardware.info/?probe=a88541d6a6) | Oct 27, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [753b30d88b](https://bsd-hardware.info/?probe=753b30d88b) | Oct 27, 2023 |
| Sophos        | UTM                         | Firewall    | [b6232a012b](https://bsd-hardware.info/?probe=b6232a012b) | Oct 27, 2023 |
| Datto         | Unknown                     | Notebook    | [8b59510085](https://bsd-hardware.info/?probe=8b59510085) | Oct 27, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [fe3d35aef8](https://bsd-hardware.info/?probe=fe3d35aef8) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [850878776a](https://bsd-hardware.info/?probe=850878776a) | Oct 27, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f8ae786555](https://bsd-hardware.info/?probe=f8ae786555) | Oct 27, 2023 |
| YANYU         | M9F baytrail                | Desktop     | [f9e833a5f9](https://bsd-hardware.info/?probe=f9e833a5f9) | Oct 27, 2023 |
| HP            | 3397                        | Desktop     | [3dad1378f7](https://bsd-hardware.info/?probe=3dad1378f7) | Oct 27, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [8af7ab0e4d](https://bsd-hardware.info/?probe=8af7ab0e4d) | Oct 27, 2023 |
| Panasonic     | CF-C2CEAZXCM                | Notebook    | [a871fb0596](https://bsd-hardware.info/?probe=a871fb0596) | Oct 27, 2023 |
| PC Engines    | apu4                        | Desktop     | [7bbd252741](https://bsd-hardware.info/?probe=7bbd252741) | Oct 27, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [8a1a0cdc32](https://bsd-hardware.info/?probe=8a1a0cdc32) | Oct 27, 2023 |
| Supermicro    | X10SLM+-LN4F                | Server      | [53651e09ac](https://bsd-hardware.info/?probe=53651e09ac) | Oct 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1157df98bf](https://bsd-hardware.info/?probe=1157df98bf) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [04349022d0](https://bsd-hardware.info/?probe=04349022d0) | Oct 26, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [bc374cdc01](https://bsd-hardware.info/?probe=bc374cdc01) | Oct 26, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [1d3ba21cf9](https://bsd-hardware.info/?probe=1d3ba21cf9) | Oct 26, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [17cdba9414](https://bsd-hardware.info/?probe=17cdba9414) | Oct 26, 2023 |
| Winston Ma... | PICO PC V1.2                | Desktop     | [244102bda8](https://bsd-hardware.info/?probe=244102bda8) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [376ab08c75](https://bsd-hardware.info/?probe=376ab08c75) | Oct 26, 2023 |
| Dell          | 0PRWNC A05                  | Server      | [9b44f96ab2](https://bsd-hardware.info/?probe=9b44f96ab2) | Oct 26, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | Notebook    | [aa85ff898d](https://bsd-hardware.info/?probe=aa85ff898d) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [9b797e809a](https://bsd-hardware.info/?probe=9b797e809a) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [4dd20af1a3](https://bsd-hardware.info/?probe=4dd20af1a3) | Oct 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [fa2f4e1f86](https://bsd-hardware.info/?probe=fa2f4e1f86) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [c66be142de](https://bsd-hardware.info/?probe=c66be142de) | Oct 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1b42e4a912](https://bsd-hardware.info/?probe=1b42e4a912) | Oct 26, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [233d4d3b64](https://bsd-hardware.info/?probe=233d4d3b64) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [400f56d13c](https://bsd-hardware.info/?probe=400f56d13c) | Oct 26, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [3541caeb52](https://bsd-hardware.info/?probe=3541caeb52) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [d78f6f9dd2](https://bsd-hardware.info/?probe=d78f6f9dd2) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b3f2cf24c](https://bsd-hardware.info/?probe=6b3f2cf24c) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [f06cbf02dc](https://bsd-hardware.info/?probe=f06cbf02dc) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [0f9ff1c9ed](https://bsd-hardware.info/?probe=0f9ff1c9ed) | Oct 25, 2023 |
| Dell          | 0DPRKF A06                  | Server      | [2df912148d](https://bsd-hardware.info/?probe=2df912148d) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [8e245ccb85](https://bsd-hardware.info/?probe=8e245ccb85) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [db96ffb93a](https://bsd-hardware.info/?probe=db96ffb93a) | Oct 25, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [980d0881bd](https://bsd-hardware.info/?probe=980d0881bd) | Oct 25, 2023 |
| PC Engines    | APU3                        | Desktop     | [fb68d3fbaf](https://bsd-hardware.info/?probe=fb68d3fbaf) | Oct 25, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [d0ee609c75](https://bsd-hardware.info/?probe=d0ee609c75) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [119cb746c8](https://bsd-hardware.info/?probe=119cb746c8) | Oct 25, 2023 |
| Toshiba       | Unknown                     | Notebook    | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [0d97ba1ab0](https://bsd-hardware.info/?probe=0d97ba1ab0) | Oct 24, 2023 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [dcd8b6e432](https://bsd-hardware.info/?probe=dcd8b6e432) | Oct 24, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [dfc8115b4a](https://bsd-hardware.info/?probe=dfc8115b4a) | Oct 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [66f5010f59](https://bsd-hardware.info/?probe=66f5010f59) | Oct 24, 2023 |
| NEXCOM        | NSA3110 B                   | Desktop     | [84b88fd96d](https://bsd-hardware.info/?probe=84b88fd96d) | Oct 24, 2023 |
| Protectli     | FW6                         | Desktop     | [9ba0e874f4](https://bsd-hardware.info/?probe=9ba0e874f4) | Oct 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [06f91445cb](https://bsd-hardware.info/?probe=06f91445cb) | Oct 24, 2023 |
| Cisco         | ASA5512 A0                  | Desktop     | [176871dd32](https://bsd-hardware.info/?probe=176871dd32) | Oct 24, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e2dad0b43a](https://bsd-hardware.info/?probe=e2dad0b43a) | Oct 24, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [8668f0e8e9](https://bsd-hardware.info/?probe=8668f0e8e9) | Oct 24, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [d9f0644c56](https://bsd-hardware.info/?probe=d9f0644c56) | Oct 24, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dea9eee8a4](https://bsd-hardware.info/?probe=dea9eee8a4) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | Notebook    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [38b1931562](https://bsd-hardware.info/?probe=38b1931562) | Oct 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [b42465c967](https://bsd-hardware.info/?probe=b42465c967) | Oct 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2424acbde7](https://bsd-hardware.info/?probe=2424acbde7) | Oct 23, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [81e77caff8](https://bsd-hardware.info/?probe=81e77caff8) | Oct 23, 2023 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [cca1027ab8](https://bsd-hardware.info/?probe=cca1027ab8) | Oct 23, 2023 |
| MECHREVO      | Unknown                     | Desktop     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |
| Shuttle       | FZ270                       | Desktop     | [1aa4ad0971](https://bsd-hardware.info/?probe=1aa4ad0971) | Oct 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2f3e0182f7](https://bsd-hardware.info/?probe=2f3e0182f7) | Oct 23, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ab44e043d2](https://bsd-hardware.info/?probe=ab44e043d2) | Oct 23, 2023 |
| Supermicro    | X10SLM-F                    | Desktop     | [8e622421c6](https://bsd-hardware.info/?probe=8e622421c6) | Oct 23, 2023 |
| AZW           | EQ                          | Desktop     | [8cb6ac80d2](https://bsd-hardware.info/?probe=8cb6ac80d2) | Oct 23, 2023 |
| HP            | 8103 A01                    | Mini pc     | [d621f08c5a](https://bsd-hardware.info/?probe=d621f08c5a) | Oct 23, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8f62c35aa0](https://bsd-hardware.info/?probe=8f62c35aa0) | Oct 23, 2023 |
| JHZD          | BQM6                        | Desktop     | [26c56ca564](https://bsd-hardware.info/?probe=26c56ca564) | Oct 23, 2023 |
| HP            | 8103 A01                    | Mini pc     | [9740c7419d](https://bsd-hardware.info/?probe=9740c7419d) | Oct 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef592dc6ed](https://bsd-hardware.info/?probe=ef592dc6ed) | Oct 22, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [3192ead8b5](https://bsd-hardware.info/?probe=3192ead8b5) | Oct 22, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| ASRock        | G31M-S                      | Desktop     | [76a3ad20f3](https://bsd-hardware.info/?probe=76a3ad20f3) | Oct 22, 2023 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [52715e6be9](https://bsd-hardware.info/?probe=52715e6be9) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [1f76a6c28c](https://bsd-hardware.info/?probe=1f76a6c28c) | Oct 22, 2023 |
| HP            | 3397                        | Desktop     | [2c004318d4](https://bsd-hardware.info/?probe=2c004318d4) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [6aea1130aa](https://bsd-hardware.info/?probe=6aea1130aa) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [3a4d822cfc](https://bsd-hardware.info/?probe=3a4d822cfc) | Oct 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a40b6fde47](https://bsd-hardware.info/?probe=a40b6fde47) | Oct 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [6569410f91](https://bsd-hardware.info/?probe=6569410f91) | Oct 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [558a8a885e](https://bsd-hardware.info/?probe=558a8a885e) | Oct 22, 2023 |
| Seco          | UDOO x86                    | Notebook    | [260f8194ed](https://bsd-hardware.info/?probe=260f8194ed) | Oct 22, 2023 |
| Sophos        | SG                          | Firewall    | [cb44d7e49b](https://bsd-hardware.info/?probe=cb44d7e49b) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [e12093f6bd](https://bsd-hardware.info/?probe=e12093f6bd) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c9f8e4f16](https://bsd-hardware.info/?probe=8c9f8e4f16) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [135c0112a4](https://bsd-hardware.info/?probe=135c0112a4) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc1a558efe](https://bsd-hardware.info/?probe=cc1a558efe) | Oct 21, 2023 |
| Sophos        | SG                          | Firewall    | [411f124671](https://bsd-hardware.info/?probe=411f124671) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [b1f5e25359](https://bsd-hardware.info/?probe=b1f5e25359) | Oct 21, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [31fff3e92b](https://bsd-hardware.info/?probe=31fff3e92b) | Oct 21, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7148ec01b2](https://bsd-hardware.info/?probe=7148ec01b2) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [629eefe0c2](https://bsd-hardware.info/?probe=629eefe0c2) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [530528316f](https://bsd-hardware.info/?probe=530528316f) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [f15d15cba2](https://bsd-hardware.info/?probe=f15d15cba2) | Oct 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [30726f25a0](https://bsd-hardware.info/?probe=30726f25a0) | Oct 21, 2023 |
| Dell          | 0M788G A07                  | Server      | [702549b133](https://bsd-hardware.info/?probe=702549b133) | Oct 21, 2023 |
| HP            | 8054                        | Desktop     | [71b61dc284](https://bsd-hardware.info/?probe=71b61dc284) | Oct 21, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a35f074d9](https://bsd-hardware.info/?probe=3a35f074d9) | Oct 20, 2023 |
| ASUSTek       | PRIME H470M-PLUS            | Desktop     | [88cdd6135f](https://bsd-hardware.info/?probe=88cdd6135f) | Oct 20, 2023 |
| Supermicro    | X11SBA-LN4FA                | Server      | [682d4aec9e](https://bsd-hardware.info/?probe=682d4aec9e) | Oct 20, 2023 |
| AZW           | EQ                          | Desktop     | [e119f62272](https://bsd-hardware.info/?probe=e119f62272) | Oct 20, 2023 |
| Dell          | Latitude 5490               | Notebook    | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8943e5449f](https://bsd-hardware.info/?probe=8943e5449f) | Oct 20, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b91ffc9125](https://bsd-hardware.info/?probe=b91ffc9125) | Oct 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [48bb0077c3](https://bsd-hardware.info/?probe=48bb0077c3) | Oct 20, 2023 |
| Intel         | S5520UR E22554-752          | Server      | [8e20922890](https://bsd-hardware.info/?probe=8e20922890) | Oct 20, 2023 |
| Lenovo        | ThinkSystem ST50 V2 7D8J... | Desktop     | [b8cb4d78ac](https://bsd-hardware.info/?probe=b8cb4d78ac) | Oct 20, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [d40c67f9ca](https://bsd-hardware.info/?probe=d40c67f9ca) | Oct 20, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [c51a6f8459](https://bsd-hardware.info/?probe=c51a6f8459) | Oct 20, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3f7a4e2865](https://bsd-hardware.info/?probe=3f7a4e2865) | Oct 20, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [7e2e07f641](https://bsd-hardware.info/?probe=7e2e07f641) | Oct 20, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [ef42c969d5](https://bsd-hardware.info/?probe=ef42c969d5) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| Sophos        | SG                          | Firewall    | [7bdc18c407](https://bsd-hardware.info/?probe=7bdc18c407) | Oct 19, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [b09bb5811b](https://bsd-hardware.info/?probe=b09bb5811b) | Oct 19, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [e96fbf80a4](https://bsd-hardware.info/?probe=e96fbf80a4) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a8dd61b29b](https://bsd-hardware.info/?probe=a8dd61b29b) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e85b1bd1ee](https://bsd-hardware.info/?probe=e85b1bd1ee) | Oct 19, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [a8727c3ee3](https://bsd-hardware.info/?probe=a8727c3ee3) | Oct 19, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1cc822b8c1](https://bsd-hardware.info/?probe=1cc822b8c1) | Oct 19, 2023 |
| HP            | 1589                        | Desktop     | [359343104e](https://bsd-hardware.info/?probe=359343104e) | Oct 19, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [3cf75f0ae6](https://bsd-hardware.info/?probe=3cf75f0ae6) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [44c276172a](https://bsd-hardware.info/?probe=44c276172a) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c8dea5d549](https://bsd-hardware.info/?probe=c8dea5d549) | Oct 19, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [bd9d649fb6](https://bsd-hardware.info/?probe=bd9d649fb6) | Oct 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [26d4882a9f](https://bsd-hardware.info/?probe=26d4882a9f) | Oct 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [94f0b39689](https://bsd-hardware.info/?probe=94f0b39689) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [26a1b95e16](https://bsd-hardware.info/?probe=26a1b95e16) | Oct 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [d63aebc59b](https://bsd-hardware.info/?probe=d63aebc59b) | Oct 19, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [12a09a39d5](https://bsd-hardware.info/?probe=12a09a39d5) | Oct 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [363b63c1a1](https://bsd-hardware.info/?probe=363b63c1a1) | Oct 18, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [6f6f1bf009](https://bsd-hardware.info/?probe=6f6f1bf009) | Oct 18, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [d8114642f5](https://bsd-hardware.info/?probe=d8114642f5) | Oct 18, 2023 |
| Sophos        | SG                          | Firewall    | [164161ab82](https://bsd-hardware.info/?probe=164161ab82) | Oct 18, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [1bf1c3b807](https://bsd-hardware.info/?probe=1bf1c3b807) | Oct 18, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [3e57b220ce](https://bsd-hardware.info/?probe=3e57b220ce) | Oct 18, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [ee39a109bc](https://bsd-hardware.info/?probe=ee39a109bc) | Oct 18, 2023 |
| AZW           | EQ                          | Desktop     | [0d647b68a6](https://bsd-hardware.info/?probe=0d647b68a6) | Oct 18, 2023 |
| AZW           | EQ                          | Desktop     | [71f6a16f5a](https://bsd-hardware.info/?probe=71f6a16f5a) | Oct 18, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [4a39ad1a98](https://bsd-hardware.info/?probe=4a39ad1a98) | Oct 18, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [4ef8d71781](https://bsd-hardware.info/?probe=4ef8d71781) | Oct 18, 2023 |
| HP            | 8299                        | Desktop     | [b4ba6a7e52](https://bsd-hardware.info/?probe=b4ba6a7e52) | Oct 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [af12786272](https://bsd-hardware.info/?probe=af12786272) | Oct 18, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Intel         | H81U                        | Notebook    | [9ed05368b5](https://bsd-hardware.info/?probe=9ed05368b5) | Oct 18, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [d69749afe5](https://bsd-hardware.info/?probe=d69749afe5) | Oct 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [0f18316a17](https://bsd-hardware.info/?probe=0f18316a17) | Oct 18, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [3dffc4d445](https://bsd-hardware.info/?probe=3dffc4d445) | Oct 18, 2023 |
| HP            | 8299                        | Desktop     | [8da92e01e0](https://bsd-hardware.info/?probe=8da92e01e0) | Oct 17, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [410f1d67d8](https://bsd-hardware.info/?probe=410f1d67d8) | Oct 17, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| Dell          | 0N5JWR A00                  | Mini pc     | [234e989b41](https://bsd-hardware.info/?probe=234e989b41) | Oct 17, 2023 |
| Sophos        | SG                          | Firewall    | [2ee4ce0769](https://bsd-hardware.info/?probe=2ee4ce0769) | Oct 17, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [34ae4abdcc](https://bsd-hardware.info/?probe=34ae4abdcc) | Oct 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [ea04f97748](https://bsd-hardware.info/?probe=ea04f97748) | Oct 17, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [f1968d86dc](https://bsd-hardware.info/?probe=f1968d86dc) | Oct 17, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| Unknown       | QDNV01                      | Desktop     | [df90627ba3](https://bsd-hardware.info/?probe=df90627ba3) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [a12be87189](https://bsd-hardware.info/?probe=a12be87189) | Oct 17, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| Dell          | Latitude 3440               | Notebook    | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [0139098ee3](https://bsd-hardware.info/?probe=0139098ee3) | Oct 16, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [eadbd154ab](https://bsd-hardware.info/?probe=eadbd154ab) | Oct 16, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| PC Engines    | APU2                        | Desktop     | [7fb59a92f0](https://bsd-hardware.info/?probe=7fb59a92f0) | Oct 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [8ff0ba4fcb](https://bsd-hardware.info/?probe=8ff0ba4fcb) | Oct 16, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [3129e4f848](https://bsd-hardware.info/?probe=3129e4f848) | Oct 16, 2023 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [bf6492c8f1](https://bsd-hardware.info/?probe=bf6492c8f1) | Oct 15, 2023 |
| ASUSTek       | P5QC                        | Desktop     | [dfb543f496](https://bsd-hardware.info/?probe=dfb543f496) | Oct 15, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [5a15dd2166](https://bsd-hardware.info/?probe=5a15dd2166) | Oct 15, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [31887e656b](https://bsd-hardware.info/?probe=31887e656b) | Oct 15, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [abe8593d6e](https://bsd-hardware.info/?probe=abe8593d6e) | Oct 15, 2023 |
| Sophos        | SG                          | Firewall    | [d825f1a130](https://bsd-hardware.info/?probe=d825f1a130) | Oct 15, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [745b988354](https://bsd-hardware.info/?probe=745b988354) | Oct 15, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [4fc886d589](https://bsd-hardware.info/?probe=4fc886d589) | Oct 15, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [128323ada4](https://bsd-hardware.info/?probe=128323ada4) | Oct 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [bf66ef021e](https://bsd-hardware.info/?probe=bf66ef021e) | Oct 15, 2023 |
| ASUSTek       | X455LD                      | Notebook    | [e61ce1bc9a](https://bsd-hardware.info/?probe=e61ce1bc9a) | Oct 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [af333f2214](https://bsd-hardware.info/?probe=af333f2214) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f38d89e6c0](https://bsd-hardware.info/?probe=f38d89e6c0) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0aa91c2a5c](https://bsd-hardware.info/?probe=0aa91c2a5c) | Oct 15, 2023 |
| Protectli     | VP4650                      | Desktop     | [9c073eb854](https://bsd-hardware.info/?probe=9c073eb854) | Oct 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [eb383d6f22](https://bsd-hardware.info/?probe=eb383d6f22) | Oct 15, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [ca5e8cfb2b](https://bsd-hardware.info/?probe=ca5e8cfb2b) | Oct 15, 2023 |
| Protectli     | VP2410                      | Desktop     | [aaffd45671](https://bsd-hardware.info/?probe=aaffd45671) | Oct 15, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [9d81c598a9](https://bsd-hardware.info/?probe=9d81c598a9) | Oct 15, 2023 |
| HP            | 213D A01                    | Desktop     | [6a023bfe9f](https://bsd-hardware.info/?probe=6a023bfe9f) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Dell          | 0654JC A02                  | Desktop     | [c5a88098ff](https://bsd-hardware.info/?probe=c5a88098ff) | Oct 14, 2023 |
| Supermicro    | A1SRi-2758F                 | Mini pc     | [88725f5ed5](https://bsd-hardware.info/?probe=88725f5ed5) | Oct 14, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [4b685d7ff1](https://bsd-hardware.info/?probe=4b685d7ff1) | Oct 14, 2023 |
| AZW           | EQ                          | Desktop     | [0879dfe1d1](https://bsd-hardware.info/?probe=0879dfe1d1) | Oct 14, 2023 |
| Sophos        | SG                          | Firewall    | [93d1eca671](https://bsd-hardware.info/?probe=93d1eca671) | Oct 14, 2023 |
| Intel         | B75                         | Desktop     | [baead94277](https://bsd-hardware.info/?probe=baead94277) | Oct 14, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [7762558ac6](https://bsd-hardware.info/?probe=7762558ac6) | Oct 14, 2023 |
| Deciso        | Netboard A20                | Notebook    | [879efbe255](https://bsd-hardware.info/?probe=879efbe255) | Oct 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [248c73db22](https://bsd-hardware.info/?probe=248c73db22) | Oct 14, 2023 |
| OEM           | H81 JHS359                  | Desktop     | [9d10d53885](https://bsd-hardware.info/?probe=9d10d53885) | Oct 14, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [95e017977c](https://bsd-hardware.info/?probe=95e017977c) | Oct 14, 2023 |
| Dell          | 0WPMFG A00                  | Desktop     | [9b200a9e60](https://bsd-hardware.info/?probe=9b200a9e60) | Oct 14, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [a8d0be21e1](https://bsd-hardware.info/?probe=a8d0be21e1) | Oct 14, 2023 |
| MSI           | MS-S0891                    | Desktop     | [a46837faa3](https://bsd-hardware.info/?probe=a46837faa3) | Oct 14, 2023 |
| AZW           | EQ                          | Desktop     | [1f76967326](https://bsd-hardware.info/?probe=1f76967326) | Oct 14, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [48e2572a0c](https://bsd-hardware.info/?probe=48e2572a0c) | Oct 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [77a827631b](https://bsd-hardware.info/?probe=77a827631b) | Oct 13, 2023 |
| IceWhale T... | ZMB216-i ZMB                | Desktop     | [10dc3669ad](https://bsd-hardware.info/?probe=10dc3669ad) | Oct 13, 2023 |
| Sophos        | XG                          | Firewall    | [ab8b265b82](https://bsd-hardware.info/?probe=ab8b265b82) | Oct 13, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [7ed49c5f2f](https://bsd-hardware.info/?probe=7ed49c5f2f) | Oct 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| HP            | 3397                        | Desktop     | [30884c4f37](https://bsd-hardware.info/?probe=30884c4f37) | Oct 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [8b0d009cc4](https://bsd-hardware.info/?probe=8b0d009cc4) | Oct 13, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [8ec0d67d48](https://bsd-hardware.info/?probe=8ec0d67d48) | Oct 13, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [95653dd42d](https://bsd-hardware.info/?probe=95653dd42d) | Oct 13, 2023 |
| Protectli     | FW4C                        | Desktop     | [16326174bb](https://bsd-hardware.info/?probe=16326174bb) | Oct 13, 2023 |
| Sophos        | SG                          | Firewall    | [896045150c](https://bsd-hardware.info/?probe=896045150c) | Oct 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [b57183cbb0](https://bsd-hardware.info/?probe=b57183cbb0) | Oct 13, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [65acf27cad](https://bsd-hardware.info/?probe=65acf27cad) | Oct 13, 2023 |
| ASUSTek       | X455LD                      | Notebook    | [b1a7a3f656](https://bsd-hardware.info/?probe=b1a7a3f656) | Oct 13, 2023 |
| Dell          | 08CYF7 A05                  | Server      | [6b8bbc4ad9](https://bsd-hardware.info/?probe=6b8bbc4ad9) | Oct 13, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [30f97615e6](https://bsd-hardware.info/?probe=30f97615e6) | Oct 13, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [fbc9fe11b1](https://bsd-hardware.info/?probe=fbc9fe11b1) | Oct 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [0fd1a7196f](https://bsd-hardware.info/?probe=0fd1a7196f) | Oct 13, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [12cd55971a](https://bsd-hardware.info/?probe=12cd55971a) | Oct 12, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [516eda52f0](https://bsd-hardware.info/?probe=516eda52f0) | Oct 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fbb1d70a63](https://bsd-hardware.info/?probe=fbb1d70a63) | Oct 12, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [916de10c11](https://bsd-hardware.info/?probe=916de10c11) | Oct 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [9145630ed9](https://bsd-hardware.info/?probe=9145630ed9) | Oct 12, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [418d78095d](https://bsd-hardware.info/?probe=418d78095d) | Oct 12, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [f3b384d87a](https://bsd-hardware.info/?probe=f3b384d87a) | Oct 12, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [a7307b8de1](https://bsd-hardware.info/?probe=a7307b8de1) | Oct 12, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Lenovo        | ThinkPad X250 20CM004VFR    | Notebook    | [e4ab2acd8d](https://bsd-hardware.info/?probe=e4ab2acd8d) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [30ec824cf5](https://bsd-hardware.info/?probe=30ec824cf5) | Oct 11, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [6dfadd1ff2](https://bsd-hardware.info/?probe=6dfadd1ff2) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c3132c17b](https://bsd-hardware.info/?probe=4c3132c17b) | Oct 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [3842802079](https://bsd-hardware.info/?probe=3842802079) | Oct 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [814bbea3a1](https://bsd-hardware.info/?probe=814bbea3a1) | Oct 11, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8c8ac1ca05](https://bsd-hardware.info/?probe=8c8ac1ca05) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d5abb3996](https://bsd-hardware.info/?probe=3d5abb3996) | Oct 11, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [054a6c3902](https://bsd-hardware.info/?probe=054a6c3902) | Oct 11, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [cdc40fe6a3](https://bsd-hardware.info/?probe=cdc40fe6a3) | Oct 11, 2023 |
| Dell          | Precision 7550              | Notebook    | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [67379c4768](https://bsd-hardware.info/?probe=67379c4768) | Oct 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5cbdc1c618](https://bsd-hardware.info/?probe=5cbdc1c618) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b315e9b1e](https://bsd-hardware.info/?probe=8b315e9b1e) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4faecc5e8](https://bsd-hardware.info/?probe=e4faecc5e8) | Oct 10, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [d5676f7895](https://bsd-hardware.info/?probe=d5676f7895) | Oct 10, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [b9c11f29c9](https://bsd-hardware.info/?probe=b9c11f29c9) | Oct 10, 2023 |
| ASUSTek       | EX-B760M-V5 D4              | Desktop     | [e8c7d65a36](https://bsd-hardware.info/?probe=e8c7d65a36) | Oct 10, 2023 |
| TONK          | TN2800                      | Desktop     | [a47aba3406](https://bsd-hardware.info/?probe=a47aba3406) | Oct 10, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [c823cbad48](https://bsd-hardware.info/?probe=c823cbad48) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [5031b0a5a7](https://bsd-hardware.info/?probe=5031b0a5a7) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [1bb43f3258](https://bsd-hardware.info/?probe=1bb43f3258) | Oct 10, 2023 |
| iEi           | B509 V1.00                  | Desktop     | [7535a7bf4d](https://bsd-hardware.info/?probe=7535a7bf4d) | Oct 10, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [12b5a57360](https://bsd-hardware.info/?probe=12b5a57360) | Oct 10, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [cf15e11738](https://bsd-hardware.info/?probe=cf15e11738) | Oct 10, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | Desktop     | [da1e562510](https://bsd-hardware.info/?probe=da1e562510) | Oct 10, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [ddffd0a126](https://bsd-hardware.info/?probe=ddffd0a126) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [f55b11d45d](https://bsd-hardware.info/?probe=f55b11d45d) | Oct 10, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3aa38e5b1f](https://bsd-hardware.info/?probe=3aa38e5b1f) | Oct 10, 2023 |
| AZW           | EQ                          | Desktop     | [ea7e5029de](https://bsd-hardware.info/?probe=ea7e5029de) | Oct 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | 03X6X0 A00                  | Server      | [26e755b8be](https://bsd-hardware.info/?probe=26e755b8be) | Oct 10, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b2a20ba176](https://bsd-hardware.info/?probe=b2a20ba176) | Oct 10, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | Desktop     | [d7cf15da0c](https://bsd-hardware.info/?probe=d7cf15da0c) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [89d680cba1](https://bsd-hardware.info/?probe=89d680cba1) | Oct 09, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [9e99e33fa3](https://bsd-hardware.info/?probe=9e99e33fa3) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [648234b9c2](https://bsd-hardware.info/?probe=648234b9c2) | Oct 09, 2023 |
| Dell          | Latitude D830               | Notebook    | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| Unknown       | QD-CMU01                    | Desktop     | [8637821e57](https://bsd-hardware.info/?probe=8637821e57) | Oct 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c07dd3b911](https://bsd-hardware.info/?probe=c07dd3b911) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [e57d68ebd3](https://bsd-hardware.info/?probe=e57d68ebd3) | Oct 09, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [08dab02121](https://bsd-hardware.info/?probe=08dab02121) | Oct 09, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [e2647b46bf](https://bsd-hardware.info/?probe=e2647b46bf) | Oct 09, 2023 |
| Sophos        | UTM                         | Firewall    | [002d6256fa](https://bsd-hardware.info/?probe=002d6256fa) | Oct 09, 2023 |
| Dell          | 065TRV A04                  | Server      | [2d07fc66b5](https://bsd-hardware.info/?probe=2d07fc66b5) | Oct 09, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [43c1b405d0](https://bsd-hardware.info/?probe=43c1b405d0) | Oct 09, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [93709074ae](https://bsd-hardware.info/?probe=93709074ae) | Oct 09, 2023 |
| HP            | 1497                        | Desktop     | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | Desktop     | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [80e01e48bf](https://bsd-hardware.info/?probe=80e01e48bf) | Oct 09, 2023 |
| Yanling       | YL-KBR6L Ver:1.01           | Desktop     | [53fab8363c](https://bsd-hardware.info/?probe=53fab8363c) | Oct 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [862d0bbe4d](https://bsd-hardware.info/?probe=862d0bbe4d) | Oct 08, 2023 |
| ASRock        | Z690M Phantom Gaming 4      | Desktop     | [20ff855aec](https://bsd-hardware.info/?probe=20ff855aec) | Oct 08, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [02d64d7433](https://bsd-hardware.info/?probe=02d64d7433) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce469807d3](https://bsd-hardware.info/?probe=ce469807d3) | Oct 08, 2023 |
| Sophos        | SG                          | Firewall    | [2e19b2128b](https://bsd-hardware.info/?probe=2e19b2128b) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [57e5ab8786](https://bsd-hardware.info/?probe=57e5ab8786) | Oct 08, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [b192196423](https://bsd-hardware.info/?probe=b192196423) | Oct 08, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [dc147098c6](https://bsd-hardware.info/?probe=dc147098c6) | Oct 08, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [ab5400f952](https://bsd-hardware.info/?probe=ab5400f952) | Oct 08, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [8262e3923f](https://bsd-hardware.info/?probe=8262e3923f) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [a64ed6b5d1](https://bsd-hardware.info/?probe=a64ed6b5d1) | Oct 08, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [d063eeb7d5](https://bsd-hardware.info/?probe=d063eeb7d5) | Oct 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f7ab105e3](https://bsd-hardware.info/?probe=1f7ab105e3) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [bb66634f7c](https://bsd-hardware.info/?probe=bb66634f7c) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [a2a905898b](https://bsd-hardware.info/?probe=a2a905898b) | Oct 08, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [0aac5f52c9](https://bsd-hardware.info/?probe=0aac5f52c9) | Oct 08, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [39894be424](https://bsd-hardware.info/?probe=39894be424) | Oct 07, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [11b0d7b64f](https://bsd-hardware.info/?probe=11b0d7b64f) | Oct 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d7a7e7338f](https://bsd-hardware.info/?probe=d7a7e7338f) | Oct 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [af88ff7c18](https://bsd-hardware.info/?probe=af88ff7c18) | Oct 07, 2023 |
| MSI           | Aspen                       | Desktop     | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [66a1e081e6](https://bsd-hardware.info/?probe=66a1e081e6) | Oct 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e3141878a9](https://bsd-hardware.info/?probe=e3141878a9) | Oct 07, 2023 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [99260d8bdf](https://bsd-hardware.info/?probe=99260d8bdf) | Oct 07, 2023 |
| Dell          | 0N0992 A02                  | Desktop     | [1a0da77587](https://bsd-hardware.info/?probe=1a0da77587) | Oct 07, 2023 |
| GVC           | DR 738                      | Desktop     | [1aa25f04a8](https://bsd-hardware.info/?probe=1aa25f04a8) | Oct 07, 2023 |
| Timi          | A34R                        | Notebook    | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | Notebook    | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [bdf86afe1c](https://bsd-hardware.info/?probe=bdf86afe1c) | Oct 07, 2023 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [f76e1fb940](https://bsd-hardware.info/?probe=f76e1fb940) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [46752213d9](https://bsd-hardware.info/?probe=46752213d9) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [13f17e09d4](https://bsd-hardware.info/?probe=13f17e09d4) | Oct 06, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d236eb8bb](https://bsd-hardware.info/?probe=9d236eb8bb) | Oct 06, 2023 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [30be7bec3f](https://bsd-hardware.info/?probe=30be7bec3f) | Oct 06, 2023 |
| Dell          | 0PXXHP A03                  | Server      | [f3f37dd0e7](https://bsd-hardware.info/?probe=f3f37dd0e7) | Oct 06, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [fb6d008bfc](https://bsd-hardware.info/?probe=fb6d008bfc) | Oct 06, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [91b63fa5c7](https://bsd-hardware.info/?probe=91b63fa5c7) | Oct 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [04dbabbf69](https://bsd-hardware.info/?probe=04dbabbf69) | Oct 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [31c7e1d3f3](https://bsd-hardware.info/?probe=31c7e1d3f3) | Oct 06, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [18bd683b61](https://bsd-hardware.info/?probe=18bd683b61) | Oct 06, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [5076395072](https://bsd-hardware.info/?probe=5076395072) | Oct 06, 2023 |
| Deciso        | Netboard A8                 | Desktop     | [cf3b678212](https://bsd-hardware.info/?probe=cf3b678212) | Oct 06, 2023 |
| HP            | 82B4                        | Desktop     | [daaf49e002](https://bsd-hardware.info/?probe=daaf49e002) | Oct 06, 2023 |
| Dell          | 0N0992 A02                  | Desktop     | [c0dad688e1](https://bsd-hardware.info/?probe=c0dad688e1) | Oct 06, 2023 |
| Intel         | QHSW02                      | Desktop     | [e0d4a273f5](https://bsd-hardware.info/?probe=e0d4a273f5) | Oct 06, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| HP            | 8056                        | Desktop     | [7516a37588](https://bsd-hardware.info/?probe=7516a37588) | Oct 06, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [6f742cd646](https://bsd-hardware.info/?probe=6f742cd646) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [287480c8e6](https://bsd-hardware.info/?probe=287480c8e6) | Oct 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c25c930afa](https://bsd-hardware.info/?probe=c25c930afa) | Oct 05, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [2ff1690bcd](https://bsd-hardware.info/?probe=2ff1690bcd) | Oct 05, 2023 |
| Deciso        | Netboard A20                | Notebook    | [c549fc9540](https://bsd-hardware.info/?probe=c549fc9540) | Oct 05, 2023 |
| Dell          | 0XN8Y6 A09                  | Server      | [0aa4133255](https://bsd-hardware.info/?probe=0aa4133255) | Oct 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f63740c0e](https://bsd-hardware.info/?probe=3f63740c0e) | Oct 05, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [a8a2d463fc](https://bsd-hardware.info/?probe=a8a2d463fc) | Oct 05, 2023 |
| Win elemen... | M600                        | Desktop     | [da4e03cd91](https://bsd-hardware.info/?probe=da4e03cd91) | Oct 05, 2023 |
| Win elemen... | M600                        | Desktop     | [27492e0298](https://bsd-hardware.info/?probe=27492e0298) | Oct 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c4dfb2a41b](https://bsd-hardware.info/?probe=c4dfb2a41b) | Oct 04, 2023 |
| Intel         | D54250WYK H13922-303        | Desktop     | [1bca98240a](https://bsd-hardware.info/?probe=1bca98240a) | Oct 04, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [aecfeaa518](https://bsd-hardware.info/?probe=aecfeaa518) | Oct 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [5d66fcb1f8](https://bsd-hardware.info/?probe=5d66fcb1f8) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9190b85f99](https://bsd-hardware.info/?probe=9190b85f99) | Oct 04, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [5b33d7b22e](https://bsd-hardware.info/?probe=5b33d7b22e) | Oct 04, 2023 |
| ASUSTek       | K73E                        | Notebook    | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [c54bad3277](https://bsd-hardware.info/?probe=c54bad3277) | Oct 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [626d74b530](https://bsd-hardware.info/?probe=626d74b530) | Oct 04, 2023 |
| Dell          | 0N051F A01                  | Server      | [6702155f9d](https://bsd-hardware.info/?probe=6702155f9d) | Oct 04, 2023 |
| PC Engines    | apu4                        | Desktop     | [0e813a0050](https://bsd-hardware.info/?probe=0e813a0050) | Oct 04, 2023 |
| Sophos        | SG                          | Firewall    | [c91ad52ddf](https://bsd-hardware.info/?probe=c91ad52ddf) | Oct 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9ad768a37a](https://bsd-hardware.info/?probe=9ad768a37a) | Oct 04, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [245e0595e2](https://bsd-hardware.info/?probe=245e0595e2) | Oct 04, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [17406f5021](https://bsd-hardware.info/?probe=17406f5021) | Oct 04, 2023 |
| Protectli     | FW4C                        | Desktop     | [671429444f](https://bsd-hardware.info/?probe=671429444f) | Oct 04, 2023 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [1792df4520](https://bsd-hardware.info/?probe=1792df4520) | Oct 04, 2023 |
| Lenovo        | ThinkPad X230 2325J67       | Notebook    | [bfbc6beca8](https://bsd-hardware.info/?probe=bfbc6beca8) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [914de9ed88](https://bsd-hardware.info/?probe=914de9ed88) | Oct 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [dfaa515b13](https://bsd-hardware.info/?probe=dfaa515b13) | Oct 04, 2023 |
| MSI           | MS-98G4                     | Desktop     | [fa88c3c925](https://bsd-hardware.info/?probe=fa88c3c925) | Oct 04, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [12b9800a9f](https://bsd-hardware.info/?probe=12b9800a9f) | Oct 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0718d64bf8](https://bsd-hardware.info/?probe=0718d64bf8) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ba9a892240](https://bsd-hardware.info/?probe=ba9a892240) | Oct 04, 2023 |
| ASUSTek       | Pro WS W680-ACE IPMI        | Desktop     | [6a98aea3f9](https://bsd-hardware.info/?probe=6a98aea3f9) | Oct 03, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [4fa9bbbecf](https://bsd-hardware.info/?probe=4fa9bbbecf) | Oct 03, 2023 |
| Dell          | Latitude 5591               | Notebook    | [8f6ca1e82a](https://bsd-hardware.info/?probe=8f6ca1e82a) | Oct 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [febaed1e4e](https://bsd-hardware.info/?probe=febaed1e4e) | Oct 03, 2023 |
| HP            | 1998                        | Desktop     | [66965d8659](https://bsd-hardware.info/?probe=66965d8659) | Oct 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| HP            | 83E2                        | Desktop     | [dbb1010907](https://bsd-hardware.info/?probe=dbb1010907) | Oct 03, 2023 |
| Fujitsu       | D2863 S26361-D2863-A10 W... | Server      | [f2d65698fb](https://bsd-hardware.info/?probe=f2d65698fb) | Oct 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [204667d485](https://bsd-hardware.info/?probe=204667d485) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | Desktop     | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [66c5aee47e](https://bsd-hardware.info/?probe=66c5aee47e) | Oct 03, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [acc8dea1e2](https://bsd-hardware.info/?probe=acc8dea1e2) | Oct 03, 2023 |
| AZW           | EQ                          | Desktop     | [81d0adbf96](https://bsd-hardware.info/?probe=81d0adbf96) | Oct 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [cab6cdb306](https://bsd-hardware.info/?probe=cab6cdb306) | Oct 02, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [5a9de12dfc](https://bsd-hardware.info/?probe=5a9de12dfc) | Oct 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d5d794abdb](https://bsd-hardware.info/?probe=d5d794abdb) | Oct 02, 2023 |
| PC Engines    | apu4                        | Desktop     | [20c432e07b](https://bsd-hardware.info/?probe=20c432e07b) | Oct 02, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [53a70ddb3b](https://bsd-hardware.info/?probe=53a70ddb3b) | Oct 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [002103bb3a](https://bsd-hardware.info/?probe=002103bb3a) | Oct 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9748abc90d](https://bsd-hardware.info/?probe=9748abc90d) | Oct 02, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [de28aee738](https://bsd-hardware.info/?probe=de28aee738) | Oct 02, 2023 |
| Platform      | ARB938                      | Notebook    | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [f2a8c7fa67](https://bsd-hardware.info/?probe=f2a8c7fa67) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [5c6c241347](https://bsd-hardware.info/?probe=5c6c241347) | Oct 02, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [39fbf2c8dc](https://bsd-hardware.info/?probe=39fbf2c8dc) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [070c5dab4f](https://bsd-hardware.info/?probe=070c5dab4f) | Oct 02, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [6b58792f5e](https://bsd-hardware.info/?probe=6b58792f5e) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [6427b9defc](https://bsd-hardware.info/?probe=6427b9defc) | Oct 02, 2023 |
| Protectli     | VP2420                      | Desktop     | [c77ef1792c](https://bsd-hardware.info/?probe=c77ef1792c) | Oct 02, 2023 |
| Intel         | NUC8BEB J72692-307          | Mini pc     | [e43673f564](https://bsd-hardware.info/?probe=e43673f564) | Oct 01, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN         | Mini pc     | [a7b161ff5e](https://bsd-hardware.info/?probe=a7b161ff5e) | Oct 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e7677e76](https://bsd-hardware.info/?probe=f5e7677e76) | Oct 01, 2023 |
| PC Engines    | APU2                        | Desktop     | [064fd13617](https://bsd-hardware.info/?probe=064fd13617) | Oct 01, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [b957ce880e](https://bsd-hardware.info/?probe=b957ce880e) | Oct 01, 2023 |
| Protectli     | VP46xx                      | Desktop     | [4985863bd8](https://bsd-hardware.info/?probe=4985863bd8) | Oct 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [05dc7174b1](https://bsd-hardware.info/?probe=05dc7174b1) | Oct 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [723569d88a](https://bsd-hardware.info/?probe=723569d88a) | Oct 01, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [14ead4227b](https://bsd-hardware.info/?probe=14ead4227b) | Oct 01, 2023 |
| Sophos        | SG                          | Firewall    | [40e14eca4b](https://bsd-hardware.info/?probe=40e14eca4b) | Oct 01, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [5524017014](https://bsd-hardware.info/?probe=5524017014) | Oct 01, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [9b9f826560](https://bsd-hardware.info/?probe=9b9f826560) | Oct 01, 2023 |
| Sophos        | SG                          | Firewall    | [13acf2a462](https://bsd-hardware.info/?probe=13acf2a462) | Oct 01, 2023 |
| Google        | Auron_Paine                 | Notebook    | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [f97e242e6b](https://bsd-hardware.info/?probe=f97e242e6b) | Oct 01, 2023 |
| Dell          | 0GU083 A00                  | Desktop     | [1286478dc2](https://bsd-hardware.info/?probe=1286478dc2) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [b5caabfd31](https://bsd-hardware.info/?probe=b5caabfd31) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [7a1378a001](https://bsd-hardware.info/?probe=7a1378a001) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [93cc6a1173](https://bsd-hardware.info/?probe=93cc6a1173) | Oct 01, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [906fd7e198](https://bsd-hardware.info/?probe=906fd7e198) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [50418139b2](https://bsd-hardware.info/?probe=50418139b2) | Sep 30, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [c6903de57a](https://bsd-hardware.info/?probe=c6903de57a) | Sep 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [a32967cbc5](https://bsd-hardware.info/?probe=a32967cbc5) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [716f9b28ab](https://bsd-hardware.info/?probe=716f9b28ab) | Sep 30, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [604bce28c1](https://bsd-hardware.info/?probe=604bce28c1) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [c46ccbd5b9](https://bsd-hardware.info/?probe=c46ccbd5b9) | Sep 30, 2023 |
| ASUSTek       | P10S-C Series               | Desktop     | [cc0a5bb631](https://bsd-hardware.info/?probe=cc0a5bb631) | Sep 30, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [8809e169a1](https://bsd-hardware.info/?probe=8809e169a1) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [273b148522](https://bsd-hardware.info/?probe=273b148522) | Sep 30, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [dfb45f6202](https://bsd-hardware.info/?probe=dfb45f6202) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [1429a7de9a](https://bsd-hardware.info/?probe=1429a7de9a) | Sep 30, 2023 |
| HP            | 83EE                        | Desktop     | [88d80d215a](https://bsd-hardware.info/?probe=88d80d215a) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [20fb7f1ba8](https://bsd-hardware.info/?probe=20fb7f1ba8) | Sep 30, 2023 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [9ceae969b0](https://bsd-hardware.info/?probe=9ceae969b0) | Sep 30, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [fc2ba7c8d8](https://bsd-hardware.info/?probe=fc2ba7c8d8) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [abc175c93b](https://bsd-hardware.info/?probe=abc175c93b) | Sep 30, 2023 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [9a73be8c9c](https://bsd-hardware.info/?probe=9a73be8c9c) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [5b7606e786](https://bsd-hardware.info/?probe=5b7606e786) | Sep 30, 2023 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [ea832a672d](https://bsd-hardware.info/?probe=ea832a672d) | Sep 30, 2023 |
| IGEL Techn... | VX900                       | Desktop     | [eb65624dc3](https://bsd-hardware.info/?probe=eb65624dc3) | Sep 29, 2023 |
| Acer          | F672CR R01-B1               | Desktop     | [2008598c7e](https://bsd-hardware.info/?probe=2008598c7e) | Sep 29, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3877143e37](https://bsd-hardware.info/?probe=3877143e37) | Sep 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb21a44f71](https://bsd-hardware.info/?probe=fb21a44f71) | Sep 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [bfe4c8617a](https://bsd-hardware.info/?probe=bfe4c8617a) | Sep 29, 2023 |
| ASUSTek       | P10S-C Series               | Desktop     | [4e7d5e6cf9](https://bsd-hardware.info/?probe=4e7d5e6cf9) | Sep 29, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [c560c88351](https://bsd-hardware.info/?probe=c560c88351) | Sep 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cda7be3da8](https://bsd-hardware.info/?probe=cda7be3da8) | Sep 29, 2023 |
| PC Engines    | APU                         | Desktop     | [ca9bc2faa7](https://bsd-hardware.info/?probe=ca9bc2faa7) | Sep 29, 2023 |
| PC Engines    | APU                         | Desktop     | [067872c1f5](https://bsd-hardware.info/?probe=067872c1f5) | Sep 29, 2023 |
| ASUSTek       | 1005PXD                     | Notebook    | [1b05e8cf1b](https://bsd-hardware.info/?probe=1b05e8cf1b) | Sep 29, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [cc346350f3](https://bsd-hardware.info/?probe=cc346350f3) | Sep 29, 2023 |
| TONK          | TN2800                      | Desktop     | [bce9c62915](https://bsd-hardware.info/?probe=bce9c62915) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b0aca42c84](https://bsd-hardware.info/?probe=b0aca42c84) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [68b8b9f531](https://bsd-hardware.info/?probe=68b8b9f531) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [e732d89b06](https://bsd-hardware.info/?probe=e732d89b06) | Sep 29, 2023 |
| HP            | 1998                        | Desktop     | [0f176c9cc9](https://bsd-hardware.info/?probe=0f176c9cc9) | Sep 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [8816b1ac4a](https://bsd-hardware.info/?probe=8816b1ac4a) | Sep 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [714516a696](https://bsd-hardware.info/?probe=714516a696) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [cac0950717](https://bsd-hardware.info/?probe=cac0950717) | Sep 29, 2023 |
| Lenovo        | ThinkCentre M81 5049D7G     | Desktop     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [3c69dd7003](https://bsd-hardware.info/?probe=3c69dd7003) | Sep 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [6ed3c7314d](https://bsd-hardware.info/?probe=6ed3c7314d) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [f98d4be34d](https://bsd-hardware.info/?probe=f98d4be34d) | Sep 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e587bca33a](https://bsd-hardware.info/?probe=e587bca33a) | Sep 29, 2023 |
| HP            | 82B4                        | Desktop     | [60d259ab3f](https://bsd-hardware.info/?probe=60d259ab3f) | Sep 29, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [29bcb3ca3e](https://bsd-hardware.info/?probe=29bcb3ca3e) | Sep 29, 2023 |
| HP            | 0B54h D                     | Desktop     | [55122a1908](https://bsd-hardware.info/?probe=55122a1908) | Sep 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e82c0f66d](https://bsd-hardware.info/?probe=7e82c0f66d) | Sep 29, 2023 |
| MSI           | MS-98G4                     | Desktop     | [a8ea23c0df](https://bsd-hardware.info/?probe=a8ea23c0df) | Sep 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f50d617197](https://bsd-hardware.info/?probe=f50d617197) | Sep 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [ff0144d21a](https://bsd-hardware.info/?probe=ff0144d21a) | Sep 28, 2023 |
| Intel         | D33217GKE G76540-205        | Desktop     | [faef2ab5c6](https://bsd-hardware.info/?probe=faef2ab5c6) | Sep 28, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Dell          | 08D89F A00                  | Server      | [6a9c0620a0](https://bsd-hardware.info/?probe=6a9c0620a0) | Sep 28, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [eaf7d5bd39](https://bsd-hardware.info/?probe=eaf7d5bd39) | Sep 28, 2023 |
| Dell          | 0J555H A00                  | Server      | [3c395551d4](https://bsd-hardware.info/?probe=3c395551d4) | Sep 28, 2023 |
| HP            | 8054                        | Desktop     | [650aa5ab8f](https://bsd-hardware.info/?probe=650aa5ab8f) | Sep 28, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [c35034519a](https://bsd-hardware.info/?probe=c35034519a) | Sep 28, 2023 |
| Dell          | Latitude 5591               | Notebook    | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [df07570acc](https://bsd-hardware.info/?probe=df07570acc) | Sep 28, 2023 |
| Sophos        | SG                          | Firewall    | [e6a4159f0c](https://bsd-hardware.info/?probe=e6a4159f0c) | Sep 28, 2023 |
| HP            | 83EE                        | Desktop     | [d08ae678b5](https://bsd-hardware.info/?probe=d08ae678b5) | Sep 28, 2023 |
| Biostar       | A55MLC2                     | Desktop     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b698f41785](https://bsd-hardware.info/?probe=b698f41785) | Sep 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [b3f0a784ab](https://bsd-hardware.info/?probe=b3f0a784ab) | Sep 28, 2023 |
| Dell          | 08D89F A00                  | Server      | [de921e42d3](https://bsd-hardware.info/?probe=de921e42d3) | Sep 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0f20928f2d](https://bsd-hardware.info/?probe=0f20928f2d) | Sep 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0f1805a40e](https://bsd-hardware.info/?probe=0f1805a40e) | Sep 27, 2023 |
| AZW           | EQ                          | Desktop     | [bd702ed861](https://bsd-hardware.info/?probe=bd702ed861) | Sep 27, 2023 |
| Dell          | Latitude E6430              | Notebook    | [bec165c243](https://bsd-hardware.info/?probe=bec165c243) | Sep 27, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [a0d9fae143](https://bsd-hardware.info/?probe=a0d9fae143) | Sep 27, 2023 |
| PC Engines    | APU2                        | Desktop     | [252385ae71](https://bsd-hardware.info/?probe=252385ae71) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d86474bd03](https://bsd-hardware.info/?probe=d86474bd03) | Sep 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [8d5549809c](https://bsd-hardware.info/?probe=8d5549809c) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [57577a5f14](https://bsd-hardware.info/?probe=57577a5f14) | Sep 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [8a4596eefa](https://bsd-hardware.info/?probe=8a4596eefa) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | Notebook    | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [9ca318e043](https://bsd-hardware.info/?probe=9ca318e043) | Sep 27, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| Intel         | S5520UR E22554-752          | Server      | [ab0b5c4d36](https://bsd-hardware.info/?probe=ab0b5c4d36) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d7cdc9b73e](https://bsd-hardware.info/?probe=d7cdc9b73e) | Sep 26, 2023 |
| HP            | 8055                        | Desktop     | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| Protectli     | FW4B                        | Desktop     | [753b149819](https://bsd-hardware.info/?probe=753b149819) | Sep 26, 2023 |
| ASUSTek       | P9D-MV Series               | Server      | [0a035e25a9](https://bsd-hardware.info/?probe=0a035e25a9) | Sep 26, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [0b2b7195c1](https://bsd-hardware.info/?probe=0b2b7195c1) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [bde8cc45df](https://bsd-hardware.info/?probe=bde8cc45df) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [0ce8f84155](https://bsd-hardware.info/?probe=0ce8f84155) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [3c10d0b8ed](https://bsd-hardware.info/?probe=3c10d0b8ed) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [bc62c36654](https://bsd-hardware.info/?probe=bc62c36654) | Sep 25, 2023 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [0f60a1a400](https://bsd-hardware.info/?probe=0f60a1a400) | Sep 25, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Dell          | 0VV3F2 A01                  | Server      | [69b9504be5](https://bsd-hardware.info/?probe=69b9504be5) | Sep 25, 2023 |
| Intel         | S5520UR E22554-753          | Server      | [4094543b6f](https://bsd-hardware.info/?probe=4094543b6f) | Sep 25, 2023 |
| HP            | 3396                        | Desktop     | [a60feb9960](https://bsd-hardware.info/?probe=a60feb9960) | Sep 25, 2023 |
| ASUSTek       | P9D-MV Series               | Server      | [bccf02e740](https://bsd-hardware.info/?probe=bccf02e740) | Sep 25, 2023 |
| HP            | 18E5                        | Desktop     | [9c21b6e355](https://bsd-hardware.info/?probe=9c21b6e355) | Sep 25, 2023 |
| ASRock        | B760M-HDV/M.2 D4            | Desktop     | [886dc0272b](https://bsd-hardware.info/?probe=886dc0272b) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a77db6c46a](https://bsd-hardware.info/?probe=a77db6c46a) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [05f45ba264](https://bsd-hardware.info/?probe=05f45ba264) | Sep 25, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [6153909c9e](https://bsd-hardware.info/?probe=6153909c9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [5232e5837b](https://bsd-hardware.info/?probe=5232e5837b) | Sep 25, 2023 |
| Unknown       | YL-J1900L4-V2               | Desktop     | [c186f8b50c](https://bsd-hardware.info/?probe=c186f8b50c) | Sep 25, 2023 |
| CncTion       | N4505-4L B0                 | Desktop     | [5880a22b30](https://bsd-hardware.info/?probe=5880a22b30) | Sep 25, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [64dac999bd](https://bsd-hardware.info/?probe=64dac999bd) | Sep 24, 2023 |
| Protectli     | VP4630                      | Desktop     | [d5c0fe73ef](https://bsd-hardware.info/?probe=d5c0fe73ef) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6a2ce1e29f](https://bsd-hardware.info/?probe=6a2ce1e29f) | Sep 24, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [a488a0576d](https://bsd-hardware.info/?probe=a488a0576d) | Sep 24, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1bd71b0bf0](https://bsd-hardware.info/?probe=1bd71b0bf0) | Sep 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c2291f803c](https://bsd-hardware.info/?probe=c2291f803c) | Sep 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| MSI           | H81M-P33                    | Desktop     | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| AZW           | EQ                          | Desktop     | [1f9a2fcb6e](https://bsd-hardware.info/?probe=1f9a2fcb6e) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [a5643cabc4](https://bsd-hardware.info/?probe=a5643cabc4) | Sep 24, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [be147f7ff1](https://bsd-hardware.info/?probe=be147f7ff1) | Sep 24, 2023 |
| NU591         | 1.0                         | Desktop     | [99f3260ee0](https://bsd-hardware.info/?probe=99f3260ee0) | Sep 24, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [6c3728aa16](https://bsd-hardware.info/?probe=6c3728aa16) | Sep 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [8644c80a4a](https://bsd-hardware.info/?probe=8644c80a4a) | Sep 24, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [3b12ca9995](https://bsd-hardware.info/?probe=3b12ca9995) | Sep 23, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| Intel         | NUC11TNBi5 M11904-500       | Mini pc     | [fd9c33d93c](https://bsd-hardware.info/?probe=fd9c33d93c) | Sep 23, 2023 |
| AZW           | SEi V1.0                    | Desktop     | [1d0307b36d](https://bsd-hardware.info/?probe=1d0307b36d) | Sep 23, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [d99ed8ecd0](https://bsd-hardware.info/?probe=d99ed8ecd0) | Sep 23, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [80f0800cee](https://bsd-hardware.info/?probe=80f0800cee) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [312bc5d526](https://bsd-hardware.info/?probe=312bc5d526) | Sep 23, 2023 |
| HP            | 8299                        | Desktop     | [fee80cc3e3](https://bsd-hardware.info/?probe=fee80cc3e3) | Sep 23, 2023 |
| AZW           | EQ                          | Desktop     | [c65840f9cf](https://bsd-hardware.info/?probe=c65840f9cf) | Sep 23, 2023 |
| PC Engines    | APU2                        | Desktop     | [3c7bd005ef](https://bsd-hardware.info/?probe=3c7bd005ef) | Sep 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [868f49643a](https://bsd-hardware.info/?probe=868f49643a) | Sep 23, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [a4ebf601cd](https://bsd-hardware.info/?probe=a4ebf601cd) | Sep 23, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [d8ccddab5a](https://bsd-hardware.info/?probe=d8ccddab5a) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e1ef4a73c](https://bsd-hardware.info/?probe=3e1ef4a73c) | Sep 23, 2023 |
| GPD           | G1619-04                    | Notebook    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [06d8f02eb7](https://bsd-hardware.info/?probe=06d8f02eb7) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [16640c7f04](https://bsd-hardware.info/?probe=16640c7f04) | Sep 22, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [6d38812084](https://bsd-hardware.info/?probe=6d38812084) | Sep 22, 2023 |
| HP            | 18E5                        | Desktop     | [02b94adef6](https://bsd-hardware.info/?probe=02b94adef6) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [d8e6c9ffe6](https://bsd-hardware.info/?probe=d8e6c9ffe6) | Sep 22, 2023 |
| Intel         | Milstead Platform           | Notebook    | [04e544d5f1](https://bsd-hardware.info/?probe=04e544d5f1) | Sep 22, 2023 |
| Dell          | Latitude E7470              | Notebook    | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [8386219e8f](https://bsd-hardware.info/?probe=8386219e8f) | Sep 22, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [6bec3eae14](https://bsd-hardware.info/?probe=6bec3eae14) | Sep 22, 2023 |
| Sophos        | SG                          | Firewall    | [54ff756b5b](https://bsd-hardware.info/?probe=54ff756b5b) | Sep 22, 2023 |
| ASRock        | Z690 Phantom Gaming 4/D5    | Desktop     | [6eab8daef7](https://bsd-hardware.info/?probe=6eab8daef7) | Sep 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [fcde651e99](https://bsd-hardware.info/?probe=fcde651e99) | Sep 21, 2023 |
| Dell          | 0KP561                      | Desktop     | [cf15aea783](https://bsd-hardware.info/?probe=cf15aea783) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e046bd9405](https://bsd-hardware.info/?probe=e046bd9405) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [90f89eea16](https://bsd-hardware.info/?probe=90f89eea16) | Sep 21, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9eb426c568](https://bsd-hardware.info/?probe=9eb426c568) | Sep 21, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [c5a2093552](https://bsd-hardware.info/?probe=c5a2093552) | Sep 21, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| HP            | 18E8                        | Desktop     | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| HP            | 859B                        | Desktop     | [7b8592b129](https://bsd-hardware.info/?probe=7b8592b129) | Sep 21, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [9a9cdd30a2](https://bsd-hardware.info/?probe=9a9cdd30a2) | Sep 21, 2023 |
| PC Engines    | apu6                        | Desktop     | [1a45dd59a4](https://bsd-hardware.info/?probe=1a45dd59a4) | Sep 21, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [5478cff8a7](https://bsd-hardware.info/?probe=5478cff8a7) | Sep 21, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5a0b8eb786](https://bsd-hardware.info/?probe=5a0b8eb786) | Sep 21, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [423687627b](https://bsd-hardware.info/?probe=423687627b) | Sep 21, 2023 |
| HP            | 18E8                        | Desktop     | [cb4a5de309](https://bsd-hardware.info/?probe=cb4a5de309) | Sep 21, 2023 |
| HP            | 8299                        | Desktop     | [2f1bdffe66](https://bsd-hardware.info/?probe=2f1bdffe66) | Sep 20, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e84cddfaaf](https://bsd-hardware.info/?probe=e84cddfaaf) | Sep 20, 2023 |
| Bochs         | Unknown                     | Desktop     | [65f7da4601](https://bsd-hardware.info/?probe=65f7da4601) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| HP            | 83F3                        | Desktop     | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c479d7824](https://bsd-hardware.info/?probe=3c479d7824) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [13ba11c952](https://bsd-hardware.info/?probe=13ba11c952) | Sep 20, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [eae9f87345](https://bsd-hardware.info/?probe=eae9f87345) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a57145af](https://bsd-hardware.info/?probe=80a57145af) | Sep 20, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [c368087050](https://bsd-hardware.info/?probe=c368087050) | Sep 20, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [da7e89f514](https://bsd-hardware.info/?probe=da7e89f514) | Sep 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [6ee2f45613](https://bsd-hardware.info/?probe=6ee2f45613) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [34bffe0ed1](https://bsd-hardware.info/?probe=34bffe0ed1) | Sep 20, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [60a616adf4](https://bsd-hardware.info/?probe=60a616adf4) | Sep 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [92da10b93b](https://bsd-hardware.info/?probe=92da10b93b) | Sep 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| HP            | 8522 A01                    | Mini pc     | [dd5d9863aa](https://bsd-hardware.info/?probe=dd5d9863aa) | Sep 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [bdc1cdb479](https://bsd-hardware.info/?probe=bdc1cdb479) | Sep 19, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c7e64c0893](https://bsd-hardware.info/?probe=c7e64c0893) | Sep 19, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [5a57c7066e](https://bsd-hardware.info/?probe=5a57c7066e) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [07698e61c2](https://bsd-hardware.info/?probe=07698e61c2) | Sep 19, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [621470728b](https://bsd-hardware.info/?probe=621470728b) | Sep 19, 2023 |
| Lenovo        | 367D 31900058 STD           | Desktop     | [efd07dfb64](https://bsd-hardware.info/?probe=efd07dfb64) | Sep 19, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8ebba0ee37](https://bsd-hardware.info/?probe=8ebba0ee37) | Sep 19, 2023 |
| Dell          | 0D28YY A02                  | Desktop     | [6c195174db](https://bsd-hardware.info/?probe=6c195174db) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ed7bef076e](https://bsd-hardware.info/?probe=ed7bef076e) | Sep 19, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [95286f41d9](https://bsd-hardware.info/?probe=95286f41d9) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7c6f946c9b](https://bsd-hardware.info/?probe=7c6f946c9b) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [0fe1aab1d8](https://bsd-hardware.info/?probe=0fe1aab1d8) | Sep 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [c4599cac13](https://bsd-hardware.info/?probe=c4599cac13) | Sep 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [f6f0fa8016](https://bsd-hardware.info/?probe=f6f0fa8016) | Sep 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [0a9c074970](https://bsd-hardware.info/?probe=0a9c074970) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5e7775568c](https://bsd-hardware.info/?probe=5e7775568c) | Sep 18, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [0cfd79f7fe](https://bsd-hardware.info/?probe=0cfd79f7fe) | Sep 18, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [65aa2c10a3](https://bsd-hardware.info/?probe=65aa2c10a3) | Sep 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [815d9f2867](https://bsd-hardware.info/?probe=815d9f2867) | Sep 18, 2023 |
| HP            | 1790                        | Desktop     | [17ace3bb2c](https://bsd-hardware.info/?probe=17ace3bb2c) | Sep 18, 2023 |
| CncTion       | Jasper-4L B0                | Desktop     | [96f81e84f6](https://bsd-hardware.info/?probe=96f81e84f6) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7b6014f65f](https://bsd-hardware.info/?probe=7b6014f65f) | Sep 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [e6e705b7cf](https://bsd-hardware.info/?probe=e6e705b7cf) | Sep 18, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [143c5f73fc](https://bsd-hardware.info/?probe=143c5f73fc) | Sep 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [39e1d38287](https://bsd-hardware.info/?probe=39e1d38287) | Sep 17, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [cdeddbf4be](https://bsd-hardware.info/?probe=cdeddbf4be) | Sep 17, 2023 |
| CncTion       | Jasper-4L B0                | Desktop     | [4254b5eac8](https://bsd-hardware.info/?probe=4254b5eac8) | Sep 17, 2023 |
| ASRock        | H670M-ITX/ax                | Desktop     | [1b6996f127](https://bsd-hardware.info/?probe=1b6996f127) | Sep 17, 2023 |
| HP            | 82A2                        | Desktop     | [4f125fbc75](https://bsd-hardware.info/?probe=4f125fbc75) | Sep 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4a9993ca08](https://bsd-hardware.info/?probe=4a9993ca08) | Sep 17, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [35fbb60b50](https://bsd-hardware.info/?probe=35fbb60b50) | Sep 17, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4ee4930d11](https://bsd-hardware.info/?probe=4ee4930d11) | Sep 17, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | Notebook    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [31455b0d33](https://bsd-hardware.info/?probe=31455b0d33) | Sep 17, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [b6763a8d49](https://bsd-hardware.info/?probe=b6763a8d49) | Sep 17, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | Notebook    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [3950a0580d](https://bsd-hardware.info/?probe=3950a0580d) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [31cf5dc87d](https://bsd-hardware.info/?probe=31cf5dc87d) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [f0b617a1bc](https://bsd-hardware.info/?probe=f0b617a1bc) | Sep 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [5aebf0e729](https://bsd-hardware.info/?probe=5aebf0e729) | Sep 16, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [029b3cdd58](https://bsd-hardware.info/?probe=029b3cdd58) | Sep 16, 2023 |
| Gigabyte      | Q170TN                      | Desktop     | [f8baffb969](https://bsd-hardware.info/?probe=f8baffb969) | Sep 16, 2023 |
| Dell          | 0R5KP9 A09                  | Server      | [54ff0b9d41](https://bsd-hardware.info/?probe=54ff0b9d41) | Sep 16, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [49593de0a0](https://bsd-hardware.info/?probe=49593de0a0) | Sep 16, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [a054400ef6](https://bsd-hardware.info/?probe=a054400ef6) | Sep 16, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [35544a61bd](https://bsd-hardware.info/?probe=35544a61bd) | Sep 16, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [80707f8712](https://bsd-hardware.info/?probe=80707f8712) | Sep 16, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1f54d2bb5b](https://bsd-hardware.info/?probe=1f54d2bb5b) | Sep 16, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [a2d011d2d7](https://bsd-hardware.info/?probe=a2d011d2d7) | Sep 16, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9a30d2d88c](https://bsd-hardware.info/?probe=9a30d2d88c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6acb378a1](https://bsd-hardware.info/?probe=d6acb378a1) | Sep 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d36ff6181c](https://bsd-hardware.info/?probe=d36ff6181c) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3fcc5727d3](https://bsd-hardware.info/?probe=3fcc5727d3) | Sep 15, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab77dcfd74](https://bsd-hardware.info/?probe=ab77dcfd74) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| AZW           | U59                         | Desktop     | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | Notebook    | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0c65fb5e8c](https://bsd-hardware.info/?probe=0c65fb5e8c) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe010506e6](https://bsd-hardware.info/?probe=fe010506e6) | Sep 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [9790cd72bc](https://bsd-hardware.info/?probe=9790cd72bc) | Sep 15, 2023 |
| Dell          | XPS 9320                    | Notebook    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| AZW           | U59                         | Desktop     | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [b90b748742](https://bsd-hardware.info/?probe=b90b748742) | Sep 14, 2023 |
| Dell          | OptiPlex 3020               | Desktop     | [dfb6cce27d](https://bsd-hardware.info/?probe=dfb6cce27d) | Sep 14, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [fe04f35995](https://bsd-hardware.info/?probe=fe04f35995) | Sep 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [f28bb4ffda](https://bsd-hardware.info/?probe=f28bb4ffda) | Sep 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [28f5d3aea6](https://bsd-hardware.info/?probe=28f5d3aea6) | Sep 14, 2023 |
| Dell          | 0D24M8 A03                  | Desktop     | [48441955a6](https://bsd-hardware.info/?probe=48441955a6) | Sep 14, 2023 |
| eMachines     | G640                        | Notebook    | [c05619033c](https://bsd-hardware.info/?probe=c05619033c) | Sep 14, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [53d31a28bf](https://bsd-hardware.info/?probe=53d31a28bf) | Sep 14, 2023 |
| Platform      | ARB938                      | Notebook    | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Alienware     | m15                         | Notebook    | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| ASRock        | J1900D2Y                    | Desktop     | [2084583d47](https://bsd-hardware.info/?probe=2084583d47) | Sep 14, 2023 |
| HP            | Pavilion dv5                | Notebook    | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [3fe0e846fe](https://bsd-hardware.info/?probe=3fe0e846fe) | Sep 14, 2023 |
| Sophos        | SG                          | Firewall    | [960f408d24](https://bsd-hardware.info/?probe=960f408d24) | Sep 13, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [227062e965](https://bsd-hardware.info/?probe=227062e965) | Sep 13, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| ASRock        | J3455M                      | Desktop     | [f9809dfb0f](https://bsd-hardware.info/?probe=f9809dfb0f) | Sep 13, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| Sophos        | SG                          | Firewall    | [3328f1aa70](https://bsd-hardware.info/?probe=3328f1aa70) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| Dell          | 0D28YY A02                  | Desktop     | [fe5635048a](https://bsd-hardware.info/?probe=fe5635048a) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| HP            | 8055                        | Desktop     | [be8554bed1](https://bsd-hardware.info/?probe=be8554bed1) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| Dell          | 0KM5PX A02                  | Server      | [2028895de0](https://bsd-hardware.info/?probe=2028895de0) | Sep 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [ae320bd7de](https://bsd-hardware.info/?probe=ae320bd7de) | Sep 13, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [1b0fcd812e](https://bsd-hardware.info/?probe=1b0fcd812e) | Sep 13, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [92ce33c604](https://bsd-hardware.info/?probe=92ce33c604) | Sep 13, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [f3594b1f7c](https://bsd-hardware.info/?probe=f3594b1f7c) | Sep 13, 2023 |
| HP            | 212B                        | Desktop     | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [5c89a7a1f1](https://bsd-hardware.info/?probe=5c89a7a1f1) | Sep 13, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [984a64677e](https://bsd-hardware.info/?probe=984a64677e) | Sep 13, 2023 |
| OEGStone      | doceo 510                   | Notebook    | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b0cd1ce0f4](https://bsd-hardware.info/?probe=b0cd1ce0f4) | Sep 13, 2023 |
| Sophos        | SG                          | Firewall    | [4bc5b044cd](https://bsd-hardware.info/?probe=4bc5b044cd) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [d3c0559486](https://bsd-hardware.info/?probe=d3c0559486) | Sep 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [8229339c2f](https://bsd-hardware.info/?probe=8229339c2f) | Sep 12, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| Protectli     | VP2420                      | Desktop     | [626a91f30d](https://bsd-hardware.info/?probe=626a91f30d) | Sep 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [0fccf590d4](https://bsd-hardware.info/?probe=0fccf590d4) | Sep 12, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [6857d78d0b](https://bsd-hardware.info/?probe=6857d78d0b) | Sep 12, 2023 |
| CheckPoint    | T-140-00                    | Desktop     | [670266bc8e](https://bsd-hardware.info/?probe=670266bc8e) | Sep 12, 2023 |
| MSI           | MS-S0891                    | Desktop     | [10b3300ed1](https://bsd-hardware.info/?probe=10b3300ed1) | Sep 12, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [f5f0e573fe](https://bsd-hardware.info/?probe=f5f0e573fe) | Sep 11, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [78bc36f5a9](https://bsd-hardware.info/?probe=78bc36f5a9) | Sep 11, 2023 |
| Dell          | BlackfordESB2               | Server      | [36b37267be](https://bsd-hardware.info/?probe=36b37267be) | Sep 11, 2023 |
| HP            | Mini 110-3100               | Notebook    | [14f75b6704](https://bsd-hardware.info/?probe=14f75b6704) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7af171368a](https://bsd-hardware.info/?probe=7af171368a) | Sep 11, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [015620b56d](https://bsd-hardware.info/?probe=015620b56d) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [0602673da0](https://bsd-hardware.info/?probe=0602673da0) | Sep 11, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6e9a9c509b](https://bsd-hardware.info/?probe=6e9a9c509b) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [fd131bd648](https://bsd-hardware.info/?probe=fd131bd648) | Sep 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3352f08ec3](https://bsd-hardware.info/?probe=3352f08ec3) | Sep 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7923196f55](https://bsd-hardware.info/?probe=7923196f55) | Sep 11, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 447       | 2.87%   |
| helloSystem 0.8.1    | 390       | 2.5%    |
| OPNsense 23.1.11     | 341       | 2.19%   |
| OPNsense 21.7.7      | 281       | 1.8%    |
| OPNsense 22.7.10     | 262       | 1.68%   |
| helloSystem 0.8.0    | 254       | 1.63%   |
| helloSystem 0.5.0    | 245       | 1.57%   |
| OPNsense 21.1        | 240       | 1.54%   |
| FreeBSD 13.1         | 234       | 1.5%    |
| OPNsense 23.1        | 229       | 1.47%   |
| OPNsense 21.7.1      | 229       | 1.47%   |
| OPNsense 22.1        | 227       | 1.46%   |
| OPNsense 21.7.3      | 225       | 1.45%   |
| OPNsense 21.1.5      | 225       | 1.45%   |
| FreeBSD 13.0         | 223       | 1.43%   |
| OPNsense 23.1.5      | 219       | 1.41%   |
| OPNsense 22.7.4      | 214       | 1.37%   |
| OPNsense 20.7.8      | 214       | 1.37%   |
| OpenBSD 6.8          | 208       | 1.34%   |
| OPNsense 21.1.3      | 205       | 1.32%   |
| OPNsense 23.1.7      | 196       | 1.26%   |
| OPNsense 23.1.1      | 192       | 1.23%   |
| OPNsense 22.1.6      | 192       | 1.23%   |
| helloSystem 0.4.0    | 190       | 1.22%   |
| OPNsense 22.1.8      | 187       | 1.2%    |
| OPNsense 22.7.6      | 184       | 1.18%   |
| OPNsense 22.1.10     | 184       | 1.18%   |
| OPNsense 22.7.9      | 175       | 1.12%   |
| OPNsense 21.1.4      | 175       | 1.12%   |
| OPNsense 23.7.1      | 169       | 1.09%   |
| OPNsense 23.1.9      | 160       | 1.03%   |
| OPNsense 21.1.1      | 157       | 1.01%   |
| FreeBSD 14.0-CURRENT | 152       | 0.98%   |
| OPNsense 23.1.6      | 149       | 0.96%   |
| OPNsense 21.1.2      | 147       | 0.94%   |
| FreeBSD 13.2         | 143       | 0.92%   |
| OPNsense 23.7.7      | 142       | 0.91%   |
| FreeBSD 12.2         | 141       | 0.91%   |
| helloSystem 0.6.0    | 139       | 0.89%   |
| OPNsense 23.7.5      | 138       | 0.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 6507      | 54.44%  |
| FreeBSD     | 2408      | 20.15%  |
| helloSystem | 1661      | 13.9%   |
| OpenBSD     | 597       | 4.99%   |
| GhostBSD    | 273       | 2.28%   |
| NomadBSD    | 190       | 1.59%   |
| NetBSD      | 74        | 0.62%   |
| TrueNAS     | 48        | 0.4%    |
| pfSense     | 33        | 0.28%   |
| FreeNAS     | 30        | 0.25%   |
| MyBee       | 27        | 0.23%   |
| HardenedBSD | 19        | 0.16%   |
| MidnightBSD | 18        | 0.15%   |
| DragonFly   | 16        | 0.13%   |
| XigmaNAS    | 14        | 0.12%   |
| FuryBSD     | 12        | 0.1%    |
| FuguIta     | 7         | 0.06%   |
| ClonOS      | 7         | 0.06%   |
| OS108       | 4         | 0.03%   |
| Ting        | 3         | 0.03%   |
| PC-BSD      | 3         | 0.03%   |
| LibertyBSD  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 11470     | 97.32%  |
| i386    | 144       | 1.22%   |
| arm64   | 128       | 1.09%   |
| arm     | 14        | 0.12%   |
| macppc  | 8         | 0.07%   |
| evbarm  | 7         | 0.06%   |
| sparc64 | 6         | 0.05%   |
| powerpc | 4         | 0.03%   |
| octeon  | 2         | 0.02%   |
| armv7   | 2         | 0.02%   |
| riscv   | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 7635      | 63.25%  |
| helloDesktop     | 1857      | 15.38%  |
| XFCE             | 503       | 4.17%   |
| KDE5             | 443       | 3.67%   |
| MATE             | 359       | 2.97%   |
| fvwm             | 274       | 2.27%   |
| Openbox          | 225       | 1.86%   |
| GNOME            | 212       | 1.76%   |
| TWM              | 185       | 1.53%   |
| i3               | 118       | 0.98%   |
| Cinnamon         | 34        | 0.28%   |
| LXQt             | 30        | 0.25%   |
| AwesomeWM        | 29        | 0.24%   |
| Fluxbox          | 25        | 0.21%   |
| Enlightenment    | 21        | 0.17%   |
| LXDE             | 16        | 0.13%   |
| Lumina           | 12        | 0.1%    |
| DWM              | 11        | 0.09%   |
| xinitrc          | 8         | 0.07%   |
| Window Maker     | 6         | 0.05%   |
| GNUstep          | 6         | 0.05%   |
| CTWM             | 6         | 0.05%   |
| Picom            | 5         | 0.04%   |
| xfwm             | 4         | 0.03%   |
| X-Cinnamon       | 4         | 0.03%   |
| IceWM            | 4         | 0.03%   |
| CDE              | 4         | 0.03%   |
| spectrwm         | 3         | 0.02%   |
| KDE              | 3         | 0.02%   |
| Budgie           | 3         | 0.02%   |
| Xfwm4            | 2         | 0.02%   |
| stumpwm          | 2         | 0.02%   |
| Mutter           | 2         | 0.02%   |
| Metacity (Marco) | 2         | 0.02%   |
| JWM              | 2         | 0.02%   |
| Compton          | 2         | 0.02%   |
| awesome          | 2         | 0.02%   |
| sway             | 1         | 0.01%   |
| sdorfehs         | 1         | 0.01%   |
| Ratpoison        | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 7743      | 65.33%  |
| X11     | 4049      | 34.16%  |
| Wayland | 59        | 0.5%    |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 8667      | 72.36%  |
| SLiM    | 2080      | 17.37%  |
| SDDM    | 456       | 3.81%   |
| LightDM | 437       | 3.65%   |
| XDM     | 169       | 1.41%   |
| GDM     | 144       | 1.2%    |
| Ly      | 22        | 0.18%   |
| PCDM    | 2         | 0.02%   |
| WDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 7795      | 64.36%  |
| en_US           | 1933      | 15.96%  |
| C               | 1300      | 10.73%  |
| ru_RU           | 206       | 1.7%    |
| fr_FR           | 159       | 1.31%   |
| de_DE           | 123       | 1.02%   |
| en              | 92        | 0.76%   |
| en_GB           | 61        | 0.5%    |
| es_ES           | 52        | 0.43%   |
| pt_BR           | 33        | 0.27%   |
| pl_PL           | 27        | 0.22%   |
| zh_CN           | 26        | 0.21%   |
| it_IT           | 26        | 0.21%   |
| fr              | 17        | 0.14%   |
| en_CA           | 16        | 0.13%   |
| en_AU           | 15        | 0.12%   |
| ru              | 12        | 0.1%    |
| ja_JP           | 12        | 0.1%    |
| fi_FI           | 11        | 0.09%   |
| zh_TW           | 10        | 0.08%   |
| uk_UA           | 10        | 0.08%   |
| pt              | 9         | 0.07%   |
| es              | 9         | 0.07%   |
| en_IE           | 8         | 0.07%   |
| de              | 8         | 0.07%   |
| nb_NO           | 7         | 0.06%   |
| tr_TR           | 6         | 0.05%   |
| nl_NL           | 6         | 0.05%   |
| hu_HU           | 6         | 0.05%   |
| cs_CZ           | 6         | 0.05%   |
| sv_SE           | 5         | 0.04%   |
| es_AR           | 5         | 0.04%   |
| en_NZ           | 5         | 0.04%   |
| el_GR           | 5         | 0.04%   |
| ru_RU.KOI8-R    | 4         | 0.03%   |
| ko_KR           | 4         | 0.03%   |
| jp_JP           | 4         | 0.03%   |
| en_US.ISO8859-1 | 4         | 0.03%   |
| pt_PT           | 3         | 0.02%   |
| it              | 3         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 9920      | 83.27%  |
| BIOS | 1993      | 16.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 5734      | 47.26%  |
| Zfs     | 5111      | 42.12%  |
| Cd9660  | 655       | 5.4%    |
| Ffs     | 605       | 4.99%   |
| Hammer2 | 15        | 0.12%   |
| Unknown | 7         | 0.06%   |
| XXX     | 3         | 0.02%   |
| Nfs     | 2         | 0.02%   |
| Xfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 10753     | 90.57%  |
| MBR     | 970       | 8.17%   |
| Unknown | 133       | 1.12%   |
| BSD     | 16        | 0.13%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1344      | 11.41%  |
| Lenovo                  | 1210      | 10.27%  |
| Hewlett-Packard         | 1027      | 8.72%   |
| Unknown                 | 999       | 8.48%   |
| ASUSTek Computer        | 993       | 8.43%   |
| Intel                   | 570       | 4.84%   |
| Supermicro              | 529       | 4.49%   |
| Gigabyte Technology     | 517       | 4.39%   |
| ASRock                  | 439       | 3.73%   |
| Protectli               | 349       | 2.96%   |
| PC Engines              | 349       | 2.96%   |
| MSI                     | 318       | 2.7%    |
| Fujitsu                 | 239       | 2.03%   |
| AMI                     | 225       | 1.91%   |
| Acer                    | 213       | 1.81%   |
| Apple                   | 184       | 1.56%   |
| Sophos                  | 165       | 1.4%    |
| Techvision              | 129       | 1.09%   |
| ZOTAC                   | 103       | 0.87%   |
| Deciso                  | 101       | 0.86%   |
| Shuttle                 | 76        | 0.65%   |
| BESSTAR Tech            | 73        | 0.62%   |
| Toshiba                 | 61        | 0.52%   |
| Samsung Electronics     | 53        | 0.45%   |
| MW                      | 53        | 0.45%   |
| AZW                     | 53        | 0.45%   |
| Biostar                 | 45        | 0.38%   |
| ASRockRack              | 41        | 0.35%   |
| IBM                     | 40        | 0.34%   |
| CncTion                 | 37        | 0.31%   |
| Sony                    | 36        | 0.31%   |
| Hardkernel              | 36        | 0.31%   |
| AWOW                    | 35        | 0.3%    |
| Raspberry Pi Foundation | 34        | 0.29%   |
| Google                  | 31        | 0.26%   |
| CWWK                    | 31        | 0.26%   |
| CompuLab                | 31        | 0.26%   |
| IceWhale Technology     | 27        | 0.23%   |
| Foxconn                 | 26        | 0.22%   |
| Pegatron                | 24        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 1041      | 8.84%   |
| PC Engines APU2                     | 171       | 1.45%   |
| AMI Aptio CRB                       | 168       | 1.43%   |
| Supermicro Super Server             | 149       | 1.26%   |
| Techvision TVI7309X                 | 129       | 1.09%   |
| Protectli FW4B                      | 126       | 1.07%   |
| Intel Q3XXG4-P V1.0                 | 126       | 1.07%   |
| PC Engines apu4                     | 109       | 0.93%   |
| Protectli FW6                       | 99        | 0.84%   |
| Sophos SG                           | 93        | 0.79%   |
| ASUS All Series                     | 90        | 0.76%   |
| Fujitsu FUTRO S920                  | 84        | 0.71%   |
| HP t620 PLUS Quad Core TC           | 58        | 0.49%   |
| MW GMLK-2_5G4L                      | 53        | 0.45%   |
| HP t730 Thin Client                 | 53        | 0.45%   |
| Dell OptiPlex 9020                  | 52        | 0.44%   |
| Dell PowerEdge R210 II              | 48        | 0.41%   |
| Dell OptiPlex 3020                  | 48        | 0.41%   |
| Dell OptiPlex 7010                  | 42        | 0.36%   |
| Sophos XG                           | 41        | 0.35%   |
| Sophos UTM                          | 30        | 0.25%   |
| Hardkernel ODROID-H2                | 29        | 0.25%   |
| Dell Wyse 5070 Extended Thin Client | 29        | 0.25%   |
| Supermicro X9SCL/X9SCM              | 28        | 0.24%   |
| Supermicro A1SAi                    | 28        | 0.24%   |
| HP EliteDesk 800 G1 SFF             | 28        | 0.24%   |
| Dell OptiPlex 7040                  | 28        | 0.24%   |
| Protectli VP2410                    | 27        | 0.23%   |
| Supermicro X10SLH-N6-ST031          | 26        | 0.22%   |
| RPi Raspberry Pi                    | 25        | 0.21%   |
| PC Engines APU3                     | 24        | 0.2%    |
| PC Engines APU                      | 24        | 0.2%    |
| HP Compaq Elite 8300 SFF            | 24        | 0.2%    |
| CompuLab fitlet2                    | 24        | 0.2%    |
| ZOTAC ZBOX-CI329NANO                | 23        | 0.2%    |
| HP ProLiant MicroServer Gen8        | 23        | 0.2%    |
| Dell PowerEdge R710                 | 23        | 0.2%    |
| Deciso NetBoard-A10                 | 23        | 0.2%    |
| Deciso Netboard A20                 | 23        | 0.2%    |
| BESSTAR Tech GK41                   | 23        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 1041      | 8.84%   |
| Lenovo ThinkPad     | 698       | 5.92%   |
| Dell OptiPlex       | 455       | 3.86%   |
| Dell PowerEdge      | 318       | 2.7%    |
| Lenovo ThinkCentre  | 233       | 1.98%   |
| Dell Latitude       | 175       | 1.49%   |
| PC Engines APU2     | 171       | 1.45%   |
| AMI Aptio           | 170       | 1.44%   |
| ASUS PRIME          | 156       | 1.32%   |
| HP ProLiant         | 155       | 1.32%   |
| Supermicro Super    | 149       | 1.26%   |
| Dell Inspiron       | 139       | 1.18%   |
| Acer Aspire         | 134       | 1.14%   |
| Techvision TVI7309X | 129       | 1.09%   |
| Intel Q3XXG4-P      | 127       | 1.08%   |
| Protectli FW4B      | 126       | 1.07%   |
| HP Compaq           | 126       | 1.07%   |
| HP EliteDesk        | 116       | 0.98%   |
| Fujitsu FUTRO       | 116       | 0.98%   |
| PC Engines apu4     | 109       | 0.93%   |
| HP ProDesk          | 103       | 0.87%   |
| Protectli FW6       | 99        | 0.84%   |
| Dell Precision      | 94        | 0.8%    |
| Sophos SG           | 93        | 0.79%   |
| ASUS All            | 90        | 0.76%   |
| Lenovo IdeaPad      | 82        | 0.7%    |
| ASUS ROG            | 77        | 0.65%   |
| HP t620             | 66        | 0.56%   |
| ASUS TUF            | 65        | 0.55%   |
| HP Pavilion         | 62        | 0.53%   |
| HP t730             | 54        | 0.46%   |
| HP EliteBook        | 54        | 0.46%   |
| MW GMLK-2           | 53        | 0.45%   |
| Deciso Netboard     | 46        | 0.39%   |
| Sophos XG           | 41        | 0.35%   |
| Toshiba Satellite   | 40        | 0.34%   |
| HP ProBook          | 38        | 0.32%   |
| Dell Wyse           | 38        | 0.32%   |
| Dell XPS            | 36        | 0.31%   |
| Fujitsu ESPRIMO     | 35        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1294      | 10.98%  |
| 2020    | 1043      | 8.85%   |
| 2019    | 1043      | 8.85%   |
| 2021    | 967       | 8.21%   |
| 2022    | 954       | 8.1%    |
| 2016    | 891       | 7.56%   |
| 2014    | 867       | 7.36%   |
| 2013    | 696       | 5.91%   |
| 2017    | 676       | 5.74%   |
| 2012    | 612       | 5.19%   |
| 2011    | 597       | 5.07%   |
| 2015    | 573       | 4.86%   |
| 2010    | 404       | 3.43%   |
| 2009    | 291       | 2.47%   |
| 2023    | 251       | 2.13%   |
| 2008    | 223       | 1.89%   |
| Unknown | 197       | 1.67%   |
| 2007    | 106       | 0.9%    |
| 2006    | 54        | 0.46%   |
| 2005    | 15        | 0.13%   |
| 2004    | 12        | 0.1%    |
| 2003    | 8         | 0.07%   |
| 2002    | 5         | 0.04%   |
| 2001    | 3         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 7125      | 60.47%  |
| Notebook       | 2641      | 22.42%  |
| Server         | 853       | 7.24%   |
| Mini pc        | 785       | 6.66%   |
| Firewall       | 192       | 1.63%   |
| System on chip | 64        | 0.54%   |
| All in one     | 63        | 0.53%   |
| Convertible    | 51        | 0.43%   |
| Tablet         | 8         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11262     | 95.58%  |
| Yes  | 521       | 4.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 4248      | 35.31%  |
| 16.01-24.0      | 2708      | 22.51%  |
| 4.01-8.0        | 2490      | 20.7%   |
| 32.01-64.0      | 1093      | 9.09%   |
| 64.01-256.0     | 482       | 4.01%   |
| 2.01-3.0        | 441       | 3.67%   |
| 3.01-4.0        | 178       | 1.48%   |
| 24.01-32.0      | 162       | 1.35%   |
| 0.51-1.0        | 96        | 0.8%    |
| 1.01-2.0        | 65        | 0.54%   |
| 0.01-0.5        | 34        | 0.28%   |
| More than 256.0 | 29        | 0.24%   |
| Unknown         | 2         | 0.02%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 6145      | 50.34%  |
| 0.51-1.0        | 3588      | 29.4%   |
| 1.01-2.0        | 1352      | 11.08%  |
| 2.01-3.0        | 327       | 2.68%   |
| 4.01-8.0        | 215       | 1.76%   |
| 3.01-4.0        | 152       | 1.25%   |
| 8.01-16.0       | 105       | 0.86%   |
| Unknown         | 89        | 0.73%   |
| 0               | 73        | 0.6%    |
| 16.01-24.0      | 49        | 0.4%    |
| 24.01-32.0      | 47        | 0.39%   |
| 32.01-64.0      | 39        | 0.32%   |
| 64.01-256.0     | 24        | 0.2%    |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 8167      | 67.23%  |
| 2      | 1727      | 14.22%  |
| 0      | 1090      | 8.97%   |
| 3      | 489       | 4.03%   |
| 4      | 264       | 2.17%   |
| 5      | 135       | 1.11%   |
| 6      | 87        | 0.72%   |
| 7      | 47        | 0.39%   |
| 8      | 29        | 0.24%   |
| 10     | 18        | 0.15%   |
| 14     | 16        | 0.13%   |
| 9      | 15        | 0.12%   |
| 12     | 13        | 0.11%   |
| 11     | 10        | 0.08%   |
| 17     | 5         | 0.04%   |
| 25     | 4         | 0.03%   |
| 13     | 4         | 0.03%   |
| 18     | 3         | 0.02%   |
| 16     | 3         | 0.02%   |
| 15     | 3         | 0.02%   |
| 58     | 2         | 0.02%   |
| 40     | 2         | 0.02%   |
| 24     | 2         | 0.02%   |
| 23     | 2         | 0.02%   |
| 21     | 2         | 0.02%   |
| 19     | 2         | 0.02%   |
| 63     | 1         | 0.01%   |
| 30     | 1         | 0.01%   |
| 28     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 9558      | 80.47%  |
| Yes       | 2319      | 19.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11204     | 95.08%  |
| No        | 580       | 4.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7376      | 62.08%  |
| Yes       | 4506      | 37.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8800      | 74.09%  |
| Yes       | 3077      | 25.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 3018      | 25.5%   |
| Germany      | 1920      | 16.22%  |
| Russia       | 628       | 5.31%   |
| UK           | 474       | 4.01%   |
| France       | 471       | 3.98%   |
| Canada       | 461       | 3.9%    |
| Poland       | 321       | 2.71%   |
| Netherlands  | 308       | 2.6%    |
| Brazil       | 296       | 2.5%    |
| Australia    | 291       | 2.46%   |
| Italy        | 244       | 2.06%   |
| Switzerland  | 220       | 1.86%   |
| Austria      | 199       | 1.68%   |
| Spain        | 196       | 1.66%   |
| China        | 187       | 1.58%   |
| Sweden       | 180       | 1.52%   |
| Czechia      | 109       | 0.92%   |
| Romania      | 107       | 0.9%    |
| Ukraine      | 103       | 0.87%   |
| Finland      | 103       | 0.87%   |
| Norway       | 101       | 0.85%   |
| Belgium      | 101       | 0.85%   |
| Indonesia    | 97        | 0.82%   |
| India        | 95        | 0.8%    |
| Japan        | 89        | 0.75%   |
| Hungary      | 85        | 0.72%   |
| Taiwan       | 78        | 0.66%   |
| Denmark      | 75        | 0.63%   |
| Portugal     | 73        | 0.62%   |
| South Korea  | 65        | 0.55%   |
| Mexico       | 65        | 0.55%   |
| Bulgaria     | 61        | 0.52%   |
| New Zealand  | 58        | 0.49%   |
| Argentina    | 54        | 0.46%   |
| South Africa | 49        | 0.41%   |
| Turkey       | 44        | 0.37%   |
| Greece       | 44        | 0.37%   |
| Thailand     | 34        | 0.29%   |
| Singapore    | 34        | 0.29%   |
| Lithuania    | 31        | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 195       | 1.48%   |
| Berlin            | 167       | 1.27%   |
| Vienna            | 109       | 0.83%   |
| Paris             | 100       | 0.76%   |
| Sydney            | 88        | 0.67%   |
| St Petersburg     | 85        | 0.65%   |
| Munich            | 77        | 0.59%   |
| Hamburg           | 76        | 0.58%   |
| London            | 73        | 0.56%   |
| Zurich            | 61        | 0.46%   |
| Amsterdam         | 60        | 0.46%   |
| Montreal          | 58        | 0.44%   |
| Melbourne         | 55        | 0.42%   |
| Seattle           | 54        | 0.41%   |
| Warsaw            | 52        | 0.4%    |
| Frankfurt am Main | 52        | 0.4%    |
| Cologne           | 48        | 0.37%   |
| Brooklyn          | 47        | 0.36%   |
| Chicago           | 46        | 0.35%   |
| Bucharest         | 46        | 0.35%   |
| Toronto           | 45        | 0.34%   |
| New York          | 45        | 0.34%   |
| Denver            | 45        | 0.34%   |
| Madrid            | 41        | 0.31%   |
| Jakarta           | 41        | 0.31%   |
| Perth             | 40        | 0.3%    |
| Helsinki          | 39        | 0.3%    |
| Milan             | 37        | 0.28%   |
| Los Angeles       | 37        | 0.28%   |
| Kyiv              | 37        | 0.28%   |
| Stuttgart         | 36        | 0.27%   |
| Portland          | 35        | 0.27%   |
| Oslo              | 35        | 0.27%   |
| Brisbane          | 35        | 0.27%   |
| Sofia             | 34        | 0.26%   |
| Singapore         | 33        | 0.25%   |
| Dallas            | 33        | 0.25%   |
| Prague            | 32        | 0.24%   |
| Rome              | 31        | 0.24%   |
| Calgary           | 31        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2119      | 3471   | 15.37%  |
| WDC                 | 1712      | 3743   | 12.41%  |
| Seagate             | 1319      | 2687   | 9.56%   |
| Kingston            | 1077      | 1513   | 7.81%   |
| Crucial             | 678       | 1036   | 4.92%   |
| Toshiba             | 606       | 1081   | 4.39%   |
| Intel               | 572       | 925    | 4.15%   |
| SanDisk             | 569       | 757    | 4.13%   |
| Transcend           | 559       | 837    | 4.05%   |
| Hitachi             | 338       | 607    | 2.45%   |
| A-DATA Technology   | 286       | 399    | 2.07%   |
| China               | 244       | 341    | 1.77%   |
| Hoodisk             | 231       | 345    | 1.68%   |
| HGST                | 197       | 539    | 1.43%   |
| Phison              | 196       | 274    | 1.42%   |
| SK hynix            | 167       | 224    | 1.21%   |
| Micron Technology   | 162       | 243    | 1.17%   |
| Hewlett-Packard     | 141       | 385    | 1.02%   |
| NVMe                | 134       | 184    | 0.97%   |
| SPCC                | 131       | 205    | 0.95%   |
| PNY                 | 114       | 176    | 0.83%   |
| FORESEE             | 107       | 156    | 0.78%   |
| OCZ                 | 100       | 136    | 0.73%   |
| Apacer              | 89        | 116    | 0.65%   |
| Protectli           | 87        | 134    | 0.63%   |
| Patriot             | 80        | 109    | 0.58%   |
| Corsair             | 75        | 128    | 0.54%   |
| Intenso             | 70        | 112    | 0.51%   |
| Apple               | 70        | 78     | 0.51%   |
| Silicon Motion      | 69        | 87     | 0.5%    |
| Innodisk            | 68        | 87     | 0.49%   |
| Dogfish             | 63        | 108    | 0.46%   |
| KingSpec            | 57        | 72     | 0.41%   |
| Gigabyte Technology | 53        | 72     | 0.38%   |
| LITEON              | 51        | 75     | 0.37%   |
| BIWIN               | 46        | 70     | 0.33%   |
| KIOXIA              | 45        | 54     | 0.33%   |
| Team                | 40        | 64     | 0.29%   |
| LITEONIT            | 40        | 49     | 0.29%   |
| Fanxiang            | 40        | 51     | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 170       | 1.13%   |
| Kingston SA400S37120G 120GB        | 132       | 0.88%   |
| Samsung SSD 850 EVO 250GB          | 125       | 0.83%   |
| Samsung SSD 860 EVO 500GB          | 92        | 0.61%   |
| Crucial CT240BX500SSD1 240GB       | 83        | 0.55%   |
| Samsung SSD 860 EVO 250GB          | 80        | 0.53%   |
| Seagate ST500DM002-1BD142 500GB    | 78        | 0.52%   |
| Phison SATA SSD 16GB               | 74        | 0.49%   |
| Kingston SUV500MS120G 120GB        | 72        | 0.48%   |
| Hoodisk SSD 32GB                   | 68        | 0.45%   |
| Hoodisk SSD 64GB                   | 67        | 0.45%   |
| Samsung SSD 850 EVO 500GB          | 66        | 0.44%   |
| Kingston SV300S37A120G 120GB       | 65        | 0.43%   |
| Crucial CT500MX500SSD1 500GB       | 65        | 0.43%   |
| Crucial CT250MX500SSD1 250GB       | 64        | 0.43%   |
| Hoodisk SSD 128GB                  | 59        | 0.39%   |
| Transcend TS128GMSA230S 128GB      | 57        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB     | 55        | 0.37%   |
| FORESEE 128GB SSD                  | 54        | 0.36%   |
| Crucial CT120BX500SSD1 120GB       | 54        | 0.36%   |
| Seagate ST1000DM010-2EP102 1TB     | 53        | 0.35%   |
| Kingston SA400S37480G 480GB        | 53        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB       | 49        | 0.33%   |
| HP RAID 1(1+0) 450GB               | 48        | 0.32%   |
| China SATA SSD 16GB                | 48        | 0.32%   |
| Seagate ST1000LM035-1RK172 1TB     | 47        | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB       | 46        | 0.31%   |
| Samsung SSD 860 EVO 1TB            | 46        | 0.31%   |
| Samsung SSD 840 EVO 250GB          | 46        | 0.31%   |
| Toshiba DT01ACA100 1TB             | 45        | 0.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 44        | 0.29%   |
| Samsung SSD 840 EVO 120GB          | 42        | 0.28%   |
| PNY CS900 120GB SSD                | 42        | 0.28%   |
| Toshiba MQ01ABD100 1TB             | 41        | 0.27%   |
| Samsung SSD 970 EVO Plus 250GB     | 40        | 0.27%   |
| Kingston SKC600MS256G 256GB        | 40        | 0.27%   |
| Crucial CT1000MX500SSD1 1TB        | 40        | 0.27%   |
| A-DATA SU650 120GB                 | 40        | 0.27%   |
| Samsung SSD 850 EVO 120GB          | 39        | 0.26%   |
| WDC WD40EFRX-68N32N0 4TB           | 38        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 1298      | 3004   | 31.22%  |
| Seagate                                | 1282      | 2614   | 30.84%  |
| Toshiba                                | 458       | 854    | 11.02%  |
| Hitachi                                | 335       | 601    | 8.06%   |
| HGST                                   | 196       | 534    | 4.71%   |
| Samsung Electronics                    | 176       | 252    | 4.23%   |
| Hewlett-Packard                        | 102       | 311    | 2.45%   |
| NVMe                                   | 85        | 116    | 2.04%   |
| Maxtor                                 | 37        | 44     | 0.89%   |
| Fujitsu                                | 37        | 47     | 0.89%   |
| Apple                                  | 26        | 29     | 0.63%   |
| OPENBSD                                | 16        | 26     | 0.38%   |
| Dell                                   | 13        | 68     | 0.31%   |
| HPE                                    | 8         | 34     | 0.19%   |
| USB                                    | 5         | 5      | 0.12%   |
| Lexar                                  | 5         | 6      | 0.12%   |
| JetFlash                               | 5         | 5      | 0.12%   |
| HPT                                    | 5         | 44     | 0.12%   |
| Generic                                | 5         | 5      | 0.12%   |
| Adaptec                                | 4         | 14     | 0.1%    |
| NETAPP                                 | 3         | 6      | 0.07%   |
| LSILOGIC                               | 3         | 6      | 0.07%   |
| LSI                                    | 3         | 9      | 0.07%   |
| IBM/Hitachi                            | 3         | 3      | 0.07%   |
| China                                  | 3         | 3      | 0.07%   |
| WD MediaMax                            | 2         | 5      | 0.05%   |
| StoreJet                               | 2         | 2      | 0.05%   |
| QUANTUM                                | 2         | 3      | 0.05%   |
| Product:              USB Flash Memory | 2         | 2      | 0.05%   |
| Multiple                               | 2         | 2      | 0.05%   |
| MaxDigital                             | 2         | 2      | 0.05%   |
| Lenovo                                 | 2         | 4      | 0.05%   |
| IBM                                    | 2         | 2      | 0.05%   |
| General                                | 2         | 2      | 0.05%   |
| Cisco                                  | 2         | 4      | 0.05%   |
| ASMT                                   | 2         | 2      | 0.05%   |
| Areca                                  | 2         | 3      | 0.05%   |
| Verbatim                               | 1         | 1      | 0.02%   |
| UFD 2.0                                | 1         | 1      | 0.02%   |
| SYNOLOGY                               | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1352      | 2198   | 17.63%  |
| Kingston            | 932       | 1318   | 12.16%  |
| SanDisk             | 565       | 749    | 7.37%   |
| Crucial             | 565       | 862    | 7.37%   |
| Transcend           | 504       | 770    | 6.57%   |
| Intel               | 440       | 752    | 5.74%   |
| WDC                 | 263       | 395    | 3.43%   |
| China               | 241       | 338    | 3.14%   |
| A-DATA Technology   | 232       | 316    | 3.03%   |
| Hoodisk             | 229       | 343    | 2.99%   |
| Phison              | 121       | 161    | 1.58%   |
| Micron Technology   | 117       | 179    | 1.53%   |
| SPCC                | 105       | 166    | 1.37%   |
| PNY                 | 104       | 163    | 1.36%   |
| OCZ                 | 100       | 136    | 1.3%    |
| FORESEE             | 97        | 145    | 1.27%   |
| Toshiba             | 89        | 126    | 1.16%   |
| Protectli           | 87        | 134    | 1.13%   |
| Apacer              | 87        | 114    | 1.13%   |
| SK hynix            | 79        | 106    | 1.03%   |
| Intenso             | 68        | 110    | 0.89%   |
| Innodisk            | 68        | 87     | 0.89%   |
| Patriot             | 63        | 90     | 0.82%   |
| Dogfish             | 63        | 108    | 0.82%   |
| KingSpec            | 57        | 72     | 0.74%   |
| Corsair             | 55        | 78     | 0.72%   |
| LITEON              | 47        | 70     | 0.61%   |
| NVMe                | 46        | 54     | 0.6%    |
| Apple               | 43        | 48     | 0.56%   |
| BIWIN               | 42        | 66     | 0.55%   |
| LITEONIT            | 40        | 49     | 0.52%   |
| Plextor             | 30        | 39     | 0.39%   |
| GOODRAM             | 30        | 42     | 0.39%   |
| Gigabyte Technology | 30        | 42     | 0.39%   |
| Seagate             | 25        | 51     | 0.33%   |
| Kston               | 25        | 33     | 0.33%   |
| Hewlett-Packard     | 25        | 38     | 0.33%   |
| Team                | 24        | 43     | 0.31%   |
| Lexar               | 22        | 30     | 0.29%   |
| ShiJi               | 21        | 32     | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6958      | 11413  | 55.94%  |
| HDD  | 3450      | 8697   | 27.74%  |
| NVMe | 2031      | 3091   | 16.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9365      | 20110  | 82.18%  |
| NVMe | 2031      | 3091   | 17.82%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 8048      | 13315  | 74.39%  |
| 0.51-1.0        | 1581      | 2802   | 14.61%  |
| 1.01-2.0        | 552       | 1295   | 5.1%    |
| 3.01-4.0        | 248       | 932    | 2.29%   |
| 4.01-10.0       | 194       | 1027   | 1.79%   |
| 2.01-3.0        | 142       | 479    | 1.31%   |
| 10.01-20.0      | 47        | 250    | 0.43%   |
| More than 100.0 | 3         | 3      | 0.03%   |
| 20.01-50.0      | 3         | 6      | 0.03%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 4654      | 37.83%  |
| 251-500        | 2011      | 16.35%  |
| 1-20           | 1887      | 15.34%  |
| 51-100         | 1290      | 10.49%  |
| 21-50          | 1093      | 8.89%   |
| 501-1000       | 893       | 7.26%   |
| 1001-2000      | 237       | 1.93%   |
| More than 3000 | 115       | 0.93%   |
| Unknown        | 70        | 0.57%   |
| 2001-3000      | 51        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 10761     | 88.36%  |
| 21-50          | 710       | 5.83%   |
| 51-100         | 253       | 2.08%   |
| 101-250        | 181       | 1.49%   |
| 251-500        | 78        | 0.64%   |
| Unknown        | 70        | 0.57%   |
| 501-1000       | 55        | 0.45%   |
| More than 3000 | 29        | 0.24%   |
| 1001-2000      | 26        | 0.21%   |
| 2001-3000      | 14        | 0.11%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 30        | 47     | 1.64%   |
| Kingston SV300S37A120G 120GB        | 19        | 23     | 1.04%   |
| HGST HTS725050A7E630 500GB          | 18        | 34     | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 20     | 0.82%   |
| Seagate ST500LT012-9WS142 500GB     | 13        | 18     | 0.71%   |
| Seagate ST500LM021-1KJ152 500GB     | 13        | 13     | 0.71%   |
| Toshiba MQ01ABD100 1TB              | 12        | 13     | 0.66%   |
| Seagate ST3500418AS 500GB           | 12        | 21     | 0.66%   |
| Kingston SV300S37A60G 64GB          | 12        | 16     | 0.66%   |
| Kingston SMS200S3120G 120GB         | 12        | 13     | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB        | 11        | 18     | 0.6%    |
| Hitachi HTS541612J9SA00 120GB       | 11        | 12     | 0.6%    |
| Seagate ST9500420AS 500GB           | 10        | 13     | 0.55%   |
| Seagate ST9500325AS 500GB           | 10        | 13     | 0.55%   |
| Seagate ST500LT012-1DG142 500GB     | 10        | 11     | 0.55%   |
| WDC WD30EFRX-68EUZN0 3TB            | 9         | 26     | 0.49%   |
| Seagate ST3500413AS 500GB           | 9         | 23     | 0.49%   |
| Apacer 16GB SATA Flash Drive        | 9         | 14     | 0.49%   |
| Toshiba MQ01ABF050 500GB            | 8         | 10     | 0.44%   |
| Toshiba DT01ACA100 1TB              | 8         | 11     | 0.44%   |
| Seagate ST9320325AS 320GB           | 8         | 8      | 0.44%   |
| Samsung Electronics SSD 870 EVO 1TB | 8         | 12     | 0.44%   |
| Samsung Electronics HM160HI 160GB   | 8         | 9      | 0.44%   |
| Kingston SMS200S360G 64GB           | 8         | 8      | 0.44%   |
| Intel SSDSA2M080G2GC 80GB           | 8         | 9      | 0.44%   |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 7      | 0.38%   |
| SanDisk SSD PLUS 240GB              | 7         | 8      | 0.38%   |
| Samsung Electronics HD501LJ 500GB   | 7         | 9      | 0.38%   |
| Intel SSDSA2M160G2GC 160GB          | 7         | 9      | 0.38%   |
| Crucial CT525MX300SSD1 528GB        | 7         | 11     | 0.38%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 6         | 6      | 0.33%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 6         | 6      | 0.33%   |
| WDC WD40EFRX-68WT0N0 4TB            | 6         | 16     | 0.33%   |
| WDC WD20EFRX-68EUZN0 2TB            | 6         | 14     | 0.33%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 0.33%   |
| Seagate ST3160815AS 160GB           | 6         | 7      | 0.33%   |
| Kingston SA400S37240G 240GB         | 6         | 6      | 0.33%   |
| Intel SSDSC2CW120A3 120GB           | 6         | 7      | 0.33%   |
| Intel SSDSC2BF180A4L 180GB          | 6         | 6      | 0.33%   |
| Hitachi HTS545050B9A300 500GB       | 6         | 7      | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 388       | 564    | 22.03%  |
| WDC                 | 320       | 490    | 18.17%  |
| Hitachi             | 145       | 188    | 8.23%   |
| Samsung Electronics | 138       | 199    | 7.84%   |
| Toshiba             | 127       | 182    | 7.21%   |
| Kingston            | 107       | 132    | 6.08%   |
| Intel               | 102       | 133    | 5.79%   |
| HGST                | 55        | 100    | 3.12%   |
| Crucial             | 54        | 86     | 3.07%   |
| SanDisk             | 45        | 65     | 2.56%   |
| A-DATA Technology   | 27        | 39     | 1.53%   |
| Micron Technology   | 22        | 30     | 1.25%   |
| OCZ                 | 19        | 25     | 1.08%   |
| SK hynix            | 18        | 23     | 1.02%   |
| Maxtor              | 18        | 23     | 1.02%   |
| Apacer              | 16        | 21     | 0.91%   |
| Corsair             | 14        | 19     | 0.8%    |
| China               | 13        | 14     | 0.74%   |
| Apple               | 9         | 9      | 0.51%   |
| Hewlett-Packard     | 8         | 14     | 0.45%   |
| Transcend           | 7         | 12     | 0.4%    |
| LITEON              | 7         | 8      | 0.4%    |
| SPCC                | 6         | 8      | 0.34%   |
| Fujitsu             | 6         | 9      | 0.34%   |
| Dogfish             | 6         | 14     | 0.34%   |
| Patriot             | 5         | 5      | 0.28%   |
| HP Phison           | 5         | 5      | 0.28%   |
| SSSTC               | 4         | 5      | 0.23%   |
| Phison              | 4         | 4      | 0.23%   |
| VisionTek           | 3         | 7      | 0.17%   |
| Plextor             | 3         | 3      | 0.17%   |
| KingSpec            | 3         | 3      | 0.17%   |
| KingDian            | 3         | 5      | 0.17%   |
| Intenso             | 3         | 3      | 0.17%   |
| BIWIN               | 3         | 5      | 0.17%   |
| SMI                 | 2         | 2      | 0.11%   |
| PNY                 | 2         | 2      | 0.11%   |
| MyDigitalSSD        | 2         | 4      | 0.11%   |
| IBM/Hitachi         | 2         | 2      | 0.11%   |
| GLOWAY              | 2         | 3      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 387       | 563    | 34.52%  |
| WDC                  | 302       | 463    | 26.94%  |
| Hitachi              | 145       | 188    | 12.93%  |
| Toshiba              | 117       | 166    | 10.44%  |
| Samsung Electronics  | 71        | 93     | 6.33%   |
| HGST                 | 54        | 99     | 4.82%   |
| Maxtor               | 18        | 23     | 1.61%   |
| Hewlett-Packard      | 7         | 12     | 0.62%   |
| Fujitsu              | 6         | 9      | 0.54%   |
| Apple                | 6         | 6      | 0.54%   |
| IBM/Hitachi          | 2         | 2      | 0.18%   |
| WD MediaMax          | 1         | 3      | 0.09%   |
| InnoLite             | 1         | 1      | 0.09%   |
| HPE                  | 1         | 3      | 0.09%   |
| ExcelStor Technology | 1         | 2      | 0.09%   |
| China                | 1         | 1      | 0.09%   |
| Cactus               | 1         | 1      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1055      | 1635   | 62.35%  |
| SSD  | 614       | 852    | 36.29%  |
| NVMe | 23        | 31     | 1.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SanDisk pSSD 256GB                               | 5         | 5      | 9.09%   |
| Samsung Electronics MZYLN256HCHP-000L2 256GB     | 2         | 2      | 3.64%   |
| WDC WD7501AALS-00J7B0 752GB                      | 1         | 1      | 1.82%   |
| WDC WD6400AARS-00Y5B1 640GB                      | 1         | 2      | 1.82%   |
| WDC WD3200L 320GB                                | 1         | 1      | 1.82%   |
| WDC WD3200BPVT-16JJ5T0 320GB                     | 1         | 1      | 1.82%   |
| WDC WD3200AAJS-00YZCA0 320GB                     | 1         | 1      | 1.82%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 1.82%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 1.82%   |
| WDC WD10SPZX-00Z10T0 1TB                         | 1         | 1      | 1.82%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB             | 1         | 1      | 1.82%   |
| Transcend TS32GSSD370S 32GB                      | 1         | 2      | 1.82%   |
| Toshiba MG05ACA800E 8TB                          | 1         | 1      | 1.82%   |
| Supermicro SSD 16GB                              | 1         | 1      | 1.82%   |
| SK hynix SC308 SATA 256GB                        | 1         | 1      | 1.82%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 1.82%   |
| Seagate ST4000NM0025 4TB                         | 1         | 2      | 1.82%   |
| Seagate ST3500418AS 500GB                        | 1         | 2      | 1.82%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 1.82%   |
| Seagate ST3160318AS 160GB                        | 1         | 1      | 1.82%   |
| SanDisk SD9SN8W-256G-1006 256GB                  | 1         | 1      | 1.82%   |
| Samsung Electronics SSD PM830 2.5-inch 7mm 256GB | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 980 250GB                | 1         | 2      | 1.82%   |
| Samsung Electronics SSD 970 EVO Plus 500GB       | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 960 EVO 250GB            | 1         | 1      | 1.82%   |
| Samsung Electronics PM981 NVMe 256GB             | 1         | 1      | 1.82%   |
| Samsung Electronics MZVLW256HEHP-00000 256GB     | 1         | 1      | 1.82%   |
| Samsung Electronics MZALQ256HBJD-00BL2 256GB     | 1         | 1      | 1.82%   |
| Samsung Electronics HM500JJ 500GB                | 1         | 1      | 1.82%   |
| Samsung Electronics HM250JI 250GB                | 1         | 1      | 1.82%   |
| Samsung Electronics HD204UI 2TB                  | 1         | 2      | 1.82%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 2      | 1.82%   |
| Micron Technology 1100_MTFDDAV256TBN 64GB        | 1         | 1      | 1.82%   |
| Maxtor 6E040L0 40GB                              | 1         | 1      | 1.82%   |
| Kingston SV300S37A60G 64GB                       | 1         | 1      | 1.82%   |
| Kingston SMS200S360G 64GB                        | 1         | 1      | 1.82%   |
| Kingston SM2280S3120G 120GB                      | 1         | 1      | 1.82%   |
| Kingston SA2000M8500G 500GB                      | 1         | 2      | 1.82%   |
| Intel SSDSC2KB019T8 1.9TB                        | 1         | 2      | 1.82%   |
| Intel SSDSC2BW120H6 120GB                        | 1         | 1      | 1.82%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 23.64%  |
| WDC                 | 9         | 10     | 16.36%  |
| SanDisk             | 6         | 6      | 10.91%  |
| Seagate             | 4         | 6      | 7.27%   |
| Kingston            | 4         | 5      | 7.27%   |
| Intel               | 3         | 4      | 5.45%   |
| Hitachi             | 3         | 16     | 5.45%   |
| Crucial             | 3         | 3      | 5.45%   |
| SK hynix            | 2         | 2      | 3.64%   |
| Transcend           | 1         | 2      | 1.82%   |
| Toshiba             | 1         | 1      | 1.82%   |
| Supermicro          | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| Maxtor              | 1         | 1      | 1.82%   |
| HPE                 | 1         | 1      | 1.82%   |
| Hoodisk             | 1         | 1      | 1.82%   |
| HGST                | 1         | 1      | 1.82%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 9484      | 19745  | 81.58%  |
| Malfunc  | 1656      | 2518   | 14.24%  |
| Detected | 431       | 861    | 3.71%   |
| Failed   | 55        | 77     | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 8925      | 62.14%  |
| AMD                                     | 1880      | 13.09%  |
| Samsung Electronics                     | 776       | 5.4%    |
| Broadcom / LSI                          | 403       | 2.81%   |
| SanDisk                                 | 324       | 2.26%   |
| ASMedia Technology                      | 204       | 1.42%   |
| Silicon Motion                          | 193       | 1.34%   |
| Phison Electronics                      | 172       | 1.2%    |
| Kingston Technology Company             | 160       | 1.11%   |
| Marvell Technology Group                | 140       | 0.97%   |
| Micron/Crucial Technology               | 118       | 0.82%   |
| Nvidia                                  | 109       | 0.76%   |
| SK hynix                                | 98        | 0.68%   |
| Hewlett-Packard                         | 90        | 0.63%   |
| JMicron Technology                      | 75        | 0.52%   |
| Toshiba                                 | 65        | 0.45%   |
| MAXIO Technology (Hangzhou)             | 61        | 0.42%   |
| KIOXIA                                  | 56        | 0.39%   |
| Micron Technology                       | 54        | 0.38%   |
| ADATA Technology                        | 52        | 0.36%   |
| Transcend                               | 44        | 0.31%   |
| Chelsio Communications                  | 38        | 0.26%   |
| Adaptec                                 | 34        | 0.24%   |
| Realtek Semiconductor                   | 32        | 0.22%   |
| VIA Technologies                        | 30        | 0.21%   |
| Shenzhen Longsys Electronics            | 27        | 0.19%   |
| Silicon Image                           | 24        | 0.17%   |
| Seagate Technology                      | 19        | 0.13%   |
| Solid State Storage Technology          | 14        | 0.1%    |
| Silicon Integrated Systems [SiS]        | 14        | 0.1%    |
| Lite-On Technology                      | 10        | 0.07%   |
| Union Memory (Shenzhen)                 | 9         | 0.06%   |
| Lenovo                                  | 9         | 0.06%   |
| Biwin Storage Technology                | 9         | 0.06%   |
| Hosin Global Electronics                | 8         | 0.06%   |
| Areca Technology                        | 8         | 0.06%   |
| Shenzhen Unionmemory Information System | 7         | 0.05%   |
| Dell                                    | 7         | 0.05%   |
| Integrated Technology Express           | 6         | 0.04%   |
| HighPoint Technologies                  | 6         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1250      | 7.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 782       | 4.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 600       | 3.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 502       | 3.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 443       | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 420       | 2.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 388       | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 385       | 2.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 379       | 2.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 312       | 1.92%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 295       | 1.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 268       | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 258       | 1.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 242       | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 242       | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 239       | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 232       | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 227       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 214       | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 202       | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 184       | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                           | 183       | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 177       | 1.09%   |
| Intel SATA Controller [RAID mode]                                                | 176       | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 173       | 1.06%   |
| AMD FCH SATA Controller [IDE mode]                                               | 157       | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 154       | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 137       | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 133       | 0.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 131       | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 127       | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 126       | 0.77%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 117       | 0.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 114       | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 112       | 0.69%   |
| AMD 500 Series Chipset SATA Controller                                           | 109       | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 105       | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 104       | 0.64%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 101       | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 100       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 9650      | 66.56%  |
| NVMe | 2311      | 15.94%  |
| IDE  | 1451      | 10.01%  |
| RAID | 774       | 5.34%   |
| SAS  | 198       | 1.37%   |
| SCSI | 114       | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 9515      | 80.55%  |
| AMD                | 2111      | 17.87%  |
| ARM                | 130       | 1.1%    |
| Unknown            | 30        | 0.25%   |
| VIA                | 5         | 0.04%   |
| PowerPC            | 4         | 0.03%   |
| Rockchip           | 2         | 0.02%   |
| IBM                | 2         | 0.02%   |
| Broadcom           | 2         | 0.02%   |
| 11th               | 2         | 0.02%   |
| SUNW,UltraAX-i2    | 1         | 0.01%   |
| Sun                | 1         | 0.01%   |
| Research           | 1         | 0.01%   |
| NXP                | 1         | 0.01%   |
| Motorola           | 1         | 0.01%   |
| i                  | 1         | 0.01%   |
| Bochs              | 1         | 0.01%   |
| Baikal Electronics | 1         | 0.01%   |
| 7447A              | 1         | 0.01%   |
| 123456789ABC       | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 308       | 2.58%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 287       | 2.4%    |
| Intel Celeron N5105 @ 2.00GHz            | 242       | 2.03%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 200       | 1.68%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 184       | 1.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 107       | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 106       | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 85        | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 84        | 0.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz         | 74        | 0.62%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 74        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 67        | 0.56%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 64        | 0.54%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 64        | 0.54%   |
| Intel N100                               | 63        | 0.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 63        | 0.53%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 62        | 0.52%   |
| Intel Atom CPU D525 @ 1.80GHz            | 60        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz        | 58        | 0.49%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 58        | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 56        | 0.47%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 56        | 0.47%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 55        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 54        | 0.45%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 54        | 0.45%   |
| Intel Core 2 Duo                         | 53        | 0.44%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 52        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 52        | 0.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 52        | 0.44%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 52        | 0.44%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 49        | 0.41%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 49        | 0.41%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 47        | 0.39%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 46        | 0.39%   |
| ARM Cortex-A72 r0p3                      | 46        | 0.39%   |
| Intel CPU Version                        | 45        | 0.38%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 45        | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 44        | 0.37%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 43        | 0.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 43        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2255      | 18.98%  |
| Intel Celeron           | 1879      | 15.82%  |
| Intel Core i7           | 1197      | 10.08%  |
| Intel Xeon              | 1196      | 10.07%  |
| Intel Core i3           | 891       | 7.5%    |
| Other                   | 562       | 4.73%   |
| Intel Atom              | 534       | 4.49%   |
| AMD GX                  | 527       | 4.44%   |
| Intel Pentium           | 314       | 2.64%   |
| Intel Core 2 Duo        | 309       | 2.6%    |
| AMD Ryzen 5             | 275       | 2.31%   |
| AMD Ryzen 7             | 262       | 2.21%   |
| Intel Pentium Silver    | 127       | 1.07%   |
| ARM Cortex              | 120       | 1.01%   |
| AMD FX                  | 94        | 0.79%   |
| AMD Ryzen 3             | 81        | 0.68%   |
| Intel Core 2 Quad       | 79        | 0.66%   |
| AMD Ryzen 9             | 71        | 0.6%    |
| AMD EPYC                | 71        | 0.6%    |
| AMD G                   | 70        | 0.59%   |
| Intel Pentium Dual-Core | 68        | 0.57%   |
| AMD Ryzen Embedded      | 48        | 0.4%    |
| AMD Athlon              | 42        | 0.35%   |
| Intel Core 2            | 40        | 0.34%   |
| AMD Ryzen 5 PRO         | 35        | 0.29%   |
| AMD Phenom II X4        | 34        | 0.29%   |
| AMD A10                 | 34        | 0.29%   |
| Intel Pentium Gold      | 32        | 0.27%   |
| Intel Genuine           | 32        | 0.27%   |
| AMD A4                  | 32        | 0.27%   |
| Intel Xeon Silver       | 31        | 0.26%   |
| AMD A6                  | 30        | 0.25%   |
| Intel Pentium 4         | 29        | 0.24%   |
| Intel Core i9           | 29        | 0.24%   |
| AMD A8                  | 29        | 0.24%   |
| AMD E                   | 26        | 0.22%   |
| AMD Ryzen 7 PRO         | 25        | 0.21%   |
| Intel Pentium Dual      | 24        | 0.2%    |
| Intel Pentium M         | 22        | 0.19%   |
| AMD Opteron             | 22        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 5580      | 46.95%  |
| 2       | 3470      | 29.19%  |
| 8       | 646       | 5.43%   |
| Unknown | 615       | 5.17%   |
| 6       | 532       | 4.48%   |
| 16      | 335       | 2.82%   |
| 12      | 333       | 2.8%    |
| 1       | 165       | 1.39%   |
| 24      | 60        | 0.5%    |
| 10      | 41        | 0.34%   |
| 32      | 40        | 0.34%   |
| 20      | 20        | 0.17%   |
| 64      | 11        | 0.09%   |
| 3       | 8         | 0.07%   |
| 48      | 6         | 0.05%   |
| 14      | 6         | 0.05%   |
| 28      | 5         | 0.04%   |
| 36      | 4         | 0.03%   |
| 128     | 2         | 0.02%   |
| 40      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 22      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11116     | 94.12%  |
| 2       | 407       | 3.45%   |
| Unknown | 280       | 2.37%   |
| 4       | 5         | 0.04%   |
| 8       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6531      | 55.14%  |
| 2       | 4629      | 39.08%  |
| Unknown | 684       | 5.77%   |
| 4       | 1         | 0.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 1470      | 12.38%  |
| Haswell         | 1205      | 10.15%  |
| Unknown         | 923       | 7.77%   |
| Silvermont      | 901       | 7.59%   |
| IvyBridge       | 846       | 7.12%   |
| Skylake         | 736       | 6.2%    |
| SandyBridge     | 708       | 5.96%   |
| Goldmont plus   | 511       | 4.3%    |
| Penryn          | 442       | 3.72%   |
| Puma            | 402       | 3.39%   |
| Broadwell       | 380       | 3.2%    |
| Goldmont        | 330       | 2.78%   |
| Westmere        | 291       | 2.45%   |
| Zen 2           | 242       | 2.04%   |
| Core            | 241       | 2.03%   |
| Zen             | 233       | 1.96%   |
| Bonnell         | 223       | 1.88%   |
| Zen+            | 204       | 1.72%   |
| Jaguar          | 200       | 1.68%   |
| CometLake       | 191       | 1.61%   |
| Zen 3           | 186       | 1.57%   |
| Nehalem         | 164       | 1.38%   |
| Piledriver      | 129       | 1.09%   |
| TigerLake       | 125       | 1.05%   |
| K10             | 123       | 1.04%   |
| Bobcat          | 116       | 0.98%   |
| Steamroller     | 76        | 0.64%   |
| Excavator       | 59        | 0.5%    |
| NetBurst        | 52        | 0.44%   |
| K8 Hammer       | 44        | 0.37%   |
| P6              | 43        | 0.36%   |
| IceLake         | 34        | 0.29%   |
| Bulldozer       | 19        | 0.16%   |
| K10 Llano       | 15        | 0.13%   |
| Geode           | 6         | 0.05%   |
| K8 & K10 hybrid | 3         | 0.03%   |
| K6              | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 7276      | 62.1%   |
| AMD                                          | 1778      | 15.17%  |
| Nvidia                                       | 1440      | 12.29%  |
| Matrox Electronics Systems                   | 611       | 5.21%   |
| ASPEED Technology                            | 567       | 4.84%   |
| XGI Technology (eXtreme Graphics Innovation) | 10        | 0.09%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.09%   |
| VIA Technologies                             | 8         | 0.07%   |
| S3 Graphics                                  | 5         | 0.04%   |
| Silicon Motion                               | 3         | 0.03%   |
| Cirrus Logic                                 | 2         | 0.02%   |
| Tseng Labs                                   | 1         | 0.01%   |
| Trident Microsystems                         | 1         | 0.01%   |
| Red Hat                                      | 1         | 0.01%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| ATI                                          | 1         | 0.01%   |
| 3DLabs                                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 567       | 4.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 462       | 3.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 462       | 3.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 443       | 3.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 405       | 3.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 385       | 3.22%   |
| Intel JasperLake [UHD Graphics]                                                          | 346       | 2.9%    |
| Intel HD Graphics 530                                                                    | 313       | 2.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 287       | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 258       | 2.16%   |
| Intel HD Graphics 620                                                                    | 257       | 2.15%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 252       | 2.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 231       | 1.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 220       | 1.84%   |
| Intel HD Graphics 500                                                                    | 208       | 1.74%   |
| Intel UHD Graphics 620                                                                   | 197       | 1.65%   |
| Intel HD Graphics 5500                                                                   | 187       | 1.57%   |
| Intel HD Graphics 630                                                                    | 171       | 1.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 163       | 1.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 137       | 1.15%   |
| Matrox Electronics Systems G200eR2                                                       | 123       | 1.03%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 116       | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 114       | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 111       | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 110       | 0.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 106       | 0.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 106       | 0.89%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 100       | 0.84%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 96        | 0.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 93        | 0.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 93        | 0.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 92        | 0.77%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 90        | 0.75%   |
| AMD ES1000                                                                               | 90        | 0.75%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 85        | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 85        | 0.71%   |
| Matrox Electronics Systems MGA G200EH                                                    | 83        | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 83        | 0.69%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 82        | 0.69%   |
| Intel HD Graphics 610                                                                    | 73        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 6330      | 53.32%  |
| 1 x AMD                                  | 1570      | 13.22%  |
| 1 x Nvidia                               | 976       | 8.22%   |
| Other                                    | 762       | 6.42%   |
| 1 x Matrox                               | 605       | 5.1%    |
| 1 x ASPEED                               | 524       | 4.41%   |
| Intel + Nvidia                           | 400       | 3.37%   |
| 2 x Intel                                | 397       | 3.34%   |
| Intel + AMD                              | 122       | 1.03%   |
| 2 x AMD                                  | 40        | 0.34%   |
| AMD + Nvidia                             | 40        | 0.34%   |
| Intel + ASPEED                           | 26        | 0.22%   |
| Nvidia + ASPEED                          | 13        | 0.11%   |
| 1 x XGI                                  | 10        | 0.08%   |
| 1 x SiS                                  | 10        | 0.08%   |
| 2 x Nvidia                               | 9         | 0.08%   |
| 1 x VIA                                  | 8         | 0.07%   |
| 1 x S3 Graphics                          | 5         | 0.04%   |
| AMD + ASPEED                             | 5         | 0.04%   |
| 1 x Silicon Motion                       | 3         | 0.03%   |
| Intel + Matrox                           | 2         | 0.02%   |
| Intel + AMD + 1 x Nvidia                 | 2         | 0.02%   |
| 1 x Cirrus Logic                         | 2         | 0.02%   |
| AMD + Matrox                             | 2         | 0.02%   |
| 2 x Intel + 1 x Nvidia                   | 1         | 0.01%   |
| 1 x Tseng Labs                           | 1         | 0.01%   |
| 1 x Trident Microsystems                 | 1         | 0.01%   |
| 1 x Red Hat                              | 1         | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.01%   |
| Nvidia + Matrox                          | 1         | 0.01%   |
| Nvidia + Huawei Technologies             | 1         | 0.01%   |
| Intel + 2 x AMD                          | 1         | 0.01%   |
| 1 x 3DLabs                               | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 10213     | 86.1%   |
| Unknown     | 927       | 7.81%   |
| Proprietary | 722       | 6.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10651     | 89.5%   |
| 1.01-2.0   | 311       | 2.61%   |
| 0.01-0.5   | 284       | 2.39%   |
| 0.51-1.0   | 204       | 1.71%   |
| 3.01-4.0   | 188       | 1.58%   |
| 7.01-8.0   | 132       | 1.11%   |
| 5.01-6.0   | 79        | 0.66%   |
| 2.01-3.0   | 26        | 0.22%   |
| 8.01-16.0  | 25        | 0.21%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 380       | 11.09%  |
| Samsung Electronics     | 371       | 10.82%  |
| LG Display              | 354       | 10.33%  |
| Chimei Innolux          | 241       | 7.03%   |
| Dell                    | 236       | 6.88%   |
| BOE                     | 224       | 6.53%   |
| Goldstar                | 183       | 5.34%   |
| Lenovo                  | 142       | 4.14%   |
| Acer                    | 118       | 3.44%   |
| Hewlett-Packard         | 110       | 3.21%   |
| BenQ                    | 94        | 2.74%   |
| Philips                 | 87        | 2.54%   |
| Apple                   | 87        | 2.54%   |
| AOC                     | 84        | 2.45%   |
| Ancor Communications    | 68        | 1.98%   |
| ViewSonic               | 45        | 1.31%   |
| Sharp                   | 45        | 1.31%   |
| Iiyama                  | 45        | 1.31%   |
| Chi Mei Optoelectronics | 42        | 1.23%   |
| LG Electronics          | 30        | 0.88%   |
| InfoVision              | 29        | 0.85%   |
| ASUSTek Computer        | 27        | 0.79%   |
| Sony                    | 21        | 0.61%   |
| NEC Computers           | 21        | 0.61%   |
| Fujitsu Siemens         | 19        | 0.55%   |
| Eizo                    | 19        | 0.55%   |
| PANDA                   | 17        | 0.5%    |
| LG Philips              | 16        | 0.47%   |
| HannStar                | 16        | 0.47%   |
| MSI                     | 13        | 0.38%   |
| Toshiba                 | 12        | 0.35%   |
| Idek Iiyama             | 11        | 0.32%   |
| CSO                     | 11        | 0.32%   |
| Unknown                 | 11        | 0.32%   |
| Vizio                   | 10        | 0.29%   |
| Unknown                 | 9         | 0.26%   |
| Panasonic               | 9         | 0.26%   |
| LGD                     | 9         | 0.26%   |
| Sceptre Tech            | 8         | 0.23%   |
| Lenovo Group Limited    | 7         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 24        | 0.68%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 17        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 13        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 12        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 12        | 0.34%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 11        | 0.31%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 11        | 0.31%   |
| Unknown                                                                  | 11        | 0.31%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 10        | 0.28%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 10        | 0.28%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 9         | 0.25%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 9         | 0.25%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 9         | 0.25%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                        | 9         | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 9         | 0.25%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 9         | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 9         | 0.25%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 9         | 0.25%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 9         | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 8         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 8         | 0.23%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 8         | 0.23%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 8         | 0.23%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 8         | 0.23%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 8         | 0.23%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 8         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 8         | 0.23%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 7         | 0.2%    |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 7         | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 7         | 0.2%    |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 7         | 0.2%    |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 7         | 0.2%    |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 7         | 0.2%    |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch               | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch         | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 7         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 7         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1348      | 40.07%  |
| 1366x768 (WXGA)    | 679       | 20.18%  |
| 2560x1440 (QHD)    | 176       | 5.23%   |
| 3840x2160 (4K)     | 172       | 5.11%   |
| 1600x900 (HD+)     | 149       | 4.43%   |
| 1280x1024 (SXGA)   | 128       | 3.8%    |
| 1280x800 (WXGA)    | 115       | 3.42%   |
| 1920x1200 (WUXGA)  | 99        | 2.94%   |
| 1440x900 (WXGA+)   | 85        | 2.53%   |
| 1680x1050 (WSXGA+) | 82        | 2.44%   |
| 2560x1080          | 36        | 1.07%   |
| 1024x600           | 34        | 1.01%   |
| Unknown            | 34        | 1.01%   |
| 3440x1440          | 33        | 0.98%   |
| 1024x768 (XGA)     | 20        | 0.59%   |
| 2560x1600          | 19        | 0.56%   |
| 1360x768           | 15        | 0.45%   |
| 3840x1080          | 11        | 0.33%   |
| 3200x1800 (QHD+)   | 11        | 0.33%   |
| 1920x540           | 11        | 0.33%   |
| 1600x1200          | 11        | 0.33%   |
| 2880x1800          | 9         | 0.27%   |
| 2256x1504          | 8         | 0.24%   |
| 2880x1620          | 7         | 0.21%   |
| 3840x1600          | 4         | 0.12%   |
| 2160x1440          | 4         | 0.12%   |
| 1400x1050          | 4         | 0.12%   |
| 5760x2160          | 3         | 0.09%   |
| 3840x1200          | 3         | 0.09%   |
| 3000x2000          | 3         | 0.09%   |
| 2736x1824          | 3         | 0.09%   |
| 2048x1152          | 3         | 0.09%   |
| 5760x1080          | 2         | 0.06%   |
| 3840x2400          | 2         | 0.06%   |
| 3520x1080          | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 9600x2160          | 1         | 0.03%   |
| 7680x2160          | 1         | 0.03%   |
| 720x1280           | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 655       | 19.14%  |
| 13      | 609       | 17.8%   |
| 24      | 283       | 8.27%   |
| 27      | 251       | 7.33%   |
| Unknown | 215       | 6.28%   |
| 21      | 211       | 6.17%   |
| 23      | 175       | 5.11%   |
| 12      | 175       | 5.11%   |
| 19      | 149       | 4.35%   |
| 17      | 130       | 3.8%    |
| 14      | 83        | 2.43%   |
| 11      | 71        | 2.07%   |
| 31      | 69        | 2.02%   |
| 18      | 57        | 1.67%   |
| 34      | 46        | 1.34%   |
| 22      | 44        | 1.29%   |
| 10      | 33        | 0.96%   |
| 20      | 31        | 0.91%   |
| 40      | 11        | 0.32%   |
| 29      | 11        | 0.32%   |
| 16      | 9         | 0.26%   |
| 9       | 9         | 0.26%   |
| 42      | 8         | 0.23%   |
| 54      | 7         | 0.2%    |
| 26      | 7         | 0.2%    |
| 25      | 7         | 0.2%    |
| 64      | 6         | 0.18%   |
| 52      | 6         | 0.18%   |
| 39      | 5         | 0.15%   |
| 32      | 5         | 0.15%   |
| 28      | 5         | 0.15%   |
| 46      | 4         | 0.12%   |
| 33      | 4         | 0.12%   |
| 50      | 3         | 0.09%   |
| 49      | 3         | 0.09%   |
| 48      | 3         | 0.09%   |
| 43      | 3         | 0.09%   |
| 41      | 3         | 0.09%   |
| 37      | 3         | 0.09%   |
| 35      | 3         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1157      | 34.19%  |
| 501-600     | 670       | 19.8%   |
| 201-300     | 534       | 15.78%  |
| 401-500     | 421       | 12.44%  |
| Unknown     | 215       | 6.35%   |
| 351-400     | 141       | 4.17%   |
| 601-700     | 110       | 3.25%   |
| 701-800     | 56        | 1.65%   |
| 1001-1500   | 36        | 1.06%   |
| 801-900     | 21        | 0.62%   |
| 901-1000    | 15        | 0.44%   |
| 101-200     | 6         | 0.18%   |
| 1501-2000   | 1         | 0.03%   |
| 1-100       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2362      | 73.42%  |
| 16/10   | 381       | 11.84%  |
| Unknown | 187       | 5.81%   |
| 5/4     | 113       | 3.51%   |
| 21/9    | 64        | 1.99%   |
| 3/2     | 53        | 1.65%   |
| 4/3     | 42        | 1.31%   |
| 6/5     | 5         | 0.16%   |
| 32/9    | 5         | 0.16%   |
| 3.18    | 1         | 0.03%   |
| 11/10   | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.46    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 603       | 17.76%  |
| 81-90          | 565       | 16.64%  |
| 91-100         | 509       | 14.99%  |
| 301-350        | 262       | 7.71%   |
| Unknown        | 215       | 6.33%   |
| 151-200        | 195       | 5.74%   |
| 61-70          | 174       | 5.12%   |
| 101-110        | 158       | 4.65%   |
| 351-500        | 134       | 3.95%   |
| 71-80          | 105       | 3.09%   |
| 141-150        | 104       | 3.06%   |
| 251-300        | 92        | 2.71%   |
| 121-130        | 72        | 2.12%   |
| 51-60          | 70        | 2.06%   |
| 501-1000       | 43        | 1.27%   |
| 41-50          | 37        | 1.09%   |
| More than 1000 | 28        | 0.82%   |
| 111-120        | 15        | 0.44%   |
| 131-140        | 9         | 0.27%   |
| 1-40           | 6         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1066      | 31.78%  |
| 101-120       | 883       | 26.33%  |
| 121-160       | 872       | 26%     |
| 161-240       | 232       | 6.92%   |
| Unknown       | 215       | 6.41%   |
| More than 240 | 62        | 1.85%   |
| 1-50          | 24        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8286      | 69.47%  |
| 1     | 3284      | 27.53%  |
| 2     | 334       | 2.8%    |
| 3     | 23        | 0.19%   |
| 4     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 8491      | 51.49%  |
| Realtek Semiconductor             | 4223      | 25.61%  |
| Broadcom                          | 1159      | 7.03%   |
| Qualcomm Atheros                  | 997       | 6.05%   |
| Marvell Technology Group          | 111       | 0.67%   |
| Ralink Technology                 | 107       | 0.65%   |
| Mellanox Technologies             | 105       | 0.64%   |
| TP-Link                           | 89        | 0.54%   |
| AMD                               | 79        | 0.48%   |
| IMC Networks                      | 70        | 0.42%   |
| Ralink                            | 67        | 0.41%   |
| Nvidia                            | 52        | 0.32%   |
| D-Link System                     | 52        | 0.32%   |
| Chelsio Communications            | 51        | 0.31%   |
| MediaTek                          | 48        | 0.29%   |
| Samsung Electronics               | 45        | 0.27%   |
| Edimax Technology                 | 43        | 0.26%   |
| Sierra Wireless                   | 35        | 0.21%   |
| Ericsson Business Mobile Networks | 35        | 0.21%   |
| U-Blox                            | 34        | 0.21%   |
| Aquantia                          | 31        | 0.19%   |
| Huawei Technologies               | 26        | 0.16%   |
| Qualcomm Atheros Communications   | 25        | 0.15%   |
| Dell                              | 25        | 0.15%   |
| Xiaomi                            | 24        | 0.15%   |
| VIA Technologies                  | 23        | 0.14%   |
| Solarflare Communications         | 23        | 0.14%   |
| American Megatrends               | 22        | 0.13%   |
| Google                            | 20        | 0.12%   |
| Emulex                            | 19        | 0.12%   |
| Apple                             | 19        | 0.12%   |
| ASUSTek Computer                  | 18        | 0.11%   |
| QLogic                            | 17        | 0.1%    |
| 3Com                              | 16        | 0.1%    |
| IBM                               | 15        | 0.09%   |
| Hewlett-Packard                   | 14        | 0.08%   |
| D-Link                            | 14        | 0.08%   |
| NetGear                           | 12        | 0.07%   |
| JMicron Technology                | 12        | 0.07%   |
| ZTE WCDMA Technologies MSM        | 11        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3405      | 16.61%  |
| Intel I211 Gigabit Network Connection                                         | 1330      | 6.49%   |
| Intel I210 Gigabit Network Connection                                         | 904       | 4.41%   |
| Intel I350 Gigabit Network Connection                                         | 619       | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 574       | 2.8%    |
| Intel 82574L Gigabit Network Connection                                       | 498       | 2.43%   |
| Intel Ethernet Controller I225-V                                              | 461       | 2.25%   |
| Intel Ethernet Controller I226-V                                              | 343       | 1.67%   |
| Intel Ethernet Connection I217-LM                                             | 319       | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 280       | 1.37%   |
| Intel 82576 Gigabit Network Connection                                        | 247       | 1.2%    |
| Intel 82583V Gigabit Network Connection                                       | 241       | 1.18%   |
| Intel Wi-Fi 6 AX200                                                           | 233       | 1.14%   |
| Intel Wireless 8265 / 8275                                                    | 226       | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                             | 225       | 1.1%    |
| Intel 82580 Gigabit Network Connection                                        | 212       | 1.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 209       | 1.02%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 208       | 1.01%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 200       | 0.98%   |
| Intel Wireless 7265                                                           | 197       | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                                         | 184       | 0.9%    |
| Intel Wireless 7260                                                           | 173       | 0.84%   |
| Intel Wireless 8260                                                           | 166       | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 166       | 0.81%   |
| Intel Wireless 3165                                                           | 154       | 0.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 145       | 0.71%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 129       | 0.63%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 129       | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                          | 126       | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 118       | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 114       | 0.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 111       | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 104       | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 103       | 0.5%    |
| Intel Ethernet Connection I354                                                | 101       | 0.49%   |
| Intel Ethernet Connection (7) I219-V                                          | 98        | 0.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 97        | 0.47%   |
| Intel Ethernet Connection I219-LM                                             | 95        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                         | 94        | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 93        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2511      | 51.6%   |
| Qualcomm Atheros                      | 818       | 16.81%  |
| Realtek Semiconductor                 | 621       | 12.76%  |
| Broadcom                              | 351       | 7.21%   |
| Ralink Technology                     | 107       | 2.2%    |
| TP-Link                               | 88        | 1.81%   |
| IMC Networks                          | 70        | 1.44%   |
| Ralink                                | 67        | 1.38%   |
| Edimax Technology                     | 43        | 0.88%   |
| MediaTek                              | 42        | 0.86%   |
| Sierra Wireless                       | 26        | 0.53%   |
| Qualcomm Atheros Communications       | 25        | 0.51%   |
| ASUSTek Computer                      | 18        | 0.37%   |
| D-Link                                | 14        | 0.29%   |
| NetGear                               | 12        | 0.25%   |
| D-Link System                         | 12        | 0.25%   |
| Dell                                  | 8         | 0.16%   |
| Mercucys                              | 4         | 0.08%   |
| Belkin Components                     | 4         | 0.08%   |
| Atheros                               | 4         | 0.08%   |
| AboCom Systems                        | 3         | 0.06%   |
| Qualcomm Technologies                 | 2         | 0.04%   |
| Marvell Technology Group              | 2         | 0.04%   |
| Linksys                               | 2         | 0.04%   |
| BUFFALO                               | 2         | 0.04%   |
| Accton Technology                     | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Qcom                                  | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Gemtek                                | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 233       | 4.74%   |
| Intel Wireless 8265 / 8275                                              | 226       | 4.59%   |
| Intel Wireless 7265                                                     | 197       | 4%      |
| Intel Wireless 7260                                                     | 173       | 3.52%   |
| Intel Wireless 8260                                                     | 166       | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 166       | 3.37%   |
| Intel Wireless 3165                                                     | 154       | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 118       | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 2.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 111       | 2.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 104       | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 103       | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 97        | 1.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 93        | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 81        | 1.65%   |
| Intel Wireless 3160                                                     | 75        | 1.52%   |
| Intel Wi-Fi 6 AX201                                                     | 75        | 1.52%   |
| Intel Wireless-AC 9260                                                  | 71        | 1.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 68        | 1.38%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 66        | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 65        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 65        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 65        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 1.32%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 54        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 52        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 46        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                          | 44        | 0.89%   |
| Intel Centrino Advanced-N 6235                                          | 43        | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 42        | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 41        | 0.83%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 41        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 40        | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 40        | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 40        | 0.81%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 40        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 40        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 39        | 0.79%   |
| Intel Centrino Ultimate-N 6300                                          | 39        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7289      | 55.7%   |
| Realtek Semiconductor            | 3950      | 30.18%  |
| Broadcom                         | 899       | 6.87%   |
| Qualcomm Atheros                 | 257       | 1.96%   |
| Marvell Technology Group         | 107       | 0.82%   |
| AMD                              | 78        | 0.6%    |
| Nvidia                           | 52        | 0.4%    |
| Samsung Electronics              | 45        | 0.34%   |
| Chelsio Communications           | 38        | 0.29%   |
| D-Link System                    | 37        | 0.28%   |
| Aquantia                         | 30        | 0.23%   |
| Xiaomi                           | 24        | 0.18%   |
| VIA Technologies                 | 23        | 0.18%   |
| Solarflare Communications        | 23        | 0.18%   |
| American Megatrends              | 22        | 0.17%   |
| QLogic                           | 17        | 0.13%   |
| Emulex                           | 17        | 0.13%   |
| Apple                            | 17        | 0.13%   |
| 3Com                             | 14        | 0.11%   |
| JMicron Technology               | 12        | 0.09%   |
| Google                           | 12        | 0.09%   |
| Huawei Technologies              | 11        | 0.08%   |
| Qualcomm                         | 10        | 0.08%   |
| ICS Advent                       | 9         | 0.07%   |
| Silicon Integrated Systems [SiS] | 8         | 0.06%   |
| Novatel Wireless                 | 7         | 0.05%   |
| Insyde Software                  | 7         | 0.05%   |
| MediaTek                         | 6         | 0.05%   |
| National Semiconductor           | 4         | 0.03%   |
| Microsoft                        | 4         | 0.03%   |
| Davicom Semiconductor            | 4         | 0.03%   |
| Silicom                          | 3         | 0.02%   |
| OPPO Electronics                 | 3         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 3         | 0.02%   |
| MYRICOM                          | 3         | 0.02%   |
| Cisco Systems                    | 3         | 0.02%   |
| ADMtek                           | 3         | 0.02%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.02%   |
| TRENDnet                         | 2         | 0.02%   |
| Tehuti Networks                  | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3405      | 22.5%   |
| Intel I211 Gigabit Network Connection                                         | 1330      | 8.79%   |
| Intel I210 Gigabit Network Connection                                         | 904       | 5.97%   |
| Intel I350 Gigabit Network Connection                                         | 619       | 4.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 574       | 3.79%   |
| Intel 82574L Gigabit Network Connection                                       | 498       | 3.29%   |
| Intel Ethernet Controller I225-V                                              | 461       | 3.05%   |
| Intel Ethernet Controller I226-V                                              | 343       | 2.27%   |
| Intel Ethernet Connection I217-LM                                             | 319       | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 280       | 1.85%   |
| Intel 82576 Gigabit Network Connection                                        | 247       | 1.63%   |
| Intel 82583V Gigabit Network Connection                                       | 241       | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                             | 215       | 1.42%   |
| Intel 82580 Gigabit Network Connection                                        | 212       | 1.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 209       | 1.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 208       | 1.37%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 200       | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                                         | 184       | 1.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 145       | 0.96%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 129       | 0.85%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 129       | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                          | 126       | 0.83%   |
| Intel Ethernet Connection I354                                                | 101       | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                          | 98        | 0.65%   |
| Intel Ethernet Connection I219-LM                                             | 95        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                         | 94        | 0.62%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 85        | 0.56%   |
| Intel Ethernet Connection X553 1GbE                                           | 81        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 78        | 0.52%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 78        | 0.52%   |
| AMD XGMAC 10GbE Controller                                                    | 77        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                       | 75        | 0.5%    |
| Intel Ethernet Controller X550                                                | 72        | 0.48%   |
| Intel Ethernet Connection I217-V                                              | 67        | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                                         | 67        | 0.44%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 62        | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                                         | 58        | 0.38%   |
| Intel Ethernet Connection (5) I219-LM                                         | 57        | 0.38%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 56        | 0.37%   |
| Intel 82577LM Gigabit Network Connection                                      | 56        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 11203     | 69.36%  |
| WiFi     | 4506      | 27.9%   |
| Unknown  | 281       | 1.74%   |
| Modem    | 161       | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10279     | 83.13%  |
| WiFi     | 2048      | 16.56%  |
| Unknown  | 25        | 0.2%    |
| Modem    | 13        | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3983      | 33.29%  |
| 1     | 1995      | 16.67%  |
| 4     | 1967      | 16.44%  |
| 3     | 1509      | 12.61%  |
| 6     | 958       | 8.01%   |
| 5     | 732       | 6.12%   |
| 8     | 250       | 2.09%   |
| 0     | 192       | 1.6%    |
| 7     | 152       | 1.27%   |
| 10    | 79        | 0.66%   |
| 9     | 75        | 0.63%   |
| 12    | 24        | 0.2%    |
| 14    | 12        | 0.1%    |
| 13    | 11        | 0.09%   |
| 11    | 10        | 0.08%   |
| 15    | 6         | 0.05%   |
| 16    | 5         | 0.04%   |
| 20    | 4         | 0.03%   |
| 17    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10347     | 85.03%  |
| Yes  | 1821      | 14.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1785      | 57.16%  |
| Broadcom                        | 206       | 6.6%    |
| Realtek Semiconductor           | 200       | 6.4%    |
| Apple                           | 177       | 5.67%   |
| Qualcomm Atheros Communications | 174       | 5.57%   |
| IMC Networks                    | 139       | 4.45%   |
| Cambridge Silicon Radio         | 113       | 3.62%   |
| Foxconn / Hon Hai               | 65        | 2.08%   |
| Lite-On Technology              | 64        | 2.05%   |
| ASUSTek Computer                | 53        | 1.7%    |
| Dell                            | 36        | 1.15%   |
| Hewlett-Packard                 | 29        | 0.93%   |
| Alps Electric                   | 18        | 0.58%   |
| MediaTek                        | 16        | 0.51%   |
| Ralink                          | 11        | 0.35%   |
| Skylight Digital                | 6         | 0.19%   |
| TP-Link                         | 5         | 0.16%   |
| Toshiba                         | 3         | 0.1%    |
| Integrated System Solution      | 3         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.06%   |
| HTC (High Tech Computer)        | 2         | 0.06%   |
| Fujitsu                         | 2         | 0.06%   |
| Creative Technology             | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Silicon Wave                    | 1         | 0.03%   |
| Ralink Technology               | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Primax Electronics              | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Esel International              | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 801       | 25.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 232       | 7.41%   |
| Intel AX200 Bluetooth                                       | 223       | 7.12%   |
| Intel AX201 Bluetooth                                       | 215       | 6.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 113       | 3.61%   |
| Intel Wireless-AC 3168 Bluetooth                            | 94        | 3%      |
| Apple Bluetooth Host Controller                             | 90        | 2.87%   |
| Realtek Bluetooth Adapter                                   | 89        | 2.84%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 73        | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 63        | 2.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 60        | 1.92%   |
| Intel AX210 Bluetooth                                       | 59        | 1.88%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 54        | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 42        | 1.34%   |
| Realtek  Bluetooth 4.2 Adapter                              | 36        | 1.15%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 36        | 1.15%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 35        | 1.12%   |
| IMC Networks Realtek Bluetooth Adapter                      | 34        | 1.09%   |
| Apple Broadcom Built-in Bluetooth                           | 28        | 0.89%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 26        | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 22        | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                            | 21        | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 20        | 0.64%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 19        | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 18        | 0.57%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 18        | 0.57%   |
| Realtek Bluetooth 4.0 Adapter                               | 17        | 0.54%   |
| Intel AX211 Bluetooth                                       | 17        | 0.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 17        | 0.54%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 17        | 0.54%   |
| Apple Built-in iSight (no firmware loaded)                  | 16        | 0.51%   |
| MediaTek RZ608 Bluetooth Adapter                            | 15        | 0.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 15        | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 15        | 0.48%   |
| Dell DW375 Bluetooth Module                                 | 14        | 0.45%   |
| Realtek Bluetooth 4.2 Adapter                               | 13        | 0.42%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 13        | 0.42%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 12        | 0.38%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 12        | 0.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 12        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 7158      | 67.45%  |
| AMD                                          | 1871      | 17.63%  |
| Nvidia                                       | 1023      | 9.64%   |
| C-Media Electronics                          | 110       | 1.04%   |
| Logitech                                     | 37        | 0.35%   |
| Creative Labs                                | 33        | 0.31%   |
| Texas Instruments                            | 32        | 0.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 23        | 0.22%   |
| Realtek Semiconductor                        | 19        | 0.18%   |
| Lenovo                                       | 17        | 0.16%   |
| GN Netcom                                    | 17        | 0.16%   |
| VIA Technologies                             | 16        | 0.15%   |
| JMTek                                        | 14        | 0.13%   |
| Generalplus Technology                       | 14        | 0.13%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.12%   |
| SteelSeries ApS                              | 12        | 0.11%   |
| Creative Technology                          | 11        | 0.1%    |
| KTMicro                                      | 9         | 0.08%   |
| Kingston Technology                          | 9         | 0.08%   |
| ASUSTek Computer                             | 9         | 0.08%   |
| BEHRINGER International                      | 8         | 0.08%   |
| Focusrite-Novation                           | 7         | 0.07%   |
| Yamaha                                       | 6         | 0.06%   |
| Sony                                         | 6         | 0.06%   |
| Plantronics                                  | 6         | 0.06%   |
| ESS Technology                               | 6         | 0.06%   |
| Corsair                                      | 6         | 0.06%   |
| Blue Microphones                             | 6         | 0.06%   |
| Hewlett-Packard                              | 5         | 0.05%   |
| Cambridge Silicon Radio                      | 5         | 0.05%   |
| XMOS                                         | 4         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.04%   |
| Tenx Technology                              | 4         | 0.04%   |
| Razer USA                                    | 4         | 0.04%   |
| ULi Electronics                              | 3         | 0.03%   |
| RODE Microphones                             | 3         | 0.03%   |
| MosArt Semiconductor                         | 3         | 0.03%   |
| M-Audio                                      | 3         | 0.03%   |
| FiiO Electronics Technology                  | 3         | 0.03%   |
| DSEA A/S                                     | 3         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 610       | 4.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 586       | 4.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 568       | 4.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 536       | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 515       | 4.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 461       | 3.64%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 446       | 3.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 358       | 2.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 353       | 2.79%   |
| AMD FCH Azalia Controller                                                                         | 347       | 2.74%   |
| Intel Jasper Lake HD Audio                                                                        | 343       | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 286       | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 282       | 2.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 274       | 2.16%   |
| Intel 8 Series HD Audio Controller                                                                | 265       | 2.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 263       | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 248       | 1.96%   |
| Intel Broadwell-U Audio Controller                                                                | 246       | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 241       | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 222       | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 215       | 1.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 210       | 1.66%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 200       | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 178       | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 174       | 1.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 174       | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 166       | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 163       | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 131       | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 129       | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 122       | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 118       | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 109       | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 95        | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 87        | 0.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 76        | 0.6%    |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 72        | 0.57%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 71        | 0.56%   |
| Nvidia High Definition Audio Controller                                                           | 67        | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 64        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 2278      | 18.47%  |
| SK hynix                                | 1692      | 13.72%  |
| Kingston                                | 1475      | 11.96%  |
| Unknown                                 | 1350      | 10.94%  |
| Micron Technology                       | 1077      | 8.73%   |
| Crucial                                 | 1053      | 8.54%   |
| Corsair                                 | 530       | 4.3%    |
| G.Skill                                 | 389       | 3.15%   |
| Unknown                                 | 365       | 2.96%   |
| Transcend                               | 217       | 1.76%   |
| A-DATA Technology                       | 196       | 1.59%   |
| Unknown (ABCD)                          | 173       | 1.4%    |
| Ramaxel Technology                      | 160       | 1.3%    |
| Nanya Technology                        | 139       | 1.13%   |
| Team                                    | 112       | 0.91%   |
| Elpida                                  | 106       | 0.86%   |
| Patriot                                 | 90        | 0.73%   |
| Apacer                                  | 59        | 0.48%   |
| Kimtigo                                 | 57        | 0.46%   |
| Hewlett-Packard                         | 52        | 0.42%   |
| Smart                                   | 45        | 0.36%   |
| Toshiba                                 | 41        | 0.33%   |
| GOODRAM                                 | 36        | 0.29%   |
| PNY                                     | 32        | 0.26%   |
| Avant                                   | 29        | 0.24%   |
| ATP                                     | 29        | 0.24%   |
| TIMETEC                                 | 28        | 0.23%   |
| Teikon                                  | 23        | 0.19%   |
| Silicon Power                           | 18        | 0.15%   |
| AMD                                     | 17        | 0.14%   |
| Innodisk                                | 16        | 0.13%   |
| Unknown (AB)                            | 14        | 0.11%   |
| Super Talent                            | 14        | 0.11%   |
| Patriot Memory (PDP Systems)            | 13        | 0.11%   |
| HPE                                     | 13        | 0.11%   |
| GeIL                                    | 13        | 0.11%   |
| Tigo                                    | 12        | 0.1%    |
| SK_Hynix                                | 12        | 0.1%    |
| Silicon Power Computer & Communications | 10        | 0.08%   |
| 48spaces                                | 10        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 365       | 2.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 159       | 1.21%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 156       | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 103       | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 96        | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 68        | 0.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 65        | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 63        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 57        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 57        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 54        | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 54        | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 52        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 50        | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 48        | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 48        | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 44        | 0.33%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 44        | 0.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 43        | 0.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s          | 41        | 0.31%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 40        | 0.3%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 39        | 0.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 38        | 0.29%   |
| Unknown RAM Module 8GB 1600MT/s                                | 37        | 0.28%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 36        | 0.27%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 36        | 0.27%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 35        | 0.27%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 35        | 0.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 35        | 0.27%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 34        | 0.26%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 33        | 0.25%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 33        | 0.25%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 33        | 0.25%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 32        | 0.24%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 32        | 0.24%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 32        | 0.24%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 32        | 0.24%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 32        | 0.24%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 31        | 0.23%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 31        | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 5047      | 46.6%   |
| DDR4            | 4209      | 38.86%  |
| DDR2            | 546       | 5.04%   |
| Unknown         | 308       | 2.84%   |
| LPDDR4          | 276       | 2.55%   |
| SDRAM           | 142       | 1.31%   |
| DDR5            | 97        | 0.9%    |
| LPDDR3          | 87        | 0.8%    |
| DDR             | 69        | 0.64%   |
| LPDDR5          | 23        | 0.21%   |
| DRAM            | 18        | 0.17%   |
| RAM             | 5         | 0.05%   |
| SRAM            | 1         | 0.01%   |
| Logical non-vol | 1         | 0.01%   |
| DDR2 FB-DIMM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 5406      | 50.07%  |
| SODIMM       | 4982      | 46.14%  |
| Row Of Chips | 209       | 1.94%   |
| Unknown      | 90        | 0.83%   |
| Chip         | 65        | 0.6%    |
| FB-DIMM      | 32        | 0.3%    |
| RIMM         | 13        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 4227      | 36.21%  |
| 4096   | 3697      | 31.67%  |
| 2048   | 1525      | 13.06%  |
| 16384  | 1517      | 12.99%  |
| 1024   | 319       | 2.73%   |
| 32768  | 310       | 2.66%   |
| 512    | 45        | 0.39%   |
| 256    | 9         | 0.08%   |
| 65536  | 6         | 0.05%   |
| 128    | 4         | 0.03%   |
| 32767  | 2         | 0.02%   |
| 3072   | 2         | 0.02%   |
| 64     | 2         | 0.02%   |
| 131072 | 1         | 0.01%   |
| 129728 | 1         | 0.01%   |
| 6144   | 1         | 0.01%   |
| 4092   | 1         | 0.01%   |
| 2560   | 1         | 0.01%   |
| 1556   | 1         | 0.01%   |
| 1491   | 1         | 0.01%   |
| 32     | 1         | 0.01%   |
| 8      | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3261      | 28.3%   |
| 1333    | 1516      | 13.16%  |
| 2400    | 1390      | 12.06%  |
| 2667    | 1112      | 9.65%   |
| 3200    | 1066      | 9.25%   |
| 2133    | 776       | 6.73%   |
| 667     | 356       | 3.09%   |
| 800     | 352       | 3.05%   |
| Unknown | 214       | 1.86%   |
| 2666    | 191       | 1.66%   |
| 1334    | 175       | 1.52%   |
| 1067    | 172       | 1.49%   |
| 1867    | 167       | 1.45%   |
| 1066    | 148       | 1.28%   |
| 4800    | 82        | 0.71%   |
| 1866    | 77        | 0.67%   |
| 3000    | 69        | 0.6%    |
| 3600    | 59        | 0.51%   |
| 2933    | 58        | 0.5%    |
| 533     | 47        | 0.41%   |
| 4267    | 36        | 0.31%   |
| 400     | 33        | 0.29%   |
| 6400    | 24        | 0.21%   |
| 975     | 12        | 0.1%    |
| 5600    | 11        | 0.1%    |
| 333     | 10        | 0.09%   |
| 2048    | 8         | 0.07%   |
| 1400    | 8         | 0.07%   |
| 266     | 8         | 0.07%   |
| 4266    | 7         | 0.06%   |
| 4000    | 7         | 0.06%   |
| 1332    | 7         | 0.06%   |
| 1033    | 7         | 0.06%   |
| 65535   | 5         | 0.04%   |
| 3733    | 5         | 0.04%   |
| 3400    | 5         | 0.04%   |
| 1639    | 5         | 0.04%   |
| 1200    | 5         | 0.04%   |
| 5200    | 4         | 0.03%   |
| 3534    | 3         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 13        | 30.95%  |
| Hewlett-Packard       | 12        | 28.57%  |
| Prolific Technology   | 3         | 7.14%   |
| Seiko Epson           | 2         | 4.76%   |
| Lexmark International | 2         | 4.76%   |
| ELGIN                 | 2         | 4.76%   |
| Dymo-CoStar           | 2         | 4.76%   |
| Samsung Electronics   | 1         | 2.38%   |
| Ricoh                 | 1         | 2.38%   |
| QinHeng Electronics   | 1         | 2.38%   |
| Kyocera               | 1         | 2.38%   |
| Canon                 | 1         | 2.38%   |
| Apple                 | 1         | 2.38%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                                                     | 3         | 6.82%   |
| ELGIN L42PRO                                                                                                      | 2         | 4.55%   |
| Brother MFC-7360N                                                                                                 | 2         | 4.55%   |
| Brother HL-1430 Laser Printer                                                                                     | 2         | 4.55%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 2.27%   |
| Seiko Epson Printer                                                                                               | 1         | 2.27%   |
| Samsung ML-1610 Mono Laser Printer                                                                                | 1         | 2.27%   |
| Ricoh SP 112                                                                                                      | 1         | 2.27%   |
| QinHeng CH340S                                                                                                    | 1         | 2.27%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 2.27%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 2.27%   |
| Kyocera FS-1025MFP                                                                                                | 1         | 2.27%   |
| HP PNP Fax Null                                                                                                   | 1         | 2.27%   |
| HP LaserJet P3005                                                                                                 | 1         | 2.27%   |
| HP LaserJet 3390                                                                                                  | 1         | 2.27%   |
| HP LaserJet 2200                                                                                                  | 1         | 2.27%   |
| HP LaserJet 1200                                                                                                  | 1         | 2.27%   |
| HP LaserJet 1020                                                                                                  | 1         | 2.27%   |
| HP LaserJet 1012                                                                                                  | 1         | 2.27%   |
| HP Laser 107a Printer                                                                                             | 1         | 2.27%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 2.27%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 2.27%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1         | 2.27%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1         | 2.27%   |
| HP DeskJet 5850c                                                                                                  | 1         | 2.27%   |
| HP Color LaserJet CP1215                                                                                          | 1         | 2.27%   |
| Dymo-CoStar LabelWriter 450                                                                                       | 1         | 2.27%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                                                              | 1         | 2.27%   |
| Canon LBP2900                                                                                                     | 1         | 2.27%   |
| Brother MFC-L2685DW                                                                                               | 1         | 2.27%   |
| Brother MFC-J485DW                                                                                                | 1         | 2.27%   |
| Brother MFC-J200                                                                                                  | 1         | 2.27%   |
| Brother HL-L5200DW series                                                                                         | 1         | 2.27%   |
| Brother HL-L2310D series                                                                                          | 1         | 2.27%   |
| Brother HL-L2300D series                                                                                          | 1         | 2.27%   |
| Brother HL-2030 Laser Printer                                                                                     | 1         | 2.27%   |
| Brother DCP-J152W                                                                                                 | 1         | 2.27%   |
| Brother DCP-J100                                                                                                  | 1         | 2.27%   |
| Apple Gamesir-G3s 2.10                                                                                            | 1         | 2.27%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 76.47%  |
| Seiko Epson     | 3         | 17.65%  |
| Hewlett-Packard | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 4         | 23.53%  |
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2         | 11.76%  |
| Canon CanoScan LiDE 220                                                             | 2         | 11.76%  |
| Canon CanoScan LiDE 210                                                             | 2         | 11.76%  |
| Canon CanoScan LiDE 120                                                             | 2         | 11.76%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 5.88%   |
| HP ScanJet 5300c/5370c                                                              | 1         | 5.88%   |
| Canon CanoScan LiDE 700F                                                            | 1         | 5.88%   |
| Canon CanoScan LIDE 25                                                              | 1         | 5.88%   |
| Canon CanoScan LiDE 100                                                             | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 574       | 27.36%  |
| Bison Electronics                      | 217       | 10.34%  |
| IMC Networks                           | 188       | 8.96%   |
| Microdia                               | 176       | 8.39%   |
| Realtek Semiconductor                  | 167       | 7.96%   |
| Sunplus Innovation Technology          | 112       | 5.34%   |
| Logitech                               | 94        | 4.48%   |
| Suyin                                  | 66        | 3.15%   |
| Lite-On Technology                     | 63        | 3%      |
| Syntek                                 | 45        | 2.14%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 2.14%   |
| Apple                                  | 43        | 2.05%   |
| Quanta                                 | 42        | 2%      |
| Silicon Motion                         | 31        | 1.48%   |
| Lenovo                                 | 27        | 1.29%   |
| Alcor Micro                            | 26        | 1.24%   |
| Luxvisions Innotech Limited            | 25        | 1.19%   |
| Z-Star Microelectronics                | 21        | 1%      |
| ALi                                    | 15        | 0.71%   |
| Ricoh                                  | 12        | 0.57%   |
| Importek                               | 11        | 0.52%   |
| ARC International                      | 8         | 0.38%   |
| Intel                                  | 6         | 0.29%   |
| Supreme Electronics                    | 5         | 0.24%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.24%   |
| Trust                                  | 4         | 0.19%   |
| Primax Electronics                     | 4         | 0.19%   |
| OmniVision Technologies                | 4         | 0.19%   |
| Genesys Logic                          | 4         | 0.19%   |
| GEMBIRD                                | 4         | 0.19%   |
| Arkmicro Technologies                  | 4         | 0.19%   |
| Tripath Technology                     | 3         | 0.14%   |
| Jiangxi Shinetech Optical              | 3         | 0.14%   |
| Generalplus Technology                 | 3         | 0.14%   |
| DigiTech                               | 3         | 0.14%   |
| Cubeternet                             | 3         | 0.14%   |
| WCM_USB                                | 2         | 0.1%    |
| USB Camera                             | 2         | 0.1%    |
| Unknown                                | 2         | 0.1%    |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 175       | 8.26%   |
| Bison Integrated Camera                       | 100       | 4.72%   |
| IMC Networks Integrated Camera                | 62        | 2.93%   |
| Microdia Integrated_Webcam_HD                 | 45        | 2.12%   |
| Realtek Integrated_Webcam_HD                  | 43        | 2.03%   |
| Lite-On Integrated Camera                     | 41        | 1.94%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 38        | 1.79%   |
| Microdia Integrated Webcam                    | 37        | 1.75%   |
| Chicony HD WebCam                             | 37        | 1.75%   |
| Sunplus Integrated_Webcam_HD                  | 33        | 1.56%   |
| Realtek USB 2.0 PC Camera                     | 27        | 1.27%   |
| Chicony Integrated Camera (1280x720@30)       | 27        | 1.27%   |
| Logitech Webcam C270                          | 25        | 1.18%   |
| Bison Lenovo EasyCamera                       | 25        | 1.18%   |
| Apple FaceTime HD Camera                      | 24        | 1.13%   |
| Logitech HD Pro Webcam C920                   | 21        | 0.99%   |
| IMC Networks Realtek PC Camera                | 21        | 0.99%   |
| Chicony Integrated Camera [ThinkPad]          | 20        | 0.94%   |
| Bison SunplusIT Integrated Camera             | 20        | 0.94%   |
| IMC Networks EasyCamera                       | 19        | 0.9%    |
| Chicony Realtek DMFT RGB                      | 18        | 0.85%   |
| Syntek Lenovo EasyCamera                      | 16        | 0.76%   |
| Apple FaceTime HD Camera (Built-in)           | 16        | 0.76%   |
| Lenovo Integrated Webcam [R5U877]             | 15        | 0.71%   |
| Chicony Integrated IR Camera                  | 15        | 0.71%   |
| Chicony HP HD Webcam [Fixed]                  | 15        | 0.71%   |
| Bison ThinkPad Integrated Camera              | 15        | 0.71%   |
| Realtek USB Camera                            | 14        | 0.66%   |
| Syntek EasyCamera                             | 13        | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 13        | 0.61%   |
| Syntek Integrated Camera                      | 12        | 0.57%   |
| Microdia USB 2.0 Camera                       | 12        | 0.57%   |
| Luxvisions Innotech Limited Integrated Camera | 12        | 0.57%   |
| Chicony Lenovo EasyCamera                     | 12        | 0.57%   |
| Chicony FJ Camera                             | 12        | 0.57%   |
| Chicony Chicony USB2.0 Camera                 | 12        | 0.57%   |
| Bison Lenovo Integrated Webcam                | 12        | 0.57%   |
| Microdia Dell Laptop Integrated Webcam HD     | 11        | 0.52%   |
| IMC Networks UVC VGA Webcam                   | 11        | 0.52%   |
| Chicony USB2.0 VGA UVC WebCam                 | 11        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 204       | 37.02%  |
| Synaptics                  | 108       | 19.6%   |
| Upek                       | 63        | 11.43%  |
| AuthenTec                  | 46        | 8.35%   |
| Shenzhen Goodix Technology | 43        | 7.8%    |
| STMicroelectronics         | 30        | 5.44%   |
| Broadcom                   | 18        | 3.27%   |
| LighTuning Technology      | 14        | 2.54%   |
| Elan Microelectronics      | 14        | 2.54%   |
| FocalTech Systems          | 6         | 1.09%   |
| Samsung Electronics        | 2         | 0.36%   |
| Next Biometrics            | 1         | 0.18%   |
| Fingerprint Cards          | 1         | 0.18%   |
| DigitalPersona             | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 68        | 12.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 60        | 10.89%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 43        | 7.8%    |
| Validity Sensors Synaptics WBDI                                              | 37        | 6.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 32        | 5.81%   |
| Shenzhen Goodix Fingerprint Reader                                           | 32        | 5.81%   |
| STMicroelectronics Fingerprint Reader                                        | 30        | 5.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 23        | 4.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 21        | 3.81%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 3.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 16        | 2.9%    |
| Elan Fingerprint Sensor                                                      | 14        | 2.54%   |
| AuthenTec AES2810                                                            | 14        | 2.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 12        | 2.18%   |
| Synaptics WBDI                                                               | 8         | 1.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 8         | 1.45%   |
| AuthenTec AES1660                                                            | 8         | 1.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 7         | 1.27%   |
| Shenzhen Goodix  Fingerprint Device                                          | 7         | 1.27%   |
| Validity Sensors VFS491                                                      | 6         | 1.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 6         | 1.09%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 6         | 1.09%   |
| AuthenTec AES1600                                                            | 6         | 1.09%   |
| Validity Sensors Fingerprint scanner                                         | 5         | 0.91%   |
| FocalTech Systems Fingerprint Reader                                         | 5         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.73%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 4         | 0.73%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 0.73%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 4         | 0.73%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 4         | 0.73%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 3         | 0.54%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.54%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.54%   |
| AuthenTec AES2660                                                            | 3         | 0.54%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 2         | 0.36%   |
| Synaptics UWP WBDI Device                                                    | 2         | 0.36%   |
| Synaptics UWP WBDI                                                           | 2         | 0.36%   |
| Samsung CanvasBio Fingerprint Reader                                         | 2         | 0.36%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.36%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4876      | 40.08%  |
| 0     | 3857      | 31.71%  |
| 2     | 2134      | 17.54%  |
| 3     | 884       | 7.27%   |
| 4     | 311       | 2.56%   |
| 5     | 70        | 0.58%   |
| 6     | 20        | 0.16%   |
| 7     | 9         | 0.07%   |
| 9     | 2         | 0.02%   |
| 8     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 6945      | 59.62%  |
| Bluetooth                | 1210      | 10.39%  |
| Net/wireless             | 1156      | 9.92%   |
| Card reader              | 725       | 6.22%   |
| Fingerprint reader       | 468       | 4.02%   |
| Firewire controller      | 375       | 3.22%   |
| Sound                    | 195       | 1.67%   |
| Net/ethernet             | 161       | 1.38%   |
| Network                  | 158       | 1.36%   |
| Graphics card            | 119       | 1.02%   |
| Storage                  | 52        | 0.45%   |
| Modem                    | 26        | 0.22%   |
| Storage/ata              | 21        | 0.18%   |
| Storage/raid             | 18        | 0.15%   |
| Dvb card                 | 10        | 0.09%   |
| Storage/ide              | 6         | 0.05%   |
| Storage/nvme             | 3         | 0.03%   |
| Wireless                 | 1         | 0.01%   |

