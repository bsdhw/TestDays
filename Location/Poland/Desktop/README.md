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

Total: 148

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Biostar       | B450NH                      | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [fe44242c3b](https://bsd-hardware.info/?probe=fe44242c3b) | Sep 25, 2022 |
| Gigabyte      | H81M-S1                     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7aa564bfb2](https://bsd-hardware.info/?probe=7aa564bfb2) | Sep 14, 2022 |
| ASUSTek       | H61M-K                      | [0ee299e989](https://bsd-hardware.info/?probe=0ee299e989) | Sep 14, 2022 |
| HP            | 213D A01                    | [6354ddb4a8](https://bsd-hardware.info/?probe=6354ddb4a8) | Sep 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b2dc861f47](https://bsd-hardware.info/?probe=b2dc861f47) | Sep 10, 2022 |
| HP            | 213D A01                    | [c495fb5448](https://bsd-hardware.info/?probe=c495fb5448) | Aug 30, 2022 |
| HP            | 213D A01                    | [1b90f312ea](https://bsd-hardware.info/?probe=1b90f312ea) | Aug 26, 2022 |
| Inventec      | Z CLASS A02                 | [cb3708c9bf](https://bsd-hardware.info/?probe=cb3708c9bf) | Aug 21, 2022 |
| Gigabyte      | IMB4100TN                   | [aa4bae0d12](https://bsd-hardware.info/?probe=aa4bae0d12) | Aug 15, 2022 |
| ASRock        | Z370 Pro4                   | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| Dell          | 084J0R A00                  | [932058e97a](https://bsd-hardware.info/?probe=932058e97a) | Aug 09, 2022 |
| iEi           | B449 V1.00                  | [7776910eea](https://bsd-hardware.info/?probe=7776910eea) | Aug 05, 2022 |
| Gigabyte      | J4005ND2P-CF                | [2967d5275e](https://bsd-hardware.info/?probe=2967d5275e) | Jul 29, 2022 |
| HP            | 3397                        | [68eb683936](https://bsd-hardware.info/?probe=68eb683936) | Jul 27, 2022 |
| ASUSTek       | P8B WS                      | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| HP            | 213D A01                    | [0f58ab215e](https://bsd-hardware.info/?probe=0f58ab215e) | Jul 03, 2022 |
| Gigabyte      | GA-970A-UD3                 | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| Unknown       | Unknown                     | [fe9f636040](https://bsd-hardware.info/?probe=fe9f636040) | Jun 13, 2022 |
| Unknown       | Unknown                     | [6acbc93101](https://bsd-hardware.info/?probe=6acbc93101) | May 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | [3f39f21672](https://bsd-hardware.info/?probe=3f39f21672) | May 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ce4d7c01e5](https://bsd-hardware.info/?probe=ce4d7c01e5) | May 24, 2022 |
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
| PC Engines    | APU2                        | [82f64585b8](https://bsd-hardware.info/?probe=82f64585b8) | Aug 14, 2020 |
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
| helloSystem 0.7.0 | 8        | 6.61%   |
| OpenBSD 7.0       | 7        | 5.79%   |
| OPNsense 22.7.4   | 4        | 3.31%   |
| OPNsense 22.1.10  | 4        | 3.31%   |
| helloSystem 0.6.0 | 4        | 3.31%   |
| OPNsense 22.7.2   | 3        | 2.48%   |
| OPNsense 22.1     | 3        | 2.48%   |
| OPNsense 21.7.7   | 3        | 2.48%   |
| OPNsense 21.7.3   | 3        | 2.48%   |
| OPNsense 21.1.2   | 3        | 2.48%   |
| OPNsense 21.1.1   | 3        | 2.48%   |
| OPNsense 21.1     | 3        | 2.48%   |
| FreeBSD 13.0-p5   | 3        | 2.48%   |
| FreeBSD 12.2-p2   | 3        | 2.48%   |
| FreeBSD 12.1-p8   | 3        | 2.48%   |
| OPNsense 22.7     | 2        | 1.65%   |
| OPNsense 22.1.8   | 2        | 1.65%   |
| OPNsense 22.1.6   | 2        | 1.65%   |
| OPNsense 22.1.5   | 2        | 1.65%   |
| OPNsense 22.1.4   | 2        | 1.65%   |
| OPNsense 22.1.1   | 2        | 1.65%   |
| OPNsense 21.7.4   | 2        | 1.65%   |
| OPNsense 21.7.2   | 2        | 1.65%   |
| OPNsense 21.7.1   | 2        | 1.65%   |
| OPNsense 21.1.6   | 2        | 1.65%   |
| OPNsense 21.1.3   | 2        | 1.65%   |
| OpenBSD 7.1       | 2        | 1.65%   |
| helloSystem 0.8.0 | 2        | 1.65%   |
| helloSystem 0.5.0 | 2        | 1.65%   |
| helloSystem 0.4.0 | 2        | 1.65%   |
| FreeBSD 13.0-p4   | 2        | 1.65%   |
| FreeBSD 12.3-p2   | 2        | 1.65%   |
| FreeBSD 12.2      | 2        | 1.65%   |
| FreeBSD 12.1-p13  | 2        | 1.65%   |
| XigmaNAS 12.2-p7  | 1        | 0.83%   |
| XigmaNAS 12.2-p6  | 1        | 0.83%   |
| OPNsense 22.7.1   | 1        | 0.83%   |
| OPNsense 22.1.9   | 1        | 0.83%   |
| OPNsense 22.1.7   | 1        | 0.83%   |
| OPNsense 22.1.3   | 1        | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 50       | 50.51%  |
| FreeBSD     | 22       | 22.22%  |
| helloSystem | 14       | 14.14%  |
| OpenBSD     | 10       | 10.1%   |
| XigmaNAS    | 2        | 2.02%   |
| NetBSD      | 1        | 1.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 94       | 94.95%  |
| arm64  | 2        | 2.02%   |
| macppc | 1        | 1.01%   |
| i386   | 1        | 1.01%   |
| armv7  | 1        | 1.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 70       | 70%     |
| helloDesktop  | 15       | 15%     |
| fvwm          | 6        | 6%      |
| GNOME         | 4        | 4%      |
| XFCE          | 2        | 2%      |
| KDE5          | 1        | 1%      |
| i3            | 1        | 1%      |
| Enlightenment | 1        | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 72       | 72.73%  |
| X11     | 27       | 27.27%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 80       | 80.81%  |
| SLiM    | 14       | 14.14%  |
| LightDM | 2        | 2.02%   |
| GDM     | 2        | 2.02%   |
| SDDM    | 1        | 1.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 72       | 72.73%  |
| en_US   | 21       | 21.21%  |
| C       | 3        | 3.03%   |
| pl_PL   | 2        | 2.02%   |
| en_GB   | 1        | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 79       | 79.8%   |
| BIOS | 20       | 20.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 44       | 44%     |
| Ufs    | 42       | 42%     |
| Ffs    | 10       | 10%     |
| Cd9660 | 4        | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 85       | 85.86%  |
| MBR     | 11       | 11.11%  |
| Unknown | 3        | 3.03%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 13       | 13.13%  |
| Hewlett-Packard            | 10       | 10.1%   |
| ASRock                     | 10       | 10.1%   |
| Gigabyte Technology        | 9        | 9.09%   |
| Intel                      | 8        | 8.08%   |
| Dell                       | 8        | 8.08%   |
| Unknown                    | 8        | 8.08%   |
| MSI                        | 6        | 6.06%   |
| Fujitsu                    | 6        | 6.06%   |
| Supermicro                 | 3        | 3.03%   |
| Shuttle                    | 3        | 3.03%   |
| Lenovo                     | 3        | 3.03%   |
| PC Engines                 | 2        | 2.02%   |
| Wistron                    | 1        | 1.01%   |
| ShenZhen MinWin Technology | 1        | 1.01%   |
| Raspberry Pi Foundation    | 1        | 1.01%   |
| Inventec                   | 1        | 1.01%   |
| iEi                        | 1        | 1.01%   |
| Essentiel B                | 1        | 1.01%   |
| Biostar                    | 1        | 1.01%   |
| ASRockRack                 | 1        | 1.01%   |
| Apple                      | 1        | 1.01%   |
| AOpen                      | 1        | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| HP t620 PLUS Quad Core TC         | 8        | 8.08%   |
| Unknown                           | 8        | 8.08%   |
| ASUS All Series                   | 3        | 3.03%   |
| ASRock Q1900B-ITX                 | 3        | 3.03%   |
| Intel SHARKBAY                    | 2        | 2.02%   |
| Intel Q3XXG4-P V1.0               | 2        | 2.02%   |
| Fujitsu FUTRO S920                | 2        | 2.02%   |
| Wistron ProLiant ML110 G5         | 1        | 1.01%   |
| Supermicro X9SCL/X9SCM            | 1        | 1.01%   |
| Supermicro X7SLA                  | 1        | 1.01%   |
| Supermicro X7DCL                  | 1        | 1.01%   |
| Shuttle XH270                     | 1        | 1.01%   |
| Shuttle SZ270R9                   | 1        | 1.01%   |
| Shuttle SZ270                     | 1        | 1.01%   |
| ShenZhen MinWin MW-NANO-APL-4L    | 1        | 1.01%   |
| RPi Raspberry Pi 400              | 1        | 1.01%   |
| PC Engines APU2                   | 1        | 1.01%   |
| PC Engines apu1                   | 1        | 1.01%   |
| MSI MS-7D25                       | 1        | 1.01%   |
| MSI MS-7C52                       | 1        | 1.01%   |
| MSI MS-7B53                       | 1        | 1.01%   |
| MSI MS-7846                       | 1        | 1.01%   |
| MSI MS-7788                       | 1        | 1.01%   |
| MSI MS-7758                       | 1        | 1.01%   |
| Lenovo ThinkCentre M93 10A2S01Q00 | 1        | 1.01%   |
| Lenovo ThinkCentre M91p 7033DE6   | 1        | 1.01%   |
| Lenovo ThinkCentre M700 10GS      | 1        | 1.01%   |
| Inventec Z CLASS                  | 1        | 1.01%   |
| Intel SKYBAY                      | 1        | 1.01%   |
| Intel D945GSEJT                   | 1        | 1.01%   |
| Intel D53427RKE G87971-406        | 1        | 1.01%   |
| Intel D2500HN AAG81480-500        | 1        | 1.01%   |
| iEi Z436                          | 1        | 1.01%   |
| HP EliteDesk 800 G1 SFF           | 1        | 1.01%   |
| HP Compaq Elite 8300 SFF          | 1        | 1.01%   |
| Gigabyte J4005ND2P-CF             | 1        | 1.01%   |
| Gigabyte IMB4100TN                | 1        | 1.01%   |
| Gigabyte H81M-S1                  | 1        | 1.01%   |
| Gigabyte H110TN                   | 1        | 1.01%   |
| Gigabyte GA-970A-UD3              | 1        | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| HP t620                        | 8        | 8.08%   |
| Unknown                        | 8        | 8.08%   |
| Dell OptiPlex                  | 5        | 5.05%   |
| Fujitsu FUTRO                  | 4        | 4.04%   |
| Lenovo ThinkCentre             | 3        | 3.03%   |
| ASUS All                       | 3        | 3.03%   |
| ASRock Q1900B-ITX              | 3        | 3.03%   |
| Intel SHARKBAY                 | 2        | 2.02%   |
| Intel Q3XXG4-P                 | 2        | 2.02%   |
| Gigabyte B450M                 | 2        | 2.02%   |
| Wistron ProLiant               | 1        | 1.01%   |
| Supermicro X9SCL               | 1        | 1.01%   |
| Supermicro X7SLA               | 1        | 1.01%   |
| Supermicro X7DCL               | 1        | 1.01%   |
| Shuttle XH270                  | 1        | 1.01%   |
| Shuttle SZ270R9                | 1        | 1.01%   |
| Shuttle SZ270                  | 1        | 1.01%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.01%   |
| RPi Raspberry                  | 1        | 1.01%   |
| PC Engines APU2                | 1        | 1.01%   |
| PC Engines apu1                | 1        | 1.01%   |
| MSI MS-7D25                    | 1        | 1.01%   |
| MSI MS-7C52                    | 1        | 1.01%   |
| MSI MS-7B53                    | 1        | 1.01%   |
| MSI MS-7846                    | 1        | 1.01%   |
| MSI MS-7788                    | 1        | 1.01%   |
| MSI MS-7758                    | 1        | 1.01%   |
| Inventec Z                     | 1        | 1.01%   |
| Intel SKYBAY                   | 1        | 1.01%   |
| Intel D945GSEJT                | 1        | 1.01%   |
| Intel D53427RKE                | 1        | 1.01%   |
| Intel D2500HN                  | 1        | 1.01%   |
| iEi Z436                       | 1        | 1.01%   |
| HP EliteDesk                   | 1        | 1.01%   |
| HP Compaq                      | 1        | 1.01%   |
| Gigabyte J4005ND2P-CF          | 1        | 1.01%   |
| Gigabyte IMB4100TN             | 1        | 1.01%   |
| Gigabyte H81M-S1               | 1        | 1.01%   |
| Gigabyte H110TN                | 1        | 1.01%   |
| Gigabyte GA-970A-UD3           | 1        | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 24       | 24.24%  |
| 2018    | 11       | 11.11%  |
| 2020    | 9        | 9.09%   |
| 2016    | 9        | 9.09%   |
| 2012    | 8        | 8.08%   |
| 2021    | 6        | 6.06%   |
| 2019    | 6        | 6.06%   |
| 2015    | 5        | 5.05%   |
| 2009    | 5        | 5.05%   |
| 2011    | 4        | 4.04%   |
| 2017    | 3        | 3.03%   |
| 2013    | 3        | 3.03%   |
| 2007    | 2        | 2.02%   |
| Unknown | 2        | 2.02%   |
| 2022    | 1        | 1.01%   |
| 2010    | 1        | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 99       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 97.98%  |
| Yes  | 2        | 2.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 31       | 31%     |
| 8.01-16.0  | 29       | 29%     |
| 16.01-24.0 | 25       | 25%     |
| 2.01-3.0   | 5        | 5%      |
| 32.01-64.0 | 3        | 3%      |
| 3.01-4.0   | 3        | 3%      |
| 0.51-1.0   | 2        | 2%      |
| 24.01-32.0 | 1        | 1%      |
| 1.01-2.0   | 1        | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 58       | 56.86%  |
| 0.51-1.0  | 23       | 22.55%  |
| 1.01-2.0  | 9        | 8.82%   |
| 4.01-8.0  | 4        | 3.92%   |
| 2.01-3.0  | 2        | 1.96%   |
| 8.01-16.0 | 2        | 1.96%   |
| 0         | 2        | 1.96%   |
| 3.01-4.0  | 1        | 0.98%   |
| Unknown   | 1        | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 57       | 54.81%  |
| 2      | 22       | 21.15%  |
| 3      | 7        | 6.73%   |
| 4      | 5        | 4.81%   |
| 0      | 5        | 4.81%   |
| 6      | 4        | 3.85%   |
| 5      | 3        | 2.88%   |
| 9      | 1        | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 83.84%  |
| Yes       | 16       | 16.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 96.97%  |
| No        | 3        | 3.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 75%     |
| Yes       | 25       | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 91.92%  |
| Yes       | 8        | 8.08%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 99       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Warsaw            | 14       | 13.08%  |
| Gdansk            | 9        | 8.41%   |
| Wroclaw           | 7        | 6.54%   |
| Krakow            | 7        | 6.54%   |
| Lodz              | 4        | 3.74%   |
| Poznan            | 3        | 2.8%    |
| Miedziana Gora    | 3        | 2.8%    |
| Е»ukowo         | 2        | 1.87%   |
| Legionowo         | 2        | 1.87%   |
| Glincz            | 2        | 1.87%   |
| Zgierz            | 1        | 0.93%   |
| Zajaczki Pierwsze | 1        | 0.93%   |
| Zagnansk          | 1        | 0.93%   |
| WЕ‚ocЕ‚awek | 1        | 0.93%   |
| Wolsztyn          | 1        | 0.93%   |
| Walcz             | 1        | 0.93%   |
| Tychy             | 1        | 0.93%   |
| Szczytno          | 1        | 0.93%   |
| Sulejowek         | 1        | 0.93%   |
| Stopnica          | 1        | 0.93%   |
| Stary Sacz        | 1        | 0.93%   |
| Spalice           | 1        | 0.93%   |
| Sosnowiec         | 1        | 0.93%   |
| Siedlce           | 1        | 0.93%   |
| RzeszГіw        | 1        | 0.93%   |
| RzeszÃ³w        | 1        | 0.93%   |
| Rybnik            | 1        | 0.93%   |
| Radostowice       | 1        | 0.93%   |
| Pruszków         | 1        | 0.93%   |
| PruszkÃ³w       | 1        | 0.93%   |
| Pilica            | 1        | 0.93%   |
| Piastow           | 1        | 0.93%   |
| Piaseczno         | 1        | 0.93%   |
| OЕ›wiД™cim  | 1        | 0.93%   |
| Ostrzeszow        | 1        | 0.93%   |
| Mława            | 1        | 0.93%   |
| Mogilno           | 1        | 0.93%   |
| Lubartow          | 1        | 0.93%   |
| Loziska           | 1        | 0.93%   |
| Lomianki          | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 48     | 16.67%  |
| Seagate             | 19       | 38     | 13.77%  |
| Samsung Electronics | 15       | 37     | 10.87%  |
| SanDisk             | 11       | 12     | 7.97%   |
| GOODRAM             | 11       | 19     | 7.97%   |
| Toshiba             | 9        | 18     | 6.52%   |
| A-DATA Technology   | 5        | 6      | 3.62%   |
| Kingston            | 4        | 4      | 2.9%    |
| Hoodisk             | 4        | 6      | 2.9%    |
| OCZ                 | 3        | 3      | 2.17%   |
| LITEON              | 3        | 3      | 2.17%   |
| Innodisk            | 3        | 4      | 2.17%   |
| Corsair             | 3        | 3      | 2.17%   |
| Transcend           | 2        | 6      | 1.45%   |
| SPCC                | 2        | 2      | 1.45%   |
| Patriot             | 2        | 2      | 1.45%   |
| Kston               | 2        | 2      | 1.45%   |
| Hitachi             | 2        | 2      | 1.45%   |
| Gigabyte Technology | 2        | 2      | 1.45%   |
| Crucial             | 2        | 3      | 1.45%   |
| Apacer              | 2        | 2      | 1.45%   |
| Team                | 1        | 1      | 0.72%   |
| SSDPR-CX            | 1        | 1      | 0.72%   |
| PNY                 | 1        | 2      | 0.72%   |
| Plextor             | 1        | 1      | 0.72%   |
| Phison              | 1        | 1      | 0.72%   |
| NVMe                | 1        | 1      | 0.72%   |
| Micron Technology   | 1        | 6      | 0.72%   |
| Intenso             | 1        | 1      | 0.72%   |
| HGST                | 1        | 2      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| GOODRAM SSDPR-CX400-128 128GB      | 3        | 1.91%   |
| WDC WD20SDZW-11JJ8S0 2TB           | 2        | 1.27%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2        | 1.27%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2        | 1.27%   |
| WDC WD20EARS-00MVWB0 2TB           | 2        | 1.27%   |
| Toshiba MQ04ABF100 1TB             | 2        | 1.27%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 1.27%   |
| Seagate ST2000DL003-9VT166 2TB     | 2        | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.27%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 2        | 1.27%   |
| Samsung SSD 860 EVO 250GB          | 2        | 1.27%   |
| Samsung SSD 850 EVO 250GB          | 2        | 1.27%   |
| Patriot Burst 120GB                | 2        | 1.27%   |
| Kingston SUV500MS120G 120GB        | 2        | 1.27%   |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 2        | 1.27%   |
| Hoodisk SSD 128GB                  | 2        | 1.27%   |
| Goodram SSDPR-CL100-120-G3 120GB   | 2        | 1.27%   |
| Corsair CMFSSD-256D1 256GB         | 2        | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1        | 0.64%   |
| WDC WD5000LPVT-75G33T0 500GB       | 1        | 0.64%   |
| WDC WD5000BPVT-08HXZT3 500GB       | 1        | 0.64%   |
| WDC WD360ADFD-00NLR5 37GB          | 1        | 0.64%   |
| WDC WD360ADFD-00NLR1 37GB          | 1        | 0.64%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1        | 0.64%   |
| WDC WD3200AAVS-00ZTB0 320GB        | 1        | 0.64%   |
| WDC WD30EZRZ-00Z5HB0 3TB           | 1        | 0.64%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1        | 0.64%   |
| WDC WD2500AAKX-753CA0 250GB        | 1        | 0.64%   |
| WDC WD2500AAKX-083CA1 250GB        | 1        | 0.64%   |
| WDC WD2500AAKX-00ERMA0 250GB       | 1        | 0.64%   |
| WDC WD20SMZW-11YFCS0 2TB           | 1        | 0.64%   |
| WDC WD20SDRW-11VUUS0 2TB           | 1        | 0.64%   |
| WDC WD20PURZ-85GU6Y0 2TB           | 1        | 0.64%   |
| WDC WD20EURS-63S48Y0 2TB           | 1        | 0.64%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1        | 0.64%   |
| WDC WD1600BEVE-00UYT0 160GB        | 1        | 0.64%   |
| WDC WD10JQLX-22JFGT0 1TB           | 1        | 0.64%   |
| WDC WD10EURX-73C57Y0 1TB           | 1        | 0.64%   |
| WDC WD10EFRX-68FYTN0 1TB           | 1        | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 40     | 36.67%  |
| Seagate             | 19       | 38     | 31.67%  |
| Toshiba             | 9        | 18     | 15%     |
| Samsung Electronics | 5        | 11     | 8.33%   |
| Hitachi             | 2        | 2      | 3.33%   |
| SSDPR-CX            | 1        | 1      | 1.67%   |
| NVMe                | 1        | 1      | 1.67%   |
| HGST                | 1        | 2      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 11       | 12     | 15.07%  |
| Samsung Electronics | 10       | 24     | 13.7%   |
| GOODRAM             | 10       | 18     | 13.7%   |
| Kingston            | 4        | 4      | 5.48%   |
| Hoodisk             | 4        | 6      | 5.48%   |
| OCZ                 | 3        | 3      | 4.11%   |
| Innodisk            | 3        | 4      | 4.11%   |
| Corsair             | 3        | 3      | 4.11%   |
| A-DATA Technology   | 3        | 3      | 4.11%   |
| Transcend           | 2        | 6      | 2.74%   |
| SPCC                | 2        | 2      | 2.74%   |
| Patriot             | 2        | 2      | 2.74%   |
| LITEON              | 2        | 2      | 2.74%   |
| Kston               | 2        | 2      | 2.74%   |
| Gigabyte Technology | 2        | 2      | 2.74%   |
| Crucial             | 2        | 3      | 2.74%   |
| Apacer              | 2        | 2      | 2.74%   |
| WDC                 | 1        | 8      | 1.37%   |
| Team                | 1        | 1      | 1.37%   |
| Plextor             | 1        | 1      | 1.37%   |
| Phison              | 1        | 1      | 1.37%   |
| Micron Technology   | 1        | 6      | 1.37%   |
| Intenso             | 1        | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 65       | 116    | 56.52%  |
| HDD  | 43       | 113    | 37.39%  |
| NVMe | 7        | 9      | 6.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 91       | 229    | 92.86%  |
| NVMe | 7        | 9      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 75       | 137    | 65.22%  |
| 0.51-1.0   | 21       | 39     | 18.26%  |
| 1.01-2.0   | 12       | 26     | 10.43%  |
| 4.01-10.0  | 3        | 9      | 2.61%   |
| 3.01-4.0   | 2        | 6      | 1.74%   |
| 2.01-3.0   | 2        | 12     | 1.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 39       | 37.14%  |
| 1-20       | 19       | 18.1%   |
| 51-100     | 17       | 16.19%  |
| 251-500    | 14       | 13.33%  |
| 21-50      | 7        | 6.67%   |
| 501-1000   | 6        | 5.71%   |
| 1001-2000  | 2        | 1.9%    |
| 2001-3000  | 1        | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 91       | 90.1%   |
| 21-50     | 4        | 3.96%   |
| 101-250   | 3        | 2.97%   |
| 1001-2000 | 2        | 1.98%   |
| 51-100    | 1        | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba MQ04ABF100 1TB              | 2        | 2      | 10.53%  |
| WDC WD360ADFD-00NLR1 37GB           | 1        | 1      | 5.26%   |
| WDC WD3200AAVS-00ZTB0 320GB         | 1        | 1      | 5.26%   |
| WDC WD2500AAKX-753CA0 250GB         | 1        | 1      | 5.26%   |
| WDC WD2500AAKX-083CA1 250GB         | 1        | 2      | 5.26%   |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 1      | 5.26%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 5.26%   |
| WDC WD1600BEVE-00UYT0 160GB         | 1        | 1      | 5.26%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 5.26%   |
| Toshiba MK3261GSYN 320GB            | 1        | 1      | 5.26%   |
| Seagate ST96812AS 64GB              | 1        | 4      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 5.26%   |
| Seagate ST32000542AS 2TB            | 1        | 1      | 5.26%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 1      | 5.26%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 5.26%   |
| Samsung Electronics HD154UI 1.5TB   | 1        | 1      | 5.26%   |
| Hitachi HTS721060G9SA00 64GB        | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 42.11%  |
| Seagate             | 5        | 8      | 26.32%  |
| Toshiba             | 3        | 3      | 15.79%  |
| Samsung Electronics | 2        | 2      | 10.53%  |
| Hitachi             | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 44.44%  |
| Seagate             | 5        | 8      | 27.78%  |
| Toshiba             | 3        | 3      | 16.67%  |
| Samsung Electronics | 1        | 1      | 5.56%   |
| Hitachi             | 1        | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 22     | 94.44%  |
| SSD  | 1        | 1      | 5.56%   |

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
| Works    | 88       | 211    | 80.73%  |
| Malfunc  | 17       | 23     | 15.6%   |
| Detected | 3        | 3      | 2.75%   |
| Failed   | 1        | 1      | 0.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 63       | 59.43%  |
| AMD                           | 28       | 26.42%  |
| Samsung Electronics           | 2        | 1.89%   |
| Broadcom / LSI                | 2        | 1.89%   |
| Silicon Motion                | 1        | 0.94%   |
| SanDisk                       | 1        | 0.94%   |
| Realtek Semiconductor         | 1        | 0.94%   |
| Phison Electronics            | 1        | 0.94%   |
| Nvidia                        | 1        | 0.94%   |
| Marvell Technology Group      | 1        | 0.94%   |
| Lite-On Technology            | 1        | 0.94%   |
| JMicron Technology            | 1        | 0.94%   |
| Integrated Technology Express | 1        | 0.94%   |
| ASMedia Technology            | 1        | 0.94%   |
| ADATA Technology              | 1        | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20       | 16.81%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 6.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 5.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 5.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 4.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 3.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4        | 3.36%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 2.52%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 1.68%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2        | 1.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 1.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.68%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.68%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 1.68%   |
| Unknown                                                                                 | 2        | 1.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.84%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.84%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.84%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.84%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 1        | 0.84%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 0.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.84%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1        | 0.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 0.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 80       | 74.77%  |
| IDE  | 15       | 14.02%  |
| NVMe | 8        | 7.48%   |
| RAID | 2        | 1.87%   |
| SAS  | 1        | 0.93%   |
| SCSI | 1        | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 65       | 65.66%  |
| AMD     | 30       | 30.3%   |
| ARM     | 3        | 3.03%   |
| PowerPC | 1        | 1.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| AMD GX-420CA SOC with Radeon HD Graphics | 8        | 8.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3        | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 3        | 3.03%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 3        | 3.03%   |
| Intel Pentium CPU G860 @ 3.00GHz         | 2        | 2.02%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 2        | 2.02%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 2        | 2.02%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 2        | 2.02%   |
| ARM Cortex-A72 r0p3                      | 2        | 2.02%   |
| AMD Ryzen 3 3100 4-Core Processor        | 2        | 2.02%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 2        | 2.02%   |
| PowerPC 7447A (Revision 0x102)           | 1        | 1.01%   |
| Intel Xeon CPU E5410 @ 2.33GHz           | 1        | 1.01%   |
| Intel Xeon CPU E31225 @ 3.10GH           | 1        | 1.01%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 1        | 1.01%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1        | 1.01%   |
| Intel Pentium Dual-Core CPU E6           | 1        | 1.01%   |
| Intel Pentium CPU G620 @ 2.60GHz         | 1        | 1.01%   |
| Intel Pentium CPU G4400 @ 3.30GHz        | 1        | 1.01%   |
| Intel Pentium CPU G3250 @ 3.20GHz        | 1        | 1.01%   |
| Intel Pentium CPU G3220 @ 3.00GHz        | 1        | 1.01%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 1        | 1.01%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 1        | 1.01%   |
| Intel Core i7-6700T CPU @ 2.80GHz        | 1        | 1.01%   |
| Intel Core i7-5550U CPU @ 2.00GHz        | 1        | 1.01%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 1        | 1.01%   |
| Intel Core i5-9400F CPU @ 2.90GHz        | 1        | 1.01%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1        | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1        | 1.01%   |
| Intel Core i5-7500T CPU @ 2.70GHz        | 1        | 1.01%   |
| Intel Core i5-6600 CPU @ 3.30GHz         | 1        | 1.01%   |
| Intel Core i5-6400T CPU @ 2.20GHz        | 1        | 1.01%   |
| Intel Core i5-4570S CPU @ 2.90GHz        | 1        | 1.01%   |
| Intel Core i5-3427U CPU @ 1.80GHz        | 1        | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1        | 1.01%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 1        | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1        | 1.01%   |
| Intel Core i5 CPU 650 @ 3.20GHz          | 1        | 1.01%   |
| Intel Core i3-9100F CPU @ 3.60GHz        | 1        | 1.01%   |
| Intel Core i3-4170 CPU @ 3.70GHz         | 1        | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 20.2%   |
| Intel Celeron           | 14       | 14.14%  |
| AMD GX                  | 12       | 12.12%  |
| Intel Core i3           | 7        | 7.07%   |
| Intel Pentium           | 6        | 6.06%   |
| Intel Core i7           | 5        | 5.05%   |
| Intel Xeon              | 4        | 4.04%   |
| Intel Atom              | 4        | 4.04%   |
| Other                   | 3        | 3.03%   |
| ARM Cortex              | 3        | 3.03%   |
| AMD Ryzen 5             | 3        | 3.03%   |
| AMD Ryzen 3             | 3        | 3.03%   |
| AMD G                   | 3        | 3.03%   |
| Intel Pentium Dual-Core | 1        | 1.01%   |
| Intel Core 2 Duo        | 1        | 1.01%   |
| Intel Core 2            | 1        | 1.01%   |
| AMD Ryzen 9             | 1        | 1.01%   |
| AMD Ryzen 7             | 1        | 1.01%   |
| AMD Ryzen 5 PRO         | 1        | 1.01%   |
| AMD Phenom II X6        | 1        | 1.01%   |
| AMD Phenom II X4        | 1        | 1.01%   |
| AMD E                   | 1        | 1.01%   |
| AMD Athlon 64 X2        | 1        | 1.01%   |
| AMD Athlon              | 1        | 1.01%   |
| AMD A4                  | 1        | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 47       | 47.47%  |
| 2       | 29       | 29.29%  |
| Unknown | 8        | 8.08%   |
| 8       | 5        | 5.05%   |
| 12      | 3        | 3.03%   |
| 1       | 3        | 3.03%   |
| 6       | 2        | 2.02%   |
| 24      | 1        | 1.01%   |
| 16      | 1        | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 92       | 92.93%  |
| Unknown | 6        | 6.06%   |
| 2       | 1        | 1.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 69       | 69.7%   |
| 2       | 20       | 20.2%   |
| Unknown | 10       | 10.1%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Jaguar        | 13       | 13.13%  |
| Haswell       | 13       | 13.13%  |
| KabyLake      | 8        | 8.08%   |
| Silvermont    | 7        | 7.07%   |
| SandyBridge   | 7        | 7.07%   |
| Skylake       | 6        | 6.06%   |
| IvyBridge     | 6        | 6.06%   |
| Unknown       | 6        | 6.06%   |
| Penryn        | 5        | 5.05%   |
| Zen 2         | 4        | 4.04%   |
| Bobcat        | 4        | 4.04%   |
| Goldmont plus | 3        | 3.03%   |
| Bonnell       | 3        | 3.03%   |
| Zen 3         | 2        | 2.02%   |
| Zen           | 2        | 2.02%   |
| K10           | 2        | 2.02%   |
| Goldmont      | 2        | 2.02%   |
| Zen+          | 1        | 1.01%   |
| Westmere      | 1        | 1.01%   |
| Puma          | 1        | 1.01%   |
| K8 Hammer     | 1        | 1.01%   |
| Core          | 1        | 1.01%   |
| Broadwell     | 1        | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 53       | 54.08%  |
| AMD                                          | 30       | 30.61%  |
| Nvidia                                       | 11       | 11.22%  |
| Matrox Electronics Systems                   | 2        | 2.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 1.02%   |
| ASPEED Technology                            | 1        | 1.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini [Radeon HD 8400E]                                                             | 8        | 8.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7        | 7.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 6.06%   |
| Intel HD Graphics 530                                                                    | 5        | 5.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 4.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4        | 4.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 4.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 3.03%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2        | 2.02%   |
| Intel HD Graphics 630                                                                    | 2        | 2.02%   |
| Intel HD Graphics 500                                                                    | 2        | 2.02%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 2.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.02%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2        | 2.02%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 2.02%   |
| AMD Cezanne                                                                              | 2        | 2.02%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 1.01%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.01%   |
| Nvidia GM206GL [Quadro M2000]                                                            | 1        | 1.01%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 1.01%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.01%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 1.01%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 1.01%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 1        | 1.01%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 1.01%   |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1        | 1.01%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.01%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 1.01%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1        | 1.01%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1        | 1.01%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1        | 1.01%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.01%   |
| Intel HD Graphics 510                                                                    | 1        | 1.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 1.01%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 1.01%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.01%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 48       | 48%     |
| 1 x AMD        | 28       | 28%     |
| 1 x Nvidia     | 10       | 10%     |
| Other          | 5        | 5%      |
| 2 x Intel      | 2        | 2%      |
| 1 x Matrox     | 2        | 2%      |
| Intel + Nvidia | 2        | 2%      |
| 1 x XGI        | 1        | 1%      |
| Intel + AMD    | 1        | 1%      |
| AMD + ASPEED   | 1        | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 86       | 86.87%  |
| Unknown     | 7        | 7.07%   |
| Proprietary | 6        | 6.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 84       | 84.85%  |
| 3.01-4.0   | 4        | 4.04%   |
| 1.01-2.0   | 4        | 4.04%   |
| 7.01-8.0   | 3        | 3.03%   |
| 0.01-0.5   | 2        | 2.02%   |
| 8.01-16.0  | 1        | 1.01%   |
| 0.51-1.0   | 1        | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| NEC Computers       | 5        | 18.52%  |
| Acer                | 4        | 14.81%  |
| Samsung Electronics | 3        | 11.11%  |
| Dell                | 3        | 11.11%  |
| Philips             | 2        | 7.41%   |
| Goldstar            | 2        | 7.41%   |
| Vestel Elektronik   | 1        | 3.7%    |
| Toshiba             | 1        | 3.7%    |
| Iiyama              | 1        | 3.7%    |
| HPN                 | 1        | 3.7%    |
| Hewlett-Packard     | 1        | 3.7%    |
| Eizo                | 1        | 3.7%    |
| BenQ                | 1        | 3.7%    |
| AOC                 | 1        | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1        | 3.7%    |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 3.7%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 3.7%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1        | 3.7%    |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch             | 1        | 3.7%    |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch            | 1        | 3.7%    |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch         | 1        | 3.7%    |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch          | 1        | 3.7%    |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch           | 1        | 3.7%    |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch              | 1        | 3.7%    |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 3.7%    |
| HPN LCD Monitor HP E233 1920x1080                                     | 1        | 3.7%    |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 1        | 3.7%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1        | 3.7%    |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 3.7%    |
| Eizo EV2455 ENC2533 1920x1200 520x330mm 24.2-inch                     | 1        | 3.7%    |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1        | 3.7%    |
| Dell U2212HM DELD047 1920x1080 480x270mm 21.7-inch                    | 1        | 3.7%    |
| Dell P2312H DEL4076 1920x1080 510x290mm 23.1-inch                     | 1        | 3.7%    |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                      | 1        | 3.7%    |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                      | 1        | 3.7%    |
| Acer X193HQ ACR0064 1366x768 400x250mm 18.6-inch                      | 1        | 3.7%    |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 3.7%    |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                     | 1        | 3.7%    |
| Acer EG220Q ACR06A1 1920x1080 480x270mm 21.7-inch                     | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 41.67%  |
| 3840x2160 (4K)     | 3        | 12.5%   |
| 1366x768 (WXGA)    | 3        | 12.5%   |
| 1920x540           | 2        | 8.33%   |
| 1920x1200 (WUXGA)  | 2        | 8.33%   |
| 1680x1050 (WSXGA+) | 2        | 8.33%   |
| 2560x1440 (QHD)    | 1        | 4.17%   |
| 2560x1080          | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 20%     |
| 21      | 5        | 20%     |
| 23      | 3        | 12%     |
| 18      | 3        | 12%     |
| 42      | 2        | 8%      |
| 31      | 2        | 8%      |
| 50      | 1        | 4%      |
| 40      | 1        | 4%      |
| 28      | 1        | 4%      |
| 22      | 1        | 4%      |
| Unknown | 1        | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 9        | 36%     |
| 501-600     | 7        | 28%     |
| 601-700     | 3        | 12%     |
| 901-1000    | 2        | 8%      |
| 801-900     | 1        | 4%      |
| 351-400     | 1        | 4%      |
| 1001-1500   | 1        | 4%      |
| Unknown     | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 69.57%  |
| 16/10   | 4        | 17.39%  |
| 3/2     | 1        | 4.35%   |
| 21/9    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 41.67%  |
| 251-300        | 4        | 16.67%  |
| 501-1000       | 3        | 12.5%   |
| 351-500        | 2        | 8.33%   |
| 141-150        | 2        | 8.33%   |
| More than 1000 | 1        | 4.17%   |
| 151-200        | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 52.17%  |
| 101-120 | 6        | 26.09%  |
| 1-50    | 2        | 8.7%    |
| 121-160 | 2        | 8.7%    |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 77       | 77.78%  |
| 1     | 18       | 18.18%  |
| 2     | 3        | 3.03%   |
| 3     | 1        | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 61       | 40.67%  |
| Realtek Semiconductor           | 58       | 38.67%  |
| Qualcomm Atheros                | 9        | 6%      |
| Broadcom                        | 8        | 5.33%   |
| Qualcomm Atheros Communications | 3        | 2%      |
| Xiaomi                          | 1        | 0.67%   |
| U-Blox                          | 1        | 0.67%   |
| TP-Link                         | 1        | 0.67%   |
| Nuvoton                         | 1        | 0.67%   |
| NetGear                         | 1        | 0.67%   |
| Mellanox Technologies           | 1        | 0.67%   |
| IMC Networks                    | 1        | 0.67%   |
| Huawei Technologies             | 1        | 0.67%   |
| D-Link System                   | 1        | 0.67%   |
| Apple                           | 1        | 0.67%   |
| American Megatrends             | 1        | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 53       | 30.81%  |
| Intel I211 Gigabit Network Connection                                         | 12       | 6.98%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 4.65%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 4.07%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 4.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 4.07%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 2.91%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 2.33%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 1.74%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 1.74%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 1.16%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.16%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.58%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.58%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.58%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.58%   |
| Nuvoton USB Virtual COM                                                       | 1        | 0.58%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 0.58%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 0.58%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.58%   |
| Intel Ethernet Controller X550                                                | 1        | 0.58%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 7        | 25.93%  |
| Realtek Semiconductor           | 5        | 18.52%  |
| Broadcom                        | 5        | 18.52%  |
| Qualcomm Atheros Communications | 3        | 11.11%  |
| Intel                           | 3        | 11.11%  |
| TP-Link                         | 1        | 3.7%    |
| NetGear                         | 1        | 3.7%    |
| IMC Networks                    | 1        | 3.7%    |
| D-Link System                   | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 14.81%  |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 7.41%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 7.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 7.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 7.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 3.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 3.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 3.7%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 3.7%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 3.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 3.7%    |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 3.7%    |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 3.7%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 3.7%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1        | 3.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 60       | 48.39%  |
| Realtek Semiconductor | 56       | 45.16%  |
| Broadcom              | 3        | 2.42%   |
| Qualcomm Atheros      | 2        | 1.61%   |
| Xiaomi                | 1        | 0.81%   |
| Apple                 | 1        | 0.81%   |
| American Megatrends   | 1        | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 53       | 37.59%  |
| Intel I211 Gigabit Network Connection                                         | 12       | 8.51%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 5.67%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 4.96%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 4.96%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 3.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 2.84%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 2.13%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.42%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.71%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.71%   |
| Intel Ethernet Controller X550                                                | 1        | 0.71%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.71%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.71%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.71%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.71%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.71%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.71%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.71%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.71%   |
| Intel 82546GB Gigabit Ethernet Controller                                     | 1        | 0.71%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.71%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.71%   |
| Broadcom BCM4401-B0 100Base-TX                                                | 1        | 0.71%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 1        | 0.71%   |
| American Megatrends Virtual Ethernet                                          | 1        | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 76.8%   |
| WiFi     | 25       | 20%     |
| Modem    | 2        | 1.6%    |
| Unknown  | 2        | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 89.11%  |
| WiFi     | 11       | 10.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 34%     |
| 2     | 21       | 21%     |
| 3     | 16       | 16%     |
| 6     | 13       | 13%     |
| 5     | 7        | 7%      |
| 4     | 6        | 6%      |
| 0     | 3        | 3%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 98       | 97.03%  |
| Yes  | 3        | 2.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 2        | 25%     |
| ASUSTek Computer                | 2        | 25%     |
| Qualcomm Atheros Communications | 1        | 12.5%   |
| Qcom                            | 1        | 12.5%   |
| Intel                           | 1        | 12.5%   |
| Apple                           | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 25%     |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 12.5%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device  | 1        | 12.5%   |
| Intel AX201 Bluetooth                               | 1        | 12.5%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 12.5%   |
| ASUS ASUS USB-BT500                                 | 1        | 12.5%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 52       | 54.74%  |
| AMD                 | 29       | 30.53%  |
| Nvidia              | 9        | 9.47%   |
| C-Media Electronics | 2        | 2.11%   |
| ROCCAT              | 1        | 1.05%   |
| Creative Technology | 1        | 1.05%   |
| Creative Labs       | 1        | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 12       | 9.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9        | 7.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8        | 6.56%   |
| AMD FCH Azalia Controller                                                                         | 8        | 6.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6        | 4.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6        | 4.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5        | 4.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 4.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 4.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 3.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 2.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 2.46%   |
| AMD Wrestler HDMI Audio                                                                           | 3        | 2.46%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 2.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 2.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 2.46%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.64%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2        | 1.64%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 1.64%   |
| ROCCAT USB PnP Sound Device                                                                       | 1        | 0.82%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.82%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 0.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 0.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 0.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 0.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1        | 0.82%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 0.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 0.82%   |
| Intel 8 Series HD Audio Controller                                                                | 1        | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 0.82%   |
| Creative Technology Sound BlasterX G1                                                             | 1        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 16       | 16.49%  |
| Samsung Electronics | 15       | 15.46%  |
| Kingston            | 15       | 15.46%  |
| Goodram             | 12       | 12.37%  |
| Unknown             | 10       | 10.31%  |
| Crucial             | 6        | 6.19%   |
| Micron Technology   | 5        | 5.15%   |
| G.Skill             | 3        | 3.09%   |
| Corsair             | 3        | 3.09%   |
| Patriot             | 2        | 2.06%   |
| Nanya Technology    | 2        | 2.06%   |
| Unknown             | 2        | 2.06%   |
| Unknown (07FB)      | 1        | 1.03%   |
| Toshiba             | 1        | 1.03%   |
| Ramaxel Technology  | 1        | 1.03%   |
| Qimonda             | 1        | 1.03%   |
| Kimtigo             | 1        | 1.03%   |
| GeIL                | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3        | 2.83%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3        | 2.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2        | 1.89%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2        | 1.89%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2        | 1.89%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2        | 1.89%   |
| Goodram RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s         | 2        | 1.89%   |
| Unknown                                                      | 2        | 1.89%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1        | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 0.94%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.94%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                  | 1        | 0.94%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 0.94%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 0.94%   |
| Unknown RAM Module 16384MB DIMM DDR3 800MT/s                 | 1        | 0.94%   |
| Unknown RAM 8G2400MHz 8GB SODIMM DDR4 2400MT/s               | 1        | 0.94%   |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s | 1        | 0.94%   |
| Toshiba RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s             | 1        | 0.94%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s        | 1        | 0.94%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1        | 0.94%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1        | 0.94%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.94%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1        | 0.94%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 800MT/s        | 1        | 0.94%   |
| SK hynix RAM HMAA4GS6AJR8N-VK 32GB SODIMM DDR4 2667MT/s      | 1        | 0.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1        | 0.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1        | 0.94%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s       | 1        | 0.94%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1        | 0.94%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 1        | 0.94%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.94%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 52       | 61.18%  |
| DDR4    | 24       | 28.24%  |
| DDR2    | 4        | 4.71%   |
| Unknown | 3        | 3.53%   |
| SDRAM   | 1        | 1.18%   |
| DDR     | 1        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 53       | 62.35%  |
| SODIMM | 32       | 37.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 34       | 36.96%  |
| 8192  | 30       | 32.61%  |
| 2048  | 17       | 18.48%  |
| 16384 | 6        | 6.52%   |
| 1024  | 3        | 3.26%   |
| 32768 | 1        | 1.09%   |
| 512   | 1        | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 34       | 37.36%  |
| 1333    | 17       | 18.68%  |
| 2400    | 12       | 13.19%  |
| 3200    | 4        | 4.4%    |
| 2133    | 4        | 4.4%    |
| 800     | 4        | 4.4%    |
| 667     | 4        | 4.4%    |
| 2667    | 3        | 3.3%    |
| 2666    | 2        | 2.2%    |
| 1867    | 2        | 2.2%    |
| 1866    | 1        | 1.1%    |
| 1334    | 1        | 1.1%    |
| 1067    | 1        | 1.1%    |
| 1066    | 1        | 1.1%    |
| Unknown | 1        | 1.1%    |

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
| 1     | 50       | 50.51%  |
| 0     | 43       | 43.43%  |
| 2     | 5        | 5.05%   |
| 4     | 1        | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 45       | 71.43%  |
| Net/wireless             | 8        | 12.7%   |
| Firewire controller      | 3        | 4.76%   |
| Net/ethernet             | 2        | 3.17%   |
| Graphics card            | 2        | 3.17%   |
| Sound                    | 1        | 1.59%   |
| Network                  | 1        | 1.59%   |
| Bluetooth                | 1        | 1.59%   |

