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

Total: 207

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | H510M K                     | [a952664d92](https://bsd-hardware.info/?probe=a952664d92) | Apr 29, 2023 |
| MSI           | H110M PRO-VD                | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| HP            | 18E5                        | [9f82560327](https://bsd-hardware.info/?probe=9f82560327) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| ASUSTek       | Crosshair IV Formula        | [a7830f5244](https://bsd-hardware.info/?probe=a7830f5244) | Apr 17, 2023 |
| Unknown       | Unknown                     | [fb756bb34e](https://bsd-hardware.info/?probe=fb756bb34e) | Apr 16, 2023 |
| Techvision    | TVI7309X B0                 | [e1e041b34a](https://bsd-hardware.info/?probe=e1e041b34a) | Apr 07, 2023 |
| Techvision    | TVI7309X B0                 | [ac38e117ac](https://bsd-hardware.info/?probe=ac38e117ac) | Apr 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [032a4be314](https://bsd-hardware.info/?probe=032a4be314) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | [f4d583f326](https://bsd-hardware.info/?probe=f4d583f326) | Apr 01, 2023 |
| Techvision    | TVI7309X B0                 | [837fdf1a2c](https://bsd-hardware.info/?probe=837fdf1a2c) | Mar 31, 2023 |
| Dell          | 0T1D10 A01                  | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| HP            | 18E5                        | [1f402a50e7](https://bsd-hardware.info/?probe=1f402a50e7) | Mar 22, 2023 |
| Intel         | X99                         | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b8404f57ba](https://bsd-hardware.info/?probe=b8404f57ba) | Mar 15, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2d5e8056c0](https://bsd-hardware.info/?probe=2d5e8056c0) | Mar 15, 2023 |
| MSI           | A320M-A PRO                 | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e8204efca6](https://bsd-hardware.info/?probe=e8204efca6) | Mar 12, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [29ad0e1044](https://bsd-hardware.info/?probe=29ad0e1044) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [12990e3b0f](https://bsd-hardware.info/?probe=12990e3b0f) | Mar 09, 2023 |
| AMI           | PB_1900A                    | [79504fcf66](https://bsd-hardware.info/?probe=79504fcf66) | Mar 02, 2023 |
| Unknown       | Unknown                     | [78d56cd69d](https://bsd-hardware.info/?probe=78d56cd69d) | Mar 01, 2023 |
| Techvision    | TVI7309X B0                 | [1758c6207c](https://bsd-hardware.info/?probe=1758c6207c) | Feb 27, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| PC Engines    | apu1                        | [41fe7362c4](https://bsd-hardware.info/?probe=41fe7362c4) | Feb 22, 2023 |
| Unknown       | V0.9x                       | [21243cad5f](https://bsd-hardware.info/?probe=21243cad5f) | Feb 21, 2023 |
| MSI           | Z97 GUARD-PRO               | [43d56964b9](https://bsd-hardware.info/?probe=43d56964b9) | Feb 12, 2023 |
| Supermicro    | X8STi                       | [4faeca02d3](https://bsd-hardware.info/?probe=4faeca02d3) | Feb 11, 2023 |
| MSI           | Z97 GUARD-PRO               | [9f066752d5](https://bsd-hardware.info/?probe=9f066752d5) | Feb 11, 2023 |
| HP            | 3396                        | [6a20d52898](https://bsd-hardware.info/?probe=6a20d52898) | Feb 08, 2023 |
| MSI           | Z97 GAMING 3                | [bbe7b327fd](https://bsd-hardware.info/?probe=bbe7b327fd) | Feb 06, 2023 |
| Unknown       | Unknown                     | [cb25ee692c](https://bsd-hardware.info/?probe=cb25ee692c) | Feb 05, 2023 |
| ASUSTek       | P5G41T-M LX3                | [ea5b1c178b](https://bsd-hardware.info/?probe=ea5b1c178b) | Feb 01, 2023 |
| Unknown       | Unknown                     | [e76cc93e5d](https://bsd-hardware.info/?probe=e76cc93e5d) | Jan 31, 2023 |
| Unknown       | Unknown                     | [540696f4e5](https://bsd-hardware.info/?probe=540696f4e5) | Jan 29, 2023 |
| Unknown       | Unknown                     | [6aa648ba82](https://bsd-hardware.info/?probe=6aa648ba82) | Jan 19, 2023 |
| HP            | 1495                        | [4e16deda5a](https://bsd-hardware.info/?probe=4e16deda5a) | Jan 11, 2023 |
| Gigabyte      | H510M K                     | [c30a71f5ae](https://bsd-hardware.info/?probe=c30a71f5ae) | Jan 10, 2023 |
| Biostar       | J4125NHU                    | [41114c45b7](https://bsd-hardware.info/?probe=41114c45b7) | Jan 05, 2023 |
| Gigabyte      | J4005ND2P-CF                | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Acer          | WG43M                       | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Unknown       | Unknown                     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| ASRock        | X570 Pro4                   | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| HP            | 3396                        | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| Gigabyte      | H110TN                      | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| Intel         | D2500CC AAG81477-401        | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| ASRockRack    | EP2C612D16FM                | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Gigabyte      | H510M K                     | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
| Gigabyte      | H510M K                     | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
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
| Shuttle       | FH270                       | [532cda62a8](https://bsd-hardware.info/?probe=532cda62a8) | Oct 29, 2020 |
| Intel         | D53427RKE G87971-406        | [bb6eeb8ef8](https://bsd-hardware.info/?probe=bb6eeb8ef8) | Oct 29, 2020 |
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
| helloSystem 0.7.0 | 8        | 4.62%   |
| OpenBSD 7.0       | 7        | 4.05%   |
| OPNsense 23.1     | 6        | 3.47%   |
| OPNsense 22.7.10  | 6        | 3.47%   |
| OPNsense 23.1.5   | 4        | 2.31%   |
| OPNsense 23.1.1   | 4        | 2.31%   |
| OPNsense 22.7.4   | 4        | 2.31%   |
| OPNsense 22.1.10  | 4        | 2.31%   |
| helloSystem 0.8.1 | 4        | 2.31%   |
| helloSystem 0.6.0 | 4        | 2.31%   |
| FreeBSD 12.3-p2   | 4        | 2.31%   |
| OPNsense 23.1.3   | 3        | 1.73%   |
| OPNsense 22.7.6   | 3        | 1.73%   |
| OPNsense 22.7.2   | 3        | 1.73%   |
| OPNsense 22.7.11  | 3        | 1.73%   |
| OPNsense 22.1     | 3        | 1.73%   |
| OPNsense 21.7.7   | 3        | 1.73%   |
| OPNsense 21.7.3   | 3        | 1.73%   |
| OPNsense 21.1.2   | 3        | 1.73%   |
| OPNsense 21.1.1   | 3        | 1.73%   |
| OPNsense 21.1     | 3        | 1.73%   |
| helloSystem 0.8.0 | 3        | 1.73%   |
| FreeBSD 13.0-p5   | 3        | 1.73%   |
| FreeBSD 12.2-p2   | 3        | 1.73%   |
| FreeBSD 12.1-p8   | 3        | 1.73%   |
| FreeBSD 12.1-p13  | 3        | 1.73%   |
| OPNsense 23.1.6   | 2        | 1.16%   |
| OPNsense 22.7.8   | 2        | 1.16%   |
| OPNsense 22.7     | 2        | 1.16%   |
| OPNsense 22.1.8   | 2        | 1.16%   |
| OPNsense 22.1.6   | 2        | 1.16%   |
| OPNsense 22.1.5   | 2        | 1.16%   |
| OPNsense 22.1.4   | 2        | 1.16%   |
| OPNsense 22.1.1   | 2        | 1.16%   |
| OPNsense 21.7.4   | 2        | 1.16%   |
| OPNsense 21.7.2   | 2        | 1.16%   |
| OPNsense 21.7.1   | 2        | 1.16%   |
| OPNsense 21.1.6   | 2        | 1.16%   |
| OPNsense 21.1.3   | 2        | 1.16%   |
| OpenBSD 7.2       | 2        | 1.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 75       | 55.97%  |
| FreeBSD     | 27       | 20.15%  |
| helloSystem | 19       | 14.18%  |
| OpenBSD     | 10       | 7.46%   |
| XigmaNAS    | 2        | 1.49%   |
| NetBSD      | 1        | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 129      | 96.27%  |
| arm64  | 2        | 1.49%   |
| macppc | 1        | 0.75%   |
| i386   | 1        | 0.75%   |
| armv7  | 1        | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 96       | 70.07%  |
| helloDesktop  | 22       | 16.06%  |
| fvwm          | 6        | 4.38%   |
| GNOME         | 4        | 2.92%   |
| XFCE          | 3        | 2.19%   |
| KDE5          | 3        | 2.19%   |
| TWM           | 1        | 0.73%   |
| i3            | 1        | 0.73%   |
| Enlightenment | 1        | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 98       | 73.13%  |
| X11     | 36       | 26.87%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 108      | 80.6%   |
| SLiM    | 19       | 14.18%  |
| XDM     | 2        | 1.49%   |
| LightDM | 2        | 1.49%   |
| GDM     | 2        | 1.49%   |
| SDDM    | 1        | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 96       | 71.64%  |
| en_US   | 23       | 17.16%  |
| C       | 8        | 5.97%   |
| pl_PL   | 4        | 2.99%   |
| pl      | 1        | 0.75%   |
| fr_FR   | 1        | 0.75%   |
| en_GB   | 1        | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 114      | 85.07%  |
| BIOS | 20       | 14.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 62       | 45.93%  |
| Zfs    | 57       | 42.22%  |
| Ffs    | 10       | 7.41%   |
| Cd9660 | 6        | 4.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 120      | 89.55%  |
| MBR     | 11       | 8.21%   |
| Unknown | 3        | 2.24%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 18       | 13.43%  |
| Hewlett-Packard            | 13       | 9.7%    |
| Unknown                    | 13       | 9.7%    |
| Gigabyte Technology        | 12       | 8.96%   |
| MSI                        | 10       | 7.46%   |
| Intel                      | 10       | 7.46%   |
| ASRock                     | 10       | 7.46%   |
| Dell                       | 9        | 6.72%   |
| Fujitsu                    | 8        | 5.97%   |
| Lenovo                     | 5        | 3.73%   |
| Supermicro                 | 4        | 2.99%   |
| Techvision                 | 3        | 2.24%   |
| Shuttle                    | 3        | 2.24%   |
| PC Engines                 | 2        | 1.49%   |
| ASRockRack                 | 2        | 1.49%   |
| Wistron                    | 1        | 0.75%   |
| ShenZhen MinWin Technology | 1        | 0.75%   |
| Seeed Studio               | 1        | 0.75%   |
| Raspberry Pi Foundation    | 1        | 0.75%   |
| Inventec                   | 1        | 0.75%   |
| iEi                        | 1        | 0.75%   |
| Essentiel B                | 1        | 0.75%   |
| Biostar                    | 1        | 0.75%   |
| Apple                      | 1        | 0.75%   |
| AOpen                      | 1        | 0.75%   |
| AMI                        | 1        | 0.75%   |
| Acer                       | 1        | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 13       | 9.7%    |
| HP t620 PLUS Quad Core TC           | 8        | 5.97%   |
| Fujitsu FUTRO S920                  | 4        | 2.99%   |
| Techvision TVI7309X                 | 3        | 2.24%   |
| ASUS All Series                     | 3        | 2.24%   |
| ASRock Q1900B-ITX                   | 3        | 2.24%   |
| Intel SHARKBAY                      | 2        | 1.49%   |
| Intel Q3XXG4-P V1.0                 | 2        | 1.49%   |
| Gigabyte H110TN                     | 2        | 1.49%   |
| Wistron ProLiant ML110 G5           | 1        | 0.75%   |
| Supermicro X9SCL/X9SCM              | 1        | 0.75%   |
| Supermicro X8STi                    | 1        | 0.75%   |
| Supermicro X7SLA                    | 1        | 0.75%   |
| Supermicro X7DCL                    | 1        | 0.75%   |
| Shuttle XH270                       | 1        | 0.75%   |
| Shuttle SZ270R9                     | 1        | 0.75%   |
| Shuttle SZ270                       | 1        | 0.75%   |
| ShenZhen MinWin MW-NANO-APL-4L      | 1        | 0.75%   |
| Seeed Studio ODYSSEY-X86J4125       | 1        | 0.75%   |
| RPi Raspberry Pi 400                | 1        | 0.75%   |
| PC Engines APU2                     | 1        | 0.75%   |
| PC Engines apu1                     | 1        | 0.75%   |
| MSI MS-7D25                         | 1        | 0.75%   |
| MSI MS-7C52                         | 1        | 0.75%   |
| MSI MS-7C51                         | 1        | 0.75%   |
| MSI MS-7B53                         | 1        | 0.75%   |
| MSI MS-7996                         | 1        | 0.75%   |
| MSI MS-7923                         | 1        | 0.75%   |
| MSI MS-7918                         | 1        | 0.75%   |
| MSI MS-7846                         | 1        | 0.75%   |
| MSI MS-7788                         | 1        | 0.75%   |
| MSI MS-7758                         | 1        | 0.75%   |
| Lenovo V50s-07IMB 11EF000YPB        | 1        | 0.75%   |
| Lenovo ThinkCentre M93 10A2S01Q00   | 1        | 0.75%   |
| Lenovo ThinkCentre M920s 10SJ0011US | 1        | 0.75%   |
| Lenovo ThinkCentre M91p 7033DE6     | 1        | 0.75%   |
| Lenovo ThinkCentre M700 10GS        | 1        | 0.75%   |
| Inventec Z CLASS                    | 1        | 0.75%   |
| Intel X99                           | 1        | 0.75%   |
| Intel SKYBAY                        | 1        | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 13       | 9.7%    |
| HP t620                        | 8        | 5.97%   |
| Fujitsu FUTRO                  | 6        | 4.48%   |
| Dell OptiPlex                  | 5        | 3.73%   |
| Lenovo ThinkCentre             | 4        | 2.99%   |
| Techvision TVI7309X            | 3        | 2.24%   |
| HP Compaq                      | 3        | 2.24%   |
| ASUS All                       | 3        | 2.24%   |
| ASRock Q1900B-ITX              | 3        | 2.24%   |
| Intel SHARKBAY                 | 2        | 1.49%   |
| Intel Q3XXG4-P                 | 2        | 1.49%   |
| HP EliteDesk                   | 2        | 1.49%   |
| Gigabyte H110TN                | 2        | 1.49%   |
| Gigabyte B450M                 | 2        | 1.49%   |
| Dell Vostro                    | 2        | 1.49%   |
| ASUS PRIME                     | 2        | 1.49%   |
| ASUS P5G41T-M                  | 2        | 1.49%   |
| Wistron ProLiant               | 1        | 0.75%   |
| Supermicro X9SCL               | 1        | 0.75%   |
| Supermicro X8STi               | 1        | 0.75%   |
| Supermicro X7SLA               | 1        | 0.75%   |
| Supermicro X7DCL               | 1        | 0.75%   |
| Shuttle XH270                  | 1        | 0.75%   |
| Shuttle SZ270R9                | 1        | 0.75%   |
| Shuttle SZ270                  | 1        | 0.75%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.75%   |
| Seeed Studio ODYSSEY-X86J4125  | 1        | 0.75%   |
| RPi Raspberry                  | 1        | 0.75%   |
| PC Engines APU2                | 1        | 0.75%   |
| PC Engines apu1                | 1        | 0.75%   |
| MSI MS-7D25                    | 1        | 0.75%   |
| MSI MS-7C52                    | 1        | 0.75%   |
| MSI MS-7C51                    | 1        | 0.75%   |
| MSI MS-7B53                    | 1        | 0.75%   |
| MSI MS-7996                    | 1        | 0.75%   |
| MSI MS-7923                    | 1        | 0.75%   |
| MSI MS-7918                    | 1        | 0.75%   |
| MSI MS-7846                    | 1        | 0.75%   |
| MSI MS-7788                    | 1        | 0.75%   |
| MSI MS-7758                    | 1        | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 27       | 20.15%  |
| 2018    | 15       | 11.19%  |
| 2012    | 13       | 9.7%    |
| 2020    | 11       | 8.21%   |
| 2022    | 9        | 6.72%   |
| 2019    | 9        | 6.72%   |
| 2016    | 9        | 6.72%   |
| 2021    | 8        | 5.97%   |
| 2013    | 6        | 4.48%   |
| 2009    | 6        | 4.48%   |
| 2015    | 5        | 3.73%   |
| 2017    | 4        | 2.99%   |
| 2011    | 4        | 2.99%   |
| 2010    | 3        | 2.24%   |
| 2007    | 2        | 1.49%   |
| Unknown | 2        | 1.49%   |
| 2023    | 1        | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 134      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 132      | 98.51%  |
| Yes  | 2        | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 47       | 34.06%  |
| 4.01-8.0    | 37       | 26.81%  |
| 16.01-24.0  | 33       | 23.91%  |
| 32.01-64.0  | 6        | 4.35%   |
| 2.01-3.0    | 5        | 3.62%   |
| 3.01-4.0    | 4        | 2.9%    |
| 24.01-32.0  | 2        | 1.45%   |
| 0.51-1.0    | 2        | 1.45%   |
| 64.01-256.0 | 1        | 0.72%   |
| 1.01-2.0    | 1        | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 82       | 57.34%  |
| 0.51-1.0  | 35       | 24.48%  |
| 1.01-2.0  | 12       | 8.39%   |
| 4.01-8.0  | 4        | 2.8%    |
| 2.01-3.0  | 4        | 2.8%    |
| 8.01-16.0 | 2        | 1.4%    |
| 0         | 2        | 1.4%    |
| 3.01-4.0  | 1        | 0.7%    |
| Unknown   | 1        | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 81       | 56.25%  |
| 2      | 28       | 19.44%  |
| 3      | 10       | 6.94%   |
| 0      | 10       | 6.94%   |
| 6      | 5        | 3.47%   |
| 4      | 5        | 3.47%   |
| 5      | 3        | 2.08%   |
| 9      | 2        | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 80%     |
| Yes       | 27       | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 131      | 97.76%  |
| No        | 3        | 2.24%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 72.06%  |
| Yes       | 38       | 27.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 89.55%  |
| Yes       | 14       | 10.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 134      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Warsaw            | 21       | 13.82%  |
| Wroclaw           | 11       | 7.24%   |
| Gdansk            | 11       | 7.24%   |
| Krakow            | 9        | 5.92%   |
| Lodz              | 5        | 3.29%   |
| Poznan            | 3        | 1.97%   |
| Miedziana Gora    | 3        | 1.97%   |
| Lezno             | 3        | 1.97%   |
| Bydgoszcz         | 3        | 1.97%   |
| Е»ukowo         | 2        | 1.32%   |
| Walendow          | 2        | 1.32%   |
| Siedlce           | 2        | 1.32%   |
| Radzionkow        | 2        | 1.32%   |
| Legionowo         | 2        | 1.32%   |
| Glincz            | 2        | 1.32%   |
| Gdynia            | 2        | 1.32%   |
| Zgierz            | 1        | 0.66%   |
| Zajaczki Pierwsze | 1        | 0.66%   |
| Zagnansk          | 1        | 0.66%   |
| WЕ‚ocЕ‚awek | 1        | 0.66%   |
| Włocławek       | 1        | 0.66%   |
| Wolsztyn          | 1        | 0.66%   |
| Wejherowo         | 1        | 0.66%   |
| Walcz             | 1        | 0.66%   |
| Tychy             | 1        | 0.66%   |
| Torun             | 1        | 0.66%   |
| Szczytno          | 1        | 0.66%   |
| Swadzim           | 1        | 0.66%   |
| Sulejowek         | 1        | 0.66%   |
| Sulechow          | 1        | 0.66%   |
| Stopnica          | 1        | 0.66%   |
| Stary Sacz        | 1        | 0.66%   |
| Spalice           | 1        | 0.66%   |
| Sosnowiec         | 1        | 0.66%   |
| RzeszГіw        | 1        | 0.66%   |
| RzeszÃ³w        | 1        | 0.66%   |
| Rybnik            | 1        | 0.66%   |
| Ruda Śląska     | 1        | 0.66%   |
| Radwanice         | 1        | 0.66%   |
| Radostowice       | 1        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 74     | 16.39%  |
| Seagate             | 25       | 49     | 13.66%  |
| Samsung Electronics | 19       | 46     | 10.38%  |
| GOODRAM             | 15       | 26     | 8.2%    |
| SanDisk             | 14       | 16     | 7.65%   |
| A-DATA Technology   | 10       | 12     | 5.46%   |
| Toshiba             | 9        | 18     | 4.92%   |
| Kingston            | 7        | 7      | 3.83%   |
| Hoodisk             | 5        | 8      | 2.73%   |
| SPCC                | 4        | 5      | 2.19%   |
| Innodisk            | 4        | 6      | 2.19%   |
| PNY                 | 3        | 7      | 1.64%   |
| Patriot             | 3        | 3      | 1.64%   |
| OCZ                 | 3        | 3      | 1.64%   |
| LITEON              | 3        | 3      | 1.64%   |
| Corsair             | 3        | 4      | 1.64%   |
| Apacer              | 3        | 3      | 1.64%   |
| Transcend           | 2        | 7      | 1.09%   |
| Kston               | 2        | 2      | 1.09%   |
| Hitachi             | 2        | 2      | 1.09%   |
| Gigabyte Technology | 2        | 2      | 1.09%   |
| Crucial             | 2        | 3      | 1.09%   |
| Team                | 1        | 1      | 0.55%   |
| SSDPR-CX            | 1        | 1      | 0.55%   |
| SK hynix            | 1        | 1      | 0.55%   |
| Silicon Motion      | 1        | 1      | 0.55%   |
| Plextor             | 1        | 1      | 0.55%   |
| Phison              | 1        | 1      | 0.55%   |
| NVMe                | 1        | 2      | 0.55%   |
| Micron Technology   | 1        | 6      | 0.55%   |
| Lexar               | 1        | 1      | 0.55%   |
| Intenso             | 1        | 2      | 0.55%   |
| HGST                | 1        | 2      | 0.55%   |
| Fanxiang            | 1        | 2      | 0.55%   |
| China               | 1        | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM003-1CH162 1TB     | 4        | 1.92%   |
| WDC WD20EFRX-68EUZN0 2TB           | 3        | 1.44%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 1.44%   |
| Kingston SUV500MS120G 120GB        | 3        | 1.44%   |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 3        | 1.44%   |
| Hoodisk SSD 128GB                  | 3        | 1.44%   |
| GOODRAM SSDPR-CX400-128 128GB      | 3        | 1.44%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 3        | 1.44%   |
| WDC WD20SDZW-11JJ8S0 2TB           | 2        | 0.96%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2        | 0.96%   |
| WDC WD20EARS-00MVWB0 2TB           | 2        | 0.96%   |
| Toshiba MQ04ABF100 1TB             | 2        | 0.96%   |
| SPCC Solid State Disk 256GB        | 2        | 0.96%   |
| Seagate ST96812AS 64GB             | 2        | 0.96%   |
| Seagate ST500LT012-1DG142 500GB    | 2        | 0.96%   |
| Seagate ST2000DL003-9VT166 2TB     | 2        | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.96%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 2        | 0.96%   |
| Samsung SSD 860 EVO 250GB          | 2        | 0.96%   |
| Samsung SSD 850 EVO 250GB          | 2        | 0.96%   |
| PNY CS900 120GB SSD                | 2        | 0.96%   |
| Patriot Burst 120GB                | 2        | 0.96%   |
| GOODRAM SSDPR-CX400-256 256GB      | 2        | 0.96%   |
| Corsair CMFSSD-256D1 256GB         | 2        | 0.96%   |
| A-DATA SU800 256GB                 | 2        | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1        | 0.48%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.48%   |
| WDC WD5003ABYZ-011FA0 500GB        | 1        | 0.48%   |
| WDC WD5002ABYS-50B1B1 500GB        | 1        | 0.48%   |
| WDC WD5000LPVT-75G33T0 500GB       | 1        | 0.48%   |
| WDC WD5000BPVT-08HXZT3 500GB       | 1        | 0.48%   |
| WDC WD360ADFD-00NLR5 37GB          | 1        | 0.48%   |
| WDC WD360ADFD-00NLR1 37GB          | 1        | 0.48%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1        | 0.48%   |
| WDC WD3200AAVS-00ZTB0 320GB        | 1        | 0.48%   |
| WDC WD30EZRZ-00Z5HB0 3TB           | 1        | 0.48%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1        | 0.48%   |
| WDC WD2500AAKX-753CA0 250GB        | 1        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 61     | 38.89%  |
| Seagate             | 25       | 49     | 34.72%  |
| Toshiba             | 9        | 18     | 12.5%   |
| Samsung Electronics | 5        | 11     | 6.94%   |
| Hitachi             | 2        | 2      | 2.78%   |
| SSDPR-CX            | 1        | 1      | 1.39%   |
| NVMe                | 1        | 2      | 1.39%   |
| HGST                | 1        | 2      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 14       | 16     | 14.74%  |
| GOODRAM             | 13       | 24     | 13.68%  |
| Samsung Electronics | 12       | 30     | 12.63%  |
| A-DATA Technology   | 7        | 8      | 7.37%   |
| Kingston            | 6        | 6      | 6.32%   |
| Hoodisk             | 5        | 8      | 5.26%   |
| SPCC                | 4        | 5      | 4.21%   |
| Innodisk            | 4        | 6      | 4.21%   |
| OCZ                 | 3        | 3      | 3.16%   |
| Corsair             | 3        | 4      | 3.16%   |
| Apacer              | 3        | 3      | 3.16%   |
| Transcend           | 2        | 7      | 2.11%   |
| PNY                 | 2        | 5      | 2.11%   |
| Patriot             | 2        | 2      | 2.11%   |
| LITEON              | 2        | 2      | 2.11%   |
| Kston               | 2        | 2      | 2.11%   |
| Gigabyte Technology | 2        | 2      | 2.11%   |
| Crucial             | 2        | 3      | 2.11%   |
| WDC                 | 1        | 12     | 1.05%   |
| Team                | 1        | 1      | 1.05%   |
| Plextor             | 1        | 1      | 1.05%   |
| Phison              | 1        | 1      | 1.05%   |
| Micron Technology   | 1        | 6      | 1.05%   |
| Intenso             | 1        | 2      | 1.05%   |
| China               | 1        | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 82       | 160    | 53.59%  |
| HDD  | 53       | 146    | 34.64%  |
| NVMe | 18       | 22     | 11.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 114      | 306    | 86.36%  |
| NVMe | 18       | 22     | 13.64%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 95       | 187    | 67.86%  |
| 0.51-1.0   | 25       | 57     | 17.86%  |
| 1.01-2.0   | 13       | 34     | 9.29%   |
| 4.01-10.0  | 3        | 10     | 2.14%   |
| 3.01-4.0   | 2        | 6      | 1.43%   |
| 2.01-3.0   | 2        | 12     | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 58       | 40.28%  |
| 1-20           | 23       | 15.97%  |
| 51-100         | 23       | 15.97%  |
| 251-500        | 17       | 11.81%  |
| 21-50          | 10       | 6.94%   |
| 501-1000       | 9        | 6.25%   |
| 1001-2000      | 2        | 1.39%   |
| More than 3000 | 1        | 0.69%   |
| 2001-3000      | 1        | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 126      | 90%     |
| 21-50          | 6        | 4.29%   |
| 101-250        | 3        | 2.14%   |
| 1001-2000      | 2        | 1.43%   |
| 51-100         | 2        | 1.43%   |
| More than 3000 | 1        | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba MQ04ABF100 1TB              | 2        | 2      | 8.33%   |
| Seagate ST96812AS 64GB              | 2        | 5      | 8.33%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 2      | 8.33%   |
| WDC WD360ADFD-00NLR1 37GB           | 1        | 1      | 4.17%   |
| WDC WD3200AAVS-00ZTB0 320GB         | 1        | 1      | 4.17%   |
| WDC WD2500AAKX-753CA0 250GB         | 1        | 1      | 4.17%   |
| WDC WD2500AAKX-083CA1 250GB         | 1        | 2      | 4.17%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1      | 4.17%   |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 1      | 4.17%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 4.17%   |
| WDC WD1600BEVE-00UYT0 160GB         | 1        | 1      | 4.17%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 4.17%   |
| Toshiba MK3261GSYN 320GB            | 1        | 1      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 4.17%   |
| Seagate ST32000542AS 2TB            | 1        | 1      | 4.17%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 1      | 4.17%   |
| SanDisk SSD U100 64GB               | 1        | 2      | 4.17%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 4.17%   |
| Samsung Electronics HD154UI 1.5TB   | 1        | 1      | 4.17%   |
| Hitachi HTS721060G9SA00 64GB        | 1        | 1      | 4.17%   |
| A-DATA Technology SU800 256GB       | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 37.5%   |
| Seagate             | 7        | 10     | 29.17%  |
| Toshiba             | 3        | 3      | 12.5%   |
| Samsung Electronics | 2        | 2      | 8.33%   |
| SanDisk             | 1        | 2      | 4.17%   |
| Hitachi             | 1        | 1      | 4.17%   |
| A-DATA Technology   | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 42.86%  |
| Seagate             | 7        | 10     | 33.33%  |
| Toshiba             | 3        | 3      | 14.29%  |
| Samsung Electronics | 1        | 1      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 25     | 86.96%  |
| SSD  | 3        | 4      | 13.04%  |

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
| Works    | 115      | 293    | 80.99%  |
| Malfunc  | 22       | 29     | 15.49%  |
| Detected | 4        | 5      | 2.82%   |
| Failed   | 1        | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 91       | 58.71%  |
| AMD                           | 35       | 22.58%  |
| Samsung Electronics           | 5        | 3.23%   |
| Silicon Motion                | 4        | 2.58%   |
| SanDisk                       | 2        | 1.29%   |
| Phison Electronics            | 2        | 1.29%   |
| JMicron Technology            | 2        | 1.29%   |
| Broadcom / LSI                | 2        | 1.29%   |
| ASMedia Technology            | 2        | 1.29%   |
| ADATA Technology              | 2        | 1.29%   |
| SK hynix                      | 1        | 0.65%   |
| Shenzhen Longsys Electronics  | 1        | 0.65%   |
| Realtek Semiconductor         | 1        | 0.65%   |
| Nvidia                        | 1        | 0.65%   |
| Marvell Technology Group      | 1        | 0.65%   |
| Lite-On Technology            | 1        | 0.65%   |
| Kingston Technology Company   | 1        | 0.65%   |
| Integrated Technology Express | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 24       | 13.79%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10       | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8        | 4.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7        | 4.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7        | 4.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6        | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 2.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5        | 2.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 2.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5        | 2.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4        | 2.3%    |
| Samsung NVMe SSD Controller 980                                                  | 4        | 2.3%    |
| Intel SATA Controller [RAID mode]                                                | 4        | 2.3%    |
| Intel Jasper Lake SATA AHCI Controller                                           | 4        | 2.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4        | 2.3%    |
| AMD 400 Series Chipset SATA Controller                                           | 4        | 2.3%    |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 1.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2        | 1.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2        | 1.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 1.15%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 1.15%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 1.15%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 2        | 1.15%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2        | 1.15%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 2        | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 1.15%   |
| AMD 500 Series Chipset SATA Controller                                           | 2        | 1.15%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2        | 1.15%   |
| Unknown                                                                          | 2        | 1.15%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1        | 0.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1        | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 0.57%   |
| Realtek NVMe Controller                                                          | 1        | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                                | 1        | 0.57%   |
| Phison E12 NVMe Controller                                                       | 1        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 111      | 71.61%  |
| NVMe | 19       | 12.26%  |
| IDE  | 19       | 12.26%  |
| RAID | 4        | 2.58%   |
| SAS  | 1        | 0.65%   |
| SCSI | 1        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 94       | 69.63%  |
| AMD     | 37       | 27.41%  |
| ARM     | 3        | 2.22%   |
| PowerPC | 1        | 0.74%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-420CA SOC with Radeon HD Graphics    | 8        | 5.93%   |
| Intel Celeron N5105 @ 2.00GHz               | 4        | 2.96%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 4        | 2.96%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 4        | 2.96%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 2.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 2.22%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 1.48%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 1.48%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.48%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 2        | 1.48%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.48%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.48%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 2        | 1.48%   |
| Intel Atom CPU D2500 @ 1.86GHz              | 2        | 1.48%   |
| ARM Cortex-A72 r0p3                         | 2        | 1.48%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.48%   |
| AMD Ryzen 3 3100 4-Core Processor           | 2        | 1.48%   |
| AMD Phenom II X4 965 Processor              | 2        | 1.48%   |
| PowerPC 7447A (Revision 0x102)              | 1        | 0.74%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.74%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 0.74%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.74%   |
| Intel Xeon CPU E31225 @ 3.10GH              | 1        | 0.74%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 1        | 0.74%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.74%   |
| Intel Pentium Dual-Core CPU E6              | 1        | 0.74%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.74%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.74%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.74%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.74%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 0.74%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 0.74%   |
| Intel Core i7-5550U CPU @ 2.00GHz           | 1        | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 0.74%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 20%     |
| Intel Celeron           | 23       | 17.04%  |
| AMD GX                  | 14       | 10.37%  |
| Intel Core i7           | 9        | 6.67%   |
| Intel Core i3           | 8        | 5.93%   |
| Intel Xeon              | 7        | 5.19%   |
| Intel Pentium           | 7        | 5.19%   |
| Intel Atom              | 5        | 3.7%    |
| Other                   | 4        | 2.96%   |
| AMD Ryzen 5             | 4        | 2.96%   |
| AMD Ryzen 3             | 4        | 2.96%   |
| ARM Cortex              | 3        | 2.22%   |
| AMD G                   | 3        | 2.22%   |
| Intel Pentium Dual-Core | 2        | 1.48%   |
| AMD Ryzen 9             | 2        | 1.48%   |
| AMD Ryzen 7             | 2        | 1.48%   |
| AMD Phenom II X4        | 2        | 1.48%   |
| Intel Core 2 Quad       | 1        | 0.74%   |
| Intel Core 2 Duo        | 1        | 0.74%   |
| Intel Core 2            | 1        | 0.74%   |
| AMD Ryzen 5 PRO         | 1        | 0.74%   |
| AMD Phenom II X6        | 1        | 0.74%   |
| AMD E                   | 1        | 0.74%   |
| AMD Athlon 64 X2        | 1        | 0.74%   |
| AMD Athlon              | 1        | 0.74%   |
| AMD A4                  | 1        | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 70       | 51.85%  |
| 2       | 34       | 25.19%  |
| Unknown | 8        | 5.93%   |
| 6       | 6        | 4.44%   |
| 8       | 5        | 3.7%    |
| 12      | 4        | 2.96%   |
| 1       | 3        | 2.22%   |
| 16      | 2        | 1.48%   |
| 32      | 1        | 0.74%   |
| 24      | 1        | 0.74%   |
| 20      | 1        | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 126      | 94.03%  |
| Unknown | 6        | 4.48%   |
| 2       | 2        | 1.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 95       | 70.37%  |
| 2       | 30       | 22.22%  |
| Unknown | 10       | 7.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 19       | 14.07%  |
| Jaguar        | 15       | 11.11%  |
| Unknown       | 13       | 9.63%   |
| SandyBridge   | 10       | 7.41%   |
| KabyLake      | 10       | 7.41%   |
| Skylake       | 8        | 5.93%   |
| Silvermont    | 8        | 5.93%   |
| Penryn        | 7        | 5.19%   |
| IvyBridge     | 7        | 5.19%   |
| Goldmont plus | 6        | 4.44%   |
| Zen 2         | 4        | 2.96%   |
| Zen           | 4        | 2.96%   |
| Bonnell       | 4        | 2.96%   |
| Bobcat        | 4        | 2.96%   |
| Zen 3         | 3        | 2.22%   |
| K10           | 3        | 2.22%   |
| Goldmont      | 2        | 1.48%   |
| Zen+          | 1        | 0.74%   |
| Westmere      | 1        | 0.74%   |
| Puma          | 1        | 0.74%   |
| Nehalem       | 1        | 0.74%   |
| K8 Hammer     | 1        | 0.74%   |
| Core          | 1        | 0.74%   |
| CometLake     | 1        | 0.74%   |
| Broadwell     | 1        | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 78       | 57.35%  |
| AMD                                          | 35       | 25.74%  |
| Nvidia                                       | 17       | 12.5%   |
| Matrox Electronics Systems                   | 3        | 2.21%   |
| ASPEED Technology                            | 2        | 1.47%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 8.03%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 8        | 5.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 5.11%   |
| Intel HD Graphics 530                                                                    | 6        | 4.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6        | 4.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 4.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 3.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 2.92%   |
| Intel JasperLake [UHD Graphics]                                                          | 4        | 2.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2.92%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 4        | 2.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 2.19%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.19%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.46%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 1.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2        | 1.46%   |
| Intel HD Graphics 630                                                                    | 2        | 1.46%   |
| Intel HD Graphics 500                                                                    | 2        | 1.46%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 1.46%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.46%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.46%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2        | 1.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.46%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.73%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.73%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.73%   |
| Nvidia GM206GL [Quadro M2000]                                                            | 1        | 0.73%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 0.73%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.73%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 0.73%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.73%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 0.73%   |
| Nvidia GF100 [GeForce GTX 470]                                                           | 1        | 0.73%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 0.73%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 1        | 0.73%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 0.73%   |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1        | 0.73%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 72       | 52.94%  |
| 1 x AMD         | 32       | 23.53%  |
| 1 x Nvidia      | 14       | 10.29%  |
| Other           | 5        | 3.68%   |
| 2 x Intel       | 3        | 2.21%   |
| 1 x Matrox      | 3        | 2.21%   |
| Intel + Nvidia  | 2        | 1.47%   |
| 1 x XGI         | 1        | 0.74%   |
| Nvidia + ASPEED | 1        | 0.74%   |
| Intel + AMD     | 1        | 0.74%   |
| AMD + Nvidia    | 1        | 0.74%   |
| AMD + ASPEED    | 1        | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 117      | 87.31%  |
| Proprietary | 10       | 7.46%   |
| Unknown     | 7        | 5.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 114      | 85.07%  |
| 1.01-2.0   | 6        | 4.48%   |
| 7.01-8.0   | 5        | 3.73%   |
| 3.01-4.0   | 5        | 3.73%   |
| 0.01-0.5   | 2        | 1.49%   |
| 8.01-16.0  | 1        | 0.75%   |
| 0.51-1.0   | 1        | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| NEC Computers       | 5        | 15.63%  |
| Samsung Electronics | 4        | 12.5%   |
| Acer                | 4        | 12.5%   |
| Dell                | 3        | 9.38%   |
| Philips             | 2        | 6.25%   |
| Iiyama              | 2        | 6.25%   |
| Idek Iiyama         | 2        | 6.25%   |
| Goldstar            | 2        | 6.25%   |
| Vestel Elektronik   | 1        | 3.13%   |
| Toshiba             | 1        | 3.13%   |
| HPN                 | 1        | 3.13%   |
| Hewlett-Packard     | 1        | 3.13%   |
| Eizo                | 1        | 3.13%   |
| BenQ                | 1        | 3.13%   |
| AOC                 | 1        | 3.13%   |
| Unknown             | 1        | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1        | 3.13%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 3.13%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1        | 3.13%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 3.13%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 1        | 3.13%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1        | 3.13%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch             | 1        | 3.13%   |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch            | 1        | 3.13%   |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch         | 1        | 3.13%   |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch          | 1        | 3.13%   |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch           | 1        | 3.13%   |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch              | 1        | 3.13%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 3.13%   |
| Iiyama PL2773HD IVM6606 1920x1080 600x340mm 27.2-inch                 | 1        | 3.13%   |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                            | 1        | 3.13%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                            | 1        | 3.13%   |
| HPN LCD Monitor HP E233 1920x1080                                     | 1        | 3.13%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 1        | 3.13%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1        | 3.13%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 3.13%   |
| Eizo EV2455 ENC2533 1920x1200 520x330mm 24.2-inch                     | 1        | 3.13%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1        | 3.13%   |
| Dell U2212HM DELD047 1920x1080 480x270mm 21.7-inch                    | 1        | 3.13%   |
| Dell P2312H DEL4076 1920x1080 510x290mm 23.1-inch                     | 1        | 3.13%   |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                      | 1        | 3.13%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                      | 1        | 3.13%   |
| Acer X193HQ ACR0064 1366x768 400x250mm 18.6-inch                      | 1        | 3.13%   |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 3.13%   |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                     | 1        | 3.13%   |
| Acer EG220Q ACR06A1 1920x1080 480x270mm 21.7-inch                     | 1        | 3.13%   |
| Unknown                                                               | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 41.38%  |
| 3840x2160 (4K)     | 4        | 13.79%  |
| 1366x768 (WXGA)    | 3        | 10.34%  |
| 1920x540           | 2        | 6.9%    |
| 1920x1200 (WUXGA)  | 2        | 6.9%    |
| 1680x1050 (WSXGA+) | 2        | 6.9%    |
| 5760x2160          | 1        | 3.45%   |
| 2560x1440 (QHD)    | 1        | 3.45%   |
| 2560x1080          | 1        | 3.45%   |
| Unknown            | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 17.24%  |
| 21      | 5        | 17.24%  |
| Unknown | 4        | 13.79%  |
| 23      | 3        | 10.34%  |
| 18      | 3        | 10.34%  |
| 42      | 2        | 6.9%    |
| 31      | 2        | 6.9%    |
| 50      | 1        | 3.45%   |
| 40      | 1        | 3.45%   |
| 28      | 1        | 3.45%   |
| 27      | 1        | 3.45%   |
| 22      | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 9        | 31.03%  |
| 501-600     | 8        | 27.59%  |
| Unknown     | 4        | 13.79%  |
| 601-700     | 3        | 10.34%  |
| 901-1000    | 2        | 6.9%    |
| 801-900     | 1        | 3.45%   |
| 351-400     | 1        | 3.45%   |
| 1001-1500   | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 62.96%  |
| 16/10   | 4        | 14.81%  |
| Unknown | 4        | 14.81%  |
| 3/2     | 1        | 3.7%    |
| 21/9    | 1        | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 35.71%  |
| 251-300        | 4        | 14.29%  |
| Unknown        | 4        | 14.29%  |
| 501-1000       | 3        | 10.71%  |
| 351-500        | 2        | 7.14%   |
| 141-150        | 2        | 7.14%   |
| More than 1000 | 1        | 3.57%   |
| 301-350        | 1        | 3.57%   |
| 151-200        | 1        | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 48.15%  |
| 101-120 | 6        | 22.22%  |
| Unknown | 4        | 14.81%  |
| 1-50    | 2        | 7.41%   |
| 121-160 | 2        | 7.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 104      | 77.61%  |
| 1     | 25       | 18.66%  |
| 2     | 4        | 2.99%   |
| 3     | 1        | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 89       | 43.2%   |
| Realtek Semiconductor           | 74       | 35.92%  |
| Qualcomm Atheros                | 12       | 5.83%   |
| Broadcom                        | 11       | 5.34%   |
| Qualcomm Atheros Communications | 4        | 1.94%   |
| Huawei Technologies             | 2        | 0.97%   |
| Xiaomi                          | 1        | 0.49%   |
| U-Blox                          | 1        | 0.49%   |
| TP-Link                         | 1        | 0.49%   |
| Seeed Technology                | 1        | 0.49%   |
| Ralink                          | 1        | 0.49%   |
| Nuvoton                         | 1        | 0.49%   |
| NetGear                         | 1        | 0.49%   |
| Mellanox Technologies           | 1        | 0.49%   |
| Marvell Technology Group        | 1        | 0.49%   |
| IMC Networks                    | 1        | 0.49%   |
| D-Link System                   | 1        | 0.49%   |
| Apple                           | 1        | 0.49%   |
| American Megatrends             | 1        | 0.49%   |
| 3Com                            | 1        | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 67       | 27.92%  |
| Intel I211 Gigabit Network Connection                                         | 15       | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 4.17%   |
| Intel I350 Gigabit Network Connection                                         | 9        | 3.75%   |
| Intel I210 Gigabit Network Connection                                         | 9        | 3.75%   |
| Intel Ethernet Connection I217-LM                                             | 8        | 3.33%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 3.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 2.5%    |
| Intel Ethernet Controller I226-V                                              | 5        | 2.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5        | 2.08%   |
| Intel Ethernet Controller I225-V                                              | 4        | 1.67%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 1.67%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.25%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 1.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 0.83%   |
| Intel Wireless 8260                                                           | 2        | 0.83%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 0.83%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.83%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 0.83%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.42%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.42%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.42%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.42%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 0.42%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.42%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 10       | 24.39%  |
| Intel                           | 9        | 21.95%  |
| Realtek Semiconductor           | 7        | 17.07%  |
| Broadcom                        | 6        | 14.63%  |
| Qualcomm Atheros Communications | 4        | 9.76%   |
| TP-Link                         | 1        | 2.44%   |
| Ralink                          | 1        | 2.44%   |
| NetGear                         | 1        | 2.44%   |
| IMC Networks                    | 1        | 2.44%   |
| D-Link System                   | 1        | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 9.76%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3        | 7.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 4.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 4.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 4.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 4.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 4.88%   |
| Intel Wireless 8260                                                           | 2        | 4.88%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 4.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 2.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 2.44%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 2.44%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 2.44%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 2.44%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.44%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 2.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 2.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 2.44%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 2.44%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1        | 2.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 2.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1        | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 86       | 50.59%  |
| Realtek Semiconductor    | 70       | 41.18%  |
| Broadcom                 | 5        | 2.94%   |
| Qualcomm Atheros         | 3        | 1.76%   |
| Xiaomi                   | 1        | 0.59%   |
| Marvell Technology Group | 1        | 0.59%   |
| Huawei Technologies      | 1        | 0.59%   |
| Apple                    | 1        | 0.59%   |
| American Megatrends      | 1        | 0.59%   |
| 3Com                     | 1        | 0.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 67       | 34.54%  |
| Intel I211 Gigabit Network Connection                                          | 15       | 7.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 5.15%   |
| Intel I350 Gigabit Network Connection                                          | 9        | 4.64%   |
| Intel I210 Gigabit Network Connection                                          | 9        | 4.64%   |
| Intel Ethernet Connection I217-LM                                              | 8        | 4.12%   |
| Intel 82574L Gigabit Network Connection                                        | 8        | 4.12%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 6        | 3.09%   |
| Intel Ethernet Controller I226-V                                               | 5        | 2.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 5        | 2.58%   |
| Intel Ethernet Controller I225-V                                               | 4        | 2.06%   |
| Intel 82580 Gigabit Network Connection                                         | 4        | 2.06%   |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 1.55%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 3        | 1.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 1.03%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 1.03%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 2        | 1.03%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 2        | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.52%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1        | 0.52%   |
| Intel Ethernet Controller X550                                                 | 1        | 0.52%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.52%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 1        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.52%   |
| Intel 82576NS Gigabit Network Connection                                       | 1        | 0.52%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.52%   |
| Intel 82575GB Gigabit Network Connection                                       | 1        | 0.52%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1        | 0.52%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                              | 1        | 0.52%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 1        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.52%   |
| Intel 82546GB Gigabit Ethernet Controller                                      | 1        | 0.52%   |
| Intel 82545GM Gigabit Ethernet Controller                                      | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 131      | 75.29%  |
| WiFi     | 38       | 21.84%  |
| Modem    | 3        | 1.72%   |
| Unknown  | 2        | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 123      | 91.11%  |
| WiFi     | 12       | 8.89%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 28.26%  |
| 2     | 32       | 23.19%  |
| 3     | 24       | 17.39%  |
| 6     | 16       | 11.59%  |
| 4     | 13       | 9.42%   |
| 5     | 10       | 7.25%   |
| 0     | 3        | 2.17%   |
| 7     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 132      | 97.06%  |
| Yes  | 4        | 2.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 35.71%  |
| Cambridge Silicon Radio         | 3        | 21.43%  |
| ASUSTek Computer                | 2        | 14.29%  |
| TP-Link                         | 1        | 7.14%   |
| Qualcomm Atheros Communications | 1        | 7.14%   |
| Qcom                            | 1        | 7.14%   |
| Apple                           | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 21.43%  |
| TP-Link Bluetooth 5.0 USB Adapter                   | 1        | 7.14%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 7.14%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device  | 1        | 7.14%   |
| Intel Bluetooth wireless interface                  | 1        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.14%   |
| Intel AX210 Bluetooth                               | 1        | 7.14%   |
| Intel AX201 Bluetooth                               | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |
| ASUS USB-BT500                                      | 1        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.14%   |
| Apple Bluetooth Host Controller                     | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 78       | 57.35%  |
| AMD                 | 36       | 26.47%  |
| Nvidia              | 15       | 11.03%  |
| Creative Labs       | 2        | 1.47%   |
| C-Media Electronics | 2        | 1.47%   |
| ROCCAT              | 1        | 0.74%   |
| Logitech            | 1        | 0.74%   |
| Creative Technology | 1        | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 14       | 8.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12       | 7.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 6.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 4.68%   |
| AMD FCH Azalia Controller                                                                         | 8        | 4.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7        | 4.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 4.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6        | 3.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6        | 3.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6        | 3.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 2.92%   |
| Intel Jasper Lake HD Audio                                                                        | 4        | 2.34%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 2.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.75%   |
| AMD Wrestler HDMI Audio                                                                           | 3        | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 1.75%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.17%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2        | 1.17%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 1.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 1.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2        | 1.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 1.17%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.17%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 2        | 1.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1.17%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 1.17%   |
| ROCCAT USB PnP Sound Device                                                                       | 1        | 0.58%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.58%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.58%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 23       | 16.67%  |
| Samsung Electronics | 22       | 15.94%  |
| SK hynix            | 21       | 15.22%  |
| Unknown             | 14       | 10.14%  |
| Goodram             | 12       | 8.7%    |
| Micron Technology   | 9        | 6.52%   |
| Crucial             | 8        | 5.8%    |
| G.Skill             | 5        | 3.62%   |
| Corsair             | 5        | 3.62%   |
| Patriot             | 4        | 2.9%    |
| Unknown             | 3        | 2.17%   |
| Wilk                | 2        | 1.45%   |
| Nanya Technology    | 2        | 1.45%   |
| Unknown (ABCD)      | 1        | 0.72%   |
| Unknown (07FB)      | 1        | 0.72%   |
| Toshiba             | 1        | 0.72%   |
| Ramaxel Technology  | 1        | 0.72%   |
| Qimonda             | 1        | 0.72%   |
| Lexar Co Limited    | 1        | 0.72%   |
| Kimtigo             | 1        | 0.72%   |
| GeIL                | 1        | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3        | 2%      |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 2%      |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 2%      |
| Unknown                                                        | 3        | 2%      |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 2        | 1.33%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 2        | 1.33%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s          | 2        | 1.33%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s          | 2        | 1.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 2        | 1.33%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s             | 2        | 1.33%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2        | 1.33%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s         | 2        | 1.33%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                     | 2        | 1.33%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2        | 1.33%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s           | 2        | 1.33%   |
| Wilk RAM IR2400D464L15S/8G 8GB DIMM DDR4 2400MT/s              | 1        | 0.67%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s            | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM                                    | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.67%   |
| Unknown RAM Module 16384MB DIMM DDR3 800MT/s                   | 1        | 0.67%   |
| Unknown RAM 8G2400MHz 8GB SODIMM DDR4 2400MT/s                 | 1        | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.67%   |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s   | 1        | 0.67%   |
| Toshiba RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s               | 1        | 0.67%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s          | 1        | 0.67%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1        | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.67%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.67%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1        | 0.67%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 800MT/s          | 1        | 0.67%   |
| SK hynix RAM HMAA4GS6AJR8N-VK 32GB SODIMM DDR4 2667MT/s        | 1        | 0.67%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 66       | 54.55%  |
| DDR4    | 41       | 33.88%  |
| Unknown | 5        | 4.13%   |
| DDR2    | 4        | 3.31%   |
| SDRAM   | 2        | 1.65%   |
| LPDDR4  | 1        | 0.83%   |
| DDR5    | 1        | 0.83%   |
| DDR     | 1        | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 76       | 63.33%  |
| SODIMM | 43       | 35.83%  |
| RIMM   | 1        | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 52       | 39.69%  |
| 4096  | 41       | 31.3%   |
| 2048  | 23       | 17.56%  |
| 16384 | 8        | 6.11%   |
| 1024  | 4        | 3.05%   |
| 32768 | 2        | 1.53%   |
| 512   | 1        | 0.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 44       | 34.38%  |
| 1333    | 20       | 15.63%  |
| 2400    | 16       | 12.5%   |
| 3200    | 10       | 7.81%   |
| 2667    | 7        | 5.47%   |
| 2133    | 6        | 4.69%   |
| 800     | 4        | 3.13%   |
| 667     | 4        | 3.13%   |
| 1867    | 3        | 2.34%   |
| 2666    | 2        | 1.56%   |
| 1066    | 2        | 1.56%   |
| Unknown | 2        | 1.56%   |
| 5200    | 1        | 0.78%   |
| 3600    | 1        | 0.78%   |
| 3333    | 1        | 0.78%   |
| 3000    | 1        | 0.78%   |
| 2933    | 1        | 0.78%   |
| 1866    | 1        | 0.78%   |
| 1334    | 1        | 0.78%   |
| 1067    | 1        | 0.78%   |

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
| 1     | 73       | 54.07%  |
| 0     | 52       | 38.52%  |
| 2     | 8        | 5.93%   |
| 4     | 1        | 0.74%   |
| 3     | 1        | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 68       | 73.12%  |
| Net/wireless             | 10       | 10.75%  |
| Firewire controller      | 4        | 4.3%    |
| Bluetooth                | 4        | 4.3%    |
| Net/ethernet             | 2        | 2.15%   |
| Graphics card            | 2        | 2.15%   |
| Sound                    | 1        | 1.08%   |
| Network                  | 1        | 1.08%   |
| Card reader              | 1        | 1.08%   |

