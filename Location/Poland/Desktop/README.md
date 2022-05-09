BSD in Poland - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Poland.

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

Total: 125

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [cc25e2d869](https://bsd-hardware.info/?probe=cc25e2d869) | May 04, 2022 |
| HP            | 213D A01                    | [562722ac56](https://bsd-hardware.info/?probe=562722ac56) | Apr 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [0d46ae5678](https://bsd-hardware.info/?probe=0d46ae5678) | Apr 25, 2022 |
| Apple         | PowerMac10,1                | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Unknown       | Unknown                     | [3c5fcc2377](https://bsd-hardware.info/?probe=3c5fcc2377) | Apr 22, 2022 |
| HP            | 213D A01                    | [4dea775e1b](https://bsd-hardware.info/?probe=4dea775e1b) | Apr 12, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [9a260e4d21](https://bsd-hardware.info/?probe=9a260e4d21) | Apr 05, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| ASUSTek       | P6-P8H61E                   | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | P6-P8H61E                   | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| Dell          | 0GXM1W A00                  | [717721a634](https://bsd-hardware.info/?probe=717721a634) | Mar 29, 2022 |
| Unknown       | Unknown                     | [38c71bac61](https://bsd-hardware.info/?probe=38c71bac61) | Mar 22, 2022 |
| Unknown       | Unknown                     | [a54ee6f019](https://bsd-hardware.info/?probe=a54ee6f019) | Mar 18, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [55515325c4](https://bsd-hardware.info/?probe=55515325c4) | Mar 15, 2022 |
| Dell          | 0GXM1W A00                  | [a488c9af25](https://bsd-hardware.info/?probe=a488c9af25) | Mar 14, 2022 |
| ASRock        | Q1900B-ITX                  | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Unknown       | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Intel         | D945GSEJT                   | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| HP            | 213D A01                    | [b9560ec339](https://bsd-hardware.info/?probe=b9560ec339) | Feb 24, 2022 |
| ASRock        | ConRoe1333-D667             | [624b4f4de7](https://bsd-hardware.info/?probe=624b4f4de7) | Feb 23, 2022 |
| Shuttle       | FZ270                       | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| HP            | 213D A01                    | [0171663489](https://bsd-hardware.info/?probe=0171663489) | Feb 12, 2022 |
| Unknown       | LeMaker Banana Pi           | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| MSI           | B75A-G43                    | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| MSI           | H61M-P20                    | [98ec852f90](https://bsd-hardware.info/?probe=98ec852f90) | Feb 06, 2022 |
| ASUSTek       | P6-P8H61E                   | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| Dell          | 04YP6J A02                  | [550e7feb7f](https://bsd-hardware.info/?probe=550e7feb7f) | Feb 03, 2022 |
| Gigabyte      | J4005ND2P-CF                | [2acf9ac926](https://bsd-hardware.info/?probe=2acf9ac926) | Jan 29, 2022 |
| Intel         | D2500HN AAG81480-500        | [3a39fe5ec2](https://bsd-hardware.info/?probe=3a39fe5ec2) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | [268906bcbe](https://bsd-hardware.info/?probe=268906bcbe) | Jan 29, 2022 |
| Dell          | 014GRG A03                  | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell          | 014GRG A03                  | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| ASRock        | A300M-STX                   | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASRock        | X570 Pro4                   | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASRockRack    | X570D4I-2T                  | [9f06290060](https://bsd-hardware.info/?probe=9f06290060) | Jan 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| Intel         | SKYBAY                      | [64db889658](https://bsd-hardware.info/?probe=64db889658) | Jan 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8ac48ba9c3](https://bsd-hardware.info/?probe=8ac48ba9c3) | Dec 23, 2021 |
| MSI           | H81M-P32                    | [bb4e756ca9](https://bsd-hardware.info/?probe=bb4e756ca9) | Dec 20, 2021 |
| Gigabyte      | H110TN                      | [8b6f0f839d](https://bsd-hardware.info/?probe=8b6f0f839d) | Dec 18, 2021 |
| Dell          | 0YY821 A00                  | [5de293a0be](https://bsd-hardware.info/?probe=5de293a0be) | Dec 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| ASUSTek       | H110M-K                     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [66ed413cab](https://bsd-hardware.info/?probe=66ed413cab) | Dec 05, 2021 |
| ASUSTek       | P7P55D                      | [73373c3c65](https://bsd-hardware.info/?probe=73373c3c65) | Dec 04, 2021 |
| ASUSTek       | P7P55D                      | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| Shuttle       | FH270                       | [81643d52fd](https://bsd-hardware.info/?probe=81643d52fd) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [7f32937b2c](https://bsd-hardware.info/?probe=7f32937b2c) | Nov 26, 2021 |
| Shuttle       | FZ270                       | [309687b5be](https://bsd-hardware.info/?probe=309687b5be) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [4df18caa5f](https://bsd-hardware.info/?probe=4df18caa5f) | Nov 26, 2021 |
| HP            | 213D A01                    | [0059e5b645](https://bsd-hardware.info/?probe=0059e5b645) | Nov 23, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| Unknown       | Unknown                     | [d31ea9f041](https://bsd-hardware.info/?probe=d31ea9f041) | Nov 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| Gigabyte      | B450M S2H                   | [f3bf8edc1e](https://bsd-hardware.info/?probe=f3bf8edc1e) | Oct 22, 2021 |
| HP            | 213D A01                    | [4b4903dfb2](https://bsd-hardware.info/?probe=4b4903dfb2) | Oct 17, 2021 |
| Gigabyte      | B450M DS3H                  | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Unknown       | YL-J3160L4                  | [3d0a63b493](https://bsd-hardware.info/?probe=3d0a63b493) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H                  | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| Intel         | SHARKBAY                    | [96448603f5](https://bsd-hardware.info/?probe=96448603f5) | Oct 02, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [a302e181a5](https://bsd-hardware.info/?probe=a302e181a5) | Sep 27, 2021 |
| Dell          | 04YP6J A02                  | [9ff547c00b](https://bsd-hardware.info/?probe=9ff547c00b) | Sep 16, 2021 |
| ASUSTek       | Q87T                        | [91e631c240](https://bsd-hardware.info/?probe=91e631c240) | Sep 11, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| Essentiel ... | MS-7848                     | [fa20a0307e](https://bsd-hardware.info/?probe=fa20a0307e) | Sep 01, 2021 |
| Intel         | SHARKBAY                    | [38332c6f8d](https://bsd-hardware.info/?probe=38332c6f8d) | Aug 16, 2021 |
| AOpen         | D1009 A1A4                  | [dc60a8dece](https://bsd-hardware.info/?probe=dc60a8dece) | Aug 03, 2021 |
| HP            | 1998                        | [fdf0088303](https://bsd-hardware.info/?probe=fdf0088303) | Jul 08, 2021 |
| Unknown       | Unknown                     | [1fffc03fbf](https://bsd-hardware.info/?probe=1fffc03fbf) | Jun 24, 2021 |
| Lenovo        | Board                       | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Gigabyte      | G31M-ES2L                   | [338240a790](https://bsd-hardware.info/?probe=338240a790) | Jun 05, 2021 |
| Gigabyte      | G31M-ES2L                   | [bf23a1ca58](https://bsd-hardware.info/?probe=bf23a1ca58) | Jun 02, 2021 |
| MSI           | H81M-P32                    | [1ffaa46853](https://bsd-hardware.info/?probe=1ffaa46853) | May 31, 2021 |
| MSI           | H81M-P32                    | [253deda07f](https://bsd-hardware.info/?probe=253deda07f) | May 28, 2021 |
| Lenovo        | Board                       | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Dell          | 0R230R A00                  | [bd8bf06e7f](https://bsd-hardware.info/?probe=bd8bf06e7f) | May 21, 2021 |
| MSI           | B450M-A PRO MAX             | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| Unknown       | Unknown                     | [1dcb55d9fe](https://bsd-hardware.info/?probe=1dcb55d9fe) | May 05, 2021 |
| Supermicro    | X7DCL                       | [27fc294bca](https://bsd-hardware.info/?probe=27fc294bca) | May 03, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [b848b8e046](https://bsd-hardware.info/?probe=b848b8e046) | Apr 03, 2021 |
| Gigabyte      | J4005ND2P-CF                | [7ce3b2f01e](https://bsd-hardware.info/?probe=7ce3b2f01e) | Mar 27, 2021 |
| Supermicro    | X7SLA                       | [043c20b93d](https://bsd-hardware.info/?probe=043c20b93d) | Mar 19, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b570778ef7](https://bsd-hardware.info/?probe=b570778ef7) | Mar 14, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [dee034110e](https://bsd-hardware.info/?probe=dee034110e) | Mar 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [73eec13c5e](https://bsd-hardware.info/?probe=73eec13c5e) | Mar 02, 2021 |
| Unknown       | Unknown                     | [6d7bac1be1](https://bsd-hardware.info/?probe=6d7bac1be1) | Feb 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | [60d084275e](https://bsd-hardware.info/?probe=60d084275e) | Feb 19, 2021 |
| Gigabyte      | J4005ND2P-CF                | [8d8683565a](https://bsd-hardware.info/?probe=8d8683565a) | Feb 13, 2021 |
| ASRock        | D1800B-ITX                  | [38f8b13f43](https://bsd-hardware.info/?probe=38f8b13f43) | Feb 10, 2021 |
| Unknown       | Unknown                     | [f4b7bb4518](https://bsd-hardware.info/?probe=f4b7bb4518) | Feb 08, 2021 |
| Dell          | 096JG8 A00                  | [b6630c8516](https://bsd-hardware.info/?probe=b6630c8516) | Feb 07, 2021 |
| Dell          | 096JG8 A00                  | [e73a728a76](https://bsd-hardware.info/?probe=e73a728a76) | Feb 03, 2021 |
| Dell          | 096JG8 A00                  | [612272e598](https://bsd-hardware.info/?probe=612272e598) | Feb 03, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [b26cfcd81d](https://bsd-hardware.info/?probe=b26cfcd81d) | Dec 28, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| HP            | 213D A01                    | [ca6ab5347e](https://bsd-hardware.info/?probe=ca6ab5347e) | Nov 13, 2020 |
| Shuttle       | FH270                       | [0ba087730e](https://bsd-hardware.info/?probe=0ba087730e) | Oct 29, 2020 |
| Shuttle       | FH270                       | [532cda62a8](https://bsd-hardware.info/?probe=532cda62a8) | Oct 29, 2020 |
| Intel         | D53427RKE G87971-406        | [bb6eeb8ef8](https://bsd-hardware.info/?probe=bb6eeb8ef8) | Oct 29, 2020 |
| Shuttle       | FH270                       | [25b278a2dc](https://bsd-hardware.info/?probe=25b278a2dc) | Oct 29, 2020 |
| Shuttle       | FH270                       | [e93928c59b](https://bsd-hardware.info/?probe=e93928c59b) | Oct 29, 2020 |
| ASRock        | QC5000M-ITX/PH              | [8d27c35122](https://bsd-hardware.info/?probe=8d27c35122) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | [9d4ea8797b](https://bsd-hardware.info/?probe=9d4ea8797b) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | [5ae47d058d](https://bsd-hardware.info/?probe=5ae47d058d) | Oct 29, 2020 |
| PC Engines    | apu1                        | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Wistron       | ProLiant ML110 G5           | [4906f28cfc](https://bsd-hardware.info/?probe=4906f28cfc) | Aug 14, 2020 |
| ASUSTek       | AM1M-A                      | [4dca0d2aa4](https://bsd-hardware.info/?probe=4dca0d2aa4) | Aug 14, 2020 |
| PC Engines    | apu2                        | [82f64585b8](https://bsd-hardware.info/?probe=82f64585b8) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | [8c92fcf25f](https://bsd-hardware.info/?probe=8c92fcf25f) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | [b6a4e39a1b](https://bsd-hardware.info/?probe=b6a4e39a1b) | Aug 14, 2020 |
| ASRock        | N3150B-ITX                  | [2b9248155e](https://bsd-hardware.info/?probe=2b9248155e) | Jun 09, 2020 |
| ASUSTek       | N3150I-C                    | [3da71be3c9](https://bsd-hardware.info/?probe=3da71be3c9) | Jun 09, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OpenBSD 7.0       | 7        | 7.07%   |
| helloSystem 0.7.0 | 5        | 5.05%   |
| helloSystem 0.6.0 | 4        | 4.04%   |
| OPNsense 22.1     | 3        | 3.03%   |
| OPNsense 21.7.7   | 3        | 3.03%   |
| OPNsense 21.7.3   | 3        | 3.03%   |
| OPNsense 21.1.2   | 3        | 3.03%   |
| OPNsense 21.1.1   | 3        | 3.03%   |
| OPNsense 21.1     | 3        | 3.03%   |
| FreeBSD 13.0-p5   | 3        | 3.03%   |
| FreeBSD 12.2-p2   | 3        | 3.03%   |
| FreeBSD 12.1-p8   | 3        | 3.03%   |
| OPNsense 22.1.6   | 2        | 2.02%   |
| OPNsense 22.1.5   | 2        | 2.02%   |
| OPNsense 22.1.4   | 2        | 2.02%   |
| OPNsense 22.1.1   | 2        | 2.02%   |
| OPNsense 21.7.4   | 2        | 2.02%   |
| OPNsense 21.7.2   | 2        | 2.02%   |
| OPNsense 21.7.1   | 2        | 2.02%   |
| OPNsense 21.1.6   | 2        | 2.02%   |
| OPNsense 21.1.3   | 2        | 2.02%   |
| helloSystem 0.8.0 | 2        | 2.02%   |
| helloSystem 0.5.0 | 2        | 2.02%   |
| helloSystem 0.4.0 | 2        | 2.02%   |
| FreeBSD 13.0-p4   | 2        | 2.02%   |
| FreeBSD 12.3-p2   | 2        | 2.02%   |
| FreeBSD 12.2      | 2        | 2.02%   |
| FreeBSD 12.1-p13  | 2        | 2.02%   |
| XigmaNAS 12.2-p7  | 1        | 1.01%   |
| XigmaNAS 12.2-p6  | 1        | 1.01%   |
| OPNsense 22.1.3   | 1        | 1.01%   |
| OPNsense 22.1.2   | 1        | 1.01%   |
| OPNsense 21.7.8   | 1        | 1.01%   |
| OPNsense 21.7.5   | 1        | 1.01%   |
| OPNsense 21.7     | 1        | 1.01%   |
| OPNsense 21.1.9   | 1        | 1.01%   |
| OPNsense 21.1.8   | 1        | 1.01%   |
| OPNsense 21.1.7   | 1        | 1.01%   |
| OPNsense 21.1.4   | 1        | 1.01%   |
| OPNsense 20.7.4   | 1        | 1.01%   |
| OpenBSD 7.1       | 1        | 1.01%   |
| OpenBSD 6.9       | 1        | 1.01%   |
| OpenBSD 6.8       | 1        | 1.01%   |
| NetBSD 9.0_STABLE | 1        | 1.01%   |
| FreeBSD 13.0-p10  | 1        | 1.01%   |
| FreeBSD 13.0      | 1        | 1.01%   |
| FreeBSD 12.2-p10  | 1        | 1.01%   |
| FreeBSD 12.1-p9   | 1        | 1.01%   |
| FreeBSD 12.1-p10  | 1        | 1.01%   |
| FreeBSD 12.1      | 1        | 1.01%   |
| FreeBSD 11.3-p11  | 1        | 1.01%   |
| FreeBSD 11.3      | 1        | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 36       | 44.44%  |
| FreeBSD     | 22       | 27.16%  |
| helloSystem | 11       | 13.58%  |
| OpenBSD     | 9        | 11.11%  |
| XigmaNAS    | 2        | 2.47%   |
| NetBSD      | 1        | 1.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 76       | 93.83%  |
| arm64  | 2        | 2.47%   |
| macppc | 1        | 1.23%   |
| i386   | 1        | 1.23%   |
| armv7  | 1        | 1.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 56       | 68.29%  |
| helloDesktop  | 11       | 13.41%  |
| fvwm          | 6        | 7.32%   |
| GNOME         | 4        | 4.88%   |
| XFCE          | 2        | 2.44%   |
| KDE5          | 1        | 1.22%   |
| i3            | 1        | 1.22%   |
| Enlightenment | 1        | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 58       | 71.6%   |
| X11     | 23       | 28.4%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 65       | 80.25%  |
| SLiM    | 11       | 13.58%  |
| LightDM | 2        | 2.47%   |
| GDM     | 2        | 2.47%   |
| SDDM    | 1        | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 70.37%  |
| en_US   | 18       | 22.22%  |
| C       | 3        | 3.7%    |
| pl_PL   | 2        | 2.47%   |
| en_GB   | 1        | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 62       | 76.54%  |
| BIOS | 19       | 23.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 37       | 45.12%  |
| Ufs    | 33       | 40.24%  |
| Ffs    | 9        | 10.98%  |
| Cd9660 | 3        | 3.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 69       | 85.19%  |
| MBR     | 10       | 12.35%  |
| Unknown | 2        | 2.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 10       | 12.35%  |
| ASRock                     | 9        | 11.11%  |
| Unknown                    | 8        | 9.88%   |
| Intel                      | 7        | 8.64%   |
| Dell                       | 7        | 8.64%   |
| MSI                        | 6        | 7.41%   |
| Hewlett-Packard            | 6        | 7.41%   |
| Gigabyte Technology        | 6        | 7.41%   |
| Fujitsu                    | 5        | 6.17%   |
| Shuttle                    | 3        | 3.7%    |
| Lenovo                     | 3        | 3.7%    |
| Supermicro                 | 2        | 2.47%   |
| PC Engines                 | 2        | 2.47%   |
| Wistron                    | 1        | 1.23%   |
| ShenZhen MinWin Technology | 1        | 1.23%   |
| Raspberry Pi Foundation    | 1        | 1.23%   |
| Essentiel B                | 1        | 1.23%   |
| ASRockRack                 | 1        | 1.23%   |
| Apple                      | 1        | 1.23%   |
| AOpen                      | 1        | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 8        | 9.88%   |
| HP t620 PLUS Quad Core TC         | 5        | 6.17%   |
| ASUS All Series                   | 3        | 3.7%    |
| ASRock Q1900B-ITX                 | 3        | 3.7%    |
| Intel SHARKBAY                    | 2        | 2.47%   |
| Wistron ProLiant ML110 G5         | 1        | 1.23%   |
| Supermicro X7SLA                  | 1        | 1.23%   |
| Supermicro X7DCL                  | 1        | 1.23%   |
| Shuttle XH270                     | 1        | 1.23%   |
| Shuttle SZ270R9                   | 1        | 1.23%   |
| Shuttle SZ270                     | 1        | 1.23%   |
| ShenZhen MinWin MW-NANO-APL-4L    | 1        | 1.23%   |
| RPi Raspberry Pi 400              | 1        | 1.23%   |
| PC Engines apu2                   | 1        | 1.23%   |
| PC Engines apu1                   | 1        | 1.23%   |
| MSI MS-7D25                       | 1        | 1.23%   |
| MSI MS-7C52                       | 1        | 1.23%   |
| MSI MS-7B53                       | 1        | 1.23%   |
| MSI MS-7846                       | 1        | 1.23%   |
| MSI MS-7788                       | 1        | 1.23%   |
| MSI MS-7758                       | 1        | 1.23%   |
| Lenovo ThinkCentre M93 10A2S01Q00 | 1        | 1.23%   |
| Lenovo ThinkCentre M91p 7033DE6   | 1        | 1.23%   |
| Lenovo ThinkCentre M700 10GS      | 1        | 1.23%   |
| Intel SKYBAY                      | 1        | 1.23%   |
| Intel Q3XXG4-P V1.0               | 1        | 1.23%   |
| Intel D945GSEJT                   | 1        | 1.23%   |
| Intel D53427RKE G87971-406        | 1        | 1.23%   |
| Intel D2500HN AAG81480-500        | 1        | 1.23%   |
| HP EliteDesk 800 G1 SFF           | 1        | 1.23%   |
| Gigabyte J4005ND2P-CF             | 1        | 1.23%   |
| Gigabyte H110TN                   | 1        | 1.23%   |
| Gigabyte G31M-ES2L                | 1        | 1.23%   |
| Gigabyte B550M AORUS ELITE        | 1        | 1.23%   |
| Gigabyte B450M S2H                | 1        | 1.23%   |
| Gigabyte B450M DS3H               | 1        | 1.23%   |
| Fujitsu FUTRO S920                | 1        | 1.23%   |
| Fujitsu FUTRO S720                | 1        | 1.23%   |
| Fujitsu FUTRO S700                | 1        | 1.23%   |
| Fujitsu ESPRIMO P920              | 1        | 1.23%   |
| Fujitsu D3220-A1                  | 1        | 1.23%   |
| Essentiel B DarkDESK series       | 1        | 1.23%   |
| Dell Precision T1600              | 1        | 1.23%   |
| Dell OptiPlex 9020                | 1        | 1.23%   |
| Dell OptiPlex 760                 | 1        | 1.23%   |
| Dell OptiPlex 7040                | 1        | 1.23%   |
| Dell OptiPlex 7010                | 1        | 1.23%   |
| Dell OptiPlex 3020                | 1        | 1.23%   |
| Dell Dimension C521               | 1        | 1.23%   |
| ASUS TUF GAMING X570-PLUS         | 1        | 1.23%   |
| ASUS PRIME H310M-D R2.0           | 1        | 1.23%   |
| ASUS P7P55D                       | 1        | 1.23%   |
| ASUS P6-P8H61E                    | 1        | 1.23%   |
| ASUS M5A97 R2.0                   | 1        | 1.23%   |
| ASUS H110M-K                      | 1        | 1.23%   |
| ASUS E45M1-I DELUXE               | 1        | 1.23%   |
| ASRockRack X570D4I-2T             | 1        | 1.23%   |
| ASRock X570 Pro4                  | 1        | 1.23%   |
| ASRock QC5000M-ITX/PH             | 1        | 1.23%   |
| ASRock N3150B-ITX                 | 1        | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 8        | 9.88%   |
| HP t620                        | 5        | 6.17%   |
| Dell OptiPlex                  | 5        | 6.17%   |
| Lenovo ThinkCentre             | 3        | 3.7%    |
| Fujitsu FUTRO                  | 3        | 3.7%    |
| ASUS All                       | 3        | 3.7%    |
| ASRock Q1900B-ITX              | 3        | 3.7%    |
| Intel SHARKBAY                 | 2        | 2.47%   |
| Gigabyte B450M                 | 2        | 2.47%   |
| Wistron ProLiant               | 1        | 1.23%   |
| Supermicro X7SLA               | 1        | 1.23%   |
| Supermicro X7DCL               | 1        | 1.23%   |
| Shuttle XH270                  | 1        | 1.23%   |
| Shuttle SZ270R9                | 1        | 1.23%   |
| Shuttle SZ270                  | 1        | 1.23%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.23%   |
| RPi Raspberry                  | 1        | 1.23%   |
| PC Engines apu2                | 1        | 1.23%   |
| PC Engines apu1                | 1        | 1.23%   |
| MSI MS-7D25                    | 1        | 1.23%   |
| MSI MS-7C52                    | 1        | 1.23%   |
| MSI MS-7B53                    | 1        | 1.23%   |
| MSI MS-7846                    | 1        | 1.23%   |
| MSI MS-7788                    | 1        | 1.23%   |
| MSI MS-7758                    | 1        | 1.23%   |
| Intel SKYBAY                   | 1        | 1.23%   |
| Intel Q3XXG4-P                 | 1        | 1.23%   |
| Intel D945GSEJT                | 1        | 1.23%   |
| Intel D53427RKE                | 1        | 1.23%   |
| Intel D2500HN                  | 1        | 1.23%   |
| HP EliteDesk                   | 1        | 1.23%   |
| Gigabyte J4005ND2P-CF          | 1        | 1.23%   |
| Gigabyte H110TN                | 1        | 1.23%   |
| Gigabyte G31M-ES2L             | 1        | 1.23%   |
| Gigabyte B550M                 | 1        | 1.23%   |
| Fujitsu ESPRIMO                | 1        | 1.23%   |
| Fujitsu D3220-A1               | 1        | 1.23%   |
| Essentiel B DarkDESK           | 1        | 1.23%   |
| Dell Precision                 | 1        | 1.23%   |
| Dell Dimension                 | 1        | 1.23%   |
| ASUS TUF                       | 1        | 1.23%   |
| ASUS PRIME                     | 1        | 1.23%   |
| ASUS P7P55D                    | 1        | 1.23%   |
| ASUS P6-P8H61E                 | 1        | 1.23%   |
| ASUS M5A97                     | 1        | 1.23%   |
| ASUS H110M-K                   | 1        | 1.23%   |
| ASUS E45M1-I                   | 1        | 1.23%   |
| ASRockRack X570D4I-2T          | 1        | 1.23%   |
| ASRock X570                    | 1        | 1.23%   |
| ASRock QC5000M-ITX             | 1        | 1.23%   |
| ASRock N3150B-ITX              | 1        | 1.23%   |
| ASRock D1800B-ITX              | 1        | 1.23%   |
| ASRock ConRoe1333-D667         | 1        | 1.23%   |
| ASRock A300M-STX               | 1        | 1.23%   |
| Apple PowerMac10               | 1        | 1.23%   |
| AOpen ESPRIMO                  | 1        | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 18       | 22.22%  |
| 2020    | 8        | 9.88%   |
| 2016    | 8        | 9.88%   |
| 2019    | 7        | 8.64%   |
| 2018    | 7        | 8.64%   |
| 2021    | 6        | 7.41%   |
| 2015    | 5        | 6.17%   |
| 2012    | 5        | 6.17%   |
| 2009    | 5        | 6.17%   |
| 2017    | 3        | 3.7%    |
| 2011    | 3        | 3.7%    |
| 2013    | 2        | 2.47%   |
| 2007    | 2        | 2.47%   |
| Unknown | 2        | 2.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 81       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 79       | 97.53%  |
| Yes  | 2        | 2.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 25       | 30.86%  |
| 8.01-16.0  | 23       | 28.4%   |
| 16.01-24.0 | 19       | 23.46%  |
| 2.01-3.0   | 4        | 4.94%   |
| 32.01-64.0 | 3        | 3.7%    |
| 3.01-4.0   | 3        | 3.7%    |
| 0.51-1.0   | 2        | 2.47%   |
| 24.01-32.0 | 1        | 1.23%   |
| 1.01-2.0   | 1        | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 47       | 56.63%  |
| 0.51-1.0  | 18       | 21.69%  |
| 1.01-2.0  | 6        | 7.23%   |
| 4.01-8.0  | 4        | 4.82%   |
| 2.01-3.0  | 2        | 2.41%   |
| 8.01-16.0 | 2        | 2.41%   |
| 0         | 2        | 2.41%   |
| 3.01-4.0  | 1        | 1.2%    |
| Unknown   | 1        | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 53.49%  |
| 2      | 20       | 23.26%  |
| 3      | 5        | 5.81%   |
| 6      | 4        | 4.65%   |
| 4      | 4        | 4.65%   |
| 5      | 3        | 3.49%   |
| 0      | 3        | 3.49%   |
| 9      | 1        | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 83.95%  |
| Yes       | 13       | 16.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 78       | 96.3%   |
| No        | 3        | 3.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 75.61%  |
| Yes       | 20       | 24.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 92.59%  |
| Yes       | 6        | 7.41%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 81       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Warsaw                  | 11       | 12.64%  |
| Gdansk                  | 9        | 10.34%  |
| Wroclaw                 | 7        | 8.05%   |
| Krakow                  | 7        | 8.05%   |
| Miedziana Gora          | 3        | 3.45%   |
| Е»ukowo               | 2        | 2.3%    |
| Poznan                  | 2        | 2.3%    |
| Lodz                    | 2        | 2.3%    |
| Glincz                  | 2        | 2.3%    |
| Zgierz                  | 1        | 1.15%   |
| Zajaczki Pierwsze       | 1        | 1.15%   |
| Zagnansk                | 1        | 1.15%   |
| WЕ‚ocЕ‚awek       | 1        | 1.15%   |
| Wolsztyn                | 1        | 1.15%   |
| Walcz                   | 1        | 1.15%   |
| Tychy                   | 1        | 1.15%   |
| Szczytno                | 1        | 1.15%   |
| Stary Sacz              | 1        | 1.15%   |
| Spalice                 | 1        | 1.15%   |
| Sosnowiec               | 1        | 1.15%   |
| Siedlce                 | 1        | 1.15%   |
| RzeszГіw              | 1        | 1.15%   |
| RzeszÃ³w              | 1        | 1.15%   |
| Rybnik                  | 1        | 1.15%   |
| PruszkÃ³w             | 1        | 1.15%   |
| Pilica                  | 1        | 1.15%   |
| Piastow                 | 1        | 1.15%   |
| OЕ›wiД™cim        | 1        | 1.15%   |
| Ostrzeszow              | 1        | 1.15%   |
| Mogilno                 | 1        | 1.15%   |
| Loziska                 | 1        | 1.15%   |
| Lomianki                | 1        | 1.15%   |
| Lipno                   | 1        | 1.15%   |
| Lezno                   | 1        | 1.15%   |
| Legnica                 | 1        | 1.15%   |
| Konin                   | 1        | 1.15%   |
| Katowice                | 1        | 1.15%   |
| Jelenia Góra           | 1        | 1.15%   |
| Jelenia GÃ³ra         | 1        | 1.15%   |
| Jedlicze                | 1        | 1.15%   |
| Gmina Moszczenica       | 1        | 1.15%   |
| Elblag                  | 1        | 1.15%   |
| DД…browa GГіrnicza | 1        | 1.15%   |
| CzД™stochowa         | 1        | 1.15%   |
| ChrzanÃ³w             | 1        | 1.15%   |
| Chojnice                | 1        | 1.15%   |
| BЕ‚onie              | 1        | 1.15%   |
| Bydgoszcz               | 1        | 1.15%   |
| Burkatow                | 1        | 1.15%   |
| Andrychow               | 1        | 1.15%   |
| ?»ukowo                | 1        | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 46     | 18.42%  |
| Seagate             | 15       | 34     | 13.16%  |
| Samsung Electronics | 13       | 34     | 11.4%   |
| Toshiba             | 9        | 18     | 7.89%   |
| SanDisk             | 9        | 10     | 7.89%   |
| GOODRAM             | 8        | 15     | 7.02%   |
| A-DATA Technology   | 4        | 5      | 3.51%   |
| LITEON              | 3        | 3      | 2.63%   |
| Kingston            | 3        | 3      | 2.63%   |
| Hoodisk             | 3        | 4      | 2.63%   |
| OCZ                 | 2        | 2      | 1.75%   |
| Kston               | 2        | 2      | 1.75%   |
| Innodisk            | 2        | 3      | 1.75%   |
| Hitachi             | 2        | 2      | 1.75%   |
| Gigabyte Technology | 2        | 2      | 1.75%   |
| Corsair             | 2        | 2      | 1.75%   |
| Apacer              | 2        | 2      | 1.75%   |
| Transcend           | 1        | 3      | 0.88%   |
| SSDPR-CX            | 1        | 1      | 0.88%   |
| SPCC                | 1        | 1      | 0.88%   |
| PNY                 | 1        | 2      | 0.88%   |
| PLEXTOR             | 1        | 1      | 0.88%   |
| Phison              | 1        | 1      | 0.88%   |
| Patriot             | 1        | 1      | 0.88%   |
| NVMe                | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 5      | 0.88%   |
| Intenso             | 1        | 1      | 0.88%   |
| HGST                | 1        | 2      | 0.88%   |
| Crucial             | 1        | 2      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD20SDZW-11JJ8S0 2TB           | 2        | 1.52%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2        | 1.52%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2        | 1.52%   |
| WDC WD20EARS-00MVWB0 2TB           | 2        | 1.52%   |
| Toshiba MQ04ABF100 1TB             | 2        | 1.52%   |
| Seagate ST2000DL003-9VT166 2TB     | 2        | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.52%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 2        | 1.52%   |
| Samsung SSD 860 EVO 250GB          | 2        | 1.52%   |
| Samsung SSD 850 EVO 250GB          | 2        | 1.52%   |
| Kingston SUV500MS120G 120GB        | 2        | 1.52%   |
| GOODRAM SSDPR-CX400-128 128GB      | 2        | 1.52%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 2        | 1.52%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1        | 0.76%   |
| WDC WD5000LPVT-75G33T0 500GB       | 1        | 0.76%   |
| WDC WD5000BPVT-08HXZT3 500GB       | 1        | 0.76%   |
| WDC WD360ADFD-00NLR5 37GB          | 1        | 0.76%   |
| WDC WD360ADFD-00NLR1 37GB          | 1        | 0.76%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1        | 0.76%   |
| WDC WD3200AAVS-00ZTB0 320GB        | 1        | 0.76%   |
| WDC WD30EZRZ-00Z5HB0 3TB           | 1        | 0.76%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1        | 0.76%   |
| WDC WD2500AAKX-083CA1 250GB        | 1        | 0.76%   |
| WDC WD2500AAKX-00ERMA0 250GB       | 1        | 0.76%   |
| WDC WD20SMZW-11YFCS0 2TB           | 1        | 0.76%   |
| WDC WD20SDRW-11VUUS0 2TB           | 1        | 0.76%   |
| WDC WD20PURZ-85GU6Y0 2TB           | 1        | 0.76%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1        | 0.76%   |
| WDC WD1600BEVE-00UYT0 160GB        | 1        | 0.76%   |
| WDC WD10JQLX-22JFGT0 1TB           | 1        | 0.76%   |
| WDC WD10EURX-73C57Y0 1TB           | 1        | 0.76%   |
| WDC WD10EFRX-68FYTN0 1TB           | 1        | 0.76%   |
| WDC WD10EARS-003BB1 1TB            | 1        | 0.76%   |
| WDC WD101KFBX-68R56N0 10TB         | 1        | 0.76%   |
| Transcend TS64GMTS400S 64GB        | 1        | 0.76%   |
| Toshiba MQ01ACF032 320GB           | 1        | 0.76%   |
| Toshiba MQ01ABD100H 1TB            | 1        | 0.76%   |
| Toshiba MQ01ABD032 320GB           | 1        | 0.76%   |
| Toshiba MK3261GSYN 320GB           | 1        | 0.76%   |
| Toshiba MK1255GSX H 120GB          | 1        | 0.76%   |
| Toshiba HDWE150 5TB                | 1        | 0.76%   |
| Toshiba HDWD130 3TB                | 1        | 0.76%   |
| Toshiba HDWD110 1TB                | 1        | 0.76%   |
| Toshiba DT01ACA100 1TB             | 1        | 0.76%   |
| SSDPR-CX 400-512-G2 512GB          | 1        | 0.76%   |
| SPCC Solid State Disk 120GB        | 1        | 0.76%   |
| Seagate ST96812AS 64GB             | 1        | 0.76%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 0.76%   |
| Seagate ST5000LM000-2AN170 5TB     | 1        | 0.76%   |
| Seagate ST4000LM024-2AN17V 4TB     | 1        | 0.76%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 0.76%   |
| Seagate ST32000542AS 2TB           | 1        | 0.76%   |
| Seagate ST3000DM001-1CH166 3TB     | 1        | 0.76%   |
| Seagate ST1000LM048-2E7172 1TB     | 1        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 0.76%   |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 0.76%   |
| Seagate BUP Slim BL 1TB            | 1        | 0.76%   |
| SanDisk Ultra 32GB                 | 1        | 0.76%   |
| SanDisk SSD U100 32GB              | 1        | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 38     | 37.04%  |
| Seagate             | 15       | 34     | 27.78%  |
| Toshiba             | 9        | 18     | 16.67%  |
| Samsung Electronics | 5        | 11     | 9.26%   |
| Hitachi             | 2        | 2      | 3.7%    |
| SSDPR-CX            | 1        | 1      | 1.85%   |
| NVMe                | 1        | 1      | 1.85%   |
| HGST                | 1        | 2      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 9        | 10     | 16.07%  |
| Samsung Electronics | 9        | 22     | 16.07%  |
| GOODRAM             | 7        | 14     | 12.5%   |
| Kingston            | 3        | 3      | 5.36%   |
| Hoodisk             | 3        | 4      | 5.36%   |
| OCZ                 | 2        | 2      | 3.57%   |
| LITEON              | 2        | 2      | 3.57%   |
| Kston               | 2        | 2      | 3.57%   |
| Innodisk            | 2        | 3      | 3.57%   |
| Gigabyte Technology | 2        | 2      | 3.57%   |
| Corsair             | 2        | 2      | 3.57%   |
| Apacer              | 2        | 2      | 3.57%   |
| A-DATA Technology   | 2        | 2      | 3.57%   |
| WDC                 | 1        | 8      | 1.79%   |
| Transcend           | 1        | 3      | 1.79%   |
| SPCC                | 1        | 1      | 1.79%   |
| PLEXTOR             | 1        | 1      | 1.79%   |
| Phison              | 1        | 1      | 1.79%   |
| Patriot             | 1        | 1      | 1.79%   |
| Micron Technology   | 1        | 5      | 1.79%   |
| Intenso             | 1        | 1      | 1.79%   |
| Crucial             | 1        | 2      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 51       | 93     | 53.68%  |
| HDD  | 38       | 107    | 40%     |
| NVMe | 6        | 8      | 6.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 75       | 200    | 92.59%  |
| NVMe | 6        | 8      | 7.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 60       | 110    | 61.22%  |
| 0.51-1.0   | 20       | 38     | 20.41%  |
| 1.01-2.0   | 11       | 25     | 11.22%  |
| 4.01-10.0  | 3        | 9      | 3.06%   |
| 3.01-4.0   | 2        | 6      | 2.04%   |
| 2.01-3.0   | 2        | 12     | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 27       | 31.03%  |
| 1-20       | 17       | 19.54%  |
| 51-100     | 16       | 18.39%  |
| 251-500    | 13       | 14.94%  |
| 21-50      | 7        | 8.05%   |
| 501-1000   | 4        | 4.6%    |
| 1001-2000  | 2        | 2.3%    |
| 2001-3000  | 1        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 74       | 90.24%  |
| 21-50     | 3        | 3.66%   |
| 101-250   | 3        | 3.66%   |
| 1001-2000 | 2        | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba MQ04ABF100 1TB              | 2        | 2      | 13.33%  |
| WDC WD360ADFD-00NLR1 37GB           | 1        | 1      | 6.67%   |
| WDC WD3200AAVS-00ZTB0 320GB         | 1        | 1      | 6.67%   |
| WDC WD2500AAKX-083CA1 250GB         | 1        | 2      | 6.67%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 6.67%   |
| WDC WD1600BEVE-00UYT0 160GB         | 1        | 1      | 6.67%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 6.67%   |
| Toshiba MK3261GSYN 320GB            | 1        | 1      | 6.67%   |
| Seagate ST96812AS 64GB              | 1        | 4      | 6.67%   |
| Seagate ST32000542AS 2TB            | 1        | 1      | 6.67%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 1      | 6.67%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 6.67%   |
| Samsung Electronics HD154UI 1.5TB   | 1        | 1      | 6.67%   |
| Hitachi HTS721060G9SA00 64GB        | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 40%     |
| Toshiba             | 3        | 3      | 20%     |
| Seagate             | 3        | 6      | 20%     |
| Samsung Electronics | 2        | 2      | 13.33%  |
| Hitachi             | 1        | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 42.86%  |
| Toshiba             | 3        | 3      | 21.43%  |
| Seagate             | 3        | 6      | 21.43%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 18     | 92.86%  |
| SSD  | 1        | 1      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 73       | 185    | 81.11%  |
| Malfunc  | 13       | 19     | 14.44%  |
| Detected | 3        | 3      | 3.33%   |
| Failed   | 1        | 1      | 1.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 52       | 60.47%  |
| AMD                           | 21       | 24.42%  |
| Broadcom / LSI                | 2        | 2.33%   |
| Silicon Motion                | 1        | 1.16%   |
| Sandisk                       | 1        | 1.16%   |
| Samsung Electronics           | 1        | 1.16%   |
| Realtek Semiconductor         | 1        | 1.16%   |
| Phison Electronics            | 1        | 1.16%   |
| Nvidia                        | 1        | 1.16%   |
| Lite-On Technology            | 1        | 1.16%   |
| JMicron Technology            | 1        | 1.16%   |
| Integrated Technology Express | 1        | 1.16%   |
| ASMedia Technology            | 1        | 1.16%   |
| ADATA Technology              | 1        | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 15.46%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 7.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 5.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 4.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 4.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 4.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 2.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2        | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 2.06%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 2.06%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 2.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.06%   |
| Unknown                                                                                 | 2        | 2.06%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.03%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.03%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.03%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.03%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 1.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.03%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.03%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1        | 1.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.03%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.03%   |
| Integrated Express IT8213 IDE Controller                                                | 1        | 1.03%   |
| Broadcom / LSI SAS2116 PCI-Express Fusion-MPT SAS-2 [Meteor]                            | 1        | 1.03%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                      | 1        | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.03%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.03%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 64       | 72.73%  |
| IDE  | 14       | 15.91%  |
| NVMe | 7        | 7.95%   |
| RAID | 1        | 1.14%   |
| SAS  | 1        | 1.14%   |
| SCSI | 1        | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 54       | 66.67%  |
| AMD     | 23       | 28.4%   |
| ARM     | 3        | 3.7%    |
| PowerPC | 1        | 1.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| AMD GX-420CA SOC with Radeon HD Graphics                 | 5        | 6.17%   |
| Intel Celeron CPU J1900 @ 1.99GHz                        | 3        | 3.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz                         | 2        | 2.47%   |
| Intel Core i5-4570 CPU @ 3.20GHz                         | 2        | 2.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz                         | 2        | 2.47%   |
| Intel Core i3-6100 CPU @ 3.70GHz                         | 2        | 2.47%   |
| Intel Celeron CPU N3150 @ 1.60GHz                        | 2        | 2.47%   |
| ARM Cortex-A72 r0p3                                      | 2        | 2.47%   |
| AMD Ryzen 3 3100 4-Core Processor                        | 2        | 2.47%   |
| PowerPC 7447A (Revision 0x102)                           | 1        | 1.23%   |
| Intel Xeon CPU E5410 @ 2.33GHz                           | 1        | 1.23%   |
| Intel Xeon CPU E31225 @ 3.10GH                           | 1        | 1.23%   |
| Intel Pentium Dual-Core CPU E6                           | 1        | 1.23%   |
| Intel Pentium CPU G860 @ 3.00GHz                         | 1        | 1.23%   |
| Intel Pentium CPU G620 @ 2.60GHz                         | 1        | 1.23%   |
| Intel Pentium CPU G4400 @ 3.30GHz                        | 1        | 1.23%   |
| Intel Pentium CPU G3250 @ 3.20GHz                        | 1        | 1.23%   |
| Intel Pentium CPU G3220 @ 3.00GHz                        | 1        | 1.23%   |
| Intel Core i7-7700 CPU @ 3.60GHz                         | 1        | 1.23%   |
| Intel Core i7-6700T CPU @ 2.80GHz                        | 1        | 1.23%   |
| Intel Core i7-5550U CPU @ 2.00GHz                        | 1        | 1.23%   |
| Intel Core i7-4790 CPU @ 3.60GHz                         | 1        | 1.23%   |
| Intel Core i5-9400F CPU @ 2.90GHz                        | 1        | 1.23%   |
| Intel Core i5-8365U CPU @ 1.60GHz                        | 1        | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz                        | 1        | 1.23%   |
| Intel Core i5-7500T CPU @ 2.70GHz                        | 1        | 1.23%   |
| Intel Core i5-6600 CPU @ 3.30GHz                         | 1        | 1.23%   |
| Intel Core i5-6400T CPU @ 2.20GHz                        | 1        | 1.23%   |
| Intel Core i5-4570S CPU @ 2.90GHz                        | 1        | 1.23%   |
| Intel Core i5-3427U CPU @ 1.80GHz                        | 1        | 1.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz                        | 1        | 1.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz                         | 1        | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz                       | 1        | 1.23%   |
| Intel Core i5 CPU 650 @ 3.20GHz                          | 1        | 1.23%   |
| Intel Core i3-9100F CPU @ 3.60GHz                        | 1        | 1.23%   |
| Intel Core i3-4170 CPU @ 3.70GHz                         | 1        | 1.23%   |
| Intel Core i3-4150 CPU @ 3.50GHz                         | 1        | 1.23%   |
| Intel Core i3-4130 CPU @ 3.40GHz                         | 1        | 1.23%   |
| Intel Core 2 Duo                                         | 1        | 1.23%   |
| Intel Core 2 CPU E8500 @ 3.16GHz                         | 1        | 1.23%   |
| Intel Celeron J4125 CPU @ 2.00GHz                        | 1        | 1.23%   |
| Intel Celeron J4005 CPU @ 2.00GHz                        | 1        | 1.23%   |
| Intel Celeron CPU J3455 @ 1.50GHz                        | 1        | 1.23%   |
| Intel Celeron CPU J3160 @ 1.60GHz                        | 1        | 1.23%   |
| Intel Celeron CPU J1800 @ 2.41GHz                        | 1        | 1.23%   |
| Intel Celeron CPU 3865U @ 1.80GHz                        | 1        | 1.23%   |
| Intel C1                                                 | 1        | 1.23%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class) | 1        | 1.23%   |
| Intel Atom CPU D2500 @ 1.86GHz                           | 1        | 1.23%   |
| Intel Atom CPU 330 @ 1.60GHz                             | 1        | 1.23%   |
| Intel 12th Gen Core i5-12600K                            | 1        | 1.23%   |
| ARM Cortex-A7 r0p4                                       | 1        | 1.23%   |
| AMD Ryzen 9 3900X 12-Core Processor                      | 1        | 1.23%   |
| AMD Ryzen 7 5700G with Radeon Graphics                   | 1        | 1.23%   |
| AMD Ryzen 5 PRO 5650GE with Radeon Graphics              | 1        | 1.23%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics              | 1        | 1.23%   |
| AMD Ryzen 5 1600X Six-Core Processor                     | 1        | 1.23%   |
| AMD Ryzen 5 1600 Six-Core Processor                      | 1        | 1.23%   |
| AMD Phenom II X6 1090T Processor                         | 1        | 1.23%   |
| AMD GX-415GA SOC with Radeon HD Graphics                 | 1        | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 22.22%  |
| Intel Celeron           | 11       | 13.58%  |
| AMD GX                  | 8        | 9.88%   |
| Intel Core i3           | 6        | 7.41%   |
| Intel Pentium           | 5        | 6.17%   |
| Intel Core i7           | 4        | 4.94%   |
| Other                   | 3        | 3.7%    |
| Intel Atom              | 3        | 3.7%    |
| ARM Cortex              | 3        | 3.7%    |
| AMD Ryzen 5             | 3        | 3.7%    |
| Intel Xeon              | 2        | 2.47%   |
| AMD Ryzen 3             | 2        | 2.47%   |
| AMD G                   | 2        | 2.47%   |
| Intel Pentium Dual-Core | 1        | 1.23%   |
| Intel Core 2 Duo        | 1        | 1.23%   |
| Intel Core 2            | 1        | 1.23%   |
| AMD Ryzen 9             | 1        | 1.23%   |
| AMD Ryzen 7             | 1        | 1.23%   |
| AMD Ryzen 5 PRO         | 1        | 1.23%   |
| AMD Phenom II X6        | 1        | 1.23%   |
| AMD E                   | 1        | 1.23%   |
| AMD Athlon 64 X2        | 1        | 1.23%   |
| AMD Athlon              | 1        | 1.23%   |
| AMD A4                  | 1        | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 37       | 45.68%  |
| 2       | 23       | 28.4%   |
| Unknown | 8        | 9.88%   |
| 8       | 4        | 4.94%   |
| 12      | 3        | 3.7%    |
| 1       | 3        | 3.7%    |
| 24      | 1        | 1.23%   |
| 16      | 1        | 1.23%   |
| 6       | 1        | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 74       | 91.36%  |
| Unknown | 6        | 7.41%   |
| 2       | 1        | 1.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 54       | 66.67%  |
| 2       | 17       | 20.99%  |
| Unknown | 10       | 12.35%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 11       | 13.58%  |
| Jaguar        | 9        | 11.11%  |
| Silvermont    | 7        | 8.64%   |
| KabyLake      | 7        | 8.64%   |
| Skylake       | 6        | 7.41%   |
| Unknown       | 6        | 7.41%   |
| SandyBridge   | 5        | 6.17%   |
| Penryn        | 4        | 4.94%   |
| Zen 2         | 3        | 3.7%    |
| IvyBridge     | 3        | 3.7%    |
| Bonnell       | 3        | 3.7%    |
| Bobcat        | 3        | 3.7%    |
| Zen 3         | 2        | 2.47%   |
| Zen           | 2        | 2.47%   |
| Goldmont plus | 2        | 2.47%   |
| Zen+          | 1        | 1.23%   |
| Westmere      | 1        | 1.23%   |
| Puma          | 1        | 1.23%   |
| K8 Hammer     | 1        | 1.23%   |
| K10           | 1        | 1.23%   |
| Goldmont      | 1        | 1.23%   |
| Core          | 1        | 1.23%   |
| Broadwell     | 1        | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 46       | 57.5%   |
| AMD                                          | 22       | 27.5%   |
| Nvidia                                       | 9        | 11.25%  |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 1.25%   |
| Matrox Electronics Systems                   | 1        | 1.25%   |
| ASPEED Technology                            | 1        | 1.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7        | 8.64%   |
| Intel HD Graphics 530                                                                    | 5        | 6.17%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 5        | 6.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5        | 6.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4        | 4.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 3.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 3.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 2.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 2.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2        | 2.47%   |
| Intel HD Graphics 630                                                                    | 2        | 2.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 2.47%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 2.47%   |
| AMD Cezanne                                                                              | 2        | 2.47%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 1.23%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.23%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 1.23%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 1.23%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 1        | 1.23%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 1.23%   |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1        | 1.23%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 1.23%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1        | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1        | 1.23%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1        | 1.23%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.23%   |
| Intel HD Graphics 510                                                                    | 1        | 1.23%   |
| Intel HD Graphics 500                                                                    | 1        | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 1.23%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 1.23%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.23%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 1.23%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 1.23%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 1.23%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 1.23%   |
| AMD RV280 [Radeon 9200]                                                                  | 1        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.23%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 1        | 1.23%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1        | 1.23%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1        | 1.23%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1        | 1.23%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 1        | 1.23%   |
| AMD Kabini [Radeon HD 8280E]                                                             | 1        | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 41       | 50%     |
| 1 x AMD        | 20       | 24.39%  |
| 1 x Nvidia     | 8        | 9.76%   |
| Other          | 5        | 6.1%    |
| 2 x Intel      | 2        | 2.44%   |
| Intel + Nvidia | 2        | 2.44%   |
| 1 x XGI        | 1        | 1.22%   |
| 1 x Matrox     | 1        | 1.22%   |
| Intel + AMD    | 1        | 1.22%   |
| AMD + ASPEED   | 1        | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 70       | 86.42%  |
| Unknown     | 7        | 8.64%   |
| Proprietary | 4        | 4.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 69       | 85.19%  |
| 7.01-8.0   | 3        | 3.7%    |
| 3.01-4.0   | 3        | 3.7%    |
| 1.01-2.0   | 3        | 3.7%    |
| 0.01-0.5   | 2        | 2.47%   |
| 0.51-1.0   | 1        | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| NEC Computers       | 4        | 20%     |
| Acer                | 4        | 20%     |
| Samsung Electronics | 2        | 10%     |
| Goldstar            | 2        | 10%     |
| Dell                | 2        | 10%     |
| Vestel Elektronik   | 1        | 5%      |
| Toshiba             | 1        | 5%      |
| Iiyama              | 1        | 5%      |
| HPN                 | 1        | 5%      |
| Hewlett-Packard     | 1        | 5%      |
| Eizo                | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch    | 1        | 5%      |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 5%      |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1        | 5%      |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 5%      |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch            | 1        | 5%      |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch         | 1        | 5%      |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch          | 1        | 5%      |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch              | 1        | 5%      |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 5%      |
| HPN LCD Monitor HP E233 1920x1080                                     | 1        | 5%      |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 1        | 5%      |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1        | 5%      |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 5%      |
| Eizo EV2455 ENC2533 1920x1200 520x330mm 24.2-inch                     | 1        | 5%      |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1        | 5%      |
| Dell P2312H DEL4076 1920x1080 510x290mm 23.1-inch                     | 1        | 5%      |
| Acer X193HQ ACR0064 1366x768 400x250mm 18.6-inch                      | 1        | 5%      |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 5%      |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                     | 1        | 5%      |
| Acer EG220Q ACR06A1 1920x1080 480x270mm 21.7-inch                     | 1        | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 40%     |
| 1366x768 (WXGA)    | 3        | 15%     |
| 3840x2160 (4K)     | 2        | 10%     |
| 1920x540           | 2        | 10%     |
| 1920x1200 (WUXGA)  | 2        | 10%     |
| 2560x1440 (QHD)    | 1        | 5%      |
| 2560x1080          | 1        | 5%      |
| 1680x1050 (WSXGA+) | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 4        | 20%     |
| 23      | 3        | 15%     |
| 21      | 3        | 15%     |
| 18      | 3        | 15%     |
| 42      | 2        | 10%     |
| 50      | 1        | 5%      |
| 40      | 1        | 5%      |
| 31      | 1        | 5%      |
| 28      | 1        | 5%      |
| Unknown | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 30%     |
| 401-500     | 6        | 30%     |
| 601-700     | 2        | 10%     |
| 901-1000    | 2        | 10%     |
| 801-900     | 1        | 5%      |
| 351-400     | 1        | 5%      |
| 1001-1500   | 1        | 5%      |
| Unknown     | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 68.42%  |
| 16/10   | 3        | 15.79%  |
| 3/2     | 1        | 5.26%   |
| 21/9    | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 35%     |
| 251-300        | 4        | 20%     |
| 501-1000       | 3        | 15%     |
| 141-150        | 2        | 10%     |
| More than 1000 | 1        | 5%      |
| 351-500        | 1        | 5%      |
| 151-200        | 1        | 5%      |
| Unknown        | 1        | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 55.56%  |
| 101-120 | 4        | 22.22%  |
| 1-50    | 2        | 11.11%  |
| 121-160 | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 63       | 77.78%  |
| 1     | 16       | 19.75%  |
| 2     | 2        | 2.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 50       | 42.02%  |
| Realtek Semiconductor           | 46       | 38.66%  |
| Broadcom                        | 7        | 5.88%   |
| Qualcomm Atheros                | 5        | 4.2%    |
| Qualcomm Atheros Communications | 3        | 2.52%   |
| U-Blox                          | 1        | 0.84%   |
| TP-Link                         | 1        | 0.84%   |
| NetGear                         | 1        | 0.84%   |
| IMC Networks                    | 1        | 0.84%   |
| Huawei Technologies             | 1        | 0.84%   |
| D-Link System                   | 1        | 0.84%   |
| Apple                           | 1        | 0.84%   |
| American Megatrends             | 1        | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 41       | 29.93%  |
| Intel I211 Gigabit Network Connection                                         | 10       | 7.3%    |
| Intel Ethernet Connection I217-LM                                             | 7        | 5.11%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 4.38%   |
| Intel I210 Gigabit Network Connection                                         | 6        | 4.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 3.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 2.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 2.92%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 2.19%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 2.19%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 1.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.46%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 1.46%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.46%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 1.46%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.73%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.73%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.73%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.73%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 0.73%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.73%   |
| Intel Ethernet Controller X550                                                | 1        | 0.73%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.73%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.73%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 0.73%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.73%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.73%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.73%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.73%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.73%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.73%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.73%   |
| Intel 82546GB Gigabit Ethernet Controller                                     | 1        | 0.73%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 0.73%   |
| Huawei E3372 LTE/UMTS/GSM HiLink Modem/Networkcard                            | 1        | 0.73%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1        | 0.73%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.73%   |
| Broadcom BCM4401-B0 100Base-TX                                                | 1        | 0.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 0.73%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 1        | 0.73%   |
| American Megatrends Virtual Ethernet                                          | 1        | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Broadcom                        | 5        | 22.73%  |
| Qualcomm Atheros                | 4        | 18.18%  |
| Realtek Semiconductor           | 3        | 13.64%  |
| Qualcomm Atheros Communications | 3        | 13.64%  |
| Intel                           | 3        | 13.64%  |
| TP-Link                         | 1        | 4.55%   |
| NetGear                         | 1        | 4.55%   |
| IMC Networks                    | 1        | 4.55%   |
| D-Link System                   | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 18.18%  |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 9.09%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 9.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 9.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 4.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 4.55%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 4.55%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 4.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 4.55%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 4.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 4.55%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 4.55%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 49       | 50%     |
| Realtek Semiconductor | 44       | 44.9%   |
| Broadcom              | 2        | 2.04%   |
| Qualcomm Atheros      | 1        | 1.02%   |
| Apple                 | 1        | 1.02%   |
| American Megatrends   | 1        | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 41       | 36.28%  |
| Intel I211 Gigabit Network Connection                                         | 10       | 8.85%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 6.19%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 5.31%   |
| Intel I210 Gigabit Network Connection                                         | 6        | 5.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 4.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 3.54%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 2.65%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.77%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 1.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.88%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.88%   |
| Intel Ethernet Controller X550                                                | 1        | 0.88%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.88%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.88%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.88%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.88%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.88%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.88%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.88%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.88%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.88%   |
| Intel 82546GB Gigabit Ethernet Controller                                     | 1        | 0.88%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.88%   |
| Broadcom BCM4401-B0 100Base-TX                                                | 1        | 0.88%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 1        | 0.88%   |
| American Megatrends Virtual Ethernet                                          | 1        | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 78       | 78%     |
| WiFi     | 20       | 20%     |
| Modem    | 1        | 1%      |
| Unknown  | 1        | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 86.9%   |
| WiFi     | 11       | 13.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 36.59%  |
| 2     | 17       | 20.73%  |
| 6     | 12       | 14.63%  |
| 3     | 10       | 12.2%   |
| 5     | 5        | 6.1%    |
| 4     | 5        | 6.1%    |
| 0     | 3        | 3.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 81       | 97.59%  |
| Yes  | 2        | 2.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 2        | 33.33%  |
| Qcom                    | 1        | 16.67%  |
| Intel                   | 1        | 16.67%  |
| Cambridge Silicon Radio | 1        | 16.67%  |
| Apple                   | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device  | 1        | 16.67%  |
| Intel AX201 Bluetooth                               | 1        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 16.67%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 16.67%  |
| ASUS ASUS USB-BT500                                 | 1        | 16.67%  |
| Apple Apple Broadcom Built-in Bluetooth             | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 43       | 56.58%  |
| AMD                 | 21       | 27.63%  |
| Nvidia              | 7        | 9.21%   |
| C-Media Electronics | 2        | 2.63%   |
| ROCCAT              | 1        | 1.32%   |
| Creative Technology | 1        | 1.32%   |
| Creative Labs       | 1        | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8        | 8.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8        | 8.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5        | 5.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 5.21%   |
| AMD FCH Azalia Controller                                                                         | 5        | 5.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5        | 5.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4        | 4.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3        | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 3.13%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2        | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2        | 2.08%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2        | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 2.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.08%   |
| ROCCAT USB PnP Sound Device                                                                       | 1        | 1.04%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 1.04%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.04%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1        | 1.04%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 1.04%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.04%   |
| Creative Technology Sound BlasterX G1                                                             | 1        | 1.04%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1        | 1.04%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                                  | 1        | 1.04%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1        | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 1.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1        | 1.04%   |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 1.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK Hynix            | 14       | 18.67%  |
| Kingston            | 13       | 17.33%  |
| Samsung Electronics | 12       | 16%     |
| Unknown             | 8        | 10.67%  |
| GOODRAM             | 8        | 10.67%  |
| Crucial             | 5        | 6.67%   |
| Patriot             | 2        | 2.67%   |
| Nanya Technology    | 2        | 2.67%   |
| Micron Technology   | 2        | 2.67%   |
| G.Skill             | 2        | 2.67%   |
| Corsair             | 2        | 2.67%   |
| Unknown (07FB)      | 1        | 1.33%   |
| Toshiba             | 1        | 1.33%   |
| Ramaxel Technology  | 1        | 1.33%   |
| Qimonda             | 1        | 1.33%   |
| GeIL                | 1        | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3        | 3.61%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 2.41%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2        | 2.41%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s         | 2        | 2.41%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                  | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 1.2%    |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 1.2%    |
| Unknown RAM Module 16384MB DIMM DDR3 800MT/s                 | 1        | 1.2%    |
| Unknown RAM 8G2400MHz 8GB SODIMM DDR4 2400MT/s               | 1        | 1.2%    |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s | 1        | 1.2%    |
| Toshiba RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s             | 1        | 1.2%    |
| SK Hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s        | 1        | 1.2%    |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.2%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1        | 1.2%    |
| SK Hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 1.2%    |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1        | 1.2%    |
| SK Hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 800MT/s        | 1        | 1.2%    |
| SK Hynix RAM HMAA4GS6AJR8N-VK 32GB SODIMM DDR4 2667MT/s      | 1        | 1.2%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1        | 1.2%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1        | 1.2%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s       | 1        | 1.2%    |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1        | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.2%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 1        | 1.2%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 1.2%    |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.2%    |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1333MT/s          | 1        | 1.2%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.2%    |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s      | 1        | 1.2%    |
| Ramaxel RAM RMT1970ED48E8F1333 2048MB SODIMM DDR3 1333MT/s   | 1        | 1.2%    |
| Qimonda RAM Module 2048MB DIMM DDR2 667MT/s                  | 1        | 1.2%    |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s               | 1        | 1.2%    |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s           | 1        | 1.2%    |
| Nanya RAM NT4GC64C88B1NS-DI 4GB DIMM DDR3 1333MT/s           | 1        | 1.2%    |
| Nanya RAM M2F4G64CC88D7N-DI 4GB DIMM DDR3 1600MT/s           | 1        | 1.2%    |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s       | 1        | 1.2%    |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s                    | 1        | 1.2%    |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s        | 1        | 1.2%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 1        | 1.2%    |
| Kingston RAM 99U5595-001.A00LF 2GB DIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Kingston RAM 99U5469-055.A00LF 4GB DIMM DDR3 1333MT/s        | 1        | 1.2%    |
| Kingston RAM 99U5469-055.A00LF 4096MB SODIMM DDR3 1600MT/s   | 1        | 1.2%    |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s      | 1        | 1.2%    |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Kingston RAM 99U5431-004.A00LF 1GB DIMM DDR2 667MT/s         | 1        | 1.2%    |
| Kingston RAM 99U5429-005.A00LF 1GB DIMM DDR2 667MT/s         | 1        | 1.2%    |
| Kingston RAM 99U5428-082.A00LF 8GB DIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Kingston RAM 99U5428-063.A00LF 8GB DIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Kingston RAM 99U5402-031.A00LF 4GB DIMM DDR3 1333MT/s        | 1        | 1.2%    |
| Kingston RAM 9965657-053.A00G 16GB SODIMM DDR4 3200MT/s      | 1        | 1.2%    |
| Kingston RAM 9905469-144.A00LF 4GB SODIMM DDR3 1333MT/s      | 1        | 1.2%    |
| Kingston RAM 9905403-149.A01LF 4GB DIMM DDR3 1333MT/s        | 1        | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 40       | 58.82%  |
| DDR4    | 21       | 30.88%  |
| DDR2    | 4        | 5.88%   |
| SDRAM   | 1        | 1.47%   |
| DDR     | 1        | 1.47%   |
| Unknown | 1        | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 44       | 64.71%  |
| SODIMM | 24       | 35.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 26       | 36.62%  |
| 8192  | 22       | 30.99%  |
| 2048  | 13       | 18.31%  |
| 16384 | 5        | 7.04%   |
| 1024  | 3        | 4.23%   |
| 32768 | 1        | 1.41%   |
| 512   | 1        | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 36.11%  |
| 1333    | 12       | 16.67%  |
| 2400    | 10       | 13.89%  |
| 2133    | 4        | 5.56%   |
| 800     | 4        | 5.56%   |
| 667     | 4        | 5.56%   |
| 3200    | 3        | 4.17%   |
| 2667    | 3        | 4.17%   |
| 2666    | 2        | 2.78%   |
| 1334    | 1        | 1.39%   |
| 1067    | 1        | 1.39%   |
| 1066    | 1        | 1.39%   |
| Unknown | 1        | 1.39%   |

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Microdia        | 1        | 33.33%  |
| Logitech        | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Microdia USB 2.0 Camera     | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |
| HP Premium Starter Webcam   | 1        | 33.33%  |

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
| 1     | 42       | 51.85%  |
| 0     | 35       | 43.21%  |
| 2     | 3        | 3.7%    |
| 4     | 1        | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 36       | 70.59%  |
| Net/wireless             | 7        | 13.73%  |
| Firewire controller      | 3        | 5.88%   |
| Net/ethernet             | 2        | 3.92%   |
| Graphics card            | 2        | 3.92%   |
| Bluetooth                | 1        | 1.96%   |

