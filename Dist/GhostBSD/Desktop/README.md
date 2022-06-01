GhostBSD - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for GhostBSD.

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

Total: 74

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell      | 0M3F6C A01                  | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek   | PRIME B350-PLUS             | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| Gigabyte  | AX370-Gaming 3-CF           | [62ab2bc823](https://bsd-hardware.info/?probe=62ab2bc823) | May 07, 2022 |
| HP        | 0B4Ch D                     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Dell      | 0DXJD9 A01                  | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| Dell      | 0Y56T3 A00                  | [d9d86d5bfd](https://bsd-hardware.info/?probe=d9d86d5bfd) | Apr 12, 2022 |
| MSI       | B250 PC MATE                | [612b0f0a34](https://bsd-hardware.info/?probe=612b0f0a34) | Mar 19, 2022 |
| ASUSTek   | TUF GAMING X570-PRO         | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| ASUSTek   | Z97-A                       | [84d7fb3f1e](https://bsd-hardware.info/?probe=84d7fb3f1e) | Jan 30, 2022 |
| Dell      | 0NNNCT A01                  | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Alienware | 01NYPT A00                  | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| ASUSTek   | PRIME Z270-K                | [a2270b6f09](https://bsd-hardware.info/?probe=a2270b6f09) | Dec 02, 2021 |
| Medion    | MS-7728                     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Gigabyte  | H410M S2 V2                 | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| ASUSTek   | SABERTOOTH X58              | [8f00f132de](https://bsd-hardware.info/?probe=8f00f132de) | Sep 23, 2021 |
| ASRock    | X570 Taichi                 | [9dc50c0bcb](https://bsd-hardware.info/?probe=9dc50c0bcb) | Sep 11, 2021 |
| ASUSTek   | PRIME B350-PLUS             | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| Gigabyte  | Z77M-D3H                    | [d60f1bc575](https://bsd-hardware.info/?probe=d60f1bc575) | Aug 29, 2021 |
| MSI       | H81M-P33                    | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock    | X570 Pro4                   | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| ASRock    | Z77 Extreme6                | [2521c70747](https://bsd-hardware.info/?probe=2521c70747) | Aug 02, 2021 |
| ASUSTek   | PRIME B350M-E               | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| ASUSTek   | PRIME A320M-A               | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Lenovo    | Board                       | [428f39cbff](https://bsd-hardware.info/?probe=428f39cbff) | May 21, 2021 |
| ASUSTek   | V-P7H55E                    | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| ASUSTek   | V-P7H55E                    | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek   | V-P7H55E                    | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Dell      | 0TP412                      | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Huanan    | X79 INTEL (INTEL Xeon E5... | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| HP        | 1850                        | [3055c06d45](https://bsd-hardware.info/?probe=3055c06d45) | Mar 22, 2021 |
| ASRock    | X570 Phantom Gaming 4       | [a64a4e0792](https://bsd-hardware.info/?probe=a64a4e0792) | Mar 19, 2021 |
| ASUSTek   | ROG STRIX B450-F GAMING     | [39a46ce44e](https://bsd-hardware.info/?probe=39a46ce44e) | Mar 06, 2021 |
| Gigabyte  | EG43M-S2H                   | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| Acer      | Aspire XC-115               | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Lenovo    | Kabini CRB 31900058 STD     | [c08ca084b0](https://bsd-hardware.info/?probe=c08ca084b0) | Feb 21, 2021 |
| ASRock    | AB350 Pro4                  | [3680c4cd75](https://bsd-hardware.info/?probe=3680c4cd75) | Feb 20, 2021 |
| ASUSTek   | PRIME B450-PLUS             | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Acer      | WG43M                       | [28a6795710](https://bsd-hardware.info/?probe=28a6795710) | Feb 15, 2021 |
| MSI       | PRESTIGE X570 CREATION      | [e6fa5753b5](https://bsd-hardware.info/?probe=e6fa5753b5) | Feb 12, 2021 |
| MSI       | PRESTIGE X570 CREATION      | [fd798dae01](https://bsd-hardware.info/?probe=fd798dae01) | Feb 12, 2021 |
| Dell      | 030VXY A01                  | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [cf41f72474](https://bsd-hardware.info/?probe=cf41f72474) | Jan 31, 2021 |
| Dell      | 0NW6H5 A00                  | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| MSI       | Z97 GAMING 5                | [9ef0da6093](https://bsd-hardware.info/?probe=9ef0da6093) | Jan 16, 2021 |
| Dell      | 0KC9NP A01                  | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell      | 030VXY A01                  | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| Dell      | 0HY9JP A02                  | [b4d2af272e](https://bsd-hardware.info/?probe=b4d2af272e) | Jan 05, 2021 |
| ASUSTek   | Z170I PRO GAMING            | [5124b24d30](https://bsd-hardware.info/?probe=5124b24d30) | Jan 04, 2021 |
| Fujitsu   | D3617-A1 S26361-D3617-A1    | [2a0187ef7a](https://bsd-hardware.info/?probe=2a0187ef7a) | Jan 02, 2021 |
| ASUSTek   | PRIME A320M-C R2.0          | [4c24fe6fc4](https://bsd-hardware.info/?probe=4c24fe6fc4) | Dec 24, 2020 |
| HP        | 0B4Ch D                     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Gigabyte  | Z370 AORUS Ultra Gaming-... | [a3a96da3fb](https://bsd-hardware.info/?probe=a3a96da3fb) | Dec 19, 2020 |
| ASUSTek   | TUF GAMING B550M-PLUS       | [464223cefe](https://bsd-hardware.info/?probe=464223cefe) | Dec 07, 2020 |
| ASRock    | B450 Gaming-ITX/ac          | [53bf449015](https://bsd-hardware.info/?probe=53bf449015) | Dec 02, 2020 |
| Quanta    | 2AF5 011                    | [172f23efac](https://bsd-hardware.info/?probe=172f23efac) | Nov 29, 2020 |
| ASRock    | AB350 Gaming-ITX/ac         | [8afa16fc20](https://bsd-hardware.info/?probe=8afa16fc20) | Nov 29, 2020 |
| Gigabyte  | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI       | B450 GAMING PLUS            | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| MSI       | B450 GAMING PLUS            | [edee76372b](https://bsd-hardware.info/?probe=edee76372b) | Nov 21, 2020 |
| ASRock    | X570 Phantom Gaming 4       | [cc075b3932](https://bsd-hardware.info/?probe=cc075b3932) | Nov 15, 2020 |
| ASRock    | X570 Phantom Gaming 4       | [6a0c640524](https://bsd-hardware.info/?probe=6a0c640524) | Nov 12, 2020 |
| ASRock    | X570 Phantom Gaming 4       | [6060033216](https://bsd-hardware.info/?probe=6060033216) | Nov 12, 2020 |
| Gigabyte  | Z97-D3H-CF                  | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Fujitsu   | D2950-A1 S26361-D2950-A1    | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu   | D2950-A1 S26361-D2950-A1    | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| MSI       | H61M-P20                    | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Gigabyte  | F2A68HM-DS2                 | [0073f8ff71](https://bsd-hardware.info/?probe=0073f8ff71) | Aug 02, 2020 |
| Gigabyte  | H67A-UD3H-B3                | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| Unknown   | SKYBAY                      | [34bb81770b](https://bsd-hardware.info/?probe=34bb81770b) | Jul 22, 2020 |
| ASRock    | X370 Gaming K4              | [4473708fd0](https://bsd-hardware.info/?probe=4473708fd0) | Jul 22, 2020 |
| ASRock    | X370 Gaming K4              | [174569bf55](https://bsd-hardware.info/?probe=174569bf55) | Jul 21, 2020 |
| ASRock    | A300M-STX                   | [f62a2ace5a](https://bsd-hardware.info/?probe=f62a2ace5a) | Jul 16, 2020 |
| Lenovo    | Win8 Pro DPK TPG            | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Gigabyte  | Z170X-UD5 TH-CF             | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GhostBSD 20.04.02 | 45       | 72.58%  |
| GhostBSD 21.08.27 | 8        | 12.9%   |
| GhostBSD 22.01.12 | 3        | 4.84%   |
| GhostBSD 22.04.06 | 2        | 3.23%   |
| GhostBSD 22.05.14 | 1        | 1.61%   |
| GhostBSD 22.04.22 | 1        | 1.61%   |
| GhostBSD 22.01.28 | 1        | 1.61%   |
| GhostBSD 19.12    | 1        | 1.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GhostBSD | 60       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 60       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MATE             | 46       | 74.19%  |
| XFCE             | 7        | 11.29%  |
| KDE5             | 4        | 6.45%   |
| openbox          | 1        | 1.61%   |
| Metacity (Marco) | 1        | 1.61%   |
| LXQt             | 1        | 1.61%   |
| i3               | 1        | 1.61%   |
| GNOME            | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 60       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 58       | 96.67%  |
| SDDM    | 2        | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 28       | 45.9%   |
| Unknown | 11       | 18.03%  |
| C       | 8        | 13.11%  |
| de_DE   | 5        | 8.2%    |
| ru_RU   | 4        | 6.56%   |
| fr_FR   | 2        | 3.28%   |
| sk_SK   | 1        | 1.64%   |
| en_GB   | 1        | 1.64%   |
| en_AU   | 1        | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 46       | 76.67%  |
| BIOS | 14       | 23.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 57       | 95%     |
| Ufs  | 3        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 56       | 93.33%  |
| MBR  | 4        | 6.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 13       | 21.67%  |
| Gigabyte Technology | 9        | 15%     |
| Dell                | 9        | 15%     |
| ASRock              | 8        | 13.33%  |
| MSI                 | 7        | 11.67%  |
| Lenovo              | 3        | 5%      |
| Hewlett-Packard     | 2        | 3.33%   |
| Fujitsu             | 2        | 3.33%   |
| Acer                | 2        | 3.33%   |
| Quanta              | 1        | 1.67%   |
| Medion              | 1        | 1.67%   |
| Huanan              | 1        | 1.67%   |
| Alienware           | 1        | 1.67%   |
| Unknown             | 1        | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI MS-7B86                                                           | 2        | 3.33%   |
| Quanta 120-1333w                                                      | 1        | 1.67%   |
| MSI MS-7C36                                                           | 1        | 1.67%   |
| MSI MS-7A72                                                           | 1        | 1.67%   |
| MSI MS-7917                                                           | 1        | 1.67%   |
| MSI MS-7817                                                           | 1        | 1.67%   |
| MSI MS-7788                                                           | 1        | 1.67%   |
| Medion MS-7728                                                        | 1        | 1.67%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1        | 1.67%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1        | 1.67%   |
| Lenovo H515s 10126                                                    | 1        | 1.67%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1        | 1.67%   |
| HP Z400 Workstation                                                   | 1        | 1.67%   |
| HP Compaq Pro 6305 SFF                                                | 1        | 1.67%   |
| Gigabyte Z97-D3H                                                      | 1        | 1.67%   |
| Gigabyte Z77M-D3H                                                     | 1        | 1.67%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1        | 1.67%   |
| Gigabyte Z170X-UD5 TH                                                 | 1        | 1.67%   |
| Gigabyte X470 AORUS ULTRA GAMING                                      | 1        | 1.67%   |
| Gigabyte H67A-UD3H-B3                                                 | 1        | 1.67%   |
| Gigabyte F2A68HM-DS2                                                  | 1        | 1.67%   |
| Gigabyte EG43M-S2H                                                    | 1        | 1.67%   |
| Gigabyte AX370-Gaming 3                                               | 1        | 1.67%   |
| Fujitsu ESPRIMO P1500                                                 | 1        | 1.67%   |
| Fujitsu CELSIUS W580                                                  | 1        | 1.67%   |
| Dell Precision WorkStation T3400                                      | 1        | 1.67%   |
| Dell Precision T5600                                                  | 1        | 1.67%   |
| Dell Precision 3630 Tower                                             | 1        | 1.67%   |
| Dell OptiPlex 9020                                                    | 1        | 1.67%   |
| Dell OptiPlex 790                                                     | 1        | 1.67%   |
| Dell OptiPlex 7050                                                    | 1        | 1.67%   |
| Dell OptiPlex 5060                                                    | 1        | 1.67%   |
| Dell OptiPlex 3080                                                    | 1        | 1.67%   |
| Dell G5 5090                                                          | 1        | 1.67%   |
| ASUS Z170I PRO GAMING                                                 | 1        | 1.67%   |
| ASUS TUF GAMING X570-PRO                                              | 1        | 1.67%   |
| ASUS TUF GAMING X570-PLUS                                             | 1        | 1.67%   |
| ASUS TUF GAMING B550M-PLUS                                            | 1        | 1.67%   |
| ASUS SABERTOOTH X58                                                   | 1        | 1.67%   |
| ASUS ROG STRIX B450-F GAMING                                          | 1        | 1.67%   |
| ASUS PRIME Z270-K                                                     | 1        | 1.67%   |
| ASUS PRIME B450-PLUS                                                  | 1        | 1.67%   |
| ASUS PRIME B350M-E                                                    | 1        | 1.67%   |
| ASUS PRIME B350-PLUS                                                  | 1        | 1.67%   |
| ASUS PRIME A320M-C R2.0                                               | 1        | 1.67%   |
| ASUS PRIME A320M-A                                                    | 1        | 1.67%   |
| ASUS All Series                                                       | 1        | 1.67%   |
| ASRock Z77 Extreme6                                                   | 1        | 1.67%   |
| ASRock X570 Taichi                                                    | 1        | 1.67%   |
| ASRock X570 Pro4                                                      | 1        | 1.67%   |
| ASRock X570 Phantom Gaming 4                                          | 1        | 1.67%   |
| ASRock X370 Gaming K4                                                 | 1        | 1.67%   |
| ASRock B450 Gaming-ITX/ac                                             | 1        | 1.67%   |
| ASRock AB350 Gaming-ITX/ac                                            | 1        | 1.67%   |
| ASRock A300M-STX                                                      | 1        | 1.67%   |
| Alienware Aurora R5                                                   | 1        | 1.67%   |
| Acer Aspire XC-115                                                    | 1        | 1.67%   |
| Acer Aspire X3910                                                     | 1        | 1.67%   |
| Unknown                                                               | 1        | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 6        | 10%     |
| Dell OptiPlex         | 5        | 8.33%   |
| Dell Precision        | 3        | 5%      |
| ASUS TUF              | 3        | 5%      |
| ASRock X570           | 3        | 5%      |
| MSI MS-7B86           | 2        | 3.33%   |
| Acer Aspire           | 2        | 3.33%   |
| Quanta 120-1333w      | 1        | 1.67%   |
| MSI MS-7C36           | 1        | 1.67%   |
| MSI MS-7A72           | 1        | 1.67%   |
| MSI MS-7917           | 1        | 1.67%   |
| MSI MS-7817           | 1        | 1.67%   |
| MSI MS-7788           | 1        | 1.67%   |
| Medion MS-7728        | 1        | 1.67%   |
| Lenovo ThinkStation   | 1        | 1.67%   |
| Lenovo ThinkCentre    | 1        | 1.67%   |
| Lenovo H515s          | 1        | 1.67%   |
| Huanan X79            | 1        | 1.67%   |
| HP Z400               | 1        | 1.67%   |
| HP Compaq             | 1        | 1.67%   |
| Gigabyte Z97-D3H      | 1        | 1.67%   |
| Gigabyte Z77M-D3H     | 1        | 1.67%   |
| Gigabyte Z370         | 1        | 1.67%   |
| Gigabyte Z170X-UD5    | 1        | 1.67%   |
| Gigabyte X470         | 1        | 1.67%   |
| Gigabyte H67A-UD3H-B3 | 1        | 1.67%   |
| Gigabyte F2A68HM-DS2  | 1        | 1.67%   |
| Gigabyte EG43M-S2H    | 1        | 1.67%   |
| Gigabyte AX370-Gaming | 1        | 1.67%   |
| Fujitsu ESPRIMO       | 1        | 1.67%   |
| Fujitsu CELSIUS       | 1        | 1.67%   |
| Dell G5               | 1        | 1.67%   |
| ASUS Z170I            | 1        | 1.67%   |
| ASUS SABERTOOTH       | 1        | 1.67%   |
| ASUS ROG              | 1        | 1.67%   |
| ASUS All              | 1        | 1.67%   |
| ASRock Z77            | 1        | 1.67%   |
| ASRock X370           | 1        | 1.67%   |
| ASRock B450           | 1        | 1.67%   |
| ASRock AB350          | 1        | 1.67%   |
| ASRock A300M-STX      | 1        | 1.67%   |
| Alienware Aurora      | 1        | 1.67%   |
| Unknown               | 1        | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 20%     |
| 2020 | 8        | 13.33%  |
| 2019 | 8        | 13.33%  |
| 2012 | 6        | 10%     |
| 2016 | 4        | 6.67%   |
| 2014 | 4        | 6.67%   |
| 2008 | 4        | 6.67%   |
| 2013 | 3        | 5%      |
| 2011 | 3        | 5%      |
| 2017 | 2        | 3.33%   |
| 2015 | 2        | 3.33%   |
| 2022 | 1        | 1.67%   |
| 2021 | 1        | 1.67%   |
| 2010 | 1        | 1.67%   |
| 2009 | 1        | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 60       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 18       | 30%     |
| 32.01-64.0  | 15       | 25%     |
| 8.01-16.0   | 14       | 23.33%  |
| 4.01-8.0    | 9        | 15%     |
| 64.01-256.0 | 3        | 5%      |
| 24.01-32.0  | 1        | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 25       | 41.67%  |
| 0.01-0.5 | 19       | 31.67%  |
| 1.01-2.0 | 13       | 21.67%  |
| 3.01-4.0 | 3        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 41.27%  |
| 1      | 18       | 28.57%  |
| 3      | 6        | 9.52%   |
| 5      | 5        | 7.94%   |
| 4      | 4        | 6.35%   |
| 6      | 2        | 3.17%   |
| 7      | 1        | 1.59%   |
| 0      | 1        | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 55%     |
| Yes       | 27       | 45%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 65%     |
| Yes       | 21       | 35%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 73.33%  |
| Yes       | 16       | 26.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 15       | 25%     |
| Germany     | 9        | 15%     |
| Russia      | 5        | 8.33%   |
| France      | 5        | 8.33%   |
| UK          | 4        | 6.67%   |
| Canada      | 3        | 5%      |
| Norway      | 2        | 3.33%   |
| Netherlands | 2        | 3.33%   |
| Czechia     | 2        | 3.33%   |
| Australia   | 2        | 3.33%   |
| Ukraine     | 1        | 1.67%   |
| Switzerland | 1        | 1.67%   |
| Sweden      | 1        | 1.67%   |
| Spain       | 1        | 1.67%   |
| Mexico      | 1        | 1.67%   |
| Malaysia    | 1        | 1.67%   |
| Luxembourg  | 1        | 1.67%   |
| Japan       | 1        | 1.67%   |
| Hungary     | 1        | 1.67%   |
| Finland     | 1        | 1.67%   |
| China       | 1        | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 3        | 5%      |
| Berlin           | 3        | 5%      |
| Obninsk          | 2        | 3.33%   |
| Denver           | 2        | 3.33%   |
| ЕЊta-ku        | 1        | 1.67%   |
| Zapopan          | 1        | 1.67%   |
| Washington       | 1        | 1.67%   |
| Vidnoye          | 1        | 1.67%   |
| Veenendaal       | 1        | 1.67%   |
| Truro            | 1        | 1.67%   |
| Traunstein       | 1        | 1.67%   |
| Sydney           | 1        | 1.67%   |
| St. Albert       | 1        | 1.67%   |
| St Petersburg    | 1        | 1.67%   |
| Springfield      | 1        | 1.67%   |
| San Jose         | 1        | 1.67%   |
| Robbins          | 1        | 1.67%   |
| Riedstadt        | 1        | 1.67%   |
| Richmond         | 1        | 1.67%   |
| Prague           | 1        | 1.67%   |
| Phoenix          | 1        | 1.67%   |
| Palm Bay         | 1        | 1.67%   |
| Oslo             | 1        | 1.67%   |
| Omaha            | 1        | 1.67%   |
| Moncton          | 1        | 1.67%   |
| Madrid           | 1        | 1.67%   |
| Luxembourg       | 1        | 1.67%   |
| Lorient          | 1        | 1.67%   |
| London           | 1        | 1.67%   |
| Larnod           | 1        | 1.67%   |
| Kyiv             | 1        | 1.67%   |
| Kuala Lumpur     | 1        | 1.67%   |
| Kaplice          | 1        | 1.67%   |
| JГ¶nkГ¶ping  | 1        | 1.67%   |
| JyvГ¤skylГ¤  | 1        | 1.67%   |
| Huntingdon       | 1        | 1.67%   |
| Heilbronn        | 1        | 1.67%   |
| Hamilton         | 1        | 1.67%   |
| Hamburg          | 1        | 1.67%   |
| Glace Bay        | 1        | 1.67%   |
| Eiken            | 1        | 1.67%   |
| Drammen          | 1        | 1.67%   |
| Delton           | 1        | 1.67%   |
| Dandenong        | 1        | 1.67%   |
| Dabas            | 1        | 1.67%   |
| Colorado Springs | 1        | 1.67%   |
| Cologne          | 1        | 1.67%   |
| Chelyabinsk      | 1        | 1.67%   |
| Bonn             | 1        | 1.67%   |
| Bijie            | 1        | 1.67%   |
| Banbury          | 1        | 1.67%   |
| Atascadero       | 1        | 1.67%   |
| Anchorage        | 1        | 1.67%   |
| Amsterdam        | 1        | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 40     | 23.73%  |
| Samsung Electronics | 22       | 29     | 18.64%  |
| Seagate             | 17       | 22     | 14.41%  |
| Crucial             | 11       | 12     | 9.32%   |
| Toshiba             | 6        | 6      | 5.08%   |
| Hitachi             | 6        | 6      | 5.08%   |
| SanDisk             | 3        | 4      | 2.54%   |
| Kingston            | 3        | 3      | 2.54%   |
| A-DATA Technology   | 3        | 3      | 2.54%   |
| Micron Technology   | 2        | 2      | 1.69%   |
| MAXTOR              | 2        | 2      | 1.69%   |
| Intel               | 2        | 2      | 1.69%   |
| HGST                | 2        | 2      | 1.69%   |
| XPG                 | 1        | 1      | 0.85%   |
| Transcend           | 1        | 1      | 0.85%   |
| SPCC                | 1        | 1      | 0.85%   |
| PNY                 | 1        | 3      | 0.85%   |
| PLEXTOR             | 1        | 1      | 0.85%   |
| Phison              | 1        | 2      | 0.85%   |
| Patriot             | 1        | 1      | 0.85%   |
| OCZ                 | 1        | 1      | 0.85%   |
| LDLC                | 1        | 1      | 0.85%   |
| HPT                 | 1        | 4      | 0.85%   |
| AMD                 | 1        | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Crucial CT1000MX500SSD1 1TB        | 4        | 3.03%   |
| Samsung SSD 850 EVO 500GB          | 3        | 2.27%   |
| WDC WD40EFRX-68N32N0 4TB           | 2        | 1.52%   |
| WDC WD2000JS-55MHB0 192GB          | 2        | 1.52%   |
| WDC WD10EZEX-21M2NA0 1TB           | 2        | 1.52%   |
| Toshiba Q300 480GB                 | 2        | 1.52%   |
| Toshiba HDWD120 2TB                | 2        | 1.52%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 1.52%   |
| Samsung SSD 970 EVO Plus 1TB       | 2        | 1.52%   |
| Samsung SSD 970 EVO 500GB          | 2        | 1.52%   |
| Samsung SSD 860 QVO 1TB            | 2        | 1.52%   |
| Samsung SSD 850 EVO 250GB          | 2        | 1.52%   |
| MAXTOR STM3320613AS 320GB          | 2        | 1.52%   |
| Crucial CT250MX500SSD1 250GB       | 2        | 1.52%   |
| XPG GAMMIX S11 Pro 256GB           | 1        | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB       | 1        | 0.76%   |
| WDC WDS500G2B0A 500GB              | 1        | 0.76%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1        | 0.76%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 1        | 0.76%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.76%   |
| WDC WD800BEVT-75ZCT2 80GB          | 1        | 0.76%   |
| WDC WD7500LPCX-00KHST0 752GB       | 1        | 0.76%   |
| WDC WD60EZRZ-00GZ5B1 6TB           | 1        | 0.76%   |
| WDC WD6003FFBX-68MU3N0 6TB         | 1        | 0.76%   |
| WDC WD5000LPLX-75ZNTT0 500GB       | 1        | 0.76%   |
| WDC WD5000BEVT-24A0RT0 500GB       | 1        | 0.76%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 0.76%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 0.76%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 0.76%   |
| WDC WD5000AAKS-60WWPA0 500GB       | 1        | 0.76%   |
| WDC WD3200BEKT-75KA9T0 320GB       | 1        | 0.76%   |
| WDC WD2500AAJS-75M0A0 250GB        | 1        | 0.76%   |
| WDC WD20SPZX-22UA7T0 2TB           | 1        | 0.76%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1        | 0.76%   |
| WDC WD2002FAEX-007BA0 2TB          | 1        | 0.76%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1        | 0.76%   |
| WDC WD10EALX-009BA0 1TB            | 1        | 0.76%   |
| WDC WD1002FBYS-05A6B0 1TB          | 1        | 0.76%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1        | 0.76%   |
| WDC PC SN520 NVMe 256GB            | 1        | 0.76%   |
| Transcend TS120GMTS820S 120GB      | 1        | 0.76%   |
| Toshiba MQ01ABD100 1TB             | 1        | 0.76%   |
| Toshiba DT01ACA050 500GB           | 1        | 0.76%   |
| SPCC Solid State Disk 240GB        | 1        | 0.76%   |
| Seagate ST8000DM004-2CX188 8TB     | 1        | 0.76%   |
| Seagate ST8000AS0002-1NA17Z 8TB    | 1        | 0.76%   |
| Seagate ST500DM002-1SB10A 500GB    | 1        | 0.76%   |
| Seagate ST500DM002-1BC142 500GB    | 1        | 0.76%   |
| Seagate ST400FP0021 400GB          | 1        | 0.76%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 0.76%   |
| Seagate ST4000DM000-1F2168 4TB     | 1        | 0.76%   |
| Seagate ST3500312CS 500GB          | 1        | 0.76%   |
| Seagate ST31500541AS 1.5TB         | 1        | 0.76%   |
| Seagate ST31000528AS 1TB           | 1        | 0.76%   |
| Seagate ST2000NM0008-2F3100 2TB    | 1        | 0.76%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 0.76%   |
| Seagate ST1500DL003-9VT16L 1.5TB   | 1        | 0.76%   |
| Seagate ST1000VM002-1SD102 1TB     | 1        | 0.76%   |
| Seagate ST1000LM049-2GH172 1TB     | 1        | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 34     | 40.68%  |
| Seagate             | 16       | 21     | 27.12%  |
| Hitachi             | 6        | 6      | 10.17%  |
| Toshiba             | 4        | 4      | 6.78%   |
| Samsung Electronics | 4        | 5      | 6.78%   |
| MAXTOR              | 2        | 2      | 3.39%   |
| HGST                | 2        | 2      | 3.39%   |
| HPT                 | 1        | 4      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 15     | 29.79%  |
| Crucial             | 10       | 11     | 21.28%  |
| SanDisk             | 3        | 4      | 6.38%   |
| A-DATA Technology   | 3        | 3      | 6.38%   |
| WDC                 | 2        | 2      | 4.26%   |
| Toshiba             | 2        | 2      | 4.26%   |
| Micron Technology   | 2        | 2      | 4.26%   |
| Kingston            | 2        | 2      | 4.26%   |
| Transcend           | 1        | 1      | 2.13%   |
| SPCC                | 1        | 1      | 2.13%   |
| Seagate             | 1        | 1      | 2.13%   |
| PNY                 | 1        | 3      | 2.13%   |
| PLEXTOR             | 1        | 1      | 2.13%   |
| Patriot             | 1        | 1      | 2.13%   |
| OCZ                 | 1        | 1      | 2.13%   |
| Intel               | 1        | 1      | 2.13%   |
| AMD                 | 1        | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 43       | 78     | 46.74%  |
| SSD  | 33       | 52     | 35.87%  |
| NVMe | 16       | 20     | 17.39%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 58       | 130    | 78.38%  |
| NVMe | 16       | 20     | 21.62%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 44       | 65     | 48.89%  |
| 0.51-1.0   | 23       | 32     | 25.56%  |
| 1.01-2.0   | 12       | 15     | 13.33%  |
| 3.01-4.0   | 6        | 7      | 6.67%   |
| 4.01-10.0  | 4        | 9      | 4.44%   |
| 2.01-3.0   | 1        | 2      | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 16       | 26.23%  |
| 251-500    | 14       | 22.95%  |
| 1-20       | 14       | 22.95%  |
| 501-1000   | 5        | 8.2%    |
| 51-100     | 5        | 8.2%    |
| Unknown    | 3        | 4.92%   |
| 21-50      | 2        | 3.28%   |
| 1001-2000  | 2        | 3.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 50       | 81.97%  |
| 21-50   | 7        | 11.48%  |
| Unknown | 3        | 4.92%   |
| 51-100  | 1        | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| MAXTOR STM3320613AS 320GB       | 2        | 2      | 15.38%  |
| WDC WD5000AAKS-60WWPA0 500GB    | 1        | 1      | 7.69%   |
| WDC WD10EZEX-21M2NA0 1TB        | 1        | 1      | 7.69%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 7.69%   |
| Seagate ST500DM002-1BC142 500GB | 1        | 1      | 7.69%   |
| Seagate ST31500541AS 1.5TB      | 1        | 1      | 7.69%   |
| Samsung Electronics HD103SJ 1TB | 1        | 2      | 7.69%   |
| OCZ AGILITY3 240GB              | 1        | 1      | 7.69%   |
| Hitachi HTS725032A9A364 320GB   | 1        | 1      | 7.69%   |
| Hitachi HTS547575A9E384 752GB   | 1        | 1      | 7.69%   |
| Hitachi HTS541680J9SA00 80GB    | 1        | 1      | 7.69%   |
| Crucial CT1000MX500SSD1 1TB     | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 23.08%  |
| Hitachi             | 3        | 3      | 23.08%  |
| WDC                 | 2        | 2      | 15.38%  |
| MAXTOR              | 2        | 2      | 15.38%  |
| Samsung Electronics | 1        | 2      | 7.69%   |
| OCZ                 | 1        | 1      | 7.69%   |
| Crucial             | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 27.27%  |
| Hitachi             | 3        | 3      | 27.27%  |
| WDC                 | 2        | 2      | 18.18%  |
| MAXTOR              | 2        | 2      | 18.18%  |
| Samsung Electronics | 1        | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 12     | 83.33%  |
| SSD  | 2        | 2      | 16.67%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 59       | 132    | 81.94%  |
| Malfunc  | 12       | 14     | 16.67%  |
| Detected | 1        | 4      | 1.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 34       | 40.48%  |
| AMD                           | 26       | 30.95%  |
| Samsung Electronics           | 7        | 8.33%   |
| Sandisk                       | 3        | 3.57%   |
| Marvell Technology Group      | 2        | 2.38%   |
| ASMedia Technology            | 2        | 2.38%   |
| Silicon Motion                | 1        | 1.19%   |
| Phison Electronics            | 1        | 1.19%   |
| Nvidia                        | 1        | 1.19%   |
| Micron/Crucial Technology     | 1        | 1.19%   |
| Kingston Technology Company   | 1        | 1.19%   |
| JMicron Technology            | 1        | 1.19%   |
| Integrated Technology Express | 1        | 1.19%   |
| HighPoint Technologies        | 1        | 1.19%   |
| ADATA Technology              | 1        | 1.19%   |
| Adaptec                       | 1        | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 21.36%  |
| Intel SATA Controller [RAID mode]                                                       | 7        | 6.8%    |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 5.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 4.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 2.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.91%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.94%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.94%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.94%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.94%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.94%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.94%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.97%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.97%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.97%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.97%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.97%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.97%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.97%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.97%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.97%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.97%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.97%   |
| Intel SSD 660P Series                                                                   | 1        | 0.97%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                            | 1        | 0.97%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.97%   |
| Integrated Express IT8213 IDE Controller                                                | 1        | 0.97%   |
| HighPoint RocketRAID 230x 4 Port SATA-II Controller                                     | 1        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.97%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 1        | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 48       | 57.83%  |
| NVMe | 16       | 19.28%  |
| IDE  | 9        | 10.84%  |
| RAID | 7        | 8.43%   |
| SCSI | 2        | 2.41%   |
| SAS  | 1        | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 34       | 56.67%  |
| AMD    | 26       | 43.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 5%      |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 5%      |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 5%      |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 3.33%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 2        | 3.33%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                | 1        | 1.67%   |
| Intel Xeon CPU W3680 @ 3.33GHz                 | 1        | 1.67%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz             | 1        | 1.67%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GH              | 1        | 1.67%   |
| Intel Xeon                                     | 1        | 1.67%   |
| Intel Unknown                                  | 1        | 1.67%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz    | 1        | 1.67%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 1        | 1.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 1        | 1.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.67%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 1.67%   |
| Intel Core i7-3770S CPU @ 3.10GHz              | 1        | 1.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.67%   |
| Intel Core i7-2600K CPU                        | 1        | 1.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 1.67%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 1.67%   |
| Intel Core i5-8600K CPU @ 3.60GHz              | 1        | 1.67%   |
| Intel Core i5-8400T CPU @ 1.70GHz              | 1        | 1.67%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 1.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 1.67%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 1        | 1.67%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.67%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 1.67%   |
| Intel Core i5-2500 CPU @ 3.30GH                | 1        | 1.67%   |
| Intel Core i5-10500T CPU @ 2.30GHz             | 1        | 1.67%   |
| Intel Core i3-7100U CPU @ 2.40GHz              | 1        | 1.67%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 1.67%   |
| Intel Core 2 Quad CPU Q9400                    | 1        | 1.67%   |
| Intel Core 2 Quad CPU                          | 1        | 1.67%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 1.67%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 1.67%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.67%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 1.67%   |
| AMD Ryzen 5 3600XT 6-Core Processor            | 1        | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 1.67%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 1        | 1.67%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 1.67%   |
| AMD Ryzen 3 PRO 4350G with Radeon Graphics     | 1        | 1.67%   |
| AMD Ryzen 3 3100 4-Core Processor              | 1        | 1.67%   |
| AMD Ryzen 3 1200 Quad-Core Processor           | 1        | 1.67%   |
| AMD E2-6110 APU with AMD Radeon R2 Graphics    | 1        | 1.67%   |
| AMD E1-2500 APU with Radeon HD Graphics        | 1        | 1.67%   |
| AMD E1-1200 APU with Radeon HD Graphics        | 1        | 1.67%   |
| AMD Athlon X4 760K Quad Core Processor         | 1        | 1.67%   |
| AMD A6-6400K APU with Radeon HD Graphics       | 1        | 1.67%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 11       | 18.33%  |
| Intel Core i5           | 11       | 18.33%  |
| AMD Ryzen 7             | 8        | 13.33%  |
| AMD Ryzen 5             | 7        | 11.67%  |
| Intel Xeon              | 5        | 8.33%   |
| Intel Core i3           | 2        | 3.33%   |
| Intel Core 2 Quad       | 2        | 3.33%   |
| AMD Ryzen 9             | 2        | 3.33%   |
| AMD Ryzen 3             | 2        | 3.33%   |
| AMD E1                  | 2        | 3.33%   |
| Other                   | 1        | 1.67%   |
| Intel Pentium Dual-Core | 1        | 1.67%   |
| Intel Pentium           | 1        | 1.67%   |
| AMD Ryzen 3 PRO         | 1        | 1.67%   |
| AMD E2                  | 1        | 1.67%   |
| AMD Athlon X4           | 1        | 1.67%   |
| AMD A6                  | 1        | 1.67%   |
| AMD A10                 | 1        | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 22       | 36.67%  |
| 16      | 8        | 13.33%  |
| 2       | 8        | 13.33%  |
| 12      | 7        | 11.67%  |
| 6       | 7        | 11.67%  |
| 8       | 4        | 6.67%   |
| Unknown | 2        | 3.33%   |
| 32      | 1        | 1.67%   |
| 24      | 1        | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 98.33%  |
| 2      | 1        | 1.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 41       | 68.33%  |
| 2       | 17       | 28.33%  |
| Unknown | 2        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 9        | 15%     |
| Zen+        | 7        | 11.67%  |
| Zen 2       | 7        | 11.67%  |
| SandyBridge | 6        | 10%     |
| Penryn      | 5        | 8.33%   |
| Haswell     | 5        | 8.33%   |
| Zen 3       | 3        | 5%      |
| Zen         | 3        | 5%      |
| Skylake     | 3        | 5%      |
| IvyBridge   | 3        | 5%      |
| Piledriver  | 2        | 3.33%   |
| Westmere    | 1        | 1.67%   |
| Puma        | 1        | 1.67%   |
| Nehalem     | 1        | 1.67%   |
| Jaguar      | 1        | 1.67%   |
| Excavator   | 1        | 1.67%   |
| CometLake   | 1        | 1.67%   |
| Bobcat      | 1        | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 34       | 53.13%  |
| AMD    | 16       | 25%     |
| Intel  | 14       | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 6.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 6.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 4.62%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 4.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 4.62%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.62%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 3.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.08%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 3.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 3.08%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 3.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 3.08%   |
| Intel HD Graphics 630                                                       | 2        | 3.08%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 3.08%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.54%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.54%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.54%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.54%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.54%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.54%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.54%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.54%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.54%   |
| Intel HD Graphics 620                                                       | 1        | 1.54%   |
| Intel HD Graphics 530                                                       | 1        | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.54%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.54%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.54%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.54%   |
| AMD Mullins [Radeon R2 Graphics]                                            | 1        | 1.54%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                            | 1        | 1.54%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 1.54%   |
| AMD Cezanne                                                                 | 1        | 1.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.54%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 29       | 48.33%  |
| 1 x AMD        | 15       | 25%     |
| 1 x Intel      | 10       | 16.67%  |
| Intel + Nvidia | 3        | 5%      |
| 2 x Nvidia     | 1        | 1.67%   |
| 2 x Intel      | 1        | 1.67%   |
| AMD + Nvidia   | 1        | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Proprietary | 31       | 51.67%  |
| Free        | 29       | 48.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 36.07%  |
| 7.01-8.0   | 10       | 16.39%  |
| 1.01-2.0   | 10       | 16.39%  |
| 0.51-1.0   | 8        | 13.11%  |
| 3.01-4.0   | 7        | 11.48%  |
| 0.01-0.5   | 3        | 4.92%   |
| 2.01-3.0   | 1        | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 9        | 14.52%  |
| Samsung Electronics  | 8        | 12.9%   |
| Goldstar             | 6        | 9.68%   |
| BenQ                 | 5        | 8.06%   |
| Acer                 | 4        | 6.45%   |
| Philips              | 3        | 4.84%   |
| Hewlett-Packard      | 3        | 4.84%   |
| AOC                  | 3        | 4.84%   |
| ViewSonic            | 2        | 3.23%   |
| LG Electronics       | 2        | 3.23%   |
| Lenovo               | 2        | 3.23%   |
| Iiyama               | 2        | 3.23%   |
| ASUSTek Computer     | 2        | 3.23%   |
| WYT                  | 1        | 1.61%   |
| Vizio                | 1        | 1.61%   |
| Toshiba              | 1        | 1.61%   |
| Pixio                | 1        | 1.61%   |
| OEM                  | 1        | 1.61%   |
| Mi                   | 1        | 1.61%   |
| Idek Iiyama          | 1        | 1.61%   |
| HannStar             | 1        | 1.61%   |
| Fujitsu Siemens      | 1        | 1.61%   |
| CHD                  | 1        | 1.61%   |
| Ancor Communications | 1        | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2        | 3.03%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1        | 1.52%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1        | 1.52%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1        | 1.52%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1        | 1.52%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1        | 1.52%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch      | 1        | 1.52%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch    | 1        | 1.52%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1        | 1.52%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1        | 1.52%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch      | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 1.52%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1        | 1.52%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 1.52%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 1.52%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1        | 1.52%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1        | 1.52%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                   | 1        | 1.52%   |
| LG Electronics LCD Monitor W1952 2806x900                              | 1        | 1.52%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1        | 1.52%   |
| Lenovo V20-10 LEN65DC 1600x900 430x240mm 19.4-inch                     | 1        | 1.52%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch               | 1        | 1.52%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                   | 1        | 1.52%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                   | 1        | 1.52%   |
| Idek Iiyama LCD Monitor PL3270Q 5120x1440                              | 1        | 1.52%   |
| Idek Iiyama LCD Monitor PL3270Q                                        | 1        | 1.52%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 410x260mm 19.1-inch             | 1        | 1.52%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 1.52%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch           | 1        | 1.52%   |
| HannStar LCD Monitor HSD2469 1680x1050 470x300mm 22.0-inch             | 1        | 1.52%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                   | 1        | 1.52%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1        | 1.52%   |
| Goldstar LG ULTRAWIDE GSM76FA 2560x1080 800x340mm 34.2-inch            | 1        | 1.52%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 1        | 1.52%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 1.52%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.52%   |
| Goldstar E2241 GSM5818 1920x1080 480x270mm 21.7-inch                   | 1        | 1.52%   |
| Fujitsu Siemens P24-9 TE FUS08B8 1920x1080 530x300mm 24.0-inch         | 1        | 1.52%   |
| Dell S2417DG DELA0E7 2560x1440 530x300mm 24.0-inch                     | 1        | 1.52%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch                      | 1        | 1.52%   |
| Dell P2317H DEL40F2 1920x1080 510x290mm 23.1-inch                      | 1        | 1.52%   |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 1.52%   |
| Dell P1917S DELD092 1280x1024 380x300mm 19.1-inch                      | 1        | 1.52%   |
| Dell LCD Monitor U3818DW 3840x1600                                     | 1        | 1.52%   |
| Dell LCD Monitor P2419H 1920x1080                                      | 1        | 1.52%   |
| Dell LCD Monitor 1908FP 3200x1080                                      | 1        | 1.52%   |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                      | 1        | 1.52%   |
| CHD M27 CHD0270 1920x1080 530x290mm 23.8-inch                          | 1        | 1.52%   |
| BenQ PD3200Q BNQ8026 2560x1440 710x400mm 32.1-inch                     | 1        | 1.52%   |
| BenQ LCD Monitor DL2215                                                | 1        | 1.52%   |
| BenQ LCD BNQ8024 2560x1440 600x340mm 27.2-inch                         | 1        | 1.52%   |
| BenQ GW2283 BNQ78E9 1920x1080 480x270mm 21.7-inch                      | 1        | 1.52%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                      | 1        | 1.52%   |
| ASUSTek Computer VG259 AUS25A6 1920x1080 540x300mm 24.3-inch           | 1        | 1.52%   |
| ASUSTek Computer VC279 AUS27C4 1920x1080 600x340mm 27.2-inch           | 1        | 1.52%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 1        | 1.52%   |
| AOC 2470W AOC2470 1920x1080 520x290mm 23.4-inch                        | 1        | 1.52%   |
| AOC 2070W AOC2070 1600x900 430x240mm 19.4-inch                         | 1        | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 43.08%  |
| 2560x1440 (QHD)    | 7        | 10.77%  |
| 3840x2160 (4K)     | 6        | 9.23%   |
| 2560x1080          | 3        | 4.62%   |
| 1600x900 (HD+)     | 3        | 4.62%   |
| 1280x1024 (SXGA)   | 3        | 4.62%   |
| Unknown            | 3        | 4.62%   |
| 1680x1050 (WSXGA+) | 2        | 3.08%   |
| 1440x900 (WXGA+)   | 2        | 3.08%   |
| 1360x768           | 2        | 3.08%   |
| 5120x1440          | 1        | 1.54%   |
| 3840x1600          | 1        | 1.54%   |
| 3200x1080          | 1        | 1.54%   |
| 2806x900           | 1        | 1.54%   |
| 1920x540           | 1        | 1.54%   |
| 1920x1200 (WUXGA)  | 1        | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 16.13%  |
| 24      | 9        | 14.52%  |
| 21      | 9        | 14.52%  |
| Unknown | 9        | 14.52%  |
| 23      | 6        | 9.68%   |
| 19      | 6        | 9.68%   |
| 54      | 2        | 3.23%   |
| 31      | 2        | 3.23%   |
| 22      | 2        | 3.23%   |
| 65      | 1        | 1.61%   |
| 40      | 1        | 1.61%   |
| 34      | 1        | 1.61%   |
| 32      | 1        | 1.61%   |
| 28      | 1        | 1.61%   |
| 17      | 1        | 1.61%   |
| 16      | 1        | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 36.07%  |
| 401-500     | 15       | 24.59%  |
| Unknown     | 9        | 14.75%  |
| 601-700     | 6        | 9.84%   |
| 1001-1500   | 3        | 4.92%   |
| 701-800     | 2        | 3.28%   |
| 301-350     | 2        | 3.28%   |
| 801-900     | 1        | 1.64%   |
| 351-400     | 1        | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 41       | 69.49%  |
| Unknown | 7        | 11.86%  |
| 16/10   | 5        | 8.47%   |
| 5/4     | 2        | 3.39%   |
| 21/9    | 2        | 3.39%   |
| 6/5     | 1        | 1.69%   |
| 32/9    | 1        | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 37.7%   |
| 301-350        | 10       | 16.39%  |
| Unknown        | 9        | 14.75%  |
| 151-200        | 6        | 9.84%   |
| 351-500        | 4        | 6.56%   |
| More than 1000 | 3        | 4.92%   |
| 251-300        | 3        | 4.92%   |
| 141-150        | 1        | 1.64%   |
| 131-140        | 1        | 1.64%   |
| 501-1000       | 1        | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 34       | 53.97%  |
| 101-120 | 13       | 20.63%  |
| Unknown | 9        | 14.29%  |
| 121-160 | 4        | 6.35%   |
| 1-50    | 2        | 3.17%   |
| 161-240 | 1        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 70.49%  |
| 2     | 11       | 18.03%  |
| 0     | 7        | 11.48%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 39.74%  |
| Realtek Semiconductor           | 27       | 34.62%  |
| Qualcomm Atheros                | 7        | 8.97%   |
| Broadcom                        | 5        | 6.41%   |
| TP-Link                         | 2        | 2.56%   |
| Ralink                          | 1        | 1.28%   |
| Qualcomm Atheros Communications | 1        | 1.28%   |
| Qualcomm                        | 1        | 1.28%   |
| Nvidia                          | 1        | 1.28%   |
| Microchip Technology            | 1        | 1.28%   |
| Aquantia                        | 1        | 1.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 22.99%  |
| Intel I211 Gigabit Network Connection                             | 9        | 10.34%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 5.75%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 4.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.3%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 2.3%    |
| TP-Link TP-LINK Wireless USB Adapter                              | 1        | 1.15%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.15%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.15%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.15%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 1.15%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.15%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 1.15%   |
| Nvidia MCP73 Ethernet                                             | 1        | 1.15%   |
| Microchip HTC Hub Controller                                      | 1        | 1.15%   |
| Intel Wireless-AC 9260                                            | 1        | 1.15%   |
| Intel Wireless 7265                                               | 1        | 1.15%   |
| Intel Wireless 3165                                               | 1        | 1.15%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.15%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.15%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.15%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.15%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.15%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.15%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.15%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.15%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 1.15%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.15%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 47.62%  |
| Qualcomm Atheros                | 4        | 19.05%  |
| Realtek Semiconductor           | 3        | 14.29%  |
| TP-Link                         | 2        | 9.52%   |
| Ralink                          | 1        | 4.76%   |
| Qualcomm Atheros Communications | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 4        | 19.05%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3        | 14.29%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3        | 14.29%  |
| TP-Link TP-LINK Wireless USB Adapter                           | 1        | 4.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 4.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 4.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 4.76%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 4.76%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 4.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 4.76%   |
| Intel Wireless-AC 9260                                         | 1        | 4.76%   |
| Intel Wireless 7265                                            | 1        | 4.76%   |
| Intel Wireless 3165                                            | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 27       | 42.19%  |
| Realtek Semiconductor | 26       | 40.63%  |
| Broadcom              | 5        | 7.81%   |
| Qualcomm Atheros      | 3        | 4.69%   |
| Qualcomm              | 1        | 1.56%   |
| Nvidia                | 1        | 1.56%   |
| Aquantia              | 1        | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 30.77%  |
| Intel I211 Gigabit Network Connection                             | 9        | 13.85%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 7.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 3.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.54%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.54%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 1.54%   |
| Nvidia MCP73 Ethernet                                             | 1        | 1.54%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1        | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.54%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.54%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.54%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.54%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.54%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 1.54%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 73.17%  |
| WiFi     | 21       | 25.61%  |
| Modem    | 1        | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 81.69%  |
| WiFi     | 13       | 18.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 66.67%  |
| 2     | 17       | 28.33%  |
| 3     | 3        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 98.33%  |
| Yes  | 1        | 1.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 60%     |
| Cambridge Silicon Radio  | 2        | 13.33%  |
| Broadcom                 | 2        | 13.33%  |
| HTC (High Tech Computer) | 1        | 6.67%   |
| ASUSTek Computer         | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 20%     |
| Intel AX200 Bluetooth                                                | 3        | 20%     |
| Intel Bluetooth wireless interface                                   | 2        | 13.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 13.33%  |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 13.33%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 6.67%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 6.67%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Nvidia               | 34       | 30.91%  |
| Intel                | 31       | 28.18%  |
| AMD                  | 31       | 28.18%  |
| Logitech             | 3        | 2.73%   |
| VIA Technologies     | 2        | 1.82%   |
| SteelSeries ApS      | 2        | 1.82%   |
| C-Media Electronics  | 2        | 1.82%   |
| Nam Tai E&E Products | 1        | 0.91%   |
| JMTek                | 1        | 0.91%   |
| Focusrite-Novation   | 1        | 0.91%   |
| Creative Technology  | 1        | 0.91%   |
| Creative Labs        | 1        | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 9        | 7.2%    |
| AMD Starship/Matisse HD Audio Controller                                              | 8        | 6.4%    |
| Nvidia GP104 High Definition Audio Controller                                         | 6        | 4.8%    |
| Nvidia GP107GL High Definition Audio Controller                                       | 5        | 4%      |
| Nvidia GK107 HDMI Audio Controller                                                    | 5        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 5        | 4%      |
| Nvidia GP108 High Definition Audio Controller                                         | 4        | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                            | 4        | 3.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 4        | 3.2%    |
| AMD FCH Azalia Controller                                                             | 4        | 3.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 4        | 3.2%    |
| Nvidia GM206 High Definition Audio Controller                                         | 3        | 2.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 3        | 2.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 3        | 2.4%    |
| Intel 200 Series PCH HD Audio                                                         | 3        | 2.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 3        | 2.4%    |
| AMD Kabini HDMI/DP Audio                                                              | 3        | 2.4%    |
| AMD Family 17h/19h HD Audio Controller                                                | 3        | 2.4%    |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2        | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                                         | 2        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 2        | 1.6%    |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 2        | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 2        | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 2        | 1.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                    | 2        | 1.6%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]               | 2        | 1.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                          | 2        | 1.6%    |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller           | 1        | 0.8%    |
| VIA Technologies USB Audio Device                                                     | 1        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                                         | 1        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                         | 1        | 0.8%    |
| Nvidia TU104 HD Audio Controller                                                      | 1        | 0.8%    |
| Nvidia MCP73 High Definition Audio                                                    | 1        | 0.8%    |
| Nvidia GF116 High Definition Audio Controller                                         | 1        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                         | 1        | 0.8%    |
| Nvidia GF100 High Definition Audio Controller                                         | 1        | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                                         | 1        | 0.8%    |
| Nam Tai E&E Products Sony SingStar USBMIC                                             | 1        | 0.8%    |
| Logitech Logitech USB Microphone                                                      | 1        | 0.8%    |
| Logitech HD Webcam C510                                                               | 1        | 0.8%    |
| Logitech G935 Gaming Headset G935 Gaming Headset G935 Gaming Headset                  | 1        | 0.8%    |
| JMTek Sharkoon 7.1 Sound Extension                                                    | 1        | 0.8%    |
| Intel Sunrise Point-LP HD Audio                                                       | 1        | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                           | 1        | 0.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller                        | 1        | 0.8%    |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                           | 1        | 0.8%    |
| Creative Technology Sound Blaster Omni Surround 5.1                                   | 1        | 0.8%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                         | 1        | 0.8%    |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                                | 1        | 0.8%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                         | 1        | 0.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                          | 1        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                   | 1        | 0.8%    |
| AMD Navi 10 HDMI Audio                                                                | 1        | 0.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                      | 1        | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                | 1        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 12       | 17.39%  |
| G.Skill             | 12       | 17.39%  |
| Corsair             | 9        | 13.04%  |
| SK Hynix            | 7        | 10.14%  |
| Samsung Electronics | 7        | 10.14%  |
| Unknown             | 6        | 8.7%    |
| Crucial             | 6        | 8.7%    |
| Nanya Technology    | 2        | 2.9%    |
| A-DATA Technology   | 2        | 2.9%    |
| Undefined-00BA      | 1        | 1.45%   |
| TIMETEC             | 1        | 1.45%   |
| S                   | 1        | 1.45%   |
| Micron Technology   | 1        | 1.45%   |
| Kingmax             | 1        | 1.45%   |
| Unknown             | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s        | 3        | 4.23%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s      | 3        | 4.23%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 1.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 1.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 1.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                  | 1        | 1.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 1        | 1.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 1.41%   |
| Undefined-00BA RAM Module 4GB DIMM DDR3 1333MT/s           | 1        | 1.41%   |
| TIMETEC RAM SD4-2666 16GB SODIMM DDR4 2666MT/s             | 1        | 1.41%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| SK Hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1        | 1.41%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s       | 1        | 1.41%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 1.41%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1        | 1.41%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1600MT/s            | 1        | 1.41%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s        | 1        | 1.41%   |
| Samsung RAM M391A4G43MB1-CTD 32GB DIMM DDR4 3200MT/s       | 1        | 1.41%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s        | 1        | 1.41%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.41%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.41%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s       | 1        | 1.41%   |
| S RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 1.41%   |
| Nanya RAM NT2GT72U8PD0BY-3C 2GB DIMM DDR2 667MT/s          | 1        | 1.41%   |
| Nanya RAM M2F4G64CB8HB5N-CG 4GB DIMM DDR3 1333MT/s         | 1        | 1.41%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s        | 1        | 1.41%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 1.41%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 1.41%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 2400MT/s       | 1        | 1.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s          | 1        | 1.41%   |
| Kingston RAM KHX2666C13/8GX 8GB DIMM DDR4 2400MT/s         | 1        | 1.41%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 2400MT/s        | 1        | 1.41%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2133MT/s        | 1        | 1.41%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 1        | 1.41%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 2400MT/s      | 1        | 1.41%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Kingston RAM 99P5474-013.A 4096MB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s       | 1        | 1.41%   |
| Kingmax RAM FLFF65F-C8KL9 4GB DIMM DDR3 1333MT/s           | 1        | 1.41%   |
| G.Skill RAM F4-4000C18-8GTZ 8GB DIMM DDR4 3333MT/s         | 1        | 1.41%   |
| G.Skill RAM F4-3600C17-16GTZSW 16GB DIMM DDR4 3600MT/s     | 1        | 1.41%   |
| G.Skill RAM F4-3600C16-8GTZ 8GB DIMM DDR4 2133MT/s         | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s        | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s       | 1        | 1.41%   |
| G.Skill RAM F4-2400C16-16GFT 16GB DIMM DDR4 2400MT/s       | 1        | 1.41%   |
| G.Skill RAM F4-2400C15-16GFT 16GB DIMM DDR4 2400MT/s       | 1        | 1.41%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1400MT/s          | 1        | 1.41%   |
| G.Skill RAM F3-1600C9-4GRSL 4GB SODIMM DDR3 1600MT/s       | 1        | 1.41%   |
| G.Skill RAM F3-10666CL9-8GBXL 8GB DIMM DDR3 1333MT/s       | 1        | 1.41%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 2400MT/s       | 1        | 1.41%   |
| Crucial RAM CT8G4DFS824A.C8FBD1 8GB DIMM DDR4 2400MT/s     | 1        | 1.41%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Crucial RAM BLS8G4D26BFSE.16FBR2 8GB DIMM DDR4 2666MT/s    | 1        | 1.41%   |
| Crucial RAM BLS8G4D240FSA.16FARG 8192MB DIMM DDR4 2400MT/s | 1        | 1.41%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Crucial RAM BL8G30C15U4R.M8FE1 8GB DIMM DDR4 2666MT/s      | 1        | 1.41%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s     | 1        | 1.41%   |
| Corsair RAM CMSX16GX4M2A2400C16 8GB SODIMM DDR4 2400MT/s   | 1        | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 33       | 55%     |
| DDR3    | 22       | 36.67%  |
| Unknown | 3        | 5%      |
| DDR2    | 2        | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 55       | 91.67%  |
| SODIMM | 5        | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 29       | 47.54%  |
| 4096  | 15       | 24.59%  |
| 16384 | 9        | 14.75%  |
| 2048  | 6        | 9.84%   |
| 32768 | 2        | 3.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 14       | 21.21%  |
| 3200  | 11       | 16.67%  |
| 2400  | 9        | 13.64%  |
| 1333  | 9        | 13.64%  |
| 2667  | 4        | 6.06%   |
| 2666  | 4        | 6.06%   |
| 2133  | 4        | 6.06%   |
| 3600  | 2        | 3.03%   |
| 800   | 2        | 3.03%   |
| 3333  | 1        | 1.52%   |
| 3066  | 1        | 1.52%   |
| 1867  | 1        | 1.52%   |
| 1400  | 1        | 1.52%   |
| 1067  | 1        | 1.52%   |
| 1066  | 1        | 1.52%   |
| 667   | 1        | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP HP Laser 107w | 1        | 100%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 3        | 50%     |
| Xiongmai            | 1        | 16.67%  |
| Trust               | 1        | 16.67%  |
| Chicony Electronics | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Xiongmai web camera                   | 1        | 16.67%  |
| Trust Trust USB Camera                | 1        | 16.67%  |
| Logitech Webcam C310                  | 1        | 16.67%  |
| Logitech HD Pro Webcam C920           | 1        | 16.67%  |
| Logitech C920 HD Pro Webcam           | 1        | 16.67%  |
| Chicony HP High Definition 1MP Webcam | 1        | 16.67%  |

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
| 1     | 31       | 51.67%  |
| 0     | 15       | 25%     |
| 2     | 11       | 18.33%  |
| 3     | 3        | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 25       | 41.67%  |
| Bluetooth                | 11       | 18.33%  |
| Net/wireless             | 9        | 15%     |
| Firewire controller      | 7        | 11.67%  |
| Sound                    | 3        | 5%      |
| Card reader              | 3        | 5%      |
| Net/ethernet             | 1        | 1.67%   |
| Modem                    | 1        | 1.67%   |

