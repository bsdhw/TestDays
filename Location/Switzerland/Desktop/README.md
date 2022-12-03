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

Total: 189

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OPNsense 22.7       | 7        | 4.76%   |
| OPNsense 21.7.3     | 7        | 4.76%   |
| OPNsense 21.7.1     | 7        | 4.76%   |
| OPNsense 21.1.6     | 7        | 4.76%   |
| OPNsense 20.7.8     | 7        | 4.76%   |
| OPNsense 22.1.8     | 6        | 4.08%   |
| OPNsense 21.7.6     | 5        | 3.4%    |
| OPNsense 22.7.4     | 4        | 2.72%   |
| OPNsense 22.1.6     | 4        | 2.72%   |
| OPNsense 22.1.3     | 4        | 2.72%   |
| OPNsense 21.7.7     | 4        | 2.72%   |
| OPNsense 21.1.3     | 4        | 2.72%   |
| OPNsense 21.1       | 4        | 2.72%   |
| OpenBSD 6.8         | 4        | 2.72%   |
| OPNsense 22.7.8     | 3        | 2.04%   |
| OPNsense 22.1.7     | 3        | 2.04%   |
| OPNsense 22.1.1     | 3        | 2.04%   |
| OPNsense 21.7       | 3        | 2.04%   |
| OPNsense 21.1.8     | 3        | 2.04%   |
| OPNsense 21.1.2     | 3        | 2.04%   |
| OPNsense 22.1.9     | 2        | 1.36%   |
| OPNsense 22.1.4     | 2        | 1.36%   |
| OPNsense 22.1.2     | 2        | 1.36%   |
| OPNsense 22.1.10    | 2        | 1.36%   |
| OPNsense 22.1       | 2        | 1.36%   |
| OPNsense 21.7.5     | 2        | 1.36%   |
| OPNsense 21.7.4     | 2        | 1.36%   |
| OPNsense 21.1.9     | 2        | 1.36%   |
| OPNsense 21.1.7     | 2        | 1.36%   |
| OPNsense 21.1.5     | 2        | 1.36%   |
| OPNsense 21.1.4     | 2        | 1.36%   |
| OpenBSD 7.0         | 2        | 1.36%   |
| OpenBSD 6.7         | 2        | 1.36%   |
| FreeBSD 13.1-p2     | 2        | 1.36%   |
| FreeBSD 13.0-p7     | 2        | 1.36%   |
| FreeBSD 12.2-p2     | 2        | 1.36%   |
| FreeBSD 12.1-STABLE | 2        | 1.36%   |
| FreeBSD 12.1-p5     | 2        | 1.36%   |
| TrueNAS 12.2-p6     | 1        | 0.68%   |
| TrueNAS 12.2-p12    | 1        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 76       | 75.25%  |
| FreeBSD     | 10       | 9.9%    |
| OpenBSD     | 9        | 8.91%   |
| helloSystem | 3        | 2.97%   |
| TrueNAS     | 2        | 1.98%   |
| GhostBSD    | 1        | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 98       | 97.03%  |
| sparc64 | 2        | 1.98%   |
| i386    | 1        | 0.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 89       | 86.41%  |
| KDE5          | 3        | 2.91%   |
| helloDesktop  | 3        | 2.91%   |
| fvwm          | 3        | 2.91%   |
| MATE          | 1        | 0.97%   |
| LXQt          | 1        | 0.97%   |
| i3            | 1        | 0.97%   |
| Enlightenment | 1        | 0.97%   |
| CDE           | 1        | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 90       | 89.11%  |
| X11     | 11       | 10.89%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 94       | 93.07%  |
| SLiM    | 3        | 2.97%   |
| LightDM | 2        | 1.98%   |
| SDDM    | 1        | 0.99%   |
| GDM     | 1        | 0.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 84.47%  |
| en_US   | 9        | 8.74%   |
| C       | 5        | 4.85%   |
| de_DE   | 1        | 0.97%   |
| de_CH   | 1        | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 87       | 86.14%  |
| BIOS | 14       | 13.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 60       | 58.82%  |
| Zfs    | 32       | 31.37%  |
| Ffs    | 9        | 8.82%   |
| Cd9660 | 1        | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 92       | 90.2%   |
| MBR     | 9        | 8.82%   |
| Unknown | 1        | 0.98%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| PC Engines          | 29       | 28.71%  |
| Unknown             | 12       | 11.88%  |
| Hewlett-Packard     | 8        | 7.92%   |
| Gigabyte Technology | 7        | 6.93%   |
| ASUSTek Computer    | 6        | 5.94%   |
| ASRock              | 6        | 5.94%   |
| Dell                | 4        | 3.96%   |
| Supermicro          | 3        | 2.97%   |
| Shuttle             | 3        | 2.97%   |
| Protectli           | 3        | 2.97%   |
| Intel               | 3        | 2.97%   |
| Apple               | 3        | 2.97%   |
| Sun                 | 2        | 1.98%   |
| ASRockRack          | 2        | 1.98%   |
| Acer                | 2        | 1.98%   |
| YANYU               | 1        | 0.99%   |
| MW                  | 1        | 0.99%   |
| Lenovo              | 1        | 0.99%   |
| Infoblox            | 1        | 0.99%   |
| HPE                 | 1        | 0.99%   |
| Biostar             | 1        | 0.99%   |
| BESSTAR Tech        | 1        | 0.99%   |
| ADI Engineering     | 1        | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| PC Engines APU2                          | 16       | 15.84%  |
| Unknown                                  | 12       | 11.88%  |
| PC Engines apu4                          | 11       | 10.89%  |
| Protectli FW6                            | 3        | 2.97%   |
| ASRock A320M-ITX                         | 3        | 2.97%   |
| Shuttle DS10U                            | 2        | 1.98%   |
| Dell Precision 3440                      | 2        | 1.98%   |
| Apple MacPro5,1                          | 2        | 1.98%   |
| YANYU D19SL_B                            | 1        | 0.99%   |
| Supermicro X9SCL/X9SCM                   | 1        | 0.99%   |
| Supermicro SYS-1019D-4C-FHN13TP          | 1        | 0.99%   |
| Supermicro PDSML                         | 1        | 0.99%   |
| Sun SUNW,Sun-Blade-1500                  | 1        | 0.99%   |
| Sun SUNW,Sun-Blade-100                   | 1        | 0.99%   |
| Shuttle TERRA_PC                         | 1        | 0.99%   |
| PC Engines apu6                          | 1        | 0.99%   |
| PC Engines APU3                          | 1        | 0.99%   |
| MW GMLK-2_5G4L                           | 1        | 0.99%   |
| Lenovo ThinkCentre M75t Gen 2 11KECTO1WW | 1        | 0.99%   |
| Intel Q3XXG4-P V1.0                      | 1        | 0.99%   |
| Intel HURONRIVER                         | 1        | 0.99%   |
| Intel D54250WYK H13922-303               | 1        | 0.99%   |
| Infoblox IB-1410                         | 1        | 0.99%   |
| HPE ProLiant MicroServer Gen10           | 1        | 0.99%   |
| HP Z620 Workstation                      | 1        | 0.99%   |
| HP Z600 Workstation                      | 1        | 0.99%   |
| HP ProLiant ML350p Gen8                  | 1        | 0.99%   |
| HP ProLiant MicroServer Gen8             | 1        | 0.99%   |
| HP Compaq Elite 8300 SFF                 | 1        | 0.99%   |
| HP Compaq Elite 8300 CMT                 | 1        | 0.99%   |
| HP Compaq 8200 Elite SFF PC              | 1        | 0.99%   |
| HP Compaq 8200 Elite CMT PC              | 1        | 0.99%   |
| Gigabyte X570 AORUS MASTER               | 1        | 0.99%   |
| Gigabyte X399 DESIGNARE EX               | 1        | 0.99%   |
| Gigabyte H97N-WIFI                       | 1        | 0.99%   |
| Gigabyte H67A-UD3H-B3                    | 1        | 0.99%   |
| Gigabyte BRi3(H)-10110                   | 1        | 0.99%   |
| Gigabyte B450M DS3H                      | 1        | 0.99%   |
| Gigabyte 990FXA-UD3                      | 1        | 0.99%   |
| Dell XPS420                              | 1        | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| PC Engines APU2                 | 16       | 15.84%  |
| Unknown                         | 12       | 11.88%  |
| PC Engines apu4                 | 11       | 10.89%  |
| HP Compaq                       | 4        | 3.96%   |
| Protectli FW6                   | 3        | 2.97%   |
| ASRock A320M-ITX                | 3        | 2.97%   |
| Sun SUNW                        | 2        | 1.98%   |
| Shuttle DS10U                   | 2        | 1.98%   |
| HP ProLiant                     | 2        | 1.98%   |
| Dell Precision                  | 2        | 1.98%   |
| Apple MacPro5                   | 2        | 1.98%   |
| Acer Aspire                     | 2        | 1.98%   |
| YANYU D19SL                     | 1        | 0.99%   |
| Supermicro X9SCL                | 1        | 0.99%   |
| Supermicro SYS-1019D-4C-FHN13TP | 1        | 0.99%   |
| Supermicro PDSML                | 1        | 0.99%   |
| Shuttle TERRA                   | 1        | 0.99%   |
| PC Engines apu6                 | 1        | 0.99%   |
| PC Engines APU3                 | 1        | 0.99%   |
| MW GMLK-2                       | 1        | 0.99%   |
| Lenovo ThinkCentre              | 1        | 0.99%   |
| Intel Q3XXG4-P                  | 1        | 0.99%   |
| Intel HURONRIVER                | 1        | 0.99%   |
| Intel D54250WYK                 | 1        | 0.99%   |
| Infoblox IB-1410                | 1        | 0.99%   |
| HPE ProLiant                    | 1        | 0.99%   |
| HP Z620                         | 1        | 0.99%   |
| HP Z600                         | 1        | 0.99%   |
| Gigabyte X570                   | 1        | 0.99%   |
| Gigabyte X399                   | 1        | 0.99%   |
| Gigabyte H97N-WIFI              | 1        | 0.99%   |
| Gigabyte H67A-UD3H-B3           | 1        | 0.99%   |
| Gigabyte BRi3(H)-10110          | 1        | 0.99%   |
| Gigabyte B450M                  | 1        | 0.99%   |
| Gigabyte 990FXA-UD3             | 1        | 0.99%   |
| Dell XPS420                     | 1        | 0.99%   |
| Dell OptiPlex                   | 1        | 0.99%   |
| Biostar H61MHV2                 | 1        | 0.99%   |
| BESSTAR Tech X35G               | 1        | 0.99%   |
| ASUS Z170-K                     | 1        | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 22       | 21.78%  |
| 2016    | 18       | 17.82%  |
| 2020    | 16       | 15.84%  |
| 2012    | 7        | 6.93%   |
| 2021    | 6        | 5.94%   |
| 2019    | 6        | 5.94%   |
| 2022    | 5        | 4.95%   |
| 2013    | 5        | 4.95%   |
| 2015    | 4        | 3.96%   |
| 2017    | 3        | 2.97%   |
| 2011    | 3        | 2.97%   |
| Unknown | 3        | 2.97%   |
| 2008    | 2        | 1.98%   |
| 2007    | 1        | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 101      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 67.33%  |
| Yes  | 33       | 32.67%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 32       | 31.07%  |
| 8.01-16.0   | 26       | 25.24%  |
| 16.01-24.0  | 24       | 23.3%   |
| 32.01-64.0  | 11       | 10.68%  |
| 64.01-256.0 | 4        | 3.88%   |
| 2.01-3.0    | 3        | 2.91%   |
| 1.01-2.0    | 1        | 0.97%   |
| 0.01-0.5    | 1        | 0.97%   |
| Unknown     | 1        | 0.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 49       | 45.79%  |
| 0.51-1.0   | 30       | 28.04%  |
| 1.01-2.0   | 9        | 8.41%   |
| 2.01-3.0   | 7        | 6.54%   |
| 4.01-8.0   | 3        | 2.8%    |
| 3.01-4.0   | 3        | 2.8%    |
| 8.01-16.0  | 2        | 1.87%   |
| 0          | 2        | 1.87%   |
| 16.01-24.0 | 1        | 0.93%   |
| Unknown    | 1        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 69.9%   |
| 0      | 13       | 12.62%  |
| 2      | 5        | 4.85%   |
| 4      | 4        | 3.88%   |
| 6      | 3        | 2.91%   |
| 3      | 3        | 2.91%   |
| 17     | 1        | 0.97%   |
| 16     | 1        | 0.97%   |
| 5      | 1        | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 86.14%  |
| Yes       | 14       | 13.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 100      | 99.01%  |
| No        | 1        | 0.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 85.15%  |
| Yes       | 15       | 14.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 88.12%  |
| Yes       | 12       | 11.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Switzerland | 101      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Zurich                             | 22       | 18.18%  |
| Winterthur                         | 6        | 4.96%   |
| Gachnang                           | 6        | 4.96%   |
| Gordola                            | 5        | 4.13%   |
| St. Moritz                         | 3        | 2.48%   |
| Lenzburg                           | 3        | 2.48%   |
| Lausanne                           | 3        | 2.48%   |
| Basel                              | 3        | 2.48%   |
| St. Gallen                         | 2        | 1.65%   |
| Riehen                             | 2        | 1.65%   |
| Ottenbach                          | 2        | 1.65%   |
| Oensingen                          | 2        | 1.65%   |
| Mettmenstetten                     | 2        | 1.65%   |
| Horgen                             | 2        | 1.65%   |
| Yverdon-les-Bains                  | 1        | 0.83%   |
| Yens                               | 1        | 0.83%   |
| Worblaufen                         | 1        | 0.83%   |
| Willisau                           | 1        | 0.83%   |
| Wiesendangen / Wiesendangen (Dorf) | 1        | 0.83%   |
| Wetzikon                           | 1        | 0.83%   |
| Wettswil                           | 1        | 0.83%   |
| Welschenrohr                       | 1        | 0.83%   |
| Uster                              | 1        | 0.83%   |
| Trogen                             | 1        | 0.83%   |
| Suhr                               | 1        | 0.83%   |
| Steckborn                          | 1        | 0.83%   |
| Sitterdorf                         | 1        | 0.83%   |
| Rumlang                            | 1        | 0.83%   |
| Riviera                            | 1        | 0.83%   |
| Rickenbach bei Wil                 | 1        | 0.83%   |
| Richterswil                        | 1        | 0.83%   |
| Renens                             | 1        | 0.83%   |
| Pfaeffikon                         | 1        | 0.83%   |
| Opfikon                            | 1        | 0.83%   |
| Oftringen                          | 1        | 0.83%   |
| Oberrieden                         | 1        | 0.83%   |
| Niederbipp                         | 1        | 0.83%   |
| Nidau                              | 1        | 0.83%   |
| Neuenegg                           | 1        | 0.83%   |
| Naters                             | 1        | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 41     | 21.36%  |
| Phison              | 13       | 16     | 12.62%  |
| WDC                 | 10       | 18     | 9.71%   |
| Kingston            | 9        | 11     | 8.74%   |
| Seagate             | 7        | 8      | 6.8%    |
| Intel               | 5        | 21     | 4.85%   |
| Hoodisk             | 5        | 7      | 4.85%   |
| Crucial             | 4        | 10     | 3.88%   |
| HPT                 | 3        | 35     | 2.91%   |
| Hitachi             | 3        | 3      | 2.91%   |
| Corsair             | 3        | 4      | 2.91%   |
| China               | 3        | 4      | 2.91%   |
| Toshiba             | 2        | 3      | 1.94%   |
| ShiJi               | 2        | 7      | 1.94%   |
| SanDisk             | 2        | 5      | 1.94%   |
| Transcend           | 1        | 1      | 0.97%   |
| SPCC                | 1        | 2      | 0.97%   |
| PNY                 | 1        | 1      | 0.97%   |
| OPENBSD             | 1        | 1      | 0.97%   |
| Micron Technology   | 1        | 2      | 0.97%   |
| Hewlett-Packard     | 1        | 10     | 0.97%   |
| FORESEE             | 1        | 1      | 0.97%   |
| BIWIN               | 1        | 1      | 0.97%   |
| Apple               | 1        | 1      | 0.97%   |
| A-DATA Technology   | 1        | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Phison SATA SSD 16GB                 | 10       | 7.04%   |
| Hoodisk SSD 32GB                     | 5        | 3.52%   |
| Samsung SSD 860 EVO 250GB            | 4        | 2.82%   |
| Phison SATA SSD 32GB                 | 3        | 2.11%   |
| Kingston RBUSNS8180DS3128GH 128GB    | 3        | 2.11%   |
| HPT DISK 0_3 3TB                     | 3        | 2.11%   |
| HPT DISK 0_2 3TB                     | 3        | 2.11%   |
| HPT DISK 0_1 6TB                     | 3        | 2.11%   |
| HPT DISK 0_0 4TB                     | 3        | 2.11%   |
| WDC WD6002FRYZ-01WD5B1 6TB           | 2        | 1.41%   |
| ShiJi SSD 128GB                      | 2        | 1.41%   |
| Samsung SSD 960 EVO 250GB            | 2        | 1.41%   |
| Samsung SSD 860 PRO 256GB            | 2        | 1.41%   |
| Samsung SSD 850 PRO 256GB            | 2        | 1.41%   |
| Samsung SSD 840 Series 120GB         | 2        | 1.41%   |
| HPT DISK 0_9 3TB                     | 2        | 1.41%   |
| HPT DISK 0_8 3TB                     | 2        | 1.41%   |
| HPT DISK 0_7 3TB                     | 2        | 1.41%   |
| HPT DISK 0_6 3TB                     | 2        | 1.41%   |
| HPT DISK 0_5 18TB                    | 2        | 1.41%   |
| HPT DISK 0_4 18TB                    | 2        | 1.41%   |
| HPT DISK 0_14 3TB                    | 2        | 1.41%   |
| HPT DISK 0_13 2TB                    | 2        | 1.41%   |
| HPT DISK 0_12 1TB                    | 2        | 1.41%   |
| HPT DISK 0_11 1TB                    | 2        | 1.41%   |
| HPT DISK 0_10 1TB                    | 2        | 1.41%   |
| Hitachi HDS721050CLA360 500GB        | 2        | 1.41%   |
| Crucial CT250MX500SSD1 250GB         | 2        | 1.41%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1        | 0.7%    |
| WDC WDS240G2G0B-00EPW0 240GB         | 1        | 0.7%    |
| WDC WDS120G2G0B-00EPW0 120GB         | 1        | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB         | 1        | 0.7%    |
| WDC WD40EFRX-68WT0N0 4TB             | 1        | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 0.7%    |
| WDC WD2002FYPS-01U1B0 2TB            | 1        | 0.7%    |
| WDC WD10EALX-009BA0 1TB              | 1        | 0.7%    |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1        | 0.7%    |
| Transcend TS64GMSA230S 64GB          | 1        | 0.7%    |
| Toshiba MQ03UBB300 3TB               | 1        | 0.7%    |
| Toshiba MK1059GSM 1TB                | 1        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Seagate         | 7        | 8      | 29.17%  |
| WDC             | 5        | 11     | 20.83%  |
| HPT             | 3        | 35     | 12.5%   |
| Hitachi         | 3        | 3      | 12.5%   |
| Toshiba         | 2        | 3      | 8.33%   |
| OPENBSD         | 1        | 1      | 4.17%   |
| Hewlett-Packard | 1        | 8      | 4.17%   |
| China           | 1        | 1      | 4.17%   |
| Apple           | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 32     | 23.94%  |
| Phison              | 13       | 16     | 18.31%  |
| Kingston            | 8        | 9      | 11.27%  |
| Intel               | 5        | 21     | 7.04%   |
| Hoodisk             | 5        | 7      | 7.04%   |
| Crucial             | 4        | 10     | 5.63%   |
| WDC                 | 3        | 5      | 4.23%   |
| ShiJi               | 2        | 7      | 2.82%   |
| SanDisk             | 2        | 5      | 2.82%   |
| Corsair             | 2        | 3      | 2.82%   |
| China               | 2        | 3      | 2.82%   |
| Transcend           | 1        | 1      | 1.41%   |
| SPCC                | 1        | 2      | 1.41%   |
| PNY                 | 1        | 1      | 1.41%   |
| Micron Technology   | 1        | 2      | 1.41%   |
| Hewlett-Packard     | 1        | 2      | 1.41%   |
| FORESEE             | 1        | 1      | 1.41%   |
| BIWIN               | 1        | 1      | 1.41%   |
| A-DATA Technology   | 1        | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 70       | 129    | 71.43%  |
| HDD  | 17       | 71     | 17.35%  |
| NVMe | 11       | 14     | 11.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 78       | 200    | 87.64%  |
| NVMe | 11       | 14     | 12.36%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 77       | 144    | 72.64%  |
| 0.51-1.0   | 7        | 12     | 6.6%    |
| 4.01-10.0  | 6        | 11     | 5.66%   |
| 2.01-3.0   | 5        | 19     | 4.72%   |
| 1.01-2.0   | 5        | 6      | 4.72%   |
| 3.01-4.0   | 4        | 4      | 3.77%   |
| 10.01-20.0 | 2        | 4      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 48       | 46.15%  |
| 1-20       | 19       | 18.27%  |
| 51-100     | 16       | 15.38%  |
| 21-50      | 12       | 11.54%  |
| 251-500    | 4        | 3.85%   |
| 501-1000   | 4        | 3.85%   |
| 1001-2000  | 1        | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 95       | 88.79%  |
| 21-50   | 7        | 6.54%   |
| 51-100  | 3        | 2.8%    |
| 251-500 | 2        | 1.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB  | 1        | 2      | 8.33%   |
| WDC WD6002FRYZ-01WD5B1 6TB    | 1        | 6      | 8.33%   |
| WDC WD40EFRX-68WT0N0 4TB      | 1        | 1      | 8.33%   |
| WDC WD2002FYPS-01U1B0 2TB     | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB         | 1        | 1      | 8.33%   |
| Seagate ST3500413AS 500GB     | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB  | 1        | 1      | 8.33%   |
| Intel SSDSC2BW240A4 240GB     | 1        | 2      | 8.33%   |
| Intel SSDSA2M160G2GC 160GB    | 1        | 2      | 8.33%   |
| Intel SSDSA2BW160G3H 160GB    | 1        | 5      | 8.33%   |
| Hitachi HDS721050CLA660 500GB | 1        | 1      | 8.33%   |
| Corsair Force 3 SSD 120GB     | 1        | 2      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 3        | 10     | 27.27%  |
| Intel    | 3        | 9      | 27.27%  |
| Toshiba  | 1        | 1      | 9.09%   |
| Seagate  | 1        | 1      | 9.09%   |
| Kingston | 1        | 1      | 9.09%   |
| Hitachi  | 1        | 1      | 9.09%   |
| Corsair  | 1        | 2      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 8      | 40%     |
| Toshiba | 1        | 1      | 20%     |
| Seagate | 1        | 1      | 20%     |
| Hitachi | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 6        | 14     | 60%     |
| HDD  | 4        | 11     | 40%     |

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
| Works    | 80       | 147    | 85.11%  |
| Malfunc  | 9        | 25     | 9.57%   |
| Detected | 5        | 42     | 5.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 55       | 45.45%  |
| AMD                         | 42       | 34.71%  |
| Samsung Electronics         | 8        | 6.61%   |
| HighPoint Technologies      | 3        | 2.48%   |
| ASMedia Technology          | 3        | 2.48%   |
| ULi Electronics             | 2        | 1.65%   |
| SanDisk                     | 2        | 1.65%   |
| Marvell Technology Group    | 2        | 1.65%   |
| Phison Electronics          | 1        | 0.83%   |
| Kingston Technology Company | 1        | 0.83%   |
| Hewlett-Packard             | 1        | 0.83%   |
| Chelsio Communications      | 1        | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28       | 20%     |
| AMD FCH SATA Controller [IDE mode]                                             | 10       | 7.14%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5        | 3.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 3.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 2.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4        | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3        | 2.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3        | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 2.14%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.14%   |
| AMD FCH SATA Controller D                                                      | 3        | 2.14%   |
| ULi M5229 IDE                                                                  | 2        | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 1.43%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2        | 1.43%   |
| Intel Atom Processor C3000 Series SATA Controller 1                            | 2        | 1.43%   |
| Intel Atom Processor C3000 Series SATA Controller 0                            | 2        | 1.43%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 1.43%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 2        | 1.43%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.71%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.71%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1        | 0.71%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 0.71%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.71%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 0.71%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.71%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1        | 0.71%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 0.71%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 0.71%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1        | 0.71%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 82       | 67.21%  |
| IDE  | 18       | 14.75%  |
| NVMe | 12       | 9.84%   |
| RAID | 7        | 5.74%   |
| SCSI | 2        | 1.64%   |
| SAS  | 1        | 0.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 57       | 56.44%  |
| AMD     | 42       | 41.58%  |
| Unknown | 2        | 1.98%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 29       | 28.71%  |
| Intel Celeron CPU 3865U @ 1.80GHz           | 4        | 3.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 2.97%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.98%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 2        | 1.98%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 1.98%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 2        | 1.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2        | 1.98%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.98%   |
|                                             | 2        | 1.98%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 1        | 0.99%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1        | 0.99%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 0.99%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.99%   |
| Intel Xeon CPU E5630 @ 2.53GHz              | 1        | 0.99%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.99%   |
| Intel Xeon CPU E5-2620 @ 2.00GHz            | 1        | 0.99%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.99%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.99%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz        | 1        | 0.99%   |
| Intel Xeon CPU E                            | 1        | 0.99%   |
| Intel Pentium Gold G7400                    | 1        | 0.99%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.99%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.99%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.99%   |
| Intel Core i7-2600K CPU                     | 1        | 0.99%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1        | 0.99%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.99%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1        | 0.99%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 0.99%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 0.99%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1        | 0.99%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1        | 0.99%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD GX                 | 29       | 28.71%  |
| Intel Core i5          | 14       | 13.86%  |
| Intel Xeon             | 11       | 10.89%  |
| Intel Celeron          | 10       | 9.9%    |
| Intel Core i7          | 8        | 7.92%   |
| Intel Core i3          | 5        | 4.95%   |
| Other                  | 4        | 3.96%   |
| AMD Ryzen 5            | 4        | 3.96%   |
| Intel Atom             | 3        | 2.97%   |
| AMD Ryzen 7            | 3        | 2.97%   |
| Intel Core 2 Duo       | 2        | 1.98%   |
| Intel Pentium Gold     | 1        | 0.99%   |
| Intel Pentium          | 1        | 0.99%   |
| AMD Ryzen Threadripper | 1        | 0.99%   |
| AMD Ryzen 7 PRO        | 1        | 0.99%   |
| AMD Ryzen 3            | 1        | 0.99%   |
| AMD Opteron            | 1        | 0.99%   |
| AMD Geode Integrated   | 1        | 0.99%   |
| AMD FX                 | 1        | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 59       | 58.42%  |
| 2       | 15       | 14.85%  |
| 8       | 10       | 9.9%    |
| 16      | 4        | 3.96%   |
| 6       | 4        | 3.96%   |
| 1       | 3        | 2.97%   |
| 12      | 2        | 1.98%   |
| Unknown | 2        | 1.98%   |
| 32      | 1        | 0.99%   |
| 10      | 1        | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 95       | 94.06%  |
| 2       | 3        | 2.97%   |
| Unknown | 2        | 1.98%   |
| 4       | 1        | 0.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 67       | 66.34%  |
| 2       | 30       | 29.7%   |
| Unknown | 4        | 3.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 29       | 28.71%  |
| KabyLake      | 13       | 12.87%  |
| IvyBridge     | 8        | 7.92%   |
| SandyBridge   | 6        | 5.94%   |
| Haswell       | 6        | 5.94%   |
| Unknown       | 4        | 3.96%   |
| Zen+          | 3        | 2.97%   |
| Zen 3         | 3        | 2.97%   |
| Zen           | 3        | 2.97%   |
| Goldmont plus | 3        | 2.97%   |
| Westmere      | 2        | 1.98%   |
| TigerLake     | 2        | 1.98%   |
| Skylake       | 2        | 1.98%   |
| Silvermont    | 2        | 1.98%   |
| Nehalem       | 2        | 1.98%   |
| Goldmont      | 2        | 1.98%   |
| Core          | 2        | 1.98%   |
| CometLake     | 2        | 1.98%   |
| Zen 2         | 1        | 0.99%   |
| Piledriver    | 1        | 0.99%   |
| Penryn        | 1        | 0.99%   |
| IceLake       | 1        | 0.99%   |
| Geode         | 1        | 0.99%   |
| Excavator     | 1        | 0.99%   |
| Broadwell     | 1        | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 36       | 52.17%  |
| AMD                                          | 12       | 17.39%  |
| Nvidia                                       | 10       | 14.49%  |
| ASPEED Technology                            | 5        | 7.25%   |
| Matrox Electronics Systems                   | 4        | 5.8%    |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 1.45%   |
| 3DLabs                                       | 1        | 1.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| ASPEED Technology ASPEED Graphics Family                                    | 5        | 7.25%   |
| Intel HD Graphics 610                                                       | 4        | 5.8%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 4.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3        | 4.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 4.35%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 2.9%    |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2        | 2.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2        | 2.9%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.9%    |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 2.9%    |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)              | 1        | 1.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.45%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.45%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.45%   |
| Nvidia GK107 [GeForce GT 640 OEM]                                           | 1        | 1.45%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.45%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.45%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.45%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.45%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                 | 1        | 1.45%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1        | 1.45%   |
| Intel HD Graphics 6000                                                      | 1        | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.45%   |
| Intel Alder Lake-S GT1 [UHD Graphics 710]                                   | 1        | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.45%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.45%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                      | 1        | 1.45%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                            | 1        | 1.45%   |
| AMD Renoir                                                                  | 1        | 1.45%   |
| AMD Rage 3 [Rage XL PCI]                                                    | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 36       | 35.64%  |
| Other      | 32       | 31.68%  |
| 1 x AMD    | 12       | 11.88%  |
| 1 x Nvidia | 10       | 9.9%    |
| 1 x ASPEED | 5        | 4.95%   |
| 1 x Matrox | 4        | 3.96%   |
| 1 x XGI    | 1        | 0.99%   |
| 1 x 3DLabs | 1        | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 60       | 59.41%  |
| Unknown     | 34       | 33.66%  |
| Proprietary | 7        | 6.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 93       | 92.08%  |
| 3.01-4.0   | 3        | 2.97%   |
| 1.01-2.0   | 3        | 2.97%   |
| 5.01-6.0   | 1        | 0.99%   |
| 2.01-3.0   | 1        | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 2        | 18.18%  |
| Samsung Electronics  | 1        | 9.09%   |
| Philips              | 1        | 9.09%   |
| NEC Computers        | 1        | 9.09%   |
| LG Electronics       | 1        | 9.09%   |
| Lenovo               | 1        | 9.09%   |
| Iiyama               | 1        | 9.09%   |
| Fujitsu Siemens      | 1        | 9.09%   |
| Eizo                 | 1        | 9.09%   |
| Ancor Communications | 1        | 9.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch | 1        | 8.33%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                | 1        | 8.33%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                      | 1        | 8.33%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                 | 1        | 8.33%   |
| LG Electronics LCD Monitor LG Ultra HD                            | 1        | 8.33%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch          | 1        | 8.33%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch             | 1        | 8.33%   |
| Fujitsu Siemens S19-1 FUS0517 1280x1024 380x300mm 19.1-inch       | 1        | 8.33%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                | 1        | 8.33%   |
| Ancor Communications VS278 ACI27A1 1920x1080 600x340mm 27.2-inch  | 1        | 8.33%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                | 1        | 8.33%   |
| Acer XB271HU A ACR052F 2560x1440 600x340mm 27.2-inch              | 1        | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 5        | 41.67%  |
| 2560x1440 (QHD)  | 3        | 25%     |
| 3840x2160 (4K)   | 1        | 8.33%   |
| 1280x1024 (SXGA) | 1        | 8.33%   |
| 11520x2160       | 1        | 8.33%   |
| Unknown          | 1        | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 45.45%  |
| Unknown | 2        | 18.18%  |
| 65      | 1        | 9.09%   |
| 31      | 1        | 9.09%   |
| 23      | 1        | 9.09%   |
| 19      | 1        | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 54.55%  |
| Unknown     | 2        | 18.18%  |
| 601-700     | 1        | 9.09%   |
| 351-400     | 1        | 9.09%   |
| 1001-1500   | 1        | 9.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 72.73%  |
| Unknown | 2        | 18.18%  |
| 5/4     | 1        | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 5        | 45.45%  |
| Unknown        | 2        | 18.18%  |
| More than 1000 | 1        | 9.09%   |
| 351-500        | 1        | 9.09%   |
| 201-250        | 1        | 9.09%   |
| 151-200        | 1        | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4        | 36.36%  |
| 101-120 | 3        | 27.27%  |
| Unknown | 2        | 18.18%  |
| 1-50    | 1        | 9.09%   |
| 121-160 | 1        | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 90       | 89.11%  |
| 1     | 10       | 9.9%    |
| 2     | 1        | 0.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 89       | 67.94%  |
| Realtek Semiconductor             | 17       | 12.98%  |
| Broadcom                          | 8        | 6.11%   |
| Qualcomm Atheros                  | 3        | 2.29%   |
| Mellanox Technologies             | 2        | 1.53%   |
| American Megatrends               | 2        | 1.53%   |
| VIA Technologies                  | 1        | 0.76%   |
| U-Blox                            | 1        | 0.76%   |
| Qualcomm Atheros Communications   | 1        | 0.76%   |
| QLogic                            | 1        | 0.76%   |
| Oracle/SUN                        | 1        | 0.76%   |
| Microchip Technology              | 1        | 0.76%   |
| Huawei Technologies               | 1        | 0.76%   |
| Free Software Initiative of Japan | 1        | 0.76%   |
| Chelsio Communications            | 1        | 0.76%   |
| Aquantia                          | 1        | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 31       | 18.24%  |
| Intel I210 Gigabit Network Connection                                         | 20       | 11.76%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13       | 7.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 4.12%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 3.53%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 2.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.35%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 1.76%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 1.76%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 1.76%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2        | 1.18%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2        | 1.18%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 1.18%   |
| Intel Ethernet Controller X550                                                | 2        | 1.18%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.18%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.18%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 1.18%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 1.18%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 1.18%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 1.18%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.18%   |
| American Megatrends Virtual Ethernet                                          | 2        | 1.18%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.59%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.59%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.59%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.59%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.59%   |
| Microchip CDC RS-232 Emulation Demo                                           | 1        | 0.59%   |
| Mellanox MT2894 Family [ConnectX-6 Lx]                                        | 1        | 0.59%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1        | 0.59%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 0.59%   |
| Intel Wireless 7260                                                           | 1        | 0.59%   |
| Intel Wireless 3160                                                           | 1        | 0.59%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 50%     |
| Realtek Semiconductor           | 3        | 21.43%  |
| Qualcomm Atheros                | 2        | 14.29%  |
| Qualcomm Atheros Communications | 1        | 7.14%   |
| Broadcom                        | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3        | 21.43%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 14.29%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2        | 14.29%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 7.14%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 7.14%   |
| Intel Wireless 8265 / 8275                                     | 1        | 7.14%   |
| Intel Wireless 7260                                            | 1        | 7.14%   |
| Intel Wireless 3160                                            | 1        | 7.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 7.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 86       | 74.78%  |
| Realtek Semiconductor  | 14       | 12.17%  |
| Broadcom               | 7        | 6.09%   |
| American Megatrends    | 2        | 1.74%   |
| VIA Technologies       | 1        | 0.87%   |
| Qualcomm Atheros       | 1        | 0.87%   |
| QLogic                 | 1        | 0.87%   |
| Oracle/SUN             | 1        | 0.87%   |
| Chelsio Communications | 1        | 0.87%   |
| Aquantia               | 1        | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 31       | 20.67%  |
| Intel I210 Gigabit Network Connection                                         | 20       | 13.33%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13       | 8.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 4.67%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 4%      |
| Intel Ethernet Controller I225-V                                              | 4        | 2.67%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 2.67%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.67%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2%      |
| Intel 82583V Gigabit Network Connection                                       | 3        | 2%      |
| Intel 82579V Gigabit Network Connection                                       | 3        | 2%      |
| Intel I210 Gigabit Fiber Network Connection                                   | 2        | 1.33%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 1.33%   |
| Intel Ethernet Controller X550                                                | 2        | 1.33%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.33%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.33%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 1.33%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 1.33%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 1.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 1.33%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.33%   |
| American Megatrends Virtual Ethernet                                          | 2        | 1.33%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.67%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.67%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.67%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1        | 0.67%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1        | 0.67%   |
| Intel Ethernet Controller I226-V                                              | 1        | 0.67%   |
| Intel Ethernet Controller E810-XXV for SFP                                    | 1        | 0.67%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1        | 0.67%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.67%   |
| Intel Ethernet Connection I354                                                | 1        | 0.67%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.67%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.67%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.67%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 100      | 83.33%  |
| WiFi     | 14       | 11.67%  |
| Modem    | 3        | 2.5%    |
| Unknown  | 3        | 2.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 97.96%  |
| WiFi     | 2        | 2.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 31       | 30.39%  |
| 4     | 20       | 19.61%  |
| 6     | 13       | 12.75%  |
| 5     | 12       | 11.76%  |
| 1     | 12       | 11.76%  |
| 2     | 8        | 7.84%   |
| 13    | 2        | 1.96%   |
| 8     | 2        | 1.96%   |
| 14    | 1        | 0.98%   |
| 7     | 1        | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 80       | 72.73%  |
| Yes  | 30       | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 6        | 50%     |
| IMC Networks     | 2        | 16.67%  |
| ASUSTek Computer | 2        | 16.67%  |
| Apple            | 2        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                          | 3        | 25%     |
| Intel Bluetooth wireless interface             | 2        | 16.67%  |
| IMC Networks Realtek Bluetooth Adapter         | 2        | 16.67%  |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 2        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1        | 8.33%   |
| ASUS Bluetooth Controller                      | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 43       | 63.24%  |
| AMD                   | 13       | 19.12%  |
| Nvidia                | 8        | 11.76%  |
| ULi Electronics       | 2        | 2.94%   |
| Realtek Semiconductor | 1        | 1.47%   |
| Logitech              | 1        | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 6.41%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 6.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 3.85%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 3        | 3.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3        | 3.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3        | 3.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 3.85%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 2.56%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2        | 2.56%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 2.56%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 2.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 2.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.56%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                | 1        | 1.28%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 1.28%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 1.28%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 1.28%   |
| Logitech H600 [Wireless Headset]                                                  | 1        | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.28%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1        | 1.28%   |
| Intel Jasper Lake HD Audio                                                        | 1        | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1        | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.28%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 1.28%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.28%   |
| Intel Alder Lake-S HD Audio Controller                                            | 1        | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 1.28%   |
| Intel 8 Series HD Audio Controller                                                | 1        | 1.28%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1        | 1.28%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 28       | 29.17%  |
| Unknown             | 20       | 20.83%  |
| Samsung Electronics | 10       | 10.42%  |
| Crucial             | 9        | 9.38%   |
| SK hynix            | 8        | 8.33%   |
| Corsair             | 8        | 8.33%   |
| Micron Technology   | 5        | 5.21%   |
| Nanya Technology    | 2        | 2.08%   |
| Hewlett-Packard     | 2        | 2.08%   |
| Unknown (0x05F7)    | 1        | 1.04%   |
| Unknown (07FB)      | 1        | 1.04%   |
| Tigo                | 1        | 1.04%   |
| Super Talent        | 1        | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 12       | 11.88%  |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s         | 3        | 2.97%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s         | 3        | 2.97%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s         | 3        | 2.97%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2133MT/s       | 3        | 2.97%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 2        | 1.98%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 2        | 1.98%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 2        | 1.98%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s        | 2        | 1.98%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s        | 2        | 1.98%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s        | 2        | 1.98%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s       | 2        | 1.98%   |
| Crucial RAM CT8G4SFRA32A.M8FR 8GB SODIMM DDR4 3200MT/s       | 2        | 1.98%   |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s         | 2        | 1.98%   |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s         | 2        | 1.98%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                   | 1        | 0.99%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1        | 0.99%   |
| Unknown (0x05F7) RAM Module 1GB FB-DIMM DDR2 800MT/s         | 1        | 0.99%   |
| Unknown (07FB) RAM GSA8G4SCL196P-26 8GB SODIMM DDR4 2667MT/s | 1        | 0.99%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                 | 1        | 0.99%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s        | 1        | 0.99%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 0.99%   |
| SK hynix RAM Module 1GB FB-DIMM DDR2 800MT/s                 | 1        | 0.99%   |
| SK hynix RAM HMT42GR7MFR4C-PB 16384MB DIMM DDR3 1600MT/s     | 1        | 0.99%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s                   | 1        | 0.99%   |
| Samsung RAM Module 16GB DIMM DDR3 1066MT/s                   | 1        | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1        | 0.99%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1        | 0.99%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 1        | 0.99%   |
| Samsung RAM M393B2G70DB0-CK0 16GB DIMM DDR3 1600MT/s         | 1        | 0.99%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s         | 1        | 0.99%   |
| Samsung RAM M393B1K70BH1-CH9 8GB DIMM DDR3 1333MT/s          | 1        | 0.99%   |
| Samsung RAM M393A1K43BB1-CTD 8GB RIMM DDR4 2133MT/s          | 1        | 0.99%   |
| Samsung RAM M391B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.99%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.99%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s            | 1        | 0.99%   |
| Nanya RAM M2S4G64CC88D5N-DI 4GB SODIMM DDR3 1600MT/s         | 1        | 0.99%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s           | 1        | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 43       | 51.19%  |
| DDR4    | 36       | 42.86%  |
| DDR2    | 3        | 3.57%   |
| LPDDR4  | 1        | 1.19%   |
| Unknown | 1        | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 47       | 55.95%  |
| SODIMM       | 34       | 40.48%  |
| Row Of Chips | 1        | 1.19%   |
| RIMM         | 1        | 1.19%   |
| FB-DIMM      | 1        | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 41       | 46.59%  |
| 4096  | 28       | 31.82%  |
| 16384 | 9        | 10.23%  |
| 2048  | 5        | 5.68%   |
| 32768 | 2        | 2.27%   |
| 1024  | 2        | 2.27%   |
| 512   | 1        | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 31       | 33.33%  |
| 2667  | 11       | 11.83%  |
| 1600  | 11       | 11.83%  |
| 3200  | 9        | 9.68%   |
| 2133  | 9        | 9.68%   |
| 2400  | 8        | 8.6%    |
| 2666  | 5        | 5.38%   |
| 667   | 4        | 4.3%    |
| 800   | 2        | 2.15%   |
| 3600  | 1        | 1.08%   |
| 1800  | 1        | 1.08%   |
| 1066  | 1        | 1.08%   |

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
| 0     | 47       | 44.34%  |
| 1     | 36       | 33.96%  |
| 2     | 15       | 14.15%  |
| 3     | 7        | 6.6%    |
| 4     | 1        | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 45       | 60%     |
| Firewire controller      | 8        | 10.67%  |
| Net/wireless             | 6        | 8%      |
| Bluetooth                | 6        | 8%      |
| Net/ethernet             | 4        | 5.33%   |
| Sound                    | 2        | 2.67%   |
| Card reader              | 2        | 2.67%   |
| Network                  | 1        | 1.33%   |
| Graphics card            | 1        | 1.33%   |

