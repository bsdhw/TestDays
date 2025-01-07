BSD in Switzerland - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

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

Total: 107

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| TUXEDO    | InfinityBook Pro AMD Gen... | [b880be6d5f](https://bsd-hardware.info/?probe=b880be6d5f) | Dec 30, 2024 |
| Apple     | MacBookPro8,1               | [dc3d4a1f8d](https://bsd-hardware.info/?probe=dc3d4a1f8d) | Nov 24, 2024 |
| ASUSTek   | G75VW                       | [2ede0a1468](https://bsd-hardware.info/?probe=2ede0a1468) | Nov 06, 2024 |
| Lenovo    | ThinkPad T14 Gen 3 21CF0... | [7aa93cd8ba](https://bsd-hardware.info/?probe=7aa93cd8ba) | Nov 03, 2024 |
| Deciso    | DEC2700 - OPNsense Appli... | [1d5b951541](https://bsd-hardware.info/?probe=1d5b951541) | Oct 04, 2024 |
| Lenovo    | ThinkPad X1 Carbon 6th 2... | [bbc44a72cc](https://bsd-hardware.info/?probe=bbc44a72cc) | Oct 03, 2024 |
| Apple     | MacBookPro11,4              | [df7c99c150](https://bsd-hardware.info/?probe=df7c99c150) | Sep 25, 2024 |
| Deciso    | DEC2700 - OPNsense Appli... | [999fa3b31b](https://bsd-hardware.info/?probe=999fa3b31b) | Sep 25, 2024 |
| Apple     | MacBookPro11,4              | [5138a61509](https://bsd-hardware.info/?probe=5138a61509) | Sep 24, 2024 |
| Lenovo    | Yoga 900S-12ISK 80ML        | [8836aa08ec](https://bsd-hardware.info/?probe=8836aa08ec) | Sep 23, 2024 |
| Lenovo    | Yoga 900S-12ISK 80ML        | [41254dde12](https://bsd-hardware.info/?probe=41254dde12) | Sep 15, 2024 |
| Deciso    | NetBoard-A20                | [2cad072780](https://bsd-hardware.info/?probe=2cad072780) | Sep 12, 2024 |
| Lenovo    | Yoga 900S-12ISK 80ML        | [ce0404f7c9](https://bsd-hardware.info/?probe=ce0404f7c9) | Aug 31, 2024 |
| Lenovo    | ThinkPad X250 20CMCTO1WW    | [403fdba0ec](https://bsd-hardware.info/?probe=403fdba0ec) | Aug 25, 2024 |
| HP        | EliteBook 2570p             | [facf720e84](https://bsd-hardware.info/?probe=facf720e84) | Aug 24, 2024 |
| Lenovo    | Yoga 900S-12ISK 80ML        | [a0abac7ab7](https://bsd-hardware.info/?probe=a0abac7ab7) | Aug 21, 2024 |
| Deciso    | DEC2700 - OPNsense Appli... | [bcbdd06498](https://bsd-hardware.info/?probe=bcbdd06498) | Jul 21, 2024 |
| Deciso    | NetBoard-A20                | [190d52ebe5](https://bsd-hardware.info/?probe=190d52ebe5) | Jul 13, 2024 |
| HP        | EliteBook 8540p             | [cad0e50ea5](https://bsd-hardware.info/?probe=cad0e50ea5) | Jun 14, 2024 |
| Lenovo    | ThinkPad X250 20CMCTO1WW    | [bbc7b223f1](https://bsd-hardware.info/?probe=bbc7b223f1) | Jun 14, 2024 |
| Deciso    | NetBoard-A20                | [e30ed0bb29](https://bsd-hardware.info/?probe=e30ed0bb29) | Jun 03, 2024 |
| Deciso    | NetBoard-A20                | [ce91493709](https://bsd-hardware.info/?probe=ce91493709) | May 24, 2024 |
| Lenovo    | ThinkPad T15p Gen 1 20TN... | [5f31e6dc7e](https://bsd-hardware.info/?probe=5f31e6dc7e) | May 04, 2024 |
| HP        | EliteBook 2560p             | [bb6303ed5b](https://bsd-hardware.info/?probe=bb6303ed5b) | Apr 29, 2024 |
| Lenovo    | Yoga 900S-12ISK 80ML        | [47f57b0893](https://bsd-hardware.info/?probe=47f57b0893) | Feb 11, 2024 |
| Lenovo    | Yoga 900S-12ISK 80ML        | [5315513827](https://bsd-hardware.info/?probe=5315513827) | Feb 11, 2024 |
| Deciso    | NetBoard-A20                | [aaadb904c1](https://bsd-hardware.info/?probe=aaadb904c1) | Jan 10, 2024 |
| Deciso    | NetBoard-A20                | [cfcb03c18a](https://bsd-hardware.info/?probe=cfcb03c18a) | Jan 05, 2024 |
| Dell      | XPS 15 7590                 | [67a65520e6](https://bsd-hardware.info/?probe=67a65520e6) | Jan 03, 2024 |
| Lenovo    | ThinkPad T14 Gen 3 21CF0... | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| Lenovo    | ThinkPad T14 Gen 3 21CF0... | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Lenovo    | ThinkPad T14 Gen 3 21CF0... | [4b1250f831](https://bsd-hardware.info/?probe=4b1250f831) | Dec 26, 2023 |
| Apple     | MacBookPro10,2              | [e1867819f3](https://bsd-hardware.info/?probe=e1867819f3) | Dec 15, 2023 |
| Deciso    | NetBoard-A20                | [18364861b5](https://bsd-hardware.info/?probe=18364861b5) | Dec 03, 2023 |
| Lenovo    | Yoga 2 Pro 20266            | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo    | Yoga 2 Pro 20266            | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| Lenovo    | ThinkPad W530 24411M9       | [0272396725](https://bsd-hardware.info/?probe=0272396725) | Nov 19, 2023 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [918706e110](https://bsd-hardware.info/?probe=918706e110) | Nov 15, 2023 |
| ASUSTek   | K56CB                       | [8d4f2c439a](https://bsd-hardware.info/?probe=8d4f2c439a) | Nov 11, 2023 |
| ASUSTek   | K56CB                       | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Seco      | UDOO x86                    | [260f8194ed](https://bsd-hardware.info/?probe=260f8194ed) | Oct 22, 2023 |
| Deciso    | NetBoard-A20                | [7ed49c5f2f](https://bsd-hardware.info/?probe=7ed49c5f2f) | Oct 13, 2023 |
| Deciso    | NetBoard-A20                | [b9c11f29c9](https://bsd-hardware.info/?probe=b9c11f29c9) | Oct 10, 2023 |
| Deciso    | Netboard A20                | [c549fc9540](https://bsd-hardware.info/?probe=c549fc9540) | Oct 05, 2023 |
| Deciso    | NetBoard-A20                | [e9e295eae3](https://bsd-hardware.info/?probe=e9e295eae3) | Aug 24, 2023 |
| Deciso    | NetBoard-A20                | [c38eb6b9bd](https://bsd-hardware.info/?probe=c38eb6b9bd) | Aug 19, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Deciso    | Netboard A20                | [e82dfa5520](https://bsd-hardware.info/?probe=e82dfa5520) | Jul 14, 2023 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Apple     | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| Deciso    | Netboard A20                | [7c91a0f01b](https://bsd-hardware.info/?probe=7c91a0f01b) | Feb 14, 2023 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| Deciso    | NetBoard-A10                | [5b226a942e](https://bsd-hardware.info/?probe=5b226a942e) | Jan 27, 2023 |
| Unknown   | Unknown                     | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Unknown   | Unknown                     | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Lenovo    | ThinkPad T460p 20FW003PM... | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Unknown   | Unknown                     | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Acer      | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Apple     | MacBookPro5,1               | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Deciso    | Netboard A20                | [c70ba0979e](https://bsd-hardware.info/?probe=c70ba0979e) | Jul 07, 2022 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Deciso    | DEC2700 - OPNsense Appli... | [926afc7ac8](https://bsd-hardware.info/?probe=926afc7ac8) | Apr 07, 2022 |
| Deciso    | Netboard A20                | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| Deciso    | Netboard A20                | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| ASUSTek   | N50Vc                       | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| Shuttle   | DS77U                       | [1ca3d58dfc](https://bsd-hardware.info/?probe=1ca3d58dfc) | Feb 23, 2022 |
| Lenovo    | ThinkPad X250 20CMCTO1WW    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| ASUSTek   | N50Vc                       | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| Lenovo    | ThinkPad T470s W10DG 20J... | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |
| Casper    | EXCALIBUR G900              | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [8f9e9ddde5](https://bsd-hardware.info/?probe=8f9e9ddde5) | Dec 02, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [0fa0f325e9](https://bsd-hardware.info/?probe=0fa0f325e9) | Oct 28, 2021 |
| Lenovo    | ThinkPad T490s 20NYS3TU0... | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 8... | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Lenovo    | ThinkPad T420 4237A12       | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| ASUSTek   | UX31A                       | [67a6df2b68](https://bsd-hardware.info/?probe=67a6df2b68) | May 30, 2021 |
| Dell      | Latitude E6430              | [8d24817728](https://bsd-hardware.info/?probe=8d24817728) | May 19, 2021 |
| HP        | EliteBook 840 G3            | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [beacf76b6a](https://bsd-hardware.info/?probe=beacf76b6a) | Mar 26, 2021 |
| HUAWEI    | MACH-WX9                    | [f7e09652d9](https://bsd-hardware.info/?probe=f7e09652d9) | Mar 25, 2021 |
| HUAWEI    | MACH-WX9                    | [f9fdc75b45](https://bsd-hardware.info/?probe=f9fdc75b45) | Mar 25, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [acbc65fd42](https://bsd-hardware.info/?probe=acbc65fd42) | Mar 10, 2021 |
| Apple     | MacBookPro9,2               | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Lenovo    | ThinkPad T430 2349H2G       | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| Lenovo    | ThinkPad T490 20N2CTO1WW    | [9458fbeb87](https://bsd-hardware.info/?probe=9458fbeb87) | Jan 19, 2021 |
| Lenovo    | Yoga 720-13IKB 81C3         | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| HP        | EliteBook 840 G3            | [e44b010bc9](https://bsd-hardware.info/?probe=e44b010bc9) | Nov 11, 2020 |
| HP        | EliteBook 840 G3            | [2fb1bc911f](https://bsd-hardware.info/?probe=2fb1bc911f) | Nov 11, 2020 |
| Lenovo    | Yoga 720-13IKB 81C3         | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo    | Yoga 720-13IKB 81C3         | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| Acer      | Aspire E1-532               | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [2dd2bb5d60](https://bsd-hardware.info/?probe=2dd2bb5d60) | Aug 20, 2020 |
| Dell      | Precision M6600             | [b6c974b8bd](https://bsd-hardware.info/?probe=b6c974b8bd) | Aug 19, 2020 |
| Dell      | Precision M6600             | [da6f06315a](https://bsd-hardware.info/?probe=da6f06315a) | Aug 06, 2020 |
| HUAWEI    | MACH-WX9                    | [455ba9f0a8](https://bsd-hardware.info/?probe=455ba9f0a8) | Jul 20, 2020 |
| Panasonic | CF-19ADUAX1M                | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.5.0    | 3         | 3.53%   |
| FreeBSD 14.1         | 3         | 3.53%   |
| FreeBSD 14.0         | 3         | 3.53%   |
| FreeBSD 13.0         | 3         | 3.53%   |
| OPNsense 23.7.1      | 2         | 2.35%   |
| OPNsense 23.4.2      | 2         | 2.35%   |
| OPNsense 23.1        | 2         | 2.35%   |
| NomadBSD 20240711    | 2         | 2.35%   |
| helloSystem 0.8.2    | 2         | 2.35%   |
| helloSystem 0.8.1    | 2         | 2.35%   |
| GhostBSD 24.07.1     | 2         | 2.35%   |
| FreeBSD 15.0-CURRENT | 2         | 2.35%   |
| FreeBSD 14.1-p3      | 2         | 2.35%   |
| FreeBSD 13.0-STABLE  | 2         | 2.35%   |
| FreeBSD 13.0-p7      | 2         | 2.35%   |
| FreeBSD 12.1-p8      | 2         | 2.35%   |
| OPNsense 24.7.5      | 1         | 1.18%   |
| OPNsense 24.4.2      | 1         | 1.18%   |
| OPNsense 24.4.1      | 1         | 1.18%   |
| OPNsense 24.4        | 1         | 1.18%   |
| OPNsense 24.1.6      | 1         | 1.18%   |
| OPNsense 24.1.10     | 1         | 1.18%   |
| OPNsense 23.7.6      | 1         | 1.18%   |
| OPNsense 23.7.5      | 1         | 1.18%   |
| OPNsense 23.7.12     | 1         | 1.18%   |
| OPNsense 23.4.1      | 1         | 1.18%   |
| OPNsense 23.10.1     | 1         | 1.18%   |
| OPNsense 23.10       | 1         | 1.18%   |
| OPNsense 22.7.4      | 1         | 1.18%   |
| OPNsense 22.7.11     | 1         | 1.18%   |
| OPNsense 22.10       | 1         | 1.18%   |
| OPNsense 22.1.9      | 1         | 1.18%   |
| OPNsense 22.1.4      | 1         | 1.18%   |
| OPNsense 22.1.1      | 1         | 1.18%   |
| OPNsense 21.1.5      | 1         | 1.18%   |
| OpenBSD 7.0          | 1         | 1.18%   |
| OpenBSD 6.8          | 1         | 1.18%   |
| OpenBSD 6.7          | 1         | 1.18%   |
| NomadBSD 20240126    | 1         | 1.18%   |
| helloSystem 0.9.0    | 1         | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 28        | 41.18%  |
| OPNsense    | 19        | 27.94%  |
| helloSystem | 8         | 11.76%  |
| GhostBSD    | 7         | 10.29%  |
| OpenBSD     | 3         | 4.41%   |
| NomadBSD    | 3         | 4.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 65        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 26        | 38.24%  |
| helloDesktop | 8         | 11.76%  |
| XFCE         | 7         | 10.29%  |
| MATE         | 7         | 10.29%  |
| KDE5         | 5         | 7.35%   |
| TWM          | 4         | 5.88%   |
| i3           | 4         | 5.88%   |
| GNOME        | 2         | 2.94%   |
| fvwm         | 2         | 2.94%   |
| wlroots      | 1         | 1.47%   |
| Openbox      | 1         | 1.47%   |
| LXDE         | 1         | 1.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 38        | 55.88%  |
| Console | 26        | 38.24%  |
| Wayland | 4         | 5.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 36        | 52.17%  |
| SLiM    | 14        | 20.29%  |
| LightDM | 10        | 14.49%  |
| SDDM    | 5         | 7.25%   |
| Ly      | 2         | 2.9%    |
| GDM     | 2         | 2.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 40.3%   |
| C       | 17        | 25.37%  |
| en_US   | 12        | 17.91%  |
| de_CH   | 4         | 5.97%   |
| ru_RU   | 3         | 4.48%   |
| fr_FR   | 2         | 2.99%   |
| fi_FI   | 1         | 1.49%   |
| de_DE   | 1         | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 89.23%  |
| BIOS | 7         | 10.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 45        | 66.18%  |
| Ufs    | 16        | 23.53%  |
| Cd9660 | 4         | 5.88%   |
| Ffs    | 3         | 4.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 62        | 95.38%  |
| MBR     | 2         | 3.08%   |
| Unknown | 1         | 1.54%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 24        | 36.92%  |
| Deciso           | 13        | 20%     |
| ASUSTek Computer | 5         | 7.69%   |
| Apple            | 5         | 7.69%   |
| Hewlett-Packard  | 4         | 6.15%   |
| Dell             | 3         | 4.62%   |
| HUAWEI           | 2         | 3.08%   |
| Acer             | 2         | 3.08%   |
| Unknown          | 2         | 3.08%   |
| TUXEDO           | 1         | 1.54%   |
| Shuttle          | 1         | 1.54%   |
| Seco             | 1         | 1.54%   |
| Panasonic        | 1         | 1.54%   |
| Casper           | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Deciso NetBoard-A20                        | 6         | 9.23%   |
| Deciso DEC2700 - OPNsense Appliance        | 4         | 6.15%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS         | 3         | 4.62%   |
| Lenovo Yoga 900S-12ISK 80ML                | 3         | 4.62%   |
| HUAWEI MACH-WX9                            | 2         | 3.08%   |
| Deciso Netboard A20                        | 2         | 3.08%   |
| Unknown                                    | 2         | 3.08%   |
| TUXEDO InfinityBook Pro AMD Gen9           | 1         | 1.54%   |
| Shuttle DS77U                              | 1         | 1.54%   |
| Seco UDOO x86                              | 1         | 1.54%   |
| Panasonic CF-19ADUAX1M                     | 1         | 1.54%   |
| Lenovo Yoga 720-13IKB 81C3                 | 1         | 1.54%   |
| Lenovo Yoga 2 Pro 20266                    | 1         | 1.54%   |
| Lenovo ThinkPad X250 20CMCTO1WW            | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JBM   | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS43F00   | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS09900   | 1         | 1.54%   |
| Lenovo ThinkPad W530 24411M9               | 1         | 1.54%   |
| Lenovo ThinkPad T490s 20NYS3TU00           | 1         | 1.54%   |
| Lenovo ThinkPad T490 20N2CTO1WW            | 1         | 1.54%   |
| Lenovo ThinkPad T470s W10DG 20JTS0A900     | 1         | 1.54%   |
| Lenovo ThinkPad T460p 20FW003PMZ           | 1         | 1.54%   |
| Lenovo ThinkPad T430 2349H2G               | 1         | 1.54%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 1.54%   |
| Lenovo ThinkPad T15p Gen 1 20TN0018MZ      | 1         | 1.54%   |
| Lenovo ThinkPad T14 Gen 3 21CF002UMZ       | 1         | 1.54%   |
| Lenovo IdeaPad Y700-15ISK 80NV             | 1         | 1.54%   |
| HP EliteBook 8540p                         | 1         | 1.54%   |
| HP EliteBook 840 G3                        | 1         | 1.54%   |
| HP EliteBook 2570p                         | 1         | 1.54%   |
| HP EliteBook 2560p                         | 1         | 1.54%   |
| Dell XPS 15 7590                           | 1         | 1.54%   |
| Dell Precision M6600                       | 1         | 1.54%   |
| Dell Latitude E6430                        | 1         | 1.54%   |
| Deciso NetBoard-A10                        | 1         | 1.54%   |
| Casper EXCALIBUR G900                      | 1         | 1.54%   |
| ASUS UX31A                                 | 1         | 1.54%   |
| ASUS N50Vc                                 | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 15        | 23.08%  |
| Lenovo Yoga            | 8         | 12.31%  |
| Deciso NetBoard-A20    | 6         | 9.23%   |
| HP EliteBook           | 4         | 6.15%   |
| Deciso DEC2700         | 4         | 6.15%   |
| HUAWEI MACH-WX9        | 2         | 3.08%   |
| Deciso Netboard        | 2         | 3.08%   |
| Acer Aspire            | 2         | 3.08%   |
| Unknown                | 2         | 3.08%   |
| TUXEDO InfinityBook    | 1         | 1.54%   |
| Shuttle DS77U          | 1         | 1.54%   |
| Seco UDOO              | 1         | 1.54%   |
| Panasonic CF-19ADUAX1M | 1         | 1.54%   |
| Lenovo IdeaPad         | 1         | 1.54%   |
| Dell XPS               | 1         | 1.54%   |
| Dell Precision         | 1         | 1.54%   |
| Dell Latitude          | 1         | 1.54%   |
| Deciso NetBoard-A10    | 1         | 1.54%   |
| Casper EXCALIBUR       | 1         | 1.54%   |
| ASUS UX31A             | 1         | 1.54%   |
| ASUS N50Vc             | 1         | 1.54%   |
| ASUS K56CB             | 1         | 1.54%   |
| ASUS G75VW             | 1         | 1.54%   |
| ASUS ASUS              | 1         | 1.54%   |
| Apple MacBookPro9      | 1         | 1.54%   |
| Apple MacBookPro8      | 1         | 1.54%   |
| Apple MacBookPro5      | 1         | 1.54%   |
| Apple MacBookPro11     | 1         | 1.54%   |
| Apple MacBookPro10     | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 26.15%  |
| 2016 | 7         | 10.77%  |
| 2015 | 7         | 10.77%  |
| 2013 | 6         | 9.23%   |
| 2019 | 5         | 7.69%   |
| 2018 | 4         | 6.15%   |
| 2017 | 4         | 6.15%   |
| 2022 | 3         | 4.62%   |
| 2012 | 3         | 4.62%   |
| 2011 | 3         | 4.62%   |
| 2020 | 2         | 3.08%   |
| 2024 | 1         | 1.54%   |
| 2023 | 1         | 1.54%   |
| 2014 | 1         | 1.54%   |
| 2009 | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 65        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 23        | 35.38%  |
| 8.01-16.0  | 22        | 33.85%  |
| 4.01-8.0   | 11        | 16.92%  |
| 32.01-64.0 | 9         | 13.85%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 30        | 46.15%  |
| 0.51-1.0 | 21        | 32.31%  |
| 1.01-2.0 | 11        | 16.92%  |
| 2.01-3.0 | 3         | 4.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 71.64%  |
| 0      | 10        | 14.93%  |
| 2      | 8         | 11.94%  |
| 4      | 1         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 83.08%  |
| Yes       | 11        | 16.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 81.82%  |
| No        | 12        | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 76.92%  |
| No        | 15        | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 66.67%  |
| No        | 22        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Switzerland | 65        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Zurich                   | 30        | 41.1%   |
| Basel                    | 3         | 4.11%   |
| Therwil                  | 2         | 2.74%   |
| Munchenstein             | 2         | 2.74%   |
| Glattbrugg               | 2         | 2.74%   |
| Corcelles-pres-Payerne   | 2         | 2.74%   |
| Steckborn                | 1         | 1.37%   |
| St. Moritz               | 1         | 1.37%   |
| Siblingen                | 1         | 1.37%   |
| Seuzach Dorf             | 1         | 1.37%   |
| Riehen                   | 1         | 1.37%   |
| Onex                     | 1         | 1.37%   |
| Moosseedorf              | 1         | 1.37%   |
| Lutry                    | 1         | 1.37%   |
| Loehningen               | 1         | 1.37%   |
| Lenzburg                 | 1         | 1.37%   |
| Le Landeron              | 1         | 1.37%   |
| Lausanne                 | 1         | 1.37%   |
| Langnau am Albis         | 1         | 1.37%   |
| Kiesen                   | 1         | 1.37%   |
| Huttwil                  | 1         | 1.37%   |
| Horgen                   | 1         | 1.37%   |
| Hittnau / Hittnau (Dorf) | 1         | 1.37%   |
| Hildisrieden             | 1         | 1.37%   |
| Grenchen                 | 1         | 1.37%   |
| Geneva                   | 1         | 1.37%   |
| Fribourg                 | 1         | 1.37%   |
| Ebikon                   | 1         | 1.37%   |
| Düdingen                | 1         | 1.37%   |
| Dinhard                  | 1         | 1.37%   |
| Cologny                  | 1         | 1.37%   |
| Burgdorf                 | 1         | 1.37%   |
| Broc                     | 1         | 1.37%   |
| Bern                     | 1         | 1.37%   |
| Belmont-sur-Lausanne     | 1         | 1.37%   |
| Arbon                    | 1         | 1.37%   |
| Aesch                    | 1         | 1.37%   |
| Adliswil                 | 1         | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 21     | 26.87%  |
| Transcend           | 13        | 20     | 19.4%   |
| Intel               | 6         | 8      | 8.96%   |
| WDC                 | 5         | 5      | 7.46%   |
| SanDisk             | 4         | 4      | 5.97%   |
| Toshiba             | 3         | 3      | 4.48%   |
| SK hynix            | 3         | 5      | 4.48%   |
| Kingston            | 3         | 3      | 4.48%   |
| Seagate             | 2         | 2      | 2.99%   |
| NVMe                | 2         | 2      | 2.99%   |
| Crucial             | 2         | 2      | 2.99%   |
| Apple               | 2         | 2      | 2.99%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| LITEON              | 1         | 6      | 1.49%   |
| Intenso             | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB         | 4         | 5.8%    |
| Transcend TS256GMTE710T 256GB          | 4         | 5.8%    |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 3         | 4.35%   |
| Transcend TS512GMTS952T2 512GB         | 2         | 2.9%    |
| Transcend TS128GMTE110S 128GB          | 2         | 2.9%    |
| Samsung SSD 850 PRO 256GB              | 2         | 2.9%    |
| Samsung MZVLB512HAJQ-00000 512GB       | 2         | 2.9%    |
| WDC WDS240G2G0A-00JH30 240GB           | 1         | 1.45%   |
| WDC WD3200BEKT-00V5T0 320GB            | 1         | 1.45%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 1.45%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB     | 1         | 1.45%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB   | 1         | 1.45%   |
| Transcend TS256GMTE652T2 256GB         | 1         | 1.45%   |
| Toshiba TR200 240GB                    | 1         | 1.45%   |
| Toshiba THNSFJ256GCSU 256GB            | 1         | 1.45%   |
| Toshiba MK3263GSXN 320GB               | 1         | 1.45%   |
| Seagate ST2000LM007-1R8174 2TB         | 1         | 1.45%   |
| Seagate SSD 500GB                      | 1         | 1.45%   |
| SanDisk SSD U100 24GB                  | 1         | 1.45%   |
| SanDisk SSD PLUS 1000GB                | 1         | 1.45%   |
| SanDisk SD8SN8U128G1001 128GB          | 1         | 1.45%   |
| SanDisk SD5SE2256G1002E 256GB          | 1         | 1.45%   |
| Samsung SSD SM841 2.5-inch 7mm 128GB   | 1         | 1.45%   |
| Samsung SSD 870 EVO 1TB                | 1         | 1.45%   |
| Samsung SSD 860 EVO mSATA 500GB        | 1         | 1.45%   |
| Samsung SSD 860 EVO 250GB              | 1         | 1.45%   |
| Samsung SSD 860 EVO 1TB                | 1         | 1.45%   |
| Samsung SSD 850 EVO 500GB              | 1         | 1.45%   |
| Samsung SSD 850 EVO 250GB              | 1         | 1.45%   |
| Samsung SSD 850 EVO 1TB                | 1         | 1.45%   |
| Samsung SSD 840 PRO Series 256GB       | 1         | 1.45%   |
| Samsung Portable SSD T7 2TB            | 1         | 1.45%   |
| Samsung MZVLW1T0HMLH-000L7 1TB         | 1         | 1.45%   |
| Samsung MZVLB1T0HBLR-000L7 1TB         | 1         | 1.45%   |
| Samsung MZVL21T0HCLR-00BL7 1TB         | 1         | 1.45%   |
| Samsung MZMTD128HAFV-000L1 128GB       | 1         | 1.45%   |
| Samsung MZHPV512HDGL-000L1 512GB       | 1         | 1.45%   |
| Samsung MZ7TD512HAGM-000L1 512GB       | 1         | 1.45%   |
| OCZ AGILITY3 240GB                     | 1         | 1.45%   |
| NVMe SanDisk A400 SD9 256GB            | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| NVMe    | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |
| Seagate | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 15     | 31.71%  |
| Transcend           | 6         | 13     | 14.63%  |
| SanDisk             | 4         | 4      | 9.76%   |
| Intel               | 4         | 6      | 9.76%   |
| Kingston            | 3         | 3      | 7.32%   |
| Toshiba             | 2         | 2      | 4.88%   |
| Apple               | 2         | 2      | 4.88%   |
| WDC                 | 1         | 1      | 2.44%   |
| Seagate             | 1         | 1      | 2.44%   |
| OCZ                 | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| LITEON              | 1         | 6      | 2.44%   |
| Intenso             | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 35        | 57     | 57.38%  |
| NVMe | 20        | 23     | 32.79%  |
| HDD  | 6         | 6      | 9.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 63     | 65.52%  |
| NVMe | 20        | 23     | 34.48%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 45     | 70.73%  |
| 0.51-1.0   | 11        | 17     | 26.83%  |
| 1.01-2.0   | 1         | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 31        | 44.93%  |
| 251-500    | 17        | 24.64%  |
| 1-20       | 9         | 13.04%  |
| 501-1000   | 9         | 13.04%  |
| 51-100     | 2         | 2.9%    |
| 21-50      | 1         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 58        | 85.29%  |
| 21-50   | 4         | 5.88%   |
| 101-250 | 3         | 4.41%   |
| 51-100  | 3         | 4.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB        | 1         | 1      | 12.5%   |
| OCZ AGILITY3 240GB                         | 1         | 1      | 12.5%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB | 1         | 1      | 12.5%   |
| Kingston SV300S37A60G 64GB                 | 1         | 1      | 12.5%   |
| Intenso SSD Sata III 248GB                 | 1         | 1      | 12.5%   |
| Intel SSDSCKKF256G8H 256GB                 | 1         | 2      | 12.5%   |
| Intel SSDSC2BW480A4 480GB                  | 1         | 2      | 12.5%   |
| Intel SSDSA2M120G2GC 120GB                 | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Intel               | 3         | 5      | 37.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| OCZ                 | 1         | 1      | 12.5%   |
| Micron Technology   | 1         | 1      | 12.5%   |
| Kingston            | 1         | 1      | 12.5%   |
| Intenso             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 10     | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 51        | 74     | 83.61%  |
| Malfunc  | 8         | 10     | 13.11%  |
| Detected | 2         | 2      | 3.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 32        | 45.07%  |
| Samsung Electronics       | 11        | 15.49%  |
| Transcend                 | 7         | 9.86%   |
| AMD                       | 6         | 8.45%   |
| SK hynix                  | 4         | 5.63%   |
| SanDisk                   | 4         | 5.63%   |
| Micron/Crucial Technology | 3         | 4.23%   |
| Toshiba                   | 1         | 1.41%   |
| Silicon Motion            | 1         | 1.41%   |
| Nvidia                    | 1         | 1.41%   |
| KIOXIA                    | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 11.11%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 6.94%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                        | 4         | 5.56%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 4.17%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 2         | 2.78%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 2         | 2.78%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 2.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 2.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.78%   |
| Transcend NVMe PCIe SSD 110Q (DRAM-less)                                         | 1         | 1.39%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 1.39%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 1.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.39%   |
| SanDisk WD Black NVMe SSD                                                        | 1         | 1.39%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.39%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 1         | 1.39%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.39%   |
| Micron/Crucial T500 NVMe PCIe SSD                                                | 1         | 1.39%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                         | 1         | 1.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.39%   |
| KIOXIA NVMe SSD                                                                  | 1         | 1.39%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 1         | 1.39%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 1         | 1.39%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 1         | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                            | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 37        | 53.62%  |
| NVMe | 29        | 42.03%  |
| RAID | 2         | 2.9%    |
| IDE  | 1         | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 70.77%  |
| AMD    | 19        | 29.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 5         | 7.69%   |
| AMD EPYC 3201 8-Core Processor          | 5         | 7.69%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz        | 3         | 4.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 4.62%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 3         | 4.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 4.62%   |
| AMD EPYC 3101 4-Core Processor          | 3         | 4.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 3.08%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 2         | 3.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 3.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.54%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.54%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.54%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.54%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.54%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.54%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz      | 1         | 1.54%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1.54%   |
| Intel Core i7-3840QM CPU @ 2.80GHz      | 1         | 1.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.54%   |
| Intel Core i7-2720QM CPU @ 2.20GH       | 1         | 1.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.54%   |
| Intel Core i7 CPU M 620 @ 2.67GHz       | 1         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.54%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.54%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 1         | 1.54%   |
| Intel Core i5-2435M CPU @ 2.40GHz       | 1         | 1.54%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 1         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.54%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.54%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz    | 1         | 1.54%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 1.54%   |
| Intel Celeron CPU N3160 @ 1.60GHz       | 1         | 1.54%   |
| Intel Celeron 2955U @ 1.40GHz           | 1         | 1.54%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 1         | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 21        | 32.31%  |
| Intel Core i5      | 15        | 23.08%  |
| AMD EPYC           | 8         | 12.31%  |
| AMD Ryzen Embedded | 5         | 7.69%   |
| AMD Ryzen 7        | 5         | 7.69%   |
| Intel Core m7      | 3         | 4.62%   |
| Other              | 2         | 3.08%   |
| Intel Core 2 Duo   | 2         | 3.08%   |
| Intel Celeron      | 2         | 3.08%   |
| Intel Core i3      | 1         | 1.54%   |
| AMD Ryzen 7 PRO    | 1         | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 26        | 39.39%  |
| 4       | 22        | 33.33%  |
| 8       | 10        | 15.15%  |
| 16      | 5         | 7.58%   |
| 6       | 2         | 3.03%   |
| Unknown | 1         | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 98.46%  |
| 2      | 1         | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 44        | 66.67%  |
| 1       | 21        | 31.82%  |
| Unknown | 1         | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Zen         | 13        | 20%     |
| KabyLake    | 10        | 15.38%  |
| IvyBridge   | 10        | 15.38%  |
| Skylake     | 8         | 12.31%  |
| SandyBridge | 5         | 7.69%   |
| Unknown     | 4         | 6.15%   |
| Zen 3       | 3         | 4.62%   |
| Haswell     | 3         | 4.62%   |
| Broadwell   | 3         | 4.62%   |
| Penryn      | 2         | 3.08%   |
| Westmere    | 1         | 1.54%   |
| TigerLake   | 1         | 1.54%   |
| Silvermont  | 1         | 1.54%   |
| CometLake   | 1         | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 68.33%  |
| Nvidia | 12        | 20%     |
| AMD    | 7         | 11.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 14.75%  |
| Intel UHD Graphics 620                                                                   | 4         | 6.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.92%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.92%   |
| Intel HD Graphics 515                                                                    | 3         | 4.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 4.92%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 3.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 3.28%   |
| Intel HD Graphics 530                                                                    | 2         | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.28%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 3.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.64%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.64%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.64%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.64%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 1.64%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.64%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 1.64%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.64%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.64%   |
| Intel HD Graphics 620                                                                    | 1         | 1.64%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.64%   |
| AMD Phoenix3                                                                             | 1         | 1.64%   |
| AMD Blackcomb [Radeon HD 6970M/6990M]                                                    | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 52.31%  |
| Other          | 13        | 20%     |
| Intel + Nvidia | 7         | 10.77%  |
| 1 x AMD        | 6         | 9.23%   |
| 1 x Nvidia     | 3         | 4.62%   |
| 2 x Nvidia     | 1         | 1.54%   |
| AMD + Nvidia   | 1         | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 70.77%  |
| Unknown     | 15        | 23.08%  |
| Proprietary | 4         | 6.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 88.24%  |
| 1.01-2.0   | 4         | 5.88%   |
| 0.51-1.0   | 2         | 2.94%   |
| 0.01-0.5   | 2         | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 23.08%  |
| LG Display              | 5         | 12.82%  |
| Sharp                   | 4         | 10.26%  |
| Apple                   | 4         | 10.26%  |
| Samsung Electronics     | 3         | 7.69%   |
| CSO                     | 3         | 7.69%   |
| Chimei Innolux          | 3         | 7.69%   |
| JDI                     | 2         | 5.13%   |
| Chi Mei Optoelectronics | 2         | 5.13%   |
| BOE                     | 2         | 5.13%   |
| Dell                    | 1         | 2.56%   |
| CSW                     | 1         | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1457 2560x1440 280x160mm 12.7-inch                  | 3         | 7.69%   |
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                    | 2         | 5.13%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                    | 2         | 5.13%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 2         | 5.13%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch                  | 1         | 2.56%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch    | 1         | 2.56%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch          | 1         | 2.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 2.56%   |
| LG Display LCD Monitor LGD06ED 1920x1200 300x190mm 14.0-inch             | 1         | 2.56%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 2.56%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 2.56%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch              | 1         | 2.56%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                        | 1         | 2.56%   |
| CSW MNE007ZA3-2 CSW1431 2880x1800 300x190mm 14.0-inch                    | 1         | 2.56%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                    | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 2.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1561 1280x800 330x210mm 15.4-inch | 1         | 2.56%   |
| Chi Mei Optoelectronics LCD Monitor 1920x1080                            | 1         | 2.56%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                    | 1         | 2.56%   |
| BOE LCD Monitor BOE06DF 1920x1080 310x170mm 13.9-inch                    | 1         | 2.56%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 300x190mm 14.0-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO206C 1366x768 280x160mm 12.7-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO159D 1920x1080 380x210mm 17.1-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 340x190mm 15.3-inch           | 1         | 2.56%   |
| Apple LCD Monitor APP9CCB 1280x800 290x180mm 13.4-inch                   | 1         | 2.56%   |
| Apple LCD Monitor APP9C84 1440x900 330x210mm 15.4-inch                   | 1         | 2.56%   |
| Apple Color LCD APPA02E 2880x1800 330x210mm 15.4-inch                    | 1         | 2.56%   |
| Apple Color LCD APPA014 2560x1600 290x180mm 13.4-inch                    | 1         | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 12        | 30.77%  |
| 2880x1800         | 4         | 10.26%  |
| 2560x1440 (QHD)   | 4         | 10.26%  |
| 1366x768 (WXGA)   | 4         | 10.26%  |
| 3840x2160 (4K)    | 3         | 7.69%   |
| 3000x2000         | 2         | 5.13%   |
| 1920x1200 (WUXGA) | 2         | 5.13%   |
| 1600x900 (HD+)    | 2         | 5.13%   |
| 1280x800 (WXGA)   | 2         | 5.13%   |
| 3440x1440         | 1         | 2.56%   |
| 3200x1800 (QHD+)  | 1         | 2.56%   |
| 2560x1600         | 1         | 2.56%   |
| 1440x900 (WXGA+)  | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 13        | 33.33%  |
| 15      | 10        | 25.64%  |
| 12      | 6         | 15.38%  |
| 14      | 5         | 12.82%  |
| 34      | 1         | 2.56%   |
| 27      | 1         | 2.56%   |
| 23      | 1         | 2.56%   |
| 17      | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 46.15%  |
| 201-300     | 16        | 41.03%  |
| 501-600     | 2         | 5.13%   |
| 701-800     | 1         | 2.56%   |
| 351-400     | 1         | 2.56%   |
| Unknown     | 1         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 24        | 63.16%  |
| 16/10   | 10        | 26.32%  |
| 4/3     | 2         | 5.26%   |
| 21/9    | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 43.59%  |
| 61-70          | 6         | 15.38%  |
| 101-110        | 6         | 15.38%  |
| 91-100         | 4         | 10.26%  |
| 71-80          | 1         | 2.56%   |
| 351-500        | 1         | 2.56%   |
| 301-350        | 1         | 2.56%   |
| 201-250        | 1         | 2.56%   |
| 121-130        | 1         | 2.56%   |
| Unknown        | 1         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 161-240       | 11        | 28.21%  |
| 121-160       | 10        | 25.64%  |
| More than 240 | 8         | 20.51%  |
| 101-120       | 6         | 15.38%  |
| 51-100        | 3         | 7.69%   |
| Unknown       | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 50%     |
| 0     | 32        | 45.71%  |
| 2     | 3         | 4.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 50        | 47.17%  |
| AMD                                    | 13        | 12.26%  |
| Realtek Semiconductor                  | 12        | 11.32%  |
| Broadcom                               | 10        | 9.43%   |
| Qualcomm Atheros                       | 4         | 3.77%   |
| TP-Link                                | 2         | 1.89%   |
| Sierra Wireless                        | 2         | 1.89%   |
| Qualcomm                               | 2         | 1.89%   |
| MediaTek                               | 2         | 1.89%   |
| Hewlett-Packard                        | 2         | 1.89%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.94%   |
| Samsung Electronics                    | 1         | 0.94%   |
| Ralink Technology                      | 1         | 0.94%   |
| Qualcomm Technologies                  | 1         | 0.94%   |
| Nvidia                                 | 1         | 0.94%   |
| Motorola PCS                           | 1         | 0.94%   |
| Ericsson Business Mobile Networks      | 1         | 0.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AMD XGMAC 10GbE Controller                                             | 13        | 9.92%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 6.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 6.11%   |
| Intel I210 Gigabit Network Connection                                  | 7         | 5.34%   |
| Intel Ethernet Controller I225-V                                       | 5         | 3.82%   |
| Intel Wireless 8265 / 8275                                             | 4         | 3.05%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 3.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 3.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 2.29%   |
| Intel Wireless 8260                                                    | 3         | 2.29%   |
| Intel Wireless 7265                                                    | 3         | 2.29%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 2.29%   |
| Sierra Wireless EM7455                                                 | 2         | 1.53%   |
| Qualcomm FP3                                                           | 2         | 1.53%   |
| Intel Wireless 7260                                                    | 2         | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.53%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 1.53%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.53%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 1.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.53%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                     | 2         | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.76%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.76%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.76%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 1         | 0.76%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.76%   |
| Motorola PCS USB RNDIS Device                                          | 1         | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 55.17%  |
| Broadcom              | 9         | 15.52%  |
| Realtek Semiconductor | 6         | 10.34%  |
| Qualcomm Atheros      | 3         | 5.17%   |
| TP-Link               | 2         | 3.45%   |
| Sierra Wireless       | 2         | 3.45%   |
| MediaTek              | 2         | 3.45%   |
| Ralink Technology     | 1         | 1.72%   |
| Qualcomm Technologies | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 4         | 6.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 6.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 5.17%   |
| Intel Wireless 8260                                            | 3         | 5.17%   |
| Intel Wireless 7265                                            | 3         | 5.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 5.17%   |
| Sierra Wireless EM7455                                         | 2         | 3.45%   |
| Intel Wireless 7260                                            | 2         | 3.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 3.45%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 3.45%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.45%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.72%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.72%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 1.72%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.72%   |
| MediaTek 802.11 n WLAN                                         | 1         | 1.72%   |
| Intel WiFi Link 5100                                           | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.72%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.72%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 1.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 35        | 52.24%  |
| AMD                                    | 13        | 19.4%   |
| Realtek Semiconductor                  | 8         | 11.94%  |
| Broadcom                               | 4         | 5.97%   |
| Qualcomm                               | 2         | 2.99%   |
| Suzhou Motorcomm Electronic Technology | 1         | 1.49%   |
| Samsung Electronics                    | 1         | 1.49%   |
| Qualcomm Atheros                       | 1         | 1.49%   |
| Nvidia                                 | 1         | 1.49%   |
| Motorola PCS                           | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AMD XGMAC 10GbE Controller                                             | 13        | 18.84%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 11.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 11.59%  |
| Intel I210 Gigabit Network Connection                                  | 7         | 10.14%  |
| Intel Ethernet Controller I225-V                                       | 5         | 7.25%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 5.8%    |
| Qualcomm FP3                                                           | 2         | 2.9%    |
| Intel I211 Gigabit Network Connection                                  | 2         | 2.9%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 2.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.9%    |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.45%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.45%   |
| Motorola PCS USB RNDIS Device                                          | 1         | 1.45%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.45%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.45%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.45%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.45%   |
| Intel Ethernet Connection (11) I219-V                                  | 1         | 1.45%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.45%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.45%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 54        | 50%     |
| WiFi     | 50        | 46.3%   |
| Modem    | 4         | 3.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 57.75%  |
| WiFi     | 30        | 42.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 31        | 47.69%  |
| 1     | 16        | 24.62%  |
| 6     | 9         | 13.85%  |
| 5     | 5         | 7.69%   |
| 3     | 3         | 4.62%   |
| 4     | 1         | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 74.63%  |
| Yes  | 17        | 25.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 22        | 50%     |
| Apple                   | 5         | 11.36%  |
| Realtek Semiconductor   | 3         | 6.82%   |
| Broadcom                | 3         | 6.82%   |
| IMC Networks            | 2         | 4.55%   |
| ASUSTek Computer        | 2         | 4.55%   |
| USI                     | 1         | 2.27%   |
| Lite-On Technology      | 1         | 2.27%   |
| Hewlett-Packard         | 1         | 2.27%   |
| Foxconn / Hon Hai       | 1         | 2.27%   |
| Dell                    | 1         | 2.27%   |
| Cambridge Silicon Radio | 1         | 2.27%   |
| Alps Electric           | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 12        | 27.27%  |
| Intel AX201 Bluetooth                                       | 4         | 9.09%   |
| Apple Bluetooth Host Controller                             | 4         | 9.09%   |
| Realtek Bluetooth Adapter                                   | 3         | 6.82%   |
| Intel AX210 Bluetooth                                       | 2         | 4.55%   |
| Intel AX200 Bluetooth                                       | 2         | 4.55%   |
| Broadcom Bluetooth 4.1 USB                                  | 2         | 4.55%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 2.27%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.27%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 2.27%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 2.27%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 2.27%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.27%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 2.27%   |
| ASUS USB-BT500                                              | 1         | 2.27%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 2.27%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 2.27%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 45        | 60.81%  |
| AMD                 | 17        | 22.97%  |
| Nvidia              | 5         | 6.76%   |
| Lenovo              | 3         | 4.05%   |
| PS Audio            | 1         | 1.35%   |
| GN Netcom           | 1         | 1.35%   |
| C-Media Electronics | 1         | 1.35%   |
| ASUSTek Computer    | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 12.94%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 10        | 11.76%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 10.59%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 7.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 7.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.53%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.53%   |
| Lenovo Lenovo USB-C Mini Dock                                                                     | 2         | 2.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.35%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 2.35%   |
| PS Audio PS Audio USB Audio 2.0                                                                   | 1         | 1.18%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.18%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.18%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.18%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Gen 2 USB Audio                                                | 1         | 1.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.18%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.18%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.18%   |
| GN Netcom Jabra UC VOICE 550 MS mono USB                                                          | 1         | 1.18%   |
| C-Media Electronics Audio Adapter                                                                 | 1         | 1.18%   |
| ASUSTek Computer C-Media CM6549 Extension                                                         | 1         | 1.18%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 1         | 1.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 21.74%  |
| SK hynix            | 14        | 20.29%  |
| Transcend           | 12        | 17.39%  |
| Micron Technology   | 10        | 14.49%  |
| Kingston            | 8         | 11.59%  |
| Unknown             | 3         | 4.35%   |
| Unknown (F301)      | 1         | 1.45%   |
| Unknown             | 1         | 1.45%   |
| Elpida              | 1         | 1.45%   |
| Crucial             | 1         | 1.45%   |
| Corsair             | 1         | 1.45%   |
| ASint Technology    | 1         | 1.45%   |
| A-DATA Technology   | 1         | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 8         | 10.96%  |
| SK hynix RAM Module 4GB SODIMM LPDDR3 1600MT/s                 | 3         | 4.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 3         | 4.11%   |
| Unknown                                                        | 3         | 4.11%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s          | 2         | 2.74%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s            | 2         | 2.74%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 2.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1         | 1.37%   |
| Unknown (F301) RAM Z18L-3AEN00 8GB SODIMM DDR3 1867MT/s        | 1         | 1.37%   |
| Transcend RAM TS2GLH64V2B 16GB SODIMM DDR4 1600MT/s            | 1         | 1.37%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.37%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s           | 1         | 1.37%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.37%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.37%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1         | 1.37%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s        | 1         | 1.37%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB DIMM LPDDR5 6400MT/s       | 1         | 1.37%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 1.37%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 1.37%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                    | 1         | 1.37%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 1.37%   |
| Samsung RAM M471B5273QH0-YKO 8GB SODIMM DDR3 1600MT/s          | 1         | 1.37%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 1         | 1.37%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 1.37%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s       | 1         | 1.37%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s       | 1         | 1.37%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 1         | 1.37%   |
| Micron RAM MT52L512M32D2PF-10 4GB SODIMM LPDDR3 1867MT/s       | 1         | 1.37%   |
| Micron RAM MT52L512M32D2PF-10 4GB Chip LPDDR3 1867MT/s         | 1         | 1.37%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.37%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s          | 1         | 1.37%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.37%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 26        | 41.94%  |
| DDR3    | 22        | 35.48%  |
| LPDDR3  | 8         | 12.9%   |
| DDR5    | 2         | 3.23%   |
| LPDDR5  | 1         | 1.61%   |
| LPDDR4  | 1         | 1.61%   |
| DDR2    | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 82.54%  |
| Row Of Chips | 8         | 12.7%   |
| Chip         | 2         | 3.17%   |
| DIMM         | 1         | 1.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 27        | 40.91%  |
| 4096  | 21        | 31.82%  |
| 16384 | 9         | 13.64%  |
| 2048  | 8         | 12.12%  |
| 32768 | 1         | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 24.62%  |
| 2667    | 14        | 21.54%  |
| 1333    | 9         | 13.85%  |
| 2133    | 7         | 10.77%  |
| 3200    | 5         | 7.69%   |
| 1867    | 4         | 6.15%   |
| 1334    | 2         | 3.08%   |
| 6400    | 1         | 1.54%   |
| 5600    | 1         | 1.54%   |
| 4800    | 1         | 1.54%   |
| 4267    | 1         | 1.54%   |
| 2400    | 1         | 1.54%   |
| 1067    | 1         | 1.54%   |
| 800     | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 31.71%  |
| IMC Networks                           | 9         | 21.95%  |
| Bison Electronics                      | 7         | 17.07%  |
| Sunplus Innovation Technology          | 3         | 7.32%   |
| Apple                                  | 3         | 7.32%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.88%   |
| Suyin                                  | 1         | 2.44%   |
| Supreme Electronics                    | 1         | 2.44%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 2.44%   |
| Microdia                               | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 6         | 14.63%  |
| Chicony Integrated Camera                                   | 5         | 12.2%   |
| IMC Networks Integrated Camera                              | 4         | 9.76%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 7.32%   |
| Apple FaceTime HD Camera                                    | 2         | 4.88%   |
| Suyin HD WebCam                                             | 1         | 2.44%   |
| Supreme Realtek PC Camera                                   | 1         | 2.44%   |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 2.44%   |
| Sunplus Laptop Integrated Webcam FHD                        | 1         | 2.44%   |
| Sunplus ASUS Webcam                                         | 1         | 2.44%   |
| Shenzhen Kingcome Optoelectronic FHD WebCam                 | 1         | 2.44%   |
| Microdia Integrated Webcam                                  | 1         | 2.44%   |
| IMC Networks EasyCamera                                     | 1         | 2.44%   |
| IMC Networks ASUS EasyCamera                                | 1         | 2.44%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 2.44%   |
| Chicony USB 2.0 2.0M UVC WebCam                             | 1         | 2.44%   |
| Chicony ThinkPad T490 Webcam                                | 1         | 2.44%   |
| Chicony Lenovo EasyCamera                                   | 1         | 2.44%   |
| Chicony Integrated HP HD Webcam                             | 1         | 2.44%   |
| Chicony Integrated Camera [ThinkPad]                        | 1         | 2.44%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 2.44%   |
| Chicony HP Universal Camera                                 | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 2.44%   |
| Bison Lenovo EasyCamera integrated webcam                   | 1         | 2.44%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 2.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 53.85%  |
| Synaptics                  | 4         | 30.77%  |
| Upek                       | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 15.38%  |
| Validity Sensors VFS491                                | 1         | 7.69%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Synaptics WBDI                                         | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.69%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 32.35%  |
| 1     | 15        | 22.06%  |
| 0     | 14        | 20.59%  |
| 3     | 9         | 13.24%  |
| 4     | 6         | 8.82%   |
| 5     | 2         | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 43        | 39.45%  |
| Bluetooth                | 17        | 15.6%   |
| Net/wireless             | 15        | 13.76%  |
| Fingerprint reader       | 11        | 10.09%  |
| Card reader              | 10        | 9.17%   |
| Firewire controller      | 7         | 6.42%   |
| Net/ethernet             | 2         | 1.83%   |
| Storage                  | 1         | 0.92%   |
| Sound                    | 1         | 0.92%   |
| Network                  | 1         | 0.92%   |
| Graphics card            | 1         | 0.92%   |

