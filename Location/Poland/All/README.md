BSD in Poland - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 249

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Gigabyte      | J4005ND2P-CF                | Desktop     | [2967d5275e](https://bsd-hardware.info/?probe=2967d5275e) | Jul 29, 2022 |
| HP            | 3397                        | Desktop     | [68eb683936](https://bsd-hardware.info/?probe=68eb683936) | Jul 27, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | Notebook    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| HP            | 213D A01                    | Desktop     | [0f58ab215e](https://bsd-hardware.info/?probe=0f58ab215e) | Jul 03, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [fe9f636040](https://bsd-hardware.info/?probe=fe9f636040) | Jun 13, 2022 |
| Dell          | 0TY019 A01                  | Server      | [1aeb1bf3bf](https://bsd-hardware.info/?probe=1aeb1bf3bf) | Jun 09, 2022 |
| Dell          | Latitude 5410               | Notebook    | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6acbc93101](https://bsd-hardware.info/?probe=6acbc93101) | May 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [3f39f21672](https://bsd-hardware.info/?probe=3f39f21672) | May 29, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [6a6fda6d6d](https://bsd-hardware.info/?probe=6a6fda6d6d) | May 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ce4d7c01e5](https://bsd-hardware.info/?probe=ce4d7c01e5) | May 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [cc25e2d869](https://bsd-hardware.info/?probe=cc25e2d869) | May 04, 2022 |
| HP            | 213D A01                    | Desktop     | [562722ac56](https://bsd-hardware.info/?probe=562722ac56) | Apr 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [0d46ae5678](https://bsd-hardware.info/?probe=0d46ae5678) | Apr 25, 2022 |
| Apple         | PowerMac10,1                | Desktop     | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [3c5fcc2377](https://bsd-hardware.info/?probe=3c5fcc2377) | Apr 22, 2022 |
| HP            | 213D A01                    | Desktop     | [4dea775e1b](https://bsd-hardware.info/?probe=4dea775e1b) | Apr 12, 2022 |
| Intel         | NUC6CAYB J26842-405         | Mini pc     | [534af14a9f](https://bsd-hardware.info/?probe=534af14a9f) | Apr 11, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [9a260e4d21](https://bsd-hardware.info/?probe=9a260e4d21) | Apr 05, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [e0c61311da](https://bsd-hardware.info/?probe=e0c61311da) | Apr 01, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [717721a634](https://bsd-hardware.info/?probe=717721a634) | Mar 29, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [30432daccb](https://bsd-hardware.info/?probe=30432daccb) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [38c71bac61](https://bsd-hardware.info/?probe=38c71bac61) | Mar 22, 2022 |
| Acer          | Aptio CRB                   | Mini pc     | [f38b7df811](https://bsd-hardware.info/?probe=f38b7df811) | Mar 20, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [a54ee6f019](https://bsd-hardware.info/?probe=a54ee6f019) | Mar 18, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [55515325c4](https://bsd-hardware.info/?probe=55515325c4) | Mar 15, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [a488c9af25](https://bsd-hardware.info/?probe=a488c9af25) | Mar 14, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Dell          | 075CGM A00                  | Mini pc     | [ac38d3156d](https://bsd-hardware.info/?probe=ac38d3156d) | Mar 10, 2022 |
| Inventec      | 0VKXH3 A01                  | Mini pc     | [d018e86ea8](https://bsd-hardware.info/?probe=d018e86ea8) | Mar 10, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [2db3ec9574](https://bsd-hardware.info/?probe=2db3ec9574) | Feb 27, 2022 |
| Intel         | D945GSEJT                   | Desktop     | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| HP            | 213D A01                    | Desktop     | [b9560ec339](https://bsd-hardware.info/?probe=b9560ec339) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| ASRock        | ConRoe1333-D667             | Desktop     | [624b4f4de7](https://bsd-hardware.info/?probe=624b4f4de7) | Feb 23, 2022 |
| Shuttle       | FZ270                       | Desktop     | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [feb7882341](https://bsd-hardware.info/?probe=feb7882341) | Feb 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| MSI           | MS-AEC11                    | All in one  | [7863616b75](https://bsd-hardware.info/?probe=7863616b75) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| HP            | 213D A01                    | Desktop     | [0171663489](https://bsd-hardware.info/?probe=0171663489) | Feb 12, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| MSI           | B75A-G43                    | Desktop     | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| MSI           | H61M-P20                    | Desktop     | [98ec852f90](https://bsd-hardware.info/?probe=98ec852f90) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| Dell          | 075CGM A00                  | Mini pc     | [5a9e6ea87f](https://bsd-hardware.info/?probe=5a9e6ea87f) | Feb 05, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [550e7feb7f](https://bsd-hardware.info/?probe=550e7feb7f) | Feb 03, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Supermicro    | A2SAN-Ha                    | Server      | [cbb110122a](https://bsd-hardware.info/?probe=cbb110122a) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [2acf9ac926](https://bsd-hardware.info/?probe=2acf9ac926) | Jan 29, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [3a39fe5ec2](https://bsd-hardware.info/?probe=3a39fe5ec2) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [268906bcbe](https://bsd-hardware.info/?probe=268906bcbe) | Jan 29, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [2506316700](https://bsd-hardware.info/?probe=2506316700) | Jan 26, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASRockRack    | X570D4I-2T                  | Desktop     | [9f06290060](https://bsd-hardware.info/?probe=9f06290060) | Jan 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Intel         | SKYBAY                      | Desktop     | [64db889658](https://bsd-hardware.info/?probe=64db889658) | Jan 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| Dell          | 0VV3F2 A02                  | Server      | [2897e61a2f](https://bsd-hardware.info/?probe=2897e61a2f) | Dec 28, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [8ac48ba9c3](https://bsd-hardware.info/?probe=8ac48ba9c3) | Dec 23, 2021 |
| MSI           | H81M-P32                    | Desktop     | [bb4e756ca9](https://bsd-hardware.info/?probe=bb4e756ca9) | Dec 20, 2021 |
| Supermicro    | X11SSN-L-VDCA               | Server      | [2efe92bba7](https://bsd-hardware.info/?probe=2efe92bba7) | Dec 20, 2021 |
| Dell          | Latitude E5470              | Notebook    | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Gigabyte      | H110TN                      | Desktop     | [8b6f0f839d](https://bsd-hardware.info/?probe=8b6f0f839d) | Dec 18, 2021 |
| Supermicro    | X11SSN-L-VDCA               | Server      | [5f9458870a](https://bsd-hardware.info/?probe=5f9458870a) | Dec 18, 2021 |
| Dell          | 0YY821 A00                  | Desktop     | [5de293a0be](https://bsd-hardware.info/?probe=5de293a0be) | Dec 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [66ed413cab](https://bsd-hardware.info/?probe=66ed413cab) | Dec 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [73373c3c65](https://bsd-hardware.info/?probe=73373c3c65) | Dec 04, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| Dell          | G15 5510                    | Notebook    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Shuttle       | FH270                       | Desktop     | [81643d52fd](https://bsd-hardware.info/?probe=81643d52fd) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [5add1e88aa](https://bsd-hardware.info/?probe=5add1e88aa) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [23281cbd58](https://bsd-hardware.info/?probe=23281cbd58) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [f092d1f57b](https://bsd-hardware.info/?probe=f092d1f57b) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | Desktop     | [7f32937b2c](https://bsd-hardware.info/?probe=7f32937b2c) | Nov 26, 2021 |
| Shuttle       | FZ270                       | Desktop     | [309687b5be](https://bsd-hardware.info/?probe=309687b5be) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | Desktop     | [4df18caa5f](https://bsd-hardware.info/?probe=4df18caa5f) | Nov 26, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [74a4364a7f](https://bsd-hardware.info/?probe=74a4364a7f) | Nov 25, 2021 |
| HP            | 213D A01                    | Desktop     | [0059e5b645](https://bsd-hardware.info/?probe=0059e5b645) | Nov 23, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Gigabyte      | MX33-BS1-V1                 | Server      | [bccac8e3bb](https://bsd-hardware.info/?probe=bccac8e3bb) | Nov 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| Dell          | G15 5510                    | Notebook    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [d31ea9f041](https://bsd-hardware.info/?probe=d31ea9f041) | Nov 02, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [76dc6d941d](https://bsd-hardware.info/?probe=76dc6d941d) | Oct 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [5c6ee51d15](https://bsd-hardware.info/?probe=5c6ee51d15) | Oct 23, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [f3bf8edc1e](https://bsd-hardware.info/?probe=f3bf8edc1e) | Oct 22, 2021 |
| HP            | 213D A01                    | Desktop     | [4b4903dfb2](https://bsd-hardware.info/?probe=4b4903dfb2) | Oct 17, 2021 |
| Dell          | Latitude E6430              | Notebook    | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [3d0a63b493](https://bsd-hardware.info/?probe=3d0a63b493) | Oct 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | Desktop     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [96448603f5](https://bsd-hardware.info/?probe=96448603f5) | Oct 02, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [e186d750d0](https://bsd-hardware.info/?probe=e186d750d0) | Sep 30, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [a302e181a5](https://bsd-hardware.info/?probe=a302e181a5) | Sep 27, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [9ff547c00b](https://bsd-hardware.info/?probe=9ff547c00b) | Sep 16, 2021 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| ASUSTek       | Q87T                        | Desktop     | [91e631c240](https://bsd-hardware.info/?probe=91e631c240) | Sep 11, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c7b549e91e](https://bsd-hardware.info/?probe=c7b549e91e) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| Essentiel ... | MS-7848                     | Desktop     | [fa20a0307e](https://bsd-hardware.info/?probe=fa20a0307e) | Sep 01, 2021 |
| Dell          | 086HF8 A07                  | Server      | [810f826ac4](https://bsd-hardware.info/?probe=810f826ac4) | Aug 26, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [38332c6f8d](https://bsd-hardware.info/?probe=38332c6f8d) | Aug 16, 2021 |
| Lenovo        | Unknown                     | Notebook    | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| AOpen         | D1009 A1A4                  | Desktop     | [dc60a8dece](https://bsd-hardware.info/?probe=dc60a8dece) | Aug 03, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [fd9fbe6981](https://bsd-hardware.info/?probe=fd9fbe6981) | Jul 16, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [ccbdcabf0a](https://bsd-hardware.info/?probe=ccbdcabf0a) | Jul 12, 2021 |
| HP            | 1998                        | Desktop     | [fdf0088303](https://bsd-hardware.info/?probe=fdf0088303) | Jul 08, 2021 |
| Supermicro    | X10SDV-TP8F                 | Server      | [51d7177ca5](https://bsd-hardware.info/?probe=51d7177ca5) | Jul 01, 2021 |
| Toshiba       | PORTEGE X20W-D              | Convertible | [1e5dc453f6](https://bsd-hardware.info/?probe=1e5dc453f6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [1fffc03fbf](https://bsd-hardware.info/?probe=1fffc03fbf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | Notebook    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | 0MJ137 A00                  | Server      | [8a115f25d1](https://bsd-hardware.info/?probe=8a115f25d1) | Jun 18, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [4097d7aea8](https://bsd-hardware.info/?probe=4097d7aea8) | Jun 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a9fe2f5aad](https://bsd-hardware.info/?probe=a9fe2f5aad) | Jun 16, 2021 |
| Lenovo        | Board                       | Desktop     | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| Dell          | Latitude 5400               | Notebook    | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Dell          | Latitude E6440              | Notebook    | [8fa2c1f5c4](https://bsd-hardware.info/?probe=8fa2c1f5c4) | Jun 13, 2021 |
| Dell          | Latitude E6440              | Notebook    | [77f259babe](https://bsd-hardware.info/?probe=77f259babe) | Jun 12, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [338240a790](https://bsd-hardware.info/?probe=338240a790) | Jun 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf23a1ca58](https://bsd-hardware.info/?probe=bf23a1ca58) | Jun 02, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [9f4ebe949f](https://bsd-hardware.info/?probe=9f4ebe949f) | May 31, 2021 |
| MSI           | H81M-P32                    | Desktop     | [1ffaa46853](https://bsd-hardware.info/?probe=1ffaa46853) | May 31, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [b19abd94b7](https://bsd-hardware.info/?probe=b19abd94b7) | May 31, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [732a50af16](https://bsd-hardware.info/?probe=732a50af16) | May 29, 2021 |
| MSI           | H81M-P32                    | Desktop     | [253deda07f](https://bsd-hardware.info/?probe=253deda07f) | May 28, 2021 |
| Lenovo        | Board                       | Desktop     | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Dell          | Latitude E6410              | Notebook    | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Dell          | 0R230R A00                  | Desktop     | [bd8bf06e7f](https://bsd-hardware.info/?probe=bd8bf06e7f) | May 21, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [1dcb55d9fe](https://bsd-hardware.info/?probe=1dcb55d9fe) | May 05, 2021 |
| Supermicro    | X7DCL                       | Desktop     | [27fc294bca](https://bsd-hardware.info/?probe=27fc294bca) | May 03, 2021 |
| Dell          | Latitude E6440              | Notebook    | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [b848b8e046](https://bsd-hardware.info/?probe=b848b8e046) | Apr 03, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [7ce3b2f01e](https://bsd-hardware.info/?probe=7ce3b2f01e) | Mar 27, 2021 |
| Dell          | 086HF8 A07                  | Server      | [0a3a820345](https://bsd-hardware.info/?probe=0a3a820345) | Mar 26, 2021 |
| Supermicro    | X7SLA                       | Desktop     | [043c20b93d](https://bsd-hardware.info/?probe=043c20b93d) | Mar 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [a332efd9d9](https://bsd-hardware.info/?probe=a332efd9d9) | Mar 15, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b570778ef7](https://bsd-hardware.info/?probe=b570778ef7) | Mar 14, 2021 |
| Dell          | 0TY019 A01                  | Server      | [6a1cb01323](https://bsd-hardware.info/?probe=6a1cb01323) | Mar 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [dee034110e](https://bsd-hardware.info/?probe=dee034110e) | Mar 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [73eec13c5e](https://bsd-hardware.info/?probe=73eec13c5e) | Mar 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [6d7bac1be1](https://bsd-hardware.info/?probe=6d7bac1be1) | Feb 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [60d084275e](https://bsd-hardware.info/?probe=60d084275e) | Feb 19, 2021 |
| Dell          | 05KX61 A02                  | Server      | [31b6e52cf4](https://bsd-hardware.info/?probe=31b6e52cf4) | Feb 15, 2021 |
| HP            | ENVY dv7                    | Notebook    | [4637a9eeff](https://bsd-hardware.info/?probe=4637a9eeff) | Feb 14, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [8d8683565a](https://bsd-hardware.info/?probe=8d8683565a) | Feb 13, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [38f8b13f43](https://bsd-hardware.info/?probe=38f8b13f43) | Feb 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [f4b7bb4518](https://bsd-hardware.info/?probe=f4b7bb4518) | Feb 08, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [b6630c8516](https://bsd-hardware.info/?probe=b6630c8516) | Feb 07, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [5f293a8796](https://bsd-hardware.info/?probe=5f293a8796) | Feb 05, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [e73a728a76](https://bsd-hardware.info/?probe=e73a728a76) | Feb 03, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [612272e598](https://bsd-hardware.info/?probe=612272e598) | Feb 03, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [b26cfcd81d](https://bsd-hardware.info/?probe=b26cfcd81d) | Dec 28, 2020 |
| Lenovo        | ThinkPad X200s 7470A98      | Notebook    | [41f36aa8b6](https://bsd-hardware.info/?probe=41f36aa8b6) | Dec 19, 2020 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown       | Spring Peak                 | Notebook    | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| PC Special... | Recoil II                   | Notebook    | [343eec31b5](https://bsd-hardware.info/?probe=343eec31b5) | Dec 06, 2020 |
| Panasonic     | CFMX4-1                     | Notebook    | [761d21f21a](https://bsd-hardware.info/?probe=761d21f21a) | Dec 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [dce3ba8c99](https://bsd-hardware.info/?probe=dce3ba8c99) | Nov 18, 2020 |
| HP            | 213D A01                    | Desktop     | [ca6ab5347e](https://bsd-hardware.info/?probe=ca6ab5347e) | Nov 13, 2020 |
| Shuttle       | FH270                       | Desktop     | [0ba087730e](https://bsd-hardware.info/?probe=0ba087730e) | Oct 29, 2020 |
| Shuttle       | FH270                       | Desktop     | [532cda62a8](https://bsd-hardware.info/?probe=532cda62a8) | Oct 29, 2020 |
| Intel         | D53427RKE G87971-406        | Desktop     | [bb6eeb8ef8](https://bsd-hardware.info/?probe=bb6eeb8ef8) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [8f4b51dabd](https://bsd-hardware.info/?probe=8f4b51dabd) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [bb3d02abc3](https://bsd-hardware.info/?probe=bb3d02abc3) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [26d1d76748](https://bsd-hardware.info/?probe=26d1d76748) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [fb3b9ecee9](https://bsd-hardware.info/?probe=fb3b9ecee9) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [785c53f34c](https://bsd-hardware.info/?probe=785c53f34c) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [f5efac2cc7](https://bsd-hardware.info/?probe=f5efac2cc7) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [cc8f51b953](https://bsd-hardware.info/?probe=cc8f51b953) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [397aee2b27](https://bsd-hardware.info/?probe=397aee2b27) | Oct 29, 2020 |
| Intel         | S2600GZ G11481-352          | Server      | [474b0e44ea](https://bsd-hardware.info/?probe=474b0e44ea) | Oct 29, 2020 |
| Dell          | 0M332H A00                  | Server      | [9c70f76349](https://bsd-hardware.info/?probe=9c70f76349) | Oct 29, 2020 |
| Dell          | 072T6D A01                  | Server      | [4389b1ce81](https://bsd-hardware.info/?probe=4389b1ce81) | Oct 29, 2020 |
| Shuttle       | FH270                       | Desktop     | [25b278a2dc](https://bsd-hardware.info/?probe=25b278a2dc) | Oct 29, 2020 |
| Shuttle       | FH270                       | Desktop     | [e93928c59b](https://bsd-hardware.info/?probe=e93928c59b) | Oct 29, 2020 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [8d27c35122](https://bsd-hardware.info/?probe=8d27c35122) | Oct 29, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [2664153a6e](https://bsd-hardware.info/?probe=2664153a6e) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | Desktop     | [9d4ea8797b](https://bsd-hardware.info/?probe=9d4ea8797b) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | Desktop     | [5ae47d058d](https://bsd-hardware.info/?probe=5ae47d058d) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 23254S6       | Notebook    | [f4ac5ddaa4](https://bsd-hardware.info/?probe=f4ac5ddaa4) | Oct 25, 2020 |
| HP            | 635                         | Notebook    | [3b21406e87](https://bsd-hardware.info/?probe=3b21406e87) | Oct 23, 2020 |
| PC Engines    | apu1                        | Desktop     | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | Notebook    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [01d2c090de](https://bsd-hardware.info/?probe=01d2c090de) | Oct 03, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [4906f28cfc](https://bsd-hardware.info/?probe=4906f28cfc) | Aug 14, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [4dca0d2aa4](https://bsd-hardware.info/?probe=4dca0d2aa4) | Aug 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [82f64585b8](https://bsd-hardware.info/?probe=82f64585b8) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [8c92fcf25f](https://bsd-hardware.info/?probe=8c92fcf25f) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [b6a4e39a1b](https://bsd-hardware.info/?probe=b6a4e39a1b) | Aug 14, 2020 |
| Dell          | Latitude XT2                | Notebook    | [19456100cf](https://bsd-hardware.info/?probe=19456100cf) | Jul 16, 2020 |
| Dell          | Latitude XT2                | Notebook    | [160725773f](https://bsd-hardware.info/?probe=160725773f) | Jul 16, 2020 |
| Sony          | SVF1521K1EB                 | Notebook    | [fe29d4e002](https://bsd-hardware.info/?probe=fe29d4e002) | Jun 29, 2020 |
| ASRock        | N3150B-ITX                  | Desktop     | [2b9248155e](https://bsd-hardware.info/?probe=2b9248155e) | Jun 09, 2020 |
| ASUSTek       | N3150I-C                    | Desktop     | [3da71be3c9](https://bsd-hardware.info/?probe=3da71be3c9) | Jun 09, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [9ba8051e48](https://bsd-hardware.info/?probe=9ba8051e48) | Jun 09, 2020 |
| Dell          | Latitude E7240              | Notebook    | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OpenBSD 7.0          | 12        | 5.8%    |
| FreeBSD 12.1-p10     | 12        | 5.8%    |
| helloSystem 0.7.0    | 11        | 5.31%   |
| helloSystem 0.6.0    | 6         | 2.9%    |
| FreeBSD 12.2         | 6         | 2.9%    |
| OPNsense 22.1        | 5         | 2.42%   |
| OPNsense 21.7.3      | 5         | 2.42%   |
| OPNsense 21.1.6      | 5         | 2.42%   |
| helloSystem 0.5.0    | 5         | 2.42%   |
| FreeBSD 14.0-CURRENT | 5         | 2.42%   |
| FreeBSD 13.0-p5      | 5         | 2.42%   |
| OPNsense 22.1.8      | 4         | 1.93%   |
| OPNsense 21.7.7      | 4         | 1.93%   |
| OPNsense 21.1.2      | 4         | 1.93%   |
| OPNsense 21.1.1      | 4         | 1.93%   |
| OPNsense 21.1        | 4         | 1.93%   |
| OpenBSD 7.1          | 4         | 1.93%   |
| GhostBSD 20.04.02    | 4         | 1.93%   |
| FreeBSD 13.0-p4      | 4         | 1.93%   |
| FreeBSD 12.2-p2      | 4         | 1.93%   |
| FreeBSD 12.2-p10     | 4         | 1.93%   |
| FreeBSD 12.1         | 4         | 1.93%   |
| OPNsense 22.1.5      | 3         | 1.45%   |
| OPNsense 22.1.2      | 3         | 1.45%   |
| OPNsense 22.1.1      | 3         | 1.45%   |
| OPNsense 21.7.4      | 3         | 1.45%   |
| OPNsense 21.7.1      | 3         | 1.45%   |
| OPNsense 21.1.8      | 3         | 1.45%   |
| OPNsense 21.1.7      | 3         | 1.45%   |
| OPNsense 21.1.3      | 3         | 1.45%   |
| OpenBSD 6.8          | 3         | 1.45%   |
| helloSystem 0.4.0    | 3         | 1.45%   |
| FreeBSD 13.0         | 3         | 1.45%   |
| FreeBSD 12.1-p8      | 3         | 1.45%   |
| OPNsense 22.1.6      | 2         | 0.97%   |
| OPNsense 22.1.4      | 2         | 0.97%   |
| OPNsense 22.1.3      | 2         | 0.97%   |
| OPNsense 21.7.6      | 2         | 0.97%   |
| OPNsense 21.7.5      | 2         | 0.97%   |
| OPNsense 21.7.2      | 2         | 0.97%   |
| OPNsense 21.7        | 2         | 0.97%   |
| OpenBSD 6.9          | 2         | 0.97%   |
| helloSystem 0.8.0    | 2         | 0.97%   |
| FreeBSD 13.0-p2      | 2         | 0.97%   |
| FreeBSD 12.3-p2      | 2         | 0.97%   |
| FreeBSD 12.1-p13     | 2         | 0.97%   |
| XigmaNAS 12.2-p7     | 1         | 0.48%   |
| XigmaNAS 12.2-p6     | 1         | 0.48%   |
| OPNsense 22.7        | 1         | 0.48%   |
| OPNsense 22.1.9      | 1         | 0.48%   |
| OPNsense 22.1.7      | 1         | 0.48%   |
| OPNsense 22.1.10     | 1         | 0.48%   |
| OPNsense 21.7.8      | 1         | 0.48%   |
| OPNsense 21.1.9      | 1         | 0.48%   |
| OPNsense 21.1.4      | 1         | 0.48%   |
| OPNsense 20.7.4      | 1         | 0.48%   |
| NomadBSD 5806f915    | 1         | 0.48%   |
| NomadBSD 1.3.1       | 1         | 0.48%   |
| NetBSD 9.0_STABLE    | 1         | 0.48%   |
| GhostBSD 22.01.12    | 1         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 63        | 36.42%  |
| FreeBSD     | 58        | 33.53%  |
| helloSystem | 22        | 12.72%  |
| OpenBSD     | 19        | 10.98%  |
| GhostBSD    | 6         | 3.47%   |
| XigmaNAS    | 2         | 1.16%   |
| NomadBSD    | 2         | 1.16%   |
| NetBSD      | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 166       | 95.95%  |
| i386   | 3         | 1.73%   |
| arm64  | 2         | 1.16%   |
| macppc | 1         | 0.58%   |
| armv7  | 1         | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 99        | 56.57%  |
| helloDesktop  | 22        | 12.57%  |
| fvwm          | 16        | 9.14%   |
| XFCE          | 9         | 5.14%   |
| MATE          | 8         | 4.57%   |
| GNOME         | 6         | 3.43%   |
| openbox       | 4         | 2.29%   |
| TWM           | 3         | 1.71%   |
| KDE5          | 3         | 1.71%   |
| i3            | 3         | 1.71%   |
| xfwm          | 1         | 0.57%   |
| Enlightenment | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 102       | 58.62%  |
| X11     | 72        | 41.38%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 124       | 71.26%  |
| SLiM    | 31        | 17.82%  |
| LightDM | 8         | 4.6%    |
| SDDM    | 6         | 3.45%   |
| GDM     | 4         | 2.3%    |
| XDM     | 1         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 111       | 63.07%  |
| en_US   | 36        | 20.45%  |
| C       | 16        | 9.09%   |
| pl_PL   | 11        | 6.25%   |
| fr_FR   | 1         | 0.57%   |
| en_GB   | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 130       | 74.71%  |
| BIOS | 44        | 25.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 84        | 48.28%  |
| Ufs    | 65        | 37.36%  |
| Ffs    | 19        | 10.92%  |
| Cd9660 | 6         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 147       | 84.97%  |
| MBR     | 24        | 13.87%  |
| Unknown | 2         | 1.16%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 45        | 26.01%  |
| Lenovo                     | 22        | 12.72%  |
| ASUSTek Computer           | 13        | 7.51%   |
| Hewlett-Packard            | 12        | 6.94%   |
| Intel                      | 10        | 5.78%   |
| ASRock                     | 9         | 5.2%    |
| Unknown                    | 9         | 5.2%    |
| Gigabyte Technology        | 8         | 4.62%   |
| MSI                        | 7         | 4.05%   |
| Supermicro                 | 5         | 2.89%   |
| Fujitsu                    | 5         | 2.89%   |
| ZOTAC                      | 3         | 1.73%   |
| Shuttle                    | 3         | 1.73%   |
| Apple                      | 3         | 1.73%   |
| Acer                       | 3         | 1.73%   |
| PC Engines                 | 2         | 1.16%   |
| Wistron                    | 1         | 0.58%   |
| Toshiba                    | 1         | 0.58%   |
| Sony                       | 1         | 0.58%   |
| ShenZhen MinWin Technology | 1         | 0.58%   |
| Raspberry Pi Foundation    | 1         | 0.58%   |
| PC Specialist              | 1         | 0.58%   |
| Panasonic                  | 1         | 0.58%   |
| Notebook                   | 1         | 0.58%   |
| Inventec                   | 1         | 0.58%   |
| IBM                        | 1         | 0.58%   |
| Fujitsu Siemens            | 1         | 0.58%   |
| Essentiel B                | 1         | 0.58%   |
| ASRockRack                 | 1         | 0.58%   |
| AOpen                      | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Dell OEM-R 720xd                       | 11        | 6.36%   |
| Unknown                                | 10        | 5.78%   |
| HP t620 PLUS Quad Core TC              | 6         | 3.47%   |
| Lenovo ThinkPad X200 745969G           | 5         | 2.89%   |
| Dell Wyse 5070 Extended Thin Client    | 3         | 1.73%   |
| ASUS All Series                        | 3         | 1.73%   |
| ASRock Q1900B-ITX                      | 3         | 1.73%   |
| Intel SHARKBAY                         | 2         | 1.16%   |
| Intel Q3XXG4-P V1.0                    | 2         | 1.16%   |
| ZOTAC ZBOX-CI341                       | 1         | 0.58%   |
| ZOTAC ZBOX-CI329NANO                   | 1         | 0.58%   |
| ZOTAC ZBOX-CI323NANO                   | 1         | 0.58%   |
| Wistron ProLiant ML110 G5              | 1         | 0.58%   |
| Toshiba PORTEGE X20W-D                 | 1         | 0.58%   |
| Supermicro X7SLA                       | 1         | 0.58%   |
| Supermicro X7DCL                       | 1         | 0.58%   |
| Supermicro X11SSN-L                    | 1         | 0.58%   |
| Supermicro SYS-5018D-FN8T              | 1         | 0.58%   |
| Supermicro Super Server                | 1         | 0.58%   |
| Sony SVF1521K1EB                       | 1         | 0.58%   |
| Shuttle XH270                          | 1         | 0.58%   |
| Shuttle SZ270R9                        | 1         | 0.58%   |
| Shuttle SZ270                          | 1         | 0.58%   |
| ShenZhen MinWin MW-NANO-APL-4L         | 1         | 0.58%   |
| RPi Raspberry Pi 400                   | 1         | 0.58%   |
| PC Specialist Recoil II                | 1         | 0.58%   |
| PC Engines APU2                        | 1         | 0.58%   |
| PC Engines apu1                        | 1         | 0.58%   |
| Panasonic CFMX4-1                      | 1         | 0.58%   |
| Notebook N85_N87,HJ,HJ1,HK1            | 1         | 0.58%   |
| MSI MS-7D25                            | 1         | 0.58%   |
| MSI MS-7C52                            | 1         | 0.58%   |
| MSI MS-7B53                            | 1         | 0.58%   |
| MSI MS-7846                            | 1         | 0.58%   |
| MSI MS-7788                            | 1         | 0.58%   |
| MSI MS-7758                            | 1         | 0.58%   |
| MSI KBL-U Pro PRO24X (MS-AEC1)         | 1         | 0.58%   |
| Lenovo ThinkPad X230 23254S6           | 1         | 0.58%   |
| Lenovo ThinkPad X200s 7470A98          | 1         | 0.58%   |
| Lenovo ThinkPad W520 4284W5L           | 1         | 0.58%   |
| Lenovo ThinkPad T495 20NJ0010PB        | 1         | 0.58%   |
| Lenovo ThinkPad T480 20L6S4GR02        | 1         | 0.58%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01  | 1         | 0.58%   |
| Lenovo ThinkPad T440 20B7S1860W        | 1         | 0.58%   |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200  | 1         | 0.58%   |
| Lenovo ThinkCentre M93 10A2S01Q00      | 1         | 0.58%   |
| Lenovo ThinkCentre M91p 7033DE6        | 1         | 0.58%   |
| Lenovo ThinkCentre M700 10GS           | 1         | 0.58%   |
| Lenovo Legion Y540-15IRH-PG0 81SY      | 1         | 0.58%   |
| Lenovo IdeaPad S130-14IGM 81J2         | 1         | 0.58%   |
| Lenovo IdeaPad 520-15IKB 81BF          | 1         | 0.58%   |
| Lenovo G580 20150                      | 1         | 0.58%   |
| Lenovo G500s 20245                     | 1         | 0.58%   |
| Inventec Dell Thin Client Desktop 5060 | 1         | 0.58%   |
| Intel TERRA Server                     | 1         | 0.58%   |
| Intel SKYBAY                           | 1         | 0.58%   |
| Intel NUC6CAYS                         | 1         | 0.58%   |
| Intel D945GSEJT                        | 1         | 0.58%   |
| Intel D53427RKE G87971-406             | 1         | 0.58%   |
| Intel D2500HN AAG81480-500             | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 13        | 7.51%   |
| Dell OEM-R                     | 11        | 6.36%   |
| Unknown                        | 10        | 5.78%   |
| Dell Latitude                  | 9         | 5.2%    |
| Dell PowerEdge                 | 8         | 4.62%   |
| HP t620                        | 6         | 3.47%   |
| Dell OptiPlex                  | 6         | 3.47%   |
| Dell Wyse                      | 4         | 2.31%   |
| Lenovo ThinkCentre             | 3         | 1.73%   |
| Fujitsu FUTRO                  | 3         | 1.73%   |
| ASUS All                       | 3         | 1.73%   |
| ASRock Q1900B-ITX              | 3         | 1.73%   |
| Lenovo IdeaPad                 | 2         | 1.16%   |
| Intel SHARKBAY                 | 2         | 1.16%   |
| Intel Q3XXG4-P                 | 2         | 1.16%   |
| HP ProLiant                    | 2         | 1.16%   |
| Gigabyte B450M                 | 2         | 1.16%   |
| Dell Vostro                    | 2         | 1.16%   |
| Dell Inspiron                  | 2         | 1.16%   |
| Acer Aspire                    | 2         | 1.16%   |
| ZOTAC ZBOX-CI341               | 1         | 0.58%   |
| ZOTAC ZBOX-CI329NANO           | 1         | 0.58%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.58%   |
| Wistron ProLiant               | 1         | 0.58%   |
| Toshiba PORTEGE                | 1         | 0.58%   |
| Supermicro X7SLA               | 1         | 0.58%   |
| Supermicro X7DCL               | 1         | 0.58%   |
| Supermicro X11SSN-L            | 1         | 0.58%   |
| Supermicro SYS-5018D-FN8T      | 1         | 0.58%   |
| Supermicro Super               | 1         | 0.58%   |
| Sony SVF1521K1EB               | 1         | 0.58%   |
| Shuttle XH270                  | 1         | 0.58%   |
| Shuttle SZ270R9                | 1         | 0.58%   |
| Shuttle SZ270                  | 1         | 0.58%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.58%   |
| RPi Raspberry                  | 1         | 0.58%   |
| PC Specialist Recoil           | 1         | 0.58%   |
| PC Engines APU2                | 1         | 0.58%   |
| PC Engines apu1                | 1         | 0.58%   |
| Panasonic CFMX4-1              | 1         | 0.58%   |
| Notebook N85                   | 1         | 0.58%   |
| MSI MS-7D25                    | 1         | 0.58%   |
| MSI MS-7C52                    | 1         | 0.58%   |
| MSI MS-7B53                    | 1         | 0.58%   |
| MSI MS-7846                    | 1         | 0.58%   |
| MSI MS-7788                    | 1         | 0.58%   |
| MSI MS-7758                    | 1         | 0.58%   |
| MSI KBL-U                      | 1         | 0.58%   |
| Lenovo Legion                  | 1         | 0.58%   |
| Lenovo G580                    | 1         | 0.58%   |
| Lenovo G500s                   | 1         | 0.58%   |
| Inventec Dell                  | 1         | 0.58%   |
| Intel TERRA                    | 1         | 0.58%   |
| Intel SKYBAY                   | 1         | 0.58%   |
| Intel NUC6CAYS                 | 1         | 0.58%   |
| Intel D945GSEJT                | 1         | 0.58%   |
| Intel D53427RKE                | 1         | 0.58%   |
| Intel D2500HN                  | 1         | 0.58%   |
| IBM ThinkPad                   | 1         | 0.58%   |
| HP ENVY                        | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 33        | 19.08%  |
| 2019    | 19        | 10.98%  |
| 2018    | 16        | 9.25%   |
| 2020    | 13        | 7.51%   |
| 2016    | 13        | 7.51%   |
| 2012    | 13        | 7.51%   |
| 2021    | 12        | 6.94%   |
| 2009    | 11        | 6.36%   |
| 2013    | 9         | 5.2%    |
| 2011    | 8         | 4.62%   |
| 2017    | 7         | 4.05%   |
| 2015    | 6         | 3.47%   |
| 2010    | 3         | 1.73%   |
| 2006    | 3         | 1.73%   |
| 2008    | 2         | 1.16%   |
| 2007    | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |
| 2022    | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 87        | 50.29%  |
| Notebook    | 45        | 26.01%  |
| Server      | 26        | 15.03%  |
| Mini pc     | 10        | 5.78%   |
| All in one  | 4         | 2.31%   |
| Convertible | 1         | 0.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 170       | 98.27%  |
| Yes  | 3         | 1.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 29.14%  |
| 8.01-16.0   | 45        | 25.71%  |
| 16.01-24.0  | 39        | 22.29%  |
| 64.01-256.0 | 15        | 8.57%   |
| 32.01-64.0  | 9         | 5.14%   |
| 2.01-3.0    | 6         | 3.43%   |
| 3.01-4.0    | 5         | 2.86%   |
| 24.01-32.0  | 2         | 1.14%   |
| 0.51-1.0    | 2         | 1.14%   |
| 1.01-2.0    | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 94        | 52.51%  |
| 0.51-1.0    | 43        | 24.02%  |
| 1.01-2.0    | 24        | 13.41%  |
| 2.01-3.0    | 5         | 2.79%   |
| 4.01-8.0    | 4         | 2.23%   |
| 8.01-16.0   | 3         | 1.68%   |
| 0           | 2         | 1.12%   |
| 3.01-4.0    | 1         | 0.56%   |
| 64.01-256.0 | 1         | 0.56%   |
| 16.01-24.0  | 1         | 0.56%   |
| Unknown     | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 94        | 52.22%  |
| 2      | 40        | 22.22%  |
| 0      | 24        | 13.33%  |
| 3      | 8         | 4.44%   |
| 4      | 5         | 2.78%   |
| 6      | 4         | 2.22%   |
| 5      | 3         | 1.67%   |
| 9      | 1         | 0.56%   |
| 8      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 80.57%  |
| Yes       | 34        | 19.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 96.53%  |
| No        | 6         | 3.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 55.68%  |
| Yes       | 78        | 44.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 76.14%  |
| Yes       | 42        | 23.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 173       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 29        | 15.68%  |
| Krakow                    | 17        | 9.19%   |
| Gdansk                    | 16        | 8.65%   |
| Gdynia                    | 14        | 7.57%   |
| Wroclaw                   | 10        | 5.41%   |
| Poznan                    | 7         | 3.78%   |
| Miedziana Gora            | 4         | 2.16%   |
| Lodz                      | 3         | 1.62%   |
| Katowice                  | 3         | 1.62%   |
| Chrusty                   | 3         | 1.62%   |
| Е»ukowo                 | 2         | 1.08%   |
| Zgierz                    | 2         | 1.08%   |
| Glincz                    | 2         | 1.08%   |
| CzД™stochowa           | 2         | 1.08%   |
| ЕљwiД™tochЕ‚owice | 1         | 0.54%   |
| Zajaczki Pierwsze         | 1         | 0.54%   |
| Zagnansk                  | 1         | 0.54%   |
| WЕ‚ocЕ‚awek         | 1         | 0.54%   |
| Wschowa                   | 1         | 0.54%   |
| Wronowy                   | 1         | 0.54%   |
| Wolsztyn                  | 1         | 0.54%   |
| Wloszczowa                | 1         | 0.54%   |
| Wieliczka                 | 1         | 0.54%   |
| Walcz                     | 1         | 0.54%   |
| Tychy                     | 1         | 0.54%   |
| Szczytno                  | 1         | 0.54%   |
| Szczecin                  | 1         | 0.54%   |
| Świnoujście             | 1         | 0.54%   |
| Stopnica                  | 1         | 0.54%   |
| Stary Sacz                | 1         | 0.54%   |
| Starogard Gdański        | 1         | 0.54%   |
| Spalice                   | 1         | 0.54%   |
| Sosnowiec                 | 1         | 0.54%   |
| Siedlce                   | 1         | 0.54%   |
| RzeszГіw                | 1         | 0.54%   |
| RzeszÃ³w                | 1         | 0.54%   |
| Rybnik                    | 1         | 0.54%   |
| Radostowice               | 1         | 0.54%   |
| PruszkÃ³w               | 1         | 0.54%   |
| Pruszcz Gdanski           | 1         | 0.54%   |
| Prudnik                   | 1         | 0.54%   |
| Pobiedziska               | 1         | 0.54%   |
| Pilica                    | 1         | 0.54%   |
| Piastow                   | 1         | 0.54%   |
| Piaseczno                 | 1         | 0.54%   |
| Pacierzow                 | 1         | 0.54%   |
| OЕ›wiД™cim          | 1         | 0.54%   |
| Ostrzeszow                | 1         | 0.54%   |
| Mogilno                   | 1         | 0.54%   |
| Lubin                     | 1         | 0.54%   |
| Lubawa                    | 1         | 0.54%   |
| Loziska                   | 1         | 0.54%   |
| Lomianki                  | 1         | 0.54%   |
| Lipno                     | 1         | 0.54%   |
| Lipie                     | 1         | 0.54%   |
| Lezno                     | 1         | 0.54%   |
| Legnica                   | 1         | 0.54%   |
| Ledziny                   | 1         | 0.54%   |
| Lancut                    | 1         | 0.54%   |
| Krasnik                   | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 58     | 15.42%  |
| Samsung Electronics | 30        | 60     | 14.93%  |
| Seagate             | 20        | 41     | 9.95%   |
| Toshiba             | 12        | 28     | 5.97%   |
| SanDisk             | 12        | 14     | 5.97%   |
| Goodram             | 10        | 17     | 4.98%   |
| A-DATA Technology   | 8         | 9      | 3.98%   |
| Kingston            | 6         | 6      | 2.99%   |
| Crucial             | 6         | 11     | 2.99%   |
| Transcend           | 4         | 7      | 1.99%   |
| Hoodisk             | 4         | 5      | 1.99%   |
| Hitachi             | 4         | 4      | 1.99%   |
| SPCC                | 3         | 3      | 1.49%   |
| SK hynix            | 3         | 3      | 1.49%   |
| Plextor             | 3         | 3      | 1.49%   |
| NVMe                | 3         | 5      | 1.49%   |
| LITEON              | 3         | 3      | 1.49%   |
| Innodisk            | 3         | 4      | 1.49%   |
| HGST                | 3         | 5      | 1.49%   |
| Hewlett-Packard     | 3         | 3      | 1.49%   |
| Gigabyte Technology | 3         | 3      | 1.49%   |
| Corsair             | 3         | 3      | 1.49%   |
| PNY                 | 2         | 3      | 1%      |
| OCZ                 | 2         | 2      | 1%      |
| Micron Technology   | 2         | 8      | 1%      |
| Kston               | 2         | 2      | 1%      |
| Intenso             | 2         | 2      | 1%      |
| Intel               | 2         | 4      | 1%      |
| Apacer              | 2         | 2      | 1%      |
| Team                | 1         | 1      | 0.5%    |
| SSSTC               | 1         | 2      | 0.5%    |
| SSDPR-CX            | 1         | 1      | 0.5%    |
| Phison              | 1         | 1      | 0.5%    |
| Patriot             | 1         | 1      | 0.5%    |
| LITEONIT            | 1         | 1      | 0.5%    |
| KIOXIA              | 1         | 1      | 0.5%    |
| FORESEE             | 1         | 1      | 0.5%    |
| China               | 1         | 1      | 0.5%    |
| Apple               | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung HM321HI 320GB              | 5         | 2.24%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 1.35%   |
| Samsung SSD 850 EVO 250GB          | 3         | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.9%    |
| WDC WD20SDZW-11JJ8S0 2TB           | 2         | 0.9%    |
| WDC WD20NMVW-59EDZS7 2TB           | 2         | 0.9%    |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.9%    |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.9%    |
| Toshiba MQ04ABF100 1TB             | 2         | 0.9%    |
| SPCC Solid State Disk 256GB        | 2         | 0.9%    |
| Seagate ST2000DL003-9VT166 2TB     | 2         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.9%    |
| SanDisk SDSA6MM-016G-1006 16GB     | 2         | 0.9%    |
| Samsung SSD 860 EVO 250GB          | 2         | 0.9%    |
| Kingston SUV500MS120G 120GB        | 2         | 0.9%    |
| Intenso SSD SATAIII 120GB          | 2         | 0.9%    |
| Hoodisk SSD 128GB                  | 2         | 0.9%    |
| Goodram SSDPR-CX400-128 128GB      | 2         | 0.9%    |
| Goodram SSDPR-CL100-120-G3 120GB   | 2         | 0.9%    |
| Goodram SSDPR-CL100-120-G2 120GB   | 2         | 0.9%    |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.9%    |
| Corsair CMFSSD-256D1 256GB         | 2         | 0.9%    |
| A-DATA SU800 256GB                 | 2         | 0.9%    |
| WDC WD7500BPKT-22PK4T0 752GB       | 1         | 0.45%   |
| WDC WD5000LPVT-75G33T0 500GB       | 1         | 0.45%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.45%   |
| WDC WD5000BPVT-08HXZT3 500GB       | 1         | 0.45%   |
| WDC WD360ADFD-00NLR5 37GB          | 1         | 0.45%   |
| WDC WD360ADFD-00NLR1 37GB          | 1         | 0.45%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 0.45%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1         | 0.45%   |
| WDC WD3200AAVS-00ZTB0 320GB        | 1         | 0.45%   |
| WDC WD30EZRZ-00Z5HB0 3TB           | 1         | 0.45%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1         | 0.45%   |
| WDC WD2500AAKX-753CA0 250GB        | 1         | 0.45%   |
| WDC WD2500AAKX-083CA1 250GB        | 1         | 0.45%   |
| WDC WD2500AAKX-00ERMA0 250GB       | 1         | 0.45%   |
| WDC WD20SMZW-11YFCS0 2TB           | 1         | 0.45%   |
| WDC WD20SDRW-11VUUS0 2TB           | 1         | 0.45%   |
| WDC WD20PURZ-85GU6Y0 2TB           | 1         | 0.45%   |
| WDC WD20EURS-63S48Y0 2TB           | 1         | 0.45%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 0.45%   |
| WDC WD1600BEVE-00UYT0 160GB        | 1         | 0.45%   |
| WDC WD1600AAJS-40H3A0 160GB        | 1         | 0.45%   |
| WDC WD1200BEVS-07RST0 120GB        | 1         | 0.45%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 0.45%   |
| WDC WD10JQLX-22JFGT0 1TB           | 1         | 0.45%   |
| WDC WD10EURX-73C57Y0 1TB           | 1         | 0.45%   |
| WDC WD10EFRX-68FYTN0 1TB           | 1         | 0.45%   |
| WDC WD10EARS-003BB1 1TB            | 1         | 0.45%   |
| WDC WD101KFBX-68R56N0 10TB         | 1         | 0.45%   |
| WDC PC SN530 NVMe 512GB            | 1         | 0.45%   |
| Transcend TS64GMTS400S 64GB        | 1         | 0.45%   |
| Transcend TS32GMSA370 32GB         | 1         | 0.45%   |
| Transcend TS128GMSA370 128GB       | 1         | 0.45%   |
| Transcend TS120GMTS420S 120GB      | 1         | 0.45%   |
| Toshiba THNSNK512GVN8 512GB        | 1         | 0.45%   |
| Toshiba MQ01ACF032 320GB           | 1         | 0.45%   |
| Toshiba MQ01ABD100H 1TB            | 1         | 0.45%   |
| Toshiba MQ01ABD032 320GB           | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 48     | 34.57%  |
| Seagate             | 20        | 41     | 24.69%  |
| Toshiba             | 10        | 26     | 12.35%  |
| Samsung Electronics | 10        | 16     | 12.35%  |
| Hitachi             | 4         | 4      | 4.94%   |
| HGST                | 3         | 5      | 3.7%    |
| NVMe                | 2         | 2      | 2.47%   |
| Hewlett-Packard     | 2         | 2      | 2.47%   |
| SSDPR-CX            | 1         | 1      | 1.23%   |
| Apple               | 1         | 1      | 1.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 38     | 16.35%  |
| SanDisk             | 12        | 14     | 11.54%  |
| Goodram             | 9         | 16     | 8.65%   |
| Kingston            | 6         | 6      | 5.77%   |
| Crucial             | 5         | 10     | 4.81%   |
| A-DATA Technology   | 5         | 5      | 4.81%   |
| Transcend           | 4         | 7      | 3.85%   |
| Hoodisk             | 4         | 5      | 3.85%   |
| SPCC                | 3         | 3      | 2.88%   |
| Plextor             | 3         | 3      | 2.88%   |
| Innodisk            | 3         | 4      | 2.88%   |
| Gigabyte Technology | 3         | 3      | 2.88%   |
| Corsair             | 3         | 3      | 2.88%   |
| WDC                 | 2         | 9      | 1.92%   |
| SK hynix            | 2         | 2      | 1.92%   |
| OCZ                 | 2         | 2      | 1.92%   |
| Micron Technology   | 2         | 8      | 1.92%   |
| LITEON              | 2         | 2      | 1.92%   |
| Kston               | 2         | 2      | 1.92%   |
| Intenso             | 2         | 2      | 1.92%   |
| Intel               | 2         | 4      | 1.92%   |
| Apacer              | 2         | 2      | 1.92%   |
| Toshiba             | 1         | 1      | 0.96%   |
| Team                | 1         | 1      | 0.96%   |
| Phison              | 1         | 1      | 0.96%   |
| Patriot             | 1         | 1      | 0.96%   |
| NVMe                | 1         | 1      | 0.96%   |
| LITEONIT            | 1         | 1      | 0.96%   |
| Hewlett-Packard     | 1         | 1      | 0.96%   |
| FORESEE             | 1         | 1      | 0.96%   |
| China               | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 92        | 159    | 53.49%  |
| HDD  | 63        | 146    | 36.63%  |
| NVMe | 17        | 24     | 9.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135       | 305    | 88.82%  |
| NVMe | 17        | 24     | 11.18%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 190    | 68.71%  |
| 0.51-1.0   | 28        | 50     | 17.18%  |
| 1.01-2.0   | 14        | 35     | 8.59%   |
| 3.01-4.0   | 3         | 8      | 1.84%   |
| 2.01-3.0   | 3         | 13     | 1.84%   |
| 4.01-10.0  | 3         | 9      | 1.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 32.61%  |
| 1-20           | 31        | 16.85%  |
| 51-100         | 31        | 16.85%  |
| 251-500        | 28        | 15.22%  |
| 21-50          | 18        | 9.78%   |
| 501-1000       | 9         | 4.89%   |
| 1001-2000      | 3         | 1.63%   |
| More than 3000 | 2         | 1.09%   |
| 2001-3000      | 2         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 159       | 89.33%  |
| 21-50     | 9         | 5.06%   |
| 101-250   | 5         | 2.81%   |
| 51-100    | 3         | 1.69%   |
| 1001-2000 | 2         | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                    | 2         | 2      | 7.41%   |
| WDC WD360ADFD-00NLR1 37GB                 | 1         | 1      | 3.7%    |
| WDC WD3200AAVS-00ZTB0 320GB               | 1         | 1      | 3.7%    |
| WDC WD2500AAKX-753CA0 250GB               | 1         | 1      | 3.7%    |
| WDC WD2500AAKX-083CA1 250GB               | 1         | 2      | 3.7%    |
| WDC WD20EURS-63S48Y0 2TB                  | 1         | 1      | 3.7%    |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 3.7%    |
| WDC WD1600BEVE-00UYT0 160GB               | 1         | 1      | 3.7%    |
| WDC WD1600AAJS-40H3A0 160GB               | 1         | 1      | 3.7%    |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1      | 3.7%    |
| WDC WD10EARS-003BB1 1TB                   | 1         | 1      | 3.7%    |
| Toshiba THNSNK512GVN8 512GB               | 1         | 1      | 3.7%    |
| Toshiba MK3261GSYN 320GB                  | 1         | 1      | 3.7%    |
| SPCC Solid State Disk 256GB               | 1         | 1      | 3.7%    |
| SK hynix SC308 SATA 256GB                 | 1         | 1      | 3.7%    |
| Seagate ST96812AS 64GB                    | 1         | 4      | 3.7%    |
| Seagate ST9500420AS 500GB                 | 1         | 2      | 3.7%    |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.7%    |
| Seagate ST32000542AS 2TB                  | 1         | 1      | 3.7%    |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 3.7%    |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 3.7%    |
| Samsung Electronics HD154UI 1.5TB         | 1         | 1      | 3.7%    |
| Plextor PX-128G7Ne 128GB                  | 1         | 1      | 3.7%    |
| Micron Technology MTFDDAT128MAM-1J2 128GB | 1         | 1      | 3.7%    |
| Hitachi HTS721060G9SA00 64GB              | 1         | 1      | 3.7%    |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 37.04%  |
| Seagate             | 5         | 9      | 18.52%  |
| Toshiba             | 4         | 4      | 14.81%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Hitachi             | 2         | 2      | 7.41%   |
| SPCC                | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| Plextor             | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 47.62%  |
| Seagate             | 5         | 9      | 23.81%  |
| Toshiba             | 3         | 3      | 14.29%  |
| Hitachi             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 26     | 76.92%  |
| SSD  | 6         | 6      | 23.08%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 134       | 286    | 79.76%  |
| Malfunc  | 25        | 32     | 14.88%  |
| Detected | 8         | 10     | 4.76%   |
| Failed   | 1         | 1      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 122       | 61.93%  |
| AMD                            | 25        | 12.69%  |
| Broadcom / LSI                 | 20        | 10.15%  |
| Samsung Electronics            | 5         | 2.54%   |
| SanDisk                        | 3         | 1.52%   |
| Silicon Motion                 | 2         | 1.02%   |
| Phison Electronics             | 2         | 1.02%   |
| Nvidia                         | 2         | 1.02%   |
| KIOXIA                         | 2         | 1.02%   |
| Hewlett-Packard                | 2         | 1.02%   |
| VIA Technologies               | 1         | 0.51%   |
| Solid State Storage Technology | 1         | 0.51%   |
| SK hynix                       | 1         | 0.51%   |
| Realtek Semiconductor          | 1         | 0.51%   |
| Micron/Crucial Technology      | 1         | 0.51%   |
| Marvell Technology Group       | 1         | 0.51%   |
| Lite-On Technology             | 1         | 0.51%   |
| JMicron Technology             | 1         | 0.51%   |
| Integrated Technology Express  | 1         | 0.51%   |
| ASMedia Technology             | 1         | 0.51%   |
| Apple                          | 1         | 0.51%   |
| ADATA Technology               | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 7.87%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 11        | 5.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 4.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 3.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 3.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 1.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 3         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.39%   |
| Unknown                                                                          | 3         | 1.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.93%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2         | 0.93%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 0.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 2         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.93%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 2         | 0.93%   |
| Broadcom / LSI MegaRAID SAS 2008 [Falcon]                                        | 2         | 0.93%   |
| Broadcom / LSI MegaRAID SAS 1078                                                 | 2         | 0.93%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.46%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.46%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.46%   |
| SanDisk unknown                                                                  | 1         | 0.46%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.46%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.46%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.46%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.46%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.46%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.46%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 0.46%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.46%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.46%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.46%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1         | 0.46%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 128       | 64.65%  |
| RAID | 23        | 11.62%  |
| IDE  | 23        | 11.62%  |
| NVMe | 20        | 10.1%   |
| SAS  | 2         | 1.01%   |
| SCSI | 2         | 1.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 141       | 81.5%   |
| AMD     | 28        | 16.18%  |
| ARM     | 3         | 1.73%   |
| PowerPC | 1         | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz      | 11        | 6.32%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 6         | 3.45%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 5         | 2.87%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 3         | 1.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 1.72%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 3         | 1.72%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 3         | 1.72%   |
| Intel Pentium CPU G860 @ 3.00GHz         | 2         | 1.15%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 2         | 1.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 1.15%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 2         | 1.15%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 2         | 1.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 2         | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.15%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 2         | 1.15%   |
| Intel Core 2 Duo                         | 2         | 1.15%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 2         | 1.15%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 2         | 1.15%   |
| ARM Cortex-A72 r0p3                      | 2         | 1.15%   |
| AMD Ryzen 3 3100 4-Core Processor        | 2         | 1.15%   |
| PowerPC 7447A (Revision 0x102)           | 1         | 0.57%   |
| Intel Xeon E-2386G CPU @ 3.50GHz         | 1         | 0.57%   |
| Intel Xeon CPU X5660 @ 2.80GHz           | 1         | 0.57%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.57%   |
| Intel Xeon CPU X3360 @ 2.83GHz           | 1         | 0.57%   |
| Intel Xeon CPU E5520 @ 2.27GHz           | 1         | 0.57%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.57%   |
| Intel Xeon CPU E5410 @ 2.33GHz           | 1         | 0.57%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz      | 1         | 0.57%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz       | 1         | 0.57%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz      | 1         | 0.57%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.57%   |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz      | 1         | 0.57%   |
| Intel Xeon CPU E31225 @ 3.10GH           | 1         | 0.57%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1         | 0.57%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1         | 0.57%   |
| Intel Xeon                               | 1         | 0.57%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 0.57%   |
| Intel Pentium M processor                | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU E6           | 1         | 0.57%   |
| Intel Pentium CPU J4205 @ 1.50GHz        | 1         | 0.57%   |
| Intel Pentium CPU G620 @ 2.60GHz         | 1         | 0.57%   |
| Intel Pentium CPU G4400 @ 3.30GHz        | 1         | 0.57%   |
| Intel Pentium CPU G3250 @ 3.20GHz        | 1         | 0.57%   |
| Intel Pentium CPU G3220 @ 3.00GHz        | 1         | 0.57%   |
| Intel Pentium CPU 4415U @ 2.30GHz        | 1         | 0.57%   |
| Intel Core i7-9750HF CPU @ 2.60GHz       | 1         | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 1         | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 0.57%   |
| Intel Core i7-6700T CPU @ 2.80GHz        | 1         | 0.57%   |
| Intel Core i7-5550U CPU @ 2.00GHz        | 1         | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 1         | 0.57%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 1         | 0.57%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 0.57%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 1         | 0.57%   |
| Intel Core i7-3610QM CPU @ 2.30GHz       | 1         | 0.57%   |
| Intel Core i7-2820QM CPU @ 2.30GHz       | 1         | 0.57%   |
| Intel Core i7-10610U CPU @ 1.80GHz       | 1         | 0.57%   |
| Intel Core i5-9400F CPU @ 2.90GHz        | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 22.99%  |
| Intel Xeon              | 27        | 15.52%  |
| Intel Celeron           | 17        | 9.77%   |
| Intel Core i7           | 13        | 7.47%   |
| Intel Core i3           | 13        | 7.47%   |
| AMD GX                  | 10        | 5.75%   |
| Intel Core 2 Duo        | 9         | 5.17%   |
| Intel Pentium           | 8         | 4.6%    |
| Other                   | 4         | 2.3%    |
| Intel Pentium Silver    | 4         | 2.3%    |
| Intel Atom              | 4         | 2.3%    |
| ARM Cortex              | 3         | 1.72%   |
| AMD Ryzen 5             | 3         | 1.72%   |
| AMD Ryzen 3             | 2         | 1.15%   |
| AMD G                   | 2         | 1.15%   |
| AMD E                   | 2         | 1.15%   |
| Intel Pentium M         | 1         | 0.57%   |
| Intel Pentium Dual-Core | 1         | 0.57%   |
| Intel Core 2            | 1         | 0.57%   |
| Intel Celeron M         | 1         | 0.57%   |
| AMD Ryzen 9             | 1         | 0.57%   |
| AMD Ryzen 7 PRO         | 1         | 0.57%   |
| AMD Ryzen 7             | 1         | 0.57%   |
| AMD Ryzen 5 PRO         | 1         | 0.57%   |
| AMD Phenom II X6        | 1         | 0.57%   |
| AMD Phenom II X4        | 1         | 0.57%   |
| AMD Athlon 64 X2        | 1         | 0.57%   |
| AMD Athlon              | 1         | 0.57%   |
| AMD A4                  | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 67        | 38.51%  |
| 2       | 53        | 30.46%  |
| Unknown | 15        | 8.62%   |
| 16      | 13        | 7.47%   |
| 8       | 7         | 4.02%   |
| 12      | 6         | 3.45%   |
| 6       | 6         | 3.45%   |
| 1       | 5         | 2.87%   |
| 24      | 1         | 0.57%   |
| 20      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 141       | 81.5%   |
| 2       | 21        | 12.14%  |
| Unknown | 11        | 6.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 78        | 44.83%  |
| 2       | 77        | 44.25%  |
| Unknown | 19        | 10.92%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 25        | 14.37%  |
| KabyLake      | 18        | 10.34%  |
| Haswell       | 17        | 9.77%   |
| Penryn        | 15        | 8.62%   |
| SandyBridge   | 14        | 8.05%   |
| Jaguar        | 10        | 5.75%   |
| Skylake       | 9         | 5.17%   |
| Goldmont plus | 9         | 5.17%   |
| Silvermont    | 8         | 4.6%    |
| Unknown       | 7         | 4.02%   |
| Westmere      | 4         | 2.3%    |
| Goldmont      | 4         | 2.3%    |
| Broadwell     | 4         | 2.3%    |
| Bobcat        | 4         | 2.3%    |
| Zen 2         | 3         | 1.72%   |
| Bonnell       | 3         | 1.72%   |
| Zen+          | 2         | 1.15%   |
| Zen 3         | 2         | 1.15%   |
| Zen           | 2         | 1.15%   |
| Puma          | 2         | 1.15%   |
| P6            | 2         | 1.15%   |
| Nehalem       | 2         | 1.15%   |
| K10           | 2         | 1.15%   |
| CometLake     | 2         | 1.15%   |
| TigerLake     | 1         | 0.57%   |
| NetBurst      | 1         | 0.57%   |
| K8 Hammer     | 1         | 0.57%   |
| Core          | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 103       | 55.38%  |
| AMD                                          | 34        | 18.28%  |
| Nvidia                                       | 24        | 12.9%   |
| Matrox Electronics Systems                   | 20        | 10.75%  |
| ASPEED Technology                            | 3         | 1.61%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.54%   |
| VIA Technologies                             | 1         | 0.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems G200eR2                                                       | 14        | 7.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 3.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.74%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 6         | 3.21%   |
| Intel HD Graphics 530                                                                    | 5         | 2.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 2.67%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 2.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.14%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 1.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.6%    |
| Intel HD Graphics 630                                                                    | 3         | 1.6%    |
| Intel HD Graphics 620                                                                    | 3         | 1.6%    |
| Intel HD Graphics 500                                                                    | 3         | 1.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.6%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 1.6%    |
| AMD ES1000                                                                               | 3         | 1.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.07%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.07%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 1.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.07%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 1.07%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.07%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.07%   |
| AMD Cezanne                                                                              | 2         | 1.07%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1         | 0.53%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.53%   |
| Nvidia GM206GL [Quadro M2000]                                                            | 1         | 0.53%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.53%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.53%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.53%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.53%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.53%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.53%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 0.53%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.53%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1         | 0.53%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.53%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 1         | 0.53%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1         | 0.53%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 0.53%   |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1         | 0.53%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 0.53%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.53%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 44%     |
| 1 x AMD        | 30        | 17.14%  |
| 1 x Matrox     | 20        | 11.43%  |
| Intel + Nvidia | 13        | 7.43%   |
| 1 x Nvidia     | 12        | 6.86%   |
| 2 x Intel      | 10        | 5.71%   |
| Other          | 5         | 2.86%   |
| Intel + AMD    | 3         | 1.71%   |
| 1 x ASPEED     | 2         | 1.14%   |
| 1 x XGI        | 1         | 0.57%   |
| 1 x VIA        | 1         | 0.57%   |
| AMD + ASPEED   | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 154       | 88.51%  |
| Proprietary | 10        | 5.75%   |
| Unknown     | 10        | 5.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 88.51%  |
| 1.01-2.0   | 6         | 3.45%   |
| 3.01-4.0   | 5         | 2.87%   |
| 7.01-8.0   | 3         | 1.72%   |
| 0.01-0.5   | 3         | 1.72%   |
| 0.51-1.0   | 2         | 1.15%   |
| 5.01-6.0   | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 18.31%  |
| Lenovo                  | 7         | 9.86%   |
| BOE                     | 6         | 8.45%   |
| NEC Computers           | 5         | 7.04%   |
| Samsung Electronics     | 4         | 5.63%   |
| Dell                    | 4         | 5.63%   |
| Acer                    | 4         | 5.63%   |
| Chimei Innolux          | 3         | 4.23%   |
| AU Optronics            | 3         | 4.23%   |
| Philips                 | 2         | 2.82%   |
| Iiyama                  | 2         | 2.82%   |
| Goldstar                | 2         | 2.82%   |
| Chi Mei Optoelectronics | 2         | 2.82%   |
| Apple                   | 2         | 2.82%   |
| Vestel Elektronik       | 1         | 1.41%   |
| Toshiba                 | 1         | 1.41%   |
| Sharp                   | 1         | 1.41%   |
| PANDA                   | 1         | 1.41%   |
| KTC                     | 1         | 1.41%   |
| JDI                     | 1         | 1.41%   |
| InfoVision              | 1         | 1.41%   |
| HPN                     | 1         | 1.41%   |
| Hewlett-Packard         | 1         | 1.41%   |
| Eizo                    | 1         | 1.41%   |
| BenQ                    | 1         | 1.41%   |
| AOC                     | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 5         | 7.04%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 2.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 2.82%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 1         | 1.41%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                        | 1         | 1.41%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                  | 1         | 1.41%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch    | 1         | 1.41%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 1.41%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch                | 1         | 1.41%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 1.41%   |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch               | 1         | 1.41%   |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch            | 1         | 1.41%   |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch             | 1         | 1.41%   |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch              | 1         | 1.41%   |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch                 | 1         | 1.41%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.41%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 1.41%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.41%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 1         | 1.41%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.41%   |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 1.41%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.41%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                  | 1         | 1.41%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 1.41%   |
| HPN LCD Monitor HP E233 1920x1080                                        | 1         | 1.41%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch                | 1         | 1.41%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 1         | 1.41%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                      | 1         | 1.41%   |
| Eizo EV2455 ENC2533 1920x1200 520x330mm 24.2-inch                        | 1         | 1.41%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                        | 1         | 1.41%   |
| Dell U2212HM DELD047 1920x1080 480x270mm 21.7-inch                       | 1         | 1.41%   |
| Dell P2312H DEL4076 1920x1080 510x290mm 23.1-inch                        | 1         | 1.41%   |
| Dell LCD Monitor DEL9408 1920x1080 520x290mm 23.4-inch                   | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 340x190mm 15.3-inch          | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.41%   |
| BOE LCD Monitor BOE092A 1920x1080 340x190mm 15.3-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE07BB 1920x1080 310x170mm 13.9-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE06FB 1920x1080 340x190mm 15.3-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE06C6 1920x1080 340x190mm 15.3-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE06BB 1920x1080 310x170mm 13.9-inch                    | 1         | 1.41%   |
| BOE LCD Monitor BOE0653 1920x1080 310x170mm 13.9-inch                    | 1         | 1.41%   |
| BenQ RL2455 BNQ7F1C 1920x1080 530x300mm 24.0-inch                        | 1         | 1.41%   |
| AU Optronics LCD Monitor AUOA114 1280x800 260x160mm 12.0-inch            | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO463D 1920x1080 310x170mm 13.9-inch           | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 1         | 1.41%   |
| Apple iMac APPAE05 3840x2160 600x340mm 27.2-inch                         | 1         | 1.41%   |
| Apple Color LCD APP9C93 1680x1050 430x270mm 20.0-inch                    | 1         | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 40.58%  |
| 1366x768 (WXGA)    | 16        | 23.19%  |
| 1280x800 (WXGA)    | 7         | 10.14%  |
| 3840x2160 (4K)     | 3         | 4.35%   |
| 1680x1050 (WSXGA+) | 3         | 4.35%   |
| 1600x900 (HD+)     | 3         | 4.35%   |
| 2560x1440 (QHD)    | 2         | 2.9%    |
| 1920x540           | 2         | 2.9%    |
| 1920x1200 (WUXGA)  | 2         | 2.9%    |
| 2560x1080          | 1         | 1.45%   |
| 1440x900 (WXGA+)   | 1         | 1.45%   |
| 1280x1024 (SXGA)   | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 24.29%  |
| 12      | 11        | 15.71%  |
| 13      | 10        | 14.29%  |
| 24      | 5         | 7.14%   |
| 23      | 5         | 7.14%   |
| 21      | 4         | 5.71%   |
| 27      | 3         | 4.29%   |
| 18      | 3         | 4.29%   |
| 42      | 2         | 2.86%   |
| 17      | 2         | 2.86%   |
| 50      | 1         | 1.43%   |
| 40      | 1         | 1.43%   |
| 31      | 1         | 1.43%   |
| 28      | 1         | 1.43%   |
| 22      | 1         | 1.43%   |
| 20      | 1         | 1.43%   |
| 14      | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 39.13%  |
| 501-600     | 12        | 17.39%  |
| 201-300     | 12        | 17.39%  |
| 401-500     | 9         | 13.04%  |
| 601-700     | 2         | 2.9%    |
| 351-400     | 2         | 2.9%    |
| 901-1000    | 2         | 2.9%    |
| 801-900     | 1         | 1.45%   |
| 1001-1500   | 1         | 1.45%   |
| Unknown     | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 49        | 74.24%  |
| 16/10   | 12        | 18.18%  |
| 3/2     | 2         | 3.03%   |
| 5/4     | 1         | 1.52%   |
| 21/9    | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 12        | 17.14%  |
| 91-100         | 12        | 17.14%  |
| 81-90          | 11        | 15.71%  |
| 61-70          | 11        | 15.71%  |
| 101-110        | 5         | 7.14%   |
| 251-300        | 4         | 5.71%   |
| 301-350        | 3         | 4.29%   |
| 141-150        | 3         | 4.29%   |
| 501-1000       | 3         | 4.29%   |
| 151-200        | 2         | 2.86%   |
| More than 1000 | 1         | 1.43%   |
| 351-500        | 1         | 1.43%   |
| 121-130        | 1         | 1.43%   |
| Unknown        | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 26        | 38.81%  |
| 51-100  | 21        | 31.34%  |
| 101-120 | 13        | 19.4%   |
| 161-240 | 4         | 5.97%   |
| 1-50    | 2         | 2.99%   |
| Unknown | 1         | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 110       | 62.86%  |
| 1     | 58        | 33.14%  |
| 2     | 7         | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 109       | 41.13%  |
| Realtek Semiconductor             | 77        | 29.06%  |
| Broadcom                          | 35        | 13.21%  |
| Qualcomm Atheros                  | 19        | 7.17%   |
| Qualcomm Atheros Communications   | 5         | 1.89%   |
| Emulex                            | 2         | 0.75%   |
| Dell                              | 2         | 0.75%   |
| Xiaomi                            | 1         | 0.38%   |
| VIA Technologies                  | 1         | 0.38%   |
| Van Ooijen Technische Informatica | 1         | 0.38%   |
| U-Blox                            | 1         | 0.38%   |
| TP-Link                           | 1         | 0.38%   |
| Sierra Wireless                   | 1         | 0.38%   |
| Ralink Technology                 | 1         | 0.38%   |
| Nvidia                            | 1         | 0.38%   |
| NetGear                           | 1         | 0.38%   |
| Mellanox Technologies             | 1         | 0.38%   |
| IMC Networks                      | 1         | 0.38%   |
| Huawei Technologies               | 1         | 0.38%   |
| D-Link System                     | 1         | 0.38%   |
| Atheros                           | 1         | 0.38%   |
| Apple                             | 1         | 0.38%   |
| American Megatrends               | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 69        | 21.97%  |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 14        | 4.46%   |
| Intel I350 Gigabit Network Connection                                         | 12        | 3.82%   |
| Intel I211 Gigabit Network Connection                                         | 11        | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10        | 3.18%   |
| Intel I210 Gigabit Network Connection                                         | 9         | 2.87%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 2.55%   |
| Intel 82567LM Gigabit Network Connection                                      | 7         | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 1.59%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 1.27%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4         | 1.27%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 0.96%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 3         | 0.96%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 0.96%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 0.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.64%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 0.64%   |
| Intel Wireless 8260                                                           | 2         | 0.64%   |
| Intel Wireless 7260                                                           | 2         | 0.64%   |
| Intel Ethernet Controller X550                                                | 2         | 0.64%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 0.64%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.64%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 0.64%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 2         | 0.64%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 2         | 0.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.32%   |
| Van Ooijen Technische Informatica CDC-ACM class devices (modems)              | 1         | 0.32%   |
| U-Blox [u-blox 7]                                                             | 1         | 0.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.32%   |
| Sierra Wireless EM7305 Modem                                                  | 1         | 0.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.32%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.32%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1         | 0.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.32%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.32%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1         | 0.32%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 51.16%  |
| Qualcomm Atheros                | 15        | 17.44%  |
| Broadcom                        | 9         | 10.47%  |
| Realtek Semiconductor           | 5         | 5.81%   |
| Qualcomm Atheros Communications | 5         | 5.81%   |
| Dell                            | 2         | 2.33%   |
| TP-Link                         | 1         | 1.16%   |
| Ralink Technology               | 1         | 1.16%   |
| NetGear                         | 1         | 1.16%   |
| IMC Networks                    | 1         | 1.16%   |
| D-Link System                   | 1         | 1.16%   |
| Atheros                         | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 5.81%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 5.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 5.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4         | 4.65%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 3.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 3.49%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 3.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 3         | 3.49%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 2.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 2.33%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.33%   |
| Intel Wireless 8260                                                           | 2         | 2.33%   |
| Intel Wireless 7260                                                           | 2         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.16%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.16%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1         | 1.16%   |
| Intel Wireless-AC 9260                                                        | 1         | 1.16%   |
| Intel Wireless 7265                                                           | 1         | 1.16%   |
| Intel Wireless 3165                                                           | 1         | 1.16%   |
| Intel Wireless 3160                                                           | 1         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.16%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.16%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.16%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.16%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.16%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.16%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 1.16%   |
| Intel Centrino Advanced-N 6200                                                | 1         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 1.16%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1         | 1.16%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1         | 1.16%   |
| Dell Dell Wireless 5560 Single-mode HSPA Mini Card with A-GPS                 | 1         | 1.16%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                       | 1         | 1.16%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1         | 1.16%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.16%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.16%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 1.16%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]          | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 89        | 44.28%  |
| Realtek Semiconductor | 74        | 36.82%  |
| Broadcom              | 27        | 13.43%  |
| Qualcomm Atheros      | 4         | 1.99%   |
| Emulex                | 2         | 1%      |
| Xiaomi                | 1         | 0.5%    |
| VIA Technologies      | 1         | 0.5%    |
| Nvidia                | 1         | 0.5%    |
| Apple                 | 1         | 0.5%    |
| American Megatrends   | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 69        | 31.08%  |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 14        | 6.31%   |
| Intel I350 Gigabit Network Connection                                         | 12        | 5.41%   |
| Intel I211 Gigabit Network Connection                                         | 11        | 4.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10        | 4.5%    |
| Intel I210 Gigabit Network Connection                                         | 9         | 4.05%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 3.6%    |
| Intel 82567LM Gigabit Network Connection                                      | 7         | 3.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 1.8%    |
| Intel 82574L Gigabit Network Connection                                       | 4         | 1.8%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 1.8%    |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 1.35%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.9%    |
| Intel Ethernet Controller X550                                                | 2         | 0.9%    |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.9%    |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.9%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 0.9%    |
| Emulex OneConnect 10Gb NIC (be3)                                              | 2         | 0.9%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 2         | 0.9%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.45%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.45%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1         | 0.45%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.45%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 1         | 0.45%   |
| Intel Ethernet Connection I217-V                                              | 1         | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.45%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.45%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.45%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 0.45%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.45%   |
| Intel 82583V Gigabit Network Connection                                       | 1         | 0.45%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.45%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.45%   |
| Intel 82575GB Gigabit Network Connection                                      | 1         | 0.45%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.45%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1         | 0.45%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.45%   |
| Intel 82546GB Gigabit Ethernet Controller                                     | 1         | 0.45%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1         | 0.45%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 0.45%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 0.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.45%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 0.45%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 0.45%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1         | 0.45%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 167       | 66.53%  |
| WiFi     | 78        | 31.08%  |
| Modem    | 3         | 1.2%    |
| Unknown  | 3         | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 149       | 73.76%  |
| WiFi     | 53        | 26.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 69        | 39.43%  |
| 1     | 38        | 21.71%  |
| 4     | 24        | 13.71%  |
| 3     | 17        | 9.71%   |
| 6     | 15        | 8.57%   |
| 5     | 7         | 4%      |
| 0     | 3         | 1.71%   |
| 14    | 1         | 0.57%   |
| 8     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 98.3%   |
| Yes  | 3         | 1.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 57.14%  |
| IMC Networks                    | 3         | 7.14%   |
| Broadcom                        | 3         | 7.14%   |
| Qualcomm Atheros Communications | 2         | 4.76%   |
| Foxconn / Hon Hai               | 2         | 4.76%   |
| ASUSTek Computer                | 2         | 4.76%   |
| Apple                           | 2         | 4.76%   |
| Qcom                            | 1         | 2.38%   |
| Hewlett-Packard                 | 1         | 2.38%   |
| Dell                            | 1         | 2.38%   |
| Cambridge Silicon Radio         | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 6         | 14.29%  |
| Intel AX201 Bluetooth                                  | 6         | 14.29%  |
| Intel Bluetooth wireless interface                     | 5         | 11.9%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]     | 3         | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                       | 2         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 2         | 4.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter       | 2         | 4.76%   |
| Apple Apple Broadcom Built-in Bluetooth                | 2         | 4.76%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                | 1         | 2.38%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device   | 1         | 2.38%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device     | 1         | 2.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1         | 2.38%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 2.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 2.38%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 2.38%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter             | 1         | 2.38%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth          | 1         | 2.38%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 2.38%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 2.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 1         | 2.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 1         | 2.38%   |
| ASUS ASUS USB-BT500                                    | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 101       | 68.24%  |
| AMD                   | 27        | 18.24%  |
| Nvidia                | 13        | 8.78%   |
| C-Media Electronics   | 2         | 1.35%   |
| VIA Technologies      | 1         | 0.68%   |
| ROCCAT                | 1         | 0.68%   |
| Realtek Semiconductor | 1         | 0.68%   |
| Creative Technology   | 1         | 0.68%   |
| Creative Labs         | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 7.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 5.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 4.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 4.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 3.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 3.33%   |
| AMD FCH Azalia Controller                                                                         | 6         | 3.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.22%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.67%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.67%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.11%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.11%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.11%   |
| Unknown                                                                                           | 2         | 1.11%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.56%   |
| ROCCAT USB PnP Sound Device                                                                       | 1         | 0.56%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                                                  | 1         | 0.56%   |
| Nvidia unknown                                                                                    | 1         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.56%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.56%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.56%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 0.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.56%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.56%   |
| Creative Technology Sound BlasterX G1                                                             | 1         | 0.56%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1         | 0.56%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                                  | 1         | 0.56%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.56%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 26.01%  |
| SK hynix            | 31        | 17.92%  |
| Kingston            | 24        | 13.87%  |
| Unknown             | 15        | 8.67%   |
| Goodram             | 13        | 7.51%   |
| Micron Technology   | 12        | 6.94%   |
| Crucial             | 8         | 4.62%   |
| Ramaxel Technology  | 5         | 2.89%   |
| Corsair             | 4         | 2.31%   |
| Patriot             | 2         | 1.16%   |
| Nanya Technology    | 2         | 1.16%   |
| G.Skill             | 2         | 1.16%   |
| Unknown (07FB)      | 1         | 0.58%   |
| Toshiba             | 1         | 0.58%   |
| Qimonda             | 1         | 0.58%   |
| Kimtigo             | 1         | 0.58%   |
| Innodisk            | 1         | 0.58%   |
| Hewlett-Packard     | 1         | 0.58%   |
| GeIL                | 1         | 0.58%   |
| Elpida              | 1         | 0.58%   |
| A-DATA Technology   | 1         | 0.58%   |
| A-DA                | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M393B1G70QH0-YK0 8GB DIMM DDR3 1600MT/s          | 11        | 5.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 4         | 2.14%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3         | 1.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.6%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 3         | 1.6%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2         | 1.07%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2         | 1.07%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 2         | 1.07%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 1.07%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 1.07%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 2         | 1.07%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2         | 1.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.07%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 1.07%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 1.07%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s      | 2         | 1.07%   |
| Goodram RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s         | 2         | 1.07%   |
| Goodram RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s        | 2         | 1.07%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 512MB SODIMM DDR                          | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR                            | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                  | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1         | 0.53%   |
| Unknown RAM Module 16384MB DIMM DDR3 800MT/s                 | 1         | 0.53%   |
| Unknown RAM 8G2400MHz 8GB SODIMM DDR4 2400MT/s               | 1         | 0.53%   |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s | 1         | 0.53%   |
| Toshiba RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s             | 1         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 0.53%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s        | 1         | 0.53%   |
| SK hynix RAM HYMP125U72CP8-Y5 2GB DIMM DDR2 667MT/s          | 1         | 0.53%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.53%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.53%   |
| SK hynix RAM HMT351R7BFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1         | 0.53%   |
| SK hynix RAM HMT351R7BFR8A-H9 4GB DIMM DDR3 1333MT/s         | 1         | 0.53%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1         | 0.53%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 0.53%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 800MT/s        | 1         | 0.53%   |
| SK hynix RAM HMT31GR7CFR4A-H9 8192MB DIMM DDR3 1333MT/s      | 1         | 0.53%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1066MT/s       | 1         | 0.53%   |
| SK hynix RAM HMAA4GS6AJR8N-VK 32GB SODIMM DDR4 2667MT/s      | 1         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.53%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s       | 1         | 0.53%   |
| SK hynix RAM HMA41GR7AFR8N-TF 8GB DIMM DDR4 2133MT/s         | 1         | 0.53%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 0.53%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s        | 1         | 0.53%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 0.53%   |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s        | 1         | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 91        | 59.87%  |
| DDR4    | 45        | 29.61%  |
| DDR2    | 7         | 4.61%   |
| Unknown | 3         | 1.97%   |
| DDR     | 2         | 1.32%   |
| SDRAM   | 1         | 0.66%   |
| LPDDR4  | 1         | 0.66%   |
| LPDDR3  | 1         | 0.66%   |
| DRAM    | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 50%     |
| DIMM         | 74        | 48.68%  |
| Row Of Chips | 1         | 0.66%   |
| FB-DIMM      | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 59        | 36.65%  |
| 8192  | 53        | 32.92%  |
| 2048  | 25        | 15.53%  |
| 16384 | 14        | 8.7%    |
| 1024  | 7         | 4.35%   |
| 512   | 2         | 1.24%   |
| 32768 | 1         | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 56        | 33.94%  |
| 1333    | 26        | 15.76%  |
| 2400    | 18        | 10.91%  |
| 2667    | 11        | 6.67%   |
| 2133    | 10        | 6.06%   |
| 3200    | 9         | 5.45%   |
| 1334    | 6         | 3.64%   |
| 800     | 6         | 3.64%   |
| 667     | 6         | 3.64%   |
| 1067    | 4         | 2.42%   |
| 1867    | 3         | 1.82%   |
| Unknown | 3         | 1.82%   |
| 2666    | 2         | 1.21%   |
| 1066    | 2         | 1.21%   |
| 1866    | 1         | 0.61%   |
| 533     | 1         | 0.61%   |
| 400     | 1         | 0.61%   |

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
| Chicony Electronics                    | 13        | 34.21%  |
| Microdia                               | 8         | 21.05%  |
| Realtek Semiconductor                  | 3         | 7.89%   |
| Acer                                   | 3         | 7.89%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Ricoh                                  | 2         | 5.26%   |
| Logitech                               | 2         | 5.26%   |
| Syntek                                 | 1         | 2.63%   |
| Lite-On Technology                     | 1         | 2.63%   |
| Hewlett-Packard                        | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.63%   |
| Apple                                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Microdia Integrated Webcam                                    | 3         | 7.89%   |
| Realtek Lenovo EasyCamera                                     | 2         | 5.26%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 5.26%   |
| Logitech HD Pro Webcam C920                                   | 2         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)                       | 2         | 5.26%   |
| Chicony Integrated Camera                                     | 2         | 5.26%   |
| Syntek Lenovo EasyCamera                                      | 1         | 2.63%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 2.63%   |
| Sunplus Integrated_Webcam_FHD                                 | 1         | 2.63%   |
| Ricoh Integrated Webcam                                       | 1         | 2.63%   |
| Ricoh HD Webcam                                               | 1         | 2.63%   |
| Realtek Integrated_Webcam_HD                                  | 1         | 2.63%   |
| Microdia USB 2.0 Camera                                       | 1         | 2.63%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 2.63%   |
| Microdia Dell Integrated HD Webcam                            | 1         | 2.63%   |
| Lite-On Integrated Camera                                     | 1         | 2.63%   |
| HP Premium Starter Webcam                                     | 1         | 2.63%   |
| Chicony ThinkPad T490 Webcam                                  | 1         | 2.63%   |
| Chicony Realtek DMFT - RGB                                    | 1         | 2.63%   |
| Chicony Integrated Camera [ThinkPad]                          | 1         | 2.63%   |
| Chicony HP Integrated Webcam                                  | 1         | 2.63%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 2.63%   |
| Chicony HD Webcam                                             | 1         | 2.63%   |
| Chicony Front Camera                                          | 1         | 2.63%   |
| Chicony Chicony USB2.0 Camera                                 | 1         | 2.63%   |
| Chicony 1.3M Webcam                                           | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M WebCam | 1         | 2.63%   |
| Apple FaceTime HD Camera (Built-in)                           | 1         | 2.63%   |
| Acer USB HD Webcam                                            | 1         | 2.63%   |
| Acer Lenovo EasyCamera                                        | 1         | 2.63%   |
| Acer EasyCamera                                               | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 27.27%  |
| Synaptics                  | 3         | 27.27%  |
| Broadcom                   | 2         | 18.18%  |
| STMicroelectronics         | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 18.18%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Validity Sensors Fingerprint scanner                                         | 1         | 9.09%   |
| Synaptics  WBDI                                                              | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 9.09%   |
| AuthenTec AES2810                                                            | 1         | 9.09%   |

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
| 1     | 64        | 36.16%  |
| 0     | 49        | 27.68%  |
| 2     | 47        | 26.55%  |
| 3     | 9         | 5.08%   |
| 4     | 5         | 2.82%   |
| 5     | 2         | 1.13%   |
| 6     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 110       | 57.89%  |
| Bluetooth                | 19        | 10%     |
| Net/wireless             | 18        | 9.47%   |
| Fingerprint reader       | 11        | 5.79%   |
| Card reader              | 10        | 5.26%   |
| Graphics card            | 9         | 4.74%   |
| Firewire controller      | 4         | 2.11%   |
| Sound                    | 2         | 1.05%   |
| Network                  | 2         | 1.05%   |
| Net/ethernet             | 2         | 1.05%   |
| Storage/nvme             | 1         | 0.53%   |
| Storage                  | 1         | 0.53%   |
| Modem                    | 1         | 0.53%   |

