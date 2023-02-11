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

Total: 312

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [e76cc93e5d](https://bsd-hardware.info/?probe=e76cc93e5d) | Jan 31, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [540696f4e5](https://bsd-hardware.info/?probe=540696f4e5) | Jan 29, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3492d9a849](https://bsd-hardware.info/?probe=3492d9a849) | Jan 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [6b331ff558](https://bsd-hardware.info/?probe=6b331ff558) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [6aa648ba82](https://bsd-hardware.info/?probe=6aa648ba82) | Jan 19, 2023 |
| Intel         | H81U                        | Notebook    | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Intel         | H81U                        | Notebook    | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| HP            | 1495                        | Desktop     | [4e16deda5a](https://bsd-hardware.info/?probe=4e16deda5a) | Jan 11, 2023 |
| Biostar       | B450NH                      | Desktop     | [c30a71f5ae](https://bsd-hardware.info/?probe=c30a71f5ae) | Jan 10, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| Biostar       | J4125NHU                    | Desktop     | [41114c45b7](https://bsd-hardware.info/?probe=41114c45b7) | Jan 05, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [29b3e0b639](https://bsd-hardware.info/?probe=29b3e0b639) | Dec 22, 2022 |
| Acer          | WG43M                       | Desktop     | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [5048d00fd8](https://bsd-hardware.info/?probe=5048d00fd8) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [60bdb57227](https://bsd-hardware.info/?probe=60bdb57227) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [ebdca950cc](https://bsd-hardware.info/?probe=ebdca950cc) | Nov 27, 2022 |
| HP            | 3396                        | Desktop     | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| Gigabyte      | H110TN                      | Desktop     | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| ASRockRack    | EP2C612D16FM                | Desktop     | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Biostar       | B450NH                      | Desktop     | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
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
| Dell          | 0K6VXP A00                  | Mini pc     | [cbb110122a](https://bsd-hardware.info/?probe=cbb110122a) | Jan 29, 2022 |
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
| helloSystem 0.7.0    | 15        | 5.64%   |
| OpenBSD 7.0          | 12        | 4.51%   |
| FreeBSD 12.1-p10     | 12        | 4.51%   |
| OPNsense 22.7.10     | 9         | 3.38%   |
| OpenBSD 7.1          | 6         | 2.26%   |
| helloSystem 0.6.0    | 6         | 2.26%   |
| FreeBSD 12.2         | 6         | 2.26%   |
| OPNsense 22.1        | 5         | 1.88%   |
| OPNsense 21.7.3      | 5         | 1.88%   |
| OPNsense 21.1.6      | 5         | 1.88%   |
| helloSystem 0.5.0    | 5         | 1.88%   |
| FreeBSD 14.0-CURRENT | 5         | 1.88%   |
| FreeBSD 13.0-p5      | 5         | 1.88%   |
| OPNsense 22.7.4      | 4         | 1.5%    |
| OPNsense 22.7.2      | 4         | 1.5%    |
| OPNsense 22.7        | 4         | 1.5%    |
| OPNsense 22.1.8      | 4         | 1.5%    |
| OPNsense 22.1.10     | 4         | 1.5%    |
| OPNsense 21.7.7      | 4         | 1.5%    |
| OPNsense 21.1.2      | 4         | 1.5%    |
| OPNsense 21.1.1      | 4         | 1.5%    |
| OPNsense 21.1        | 4         | 1.5%    |
| GhostBSD 20.04.02    | 4         | 1.5%    |
| FreeBSD 13.1-p2      | 4         | 1.5%    |
| FreeBSD 13.0-p4      | 4         | 1.5%    |
| FreeBSD 12.3-p2      | 4         | 1.5%    |
| FreeBSD 12.2-p2      | 4         | 1.5%    |
| FreeBSD 12.2-p10     | 4         | 1.5%    |
| FreeBSD 12.1-p13     | 4         | 1.5%    |
| FreeBSD 12.1         | 4         | 1.5%    |
| OPNsense 23.1        | 3         | 1.13%   |
| OPNsense 22.7.6      | 3         | 1.13%   |
| OPNsense 22.1.5      | 3         | 1.13%   |
| OPNsense 22.1.2      | 3         | 1.13%   |
| OPNsense 22.1.1      | 3         | 1.13%   |
| OPNsense 21.7.4      | 3         | 1.13%   |
| OPNsense 21.7.1      | 3         | 1.13%   |
| OPNsense 21.1.8      | 3         | 1.13%   |
| OPNsense 21.1.7      | 3         | 1.13%   |
| OPNsense 21.1.3      | 3         | 1.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 92        | 42.2%   |
| FreeBSD     | 67        | 30.73%  |
| helloSystem | 27        | 12.39%  |
| OpenBSD     | 21        | 9.63%   |
| GhostBSD    | 6         | 2.75%   |
| XigmaNAS    | 2         | 0.92%   |
| NomadBSD    | 2         | 0.92%   |
| NetBSD      | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 211       | 96.79%  |
| i386   | 3         | 1.38%   |
| arm64  | 2         | 0.92%   |
| macppc | 1         | 0.46%   |
| armv7  | 1         | 0.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 135       | 61.09%  |
| helloDesktop  | 30        | 13.57%  |
| fvwm          | 16        | 7.24%   |
| XFCE          | 10        | 4.52%   |
| MATE          | 8         | 3.62%   |
| GNOME         | 6         | 2.71%   |
| openbox       | 4         | 1.81%   |
| KDE5          | 4         | 1.81%   |
| TWM           | 3         | 1.36%   |
| i3            | 3         | 1.36%   |
| xfwm          | 1         | 0.45%   |
| Enlightenment | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 138       | 63.01%  |
| X11     | 81        | 36.99%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 163       | 74.43%  |
| SLiM    | 37        | 16.89%  |
| LightDM | 8         | 3.65%   |
| SDDM    | 6         | 2.74%   |
| GDM     | 4         | 1.83%   |
| XDM     | 1         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 140       | 63.35%  |
| en_US   | 41        | 18.55%  |
| C       | 24        | 10.86%  |
| pl_PL   | 13        | 5.88%   |
| fr_FR   | 1         | 0.45%   |
| en_GB   | 1         | 0.45%   |
| en      | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 170       | 77.63%  |
| BIOS | 49        | 22.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 104       | 47.27%  |
| Ufs    | 87        | 39.55%  |
| Ffs    | 21        | 9.55%   |
| Cd9660 | 8         | 3.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 190       | 87.16%  |
| MBR     | 25        | 11.47%  |
| Unknown | 3         | 1.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 53        | 24.31%  |
| Lenovo                     | 26        | 11.93%  |
| Hewlett-Packard            | 20        | 9.17%   |
| ASUSTek Computer           | 15        | 6.88%   |
| Unknown                    | 13        | 5.96%   |
| Intel                      | 12        | 5.5%    |
| Gigabyte Technology        | 11        | 5.05%   |
| ASRock                     | 10        | 4.59%   |
| MSI                        | 7         | 3.21%   |
| Fujitsu                    | 6         | 2.75%   |
| Supermicro                 | 5         | 2.29%   |
| ZOTAC                      | 4         | 1.83%   |
| Acer                       | 4         | 1.83%   |
| Shuttle                    | 3         | 1.38%   |
| Apple                      | 3         | 1.38%   |
| PC Engines                 | 2         | 0.92%   |
| Inventec                   | 2         | 0.92%   |
| Biostar                    | 2         | 0.92%   |
| ASRockRack                 | 2         | 0.92%   |
| Wistron                    | 1         | 0.46%   |
| Toshiba                    | 1         | 0.46%   |
| Sony                       | 1         | 0.46%   |
| ShenZhen MinWin Technology | 1         | 0.46%   |
| Seeed Studio               | 1         | 0.46%   |
| Raspberry Pi Foundation    | 1         | 0.46%   |
| PC Specialist              | 1         | 0.46%   |
| Panasonic                  | 1         | 0.46%   |
| Notebook                   | 1         | 0.46%   |
| iEi                        | 1         | 0.46%   |
| IBM                        | 1         | 0.46%   |
| Google                     | 1         | 0.46%   |
| Fujitsu Siemens            | 1         | 0.46%   |
| Essentiel B                | 1         | 0.46%   |
| Deciso                     | 1         | 0.46%   |
| AOpen                      | 1         | 0.46%   |
| AMI                        | 1         | 0.46%   |
| Acidanthera                | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 14        | 6.42%   |
| Dell OEM-R 720xd                    | 13        | 5.96%   |
| HP t620 PLUS Quad Core TC           | 8         | 3.67%   |
| Lenovo ThinkPad X200 745969G        | 5         | 2.29%   |
| Dell Wyse 5070 Thin Client          | 3         | 1.38%   |
| Dell Wyse 5070 Extended Thin Client | 3         | 1.38%   |
| ASUS All Series                     | 3         | 1.38%   |
| ASRock Q1900B-ITX                   | 3         | 1.38%   |
| ZOTAC ZBOX-CI329NANO                | 2         | 0.92%   |
| Intel SHARKBAY                      | 2         | 0.92%   |
| Intel Q3XXG4-P V1.0                 | 2         | 0.92%   |
| Gigabyte H110TN                     | 2         | 0.92%   |
| Fujitsu FUTRO S920                  | 2         | 0.92%   |
| Dell Latitude E6430                 | 2         | 0.92%   |
| ZOTAC ZBOX-CI341                    | 1         | 0.46%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.46%   |
| Wistron ProLiant ML110 G5           | 1         | 0.46%   |
| Toshiba PORTEGE X20W-D              | 1         | 0.46%   |
| Supermicro X9SCL/X9SCM              | 1         | 0.46%   |
| Supermicro X7SLA                    | 1         | 0.46%   |
| Supermicro X7DCL                    | 1         | 0.46%   |
| Supermicro X11SSN-L                 | 1         | 0.46%   |
| Supermicro SYS-5018D-FN8T           | 1         | 0.46%   |
| Sony SVF1521K1EB                    | 1         | 0.46%   |
| Shuttle XH270                       | 1         | 0.46%   |
| Shuttle SZ270R9                     | 1         | 0.46%   |
| Shuttle SZ270                       | 1         | 0.46%   |
| ShenZhen MinWin MW-NANO-APL-4L      | 1         | 0.46%   |
| Seeed Studio ODYSSEY-X86J4125       | 1         | 0.46%   |
| RPi Raspberry Pi 400                | 1         | 0.46%   |
| PC Specialist Recoil II             | 1         | 0.46%   |
| PC Engines APU2                     | 1         | 0.46%   |
| PC Engines apu1                     | 1         | 0.46%   |
| Panasonic CFMX4-1                   | 1         | 0.46%   |
| Notebook N85_N87,HJ,HJ1,HK1         | 1         | 0.46%   |
| MSI MS-7D25                         | 1         | 0.46%   |
| MSI MS-7C52                         | 1         | 0.46%   |
| MSI MS-7B53                         | 1         | 0.46%   |
| MSI MS-7846                         | 1         | 0.46%   |
| MSI MS-7788                         | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 14        | 6.42%   |
| Unknown                        | 14        | 6.42%   |
| Dell OEM-R                     | 13        | 5.96%   |
| Dell PowerEdge                 | 10        | 4.59%   |
| Dell Latitude                  | 10        | 4.59%   |
| HP t620                        | 8         | 3.67%   |
| Dell Wyse                      | 6         | 2.75%   |
| Dell OptiPlex                  | 6         | 2.75%   |
| Lenovo ThinkCentre             | 4         | 1.83%   |
| Fujitsu FUTRO                  | 4         | 1.83%   |
| HP Compaq                      | 3         | 1.38%   |
| Dell Vostro                    | 3         | 1.38%   |
| ASUS All                       | 3         | 1.38%   |
| ASRock Q1900B-ITX              | 3         | 1.38%   |
| Acer Aspire                    | 3         | 1.38%   |
| ZOTAC ZBOX-CI329NANO           | 2         | 0.92%   |
| Lenovo IdeaPad                 | 2         | 0.92%   |
| Intel SHARKBAY                 | 2         | 0.92%   |
| Intel Q3XXG4-P                 | 2         | 0.92%   |
| HP ProLiant                    | 2         | 0.92%   |
| HP ENVY                        | 2         | 0.92%   |
| Gigabyte H110TN                | 2         | 0.92%   |
| Gigabyte B450M                 | 2         | 0.92%   |
| Dell Inspiron                  | 2         | 0.92%   |
| ZOTAC ZBOX-CI341               | 1         | 0.46%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.46%   |
| Wistron ProLiant               | 1         | 0.46%   |
| Toshiba PORTEGE                | 1         | 0.46%   |
| Supermicro X9SCL               | 1         | 0.46%   |
| Supermicro X7SLA               | 1         | 0.46%   |
| Supermicro X7DCL               | 1         | 0.46%   |
| Supermicro X11SSN-L            | 1         | 0.46%   |
| Supermicro SYS-5018D-FN8T      | 1         | 0.46%   |
| Sony SVF1521K1EB               | 1         | 0.46%   |
| Shuttle XH270                  | 1         | 0.46%   |
| Shuttle SZ270R9                | 1         | 0.46%   |
| Shuttle SZ270                  | 1         | 0.46%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.46%   |
| Seeed Studio ODYSSEY-X86J4125  | 1         | 0.46%   |
| RPi Raspberry                  | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 41        | 18.81%  |
| 2019    | 23        | 10.55%  |
| 2018    | 21        | 9.63%   |
| 2012    | 18        | 8.26%   |
| 2020    | 16        | 7.34%   |
| 2021    | 15        | 6.88%   |
| 2016    | 15        | 6.88%   |
| 2013    | 14        | 6.42%   |
| 2009    | 11        | 5.05%   |
| 2022    | 9         | 4.13%   |
| 2011    | 9         | 4.13%   |
| 2017    | 7         | 3.21%   |
| 2015    | 6         | 2.75%   |
| 2010    | 4         | 1.83%   |
| 2006    | 3         | 1.38%   |
| 2008    | 2         | 0.92%   |
| 2007    | 2         | 0.92%   |
| Unknown | 2         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 114       | 52.29%  |
| Notebook    | 54        | 24.77%  |
| Server      | 29        | 13.3%   |
| Mini pc     | 14        | 6.42%   |
| All in one  | 5         | 2.29%   |
| Convertible | 2         | 0.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 214       | 98.17%  |
| Yes  | 4         | 1.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 64        | 28.83%  |
| 8.01-16.0   | 63        | 28.38%  |
| 16.01-24.0  | 45        | 20.27%  |
| 64.01-256.0 | 18        | 8.11%   |
| 32.01-64.0  | 13        | 5.86%   |
| 2.01-3.0    | 7         | 3.15%   |
| 3.01-4.0    | 6         | 2.7%    |
| 24.01-32.0  | 3         | 1.35%   |
| 0.51-1.0    | 2         | 0.9%    |
| 1.01-2.0    | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 124       | 54.15%  |
| 0.51-1.0    | 54        | 23.58%  |
| 1.01-2.0    | 31        | 13.54%  |
| 2.01-3.0    | 5         | 2.18%   |
| 4.01-8.0    | 4         | 1.75%   |
| 8.01-16.0   | 4         | 1.75%   |
| 3.01-4.0    | 2         | 0.87%   |
| 0           | 2         | 0.87%   |
| 64.01-256.0 | 1         | 0.44%   |
| 16.01-24.0  | 1         | 0.44%   |
| Unknown     | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 122       | 53.74%  |
| 2      | 46        | 20.26%  |
| 0      | 33        | 14.54%  |
| 3      | 11        | 4.85%   |
| 6      | 5         | 2.2%    |
| 4      | 5         | 2.2%    |
| 5      | 3         | 1.32%   |
| 9      | 1         | 0.44%   |
| 8      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 178       | 80.91%  |
| Yes       | 42        | 19.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 96.33%  |
| No        | 8         | 3.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 57.47%  |
| Yes       | 94        | 42.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 75.57%  |
| Yes       | 54        | 24.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 218       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 37        | 15.42%  |
| Gdynia                    | 19        | 7.92%   |
| Krakow                    | 18        | 7.5%    |
| Gdansk                    | 18        | 7.5%    |
| Wroclaw                   | 14        | 5.83%   |
| Poznan                    | 7         | 2.92%   |
| Lodz                      | 5         | 2.08%   |
| Miedziana Gora            | 4         | 1.67%   |
| Lezno                     | 3         | 1.25%   |
| Legionowo                 | 3         | 1.25%   |
| Katowice                  | 3         | 1.25%   |
| Chrusty                   | 3         | 1.25%   |
| Е»ukowo                 | 2         | 0.83%   |
| Zgierz                    | 2         | 0.83%   |
| Walendow                  | 2         | 0.83%   |
| Szczecin                  | 2         | 0.83%   |
| Siedlce                   | 2         | 0.83%   |
| Radom                     | 2         | 0.83%   |
| Lubin                     | 2         | 0.83%   |
| Kielce                    | 2         | 0.83%   |
| Glincz                    | 2         | 0.83%   |
| CzД™stochowa           | 2         | 0.83%   |
| Bialystok                 | 2         | 0.83%   |
| ЕљwiД™tochЕ‚owice | 1         | 0.42%   |
| Zajaczki Pierwsze         | 1         | 0.42%   |
| Zagnansk                  | 1         | 0.42%   |
| WЕ‚ocЕ‚awek         | 1         | 0.42%   |
| Wschowa                   | 1         | 0.42%   |
| Wronowy                   | 1         | 0.42%   |
| Wolsztyn                  | 1         | 0.42%   |
| Wloszczowa                | 1         | 0.42%   |
| Wieliczka                 | 1         | 0.42%   |
| Walcz                     | 1         | 0.42%   |
| Tychy                     | 1         | 0.42%   |
| Szczytno                  | 1         | 0.42%   |
| Świnoujście             | 1         | 0.42%   |
| Sulejowek                 | 1         | 0.42%   |
| Sulechow                  | 1         | 0.42%   |
| Stopnica                  | 1         | 0.42%   |
| Stary Sacz                | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 71     | 14.52%  |
| WDC                 | 34        | 73     | 13.71%  |
| Seagate             | 27        | 52     | 10.89%  |
| SanDisk             | 16        | 18     | 6.45%   |
| GOODRAM             | 15        | 26     | 6.05%   |
| Toshiba             | 12        | 28     | 4.84%   |
| A-DATA Technology   | 11        | 12     | 4.44%   |
| Kingston            | 8         | 8      | 3.23%   |
| Transcend           | 6         | 11     | 2.42%   |
| Crucial             | 6         | 11     | 2.42%   |
| SPCC                | 5         | 6      | 2.02%   |
| Intel               | 5         | 7      | 2.02%   |
| Hoodisk             | 5         | 7      | 2.02%   |
| LITEON              | 4         | 4      | 1.61%   |
| Innodisk            | 4         | 5      | 1.61%   |
| Hitachi             | 4         | 4      | 1.61%   |
| Apacer              | 4         | 5      | 1.61%   |
| SK hynix            | 3         | 3      | 1.21%   |
| PNY                 | 3         | 7      | 1.21%   |
| Plextor             | 3         | 3      | 1.21%   |
| Patriot             | 3         | 3      | 1.21%   |
| OCZ                 | 3         | 3      | 1.21%   |
| NVMe                | 3         | 6      | 1.21%   |
| HGST                | 3         | 5      | 1.21%   |
| Hewlett-Packard     | 3         | 3      | 1.21%   |
| Gigabyte Technology | 3         | 3      | 1.21%   |
| Corsair             | 3         | 3      | 1.21%   |
| Micron Technology   | 2         | 8      | 0.81%   |
| Kston               | 2         | 2      | 0.81%   |
| Intenso             | 2         | 3      | 0.81%   |
| China               | 2         | 3      | 0.81%   |
| Team                | 1         | 1      | 0.4%    |
| SSSTC               | 1         | 2      | 0.4%    |
| SSDPR-CX            | 1         | 1      | 0.4%    |
| Phison              | 1         | 1      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |
| KIOXIA              | 1         | 1      | 0.4%    |
| FORESEE             | 1         | 1      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung HM321HI 320GB              | 5         | 1.84%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.47%   |
| SPCC Solid State Disk 256GB        | 3         | 1.1%    |
| Samsung SSD 850 EVO 250GB          | 3         | 1.1%    |
| Kingston SUV500MS120G 120GB        | 3         | 1.1%    |
| Hoodisk SSD 128GB                  | 3         | 1.1%    |
| GOODRAM SSDPR-CX400-128 128GB      | 3         | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.74%   |
| WDC WD20SDZW-11JJ8S0 2TB           | 2         | 0.74%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2         | 0.74%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.74%   |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.74%   |
| Transcend TS120GMTS420S 120GB      | 2         | 0.74%   |
| Toshiba MQ04ABF100 1TB             | 2         | 0.74%   |
| Seagate ST96812AS 64GB             | 2         | 0.74%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.74%   |
| Seagate ST2000DL003-9VT166 2TB     | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 0.74%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 2         | 0.74%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.74%   |
| Patriot Burst 120GB                | 2         | 0.74%   |
| Kingston SA400S37240G 240GB        | 2         | 0.74%   |
| Intenso SSD SATAIII 128GB          | 2         | 0.74%   |
| Intel SSDPEKNW512G8H 512GB         | 2         | 0.74%   |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 2         | 0.74%   |
| GOODRAM SSDPR-CX400-256 256GB      | 2         | 0.74%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 2         | 0.74%   |
| Goodram SSDPR-CL100-120-G2 120GB   | 2         | 0.74%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.74%   |
| Corsair CMFSSD-256D1 256GB         | 2         | 0.74%   |
| China SATA SSD 64GB                | 2         | 0.74%   |
| Apacer AS340 240GB                 | 2         | 0.74%   |
| A-DATA SU800 256GB                 | 2         | 0.74%   |
| A-DATA SU800 128GB                 | 2         | 0.74%   |
| WDC WD7500BPKT-22PK4T0 752GB       | 1         | 0.37%   |
| WDC WD5000LPVT-75G33T0 500GB       | 1         | 0.37%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.37%   |
| WDC WD5000BPVT-08HXZT3 500GB       | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 59     | 34.07%  |
| Seagate             | 27        | 52     | 29.67%  |
| Toshiba             | 10        | 26     | 10.99%  |
| Samsung Electronics | 10        | 16     | 10.99%  |
| Hitachi             | 4         | 4      | 4.4%    |
| HGST                | 3         | 5      | 3.3%    |
| NVMe                | 2         | 3      | 2.2%    |
| Hewlett-Packard     | 2         | 2      | 2.2%    |
| SSDPR-CX            | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 45     | 14.29%  |
| SanDisk             | 16        | 18     | 12.03%  |
| GOODRAM             | 14        | 25     | 10.53%  |
| Kingston            | 8         | 8      | 6.02%   |
| A-DATA Technology   | 8         | 8      | 6.02%   |
| Transcend           | 5         | 10     | 3.76%   |
| SPCC                | 5         | 6      | 3.76%   |
| Hoodisk             | 5         | 7      | 3.76%   |
| Crucial             | 5         | 10     | 3.76%   |
| Innodisk            | 4         | 5      | 3.01%   |
| Apacer              | 4         | 5      | 3.01%   |
| Plextor             | 3         | 3      | 2.26%   |
| OCZ                 | 3         | 3      | 2.26%   |
| LITEON              | 3         | 3      | 2.26%   |
| Intel               | 3         | 5      | 2.26%   |
| Gigabyte Technology | 3         | 3      | 2.26%   |
| Corsair             | 3         | 3      | 2.26%   |
| WDC                 | 2         | 13     | 1.5%    |
| SK hynix            | 2         | 2      | 1.5%    |
| Patriot             | 2         | 2      | 1.5%    |
| Micron Technology   | 2         | 8      | 1.5%    |
| Kston               | 2         | 2      | 1.5%    |
| Intenso             | 2         | 3      | 1.5%    |
| China               | 2         | 3      | 1.5%    |
| Toshiba             | 1         | 1      | 0.75%   |
| Team                | 1         | 1      | 0.75%   |
| PNY                 | 1         | 4      | 0.75%   |
| Phison              | 1         | 1      | 0.75%   |
| NVMe                | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| Hewlett-Packard     | 1         | 1      | 0.75%   |
| FORESEE             | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 117       | 211    | 54.93%  |
| HDD  | 72        | 169    | 33.8%   |
| NVMe | 24        | 32     | 11.27%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 165       | 380    | 87.3%   |
| NVMe | 24        | 32     | 12.7%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 139       | 244    | 71.65%  |
| 0.51-1.0   | 31        | 66     | 15.98%  |
| 1.01-2.0   | 15        | 39     | 7.73%   |
| 3.01-4.0   | 3         | 8      | 1.55%   |
| 2.01-3.0   | 3         | 13     | 1.55%   |
| 4.01-10.0  | 3         | 10     | 1.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 84        | 36.36%  |
| 51-100         | 37        | 16.02%  |
| 1-20           | 35        | 15.15%  |
| 251-500        | 32        | 13.85%  |
| 21-50          | 22        | 9.52%   |
| 501-1000       | 13        | 5.63%   |
| More than 3000 | 3         | 1.3%    |
| 1001-2000      | 3         | 1.3%    |
| 2001-3000      | 2         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 202       | 89.78%  |
| 21-50          | 10        | 4.44%   |
| 101-250        | 5         | 2.22%   |
| 51-100         | 5         | 2.22%   |
| 1001-2000      | 2         | 0.89%   |
| More than 3000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                    | 2         | 2      | 6.25%   |
| Seagate ST96812AS 64GB                    | 2         | 5      | 6.25%   |
| WDC WD360ADFD-00NLR1 37GB                 | 1         | 1      | 3.13%   |
| WDC WD3200BEKT-22PVMT0 320GB              | 1         | 1      | 3.13%   |
| WDC WD3200AAVS-00ZTB0 320GB               | 1         | 1      | 3.13%   |
| WDC WD2500AAKX-753CA0 250GB               | 1         | 1      | 3.13%   |
| WDC WD2500AAKX-083CA1 250GB               | 1         | 2      | 3.13%   |
| WDC WD20EURS-63S48Y0 2TB                  | 1         | 1      | 3.13%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 3.13%   |
| WDC WD1600BEVE-00UYT0 160GB               | 1         | 1      | 3.13%   |
| WDC WD1600AAJS-40H3A0 160GB               | 1         | 1      | 3.13%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1      | 3.13%   |
| WDC WD10EARS-003BB1 1TB                   | 1         | 1      | 3.13%   |
| Toshiba THNSNK512GVN8 512GB               | 1         | 1      | 3.13%   |
| Toshiba MK3261GSYN 320GB                  | 1         | 1      | 3.13%   |
| SPCC Solid State Disk 256GB               | 1         | 1      | 3.13%   |
| SK hynix SC308 SATA 256GB                 | 1         | 1      | 3.13%   |
| Seagate ST9500420AS 500GB                 | 1         | 2      | 3.13%   |
| Seagate ST9160412AS 160GB                 | 1         | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 3.13%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.13%   |
| Seagate ST32000542AS 2TB                  | 1         | 1      | 3.13%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 3.13%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 3.13%   |
| Samsung Electronics HD154UI 1.5TB         | 1         | 1      | 3.13%   |
| Plextor PX-128G7Ne 128GB                  | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB | 1         | 1      | 3.13%   |
| Hitachi HTS721060G9SA00 64GB              | 1         | 1      | 3.13%   |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 12     | 34.38%  |
| Seagate             | 9         | 13     | 28.13%  |
| Toshiba             | 4         | 4      | 12.5%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| Hitachi             | 2         | 2      | 6.25%   |
| SPCC                | 1         | 1      | 3.13%   |
| SK hynix            | 1         | 1      | 3.13%   |
| Plextor             | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 12     | 42.31%  |
| Seagate             | 9         | 13     | 34.62%  |
| Toshiba             | 3         | 3      | 11.54%  |
| Hitachi             | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 31     | 80.65%  |
| SSD  | 6         | 6      | 19.35%  |

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
| Works    | 166       | 362    | 80.58%  |
| Malfunc  | 30        | 37     | 14.56%  |
| Detected | 9         | 12     | 4.37%   |
| Failed   | 1         | 1      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 156       | 63.16%  |
| AMD                            | 30        | 12.15%  |
| Broadcom / LSI                 | 24        | 9.72%   |
| Samsung Electronics            | 9         | 3.64%   |
| Silicon Motion                 | 3         | 1.21%   |
| SanDisk                        | 3         | 1.21%   |
| Phison Electronics             | 2         | 0.81%   |
| Nvidia                         | 2         | 0.81%   |
| KIOXIA                         | 2         | 0.81%   |
| Hewlett-Packard                | 2         | 0.81%   |
| ASMedia Technology             | 2         | 0.81%   |
| VIA Technologies               | 1         | 0.4%    |
| Transcend                      | 1         | 0.4%    |
| Solid State Storage Technology | 1         | 0.4%    |
| SK hynix                       | 1         | 0.4%    |
| Realtek Semiconductor          | 1         | 0.4%    |
| Micron/Crucial Technology      | 1         | 0.4%    |
| Marvell Technology Group       | 1         | 0.4%    |
| Lite-On Technology             | 1         | 0.4%    |
| JMicron Technology             | 1         | 0.4%    |
| Integrated Technology Express  | 1         | 0.4%    |
| Apple                          | 1         | 0.4%    |
| ADATA Technology               | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 7.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 16        | 5.93%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 15        | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9         | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 2.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 2.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 1.85%   |
| Unknown                                                                          | 5         | 1.85%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 1.48%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.11%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3         | 1.11%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.11%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 3         | 1.11%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.74%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.74%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.74%   |
| Intel SSD 660P Series                                                            | 2         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.74%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 0.74%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 165       | 66.53%  |
| RAID | 29        | 11.69%  |
| NVMe | 27        | 10.89%  |
| IDE  | 23        | 9.27%   |
| SAS  | 2         | 0.81%   |
| SCSI | 2         | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 179       | 82.11%  |
| AMD     | 35        | 16.06%  |
| ARM     | 3         | 1.38%   |
| PowerPC | 1         | 0.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz      | 13        | 5.91%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 8         | 3.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 5         | 2.27%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 4         | 1.82%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 4         | 1.82%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 4         | 1.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 1.36%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 1.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 3         | 1.36%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 1.36%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 3         | 1.36%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 3         | 1.36%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 3         | 1.36%   |
| Intel Pentium CPU G860 @ 3.00GHz         | 2         | 0.91%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 2         | 0.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.91%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 2         | 0.91%   |
| Intel Core i5-6400T CPU @ 2.20GHz        | 2         | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 2         | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 2         | 0.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 2         | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 0.91%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 2         | 0.91%   |
| Intel Core i3-2100 CPU @ 3.10GHz         | 2         | 0.91%   |
| Intel Core 2 Duo                         | 2         | 0.91%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 2         | 0.91%   |
| Intel Atom CPU D2500 @ 1.86GHz           | 2         | 0.91%   |
| ARM Cortex-A72 r0p3                      | 2         | 0.91%   |
| AMD Ryzen 3 3100 4-Core Processor        | 2         | 0.91%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 2         | 0.91%   |
| PowerPC 7447A (Revision 0x102)           | 1         | 0.45%   |
| Intel Xeon E-2386G CPU @ 3.50GHz         | 1         | 0.45%   |
| Intel Xeon CPU X5660 @ 2.80GHz           | 1         | 0.45%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.45%   |
| Intel Xeon CPU X3360 @ 2.83GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5520 @ 2.27GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5410 @ 2.33GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz      | 1         | 0.45%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz       | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 50        | 22.73%  |
| Intel Xeon              | 33        | 15%     |
| Intel Celeron           | 30        | 13.64%  |
| Intel Core i7           | 18        | 8.18%   |
| Intel Core i3           | 14        | 6.36%   |
| AMD GX                  | 13        | 5.91%   |
| Intel Core 2 Duo        | 9         | 4.09%   |
| Intel Pentium           | 8         | 3.64%   |
| Intel Atom              | 6         | 2.73%   |
| Intel Pentium Silver    | 5         | 2.27%   |
| Other                   | 4         | 1.82%   |
| ARM Cortex              | 3         | 1.36%   |
| AMD Ryzen 5             | 3         | 1.36%   |
| AMD Ryzen 3             | 3         | 1.36%   |
| AMD G                   | 3         | 1.36%   |
| Intel Pentium Dual-Core | 2         | 0.91%   |
| AMD Ryzen 7             | 2         | 0.91%   |
| AMD E                   | 2         | 0.91%   |
| Intel Pentium M         | 1         | 0.45%   |
| Intel Core 2            | 1         | 0.45%   |
| Intel Celeron M         | 1         | 0.45%   |
| AMD Ryzen Embedded      | 1         | 0.45%   |
| AMD Ryzen 9             | 1         | 0.45%   |
| AMD Ryzen 7 PRO         | 1         | 0.45%   |
| AMD Ryzen 5 PRO         | 1         | 0.45%   |
| AMD Phenom II X6        | 1         | 0.45%   |
| AMD Phenom II X4        | 1         | 0.45%   |
| AMD Athlon 64 X2        | 1         | 0.45%   |
| AMD Athlon              | 1         | 0.45%   |
| AMD A4                  | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 85        | 38.81%  |
| 2       | 68        | 31.05%  |
| 16      | 15        | 6.85%   |
| Unknown | 15        | 6.85%   |
| 8       | 12        | 5.48%   |
| 6       | 9         | 4.11%   |
| 12      | 7         | 3.2%    |
| 1       | 5         | 2.28%   |
| 20      | 2         | 0.91%   |
| 24      | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 181       | 83.03%  |
| 2       | 26        | 11.93%  |
| Unknown | 11        | 5.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 108       | 49.32%  |
| 2       | 92        | 42.01%  |
| Unknown | 19        | 8.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 33        | 15%     |
| KabyLake      | 23        | 10.45%  |
| Haswell       | 20        | 9.09%   |
| SandyBridge   | 18        | 8.18%   |
| Penryn        | 16        | 7.27%   |
| Goldmont plus | 16        | 7.27%   |
| Skylake       | 13        | 5.91%   |
| Jaguar        | 13        | 5.91%   |
| Silvermont    | 10        | 4.55%   |
| Unknown       | 9         | 4.09%   |
| Zen 2         | 5         | 2.27%   |
| Goldmont      | 5         | 2.27%   |
| Bobcat        | 5         | 2.27%   |
| Westmere      | 4         | 1.82%   |
| Broadwell     | 4         | 1.82%   |
| Bonnell       | 4         | 1.82%   |
| Zen           | 3         | 1.36%   |
| CometLake     | 3         | 1.36%   |
| Zen+          | 2         | 0.91%   |
| Zen 3         | 2         | 0.91%   |
| Puma          | 2         | 0.91%   |
| P6            | 2         | 0.91%   |
| Nehalem       | 2         | 0.91%   |
| K10           | 2         | 0.91%   |
| TigerLake     | 1         | 0.45%   |
| NetBurst      | 1         | 0.45%   |
| K8 Hammer     | 1         | 0.45%   |
| Core          | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 133       | 57.33%  |
| AMD                                          | 42        | 18.1%   |
| Nvidia                                       | 26        | 11.21%  |
| Matrox Electronics Systems                   | 25        | 10.78%  |
| ASPEED Technology                            | 4         | 1.72%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.43%   |
| VIA Technologies                             | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems G200eR2                                                       | 18        | 7.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 4.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.7%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 8         | 3.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 2.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.99%   |
| Intel HD Graphics 530                                                                    | 6         | 2.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 2.56%   |
| Intel HD Graphics 620                                                                    | 5         | 2.14%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 2.14%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4         | 1.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.71%   |
| Intel HD Graphics 500                                                                    | 4         | 1.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.71%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 1.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.28%   |
| Intel HD Graphics 630                                                                    | 3         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.28%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.28%   |
| AMD ES1000                                                                               | 3         | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.85%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.85%   |
| Intel HD Graphics 610                                                                    | 2         | 0.85%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.85%   |
| Intel HD Graphics 510                                                                    | 2         | 0.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.85%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.85%   |
| AMD Renoir                                                                               | 2         | 0.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.85%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 105       | 47.73%  |
| 1 x AMD         | 37        | 16.82%  |
| 1 x Matrox      | 25        | 11.36%  |
| 1 x Nvidia      | 13        | 5.91%   |
| Intel + Nvidia  | 13        | 5.91%   |
| 2 x Intel       | 11        | 5%      |
| Other           | 6         | 2.73%   |
| Intel + AMD     | 4         | 1.82%   |
| 1 x ASPEED      | 2         | 0.91%   |
| 1 x XGI         | 1         | 0.45%   |
| 1 x VIA         | 1         | 0.45%   |
| Nvidia + ASPEED | 1         | 0.45%   |
| AMD + ASPEED    | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 196       | 89.5%   |
| Proprietary | 12        | 5.48%   |
| Unknown     | 11        | 5.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 198       | 90.41%  |
| 1.01-2.0   | 6         | 2.74%   |
| 3.01-4.0   | 5         | 2.28%   |
| 7.01-8.0   | 3         | 1.37%   |
| 0.01-0.5   | 3         | 1.37%   |
| 0.51-1.0   | 2         | 0.91%   |
| 5.01-6.0   | 1         | 0.46%   |
| 8.01-16.0  | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 18.29%  |
| Lenovo                  | 7         | 8.54%   |
| BOE                     | 7         | 8.54%   |
| Samsung Electronics     | 6         | 7.32%   |
| NEC Computers           | 5         | 6.1%    |
| Dell                    | 5         | 6.1%    |
| Chimei Innolux          | 4         | 4.88%   |
| Acer                    | 4         | 4.88%   |
| Philips                 | 3         | 3.66%   |
| Iiyama                  | 3         | 3.66%   |
| AU Optronics            | 3         | 3.66%   |
| Goldstar                | 2         | 2.44%   |
| Chi Mei Optoelectronics | 2         | 2.44%   |
| BenQ                    | 2         | 2.44%   |
| Apple                   | 2         | 2.44%   |
| AOC                     | 2         | 2.44%   |
| Vestel Elektronik       | 1         | 1.22%   |
| Toshiba                 | 1         | 1.22%   |
| Sharp                   | 1         | 1.22%   |
| PANDA                   | 1         | 1.22%   |
| KTC                     | 1         | 1.22%   |
| JDI                     | 1         | 1.22%   |
| InfoVision              | 1         | 1.22%   |
| HPN                     | 1         | 1.22%   |
| Hewlett-Packard         | 1         | 1.22%   |
| Eizo                    | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 5         | 6.1%    |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 2.44%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 1         | 1.22%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                        | 1         | 1.22%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                  | 1         | 1.22%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch        | 1         | 1.22%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch    | 1         | 1.22%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 1.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 1.22%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch                | 1         | 1.22%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 1.22%   |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch               | 1         | 1.22%   |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch            | 1         | 1.22%   |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch             | 1         | 1.22%   |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch              | 1         | 1.22%   |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch                 | 1         | 1.22%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD0368 1366x768 310x170mm 13.9-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.22%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.22%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.22%   |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 1.22%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.22%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                  | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 41.03%  |
| 1366x768 (WXGA)    | 19        | 24.36%  |
| 1280x800 (WXGA)    | 7         | 8.97%   |
| 3840x2160 (4K)     | 5         | 6.41%   |
| 1680x1050 (WSXGA+) | 3         | 3.85%   |
| 1600x900 (HD+)     | 3         | 3.85%   |
| 2560x1440 (QHD)    | 2         | 2.56%   |
| 1920x540           | 2         | 2.56%   |
| 1920x1200 (WUXGA)  | 2         | 2.56%   |
| 2560x1080          | 1         | 1.28%   |
| 1440x900 (WXGA+)   | 1         | 1.28%   |
| 1280x1024 (SXGA)   | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 23.75%  |
| 13      | 12        | 15%     |
| 12      | 12        | 15%     |
| 24      | 7         | 8.75%   |
| 23      | 5         | 6.25%   |
| 21      | 5         | 6.25%   |
| 27      | 4         | 5%      |
| 18      | 3         | 3.75%   |
| 42      | 2         | 2.5%    |
| 31      | 2         | 2.5%    |
| 17      | 2         | 2.5%    |
| 50      | 1         | 1.25%   |
| 40      | 1         | 1.25%   |
| 28      | 1         | 1.25%   |
| 22      | 1         | 1.25%   |
| 20      | 1         | 1.25%   |
| 14      | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 39.24%  |
| 501-600     | 15        | 18.99%  |
| 201-300     | 13        | 16.46%  |
| 401-500     | 10        | 12.66%  |
| 601-700     | 3         | 3.8%    |
| 351-400     | 2         | 2.53%   |
| 901-1000    | 2         | 2.53%   |
| 801-900     | 1         | 1.27%   |
| 1001-1500   | 1         | 1.27%   |
| Unknown     | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 77.33%  |
| 16/10   | 12        | 16%     |
| 3/2     | 2         | 2.67%   |
| 5/4     | 1         | 1.33%   |
| 21/9    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 14        | 17.72%  |
| 91-100         | 14        | 17.72%  |
| 81-90          | 13        | 16.46%  |
| 61-70          | 12        | 15.19%  |
| 101-110        | 5         | 6.33%   |
| 301-350        | 4         | 5.06%   |
| 251-300        | 4         | 5.06%   |
| 141-150        | 3         | 3.8%    |
| 501-1000       | 3         | 3.8%    |
| 351-500        | 2         | 2.53%   |
| 151-200        | 2         | 2.53%   |
| More than 1000 | 1         | 1.27%   |
| 121-130        | 1         | 1.27%   |
| Unknown        | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 29        | 37.66%  |
| 51-100  | 23        | 29.87%  |
| 101-120 | 17        | 22.08%  |
| 161-240 | 5         | 6.49%   |
| 1-50    | 2         | 2.6%    |
| Unknown | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 146       | 66.36%  |
| 1     | 66        | 30%     |
| 2     | 7         | 3.18%   |
| 3     | 1         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 141       | 41.96%  |
| Realtek Semiconductor             | 97        | 28.87%  |
| Broadcom                          | 43        | 12.8%   |
| Qualcomm Atheros                  | 23        | 6.85%   |
| Qualcomm Atheros Communications   | 5         | 1.49%   |
| TP-Link                           | 2         | 0.6%    |
| Huawei Technologies               | 2         | 0.6%    |
| Emulex                            | 2         | 0.6%    |
| Dell                              | 2         | 0.6%    |
| Xiaomi                            | 1         | 0.3%    |
| VIA Technologies                  | 1         | 0.3%    |
| Van Ooijen Technische Informatica | 1         | 0.3%    |
| U-Blox                            | 1         | 0.3%    |
| Sierra Wireless                   | 1         | 0.3%    |
| Seeed Technology                  | 1         | 0.3%    |
| Ralink Technology                 | 1         | 0.3%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.3%    |
| Nvidia                            | 1         | 0.3%    |
| Nuvoton                           | 1         | 0.3%    |
| NetGear                           | 1         | 0.3%    |
| Mellanox Technologies             | 1         | 0.3%    |
| IMC Networks                      | 1         | 0.3%    |
| D-Link System                     | 1         | 0.3%    |
| Atheros                           | 1         | 0.3%    |
| Apple                             | 1         | 0.3%    |
| American Megatrends               | 1         | 0.3%    |
| AMD                               | 1         | 0.3%    |
| 3Com                              | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 88        | 22.34%  |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 18        | 4.57%   |
| Intel I211 Gigabit Network Connection                                         | 17        | 4.31%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 3.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 3.55%   |
| Intel I210 Gigabit Network Connection                                         | 11        | 2.79%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 2.03%   |
| Intel 82567LM Gigabit Network Connection                                      | 7         | 1.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 1.52%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 1.52%   |
| Intel Wireless 8260                                                           | 5         | 1.27%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 1.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 5         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 5         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 1.02%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.02%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.02%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 0.76%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.76%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 0.76%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 0.76%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 0.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 0.51%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 0.51%   |
| Intel Wireless 7265                                                           | 2         | 0.51%   |
| Intel Wireless 7260                                                           | 2         | 0.51%   |
| Intel Wireless 3165                                                           | 2         | 0.51%   |
| Intel Ethernet Controller X550                                                | 2         | 0.51%   |
| Intel Ethernet Controller I226-V                                              | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 50.49%  |
| Qualcomm Atheros                | 19        | 18.45%  |
| Broadcom                        | 11        | 10.68%  |
| Realtek Semiconductor           | 7         | 6.8%    |
| Qualcomm Atheros Communications | 5         | 4.85%   |
| TP-Link                         | 2         | 1.94%   |
| Dell                            | 2         | 1.94%   |
| Ralink Technology               | 1         | 0.97%   |
| NetGear                         | 1         | 0.97%   |
| IMC Networks                    | 1         | 0.97%   |
| D-Link System                   | 1         | 0.97%   |
| Atheros                         | 1         | 0.97%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 5.83%   |
| Intel Wireless 8260                                                           | 5         | 4.85%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 4.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 5         | 4.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 4.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 5         | 4.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 3.88%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 2.91%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 2.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 1.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 1.94%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.94%   |
| Intel Wireless 7265                                                           | 2         | 1.94%   |
| Intel Wireless 7260                                                           | 2         | 1.94%   |
| Intel Wireless 3165                                                           | 2         | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 1.94%   |
| Intel Centrino Advanced-N 6235                                                | 2         | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.97%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.97%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1         | 0.97%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.97%   |
| Intel Wireless 3160                                                           | 1         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.97%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 0.97%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 0.97%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 117       | 45.35%  |
| Realtek Semiconductor         | 93        | 36.05%  |
| Broadcom                      | 33        | 12.79%  |
| Qualcomm Atheros              | 4         | 1.55%   |
| Emulex                        | 2         | 0.78%   |
| Xiaomi                        | 1         | 0.39%   |
| VIA Technologies              | 1         | 0.39%   |
| OnePlus Technology (Shenzhen) | 1         | 0.39%   |
| Nvidia                        | 1         | 0.39%   |
| Huawei Technologies           | 1         | 0.39%   |
| Apple                         | 1         | 0.39%   |
| American Megatrends           | 1         | 0.39%   |
| AMD                           | 1         | 0.39%   |
| 3Com                          | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 88        | 31.1%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 18        | 6.36%   |
| Intel I211 Gigabit Network Connection                                         | 17        | 6.01%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 4.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 4.95%   |
| Intel I210 Gigabit Network Connection                                         | 11        | 3.89%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 2.83%   |
| Intel 82567LM Gigabit Network Connection                                      | 7         | 2.47%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 2.12%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5         | 1.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 1.41%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.41%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.06%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 1.06%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 1.06%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.71%   |
| Intel Ethernet Controller X550                                                | 2         | 0.71%   |
| Intel Ethernet Controller I226-V                                              | 2         | 0.71%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.71%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.71%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.71%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 0.71%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 2         | 0.71%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 2         | 0.71%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.35%   |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data                  | 1         | 0.35%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.35%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1         | 0.35%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 1         | 0.35%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.35%   |
| Intel Ethernet Connection I217-V                                              | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 210       | 67.31%  |
| WiFi     | 94        | 30.13%  |
| Modem    | 5         | 1.6%    |
| Unknown  | 3         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 187       | 76.33%  |
| WiFi     | 58        | 23.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 85        | 38.46%  |
| 1     | 44        | 19.91%  |
| 4     | 31        | 14.03%  |
| 3     | 27        | 12.22%  |
| 6     | 18        | 8.14%   |
| 5     | 11        | 4.98%   |
| 0     | 3         | 1.36%   |
| 14    | 1         | 0.45%   |
| 8     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 217       | 98.19%  |
| Yes  | 4         | 1.81%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 59.26%  |
| Broadcom                        | 4         | 7.41%   |
| Qualcomm Atheros Communications | 3         | 5.56%   |
| IMC Networks                    | 3         | 5.56%   |
| Foxconn / Hon Hai               | 2         | 3.7%    |
| Cambridge Silicon Radio         | 2         | 3.7%    |
| ASUSTek Computer                | 2         | 3.7%    |
| Apple                           | 2         | 3.7%    |
| Realtek Semiconductor           | 1         | 1.85%   |
| Qcom                            | 1         | 1.85%   |
| Hewlett-Packard                 | 1         | 1.85%   |
| Dell                            | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 10        | 18.52%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 8         | 14.81%  |
| Intel AX201 Bluetooth                                  | 6         | 11.11%  |
| Intel Centrino Bluetooth Wireless Transceiver          | 3         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]     | 3         | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                       | 2         | 3.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter       | 2         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 2         | 3.7%    |
| Apple Apple Broadcom Built-in Bluetooth                | 2         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 1.85%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                | 1         | 1.85%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device   | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Bluetooth                      | 1         | 1.85%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device     | 1         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1         | 1.85%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 1.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 1.85%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 1.85%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter             | 1         | 1.85%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth          | 1         | 1.85%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 1.85%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 1.85%   |
| Broadcom BCM43142A0 Bluetooth Module                   | 1         | 1.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 1         | 1.85%   |
| ASUS ASUS USB-BT500                                    | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 131       | 69.31%  |
| AMD                   | 35        | 18.52%  |
| Nvidia                | 15        | 7.94%   |
| C-Media Electronics   | 2         | 1.06%   |
| VIA Technologies      | 1         | 0.53%   |
| ROCCAT                | 1         | 0.53%   |
| Realtek Semiconductor | 1         | 0.53%   |
| Kingston Technology   | 1         | 0.53%   |
| Creative Technology   | 1         | 0.53%   |
| Creative Labs         | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 7.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 6.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 5.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 5.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 4.39%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 3.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.75%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.32%   |
| Unknown                                                                                           | 3         | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.88%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.88%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.44%   |
| ROCCAT USB PnP Sound Device                                                                       | 1         | 0.44%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                                                  | 1         | 0.44%   |
| Nvidia unknown                                                                                    | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 59        | 26.46%  |
| SK hynix            | 39        | 17.49%  |
| Kingston            | 30        | 13.45%  |
| Unknown             | 18        | 8.07%   |
| GOODRAM             | 17        | 7.62%   |
| Micron Technology   | 15        | 6.73%   |
| Crucial             | 10        | 4.48%   |
| Ramaxel Technology  | 5         | 2.24%   |
| G.Skill             | 5         | 2.24%   |
| Corsair             | 4         | 1.79%   |
| Patriot             | 3         | 1.35%   |
| Nanya Technology    | 2         | 0.9%    |
| Unknown             | 2         | 0.9%    |
| Wilk                | 1         | 0.45%   |
| Unknown (ABCD)      | 1         | 0.45%   |
| Unknown (07FB)      | 1         | 0.45%   |
| Transcend           | 1         | 0.45%   |
| Toshiba             | 1         | 0.45%   |
| Qimonda             | 1         | 0.45%   |
| Lexar Co Limited    | 1         | 0.45%   |
| Kimtigo             | 1         | 0.45%   |
| Innodisk            | 1         | 0.45%   |
| Hewlett-Packard     | 1         | 0.45%   |
| GeIL                | 1         | 0.45%   |
| Elpida              | 1         | 0.45%   |
| A-DATA Technology   | 1         | 0.45%   |
| A-DA                | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s    | 15        | 6.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s     | 6         | 2.51%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 4         | 1.67%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 3         | 1.26%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s      | 3         | 1.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.26%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 3         | 1.26%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2         | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                 | 2         | 0.84%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.84%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 0.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 0.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s    | 2         | 0.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 2         | 0.84%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s     | 2         | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 2         | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s     | 2         | 0.84%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 0.84%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s        | 2         | 0.84%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s    | 2         | 0.84%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                | 2         | 0.84%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s   | 2         | 0.84%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s      | 2         | 0.84%   |
| Goodram RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s     | 2         | 0.84%   |
| Crucial RAM CT4G4SFS8266.M8FG 4GB SODIMM DDR4 2667MT/s    | 2         | 0.84%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s   | 2         | 0.84%   |
| Unknown                                                   | 2         | 0.84%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s       | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s               | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                  | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR                         | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s               | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 111       | 56.92%  |
| DDR4    | 66        | 33.85%  |
| DDR2    | 7         | 3.59%   |
| Unknown | 3         | 1.54%   |
| LPDDR4  | 2         | 1.03%   |
| LPDDR3  | 2         | 1.03%   |
| DDR     | 2         | 1.03%   |
| SDRAM   | 1         | 0.51%   |
| DRAM    | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 48.97%  |
| DIMM         | 94        | 48.45%  |
| Row Of Chips | 2         | 1.03%   |
| RIMM         | 1         | 0.52%   |
| FB-DIMM      | 1         | 0.52%   |
| Unknown      | 1         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 74        | 35.58%  |
| 4096  | 72        | 34.62%  |
| 2048  | 34        | 16.35%  |
| 16384 | 17        | 8.17%   |
| 1024  | 8         | 3.85%   |
| 512   | 2         | 0.96%   |
| 32768 | 1         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 70        | 33.02%  |
| 1333    | 30        | 14.15%  |
| 2400    | 29        | 13.68%  |
| 2667    | 16        | 7.55%   |
| 3200    | 13        | 6.13%   |
| 2133    | 13        | 6.13%   |
| 1867    | 6         | 2.83%   |
| 1334    | 6         | 2.83%   |
| 800     | 6         | 2.83%   |
| 667     | 6         | 2.83%   |
| 1067    | 4         | 1.89%   |
| 1066    | 3         | 1.42%   |
| Unknown | 3         | 1.42%   |
| 2666    | 2         | 0.94%   |
| 1866    | 2         | 0.94%   |
| 2933    | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| 400     | 1         | 0.47%   |

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
| Chicony Electronics                    | 16        | 37.21%  |
| Microdia                               | 8         | 18.6%   |
| Realtek Semiconductor                  | 4         | 9.3%    |
| Acer                                   | 3         | 6.98%   |
| Sunplus Innovation Technology          | 2         | 4.65%   |
| Ricoh                                  | 2         | 4.65%   |
| Logitech                               | 2         | 4.65%   |
| Lite-On Technology                     | 2         | 4.65%   |
| Syntek                                 | 1         | 2.33%   |
| Hewlett-Packard                        | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.33%   |
| Apple                                  | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                     | 3         | 6.98%   |
| Microdia Integrated Webcam                                    | 3         | 6.98%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 4.65%   |
| Logitech HD Pro Webcam C920                                   | 2         | 4.65%   |
| Lite-On Integrated Camera                                     | 2         | 4.65%   |
| Chicony Realtek DMFT - RGB                                    | 2         | 4.65%   |
| Chicony Integrated Camera (1280x720@30)                       | 2         | 4.65%   |
| Chicony Integrated Camera                                     | 2         | 4.65%   |
| Chicony HD WebCam                                             | 2         | 4.65%   |
| Syntek Lenovo EasyCamera                                      | 1         | 2.33%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 2.33%   |
| Sunplus Integrated_Webcam_FHD                                 | 1         | 2.33%   |
| Ricoh Integrated Webcam                                       | 1         | 2.33%   |
| Ricoh HD Webcam                                               | 1         | 2.33%   |
| Realtek Integrated_Webcam_HD                                  | 1         | 2.33%   |
| Microdia USB 2.0 Camera                                       | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 2.33%   |
| Microdia Dell Integrated HD Webcam                            | 1         | 2.33%   |
| HP Premium Starter Webcam                                     | 1         | 2.33%   |
| Chicony ThinkPad T490 Webcam                                  | 1         | 2.33%   |
| Chicony Integrated Camera [ThinkPad]                          | 1         | 2.33%   |
| Chicony HP Wide Vision HD Camera                              | 1         | 2.33%   |
| Chicony HP Integrated Webcam                                  | 1         | 2.33%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 2.33%   |
| Chicony Front Camera                                          | 1         | 2.33%   |
| Chicony Chicony USB2.0 Camera                                 | 1         | 2.33%   |
| Chicony 1.3M Webcam                                           | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M WebCam | 1         | 2.33%   |
| Apple FaceTime HD Camera (Built-in)                           | 1         | 2.33%   |
| Acer USB HD Webcam                                            | 1         | 2.33%   |
| Acer Lenovo EasyCamera                                        | 1         | 2.33%   |
| Acer EasyCamera                                               | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 25%     |
| Synaptics                  | 3         | 25%     |
| Broadcom                   | 3         | 25%     |
| STMicroelectronics         | 1         | 8.33%   |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 16.67%  |
| Validity Sensors Fingerprint scanner                                         | 1         | 8.33%   |
| Synaptics  WBDI                                                              | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 8.33%   |
| AuthenTec AES2810                                                            | 1         | 8.33%   |

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
| 1     | 89        | 40.09%  |
| 0     | 58        | 26.13%  |
| 2     | 55        | 24.77%  |
| 3     | 12        | 5.41%   |
| 4     | 5         | 2.25%   |
| 5     | 2         | 0.9%    |
| 6     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 142       | 60.43%  |
| Bluetooth                | 25        | 10.64%  |
| Net/wireless             | 21        | 8.94%   |
| Fingerprint reader       | 12        | 5.11%   |
| Card reader              | 12        | 5.11%   |
| Graphics card            | 9         | 3.83%   |
| Firewire controller      | 5         | 2.13%   |
| Sound                    | 2         | 0.85%   |
| Network                  | 2         | 0.85%   |
| Net/ethernet             | 2         | 0.85%   |
| Storage/nvme             | 1         | 0.43%   |
| Storage                  | 1         | 0.43%   |
| Modem                    | 1         | 0.43%   |

