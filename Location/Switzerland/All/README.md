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

Total: 311

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Shuttle       | FS81                        | Desktop     | [5787eda5ac](https://bsd-hardware.info/?probe=5787eda5ac) | Feb 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [913946ccc9](https://bsd-hardware.info/?probe=913946ccc9) | Feb 25, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [0e62dfc436](https://bsd-hardware.info/?probe=0e62dfc436) | Feb 25, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [c51a264e20](https://bsd-hardware.info/?probe=c51a264e20) | Feb 23, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [727ca24f1c](https://bsd-hardware.info/?probe=727ca24f1c) | Feb 22, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5b8fdd6349](https://bsd-hardware.info/?probe=5b8fdd6349) | Feb 21, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [9bdcc78235](https://bsd-hardware.info/?probe=9bdcc78235) | Feb 19, 2023 |
| Deciso        | Netboard A20                | Notebook    | [7c91a0f01b](https://bsd-hardware.info/?probe=7c91a0f01b) | Feb 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [4874e3417f](https://bsd-hardware.info/?probe=4874e3417f) | Feb 09, 2023 |
| Intel BOX4... | Geminilake                  | Desktop     | [286c29b1bb](https://bsd-hardware.info/?probe=286c29b1bb) | Feb 08, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3a47e70001](https://bsd-hardware.info/?probe=3a47e70001) | Feb 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [193659d215](https://bsd-hardware.info/?probe=193659d215) | Feb 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [c3ff966a17](https://bsd-hardware.info/?probe=c3ff966a17) | Feb 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [315ef90664](https://bsd-hardware.info/?probe=315ef90664) | Feb 01, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e43ebed0e6](https://bsd-hardware.info/?probe=e43ebed0e6) | Jan 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [92aedf2a46](https://bsd-hardware.info/?probe=92aedf2a46) | Jan 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [5b226a942e](https://bsd-hardware.info/?probe=5b226a942e) | Jan 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [06e3f3daea](https://bsd-hardware.info/?probe=06e3f3daea) | Jan 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [739cc6e5ac](https://bsd-hardware.info/?probe=739cc6e5ac) | Jan 18, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [9994ae920b](https://bsd-hardware.info/?probe=9994ae920b) | Jan 15, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [320272bdf1](https://bsd-hardware.info/?probe=320272bdf1) | Jan 11, 2023 |
| PC Engines    | apu4                        | Desktop     | [3d69b3aec1](https://bsd-hardware.info/?probe=3d69b3aec1) | Jan 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [62e6e7e679](https://bsd-hardware.info/?probe=62e6e7e679) | Jan 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2973cd399c](https://bsd-hardware.info/?probe=2973cd399c) | Jan 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| Sophos        | SG                          | Firewall    | [e331fe5e06](https://bsd-hardware.info/?probe=e331fe5e06) | Dec 26, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [78893acbd5](https://bsd-hardware.info/?probe=78893acbd5) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | Desktop     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| Intel         | NUC9i7QNB K49245-500        | Mini pc     | [154dad5874](https://bsd-hardware.info/?probe=154dad5874) | Oct 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| PC Engines    | APU2                        | Desktop     | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [02a9700c12](https://bsd-hardware.info/?probe=02a9700c12) | Oct 03, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [353008eb5e](https://bsd-hardware.info/?probe=353008eb5e) | Sep 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [3fcc5e5ae2](https://bsd-hardware.info/?probe=3fcc5e5ae2) | Sep 25, 2022 |
| Lenovo        | ThinkPad T460p 20FW003PM... | Notebook    | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Sophos        | SG                          | Firewall    | [d485561c3b](https://bsd-hardware.info/?probe=d485561c3b) | Sep 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | Desktop     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [68ac9de055](https://bsd-hardware.info/?probe=68ac9de055) | Sep 05, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [9422de47ab](https://bsd-hardware.info/?probe=9422de47ab) | Aug 30, 2022 |
| Shuttle       | FS81                        | Desktop     | [b2db8ceabe](https://bsd-hardware.info/?probe=b2db8ceabe) | Aug 24, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [5428710004](https://bsd-hardware.info/?probe=5428710004) | Aug 16, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [3b99c8f471](https://bsd-hardware.info/?probe=3b99c8f471) | Aug 09, 2022 |
| Acer          | Aspire X3995                | Desktop     | [9240256ae5](https://bsd-hardware.info/?probe=9240256ae5) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [9f98df6faf](https://bsd-hardware.info/?probe=9f98df6faf) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [25ca16baef](https://bsd-hardware.info/?probe=25ca16baef) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [f9bf5b2e00](https://bsd-hardware.info/?probe=f9bf5b2e00) | Aug 04, 2022 |
| PC Engines    | APU2                        | Desktop     | [35d0a79b04](https://bsd-hardware.info/?probe=35d0a79b04) | Aug 04, 2022 |
| Protectli     | FW6                         | Desktop     | [b686fdf1c1](https://bsd-hardware.info/?probe=b686fdf1c1) | Jul 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [0b84314fbf](https://bsd-hardware.info/?probe=0b84314fbf) | Jul 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e721b00d5](https://bsd-hardware.info/?probe=4e721b00d5) | Jul 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [7d3a1f2825](https://bsd-hardware.info/?probe=7d3a1f2825) | Jul 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [0dd60aeb9a](https://bsd-hardware.info/?probe=0dd60aeb9a) | Jul 14, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [58a61e6171](https://bsd-hardware.info/?probe=58a61e6171) | Jul 11, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [2aa5e2a62d](https://bsd-hardware.info/?probe=2aa5e2a62d) | Jul 08, 2022 |
| Deciso        | Netboard A20                | Notebook    | [c70ba0979e](https://bsd-hardware.info/?probe=c70ba0979e) | Jul 07, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [fb2e5bec61](https://bsd-hardware.info/?probe=fb2e5bec61) | Jul 05, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [629de6cdb6](https://bsd-hardware.info/?probe=629de6cdb6) | Jul 05, 2022 |
| HP            | 1494                        | Desktop     | [3a61eb7bae](https://bsd-hardware.info/?probe=3a61eb7bae) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [34bb6613ee](https://bsd-hardware.info/?probe=34bb6613ee) | Jun 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [d7d6b654a4](https://bsd-hardware.info/?probe=d7d6b654a4) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [180af6a2da](https://bsd-hardware.info/?probe=180af6a2da) | Jun 19, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [c58d529930](https://bsd-hardware.info/?probe=c58d529930) | Jun 19, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [97e567c06b](https://bsd-hardware.info/?probe=97e567c06b) | Jun 18, 2022 |
| Supermicro    | A1SRM-2758F                 | Server      | [3c53a92a68](https://bsd-hardware.info/?probe=3c53a92a68) | Jun 17, 2022 |
| Supermicro    | X11SSM-F                    | Server      | [626b058309](https://bsd-hardware.info/?probe=626b058309) | Jun 16, 2022 |
| Supermicro    | X11SSM-F                    | Server      | [ef0e973cad](https://bsd-hardware.info/?probe=ef0e973cad) | Jun 15, 2022 |
| ASUSTek       | Pro B660M-C D4              | Desktop     | [302ea8252d](https://bsd-hardware.info/?probe=302ea8252d) | Jun 08, 2022 |
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
| CompuLab      | fitlet2                     | Mini pc     | [18ce49973d](https://bsd-hardware.info/?probe=18ce49973d) | Jul 24, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [f29fab4508](https://bsd-hardware.info/?probe=f29fab4508) | Jul 23, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [b7c3a2b2e4](https://bsd-hardware.info/?probe=b7c3a2b2e4) | Jul 23, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [89938d9a3a](https://bsd-hardware.info/?probe=89938d9a3a) | Jul 20, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [c2721a852b](https://bsd-hardware.info/?probe=c2721a852b) | Jul 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Supermicro    | PDSML+                      | Desktop     | [f8a9ca42d6](https://bsd-hardware.info/?probe=f8a9ca42d6) | Jul 11, 2021 |
| PC Engines    | APU2                        | Desktop     | [fe77a10950](https://bsd-hardware.info/?probe=fe77a10950) | Jul 08, 2021 |
| Intel         | NUC7i7BNB J31145-302        | Mini pc     | [a54eaf1e7b](https://bsd-hardware.info/?probe=a54eaf1e7b) | Jun 28, 2021 |
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
| Fujitsu       | D3383-B1 S26361-D3383-B1... | Server      | [6460f775b0](https://bsd-hardware.info/?probe=6460f775b0) | May 25, 2021 |
| Fujitsu       | D3383-B1 S26361-D3383-B1... | Server      | [10a74a9200](https://bsd-hardware.info/?probe=10a74a9200) | May 25, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [b8b40dbc2d](https://bsd-hardware.info/?probe=b8b40dbc2d) | May 20, 2021 |
| Dell          | Latitude E6430              | Notebook    | [8d24817728](https://bsd-hardware.info/?probe=8d24817728) | May 19, 2021 |
| ASUSTek       | P9D-I Series                | Server      | [fe8dc15588](https://bsd-hardware.info/?probe=fe8dc15588) | May 17, 2021 |
| Sophos        | SG                          | Firewall    | [8d2f78f042](https://bsd-hardware.info/?probe=8d2f78f042) | May 16, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [ae3bb311de](https://bsd-hardware.info/?probe=ae3bb311de) | May 07, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [ef131c774d](https://bsd-hardware.info/?probe=ef131c774d) | May 02, 2021 |
| Lenovo        | 318E NOK                    | Desktop     | [115f2c7b35](https://bsd-hardware.info/?probe=115f2c7b35) | Apr 27, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [44e10ac014](https://bsd-hardware.info/?probe=44e10ac014) | Apr 19, 2021 |
| Sophos        | XG                          | Firewall    | [428b16a419](https://bsd-hardware.info/?probe=428b16a419) | Apr 14, 2021 |
| PC Engines    | APU2                        | Desktop     | [8b425e6086](https://bsd-hardware.info/?probe=8b425e6086) | Apr 08, 2021 |
| PC Engines    | APU2                        | Desktop     | [f261049b51](https://bsd-hardware.info/?probe=f261049b51) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [beacf76b6a](https://bsd-hardware.info/?probe=beacf76b6a) | Mar 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [09e3c55edf](https://bsd-hardware.info/?probe=09e3c55edf) | Mar 26, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f7e09652d9](https://bsd-hardware.info/?probe=f7e09652d9) | Mar 25, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f9fdc75b45](https://bsd-hardware.info/?probe=f9fdc75b45) | Mar 25, 2021 |
| PC Engines    | APU2                        | Desktop     | [6204024271](https://bsd-hardware.info/?probe=6204024271) | Mar 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [b39d8ba487](https://bsd-hardware.info/?probe=b39d8ba487) | Mar 24, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [40ec36ad78](https://bsd-hardware.info/?probe=40ec36ad78) | Mar 18, 2021 |
| PC Engines    | apu4                        | Desktop     | [e10b5c92e9](https://bsd-hardware.info/?probe=e10b5c92e9) | Mar 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [36f81afd88](https://bsd-hardware.info/?probe=36f81afd88) | Mar 13, 2021 |
| PC Engines    | apu4                        | Desktop     | [9268ee6857](https://bsd-hardware.info/?probe=9268ee6857) | Mar 13, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [acbc65fd42](https://bsd-hardware.info/?probe=acbc65fd42) | Mar 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2c0b0d8eb0](https://bsd-hardware.info/?probe=2c0b0d8eb0) | Mar 09, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [6d455b5e28](https://bsd-hardware.info/?probe=6d455b5e28) | Mar 08, 2021 |
| PC Engines    | APU3                        | Desktop     | [cf397191d2](https://bsd-hardware.info/?probe=cf397191d2) | Mar 04, 2021 |
| HP            | 0B54h D                     | Desktop     | [eb8428d5f3](https://bsd-hardware.info/?probe=eb8428d5f3) | Mar 01, 2021 |
| PC Engines    | APU2                        | Desktop     | [2ac1695054](https://bsd-hardware.info/?probe=2ac1695054) | Feb 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [b6c6031b46](https://bsd-hardware.info/?probe=b6c6031b46) | Feb 27, 2021 |
| Sophos        | SG                          | Firewall    | [c7392a1f0d](https://bsd-hardware.info/?probe=c7392a1f0d) | Feb 23, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Supermicro    | X10SDV-8C-TLN4F             | Server      | [636a269a2a](https://bsd-hardware.info/?probe=636a269a2a) | Feb 15, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [ad3998234a](https://bsd-hardware.info/?probe=ad3998234a) | Feb 11, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5a0b61ac41](https://bsd-hardware.info/?probe=5a0b61ac41) | Feb 07, 2021 |
| PC Engines    | APU2                        | Desktop     | [836a3035f1](https://bsd-hardware.info/?probe=836a3035f1) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| PC Engines    | APU2                        | Desktop     | [4985fa31bf](https://bsd-hardware.info/?probe=4985fa31bf) | Feb 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [c740c17c50](https://bsd-hardware.info/?probe=c740c17c50) | Feb 01, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [db0ed2b3c2](https://bsd-hardware.info/?probe=db0ed2b3c2) | Jan 31, 2021 |
| YANYU         | D19SL_B                     | Desktop     | [d16128eed9](https://bsd-hardware.info/?probe=d16128eed9) | Jan 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [d2895512c0](https://bsd-hardware.info/?probe=d2895512c0) | Jan 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [b936d5a273](https://bsd-hardware.info/?probe=b936d5a273) | Jan 27, 2021 |
| PC Engines    | APU2                        | Desktop     | [3448eacd29](https://bsd-hardware.info/?probe=3448eacd29) | Jan 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [72e0243d73](https://bsd-hardware.info/?probe=72e0243d73) | Jan 23, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | Desktop     | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | APU2                        | Desktop     | [c6c764813a](https://bsd-hardware.info/?probe=c6c764813a) | Jan 21, 2021 |
| PC Engines    | APU2                        | Desktop     | [bf1b93e96d](https://bsd-hardware.info/?probe=bf1b93e96d) | Jan 21, 2021 |
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
| PC Engines    | APU2                        | Desktop     | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
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


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OPNsense 22.1.8     | 8         | 3.32%   |
| OPNsense 21.7.1     | 8         | 3.32%   |
| OPNsense 20.7.8     | 8         | 3.32%   |
| OPNsense 23.1       | 7         | 2.9%    |
| OPNsense 22.7       | 7         | 2.9%    |
| OPNsense 21.7.3     | 7         | 2.9%    |
| OPNsense 21.1.6     | 7         | 2.9%    |
| OPNsense 22.7.4     | 6         | 2.49%   |
| OPNsense 22.7.10    | 6         | 2.49%   |
| OPNsense 21.1       | 6         | 2.49%   |
| OPNsense 23.1.1     | 5         | 2.07%   |
| OPNsense 21.7.7     | 5         | 2.07%   |
| OPNsense 21.7.6     | 5         | 2.07%   |
| OPNsense 21.1.5     | 5         | 2.07%   |
| OpenBSD 6.8         | 5         | 2.07%   |
| FreeBSD 13.0-p7     | 5         | 2.07%   |
| OPNsense 22.1.6     | 4         | 1.66%   |
| OPNsense 22.1.3     | 4         | 1.66%   |
| OPNsense 22.1.1     | 4         | 1.66%   |
| OPNsense 22.1       | 4         | 1.66%   |
| OPNsense 21.1.3     | 4         | 1.66%   |
| OPNsense 21.1.2     | 4         | 1.66%   |
| GhostBSD 20.04.02   | 4         | 1.66%   |
| FreeBSD 13.1-STABLE | 4         | 1.66%   |
| FreeBSD 13.0        | 4         | 1.66%   |
| OPNsense 22.7.8     | 3         | 1.24%   |
| OPNsense 22.1.9     | 3         | 1.24%   |
| OPNsense 22.1.7     | 3         | 1.24%   |
| OPNsense 22.1.4     | 3         | 1.24%   |
| OPNsense 22.1.10    | 3         | 1.24%   |
| OPNsense 21.7.4     | 3         | 1.24%   |
| OPNsense 21.7       | 3         | 1.24%   |
| OPNsense 21.1.8     | 3         | 1.24%   |
| OPNsense 21.1.7     | 3         | 1.24%   |
| OPNsense 21.1.4     | 3         | 1.24%   |
| OpenBSD 7.0         | 3         | 1.24%   |
| OpenBSD 6.7         | 3         | 1.24%   |
| helloSystem 0.5.0   | 3         | 1.24%   |
| FreeBSD 12.1-p8     | 3         | 1.24%   |
| OPNsense 22.7.9     | 2         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 113       | 64.94%  |
| FreeBSD     | 35        | 20.11%  |
| OpenBSD     | 12        | 6.9%    |
| helloSystem | 7         | 4.02%   |
| GhostBSD    | 5         | 2.87%   |
| TrueNAS     | 2         | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 168       | 97.11%  |
| sparc64 | 2         | 1.16%   |
| arm64   | 2         | 1.16%   |
| i386    | 1         | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 135       | 76.27%  |
| KDE5          | 8         | 4.52%   |
| helloDesktop  | 8         | 4.52%   |
| MATE          | 5         | 2.82%   |
| fvwm          | 5         | 2.82%   |
| XFCE          | 4         | 2.26%   |
| i3            | 4         | 2.26%   |
| TWM           | 2         | 1.13%   |
| LXQt          | 2         | 1.13%   |
| LXDE          | 1         | 0.56%   |
| GNOME         | 1         | 0.56%   |
| Enlightenment | 1         | 0.56%   |
| CDE           | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 137       | 78.74%  |
| X11     | 36        | 20.69%  |
| Wayland | 1         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 148       | 85.06%  |
| SLiM    | 13        | 7.47%   |
| LightDM | 7         | 4.02%   |
| XDM     | 2         | 1.15%   |
| SDDM    | 2         | 1.15%   |
| GDM     | 2         | 1.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 132       | 75%     |
| C       | 20        | 11.36%  |
| en_US   | 18        | 10.23%  |
| de_CH   | 3         | 1.7%    |
| de_DE   | 2         | 1.14%   |
| fr_FR   | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 151       | 87.28%  |
| BIOS | 22        | 12.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 91        | 51.7%   |
| Zfs    | 71        | 40.34%  |
| Ffs    | 12        | 6.82%   |
| Cd9660 | 2         | 1.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 159       | 91.38%  |
| MBR     | 14        | 8.05%   |
| Unknown | 1         | 0.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| PC Engines              | 30        | 17.34%  |
| Lenovo                  | 15        | 8.67%   |
| Unknown                 | 15        | 8.67%   |
| Supermicro              | 11        | 6.36%   |
| ASUSTek Computer        | 11        | 6.36%   |
| Hewlett-Packard         | 9         | 5.2%    |
| Gigabyte Technology     | 8         | 4.62%   |
| Dell                    | 8         | 4.62%   |
| Sophos                  | 7         | 4.05%   |
| Intel                   | 7         | 4.05%   |
| ASRock                  | 6         | 3.47%   |
| Apple                   | 5         | 2.89%   |
| Shuttle                 | 4         | 2.31%   |
| Acer                    | 4         | 2.31%   |
| Protectli               | 3         | 1.73%   |
| Fujitsu                 | 3         | 1.73%   |
| Deciso                  | 3         | 1.73%   |
| Techvision              | 2         | 1.16%   |
| Sun                     | 2         | 1.16%   |
| HUAWEI                  | 2         | 1.16%   |
| BESSTAR Tech            | 2         | 1.16%   |
| ASRockRack              | 2         | 1.16%   |
| AMI                     | 2         | 1.16%   |
| ZOTAC                   | 1         | 0.58%   |
| YANYU                   | 1         | 0.58%   |
| Raspberry Pi Foundation | 1         | 0.58%   |
| Panasonic               | 1         | 0.58%   |
| MW                      | 1         | 0.58%   |
| Intel BOX4A200          | 1         | 0.58%   |
| Infoblox                | 1         | 0.58%   |
| HPE                     | 1         | 0.58%   |
| CompuLab                | 1         | 0.58%   |
| Casper                  | 1         | 0.58%   |
| Biostar                 | 1         | 0.58%   |
| ADI Engineering         | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| PC Engines APU2                            | 16        | 9.25%   |
| Unknown                                    | 15        | 8.67%   |
| PC Engines apu4                            | 12        | 6.94%   |
| Sophos SG                                  | 5         | 2.89%   |
| Supermicro Super Server                    | 3         | 1.73%   |
| Protectli FW6                              | 3         | 1.73%   |
| ASRock A320M-ITX                           | 3         | 1.73%   |
| Techvision TVI7309X                        | 2         | 1.16%   |
| Shuttle DS10U                              | 2         | 1.16%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS         | 2         | 1.16%   |
| HUAWEI MACH-WX9                            | 2         | 1.16%   |
| Fujitsu PRIMERGY RX2530 M5                 | 2         | 1.16%   |
| Dell Precision 3440                        | 2         | 1.16%   |
| Apple MacPro5,1                            | 2         | 1.16%   |
| ZOTAC ZBOX-CI327NANO-GS-01                 | 1         | 0.58%   |
| YANYU D19SL_B                              | 1         | 0.58%   |
| Supermicro X9SCL/X9SCM                     | 1         | 0.58%   |
| Supermicro X10SLL-F                        | 1         | 0.58%   |
| Supermicro SYS-5018D-FN8T                  | 1         | 0.58%   |
| Supermicro SYS-1019D-4C-FHN13TP            | 1         | 0.58%   |
| Supermicro PDSML                           | 1         | 0.58%   |
| Supermicro AS -5019D-FTN4                  | 1         | 0.58%   |
| Supermicro A1SRM-2758F                     | 1         | 0.58%   |
| Supermicro A1SAi                           | 1         | 0.58%   |
| Sun SUNW,Sun-Blade-1500                    | 1         | 0.58%   |
| Sun SUNW,Sun-Blade-100                     | 1         | 0.58%   |
| Sophos XG                                  | 1         | 0.58%   |
| Sophos UTM                                 | 1         | 0.58%   |
| Shuttle TERRA_PC                           | 1         | 0.58%   |
| Shuttle DS77U                              | 1         | 0.58%   |
| RPi Raspberry Pi                           | 1         | 0.58%   |
| PC Engines apu6                            | 1         | 0.58%   |
| PC Engines APU3                            | 1         | 0.58%   |
| Panasonic CF-19ADUAX1M                     | 1         | 0.58%   |
| MW GMLK-2_5G4L                             | 1         | 0.58%   |
| Lenovo Yoga 720-13IKB 81C3                 | 1         | 0.58%   |
| Lenovo ThinkPad X250 20CMCTO1WW            | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS09900   | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| PC Engines APU2                 | 16        | 9.25%   |
| Unknown                         | 15        | 8.67%   |
| PC Engines apu4                 | 12        | 6.94%   |
| Lenovo ThinkPad                 | 10        | 5.78%   |
| Sophos SG                       | 5         | 2.89%   |
| HP Compaq                       | 4         | 2.31%   |
| Acer Aspire                     | 4         | 2.31%   |
| Supermicro Super                | 3         | 1.73%   |
| Protectli FW6                   | 3         | 1.73%   |
| Lenovo Yoga                     | 3         | 1.73%   |
| Dell Precision                  | 3         | 1.73%   |
| ASRock A320M-ITX                | 3         | 1.73%   |
| Techvision TVI7309X             | 2         | 1.16%   |
| Sun SUNW                        | 2         | 1.16%   |
| Shuttle DS10U                   | 2         | 1.16%   |
| HUAWEI MACH-WX9                 | 2         | 1.16%   |
| HP ProLiant                     | 2         | 1.16%   |
| Fujitsu PRIMERGY                | 2         | 1.16%   |
| Dell OptiPlex                   | 2         | 1.16%   |
| Apple MacPro5                   | 2         | 1.16%   |
| ZOTAC ZBOX-CI327NANO-GS-01      | 1         | 0.58%   |
| YANYU D19SL                     | 1         | 0.58%   |
| Supermicro X9SCL                | 1         | 0.58%   |
| Supermicro X10SLL-F             | 1         | 0.58%   |
| Supermicro SYS-5018D-FN8T       | 1         | 0.58%   |
| Supermicro SYS-1019D-4C-FHN13TP | 1         | 0.58%   |
| Supermicro PDSML                | 1         | 0.58%   |
| Supermicro AS                   | 1         | 0.58%   |
| Supermicro A1SRM-2758F          | 1         | 0.58%   |
| Supermicro A1SAi                | 1         | 0.58%   |
| Sophos XG                       | 1         | 0.58%   |
| Sophos UTM                      | 1         | 0.58%   |
| Shuttle TERRA                   | 1         | 0.58%   |
| Shuttle DS77U                   | 1         | 0.58%   |
| RPi Raspberry                   | 1         | 0.58%   |
| PC Engines apu6                 | 1         | 0.58%   |
| PC Engines APU3                 | 1         | 0.58%   |
| Panasonic CF-19ADUAX1M          | 1         | 0.58%   |
| MW GMLK-2                       | 1         | 0.58%   |
| Lenovo ThinkCentre              | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 26        | 15.03%  |
| 2016    | 24        | 13.87%  |
| 2020    | 23        | 13.29%  |
| 2021    | 14        | 8.09%   |
| 2019    | 13        | 7.51%   |
| 2022    | 11        | 6.36%   |
| 2017    | 11        | 6.36%   |
| 2015    | 10        | 5.78%   |
| 2014    | 8         | 4.62%   |
| 2013    | 8         | 4.62%   |
| 2012    | 8         | 4.62%   |
| 2011    | 7         | 4.05%   |
| Unknown | 5         | 2.89%   |
| 2008    | 2         | 1.16%   |
| 2010    | 1         | 0.58%   |
| 2009    | 1         | 0.58%   |
| 2007    | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 110       | 63.58%  |
| Notebook       | 33        | 19.08%  |
| Mini pc        | 11        | 6.36%   |
| Server         | 9         | 5.2%    |
| Firewall       | 7         | 4.05%   |
| System on chip | 2         | 1.16%   |
| Convertible    | 1         | 0.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 80.35%  |
| Yes  | 34        | 19.65%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 51        | 28.81%  |
| 16.01-24.0  | 47        | 26.55%  |
| 4.01-8.0    | 40        | 22.6%   |
| 32.01-64.0  | 20        | 11.3%   |
| 64.01-256.0 | 9         | 5.08%   |
| 2.01-3.0    | 4         | 2.26%   |
| 0.51-1.0    | 2         | 1.13%   |
| 3.01-4.0    | 1         | 0.56%   |
| 1.01-2.0    | 1         | 0.56%   |
| 0.01-0.5    | 1         | 0.56%   |
| Unknown     | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 83        | 45.86%  |
| 0.51-1.0    | 53        | 29.28%  |
| 1.01-2.0    | 21        | 11.6%   |
| 2.01-3.0    | 9         | 4.97%   |
| 3.01-4.0    | 4         | 2.21%   |
| 4.01-8.0    | 3         | 1.66%   |
| 0           | 3         | 1.66%   |
| 8.01-16.0   | 2         | 1.1%    |
| 64.01-256.0 | 1         | 0.55%   |
| 16.01-24.0  | 1         | 0.55%   |
| Unknown     | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 71.02%  |
| 0      | 18        | 10.23%  |
| 2      | 17        | 9.66%   |
| 4      | 4         | 2.27%   |
| 6      | 3         | 1.7%    |
| 3      | 3         | 1.7%    |
| 5      | 2         | 1.14%   |
| 17     | 1         | 0.57%   |
| 16     | 1         | 0.57%   |
| 8      | 1         | 0.57%   |
| 7      | 1         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 85.55%  |
| Yes       | 25        | 14.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 93.64%  |
| No        | 11        | 6.36%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 69.36%  |
| Yes       | 53        | 30.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 129       | 74.57%  |
| Yes       | 44        | 25.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 173       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 50        | 24.39%  |
| Gachnang                           | 7         | 3.41%   |
| Winterthur                         | 6         | 2.93%   |
| Gordola                            | 5         | 2.44%   |
| Basel                              | 5         | 2.44%   |
| St. Moritz                         | 4         | 1.95%   |
| Lenzburg                           | 4         | 1.95%   |
| Lausanne                           | 4         | 1.95%   |
| Horgen                             | 3         | 1.46%   |
| Geneva                             | 3         | 1.46%   |
| Wallisellen                        | 2         | 0.98%   |
| Therwil                            | 2         | 0.98%   |
| St. Gallen                         | 2         | 0.98%   |
| Siggenthal Station                 | 2         | 0.98%   |
| Riehen                             | 2         | 0.98%   |
| Ottenbach                          | 2         | 0.98%   |
| Oensingen                          | 2         | 0.98%   |
| Munchenstein                       | 2         | 0.98%   |
| Moosseedorf                        | 2         | 0.98%   |
| Mettmenstetten                     | 2         | 0.98%   |
| Lucerne                            | 2         | 0.98%   |
| Hittnau / Hittnau (Dorf)           | 2         | 0.98%   |
| Hildisrieden                       | 2         | 0.98%   |
| Glattbrugg                         | 2         | 0.98%   |
| Eiken                              | 2         | 0.98%   |
| Dinhard                            | 2         | 0.98%   |
| Dietikon                           | 2         | 0.98%   |
| Corcelles-pres-Payerne             | 2         | 0.98%   |
| Burgdorf                           | 2         | 0.98%   |
| Buchs                              | 2         | 0.98%   |
| Bern                               | 2         | 0.98%   |
| Zufikon                            | 1         | 0.49%   |
| Yverdon-les-Bains                  | 1         | 0.49%   |
| Yens                               | 1         | 0.49%   |
| Worblaufen                         | 1         | 0.49%   |
| Willisau                           | 1         | 0.49%   |
| Wiesendangen / Wiesendangen (Dorf) | 1         | 0.49%   |
| Wetzikon                           | 1         | 0.49%   |
| Wettswil                           | 1         | 0.49%   |
| Welschenrohr                       | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 72     | 25.14%  |
| WDC                 | 21        | 43     | 11.73%  |
| Phison              | 13        | 16     | 7.26%   |
| Kingston            | 13        | 17     | 7.26%   |
| Intel               | 12        | 31     | 6.7%    |
| Seagate             | 9         | 13     | 5.03%   |
| Transcend           | 6         | 9      | 3.35%   |
| Crucial             | 6         | 13     | 3.35%   |
| Hoodisk             | 5         | 7      | 2.79%   |
| Toshiba             | 4         | 5      | 2.23%   |
| SanDisk             | 4         | 7      | 2.23%   |
| Corsair             | 4         | 6      | 2.23%   |
| HPT                 | 3         | 35     | 1.68%   |
| Hitachi             | 3         | 3      | 1.68%   |
| China               | 3         | 4      | 1.68%   |
| SK hynix            | 2         | 2      | 1.12%   |
| ShiJi               | 2         | 7      | 1.12%   |
| OCZ                 | 2         | 3      | 1.12%   |
| NVMe                | 2         | 2      | 1.12%   |
| KingSpec            | 2         | 2      | 1.12%   |
| FTS                 | 2         | 2      | 1.12%   |
| SPCC                | 1         | 2      | 0.56%   |
| Silicon Motion      | 1         | 1      | 0.56%   |
| PNY                 | 1         | 1      | 0.56%   |
| OPENBSD             | 1         | 1      | 0.56%   |
| Micron Technology   | 1         | 2      | 0.56%   |
| LITEON              | 1         | 6      | 0.56%   |
| KIOXIA              | 1         | 1      | 0.56%   |
| Intenso             | 1         | 2      | 0.56%   |
| HGST                | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 10     | 0.56%   |
| Gigabyte Technology | 1         | 1      | 0.56%   |
| FORESEE             | 1         | 1      | 0.56%   |
| Fanxiang            | 1         | 1      | 0.56%   |
| BIWIN               | 1         | 1      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |
| A-DATA Technology   | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Phison SATA SSD 16GB              | 10        | 4.44%   |
| Samsung SSD 860 EVO 250GB         | 5         | 2.22%   |
| Hoodisk SSD 32GB                  | 5         | 2.22%   |
| Samsung SSD 860 PRO 256GB         | 4         | 1.78%   |
| Phison SATA SSD 32GB              | 3         | 1.33%   |
| Kingston RBUSNS8180DS3128GH 128GB | 3         | 1.33%   |
| HPT DISK 0_3 1TB                  | 3         | 1.33%   |
| HPT DISK 0_2 1TB                  | 3         | 1.33%   |
| HPT DISK 0_1 1TB                  | 3         | 1.33%   |
| HPT DISK 0_0 1TB                  | 3         | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB      | 2         | 0.89%   |
| WDC WDS120G2G0B-00EPW0 120GB      | 2         | 0.89%   |
| WDC WD6002FRYZ-01WD5B1 6TB        | 2         | 0.89%   |
| WDC WD30EFRX-68EUZN0 3TB          | 2         | 0.89%   |
| Transcend TS128GMTE110S 128GB     | 2         | 0.89%   |
| ShiJi SSD 128GB                   | 2         | 0.89%   |
| Samsung SSD 980 PRO 250GB         | 2         | 0.89%   |
| Samsung SSD 960 EVO 250GB         | 2         | 0.89%   |
| Samsung SSD 850 PRO 256GB         | 2         | 0.89%   |
| Samsung SSD 850 EVO 500GB         | 2         | 0.89%   |
| Samsung SSD 850 EVO 250GB         | 2         | 0.89%   |
| Samsung SSD 840 Series 120GB      | 2         | 0.89%   |
| Samsung MZVLB512HAJQ-00000 512GB  | 2         | 0.89%   |
| Kingston SA400S37120G 120GB       | 2         | 0.89%   |
| Intel SSDSC2BW180A4 180GB         | 2         | 0.89%   |
| Intel SSDSA2BW160G3H 160GB        | 2         | 0.89%   |
| HPT DISK 0_9 3TB                  | 2         | 0.89%   |
| HPT DISK 0_8 3TB                  | 2         | 0.89%   |
| HPT DISK 0_7 1TB                  | 2         | 0.89%   |
| HPT DISK 0_6 1TB                  | 2         | 0.89%   |
| HPT DISK 0_5 1TB                  | 2         | 0.89%   |
| HPT DISK 0_4 1TB                  | 2         | 0.89%   |
| HPT DISK 0_14 3TB                 | 2         | 0.89%   |
| HPT DISK 0_13 2TB                 | 2         | 0.89%   |
| HPT DISK 0_12 1TB                 | 2         | 0.89%   |
| HPT DISK 0_11 1TB                 | 2         | 0.89%   |
| HPT DISK 0_10 1TB                 | 2         | 0.89%   |
| Hitachi HDS721050CLA360 500GB     | 2         | 0.89%   |
| FTS PRAID EP580i 2.8TB            | 2         | 0.89%   |
| Crucial CT250MX500SSD1 250GB      | 2         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 28     | 30.56%  |
| Seagate             | 9         | 13     | 25%     |
| HPT                 | 3         | 35     | 8.33%   |
| Hitachi             | 3         | 3      | 8.33%   |
| Toshiba             | 2         | 3      | 5.56%   |
| NVMe                | 2         | 2      | 5.56%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| OPENBSD             | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| Hewlett-Packard     | 1         | 10     | 2.78%   |
| China               | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 53     | 26.96%  |
| Phison              | 13        | 16     | 11.3%   |
| Kingston            | 12        | 14     | 10.43%  |
| Intel               | 10        | 29     | 8.7%    |
| WDC                 | 7         | 11     | 6.09%   |
| Hoodisk             | 5         | 7      | 4.35%   |
| Crucial             | 5         | 12     | 4.35%   |
| SanDisk             | 4         | 7      | 3.48%   |
| Transcend           | 3         | 6      | 2.61%   |
| Corsair             | 3         | 5      | 2.61%   |
| Toshiba             | 2         | 2      | 1.74%   |
| SK hynix            | 2         | 2      | 1.74%   |
| ShiJi               | 2         | 7      | 1.74%   |
| OCZ                 | 2         | 3      | 1.74%   |
| KingSpec            | 2         | 2      | 1.74%   |
| FTS                 | 2         | 2      | 1.74%   |
| China               | 2         | 3      | 1.74%   |
| SPCC                | 1         | 2      | 0.87%   |
| PNY                 | 1         | 1      | 0.87%   |
| Micron Technology   | 1         | 2      | 0.87%   |
| LITEON              | 1         | 6      | 0.87%   |
| Intenso             | 1         | 2      | 0.87%   |
| FORESEE             | 1         | 1      | 0.87%   |
| BIWIN               | 1         | 1      | 0.87%   |
| A-DATA Technology   | 1         | 1      | 0.87%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 112       | 197    | 65.12%  |
| NVMe | 32        | 36     | 18.6%   |
| HDD  | 28        | 99     | 16.28%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 296    | 79.87%  |
| NVMe | 32        | 36     | 20.13%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 116       | 206    | 75.32%  |
| 0.51-1.0   | 18        | 54     | 11.69%  |
| 2.01-3.0   | 7         | 15     | 4.55%   |
| 1.01-2.0   | 7         | 10     | 4.55%   |
| 4.01-10.0  | 4         | 9      | 2.6%    |
| 3.01-4.0   | 2         | 2      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 80        | 45.2%   |
| 1-20       | 27        | 15.25%  |
| 51-100     | 21        | 11.86%  |
| 251-500    | 19        | 10.73%  |
| 21-50      | 15        | 8.47%   |
| 501-1000   | 13        | 7.34%   |
| 2001-3000  | 1         | 0.56%   |
| 1001-2000  | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 160       | 88.4%   |
| 21-50   | 11        | 6.08%   |
| 51-100  | 6         | 3.31%   |
| 251-500 | 2         | 1.1%    |
| 101-250 | 2         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB    | 1         | 2      | 5.56%   |
| WDC WD6002FRYZ-01WD5B1 6TB      | 1         | 6      | 5.56%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1         | 1      | 5.56%   |
| WDC WD30EFRX-68EUZN0 3TB        | 1         | 1      | 5.56%   |
| WDC WD2002FYPS-01U1B0 2TB       | 1         | 1      | 5.56%   |
| Toshiba MK1059GSM 1TB           | 1         | 1      | 5.56%   |
| Seagate ST3500413AS 500GB       | 1         | 1      | 5.56%   |
| Seagate ST2000VN004-2E4164 2TB  | 1         | 2      | 5.56%   |
| Samsung Electronics HD204UI 2TB | 1         | 1      | 5.56%   |
| OCZ AGILITY3 240GB              | 1         | 1      | 5.56%   |
| Kingston SV300S37A120G 120GB    | 1         | 1      | 5.56%   |
| Intel SSDSCKKF256G8H 256GB      | 1         | 2      | 5.56%   |
| Intel SSDSC2BW240A4 240GB       | 1         | 2      | 5.56%   |
| Intel SSDSA2M160G2GC 160GB      | 1         | 2      | 5.56%   |
| Intel SSDSA2BW160G3H 160GB      | 1         | 5      | 5.56%   |
| Hitachi HDS721050CLA660 500GB   | 1         | 1      | 5.56%   |
| HGST HTE725032A7E630 320GB      | 1         | 1      | 5.56%   |
| Corsair Force 3 SSD 120GB       | 1         | 2      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 11     | 23.53%  |
| Intel               | 4         | 11     | 23.53%  |
| Seagate             | 2         | 3      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| OCZ                 | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |
| Corsair             | 1         | 2      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 9      | 33.33%  |
| Seagate             | 2         | 3      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 17     | 53.33%  |
| HDD  | 7         | 16     | 46.67%  |

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
| Works    | 141       | 253    | 85.98%  |
| Malfunc  | 14        | 33     | 8.54%   |
| Detected | 9         | 46     | 5.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 104       | 50.49%  |
| AMD                         | 49        | 23.79%  |
| Samsung Electronics         | 18        | 8.74%   |
| SanDisk                     | 5         | 2.43%   |
| Silicon Motion              | 3         | 1.46%   |
| HighPoint Technologies      | 3         | 1.46%   |
| Broadcom / LSI              | 3         | 1.46%   |
| ASMedia Technology          | 3         | 1.46%   |
| ULi Electronics             | 2         | 0.97%   |
| Transcend                   | 2         | 0.97%   |
| Phison Electronics          | 2         | 0.97%   |
| Marvell Technology Group    | 2         | 0.97%   |
| KIOXIA                      | 2         | 0.97%   |
| JMicron Technology          | 2         | 0.97%   |
| Chelsio Communications      | 2         | 0.97%   |
| Nvidia                      | 1         | 0.49%   |
| Micron/Crucial Technology   | 1         | 0.49%   |
| Kingston Technology Company | 1         | 0.49%   |
| Hewlett-Packard             | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 14.22%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 4.31%   |
| AMD FCH SATA Controller [IDE mode]                                             | 10        | 4.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 2.59%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 2.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 2.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 2.16%   |
| Unknown                                                                        | 5         | 2.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.72%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 4         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.72%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.29%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 3         | 1.29%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 3         | 1.29%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.29%   |
| Intel Atom Processor C3000 Series SATA Controller 1                            | 3         | 1.29%   |
| Intel Atom Processor C3000 Series SATA Controller 0                            | 3         | 1.29%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 3         | 1.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.29%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.29%   |
| AMD FCH SATA Controller D                                                      | 3         | 1.29%   |
| ULi M5229 IDE                                                                  | 2         | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.86%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 0.86%   |
| JMicron JMB58x AHCI SATA controller                                            | 2         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.86%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 2         | 0.86%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 2         | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 65.7%   |
| NVMe | 35        | 16.91%  |
| IDE  | 19        | 9.18%   |
| RAID | 12        | 5.8%    |
| SCSI | 3         | 1.45%   |
| SAS  | 2         | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 116       | 67.05%  |
| AMD     | 53        | 30.64%  |
| ARM     | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                            | 30        | 17.34%  |
| Intel Celeron J4125 CPU @ 2.00GHz           | 4         | 2.31%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 4         | 2.31%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.73%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 1.73%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz        | 2         | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.16%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 1.16%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2         | 1.16%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 2         | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.16%   |
| Intel Celeron N5100 @ 1.10GHz               | 2         | 1.16%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2         | 1.16%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 2         | 1.16%   |
| Intel Atom CPU C2558 @ 2.40GHz              | 2         | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.16%   |
| ARM Cortex-A53 r0p4                         | 2         | 1.16%   |
| AMD Ryzen Embedded V1500B                   | 2         | 1.16%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2         | 1.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 1.16%   |
|                                             | 2         | 1.16%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 1         | 0.58%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1         | 0.58%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1         | 0.58%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.58%   |
| Intel Xeon CPU E5630 @ 2.53GHz              | 1         | 0.58%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1         | 0.58%   |
| Intel Xeon CPU E5-2620 @ 2.00GHz            | 1         | 0.58%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1         | 0.58%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1         | 0.58%   |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz        | 1         | 0.58%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1         | 0.58%   |
| Intel Xeon CPU E                            | 1         | 0.58%   |
| Intel Xeon CPU D-1540 @ 2.00GHz             | 1         | 0.58%   |
| Intel Xeon CPU D-1518 @ 2.20GHz             | 1         | 0.58%   |
| Intel Pentium Gold G7400                    | 1         | 0.58%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1         | 0.58%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| AMD GX                 | 31        | 17.92%  |
| Intel Core i5          | 28        | 16.18%  |
| Intel Core i7          | 22        | 12.72%  |
| Intel Celeron          | 19        | 10.98%  |
| Intel Xeon             | 16        | 9.25%   |
| Intel Atom             | 9         | 5.2%    |
| Intel Core i3          | 8         | 4.62%   |
| Other                  | 7         | 4.05%   |
| AMD Ryzen 7            | 6         | 3.47%   |
| Intel Core 2 Duo       | 4         | 2.31%   |
| AMD Ryzen 5            | 4         | 2.31%   |
| Intel Xeon Silver      | 2         | 1.16%   |
| Intel Pentium          | 2         | 1.16%   |
| ARM Cortex             | 2         | 1.16%   |
| AMD Ryzen Embedded     | 2         | 1.16%   |
| AMD Ryzen 7 PRO        | 2         | 1.16%   |
| AMD Ryzen 3            | 2         | 1.16%   |
| AMD EPYC               | 2         | 1.16%   |
| Intel Pentium Gold     | 1         | 0.58%   |
| AMD Ryzen Threadripper | 1         | 0.58%   |
| AMD Opteron            | 1         | 0.58%   |
| AMD Geode Integrated   | 1         | 0.58%   |
| AMD FX                 | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 92        | 53.18%  |
| 2       | 37        | 21.39%  |
| 8       | 15        | 8.67%   |
| 16      | 9         | 5.2%    |
| 6       | 5         | 2.89%   |
| Unknown | 5         | 2.89%   |
| 12      | 3         | 1.73%   |
| 1       | 3         | 1.73%   |
| 20      | 2         | 1.16%   |
| 32      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 162       | 93.64%  |
| 2       | 6         | 3.47%   |
| Unknown | 4         | 2.31%   |
| 4       | 1         | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 99        | 57.23%  |
| 2       | 67        | 38.73%  |
| Unknown | 7         | 4.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Puma          | 30        | 17.34%  |
| KabyLake      | 24        | 13.87%  |
| IvyBridge     | 13        | 7.51%   |
| Haswell       | 13        | 7.51%   |
| Skylake       | 11        | 6.36%   |
| Unknown       | 10        | 5.78%   |
| SandyBridge   | 9         | 5.2%    |
| Zen 3         | 7         | 4.05%   |
| Zen           | 7         | 4.05%   |
| Silvermont    | 7         | 4.05%   |
| Broadwell     | 6         | 3.47%   |
| Goldmont plus | 5         | 2.89%   |
| Goldmont      | 5         | 2.89%   |
| Zen+          | 3         | 1.73%   |
| TigerLake     | 3         | 1.73%   |
| Penryn        | 3         | 1.73%   |
| Core          | 3         | 1.73%   |
| Zen 2         | 2         | 1.16%   |
| Westmere      | 2         | 1.16%   |
| Nehalem       | 2         | 1.16%   |
| IceLake       | 2         | 1.16%   |
| CometLake     | 2         | 1.16%   |
| Piledriver    | 1         | 0.58%   |
| Jaguar        | 1         | 0.58%   |
| Geode         | 1         | 0.58%   |
| Excavator     | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 81        | 58.27%  |
| AMD                                          | 18        | 12.95%  |
| Nvidia                                       | 17        | 12.23%  |
| ASPEED Technology                            | 15        | 10.79%  |
| Matrox Electronics Systems                   | 6         | 4.32%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.72%   |
| 3DLabs                                       | 1         | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                    | 15        | 10.71%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 4.29%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 2.86%   |
| Intel HD Graphics 610                                                       | 4         | 2.86%   |
| Intel HD Graphics 530                                                       | 4         | 2.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.86%   |
| Intel UHD Graphics 620                                                      | 3         | 2.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 2.14%   |
| Intel JasperLake [UHD Graphics]                                             | 3         | 2.14%   |
| Intel HD Graphics 5500                                                      | 3         | 2.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 2.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 2.14%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.43%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 1.43%   |
| Matrox Electronics Systems MGA G200EH                                       | 2         | 1.43%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 1.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.43%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 1.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.43%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.43%   |
| AMD Renoir                                                                  | 2         | 1.43%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2         | 1.43%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)              | 1         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.71%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.71%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1         | 0.71%   |
| Nvidia GK107 [GeForce GT 640 OEM]                                           | 1         | 0.71%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 0.71%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1         | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 76        | 43.93%  |
| Other          | 38        | 21.97%  |
| 1 x AMD        | 18        | 10.4%   |
| 1 x ASPEED     | 15        | 8.67%   |
| 1 x Nvidia     | 12        | 6.94%   |
| 1 x Matrox     | 6         | 3.47%   |
| Intel + Nvidia | 4         | 2.31%   |
| 2 x Nvidia     | 1         | 0.58%   |
| 2 x Intel      | 1         | 0.58%   |
| 1 x XGI        | 1         | 0.58%   |
| 1 x 3DLabs     | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 121       | 69.94%  |
| Unknown     | 43        | 24.86%  |
| Proprietary | 9         | 5.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 161       | 93.06%  |
| 1.01-2.0   | 4         | 2.31%   |
| 3.01-4.0   | 3         | 1.73%   |
| 0.01-0.5   | 3         | 1.73%   |
| 5.01-6.0   | 1         | 0.58%   |
| 2.01-3.0   | 1         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 6         | 18.75%  |
| Samsung Electronics     | 3         | 9.38%   |
| LG Display              | 3         | 9.38%   |
| Chimei Innolux          | 3         | 9.38%   |
| JDI                     | 2         | 6.25%   |
| Acer                    | 2         | 6.25%   |
| Sharp                   | 1         | 3.13%   |
| Philips                 | 1         | 3.13%   |
| NEC Computers           | 1         | 3.13%   |
| LG Electronics          | 1         | 3.13%   |
| Lenovo                  | 1         | 3.13%   |
| Iiyama                  | 1         | 3.13%   |
| Fujitsu Siemens         | 1         | 3.13%   |
| Eizo                    | 1         | 3.13%   |
| Dell                    | 1         | 3.13%   |
| Chi Mei Optoelectronics | 1         | 3.13%   |
| BOE                     | 1         | 3.13%   |
| Apple                   | 1         | 3.13%   |
| Ancor Communications    | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                    | 2         | 6.06%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 2         | 6.06%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch                  | 1         | 3.03%   |
| Samsung Electronics U32E850 SAM0CE3 3840x2160 700x390mm 31.5-inch        | 1         | 3.03%   |
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch        | 1         | 3.03%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch          | 1         | 3.03%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                       | 1         | 3.03%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                             | 1         | 3.03%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                        | 1         | 3.03%   |
| LG Electronics LCD Monitor LG Ultra HD                                   | 1         | 3.03%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 3.03%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch                 | 1         | 3.03%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                    | 1         | 3.03%   |
| Fujitsu Siemens S19-1 FUS0517 1280x1024 380x300mm 19.1-inch              | 1         | 3.03%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                       | 1         | 3.03%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                        | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1561 1280x800 330x210mm 15.4-inch | 1         | 3.03%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                    | 1         | 3.03%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 300x190mm 14.0-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO159D 1920x1080 380x210mm 17.1-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch           | 1         | 3.03%   |
| Apple LCD Monitor APP9C84 1440x900 330x210mm 15.4-inch                   | 1         | 3.03%   |
| Ancor Communications VS278 ACI27A1 1920x1080 600x340mm 27.2-inch         | 1         | 3.03%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                       | 1         | 3.03%   |
| Acer XB271HU A ACR052F 2560x1440 600x340mm 27.2-inch                     | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 39.39%  |
| 3840x2160 (4K)    | 4         | 12.12%  |
| 2560x1440 (QHD)   | 4         | 12.12%  |
| 3000x2000         | 2         | 6.06%   |
| 1366x768 (WXGA)   | 2         | 6.06%   |
| 3440x1440         | 1         | 3.03%   |
| 1920x1200 (WUXGA) | 1         | 3.03%   |
| 1600x900 (HD+)    | 1         | 3.03%   |
| 1440x900 (WXGA+)  | 1         | 3.03%   |
| 1280x800 (WXGA)   | 1         | 3.03%   |
| 1280x1024 (SXGA)  | 1         | 3.03%   |
| 11520x2160        | 1         | 3.03%   |
| Unknown           | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 9         | 28.13%  |
| 27      | 6         | 18.75%  |
| 15      | 5         | 15.63%  |
| 31      | 2         | 6.25%   |
| 12      | 2         | 6.25%   |
| Unknown | 2         | 6.25%   |
| 65      | 1         | 3.13%   |
| 34      | 1         | 3.13%   |
| 23      | 1         | 3.13%   |
| 19      | 1         | 3.13%   |
| 17      | 1         | 3.13%   |
| 14      | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 37.5%   |
| 501-600     | 7         | 21.88%  |
| 201-300     | 5         | 15.63%  |
| 601-700     | 2         | 6.25%   |
| 351-400     | 2         | 6.25%   |
| Unknown     | 2         | 6.25%   |
| 701-800     | 1         | 3.13%   |
| 1001-1500   | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 23        | 71.88%  |
| 16/10   | 3         | 9.38%   |
| 4/3     | 2         | 6.25%   |
| Unknown | 2         | 6.25%   |
| 5/4     | 1         | 3.13%   |
| 21/9    | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 31.25%  |
| 301-350        | 6         | 18.75%  |
| 101-110        | 4         | 12.5%   |
| 351-500        | 3         | 9.38%   |
| 61-70          | 2         | 6.25%   |
| Unknown        | 2         | 6.25%   |
| More than 1000 | 1         | 3.13%   |
| 201-250        | 1         | 3.13%   |
| 151-200        | 1         | 3.13%   |
| 121-130        | 1         | 3.13%   |
| 91-100         | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 9         | 28.13%  |
| 101-120       | 6         | 18.75%  |
| 51-100        | 6         | 18.75%  |
| 161-240       | 5         | 15.63%  |
| More than 240 | 3         | 9.38%   |
| Unknown       | 2         | 6.25%   |
| 1-50          | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 141       | 81.03%  |
| 1     | 30        | 17.24%  |
| 2     | 3         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 150       | 66.37%  |
| Realtek Semiconductor             | 31        | 13.72%  |
| Broadcom                          | 12        | 5.31%   |
| Qualcomm Atheros                  | 5         | 2.21%   |
| TP-Link                           | 3         | 1.33%   |
| Mellanox Technologies             | 3         | 1.33%   |
| AMD                               | 3         | 1.33%   |
| Huawei Technologies               | 2         | 0.88%   |
| Chelsio Communications            | 2         | 0.88%   |
| American Megatrends               | 2         | 0.88%   |
| VIA Technologies                  | 1         | 0.44%   |
| U-Blox                            | 1         | 0.44%   |
| Sierra Wireless                   | 1         | 0.44%   |
| Samsung Electronics               | 1         | 0.44%   |
| Ralink Technology                 | 1         | 0.44%   |
| Qualcomm Atheros Communications   | 1         | 0.44%   |
| QLogic                            | 1         | 0.44%   |
| Oracle/SUN                        | 1         | 0.44%   |
| Nvidia                            | 1         | 0.44%   |
| Microchip Technology              | 1         | 0.44%   |
| MediaTek                          | 1         | 0.44%   |
| Free Software Initiative of Japan | 1         | 0.44%   |
| Aquantia                          | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I211 Gigabit Network Connection                                         | 39        | 12.91%  |
| Intel I210 Gigabit Network Connection                                         | 31        | 10.26%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 23        | 7.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 4.3%    |
| Intel I350 Gigabit Network Connection                                         | 10        | 3.31%   |
| Intel 82574L Gigabit Network Connection                                       | 8         | 2.65%   |
| Intel Ethernet Controller I225-V                                              | 7         | 2.32%   |
| Intel Wi-Fi 6 AX200                                                           | 6         | 1.99%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6         | 1.99%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 1.66%   |
| Intel Ethernet Connection I354                                                | 4         | 1.32%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 1.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.32%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 0.99%   |
| Intel Ethernet Controller X550                                                | 3         | 0.99%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                                          | 3         | 0.99%   |
| Intel Ethernet Connection (6) I219-LM                                         | 3         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 3         | 0.99%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.99%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.99%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.99%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 3         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 2         | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.66%   |
| Intel Wireless 8260                                                           | 2         | 0.66%   |
| Intel Wireless 7265                                                           | 2         | 0.66%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 2         | 0.66%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2         | 0.66%   |
| Intel Ethernet Controller I226-V                                              | 2         | 0.66%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 2         | 0.66%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2         | 0.66%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 0.66%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2         | 0.66%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 0.66%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 0.66%   |
| American Megatrends Virtual Ethernet                                          | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 60.34%  |
| Realtek Semiconductor           | 8         | 13.79%  |
| Qualcomm Atheros                | 4         | 6.9%    |
| Broadcom                        | 4         | 6.9%    |
| TP-Link                         | 3         | 5.17%   |
| Sierra Wireless                 | 1         | 1.72%   |
| Ralink Technology               | 1         | 1.72%   |
| Qualcomm Atheros Communications | 1         | 1.72%   |
| MediaTek                        | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6         | 10.34%  |
| Intel Wireless 8265 / 8275                                     | 5         | 8.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 5.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 3.45%   |
| Intel Wireless 8260                                            | 2         | 3.45%   |
| Intel Wireless 7265                                            | 2         | 3.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 3.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.72%   |
| Sierra Wireless EM7455                                         | 1         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.72%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.72%   |
| MediaTek 802.11 n WLAN                                         | 1         | 1.72%   |
| Intel Wireless 7260                                            | 1         | 1.72%   |
| Intel Wireless 3165                                            | 1         | 1.72%   |
| Intel Wireless 3160                                            | 1         | 1.72%   |
| Intel WiFi Link 5100                                           | 1         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.72%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.72%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 1.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 135       | 73.37%  |
| Realtek Semiconductor  | 25        | 13.59%  |
| Broadcom               | 9         | 4.89%   |
| AMD                    | 3         | 1.63%   |
| Chelsio Communications | 2         | 1.09%   |
| American Megatrends    | 2         | 1.09%   |
| VIA Technologies       | 1         | 0.54%   |
| Samsung Electronics    | 1         | 0.54%   |
| Qualcomm Atheros       | 1         | 0.54%   |
| QLogic                 | 1         | 0.54%   |
| Oracle/SUN             | 1         | 0.54%   |
| Nvidia                 | 1         | 0.54%   |
| Huawei Technologies    | 1         | 0.54%   |
| Aquantia               | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I211 Gigabit Network Connection                                         | 39        | 16.46%  |
| Intel I210 Gigabit Network Connection                                         | 31        | 13.08%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 23        | 9.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 5.49%   |
| Intel I350 Gigabit Network Connection                                         | 10        | 4.22%   |
| Intel 82574L Gigabit Network Connection                                       | 8         | 3.38%   |
| Intel Ethernet Controller I225-V                                              | 7         | 2.95%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6         | 2.53%   |
| Intel Ethernet Connection I354                                                | 4         | 1.69%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 1.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.69%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 1.27%   |
| Intel Ethernet Controller X550                                                | 3         | 1.27%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                                          | 3         | 1.27%   |
| Intel Ethernet Connection (6) I219-LM                                         | 3         | 1.27%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.27%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 1.27%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 3         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.84%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 2         | 0.84%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2         | 0.84%   |
| Intel Ethernet Controller I226-V                                              | 2         | 0.84%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 2         | 0.84%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2         | 0.84%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 0.84%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2         | 0.84%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 0.84%   |
| American Megatrends Virtual Ethernet                                          | 2         | 0.84%   |
| VIA VT6105M [Rhine-III]                                                       | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.42%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 0.42%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1         | 0.42%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.42%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1         | 0.42%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1         | 0.42%   |
| Intel Ethernet Controller E810-XXV for SFP                                    | 1         | 0.42%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 162       | 73.3%   |
| WiFi     | 52        | 23.53%  |
| Unknown  | 4         | 1.81%   |
| Modem    | 3         | 1.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 155       | 85.64%  |
| WiFi     | 26        | 14.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 35        | 20.11%  |
| 4     | 32        | 18.39%  |
| 2     | 31        | 17.82%  |
| 1     | 24        | 13.79%  |
| 6     | 21        | 12.07%  |
| 5     | 16        | 9.2%    |
| 8     | 5         | 2.87%   |
| 13    | 2         | 1.15%   |
| 10    | 2         | 1.15%   |
| 7     | 2         | 1.15%   |
| 0     | 2         | 1.15%   |
| 14    | 1         | 0.57%   |
| 12    | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 74.19%  |
| Yes  | 48        | 25.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 26        | 59.09%  |
| Apple                   | 4         | 9.09%   |
| IMC Networks            | 3         | 6.82%   |
| ASUSTek Computer        | 3         | 6.82%   |
| Realtek Semiconductor   | 2         | 4.55%   |
| Lite-On Technology      | 1         | 2.27%   |
| Foxconn / Hon Hai       | 1         | 2.27%   |
| Dell                    | 1         | 2.27%   |
| Cambridge Silicon Radio | 1         | 2.27%   |
| Broadcom                | 1         | 2.27%   |
| Alps Electric           | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 10        | 22.73%  |
| Intel AX200 Bluetooth                                       | 6         | 13.64%  |
| Intel AX201 Bluetooth                                       | 4         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 6.82%   |
| Realtek Bluetooth Radio                                     | 2         | 4.55%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 4.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 4.55%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 2.27%   |
| Intel Intel Wireless Bluetooth                              | 1         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 2.27%   |
| Intel AX210 Bluetooth                                       | 1         | 2.27%   |
| IMC Networks Bluetooth Radio                                | 1         | 2.27%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.27%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 2.27%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 2.27%   |
| ASUS Bluetooth Controller                                   | 1         | 2.27%   |
| Apple Bluetooth Host Controller                             | 1         | 2.27%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2.27%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 69.05%  |
| AMD                   | 23        | 18.25%  |
| Nvidia                | 11        | 8.73%   |
| ULi Electronics       | 2         | 1.59%   |
| Realtek Semiconductor | 1         | 0.79%   |
| Logitech              | 1         | 0.79%   |
| GN Netcom             | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 11        | 7.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 6.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 6.21%   |
| Intel Sunrise Point-LP HD Audio                                                   | 8         | 5.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7         | 4.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 6         | 4.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6         | 4.14%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 5         | 3.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 5         | 3.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 3.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 2.76%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 2.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 2.07%   |
| Intel Jasper Lake HD Audio                                                        | 3         | 2.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3         | 2.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3         | 2.07%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 2.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 2.07%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2         | 1.38%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2         | 1.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.38%   |
| Intel Comet Lake PCH cAVS                                                         | 2         | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2         | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2         | 1.38%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.38%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                | 1         | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.69%   |
| Nvidia MCP79 High Definition Audio                                                | 1         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.69%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 0.69%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1         | 0.69%   |
| Logitech H600 [Wireless Headset]                                                  | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 41        | 25.15%  |
| Unknown             | 23        | 14.11%  |
| SK hynix            | 21        | 12.88%  |
| Samsung Electronics | 20        | 12.27%  |
| Micron Technology   | 15        | 9.2%    |
| Corsair             | 12        | 7.36%   |
| Crucial             | 11        | 6.75%   |
| Transcend           | 5         | 3.07%   |
| Unknown (ABCD)      | 2         | 1.23%   |
| Toshiba             | 2         | 1.23%   |
| Nanya Technology    | 2         | 1.23%   |
| Hewlett-Packard     | 2         | 1.23%   |
| Unknown (0x05F7)    | 1         | 0.61%   |
| Unknown (07FB)      | 1         | 0.61%   |
| Tigo                | 1         | 0.61%   |
| Super Talent        | 1         | 0.61%   |
| Silicon Power       | 1         | 0.61%   |
| Elpida              | 1         | 0.61%   |
| A-DATA Technology   | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 12        | 6.94%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 3         | 1.73%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s              | 3         | 1.73%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s              | 3         | 1.73%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s              | 3         | 1.73%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2133MT/s            | 3         | 1.73%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 2         | 1.16%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 1.16%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2         | 1.16%   |
| SK hynix RAM HMA82GR7CJR4N-WM 16GB DIMM DDR4 2933MT/s             | 2         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.16%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s    | 2         | 1.16%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s             | 2         | 1.16%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s             | 2         | 1.16%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s             | 2         | 1.16%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s            | 2         | 1.16%   |
| Crucial RAM CT8G4SFRA32A.M8FR 8GB SODIMM DDR4 3200MT/s            | 2         | 1.16%   |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s              | 2         | 1.16%   |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s              | 2         | 1.16%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                        | 1         | 0.58%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                        | 1         | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1         | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                          | 1         | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                         | 1         | 0.58%   |
| Unknown (0x05F7) RAM Module 1GB FB-DIMM DDR2 800MT/s              | 1         | 0.58%   |
| Unknown (07FB) RAM GSA8G4SCL196P-26 8GB SODIMM DDR4 2667MT/s      | 1         | 0.58%   |
| Transcend RAM TS512MSK64W6H 4GB DIMM DDR3 1600MT/s                | 1         | 0.58%   |
| Transcend RAM TS512MLK64W6H 4GB DIMM DDR3 1600MT/s                | 1         | 0.58%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s             | 1         | 0.58%   |
| Transcend RAM TS256MLK64W6N 2GB DIMM DDR3 1600MT/s                | 1         | 0.58%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 1         | 0.58%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s               | 1         | 0.58%   |
| Toshiba RAM 9965527-021.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 0.58%   |
| Toshiba RAM 9965525-140.A00LF 8GB DIMM DDR3 1333MT/s              | 1         | 0.58%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.58%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s             | 1         | 0.58%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.58%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.58%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 67        | 45.89%  |
| DDR4    | 65        | 44.52%  |
| LPDDR4  | 5         | 3.42%   |
| DDR2    | 5         | 3.42%   |
| LPDDR3  | 3         | 2.05%   |
| Unknown | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 47.26%  |
| DIMM         | 66        | 45.21%  |
| Row Of Chips | 8         | 5.48%   |
| RIMM         | 1         | 0.68%   |
| FB-DIMM      | 1         | 0.68%   |
| Chip         | 1         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 67        | 43.51%  |
| 4096  | 41        | 26.62%  |
| 16384 | 28        | 18.18%  |
| 2048  | 12        | 7.79%   |
| 1024  | 3         | 1.95%   |
| 32768 | 2         | 1.3%    |
| 512   | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1333  | 37        | 23.57%  |
| 1600  | 27        | 17.2%   |
| 2667  | 19        | 12.1%   |
| 2133  | 18        | 11.46%  |
| 3200  | 16        | 10.19%  |
| 2400  | 15        | 9.55%   |
| 2666  | 5         | 3.18%   |
| 800   | 4         | 2.55%   |
| 667   | 4         | 2.55%   |
| 4267  | 2         | 1.27%   |
| 2933  | 2         | 1.27%   |
| 3600  | 1         | 0.64%   |
| 3000  | 1         | 0.64%   |
| 1867  | 1         | 0.64%   |
| 1866  | 1         | 0.64%   |
| 1800  | 1         | 0.64%   |
| 1067  | 1         | 0.64%   |
| 1066  | 1         | 0.64%   |
| 1033  | 1         | 0.64%   |

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
| Chicony Electronics                    | 9         | 45%     |
| IMC Networks                           | 4         | 20%     |
| Sunplus Innovation Technology          | 2         | 10%     |
| Bison Electronics                      | 2         | 10%     |
| Suyin                                  | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5%      |
| Apple                                  | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 4         | 20%     |
| IMC Networks Integrated Camera                   | 3         | 15%     |
| Bison Integrated Camera                          | 2         | 10%     |
| Suyin HD WebCam                                  | 1         | 5%      |
| Sunplus Laptop Integrated WebCam HD              | 1         | 5%      |
| Sunplus Laptop Integrated Webcam FHD             | 1         | 5%      |
| IMC Networks EasyCamera                          | 1         | 5%      |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 5%      |
| Chicony USB 2.0 2.0M UVC WebCam                  | 1         | 5%      |
| Chicony ThinkPad T490 Webcam                     | 1         | 5%      |
| Chicony Lenovo EasyCamera                        | 1         | 5%      |
| Chicony HP Universal Camera                      | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 5%      |
| Apple FaceTime HD Camera                         | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 2         | 33.33%  |
| Upek             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                        | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Synaptics  WBDI                                        | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 16.67%  |

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
| 0     | 69        | 38.33%  |
| 1     | 54        | 30%     |
| 2     | 31        | 17.22%  |
| 3     | 17        | 9.44%   |
| 4     | 6         | 3.33%   |
| 5     | 3         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 91        | 53.85%  |
| Bluetooth                | 22        | 13.02%  |
| Net/wireless             | 16        | 9.47%   |
| Firewire controller      | 12        | 7.1%    |
| Card reader              | 9         | 5.33%   |
| Sound                    | 5         | 2.96%   |
| Fingerprint reader       | 5         | 2.96%   |
| Net/ethernet             | 4         | 2.37%   |
| Network                  | 2         | 1.18%   |
| Graphics card            | 2         | 1.18%   |
| Storage                  | 1         | 0.59%   |

