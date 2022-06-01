BSD in Switzerland - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for BSD in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 235

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| PC Engines    | apu4                        | Desktop     | [1067180759](https://bsd-hardware.info/?probe=1067180759) | May 31, 2022 |
| PC Engines    | apu4                        | Desktop     | [214bc37259](https://bsd-hardware.info/?probe=214bc37259) | May 26, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Protectli     | FW6                         | Desktop     | [0dc7509652](https://bsd-hardware.info/?probe=0dc7509652) | May 24, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c260c2423](https://bsd-hardware.info/?probe=7c260c2423) | May 20, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8f9e0896d7](https://bsd-hardware.info/?probe=8f9e0896d7) | May 12, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [d1596f34bf](https://bsd-hardware.info/?probe=d1596f34bf) | May 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [6dfeb3d80d](https://bsd-hardware.info/?probe=6dfeb3d80d) | May 10, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [515172b464](https://bsd-hardware.info/?probe=515172b464) | May 09, 2022 |
| PC Engines    | APU2                        | Desktop     | [a2b68686f0](https://bsd-hardware.info/?probe=a2b68686f0) | Apr 27, 2022 |
| Dell          | 0TP406                      | Desktop     | [775061bc83](https://bsd-hardware.info/?probe=775061bc83) | Apr 25, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [7d9806d719](https://bsd-hardware.info/?probe=7d9806d719) | Apr 21, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [378021707a](https://bsd-hardware.info/?probe=378021707a) | Apr 17, 2022 |
| Sophos        | SG                          | Firewall    | [2b5126d5a1](https://bsd-hardware.info/?probe=2b5126d5a1) | Apr 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Sophos        | UTM                         | Firewall    | [37af5c0425](https://bsd-hardware.info/?probe=37af5c0425) | Apr 08, 2022 |
| Sophos        | UTM                         | Firewall    | [8e79b3e5bf](https://bsd-hardware.info/?probe=8e79b3e5bf) | Apr 07, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [926afc7ac8](https://bsd-hardware.info/?probe=926afc7ac8) | Apr 07, 2022 |
| Dell          | 0TP406                      | Desktop     | [9a29305ef1](https://bsd-hardware.info/?probe=9a29305ef1) | Apr 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [b6b1ec9dc1](https://bsd-hardware.info/?probe=b6b1ec9dc1) | Mar 30, 2022 |
| Deciso        | Netboard A20                | Notebook    | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7e042aa70d](https://bsd-hardware.info/?probe=7e042aa70d) | Mar 25, 2022 |
| Deciso        | Netboard A20                | Notebook    | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [abb17bcb42](https://bsd-hardware.info/?probe=abb17bcb42) | Mar 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d97ecbc95](https://bsd-hardware.info/?probe=1d97ecbc95) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [e169892276](https://bsd-hardware.info/?probe=e169892276) | Mar 18, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [456b55de38](https://bsd-hardware.info/?probe=456b55de38) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [1ed23967fd](https://bsd-hardware.info/?probe=1ed23967fd) | Mar 17, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4d7d8fd92b](https://bsd-hardware.info/?probe=4d7d8fd92b) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [95154c4898](https://bsd-hardware.info/?probe=95154c4898) | Mar 16, 2022 |
| ASUSTek       | N50Vc                       | Notebook    | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [6e5badb880](https://bsd-hardware.info/?probe=6e5badb880) | Mar 04, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7da5182091](https://bsd-hardware.info/?probe=7da5182091) | Feb 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [40ba1b35da](https://bsd-hardware.info/?probe=40ba1b35da) | Feb 24, 2022 |
| Shuttle       | DS77U                       | Notebook    | [1ca3d58dfc](https://bsd-hardware.info/?probe=1ca3d58dfc) | Feb 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [3ac0b6f7c4](https://bsd-hardware.info/?probe=3ac0b6f7c4) | Feb 21, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [fea17bcf92](https://bsd-hardware.info/?probe=fea17bcf92) | Feb 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [547be2fb61](https://bsd-hardware.info/?probe=547be2fb61) | Feb 19, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [a62eea5e4e](https://bsd-hardware.info/?probe=a62eea5e4e) | Feb 11, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [55b7348a0c](https://bsd-hardware.info/?probe=55b7348a0c) | Feb 11, 2022 |
| PC Engines    | APU2                        | Desktop     | [566948b2c1](https://bsd-hardware.info/?probe=566948b2c1) | Feb 09, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [76fadb9527](https://bsd-hardware.info/?probe=76fadb9527) | Feb 09, 2022 |
| HP            | 0B54h D                     | Desktop     | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [0fa41ad797](https://bsd-hardware.info/?probe=0fa41ad797) | Feb 06, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d04ab1a7bf](https://bsd-hardware.info/?probe=d04ab1a7bf) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| HP            | 0B54h D                     | Desktop     | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b9ed6f82cc](https://bsd-hardware.info/?probe=b9ed6f82cc) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [c6a0bd2277](https://bsd-hardware.info/?probe=c6a0bd2277) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [000331f38e](https://bsd-hardware.info/?probe=000331f38e) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [df6e313377](https://bsd-hardware.info/?probe=df6e313377) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [74b8fc0269](https://bsd-hardware.info/?probe=74b8fc0269) | Jan 30, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [3e78e7eb38](https://bsd-hardware.info/?probe=3e78e7eb38) | Jan 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [4f6a1c9c9a](https://bsd-hardware.info/?probe=4f6a1c9c9a) | Jan 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [b572e30460](https://bsd-hardware.info/?probe=b572e30460) | Jan 19, 2022 |
| ASUSTek       | N50Vc                       | Notebook    | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b11f87a501](https://bsd-hardware.info/?probe=b11f87a501) | Jan 16, 2022 |
| HP            | 3396                        | Desktop     | [236ed20a86](https://bsd-hardware.info/?probe=236ed20a86) | Jan 11, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [e38915ac8c](https://bsd-hardware.info/?probe=e38915ac8c) | Jan 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [0a82e095ee](https://bsd-hardware.info/?probe=0a82e095ee) | Jan 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [9c67eb6ecd](https://bsd-hardware.info/?probe=9c67eb6ecd) | Dec 30, 2021 |
| Casper        | EXCALIBUR G900              | Notebook    | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [3ccd5eace4](https://bsd-hardware.info/?probe=3ccd5eace4) | Dec 15, 2021 |
| ASRock        | B550 Taichi                 | Desktop     | [ed2fd72332](https://bsd-hardware.info/?probe=ed2fd72332) | Dec 14, 2021 |
| PC Engines    | apu4                        | Desktop     | [a06765ebb1](https://bsd-hardware.info/?probe=a06765ebb1) | Dec 09, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [015319ce8c](https://bsd-hardware.info/?probe=015319ce8c) | Dec 08, 2021 |
| Supermicro    | X11SDW-4C-TP13F             | Desktop     | [f424260bfa](https://bsd-hardware.info/?probe=f424260bfa) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [8f9e9ddde5](https://bsd-hardware.info/?probe=8f9e9ddde5) | Dec 02, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [b35a4b529c](https://bsd-hardware.info/?probe=b35a4b529c) | Nov 22, 2021 |
| Intel         | HURONRIVER                  | Desktop     | [741fd0e126](https://bsd-hardware.info/?probe=741fd0e126) | Nov 13, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [d08d7fde4a](https://bsd-hardware.info/?probe=d08d7fde4a) | Nov 13, 2021 |
| PC Engines    | apu4                        | Desktop     | [64cad2ccf6](https://bsd-hardware.info/?probe=64cad2ccf6) | Nov 08, 2021 |
| HP            | 3397                        | Desktop     | [3434fa8427](https://bsd-hardware.info/?probe=3434fa8427) | Nov 07, 2021 |
| HP            | 3397                        | Desktop     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cc8c604fa6](https://bsd-hardware.info/?probe=cc8c604fa6) | Nov 03, 2021 |
| BESSTAR Te... | GB7                         | Mini pc     | [45a2da748c](https://bsd-hardware.info/?probe=45a2da748c) | Oct 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0fa0f325e9](https://bsd-hardware.info/?probe=0fa0f325e9) | Oct 28, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [7f77c09ea1](https://bsd-hardware.info/?probe=7f77c09ea1) | Oct 28, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [15d56aee58](https://bsd-hardware.info/?probe=15d56aee58) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [4e91fa71b2](https://bsd-hardware.info/?probe=4e91fa71b2) | Oct 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [734ec7d9fc](https://bsd-hardware.info/?probe=734ec7d9fc) | Oct 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [4ecab88e78](https://bsd-hardware.info/?probe=4ecab88e78) | Oct 17, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [06a8c0d2ac](https://bsd-hardware.info/?probe=06a8c0d2ac) | Oct 08, 2021 |
| ASRock        | B550 Taichi                 | Desktop     | [7599775c70](https://bsd-hardware.info/?probe=7599775c70) | Oct 08, 2021 |
| PC Engines    | APU2                        | Desktop     | [7a21594bf7](https://bsd-hardware.info/?probe=7a21594bf7) | Oct 08, 2021 |
| PC Engines    | apu6                        | Desktop     | [a184c5f1b2](https://bsd-hardware.info/?probe=a184c5f1b2) | Oct 06, 2021 |
| PC Engines    | APU2                        | Desktop     | [d36e631149](https://bsd-hardware.info/?probe=d36e631149) | Oct 03, 2021 |
| Lenovo        | ThinkPad T490s 20NYS3TU0... | Notebook    | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [cec09523c6](https://bsd-hardware.info/?probe=cec09523c6) | Sep 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| PC Engines    | apu4                        | Desktop     | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | Desktop     | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [051ca0708f](https://bsd-hardware.info/?probe=051ca0708f) | Sep 03, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [23bccfa11c](https://bsd-hardware.info/?probe=23bccfa11c) | Sep 01, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [eb4948e855](https://bsd-hardware.info/?probe=eb4948e855) | Aug 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [114a632ab4](https://bsd-hardware.info/?probe=114a632ab4) | Aug 30, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [b0339f73bc](https://bsd-hardware.info/?probe=b0339f73bc) | Aug 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [5bb434cb3f](https://bsd-hardware.info/?probe=5bb434cb3f) | Aug 27, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [c28bfd784d](https://bsd-hardware.info/?probe=c28bfd784d) | Aug 27, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [47284b4819](https://bsd-hardware.info/?probe=47284b4819) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [31b995146e](https://bsd-hardware.info/?probe=31b995146e) | Aug 25, 2021 |
| PC Engines    | apu4                        | Desktop     | [9f5ec6c23f](https://bsd-hardware.info/?probe=9f5ec6c23f) | Aug 23, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [c40cb92b67](https://bsd-hardware.info/?probe=c40cb92b67) | Aug 15, 2021 |
| PC Engines    | apu4                        | Desktop     | [514a974f68](https://bsd-hardware.info/?probe=514a974f68) | Aug 10, 2021 |
| PC Engines    | APU2                        | Desktop     | [823fdc32f0](https://bsd-hardware.info/?probe=823fdc32f0) | Aug 09, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [1ac35fcecf](https://bsd-hardware.info/?probe=1ac35fcecf) | Aug 08, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [fa4ba34119](https://bsd-hardware.info/?probe=fa4ba34119) | Aug 07, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [9fe86991b5](https://bsd-hardware.info/?probe=9fe86991b5) | Aug 04, 2021 |
| Shuttle       | DS10U                       | Desktop     | [fa151322fc](https://bsd-hardware.info/?probe=fa151322fc) | Aug 03, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [772a9416ab](https://bsd-hardware.info/?probe=772a9416ab) | Aug 01, 2021 |
| PC Engines    | APU2                        | Desktop     | [4c2b89d2e6](https://bsd-hardware.info/?probe=4c2b89d2e6) | Jul 31, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [a528966ab8](https://bsd-hardware.info/?probe=a528966ab8) | Jul 30, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [51136572fc](https://bsd-hardware.info/?probe=51136572fc) | Jul 29, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8a2efd6b5b](https://bsd-hardware.info/?probe=8a2efd6b5b) | Jul 25, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [fea747e9eb](https://bsd-hardware.info/?probe=fea747e9eb) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [18ce49973d](https://bsd-hardware.info/?probe=18ce49973d) | Jul 24, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [f29fab4508](https://bsd-hardware.info/?probe=f29fab4508) | Jul 23, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [b7c3a2b2e4](https://bsd-hardware.info/?probe=b7c3a2b2e4) | Jul 23, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [89938d9a3a](https://bsd-hardware.info/?probe=89938d9a3a) | Jul 20, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [c2721a852b](https://bsd-hardware.info/?probe=c2721a852b) | Jul 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Supermicro    | PDSML+                      | Desktop     | [f8a9ca42d6](https://bsd-hardware.info/?probe=f8a9ca42d6) | Jul 11, 2021 |
| PC Engines    | APU2                        | Desktop     | [fe77a10950](https://bsd-hardware.info/?probe=fe77a10950) | Jul 08, 2021 |
| Intel         | NUC7i7BNB J31145-302        | Mini pc     | [a54eaf1e7b](https://bsd-hardware.info/?probe=a54eaf1e7b) | Jun 28, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ae63f87748](https://bsd-hardware.info/?probe=ae63f87748) | Jun 22, 2021 |
| Protectli     | FW6                         | Desktop     | [c28479f624](https://bsd-hardware.info/?probe=c28479f624) | Jun 20, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6efb43e299](https://bsd-hardware.info/?probe=6efb43e299) | Jun 18, 2021 |
| Protectli     | FW6                         | Desktop     | [36d53d9465](https://bsd-hardware.info/?probe=36d53d9465) | Jun 17, 2021 |
| Sophos        | SG                          | Firewall    | [48b4a02fef](https://bsd-hardware.info/?probe=48b4a02fef) | Jun 17, 2021 |
| Protectli     | FW6                         | Desktop     | [9579e972f2](https://bsd-hardware.info/?probe=9579e972f2) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [15ba8e73e1](https://bsd-hardware.info/?probe=15ba8e73e1) | Jun 09, 2021 |
| PC Engines    | apu4                        | Desktop     | [7ffaed1505](https://bsd-hardware.info/?probe=7ffaed1505) | Jun 06, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | Notebook    | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [74f5dbcf1b](https://bsd-hardware.info/?probe=74f5dbcf1b) | Jun 01, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [67a6df2b68](https://bsd-hardware.info/?probe=67a6df2b68) | May 30, 2021 |
| PC Engines    | apu4                        | Desktop     | [aad3e6a309](https://bsd-hardware.info/?probe=aad3e6a309) | May 28, 2021 |
| Shuttle       | DS10U                       | Desktop     | [bd8bea4a6a](https://bsd-hardware.info/?probe=bd8bea4a6a) | May 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [1cdbad9dfe](https://bsd-hardware.info/?probe=1cdbad9dfe) | May 27, 2021 |
| Fujitsu       | D3383-B1 S26361-D3383-B1... | Server      | [6460f775b0](https://bsd-hardware.info/?probe=6460f775b0) | May 25, 2021 |
| Fujitsu       | D3383-B1 S26361-D3383-B1... | Server      | [10a74a9200](https://bsd-hardware.info/?probe=10a74a9200) | May 25, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [b8b40dbc2d](https://bsd-hardware.info/?probe=b8b40dbc2d) | May 20, 2021 |
| Dell          | Latitude E6430              | Notebook    | [8d24817728](https://bsd-hardware.info/?probe=8d24817728) | May 19, 2021 |
| ASUSTek       | P9D-I Series                | Server      | [fe8dc15588](https://bsd-hardware.info/?probe=fe8dc15588) | May 17, 2021 |
| Sophos        | SG                          | Firewall    | [8d2f78f042](https://bsd-hardware.info/?probe=8d2f78f042) | May 16, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [d4a2aebcf1](https://bsd-hardware.info/?probe=d4a2aebcf1) | May 12, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [ae3bb311de](https://bsd-hardware.info/?probe=ae3bb311de) | May 07, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [ef131c774d](https://bsd-hardware.info/?probe=ef131c774d) | May 02, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5020fdee8a](https://bsd-hardware.info/?probe=5020fdee8a) | May 01, 2021 |
| Lenovo        | 318E NOK                    | Desktop     | [115f2c7b35](https://bsd-hardware.info/?probe=115f2c7b35) | Apr 27, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [44e10ac014](https://bsd-hardware.info/?probe=44e10ac014) | Apr 19, 2021 |
| Sophos        | XG                          | Firewall    | [428b16a419](https://bsd-hardware.info/?probe=428b16a419) | Apr 14, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6f935f23d5](https://bsd-hardware.info/?probe=6f935f23d5) | Apr 11, 2021 |
| PC Engines    | APU2                        | Desktop     | [8b425e6086](https://bsd-hardware.info/?probe=8b425e6086) | Apr 08, 2021 |
| PC Engines    | apu2                        | Desktop     | [f261049b51](https://bsd-hardware.info/?probe=f261049b51) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [beacf76b6a](https://bsd-hardware.info/?probe=beacf76b6a) | Mar 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [09e3c55edf](https://bsd-hardware.info/?probe=09e3c55edf) | Mar 26, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f7e09652d9](https://bsd-hardware.info/?probe=f7e09652d9) | Mar 25, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f9fdc75b45](https://bsd-hardware.info/?probe=f9fdc75b45) | Mar 25, 2021 |
| PC Engines    | APU2                        | Desktop     | [6204024271](https://bsd-hardware.info/?probe=6204024271) | Mar 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [b39d8ba487](https://bsd-hardware.info/?probe=b39d8ba487) | Mar 24, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [40ec36ad78](https://bsd-hardware.info/?probe=40ec36ad78) | Mar 18, 2021 |
| PC Engines    | apu4                        | Desktop     | [e10b5c92e9](https://bsd-hardware.info/?probe=e10b5c92e9) | Mar 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [36f81afd88](https://bsd-hardware.info/?probe=36f81afd88) | Mar 13, 2021 |
| PC Engines    | apu4                        | Desktop     | [6d42054ec5](https://bsd-hardware.info/?probe=6d42054ec5) | Mar 13, 2021 |
| PC Engines    | apu4                        | Desktop     | [9268ee6857](https://bsd-hardware.info/?probe=9268ee6857) | Mar 13, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [acbc65fd42](https://bsd-hardware.info/?probe=acbc65fd42) | Mar 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2c0b0d8eb0](https://bsd-hardware.info/?probe=2c0b0d8eb0) | Mar 09, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [6d455b5e28](https://bsd-hardware.info/?probe=6d455b5e28) | Mar 08, 2021 |
| PC Engines    | APU3                        | Desktop     | [cf397191d2](https://bsd-hardware.info/?probe=cf397191d2) | Mar 04, 2021 |
| HP            | 0B54h D                     | Desktop     | [eb8428d5f3](https://bsd-hardware.info/?probe=eb8428d5f3) | Mar 01, 2021 |
| PC Engines    | apu2                        | Desktop     | [2ac1695054](https://bsd-hardware.info/?probe=2ac1695054) | Feb 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [b6c6031b46](https://bsd-hardware.info/?probe=b6c6031b46) | Feb 27, 2021 |
| Sophos        | SG                          | Firewall    | [c7392a1f0d](https://bsd-hardware.info/?probe=c7392a1f0d) | Feb 23, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Supermicro    | X10SDV-8C-TLN4F             | Server      | [636a269a2a](https://bsd-hardware.info/?probe=636a269a2a) | Feb 15, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [ad3998234a](https://bsd-hardware.info/?probe=ad3998234a) | Feb 11, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5a0b61ac41](https://bsd-hardware.info/?probe=5a0b61ac41) | Feb 07, 2021 |
| PC Engines    | apu2                        | Desktop     | [836a3035f1](https://bsd-hardware.info/?probe=836a3035f1) | Feb 06, 2021 |
| PC Engines    | apu2                        | Desktop     | [22b310774a](https://bsd-hardware.info/?probe=22b310774a) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| PC Engines    | apu2                        | Desktop     | [290957c97b](https://bsd-hardware.info/?probe=290957c97b) | Feb 04, 2021 |
| PC Engines    | apu2                        | Desktop     | [4985fa31bf](https://bsd-hardware.info/?probe=4985fa31bf) | Feb 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [c740c17c50](https://bsd-hardware.info/?probe=c740c17c50) | Feb 01, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [db0ed2b3c2](https://bsd-hardware.info/?probe=db0ed2b3c2) | Jan 31, 2021 |
| YANYU         | D19SL_B                     | Desktop     | [d16128eed9](https://bsd-hardware.info/?probe=d16128eed9) | Jan 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [d2895512c0](https://bsd-hardware.info/?probe=d2895512c0) | Jan 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [b936d5a273](https://bsd-hardware.info/?probe=b936d5a273) | Jan 27, 2021 |
| PC Engines    | apu2                        | Desktop     | [3448eacd29](https://bsd-hardware.info/?probe=3448eacd29) | Jan 24, 2021 |
| PC Engines    | apu2                        | Desktop     | [72e0243d73](https://bsd-hardware.info/?probe=72e0243d73) | Jan 23, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | Desktop     | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | apu2                        | Desktop     | [c6c764813a](https://bsd-hardware.info/?probe=c6c764813a) | Jan 21, 2021 |
| PC Engines    | apu2                        | Desktop     | [bf1b93e96d](https://bsd-hardware.info/?probe=bf1b93e96d) | Jan 21, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [cf9cb3dfcf](https://bsd-hardware.info/?probe=cf9cb3dfcf) | Jan 20, 2021 |
| ADI Engine... | RCC                         | Desktop     | [199da8eab6](https://bsd-hardware.info/?probe=199da8eab6) | Jan 20, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [3d1e915a1b](https://bsd-hardware.info/?probe=3d1e915a1b) | Jan 19, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [39f883b288](https://bsd-hardware.info/?probe=39f883b288) | Jan 19, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [9458fbeb87](https://bsd-hardware.info/?probe=9458fbeb87) | Jan 19, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [c107103d53](https://bsd-hardware.info/?probe=c107103d53) | Jan 19, 2021 |
| Sun           | SUNW,Sun-Blade-100          | Desktop     | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| HP            | 1495                        | Desktop     | [2606547041](https://bsd-hardware.info/?probe=2606547041) | Dec 22, 2020 |
| HP            | 0B54h D                     | Desktop     | [de35ebc178](https://bsd-hardware.info/?probe=de35ebc178) | Dec 04, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e44b010bc9](https://bsd-hardware.info/?probe=e44b010bc9) | Nov 11, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [2fb1bc911f](https://bsd-hardware.info/?probe=2fb1bc911f) | Nov 11, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| PC Engines    | apu2                        | Desktop     | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| PC Engines    | apu4                        | Desktop     | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [94a279c84d](https://bsd-hardware.info/?probe=94a279c84d) | Sep 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [2dd2bb5d60](https://bsd-hardware.info/?probe=2dd2bb5d60) | Aug 20, 2020 |
| Dell          | Precision M6600             | Notebook    | [b6c974b8bd](https://bsd-hardware.info/?probe=b6c974b8bd) | Aug 19, 2020 |
| HP            | 0B54h D                     | Desktop     | [840b12f1f9](https://bsd-hardware.info/?probe=840b12f1f9) | Aug 09, 2020 |
| HP            | 0B54h D                     | Desktop     | [c4454eaa39](https://bsd-hardware.info/?probe=c4454eaa39) | Aug 09, 2020 |
| Dell          | Precision M6600             | Notebook    | [da6f06315a](https://bsd-hardware.info/?probe=da6f06315a) | Aug 06, 2020 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [455ba9f0a8](https://bsd-hardware.info/?probe=455ba9f0a8) | Jul 20, 2020 |
| PC Engines    | apu4                        | Desktop     | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| HP            | 158A                        | Desktop     | [dfff5dd2f9](https://bsd-hardware.info/?probe=dfff5dd2f9) | Jun 09, 2020 |
| Panasonic     | CF-19ADUAX1M                | Notebook    | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [d65f5372ec](https://bsd-hardware.info/?probe=d65f5372ec) | May 26, 2020 |
| HP            | 0B54h D                     | Desktop     | [b43db1d84e](https://bsd-hardware.info/?probe=b43db1d84e) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| OPNsense 21.7.1         | 8         | 4.68%   |
| OPNsense 20.7.8         | 8         | 4.68%   |
| OPNsense 21.7.3         | 7         | 4.09%   |
| OPNsense 21.1.6         | 7         | 4.09%   |
| OPNsense 21.1           | 6         | 3.51%   |
| OPNsense 21.7.7         | 5         | 2.92%   |
| OPNsense 21.7.6         | 5         | 2.92%   |
| OPNsense 21.1.5         | 5         | 2.92%   |
| OpenBSD 6.8             | 5         | 2.92%   |
| FreeBSD 13.0-p7         | 5         | 2.92%   |
| OPNsense 22.1.6         | 4         | 2.34%   |
| OPNsense 22.1.3         | 4         | 2.34%   |
| OPNsense 22.1.1         | 4         | 2.34%   |
| OPNsense 22.1           | 4         | 2.34%   |
| OPNsense 21.1.3         | 4         | 2.34%   |
| OPNsense 21.1.2         | 4         | 2.34%   |
| GhostBSD 20.04.02       | 4         | 2.34%   |
| FreeBSD 13.0            | 4         | 2.34%   |
| OPNsense 22.1.7         | 3         | 1.75%   |
| OPNsense 22.1.4         | 3         | 1.75%   |
| OPNsense 21.7.4         | 3         | 1.75%   |
| OPNsense 21.7           | 3         | 1.75%   |
| OPNsense 21.1.8         | 3         | 1.75%   |
| OPNsense 21.1.7         | 3         | 1.75%   |
| OPNsense 21.1.4         | 3         | 1.75%   |
| OpenBSD 7.0             | 3         | 1.75%   |
| OpenBSD 6.7             | 3         | 1.75%   |
| helloSystem 0.5.0       | 3         | 1.75%   |
| FreeBSD 12.1-p8         | 3         | 1.75%   |
| OPNsense 22.1.5         | 2         | 1.17%   |
| OPNsense 22.1.2         | 2         | 1.17%   |
| OPNsense 21.7.5         | 2         | 1.17%   |
| OPNsense 21.1.9         | 2         | 1.17%   |
| FreeBSD 14.0-CURRENT    | 2         | 1.17%   |
| FreeBSD 13.0-STABLE     | 2         | 1.17%   |
| FreeBSD 13.0-p5         | 2         | 1.17%   |
| FreeBSD 12.2-p4         | 2         | 1.17%   |
| FreeBSD 12.2-p2         | 2         | 1.17%   |
| FreeBSD 12.2            | 2         | 1.17%   |
| FreeBSD 12.1-STABLE     | 2         | 1.17%   |
| FreeBSD 12.1-p5         | 2         | 1.17%   |
| FreeBSD 12.1            | 2         | 1.17%   |
| FreeBSD 11.4-p9         | 2         | 1.17%   |
| TrueNAS 12.2-p6         | 1         | 0.58%   |
| TrueNAS 12.2-p12        | 1         | 0.58%   |
| OPNsense 22.1.8         | 1         | 0.58%   |
| OPNsense 21.1.1         | 1         | 0.58%   |
| OPNsense 20.7.5         | 1         | 0.58%   |
| OpenBSD 6.9             | 1         | 0.58%   |
| helloSystem 0.6.0       | 1         | 0.58%   |
| helloSystem 0.4.0       | 1         | 0.58%   |
| GhostBSD 21.08.27       | 1         | 0.58%   |
| FreeBSD 13.1-STABLE     | 1         | 0.58%   |
| FreeBSD 13.1-PRERELEASE | 1         | 0.58%   |
| FreeBSD 13.0-p6         | 1         | 0.58%   |
| FreeBSD 13.0-p2         | 1         | 0.58%   |
| FreeBSD 13.0-p1         | 1         | 0.58%   |
| FreeBSD 12.2-STABLE     | 1         | 0.58%   |
| FreeBSD 12.2-p1         | 1         | 0.58%   |
| FreeBSD 12.1-p22-HBSD   | 1         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 79        | 58.52%  |
| FreeBSD     | 32        | 23.7%   |
| OpenBSD     | 12        | 8.89%   |
| helloSystem | 5         | 3.7%    |
| GhostBSD    | 5         | 3.7%    |
| TrueNAS     | 2         | 1.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 130       | 96.3%   |
| sparc64 | 2         | 1.48%   |
| arm64   | 2         | 1.48%   |
| i386    | 1         | 0.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 101       | 73.72%  |
| KDE5         | 8         | 5.84%   |
| MATE         | 5         | 3.65%   |
| helloDesktop | 5         | 3.65%   |
| fvwm         | 5         | 3.65%   |
| i3           | 4         | 2.92%   |
| XFCE         | 3         | 2.19%   |
| TWM          | 2         | 1.46%   |
| LXQt         | 1         | 0.73%   |
| LXDE         | 1         | 0.73%   |
| GNOME        | 1         | 0.73%   |
| CDE          | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 103       | 75.74%  |
| X11     | 33        | 24.26%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 113       | 83.09%  |
| SLiM    | 11        | 8.09%   |
| LightDM | 7         | 5.15%   |
| SDDM    | 2         | 1.47%   |
| GDM     | 2         | 1.47%   |
| XDM     | 1         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 99        | 72.79%  |
| en_US   | 17        | 12.5%   |
| C       | 15        | 11.03%  |
| de_CH   | 3         | 2.21%   |
| de_DE   | 2         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 114       | 84.44%  |
| BIOS | 21        | 15.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 76        | 55.47%  |
| Zfs  | 49        | 35.77%  |
| Ffs  | 12        | 8.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 121       | 89.63%  |
| MBR     | 13        | 9.63%   |
| Unknown | 1         | 0.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| PC Engines              | 28        | 20.74%  |
| Lenovo                  | 14        | 10.37%  |
| ASUSTek Computer        | 9         | 6.67%   |
| Unknown                 | 9         | 6.67%   |
| Hewlett-Packard         | 8         | 5.93%   |
| Supermicro              | 7         | 5.19%   |
| Gigabyte Technology     | 6         | 4.44%   |
| Dell                    | 6         | 4.44%   |
| ASRock                  | 6         | 4.44%   |
| Sophos                  | 5         | 3.7%    |
| Intel                   | 5         | 3.7%    |
| Shuttle                 | 3         | 2.22%   |
| Protectli               | 3         | 2.22%   |
| Apple                   | 3         | 2.22%   |
| Sun                     | 2         | 1.48%   |
| HUAWEI                  | 2         | 1.48%   |
| Fujitsu                 | 2         | 1.48%   |
| Deciso                  | 2         | 1.48%   |
| BESSTAR Tech            | 2         | 1.48%   |
| ASRockRack              | 2         | 1.48%   |
| Acer                    | 2         | 1.48%   |
| ZOTAC                   | 1         | 0.74%   |
| YANYU                   | 1         | 0.74%   |
| Raspberry Pi Foundation | 1         | 0.74%   |
| Panasonic               | 1         | 0.74%   |
| HPE                     | 1         | 0.74%   |
| Compulab                | 1         | 0.74%   |
| Casper                  | 1         | 0.74%   |
| Biostar                 | 1         | 0.74%   |
| ADI Engineering         | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| PC Engines APU2                            | 15        | 11.11%  |
| PC Engines apu4                            | 11        | 8.15%   |
| Unknown                                    | 9         | 6.67%   |
| Sophos SG                                  | 3         | 2.22%   |
| Protectli FW6                              | 3         | 2.22%   |
| ASRock A320M-ITX                           | 3         | 2.22%   |
| Supermicro Super Server                    | 2         | 1.48%   |
| Shuttle DS10U                              | 2         | 1.48%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS         | 2         | 1.48%   |
| HUAWEI MACH-WX9                            | 2         | 1.48%   |
| Fujitsu PRIMERGY RX2530 M5                 | 2         | 1.48%   |
| Dell Precision 3440                        | 2         | 1.48%   |
| ZOTAC ZBOX-CI327NANO-GS-01                 | 1         | 0.74%   |
| YANYU D19SL_B                              | 1         | 0.74%   |
| Supermicro X9SCL/X9SCM                     | 1         | 0.74%   |
| Supermicro X10SLL-F                        | 1         | 0.74%   |
| Supermicro SYS-1019D-4C-FHN13TP            | 1         | 0.74%   |
| Supermicro PDSML                           | 1         | 0.74%   |
| Supermicro A1SAi                           | 1         | 0.74%   |
| Sun SUNW,Sun-Blade-1500                    | 1         | 0.74%   |
| Sun SUNW,Sun-Blade-100                     | 1         | 0.74%   |
| Sophos XG                                  | 1         | 0.74%   |
| Sophos UTM                                 | 1         | 0.74%   |
| Shuttle DS77U                              | 1         | 0.74%   |
| RPi Raspberry Pi                           | 1         | 0.74%   |
| PC Engines apu6                            | 1         | 0.74%   |
| PC Engines APU3                            | 1         | 0.74%   |
| Panasonic CF-19ADUAX1M                     | 1         | 0.74%   |
| Lenovo Yoga 720-13IKB 81C3                 | 1         | 0.74%   |
| Lenovo ThinkPad X250 20CMCTO1WW            | 1         | 0.74%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 0.74%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.74%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS09900   | 1         | 0.74%   |
| Lenovo ThinkPad T490s 20NYS3TU00           | 1         | 0.74%   |
| Lenovo ThinkPad T490 20N2CTO1WW            | 1         | 0.74%   |
| Lenovo ThinkPad T470s W10DG 20JTS0A900     | 1         | 0.74%   |
| Lenovo ThinkPad T430 2349H2G               | 1         | 0.74%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.74%   |
| Lenovo ThinkCentre M75t Gen 2 11KECTO1WW   | 1         | 0.74%   |
| Lenovo IdeaPad Y700-15ISK 80NV             | 1         | 0.74%   |
| Intel Q3XXG4-P V1.0                        | 1         | 0.74%   |
| Intel NUC8i5BEH                            | 1         | 0.74%   |
| Intel NUC7i7BNB J31145-302                 | 1         | 0.74%   |
| Intel HURONRIVER                           | 1         | 0.74%   |
| Intel D54250WYK H13922-303                 | 1         | 0.74%   |
| HPE ProLiant MicroServer Gen10             | 1         | 0.74%   |
| HP Z620 Workstation                        | 1         | 0.74%   |
| HP Z600 Workstation                        | 1         | 0.74%   |
| HP ProLiant ML350p Gen8                    | 1         | 0.74%   |
| HP ProLiant MicroServer Gen8               | 1         | 0.74%   |
| HP EliteBook 840 G3                        | 1         | 0.74%   |
| HP Compaq Elite 8300 SFF                   | 1         | 0.74%   |
| HP Compaq Elite 8300 CMT                   | 1         | 0.74%   |
| HP Compaq 8200 Elite SFF PC                | 1         | 0.74%   |
| Gigabyte X399 DESIGNARE EX                 | 1         | 0.74%   |
| Gigabyte H97N-WIFI                         | 1         | 0.74%   |
| Gigabyte H67A-UD3H-B3                      | 1         | 0.74%   |
| Gigabyte BRi3(H)-10110                     | 1         | 0.74%   |
| Gigabyte B450M DS3H                        | 1         | 0.74%   |
| Gigabyte 990FXA-UD3                        | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| PC Engines APU2                 | 15        | 11.11%  |
| PC Engines apu4                 | 11        | 8.15%   |
| Lenovo ThinkPad                 | 9         | 6.67%   |
| Unknown                         | 9         | 6.67%   |
| Sophos SG                       | 3         | 2.22%   |
| Protectli FW6                   | 3         | 2.22%   |
| Lenovo Yoga                     | 3         | 2.22%   |
| HP Compaq                       | 3         | 2.22%   |
| Dell Precision                  | 3         | 2.22%   |
| ASRock A320M-ITX                | 3         | 2.22%   |
| Supermicro Super                | 2         | 1.48%   |
| Sun SUNW                        | 2         | 1.48%   |
| Shuttle DS10U                   | 2         | 1.48%   |
| HUAWEI MACH-WX9                 | 2         | 1.48%   |
| HP ProLiant                     | 2         | 1.48%   |
| Fujitsu PRIMERGY                | 2         | 1.48%   |
| Acer Aspire                     | 2         | 1.48%   |
| ZOTAC ZBOX-CI327NANO-GS-01      | 1         | 0.74%   |
| YANYU D19SL                     | 1         | 0.74%   |
| Supermicro X9SCL                | 1         | 0.74%   |
| Supermicro X10SLL-F             | 1         | 0.74%   |
| Supermicro SYS-1019D-4C-FHN13TP | 1         | 0.74%   |
| Supermicro PDSML                | 1         | 0.74%   |
| Supermicro A1SAi                | 1         | 0.74%   |
| Sophos XG                       | 1         | 0.74%   |
| Sophos UTM                      | 1         | 0.74%   |
| Shuttle DS77U                   | 1         | 0.74%   |
| RPi Raspberry                   | 1         | 0.74%   |
| PC Engines apu6                 | 1         | 0.74%   |
| PC Engines APU3                 | 1         | 0.74%   |
| Panasonic CF-19ADUAX1M          | 1         | 0.74%   |
| Lenovo ThinkCentre              | 1         | 0.74%   |
| Lenovo IdeaPad                  | 1         | 0.74%   |
| Intel Q3XXG4-P                  | 1         | 0.74%   |
| Intel NUC8i5BEH                 | 1         | 0.74%   |
| Intel NUC7i7BNB                 | 1         | 0.74%   |
| Intel HURONRIVER                | 1         | 0.74%   |
| Intel D54250WYK                 | 1         | 0.74%   |
| HPE ProLiant                    | 1         | 0.74%   |
| HP Z620                         | 1         | 0.74%   |
| HP Z600                         | 1         | 0.74%   |
| HP EliteBook                    | 1         | 0.74%   |
| Gigabyte X399                   | 1         | 0.74%   |
| Gigabyte H97N-WIFI              | 1         | 0.74%   |
| Gigabyte H67A-UD3H-B3           | 1         | 0.74%   |
| Gigabyte BRi3(H)-10110          | 1         | 0.74%   |
| Gigabyte B450M                  | 1         | 0.74%   |
| Gigabyte 990FXA-UD3             | 1         | 0.74%   |
| Dell XPS420                     | 1         | 0.74%   |
| Dell XPS                        | 1         | 0.74%   |
| Dell Latitude                   | 1         | 0.74%   |
| Deciso Netboard                 | 1         | 0.74%   |
| Deciso DEC2700                  | 1         | 0.74%   |
| Compulab fitlet2                | 1         | 0.74%   |
| Casper EXCALIBUR                | 1         | 0.74%   |
| Biostar H61MHV2                 | 1         | 0.74%   |
| BESSTAR Tech X35G               | 1         | 0.74%   |
| BESSTAR Tech GK41               | 1         | 0.74%   |
| ASUS Z170-K                     | 1         | 0.74%   |
| ASUS UX31A                      | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 26        | 19.26%  |
| 2020    | 20        | 14.81%  |
| 2016    | 20        | 14.81%  |
| 2021    | 13        | 9.63%   |
| 2017    | 10        | 7.41%   |
| 2013    | 8         | 5.93%   |
| 2015    | 7         | 5.19%   |
| 2019    | 6         | 4.44%   |
| 2012    | 6         | 4.44%   |
| 2011    | 5         | 3.7%    |
| Unknown | 5         | 3.7%    |
| 2014    | 4         | 2.96%   |
| 2008    | 2         | 1.48%   |
| 2022    | 1         | 0.74%   |
| 2009    | 1         | 0.74%   |
| 2007    | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 87        | 64.44%  |
| Notebook       | 27        | 20%     |
| Mini pc        | 7         | 5.19%   |
| Server         | 6         | 4.44%   |
| Firewall       | 5         | 3.7%    |
| System on chip | 2         | 1.48%   |
| Convertible    | 1         | 0.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 76.3%   |
| Yes  | 32        | 23.7%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 42        | 30.88%  |
| 4.01-8.0    | 34        | 25%     |
| 8.01-16.0   | 33        | 24.26%  |
| 32.01-64.0  | 13        | 9.56%   |
| 64.01-256.0 | 5         | 3.68%   |
| 2.01-3.0    | 3         | 2.21%   |
| 0.51-1.0    | 2         | 1.47%   |
| 3.01-4.0    | 1         | 0.74%   |
| 1.01-2.0    | 1         | 0.74%   |
| 0.01-0.5    | 1         | 0.74%   |
| Unknown     | 1         | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 62        | 43.97%  |
| 0.51-1.0    | 44        | 31.21%  |
| 1.01-2.0    | 13        | 9.22%   |
| 2.01-3.0    | 9         | 6.38%   |
| 4.01-8.0    | 3         | 2.13%   |
| 0           | 3         | 2.13%   |
| 3.01-4.0    | 2         | 1.42%   |
| 8.01-16.0   | 2         | 1.42%   |
| 64.01-256.0 | 1         | 0.71%   |
| 16.01-24.0  | 1         | 0.71%   |
| Unknown     | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 69.85%  |
| 2      | 15        | 11.03%  |
| 0      | 15        | 11.03%  |
| 4      | 4         | 2.94%   |
| 6      | 3         | 2.21%   |
| 3      | 2         | 1.47%   |
| 17     | 1         | 0.74%   |
| 16     | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 85.19%  |
| Yes       | 20        | 14.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 91.85%  |
| No        | 11        | 8.15%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 67.41%  |
| Yes       | 44        | 32.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 74.07%  |
| Yes       | 35        | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 135       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Zurich                 | 42        | 27.1%   |
| Gachnang               | 6         | 3.87%   |
| Gordola                | 5         | 3.23%   |
| St. Moritz             | 4         | 2.58%   |
| Winterthur             | 3         | 1.94%   |
| Lenzburg               | 3         | 1.94%   |
| Lausanne               | 3         | 1.94%   |
| Basel                  | 3         | 1.94%   |
| Wallisellen            | 2         | 1.29%   |
| Therwil                | 2         | 1.29%   |
| Riehen                 | 2         | 1.29%   |
| Ottenbach              | 2         | 1.29%   |
| Oensingen              | 2         | 1.29%   |
| Munchenstein           | 2         | 1.29%   |
| Mettmenstetten         | 2         | 1.29%   |
| Lucerne                | 2         | 1.29%   |
| Geneva                 | 2         | 1.29%   |
| Eiken                  | 2         | 1.29%   |
| Dinhard                | 2         | 1.29%   |
| Corcelles-pres-Payerne | 2         | 1.29%   |
| Buchs                  | 2         | 1.29%   |
| Zufikon                | 1         | 0.65%   |
| Yverdon-les-Bains      | 1         | 0.65%   |
| Yens                   | 1         | 0.65%   |
| Worblaufen             | 1         | 0.65%   |
| Willisau               | 1         | 0.65%   |
| Wetzikon               | 1         | 0.65%   |
| Wettswil               | 1         | 0.65%   |
| Welschenrohr           | 1         | 0.65%   |
| Uster                  | 1         | 0.65%   |
| Trogen                 | 1         | 0.65%   |
| Suhr                   | 1         | 0.65%   |
| Steckborn              | 1         | 0.65%   |
| St. Gallen             | 1         | 0.65%   |
| Sitterdorf             | 1         | 0.65%   |
| Rumlang                | 1         | 0.65%   |
| Root                   | 1         | 0.65%   |
| Romanens               | 1         | 0.65%   |
| Riviera                | 1         | 0.65%   |
| Rickenbach bei Wil     | 1         | 0.65%   |
| Richterswil            | 1         | 0.65%   |
| Renens                 | 1         | 0.65%   |
| Pfaeffikon             | 1         | 0.65%   |
| Opfikon                | 1         | 0.65%   |
| Onex                   | 1         | 0.65%   |
| Oftringen              | 1         | 0.65%   |
| Oetwil am See          | 1         | 0.65%   |
| Niederbipp             | 1         | 0.65%   |
| Nidau                  | 1         | 0.65%   |
| Neuenegg               | 1         | 0.65%   |
| Naters                 | 1         | 0.65%   |
| Moosseedorf            | 1         | 0.65%   |
| Mendrisio              | 1         | 0.65%   |
| Mellingen              | 1         | 0.65%   |
| Lupfig                 | 1         | 0.65%   |
| Lohnstorf              | 1         | 0.65%   |
| Liestal                | 1         | 0.65%   |
| Langnau am Albis       | 1         | 0.65%   |
| La Tour-de-Peilz       | 1         | 0.65%   |
| Jona                   | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 52     | 23.4%   |
| WDC                 | 19        | 27     | 13.48%  |
| Phison              | 13        | 16     | 9.22%   |
| Kingston            | 11        | 11     | 7.8%    |
| Seagate             | 9         | 11     | 6.38%   |
| Intel               | 7         | 22     | 4.96%   |
| Crucial             | 6         | 12     | 4.26%   |
| Hoodisk             | 5         | 6      | 3.55%   |
| Toshiba             | 4         | 5      | 2.84%   |
| SanDisk             | 4         | 6      | 2.84%   |
| Transcend           | 3         | 3      | 2.13%   |
| HPT                 | 3         | 35     | 2.13%   |
| Corsair             | 3         | 5      | 2.13%   |
| NVMe                | 2         | 2      | 1.42%   |
| Hitachi             | 2         | 2      | 1.42%   |
| FTS                 | 2         | 2      | 1.42%   |
| China               | 2         | 3      | 1.42%   |
| SPCC                | 1         | 2      | 0.71%   |
| ShiJi               | 1         | 1      | 0.71%   |
| OPENBSD             | 1         | 1      | 0.71%   |
| Micron Technology   | 1         | 2      | 0.71%   |
| LITEON              | 1         | 9      | 0.71%   |
| KIOXIA              | 1         | 1      | 0.71%   |
| KingSpec            | 1         | 1      | 0.71%   |
| Hewlett-Packard     | 1         | 5      | 0.71%   |
| Gigabyte Technology | 1         | 1      | 0.71%   |
| FORESEE             | 1         | 1      | 0.71%   |
| BIWIN               | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |
| A-DATA Technology   | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Phison SATA SSD 16GB                 | 10        | 5.56%   |
| Samsung SSD 860 EVO 250GB            | 5         | 2.78%   |
| Hoodisk SSD 32GB                     | 5         | 2.78%   |
| Samsung SSD 860 PRO 256GB            | 3         | 1.67%   |
| Phison SATA SSD 32GB                 | 3         | 1.67%   |
| Kingston RBUSNS8180DS3128GH 128GB    | 3         | 1.67%   |
| HPT DISK 0_3 3TB                     | 3         | 1.67%   |
| HPT DISK 0_2 3TB                     | 3         | 1.67%   |
| HPT DISK 0_1 6TB                     | 3         | 1.67%   |
| HPT DISK 0_0 4TB                     | 3         | 1.67%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.11%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 2         | 1.11%   |
| WDC WD6002FRYZ-01WD5B1 6TB           | 2         | 1.11%   |
| Samsung SSD 960 EVO 250GB            | 2         | 1.11%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.11%   |
| Samsung MZVLB512HAJQ-00000 512GB     | 2         | 1.11%   |
| Kingston SA400S37120G 120GB          | 2         | 1.11%   |
| HPT DISK 0_9 3TB                     | 2         | 1.11%   |
| HPT DISK 0_8 3TB                     | 2         | 1.11%   |
| HPT DISK 0_7 3TB                     | 2         | 1.11%   |
| HPT DISK 0_6 3TB                     | 2         | 1.11%   |
| HPT DISK 0_5 18TB                    | 2         | 1.11%   |
| HPT DISK 0_4 18TB                    | 2         | 1.11%   |
| HPT DISK 0_14 3TB                    | 2         | 1.11%   |
| HPT DISK 0_13 2TB                    | 2         | 1.11%   |
| HPT DISK 0_12 1TB                    | 2         | 1.11%   |
| HPT DISK 0_11 1TB                    | 2         | 1.11%   |
| HPT DISK 0_10 1TB                    | 2         | 1.11%   |
| Hitachi HDS721050CLA360 500GB        | 2         | 1.11%   |
| FTS PRAID EP580i 2.8TB               | 2         | 1.11%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.11%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.56%   |
| WDC WD5000BEKT-00KA9T0 500GB         | 1         | 0.56%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.56%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.56%   |
| WDC WD2503ABYX-01WERA1 256GB         | 1         | 0.56%   |
| WDC WD2002FYPS-01U1B0 2TB            | 1         | 0.56%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.56%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.56%   |
| WDC WD10EALX-009BA0 1TB              | 1         | 0.56%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.56%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.56%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.56%   |
| Transcend TS64GMSA230S 64GB          | 1         | 0.56%   |
| Transcend TS256GMTS952T2 256GB       | 1         | 0.56%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 0.56%   |
| Toshiba TR200 240GB                  | 1         | 0.56%   |
| Toshiba THNSFJ256GCSU 256GB          | 1         | 0.56%   |
| Toshiba MQ03UBB300 3TB               | 1         | 0.56%   |
| Toshiba MK1059GSM 1TB                | 1         | 0.56%   |
| Toshiba DT01ACA200 2TB               | 1         | 0.56%   |
| SPCC Solid State Disk 256GB          | 1         | 0.56%   |
| ShiJi SSD 128GB                      | 1         | 0.56%   |
| Seagate ST9250410AS 250GB            | 1         | 0.56%   |
| Seagate ST5000DM000-1FK178 5TB       | 1         | 0.56%   |
| Seagate ST3500413AS 500GB            | 1         | 0.56%   |
| Seagate ST3320820A 320GB             | 1         | 0.56%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 9         | 15     | 29.03%  |
| Seagate         | 9         | 11     | 29.03%  |
| HPT             | 3         | 35     | 9.68%   |
| Toshiba         | 2         | 3      | 6.45%   |
| NVMe            | 2         | 2      | 6.45%   |
| Hitachi         | 2         | 2      | 6.45%   |
| OPENBSD         | 1         | 1      | 3.23%   |
| Hewlett-Packard | 1         | 5      | 3.23%   |
| China           | 1         | 1      | 3.23%   |
| Apple           | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 39     | 25.27%  |
| Phison              | 13        | 16     | 14.29%  |
| Kingston            | 11        | 11     | 12.09%  |
| WDC                 | 6         | 8      | 6.59%   |
| Intel               | 6         | 21     | 6.59%   |
| Hoodisk             | 5         | 6      | 5.49%   |
| Crucial             | 5         | 11     | 5.49%   |
| SanDisk             | 4         | 6      | 4.4%    |
| Corsair             | 3         | 5      | 3.3%    |
| Transcend           | 2         | 2      | 2.2%    |
| Toshiba             | 2         | 2      | 2.2%    |
| FTS                 | 2         | 2      | 2.2%    |
| SPCC                | 1         | 2      | 1.1%    |
| ShiJi               | 1         | 1      | 1.1%    |
| Micron Technology   | 1         | 2      | 1.1%    |
| LITEON              | 1         | 9      | 1.1%    |
| KingSpec            | 1         | 1      | 1.1%    |
| FORESEE             | 1         | 1      | 1.1%    |
| China               | 1         | 2      | 1.1%    |
| BIWIN               | 1         | 1      | 1.1%    |
| A-DATA Technology   | 1         | 1      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 89        | 149    | 66.42%  |
| HDD  | 24        | 76     | 17.91%  |
| NVMe | 21        | 22     | 15.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 225    | 82.93%  |
| NVMe | 21        | 22     | 17.07%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 93        | 150    | 69.92%  |
| 0.51-1.0   | 15        | 29     | 11.28%  |
| 2.01-3.0   | 7         | 21     | 5.26%   |
| 1.01-2.0   | 6         | 7      | 4.51%   |
| 4.01-10.0  | 6         | 10     | 4.51%   |
| 3.01-4.0   | 4         | 4      | 3.01%   |
| 10.01-20.0 | 2         | 4      | 1.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 59        | 43.07%  |
| 1-20       | 23        | 16.79%  |
| 51-100     | 16        | 11.68%  |
| 21-50      | 14        | 10.22%  |
| 251-500    | 13        | 9.49%   |
| 501-1000   | 11        | 8.03%   |
| 1001-2000  | 1         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 125       | 88.65%  |
| 21-50   | 9         | 6.38%   |
| 51-100  | 5         | 3.55%   |
| 251-500 | 1         | 0.71%   |
| 101-250 | 1         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB | 1         | 1      | 9.09%   |
| WDC WD6002FRYZ-01WD5B1 6TB   | 1         | 5      | 9.09%   |
| WDC WD40EFRX-68WT0N0 4TB     | 1         | 1      | 9.09%   |
| WDC WD2002FYPS-01U1B0 2TB    | 1         | 1      | 9.09%   |
| Toshiba MK1059GSM 1TB        | 1         | 1      | 9.09%   |
| Seagate ST3500413AS 500GB    | 1         | 1      | 9.09%   |
| Kingston SV300S37A120G 120GB | 1         | 1      | 9.09%   |
| Intel SSDSCKKF256G8H 256GB   | 1         | 2      | 9.09%   |
| Intel SSDSC2BW240A4 240GB    | 1         | 1      | 9.09%   |
| Intel SSDSA2BW160G3H 160GB   | 1         | 5      | 9.09%   |
| Corsair Force 3 SSD 120GB    | 1         | 2      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 3         | 8      | 30%     |
| Intel    | 3         | 8      | 30%     |
| Toshiba  | 1         | 1      | 10%     |
| Seagate  | 1         | 1      | 10%     |
| Kingston | 1         | 1      | 10%     |
| Corsair  | 1         | 2      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 7      | 50%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 12     | 66.67%  |
| HDD  | 3         | 9      | 33.33%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 110       | 180    | 86.61%  |
| Detected | 9         | 46     | 7.09%   |
| Malfunc  | 8         | 21     | 6.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 75        | 48.7%   |
| AMD                       | 42        | 27.27%  |
| Samsung Electronics       | 14        | 9.09%   |
| Sandisk                   | 5         | 3.25%   |
| HighPoint Technologies    | 3         | 1.95%   |
| ASMedia Technology        | 3         | 1.95%   |
| ULi Electronics           | 2         | 1.3%    |
| Marvell Technology Group  | 2         | 1.3%    |
| KIOXIA                    | 2         | 1.3%    |
| Broadcom / LSI            | 2         | 1.3%    |
| Phison Electronics        | 1         | 0.65%   |
| Micron/Crucial Technology | 1         | 0.65%   |
| Hewlett-Packard           | 1         | 0.65%   |
| Unknown                   | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 16.48%  |
| AMD FCH SATA Controller [IDE mode]                                             | 9         | 5.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 3.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 2.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.7%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 3         | 1.7%    |
| Intel Atom Processor C3000 Series SATA Controller 1                            | 3         | 1.7%    |
| Intel Atom Processor C3000 Series SATA Controller 0                            | 3         | 1.7%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 3         | 1.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.7%    |
| AMD FCH SATA Controller D                                                      | 3         | 1.7%    |
| ULi M5229 IDE                                                                  | 2         | 1.14%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.14%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 2         | 1.14%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 2         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.14%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 2         | 1.14%   |
| Broadcom / LSI MegaRAID Tri-Mode SAS3516                                       | 2         | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.14%   |
| Unknown                                                                        | 2         | 1.14%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.57%   |
| Sandisk WD Black NVMe SSD                                                      | 1         | 0.57%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.57%   |
| Samsung SM951 AHCI                                                             | 1         | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.57%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1         | 0.57%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 0.57%   |
| KIOXIA unknown                                                                 | 1         | 0.57%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.57%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.57%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.57%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 0.57%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 0.57%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1         | 0.57%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1         | 0.57%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 1         | 0.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 0.57%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 0.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 1         | 0.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 101       | 65.16%  |
| NVMe | 24        | 15.48%  |
| IDE  | 18        | 11.61%  |
| RAID | 10        | 6.45%   |
| SAS  | 1         | 0.65%   |
| SCSI | 1         | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 86        | 63.7%   |
| AMD     | 45        | 33.33%  |
| ARM     | 2         | 1.48%   |
| Unknown | 2         | 1.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                            | 28        | 20.74%  |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 2.22%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 3         | 2.22%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 2.22%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz        | 2         | 1.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.48%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 1.48%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 2         | 1.48%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 2         | 1.48%   |
| Intel Atom CPU C2558 @ 2.40GHz              | 2         | 1.48%   |
| ARM Cortex-A53 r0p4                         | 2         | 1.48%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 1.48%   |
|                                             | 2         | 1.48%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 1         | 0.74%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.74%   |
| Intel Xeon CPU E5630 @ 2.53GHz              | 1         | 0.74%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1         | 0.74%   |
| Intel Xeon CPU E5-2620 @ 2.00GHz            | 1         | 0.74%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1         | 0.74%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1         | 0.74%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.74%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz        | 1         | 0.74%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1         | 0.74%   |
| Intel Xeon CPU E                            | 1         | 0.74%   |
| Intel Xeon CPU D-1540 @ 2.00GHz             | 1         | 0.74%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1         | 0.74%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.74%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.74%   |
| Intel Core i7-7567U CPU @ 3.50GHz           | 1         | 0.74%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.74%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.74%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.74%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.74%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.74%   |
| Intel Core i7-2720QM CPU @ 2.20GH           | 1         | 0.74%   |
| Intel Core i7-2600K CPU                     | 1         | 0.74%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.74%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 0.74%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.74%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1         | 0.74%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 0.74%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1         | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.74%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 0.74%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.74%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 0.74%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 0.74%   |
| Intel Core i3-8350K CPU @ 4.00GHz           | 1         | 0.74%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 0.74%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| AMD GX                 | 28        | 20.74%  |
| Intel Core i5          | 21        | 15.56%  |
| Intel Core i7          | 19        | 14.07%  |
| Intel Xeon             | 12        | 8.89%   |
| Intel Celeron          | 10        | 7.41%   |
| Intel Core i3          | 8         | 5.93%   |
| Intel Atom             | 7         | 5.19%   |
| Other                  | 5         | 3.7%    |
| AMD Ryzen 7            | 4         | 2.96%   |
| AMD Ryzen 5            | 4         | 2.96%   |
| Intel Core 2 Duo       | 3         | 2.22%   |
| Intel Xeon Silver      | 2         | 1.48%   |
| ARM Cortex             | 2         | 1.48%   |
| AMD Ryzen 3            | 2         | 1.48%   |
| Intel Pentium          | 1         | 0.74%   |
| AMD Ryzen Threadripper | 1         | 0.74%   |
| AMD Ryzen Embedded     | 1         | 0.74%   |
| AMD Ryzen 7 PRO        | 1         | 0.74%   |
| AMD Opteron            | 1         | 0.74%   |
| AMD Geode Integrated   | 1         | 0.74%   |
| AMD FX                 | 1         | 0.74%   |
| AMD EPYC               | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 71        | 52.59%  |
| 2       | 30        | 22.22%  |
| 8       | 12        | 8.89%   |
| 16      | 5         | 3.7%    |
| 6       | 4         | 2.96%   |
| Unknown | 4         | 2.96%   |
| 1       | 3         | 2.22%   |
| 20      | 2         | 1.48%   |
| 12      | 2         | 1.48%   |
| 32      | 1         | 0.74%   |
| 10      | 1         | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 126       | 93.33%  |
| 2       | 4         | 2.96%   |
| Unknown | 4         | 2.96%   |
| 4       | 1         | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 74        | 54.81%  |
| 2       | 55        | 40.74%  |
| Unknown | 6         | 4.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Puma          | 28        | 20.74%  |
| KabyLake      | 21        | 15.56%  |
| IvyBridge     | 11        | 8.15%   |
| Haswell       | 9         | 6.67%   |
| Skylake       | 8         | 5.93%   |
| SandyBridge   | 8         | 5.93%   |
| Zen           | 5         | 3.7%    |
| Goldmont      | 5         | 3.7%    |
| Unknown       | 5         | 3.7%    |
| Zen 3         | 4         | 2.96%   |
| Silvermont    | 4         | 2.96%   |
| Broadwell     | 4         | 2.96%   |
| Zen+          | 3         | 2.22%   |
| Core          | 3         | 2.22%   |
| Zen 2         | 2         | 1.48%   |
| Westmere      | 2         | 1.48%   |
| TigerLake     | 2         | 1.48%   |
| Penryn        | 2         | 1.48%   |
| IceLake       | 2         | 1.48%   |
| Goldmont plus | 2         | 1.48%   |
| CometLake     | 2         | 1.48%   |
| Piledriver    | 1         | 0.74%   |
| Geode         | 1         | 0.74%   |
| Excavator     | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 57        | 54.81%  |
| AMD                                          | 16        | 15.38%  |
| Nvidia                                       | 13        | 12.5%   |
| ASPEED Technology                            | 11        | 10.58%  |
| Matrox Electronics Systems                   | 5         | 4.81%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.96%   |
| 3DLabs                                       | 1         | 0.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                           | 11        | 10.58%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 4         | 3.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 4         | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 4         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 4         | 3.85%   |
| Intel UHD Graphics 620                                                             | 3         | 2.88%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                               | 3         | 2.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                          | 3         | 2.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]               | 3         | 2.88%   |
| AMD Cezanne                                                                        | 3         | 2.88%   |
| Nvidia GP108M [GeForce MX150]                                                      | 2         | 1.92%   |
| Matrox Electronics Systems MGA G200EH                                              | 2         | 1.92%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                  | 2         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller        | 2         | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                          | 2         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 2         | 1.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                             | 2         | 1.92%   |
| Intel HD Graphics 5500                                                             | 2         | 1.92%   |
| Intel HD Graphics 530                                                              | 2         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 2         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 2         | 1.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                           | 2         | 1.92%   |
| AMD Renoir                                                                         | 2         | 1.92%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                               | 2         | 1.92%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)                     | 1         | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                              | 1         | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                | 1         | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                                     | 1         | 0.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                  | 1         | 0.96%   |
| Nvidia GK107 [GeForce GT 640]                                                      | 1         | 0.96%   |
| Nvidia GK104 [GeForce GTX 680]                                                     | 1         | 0.96%   |
| Nvidia GF108GL [Quadro 600]                                                        | 1         | 0.96%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                    | 1         | 0.96%   |
| Nvidia G98M [GeForce 9300M GS]                                                     | 1         | 0.96%   |
| Nvidia G98 [Quadro NVS 295]                                                        | 1         | 0.96%   |
| Nvidia G92 [GeForce 8800 GT]                                                       | 1         | 0.96%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                      | 1         | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                   | 1         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                               | 1         | 0.96%   |
| Intel Iris Plus Graphics G7                                                        | 1         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                             | 1         | 0.96%   |
| Intel Iris Plus Graphics 650                                                       | 1         | 0.96%   |
| Intel HD Graphics 620                                                              | 1         | 0.96%   |
| Intel HD Graphics 6000                                                             | 1         | 0.96%   |
| Intel HD Graphics 500                                                              | 1         | 0.96%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                   | 1         | 0.96%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                      | 1         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 1         | 0.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller          | 1         | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                              | 1         | 0.96%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                | 1         | 0.96%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                             | 1         | 0.96%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                                   | 1         | 0.96%   |
| AMD Rage 3 [Rage XL PCI]                                                           | 1         | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                            | 1         | 0.96%   |
| AMD Blackcomb [Radeon HD 6970M/6990M]                                              | 1         | 0.96%   |
| 3DLabs Sun XVR-500 Graphics Accelerator                                            | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 39.26%  |
| Other          | 34        | 25.19%  |
| 1 x AMD        | 16        | 11.85%  |
| 1 x ASPEED     | 11        | 8.15%   |
| 1 x Nvidia     | 10        | 7.41%   |
| 1 x Matrox     | 5         | 3.7%    |
| Intel + Nvidia | 3         | 2.22%   |
| 2 x Intel      | 1         | 0.74%   |
| 1 x XGI        | 1         | 0.74%   |
| 1 x 3DLabs     | 1         | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 90        | 66.67%  |
| Unknown     | 38        | 28.15%  |
| Proprietary | 7         | 5.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 93.33%  |
| 1.01-2.0   | 4         | 2.96%   |
| 3.01-4.0   | 2         | 1.48%   |
| 5.01-6.0   | 1         | 0.74%   |
| 2.01-3.0   | 1         | 0.74%   |
| 0.01-0.5   | 1         | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 6         | 20.69%  |
| LG Display              | 3         | 10.34%  |
| Chimei Innolux          | 3         | 10.34%  |
| Samsung Electronics     | 2         | 6.9%    |
| JDI                     | 2         | 6.9%    |
| Acer                    | 2         | 6.9%    |
| Sharp                   | 1         | 3.45%   |
| Philips                 | 1         | 3.45%   |
| NEC Computers           | 1         | 3.45%   |
| LG Electronics          | 1         | 3.45%   |
| Lenovo                  | 1         | 3.45%   |
| Iiyama                  | 1         | 3.45%   |
| Eizo                    | 1         | 3.45%   |
| Dell                    | 1         | 3.45%   |
| Chi Mei Optoelectronics | 1         | 3.45%   |
| BOE                     | 1         | 3.45%   |
| Ancor Communications    | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                    | 2         | 6.67%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 2         | 6.67%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch                  | 1         | 3.33%   |
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch        | 1         | 3.33%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch          | 1         | 3.33%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                       | 1         | 3.33%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                             | 1         | 3.33%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                        | 1         | 3.33%   |
| LG Electronics LCD Monitor LG Ultra HD                                   | 1         | 3.33%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 3.33%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 3.33%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch                 | 1         | 3.33%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                    | 1         | 3.33%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                       | 1         | 3.33%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                        | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 3.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1561 1280x800 330x210mm 15.4-inch | 1         | 3.33%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                    | 1         | 3.33%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 300x190mm 14.0-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO159D 1920x1080 380x210mm 17.1-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch           | 1         | 3.33%   |
| Ancor Communications VS278 ACI27A1 1920x1080 600x340mm 27.2-inch         | 1         | 3.33%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                       | 1         | 3.33%   |
| Acer XB271HU A ACR052F 2560x1440 600x340mm 27.2-inch                     | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 43.33%  |
| 2560x1440 (QHD)   | 4         | 13.33%  |
| 3840x2160 (4K)    | 3         | 10%     |
| 3000x2000         | 2         | 6.67%   |
| 1366x768 (WXGA)   | 2         | 6.67%   |
| 3440x1440         | 1         | 3.33%   |
| 1920x1200 (WUXGA) | 1         | 3.33%   |
| 1600x900 (HD+)    | 1         | 3.33%   |
| 1280x800 (WXGA)   | 1         | 3.33%   |
| 11520x2160        | 1         | 3.33%   |
| Unknown           | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 9         | 31.03%  |
| 27      | 6         | 20.69%  |
| 15      | 4         | 13.79%  |
| 12      | 2         | 6.9%    |
| Unknown | 2         | 6.9%    |
| 65      | 1         | 3.45%   |
| 34      | 1         | 3.45%   |
| 31      | 1         | 3.45%   |
| 23      | 1         | 3.45%   |
| 17      | 1         | 3.45%   |
| 14      | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 37.93%  |
| 501-600     | 7         | 24.14%  |
| 201-300     | 5         | 17.24%  |
| Unknown     | 2         | 6.9%    |
| 701-800     | 1         | 3.45%   |
| 601-700     | 1         | 3.45%   |
| 351-400     | 1         | 3.45%   |
| 1001-1500   | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 22        | 75.86%  |
| 4/3     | 2         | 6.9%    |
| 16/10   | 2         | 6.9%    |
| Unknown | 2         | 6.9%    |
| 21/9    | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 34.48%  |
| 301-350        | 6         | 20.69%  |
| 101-110        | 3         | 10.34%  |
| 61-70          | 2         | 6.9%    |
| 351-500        | 2         | 6.9%    |
| Unknown        | 2         | 6.9%    |
| More than 1000 | 1         | 3.45%   |
| 201-250        | 1         | 3.45%   |
| 121-130        | 1         | 3.45%   |
| 91-100         | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 8         | 27.59%  |
| 161-240       | 5         | 17.24%  |
| 101-120       | 5         | 17.24%  |
| 51-100        | 5         | 17.24%  |
| More than 240 | 3         | 10.34%  |
| Unknown       | 2         | 6.9%    |
| 1-50          | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 106       | 77.94%  |
| 1     | 27        | 19.85%  |
| 2     | 3         | 2.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 116       | 66.67%  |
| Realtek Semiconductor             | 22        | 12.64%  |
| Broadcom                          | 11        | 6.32%   |
| TP-Link                           | 3         | 1.72%   |
| Qualcomm Atheros                  | 3         | 1.72%   |
| Mellanox Technologies             | 3         | 1.72%   |
| American Megatrends               | 2         | 1.15%   |
| AMD                               | 2         | 1.15%   |
| VIA Technologies                  | 1         | 0.57%   |
| U-Blox                            | 1         | 0.57%   |
| Sierra Wireless                   | 1         | 0.57%   |
| Samsung Electronics               | 1         | 0.57%   |
| Ralink Technology                 | 1         | 0.57%   |
| Qualcomm Atheros Communications   | 1         | 0.57%   |
| QLogic                            | 1         | 0.57%   |
| Oracle/SUN                        | 1         | 0.57%   |
| MediaTek                          | 1         | 0.57%   |
| Huawei Technologies               | 1         | 0.57%   |
| Free Software Initiative of Japan | 1         | 0.57%   |
| Aquantia                          | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I211 Gigabit Network Connection                                         | 32        | 13.56%  |
| Intel I210 Gigabit Network Connection                                         | 26        | 11.02%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16        | 6.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 5.08%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 2.54%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6         | 2.54%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 2.12%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 2.12%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 1.27%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 1.27%   |
| Intel Ethernet Connection I354                                                | 3         | 1.27%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                                          | 3         | 1.27%   |
| Intel Ethernet Connection (6) I219-LM                                         | 3         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 3         | 1.27%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.27%   |
| Intel 82576 Gigabit Network Connection                                        | 3         | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 1.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 2         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.85%   |
| Intel Wireless 8260                                                           | 2         | 0.85%   |
| Intel Wireless 7265                                                           | 2         | 0.85%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2         | 0.85%   |
| Intel Ethernet Controller X550                                                | 2         | 0.85%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 2         | 0.85%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2         | 0.85%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 0.85%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2         | 0.85%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 0.85%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 0.85%   |
| American Megatrends Virtual Ethernet                                          | 2         | 0.85%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 2         | 0.85%   |
| VIA VT6105M [Rhine-III]                                                       | 1         | 0.42%   |
| U-Blox [u-blox 7]                                                             | 1         | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.42%   |
| Sierra Wireless EM7455                                                        | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.42%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.42%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 1         | 0.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.42%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.42%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.42%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 0.42%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1         | 0.42%   |
| Mellanox MT2894 Family [ConnectX-6 Lx]                                        | 1         | 0.42%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1         | 0.42%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 0.42%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 0.42%   |
| Intel Wireless 7260                                                           | 1         | 0.42%   |
| Intel Wireless 3165                                                           | 1         | 0.42%   |
| Intel WiFi Link 5100                                                          | 1         | 0.42%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 0.42%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 59.18%  |
| Realtek Semiconductor           | 8         | 16.33%  |
| TP-Link                         | 3         | 6.12%   |
| Broadcom                        | 3         | 6.12%   |
| Qualcomm Atheros                | 2         | 4.08%   |
| Sierra Wireless                 | 1         | 2.04%   |
| Ralink Technology               | 1         | 2.04%   |
| Qualcomm Atheros Communications | 1         | 2.04%   |
| MediaTek                        | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 5         | 10.2%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 6.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 6.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 6.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.08%   |
| Intel Wireless 8260                                            | 2         | 4.08%   |
| Intel Wireless 7265                                            | 2         | 4.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 2.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 2.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 2.04%   |
| Sierra Wireless EM7455                                         | 1         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.04%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.04%   |
| MediaTek 802.11 n WLAN                                         | 1         | 2.04%   |
| Intel Wireless 7260                                            | 1         | 2.04%   |
| Intel Wireless 3165                                            | 1         | 2.04%   |
| Intel WiFi Link 5100                                           | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.04%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.04%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 103       | 74.64%  |
| Realtek Semiconductor | 16        | 11.59%  |
| Broadcom              | 9         | 6.52%   |
| American Megatrends   | 2         | 1.45%   |
| AMD                   | 2         | 1.45%   |
| VIA Technologies      | 1         | 0.72%   |
| Samsung Electronics   | 1         | 0.72%   |
| Qualcomm Atheros      | 1         | 0.72%   |
| QLogic                | 1         | 0.72%   |
| Oracle/SUN            | 1         | 0.72%   |
| Aquantia              | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I211 Gigabit Network Connection                                         | 32        | 17.68%  |
| Intel I210 Gigabit Network Connection                                         | 26        | 14.36%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16        | 8.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 6.63%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 3.31%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6         | 3.31%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 2.76%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 1.66%   |
| Intel Ethernet Connection I354                                                | 3         | 1.66%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.66%   |
| Intel Ethernet Connection (6) I219-V                                          | 3         | 1.66%   |
| Intel Ethernet Connection (6) I219-LM                                         | 3         | 1.66%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.66%   |
| Intel 82576 Gigabit Network Connection                                        | 3         | 1.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 1.66%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2         | 1.1%    |
| Intel Ethernet Controller X550                                                | 2         | 1.1%    |
| Intel Ethernet Connection X722 for 1GbE                                       | 2         | 1.1%    |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2         | 1.1%    |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.1%    |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2         | 1.1%    |
| Intel 82579V Gigabit Network Connection                                       | 2         | 1.1%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 1.1%    |
| American Megatrends Virtual Ethernet                                          | 2         | 1.1%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 2         | 1.1%    |
| VIA VT6105M [Rhine-III]                                                       | 1         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.55%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 0.55%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1         | 0.55%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1         | 0.55%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1         | 0.55%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1         | 0.55%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.55%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1         | 0.55%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 0.55%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 0.55%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 0.55%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 1         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.55%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.55%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.55%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 0.55%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.55%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 0.55%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1         | 0.55%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1         | 0.55%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 1         | 0.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.55%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 0.55%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1         | 0.55%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 0.55%   |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 1         | 0.55%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]                          | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 124       | 71.68%  |
| WiFi     | 43        | 24.86%  |
| Unknown  | 4         | 2.31%   |
| Modem    | 2         | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 82.52%  |
| WiFi     | 25        | 17.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 32        | 23.53%  |
| 2     | 26        | 19.12%  |
| 1     | 21        | 15.44%  |
| 4     | 20        | 14.71%  |
| 6     | 16        | 11.76%  |
| 5     | 10        | 7.35%   |
| 8     | 3         | 2.21%   |
| 13    | 2         | 1.47%   |
| 0     | 2         | 1.47%   |
| 14    | 1         | 0.74%   |
| 12    | 1         | 0.74%   |
| 10    | 1         | 0.74%   |
| 7     | 1         | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 111       | 77.62%  |
| Yes  | 32        | 22.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 20        | 57.14%  |
| IMC Networks            | 3         | 8.57%   |
| ASUSTek Computer        | 3         | 8.57%   |
| Realtek Semiconductor   | 2         | 5.71%   |
| Apple                   | 2         | 5.71%   |
| Lite-On Technology      | 1         | 2.86%   |
| Dell                    | 1         | 2.86%   |
| Cambridge Silicon Radio | 1         | 2.86%   |
| Broadcom                | 1         | 2.86%   |
| Alps Electric           | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 25.71%  |
| Intel AX201 Bluetooth                               | 4         | 11.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.57%   |
| Intel AX200 Bluetooth                               | 3         | 8.57%   |
| Realtek Bluetooth Radio                             | 2         | 5.71%   |
| IMC Networks Realtek Bluetooth Adapter              | 2         | 5.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.86%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.86%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module         | 1         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.86%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.86%   |
| ASUS Bluetooth Controller                           | 1         | 2.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.86%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.86%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 67.02%  |
| AMD                   | 18        | 19.15%  |
| Nvidia                | 8         | 8.51%   |
| ULi Electronics       | 2         | 2.13%   |
| Realtek Semiconductor | 1         | 1.06%   |
| Logitech              | 1         | 1.06%   |
| GN Netcom             | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 9         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 7.41%   |
| Intel Sunrise Point-LP HD Audio                                                   | 7         | 6.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 6.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 6         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5         | 4.63%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 4         | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3         | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 2.78%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 2.78%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2         | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 1.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                         | 2         | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.85%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.85%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                | 1         | 0.93%   |
| Nvidia unknown                                                                    | 1         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.93%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.93%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 0.93%   |
| Logitech H600 [Wireless Headset]                                                  | 1         | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 1         | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 0.93%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 0.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1         | 0.93%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1         | 0.93%   |
| Intel 200 Series PCH HD Audio                                                     | 1         | 0.93%   |
| GN Netcom Jabra UC VOICE 550 MS mono USB                                          | 1         | 0.93%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 1         | 0.93%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1         | 0.93%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 33        | 26.4%   |
| Unknown             | 22        | 17.6%   |
| Samsung Electronics | 14        | 11.2%   |
| SK Hynix            | 13        | 10.4%   |
| Micron Technology   | 12        | 9.6%    |
| Crucial             | 8         | 6.4%    |
| Corsair             | 8         | 6.4%    |
| Transcend           | 3         | 2.4%    |
| Hewlett-Packard     | 2         | 1.6%    |
| Unknown (ABCD)      | 1         | 0.8%    |
| Unknown (0x05F7)    | 1         | 0.8%    |
| Unknown (07FB)      | 1         | 0.8%    |
| Toshiba             | 1         | 0.8%    |
| Tigo                | 1         | 0.8%    |
| Super Talent        | 1         | 0.8%    |
| Silicon Power       | 1         | 0.8%    |
| Nanya Technology    | 1         | 0.8%    |
| Elpida              | 1         | 0.8%    |
| A-DATA Technology   | 1         | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 12        | 9.02%   |
| SK Hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 3         | 2.26%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s             | 3         | 2.26%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2133MT/s           | 3         | 2.26%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                       | 2         | 1.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 1.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 1.5%    |
| SK Hynix RAM HMA82GR7CJR4N-WM 16GB DIMM DDR4 2933MT/s            | 2         | 1.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.5%    |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 1.5%    |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 2         | 1.5%    |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s            | 2         | 1.5%    |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s             | 2         | 1.5%    |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s             | 2         | 1.5%    |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                       | 1         | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                        | 1         | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.75%   |
| Unknown (0x05F7) RAM Module 1GB FB-DIMM DDR2 800MT/s             | 1         | 0.75%   |
| Unknown (07FB) RAM GSA8G4SCL196P-26 8GB SODIMM DDR4 2667MT/s     | 1         | 0.75%   |
| Transcend RAM TS512MLK64W6H 4GB DIMM DDR3 1600MT/s               | 1         | 0.75%   |
| Transcend RAM TS256MLK64W6N 2GB DIMM DDR3 1600MT/s               | 1         | 0.75%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 1         | 0.75%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s              | 1         | 0.75%   |
| Toshiba RAM 9965527-021.A00LF 8GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.75%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1333MT/s            | 1         | 0.75%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.75%   |
| SK Hynix RAM Module 1GB FB-DIMM DDR2 800MT/s                     | 1         | 0.75%   |
| SK Hynix RAM HMT42GR7MFR4C-PB 16384MB DIMM DDR3 1600MT/s         | 1         | 0.75%   |
| SK Hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 0.75%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.75%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s          | 1         | 0.75%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 1         | 0.75%   |
| SK Hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.75%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 1         | 0.75%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.75%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 0.75%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s                       | 1         | 0.75%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s              | 1         | 0.75%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 1         | 0.75%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.75%   |
| Samsung RAM M393B2G70DB0-CK0 16GB DIMM DDR3 1600MT/s             | 1         | 0.75%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s             | 1         | 0.75%   |
| Samsung RAM M393B1K70BH1-CH9 8GB DIMM DDR3 1333MT/s              | 1         | 0.75%   |
| Samsung RAM M393A1K43BB1-CTD 8GB RIMM DDR4 2133MT/s              | 1         | 0.75%   |
| Samsung RAM M391B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s           | 1         | 0.75%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 0.75%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s                | 1         | 0.75%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s               | 1         | 0.75%   |
| Micron RAM Module 4096MB DIMM DDR3 1333MT/s                      | 1         | 0.75%   |
| Micron RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 0.75%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s            | 1         | 0.75%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.75%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 52        | 46.43%  |
| DDR4    | 47        | 41.96%  |
| DDR2    | 5         | 4.46%   |
| LPDDR4  | 4         | 3.57%   |
| LPDDR3  | 3         | 2.68%   |
| Unknown | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 46.43%  |
| DIMM         | 49        | 43.75%  |
| Row Of Chips | 8         | 7.14%   |
| RIMM         | 1         | 0.89%   |
| FB-DIMM      | 1         | 0.89%   |
| Chip         | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 52        | 44.07%  |
| 4096  | 35        | 29.66%  |
| 16384 | 17        | 14.41%  |
| 2048  | 9         | 7.63%   |
| 1024  | 3         | 2.54%   |
| 32768 | 1         | 0.85%   |
| 512   | 1         | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1333  | 31        | 25.83%  |
| 1600  | 19        | 15.83%  |
| 2133  | 16        | 13.33%  |
| 2667  | 14        | 11.67%  |
| 2400  | 10        | 8.33%   |
| 3200  | 9         | 7.5%    |
| 2666  | 5         | 4.17%   |
| 800   | 4         | 3.33%   |
| 667   | 4         | 3.33%   |
| 4267  | 2         | 1.67%   |
| 2933  | 2         | 1.67%   |
| 1867  | 1         | 0.83%   |
| 1866  | 1         | 0.83%   |
| 1800  | 1         | 0.83%   |
| 1033  | 1         | 0.83%   |

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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 47.37%  |
| IMC Networks                           | 4         | 21.05%  |
| Acer                                   | 2         | 10.53%  |
| Suyin                                  | 1         | 5.26%   |
| Sunplus Innovation Technology          | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |
| Apple                                  | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 4         | 21.05%  |
| IMC Networks Integrated Camera                   | 3         | 15.79%  |
| Acer Integrated Camera                           | 2         | 10.53%  |
| Suyin HD WebCam                                  | 1         | 5.26%   |
| Sunplus Laptop Integrated Webcam FHD             | 1         | 5.26%   |
| IMC Networks EasyCamera                          | 1         | 5.26%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 5.26%   |
| Chicony USB 2.0 2.0M UVC WebCam                  | 1         | 5.26%   |
| Chicony ThinkPad T490 Webcam                     | 1         | 5.26%   |
| Chicony Lenovo EasyCamera                        | 1         | 5.26%   |
| Chicony HP Universal Camera                      | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 5.26%   |
| Apple FaceTime HD Camera                         | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 40%     |
| Synaptics        | 2         | 40%     |
| Upek             | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 20%     |
| Validity Sensors Synaptics WBDI                        | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Synaptics  WBDI                                        | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 20%     |

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
| 0     | 54        | 38.57%  |
| 1     | 40        | 28.57%  |
| 2     | 25        | 17.86%  |
| 3     | 13        | 9.29%   |
| 4     | 6         | 4.29%   |
| 5     | 2         | 1.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 69        | 51.11%  |
| Bluetooth                | 16        | 11.85%  |
| Net/wireless             | 15        | 11.11%  |
| Firewire controller      | 12        | 8.89%   |
| Card reader              | 7         | 5.19%   |
| Sound                    | 4         | 2.96%   |
| Net/ethernet             | 4         | 2.96%   |
| Fingerprint reader       | 4         | 2.96%   |
| Graphics card            | 2         | 1.48%   |
| Storage                  | 1         | 0.74%   |
| Network                  | 1         | 0.74%   |

