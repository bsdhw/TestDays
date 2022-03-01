helloSystem 0.7.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor   | Model                    | Probe                                                     | Date         |
|----------|--------------------------|-----------------------------------------------------------|--------------|
| Gigabyte | B450M S2H                | [78f79fab6f](https://bsd-hardware.info/?probe=78f79fab6f) | Feb 28, 2022 |
| Dell     | 0KV62T A00               | [0541a207c7](https://bsd-hardware.info/?probe=0541a207c7) | Feb 28, 2022 |
| HP       | 1905                     | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| ASRock   | TRX40 Taichi             | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Intel    | H81                      | [04d2739bdc](https://bsd-hardware.info/?probe=04d2739bdc) | Feb 25, 2022 |
| Intel    | DCP847SKE G80890-107     | [f9d33f1ab1](https://bsd-hardware.info/?probe=f9d33f1ab1) | Feb 23, 2022 |
| Medion   | H61H2-LM3                | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| ASRock   | H81M-DG4                 | [e20db6ad83](https://bsd-hardware.info/?probe=e20db6ad83) | Feb 23, 2022 |
| HP       | 1998                     | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| Dell     | 0VD5HY A07               | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| ASUSTek  | CROSSHAIR VI HERO        | [1e6ff84e5d](https://bsd-hardware.info/?probe=1e6ff84e5d) | Feb 21, 2022 |
| Gigabyte | P41T-D3                  | [e5417931a7](https://bsd-hardware.info/?probe=e5417931a7) | Feb 18, 2022 |
| ASRock   | B460M Pro4               | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| ASUSTek  | PRIME Z390-P             | [3a72227408](https://bsd-hardware.info/?probe=3a72227408) | Feb 16, 2022 |
| Gigabyte | C246M-WU4-CF             | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| MSI      | B450 GAMING PLUS MAX     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| ASRock   | H61M/U3S3                | [257e13f206](https://bsd-hardware.info/?probe=257e13f206) | Feb 12, 2022 |
| ASUSTek  | PRIME Z390-P             | [abf34bbc7e](https://bsd-hardware.info/?probe=abf34bbc7e) | Feb 12, 2022 |
| ASRock   | H61M/U3S3                | [34dac4c0cd](https://bsd-hardware.info/?probe=34dac4c0cd) | Feb 11, 2022 |
| MSI      | B450 GAMING PLUS MAX     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| Intel    | X58                      | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| ASUSTek  | PRIME Z390-P             | [b1931633be](https://bsd-hardware.info/?probe=b1931633be) | Feb 09, 2022 |
| ASUSTek  | PRIME Z390-P             | [f9c1e787a9](https://bsd-hardware.info/?probe=f9c1e787a9) | Feb 09, 2022 |
| MSI      | B75A-G43                 | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| ASUSTek  | P6-P8H61E                | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| ASRock   | H81M-VG4 R2.0            | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| Apple    | Mac-F221BEC8             | [e5043f0af4](https://bsd-hardware.info/?probe=e5043f0af4) | Feb 04, 2022 |
| Pegatron | NARRA5                   | [64d4fb9b97](https://bsd-hardware.info/?probe=64d4fb9b97) | Feb 02, 2022 |
| Gigabyte | Z390 GAMING X-CF         | [ee05643521](https://bsd-hardware.info/?probe=ee05643521) | Feb 01, 2022 |
| ASUSTek  | P5P43TD PRO              | [5999e0ebfb](https://bsd-hardware.info/?probe=5999e0ebfb) | Jan 31, 2022 |
| Intel    | H81                      | [c2f3025900](https://bsd-hardware.info/?probe=c2f3025900) | Jan 31, 2022 |
| Pegatron | 2A99h                    | [e34b6118a2](https://bsd-hardware.info/?probe=e34b6118a2) | Jan 30, 2022 |
| Fujitsu  | D3161-A1 S26361-D3161-A1 | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Intel    | DH77EB AAG39073-400      | [bfe6ef301b](https://bsd-hardware.info/?probe=bfe6ef301b) | Jan 29, 2022 |
| ASUSTek  | P5GC-MX                  | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Unknown  | Unknown                  | [a9d799ca71](https://bsd-hardware.info/?probe=a9d799ca71) | Jan 27, 2022 |
| ASUSTek  | P5B SE                   | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Fujitsu  | D3161-A1 S26361-D3161-A1 | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek  | P5B SE                   | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock   | B460M Pro4               | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| ASRock   | A300M-STX                | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASUSTek  | BM6835_BM6635_BP6335     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek  | P8H61-M LX3 PLUS R2.0    | [df08e2e8f0](https://bsd-hardware.info/?probe=df08e2e8f0) | Jan 24, 2022 |
| ASUSTek  | P7H55-M                  | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| HP       | 1998                     | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING  | [670e41ed41](https://bsd-hardware.info/?probe=670e41ed41) | Jan 21, 2022 |
| MSI      | PRO Z690-A WIFI DDR4     | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASUSTek  | Maximus VIII HERO        | [a780a7bab2](https://bsd-hardware.info/?probe=a780a7bab2) | Jan 18, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS     | [9cd2758a5f](https://bsd-hardware.info/?probe=9cd2758a5f) | Jan 18, 2022 |
| ASUSTek  | PRIME X570-P             | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Gigabyte | B365 HD3                 | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| Dell     | 0XCR8D A03               | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| ASUSTek  | ROG STRIX Z390-E GAMING  | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| Gigabyte | Z77N-WIFI                | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| ASUSTek  | P8Z68-M PRO              | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| HP       | 8169                     | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| ASUSTek  | GA35DX                   | [eccb947ae4](https://bsd-hardware.info/?probe=eccb947ae4) | Jan 05, 2022 |
| Unknown  | G31T-M7                  | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS     | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| ASRock   | X570 Phantom Gaming 4    | [15211db056](https://bsd-hardware.info/?probe=15211db056) | Dec 28, 2021 |
| Dell     | 0200DY A01               | [fb37dcbb93](https://bsd-hardware.info/?probe=fb37dcbb93) | Dec 28, 2021 |
| Pegatron | IPM41-D3                 | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Dell     | 0H9KW5 A00               | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Gigabyte | 970A-DS3P                | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek  | PRIME B350M-A            | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| ASUSTek  | Z170-P                   | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS     | [8ac48ba9c3](https://bsd-hardware.info/?probe=8ac48ba9c3) | Dec 23, 2021 |
| Gigabyte | E3000N                   | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| ASUSTek  | ROG STRIX Z370-E GAMING  | [936afa4de3](https://bsd-hardware.info/?probe=936afa4de3) | Dec 21, 2021 |
| ASUSTek  | PRIME A320M-K            | [42599b554e](https://bsd-hardware.info/?probe=42599b554e) | Dec 21, 2021 |
| Gigabyte | X58A-UD5                 | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING  | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| Gigabyte | H170-D3HP-CF             | [a490614a39](https://bsd-hardware.info/?probe=a490614a39) | Dec 21, 2021 |
| ASRock   | H110M-DGS                | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| ASUSTek  | P5VD2-VM                 | [7e8f3cf783](https://bsd-hardware.info/?probe=7e8f3cf783) | Dec 20, 2021 |
| ASUSTek  | Q170M-C                  | [7f9e35a31c](https://bsd-hardware.info/?probe=7f9e35a31c) | Dec 20, 2021 |
| Dell     | 0TDG4V A00               | [3ce808c135](https://bsd-hardware.info/?probe=3ce808c135) | Dec 20, 2021 |
| Dell     | 0TDG4V A00               | [5292ad64ef](https://bsd-hardware.info/?probe=5292ad64ef) | Dec 20, 2021 |
| ASUSTek  | P8Z77-V LX               | [3c71a8ba4e](https://bsd-hardware.info/?probe=3c71a8ba4e) | Dec 20, 2021 |
| MSI      | X370 SLI PLUS            | [73853f1fc2](https://bsd-hardware.info/?probe=73853f1fc2) | Dec 19, 2021 |
| Quanta   | 2AC7 011                 | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| Gigabyte | Z77X-UD3H                | [759ce775c9](https://bsd-hardware.info/?probe=759ce775c9) | Dec 15, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS     | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| HP       | 843B                     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP       | 843B                     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| ASUSTek  | PRIME B450M-A            | [aea4a33dee](https://bsd-hardware.info/?probe=aea4a33dee) | Dec 13, 2021 |
| Gigabyte | H270M-DS3H-CF            | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Acer     | RevoOne RL85             | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [b900b364f6](https://bsd-hardware.info/?probe=b900b364f6) | Dec 10, 2021 |
| Dell     | 0YF8P5 A00               | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell     | 0YF8P5 A00               | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte | H270M-DS3H-CF            | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte | H270M-DS3H-CF            | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Gigabyte | X570 AORUS ELITE         | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| HP       | 843B                     | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| Intel    | DG41TY AAE47335-300      | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP       | 843B                     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP       | 843B                     | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| HP       | 1825                     | [32f07d2ba3](https://bsd-hardware.info/?probe=32f07d2ba3) | Nov 28, 2021 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| ASRock   | 775i945GZ                | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| HP       | 844C                     | [fb7d8eaf5d](https://bsd-hardware.info/?probe=fb7d8eaf5d) | Nov 06, 2021 |
| Unknown  | X79                      | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| HP       | 843B                     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| Acer     | Aspire TC-780            | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 81       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 80       | 98.77%  |
| GNOME        | 1        | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 81       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 81       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 79       | 97.53%  |
| de_DE | 1        | 1.23%   |
| C     | 1        | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 78       | 96.3%   |
| BIOS | 3        | 3.7%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 51       | 61.45%  |
| Zfs    | 32       | 38.55%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 78       | 96.3%   |
| MBR  | 3        | 3.7%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 26       | 32.1%   |
| Gigabyte Technology | 14       | 17.28%  |
| ASRock              | 9        | 11.11%  |
| Dell                | 7        | 8.64%   |
| Hewlett-Packard     | 6        | 7.41%   |
| Intel               | 5        | 6.17%   |
| MSI                 | 4        | 4.94%   |
| Pegatron            | 3        | 3.7%    |
| Unknown             | 2        | 2.47%   |
| Quanta              | 1        | 1.23%   |
| Medion              | 1        | 1.23%   |
| Fujitsu             | 1        | 1.23%   |
| Apple               | 1        | 1.23%   |
| Acer                | 1        | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS TUF GAMING X570-PLUS           | 2        | 2.47%   |
| Unknown                             | 2        | 2.47%   |
| Quanta 120-1135                     | 1        | 1.23%   |
| Pegatron IPM41-D3                   | 1        | 1.23%   |
| Pegatron Compaq 505B Microtower PC  | 1        | 1.23%   |
| Pegatron AY627AA-ABA a4313w         | 1        | 1.23%   |
| MSI MS-7D25                         | 1        | 1.23%   |
| MSI MS-7B86                         | 1        | 1.23%   |
| MSI MS-7A33                         | 1        | 1.23%   |
| MSI MS-7758                         | 1        | 1.23%   |
| Medion H61H2-LM3                    | 1        | 1.23%   |
| Intel X58                           | 1        | 1.23%   |
| Intel H81                           | 1        | 1.23%   |
| Intel DH77EB AAG39073-400           | 1        | 1.23%   |
| Intel DG41TY AAE47335-300           | 1        | 1.23%   |
| Intel DCP847SKE G80890-107          | 1        | 1.23%   |
| HP Z230 Tower Workstation           | 1        | 1.23%   |
| HP ProDesk 600 G2 DM                | 1        | 1.23%   |
| HP Pavilion Gaming Desktop 690-00xx | 1        | 1.23%   |
| HP EliteDesk 800 G1 DM              | 1        | 1.23%   |
| HP EliteDesk 700 G1 SFF             | 1        | 1.23%   |
| HP 844C                             | 1        | 1.23%   |
| Gigabyte Z77X-UD3H                  | 1        | 1.23%   |
| Gigabyte Z77N-WIFI                  | 1        | 1.23%   |
| Gigabyte Z390 GAMING X              | 1        | 1.23%   |
| Gigabyte X58A-UD5                   | 1        | 1.23%   |
| Gigabyte X570 AORUS ELITE           | 1        | 1.23%   |
| Gigabyte P41T-D3                    | 1        | 1.23%   |
| Gigabyte H270M-DS3H                 | 1        | 1.23%   |
| Gigabyte H170-D3HP                  | 1        | 1.23%   |
| Gigabyte E3000N                     | 1        | 1.23%   |
| Gigabyte C246M-WU4                  | 1        | 1.23%   |
| Gigabyte B450M S2H                  | 1        | 1.23%   |
| Gigabyte B450 I AORUS PRO WIFI      | 1        | 1.23%   |
| Gigabyte B365 HD3                   | 1        | 1.23%   |
| Gigabyte 970A-DS3P                  | 1        | 1.23%   |
| Fujitsu ESPRIMO E710                | 1        | 1.23%   |
| Dell Vostro 3667                    | 1        | 1.23%   |
| Dell Precision T1700                | 1        | 1.23%   |
| Dell PowerEdge T20                  | 1        | 1.23%   |
| Dell OptiPlex 9020                  | 1        | 1.23%   |
| Dell OptiPlex 9010                  | 1        | 1.23%   |
| Dell OptiPlex 780                   | 1        | 1.23%   |
| Dell Inspiron 3891                  | 1        | 1.23%   |
| ASUS Z170-P                         | 1        | 1.23%   |
| ASUS ROG STRIX Z390-E GAMING        | 1        | 1.23%   |
| ASUS ROG STRIX Z370-E GAMING        | 1        | 1.23%   |
| ASUS ROG STRIX X570-E GAMING        | 1        | 1.23%   |
| ASUS ROG Strix GA35DX_G35DX         | 1        | 1.23%   |
| ASUS ROG STRIX B450-F GAMING        | 1        | 1.23%   |
| ASUS Q170M-C                        | 1        | 1.23%   |
| ASUS PRIME Z390-P                   | 1        | 1.23%   |
| ASUS PRIME X570-P                   | 1        | 1.23%   |
| ASUS PRIME B450M-A                  | 1        | 1.23%   |
| ASUS PRIME B350M-A                  | 1        | 1.23%   |
| ASUS PRIME A320M-K                  | 1        | 1.23%   |
| ASUS P8Z77-V LX                     | 1        | 1.23%   |
| ASUS P8Z68-M PRO                    | 1        | 1.23%   |
| ASUS P8H61-M LX3 PLUS R2.0          | 1        | 1.23%   |
| ASUS P7H55-M                        | 1        | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 5        | 6.17%   |
| ASUS PRIME           | 5        | 6.17%   |
| Dell OptiPlex        | 3        | 3.7%    |
| HP EliteDesk         | 2        | 2.47%   |
| ASUS TUF             | 2        | 2.47%   |
| Unknown              | 2        | 2.47%   |
| Quanta 120-1135      | 1        | 1.23%   |
| Pegatron IPM41-D3    | 1        | 1.23%   |
| Pegatron Compaq      | 1        | 1.23%   |
| Pegatron AY627AA-ABA | 1        | 1.23%   |
| MSI MS-7D25          | 1        | 1.23%   |
| MSI MS-7B86          | 1        | 1.23%   |
| MSI MS-7A33          | 1        | 1.23%   |
| MSI MS-7758          | 1        | 1.23%   |
| Medion H61H2-LM3     | 1        | 1.23%   |
| Intel X58            | 1        | 1.23%   |
| Intel H81            | 1        | 1.23%   |
| Intel DH77EB         | 1        | 1.23%   |
| Intel DG41TY         | 1        | 1.23%   |
| Intel DCP847SKE      | 1        | 1.23%   |
| HP Z230              | 1        | 1.23%   |
| HP ProDesk           | 1        | 1.23%   |
| HP Pavilion          | 1        | 1.23%   |
| HP 844C              | 1        | 1.23%   |
| Gigabyte Z77X-UD3H   | 1        | 1.23%   |
| Gigabyte Z77N-WIFI   | 1        | 1.23%   |
| Gigabyte Z390        | 1        | 1.23%   |
| Gigabyte X58A-UD5    | 1        | 1.23%   |
| Gigabyte X570        | 1        | 1.23%   |
| Gigabyte P41T-D3     | 1        | 1.23%   |
| Gigabyte H270M-DS3H  | 1        | 1.23%   |
| Gigabyte H170-D3HP   | 1        | 1.23%   |
| Gigabyte E3000N      | 1        | 1.23%   |
| Gigabyte C246M-WU4   | 1        | 1.23%   |
| Gigabyte B450M       | 1        | 1.23%   |
| Gigabyte B450        | 1        | 1.23%   |
| Gigabyte B365        | 1        | 1.23%   |
| Gigabyte 970A-DS3P   | 1        | 1.23%   |
| Fujitsu ESPRIMO      | 1        | 1.23%   |
| Dell Vostro          | 1        | 1.23%   |
| Dell Precision       | 1        | 1.23%   |
| Dell PowerEdge       | 1        | 1.23%   |
| Dell Inspiron        | 1        | 1.23%   |
| ASUS Z170-P          | 1        | 1.23%   |
| ASUS Q170M-C         | 1        | 1.23%   |
| ASUS P8Z77-V         | 1        | 1.23%   |
| ASUS P8Z68-M         | 1        | 1.23%   |
| ASUS P8H61-M         | 1        | 1.23%   |
| ASUS P7H55-M         | 1        | 1.23%   |
| ASUS P6-P8H61E       | 1        | 1.23%   |
| ASUS P5VD2-VM        | 1        | 1.23%   |
| ASUS P5P43TD         | 1        | 1.23%   |
| ASUS P5GC-MX         | 1        | 1.23%   |
| ASUS P5B             | 1        | 1.23%   |
| ASUS Maximus         | 1        | 1.23%   |
| ASUS CROSSHAIR       | 1        | 1.23%   |
| ASUS BM6835          | 1        | 1.23%   |
| ASRock X570          | 1        | 1.23%   |
| ASRock TRX40         | 1        | 1.23%   |
| ASRock H81M-VG4      | 1        | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 13       | 16.05%  |
| 2021 | 12       | 14.81%  |
| 2013 | 8        | 9.88%   |
| 2017 | 7        | 8.64%   |
| 2018 | 6        | 7.41%   |
| 2012 | 6        | 7.41%   |
| 2014 | 5        | 6.17%   |
| 2010 | 5        | 6.17%   |
| 2020 | 4        | 4.94%   |
| 2016 | 3        | 3.7%    |
| 2015 | 3        | 3.7%    |
| 2009 | 3        | 3.7%    |
| 2007 | 3        | 3.7%    |
| 2011 | 2        | 2.47%   |
| 2008 | 1        | 1.23%   |

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
| No   | 81       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 22       | 27.16%  |
| 8.01-16.0   | 19       | 23.46%  |
| 32.01-64.0  | 17       | 20.99%  |
| 4.01-8.0    | 13       | 16.05%  |
| 64.01-256.0 | 4        | 4.94%   |
| 2.01-3.0    | 3        | 3.7%    |
| 24.01-32.0  | 2        | 2.47%   |
| 0.51-1.0    | 1        | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 30       | 36.59%  |
| 0.51-1.0  | 25       | 30.49%  |
| 1.01-2.0  | 22       | 26.83%  |
| 2.01-3.0  | 3        | 3.66%   |
| 3.01-4.0  | 1        | 1.22%   |
| 8.01-16.0 | 1        | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 35.8%   |
| 2      | 25       | 30.86%  |
| 4      | 8        | 9.88%   |
| 3      | 7        | 8.64%   |
| 0      | 5        | 6.17%   |
| 5      | 4        | 4.94%   |
| 6      | 2        | 2.47%   |
| 7      | 1        | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 66.67%  |
| Yes       | 27       | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 79       | 97.53%  |
| No        | 2        | 2.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 67.9%   |
| Yes       | 26       | 32.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 64.2%   |
| Yes       | 29       | 35.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 16.05%  |
| Russia      | 13       | 16.05%  |
| Hungary     | 6        | 7.41%   |
| Poland      | 5        | 6.17%   |
| Ukraine     | 4        | 4.94%   |
| Spain       | 4        | 4.94%   |
| Canada      | 4        | 4.94%   |
| Italy       | 3        | 3.7%    |
| India       | 3        | 3.7%    |
| Germany     | 3        | 3.7%    |
| Brazil      | 3        | 3.7%    |
| UK          | 2        | 2.47%   |
| Romania     | 2        | 2.47%   |
| France      | 2        | 2.47%   |
| China       | 2        | 2.47%   |
| Australia   | 2        | 2.47%   |
| Vietnam     | 1        | 1.23%   |
| Turkey      | 1        | 1.23%   |
| Taiwan      | 1        | 1.23%   |
| Philippines | 1        | 1.23%   |
| Peru        | 1        | 1.23%   |
| Norway      | 1        | 1.23%   |
| Kazakhstan  | 1        | 1.23%   |
| Greece      | 1        | 1.23%   |
| Finland     | 1        | 1.23%   |
| Denmark     | 1        | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Surgut                        | 2        | 2.41%   |
| St Petersburg                 | 2        | 2.41%   |
| Myrtle Beach                  | 2        | 2.41%   |
| Kharkiv                       | 2        | 2.41%   |
| Barnaul                       | 2        | 2.41%   |
| Yunlin                        | 1        | 1.2%    |
| Warsaw                        | 1        | 1.2%    |
| Tiruchi                       | 1        | 1.2%    |
| Szeged                        | 1        | 1.2%    |
| SzÃ©kesfehÃ©rvÃ¡r       | 1        | 1.2%    |
| Suceava                       | 1        | 1.2%    |
| Stavropol                     | 1        | 1.2%    |
| Spalice                       | 1        | 1.2%    |
| Sopron                        | 1        | 1.2%    |
| Smiths Falls                  | 1        | 1.2%    |
| Seville                       | 1        | 1.2%    |
| Santa Maria                   | 1        | 1.2%    |
| San SebastiÃ¡n de los Reyes | 1        | 1.2%    |
| Rio de Janeiro                | 1        | 1.2%    |
| Renfrew                       | 1        | 1.2%    |
| Pilica                        | 1        | 1.2%    |
| Pflugerville                  | 1        | 1.2%    |
| Penza                         | 1        | 1.2%    |
| Paso Robles                   | 1        | 1.2%    |
| Ourense                       | 1        | 1.2%    |
| Ormond Beach                  | 1        | 1.2%    |
| Novosibirsk                   | 1        | 1.2%    |
| New Delhi                     | 1        | 1.2%    |
| Myski                         | 1        | 1.2%    |
| Montreal                      | 1        | 1.2%    |
| Midlothian                    | 1        | 1.2%    |
| Melbourne                     | 1        | 1.2%    |
| Maglod                        | 1        | 1.2%    |
| Luton                         | 1        | 1.2%    |
| Lima                          | 1        | 1.2%    |
| Lehrte                        | 1        | 1.2%    |
| Kremenchug                    | 1        | 1.2%    |
| Kozani                        | 1        | 1.2%    |
| Kostroma                      | 1        | 1.2%    |
| Katowice                      | 1        | 1.2%    |
| Junction City                 | 1        | 1.2%    |
| Jelenia GÃ³ra               | 1        | 1.2%    |
| Imperial                      | 1        | 1.2%    |
| Helsinki                      | 1        | 1.2%    |
| Hayfork                       | 1        | 1.2%    |
| Hanoi                         | 1        | 1.2%    |
| Hangzhou                      | 1        | 1.2%    |
| Gyomro                        | 1        | 1.2%    |
| Guangzhou                     | 1        | 1.2%    |
| Greater Sudbury               | 1        | 1.2%    |
| Genille                       | 1        | 1.2%    |
| Front Royal                   | 1        | 1.2%    |
| Follonica                     | 1        | 1.2%    |
| Foligno                       | 1        | 1.2%    |
| Finmere                       | 1        | 1.2%    |
| Escondido                     | 1        | 1.2%    |
| Esbjerg                       | 1        | 1.2%    |
| Ernakulam                     | 1        | 1.2%    |
| Dreieich                      | 1        | 1.2%    |
| Curitiba                      | 1        | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 45     | 21.83%  |
| WDC                 | 24       | 35     | 16.9%   |
| Samsung Electronics | 24       | 29     | 16.9%   |
| Crucial             | 10       | 15     | 7.04%   |
| Toshiba             | 8        | 11     | 5.63%   |
| Kingston            | 8        | 9      | 5.63%   |
| SK Hynix            | 4        | 6      | 2.82%   |
| GOODRAM             | 4        | 4      | 2.82%   |
| A-DATA Technology   | 4        | 4      | 2.82%   |
| Phison              | 3        | 3      | 2.11%   |
| Intel               | 3        | 3      | 2.11%   |
| Hitachi             | 3        | 3      | 2.11%   |
| XPG                 | 2        | 2      | 1.41%   |
| OCZ                 | 2        | 2      | 1.41%   |
| HGST                | 2        | 2      | 1.41%   |
| Gigabyte Technology | 2        | 3      | 1.41%   |
| SanDisk             | 1        | 1      | 0.7%    |
| PNY                 | 1        | 1      | 0.7%    |
| PLEXTOR             | 1        | 1      | 0.7%    |
| Patriot             | 1        | 1      | 0.7%    |
| Mushkin             | 1        | 1      | 0.7%    |
| Lite-On             | 1        | 1      | 0.7%    |
| KingSpec            | 1        | 1      | 0.7%    |
| Apacer              | 1        | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB          | 3        | 1.83%   |
| Seagate ST2000DM008-2FR102 2TB          | 3        | 1.83%   |
| Seagate ST1000DM010-2EP102 1TB          | 3        | 1.83%   |
| Samsung SSD 850 EVO 250GB               | 3        | 1.83%   |
| Crucial CT500MX500SSD1 500GB            | 3        | 1.83%   |
| XPG GAMMIX S11 Pro 256GB                | 2        | 1.22%   |
| WDC WDS240G2G0A-00JH30 240GB            | 2        | 1.22%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2        | 1.22%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 2        | 1.22%   |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 2        | 1.22%   |
| Seagate ST3500413AS 500GB               | 2        | 1.22%   |
| Seagate ST3320418AS 320GB               | 2        | 1.22%   |
| Seagate ST1000DM003-1ER162 1TB          | 2        | 1.22%   |
| Samsung SSD 970 EVO Plus 1TB            | 2        | 1.22%   |
| Samsung SSD 970 EVO 250GB               | 2        | 1.22%   |
| Samsung SSD 860 EVO 500GB               | 2        | 1.22%   |
| Kingston SA400S37120G 120GB             | 2        | 1.22%   |
| GOODRAM SSDPR-CL100-120-G2 120GB        | 2        | 1.22%   |
| Crucial CT256MX100SSD1 256GB            | 2        | 1.22%   |
| Crucial CT120BX500SSD1 120GB            | 2        | 1.22%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1        | 0.61%   |
| WDC WDS500G2B0B-00YS70 500GB            | 1        | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1        | 0.61%   |
| WDC WDS250G1B0A-00H9H0 250GB            | 1        | 0.61%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1        | 0.61%   |
| WDC WDBA3V0010BNC-WRSN 1TB              | 1        | 0.61%   |
| WDC WD5000AZLX-00CL5A0 500GB            | 1        | 0.61%   |
| WDC WD5000AAKS-22A7B0 500GB             | 1        | 0.61%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1        | 0.61%   |
| WDC WD40EFRX-68N32N0 4TB                | 1        | 0.61%   |
| WDC WD4004FZWX-00GBGB0 4TB              | 1        | 0.61%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1        | 0.61%   |
| WDC WD3200AAJS-22B4A0 320GB             | 1        | 0.61%   |
| WDC WD3003FZEX-00Z4SA0 3TB              | 1        | 0.61%   |
| WDC WD2500AAKX-75U6AA0 250GB            | 1        | 0.61%   |
| WDC WD2500AAKX-073CA1 250GB             | 1        | 0.61%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1        | 0.61%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 0.61%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 1        | 0.61%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 0.61%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1        | 0.61%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1        | 0.61%   |
| WDC WD10EARS-003BB1 1TB                 | 1        | 0.61%   |
| Toshiba Q300 480GB                      | 1        | 0.61%   |
| Toshiba MK1655GSX 160GB                 | 1        | 0.61%   |
| Toshiba MD04ACA400 4TB                  | 1        | 0.61%   |
| Toshiba HDWE160 6TB                     | 1        | 0.61%   |
| Toshiba HDWD110 1TB                     | 1        | 0.61%   |
| Toshiba DT01ACA200 2TB                  | 1        | 0.61%   |
| Toshiba DT01ACA100 1TB                  | 1        | 0.61%   |
| Toshiba DT01ACA050 500GB                | 1        | 0.61%   |
| Toshiba DT01ABA300 3TB                  | 1        | 0.61%   |
| SK Hynix SHGS31-1000GS-2 1TB            | 1        | 0.61%   |
| SK Hynix BC711 NVMe 256GB               | 1        | 0.61%   |
| Seagate ST500NM0011 500GB               | 1        | 0.61%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 0.61%   |
| Seagate ST500DM002-1BC142 500GB         | 1        | 0.61%   |
| Seagate ST4000NC001-1FS168 4TB          | 1        | 0.61%   |
| Seagate ST4000NC000-1FR168 4TB          | 1        | 0.61%   |
| Seagate ST380211AS 80GB                 | 1        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 42     | 48.44%  |
| WDC                 | 18       | 24     | 28.13%  |
| Toshiba             | 7        | 10     | 10.94%  |
| Samsung Electronics | 3        | 3      | 4.69%   |
| Hitachi             | 3        | 3      | 4.69%   |
| HGST                | 2        | 2      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 16     | 25.42%  |
| Crucial             | 10       | 14     | 16.95%  |
| Kingston            | 6        | 6      | 10.17%  |
| WDC                 | 5        | 8      | 8.47%   |
| GOODRAM             | 4        | 4      | 6.78%   |
| A-DATA Technology   | 4        | 4      | 6.78%   |
| OCZ                 | 2        | 2      | 3.39%   |
| Intel               | 2        | 2      | 3.39%   |
| Gigabyte Technology | 2        | 3      | 3.39%   |
| Toshiba             | 1        | 1      | 1.69%   |
| SK Hynix            | 1        | 1      | 1.69%   |
| SanDisk             | 1        | 1      | 1.69%   |
| PNY                 | 1        | 1      | 1.69%   |
| PLEXTOR             | 1        | 1      | 1.69%   |
| Patriot             | 1        | 1      | 1.69%   |
| Lite-On             | 1        | 1      | 1.69%   |
| KingSpec            | 1        | 1      | 1.69%   |
| Apacer              | 1        | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 52       | 84     | 42.62%  |
| SSD  | 48       | 68     | 39.34%  |
| NVMe | 22       | 32     | 18.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 71       | 152    | 76.34%  |
| NVMe | 22       | 32     | 23.66%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 61       | 93     | 59.22%  |
| 0.51-1.0   | 18       | 26     | 17.48%  |
| 1.01-2.0   | 13       | 14     | 12.62%  |
| 3.01-4.0   | 7        | 14     | 6.8%    |
| 2.01-3.0   | 3        | 4      | 2.91%   |
| 4.01-10.0  | 1        | 1      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 51       | 62.2%   |
| 101-250    | 18       | 21.95%  |
| 251-500    | 8        | 9.76%   |
| 501-1000   | 2        | 2.44%   |
| 51-100     | 2        | 2.44%   |
| 21-50      | 1        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 81       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2        | 2      | 8%      |
| Seagate ST3320418AS 320GB           | 2        | 2      | 8%      |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 4%      |
| WDC WD5000AAKS-22A7B0 500GB         | 1        | 1      | 4%      |
| WDC WD3200AAJS-22B4A0 320GB         | 1        | 1      | 4%      |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1      | 4%      |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1      | 4%      |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 4%      |
| Toshiba MD04ACA400 4TB              | 1        | 1      | 4%      |
| Toshiba DT01ACA100 1TB              | 1        | 3      | 4%      |
| Toshiba DT01ABA300 3TB              | 1        | 1      | 4%      |
| Seagate ST380211AS 80GB             | 1        | 1      | 4%      |
| Seagate ST3500418AS 500GB           | 1        | 1      | 4%      |
| Seagate ST3160812AS 160GB           | 1        | 1      | 4%      |
| Seagate ST31000528AS 1TB            | 1        | 2      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1      | 4%      |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 4%      |
| Samsung Electronics HD322HJ 320GB   | 1        | 1      | 4%      |
| Kingston SV200S3128G 128GB          | 1        | 1      | 4%      |
| Kingston SMS200S3120G 120GB         | 1        | 1      | 4%      |
| Hitachi HTS541680J9SA00 80GB        | 1        | 1      | 4%      |
| Hitachi HDT721010SLA360 1TB         | 1        | 1      | 4%      |
| Crucial CT240M500SSD1 240GB         | 1        | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 34.78%  |
| WDC                 | 6        | 6      | 26.09%  |
| Toshiba             | 2        | 5      | 8.7%    |
| Samsung Electronics | 2        | 2      | 8.7%    |
| Kingston            | 2        | 2      | 8.7%    |
| Hitachi             | 2        | 2      | 8.7%    |
| Crucial             | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 42.11%  |
| WDC                 | 6        | 6      | 31.58%  |
| Toshiba             | 2        | 5      | 10.53%  |
| Hitachi             | 2        | 2      | 10.53%  |
| Samsung Electronics | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 24     | 81.82%  |
| SSD  | 4        | 4      | 18.18%  |

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
| Works    | 69       | 155    | 75.82%  |
| Malfunc  | 21       | 28     | 23.08%  |
| Detected | 1        | 1      | 1.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 58       | 51.79%  |
| AMD                         | 20       | 17.86%  |
| Samsung Electronics         | 8        | 7.14%   |
| SK Hynix                    | 3        | 2.68%   |
| Phison Electronics          | 3        | 2.68%   |
| JMicron Technology          | 3        | 2.68%   |
| ASMedia Technology          | 3        | 2.68%   |
| Sandisk                     | 2        | 1.79%   |
| Nvidia                      | 2        | 1.79%   |
| Marvell Technology Group    | 2        | 1.79%   |
| Kingston Technology Company | 2        | 1.79%   |
| ADATA Technology            | 2        | 1.79%   |
| VIA Technologies            | 1        | 0.89%   |
| Silicon Motion              | 1        | 0.89%   |
| Seagate Technology          | 1        | 0.89%   |
| Micron/Crucial Technology   | 1        | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 12.98%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 5.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 5.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 4.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 4.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 4.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 4.58%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 3.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.05%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.29%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2        | 1.53%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.53%   |
| Phison E12 NVMe Controller                                                              | 2        | 1.53%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.53%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.53%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.53%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.53%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.53%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.53%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 1.53%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.76%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.76%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.76%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.76%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.76%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.76%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.76%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.76%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.76%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.76%   |
| Intel SSD 660P Series                                                                   | 1        | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 1        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1        | 0.76%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 1        | 0.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1        | 0.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.76%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.76%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.76%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 60       | 58.25%  |
| NVMe | 22       | 21.36%  |
| IDE  | 15       | 14.56%  |
| RAID | 6        | 5.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 58       | 71.6%   |
| AMD    | 23       | 28.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 2.47%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 2.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.47%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 2.47%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 2.47%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1        | 1.23%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 1.23%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 1.23%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 1.23%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1        | 1.23%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 1.23%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 1.23%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 1.23%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 1.23%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.23%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 1.23%   |
| Intel Pentium Dual-Core CPU E6500 @         | 1        | 1.23%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 1.23%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 1.23%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 1.23%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 1.23%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 1.23%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.23%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.23%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.23%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 1.23%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.23%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.23%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.23%   |
| Intel Core i7 CPU                           | 1        | 1.23%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.23%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.23%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.23%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.23%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.23%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.23%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.23%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.23%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.23%   |
| Intel Core i5-3475S CPU @ 2.90GHz           | 1        | 1.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.23%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 1.23%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.23%   |
| Intel Core i5-2405S CPU @ 2.50GHz           | 1        | 1.23%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 1        | 1.23%   |
| Intel Core i3-6320 CPU @ 3.90GHz            | 1        | 1.23%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 1.23%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1        | 1.23%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.23%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 1.23%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.23%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.23%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.23%   |
| Intel Core 2 Duo CPU E4700 @ 2.60GHz        | 1        | 1.23%   |
| Intel Core 2 Duo                            | 1        | 1.23%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 1.23%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 1        | 1.23%   |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 1.23%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1.23%   |
| Intel 12th Gen Core i5-12600K               | 1        | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 18.52%  |
| Intel Core i7           | 10       | 12.35%  |
| Intel Xeon              | 9        | 11.11%  |
| AMD Ryzen 7             | 7        | 8.64%   |
| AMD Ryzen 5             | 7        | 8.64%   |
| Intel Core i3           | 6        | 7.41%   |
| Intel Pentium Dual-Core | 4        | 4.94%   |
| Intel Core 2 Duo        | 3        | 3.7%    |
| Other                   | 2        | 2.47%   |
| Intel Pentium           | 2        | 2.47%   |
| Intel Celeron           | 2        | 2.47%   |
| AMD Ryzen 9             | 2        | 2.47%   |
| Intel Pentium Dual      | 1        | 1.23%   |
| Intel Core i9           | 1        | 1.23%   |
| Intel Core 2 Quad       | 1        | 1.23%   |
| Intel Core 2            | 1        | 1.23%   |
| Intel Atom              | 1        | 1.23%   |
| AMD Ryzen Threadripper  | 1        | 1.23%   |
| AMD Ryzen 3             | 1        | 1.23%   |
| AMD Phenom II X4        | 1        | 1.23%   |
| AMD FX                  | 1        | 1.23%   |
| AMD E2                  | 1        | 1.23%   |
| AMD E                   | 1        | 1.23%   |
| AMD Athlon II X2        | 1        | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 27       | 33.33%  |
| 2       | 18       | 22.22%  |
| 6       | 10       | 12.35%  |
| 16      | 6        | 7.41%   |
| 8       | 6        | 7.41%   |
| Unknown | 6        | 7.41%   |
| 12      | 4        | 4.94%   |
| 24      | 2        | 2.47%   |
| 64      | 1        | 1.23%   |
| 14      | 1        | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 81       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 47       | 58.02%  |
| 2       | 28       | 34.57%  |
| Unknown | 6        | 7.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 9        | 11.11%  |
| Haswell     | 9        | 11.11%  |
| IvyBridge   | 8        | 9.88%   |
| Skylake     | 7        | 8.64%   |
| Penryn      | 7        | 8.64%   |
| Zen 2       | 6        | 7.41%   |
| SandyBridge | 6        | 7.41%   |
| Zen+        | 4        | 4.94%   |
| Zen 3       | 4        | 4.94%   |
| Zen         | 4        | 4.94%   |
| Core        | 3        | 3.7%    |
| Westmere    | 2        | 2.47%   |
| Nehalem     | 2        | 2.47%   |
| K10         | 2        | 2.47%   |
| Unknown     | 2        | 2.47%   |
| Piledriver  | 1        | 1.23%   |
| Jaguar      | 1        | 1.23%   |
| CometLake   | 1        | 1.23%   |
| Broadwell   | 1        | 1.23%   |
| Bonnell     | 1        | 1.23%   |
| Bobcat      | 1        | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 33       | 39.76%  |
| Intel  | 30       | 36.14%  |
| AMD    | 20       | 24.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 6.02%   |
| Intel HD Graphics 530                                                       | 4        | 4.82%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.61%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 3.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.61%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 3.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.41%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.41%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 2.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.41%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.41%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.2%    |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.2%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.2%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.2%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.2%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.2%    |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.2%    |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.2%    |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.2%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.2%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.2%    |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.2%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.2%    |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.2%    |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 1.2%    |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 1.2%    |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 1.2%    |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 1.2%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.2%    |
| Intel HD Graphics 630                                                       | 1        | 1.2%    |
| Intel HD Graphics 5500                                                      | 1        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.2%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 1.2%    |
| Intel AlderLake-S GT1                                                       | 1        | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.2%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.2%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.2%    |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.2%    |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.2%    |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.2%    |
| AMD Kabini [Radeon HD 8280 / R3 Series]                                     | 1        | 1.2%    |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 1.2%    |
| AMD Cezanne                                                                 | 1        | 1.2%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 32       | 39.51%  |
| 1 x Intel      | 26       | 32.1%   |
| 1 x AMD        | 19       | 23.46%  |
| 2 x Intel      | 2        | 2.47%   |
| Intel + Nvidia | 1        | 1.23%   |
| Intel + AMD    | 1        | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 51       | 62.2%   |
| Proprietary | 28       | 34.15%  |
| Unknown     | 3        | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 46.34%  |
| 3.01-4.0   | 11       | 13.41%  |
| 1.01-2.0   | 11       | 13.41%  |
| 7.01-8.0   | 9        | 10.98%  |
| 0.51-1.0   | 7        | 8.54%   |
| 0.01-0.5   | 4        | 4.88%   |
| 5.01-6.0   | 2        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 16.22%  |
| Goldstar             | 9        | 12.16%  |
| BenQ                 | 9        | 12.16%  |
| Dell                 | 7        | 9.46%   |
| AOC                  | 7        | 9.46%   |
| Philips              | 5        | 6.76%   |
| Hewlett-Packard      | 5        | 6.76%   |
| Acer                 | 5        | 6.76%   |
| Sony                 | 3        | 4.05%   |
| Ancor Communications | 3        | 4.05%   |
| ASUSTek Computer     | 2        | 2.7%    |
| Westinghouse         | 1        | 1.35%   |
| SGT                  | 1        | 1.35%   |
| NEC Computers        | 1        | 1.35%   |
| Lenovo               | 1        | 1.35%   |
| Iiyama               | 1        | 1.35%   |
| Fujitsu Siemens      | 1        | 1.35%   |
| Denver               | 1        | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 2.6%    |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1        | 1.3%    |
| Sony TV SNYEE01 1920x1080                                              | 1        | 1.3%    |
| Sony TV SNY9C01 1360x768                                               | 1        | 1.3%    |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 1.3%    |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1        | 1.3%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 1.3%    |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1        | 1.3%    |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1        | 1.3%    |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 1.3%    |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1        | 1.3%    |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1        | 1.3%    |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 1        | 1.3%    |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch      | 1        | 1.3%    |
| Samsung Electronics C24FG7x SAM0E44 1920x1080 530x300mm 24.0-inch      | 1        | 1.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1        | 1.3%    |
| Philips PHL 278E1 PHLC217 3840x2160 600x340mm 27.2-inch                | 1        | 1.3%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1        | 1.3%    |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1        | 1.3%    |
| Philips 220E PHLC02E 1920x1080 470x260mm 21.1-inch                     | 1        | 1.3%    |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                      | 1        | 1.3%    |
| NEC Computers LCD1770VX NEC6696 1280x1024 340x270mm 17.1-inch          | 1        | 1.3%    |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch               | 1        | 1.3%    |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 1        | 1.3%    |
| Hewlett-Packard Z24n G2 HPN3485 1920x1200 520x320mm 24.0-inch          | 1        | 1.3%    |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 1.3%    |
| Hewlett-Packard LCD Monitor HPN3425 1920x1080 540x300mm 24.3-inch      | 1        | 1.3%    |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch              | 1        | 1.3%    |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 1.3%    |
| Goldstar W2361 GSM56FB 1920x1080 510x290mm 23.1-inch                   | 1        | 1.3%    |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                    | 1        | 1.3%    |
| Goldstar M2280D GSM57B9 1920x1080 480x270mm 21.7-inch                  | 1        | 1.3%    |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 1.3%    |
| Goldstar LCD Monitor GSM5807 1920x1080 480x270mm 21.7-inch             | 1        | 1.3%    |
| Goldstar 700E GSM4317 1280x1024 330x250mm 16.3-inch                    | 1        | 1.3%    |
| Goldstar 19MB35 GSM4C23 1280x1024 380x300mm 19.1-inch                  | 1        | 1.3%    |
| Fujitsu Siemens L19-8 FUS075B 1280x1024 380x300mm 19.1-inch            | 1        | 1.3%    |
| Denver UXGA-100-C LHC2900 2560x1080 680x280mm 29.0-inch                | 1        | 1.3%    |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                      | 1        | 1.3%    |
| Dell U2515H DELD06F 2560x1440 550x310mm 24.9-inch                      | 1        | 1.3%    |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                       | 1        | 1.3%    |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 1        | 1.3%    |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 1.3%    |
| Dell P1914S DELF04B 1280x1024 380x300mm 19.1-inch                      | 1        | 1.3%    |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                     | 1        | 1.3%    |
| BenQ XL2411Z BNQ7F31 1920x1080 530x300mm 24.0-inch                     | 1        | 1.3%    |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                      | 1        | 1.3%    |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                      | 1        | 1.3%    |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 1        | 1.3%    |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                      | 1        | 1.3%    |
| BenQ G702AD BNQ7846 1280x1024 340x270mm 17.1-inch                      | 1        | 1.3%    |
| BenQ G2020HD BNQ781F 1600x900 440x250mm 19.9-inch                      | 1        | 1.3%    |
| BenQ EW2440L BNQ7938 1920x1080 530x300mm 24.0-inch                     | 1        | 1.3%    |
| BenQ BL2780 BNQ802B 1920x1080 600x340mm 27.2-inch                      | 1        | 1.3%    |
| ASUSTek Computer VP228 AUS22A1 1920x1080 480x270mm 21.7-inch           | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 35       | 47.3%   |
| 1280x1024 (SXGA)   | 8        | 10.81%  |
| 2560x1440 (QHD)    | 5        | 6.76%   |
| 1440x900 (WXGA+)   | 5        | 6.76%   |
| 3840x2160 (4K)     | 4        | 5.41%   |
| 1920x1200 (WUXGA)  | 4        | 5.41%   |
| 1600x900 (HD+)     | 4        | 5.41%   |
| 1680x1050 (WSXGA+) | 3        | 4.05%   |
| 1366x768 (WXGA)    | 3        | 4.05%   |
| 3440x1440          | 1        | 1.35%   |
| 2560x1080          | 1        | 1.35%   |
| 1360x768           | 1        | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 16       | 21.33%  |
| 21      | 11       | 14.67%  |
| 19      | 11       | 14.67%  |
| 27      | 8        | 10.67%  |
| 23      | 8        | 10.67%  |
| 18      | 5        | 6.67%   |
| 17      | 4        | 5.33%   |
| 31      | 3        | 4%      |
| Unknown | 3        | 4%      |
| 50      | 1        | 1.33%   |
| 34      | 1        | 1.33%   |
| 33      | 1        | 1.33%   |
| 29      | 1        | 1.33%   |
| 20      | 1        | 1.33%   |
| 16      | 1        | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 28       | 39.44%  |
| 401-500     | 21       | 29.58%  |
| 351-400     | 7        | 9.86%   |
| 601-700     | 5        | 7.04%   |
| 301-350     | 4        | 5.63%   |
| Unknown     | 3        | 4.23%   |
| 701-800     | 2        | 2.82%   |
| 1001-1500   | 1        | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 49       | 69.01%  |
| 16/10 | 12       | 16.9%   |
| 5/4   | 6        | 8.45%   |
| 21/9  | 2        | 2.82%   |
| 4/3   | 1        | 1.41%   |
| 3/2   | 1        | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 36.49%  |
| 151-200        | 16       | 21.62%  |
| 301-350        | 8        | 10.81%  |
| 251-300        | 7        | 9.46%   |
| 351-500        | 5        | 6.76%   |
| 141-150        | 5        | 6.76%   |
| Unknown        | 3        | 4.05%   |
| 121-130        | 2        | 2.7%    |
| More than 1000 | 1        | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 50       | 66.67%  |
| 101-120 | 17       | 22.67%  |
| Unknown | 3        | 4%      |
| 161-240 | 2        | 2.67%   |
| 121-160 | 2        | 2.67%   |
| 1-50    | 1        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 64       | 78.05%  |
| 0     | 9        | 10.98%  |
| 2     | 8        | 9.76%   |
| 3     | 1        | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 49       | 49.49%  |
| Intel                 | 35       | 35.35%  |
| Qualcomm Atheros      | 6        | 6.06%   |
| Broadcom              | 3        | 3.03%   |
| Ralink                | 2        | 2.02%   |
| TP-Link               | 1        | 1.01%   |
| Ralink Technology     | 1        | 1.01%   |
| NetGear               | 1        | 1.01%   |
| Microchip Technology  | 1        | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 38       | 33.63%  |
| Intel I211 Gigabit Network Connection                                         | 8        | 7.08%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 5.31%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 3.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 2.65%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 2.65%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.77%   |
| Intel Wireless-AC 9260                                                        | 2        | 1.77%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.77%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.88%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.88%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 0.88%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 0.88%   |
| Ralink RT2500 Wireless 802.11bg                                               | 1        | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.88%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 0.88%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.88%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 0.88%   |
| Microchip HTC Hub Controller                                                  | 1        | 0.88%   |
| Intel Wireless 7265                                                           | 1        | 0.88%   |
| Intel Wireless 7260                                                           | 1        | 0.88%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.88%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.88%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 0.88%   |
| Intel Centrino Wireless-N 2230                                                | 1        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 0.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 0.88%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.88%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.88%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 39.29%  |
| Realtek Semiconductor | 9        | 32.14%  |
| Ralink                | 2        | 7.14%   |
| Broadcom              | 2        | 7.14%   |
| TP-Link               | 1        | 3.57%   |
| Ralink Technology     | 1        | 3.57%   |
| Qualcomm Atheros      | 1        | 3.57%   |
| NetGear               | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 3        | 10.71%  |
| Intel Wi-Fi 6 AX200                                              | 3        | 10.71%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 2        | 7.14%   |
| Intel Wireless-AC 9260                                           | 2        | 7.14%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 1        | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1        | 3.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1        | 3.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                           | 1        | 3.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1        | 3.57%   |
| Ralink RT5370 Wireless Adapter                                   | 1        | 3.57%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                        | 1        | 3.57%   |
| Ralink RT2500 Wireless 802.11bg                                  | 1        | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1        | 3.57%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101] | 1        | 3.57%   |
| Intel Wireless 7265                                              | 1        | 3.57%   |
| Intel Wireless 7260                                              | 1        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 1        | 3.57%   |
| Intel Centrino Wireless-N 2230                                   | 1        | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 1        | 3.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1        | 3.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter               | 1        | 3.57%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller           | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 44       | 53.66%  |
| Intel                 | 32       | 39.02%  |
| Qualcomm Atheros      | 5        | 6.1%    |
| Broadcom              | 1        | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 38       | 45.24%  |
| Intel I211 Gigabit Network Connection                                         | 8        | 9.52%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 7.14%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 2.38%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.19%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 1.19%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 1.19%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 1.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1.19%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 1.19%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 1.19%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.19%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 1.19%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 1.19%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 1.19%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 1.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.19%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 74.53%  |
| WiFi     | 26       | 24.53%  |
| Modem    | 1        | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 81.91%  |
| WiFi     | 17       | 18.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 69.14%  |
| 2     | 16       | 19.75%  |
| 3     | 4        | 4.94%   |
| 4     | 3        | 3.7%    |
| 0     | 2        | 2.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 78       | 96.3%   |
| Yes  | 3        | 3.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 41.38%  |
| Cambridge Silicon Radio         | 6        | 20.69%  |
| Realtek Semiconductor           | 2        | 6.9%    |
| IMC Networks                    | 2        | 6.9%    |
| ASUSTek Computer                | 2        | 6.9%    |
| Apple                           | 2        | 6.9%    |
| Qualcomm Atheros Communications | 1        | 3.45%   |
| Integrated System Solution      | 1        | 3.45%   |
| HTC (High Tech Computer)        | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6        | 20.69%  |
| Intel AX200 Bluetooth                                                | 3        | 10.34%  |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 6.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 6.9%    |
| Intel Bluetooth wireless interface                                   | 2        | 6.9%    |
| Intel AX201 Bluetooth                                                | 2        | 6.9%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1        | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 3.45%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 3.45%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1        | 3.45%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1        | 3.45%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.45%   |
| ASUS Bluetooth Controller                                            | 1        | 3.45%   |
| ASUS ASUS USB-BT500                                                  | 1        | 3.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 3.45%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 54       | 39.42%  |
| Nvidia                  | 31       | 22.63%  |
| AMD                     | 29       | 21.17%  |
| C-Media Electronics     | 4        | 2.92%   |
| Texas Instruments       | 3        | 2.19%   |
| Logitech                | 2        | 1.46%   |
| GN Netcom               | 2        | 1.46%   |
| Yamaha                  | 1        | 0.73%   |
| VIA Technologies        | 1        | 0.73%   |
| SteelSeries ApS         | 1        | 0.73%   |
| Nektar                  | 1        | 0.73%   |
| KORG                    | 1        | 0.73%   |
| Kingston Technology     | 1        | 0.73%   |
| JMTek                   | 1        | 0.73%   |
| Focusrite-Novation      | 1        | 0.73%   |
| Creative Labs           | 1        | 0.73%   |
| Corsair                 | 1        | 0.73%   |
| Cambridge Silicon Radio | 1        | 0.73%   |
| ASUSTek Computer        | 1        | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 5.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 5.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 5.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 4.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 3.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 3.25%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 2.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.95%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.95%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.95%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.95%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.3%    |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.3%    |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.3%    |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.3%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.3%    |
| Yamaha Steinberg UR12                                                      | 1        | 0.65%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.65%   |
| Texas Instruments PCM2902C Audio CODEC                                     | 1        | 0.65%   |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game           | 1        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.65%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.65%   |
| Nektar Impact GX61                                                         | 1        | 0.65%   |
| Logitech Headset H390                                                      | 1        | 0.65%   |
| Logitech HD Webcam C510                                                    | 1        | 0.65%   |
| KORG microKEY-25                                                           | 1        | 0.65%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 0.65%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.65%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.65%   |
| Intel Broadwell-U Audio Controller                                         | 1        | 0.65%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.65%   |
| GN Netcom Jabra SPEAK 510 USB                                              | 1        | 0.65%   |
| GN Netcom Jabra Link 380                                                   | 1        | 0.65%   |
| Focusrite-Novation Launchkey MK3 49 LKMK3 MIDI LKMK3 MIDI Int LKMK3 HID    | 1        | 0.65%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 0.65%   |
| Corsair Corsair HS60 Surround Gaming Dongle                                | 1        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 15       | 17.05%  |
| Unknown             | 14       | 15.91%  |
| Crucial             | 9        | 10.23%  |
| Corsair             | 9        | 10.23%  |
| SK Hynix            | 8        | 9.09%   |
| G.Skill             | 8        | 9.09%   |
| Samsung Electronics | 5        | 5.68%   |
| Micron Technology   | 4        | 4.55%   |
| Team                | 3        | 3.41%   |
| Patriot             | 2        | 2.27%   |
| AMD                 | 2        | 2.27%   |
| Unknown             | 2        | 2.27%   |
| Unifosa             | 1        | 1.14%   |
| Nanya Technology    | 1        | 1.14%   |
| Hikvision           | 1        | 1.14%   |
| GOODRAM             | 1        | 1.14%   |
| Goldkey             | 1        | 1.14%   |
| Atermiter           | 1        | 1.14%   |
| A-DATA Technology   | 1        | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 2.15%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2        | 2.15%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 2        | 2.15%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s | 2        | 2.15%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 2.15%   |
| Unknown                                                | 2        | 2.15%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 1.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 1.08%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s             | 1        | 1.08%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 1        | 1.08%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s              | 1        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 1        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 1.08%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 1.08%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s               | 1        | 1.08%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s      | 1        | 1.08%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s    | 1        | 1.08%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s     | 1        | 1.08%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 1        | 1.08%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s           | 1        | 1.08%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 1.08%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.08%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s  | 1        | 1.08%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1        | 1.08%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s   | 1        | 1.08%   |
| SK Hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 1.08%   |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 1.08%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s            | 1        | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s    | 1        | 1.08%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.08%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2666MT/s    | 1        | 1.08%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s    | 1        | 1.08%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 1        | 1.08%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s     | 1        | 1.08%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s     | 1        | 1.08%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s     | 1        | 1.08%   |
| Micron RAM 4ATF51264AZ-3G2J1 4GB DIMM DDR4 3200MT/s    | 1        | 1.08%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 1        | 1.08%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s   | 1        | 1.08%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s  | 1        | 1.08%   |
| Kingston RAM termiter 4GB DIMM DDR3 1333MT/s           | 1        | 1.08%   |
| Kingston RAM Module 8GB DIMM DDR4 2666MT/s             | 1        | 1.08%   |
| Kingston RAM KHX3733C19D4/16GX 16GB DIMM DDR4 3733MT/s | 1        | 1.08%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 2400MT/s    | 1        | 1.08%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 1        | 1.08%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3200MT/s | 1        | 1.08%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s      | 1        | 1.08%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s    | 1        | 1.08%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s  | 1        | 1.08%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2133MT/s    | 1        | 1.08%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2133MT/s      | 1        | 1.08%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s    | 1        | 1.08%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 1        | 1.08%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 2400MT/s  | 1        | 1.08%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1333MT/s  | 1        | 1.08%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s  | 1        | 1.08%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s  | 1        | 1.08%   |
| Hikvision RAM HKED3041AAB3H3HA1 4GB DIMM DDR3 1600MT/s | 1        | 1.08%   |
| GOODRAM RAM GR2666D464L19S/8G 8GB DIMM DDR4 2400MT/s   | 1        | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 37       | 47.44%  |
| DDR3    | 29       | 37.18%  |
| DDR2    | 5        | 6.41%   |
| SDRAM   | 3        | 3.85%   |
| Unknown | 3        | 3.85%   |
| DDR     | 1        | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 72       | 92.31%  |
| SODIMM | 6        | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 35.29%  |
| 4096  | 21       | 24.71%  |
| 16384 | 14       | 16.47%  |
| 2048  | 13       | 15.29%  |
| 1024  | 5        | 5.88%   |
| 32768 | 2        | 2.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 20%     |
| 3200    | 11       | 13.75%  |
| 1333    | 11       | 13.75%  |
| 2133    | 9        | 11.25%  |
| 2400    | 7        | 8.75%   |
| 2666    | 6        | 7.5%    |
| 2667    | 3        | 3.75%   |
| 800     | 3        | 3.75%   |
| Unknown | 3        | 3.75%   |
| 3600    | 2        | 2.5%    |
| 667     | 2        | 2.5%    |
| 400     | 2        | 2.5%    |
| 3733    | 1        | 1.25%   |
| 1867    | 1        | 1.25%   |
| 1066    | 1        | 1.25%   |
| 533     | 1        | 1.25%   |
| 333     | 1        | 1.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-1430 Laser Printer | 1        | 100%    |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech              | 4        | 50%     |
| IMC Networks          | 1        | 12.5%   |
| Hewlett-Packard       | 1        | 12.5%   |
| Chicony Electronics   | 1        | 12.5%   |
| Arkmicro Technologies | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C930e         | 1        | 12.5%   |
| Logitech Webcam C310          | 1        | 12.5%   |
| Logitech Webcam C270          | 1        | 12.5%   |
| Logitech BRIO Ultra HD Webcam | 1        | 12.5%   |
| IMC Networks XHC Camera       | 1        | 12.5%   |
| HP Realtek PC Camera          | 1        | 12.5%   |
| Chicony HP 0.3MP Webcam       | 1        | 12.5%   |
| Arkmicro USB2.0 PC CAMERA     | 1        | 12.5%   |

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
| 1     | 36       | 44.44%  |
| 0     | 30       | 37.04%  |
| 2     | 10       | 12.35%  |
| 3     | 3        | 3.7%    |
| 4     | 2        | 2.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 45       | 66.18%  |
| Net/wireless             | 14       | 20.59%  |
| Bluetooth                | 4        | 5.88%   |
| Sound                    | 2        | 2.94%   |
| Network                  | 1        | 1.47%   |
| Net/ethernet             | 1        | 1.47%   |
| Card reader              | 1        | 1.47%   |

