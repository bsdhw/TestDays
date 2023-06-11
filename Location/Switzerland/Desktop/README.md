BSD in Switzerland - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Switzerland.

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

Total: 227

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| PC Engines    | apu4                        | [f130ecbaa3](https://bsd-hardware.info/?probe=f130ecbaa3) | Jun 01, 2023 |
| Unknown       | Unknown                     | [c1854cc5f2](https://bsd-hardware.info/?probe=c1854cc5f2) | May 27, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| HP            | 8299                        | [f5ecf1eaeb](https://bsd-hardware.info/?probe=f5ecf1eaeb) | May 17, 2023 |
| CWWK          | MINIPC-G12                  | [b26aab0f0d](https://bsd-hardware.info/?probe=b26aab0f0d) | May 17, 2023 |
| PC Engines    | apu6                        | [3733cf215f](https://bsd-hardware.info/?probe=3733cf215f) | May 13, 2023 |
| Supermicro    | X11SDW-16C-TP13F+           | [1cc0308686](https://bsd-hardware.info/?probe=1cc0308686) | May 13, 2023 |
| MW            | GMLK-2_5G4L                 | [9fea438eba](https://bsd-hardware.info/?probe=9fea438eba) | May 07, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | [472c5fb78e](https://bsd-hardware.info/?probe=472c5fb78e) | Apr 29, 2023 |
| PC Engines    | APU2                        | [4337168a3a](https://bsd-hardware.info/?probe=4337168a3a) | Apr 20, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | [49a95f197c](https://bsd-hardware.info/?probe=49a95f197c) | Apr 20, 2023 |
| Intel BOX4... | Geminilake                  | [79d72cc60f](https://bsd-hardware.info/?probe=79d72cc60f) | Apr 13, 2023 |
| PC Engines    | APU2                        | [766755078c](https://bsd-hardware.info/?probe=766755078c) | Apr 10, 2023 |
| GoWin Solu... | R86S                        | [35e1503946](https://bsd-hardware.info/?probe=35e1503946) | Mar 08, 2023 |
| Protectli     | FW4C Ver                    | [d93437d96b](https://bsd-hardware.info/?probe=d93437d96b) | Mar 04, 2023 |
| Shuttle       | FS81                        | [5787eda5ac](https://bsd-hardware.info/?probe=5787eda5ac) | Feb 26, 2023 |
| Unknown       | Unknown                     | [913946ccc9](https://bsd-hardware.info/?probe=913946ccc9) | Feb 25, 2023 |
| Techvision    | TVI7309X B0                 | [0e62dfc436](https://bsd-hardware.info/?probe=0e62dfc436) | Feb 25, 2023 |
| Dell          | 05XGC8 A01                  | [c51a264e20](https://bsd-hardware.info/?probe=c51a264e20) | Feb 23, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | [4874e3417f](https://bsd-hardware.info/?probe=4874e3417f) | Feb 09, 2023 |
| Intel BOX4... | Geminilake                  | [286c29b1bb](https://bsd-hardware.info/?probe=286c29b1bb) | Feb 08, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3a47e70001](https://bsd-hardware.info/?probe=3a47e70001) | Feb 03, 2023 |
| PC Engines    | apu4                        | [c3ff966a17](https://bsd-hardware.info/?probe=c3ff966a17) | Feb 03, 2023 |
| PC Engines    | APU2                        | [315ef90664](https://bsd-hardware.info/?probe=315ef90664) | Feb 01, 2023 |
| Techvision    | TVI7309X B0                 | [739cc6e5ac](https://bsd-hardware.info/?probe=739cc6e5ac) | Jan 18, 2023 |
| Intel         | HURONRIVER                  | [9994ae920b](https://bsd-hardware.info/?probe=9994ae920b) | Jan 15, 2023 |
| Intel         | HURONRIVER                  | [320272bdf1](https://bsd-hardware.info/?probe=320272bdf1) | Jan 11, 2023 |
| PC Engines    | apu4                        | [3d69b3aec1](https://bsd-hardware.info/?probe=3d69b3aec1) | Jan 03, 2023 |
| PC Engines    | apu4                        | [62e6e7e679](https://bsd-hardware.info/?probe=62e6e7e679) | Jan 03, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| Intel BOX4... | Geminilake                  | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Dell          | 0X4N41 A01                  | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| Unknown       | Unknown                     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| Unknown       | Unknown                     | [78893acbd5](https://bsd-hardware.info/?probe=78893acbd5) | Dec 06, 2022 |
| Unknown       | Unknown                     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| Unknown       | Unknown                     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| MW            | GMLK-2_5G4L                 | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| Unknown       | Unknown                     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Unknown       | Unknown                     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| Unknown       | Unknown                     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| PC Engines    | APU2                        | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |
| Unknown       | Unknown                     | [02a9700c12](https://bsd-hardware.info/?probe=02a9700c12) | Oct 03, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [353008eb5e](https://bsd-hardware.info/?probe=353008eb5e) | Sep 29, 2022 |
| PC Engines    | APU2                        | [3fcc5e5ae2](https://bsd-hardware.info/?probe=3fcc5e5ae2) | Sep 25, 2022 |
| HP            | ProLiant ML350p Gen8        | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| Unknown       | Unknown                     | [9422de47ab](https://bsd-hardware.info/?probe=9422de47ab) | Aug 30, 2022 |
| Shuttle       | FS81                        | [b2db8ceabe](https://bsd-hardware.info/?probe=b2db8ceabe) | Aug 24, 2022 |
| Dell          | 02YYK5 A00                  | [5428710004](https://bsd-hardware.info/?probe=5428710004) | Aug 16, 2022 |
| Acer          | Aspire X3995                | [9240256ae5](https://bsd-hardware.info/?probe=9240256ae5) | Aug 06, 2022 |
| Unknown       | Unknown                     | [9f98df6faf](https://bsd-hardware.info/?probe=9f98df6faf) | Aug 05, 2022 |
| Unknown       | Unknown                     | [25ca16baef](https://bsd-hardware.info/?probe=25ca16baef) | Aug 05, 2022 |
| Unknown       | Unknown                     | [f9bf5b2e00](https://bsd-hardware.info/?probe=f9bf5b2e00) | Aug 04, 2022 |
| PC Engines    | APU2                        | [35d0a79b04](https://bsd-hardware.info/?probe=35d0a79b04) | Aug 04, 2022 |
| Protectli     | FW6                         | [b686fdf1c1](https://bsd-hardware.info/?probe=b686fdf1c1) | Jul 31, 2022 |
| Unknown       | Unknown                     | [0b84314fbf](https://bsd-hardware.info/?probe=0b84314fbf) | Jul 28, 2022 |
| Unknown       | Unknown                     | [4e721b00d5](https://bsd-hardware.info/?probe=4e721b00d5) | Jul 28, 2022 |
| PC Engines    | APU2                        | [7d3a1f2825](https://bsd-hardware.info/?probe=7d3a1f2825) | Jul 14, 2022 |
| PC Engines    | APU2                        | [0dd60aeb9a](https://bsd-hardware.info/?probe=0dd60aeb9a) | Jul 14, 2022 |
| Biostar       | H61MHV2                     | [58a61e6171](https://bsd-hardware.info/?probe=58a61e6171) | Jul 11, 2022 |
| Biostar       | H61MHV2                     | [2aa5e2a62d](https://bsd-hardware.info/?probe=2aa5e2a62d) | Jul 08, 2022 |
| Dell          | 02YYK5 A00                  | [fb2e5bec61](https://bsd-hardware.info/?probe=fb2e5bec61) | Jul 05, 2022 |
| Dell          | 02YYK5 A00                  | [629de6cdb6](https://bsd-hardware.info/?probe=629de6cdb6) | Jul 05, 2022 |
| HP            | 1494                        | [3a61eb7bae](https://bsd-hardware.info/?probe=3a61eb7bae) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [34bb6613ee](https://bsd-hardware.info/?probe=34bb6613ee) | Jun 23, 2022 |
| Unknown       | Unknown                     | [d7d6b654a4](https://bsd-hardware.info/?probe=d7d6b654a4) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | [180af6a2da](https://bsd-hardware.info/?probe=180af6a2da) | Jun 19, 2022 |
| Dell          | 02YYK5 A00                  | [c58d529930](https://bsd-hardware.info/?probe=c58d529930) | Jun 19, 2022 |
| MW            | GMLK-2_5G4L                 | [97e567c06b](https://bsd-hardware.info/?probe=97e567c06b) | Jun 18, 2022 |
| ASUSTek       | Pro B660M-C D4              | [302ea8252d](https://bsd-hardware.info/?probe=302ea8252d) | Jun 08, 2022 |
| PC Engines    | apu4                        | [1067180759](https://bsd-hardware.info/?probe=1067180759) | May 31, 2022 |
| PC Engines    | apu4                        | [214bc37259](https://bsd-hardware.info/?probe=214bc37259) | May 26, 2022 |
| Protectli     | FW6                         | [0dc7509652](https://bsd-hardware.info/?probe=0dc7509652) | May 24, 2022 |
| Unknown       | Unknown                     | [7c260c2423](https://bsd-hardware.info/?probe=7c260c2423) | May 20, 2022 |
| Intel         | D54250WYK H13922-303        | [8f9e0896d7](https://bsd-hardware.info/?probe=8f9e0896d7) | May 12, 2022 |
| Dell          | 0X4N41 A01                  | [d1596f34bf](https://bsd-hardware.info/?probe=d1596f34bf) | May 12, 2022 |
| Intel         | D54250WYK H13922-303        | [6dfeb3d80d](https://bsd-hardware.info/?probe=6dfeb3d80d) | May 10, 2022 |
| Intel         | HURONRIVER                  | [515172b464](https://bsd-hardware.info/?probe=515172b464) | May 09, 2022 |
| PC Engines    | APU2                        | [a2b68686f0](https://bsd-hardware.info/?probe=a2b68686f0) | Apr 27, 2022 |
| Dell          | 0TP406                      | [775061bc83](https://bsd-hardware.info/?probe=775061bc83) | Apr 25, 2022 |
| Biostar       | H61MHV2                     | [7d9806d719](https://bsd-hardware.info/?probe=7d9806d719) | Apr 21, 2022 |
| Gigabyte      | 990FXA-UD3                  | [378021707a](https://bsd-hardware.info/?probe=378021707a) | Apr 17, 2022 |
| PC Engines    | apu4                        | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Dell          | 0TP406                      | [9a29305ef1](https://bsd-hardware.info/?probe=9a29305ef1) | Apr 06, 2022 |
| Unknown       | Unknown                     | [b6b1ec9dc1](https://bsd-hardware.info/?probe=b6b1ec9dc1) | Mar 30, 2022 |
| ASRockRack    | X570D4U-2L2T                | [7e042aa70d](https://bsd-hardware.info/?probe=7e042aa70d) | Mar 25, 2022 |
| Unknown       | Unknown                     | [abb17bcb42](https://bsd-hardware.info/?probe=abb17bcb42) | Mar 21, 2022 |
| Unknown       | Unknown                     | [1d97ecbc95](https://bsd-hardware.info/?probe=1d97ecbc95) | Mar 20, 2022 |
| Unknown       | Unknown                     | [e169892276](https://bsd-hardware.info/?probe=e169892276) | Mar 18, 2022 |
| Dell          | 0X4N41 A01                  | [456b55de38](https://bsd-hardware.info/?probe=456b55de38) | Mar 17, 2022 |
| Unknown       | Unknown                     | [1ed23967fd](https://bsd-hardware.info/?probe=1ed23967fd) | Mar 17, 2022 |
| Dell          | 0X4N41 A01                  | [4d7d8fd92b](https://bsd-hardware.info/?probe=4d7d8fd92b) | Mar 17, 2022 |
| Unknown       | Unknown                     | [95154c4898](https://bsd-hardware.info/?probe=95154c4898) | Mar 16, 2022 |
| PC Engines    | APU2                        | [6e5badb880](https://bsd-hardware.info/?probe=6e5badb880) | Mar 04, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7da5182091](https://bsd-hardware.info/?probe=7da5182091) | Feb 27, 2022 |
| PC Engines    | APU2                        | [40ba1b35da](https://bsd-hardware.info/?probe=40ba1b35da) | Feb 24, 2022 |
| Dell          | 0X4N41 A01                  | [fea17bcf92](https://bsd-hardware.info/?probe=fea17bcf92) | Feb 19, 2022 |
| PC Engines    | APU2                        | [547be2fb61](https://bsd-hardware.info/?probe=547be2fb61) | Feb 19, 2022 |
| Dell          | 0X4N41 A01                  | [a62eea5e4e](https://bsd-hardware.info/?probe=a62eea5e4e) | Feb 11, 2022 |
| Dell          | 0X4N41 A01                  | [55b7348a0c](https://bsd-hardware.info/?probe=55b7348a0c) | Feb 11, 2022 |
| PC Engines    | APU2                        | [566948b2c1](https://bsd-hardware.info/?probe=566948b2c1) | Feb 09, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [76fadb9527](https://bsd-hardware.info/?probe=76fadb9527) | Feb 09, 2022 |
| HP            | 0B54h D                     | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| HP            | ProLiant ML350p Gen8        | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| HP            | 0B54h D                     | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| Unknown       | Unknown                     | [000331f38e](https://bsd-hardware.info/?probe=000331f38e) | Jan 31, 2022 |
| Unknown       | Unknown                     | [74b8fc0269](https://bsd-hardware.info/?probe=74b8fc0269) | Jan 30, 2022 |
| PC Engines    | apu4                        | [4f6a1c9c9a](https://bsd-hardware.info/?probe=4f6a1c9c9a) | Jan 25, 2022 |
| Unknown       | Unknown                     | [b572e30460](https://bsd-hardware.info/?probe=b572e30460) | Jan 19, 2022 |
| HP            | 3396                        | [236ed20a86](https://bsd-hardware.info/?probe=236ed20a86) | Jan 11, 2022 |
| Unknown       | Unknown                     | [e38915ac8c](https://bsd-hardware.info/?probe=e38915ac8c) | Jan 08, 2022 |
| Unknown       | Unknown                     | [0a82e095ee](https://bsd-hardware.info/?probe=0a82e095ee) | Jan 08, 2022 |
| Unknown       | Unknown                     | [9c67eb6ecd](https://bsd-hardware.info/?probe=9c67eb6ecd) | Dec 30, 2021 |
| Gigabyte      | H97N-WIFI                   | [3ccd5eace4](https://bsd-hardware.info/?probe=3ccd5eace4) | Dec 15, 2021 |
| ASRock        | B550 Taichi                 | [ed2fd72332](https://bsd-hardware.info/?probe=ed2fd72332) | Dec 14, 2021 |
| PC Engines    | apu4                        | [a06765ebb1](https://bsd-hardware.info/?probe=a06765ebb1) | Dec 09, 2021 |
| Dell          | 0X4N41 A01                  | [015319ce8c](https://bsd-hardware.info/?probe=015319ce8c) | Dec 08, 2021 |
| Supermicro    | X11SDW-4C-TP13F             | [f424260bfa](https://bsd-hardware.info/?probe=f424260bfa) | Dec 03, 2021 |
| ASRockRack    | X570D4U-2L2T                | [b35a4b529c](https://bsd-hardware.info/?probe=b35a4b529c) | Nov 22, 2021 |
| Intel         | HURONRIVER                  | [741fd0e126](https://bsd-hardware.info/?probe=741fd0e126) | Nov 13, 2021 |
| Dell          | 0X4N41 A01                  | [d08d7fde4a](https://bsd-hardware.info/?probe=d08d7fde4a) | Nov 13, 2021 |
| PC Engines    | apu4                        | [64cad2ccf6](https://bsd-hardware.info/?probe=64cad2ccf6) | Nov 08, 2021 |
| HP            | 3397                        | [3434fa8427](https://bsd-hardware.info/?probe=3434fa8427) | Nov 07, 2021 |
| HP            | 3397                        | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [15d56aee58](https://bsd-hardware.info/?probe=15d56aee58) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Apple         | Mac-F221BEC8                | [4e91fa71b2](https://bsd-hardware.info/?probe=4e91fa71b2) | Oct 19, 2021 |
| Unknown       | Unknown                     | [734ec7d9fc](https://bsd-hardware.info/?probe=734ec7d9fc) | Oct 18, 2021 |
| Unknown       | Unknown                     | [4ecab88e78](https://bsd-hardware.info/?probe=4ecab88e78) | Oct 17, 2021 |
| ASRock        | A320M-ITX                   | [06a8c0d2ac](https://bsd-hardware.info/?probe=06a8c0d2ac) | Oct 08, 2021 |
| ASRock        | B550 Taichi                 | [7599775c70](https://bsd-hardware.info/?probe=7599775c70) | Oct 08, 2021 |
| PC Engines    | APU2                        | [7a21594bf7](https://bsd-hardware.info/?probe=7a21594bf7) | Oct 08, 2021 |
| PC Engines    | apu6                        | [a184c5f1b2](https://bsd-hardware.info/?probe=a184c5f1b2) | Oct 06, 2021 |
| PC Engines    | APU2                        | [d36e631149](https://bsd-hardware.info/?probe=d36e631149) | Oct 03, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| PC Engines    | apu4                        | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| ASRock        | A320M-ITX                   | [051ca0708f](https://bsd-hardware.info/?probe=051ca0708f) | Sep 03, 2021 |
| ASRock        | A320M-ITX                   | [23bccfa11c](https://bsd-hardware.info/?probe=23bccfa11c) | Sep 01, 2021 |
| ASUSTek       | P8Z77-V                     | [eb4948e855](https://bsd-hardware.info/?probe=eb4948e855) | Aug 31, 2021 |
| Unknown       | Unknown                     | [114a632ab4](https://bsd-hardware.info/?probe=114a632ab4) | Aug 30, 2021 |
| ASRock        | A320M-ITX                   | [b0339f73bc](https://bsd-hardware.info/?probe=b0339f73bc) | Aug 28, 2021 |
| Unknown       | Unknown                     | [5bb434cb3f](https://bsd-hardware.info/?probe=5bb434cb3f) | Aug 27, 2021 |
| ASRock        | A320M-ITX                   | [c28bfd784d](https://bsd-hardware.info/?probe=c28bfd784d) | Aug 27, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [47284b4819](https://bsd-hardware.info/?probe=47284b4819) | Aug 27, 2021 |
| PC Engines    | apu4                        | [9f5ec6c23f](https://bsd-hardware.info/?probe=9f5ec6c23f) | Aug 23, 2021 |
| PC Engines    | apu4                        | [514a974f68](https://bsd-hardware.info/?probe=514a974f68) | Aug 10, 2021 |
| PC Engines    | APU2                        | [823fdc32f0](https://bsd-hardware.info/?probe=823fdc32f0) | Aug 09, 2021 |
| ASRock        | J4105-ITX                   | [1ac35fcecf](https://bsd-hardware.info/?probe=1ac35fcecf) | Aug 08, 2021 |
| Shuttle       | DS10U                       | [fa151322fc](https://bsd-hardware.info/?probe=fa151322fc) | Aug 03, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [772a9416ab](https://bsd-hardware.info/?probe=772a9416ab) | Aug 01, 2021 |
| PC Engines    | APU2                        | [4c2b89d2e6](https://bsd-hardware.info/?probe=4c2b89d2e6) | Jul 31, 2021 |
| Dell          | 0X4N41 A01                  | [a528966ab8](https://bsd-hardware.info/?probe=a528966ab8) | Jul 30, 2021 |
| Dell          | 0X4N41 A01                  | [51136572fc](https://bsd-hardware.info/?probe=51136572fc) | Jul 29, 2021 |
| ASRockRack    | X470D4U2-2T                 | [8a2efd6b5b](https://bsd-hardware.info/?probe=8a2efd6b5b) | Jul 25, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [fea747e9eb](https://bsd-hardware.info/?probe=fea747e9eb) | Jul 25, 2021 |
| Dell          | 0X4N41 A01                  | [f29fab4508](https://bsd-hardware.info/?probe=f29fab4508) | Jul 23, 2021 |
| Dell          | 0X4N41 A01                  | [b7c3a2b2e4](https://bsd-hardware.info/?probe=b7c3a2b2e4) | Jul 23, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [89938d9a3a](https://bsd-hardware.info/?probe=89938d9a3a) | Jul 20, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [c2721a852b](https://bsd-hardware.info/?probe=c2721a852b) | Jul 18, 2021 |
| Supermicro    | PDSML+                      | [f8a9ca42d6](https://bsd-hardware.info/?probe=f8a9ca42d6) | Jul 11, 2021 |
| PC Engines    | APU2                        | [fe77a10950](https://bsd-hardware.info/?probe=fe77a10950) | Jul 08, 2021 |
| Protectli     | FW6                         | [c28479f624](https://bsd-hardware.info/?probe=c28479f624) | Jun 20, 2021 |
| ASRockRack    | X470D4U2-2T                 | [6efb43e299](https://bsd-hardware.info/?probe=6efb43e299) | Jun 18, 2021 |
| Protectli     | FW6                         | [36d53d9465](https://bsd-hardware.info/?probe=36d53d9465) | Jun 17, 2021 |
| Protectli     | FW6                         | [9579e972f2](https://bsd-hardware.info/?probe=9579e972f2) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [15ba8e73e1](https://bsd-hardware.info/?probe=15ba8e73e1) | Jun 09, 2021 |
| PC Engines    | apu4                        | [7ffaed1505](https://bsd-hardware.info/?probe=7ffaed1505) | Jun 06, 2021 |
| HPE           | ProLiant MicroServer Gen... | [74f5dbcf1b](https://bsd-hardware.info/?probe=74f5dbcf1b) | Jun 01, 2021 |
| PC Engines    | apu4                        | [aad3e6a309](https://bsd-hardware.info/?probe=aad3e6a309) | May 28, 2021 |
| Shuttle       | DS10U                       | [bd8bea4a6a](https://bsd-hardware.info/?probe=bd8bea4a6a) | May 27, 2021 |
| ASRock        | X99M Extreme4               | [ef131c774d](https://bsd-hardware.info/?probe=ef131c774d) | May 02, 2021 |
| Lenovo        | 318E NOK                    | [115f2c7b35](https://bsd-hardware.info/?probe=115f2c7b35) | Apr 27, 2021 |
| Unknown       | Unknown                     | [44e10ac014](https://bsd-hardware.info/?probe=44e10ac014) | Apr 19, 2021 |
| PC Engines    | APU2                        | [8b425e6086](https://bsd-hardware.info/?probe=8b425e6086) | Apr 08, 2021 |
| PC Engines    | APU2                        | [f261049b51](https://bsd-hardware.info/?probe=f261049b51) | Apr 07, 2021 |
| Unknown       | Unknown                     | [09e3c55edf](https://bsd-hardware.info/?probe=09e3c55edf) | Mar 26, 2021 |
| PC Engines    | APU2                        | [6204024271](https://bsd-hardware.info/?probe=6204024271) | Mar 24, 2021 |
| PC Engines    | APU2                        | [b39d8ba487](https://bsd-hardware.info/?probe=b39d8ba487) | Mar 24, 2021 |
| HPE           | ProLiant MicroServer Gen... | [40ec36ad78](https://bsd-hardware.info/?probe=40ec36ad78) | Mar 18, 2021 |
| PC Engines    | apu4                        | [e10b5c92e9](https://bsd-hardware.info/?probe=e10b5c92e9) | Mar 16, 2021 |
| Unknown       | Unknown                     | [36f81afd88](https://bsd-hardware.info/?probe=36f81afd88) | Mar 13, 2021 |
| PC Engines    | apu4                        | [9268ee6857](https://bsd-hardware.info/?probe=9268ee6857) | Mar 13, 2021 |
| HPE           | ProLiant MicroServer Gen... | [2c0b0d8eb0](https://bsd-hardware.info/?probe=2c0b0d8eb0) | Mar 09, 2021 |
| BESSTAR Te... | IB9                         | [6d455b5e28](https://bsd-hardware.info/?probe=6d455b5e28) | Mar 08, 2021 |
| PC Engines    | APU3                        | [cf397191d2](https://bsd-hardware.info/?probe=cf397191d2) | Mar 04, 2021 |
| HP            | 0B54h D                     | [eb8428d5f3](https://bsd-hardware.info/?probe=eb8428d5f3) | Mar 01, 2021 |
| PC Engines    | APU2                        | [2ac1695054](https://bsd-hardware.info/?probe=2ac1695054) | Feb 28, 2021 |
| Unknown       | Unknown                     | [b6c6031b46](https://bsd-hardware.info/?probe=b6c6031b46) | Feb 27, 2021 |
| ASUSTek       | Z170-K                      | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Unknown       | Unknown                     | [ad3998234a](https://bsd-hardware.info/?probe=ad3998234a) | Feb 11, 2021 |
| PC Engines    | APU2                        | [836a3035f1](https://bsd-hardware.info/?probe=836a3035f1) | Feb 06, 2021 |
| PC Engines    | APU2                        | [4985fa31bf](https://bsd-hardware.info/?probe=4985fa31bf) | Feb 03, 2021 |
| PC Engines    | apu4                        | [c740c17c50](https://bsd-hardware.info/?probe=c740c17c50) | Feb 01, 2021 |
| YANYU         | D19SL_B                     | [d16128eed9](https://bsd-hardware.info/?probe=d16128eed9) | Jan 28, 2021 |
| Unknown       | Unknown                     | [d2895512c0](https://bsd-hardware.info/?probe=d2895512c0) | Jan 27, 2021 |
| Unknown       | Unknown                     | [b936d5a273](https://bsd-hardware.info/?probe=b936d5a273) | Jan 27, 2021 |
| PC Engines    | APU2                        | [3448eacd29](https://bsd-hardware.info/?probe=3448eacd29) | Jan 24, 2021 |
| PC Engines    | APU2                        | [72e0243d73](https://bsd-hardware.info/?probe=72e0243d73) | Jan 23, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | APU2                        | [c6c764813a](https://bsd-hardware.info/?probe=c6c764813a) | Jan 21, 2021 |
| PC Engines    | APU2                        | [bf1b93e96d](https://bsd-hardware.info/?probe=bf1b93e96d) | Jan 21, 2021 |
| ADI Engine... | RCC                         | [199da8eab6](https://bsd-hardware.info/?probe=199da8eab6) | Jan 20, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [c107103d53](https://bsd-hardware.info/?probe=c107103d53) | Jan 19, 2021 |
| Sun           | SUNW,Sun-Blade-100          | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| HP            | 1495                        | [2606547041](https://bsd-hardware.info/?probe=2606547041) | Dec 22, 2020 |
| HP            | 0B54h D                     | [de35ebc178](https://bsd-hardware.info/?probe=de35ebc178) | Dec 04, 2020 |
| PC Engines    | APU2                        | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| PC Engines    | apu4                        | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| HP            | ProLiant MicroServer Gen... | [94a279c84d](https://bsd-hardware.info/?probe=94a279c84d) | Sep 03, 2020 |
| HP            | 0B54h D                     | [840b12f1f9](https://bsd-hardware.info/?probe=840b12f1f9) | Aug 09, 2020 |
| HP            | 0B54h D                     | [c4454eaa39](https://bsd-hardware.info/?probe=c4454eaa39) | Aug 09, 2020 |
| Gigabyte      | H67A-UD3H-B3                | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| PC Engines    | apu4                        | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| HP            | 158A                        | [dfff5dd2f9](https://bsd-hardware.info/?probe=dfff5dd2f9) | Jun 09, 2020 |
| Unknown       | Unknown                     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| ASUSTek       | H81M-C                      | [d65f5372ec](https://bsd-hardware.info/?probe=d65f5372ec) | May 26, 2020 |
| HP            | 0B54h D                     | [b43db1d84e](https://bsd-hardware.info/?probe=b43db1d84e) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OPNsense 22.7       | 7        | 3.89%   |
| OPNsense 21.7.3     | 7        | 3.89%   |
| OPNsense 21.7.1     | 7        | 3.89%   |
| OPNsense 21.1.6     | 7        | 3.89%   |
| OPNsense 20.7.8     | 7        | 3.89%   |
| OPNsense 22.1.8     | 6        | 3.33%   |
| OPNsense 21.7.6     | 5        | 2.78%   |
| OPNsense 23.1.7     | 4        | 2.22%   |
| OPNsense 23.1.1     | 4        | 2.22%   |
| OPNsense 23.1       | 4        | 2.22%   |
| OPNsense 22.7.4     | 4        | 2.22%   |
| OPNsense 22.7.10    | 4        | 2.22%   |
| OPNsense 22.1.6     | 4        | 2.22%   |
| OPNsense 22.1.3     | 4        | 2.22%   |
| OPNsense 21.7.7     | 4        | 2.22%   |
| OPNsense 21.1.3     | 4        | 2.22%   |
| OPNsense 21.1       | 4        | 2.22%   |
| OpenBSD 6.8         | 4        | 2.22%   |
| OPNsense 23.1.5     | 3        | 1.67%   |
| OPNsense 22.7.8     | 3        | 1.67%   |
| OPNsense 22.1.7     | 3        | 1.67%   |
| OPNsense 22.1.10    | 3        | 1.67%   |
| OPNsense 22.1.1     | 3        | 1.67%   |
| OPNsense 21.7       | 3        | 1.67%   |
| OPNsense 21.1.8     | 3        | 1.67%   |
| OPNsense 21.1.2     | 3        | 1.67%   |
| FreeBSD 13.1-STABLE | 3        | 1.67%   |
| OPNsense 23.1.8     | 2        | 1.11%   |
| OPNsense 23.1.6     | 2        | 1.11%   |
| OPNsense 22.7.9     | 2        | 1.11%   |
| OPNsense 22.1.9     | 2        | 1.11%   |
| OPNsense 22.1.4     | 2        | 1.11%   |
| OPNsense 22.1.2     | 2        | 1.11%   |
| OPNsense 22.1       | 2        | 1.11%   |
| OPNsense 21.7.5     | 2        | 1.11%   |
| OPNsense 21.7.4     | 2        | 1.11%   |
| OPNsense 21.1.9     | 2        | 1.11%   |
| OPNsense 21.1.7     | 2        | 1.11%   |
| OPNsense 21.1.5     | 2        | 1.11%   |
| OPNsense 21.1.4     | 2        | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 94       | 77.05%  |
| FreeBSD     | 12       | 9.84%   |
| OpenBSD     | 9        | 7.38%   |
| helloSystem | 4        | 3.28%   |
| TrueNAS     | 2        | 1.64%   |
| GhostBSD    | 1        | 0.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 119      | 97.54%  |
| sparc64 | 2        | 1.64%   |
| i386    | 1        | 0.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 107      | 85.6%   |
| helloDesktop  | 5        | 4%      |
| KDE5          | 3        | 2.4%    |
| fvwm          | 3        | 2.4%    |
| LXQt          | 2        | 1.6%    |
| XFCE          | 1        | 0.8%    |
| MATE          | 1        | 0.8%    |
| i3            | 1        | 0.8%    |
| Enlightenment | 1        | 0.8%    |
| CDE           | 1        | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 109      | 89.34%  |
| X11     | 13       | 10.66%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 113      | 92.62%  |
| SLiM    | 4        | 3.28%   |
| LightDM | 2        | 1.64%   |
| XDM     | 1        | 0.82%   |
| SDDM    | 1        | 0.82%   |
| GDM     | 1        | 0.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 105      | 84%     |
| en_US   | 9        | 7.2%    |
| C       | 8        | 6.4%    |
| de_DE   | 2        | 1.6%    |
| de_CH   | 1        | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 108      | 88.52%  |
| BIOS | 14       | 11.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 71       | 57.72%  |
| Zfs    | 42       | 34.15%  |
| Ffs    | 9        | 7.32%   |
| Cd9660 | 1        | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 113      | 91.87%  |
| MBR     | 9        | 7.32%   |
| Unknown | 1        | 0.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| PC Engines          | 34       | 27.87%  |
| Unknown             | 13       | 10.66%  |
| Hewlett-Packard     | 9        | 7.38%   |
| Gigabyte Technology | 8        | 6.56%   |
| ASUSTek Computer    | 8        | 6.56%   |
| ASRock              | 7        | 5.74%   |
| Supermicro          | 5        | 4.1%    |
| Dell                | 5        | 4.1%    |
| Protectli           | 4        | 3.28%   |
| Shuttle             | 3        | 2.46%   |
| Intel               | 3        | 2.46%   |
| Apple               | 3        | 2.46%   |
| Techvision          | 2        | 1.64%   |
| Sun                 | 2        | 1.64%   |
| ASRockRack          | 2        | 1.64%   |
| Acer                | 2        | 1.64%   |
| YANYU               | 1        | 0.82%   |
| MW                  | 1        | 0.82%   |
| Lenovo              | 1        | 0.82%   |
| Intel BOX4A200      | 1        | 0.82%   |
| Infoblox            | 1        | 0.82%   |
| HPE                 | 1        | 0.82%   |
| GoWin Solution      | 1        | 0.82%   |
| Fujitsu             | 1        | 0.82%   |
| CWWK                | 1        | 0.82%   |
| Biostar             | 1        | 0.82%   |
| BESSTAR Tech        | 1        | 0.82%   |
| ADI Engineering     | 1        | 0.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| PC Engines APU2                          | 18       | 14.75%  |
| PC Engines apu4                          | 13       | 10.66%  |
| Unknown                                  | 13       | 10.66%  |
| Protectli FW6                            | 3        | 2.46%   |
| ASRock A320M-ITX                         | 3        | 2.46%   |
| Techvision TVI7309X                      | 2        | 1.64%   |
| Shuttle DS10U                            | 2        | 1.64%   |
| PC Engines apu6                          | 2        | 1.64%   |
| Dell Precision 3440                      | 2        | 1.64%   |
| Apple MacPro5,1                          | 2        | 1.64%   |
| YANYU D19SL_B                            | 1        | 0.82%   |
| Supermicro X9SCL/X9SCM                   | 1        | 0.82%   |
| Supermicro SYS-1019D-4C-FHN13TP          | 1        | 0.82%   |
| Supermicro SYS-1019D-16C-RAN13TP+        | 1        | 0.82%   |
| Supermicro PDSML                         | 1        | 0.82%   |
| Supermicro AS -5019D-FTN4                | 1        | 0.82%   |
| Sun SUNW,Sun-Blade-1500                  | 1        | 0.82%   |
| Sun SUNW,Sun-Blade-100                   | 1        | 0.82%   |
| Shuttle TERRA_PC                         | 1        | 0.82%   |
| Protectli FW4C                           | 1        | 0.82%   |
| PC Engines APU3                          | 1        | 0.82%   |
| MW GMLK-2_5G4L                           | 1        | 0.82%   |
| Lenovo ThinkCentre M75t Gen 2 11KECTO1WW | 1        | 0.82%   |
| Intel Q3XXG4-P V1.0                      | 1        | 0.82%   |
| Intel HURONRIVER                         | 1        | 0.82%   |
| Intel D54250WYK H13922-303               | 1        | 0.82%   |
| Intel BOX4A200 Geminilake                | 1        | 0.82%   |
| Infoblox IB-1410                         | 1        | 0.82%   |
| HPE ProLiant MicroServer Gen10           | 1        | 0.82%   |
| HP Z620 Workstation                      | 1        | 0.82%   |
| HP Z600 Workstation                      | 1        | 0.82%   |
| HP ProLiant ML350p Gen8                  | 1        | 0.82%   |
| HP ProLiant MicroServer Gen8             | 1        | 0.82%   |
| HP EliteDesk 800 G3 SFF                  | 1        | 0.82%   |
| HP Compaq Elite 8300 SFF                 | 1        | 0.82%   |
| HP Compaq Elite 8300 CMT                 | 1        | 0.82%   |
| HP Compaq 8200 Elite SFF PC              | 1        | 0.82%   |
| HP Compaq 8200 Elite CMT PC              | 1        | 0.82%   |
| GoWin Solution R86S                      | 1        | 0.82%   |
| Gigabyte X570 AORUS MASTER               | 1        | 0.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| PC Engines APU2                   | 18       | 14.75%  |
| PC Engines apu4                   | 13       | 10.66%  |
| Unknown                           | 13       | 10.66%  |
| HP Compaq                         | 4        | 3.28%   |
| Protectli FW6                     | 3        | 2.46%   |
| ASRock A320M-ITX                  | 3        | 2.46%   |
| Techvision TVI7309X               | 2        | 1.64%   |
| Sun SUNW                          | 2        | 1.64%   |
| Shuttle DS10U                     | 2        | 1.64%   |
| PC Engines apu6                   | 2        | 1.64%   |
| HP ProLiant                       | 2        | 1.64%   |
| Dell Precision                    | 2        | 1.64%   |
| Dell OptiPlex                     | 2        | 1.64%   |
| ASUS PRIME                        | 2        | 1.64%   |
| Apple MacPro5                     | 2        | 1.64%   |
| Acer Aspire                       | 2        | 1.64%   |
| YANYU D19SL                       | 1        | 0.82%   |
| Supermicro X9SCL                  | 1        | 0.82%   |
| Supermicro SYS-1019D-4C-FHN13TP   | 1        | 0.82%   |
| Supermicro SYS-1019D-16C-RAN13TP+ | 1        | 0.82%   |
| Supermicro PDSML                  | 1        | 0.82%   |
| Supermicro AS                     | 1        | 0.82%   |
| Shuttle TERRA                     | 1        | 0.82%   |
| Protectli FW4C                    | 1        | 0.82%   |
| PC Engines APU3                   | 1        | 0.82%   |
| MW GMLK-2                         | 1        | 0.82%   |
| Lenovo ThinkCentre                | 1        | 0.82%   |
| Intel Q3XXG4-P                    | 1        | 0.82%   |
| Intel HURONRIVER                  | 1        | 0.82%   |
| Intel D54250WYK                   | 1        | 0.82%   |
| Intel BOX4A200 Geminilake         | 1        | 0.82%   |
| Infoblox IB-1410                  | 1        | 0.82%   |
| HPE ProLiant                      | 1        | 0.82%   |
| HP Z620                           | 1        | 0.82%   |
| HP Z600                           | 1        | 0.82%   |
| HP EliteDesk                      | 1        | 0.82%   |
| GoWin Solution R86S               | 1        | 0.82%   |
| Gigabyte X570                     | 1        | 0.82%   |
| Gigabyte X399                     | 1        | 0.82%   |
| Gigabyte H97N-WIFI                | 1        | 0.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 23       | 18.85%  |
| 2016    | 21       | 17.21%  |
| 2020    | 18       | 14.75%  |
| 2022    | 12       | 9.84%   |
| 2019    | 8        | 6.56%   |
| 2012    | 8        | 6.56%   |
| 2021    | 6        | 4.92%   |
| 2013    | 5        | 4.1%    |
| 2017    | 4        | 3.28%   |
| 2015    | 4        | 3.28%   |
| 2011    | 3        | 2.46%   |
| Unknown | 3        | 2.46%   |
| 2023    | 2        | 1.64%   |
| 2008    | 2        | 1.64%   |
| 2014    | 1        | 0.82%   |
| 2010    | 1        | 0.82%   |
| 2007    | 1        | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 122      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 68.85%  |
| Yes  | 38       | 31.15%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 37       | 29.6%   |
| 16.01-24.0  | 31       | 24.8%   |
| 8.01-16.0   | 30       | 24%     |
| 32.01-64.0  | 13       | 10.4%   |
| 64.01-256.0 | 7        | 5.6%    |
| 2.01-3.0    | 4        | 3.2%    |
| 1.01-2.0    | 1        | 0.8%    |
| 0.01-0.5    | 1        | 0.8%    |
| Unknown     | 1        | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 57       | 43.85%  |
| 0.51-1.0   | 40       | 30.77%  |
| 1.01-2.0   | 12       | 9.23%   |
| 2.01-3.0   | 8        | 6.15%   |
| 4.01-8.0   | 4        | 3.08%   |
| 3.01-4.0   | 3        | 2.31%   |
| 8.01-16.0  | 2        | 1.54%   |
| 0          | 2        | 1.54%   |
| 16.01-24.0 | 1        | 0.77%   |
| Unknown    | 1        | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 69.6%   |
| 0      | 16       | 12.8%   |
| 2      | 5        | 4%      |
| 4      | 4        | 3.2%    |
| 3      | 4        | 3.2%    |
| 6      | 3        | 2.4%    |
| 5      | 2        | 1.6%    |
| 17     | 1        | 0.8%    |
| 16     | 1        | 0.8%    |
| 8      | 1        | 0.8%    |
| 7      | 1        | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 85.25%  |
| Yes       | 18       | 14.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 99.18%  |
| No        | 1        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 86.07%  |
| Yes       | 17       | 13.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 89.34%  |
| Yes       | 13       | 10.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Switzerland | 122      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Zurich                             | 29       | 20%     |
| Winterthur                         | 6        | 4.14%   |
| Gachnang                           | 6        | 4.14%   |
| Gordola                            | 5        | 3.45%   |
| Lausanne                           | 4        | 2.76%   |
| St. Moritz                         | 3        | 2.07%   |
| St. Gallen                         | 3        | 2.07%   |
| Lenzburg                           | 3        | 2.07%   |
| Basel                              | 3        | 2.07%   |
| Siggenthal Station                 | 2        | 1.38%   |
| Riehen                             | 2        | 1.38%   |
| Ottenbach                          | 2        | 1.38%   |
| Oensingen                          | 2        | 1.38%   |
| Mettmenstetten                     | 2        | 1.38%   |
| Lucerne                            | 2        | 1.38%   |
| Horgen                             | 2        | 1.38%   |
| Geneva                             | 2        | 1.38%   |
| Dietikon                           | 2        | 1.38%   |
| Burgdorf                           | 2        | 1.38%   |
| Bern                               | 2        | 1.38%   |
| Yverdon-les-Bains                  | 1        | 0.69%   |
| Yens                               | 1        | 0.69%   |
| Worblaufen                         | 1        | 0.69%   |
| Willisau                           | 1        | 0.69%   |
| Wiesendangen / Wiesendangen (Dorf) | 1        | 0.69%   |
| Wetzikon                           | 1        | 0.69%   |
| Wettswil                           | 1        | 0.69%   |
| Welschenrohr                       | 1        | 0.69%   |
| Uster                              | 1        | 0.69%   |
| Trogen                             | 1        | 0.69%   |
| Suhr                               | 1        | 0.69%   |
| Steckborn                          | 1        | 0.69%   |
| Stallikon                          | 1        | 0.69%   |
| Sitterdorf                         | 1        | 0.69%   |
| Sissach                            | 1        | 0.69%   |
| Rumlang                            | 1        | 0.69%   |
| Riviera                            | 1        | 0.69%   |
| Rickenbach bei Wil                 | 1        | 0.69%   |
| Richterswil                        | 1        | 0.69%   |
| Renens                             | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 27       | 51     | 21.43%  |
| WDC                 | 13       | 33     | 10.32%  |
| Phison              | 13       | 16     | 10.32%  |
| Kingston            | 11       | 15     | 8.73%   |
| Seagate             | 7        | 10     | 5.56%   |
| China               | 6        | 7      | 4.76%   |
| Intel               | 5        | 21     | 3.97%   |
| Hoodisk             | 5        | 7      | 3.97%   |
| Crucial             | 5        | 12     | 3.97%   |
| Toshiba             | 3        | 4      | 2.38%   |
| HPT                 | 3        | 35     | 2.38%   |
| Hitachi             | 3        | 3      | 2.38%   |
| Corsair             | 3        | 4      | 2.38%   |
| SK hynix            | 2        | 2      | 1.59%   |
| Silicon Motion      | 2        | 2      | 1.59%   |
| ShiJi               | 2        | 8      | 1.59%   |
| SanDisk             | 2        | 5      | 1.59%   |
| Transcend           | 1        | 1      | 0.79%   |
| SPCC                | 1        | 2      | 0.79%   |
| Protectli           | 1        | 1      | 0.79%   |
| PNY                 | 1        | 1      | 0.79%   |
| OPENBSD             | 1        | 1      | 0.79%   |
| Micron Technology   | 1        | 2      | 0.79%   |
| KingSpec            | 1        | 1      | 0.79%   |
| Intenso             | 1        | 3      | 0.79%   |
| Hewlett-Packard     | 1        | 10     | 0.79%   |
| FORESEE             | 1        | 1      | 0.79%   |
| Fanxiang            | 1        | 1      | 0.79%   |
| BIWIN               | 1        | 1      | 0.79%   |
| Apple               | 1        | 1      | 0.79%   |
| A-DATA Technology   | 1        | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Phison SATA SSD 16GB              | 10       | 5.88%   |
| Hoodisk SSD 32GB                  | 5        | 2.94%   |
| Samsung SSD 860 EVO 250GB         | 4        | 2.35%   |
| Samsung SSD 860 PRO 256GB         | 3        | 1.76%   |
| Phison SATA SSD 32GB              | 3        | 1.76%   |
| Kingston RBUSNS8180DS3128GH 128GB | 3        | 1.76%   |
| HPT DISK 0_3 1TB                  | 3        | 1.76%   |
| HPT DISK 0_2 1TB                  | 3        | 1.76%   |
| HPT DISK 0_1 1TB                  | 3        | 1.76%   |
| HPT DISK 0_0 4TB                  | 3        | 1.76%   |
| China SATA SSD 16GB               | 3        | 1.76%   |
| WDC WD6002FRYZ-01WD5B1 6TB        | 2        | 1.18%   |
| WDC WD30EFRX-68EUZN0 3TB          | 2        | 1.18%   |
| ShiJi SSD 128GB                   | 2        | 1.18%   |
| Samsung SSD 980 PRO 250GB         | 2        | 1.18%   |
| Samsung SSD 960 EVO 250GB         | 2        | 1.18%   |
| Samsung SSD 850 PRO 256GB         | 2        | 1.18%   |
| Samsung SSD 840 Series 120GB      | 2        | 1.18%   |
| HPT DISK 0_9 3TB                  | 2        | 1.18%   |
| HPT DISK 0_8 3TB                  | 2        | 1.18%   |
| HPT DISK 0_7 1TB                  | 2        | 1.18%   |
| HPT DISK 0_6 1TB                  | 2        | 1.18%   |
| HPT DISK 0_5 1TB                  | 2        | 1.18%   |
| HPT DISK 0_4 1TB                  | 2        | 1.18%   |
| HPT DISK 0_14 3TB                 | 2        | 1.18%   |
| HPT DISK 0_13 2TB                 | 2        | 1.18%   |
| HPT DISK 0_12 1TB                 | 2        | 1.18%   |
| HPT DISK 0_11 1TB                 | 2        | 1.18%   |
| HPT DISK 0_10 1TB                 | 2        | 1.18%   |
| Hitachi HDS721050CLA360 500GB     | 2        | 1.18%   |
| Crucial CT250MX500SSD1 250GB      | 2        | 1.18%   |
| WDC WDS500G1R0A-68A4W0 500GB      | 1        | 0.59%   |
| WDC WDS250G2B0C-00PXH0 250GB      | 1        | 0.59%   |
| WDC WDS240G2G0B-00EPW0 240GB      | 1        | 0.59%   |
| WDC WDS120G2G0B-00EPW0 120GB      | 1        | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB      | 1        | 0.59%   |
| WDC WD60EFRX-68L0BN1 6TB          | 1        | 0.59%   |
| WDC WD40EFZX-68AWUN0 4TB          | 1        | 0.59%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 0.59%   |
| WDC WD2500AAJS-00VTA0 250GB       | 1        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 24     | 28.57%  |
| Seagate             | 7        | 10     | 25%     |
| HPT                 | 3        | 35     | 10.71%  |
| Hitachi             | 3        | 3      | 10.71%  |
| Toshiba             | 2        | 3      | 7.14%   |
| Samsung Electronics | 1        | 1      | 3.57%   |
| OPENBSD             | 1        | 1      | 3.57%   |
| Hewlett-Packard     | 1        | 10     | 3.57%   |
| China               | 1        | 1      | 3.57%   |
| Apple               | 1        | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 37     | 21.69%  |
| Phison              | 13       | 16     | 15.66%  |
| Kingston            | 9        | 11     | 10.84%  |
| Intel               | 5        | 21     | 6.02%   |
| Hoodisk             | 5        | 7      | 6.02%   |
| Crucial             | 5        | 12     | 6.02%   |
| China               | 5        | 6      | 6.02%   |
| WDC                 | 4        | 7      | 4.82%   |
| SK hynix            | 2        | 2      | 2.41%   |
| ShiJi               | 2        | 8      | 2.41%   |
| SanDisk             | 2        | 5      | 2.41%   |
| Corsair             | 2        | 3      | 2.41%   |
| Transcend           | 1        | 1      | 1.2%    |
| Toshiba             | 1        | 1      | 1.2%    |
| SPCC                | 1        | 2      | 1.2%    |
| Protectli           | 1        | 1      | 1.2%    |
| PNY                 | 1        | 1      | 1.2%    |
| Micron Technology   | 1        | 2      | 1.2%    |
| KingSpec            | 1        | 1      | 1.2%    |
| Intenso             | 1        | 3      | 1.2%    |
| FORESEE             | 1        | 1      | 1.2%    |
| BIWIN               | 1        | 1      | 1.2%    |
| A-DATA Technology   | 1        | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 80       | 150    | 67.8%   |
| HDD  | 20       | 89     | 16.95%  |
| NVMe | 18       | 23     | 15.25%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 89       | 239    | 83.18%  |
| NVMe | 18       | 23     | 16.82%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 87       | 165    | 74.36%  |
| 0.51-1.0   | 9        | 37     | 7.69%   |
| 1.01-2.0   | 7        | 10     | 5.98%   |
| 3.01-4.0   | 5        | 5      | 4.27%   |
| 2.01-3.0   | 5        | 13     | 4.27%   |
| 4.01-10.0  | 4        | 9      | 3.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 59       | 46.83%  |
| 1-20       | 22       | 17.46%  |
| 51-100     | 17       | 13.49%  |
| 21-50      | 13       | 10.32%  |
| 251-500    | 7        | 5.56%   |
| 501-1000   | 5        | 3.97%   |
| 1001-2000  | 2        | 1.59%   |
| 2001-3000  | 1        | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 115      | 89.84%  |
| 21-50   | 7        | 5.47%   |
| 51-100  | 4        | 3.13%   |
| 251-500 | 2        | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB    | 1        | 2      | 6.67%   |
| WDC WD6002FRYZ-01WD5B1 6TB      | 1        | 6      | 6.67%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1        | 1      | 6.67%   |
| WDC WD30EFRX-68EUZN0 3TB        | 1        | 1      | 6.67%   |
| WDC WD2002FYPS-01U1B0 2TB       | 1        | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB           | 1        | 1      | 6.67%   |
| Seagate ST3500413AS 500GB       | 1        | 1      | 6.67%   |
| Seagate ST2000VN004-2E4164 2TB  | 1        | 2      | 6.67%   |
| Samsung Electronics HD204UI 2TB | 1        | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB    | 1        | 1      | 6.67%   |
| Intel SSDSC2BW240A4 240GB       | 1        | 2      | 6.67%   |
| Intel SSDSA2M160G2GC 160GB      | 1        | 2      | 6.67%   |
| Intel SSDSA2BW160G3H 160GB      | 1        | 5      | 6.67%   |
| Hitachi HDS721050CLA660 500GB   | 1        | 1      | 6.67%   |
| Corsair Force 3 SSD 120GB       | 1        | 2      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 11     | 28.57%  |
| Intel               | 3        | 9      | 21.43%  |
| Seagate             | 2        | 3      | 14.29%  |
| Toshiba             | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Kingston            | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| Corsair             | 1        | 2      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 9      | 37.5%   |
| Seagate             | 2        | 3      | 25%     |
| Toshiba             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 6        | 14     | 50%     |
| HDD  | 6        | 15     | 50%     |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 97       | 188    | 85.09%  |
| Malfunc  | 11       | 29     | 9.65%   |
| Detected | 6        | 45     | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 65       | 43.05%  |
| AMD                         | 51       | 33.77%  |
| Samsung Electronics         | 11       | 7.28%   |
| Silicon Motion              | 3        | 1.99%   |
| SanDisk                     | 3        | 1.99%   |
| HighPoint Technologies      | 3        | 1.99%   |
| ASMedia Technology          | 3        | 1.99%   |
| ULi Electronics             | 2        | 1.32%   |
| Marvell Technology Group    | 2        | 1.32%   |
| Kingston Technology Company | 2        | 1.32%   |
| JMicron Technology          | 2        | 1.32%   |
| Phison Electronics          | 1        | 0.66%   |
| Hewlett-Packard             | 1        | 0.66%   |
| Chelsio Communications      | 1        | 0.66%   |
| Broadcom / LSI              | 1        | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34       | 19.88%  |
| AMD FCH SATA Controller [IDE mode]                                             | 11       | 6.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 3.51%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5        | 2.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 2.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 2.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 2.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4        | 2.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4        | 2.34%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 2.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 1.75%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 3        | 1.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3        | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 1.75%   |
| AMD FCH SATA Controller D                                                      | 3        | 1.75%   |
| ULi M5229 IDE                                                                  | 2        | 1.17%   |
| JMicron JMB58x AHCI SATA controller                                            | 2        | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 1.17%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2        | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.17%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2        | 1.17%   |
| Intel Atom Processor C3000 Series SATA Controller 1                            | 2        | 1.17%   |
| Intel Atom Processor C3000 Series SATA Controller 0                            | 2        | 1.17%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.17%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 1.17%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 2        | 1.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.17%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.58%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.58%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.58%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1        | 0.58%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.58%   |
| Kingston Company unknown                                                       | 1        | 0.58%   |
| Kingston Company NVMe Controller                                               | 1        | 0.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 100      | 66.23%  |
| NVMe | 20       | 13.25%  |
| IDE  | 19       | 12.58%  |
| RAID | 8        | 5.3%    |
| SAS  | 2        | 1.32%   |
| SCSI | 2        | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 69       | 56.56%  |
| AMD     | 51       | 41.8%   |
| Unknown | 2        | 1.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 34       | 27.87%  |
| Intel Celeron CPU 3865U @ 1.80GHz           | 4        | 3.28%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 2.46%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 2.46%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.64%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 2        | 1.64%   |
| Intel Celeron N5105 @ 2.00GHz               | 2        | 1.64%   |
| Intel Celeron N5100 @ 1.10GHz               | 2        | 1.64%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 2        | 1.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2        | 1.64%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.64%   |
|                                             | 2        | 1.64%   |
| Intel Xeon D-2183IT CPU @ 2.20GHz           | 1        | 0.82%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 1        | 0.82%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1        | 0.82%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 0.82%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.82%   |
| Intel Xeon CPU E5630 @ 2.53GHz              | 1        | 0.82%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.82%   |
| Intel Xeon CPU E5-2620 @ 2.00GHz            | 1        | 0.82%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.82%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.82%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz        | 1        | 0.82%   |
| Intel Xeon CPU E                            | 1        | 0.82%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.82%   |
| Intel Pentium Gold G7400                    | 1        | 0.82%   |
| Intel Pentium CPU J3710 @ 1.60GHz           | 1        | 0.82%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.82%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.82%   |
| Intel Core i7-2600K CPU                     | 1        | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1        | 0.82%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.82%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1        | 0.82%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 0.82%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD GX                 | 35       | 28.69%  |
| Intel Core i5          | 16       | 13.11%  |
| Intel Celeron          | 14       | 11.48%  |
| Intel Xeon             | 12       | 9.84%   |
| Intel Core i7          | 8        | 6.56%   |
| Other                  | 6        | 4.92%   |
| Intel Core i3          | 6        | 4.92%   |
| AMD Ryzen 7            | 4        | 3.28%   |
| AMD Ryzen 5            | 4        | 3.28%   |
| Intel Atom             | 3        | 2.46%   |
| Intel Pentium          | 2        | 1.64%   |
| Intel Core 2 Duo       | 2        | 1.64%   |
| AMD Ryzen 7 PRO        | 2        | 1.64%   |
| Intel Pentium Silver   | 1        | 0.82%   |
| Intel Pentium Gold     | 1        | 0.82%   |
| AMD Ryzen Threadripper | 1        | 0.82%   |
| AMD Ryzen 3            | 1        | 0.82%   |
| AMD Opteron            | 1        | 0.82%   |
| AMD Geode Integrated   | 1        | 0.82%   |
| AMD FX                 | 1        | 0.82%   |
| AMD EPYC               | 1        | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 74       | 60.66%  |
| 2       | 16       | 13.11%  |
| 8       | 11       | 9.02%   |
| 16      | 8        | 6.56%   |
| 6       | 4        | 3.28%   |
| 1       | 3        | 2.46%   |
| 12      | 2        | 1.64%   |
| Unknown | 2        | 1.64%   |
| 32      | 1        | 0.82%   |
| 10      | 1        | 0.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 116      | 95.08%  |
| 2       | 3        | 2.46%   |
| Unknown | 2        | 1.64%   |
| 4       | 1        | 0.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 85       | 69.67%  |
| 2       | 33       | 27.05%  |
| Unknown | 4        | 3.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 34       | 27.87%  |
| KabyLake      | 13       | 10.66%  |
| Unknown       | 10       | 8.2%    |
| IvyBridge     | 8        | 6.56%   |
| SandyBridge   | 7        | 5.74%   |
| Haswell       | 6        | 4.92%   |
| Zen 3         | 5        | 4.1%    |
| Skylake       | 5        | 4.1%    |
| Zen           | 4        | 3.28%   |
| Goldmont plus | 4        | 3.28%   |
| Zen+          | 3        | 2.46%   |
| Silvermont    | 3        | 2.46%   |
| Westmere      | 2        | 1.64%   |
| TigerLake     | 2        | 1.64%   |
| Nehalem       | 2        | 1.64%   |
| Goldmont      | 2        | 1.64%   |
| Core          | 2        | 1.64%   |
| CometLake     | 2        | 1.64%   |
| Zen 2         | 1        | 0.82%   |
| Piledriver    | 1        | 0.82%   |
| Penryn        | 1        | 0.82%   |
| Jaguar        | 1        | 0.82%   |
| IceLake       | 1        | 0.82%   |
| Geode         | 1        | 0.82%   |
| Excavator     | 1        | 0.82%   |
| Broadwell     | 1        | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 47       | 54.65%  |
| AMD                                          | 14       | 16.28%  |
| Nvidia                                       | 12       | 13.95%  |
| ASPEED Technology                            | 7        | 8.14%   |
| Matrox Electronics Systems                   | 4        | 4.65%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 1.16%   |
| 3DLabs                                       | 1        | 1.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 8.14%   |
| Intel JasperLake [UHD Graphics]                                                          | 5        | 5.81%   |
| Intel HD Graphics 610                                                                    | 4        | 4.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4        | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 4.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3        | 3.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 3.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 3.49%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 2.33%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2        | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 2.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 2.33%   |
| Intel HD Graphics 530                                                                    | 2        | 2.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 2.33%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2        | 2.33%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)                           | 1        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 1.16%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.16%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.16%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 1.16%   |
| Nvidia GK107 [GeForce GT 640 OEM]                                                        | 1        | 1.16%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 1        | 1.16%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 1.16%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 1.16%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 1        | 1.16%   |
| Nvidia G92 [GeForce 8800 GT]                                                             | 1        | 1.16%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1        | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1        | 1.16%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.16%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 1        | 1.16%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 1        | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 46       | 37.7%   |
| Other          | 37       | 30.33%  |
| 1 x AMD        | 14       | 11.48%  |
| 1 x Nvidia     | 11       | 9.02%   |
| 1 x ASPEED     | 7        | 5.74%   |
| 1 x Matrox     | 4        | 3.28%   |
| 1 x XGI        | 1        | 0.82%   |
| Intel + Nvidia | 1        | 0.82%   |
| 1 x 3DLabs     | 1        | 0.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 74       | 60.66%  |
| Unknown     | 40       | 32.79%  |
| Proprietary | 8        | 6.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 112      | 91.8%   |
| 1.01-2.0   | 4        | 3.28%   |
| 3.01-4.0   | 3        | 2.46%   |
| 5.01-6.0   | 1        | 0.82%   |
| 2.01-3.0   | 1        | 0.82%   |
| 0.01-0.5   | 1        | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2        | 15.38%  |
| Acer                 | 2        | 15.38%  |
| Philips              | 1        | 7.69%   |
| NEC Computers        | 1        | 7.69%   |
| LG Electronics       | 1        | 7.69%   |
| Lenovo               | 1        | 7.69%   |
| Iiyama               | 1        | 7.69%   |
| Fujitsu Siemens      | 1        | 7.69%   |
| Eizo                 | 1        | 7.69%   |
| BenQ                 | 1        | 7.69%   |
| Ancor Communications | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics U32E850 SAM0CE3 3840x2160 700x390mm 31.5-inch | 1        | 7.14%   |
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch | 1        | 7.14%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                | 1        | 7.14%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                      | 1        | 7.14%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                 | 1        | 7.14%   |
| LG Electronics LCD Monitor LG Ultra HD                            | 1        | 7.14%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch          | 1        | 7.14%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch             | 1        | 7.14%   |
| Fujitsu Siemens S19-1 FUS0517 1280x1024 380x300mm 19.1-inch       | 1        | 7.14%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                | 1        | 7.14%   |
| BenQ GW2250H BNQ78BD 1920x1080 480x270mm 21.7-inch                | 1        | 7.14%   |
| Ancor Communications VS278 ACI27A1 1920x1080 600x340mm 27.2-inch  | 1        | 7.14%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                | 1        | 7.14%   |
| Acer XB271HU A ACR052F 2560x1440 600x340mm 27.2-inch              | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 6        | 42.86%  |
| 2560x1440 (QHD)  | 3        | 21.43%  |
| 3840x2160 (4K)   | 2        | 14.29%  |
| 1280x1024 (SXGA) | 1        | 7.14%   |
| 11520x2160       | 1        | 7.14%   |
| Unknown          | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 38.46%  |
| 31      | 2        | 15.38%  |
| Unknown | 2        | 15.38%  |
| 65      | 1        | 7.69%   |
| 23      | 1        | 7.69%   |
| 21      | 1        | 7.69%   |
| 19      | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 46.15%  |
| 601-700     | 2        | 15.38%  |
| Unknown     | 2        | 15.38%  |
| 401-500     | 1        | 7.69%   |
| 351-400     | 1        | 7.69%   |
| 1001-1500   | 1        | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 76.92%  |
| Unknown | 2        | 15.38%  |
| 5/4     | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 5        | 38.46%  |
| 351-500        | 2        | 15.38%  |
| 201-250        | 2        | 15.38%  |
| Unknown        | 2        | 15.38%  |
| More than 1000 | 1        | 7.69%   |
| 151-200        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 4        | 30.77%  |
| 51-100  | 4        | 30.77%  |
| 121-160 | 2        | 15.38%  |
| Unknown | 2        | 15.38%  |
| 1-50    | 1        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 109      | 89.34%  |
| 1     | 12       | 9.84%   |
| 2     | 1        | 0.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 106      | 67.09%  |
| Realtek Semiconductor             | 23       | 14.56%  |
| Broadcom                          | 8        | 5.06%   |
| Qualcomm Atheros                  | 4        | 2.53%   |
| Mellanox Technologies             | 3        | 1.9%    |
| Huawei Technologies               | 2        | 1.27%   |
| American Megatrends               | 2        | 1.27%   |
| VIA Technologies                  | 1        | 0.63%   |
| U-Blox                            | 1        | 0.63%   |
| Qualcomm Atheros Communications   | 1        | 0.63%   |
| QLogic                            | 1        | 0.63%   |
| Oracle/SUN                        | 1        | 0.63%   |
| Microchip Technology              | 1        | 0.63%   |
| Free Software Initiative of Japan | 1        | 0.63%   |
| Edimax Technology                 | 1        | 0.63%   |
| Chelsio Communications            | 1        | 0.63%   |
| Aquantia                          | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 34       | 16.67%  |
| Intel I210 Gigabit Network Connection                                         | 23       | 11.27%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 18       | 8.82%   |
| Intel Ethernet Controller I225-V                                              | 8        | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 3.43%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 2.94%   |
| Intel I350 Gigabit Network Connection                                         | 5        | 2.45%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 2.45%   |
| Intel Ethernet Controller I226-V                                              | 4        | 1.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 1.96%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 1.47%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3        | 1.47%   |
| Intel Ethernet Controller X550                                                | 3        | 1.47%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 1.47%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.47%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2        | 0.98%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 0.98%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 0.98%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 0.98%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 0.98%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 0.98%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 0.98%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.98%   |
| American Megatrends Virtual Ethernet                                          | 2        | 0.98%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.49%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.49%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.49%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.49%   |
| Microchip CDC RS-232 Emulation Demo                                           | 1        | 0.49%   |
| Mellanox MT2894 Family [ConnectX-6 Lx]                                        | 1        | 0.49%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1        | 0.49%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 47.06%  |
| Realtek Semiconductor           | 3        | 17.65%  |
| Qualcomm Atheros                | 3        | 17.65%  |
| Qualcomm Atheros Communications | 1        | 5.88%   |
| Edimax Technology               | 1        | 5.88%   |
| Broadcom                        | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3        | 17.65%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 11.76%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2        | 11.76%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 5.88%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 5.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 5.88%   |
| Intel Wireless 8265 / 8275                                     | 1        | 5.88%   |
| Intel Wireless 7260                                            | 1        | 5.88%   |
| Intel Wireless 3160                                            | 1        | 5.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 5.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 5.88%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]       | 1        | 5.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 103      | 74.1%   |
| Realtek Semiconductor  | 20       | 14.39%  |
| Broadcom               | 7        | 5.04%   |
| American Megatrends    | 2        | 1.44%   |
| VIA Technologies       | 1        | 0.72%   |
| Qualcomm Atheros       | 1        | 0.72%   |
| QLogic                 | 1        | 0.72%   |
| Oracle/SUN             | 1        | 0.72%   |
| Huawei Technologies    | 1        | 0.72%   |
| Chelsio Communications | 1        | 0.72%   |
| Aquantia               | 1        | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 34       | 18.89%  |
| Intel I210 Gigabit Network Connection                                         | 23       | 12.78%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 18       | 10%     |
| Intel Ethernet Controller I225-V                                              | 8        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 3.89%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 3.33%   |
| Intel I350 Gigabit Network Connection                                         | 5        | 2.78%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 2.78%   |
| Intel Ethernet Controller I226-V                                              | 4        | 2.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.22%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3        | 1.67%   |
| Intel Ethernet Controller X550                                                | 3        | 1.67%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 1.67%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.67%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.67%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 1.11%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 1.11%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 1.11%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.11%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.11%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 1.11%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 1.11%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.11%   |
| American Megatrends Virtual Ethernet                                          | 2        | 1.11%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.56%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.56%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.56%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1        | 0.56%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1        | 0.56%   |
| Intel Ethernet Controller E810-XXV for SFP                                    | 1        | 0.56%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.56%   |
| Intel Ethernet Connection I354                                                | 1        | 0.56%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.56%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.56%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.56%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 121      | 84.03%  |
| WiFi     | 16       | 11.11%  |
| Unknown  | 4        | 2.78%   |
| Modem    | 3        | 2.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 98.31%  |
| WiFi     | 2        | 1.69%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 33       | 26.83%  |
| 4     | 30       | 24.39%  |
| 6     | 15       | 12.2%   |
| 5     | 14       | 11.38%  |
| 1     | 14       | 11.38%  |
| 2     | 9        | 7.32%   |
| 13    | 3        | 2.44%   |
| 8     | 2        | 1.63%   |
| 7     | 2        | 1.63%   |
| 14    | 1        | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 73.48%  |
| Yes  | 35       | 26.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 7        | 53.85%  |
| IMC Networks     | 2        | 15.38%  |
| ASUSTek Computer | 2        | 15.38%  |
| Apple            | 2        | 15.38%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                          | 3        | 23.08%  |
| Intel Bluetooth wireless interface             | 2        | 15.38%  |
| IMC Networks Realtek Bluetooth Adapter         | 2        | 15.38%  |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 2        | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 7.69%   |
| Intel AX210 Bluetooth                          | 1        | 7.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1        | 7.69%   |
| ASUS Bluetooth Controller                      | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 54       | 64.29%  |
| AMD                   | 16       | 19.05%  |
| Nvidia                | 10       | 11.9%   |
| ULi Electronics       | 2        | 2.38%   |
| Realtek Semiconductor | 1        | 1.19%   |
| Logitech              | 1        | 1.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6        | 6.25%   |
| Intel Jasper Lake HD Audio                                                                        | 5        | 5.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 5.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 3.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3        | 3.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3        | 3.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 3.13%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 2        | 2.08%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2        | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2        | 2.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 2.08%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2        | 2.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2        | 2.08%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                                | 1        | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 1.04%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.04%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.04%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 1.04%   |
| Logitech H600 [Wireless Headset]                                                                  | 1        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1        | 1.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 1.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.04%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 1.04%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 30       | 25.64%  |
| Unknown             | 24       | 20.51%  |
| Samsung Electronics | 13       | 11.11%  |
| SK hynix            | 12       | 10.26%  |
| Crucial             | 10       | 8.55%   |
| Corsair             | 10       | 8.55%   |
| Micron Technology   | 9        | 7.69%   |
| Nanya Technology    | 2        | 1.71%   |
| Hewlett-Packard     | 2        | 1.71%   |
| Unknown (ABCD)      | 1        | 0.85%   |
| Unknown (0x05F7)    | 1        | 0.85%   |
| Unknown (07FB)      | 1        | 0.85%   |
| Tigo                | 1        | 0.85%   |
| Super Talent        | 1        | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 15       | 12.3%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 3        | 2.46%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s           | 3        | 2.46%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s           | 3        | 2.46%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s           | 3        | 2.46%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2133MT/s         | 3        | 2.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 2        | 1.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2        | 1.64%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 2        | 1.64%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s          | 2        | 1.64%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s          | 2        | 1.64%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s          | 2        | 1.64%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s         | 2        | 1.64%   |
| Crucial RAM CT8G4SFRA32A.M8FR 8GB SODIMM DDR4 3200MT/s         | 2        | 1.64%   |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s           | 2        | 1.64%   |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s           | 2        | 1.64%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1        | 0.82%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.82%   |
| Unknown (0x05F7) RAM Module 1GB FB-DIMM DDR2 800MT/s           | 1        | 0.82%   |
| Unknown (07FB) RAM GSA8G4SCL196P-26 8GB SODIMM DDR4 2667MT/s   | 1        | 0.82%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                   | 1        | 0.82%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s          | 1        | 0.82%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1        | 0.82%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                     | 1        | 0.82%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 0.82%   |
| SK hynix RAM Module 1GB FB-DIMM DDR2 800MT/s                   | 1        | 0.82%   |
| SK hynix RAM HMT42GR7MFR4C-PB 16384MB DIMM DDR3 1600MT/s       | 1        | 0.82%   |
| SK hynix RAM HMT41GU6DFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.82%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s           | 1        | 0.82%   |
| SK hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.82%   |
| SK hynix RAM HMA82GU6DJR8N-VK 16GB DIMM DDR4 2667MT/s          | 1        | 0.82%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                   | 1        | 0.82%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s                     | 1        | 0.82%   |
| Samsung RAM Module 16GB DIMM DDR3 1066MT/s                     | 1        | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 1        | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1        | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 1        | 0.82%   |
| Samsung RAM M393B2G70DB0-CK0 16GB DIMM DDR3 1600MT/s           | 1        | 0.82%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s           | 1        | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 51       | 49.04%  |
| DDR4    | 45       | 43.27%  |
| LPDDR4  | 4        | 3.85%   |
| DDR2    | 3        | 2.88%   |
| Unknown | 1        | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 57       | 54.81%  |
| SODIMM       | 42       | 40.38%  |
| Row Of Chips | 3        | 2.88%   |
| RIMM         | 1        | 0.96%   |
| FB-DIMM      | 1        | 0.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 47       | 43.52%  |
| 4096  | 33       | 30.56%  |
| 16384 | 15       | 13.89%  |
| 2048  | 6        | 5.56%   |
| 32768 | 3        | 2.78%   |
| 1024  | 2        | 1.85%   |
| 65536 | 1        | 0.93%   |
| 512   | 1        | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 35       | 30.7%   |
| 1600  | 15       | 13.16%  |
| 3200  | 14       | 12.28%  |
| 2667  | 14       | 12.28%  |
| 2133  | 10       | 8.77%   |
| 2400  | 9        | 7.89%   |
| 2666  | 5        | 4.39%   |
| 667   | 4        | 3.51%   |
| 2933  | 2        | 1.75%   |
| 800   | 2        | 1.75%   |
| 3600  | 1        | 0.88%   |
| 3000  | 1        | 0.88%   |
| 1800  | 1        | 0.88%   |
| 1066  | 1        | 0.88%   |

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

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 57       | 44.88%  |
| 1     | 46       | 36.22%  |
| 2     | 15       | 11.81%  |
| 3     | 8        | 6.3%    |
| 4     | 1        | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 55       | 63.95%  |
| Firewire controller      | 8        | 9.3%    |
| Bluetooth                | 7        | 8.14%   |
| Net/wireless             | 6        | 6.98%   |
| Net/ethernet             | 4        | 4.65%   |
| Sound                    | 2        | 2.33%   |
| Card reader              | 2        | 2.33%   |
| Network                  | 1        | 1.16%   |
| Graphics card            | 1        | 1.16%   |

