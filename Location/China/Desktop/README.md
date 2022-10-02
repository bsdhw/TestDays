BSD in China - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BSD in China.

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

Total: 84

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | 0KYJ8C A02                  | [12493c3802](https://bsd-hardware.info/?probe=12493c3802) | Sep 26, 2022 |
| Unknown       | Unknown                     | [199ad16750](https://bsd-hardware.info/?probe=199ad16750) | Sep 21, 2022 |
| Gigabyte      | H410M S2 V2                 | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Dell          | 0KYJ8C A02                  | [fb950378c9](https://bsd-hardware.info/?probe=fb950378c9) | Sep 13, 2022 |
| Dell          | 0KYJ8C A02                  | [bb784470e7](https://bsd-hardware.info/?probe=bb784470e7) | Sep 12, 2022 |
| Dell          | 0KYJ8C A02                  | [7e8d44c688](https://bsd-hardware.info/?probe=7e8d44c688) | Sep 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Techvision    | TVI7309X B0                 | [9941ee7afb](https://bsd-hardware.info/?probe=9941ee7afb) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Unknown       | DTB1168                     | [e924ba2a44](https://bsd-hardware.info/?probe=e924ba2a44) | Sep 01, 2022 |
| WlanCN        | 6000 Series                 | [7fda15ca84](https://bsd-hardware.info/?probe=7fda15ca84) | Aug 25, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| Techvision    | TVI7309X B0                 | [b2aa5f61e2](https://bsd-hardware.info/?probe=b2aa5f61e2) | Jul 11, 2022 |
| ASUSTek       | Maximus IX HERO             | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Unknown       | Unknown                     | [0f45bdf1ec](https://bsd-hardware.info/?probe=0f45bdf1ec) | Jun 14, 2022 |
| Unknown       | Unknown                     | [57a6f58607](https://bsd-hardware.info/?probe=57a6f58607) | Jun 09, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d9c28e14df](https://bsd-hardware.info/?probe=d9c28e14df) | May 13, 2022 |
| Lenovo        | MAHOBAY                     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| OEM           | B85 JHS359                  | [c5d29cc6b3](https://bsd-hardware.info/?probe=c5d29cc6b3) | May 03, 2022 |
| PAIQ          | EC3-BT19D4L A1              | [9642cf3129](https://bsd-hardware.info/?probe=9642cf3129) | Mar 30, 2022 |
| ASRock        | Q1900M                      | [e2473b7f22](https://bsd-hardware.info/?probe=e2473b7f22) | Mar 29, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [97f4960723](https://bsd-hardware.info/?probe=97f4960723) | Mar 28, 2022 |
| Unknown       | J3160-4L                    | [e2717ea0eb](https://bsd-hardware.info/?probe=e2717ea0eb) | Mar 24, 2022 |
| Unknown       | Unknown                     | [d08da1541a](https://bsd-hardware.info/?probe=d08da1541a) | Mar 14, 2022 |
| Lenovo        | IdeaCentre B545 10100       | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| Unknown       | Unknown                     | [ce3fedcbaf](https://bsd-hardware.info/?probe=ce3fedcbaf) | Mar 07, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [b54ace2a34](https://bsd-hardware.info/?probe=b54ace2a34) | Mar 03, 2022 |
| Intel         | X58                         | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| Unknown       | Unknown                     | [8eda642f6a](https://bsd-hardware.info/?probe=8eda642f6a) | Jan 04, 2022 |
| Dell          | 0H9KW5 A00                  | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [e115f87ef7](https://bsd-hardware.info/?probe=e115f87ef7) | Nov 30, 2021 |
| Unknown       | Unknown                     | [08f546f789](https://bsd-hardware.info/?probe=08f546f789) | Nov 21, 2021 |
| Unknown       | Unknown                     | [d958c5d8f1](https://bsd-hardware.info/?probe=d958c5d8f1) | Nov 18, 2021 |
| Unknown       | Unknown                     | [d3e799d3a6](https://bsd-hardware.info/?probe=d3e799d3a6) | Nov 13, 2021 |
| Unknown       | YL-SKUL6-7 Series           | [8c72c2f429](https://bsd-hardware.info/?probe=8c72c2f429) | Nov 12, 2021 |
| GuoGuang      | IC2M1028V-6                 | [1aa8bbd5b2](https://bsd-hardware.info/?probe=1aa8bbd5b2) | Nov 07, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | [9b545faf66](https://bsd-hardware.info/?probe=9b545faf66) | Oct 28, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | [f269216a0d](https://bsd-hardware.info/?probe=f269216a0d) | Oct 27, 2021 |
| MSI           | MAG B460M MORTAR            | [f9c5120643](https://bsd-hardware.info/?probe=f9c5120643) | Oct 22, 2021 |
| Gigabyte      | H410M S2 V2                 | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Dell          | 0DR845                      | [d8324d1639](https://bsd-hardware.info/?probe=d8324d1639) | Oct 21, 2021 |
| HP            | 3398                        | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| Gigabyte      | H410M S2 V2                 | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [84f06376e2](https://bsd-hardware.info/?probe=84f06376e2) | Oct 02, 2021 |
| NEC Comput... | SHARKBAY                    | [24229ed11f](https://bsd-hardware.info/?probe=24229ed11f) | Sep 22, 2021 |
| CNCTION-IA... | Unknown                     | [aad95eb2bf](https://bsd-hardware.info/?probe=aad95eb2bf) | Sep 21, 2021 |
| YANYU         | ITX-N29 VER:1.5 baytrail    | [c851a73aa5](https://bsd-hardware.info/?probe=c851a73aa5) | Sep 20, 2021 |
| Unknown       | Unknown                     | [0da457285c](https://bsd-hardware.info/?probe=0da457285c) | Aug 23, 2021 |
| Unknown       | J3160-4L                    | [3063e4b82f](https://bsd-hardware.info/?probe=3063e4b82f) | Aug 21, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [cce0d947f1](https://bsd-hardware.info/?probe=cce0d947f1) | Aug 20, 2021 |
| PAIQ          | EC3-BT19D4L A1              | [1a438c7632](https://bsd-hardware.info/?probe=1a438c7632) | Aug 19, 2021 |
| CNCTION-IA... | Unknown                     | [7763f089a3](https://bsd-hardware.info/?probe=7763f089a3) | Aug 17, 2021 |
| Unknown       | J3160-4L                    | [dc1e25a4e0](https://bsd-hardware.info/?probe=dc1e25a4e0) | Aug 07, 2021 |
| Lenovo        | NOK                         | [de711c244f](https://bsd-hardware.info/?probe=de711c244f) | Aug 05, 2021 |
| Lenovo        | NOK                         | [5bd27802f0](https://bsd-hardware.info/?probe=5bd27802f0) | Aug 04, 2021 |
| GuoGuang      | IC2M1028V-6                 | [9bfe0dca00](https://bsd-hardware.info/?probe=9bfe0dca00) | Jul 21, 2021 |
| Unknown       | Unknown                     | [58f03a472f](https://bsd-hardware.info/?probe=58f03a472f) | Jul 03, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [b8712916f2](https://bsd-hardware.info/?probe=b8712916f2) | Jun 29, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [0b0951a048](https://bsd-hardware.info/?probe=0b0951a048) | Jun 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [8fe29978c3](https://bsd-hardware.info/?probe=8fe29978c3) | Jun 22, 2021 |
| Protectli     | FW6                         | [7fe94af21a](https://bsd-hardware.info/?probe=7fe94af21a) | Jun 11, 2021 |
| CNCTION-IA... | Unknown                     | [ff1a657505](https://bsd-hardware.info/?probe=ff1a657505) | Jun 08, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [c0b3c87810](https://bsd-hardware.info/?probe=c0b3c87810) | Jun 04, 2021 |
| Colorful T... | C.Q1900M PRO V20            | [5283765cbe](https://bsd-hardware.info/?probe=5283765cbe) | Apr 03, 2021 |
| Gigabyte      | MZBSWBP-00                  | [3623b04225](https://bsd-hardware.info/?probe=3623b04225) | Mar 31, 2021 |
| Dell          | 018D1Y A00                  | [13754ed4ee](https://bsd-hardware.info/?probe=13754ed4ee) | Mar 23, 2021 |
| Dell          | 0YXT71 A00                  | [cb3d9f12c6](https://bsd-hardware.info/?probe=cb3d9f12c6) | Mar 20, 2021 |
| Dell          | 0W2PJY A01                  | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| MSI           | B150M MORTAR                | [19923e24d6](https://bsd-hardware.info/?probe=19923e24d6) | Mar 10, 2021 |
| Dell          | 0W2PJY A01                  | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [9a23dee2ea](https://bsd-hardware.info/?probe=9a23dee2ea) | Mar 01, 2021 |
| Gigabyte      | GA-870-UD3P                 | [e228db2983](https://bsd-hardware.info/?probe=e228db2983) | Feb 20, 2021 |
| Dell          | 018D1Y A00                  | [a54f14d773](https://bsd-hardware.info/?probe=a54f14d773) | Feb 18, 2021 |
| Unknown       | Unknown                     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| Google        | Guado                       | [f6473eeb71](https://bsd-hardware.info/?probe=f6473eeb71) | Feb 16, 2021 |
| HP            | 8768 A                      | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| ASUSTek       | EX-B85M-V                   | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| Unknown       | Unknown                     | [bc823e0dfc](https://bsd-hardware.info/?probe=bc823e0dfc) | Feb 08, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [12e20c2cb0](https://bsd-hardware.info/?probe=12e20c2cb0) | Jan 23, 2021 |
| ASRock        | A320M-ITX                   | [7fab9dd55a](https://bsd-hardware.info/?probe=7fab9dd55a) | Oct 31, 2020 |
| HP            | 213D A01                    | [b081e36525](https://bsd-hardware.info/?probe=b081e36525) | Oct 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| helloSystem 0.7.0 | 8        | 11.43%  |
| OPNsense 21.7.1   | 6        | 8.57%   |
| OPNsense 21.7.3   | 4        | 5.71%   |
| OPNsense 21.1.7   | 4        | 5.71%   |
| helloSystem 0.5.0 | 4        | 5.71%   |
| OPNsense 21.7.5   | 3        | 4.29%   |
| OPNsense 21.7.2   | 3        | 4.29%   |
| FreeBSD 13.1-p2   | 3        | 4.29%   |
| OPNsense 22.7.2   | 2        | 2.86%   |
| OPNsense 22.1.4   | 2        | 2.86%   |
| OPNsense 22.1.2   | 2        | 2.86%   |
| OPNsense 22.1.10  | 2        | 2.86%   |
| OPNsense 21.1.6   | 2        | 2.86%   |
| OPNsense 21.1.3   | 2        | 2.86%   |
| OPNsense 21.1     | 2        | 2.86%   |
| helloSystem 0.6.0 | 2        | 2.86%   |
| helloSystem 0.4.0 | 2        | 2.86%   |
| OPNsense 22.7.4   | 1        | 1.43%   |
| OPNsense 22.7.3   | 1        | 1.43%   |
| OPNsense 22.1.8   | 1        | 1.43%   |
| OPNsense 22.1.3   | 1        | 1.43%   |
| OPNsense 21.7.8   | 1        | 1.43%   |
| OPNsense 21.7.7   | 1        | 1.43%   |
| OPNsense 21.7.6   | 1        | 1.43%   |
| OPNsense 21.7.4   | 1        | 1.43%   |
| OPNsense 21.1.4   | 1        | 1.43%   |
| OPNsense 21.1.2   | 1        | 1.43%   |
| OPNsense 21.1.1   | 1        | 1.43%   |
| GhostBSD 21.08.27 | 1        | 1.43%   |
| FreeBSD 13.0-RC5  | 1        | 1.43%   |
| FreeBSD 12.2-p4   | 1        | 1.43%   |
| FreeBSD 12.2-p2   | 1        | 1.43%   |
| FreeBSD 12.2      | 1        | 1.43%   |
| FreeBSD 12.1      | 1        | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 34       | 57.63%  |
| helloSystem | 16       | 27.12%  |
| FreeBSD     | 8        | 13.56%  |
| GhostBSD    | 1        | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 57       | 98.28%  |
| arm64 | 1        | 1.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 37       | 62.71%  |
| helloDesktop | 16       | 27.12%  |
| KDE5         | 4        | 6.78%   |
| XFCE         | 1        | 1.69%   |
| MATE         | 1        | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 37       | 63.79%  |
| X11     | 21       | 36.21%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 37       | 62.71%  |
| SLiM    | 16       | 27.12%  |
| SDDM    | 5        | 8.47%   |
| LightDM | 1        | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 62.71%  |
| en_US   | 16       | 27.12%  |
| zh_CN   | 3        | 5.08%   |
| C       | 3        | 5.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 48       | 82.76%  |
| BIOS | 10       | 17.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 32       | 54.24%  |
| Zfs    | 22       | 37.29%  |
| Cd9660 | 5        | 8.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 51       | 87.93%  |
| MBR     | 5        | 8.62%   |
| Unknown | 2        | 3.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 13       | 22.41%  |
| Lenovo                                     | 6        | 10.34%  |
| Dell                                       | 6        | 10.34%  |
| Gigabyte Technology                        | 4        | 6.9%    |
| ASUSTek Computer                           | 4        | 6.9%    |
| MSI                                        | 3        | 5.17%   |
| Hewlett-Packard                            | 3        | 5.17%   |
| ShenZhen MinWin Technology                 | 2        | 3.45%   |
| PAIQ                                       | 2        | 3.45%   |
| ASRock                                     | 2        | 3.45%   |
| YANYU                                      | 1        | 1.72%   |
| WlanCN                                     | 1        | 1.72%   |
| Techvision                                 | 1        | 1.72%   |
| Protectli                                  | 1        | 1.72%   |
| OEM                                        | 1        | 1.72%   |
| NEC Computers                              | 1        | 1.72%   |
| MAXSUN                                     | 1        | 1.72%   |
| Intel                                      | 1        | 1.72%   |
| GuoGuang                                   | 1        | 1.72%   |
| Google                                     | 1        | 1.72%   |
| Colorful YuGong Technology And Development | 1        | 1.72%   |
| Colorful Technology                        | 1        | 1.72%   |
| CNCTION-IAF-E3845                          | 1        | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                   | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 14       | 24.14%  |
| ShenZhen MinWin MW-NANO-APL-4L                         | 2        | 3.45%   |
| PAIQ EC3-BT19D4L                                       | 2        | 3.45%   |
| YANYU ITX-N29 VER:1.5 baytrail                         | 1        | 1.72%   |
| WlanCN 6000 Series                                     | 1        | 1.72%   |
| Techvision TVI7309X                                    | 1        | 1.72%   |
| Protectli FW6                                          | 1        | 1.72%   |
| OEM B85 JHS359                                         | 1        | 1.72%   |
| NEC Computers SHARKBAY                                 | 1        | 1.72%   |
| MSI MS-7C82                                            | 1        | 1.72%   |
| MSI MS-7C37                                            | 1        | 1.72%   |
| MSI MS-7972                                            | 1        | 1.72%   |
| MAXSUN MS-H110D4L FS M.2                               | 1        | 1.72%   |
| Lenovo YangTianW2090v-00                               | 1        | 1.72%   |
| Lenovo YangTianM6880N                                  | 1        | 1.72%   |
| Lenovo YangTianA8800T                                  | 1        | 1.72%   |
| Lenovo ThinkCentre M93p 10AA0020CN                     | 1        | 1.72%   |
| Lenovo SHARKBAY 0B98401 WIN                            | 1        | 1.72%   |
| Lenovo IdeaCentre B545 10100                           | 1        | 1.72%   |
| Intel X58                                              | 1        | 1.72%   |
| HP t620 PLUS Quad Core TC                              | 1        | 1.72%   |
| HP Slim Desktop S01-pF1xxx                             | 1        | 1.72%   |
| HP Compaq Elite 8300 USDT                              | 1        | 1.72%   |
| GuoGuang IC2M1028V-6                                   | 1        | 1.72%   |
| Google Guado                                           | 1        | 1.72%   |
| Gigabyte H410M S2 V2                                   | 1        | 1.72%   |
| Gigabyte GB-BACE-3150                                  | 1        | 1.72%   |
| Gigabyte GA-870-UD3P                                   | 1        | 1.72%   |
| Gigabyte AB350N-Gaming WIFI                            | 1        | 1.72%   |
| Dell Vostro 3667                                       | 1        | 1.72%   |
| Dell Precision WorkStation T5500                       | 1        | 1.72%   |
| Dell OptiPlex 755                                      | 1        | 1.72%   |
| Dell OptiPlex 7060                                     | 1        | 1.72%   |
| Dell OptiPlex 7010                                     | 1        | 1.72%   |
| Dell Inspiron 560s                                     | 1        | 1.72%   |
| Colorful YuGong And Development C.J1900A-BTC PLUS YV20 | 1        | 1.72%   |
| Colorful C.Q1900M PRO V20                              | 1        | 1.72%   |
| ASUS TUF GAMING X570-PRO                               | 1        | 1.72%   |
| ASUS TUF GAMING B550M-PLUS                             | 1        | 1.72%   |
| ASUS Maximus IX HERO                                   | 1        | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 14       | 24.14%  |
| Dell OptiPlex                           | 3        | 5.17%   |
| ShenZhen MinWin MW-NANO-APL-4L          | 2        | 3.45%   |
| PAIQ EC3-BT19D4L                        | 2        | 3.45%   |
| ASUS TUF                                | 2        | 3.45%   |
| YANYU ITX-N29                           | 1        | 1.72%   |
| WlanCN 6000                             | 1        | 1.72%   |
| Techvision TVI7309X                     | 1        | 1.72%   |
| Protectli FW6                           | 1        | 1.72%   |
| OEM B85                                 | 1        | 1.72%   |
| NEC Computers SHARKBAY                  | 1        | 1.72%   |
| MSI MS-7C82                             | 1        | 1.72%   |
| MSI MS-7C37                             | 1        | 1.72%   |
| MSI MS-7972                             | 1        | 1.72%   |
| MAXSUN MS-H110D4L                       | 1        | 1.72%   |
| Lenovo YangTianW2090v-00                | 1        | 1.72%   |
| Lenovo YangTianM6880N                   | 1        | 1.72%   |
| Lenovo YangTianA8800T                   | 1        | 1.72%   |
| Lenovo ThinkCentre                      | 1        | 1.72%   |
| Lenovo SHARKBAY                         | 1        | 1.72%   |
| Lenovo IdeaCentre                       | 1        | 1.72%   |
| Intel X58                               | 1        | 1.72%   |
| HP t620                                 | 1        | 1.72%   |
| HP Slim                                 | 1        | 1.72%   |
| HP Compaq                               | 1        | 1.72%   |
| GuoGuang IC2M1028V-6                    | 1        | 1.72%   |
| Google Guado                            | 1        | 1.72%   |
| Gigabyte H410M                          | 1        | 1.72%   |
| Gigabyte GB-BACE-3150                   | 1        | 1.72%   |
| Gigabyte GA-870-UD3P                    | 1        | 1.72%   |
| Gigabyte AB350N-Gaming                  | 1        | 1.72%   |
| Dell Vostro                             | 1        | 1.72%   |
| Dell Precision                          | 1        | 1.72%   |
| Dell Inspiron                           | 1        | 1.72%   |
| Colorful YuGong And Development C.J1900 | 1        | 1.72%   |
| Colorful C.Q1900M                       | 1        | 1.72%   |
| ASUS Maximus                            | 1        | 1.72%   |
| ASUS All                                | 1        | 1.72%   |
| ASRock Q1900M                           | 1        | 1.72%   |
| ASRock A320M-ITX                        | 1        | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 8        | 13.79%  |
| 2019 | 8        | 13.79%  |
| 2020 | 6        | 10.34%  |
| 2018 | 5        | 8.62%   |
| 2017 | 5        | 8.62%   |
| 2014 | 5        | 8.62%   |
| 2016 | 4        | 6.9%    |
| 2012 | 4        | 6.9%    |
| 2013 | 3        | 5.17%   |
| 2022 | 2        | 3.45%   |
| 2015 | 2        | 3.45%   |
| 2011 | 2        | 3.45%   |
| 2010 | 2        | 3.45%   |
| 2008 | 1        | 1.72%   |
| 2007 | 1        | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 58       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 96.55%  |
| Yes  | 2        | 3.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 22       | 37.29%  |
| 4.01-8.0   | 13       | 22.03%  |
| 16.01-24.0 | 9        | 15.25%  |
| 2.01-3.0   | 7        | 11.86%  |
| 32.01-64.0 | 6        | 10.17%  |
| 1.01-2.0   | 1        | 1.69%   |
| 0.51-1.0   | 1        | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 38       | 64.41%  |
| 0.51-1.0 | 14       | 23.73%  |
| 1.01-2.0 | 6        | 10.17%  |
| 3.01-4.0 | 1        | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 63.33%  |
| 2      | 9        | 15%     |
| 0      | 6        | 10%     |
| 5      | 3        | 5%      |
| 3      | 3        | 5%      |
| 4      | 1        | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 83.05%  |
| Yes       | 10       | 16.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 57       | 98.28%  |
| No        | 1        | 1.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 77.59%  |
| Yes       | 13       | 22.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 82.76%  |
| Yes       | 10       | 17.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 58       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Shanghai         | 7        | 11.11%  |
| Beijing          | 7        | 11.11%  |
| Chengdu          | 5        | 7.94%   |
| Shenzhen         | 4        | 6.35%   |
| Guangzhou        | 3        | 4.76%   |
| Zhengzhou        | 2        | 3.17%   |
| Xi'an            | 2        | 3.17%   |
| Qingdao          | 2        | 3.17%   |
| Jinrongjie       | 2        | 3.17%   |
| Hangzhou         | 2        | 3.17%   |
| Zhongshan        | 1        | 1.59%   |
| Yancheng         | 1        | 1.59%   |
| Xicheng District | 1        | 1.59%   |
| Xiamen           | 1        | 1.59%   |
| Wuhan            | 1        | 1.59%   |
| Tongshan         | 1        | 1.59%   |
| Tieling          | 1        | 1.59%   |
| Suzhou           | 1        | 1.59%   |
| Shahekou         | 1        | 1.59%   |
| Qinnan           | 1        | 1.59%   |
| Qingpu           | 1        | 1.59%   |
| Putuo            | 1        | 1.59%   |
| Ningbo           | 1        | 1.59%   |
| Nanjing          | 1        | 1.59%   |
| Liuzhou          | 1        | 1.59%   |
| Kunming          | 1        | 1.59%   |
| Kuiju            | 1        | 1.59%   |
| Hongkou          | 1        | 1.59%   |
| Guli             | 1        | 1.59%   |
| Gaoqiao          | 1        | 1.59%   |
| Gaoleshan        | 1        | 1.59%   |
| Fuzhou           | 1        | 1.59%   |
| Dalian           | 1        | 1.59%   |
| Chaoyang Shi     | 1        | 1.59%   |
| Changchun        | 1        | 1.59%   |
| Bijie            | 1        | 1.59%   |
| Baiyun           | 1        | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 16.22%  |
| Samsung Electronics | 10       | 14     | 13.51%  |
| WDC                 | 9        | 20     | 12.16%  |
| Intel               | 7        | 7      | 9.46%   |
| SanDisk             | 5        | 6      | 6.76%   |
| Toshiba             | 4        | 4      | 5.41%   |
| Hitachi             | 3        | 3      | 4.05%   |
| China               | 3        | 5      | 4.05%   |
| Transcend           | 2        | 2      | 2.7%    |
| HGST                | 2        | 3      | 2.7%    |
| tigo                | 1        | 1      | 1.35%   |
| Ramsta              | 1        | 1      | 1.35%   |
| Plextor             | 1        | 2      | 1.35%   |
| Netac               | 1        | 1      | 1.35%   |
| Micron Technology   | 1        | 2      | 1.35%   |
| LITEONIT            | 1        | 1      | 1.35%   |
| Lenovo              | 1        | 1      | 1.35%   |
| KIOXIA-EXCERIA      | 1        | 2      | 1.35%   |
| Kingston            | 1        | 1      | 1.35%   |
| KingSpec            | 1        | 1      | 1.35%   |
| FREEBSD             | 1        | 1      | 1.35%   |
| FORESEE             | 1        | 1      | 1.35%   |
| Faspeed             | 1        | 1      | 1.35%   |
| Crucial             | 1        | 1      | 1.35%   |
| Colorful            | 1        | 1      | 1.35%   |
| BIWIN               | 1        | 3      | 1.35%   |
| Apacer              | 1        | 1      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST1000DM003-1SB102 1TB  | 3        | 3.49%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 2.33%   |
| Intel SSDSA2SH032G1GN 32GB      | 2        | 2.33%   |
| WDC WUH721414ALE6L4 14TB        | 1        | 1.16%   |
| WDC WDS500G2B0C-00PXH0 500GB    | 1        | 1.16%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 1.16%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1        | 1.16%   |
| WDC WD5000LPCX-00VHAT0 500GB    | 1        | 1.16%   |
| WDC WD4005FZBX-00K5WB0 4TB      | 1        | 1.16%   |
| WDC WD30EZRZ-00WN9B0 3TB        | 1        | 1.16%   |
| WDC WD20SPZX-22UA7T0 2TB        | 1        | 1.16%   |
| WDC WD2003FYYS-007BA0 2TB       | 1        | 1.16%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1        | 1.16%   |
| WDC WD1600AAJS-22L7A0 160GB     | 1        | 1.16%   |
| WDC WD120EMAZ-11BLFA0 12TB      | 1        | 1.16%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1        | 1.16%   |
| WDC WD10SPCX-00KHST0 1TB        | 1        | 1.16%   |
| WDC WD10EZEX-21WN4A0 1TB        | 1        | 1.16%   |
| WDC WD10EJRX-89N74Y0 1TB        | 1        | 1.16%   |
| WDC WD10EARS-003BB1 1TB         | 1        | 1.16%   |
| Transcend TS4GCF150 4GB         | 1        | 1.16%   |
| Transcend TS128GMTS400 128GB    | 1        | 1.16%   |
| Toshiba MQ04ABF100 1TB          | 1        | 1.16%   |
| Toshiba DT01ACA100 1TB          | 1        | 1.16%   |
| Toshiba DT01ACA050 500GB        | 1        | 1.16%   |
| Toshiba A100 240GB              | 1        | 1.16%   |
| tigo SSD 480GB                  | 1        | 1.16%   |
| Seagate ST500LM000-1EJ162 500GB | 1        | 1.16%   |
| Seagate ST500DM002-1SB10A 500GB | 1        | 1.16%   |
| Seagate ST3500418AS 500GB       | 1        | 1.16%   |
| Seagate ST3500312CS 500GB       | 1        | 1.16%   |
| Seagate ST3320418AS 320GB       | 1        | 1.16%   |
| Seagate ST31500541AS 1.5TB      | 1        | 1.16%   |
| Seagate ST31000528AS 1TB        | 1        | 1.16%   |
| Seagate ST3000DM007-1WY10G 3TB  | 1        | 1.16%   |
| Seagate ST2000VN004-2E4164 2TB  | 1        | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB  | 1        | 1.16%   |
| SanDisk SSD G5 BICS4 1TB        | 1        | 1.16%   |
| SanDisk SDSSDA120G 120GB        | 1        | 1.16%   |
| SanDisk SDSA6AM-008G-1006 8GB   | 1        | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 12       | 16     | 41.38%  |
| WDC     | 9        | 18     | 31.03%  |
| Toshiba | 3        | 3      | 10.34%  |
| Hitachi | 3        | 3      | 10.34%  |
| HGST    | 2        | 3      | 6.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 7      | 15.79%  |
| Intel               | 6        | 6      | 15.79%  |
| SanDisk             | 5        | 6      | 13.16%  |
| China               | 3        | 5      | 7.89%   |
| Transcend           | 2        | 2      | 5.26%   |
| Toshiba             | 1        | 1      | 2.63%   |
| tigo                | 1        | 1      | 2.63%   |
| Ramsta              | 1        | 1      | 2.63%   |
| Netac               | 1        | 1      | 2.63%   |
| Micron Technology   | 1        | 2      | 2.63%   |
| LITEONIT            | 1        | 1      | 2.63%   |
| Lenovo              | 1        | 1      | 2.63%   |
| KIOXIA-EXCERIA      | 1        | 2      | 2.63%   |
| Kingston            | 1        | 1      | 2.63%   |
| KingSpec            | 1        | 1      | 2.63%   |
| FREEBSD             | 1        | 1      | 2.63%   |
| FORESEE             | 1        | 1      | 2.63%   |
| Faspeed             | 1        | 1      | 2.63%   |
| Colorful            | 1        | 1      | 2.63%   |
| BIWIN               | 1        | 3      | 2.63%   |
| Apacer              | 1        | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 36       | 46     | 51.43%  |
| HDD  | 24       | 43     | 34.29%  |
| NVMe | 10       | 13     | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 51       | 89     | 83.61%  |
| NVMe | 10       | 13     | 16.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 44       | 59     | 65.67%  |
| 0.51-1.0   | 14       | 17     | 20.9%   |
| 1.01-2.0   | 4        | 5      | 5.97%   |
| 2.01-3.0   | 2        | 3      | 2.99%   |
| 3.01-4.0   | 1        | 1      | 1.49%   |
| 10.01-20.0 | 1        | 2      | 1.49%   |
| 4.01-10.0  | 1        | 2      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 17       | 28.33%  |
| 1-20       | 17       | 28.33%  |
| 251-500    | 8        | 13.33%  |
| 21-50      | 8        | 13.33%  |
| 51-100     | 7        | 11.67%  |
| 501-1000   | 2        | 3.33%   |
| 1001-2000  | 1        | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 54       | 91.53%  |
| 21-50   | 3        | 5.08%   |
| 51-100  | 2        | 3.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1600AAJS-22L7A0 160GB   | 1        | 1      | 9.09%   |
| WDC WD10EJRX-89N74Y0 1TB      | 1        | 1      | 9.09%   |
| Seagate ST3320418AS 320GB     | 1        | 2      | 9.09%   |
| Seagate ST31500541AS 1.5TB    | 1        | 1      | 9.09%   |
| Seagate ST31000528AS 1TB      | 1        | 1      | 9.09%   |
| Intel SSDSA2M120G2GC 120GB    | 1        | 1      | 9.09%   |
| Hitachi HTS723232A7A364 320GB | 1        | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB    | 1        | 1      | 9.09%   |
| Colorful SL500 640GB          | 1        | 1      | 9.09%   |
| China XJH-32GB                | 1        | 1      | 9.09%   |
| BIWIN SSD 32GB                | 1        | 3      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 3        | 4      | 27.27%  |
| WDC      | 2        | 2      | 18.18%  |
| Intel    | 1        | 1      | 9.09%   |
| Hitachi  | 1        | 1      | 9.09%   |
| HGST     | 1        | 1      | 9.09%   |
| Colorful | 1        | 1      | 9.09%   |
| China    | 1        | 1      | 9.09%   |
| BIWIN    | 1        | 3      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 4      | 42.86%  |
| WDC     | 2        | 2      | 28.57%  |
| Hitachi | 1        | 1      | 14.29%  |
| HGST    | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 8      | 63.64%  |
| SSD  | 4        | 6      | 36.36%  |

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
| Works    | 46       | 87     | 79.31%  |
| Malfunc  | 11       | 14     | 18.97%  |
| Detected | 1        | 1      | 1.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 49       | 71.01%  |
| AMD                       | 8        | 11.59%  |
| Samsung Electronics       | 5        | 7.25%   |
| SanDisk                   | 2        | 2.9%    |
| Broadcom / LSI            | 2        | 2.9%    |
| Micron/Crucial Technology | 1        | 1.45%   |
| Lite-On Technology        | 1        | 1.45%   |
| ASMedia Technology        | 1        | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7        | 8.75%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6        | 7.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5        | 6.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5        | 6.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3        | 3.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3        | 3.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3        | 3.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 3.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2        | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 2.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 2.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 2.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2        | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 2.5%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2        | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 2.5%    |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 1        | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 1.25%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 1.25%   |
| Intel SSD 660P Series                                                            | 1        | 1.25%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 1.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 1.25%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1        | 1.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 1.25%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1        | 1.25%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 1.25%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 1.25%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1        | 1.25%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 1.25%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 1.25%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 1        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1        | 1.25%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1        | 1.25%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 1        | 1.25%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1        | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 69.01%  |
| NVMe | 10       | 14.08%  |
| IDE  | 9        | 12.68%  |
| RAID | 2        | 2.82%   |
| SAS  | 1        | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 49       | 84.48%  |
| AMD    | 8        | 13.79%  |
| ARM    | 1        | 1.72%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 6        | 10.34%  |
| Intel Atom CPU D525 @ 1.80GHz               | 3        | 5.17%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 2        | 3.45%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 3.45%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2        | 3.45%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2        | 3.45%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 1.72%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 1.72%   |
| Intel Xeon                                  | 1        | 1.72%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.72%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1        | 1.72%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.72%   |
| Intel Pentium CPU G3460T @ 3.00GHz          | 1        | 1.72%   |
| Intel Genuine CPU 0000 @ 2.50GHz            | 1        | 1.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 1.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 1.72%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.72%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.72%   |
| Intel Core i3-8100T CPU @ 3.10GHz           | 1        | 1.72%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1        | 1.72%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 1.72%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.72%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.72%   |
| Intel Core 2 Duo                            | 1        | 1.72%   |
| Intel Celeron N5105 @ 2.00GHz               | 1        | 1.72%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 1        | 1.72%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 1        | 1.72%   |
| Intel Celeron CPU J3160 @ 1.60GHz           | 1        | 1.72%   |
| Intel Celeron CPU G1820 @ 2.70GHz           | 1        | 1.72%   |
| Intel Celeron CPU 3965U @ 2.20GHz           | 1        | 1.72%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1        | 1.72%   |
| Intel Atom CPU D2550 @ 1.86GHz              | 1        | 1.72%   |
| Intel Atom CPU C3336 @ 1.50GHz              | 1        | 1.72%   |
| ARM Cortex-A53 r0p4                         | 1        | 1.72%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 18       | 31.03%  |
| Intel Atom              | 6        | 10.34%  |
| Intel Pentium           | 5        | 8.62%   |
| Intel Core i7           | 5        | 8.62%   |
| Intel Core i5           | 4        | 6.9%    |
| Intel Core i3           | 4        | 6.9%    |
| Intel Xeon              | 3        | 5.17%   |
| Intel Core 2 Duo        | 2        | 3.45%   |
| AMD Ryzen 5             | 2        | 3.45%   |
| Intel Pentium Dual-Core | 1        | 1.72%   |
| Intel Genuine           | 1        | 1.72%   |
| ARM Cortex              | 1        | 1.72%   |
| AMD Ryzen 9             | 1        | 1.72%   |
| AMD Ryzen 7             | 1        | 1.72%   |
| AMD Ryzen 3             | 1        | 1.72%   |
| AMD Phenom II X4        | 1        | 1.72%   |
| AMD GX                  | 1        | 1.72%   |
| AMD A10                 | 1        | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 32       | 55.17%  |
| 2       | 20       | 34.48%  |
| 12      | 2        | 3.45%   |
| 24      | 1        | 1.72%   |
| 16      | 1        | 1.72%   |
| 8       | 1        | 1.72%   |
| Unknown | 1        | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 57       | 98.28%  |
| Unknown | 1        | 1.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 41       | 70.69%  |
| 2       | 16       | 27.59%  |
| Unknown | 1        | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 9        | 15.52%  |
| KabyLake      | 8        | 13.79%  |
| Haswell       | 6        | 10.34%  |
| Bonnell       | 5        | 8.62%   |
| Goldmont plus | 3        | 5.17%   |
| Goldmont      | 3        | 5.17%   |
| CometLake     | 3        | 5.17%   |
| Zen 2         | 2        | 3.45%   |
| Zen           | 2        | 3.45%   |
| Westmere      | 2        | 3.45%   |
| Skylake       | 2        | 3.45%   |
| Penryn        | 2        | 3.45%   |
| IvyBridge     | 2        | 3.45%   |
| Unknown       | 2        | 3.45%   |
| Zen 3         | 1        | 1.72%   |
| SandyBridge   | 1        | 1.72%   |
| Piledriver    | 1        | 1.72%   |
| K10           | 1        | 1.72%   |
| Jaguar        | 1        | 1.72%   |
| Core          | 1        | 1.72%   |
| Broadwell     | 1        | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 40       | 72.73%  |
| Nvidia | 8        | 14.55%  |
| AMD    | 7        | 12.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7        | 12.5%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 7.14%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3        | 5.36%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 5.36%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 5.36%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3        | 5.36%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2        | 3.57%   |
| Intel HD Graphics 620                                                                    | 2        | 3.57%   |
| Intel HD Graphics 500                                                                    | 2        | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 3.57%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 3.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.79%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 1.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.79%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.79%   |
| Intel HD Graphics 5500                                                                   | 1        | 1.79%   |
| Intel HD Graphics 530                                                                    | 1        | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.79%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.79%   |
| AMD Trinity [Radeon HD 7660D]                                                            | 1        | 1.79%   |
| AMD RV620 GL [FirePro 2260]                                                              | 1        | 1.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 1.79%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 1.79%   |
| AMD Caicos [Radeon HD 6450A/7450A]                                                       | 1        | 1.79%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1        | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 36       | 62.07%  |
| 1 x Nvidia | 8        | 13.79%  |
| 1 x AMD    | 6        | 10.34%  |
| 2 x Intel  | 4        | 6.9%    |
| Other      | 3        | 5.17%   |
| 2 x AMD    | 1        | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 48       | 82.76%  |
| Proprietary | 5        | 8.62%   |
| Unknown     | 5        | 8.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 86.21%  |
| 7.01-8.0   | 2        | 3.45%   |
| 0.01-0.5   | 2        | 3.45%   |
| 3.01-4.0   | 1        | 1.72%   |
| 1.01-2.0   | 1        | 1.72%   |
| 8.01-16.0  | 1        | 1.72%   |
| 0.51-1.0   | 1        | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Dell    | 3        | 18.75%  |
| AOC     | 3        | 18.75%  |
| Lenovo  | 2        | 12.5%   |
| ZL_     | 1        | 6.25%   |
| Philips | 1        | 6.25%   |
| Mi      | 1        | 6.25%   |
| Haier   | 1        | 6.25%   |
| GRR     | 1        | 6.25%   |
| CAN     | 1        | 6.25%   |
| BenQ    | 1        | 6.25%   |
| Acer    | 1        | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch   | 1        | 6.25%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch        | 1        | 6.25%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch     | 1        | 6.25%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch  | 1        | 6.25%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch    | 1        | 6.25%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch | 1        | 6.25%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch            | 1        | 6.25%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch        | 1        | 6.25%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch        | 1        | 6.25%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch        | 1        | 6.25%   |
| CAN F55C CAN0055 3840x2160 1210x680mm 54.6-inch          | 1        | 6.25%   |
| BenQ FP91G+ BNQ76A6 1280x1024 380x300mm 19.1-inch        | 1        | 6.25%   |
| AOC Q27P1B AOC2701 1920x1080 600x340mm 27.2-inch         | 1        | 6.25%   |
| AOC 2778X AOC2778 2560x1440 600x340mm 27.2-inch          | 1        | 6.25%   |
| AOC 2479W AOC2479 1920x1080 520x290mm 23.4-inch          | 1        | 6.25%   |
| Acer G195WV ACR0263 1440x900 410x260mm 19.1-inch         | 1        | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 8        | 50%     |
| 2560x1440 (QHD)  | 3        | 18.75%  |
| 1440x900 (WXGA+) | 3        | 18.75%  |
| 3840x2160 (4K)   | 1        | 6.25%   |
| 1280x1024 (SXGA) | 1        | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 4        | 25%     |
| 23     | 3        | 18.75%  |
| 19     | 3        | 18.75%  |
| 24     | 2        | 12.5%   |
| 21     | 2        | 12.5%   |
| 54     | 1        | 6.25%   |
| 18     | 1        | 6.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 56.25%  |
| 401-500     | 4        | 25%     |
| 351-400     | 2        | 12.5%   |
| 1001-1500   | 1        | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 12       | 75%     |
| 16/10 | 3        | 18.75%  |
| 5/4   | 1        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 43.75%  |
| 301-350        | 4        | 25%     |
| 151-200        | 4        | 25%     |
| More than 1000 | 1        | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 68.75%  |
| 101-120 | 5        | 31.25%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 42       | 71.19%  |
| 1     | 17       | 28.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 38       | 51.35%  |
| Realtek Semiconductor    | 29       | 39.19%  |
| Qualcomm Atheros         | 3        | 4.05%   |
| Broadcom                 | 2        | 2.7%    |
| Ralink Technology        | 1        | 1.35%   |
| Marvell Technology Group | 1        | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 29.41%  |
| Intel I211 Gigabit Network Connection                             | 13       | 15.29%  |
| Intel 82583V Gigabit Network Connection                           | 4        | 4.71%   |
| Intel I350 Gigabit Network Connection                             | 3        | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.35%   |
| Intel Wireless 7260                                               | 2        | 2.35%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 2.35%   |
| Intel I210 Gigabit Network Connection                             | 2        | 2.35%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.35%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.18%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.18%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.18%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 1.18%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter   | 1        | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 1.18%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.18%   |
| Intel Wireless 3165                                               | 1        | 1.18%   |
| Intel Wireless 3160                                               | 1        | 1.18%   |
| Intel Ethernet Connection X553 1GbE                               | 1        | 1.18%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.18%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.18%   |
| Intel 82580 Gigabit Network Connection                            | 1        | 1.18%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.18%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.18%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.18%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.18%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 46.67%  |
| Realtek Semiconductor | 3        | 20%     |
| Qualcomm Atheros      | 3        | 20%     |
| Ralink Technology     | 1        | 6.67%   |
| Broadcom              | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                             | 2        | 13.33%  |
| Intel Wi-Fi 6 AX200                                             | 2        | 13.33%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 6.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 6.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1        | 6.67%   |
| Ralink RT5370 Wireless Adapter                                  | 1        | 6.67%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 6.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1        | 6.67%   |
| Intel Wireless 3165                                             | 1        | 6.67%   |
| Intel Wireless 3160                                             | 1        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 6.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 33       | 52.38%  |
| Realtek Semiconductor    | 28       | 44.44%  |
| Marvell Technology Group | 1        | 1.59%   |
| Broadcom                 | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 35.71%  |
| Intel I211 Gigabit Network Connection                             | 13       | 18.57%  |
| Intel 82583V Gigabit Network Connection                           | 4        | 5.71%   |
| Intel I350 Gigabit Network Connection                             | 3        | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.86%   |
| Intel I210 Gigabit Network Connection                             | 2        | 2.86%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.43%   |
| Intel Ethernet Connection X553 1GbE                               | 1        | 1.43%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.43%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.43%   |
| Intel 82580 Gigabit Network Connection                            | 1        | 1.43%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.43%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.43%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 81.43%  |
| WiFi     | 13       | 18.57%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 91.8%   |
| WiFi     | 5        | 8.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 27       | 46.55%  |
| 1     | 9        | 15.52%  |
| 4     | 8        | 13.79%  |
| 6     | 7        | 12.07%  |
| 5     | 5        | 8.62%   |
| 7     | 1        | 1.72%   |
| 0     | 1        | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 78.69%  |
| Yes  | 13       | 21.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 50%     |
| Realtek Semiconductor           | 2        | 20%     |
| Qualcomm Atheros Communications | 1        | 10%     |
| Cambridge Silicon Radio         | 1        | 10%     |
| Apple                           | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 2        | 20%     |
| Intel AX200 Bluetooth                                       | 2        | 20%     |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 10%     |
| Realtek  Bluetooth 4.0 Adapter                              | 1        | 10%     |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 10%     |
| Apple Apple Broadcom Built-in Bluetooth                     | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 41       | 69.49%  |
| AMD                    | 9        | 15.25%  |
| Nvidia                 | 8        | 13.56%  |
| Generalplus Technology | 1        | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5        | 7.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4        | 6.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 4.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 4.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3        | 4.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 4.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 4.55%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 3.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 3.03%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 3.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 3.03%   |
| AMD FCH Azalia Controller                                                                         | 2        | 3.03%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 1.52%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 1.52%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 1.52%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 1.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.52%   |
| Intel Jasper Lake HD Audio                                                                        | 1        | 1.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 1.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.52%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1        | 1.52%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.52%   |
| Generalplus Technology USB Audio Device                                                           | 1        | 1.52%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 1.52%   |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 1.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1        | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 1.52%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1        | 1.52%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1        | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 16       | 25%     |
| Unknown             | 10       | 15.63%  |
| Micron Technology   | 9        | 14.06%  |
| Kingston            | 9        | 14.06%  |
| SK hynix            | 5        | 7.81%   |
| A-DATA Technology   | 4        | 6.25%   |
| Nanya Technology    | 2        | 3.13%   |
| G.Skill             | 2        | 3.13%   |
| Unknown             | 2        | 3.13%   |
| Team                | 1        | 1.56%   |
| Ramsta              | 1        | 1.56%   |
| Ramaxel Technology  | 1        | 1.56%   |
| Elpida              | 1        | 1.56%   |
| Corsair             | 1        | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3        | 4.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 2        | 2.99%   |
| Unknown                                                    | 2        | 2.99%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s              | 1        | 1.49%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                  | 1        | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                 | 1        | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                 | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 1.49%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                   | 1        | 1.49%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s         | 1        | 1.49%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM 1066MT/s            | 1        | 1.49%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 1.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1        | 1.49%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 1        | 1.49%   |
| SK hynix RAM 8ATF1G64HZ-2G3A1 8GB DIMM DDR4 2400MT/s       | 1        | 1.49%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 1333MT/s        | 1        | 1.49%   |
| Samsung RAM M471B5273DM0-CH9 4GB DIMM DDR3 1333MT/s        | 1        | 1.49%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB DIMM DDR3 1333MT/s        | 1        | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M471B1G73QHO-YKO 4GB SODIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB DDR3 1600MT/s          | 1        | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1        | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1        | 1.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s      | 1        | 1.49%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s        | 1        | 1.49%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.49%   |
| Ramsta RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 1.49%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Nanya RAM NT8GC64B8HB0NS-DI 8GB SODIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Micron RAM Module 8192MB DIMM DDR4 3200MT/s                | 1        | 1.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 1        | 1.49%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s        | 1        | 1.49%   |
| Micron RAM 8ATF51264AZ-2G1A1 4GB SODIMM DDR4 2133MT/s      | 1        | 1.49%   |
| Micron RAM 4JTF25664AZ-1G6E1 2GB DIMM DDR3 1600MT/s        | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 28       | 50%     |
| DDR4    | 23       | 41.07%  |
| DDR2    | 4        | 7.14%   |
| Unknown | 1        | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 33       | 57.89%  |
| SODIMM  | 22       | 38.6%   |
| Unknown | 2        | 3.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 22       | 36.07%  |
| 8192  | 18       | 29.51%  |
| 2048  | 12       | 19.67%  |
| 16384 | 8        | 13.11%  |
| 1024  | 1        | 1.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 16       | 25.4%   |
| 1333  | 9        | 14.29%  |
| 2133  | 8        | 12.7%   |
| 2400  | 6        | 9.52%   |
| 2667  | 5        | 7.94%   |
| 3200  | 4        | 6.35%   |
| 800   | 4        | 6.35%   |
| 2666  | 3        | 4.76%   |
| 1334  | 3        | 4.76%   |
| 2933  | 2        | 3.17%   |
| 1867  | 1        | 1.59%   |
| 1066  | 1        | 1.59%   |
| 667   | 1        | 1.59%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 2        | 66.67%  |
| Z-Star Microelectronics | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Lenovo USB2.0 UVC Camera | 1        | 33.33%  |
| Logitech Webcam C170            | 1        | 33.33%  |
| Logitech C670i FHD Webcam       | 1        | 33.33%  |

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
| 1     | 26       | 44.83%  |
| 0     | 24       | 41.38%  |
| 2     | 8        | 13.79%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 30       | 75%     |
| Net/wireless             | 6        | 15%     |
| Card reader              | 2        | 5%      |
| Sound                    | 1        | 2.5%    |
| Net/ethernet             | 1        | 2.5%    |

