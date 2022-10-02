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

Total: 274

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Biostar       | B450NH                      | Desktop     | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [fe44242c3b](https://bsd-hardware.info/?probe=fe44242c3b) | Sep 25, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7aa564bfb2](https://bsd-hardware.info/?probe=7aa564bfb2) | Sep 14, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0ee299e989](https://bsd-hardware.info/?probe=0ee299e989) | Sep 14, 2022 |
| Dell          | 0HJK12 A03                  | Server      | [96ad323ca0](https://bsd-hardware.info/?probe=96ad323ca0) | Sep 13, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [acb91f797f](https://bsd-hardware.info/?probe=acb91f797f) | Sep 13, 2022 |
| HP            | 213D A01                    | Desktop     | [6354ddb4a8](https://bsd-hardware.info/?probe=6354ddb4a8) | Sep 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b2dc861f47](https://bsd-hardware.info/?probe=b2dc861f47) | Sep 10, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| HP            | 213D A01                    | Desktop     | [c495fb5448](https://bsd-hardware.info/?probe=c495fb5448) | Aug 30, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [d721e505cb](https://bsd-hardware.info/?probe=d721e505cb) | Aug 27, 2022 |
| HP            | 213D A01                    | Desktop     | [1b90f312ea](https://bsd-hardware.info/?probe=1b90f312ea) | Aug 26, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [eec9546431](https://bsd-hardware.info/?probe=eec9546431) | Aug 23, 2022 |
| Inventec      | Z CLASS A02                 | Desktop     | [cb3708c9bf](https://bsd-hardware.info/?probe=cb3708c9bf) | Aug 21, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Gigabyte      | IMB4100TN                   | Desktop     | [aa4bae0d12](https://bsd-hardware.info/?probe=aa4bae0d12) | Aug 15, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [932058e97a](https://bsd-hardware.info/?probe=932058e97a) | Aug 09, 2022 |
| iEi           | B449 V1.00                  | Desktop     | [7776910eea](https://bsd-hardware.info/?probe=7776910eea) | Aug 05, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c38ad87323](https://bsd-hardware.info/?probe=c38ad87323) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6093566ed2](https://bsd-hardware.info/?probe=6093566ed2) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [706d8fc244](https://bsd-hardware.info/?probe=706d8fc244) | Aug 04, 2022 |
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
| helloSystem 0.7.0    | 13        | 5.65%   |
| OpenBSD 7.0          | 12        | 5.22%   |
| FreeBSD 12.1-p10     | 12        | 5.22%   |
| OpenBSD 7.1          | 6         | 2.61%   |
| helloSystem 0.6.0    | 6         | 2.61%   |
| FreeBSD 12.2         | 6         | 2.61%   |
| OPNsense 22.1        | 5         | 2.17%   |
| OPNsense 21.7.3      | 5         | 2.17%   |
| OPNsense 21.1.6      | 5         | 2.17%   |
| helloSystem 0.5.0    | 5         | 2.17%   |
| FreeBSD 14.0-CURRENT | 5         | 2.17%   |
| FreeBSD 13.0-p5      | 5         | 2.17%   |
| OPNsense 22.7.4      | 4         | 1.74%   |
| OPNsense 22.7.2      | 4         | 1.74%   |
| OPNsense 22.7        | 4         | 1.74%   |
| OPNsense 22.1.8      | 4         | 1.74%   |
| OPNsense 22.1.10     | 4         | 1.74%   |
| OPNsense 21.7.7      | 4         | 1.74%   |
| OPNsense 21.1.2      | 4         | 1.74%   |
| OPNsense 21.1.1      | 4         | 1.74%   |
| OPNsense 21.1        | 4         | 1.74%   |
| GhostBSD 20.04.02    | 4         | 1.74%   |
| FreeBSD 13.0-p4      | 4         | 1.74%   |
| FreeBSD 12.2-p2      | 4         | 1.74%   |
| FreeBSD 12.2-p10     | 4         | 1.74%   |
| FreeBSD 12.1         | 4         | 1.74%   |
| OPNsense 22.1.5      | 3         | 1.3%    |
| OPNsense 22.1.2      | 3         | 1.3%    |
| OPNsense 22.1.1      | 3         | 1.3%    |
| OPNsense 21.7.4      | 3         | 1.3%    |
| OPNsense 21.7.1      | 3         | 1.3%    |
| OPNsense 21.1.8      | 3         | 1.3%    |
| OPNsense 21.1.7      | 3         | 1.3%    |
| OPNsense 21.1.3      | 3         | 1.3%    |
| OpenBSD 6.8          | 3         | 1.3%    |
| helloSystem 0.4.0    | 3         | 1.3%    |
| FreeBSD 13.0         | 3         | 1.3%    |
| FreeBSD 12.1-p8      | 3         | 1.3%    |
| OPNsense 22.1.6      | 2         | 0.87%   |
| OPNsense 22.1.4      | 2         | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 76        | 39.38%  |
| FreeBSD     | 61        | 31.61%  |
| helloSystem | 24        | 12.44%  |
| OpenBSD     | 21        | 10.88%  |
| GhostBSD    | 6         | 3.11%   |
| XigmaNAS    | 2         | 1.04%   |
| NomadBSD    | 2         | 1.04%   |
| NetBSD      | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 186       | 96.37%  |
| i386   | 3         | 1.55%   |
| arm64  | 2         | 1.04%   |
| macppc | 1         | 0.52%   |
| armv7  | 1         | 0.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 115       | 58.97%  |
| helloDesktop  | 26        | 13.33%  |
| fvwm          | 16        | 8.21%   |
| XFCE          | 9         | 4.62%   |
| MATE          | 8         | 4.1%    |
| GNOME         | 6         | 3.08%   |
| Openbox       | 4         | 2.05%   |
| TWM           | 3         | 1.54%   |
| KDE5          | 3         | 1.54%   |
| i3            | 3         | 1.54%   |
| xfwm          | 1         | 0.51%   |
| Enlightenment | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 118       | 60.82%  |
| X11     | 76        | 39.18%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 142       | 73.2%   |
| SLiM    | 33        | 17.01%  |
| LightDM | 8         | 4.12%   |
| SDDM    | 6         | 3.09%   |
| GDM     | 4         | 2.06%   |
| XDM     | 1         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 125       | 63.78%  |
| en_US   | 38        | 19.39%  |
| C       | 19        | 9.69%   |
| pl_PL   | 12        | 6.12%   |
| fr_FR   | 1         | 0.51%   |
| en_GB   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 147       | 75.77%  |
| BIOS | 47        | 24.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 93        | 47.94%  |
| Ufs    | 74        | 38.14%  |
| Ffs    | 21        | 10.82%  |
| Cd9660 | 6         | 3.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 165       | 85.49%  |
| MBR     | 25        | 12.95%  |
| Unknown | 3         | 1.55%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 48        | 24.87%  |
| Lenovo                     | 24        | 12.44%  |
| Hewlett-Packard            | 15        | 7.77%   |
| ASUSTek Computer           | 14        | 7.25%   |
| Intel                      | 10        | 5.18%   |
| Gigabyte Technology        | 10        | 5.18%   |
| ASRock                     | 10        | 5.18%   |
| Unknown                    | 9         | 4.66%   |
| MSI                        | 7         | 3.63%   |
| Supermicro                 | 6         | 3.11%   |
| Fujitsu                    | 6         | 3.11%   |
| ZOTAC                      | 4         | 2.07%   |
| Shuttle                    | 3         | 1.55%   |
| Apple                      | 3         | 1.55%   |
| Acer                       | 3         | 1.55%   |
| PC Engines                 | 2         | 1.04%   |
| Inventec                   | 2         | 1.04%   |
| Wistron                    | 1         | 0.52%   |
| Toshiba                    | 1         | 0.52%   |
| Sony                       | 1         | 0.52%   |
| ShenZhen MinWin Technology | 1         | 0.52%   |
| Raspberry Pi Foundation    | 1         | 0.52%   |
| PC Specialist              | 1         | 0.52%   |
| Panasonic                  | 1         | 0.52%   |
| Notebook                   | 1         | 0.52%   |
| iEi                        | 1         | 0.52%   |
| IBM                        | 1         | 0.52%   |
| Fujitsu Siemens            | 1         | 0.52%   |
| Essentiel B                | 1         | 0.52%   |
| Deciso                     | 1         | 0.52%   |
| Biostar                    | 1         | 0.52%   |
| ASRockRack                 | 1         | 0.52%   |
| AOpen                      | 1         | 0.52%   |
| AMI                        | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell OEM-R 720xd                    | 11        | 5.7%    |
| Unknown                             | 10        | 5.18%   |
| HP t620 PLUS Quad Core TC           | 8         | 4.15%   |
| Lenovo ThinkPad X200 745969G        | 5         | 2.59%   |
| Dell Wyse 5070 Extended Thin Client | 3         | 1.55%   |
| ASUS All Series                     | 3         | 1.55%   |
| ASRock Q1900B-ITX                   | 3         | 1.55%   |
| ZOTAC ZBOX-CI329NANO                | 2         | 1.04%   |
| Intel SHARKBAY                      | 2         | 1.04%   |
| Intel Q3XXG4-P V1.0                 | 2         | 1.04%   |
| Fujitsu FUTRO S920                  | 2         | 1.04%   |
| ZOTAC ZBOX-CI341                    | 1         | 0.52%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.52%   |
| Wistron ProLiant ML110 G5           | 1         | 0.52%   |
| Toshiba PORTEGE X20W-D              | 1         | 0.52%   |
| Supermicro X9SCL/X9SCM              | 1         | 0.52%   |
| Supermicro X7SLA                    | 1         | 0.52%   |
| Supermicro X7DCL                    | 1         | 0.52%   |
| Supermicro X11SSN-L                 | 1         | 0.52%   |
| Supermicro SYS-5018D-FN8T           | 1         | 0.52%   |
| Supermicro Super Server             | 1         | 0.52%   |
| Sony SVF1521K1EB                    | 1         | 0.52%   |
| Shuttle XH270                       | 1         | 0.52%   |
| Shuttle SZ270R9                     | 1         | 0.52%   |
| Shuttle SZ270                       | 1         | 0.52%   |
| ShenZhen MinWin MW-NANO-APL-4L      | 1         | 0.52%   |
| RPi Raspberry Pi 400                | 1         | 0.52%   |
| PC Specialist Recoil II             | 1         | 0.52%   |
| PC Engines APU2                     | 1         | 0.52%   |
| PC Engines apu1                     | 1         | 0.52%   |
| Panasonic CFMX4-1                   | 1         | 0.52%   |
| Notebook N85_N87,HJ,HJ1,HK1         | 1         | 0.52%   |
| MSI MS-7D25                         | 1         | 0.52%   |
| MSI MS-7C52                         | 1         | 0.52%   |
| MSI MS-7B53                         | 1         | 0.52%   |
| MSI MS-7846                         | 1         | 0.52%   |
| MSI MS-7788                         | 1         | 0.52%   |
| MSI MS-7758                         | 1         | 0.52%   |
| MSI KBL-U Pro PRO24X (MS-AEC1)      | 1         | 0.52%   |
| Lenovo ThinkPad X260 20F5S10W0H     | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 14        | 7.25%   |
| Dell OEM-R                     | 11        | 5.7%    |
| Dell PowerEdge                 | 10        | 5.18%   |
| Unknown                        | 10        | 5.18%   |
| Dell Latitude                  | 9         | 4.66%   |
| HP t620                        | 8         | 4.15%   |
| Dell OptiPlex                  | 6         | 3.11%   |
| Fujitsu FUTRO                  | 4         | 2.07%   |
| Dell Wyse                      | 4         | 2.07%   |
| Lenovo ThinkCentre             | 3         | 1.55%   |
| Dell Vostro                    | 3         | 1.55%   |
| ASUS All                       | 3         | 1.55%   |
| ASRock Q1900B-ITX              | 3         | 1.55%   |
| ZOTAC ZBOX-CI329NANO           | 2         | 1.04%   |
| Lenovo IdeaPad                 | 2         | 1.04%   |
| Intel SHARKBAY                 | 2         | 1.04%   |
| Intel Q3XXG4-P                 | 2         | 1.04%   |
| HP ProLiant                    | 2         | 1.04%   |
| HP ENVY                        | 2         | 1.04%   |
| Gigabyte B450M                 | 2         | 1.04%   |
| Dell Inspiron                  | 2         | 1.04%   |
| Acer Aspire                    | 2         | 1.04%   |
| ZOTAC ZBOX-CI341               | 1         | 0.52%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.52%   |
| Wistron ProLiant               | 1         | 0.52%   |
| Toshiba PORTEGE                | 1         | 0.52%   |
| Supermicro X9SCL               | 1         | 0.52%   |
| Supermicro X7SLA               | 1         | 0.52%   |
| Supermicro X7DCL               | 1         | 0.52%   |
| Supermicro X11SSN-L            | 1         | 0.52%   |
| Supermicro SYS-5018D-FN8T      | 1         | 0.52%   |
| Supermicro Super               | 1         | 0.52%   |
| Sony SVF1521K1EB               | 1         | 0.52%   |
| Shuttle XH270                  | 1         | 0.52%   |
| Shuttle SZ270R9                | 1         | 0.52%   |
| Shuttle SZ270                  | 1         | 0.52%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.52%   |
| RPi Raspberry                  | 1         | 0.52%   |
| PC Specialist Recoil           | 1         | 0.52%   |
| PC Engines APU2                | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 41        | 21.24%  |
| 2019    | 19        | 9.84%   |
| 2018    | 19        | 9.84%   |
| 2020    | 15        | 7.77%   |
| 2016    | 14        | 7.25%   |
| 2012    | 14        | 7.25%   |
| 2021    | 13        | 6.74%   |
| 2009    | 11        | 5.7%    |
| 2013    | 10        | 5.18%   |
| 2011    | 9         | 4.66%   |
| 2017    | 7         | 3.63%   |
| 2015    | 6         | 3.11%   |
| 2022    | 3         | 1.55%   |
| 2010    | 3         | 1.55%   |
| 2006    | 3         | 1.55%   |
| 2008    | 2         | 1.04%   |
| 2007    | 2         | 1.04%   |
| Unknown | 2         | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 99        | 51.3%   |
| Notebook    | 48        | 24.87%  |
| Server      | 28        | 14.51%  |
| Mini pc     | 12        | 6.22%   |
| All in one  | 4         | 2.07%   |
| Convertible | 2         | 1.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 190       | 98.45%  |
| Yes  | 3         | 1.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 59        | 30.26%  |
| 8.01-16.0   | 50        | 25.64%  |
| 16.01-24.0  | 43        | 22.05%  |
| 64.01-256.0 | 16        | 8.21%   |
| 32.01-64.0  | 10        | 5.13%   |
| 2.01-3.0    | 7         | 3.59%   |
| 3.01-4.0    | 5         | 2.56%   |
| 24.01-32.0  | 2         | 1.03%   |
| 0.51-1.0    | 2         | 1.03%   |
| 1.01-2.0    | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 106       | 53.27%  |
| 0.51-1.0    | 47        | 23.62%  |
| 1.01-2.0    | 28        | 14.07%  |
| 2.01-3.0    | 5         | 2.51%   |
| 4.01-8.0    | 4         | 2.01%   |
| 8.01-16.0   | 3         | 1.51%   |
| 0           | 2         | 1.01%   |
| 3.01-4.0    | 1         | 0.5%    |
| 64.01-256.0 | 1         | 0.5%    |
| 16.01-24.0  | 1         | 0.5%    |
| Unknown     | 1         | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 107       | 53.5%   |
| 2      | 41        | 20.5%   |
| 0      | 28        | 14%     |
| 3      | 10        | 5%      |
| 4      | 5         | 2.5%    |
| 6      | 4         | 2%      |
| 5      | 3         | 1.5%    |
| 9      | 1         | 0.5%    |
| 8      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 80.51%  |
| Yes       | 38        | 19.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 96.37%  |
| No        | 7         | 3.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 56.63%  |
| Yes       | 85        | 43.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 75.51%  |
| Yes       | 48        | 24.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 193       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 33        | 16.02%  |
| Krakow                    | 17        | 8.25%   |
| Gdynia                    | 16        | 7.77%   |
| Gdansk                    | 16        | 7.77%   |
| Wroclaw                   | 11        | 5.34%   |
| Poznan                    | 7         | 3.4%    |
| Lodz                      | 5         | 2.43%   |
| Miedziana Gora            | 4         | 1.94%   |
| Legionowo                 | 3         | 1.46%   |
| Katowice                  | 3         | 1.46%   |
| Chrusty                   | 3         | 1.46%   |
| Е»ukowo                 | 2         | 0.97%   |
| Zgierz                    | 2         | 0.97%   |
| Kielce                    | 2         | 0.97%   |
| Glincz                    | 2         | 0.97%   |
| CzД™stochowa           | 2         | 0.97%   |
| ЕљwiД™tochЕ‚owice | 1         | 0.49%   |
| Zajaczki Pierwsze         | 1         | 0.49%   |
| Zagnansk                  | 1         | 0.49%   |
| WЕ‚ocЕ‚awek         | 1         | 0.49%   |
| Wschowa                   | 1         | 0.49%   |
| Wronowy                   | 1         | 0.49%   |
| Wolsztyn                  | 1         | 0.49%   |
| Wloszczowa                | 1         | 0.49%   |
| Wieliczka                 | 1         | 0.49%   |
| Walcz                     | 1         | 0.49%   |
| Tychy                     | 1         | 0.49%   |
| Szczytno                  | 1         | 0.49%   |
| Szczecin                  | 1         | 0.49%   |
| Świnoujście             | 1         | 0.49%   |
| Sulejowek                 | 1         | 0.49%   |
| Stopnica                  | 1         | 0.49%   |
| Stary Sacz                | 1         | 0.49%   |
| Starogard Gdański        | 1         | 0.49%   |
| Spalice                   | 1         | 0.49%   |
| Sosnowiec                 | 1         | 0.49%   |
| Siedlce                   | 1         | 0.49%   |
| RzeszГіw                | 1         | 0.49%   |
| RzeszÃ³w                | 1         | 0.49%   |
| Rybnik                    | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 63     | 14.48%  |
| WDC                 | 31        | 58     | 14.03%  |
| Seagate             | 24        | 45     | 10.86%  |
| SanDisk             | 13        | 15     | 5.88%   |
| GOODRAM             | 13        | 21     | 5.88%   |
| Toshiba             | 12        | 28     | 5.43%   |
| A-DATA Technology   | 10        | 11     | 4.52%   |
| Transcend           | 6         | 10     | 2.71%   |
| Kingston            | 6         | 6      | 2.71%   |
| Crucial             | 6         | 11     | 2.71%   |
| Innodisk            | 4         | 5      | 1.81%   |
| Hoodisk             | 4         | 6      | 1.81%   |
| Hitachi             | 4         | 4      | 1.81%   |
| SPCC                | 3         | 3      | 1.36%   |
| SK hynix            | 3         | 3      | 1.36%   |
| Plextor             | 3         | 3      | 1.36%   |
| OCZ                 | 3         | 3      | 1.36%   |
| NVMe                | 3         | 5      | 1.36%   |
| LITEON              | 3         | 3      | 1.36%   |
| Intel               | 3         | 5      | 1.36%   |
| HGST                | 3         | 5      | 1.36%   |
| Hewlett-Packard     | 3         | 3      | 1.36%   |
| Gigabyte Technology | 3         | 3      | 1.36%   |
| Corsair             | 3         | 3      | 1.36%   |
| Apacer              | 3         | 3      | 1.36%   |
| PNY                 | 2         | 3      | 0.9%    |
| Patriot             | 2         | 2      | 0.9%    |
| Micron Technology   | 2         | 8      | 0.9%    |
| Kston               | 2         | 2      | 0.9%    |
| Intenso             | 2         | 2      | 0.9%    |
| China               | 2         | 3      | 0.9%    |
| Team                | 1         | 1      | 0.45%   |
| SSSTC               | 1         | 2      | 0.45%   |
| SSDPR-CX            | 1         | 1      | 0.45%   |
| Phison              | 1         | 1      | 0.45%   |
| LITEONIT            | 1         | 1      | 0.45%   |
| KIOXIA              | 1         | 1      | 0.45%   |
| FORESEE             | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung HM321HI 320GB              | 5         | 2.05%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 1.23%   |
| Samsung SSD 850 EVO 250GB          | 3         | 1.23%   |
| GOODRAM SSDPR-CX400-128 128GB      | 3         | 1.23%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.82%   |
| WDC WD20SDZW-11JJ8S0 2TB           | 2         | 0.82%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2         | 0.82%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.82%   |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.82%   |
| Transcend TS120GMTS420S 120GB      | 2         | 0.82%   |
| Toshiba MQ04ABF100 1TB             | 2         | 0.82%   |
| SPCC Solid State Disk 256GB        | 2         | 0.82%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.82%   |
| Seagate ST2000DL003-9VT166 2TB     | 2         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.82%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 2         | 0.82%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.82%   |
| Patriot Burst 120GB                | 2         | 0.82%   |
| Kingston SUV500MS120G 120GB        | 2         | 0.82%   |
| Intenso SSD SATAIII 120GB          | 2         | 0.82%   |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 2         | 0.82%   |
| Hoodisk SSD 128GB                  | 2         | 0.82%   |
| Goodram SSDPR-CL100-120-G3 120GB   | 2         | 0.82%   |
| Goodram SSDPR-CL100-120-G2 120GB   | 2         | 0.82%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.82%   |
| Corsair CMFSSD-256D1 256GB         | 2         | 0.82%   |
| China SATA SSD 64GB                | 2         | 0.82%   |
| Apacer AS340 240GB                 | 2         | 0.82%   |
| A-DATA SU800 256GB                 | 2         | 0.82%   |
| WDC WD7500BPKT-22PK4T0 752GB       | 1         | 0.41%   |
| WDC WD5000LPVT-75G33T0 500GB       | 1         | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.41%   |
| WDC WD5000BPVT-08HXZT3 500GB       | 1         | 0.41%   |
| WDC WD360ADFD-00NLR5 37GB          | 1         | 0.41%   |
| WDC WD360ADFD-00NLR1 37GB          | 1         | 0.41%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 0.41%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1         | 0.41%   |
| WDC WD3200AAVS-00ZTB0 320GB        | 1         | 0.41%   |
| WDC WD30EZRZ-00Z5HB0 3TB           | 1         | 0.41%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 48     | 32.94%  |
| Seagate             | 24        | 45     | 28.24%  |
| Toshiba             | 10        | 26     | 11.76%  |
| Samsung Electronics | 10        | 16     | 11.76%  |
| Hitachi             | 4         | 4      | 4.71%   |
| HGST                | 3         | 5      | 3.53%   |
| NVMe                | 2         | 2      | 2.35%   |
| Hewlett-Packard     | 2         | 2      | 2.35%   |
| SSDPR-CX            | 1         | 1      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 40     | 15.38%  |
| SanDisk             | 13        | 15     | 11.11%  |
| GOODRAM             | 12        | 20     | 10.26%  |
| A-DATA Technology   | 7         | 7      | 5.98%   |
| Kingston            | 6         | 6      | 5.13%   |
| Transcend           | 5         | 9      | 4.27%   |
| Crucial             | 5         | 10     | 4.27%   |
| Innodisk            | 4         | 5      | 3.42%   |
| Hoodisk             | 4         | 6      | 3.42%   |
| SPCC                | 3         | 3      | 2.56%   |
| Plextor             | 3         | 3      | 2.56%   |
| OCZ                 | 3         | 3      | 2.56%   |
| Gigabyte Technology | 3         | 3      | 2.56%   |
| Corsair             | 3         | 3      | 2.56%   |
| Apacer              | 3         | 3      | 2.56%   |
| WDC                 | 2         | 9      | 1.71%   |
| SK hynix            | 2         | 2      | 1.71%   |
| Patriot             | 2         | 2      | 1.71%   |
| Micron Technology   | 2         | 8      | 1.71%   |
| LITEON              | 2         | 2      | 1.71%   |
| Kston               | 2         | 2      | 1.71%   |
| Intenso             | 2         | 2      | 1.71%   |
| Intel               | 2         | 4      | 1.71%   |
| China               | 2         | 3      | 1.71%   |
| Toshiba             | 1         | 1      | 0.85%   |
| Team                | 1         | 1      | 0.85%   |
| Phison              | 1         | 1      | 0.85%   |
| NVMe                | 1         | 1      | 0.85%   |
| LITEONIT            | 1         | 1      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |
| FORESEE             | 1         | 1      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 103       | 177    | 54.21%  |
| HDD  | 67        | 150    | 35.26%  |
| NVMe | 20        | 27     | 10.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 149       | 327    | 88.17%  |
| NVMe | 20        | 27     | 11.83%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 125       | 211    | 70.62%  |
| 0.51-1.0   | 29        | 51     | 16.38%  |
| 1.01-2.0   | 14        | 35     | 7.91%   |
| 3.01-4.0   | 3         | 8      | 1.69%   |
| 2.01-3.0   | 3         | 13     | 1.69%   |
| 4.01-10.0  | 3         | 9      | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 34.8%   |
| 51-100         | 33        | 16.18%  |
| 251-500        | 32        | 15.69%  |
| 1-20           | 32        | 15.69%  |
| 21-50          | 18        | 8.82%   |
| 501-1000       | 11        | 5.39%   |
| 1001-2000      | 3         | 1.47%   |
| More than 3000 | 2         | 0.98%   |
| 2001-3000      | 2         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 177       | 89.39%  |
| 21-50     | 9         | 4.55%   |
| 101-250   | 5         | 2.53%   |
| 51-100    | 5         | 2.53%   |
| 1001-2000 | 2         | 1.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                    | 2         | 2      | 6.67%   |
| WDC WD360ADFD-00NLR1 37GB                 | 1         | 1      | 3.33%   |
| WDC WD3200AAVS-00ZTB0 320GB               | 1         | 1      | 3.33%   |
| WDC WD2500AAKX-753CA0 250GB               | 1         | 1      | 3.33%   |
| WDC WD2500AAKX-083CA1 250GB               | 1         | 2      | 3.33%   |
| WDC WD20EURS-63S48Y0 2TB                  | 1         | 1      | 3.33%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 3.33%   |
| WDC WD1600BEVE-00UYT0 160GB               | 1         | 1      | 3.33%   |
| WDC WD1600AAJS-40H3A0 160GB               | 1         | 1      | 3.33%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1      | 3.33%   |
| WDC WD10EARS-003BB1 1TB                   | 1         | 1      | 3.33%   |
| Toshiba THNSNK512GVN8 512GB               | 1         | 1      | 3.33%   |
| Toshiba MK3261GSYN 320GB                  | 1         | 1      | 3.33%   |
| SPCC Solid State Disk 256GB               | 1         | 1      | 3.33%   |
| SK hynix SC308 SATA 256GB                 | 1         | 1      | 3.33%   |
| Seagate ST96812AS 64GB                    | 1         | 4      | 3.33%   |
| Seagate ST9500420AS 500GB                 | 1         | 2      | 3.33%   |
| Seagate ST9160412AS 160GB                 | 1         | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 3.33%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.33%   |
| Seagate ST32000542AS 2TB                  | 1         | 1      | 3.33%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 3.33%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 3.33%   |
| Samsung Electronics HD154UI 1.5TB         | 1         | 1      | 3.33%   |
| Plextor PX-128G7Ne 128GB                  | 1         | 1      | 3.33%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB | 1         | 1      | 3.33%   |
| Hitachi HTS721060G9SA00 64GB              | 1         | 1      | 3.33%   |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 33.33%  |
| Seagate             | 8         | 12     | 26.67%  |
| Toshiba             | 4         | 4      | 13.33%  |
| Samsung Electronics | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| SPCC                | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Plextor             | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 41.67%  |
| Seagate             | 8         | 12     | 33.33%  |
| Toshiba             | 3         | 3      | 12.5%   |
| Hitachi             | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 29     | 79.31%  |
| SSD  | 6         | 6      | 20.69%  |

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
| Works    | 148       | 308    | 80%     |
| Malfunc  | 28        | 35     | 15.14%  |
| Detected | 8         | 10     | 4.32%   |
| Failed   | 1         | 1      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 135       | 61.64%  |
| AMD                            | 30        | 13.7%   |
| Broadcom / LSI                 | 22        | 10.05%  |
| Samsung Electronics            | 6         | 2.74%   |
| SanDisk                        | 3         | 1.37%   |
| Silicon Motion                 | 2         | 0.91%   |
| Phison Electronics             | 2         | 0.91%   |
| Nvidia                         | 2         | 0.91%   |
| KIOXIA                         | 2         | 0.91%   |
| Hewlett-Packard                | 2         | 0.91%   |
| VIA Technologies               | 1         | 0.46%   |
| Solid State Storage Technology | 1         | 0.46%   |
| SK hynix                       | 1         | 0.46%   |
| Realtek Semiconductor          | 1         | 0.46%   |
| Micron/Crucial Technology      | 1         | 0.46%   |
| Marvell Technology Group       | 1         | 0.46%   |
| Lite-On Technology             | 1         | 0.46%   |
| JMicron Technology             | 1         | 0.46%   |
| Integrated Technology Express  | 1         | 0.46%   |
| ASMedia Technology             | 1         | 0.46%   |
| Apple                          | 1         | 0.46%   |
| ADATA Technology               | 1         | 0.46%   |
| Unknown                        | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 8.79%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 13        | 5.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 4.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 4.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8         | 3.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 2.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 2.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 2.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.67%   |
| Unknown                                                                          | 4         | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.26%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.26%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 3         | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.84%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.84%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.84%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.84%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 0.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 0.84%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 2         | 0.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.84%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 2         | 0.84%   |
| Broadcom / LSI MegaRAID SAS 2008 [Falcon]                                        | 2         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 144       | 65.45%  |
| RAID | 26        | 11.82%  |
| NVMe | 23        | 10.45%  |
| IDE  | 23        | 10.45%  |
| SAS  | 2         | 0.91%   |
| SCSI | 2         | 0.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 154       | 79.79%  |
| AMD     | 35        | 18.13%  |
| ARM     | 3         | 1.55%   |
| PowerPC | 1         | 0.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz      | 11        | 5.67%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 8         | 4.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 5         | 2.58%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 4         | 2.06%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 4         | 2.06%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 3         | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 1.55%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 1.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 3         | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 1.55%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 3         | 1.55%   |
| Intel Pentium CPU G860 @ 3.00GHz         | 2         | 1.03%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 2         | 1.03%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 2         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.03%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 2         | 1.03%   |
| Intel Core 2 Duo                         | 2         | 1.03%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 2         | 1.03%   |
| ARM Cortex-A72 r0p3                      | 2         | 1.03%   |
| AMD Ryzen 3 3100 4-Core Processor        | 2         | 1.03%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 2         | 1.03%   |
| PowerPC 7447A (Revision 0x102)           | 1         | 0.52%   |
| Intel Xeon E-2386G CPU @ 3.50GHz         | 1         | 0.52%   |
| Intel Xeon CPU X5660 @ 2.80GHz           | 1         | 0.52%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.52%   |
| Intel Xeon CPU X3360 @ 2.83GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5520 @ 2.27GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5410 @ 2.33GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz      | 1         | 0.52%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz       | 1         | 0.52%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz      | 1         | 0.52%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz      | 1         | 0.52%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.52%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz       | 1         | 0.52%   |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz      | 1         | 0.52%   |
| Intel Xeon CPU E31225 @ 3.10GH           | 1         | 0.52%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 1         | 0.52%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1         | 0.52%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 22.16%  |
| Intel Xeon              | 30        | 15.46%  |
| Intel Celeron           | 22        | 11.34%  |
| Intel Core i7           | 14        | 7.22%   |
| Intel Core i3           | 13        | 6.7%    |
| AMD GX                  | 13        | 6.7%    |
| Intel Core 2 Duo        | 9         | 4.64%   |
| Intel Pentium           | 8         | 4.12%   |
| Intel Atom              | 5         | 2.58%   |
| Other                   | 4         | 2.06%   |
| Intel Pentium Silver    | 4         | 2.06%   |
| ARM Cortex              | 3         | 1.55%   |
| AMD Ryzen 5             | 3         | 1.55%   |
| AMD Ryzen 3             | 3         | 1.55%   |
| AMD G                   | 3         | 1.55%   |
| AMD Ryzen 7             | 2         | 1.03%   |
| AMD E                   | 2         | 1.03%   |
| Intel Pentium M         | 1         | 0.52%   |
| Intel Pentium Dual-Core | 1         | 0.52%   |
| Intel Core 2            | 1         | 0.52%   |
| Intel Celeron M         | 1         | 0.52%   |
| AMD Ryzen Embedded      | 1         | 0.52%   |
| AMD Ryzen 9             | 1         | 0.52%   |
| AMD Ryzen 7 PRO         | 1         | 0.52%   |
| AMD Ryzen 5 PRO         | 1         | 0.52%   |
| AMD Phenom II X6        | 1         | 0.52%   |
| AMD Phenom II X4        | 1         | 0.52%   |
| AMD Athlon 64 X2        | 1         | 0.52%   |
| AMD Athlon              | 1         | 0.52%   |
| AMD A4                  | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 76        | 39.18%  |
| 2       | 58        | 29.9%   |
| Unknown | 15        | 7.73%   |
| 16      | 13        | 6.7%    |
| 8       | 11        | 5.67%   |
| 12      | 7         | 3.61%   |
| 6       | 7         | 3.61%   |
| 1       | 5         | 2.58%   |
| 24      | 1         | 0.52%   |
| 20      | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 159       | 82.38%  |
| 2       | 23        | 11.92%  |
| Unknown | 11        | 5.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 95        | 48.97%  |
| 2       | 80        | 41.24%  |
| Unknown | 19        | 9.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 28        | 14.43%  |
| KabyLake      | 19        | 9.79%   |
| Haswell       | 18        | 9.28%   |
| SandyBridge   | 16        | 8.25%   |
| Penryn        | 15        | 7.73%   |
| Jaguar        | 13        | 6.7%    |
| Goldmont plus | 11        | 5.67%   |
| Skylake       | 10        | 5.15%   |
| Silvermont    | 10        | 5.15%   |
| Unknown       | 7         | 3.61%   |
| Zen 2         | 5         | 2.58%   |
| Goldmont      | 5         | 2.58%   |
| Bobcat        | 5         | 2.58%   |
| Westmere      | 4         | 2.06%   |
| Broadwell     | 4         | 2.06%   |
| Zen           | 3         | 1.55%   |
| Bonnell       | 3         | 1.55%   |
| Zen+          | 2         | 1.03%   |
| Zen 3         | 2         | 1.03%   |
| Puma          | 2         | 1.03%   |
| P6            | 2         | 1.03%   |
| Nehalem       | 2         | 1.03%   |
| K10           | 2         | 1.03%   |
| CometLake     | 2         | 1.03%   |
| TigerLake     | 1         | 0.52%   |
| NetBurst      | 1         | 0.52%   |
| K8 Hammer     | 1         | 0.52%   |
| Core          | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 111       | 54.15%  |
| AMD                                          | 41        | 20%     |
| Nvidia                                       | 25        | 12.2%   |
| Matrox Electronics Systems                   | 23        | 11.22%  |
| ASPEED Technology                            | 3         | 1.46%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.49%   |
| VIA Technologies                             | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems G200eR2                                                       | 16        | 7.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.37%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 8         | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 3.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 3.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 2.91%   |
| Intel HD Graphics 530                                                                    | 5         | 2.43%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4         | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.94%   |
| Intel HD Graphics 500                                                                    | 4         | 1.94%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.46%   |
| Intel HD Graphics 630                                                                    | 3         | 1.46%   |
| Intel HD Graphics 620                                                                    | 3         | 1.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.46%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.46%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 1.46%   |
| AMD ES1000                                                                               | 3         | 1.46%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.97%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.97%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.97%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.97%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.97%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.97%   |
| AMD Renoir                                                                               | 2         | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.97%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2         | 0.97%   |
| AMD Cezanne                                                                              | 2         | 0.97%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1         | 0.49%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 85        | 43.59%  |
| 1 x AMD        | 37        | 18.97%  |
| 1 x Matrox     | 23        | 11.79%  |
| 1 x Nvidia     | 13        | 6.67%   |
| Intel + Nvidia | 13        | 6.67%   |
| 2 x Intel      | 10        | 5.13%   |
| Other          | 6         | 3.08%   |
| Intel + AMD    | 3         | 1.54%   |
| 1 x ASPEED     | 2         | 1.03%   |
| 1 x XGI        | 1         | 0.51%   |
| 1 x VIA        | 1         | 0.51%   |
| AMD + ASPEED   | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 172       | 88.66%  |
| Proprietary | 11        | 5.67%   |
| Unknown     | 11        | 5.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 173       | 89.18%  |
| 1.01-2.0   | 6         | 3.09%   |
| 3.01-4.0   | 5         | 2.58%   |
| 7.01-8.0   | 3         | 1.55%   |
| 0.01-0.5   | 3         | 1.55%   |
| 0.51-1.0   | 2         | 1.03%   |
| 5.01-6.0   | 1         | 0.52%   |
| 8.01-16.0  | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 18.18%  |
| Lenovo                  | 7         | 9.09%   |
| Samsung Electronics     | 6         | 7.79%   |
| BOE                     | 6         | 7.79%   |
| NEC Computers           | 5         | 6.49%   |
| Dell                    | 4         | 5.19%   |
| Acer                    | 4         | 5.19%   |
| Philips                 | 3         | 3.9%    |
| Chimei Innolux          | 3         | 3.9%    |
| AU Optronics            | 3         | 3.9%    |
| Iiyama                  | 2         | 2.6%    |
| Goldstar                | 2         | 2.6%    |
| Chi Mei Optoelectronics | 2         | 2.6%    |
| BenQ                    | 2         | 2.6%    |
| Apple                   | 2         | 2.6%    |
| AOC                     | 2         | 2.6%    |
| Vestel Elektronik       | 1         | 1.3%    |
| Toshiba                 | 1         | 1.3%    |
| Sharp                   | 1         | 1.3%    |
| PANDA                   | 1         | 1.3%    |
| KTC                     | 1         | 1.3%    |
| JDI                     | 1         | 1.3%    |
| InfoVision              | 1         | 1.3%    |
| HPN                     | 1         | 1.3%    |
| Hewlett-Packard         | 1         | 1.3%    |
| Eizo                    | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 5         | 6.49%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 2.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 2.6%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 1         | 1.3%    |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                        | 1         | 1.3%    |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                  | 1         | 1.3%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch        | 1         | 1.3%    |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch     | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch    | 1         | 1.3%    |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 1.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 1.3%    |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch                | 1         | 1.3%    |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 1.3%    |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch               | 1         | 1.3%    |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch            | 1         | 1.3%    |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch             | 1         | 1.3%    |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch              | 1         | 1.3%    |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch                 | 1         | 1.3%    |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 1.3%    |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.3%    |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 1.3%    |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.3%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.3%    |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 1         | 1.3%    |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.3%    |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 1.3%    |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.3%    |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                  | 1         | 1.3%    |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 41.1%   |
| 1366x768 (WXGA)    | 17        | 23.29%  |
| 1280x800 (WXGA)    | 7         | 9.59%   |
| 3840x2160 (4K)     | 4         | 5.48%   |
| 1680x1050 (WSXGA+) | 3         | 4.11%   |
| 1600x900 (HD+)     | 3         | 4.11%   |
| 2560x1440 (QHD)    | 2         | 2.74%   |
| 1920x540           | 2         | 2.74%   |
| 1920x1200 (WUXGA)  | 2         | 2.74%   |
| 2560x1080          | 1         | 1.37%   |
| 1440x900 (WXGA+)   | 1         | 1.37%   |
| 1280x1024 (SXGA)   | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 24%     |
| 12      | 12        | 16%     |
| 13      | 10        | 13.33%  |
| 24      | 6         | 8%      |
| 23      | 5         | 6.67%   |
| 21      | 5         | 6.67%   |
| 27      | 3         | 4%      |
| 18      | 3         | 4%      |
| 42      | 2         | 2.67%   |
| 31      | 2         | 2.67%   |
| 17      | 2         | 2.67%   |
| 50      | 1         | 1.33%   |
| 40      | 1         | 1.33%   |
| 28      | 1         | 1.33%   |
| 22      | 1         | 1.33%   |
| 20      | 1         | 1.33%   |
| 14      | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 37.84%  |
| 501-600     | 13        | 17.57%  |
| 201-300     | 13        | 17.57%  |
| 401-500     | 10        | 13.51%  |
| 601-700     | 3         | 4.05%   |
| 351-400     | 2         | 2.7%    |
| 901-1000    | 2         | 2.7%    |
| 801-900     | 1         | 1.35%   |
| 1001-1500   | 1         | 1.35%   |
| Unknown     | 1         | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 53        | 75.71%  |
| 16/10   | 12        | 17.14%  |
| 3/2     | 2         | 2.86%   |
| 5/4     | 1         | 1.43%   |
| 21/9    | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 13        | 17.57%  |
| 91-100         | 13        | 17.57%  |
| 61-70          | 12        | 16.22%  |
| 81-90          | 11        | 14.86%  |
| 101-110        | 5         | 6.76%   |
| 251-300        | 4         | 5.41%   |
| 301-350        | 3         | 4.05%   |
| 141-150        | 3         | 4.05%   |
| 501-1000       | 3         | 4.05%   |
| 351-500        | 2         | 2.7%    |
| 151-200        | 2         | 2.7%    |
| More than 1000 | 1         | 1.35%   |
| 121-130        | 1         | 1.35%   |
| Unknown        | 1         | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 28        | 38.89%  |
| 51-100  | 22        | 30.56%  |
| 101-120 | 15        | 20.83%  |
| 161-240 | 4         | 5.56%   |
| 1-50    | 2         | 2.78%   |
| Unknown | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 126       | 64.62%  |
| 1     | 61        | 31.28%  |
| 2     | 7         | 3.59%   |
| 3     | 1         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 120       | 40.54%  |
| Realtek Semiconductor             | 88        | 29.73%  |
| Broadcom                          | 38        | 12.84%  |
| Qualcomm Atheros                  | 21        | 7.09%   |
| Qualcomm Atheros Communications   | 5         | 1.69%   |
| TP-Link                           | 2         | 0.68%   |
| Emulex                            | 2         | 0.68%   |
| Dell                              | 2         | 0.68%   |
| Xiaomi                            | 1         | 0.34%   |
| VIA Technologies                  | 1         | 0.34%   |
| Van Ooijen Technische Informatica | 1         | 0.34%   |
| U-Blox                            | 1         | 0.34%   |
| Sierra Wireless                   | 1         | 0.34%   |
| Ralink Technology                 | 1         | 0.34%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.34%   |
| Nvidia                            | 1         | 0.34%   |
| Nuvoton                           | 1         | 0.34%   |
| NetGear                           | 1         | 0.34%   |
| Mellanox Technologies             | 1         | 0.34%   |
| IMC Networks                      | 1         | 0.34%   |
| Huawei Technologies               | 1         | 0.34%   |
| D-Link System                     | 1         | 0.34%   |
| Atheros                           | 1         | 0.34%   |
| Apple                             | 1         | 0.34%   |
| American Megatrends               | 1         | 0.34%   |
| AMD                               | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 79        | 22.64%  |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 16        | 4.58%   |
| Intel I211 Gigabit Network Connection                                         | 14        | 4.01%   |
| Intel I350 Gigabit Network Connection                                         | 13        | 3.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 3.15%   |
| Intel I210 Gigabit Network Connection                                         | 10        | 2.87%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 2.29%   |
| Intel 82567LM Gigabit Network Connection                                      | 7         | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 1.43%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.43%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 4         | 1.15%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.15%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4         | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 0.86%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 0.86%   |
| Intel Wireless 8260                                                           | 3         | 0.86%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 0.86%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 0.86%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 0.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 0.57%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 0.57%   |
| Intel Wireless 7260                                                           | 2         | 0.57%   |
| Intel Ethernet Controller X550                                                | 2         | 0.57%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 48.94%  |
| Qualcomm Atheros                | 17        | 18.09%  |
| Broadcom                        | 10        | 10.64%  |
| Realtek Semiconductor           | 7         | 7.45%   |
| Qualcomm Atheros Communications | 5         | 5.32%   |
| TP-Link                         | 2         | 2.13%   |
| Dell                            | 2         | 2.13%   |
| Ralink Technology               | 1         | 1.06%   |
| NetGear                         | 1         | 1.06%   |
| IMC Networks                    | 1         | 1.06%   |
| D-Link System                   | 1         | 1.06%   |
| Atheros                         | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 5.32%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 5.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 5.32%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 4         | 4.26%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4         | 4.26%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 3.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 3.19%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 3.19%   |
| Intel Wireless 8260                                                           | 3         | 3.19%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 2.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 2.13%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.13%   |
| Intel Wireless 7260                                                           | 2         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.06%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.06%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.06%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1         | 1.06%   |
| Intel Wireless-AC 9260                                                        | 1         | 1.06%   |
| Intel Wireless 7265                                                           | 1         | 1.06%   |
| Intel Wireless 3165                                                           | 1         | 1.06%   |
| Intel Wireless 3160                                                           | 1         | 1.06%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.06%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.06%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.06%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.06%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 99        | 44%     |
| Realtek Semiconductor         | 84        | 37.33%  |
| Broadcom                      | 29        | 12.89%  |
| Qualcomm Atheros              | 4         | 1.78%   |
| Emulex                        | 2         | 0.89%   |
| Xiaomi                        | 1         | 0.44%   |
| VIA Technologies              | 1         | 0.44%   |
| OnePlus Technology (Shenzhen) | 1         | 0.44%   |
| Nvidia                        | 1         | 0.44%   |
| Apple                         | 1         | 0.44%   |
| American Megatrends           | 1         | 0.44%   |
| AMD                           | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 79        | 31.85%  |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 16        | 6.45%   |
| Intel I211 Gigabit Network Connection                                         | 14        | 5.65%   |
| Intel I350 Gigabit Network Connection                                         | 13        | 5.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 4.44%   |
| Intel I210 Gigabit Network Connection                                         | 10        | 4.03%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 3.23%   |
| Intel 82567LM Gigabit Network Connection                                      | 7         | 2.82%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 1.61%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 1.61%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 1.21%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 1.21%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 1.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.81%   |
| Intel Ethernet Controller X550                                                | 2         | 0.81%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.81%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.81%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.81%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 0.81%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 2         | 0.81%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 2         | 0.81%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.4%    |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data                  | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.4%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1         | 0.4%    |
| Intel Ethernet Controller I225-V                                              | 1         | 0.4%    |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 1         | 0.4%    |
| Intel Ethernet Connection I217-V                                              | 1         | 0.4%    |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 186       | 66.91%  |
| WiFi     | 85        | 30.58%  |
| Modem    | 4         | 1.44%   |
| Unknown  | 3         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 75.45%  |
| WiFi     | 54        | 24.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 75        | 38.46%  |
| 1     | 42        | 21.54%  |
| 4     | 27        | 13.85%  |
| 3     | 22        | 11.28%  |
| 6     | 15        | 7.69%   |
| 5     | 9         | 4.62%   |
| 0     | 3         | 1.54%   |
| 14    | 1         | 0.51%   |
| 8     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 192       | 97.96%  |
| Yes  | 4         | 2.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 54.17%  |
| Broadcom                        | 4         | 8.33%   |
| Qualcomm Atheros Communications | 3         | 6.25%   |
| IMC Networks                    | 3         | 6.25%   |
| Foxconn / Hon Hai               | 2         | 4.17%   |
| Cambridge Silicon Radio         | 2         | 4.17%   |
| ASUSTek Computer                | 2         | 4.17%   |
| Apple                           | 2         | 4.17%   |
| Realtek Semiconductor           | 1         | 2.08%   |
| Qcom                            | 1         | 2.08%   |
| Hewlett-Packard                 | 1         | 2.08%   |
| Dell                            | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 7         | 14.58%  |
| Intel Bluetooth wireless interface                     | 6         | 12.5%   |
| Intel AX201 Bluetooth                                  | 6         | 12.5%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]     | 3         | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                       | 2         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 2         | 4.17%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter       | 2         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 2         | 4.17%   |
| Apple Apple Broadcom Built-in Bluetooth                | 2         | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 2.08%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                | 1         | 2.08%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device   | 1         | 2.08%   |
| Qualcomm Atheros AR9462 Bluetooth                      | 1         | 2.08%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device     | 1         | 2.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1         | 2.08%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 2.08%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 2.08%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 2.08%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter             | 1         | 2.08%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth          | 1         | 2.08%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 2.08%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 2.08%   |
| Broadcom BCM43142A0 Bluetooth Module                   | 1         | 2.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 1         | 2.08%   |
| ASUS ASUS USB-BT500                                    | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 110       | 66.27%  |
| AMD                   | 35        | 21.08%  |
| Nvidia                | 14        | 8.43%   |
| C-Media Electronics   | 2         | 1.2%    |
| VIA Technologies      | 1         | 0.6%    |
| ROCCAT                | 1         | 0.6%    |
| Realtek Semiconductor | 1         | 0.6%    |
| Creative Technology   | 1         | 0.6%    |
| Creative Labs         | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.9%    |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 6.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 5.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 4.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 4.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 4.43%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 3.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 2.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 2.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.97%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.48%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.48%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.99%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.99%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.99%   |
| Unknown                                                                                           | 2         | 0.99%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.49%   |
| ROCCAT USB PnP Sound Device                                                                       | 1         | 0.49%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                                                  | 1         | 0.49%   |
| Nvidia unknown                                                                                    | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 50        | 25.77%  |
| SK hynix            | 33        | 17.01%  |
| Kingston            | 25        | 12.89%  |
| Goodram             | 17        | 8.76%   |
| Unknown             | 16        | 8.25%   |
| Micron Technology   | 14        | 7.22%   |
| Crucial             | 10        | 5.15%   |
| Ramaxel Technology  | 5         | 2.58%   |
| Corsair             | 4         | 2.06%   |
| G.Skill             | 3         | 1.55%   |
| Patriot             | 2         | 1.03%   |
| Nanya Technology    | 2         | 1.03%   |
| Unknown             | 2         | 1.03%   |
| Unknown (07FB)      | 1         | 0.52%   |
| Transcend           | 1         | 0.52%   |
| Toshiba             | 1         | 0.52%   |
| Qimonda             | 1         | 0.52%   |
| Kimtigo             | 1         | 0.52%   |
| Innodisk            | 1         | 0.52%   |
| Hewlett-Packard     | 1         | 0.52%   |
| GeIL                | 1         | 0.52%   |
| Elpida              | 1         | 0.52%   |
| A-DATA Technology   | 1         | 0.52%   |
| A-DA                | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M393B1G70QH0-YK0 8GB DIMM DDR3 1600MT/s          | 13        | 6.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 4         | 1.91%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 4         | 1.91%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3         | 1.44%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3         | 1.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 3         | 1.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2         | 0.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.96%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 2         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 0.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 2         | 0.96%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2         | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.96%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 0.96%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s      | 2         | 0.96%   |
| Goodram RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s         | 2         | 0.96%   |
| Goodram RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s        | 2         | 0.96%   |
| Crucial RAM CT4G4SFS8266.M8FG 4GB SODIMM DDR4 2667MT/s       | 2         | 0.96%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 0.96%   |
| Unknown                                                      | 2         | 0.96%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DDR                          | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1         | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR                            | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1         | 0.48%   |
| Unknown RAM Module 16384MB DIMM DDR3 800MT/s                 | 1         | 0.48%   |
| Unknown RAM 8G2400MHz 8GB SODIMM DDR4 2400MT/s               | 1         | 0.48%   |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s | 1         | 0.48%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 103       | 60.59%  |
| DDR4    | 51        | 30%     |
| DDR2    | 7         | 4.12%   |
| Unknown | 3         | 1.76%   |
| DDR     | 2         | 1.18%   |
| SDRAM   | 1         | 0.59%   |
| LPDDR4  | 1         | 0.59%   |
| LPDDR3  | 1         | 0.59%   |
| DRAM    | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 85        | 50%     |
| DIMM         | 82        | 48.24%  |
| Row Of Chips | 2         | 1.18%   |
| FB-DIMM      | 1         | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 66        | 36.46%  |
| 8192  | 62        | 34.25%  |
| 2048  | 29        | 16.02%  |
| 16384 | 14        | 7.73%   |
| 1024  | 7         | 3.87%   |
| 512   | 2         | 1.1%    |
| 32768 | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 65        | 35.33%  |
| 1333    | 28        | 15.22%  |
| 2400    | 20        | 10.87%  |
| 2667    | 13        | 7.07%   |
| 3200    | 11        | 5.98%   |
| 2133    | 10        | 5.43%   |
| 1334    | 6         | 3.26%   |
| 800     | 6         | 3.26%   |
| 667     | 6         | 3.26%   |
| 1867    | 4         | 2.17%   |
| 1067    | 4         | 2.17%   |
| Unknown | 3         | 1.63%   |
| 2666    | 2         | 1.09%   |
| 1866    | 2         | 1.09%   |
| 1066    | 2         | 1.09%   |
| 533     | 1         | 0.54%   |
| 400     | 1         | 0.54%   |

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
| Chicony Electronics                    | 14        | 34.15%  |
| Microdia                               | 8         | 19.51%  |
| Realtek Semiconductor                  | 4         | 9.76%   |
| Acer                                   | 3         | 7.32%   |
| Sunplus Innovation Technology          | 2         | 4.88%   |
| Ricoh                                  | 2         | 4.88%   |
| Logitech                               | 2         | 4.88%   |
| Lite-On Technology                     | 2         | 4.88%   |
| Syntek                                 | 1         | 2.44%   |
| Hewlett-Packard                        | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.44%   |
| Apple                                  | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                     | 3         | 7.32%   |
| Microdia Integrated Webcam                                    | 3         | 7.32%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 4.88%   |
| Logitech HD Pro Webcam C920                                   | 2         | 4.88%   |
| Lite-On Integrated Camera                                     | 2         | 4.88%   |
| Chicony Integrated Camera (1280x720@30)                       | 2         | 4.88%   |
| Chicony Integrated Camera                                     | 2         | 4.88%   |
| Syntek Lenovo EasyCamera                                      | 1         | 2.44%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 2.44%   |
| Sunplus Integrated_Webcam_FHD                                 | 1         | 2.44%   |
| Ricoh Integrated Webcam                                       | 1         | 2.44%   |
| Ricoh HD Webcam                                               | 1         | 2.44%   |
| Realtek Integrated_Webcam_HD                                  | 1         | 2.44%   |
| Microdia USB 2.0 Camera                                       | 1         | 2.44%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 2.44%   |
| Microdia Dell Integrated HD Webcam                            | 1         | 2.44%   |
| HP Premium Starter Webcam                                     | 1         | 2.44%   |
| Chicony ThinkPad T490 Webcam                                  | 1         | 2.44%   |
| Chicony Realtek DMFT - RGB                                    | 1         | 2.44%   |
| Chicony Integrated Camera [ThinkPad]                          | 1         | 2.44%   |
| Chicony HP Wide Vision HD Camera                              | 1         | 2.44%   |
| Chicony HP Integrated Webcam                                  | 1         | 2.44%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 2.44%   |
| Chicony HD Webcam                                             | 1         | 2.44%   |
| Chicony Front Camera                                          | 1         | 2.44%   |
| Chicony Chicony USB2.0 Camera                                 | 1         | 2.44%   |
| Chicony 1.3M Webcam                                           | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M WebCam | 1         | 2.44%   |
| Apple FaceTime HD Camera (Built-in)                           | 1         | 2.44%   |
| Acer USB HD Webcam                                            | 1         | 2.44%   |
| Acer Lenovo EasyCamera                                        | 1         | 2.44%   |
| Acer EasyCamera                                               | 1         | 2.44%   |

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
| 1     | 72        | 36.55%  |
| 0     | 57        | 28.93%  |
| 2     | 50        | 25.38%  |
| 3     | 10        | 5.08%   |
| 4     | 5         | 2.54%   |
| 5     | 2         | 1.02%   |
| 6     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 120       | 58.54%  |
| Bluetooth                | 21        | 10.24%  |
| Net/wireless             | 20        | 9.76%   |
| Fingerprint reader       | 11        | 5.37%   |
| Card reader              | 11        | 5.37%   |
| Graphics card            | 9         | 4.39%   |
| Firewire controller      | 4         | 1.95%   |
| Sound                    | 2         | 0.98%   |
| Network                  | 2         | 0.98%   |
| Net/ethernet             | 2         | 0.98%   |
| Storage/nvme             | 1         | 0.49%   |
| Storage                  | 1         | 0.49%   |
| Modem                    | 1         | 0.49%   |

