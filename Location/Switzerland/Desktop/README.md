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

Total: 212

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OPNsense 22.7       | 7        | 4.22%   |
| OPNsense 21.7.3     | 7        | 4.22%   |
| OPNsense 21.7.1     | 7        | 4.22%   |
| OPNsense 21.1.6     | 7        | 4.22%   |
| OPNsense 20.7.8     | 7        | 4.22%   |
| OPNsense 22.1.8     | 6        | 3.61%   |
| OPNsense 21.7.6     | 5        | 3.01%   |
| OPNsense 23.1       | 4        | 2.41%   |
| OPNsense 22.7.4     | 4        | 2.41%   |
| OPNsense 22.7.10    | 4        | 2.41%   |
| OPNsense 22.1.6     | 4        | 2.41%   |
| OPNsense 22.1.3     | 4        | 2.41%   |
| OPNsense 21.7.7     | 4        | 2.41%   |
| OPNsense 21.1.3     | 4        | 2.41%   |
| OPNsense 21.1       | 4        | 2.41%   |
| OpenBSD 6.8         | 4        | 2.41%   |
| OPNsense 23.1.1     | 3        | 1.81%   |
| OPNsense 22.7.8     | 3        | 1.81%   |
| OPNsense 22.1.7     | 3        | 1.81%   |
| OPNsense 22.1.10    | 3        | 1.81%   |
| OPNsense 22.1.1     | 3        | 1.81%   |
| OPNsense 21.7       | 3        | 1.81%   |
| OPNsense 21.1.8     | 3        | 1.81%   |
| OPNsense 21.1.2     | 3        | 1.81%   |
| FreeBSD 13.1-STABLE | 3        | 1.81%   |
| OPNsense 22.7.9     | 2        | 1.2%    |
| OPNsense 22.1.9     | 2        | 1.2%    |
| OPNsense 22.1.4     | 2        | 1.2%    |
| OPNsense 22.1.2     | 2        | 1.2%    |
| OPNsense 22.1       | 2        | 1.2%    |
| OPNsense 21.7.5     | 2        | 1.2%    |
| OPNsense 21.7.4     | 2        | 1.2%    |
| OPNsense 21.1.9     | 2        | 1.2%    |
| OPNsense 21.1.7     | 2        | 1.2%    |
| OPNsense 21.1.5     | 2        | 1.2%    |
| OPNsense 21.1.4     | 2        | 1.2%    |
| OpenBSD 7.0         | 2        | 1.2%    |
| OpenBSD 6.7         | 2        | 1.2%    |
| FreeBSD 13.1-p2     | 2        | 1.2%    |
| FreeBSD 13.0-p7     | 2        | 1.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 83       | 75.45%  |
| FreeBSD     | 12       | 10.91%  |
| OpenBSD     | 9        | 8.18%   |
| helloSystem | 3        | 2.73%   |
| TrueNAS     | 2        | 1.82%   |
| GhostBSD    | 1        | 0.91%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 107      | 97.27%  |
| sparc64 | 2        | 1.82%   |
| i386    | 1        | 0.91%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 96       | 84.96%  |
| helloDesktop  | 4        | 3.54%   |
| KDE5          | 3        | 2.65%   |
| fvwm          | 3        | 2.65%   |
| LXQt          | 2        | 1.77%   |
| XFCE          | 1        | 0.88%   |
| MATE          | 1        | 0.88%   |
| i3            | 1        | 0.88%   |
| Enlightenment | 1        | 0.88%   |
| CDE           | 1        | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 98       | 89.09%  |
| X11     | 12       | 10.91%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 102      | 92.73%  |
| SLiM    | 3        | 2.73%   |
| LightDM | 2        | 1.82%   |
| XDM     | 1        | 0.91%   |
| SDDM    | 1        | 0.91%   |
| GDM     | 1        | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 83.19%  |
| en_US   | 9        | 7.96%   |
| C       | 8        | 7.08%   |
| de_DE   | 1        | 0.88%   |
| de_CH   | 1        | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 96       | 87.27%  |
| BIOS | 14       | 12.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 65       | 58.56%  |
| Zfs    | 36       | 32.43%  |
| Ffs    | 9        | 8.11%   |
| Cd9660 | 1        | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 101      | 90.99%  |
| MBR     | 9        | 8.11%   |
| Unknown | 1        | 0.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| PC Engines          | 30       | 27.27%  |
| Unknown             | 12       | 10.91%  |
| Hewlett-Packard     | 8        | 7.27%   |
| Gigabyte Technology | 8        | 7.27%   |
| ASUSTek Computer    | 7        | 6.36%   |
| ASRock              | 6        | 5.45%   |
| Dell                | 5        | 4.55%   |
| Supermicro          | 4        | 3.64%   |
| Shuttle             | 3        | 2.73%   |
| Protectli           | 3        | 2.73%   |
| Intel               | 3        | 2.73%   |
| Apple               | 3        | 2.73%   |
| Techvision          | 2        | 1.82%   |
| Sun                 | 2        | 1.82%   |
| ASRockRack          | 2        | 1.82%   |
| Acer                | 2        | 1.82%   |
| YANYU               | 1        | 0.91%   |
| MW                  | 1        | 0.91%   |
| Lenovo              | 1        | 0.91%   |
| Intel BOX4A200      | 1        | 0.91%   |
| Infoblox            | 1        | 0.91%   |
| HPE                 | 1        | 0.91%   |
| Fujitsu             | 1        | 0.91%   |
| Biostar             | 1        | 0.91%   |
| BESSTAR Tech        | 1        | 0.91%   |
| ADI Engineering     | 1        | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| PC Engines APU2                          | 16       | 14.55%  |
| PC Engines apu4                          | 12       | 10.91%  |
| Unknown                                  | 12       | 10.91%  |
| Protectli FW6                            | 3        | 2.73%   |
| ASRock A320M-ITX                         | 3        | 2.73%   |
| Techvision TVI7309X                      | 2        | 1.82%   |
| Shuttle DS10U                            | 2        | 1.82%   |
| Dell Precision 3440                      | 2        | 1.82%   |
| Apple MacPro5,1                          | 2        | 1.82%   |
| YANYU D19SL_B                            | 1        | 0.91%   |
| Supermicro X9SCL/X9SCM                   | 1        | 0.91%   |
| Supermicro SYS-1019D-4C-FHN13TP          | 1        | 0.91%   |
| Supermicro PDSML                         | 1        | 0.91%   |
| Supermicro AS -5019D-FTN4                | 1        | 0.91%   |
| Sun SUNW,Sun-Blade-1500                  | 1        | 0.91%   |
| Sun SUNW,Sun-Blade-100                   | 1        | 0.91%   |
| Shuttle TERRA_PC                         | 1        | 0.91%   |
| PC Engines apu6                          | 1        | 0.91%   |
| PC Engines APU3                          | 1        | 0.91%   |
| MW GMLK-2_5G4L                           | 1        | 0.91%   |
| Lenovo ThinkCentre M75t Gen 2 11KECTO1WW | 1        | 0.91%   |
| Intel Q3XXG4-P V1.0                      | 1        | 0.91%   |
| Intel HURONRIVER                         | 1        | 0.91%   |
| Intel D54250WYK H13922-303               | 1        | 0.91%   |
| Intel BOX4A200 Geminilake                | 1        | 0.91%   |
| Infoblox IB-1410                         | 1        | 0.91%   |
| HPE ProLiant MicroServer Gen10           | 1        | 0.91%   |
| HP Z620 Workstation                      | 1        | 0.91%   |
| HP Z600 Workstation                      | 1        | 0.91%   |
| HP ProLiant ML350p Gen8                  | 1        | 0.91%   |
| HP ProLiant MicroServer Gen8             | 1        | 0.91%   |
| HP Compaq Elite 8300 SFF                 | 1        | 0.91%   |
| HP Compaq Elite 8300 CMT                 | 1        | 0.91%   |
| HP Compaq 8200 Elite SFF PC              | 1        | 0.91%   |
| HP Compaq 8200 Elite CMT PC              | 1        | 0.91%   |
| Gigabyte X570 AORUS MASTER               | 1        | 0.91%   |
| Gigabyte X399 DESIGNARE EX               | 1        | 0.91%   |
| Gigabyte H97N-WIFI                       | 1        | 0.91%   |
| Gigabyte H67A-UD3H-B3                    | 1        | 0.91%   |
| Gigabyte BRi3(H)-10110                   | 1        | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| PC Engines APU2                 | 16       | 14.55%  |
| PC Engines apu4                 | 12       | 10.91%  |
| Unknown                         | 12       | 10.91%  |
| HP Compaq                       | 4        | 3.64%   |
| Protectli FW6                   | 3        | 2.73%   |
| ASRock A320M-ITX                | 3        | 2.73%   |
| Techvision TVI7309X             | 2        | 1.82%   |
| Sun SUNW                        | 2        | 1.82%   |
| Shuttle DS10U                   | 2        | 1.82%   |
| HP ProLiant                     | 2        | 1.82%   |
| Dell Precision                  | 2        | 1.82%   |
| Dell OptiPlex                   | 2        | 1.82%   |
| Apple MacPro5                   | 2        | 1.82%   |
| Acer Aspire                     | 2        | 1.82%   |
| YANYU D19SL                     | 1        | 0.91%   |
| Supermicro X9SCL                | 1        | 0.91%   |
| Supermicro SYS-1019D-4C-FHN13TP | 1        | 0.91%   |
| Supermicro PDSML                | 1        | 0.91%   |
| Supermicro AS                   | 1        | 0.91%   |
| Shuttle TERRA                   | 1        | 0.91%   |
| PC Engines apu6                 | 1        | 0.91%   |
| PC Engines APU3                 | 1        | 0.91%   |
| MW GMLK-2                       | 1        | 0.91%   |
| Lenovo ThinkCentre              | 1        | 0.91%   |
| Intel Q3XXG4-P                  | 1        | 0.91%   |
| Intel HURONRIVER                | 1        | 0.91%   |
| Intel D54250WYK                 | 1        | 0.91%   |
| Intel BOX4A200 Geminilake       | 1        | 0.91%   |
| Infoblox IB-1410                | 1        | 0.91%   |
| HPE ProLiant                    | 1        | 0.91%   |
| HP Z620                         | 1        | 0.91%   |
| HP Z600                         | 1        | 0.91%   |
| Gigabyte X570                   | 1        | 0.91%   |
| Gigabyte X399                   | 1        | 0.91%   |
| Gigabyte H97N-WIFI              | 1        | 0.91%   |
| Gigabyte H67A-UD3H-B3           | 1        | 0.91%   |
| Gigabyte BRi3(H)-10110          | 1        | 0.91%   |
| Gigabyte B550M                  | 1        | 0.91%   |
| Gigabyte B450M                  | 1        | 0.91%   |
| Gigabyte 990FXA-UD3             | 1        | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 22       | 20%     |
| 2016    | 19       | 17.27%  |
| 2020    | 17       | 15.45%  |
| 2022    | 8        | 7.27%   |
| 2019    | 8        | 7.27%   |
| 2012    | 7        | 6.36%   |
| 2021    | 6        | 5.45%   |
| 2013    | 5        | 4.55%   |
| 2015    | 4        | 3.64%   |
| 2017    | 3        | 2.73%   |
| 2011    | 3        | 2.73%   |
| Unknown | 3        | 2.73%   |
| 2008    | 2        | 1.82%   |
| 2014    | 1        | 0.91%   |
| 2010    | 1        | 0.91%   |
| 2007    | 1        | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 110      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 69.09%  |
| Yes  | 34       | 30.91%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 32       | 28.32%  |
| 8.01-16.0   | 29       | 25.66%  |
| 16.01-24.0  | 27       | 23.89%  |
| 32.01-64.0  | 13       | 11.5%   |
| 64.01-256.0 | 5        | 4.42%   |
| 2.01-3.0    | 4        | 3.54%   |
| 1.01-2.0    | 1        | 0.88%   |
| 0.01-0.5    | 1        | 0.88%   |
| Unknown     | 1        | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 53       | 44.92%  |
| 0.51-1.0   | 34       | 28.81%  |
| 1.01-2.0   | 12       | 10.17%  |
| 2.01-3.0   | 7        | 5.93%   |
| 4.01-8.0   | 3        | 2.54%   |
| 3.01-4.0   | 3        | 2.54%   |
| 8.01-16.0  | 2        | 1.69%   |
| 0          | 2        | 1.69%   |
| 16.01-24.0 | 1        | 0.85%   |
| Unknown    | 1        | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 78       | 69.03%  |
| 0      | 14       | 12.39%  |
| 2      | 5        | 4.42%   |
| 4      | 4        | 3.54%   |
| 6      | 3        | 2.65%   |
| 3      | 3        | 2.65%   |
| 5      | 2        | 1.77%   |
| 17     | 1        | 0.88%   |
| 16     | 1        | 0.88%   |
| 8      | 1        | 0.88%   |
| 7      | 1        | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 84.55%  |
| Yes       | 17       | 15.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 109      | 99.09%  |
| No        | 1        | 0.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 85.45%  |
| Yes       | 16       | 14.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 88.18%  |
| Yes       | 13       | 11.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Switzerland | 110      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Zurich                             | 25       | 18.8%   |
| Winterthur                         | 6        | 4.51%   |
| Gachnang                           | 6        | 4.51%   |
| Gordola                            | 5        | 3.76%   |
| Lausanne                           | 4        | 3.01%   |
| St. Moritz                         | 3        | 2.26%   |
| Lenzburg                           | 3        | 2.26%   |
| Basel                              | 3        | 2.26%   |
| St. Gallen                         | 2        | 1.5%    |
| Siggenthal Station                 | 2        | 1.5%    |
| Riehen                             | 2        | 1.5%    |
| Ottenbach                          | 2        | 1.5%    |
| Oensingen                          | 2        | 1.5%    |
| Mettmenstetten                     | 2        | 1.5%    |
| Horgen                             | 2        | 1.5%    |
| Geneva                             | 2        | 1.5%    |
| Dietikon                           | 2        | 1.5%    |
| Burgdorf                           | 2        | 1.5%    |
| Yverdon-les-Bains                  | 1        | 0.75%   |
| Yens                               | 1        | 0.75%   |
| Worblaufen                         | 1        | 0.75%   |
| Willisau                           | 1        | 0.75%   |
| Wiesendangen / Wiesendangen (Dorf) | 1        | 0.75%   |
| Wetzikon                           | 1        | 0.75%   |
| Wettswil                           | 1        | 0.75%   |
| Welschenrohr                       | 1        | 0.75%   |
| Uster                              | 1        | 0.75%   |
| Trogen                             | 1        | 0.75%   |
| Suhr                               | 1        | 0.75%   |
| Steckborn                          | 1        | 0.75%   |
| Stallikon                          | 1        | 0.75%   |
| Sitterdorf                         | 1        | 0.75%   |
| Sissach                            | 1        | 0.75%   |
| Rumlang                            | 1        | 0.75%   |
| Riviera                            | 1        | 0.75%   |
| Rickenbach bei Wil                 | 1        | 0.75%   |
| Richterswil                        | 1        | 0.75%   |
| Renens                             | 1        | 0.75%   |
| Pfaeffikon                         | 1        | 0.75%   |
| Opfikon                            | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 48     | 21.93%  |
| Phison              | 13       | 16     | 11.4%   |
| WDC                 | 12       | 32     | 10.53%  |
| Kingston            | 9        | 13     | 7.89%   |
| Seagate             | 7        | 10     | 6.14%   |
| Intel               | 5        | 21     | 4.39%   |
| Hoodisk             | 5        | 7      | 4.39%   |
| Crucial             | 4        | 11     | 3.51%   |
| HPT                 | 3        | 35     | 2.63%   |
| Hitachi             | 3        | 3      | 2.63%   |
| Corsair             | 3        | 4      | 2.63%   |
| China               | 3        | 4      | 2.63%   |
| Toshiba             | 2        | 3      | 1.75%   |
| SK hynix            | 2        | 2      | 1.75%   |
| ShiJi               | 2        | 7      | 1.75%   |
| SanDisk             | 2        | 5      | 1.75%   |
| Transcend           | 1        | 1      | 0.88%   |
| SPCC                | 1        | 2      | 0.88%   |
| Silicon Motion      | 1        | 1      | 0.88%   |
| PNY                 | 1        | 1      | 0.88%   |
| OPENBSD             | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 2      | 0.88%   |
| KingSpec            | 1        | 1      | 0.88%   |
| Intenso             | 1        | 2      | 0.88%   |
| Hewlett-Packard     | 1        | 10     | 0.88%   |
| FORESEE             | 1        | 1      | 0.88%   |
| Fanxiang            | 1        | 1      | 0.88%   |
| BIWIN               | 1        | 1      | 0.88%   |
| Apple               | 1        | 1      | 0.88%   |
| A-DATA Technology   | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Phison SATA SSD 16GB              | 10       | 6.33%   |
| Hoodisk SSD 32GB                  | 5        | 3.16%   |
| Samsung SSD 860 EVO 250GB         | 4        | 2.53%   |
| Samsung SSD 860 PRO 256GB         | 3        | 1.9%    |
| Phison SATA SSD 32GB              | 3        | 1.9%    |
| Kingston RBUSNS8180DS3128GH 128GB | 3        | 1.9%    |
| HPT DISK 0_3 1TB                  | 3        | 1.9%    |
| HPT DISK 0_2 1TB                  | 3        | 1.9%    |
| HPT DISK 0_1 1TB                  | 3        | 1.9%    |
| HPT DISK 0_0 1TB                  | 3        | 1.9%    |
| WDC WD6002FRYZ-01WD5B1 6TB        | 2        | 1.27%   |
| WDC WD30EFRX-68EUZN0 3TB          | 2        | 1.27%   |
| ShiJi SSD 128GB                   | 2        | 1.27%   |
| Samsung SSD 980 PRO 250GB         | 2        | 1.27%   |
| Samsung SSD 960 EVO 250GB         | 2        | 1.27%   |
| Samsung SSD 850 PRO 256GB         | 2        | 1.27%   |
| Samsung SSD 840 Series 120GB      | 2        | 1.27%   |
| HPT DISK 0_9 3TB                  | 2        | 1.27%   |
| HPT DISK 0_8 3TB                  | 2        | 1.27%   |
| HPT DISK 0_7 1TB                  | 2        | 1.27%   |
| HPT DISK 0_6 1TB                  | 2        | 1.27%   |
| HPT DISK 0_5 1TB                  | 2        | 1.27%   |
| HPT DISK 0_4 1TB                  | 2        | 1.27%   |
| HPT DISK 0_14 3TB                 | 2        | 1.27%   |
| HPT DISK 0_13 2TB                 | 2        | 1.27%   |
| HPT DISK 0_12 1TB                 | 2        | 1.27%   |
| HPT DISK 0_11 1TB                 | 2        | 1.27%   |
| HPT DISK 0_10 1TB                 | 2        | 1.27%   |
| Hitachi HDS721050CLA360 500GB     | 2        | 1.27%   |
| Crucial CT250MX500SSD1 250GB      | 2        | 1.27%   |
| WDC WDS500G1R0A-68A4W0 500GB      | 1        | 0.63%   |
| WDC WDS250G2B0C-00PXH0 250GB      | 1        | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB      | 1        | 0.63%   |
| WDC WDS120G2G0B-00EPW0 120GB      | 1        | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB      | 1        | 0.63%   |
| WDC WD60EFRX-68L0BN1 6TB          | 1        | 0.63%   |
| WDC WD40EFZX-68AWUN0 4TB          | 1        | 0.63%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 0.63%   |
| WDC WD2002FYPS-01U1B0 2TB         | 1        | 0.63%   |
| WDC WD10EFRX-68PJCN0 1TB          | 1        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 23     | 25.93%  |
| Seagate             | 7        | 10     | 25.93%  |
| HPT                 | 3        | 35     | 11.11%  |
| Hitachi             | 3        | 3      | 11.11%  |
| Toshiba             | 2        | 3      | 7.41%   |
| Samsung Electronics | 1        | 1      | 3.7%    |
| OPENBSD             | 1        | 1      | 3.7%    |
| Hewlett-Packard     | 1        | 10     | 3.7%    |
| China               | 1        | 1      | 3.7%    |
| Apple               | 1        | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 37     | 23.68%  |
| Phison              | 13       | 16     | 17.11%  |
| Kingston            | 8        | 10     | 10.53%  |
| Intel               | 5        | 21     | 6.58%   |
| Hoodisk             | 5        | 7      | 6.58%   |
| WDC                 | 4        | 7      | 5.26%   |
| Crucial             | 4        | 11     | 5.26%   |
| SK hynix            | 2        | 2      | 2.63%   |
| ShiJi               | 2        | 7      | 2.63%   |
| SanDisk             | 2        | 5      | 2.63%   |
| Corsair             | 2        | 3      | 2.63%   |
| China               | 2        | 3      | 2.63%   |
| Transcend           | 1        | 1      | 1.32%   |
| SPCC                | 1        | 2      | 1.32%   |
| PNY                 | 1        | 1      | 1.32%   |
| Micron Technology   | 1        | 2      | 1.32%   |
| KingSpec            | 1        | 1      | 1.32%   |
| Intenso             | 1        | 2      | 1.32%   |
| FORESEE             | 1        | 1      | 1.32%   |
| BIWIN               | 1        | 1      | 1.32%   |
| A-DATA Technology   | 1        | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 74       | 141    | 69.16%  |
| HDD  | 19       | 88     | 17.76%  |
| NVMe | 14       | 18     | 13.08%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 83       | 229    | 85.57%  |
| NVMe | 14       | 18     | 14.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 82       | 158    | 76.64%  |
| 0.51-1.0   | 8        | 38     | 7.48%   |
| 1.01-2.0   | 6        | 9      | 5.61%   |
| 2.01-3.0   | 5        | 13     | 4.67%   |
| 4.01-10.0  | 4        | 9      | 3.74%   |
| 3.01-4.0   | 2        | 2      | 1.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 56       | 49.12%  |
| 1-20       | 19       | 16.67%  |
| 51-100     | 16       | 14.04%  |
| 21-50      | 12       | 10.53%  |
| 251-500    | 5        | 4.39%   |
| 501-1000   | 4        | 3.51%   |
| 2001-3000  | 1        | 0.88%   |
| 1001-2000  | 1        | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 103      | 88.79%  |
| 21-50   | 7        | 6.03%   |
| 51-100  | 4        | 3.45%   |
| 251-500 | 2        | 1.72%   |

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
| Works    | 88       | 176    | 84.62%  |
| Malfunc  | 11       | 29     | 10.58%  |
| Detected | 5        | 42     | 4.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 59       | 43.38%  |
| AMD                         | 47       | 34.56%  |
| Samsung Electronics         | 9        | 6.62%   |
| HighPoint Technologies      | 3        | 2.21%   |
| ASMedia Technology          | 3        | 2.21%   |
| ULi Electronics             | 2        | 1.47%   |
| Silicon Motion              | 2        | 1.47%   |
| SanDisk                     | 2        | 1.47%   |
| Marvell Technology Group    | 2        | 1.47%   |
| JMicron Technology          | 2        | 1.47%   |
| Phison Electronics          | 1        | 0.74%   |
| Kingston Technology Company | 1        | 0.74%   |
| Hewlett-Packard             | 1        | 0.74%   |
| Chelsio Communications      | 1        | 0.74%   |
| Broadcom / LSI              | 1        | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 31       | 20%     |
| AMD FCH SATA Controller [IDE mode]                                             | 10       | 6.45%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5        | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 3.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 2.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4        | 2.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4        | 2.58%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 2.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.94%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 3        | 1.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3        | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 1.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 1.94%   |
| AMD FCH SATA Controller D                                                      | 3        | 1.94%   |
| ULi M5229 IDE                                                                  | 2        | 1.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2        | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 1.29%   |
| JMicron JMB58x AHCI SATA controller                                            | 2        | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2        | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.29%   |
| Intel Atom Processor C3000 Series SATA Controller 1                            | 2        | 1.29%   |
| Intel Atom Processor C3000 Series SATA Controller 0                            | 2        | 1.29%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 1.29%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 2        | 1.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.65%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.65%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1        | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 0.65%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.65%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 0.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.65%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1        | 0.65%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 0.65%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 91       | 67.41%  |
| IDE  | 18       | 13.33%  |
| NVMe | 15       | 11.11%  |
| RAID | 7        | 5.19%   |
| SAS  | 2        | 1.48%   |
| SCSI | 2        | 1.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 61       | 55.45%  |
| AMD     | 47       | 42.73%  |
| Unknown | 2        | 1.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 30       | 27.27%  |
| Intel Celeron CPU 3865U @ 1.80GHz           | 4        | 3.64%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 2.73%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 2.73%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.82%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 2        | 1.82%   |
| Intel Celeron N5100 @ 1.10GHz               | 2        | 1.82%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 2        | 1.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2        | 1.82%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.82%   |
|                                             | 2        | 1.82%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 1        | 0.91%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1        | 0.91%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 0.91%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.91%   |
| Intel Xeon CPU E5630 @ 2.53GHz              | 1        | 0.91%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.91%   |
| Intel Xeon CPU E5-2620 @ 2.00GHz            | 1        | 0.91%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.91%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.91%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz        | 1        | 0.91%   |
| Intel Xeon CPU E                            | 1        | 0.91%   |
| Intel Pentium Gold G7400                    | 1        | 0.91%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.91%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.91%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.91%   |
| Intel Core i7-2600K CPU                     | 1        | 0.91%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1        | 0.91%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.91%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1        | 0.91%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.91%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 0.91%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.91%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 0.91%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1        | 0.91%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 0.91%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD GX                 | 31       | 28.18%  |
| Intel Core i5          | 15       | 13.64%  |
| Intel Celeron          | 13       | 11.82%  |
| Intel Xeon             | 11       | 10%     |
| Intel Core i7          | 8        | 7.27%   |
| Intel Core i3          | 5        | 4.55%   |
| Other                  | 4        | 3.64%   |
| AMD Ryzen 7            | 4        | 3.64%   |
| AMD Ryzen 5            | 4        | 3.64%   |
| Intel Atom             | 3        | 2.73%   |
| Intel Core 2 Duo       | 2        | 1.82%   |
| AMD Ryzen 7 PRO        | 2        | 1.82%   |
| Intel Pentium Gold     | 1        | 0.91%   |
| Intel Pentium          | 1        | 0.91%   |
| AMD Ryzen Threadripper | 1        | 0.91%   |
| AMD Ryzen 3            | 1        | 0.91%   |
| AMD Opteron            | 1        | 0.91%   |
| AMD Geode Integrated   | 1        | 0.91%   |
| AMD FX                 | 1        | 0.91%   |
| AMD EPYC               | 1        | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 65       | 59.09%  |
| 2       | 15       | 13.64%  |
| 8       | 10       | 9.09%   |
| 16      | 7        | 6.36%   |
| 6       | 4        | 3.64%   |
| 1       | 3        | 2.73%   |
| 12      | 2        | 1.82%   |
| Unknown | 2        | 1.82%   |
| 32      | 1        | 0.91%   |
| 10      | 1        | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 104      | 94.55%  |
| 2       | 3        | 2.73%   |
| Unknown | 2        | 1.82%   |
| 4       | 1        | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 76       | 69.09%  |
| 2       | 30       | 27.27%  |
| Unknown | 4        | 3.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 30       | 27.27%  |
| KabyLake      | 13       | 11.82%  |
| IvyBridge     | 8        | 7.27%   |
| SandyBridge   | 6        | 5.45%   |
| Haswell       | 6        | 5.45%   |
| Unknown       | 6        | 5.45%   |
| Zen 3         | 5        | 4.55%   |
| Zen           | 4        | 3.64%   |
| Goldmont plus | 4        | 3.64%   |
| Zen+          | 3        | 2.73%   |
| Skylake       | 3        | 2.73%   |
| Westmere      | 2        | 1.82%   |
| TigerLake     | 2        | 1.82%   |
| Silvermont    | 2        | 1.82%   |
| Nehalem       | 2        | 1.82%   |
| Goldmont      | 2        | 1.82%   |
| Core          | 2        | 1.82%   |
| CometLake     | 2        | 1.82%   |
| Zen 2         | 1        | 0.91%   |
| Piledriver    | 1        | 0.91%   |
| Penryn        | 1        | 0.91%   |
| Jaguar        | 1        | 0.91%   |
| IceLake       | 1        | 0.91%   |
| Geode         | 1        | 0.91%   |
| Excavator     | 1        | 0.91%   |
| Broadwell     | 1        | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 40       | 51.95%  |
| AMD                                          | 14       | 18.18%  |
| Nvidia                                       | 11       | 14.29%  |
| ASPEED Technology                            | 6        | 7.79%   |
| Matrox Electronics Systems                   | 4        | 5.19%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 1.3%    |
| 3DLabs                                       | 1        | 1.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| ASPEED Technology ASPEED Graphics Family                                    | 6        | 7.79%   |
| Intel HD Graphics 610                                                       | 4        | 5.19%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4        | 5.19%   |
| Intel JasperLake [UHD Graphics]                                             | 3        | 3.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3        | 3.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.9%    |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 2.6%    |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2        | 2.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2        | 2.6%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.6%    |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 2.6%    |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)              | 1        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.3%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.3%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.3%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.3%    |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.3%    |
| Nvidia GK107 [GeForce GT 640 OEM]                                           | 1        | 1.3%    |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.3%    |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.3%    |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.3%    |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.3%    |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                 | 1        | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1        | 1.3%    |
| Intel HD Graphics 6000                                                      | 1        | 1.3%    |
| Intel HD Graphics 530                                                       | 1        | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.3%    |
| Intel Alder Lake-S GT1 [UHD Graphics 710]                                   | 1        | 1.3%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.3%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.3%    |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                      | 1        | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 40       | 36.36%  |
| Other      | 33       | 30%     |
| 1 x AMD    | 14       | 12.73%  |
| 1 x Nvidia | 11       | 10%     |
| 1 x ASPEED | 6        | 5.45%   |
| 1 x Matrox | 4        | 3.64%   |
| 1 x XGI    | 1        | 0.91%   |
| 1 x 3DLabs | 1        | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 67       | 60.91%  |
| Unknown     | 36       | 32.73%  |
| Proprietary | 7        | 6.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 101      | 91.82%  |
| 3.01-4.0   | 3        | 2.73%   |
| 1.01-2.0   | 3        | 2.73%   |
| 5.01-6.0   | 1        | 0.91%   |
| 2.01-3.0   | 1        | 0.91%   |
| 0.01-0.5   | 1        | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2        | 16.67%  |
| Acer                 | 2        | 16.67%  |
| Philips              | 1        | 8.33%   |
| NEC Computers        | 1        | 8.33%   |
| LG Electronics       | 1        | 8.33%   |
| Lenovo               | 1        | 8.33%   |
| Iiyama               | 1        | 8.33%   |
| Fujitsu Siemens      | 1        | 8.33%   |
| Eizo                 | 1        | 8.33%   |
| Ancor Communications | 1        | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics U32E850 SAM0CE3 3840x2160 700x390mm 31.5-inch | 1        | 7.69%   |
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch | 1        | 7.69%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                | 1        | 7.69%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                      | 1        | 7.69%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                 | 1        | 7.69%   |
| LG Electronics LCD Monitor LG Ultra HD                            | 1        | 7.69%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch          | 1        | 7.69%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch             | 1        | 7.69%   |
| Fujitsu Siemens S19-1 FUS0517 1280x1024 380x300mm 19.1-inch       | 1        | 7.69%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                | 1        | 7.69%   |
| Ancor Communications VS278 ACI27A1 1920x1080 600x340mm 27.2-inch  | 1        | 7.69%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                | 1        | 7.69%   |
| Acer XB271HU A ACR052F 2560x1440 600x340mm 27.2-inch              | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 5        | 38.46%  |
| 2560x1440 (QHD)  | 3        | 23.08%  |
| 3840x2160 (4K)   | 2        | 15.38%  |
| 1280x1024 (SXGA) | 1        | 7.69%   |
| 11520x2160       | 1        | 7.69%   |
| Unknown          | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 41.67%  |
| 31      | 2        | 16.67%  |
| Unknown | 2        | 16.67%  |
| 65      | 1        | 8.33%   |
| 23      | 1        | 8.33%   |
| 19      | 1        | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 50%     |
| 601-700     | 2        | 16.67%  |
| Unknown     | 2        | 16.67%  |
| 351-400     | 1        | 8.33%   |
| 1001-1500   | 1        | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 9        | 75%     |
| Unknown | 2        | 16.67%  |
| 5/4     | 1        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 5        | 41.67%  |
| 351-500        | 2        | 16.67%  |
| Unknown        | 2        | 16.67%  |
| More than 1000 | 1        | 8.33%   |
| 201-250        | 1        | 8.33%   |
| 151-200        | 1        | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4        | 33.33%  |
| 101-120 | 3        | 25%     |
| 121-160 | 2        | 16.67%  |
| Unknown | 2        | 16.67%  |
| 1-50    | 1        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 98       | 89.09%  |
| 1     | 11       | 10%     |
| 2     | 1        | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 96       | 67.13%  |
| Realtek Semiconductor             | 21       | 14.69%  |
| Broadcom                          | 8        | 5.59%   |
| Qualcomm Atheros                  | 3        | 2.1%    |
| Mellanox Technologies             | 2        | 1.4%    |
| Huawei Technologies               | 2        | 1.4%    |
| American Megatrends               | 2        | 1.4%    |
| VIA Technologies                  | 1        | 0.7%    |
| U-Blox                            | 1        | 0.7%    |
| Qualcomm Atheros Communications   | 1        | 0.7%    |
| QLogic                            | 1        | 0.7%    |
| Oracle/SUN                        | 1        | 0.7%    |
| Microchip Technology              | 1        | 0.7%    |
| Free Software Initiative of Japan | 1        | 0.7%    |
| Chelsio Communications            | 1        | 0.7%    |
| Aquantia                          | 1        | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 32       | 17.39%  |
| Intel I210 Gigabit Network Connection                                         | 20       | 10.87%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16       | 8.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 3.8%    |
| Intel Ethernet Controller I225-V                                              | 6        | 3.26%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 3.26%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 2.17%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 2.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.17%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 1.63%   |
| Intel Ethernet Controller X550                                                | 3        | 1.63%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 1.63%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.63%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2        | 1.09%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2        | 1.09%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 1.09%   |
| Intel Ethernet Controller I226-V                                              | 2        | 1.09%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.09%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.09%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 1.09%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 1.09%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.09%   |
| American Megatrends Virtual Ethernet                                          | 2        | 1.09%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.54%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.54%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.54%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.54%   |
| Microchip CDC RS-232 Emulation Demo                                           | 1        | 0.54%   |
| Mellanox MT2894 Family [ConnectX-6 Lx]                                        | 1        | 0.54%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1        | 0.54%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 0.54%   |
| Intel Wireless 7260                                                           | 1        | 0.54%   |
| Intel Wireless 3160                                                           | 1        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 53.33%  |
| Realtek Semiconductor           | 3        | 20%     |
| Qualcomm Atheros                | 2        | 13.33%  |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| Broadcom                        | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3        | 20%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 13.33%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2        | 13.33%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 6.67%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 6.67%   |
| Intel Wireless 8265 / 8275                                     | 1        | 6.67%   |
| Intel Wireless 7260                                            | 1        | 6.67%   |
| Intel Wireless 3160                                            | 1        | 6.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 6.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 93       | 73.23%  |
| Realtek Semiconductor  | 18       | 14.17%  |
| Broadcom               | 7        | 5.51%   |
| American Megatrends    | 2        | 1.57%   |
| VIA Technologies       | 1        | 0.79%   |
| Qualcomm Atheros       | 1        | 0.79%   |
| QLogic                 | 1        | 0.79%   |
| Oracle/SUN             | 1        | 0.79%   |
| Huawei Technologies    | 1        | 0.79%   |
| Chelsio Communications | 1        | 0.79%   |
| Aquantia               | 1        | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 32       | 19.63%  |
| Intel I210 Gigabit Network Connection                                         | 20       | 12.27%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16       | 9.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 4.29%   |
| Intel Ethernet Controller I225-V                                              | 6        | 3.68%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 3.68%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 2.45%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 2.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.45%   |
| Intel Ethernet Controller X550                                                | 3        | 1.84%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 1.84%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.84%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.84%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 1.23%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2        | 1.23%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 1.23%   |
| Intel Ethernet Controller I226-V                                              | 2        | 1.23%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.23%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 1.23%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 1.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.23%   |
| American Megatrends Virtual Ethernet                                          | 2        | 1.23%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.61%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.61%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.61%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1        | 0.61%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1        | 0.61%   |
| Intel Ethernet Controller E810-XXV for SFP                                    | 1        | 0.61%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1        | 0.61%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.61%   |
| Intel Ethernet Connection I354                                                | 1        | 0.61%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.61%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.61%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.61%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 109      | 83.85%  |
| WiFi     | 15       | 11.54%  |
| Modem    | 3        | 2.31%   |
| Unknown  | 3        | 2.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 105      | 98.13%  |
| WiFi     | 2        | 1.87%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 31       | 27.93%  |
| 4     | 25       | 22.52%  |
| 6     | 14       | 12.61%  |
| 1     | 14       | 12.61%  |
| 5     | 13       | 11.71%  |
| 2     | 8        | 7.21%   |
| 13    | 2        | 1.8%    |
| 8     | 2        | 1.8%    |
| 14    | 1        | 0.9%    |
| 7     | 1        | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 85       | 70.83%  |
| Yes  | 35       | 29.17%  |

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
| Intel                 | 47       | 61.84%  |
| AMD                   | 16       | 21.05%  |
| Nvidia                | 9        | 11.84%  |
| ULi Electronics       | 2        | 2.63%   |
| Realtek Semiconductor | 1        | 1.32%   |
| Logitech              | 1        | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 6.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 5.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 4        | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 3.41%   |
| Intel Jasper Lake HD Audio                                                        | 3        | 3.41%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 3        | 3.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3        | 3.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 3.41%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 3.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 3.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 3.41%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 2.27%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 2.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2        | 2.27%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 2.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.27%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                | 1        | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.14%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 1.14%   |
| Logitech H600 [Wireless Headset]                                                  | 1        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.14%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1        | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1        | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.14%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 1.14%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.14%   |
| Intel Alder Lake-S HD Audio Controller                                            | 1        | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 1.14%   |
| Intel 8 Series HD Audio Controller                                                | 1        | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 29       | 27.36%  |
| Unknown             | 21       | 19.81%  |
| SK hynix            | 11       | 10.38%  |
| Samsung Electronics | 11       | 10.38%  |
| Crucial             | 9        | 8.49%   |
| Corsair             | 9        | 8.49%   |
| Micron Technology   | 7        | 6.6%    |
| Nanya Technology    | 2        | 1.89%   |
| Hewlett-Packard     | 2        | 1.89%   |
| Unknown (ABCD)      | 1        | 0.94%   |
| Unknown (0x05F7)    | 1        | 0.94%   |
| Unknown (07FB)      | 1        | 0.94%   |
| Tigo                | 1        | 0.94%   |
| Super Talent        | 1        | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 12       | 10.81%  |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 3        | 2.7%    |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s              | 3        | 2.7%    |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s              | 3        | 2.7%    |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s              | 3        | 2.7%    |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2133MT/s            | 3        | 2.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 2        | 1.8%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 2        | 1.8%    |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s             | 2        | 1.8%    |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s             | 2        | 1.8%    |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s             | 2        | 1.8%    |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s            | 2        | 1.8%    |
| Crucial RAM CT8G4SFRA32A.M8FR 8GB SODIMM DDR4 3200MT/s            | 2        | 1.8%    |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s              | 2        | 1.8%    |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s              | 2        | 1.8%    |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                        | 1        | 0.9%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1        | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 0.9%    |
| Unknown (0x05F7) RAM Module 1GB FB-DIMM DDR2 800MT/s              | 1        | 0.9%    |
| Unknown (07FB) RAM GSA8G4SCL196P-26 8GB SODIMM DDR4 2667MT/s      | 1        | 0.9%    |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                      | 1        | 0.9%    |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s             | 1        | 0.9%    |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1        | 0.9%    |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 0.9%    |
| SK hynix RAM Module 1GB FB-DIMM DDR2 800MT/s                      | 1        | 0.9%    |
| SK hynix RAM HMT42GR7MFR4C-PB 16384MB DIMM DDR3 1600MT/s          | 1        | 0.9%    |
| SK hynix RAM HMT41GU6DFR8A-PB 8GB DIMM DDR3 1600MT/s              | 1        | 0.9%    |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s              | 1        | 0.9%    |
| SK hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.9%    |
| SK hynix RAM HMA82GU6DJR8N-VK 16GB DIMM DDR4 2667MT/s             | 1        | 0.9%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1        | 0.9%    |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s                        | 1        | 0.9%    |
| Samsung RAM Module 16GB DIMM DDR3 1066MT/s                        | 1        | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 1        | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 1        | 0.9%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s             | 1        | 0.9%    |
| Samsung RAM M393B2G70DB0-CK0 16GB DIMM DDR3 1600MT/s              | 1        | 0.9%    |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s              | 1        | 0.9%    |
| Samsung RAM M393B1K70BH1-CH9 8GB DIMM DDR3 1333MT/s               | 1        | 0.9%    |
| Samsung RAM M393A1K43BB1-CTD 8GB RIMM DDR4 2133MT/s               | 1        | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 46       | 49.46%  |
| DDR4    | 41       | 44.09%  |
| DDR2    | 3        | 3.23%   |
| LPDDR4  | 2        | 2.15%   |
| Unknown | 1        | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 52       | 55.91%  |
| SODIMM       | 38       | 40.86%  |
| Row Of Chips | 1        | 1.08%   |
| RIMM         | 1        | 1.08%   |
| FB-DIMM      | 1        | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 44       | 45.36%  |
| 4096  | 28       | 28.87%  |
| 16384 | 14       | 14.43%  |
| 2048  | 6        | 6.19%   |
| 32768 | 2        | 2.06%   |
| 1024  | 2        | 2.06%   |
| 512   | 1        | 1.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 32       | 31.07%  |
| 2667  | 13       | 12.62%  |
| 1600  | 13       | 12.62%  |
| 3200  | 12       | 11.65%  |
| 2400  | 9        | 8.74%   |
| 2133  | 9        | 8.74%   |
| 2666  | 5        | 4.85%   |
| 667   | 4        | 3.88%   |
| 800   | 2        | 1.94%   |
| 3600  | 1        | 0.97%   |
| 3000  | 1        | 0.97%   |
| 1800  | 1        | 0.97%   |
| 1066  | 1        | 0.97%   |

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
| 0     | 51       | 44.35%  |
| 1     | 41       | 35.65%  |
| 2     | 15       | 13.04%  |
| 3     | 7        | 6.09%   |
| 4     | 1        | 0.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 49       | 61.25%  |
| Firewire controller      | 8        | 10%     |
| Bluetooth                | 7        | 8.75%   |
| Net/wireless             | 6        | 7.5%    |
| Net/ethernet             | 4        | 5%      |
| Sound                    | 2        | 2.5%    |
| Card reader              | 2        | 2.5%    |
| Network                  | 1        | 1.25%   |
| Graphics card            | 1        | 1.25%   |

