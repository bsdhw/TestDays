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

Total: 226

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | 05XGC8 A00                  | [f79924e37b](https://bsd-hardware.info/?probe=f79924e37b) | Jun 08, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [95ceb1335c](https://bsd-hardware.info/?probe=95ceb1335c) | Jun 04, 2023 |
| Dell          | 05XGC8 A00                  | [98ebd3efdb](https://bsd-hardware.info/?probe=98ebd3efdb) | Jun 02, 2023 |
| Unknown       | Unknown                     | [e057606b14](https://bsd-hardware.info/?probe=e057606b14) | May 29, 2023 |
| NU591R        | 1.0                         | [e4bdd753d1](https://bsd-hardware.info/?probe=e4bdd753d1) | May 28, 2023 |
| Dell          | 05XGC8 A00                  | [b121b2cba9](https://bsd-hardware.info/?probe=b121b2cba9) | May 26, 2023 |
| Unknown       | Unknown                     | [1070ff80a8](https://bsd-hardware.info/?probe=1070ff80a8) | May 26, 2023 |
| PC Engines    | apu6                        | [cfebc05e50](https://bsd-hardware.info/?probe=cfebc05e50) | May 21, 2023 |
| PC Engines    | apu6                        | [320d6a85a3](https://bsd-hardware.info/?probe=320d6a85a3) | May 21, 2023 |
| HP            | 213D A01                    | [8e1d1d5670](https://bsd-hardware.info/?probe=8e1d1d5670) | May 20, 2023 |
| PC Engines    | apu4                        | [1d4c0fad6a](https://bsd-hardware.info/?probe=1d4c0fad6a) | May 16, 2023 |
| PC Engines    | apu4                        | [94bdc05090](https://bsd-hardware.info/?probe=94bdc05090) | May 16, 2023 |
| Supermicro    | X8SIL                       | [bb30062fc1](https://bsd-hardware.info/?probe=bb30062fc1) | May 14, 2023 |
| Dell          | 05XGC8 A00                  | [dd2b0657d0](https://bsd-hardware.info/?probe=dd2b0657d0) | May 13, 2023 |
| Dell          | 05XGC8 A00                  | [131214e3a7](https://bsd-hardware.info/?probe=131214e3a7) | May 12, 2023 |
| HP            | 213D A01                    | [92c8d4c54e](https://bsd-hardware.info/?probe=92c8d4c54e) | May 12, 2023 |
| ASRock        | J4125-ITX                   | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Gigabyte      | H510M K                     | [e4a5065086](https://bsd-hardware.info/?probe=e4a5065086) | May 03, 2023 |
| HP            | 213D A01                    | [6810604547](https://bsd-hardware.info/?probe=6810604547) | May 03, 2023 |
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
| helloSystem 0.7.0 | 8        | 4.35%   |
| OpenBSD 7.0       | 7        | 3.8%    |
| OPNsense 23.1     | 6        | 3.26%   |
| OPNsense 22.7.10  | 6        | 3.26%   |
| OPNsense 23.1.7   | 5        | 2.72%   |
| helloSystem 0.8.1 | 5        | 2.72%   |
| OPNsense 23.1.8   | 4        | 2.17%   |
| OPNsense 23.1.5   | 4        | 2.17%   |
| OPNsense 23.1.1   | 4        | 2.17%   |
| OPNsense 22.7.4   | 4        | 2.17%   |
| OPNsense 22.1.10  | 4        | 2.17%   |
| helloSystem 0.6.0 | 4        | 2.17%   |
| FreeBSD 12.3-p2   | 4        | 2.17%   |
| OPNsense 23.1.3   | 3        | 1.63%   |
| OPNsense 22.7.6   | 3        | 1.63%   |
| OPNsense 22.7.2   | 3        | 1.63%   |
| OPNsense 22.7.11  | 3        | 1.63%   |
| OPNsense 22.1     | 3        | 1.63%   |
| OPNsense 21.7.7   | 3        | 1.63%   |
| OPNsense 21.7.3   | 3        | 1.63%   |
| OPNsense 21.1.2   | 3        | 1.63%   |
| OPNsense 21.1.1   | 3        | 1.63%   |
| OPNsense 21.1     | 3        | 1.63%   |
| helloSystem 0.8.0 | 3        | 1.63%   |
| FreeBSD 13.0-p5   | 3        | 1.63%   |
| FreeBSD 12.2-p2   | 3        | 1.63%   |
| FreeBSD 12.1-p8   | 3        | 1.63%   |
| FreeBSD 12.1-p13  | 3        | 1.63%   |
| OPNsense 23.1.6   | 2        | 1.09%   |
| OPNsense 22.7.8   | 2        | 1.09%   |
| OPNsense 22.7     | 2        | 1.09%   |
| OPNsense 22.1.8   | 2        | 1.09%   |
| OPNsense 22.1.6   | 2        | 1.09%   |
| OPNsense 22.1.5   | 2        | 1.09%   |
| OPNsense 22.1.4   | 2        | 1.09%   |
| OPNsense 22.1.1   | 2        | 1.09%   |
| OPNsense 21.7.4   | 2        | 1.09%   |
| OPNsense 21.7.2   | 2        | 1.09%   |
| OPNsense 21.7.1   | 2        | 1.09%   |
| OPNsense 21.1.6   | 2        | 1.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 82       | 57.75%  |
| FreeBSD     | 27       | 19.01%  |
| helloSystem | 20       | 14.08%  |
| OpenBSD     | 10       | 7.04%   |
| XigmaNAS    | 2        | 1.41%   |
| NetBSD      | 1        | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 137      | 96.48%  |
| arm64  | 2        | 1.41%   |
| macppc | 1        | 0.7%    |
| i386   | 1        | 0.7%    |
| armv7  | 1        | 0.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 103      | 71.03%  |
| helloDesktop  | 23       | 15.86%  |
| fvwm          | 6        | 4.14%   |
| GNOME         | 4        | 2.76%   |
| XFCE          | 3        | 2.07%   |
| KDE5          | 3        | 2.07%   |
| TWM           | 1        | 0.69%   |
| i3            | 1        | 0.69%   |
| Enlightenment | 1        | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 105      | 73.94%  |
| X11     | 37       | 26.06%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 115      | 80.99%  |
| SLiM    | 20       | 14.08%  |
| XDM     | 2        | 1.41%   |
| LightDM | 2        | 1.41%   |
| GDM     | 2        | 1.41%   |
| SDDM    | 1        | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 103      | 72.03%  |
| en_US   | 24       | 16.78%  |
| C       | 9        | 6.29%   |
| pl_PL   | 4        | 2.8%    |
| pl      | 1        | 0.7%    |
| fr_FR   | 1        | 0.7%    |
| en_GB   | 1        | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 121      | 85.21%  |
| BIOS | 21       | 14.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 67       | 46.21%  |
| Zfs    | 61       | 42.07%  |
| Ffs    | 10       | 6.9%    |
| Cd9660 | 7        | 4.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 127      | 89.44%  |
| MBR     | 12       | 8.45%   |
| Unknown | 3        | 2.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 18       | 12.68%  |
| Unknown                    | 14       | 9.86%   |
| Hewlett-Packard            | 13       | 9.15%   |
| Gigabyte Technology        | 12       | 8.45%   |
| ASRock                     | 11       | 7.75%   |
| MSI                        | 10       | 7.04%   |
| Intel                      | 10       | 7.04%   |
| Dell                       | 10       | 7.04%   |
| Fujitsu                    | 9        | 6.34%   |
| Supermicro                 | 5        | 3.52%   |
| Lenovo                     | 5        | 3.52%   |
| PC Engines                 | 4        | 2.82%   |
| Techvision                 | 3        | 2.11%   |
| Shuttle                    | 3        | 2.11%   |
| ASRockRack                 | 2        | 1.41%   |
| Wistron                    | 1        | 0.7%    |
| ShenZhen MinWin Technology | 1        | 0.7%    |
| Seeed Studio               | 1        | 0.7%    |
| Raspberry Pi Foundation    | 1        | 0.7%    |
| NU591R                     | 1        | 0.7%    |
| Inventec                   | 1        | 0.7%    |
| iEi                        | 1        | 0.7%    |
| Essentiel B                | 1        | 0.7%    |
| Biostar                    | 1        | 0.7%    |
| Apple                      | 1        | 0.7%    |
| AOpen                      | 1        | 0.7%    |
| AMI                        | 1        | 0.7%    |
| Acer                       | 1        | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 14       | 9.86%   |
| HP t620 PLUS Quad Core TC           | 8        | 5.63%   |
| Fujitsu FUTRO S920                  | 5        | 3.52%   |
| Techvision TVI7309X                 | 3        | 2.11%   |
| ASUS All Series                     | 3        | 2.11%   |
| ASRock Q1900B-ITX                   | 3        | 2.11%   |
| Intel SHARKBAY                      | 2        | 1.41%   |
| Intel Q3XXG4-P V1.0                 | 2        | 1.41%   |
| Gigabyte H110TN                     | 2        | 1.41%   |
| Wistron ProLiant ML110 G5           | 1        | 0.7%    |
| Supermicro X9SCL/X9SCM              | 1        | 0.7%    |
| Supermicro X8STi                    | 1        | 0.7%    |
| Supermicro X8SIL                    | 1        | 0.7%    |
| Supermicro X7SLA                    | 1        | 0.7%    |
| Supermicro X7DCL                    | 1        | 0.7%    |
| Shuttle XH270                       | 1        | 0.7%    |
| Shuttle SZ270R9                     | 1        | 0.7%    |
| Shuttle SZ270                       | 1        | 0.7%    |
| ShenZhen MinWin MW-NANO-APL-4L      | 1        | 0.7%    |
| Seeed Studio ODYSSEY-X86J4125       | 1        | 0.7%    |
| RPi Raspberry Pi 400                | 1        | 0.7%    |
| PC Engines apu6                     | 1        | 0.7%    |
| PC Engines apu4                     | 1        | 0.7%    |
| PC Engines APU2                     | 1        | 0.7%    |
| PC Engines apu1                     | 1        | 0.7%    |
| NU591R NU591R                       | 1        | 0.7%    |
| MSI MS-7D25                         | 1        | 0.7%    |
| MSI MS-7C52                         | 1        | 0.7%    |
| MSI MS-7C51                         | 1        | 0.7%    |
| MSI MS-7B53                         | 1        | 0.7%    |
| MSI MS-7996                         | 1        | 0.7%    |
| MSI MS-7923                         | 1        | 0.7%    |
| MSI MS-7918                         | 1        | 0.7%    |
| MSI MS-7846                         | 1        | 0.7%    |
| MSI MS-7788                         | 1        | 0.7%    |
| MSI MS-7758                         | 1        | 0.7%    |
| Lenovo V50s-07IMB 11EF000YPB        | 1        | 0.7%    |
| Lenovo ThinkCentre M93 10A2S01Q00   | 1        | 0.7%    |
| Lenovo ThinkCentre M920s 10SJ0011US | 1        | 0.7%    |
| Lenovo ThinkCentre M91p 7033DE6     | 1        | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 14       | 9.86%   |
| HP t620                        | 8        | 5.63%   |
| Fujitsu FUTRO                  | 7        | 4.93%   |
| Dell OptiPlex                  | 6        | 4.23%   |
| Lenovo ThinkCentre             | 4        | 2.82%   |
| Techvision TVI7309X            | 3        | 2.11%   |
| HP Compaq                      | 3        | 2.11%   |
| ASUS All                       | 3        | 2.11%   |
| ASRock Q1900B-ITX              | 3        | 2.11%   |
| Intel SHARKBAY                 | 2        | 1.41%   |
| Intel Q3XXG4-P                 | 2        | 1.41%   |
| HP EliteDesk                   | 2        | 1.41%   |
| Gigabyte H110TN                | 2        | 1.41%   |
| Gigabyte B450M                 | 2        | 1.41%   |
| Dell Vostro                    | 2        | 1.41%   |
| ASUS PRIME                     | 2        | 1.41%   |
| ASUS P5G41T-M                  | 2        | 1.41%   |
| Wistron ProLiant               | 1        | 0.7%    |
| Supermicro X9SCL               | 1        | 0.7%    |
| Supermicro X8STi               | 1        | 0.7%    |
| Supermicro X8SIL               | 1        | 0.7%    |
| Supermicro X7SLA               | 1        | 0.7%    |
| Supermicro X7DCL               | 1        | 0.7%    |
| Shuttle XH270                  | 1        | 0.7%    |
| Shuttle SZ270R9                | 1        | 0.7%    |
| Shuttle SZ270                  | 1        | 0.7%    |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.7%    |
| Seeed Studio ODYSSEY-X86J4125  | 1        | 0.7%    |
| RPi Raspberry                  | 1        | 0.7%    |
| PC Engines apu6                | 1        | 0.7%    |
| PC Engines apu4                | 1        | 0.7%    |
| PC Engines APU2                | 1        | 0.7%    |
| PC Engines apu1                | 1        | 0.7%    |
| NU591R NU591R                  | 1        | 0.7%    |
| MSI MS-7D25                    | 1        | 0.7%    |
| MSI MS-7C52                    | 1        | 0.7%    |
| MSI MS-7C51                    | 1        | 0.7%    |
| MSI MS-7B53                    | 1        | 0.7%    |
| MSI MS-7996                    | 1        | 0.7%    |
| MSI MS-7923                    | 1        | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 28       | 19.72%  |
| 2018    | 16       | 11.27%  |
| 2020    | 13       | 9.15%   |
| 2012    | 13       | 9.15%   |
| 2022    | 11       | 7.75%   |
| 2019    | 9        | 6.34%   |
| 2016    | 9        | 6.34%   |
| 2021    | 8        | 5.63%   |
| 2009    | 7        | 4.93%   |
| 2015    | 6        | 4.23%   |
| 2013    | 6        | 4.23%   |
| 2017    | 4        | 2.82%   |
| 2011    | 4        | 2.82%   |
| 2010    | 3        | 2.11%   |
| 2007    | 2        | 1.41%   |
| Unknown | 2        | 1.41%   |
| 2023    | 1        | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 142      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 97.18%  |
| Yes  | 4        | 2.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 51       | 34.93%  |
| 4.01-8.0    | 41       | 28.08%  |
| 16.01-24.0  | 33       | 22.6%   |
| 32.01-64.0  | 6        | 4.11%   |
| 2.01-3.0    | 5        | 3.42%   |
| 3.01-4.0    | 4        | 2.74%   |
| 24.01-32.0  | 2        | 1.37%   |
| 0.51-1.0    | 2        | 1.37%   |
| 64.01-256.0 | 1        | 0.68%   |
| 1.01-2.0    | 1        | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 87       | 57.62%  |
| 0.51-1.0  | 38       | 25.17%  |
| 1.01-2.0  | 12       | 7.95%   |
| 4.01-8.0  | 4        | 2.65%   |
| 2.01-3.0  | 4        | 2.65%   |
| 8.01-16.0 | 2        | 1.32%   |
| 0         | 2        | 1.32%   |
| 3.01-4.0  | 1        | 0.66%   |
| Unknown   | 1        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 86       | 56.58%  |
| 2      | 29       | 19.08%  |
| 3      | 11       | 7.24%   |
| 0      | 11       | 7.24%   |
| 6      | 5        | 3.29%   |
| 4      | 5        | 3.29%   |
| 5      | 3        | 1.97%   |
| 9      | 2        | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 79.86%  |
| Yes       | 29       | 20.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 139      | 97.89%  |
| No        | 3        | 2.11%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 73.61%  |
| Yes       | 38       | 26.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 90.14%  |
| Yes       | 14       | 9.86%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 142      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Warsaw            | 23       | 14.2%   |
| Wroclaw           | 13       | 8.02%   |
| Gdansk            | 11       | 6.79%   |
| Krakow            | 10       | 6.17%   |
| Lodz              | 5        | 3.09%   |
| Poznan            | 3        | 1.85%   |
| Miedziana Gora    | 3        | 1.85%   |
| Lezno             | 3        | 1.85%   |
| Bydgoszcz         | 3        | 1.85%   |
| Е»ukowo         | 2        | 1.23%   |
| Walendow          | 2        | 1.23%   |
| Siedlce           | 2        | 1.23%   |
| Radzionkow        | 2        | 1.23%   |
| Police            | 2        | 1.23%   |
| Legionowo         | 2        | 1.23%   |
| Jelenia Góra     | 2        | 1.23%   |
| Glincz            | 2        | 1.23%   |
| Gdynia            | 2        | 1.23%   |
| Zgierz            | 1        | 0.62%   |
| Zajaczki Pierwsze | 1        | 0.62%   |
| Zagnansk          | 1        | 0.62%   |
| WЕ‚ocЕ‚awek | 1        | 0.62%   |
| Włocławek       | 1        | 0.62%   |
| Wolsztyn          | 1        | 0.62%   |
| Witkow            | 1        | 0.62%   |
| Wejherowo         | 1        | 0.62%   |
| Walcz             | 1        | 0.62%   |
| Tychy             | 1        | 0.62%   |
| Torun             | 1        | 0.62%   |
| Szczytno          | 1        | 0.62%   |
| Swadzim           | 1        | 0.62%   |
| Sulejowek         | 1        | 0.62%   |
| Sulechow          | 1        | 0.62%   |
| Stopnica          | 1        | 0.62%   |
| Stary Sacz        | 1        | 0.62%   |
| Spalice           | 1        | 0.62%   |
| Sosnowiec         | 1        | 0.62%   |
| RzeszГіw        | 1        | 0.62%   |
| RzeszÃ³w        | 1        | 0.62%   |
| Rybnik            | 1        | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 31       | 75     | 16.15%  |
| Seagate             | 26       | 50     | 13.54%  |
| Samsung Electronics | 21       | 49     | 10.94%  |
| GOODRAM             | 16       | 28     | 8.33%   |
| SanDisk             | 14       | 17     | 7.29%   |
| A-DATA Technology   | 10       | 12     | 5.21%   |
| Toshiba             | 9        | 18     | 4.69%   |
| Kingston            | 7        | 7      | 3.65%   |
| SPCC                | 5        | 7      | 2.6%    |
| Hoodisk             | 5        | 9      | 2.6%    |
| Innodisk            | 4        | 6      | 2.08%   |
| PNY                 | 3        | 7      | 1.56%   |
| Patriot             | 3        | 3      | 1.56%   |
| OCZ                 | 3        | 3      | 1.56%   |
| LITEON              | 3        | 3      | 1.56%   |
| Corsair             | 3        | 4      | 1.56%   |
| China               | 3        | 3      | 1.56%   |
| Apacer              | 3        | 3      | 1.56%   |
| Transcend           | 2        | 7      | 1.04%   |
| Kston               | 2        | 2      | 1.04%   |
| Hitachi             | 2        | 2      | 1.04%   |
| Gigabyte Technology | 2        | 2      | 1.04%   |
| Fanxiang            | 2        | 3      | 1.04%   |
| Crucial             | 2        | 3      | 1.04%   |
| Team                | 1        | 1      | 0.52%   |
| SSDPR-CX            | 1        | 1      | 0.52%   |
| SK hynix            | 1        | 1      | 0.52%   |
| Silicon Motion      | 1        | 1      | 0.52%   |
| Plextor             | 1        | 1      | 0.52%   |
| Phison              | 1        | 1      | 0.52%   |
| NVMe                | 1        | 2      | 0.52%   |
| Micron Technology   | 1        | 6      | 0.52%   |
| Lexar               | 1        | 1      | 0.52%   |
| Intenso             | 1        | 2      | 0.52%   |
| HGST                | 1        | 2      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM003-1CH162 1TB     | 4        | 1.83%   |
| WDC WD20EFRX-68EUZN0 2TB           | 3        | 1.38%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 1.38%   |
| Kingston SUV500MS120G 120GB        | 3        | 1.38%   |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 3        | 1.38%   |
| Hoodisk SSD 128GB                  | 3        | 1.38%   |
| GOODRAM SSDPR-CX400-128 128GB      | 3        | 1.38%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 3        | 1.38%   |
| WDC WD20SDZW-11JJ8S0 2TB           | 2        | 0.92%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2        | 0.92%   |
| WDC WD20EARS-00MVWB0 2TB           | 2        | 0.92%   |
| Toshiba MQ04ABF100 1TB             | 2        | 0.92%   |
| SPCC Solid State Disk 256GB        | 2        | 0.92%   |
| Seagate ST96812AS 64GB             | 2        | 0.92%   |
| Seagate ST500LT012-1DG142 500GB    | 2        | 0.92%   |
| Seagate ST2000DL003-9VT166 2TB     | 2        | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.92%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.92%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 2        | 0.92%   |
| Samsung SSD 860 EVO 250GB          | 2        | 0.92%   |
| Samsung SSD 850 EVO 250GB          | 2        | 0.92%   |
| PNY CS900 120GB SSD                | 2        | 0.92%   |
| Patriot Burst 120GB                | 2        | 0.92%   |
| GOODRAM SSDPR-CX400-256-G2 256GB   | 2        | 0.92%   |
| GOODRAM SSDPR-CX400-256 256GB      | 2        | 0.92%   |
| Fanxiang S501 128GB                | 2        | 0.92%   |
| Corsair CMFSSD-256D1 256GB         | 2        | 0.92%   |
| China SATA SSD 32GB                | 2        | 0.92%   |
| A-DATA SU800 256GB                 | 2        | 0.92%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1        | 0.46%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.46%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1        | 0.46%   |
| WDC WD5003ABYZ-011FA0 500GB        | 1        | 0.46%   |
| WDC WD5002ABYS-50B1B1 500GB        | 1        | 0.46%   |
| WDC WD5000LPVT-75G33T0 500GB       | 1        | 0.46%   |
| WDC WD5000BPVT-08HXZT3 500GB       | 1        | 0.46%   |
| WDC WD360ADFD-00NLR5 37GB          | 1        | 0.46%   |
| WDC WD360ADFD-00NLR1 37GB          | 1        | 0.46%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 62     | 38.67%  |
| Seagate             | 26       | 50     | 34.67%  |
| Toshiba             | 9        | 18     | 12%     |
| Samsung Electronics | 6        | 13     | 8%      |
| Hitachi             | 2        | 2      | 2.67%   |
| SSDPR-CX            | 1        | 1      | 1.33%   |
| NVMe                | 1        | 2      | 1.33%   |
| HGST                | 1        | 2      | 1.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 14       | 17     | 14%     |
| GOODRAM             | 14       | 25     | 14%     |
| Samsung Electronics | 13       | 31     | 13%     |
| A-DATA Technology   | 7        | 8      | 7%      |
| Kingston            | 6        | 6      | 6%      |
| SPCC                | 5        | 7      | 5%      |
| Hoodisk             | 5        | 9      | 5%      |
| Innodisk            | 4        | 6      | 4%      |
| OCZ                 | 3        | 3      | 3%      |
| Corsair             | 3        | 4      | 3%      |
| China               | 3        | 3      | 3%      |
| Apacer              | 3        | 3      | 3%      |
| Transcend           | 2        | 7      | 2%      |
| PNY                 | 2        | 5      | 2%      |
| Patriot             | 2        | 2      | 2%      |
| LITEON              | 2        | 2      | 2%      |
| Kston               | 2        | 2      | 2%      |
| Gigabyte Technology | 2        | 2      | 2%      |
| Crucial             | 2        | 3      | 2%      |
| WDC                 | 1        | 12     | 1%      |
| Team                | 1        | 1      | 1%      |
| Plextor             | 1        | 1      | 1%      |
| Phison              | 1        | 1      | 1%      |
| Micron Technology   | 1        | 6      | 1%      |
| Intenso             | 1        | 2      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 87       | 168    | 54.04%  |
| HDD  | 55       | 150    | 34.16%  |
| NVMe | 19       | 24     | 11.8%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 120      | 318    | 86.33%  |
| NVMe | 19       | 24     | 13.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 101      | 198    | 68.71%  |
| 0.51-1.0   | 26       | 58     | 17.69%  |
| 1.01-2.0   | 13       | 34     | 8.84%   |
| 4.01-10.0  | 3        | 10     | 2.04%   |
| 3.01-4.0   | 2        | 6      | 1.36%   |
| 2.01-3.0   | 2        | 12     | 1.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 62       | 40.79%  |
| 1-20           | 25       | 16.45%  |
| 51-100         | 24       | 15.79%  |
| 251-500        | 17       | 11.18%  |
| 21-50          | 11       | 7.24%   |
| 501-1000       | 9        | 5.92%   |
| 1001-2000      | 2        | 1.32%   |
| More than 3000 | 1        | 0.66%   |
| 2001-3000      | 1        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 134      | 90.54%  |
| 21-50          | 6        | 4.05%   |
| 101-250        | 3        | 2.03%   |
| 1001-2000      | 2        | 1.35%   |
| 51-100         | 2        | 1.35%   |
| More than 3000 | 1        | 0.68%   |

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
| Works    | 122      | 307    | 81.88%  |
| Malfunc  | 22       | 29     | 14.77%  |
| Detected | 4        | 5      | 2.68%   |
| Failed   | 1        | 1      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 96       | 58.18%  |
| AMD                           | 38       | 23.03%  |
| Silicon Motion                | 5        | 3.03%   |
| Samsung Electronics           | 5        | 3.03%   |
| ASMedia Technology            | 3        | 1.82%   |
| SanDisk                       | 2        | 1.21%   |
| Phison Electronics            | 2        | 1.21%   |
| JMicron Technology            | 2        | 1.21%   |
| Broadcom / LSI                | 2        | 1.21%   |
| ADATA Technology              | 2        | 1.21%   |
| SK hynix                      | 1        | 0.61%   |
| Shenzhen Longsys Electronics  | 1        | 0.61%   |
| Realtek Semiconductor         | 1        | 0.61%   |
| Nvidia                        | 1        | 0.61%   |
| Marvell Technology Group      | 1        | 0.61%   |
| Lite-On Technology            | 1        | 0.61%   |
| Kingston Technology Company   | 1        | 0.61%   |
| Integrated Technology Express | 1        | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27       | 14.67%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10       | 5.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8        | 4.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7        | 3.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7        | 3.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 5        | 2.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 2.72%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5        | 2.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5        | 2.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 2.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5        | 2.72%   |
| Samsung NVMe SSD Controller 980                                                  | 4        | 2.17%   |
| Intel SATA Controller [RAID mode]                                                | 4        | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4        | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                           | 4        | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3        | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 1.63%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 1.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2        | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2        | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2        | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 1.09%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 1.09%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2        | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 1.09%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 2        | 1.09%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2        | 1.09%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 2        | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                           | 2        | 1.09%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2        | 1.09%   |
| Unknown                                                                          | 2        | 1.09%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1        | 0.54%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1        | 0.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 0.54%   |
| Realtek NVMe Controller                                                          | 1        | 0.54%   |
| Phison PS5013 E13 NVMe Controller                                                | 1        | 0.54%   |
| Phison E12 NVMe Controller                                                       | 1        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 118      | 71.95%  |
| NVMe | 20       | 12.2%   |
| IDE  | 20       | 12.2%   |
| RAID | 4        | 2.44%   |
| SAS  | 1        | 0.61%   |
| SCSI | 1        | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 99       | 69.23%  |
| AMD     | 40       | 27.97%  |
| ARM     | 3        | 2.1%    |
| PowerPC | 1        | 0.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-420CA SOC with Radeon HD Graphics    | 8        | 5.59%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 5        | 3.5%    |
| Intel Celeron N5105 @ 2.00GHz               | 4        | 2.8%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 4        | 2.8%    |
| Intel Celeron CPU J1900 @ 1.99GHz           | 4        | 2.8%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 2.1%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.1%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 2.1%    |
| AMD GX-412TC SOC                            | 3        | 2.1%    |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 1.4%    |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 1.4%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.4%    |
| Intel Core i5-6400T CPU @ 2.20GHz           | 2        | 1.4%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.4%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.4%    |
| Intel Celeron CPU N3150 @ 1.60GHz           | 2        | 1.4%    |
| Intel Atom CPU D2500 @ 1.86GHz              | 2        | 1.4%    |
| ARM Cortex-A72 r0p3                         | 2        | 1.4%    |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.4%    |
| AMD Ryzen 3 3100 4-Core Processor           | 2        | 1.4%    |
| AMD Phenom II X4 965 Processor              | 2        | 1.4%    |
| PowerPC 7447A (Revision 0x102)              | 1        | 0.7%    |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.7%    |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.7%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.7%    |
| Intel Xeon CPU E31225 @ 3.10GH              | 1        | 0.7%    |
| Intel Xeon CPU E31220 @ 3.10GHz             | 1        | 0.7%    |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.7%    |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E6              | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.7%    |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.7%    |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.7%    |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 0.7%    |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 0.7%    |
| Intel Core i7-5550U CPU @ 2.00GHz           | 1        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 18.88%  |
| Intel Celeron           | 25       | 17.48%  |
| AMD GX                  | 17       | 11.89%  |
| Intel Core i7           | 9        | 6.29%   |
| Intel Core i3           | 9        | 6.29%   |
| Intel Xeon              | 8        | 5.59%   |
| Intel Pentium           | 7        | 4.9%    |
| Intel Atom              | 5        | 3.5%    |
| Other                   | 4        | 2.8%    |
| AMD Ryzen 5             | 4        | 2.8%    |
| AMD Ryzen 3             | 4        | 2.8%    |
| ARM Cortex              | 3        | 2.1%    |
| AMD G                   | 3        | 2.1%    |
| Intel Pentium Dual-Core | 2        | 1.4%    |
| AMD Ryzen 9             | 2        | 1.4%    |
| AMD Ryzen 7             | 2        | 1.4%    |
| AMD Phenom II X4        | 2        | 1.4%    |
| Intel Pentium Silver    | 1        | 0.7%    |
| Intel Core 2 Quad       | 1        | 0.7%    |
| Intel Core 2 Duo        | 1        | 0.7%    |
| Intel Core 2            | 1        | 0.7%    |
| AMD Ryzen 5 PRO         | 1        | 0.7%    |
| AMD Phenom II X6        | 1        | 0.7%    |
| AMD E                   | 1        | 0.7%    |
| AMD Athlon 64 X2        | 1        | 0.7%    |
| AMD Athlon              | 1        | 0.7%    |
| AMD A4                  | 1        | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 77       | 53.85%  |
| 2       | 35       | 24.48%  |
| Unknown | 8        | 5.59%   |
| 6       | 6        | 4.2%    |
| 8       | 5        | 3.5%    |
| 12      | 4        | 2.8%    |
| 1       | 3        | 2.1%    |
| 16      | 2        | 1.4%    |
| 32      | 1        | 0.7%    |
| 24      | 1        | 0.7%    |
| 20      | 1        | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 134      | 94.37%  |
| Unknown | 6        | 4.23%   |
| 2       | 2        | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 102      | 71.33%  |
| 2       | 31       | 21.68%  |
| Unknown | 10       | 6.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 19       | 13.29%  |
| Jaguar        | 16       | 11.19%  |
| Unknown       | 14       | 9.79%   |
| SandyBridge   | 10       | 6.99%   |
| KabyLake      | 10       | 6.99%   |
| Skylake       | 9        | 6.29%   |
| Silvermont    | 9        | 6.29%   |
| Penryn        | 7        | 4.9%    |
| IvyBridge     | 7        | 4.9%    |
| Goldmont plus | 7        | 4.9%    |
| Zen 2         | 4        | 2.8%    |
| Zen           | 4        | 2.8%    |
| Bonnell       | 4        | 2.8%    |
| Bobcat        | 4        | 2.8%    |
| Zen 3         | 3        | 2.1%    |
| Puma          | 3        | 2.1%    |
| K10           | 3        | 2.1%    |
| Nehalem       | 2        | 1.4%    |
| Goldmont      | 2        | 1.4%    |
| Zen+          | 1        | 0.7%    |
| Westmere      | 1        | 0.7%    |
| K8 Hammer     | 1        | 0.7%    |
| Core          | 1        | 0.7%    |
| CometLake     | 1        | 0.7%    |
| Broadwell     | 1        | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 82       | 57.75%  |
| AMD                                          | 36       | 25.35%  |
| Nvidia                                       | 17       | 11.97%  |
| Matrox Electronics Systems                   | 4        | 2.82%   |
| ASPEED Technology                            | 2        | 1.41%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 7.69%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 8        | 5.59%   |
| Intel HD Graphics 530                                                                    | 7        | 4.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 4.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 4.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 4.2%    |
| Intel JasperLake [UHD Graphics]                                                          | 5        | 3.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 3.5%    |
| AMD Kabini [Radeon HD 8330E]                                                             | 5        | 3.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 2.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 2.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2.8%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 2.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.1%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2        | 1.4%    |
| Intel HD Graphics 630                                                                    | 2        | 1.4%    |
| Intel HD Graphics 500                                                                    | 2        | 1.4%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 1.4%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.4%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.4%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 2        | 1.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.4%    |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.7%    |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 0.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.7%    |
| Nvidia GM206GL [Quadro M2000]                                                            | 1        | 0.7%    |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.7%    |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 0.7%    |
| Nvidia GF100 [GeForce GTX 470]                                                           | 1        | 0.7%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 0.7%    |
| Nvidia G98 [Quadro NVS 295]                                                              | 1        | 0.7%    |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 0.7%    |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1        | 0.7%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 76       | 52.78%  |
| 1 x AMD         | 33       | 22.92%  |
| 1 x Nvidia      | 14       | 9.72%   |
| Other           | 7        | 4.86%   |
| 1 x Matrox      | 4        | 2.78%   |
| 2 x Intel       | 3        | 2.08%   |
| Intel + Nvidia  | 2        | 1.39%   |
| 1 x XGI         | 1        | 0.69%   |
| Nvidia + ASPEED | 1        | 0.69%   |
| Intel + AMD     | 1        | 0.69%   |
| AMD + Nvidia    | 1        | 0.69%   |
| AMD + ASPEED    | 1        | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 123      | 86.62%  |
| Proprietary | 10       | 7.04%   |
| Unknown     | 9        | 6.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 122      | 85.92%  |
| 1.01-2.0   | 6        | 4.23%   |
| 7.01-8.0   | 5        | 3.52%   |
| 3.01-4.0   | 5        | 3.52%   |
| 0.01-0.5   | 2        | 1.41%   |
| 8.01-16.0  | 1        | 0.7%    |
| 0.51-1.0   | 1        | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| NEC Computers       | 5        | 15.15%  |
| Samsung Electronics | 4        | 12.12%  |
| Acer                | 4        | 12.12%  |
| Philips             | 3        | 9.09%   |
| Dell                | 3        | 9.09%   |
| Iiyama              | 2        | 6.06%   |
| Idek Iiyama         | 2        | 6.06%   |
| Goldstar            | 2        | 6.06%   |
| Vestel Elektronik   | 1        | 3.03%   |
| Toshiba             | 1        | 3.03%   |
| HPN                 | 1        | 3.03%   |
| Hewlett-Packard     | 1        | 3.03%   |
| Eizo                | 1        | 3.03%   |
| BenQ                | 1        | 3.03%   |
| AOC                 | 1        | 3.03%   |
| Unknown             | 1        | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1        | 3.03%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 3.03%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 3.03%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 3.03%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 1        | 3.03%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1        | 3.03%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch             | 1        | 3.03%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                     | 1        | 3.03%   |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch            | 1        | 3.03%   |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch         | 1        | 3.03%   |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch          | 1        | 3.03%   |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch           | 1        | 3.03%   |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch              | 1        | 3.03%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 3.03%   |
| Iiyama PL2773HD IVM6606 1920x1080 600x340mm 27.2-inch                 | 1        | 3.03%   |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                            | 1        | 3.03%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                            | 1        | 3.03%   |
| HPN LCD Monitor HP E233 1920x1080                                     | 1        | 3.03%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 1        | 3.03%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1        | 3.03%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 3.03%   |
| Eizo EV2455 ENC2533 1920x1200 520x330mm 24.2-inch                     | 1        | 3.03%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1        | 3.03%   |
| Dell U2212HM DELD047 1920x1080 480x270mm 21.7-inch                    | 1        | 3.03%   |
| Dell P2312H DEL4076 1920x1080 510x290mm 23.1-inch                     | 1        | 3.03%   |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                      | 1        | 3.03%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                      | 1        | 3.03%   |
| Acer X193HQ ACR0064 1366x768 400x250mm 18.6-inch                      | 1        | 3.03%   |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 3.03%   |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                     | 1        | 3.03%   |
| Acer EG220Q ACR06A1 1920x1080 480x270mm 21.7-inch                     | 1        | 3.03%   |
| Unknown                                                               | 1        | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 40%     |
| 3840x2160 (4K)     | 4        | 13.33%  |
| 1366x768 (WXGA)    | 3        | 10%     |
| 1920x540           | 2        | 6.67%   |
| 1920x1200 (WUXGA)  | 2        | 6.67%   |
| 1680x1050 (WSXGA+) | 2        | 6.67%   |
| 5760x2160          | 1        | 3.33%   |
| 2560x1440 (QHD)    | 1        | 3.33%   |
| 2560x1080          | 1        | 3.33%   |
| 1024x768 (XGA)     | 1        | 3.33%   |
| Unknown            | 1        | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 16.67%  |
| 21      | 5        | 16.67%  |
| Unknown | 4        | 13.33%  |
| 23      | 3        | 10%     |
| 18      | 3        | 10%     |
| 42      | 2        | 6.67%   |
| 31      | 2        | 6.67%   |
| 50      | 1        | 3.33%   |
| 40      | 1        | 3.33%   |
| 28      | 1        | 3.33%   |
| 27      | 1        | 3.33%   |
| 22      | 1        | 3.33%   |
| 14      | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 9        | 30%     |
| 501-600     | 8        | 26.67%  |
| Unknown     | 4        | 13.33%  |
| 601-700     | 3        | 10%     |
| 901-1000    | 2        | 6.67%   |
| 801-900     | 1        | 3.33%   |
| 351-400     | 1        | 3.33%   |
| 201-300     | 1        | 3.33%   |
| 1001-1500   | 1        | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 60.71%  |
| 16/10   | 4        | 14.29%  |
| Unknown | 4        | 14.29%  |
| 4/3     | 1        | 3.57%   |
| 3/2     | 1        | 3.57%   |
| 21/9    | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 34.48%  |
| 251-300        | 4        | 13.79%  |
| Unknown        | 4        | 13.79%  |
| 501-1000       | 3        | 10.34%  |
| 351-500        | 2        | 6.9%    |
| 141-150        | 2        | 6.9%    |
| More than 1000 | 1        | 3.45%   |
| 301-350        | 1        | 3.45%   |
| 151-200        | 1        | 3.45%   |
| 101-110        | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 50%     |
| 101-120 | 6        | 21.43%  |
| Unknown | 4        | 14.29%  |
| 1-50    | 2        | 7.14%   |
| 121-160 | 2        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 111      | 78.17%  |
| 1     | 26       | 18.31%  |
| 2     | 4        | 2.82%   |
| 3     | 1        | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 95       | 43.78%  |
| Realtek Semiconductor           | 78       | 35.94%  |
| Qualcomm Atheros                | 12       | 5.53%   |
| Broadcom                        | 12       | 5.53%   |
| Qualcomm Atheros Communications | 4        | 1.84%   |
| Huawei Technologies             | 2        | 0.92%   |
| Xiaomi                          | 1        | 0.46%   |
| U-Blox                          | 1        | 0.46%   |
| TP-Link                         | 1        | 0.46%   |
| Seeed Technology                | 1        | 0.46%   |
| Ralink                          | 1        | 0.46%   |
| Nuvoton                         | 1        | 0.46%   |
| NetGear                         | 1        | 0.46%   |
| Mellanox Technologies           | 1        | 0.46%   |
| Marvell Technology Group        | 1        | 0.46%   |
| IMC Networks                    | 1        | 0.46%   |
| D-Link System                   | 1        | 0.46%   |
| Apple                           | 1        | 0.46%   |
| American Megatrends             | 1        | 0.46%   |
| 3Com                            | 1        | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 71       | 28.17%  |
| Intel I211 Gigabit Network Connection                                         | 18       | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 3.97%   |
| Intel I350 Gigabit Network Connection                                         | 9        | 3.57%   |
| Intel I210 Gigabit Network Connection                                         | 9        | 3.57%   |
| Intel 82574L Gigabit Network Connection                                       | 9        | 3.57%   |
| Intel Ethernet Connection I217-LM                                             | 8        | 3.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 2.78%   |
| Intel Ethernet Controller I226-V                                              | 6        | 2.38%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5        | 1.98%   |
| Intel Ethernet Controller I225-V                                              | 4        | 1.59%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 1.59%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 1.59%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.19%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 1.19%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3        | 1.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 0.79%   |
| Intel Wireless 8260                                                           | 2        | 0.79%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 0.79%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.79%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.4%    |
| U-Blox [u-blox 7]                                                             | 1        | 0.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.4%    |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.4%    |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 0.4%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.4%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.4%    |

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
| Intel                    | 92       | 50.83%  |
| Realtek Semiconductor    | 74       | 40.88%  |
| Broadcom                 | 6        | 3.31%   |
| Qualcomm Atheros         | 3        | 1.66%   |
| Xiaomi                   | 1        | 0.55%   |
| Marvell Technology Group | 1        | 0.55%   |
| Huawei Technologies      | 1        | 0.55%   |
| Apple                    | 1        | 0.55%   |
| American Megatrends      | 1        | 0.55%   |
| 3Com                     | 1        | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 71       | 34.47%  |
| Intel I211 Gigabit Network Connection                                          | 18       | 8.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 4.85%   |
| Intel I350 Gigabit Network Connection                                          | 9        | 4.37%   |
| Intel I210 Gigabit Network Connection                                          | 9        | 4.37%   |
| Intel 82574L Gigabit Network Connection                                        | 9        | 4.37%   |
| Intel Ethernet Connection I217-LM                                              | 8        | 3.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 7        | 3.4%    |
| Intel Ethernet Controller I226-V                                               | 6        | 2.91%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 5        | 2.43%   |
| Intel Ethernet Controller I225-V                                               | 4        | 1.94%   |
| Intel 82580 Gigabit Network Connection                                         | 4        | 1.94%   |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 1.46%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 3        | 1.46%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 3        | 1.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 0.97%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 0.97%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 2        | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.49%   |
| Intel I210 Gigabit Fiber Network Connection                                    | 1        | 0.49%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1        | 0.49%   |
| Intel Ethernet Controller X550                                                 | 1        | 0.49%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 1        | 0.49%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.49%   |
| Intel 82576NS Gigabit Network Connection                                       | 1        | 0.49%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.49%   |
| Intel 82575GB Gigabit Network Connection                                       | 1        | 0.49%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1        | 0.49%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                              | 1        | 0.49%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 1        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.49%   |
| Intel 82546GB Gigabit Ethernet Controller                                      | 1        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 76.37%  |
| WiFi     | 38       | 20.88%  |
| Modem    | 3        | 1.65%   |
| Unknown  | 2        | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 131      | 91.61%  |
| WiFi     | 12       | 8.39%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 27.21%  |
| 2     | 34       | 23.13%  |
| 3     | 26       | 17.69%  |
| 6     | 16       | 10.88%  |
| 4     | 16       | 10.88%  |
| 5     | 11       | 7.48%   |
| 0     | 3        | 2.04%   |
| 7     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 140      | 97.22%  |
| Yes  | 4        | 2.78%   |

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
| Intel               | 82       | 58.16%  |
| AMD                 | 37       | 26.24%  |
| Nvidia              | 15       | 10.64%  |
| Creative Labs       | 2        | 1.42%   |
| C-Media Electronics | 2        | 1.42%   |
| ROCCAT              | 1        | 0.71%   |
| Logitech            | 1        | 0.71%   |
| Creative Technology | 1        | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 15       | 8.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12       | 6.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 6.21%   |
| AMD FCH Azalia Controller                                                                         | 9        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 4.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8        | 4.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 3.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 3.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7        | 3.95%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6        | 3.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6        | 3.39%   |
| Intel Jasper Lake HD Audio                                                                        | 5        | 2.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4        | 2.26%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 2.26%   |
| AMD Wrestler HDMI Audio                                                                           | 3        | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 1.69%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.13%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2        | 1.13%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 1.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2        | 1.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 1.13%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.13%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 2        | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1.13%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 1.13%   |
| ROCCAT USB PnP Sound Device                                                                       | 1        | 0.56%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.56%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.56%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 23       | 15.65%  |
| Samsung Electronics | 23       | 15.65%  |
| Kingston            | 23       | 15.65%  |
| Unknown             | 16       | 10.88%  |
| GOODRAM             | 12       | 8.16%   |
| Micron Technology   | 11       | 7.48%   |
| Crucial             | 9        | 6.12%   |
| G.Skill             | 5        | 3.4%    |
| Corsair             | 5        | 3.4%    |
| Patriot             | 4        | 2.72%   |
| Unknown             | 3        | 2.04%   |
| Wilk                | 2        | 1.36%   |
| Nanya Technology    | 2        | 1.36%   |
| Unknown (ABCD)      | 1        | 0.68%   |
| Unknown (07FB)      | 1        | 0.68%   |
| Toshiba             | 1        | 0.68%   |
| Ramaxel Technology  | 1        | 0.68%   |
| Qimonda             | 1        | 0.68%   |
| Lexar Co Limited    | 1        | 0.68%   |
| Kimtigo             | 1        | 0.68%   |
| GeIL                | 1        | 0.68%   |
| ATP                 | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3        | 1.89%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 1.89%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 1.89%   |
| Unknown                                                        | 3        | 1.89%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 2        | 1.26%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 2        | 1.26%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s          | 2        | 1.26%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s          | 2        | 1.26%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 2        | 1.26%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s             | 2        | 1.26%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                     | 2        | 1.26%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2        | 1.26%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s         | 2        | 1.26%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                     | 2        | 1.26%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2        | 1.26%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s           | 2        | 1.26%   |
| Wilk RAM IR2400D464L15S/8G 8GB DIMM DDR4 2400MT/s              | 1        | 0.63%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s            | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 1        | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM                                    | 1        | 0.63%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                    | 1        | 0.63%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 0.63%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.63%   |
| Unknown RAM Module 16384MB DIMM DDR3 800MT/s                   | 1        | 0.63%   |
| Unknown RAM 8G2400MHz 8GB SODIMM DDR4 2400MT/s                 | 1        | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.63%   |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s   | 1        | 0.63%   |
| Toshiba RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s               | 1        | 0.63%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s          | 1        | 0.63%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.63%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1        | 0.63%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.63%   |
| SK hynix RAM HMT351R7BFR8A-H9 4GB DIMM DDR3 1333MT/s           | 1        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 72       | 55.81%  |
| DDR4    | 43       | 33.33%  |
| Unknown | 5        | 3.88%   |
| DDR2    | 4        | 3.1%    |
| SDRAM   | 2        | 1.55%   |
| LPDDR4  | 1        | 0.78%   |
| DDR5    | 1        | 0.78%   |
| DDR     | 1        | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 79       | 61.72%  |
| SODIMM | 48       | 37.5%   |
| RIMM   | 1        | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 53       | 38.13%  |
| 4096  | 48       | 34.53%  |
| 2048  | 23       | 16.55%  |
| 16384 | 8        | 5.76%   |
| 1024  | 4        | 2.88%   |
| 32768 | 2        | 1.44%   |
| 512   | 1        | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 47       | 34.56%  |
| 1333    | 22       | 16.18%  |
| 2400    | 17       | 12.5%   |
| 3200    | 11       | 8.09%   |
| 2667    | 7        | 5.15%   |
| 2133    | 6        | 4.41%   |
| 667     | 5        | 3.68%   |
| 800     | 4        | 2.94%   |
| 1867    | 3        | 2.21%   |
| 2666    | 2        | 1.47%   |
| 1066    | 2        | 1.47%   |
| Unknown | 2        | 1.47%   |
| 5200    | 1        | 0.74%   |
| 3600    | 1        | 0.74%   |
| 3333    | 1        | 0.74%   |
| 3000    | 1        | 0.74%   |
| 2933    | 1        | 0.74%   |
| 1866    | 1        | 0.74%   |
| 1334    | 1        | 0.74%   |
| 1067    | 1        | 0.74%   |

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
| 1     | 76       | 53.15%  |
| 0     | 57       | 39.86%  |
| 2     | 8        | 5.59%   |
| 4     | 1        | 0.7%    |
| 3     | 1        | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 71       | 73.96%  |
| Net/wireless             | 10       | 10.42%  |
| Firewire controller      | 4        | 4.17%   |
| Bluetooth                | 4        | 4.17%   |
| Net/ethernet             | 2        | 2.08%   |
| Graphics card            | 2        | 2.08%   |
| Sound                    | 1        | 1.04%   |
| Network                  | 1        | 1.04%   |
| Card reader              | 1        | 1.04%   |

