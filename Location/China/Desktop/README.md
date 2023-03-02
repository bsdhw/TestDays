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

Total: 102

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [815cd70e71](https://bsd-hardware.info/?probe=815cd70e71) | Feb 25, 2023 |
| Unknown       | Unknown                     | [866ff788f9](https://bsd-hardware.info/?probe=866ff788f9) | Feb 23, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | [4cd5bcdfed](https://bsd-hardware.info/?probe=4cd5bcdfed) | Feb 18, 2023 |
| Dell          | 0KYJ8C A02                  | [854d373499](https://bsd-hardware.info/?probe=854d373499) | Feb 16, 2023 |
| Dell          | 0K240Y A01                  | [d9f16ef94b](https://bsd-hardware.info/?probe=d9f16ef94b) | Jan 18, 2023 |
| Dell          | 0KYJ8C A02                  | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Dell          | 0KYJ8C A02                  | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| TOPFEEL       | H110D4-P1                   | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Lenovo        | YangTianM6880N              | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| Centerm       | GA690-2 2                   | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| AMD           | Inagua CRB                  | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| Unknown       | Unknown                     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Unknown       | Unknown                     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Dell          | 0KYJ8C A02                  | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| Dell          | 0KYJ8C A02                  | [12493c3802](https://bsd-hardware.info/?probe=12493c3802) | Sep 26, 2022 |
| Unknown       | Unknown                     | [199ad16750](https://bsd-hardware.info/?probe=199ad16750) | Sep 21, 2022 |
| Gigabyte      | H410M S2 V2                 | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
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
| helloSystem 0.7.0 | 9        | 10.47%  |
| OPNsense 21.7.1   | 6        | 6.98%   |
| OPNsense 21.7.3   | 4        | 4.65%   |
| OPNsense 21.1.7   | 4        | 4.65%   |
| helloSystem 0.5.0 | 4        | 4.65%   |
| FreeBSD 13.1-p2   | 4        | 4.65%   |
| OPNsense 23.1.1   | 3        | 3.49%   |
| OPNsense 22.7.5   | 3        | 3.49%   |
| OPNsense 21.7.5   | 3        | 3.49%   |
| OPNsense 21.7.2   | 3        | 3.49%   |
| OPNsense 22.7.2   | 2        | 2.33%   |
| OPNsense 22.1.4   | 2        | 2.33%   |
| OPNsense 22.1.2   | 2        | 2.33%   |
| OPNsense 22.1.10  | 2        | 2.33%   |
| OPNsense 21.1.6   | 2        | 2.33%   |
| OPNsense 21.1.3   | 2        | 2.33%   |
| OPNsense 21.1     | 2        | 2.33%   |
| helloSystem 0.6.0 | 2        | 2.33%   |
| helloSystem 0.4.0 | 2        | 2.33%   |
| OPNsense 22.7.9   | 1        | 1.16%   |
| OPNsense 22.7.8   | 1        | 1.16%   |
| OPNsense 22.7.6   | 1        | 1.16%   |
| OPNsense 22.7.4   | 1        | 1.16%   |
| OPNsense 22.7.3   | 1        | 1.16%   |
| OPNsense 22.7.11  | 1        | 1.16%   |
| OPNsense 22.1.8   | 1        | 1.16%   |
| OPNsense 22.1.3   | 1        | 1.16%   |
| OPNsense 21.7.8   | 1        | 1.16%   |
| OPNsense 21.7.7   | 1        | 1.16%   |
| OPNsense 21.7.6   | 1        | 1.16%   |
| OPNsense 21.7.4   | 1        | 1.16%   |
| OPNsense 21.1.4   | 1        | 1.16%   |
| OPNsense 21.1.2   | 1        | 1.16%   |
| OPNsense 21.1.1   | 1        | 1.16%   |
| helloSystem 0.8.0 | 1        | 1.16%   |
| GhostBSD 21.08.27 | 1        | 1.16%   |
| FreeBSD 13.1-RC4  | 1        | 1.16%   |
| FreeBSD 13.1-p5   | 1        | 1.16%   |
| FreeBSD 13.1-p3   | 1        | 1.16%   |
| FreeBSD 13.0-RC5  | 1        | 1.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 40       | 57.14%  |
| helloSystem | 18       | 25.71%  |
| FreeBSD     | 11       | 15.71%  |
| GhostBSD    | 1        | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 68       | 98.55%  |
| arm64 | 1        | 1.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 44       | 62.86%  |
| helloDesktop | 18       | 25.71%  |
| KDE5         | 4        | 5.71%   |
| XFCE         | 1        | 1.43%   |
| MATE         | 1        | 1.43%   |
| i3           | 1        | 1.43%   |
| GNUstep      | 1        | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 44       | 63.77%  |
| X11     | 25       | 36.23%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 45       | 64.29%  |
| SLiM    | 19       | 27.14%  |
| SDDM    | 5        | 7.14%   |
| LightDM | 1        | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 61.43%  |
| en_US   | 18       | 25.71%  |
| zh_CN   | 5        | 7.14%   |
| C       | 4        | 5.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 59       | 85.51%  |
| BIOS | 10       | 14.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 37       | 52.86%  |
| Zfs    | 26       | 37.14%  |
| Cd9660 | 7        | 10%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 62       | 89.86%  |
| MBR     | 5        | 7.25%   |
| Unknown | 2        | 2.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 16       | 23.19%  |
| Lenovo                                     | 7        | 10.14%  |
| Dell                                       | 7        | 10.14%  |
| MSI                                        | 4        | 5.8%    |
| Gigabyte Technology                        | 4        | 5.8%    |
| ASUSTek Computer                           | 4        | 5.8%    |
| ShenZhen MinWin Technology                 | 3        | 4.35%   |
| Hewlett-Packard                            | 3        | 4.35%   |
| PAIQ                                       | 2        | 2.9%    |
| ASRock                                     | 2        | 2.9%    |
| YANYU                                      | 1        | 1.45%   |
| WlanCN                                     | 1        | 1.45%   |
| TOPFEEL                                    | 1        | 1.45%   |
| Techvision                                 | 1        | 1.45%   |
| Protectli                                  | 1        | 1.45%   |
| ONDA                                       | 1        | 1.45%   |
| OEM                                        | 1        | 1.45%   |
| NEC Computers                              | 1        | 1.45%   |
| MAXSUN                                     | 1        | 1.45%   |
| Intel                                      | 1        | 1.45%   |
| GuoGuang                                   | 1        | 1.45%   |
| Google                                     | 1        | 1.45%   |
| Colorful YuGong Technology And Development | 1        | 1.45%   |
| Colorful Technology                        | 1        | 1.45%   |
| CNCTION-IAF-E3845                          | 1        | 1.45%   |
| Centerm                                    | 1        | 1.45%   |
| AMD                                        | 1        | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 17       | 24.64%  |
| ShenZhen MinWin MW-NANO-APL-4L     | 3        | 4.35%   |
| PAIQ EC3-BT19D4L                   | 2        | 2.9%    |
| YANYU ITX-N29 VER:1.5 baytrail     | 1        | 1.45%   |
| WlanCN 6000 Series                 | 1        | 1.45%   |
| TOPFEEL Topone series              | 1        | 1.45%   |
| Techvision TVI7309X                | 1        | 1.45%   |
| Protectli FW6                      | 1        | 1.45%   |
| ONDA N78G5D3 Ver:5.00              | 1        | 1.45%   |
| OEM B85 JHS359                     | 1        | 1.45%   |
| NEC Computers SHARKBAY             | 1        | 1.45%   |
| MSI MS-7C82                        | 1        | 1.45%   |
| MSI MS-7C37                        | 1        | 1.45%   |
| MSI MS-7A38                        | 1        | 1.45%   |
| MSI MS-7972                        | 1        | 1.45%   |
| MAXSUN MS-H110D4L FS M.2           | 1        | 1.45%   |
| Lenovo YangTianW2090v-00           | 1        | 1.45%   |
| Lenovo YangTianM6880N              | 1        | 1.45%   |
| Lenovo YangTianA8800T              | 1        | 1.45%   |
| Lenovo ThinkCentre M93p 10AA0020CN | 1        | 1.45%   |
| Lenovo SHARKBAY SDK0A46860 WIN     | 1        | 1.45%   |
| Lenovo SHARKBAY 0B98401 WIN        | 1        | 1.45%   |
| Lenovo IdeaCentre B545 10100       | 1        | 1.45%   |
| Intel X58                          | 1        | 1.45%   |
| HP t620 PLUS Quad Core TC          | 1        | 1.45%   |
| HP Slim Desktop S01-pF1xxx         | 1        | 1.45%   |
| HP Compaq Elite 8300 USDT          | 1        | 1.45%   |
| GuoGuang IC2M1028V-6               | 1        | 1.45%   |
| Google Guado                       | 1        | 1.45%   |
| Gigabyte H410M S2 V2               | 1        | 1.45%   |
| Gigabyte GB-BACE-3150              | 1        | 1.45%   |
| Gigabyte GA-870-UD3P               | 1        | 1.45%   |
| Gigabyte AB350N-Gaming WIFI        | 1        | 1.45%   |
| Dell Vostro 3667                   | 1        | 1.45%   |
| Dell Precision WorkStation T5500   | 1        | 1.45%   |
| Dell Precision Tower 5810          | 1        | 1.45%   |
| Dell OptiPlex 755                  | 1        | 1.45%   |
| Dell OptiPlex 7060                 | 1        | 1.45%   |
| Dell OptiPlex 7010                 | 1        | 1.45%   |
| Dell Inspiron 560s                 | 1        | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 17       | 24.64%  |
| ShenZhen MinWin MW-NANO-APL-4L          | 3        | 4.35%   |
| Dell OptiPlex                           | 3        | 4.35%   |
| PAIQ EC3-BT19D4L                        | 2        | 2.9%    |
| Lenovo SHARKBAY                         | 2        | 2.9%    |
| Dell Precision                          | 2        | 2.9%    |
| ASUS TUF                                | 2        | 2.9%    |
| YANYU ITX-N29                           | 1        | 1.45%   |
| WlanCN 6000                             | 1        | 1.45%   |
| TOPFEEL Topone                          | 1        | 1.45%   |
| Techvision TVI7309X                     | 1        | 1.45%   |
| Protectli FW6                           | 1        | 1.45%   |
| ONDA N78G5D3                            | 1        | 1.45%   |
| OEM B85                                 | 1        | 1.45%   |
| NEC Computers SHARKBAY                  | 1        | 1.45%   |
| MSI MS-7C82                             | 1        | 1.45%   |
| MSI MS-7C37                             | 1        | 1.45%   |
| MSI MS-7A38                             | 1        | 1.45%   |
| MSI MS-7972                             | 1        | 1.45%   |
| MAXSUN MS-H110D4L                       | 1        | 1.45%   |
| Lenovo YangTianW2090v-00                | 1        | 1.45%   |
| Lenovo YangTianM6880N                   | 1        | 1.45%   |
| Lenovo YangTianA8800T                   | 1        | 1.45%   |
| Lenovo ThinkCentre                      | 1        | 1.45%   |
| Lenovo IdeaCentre                       | 1        | 1.45%   |
| Intel X58                               | 1        | 1.45%   |
| HP t620                                 | 1        | 1.45%   |
| HP Slim                                 | 1        | 1.45%   |
| HP Compaq                               | 1        | 1.45%   |
| GuoGuang IC2M1028V-6                    | 1        | 1.45%   |
| Google Guado                            | 1        | 1.45%   |
| Gigabyte H410M                          | 1        | 1.45%   |
| Gigabyte GB-BACE-3150                   | 1        | 1.45%   |
| Gigabyte GA-870-UD3P                    | 1        | 1.45%   |
| Gigabyte AB350N-Gaming                  | 1        | 1.45%   |
| Dell Vostro                             | 1        | 1.45%   |
| Dell Inspiron                           | 1        | 1.45%   |
| Colorful YuGong And Development C.J1900 | 1        | 1.45%   |
| Colorful C.Q1900M                       | 1        | 1.45%   |
| Centerm GA690-2                         | 1        | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 10       | 14.49%  |
| 2019 | 8        | 11.59%  |
| 2020 | 7        | 10.14%  |
| 2018 | 6        | 8.7%    |
| 2017 | 6        | 8.7%    |
| 2012 | 6        | 8.7%    |
| 2014 | 5        | 7.25%   |
| 2022 | 4        | 5.8%    |
| 2016 | 4        | 5.8%    |
| 2013 | 4        | 5.8%    |
| 2010 | 3        | 4.35%   |
| 2015 | 2        | 2.9%    |
| 2011 | 2        | 2.9%    |
| 2008 | 1        | 1.45%   |
| 2007 | 1        | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 69       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 97.1%   |
| Yes  | 2        | 2.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 24       | 34.29%  |
| 4.01-8.0   | 16       | 22.86%  |
| 16.01-24.0 | 12       | 17.14%  |
| 2.01-3.0   | 10       | 14.29%  |
| 32.01-64.0 | 6        | 8.57%   |
| 1.01-2.0   | 1        | 1.43%   |
| 0.51-1.0   | 1        | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 43       | 61.43%  |
| 0.51-1.0 | 20       | 28.57%  |
| 1.01-2.0 | 6        | 8.57%   |
| 3.01-4.0 | 1        | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 61.97%  |
| 2      | 11       | 15.49%  |
| 0      | 9        | 12.68%  |
| 5      | 3        | 4.23%   |
| 3      | 3        | 4.23%   |
| 4      | 1        | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 85.71%  |
| Yes       | 10       | 14.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 98.55%  |
| No        | 1        | 1.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 79.71%  |
| Yes       | 14       | 20.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 84.06%  |
| Yes       | 11       | 15.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 69       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Beijing          | 9        | 12%     |
| Shanghai         | 8        | 10.67%  |
| Shenzhen         | 6        | 8%      |
| Zhengzhou        | 5        | 6.67%   |
| Chengdu          | 5        | 6.67%   |
| Guangzhou        | 3        | 4%      |
| Yancheng         | 2        | 2.67%   |
| Xi'an            | 2        | 2.67%   |
| Qingdao          | 2        | 2.67%   |
| Jinrongjie       | 2        | 2.67%   |
| Hangzhou         | 2        | 2.67%   |
| Zhongshan        | 1        | 1.33%   |
| Xicheng District | 1        | 1.33%   |
| Xiamen           | 1        | 1.33%   |
| Wuhan            | 1        | 1.33%   |
| Wenzhou          | 1        | 1.33%   |
| Tongshan         | 1        | 1.33%   |
| Tieling          | 1        | 1.33%   |
| Suzhou           | 1        | 1.33%   |
| Shahekou         | 1        | 1.33%   |
| Qinnan           | 1        | 1.33%   |
| Qingpu           | 1        | 1.33%   |
| Putuo            | 1        | 1.33%   |
| Ningbo           | 1        | 1.33%   |
| Nanjing          | 1        | 1.33%   |
| Liuzhou          | 1        | 1.33%   |
| Kunming          | 1        | 1.33%   |
| Kuiju            | 1        | 1.33%   |
| Jinhua           | 1        | 1.33%   |
| Jiangbei         | 1        | 1.33%   |
| Hongkou          | 1        | 1.33%   |
| Guli             | 1        | 1.33%   |
| Gaoqiao          | 1        | 1.33%   |
| Gaoleshan        | 1        | 1.33%   |
| Fuzhou           | 1        | 1.33%   |
| Dalian           | 1        | 1.33%   |
| Chaoyang Shi     | 1        | 1.33%   |
| Changchun        | 1        | 1.33%   |
| Bijie            | 1        | 1.33%   |
| Baiyun           | 1        | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 18     | 15.48%  |
| WDC                 | 12       | 23     | 14.29%  |
| Samsung Electronics | 11       | 19     | 13.1%   |
| Intel               | 7        | 7      | 8.33%   |
| SanDisk             | 5        | 6      | 5.95%   |
| Toshiba             | 4        | 4      | 4.76%   |
| Transcend           | 3        | 3      | 3.57%   |
| Hitachi             | 3        | 3      | 3.57%   |
| China               | 3        | 5      | 3.57%   |
| Kingston            | 2        | 2      | 2.38%   |
| HGST                | 2        | 7      | 2.38%   |
| tigo                | 1        | 1      | 1.19%   |
| Ramsta              | 1        | 1      | 1.19%   |
| Plextor             | 1        | 2      | 1.19%   |
| ORICO               | 1        | 1      | 1.19%   |
| Netac               | 1        | 1      | 1.19%   |
| Micron Technology   | 1        | 2      | 1.19%   |
| LITEONIT            | 1        | 1      | 1.19%   |
| Lenovo              | 1        | 1      | 1.19%   |
| KIOXIA-EXCERIA      | 1        | 2      | 1.19%   |
| KingSpec            | 1        | 1      | 1.19%   |
| Hewlett-Packard     | 1        | 1      | 1.19%   |
| FREEBSD             | 1        | 1      | 1.19%   |
| FORESEE             | 1        | 1      | 1.19%   |
| Faspeed             | 1        | 1      | 1.19%   |
| Crucial             | 1        | 1      | 1.19%   |
| Colorful            | 1        | 1      | 1.19%   |
| BIWIN               | 1        | 3      | 1.19%   |
| Apacer              | 1        | 1      | 1.19%   |
| A-DATA Technology   | 1        | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST1000DM003-1SB102 1TB  | 3        | 3.13%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 2.08%   |
| Intel SSDSA2SH032G1GN 32GB      | 2        | 2.08%   |
| WDC WUH721414ALE6L4 14TB        | 1        | 1.04%   |
| WDC WDS500G2B0C-00PXH0 500GB    | 1        | 1.04%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 1.04%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 1.04%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1        | 1.04%   |
| WDC WD5000LPCX-24C6HT0 500GB    | 1        | 1.04%   |
| WDC WD5000LPCX-00VHAT0 500GB    | 1        | 1.04%   |
| WDC WD4005FZBX-00K5WB0 4TB      | 1        | 1.04%   |
| WDC WD30EZRZ-00WN9B0 3TB        | 1        | 1.04%   |
| WDC WD20SPZX-22UA7T0 2TB        | 1        | 1.04%   |
| WDC WD2003FYYS-007BA0 2TB       | 1        | 1.04%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1        | 1.04%   |
| WDC WD1600AAJS-22L7A0 160GB     | 1        | 1.04%   |
| WDC WD120EMAZ-11BLFA0 12TB      | 1        | 1.04%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1        | 1.04%   |
| WDC WD10SPCX-00KHST0 1TB        | 1        | 1.04%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 1.04%   |
| WDC WD10EZEX-21WN4A0 1TB        | 1        | 1.04%   |
| WDC WD10EJRX-89N74Y0 1TB        | 1        | 1.04%   |
| WDC WD10EARS-003BB1 1TB         | 1        | 1.04%   |
| Transcend TS64GMSA230S 64GB     | 1        | 1.04%   |
| Transcend TS4GCF150 4GB         | 1        | 1.04%   |
| Transcend TS128GMTS400 128GB    | 1        | 1.04%   |
| Toshiba MQ04ABF100 1TB          | 1        | 1.04%   |
| Toshiba DT01ACA100 1TB          | 1        | 1.04%   |
| Toshiba DT01ACA050 500GB        | 1        | 1.04%   |
| Toshiba A100 240GB              | 1        | 1.04%   |
| tigo SSD 480GB                  | 1        | 1.04%   |
| Seagate ST500LM000-1EJ162 500GB | 1        | 1.04%   |
| Seagate ST500DM002-1SB10A 500GB | 1        | 1.04%   |
| Seagate ST3500418AS 500GB       | 1        | 1.04%   |
| Seagate ST3500312CS 500GB       | 1        | 1.04%   |
| Seagate ST3320418AS 320GB       | 1        | 1.04%   |
| Seagate ST31500541AS 1.5TB      | 1        | 1.04%   |
| Seagate ST31000528AS 1TB        | 1        | 1.04%   |
| Seagate ST3000DM007-1WY10G 3TB  | 1        | 1.04%   |
| Seagate ST2000VN004-2E4164 2TB  | 1        | 1.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Seagate         | 13       | 18     | 39.39%  |
| WDC             | 11       | 20     | 33.33%  |
| Toshiba         | 3        | 3      | 9.09%   |
| Hitachi         | 3        | 3      | 9.09%   |
| HGST            | 2        | 7      | 6.06%   |
| Hewlett-Packard | 1        | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 16.28%  |
| Intel               | 6        | 6      | 13.95%  |
| SanDisk             | 5        | 6      | 11.63%  |
| Transcend           | 3        | 3      | 6.98%   |
| China               | 3        | 5      | 6.98%   |
| Kingston            | 2        | 2      | 4.65%   |
| Toshiba             | 1        | 1      | 2.33%   |
| tigo                | 1        | 1      | 2.33%   |
| Ramsta              | 1        | 1      | 2.33%   |
| ORICO               | 1        | 1      | 2.33%   |
| Netac               | 1        | 1      | 2.33%   |
| Micron Technology   | 1        | 2      | 2.33%   |
| LITEONIT            | 1        | 1      | 2.33%   |
| Lenovo              | 1        | 1      | 2.33%   |
| KIOXIA-EXCERIA      | 1        | 2      | 2.33%   |
| KingSpec            | 1        | 1      | 2.33%   |
| FREEBSD             | 1        | 1      | 2.33%   |
| FORESEE             | 1        | 1      | 2.33%   |
| Faspeed             | 1        | 1      | 2.33%   |
| Colorful            | 1        | 1      | 2.33%   |
| BIWIN               | 1        | 3      | 2.33%   |
| Apacer              | 1        | 1      | 2.33%   |
| A-DATA Technology   | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 41       | 51     | 51.25%  |
| HDD  | 28       | 52     | 35%     |
| NVMe | 11       | 18     | 13.75%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 59       | 103    | 84.29%  |
| NVMe | 11       | 18     | 15.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 51       | 71     | 67.11%  |
| 0.51-1.0   | 15       | 18     | 19.74%  |
| 1.01-2.0   | 5        | 6      | 6.58%   |
| 2.01-3.0   | 2        | 3      | 2.63%   |
| 3.01-4.0   | 1        | 1      | 1.32%   |
| 10.01-20.0 | 1        | 2      | 1.32%   |
| 4.01-10.0  | 1        | 2      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 21       | 29.17%  |
| 101-250    | 20       | 27.78%  |
| 21-50      | 10       | 13.89%  |
| 251-500    | 9        | 12.5%   |
| 51-100     | 8        | 11.11%  |
| 501-1000   | 3        | 4.17%   |
| 1001-2000  | 1        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 64       | 91.43%  |
| 21-50   | 4        | 5.71%   |
| 51-100  | 2        | 2.86%   |

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
| HGST HTS725050A7E630 500GB    | 1        | 5      | 9.09%   |
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
| HGST     | 1        | 5      | 9.09%   |
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
| HGST    | 1        | 5      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 12     | 63.64%  |
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
| Works    | 53       | 101    | 80.3%   |
| Malfunc  | 11       | 18     | 16.67%  |
| Detected | 2        | 2      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 56       | 69.14%  |
| AMD                       | 11       | 13.58%  |
| Samsung Electronics       | 5        | 6.17%   |
| SanDisk                   | 3        | 3.7%    |
| Broadcom / LSI            | 2        | 2.47%   |
| Nvidia                    | 1        | 1.23%   |
| Micron/Crucial Technology | 1        | 1.23%   |
| Lite-On Technology        | 1        | 1.23%   |
| ASMedia Technology        | 1        | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7        | 7.14%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7        | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6        | 6.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5        | 5.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4        | 4.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4        | 4.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3        | 3.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3        | 3.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3        | 3.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 3.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2        | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 2.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 2.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 2.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2        | 2.04%   |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 1        | 1.02%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1        | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 1.02%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 1.02%   |
| Nvidia MCP61 IDE                                                                 | 1        | 1.02%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 1.02%   |
| Intel SSD 660P Series                                                            | 1        | 1.02%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 1.02%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 1.02%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1        | 1.02%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1        | 1.02%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 1.02%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 1.02%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1        | 1.02%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 1.02%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 55       | 65.48%  |
| IDE  | 14       | 16.67%  |
| NVMe | 11       | 13.1%   |
| RAID | 3        | 3.57%   |
| SAS  | 1        | 1.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 56       | 81.16%  |
| AMD    | 12       | 17.39%  |
| ARM    | 1        | 1.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 6        | 8.7%    |
| Intel Atom CPU D525 @ 1.80GHz               | 4        | 5.8%    |
| Intel Celeron CPU J3455 @ 1.50GHz           | 3        | 4.35%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 2        | 2.9%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 2.9%    |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2        | 2.9%    |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 1.45%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 1.45%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 1.45%   |
| Intel Xeon                                  | 1        | 1.45%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.45%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1        | 1.45%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.45%   |
| Intel Pentium CPU G3460T @ 3.00GHz          | 1        | 1.45%   |
| Intel Genuine CPU 0000 @ 2.50GHz            | 1        | 1.45%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 1.45%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.45%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 1.45%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.45%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.45%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.45%   |
| Intel Core i3-8100T CPU @ 3.10GHz           | 1        | 1.45%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.45%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1        | 1.45%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 1.45%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.45%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.45%   |
| Intel Core 2 Duo                            | 1        | 1.45%   |
| Intel Celeron N5105 @ 2.00GHz               | 1        | 1.45%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 1        | 1.45%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 1        | 1.45%   |
| Intel Celeron CPU J3160 @ 1.60GHz           | 1        | 1.45%   |
| Intel Celeron CPU G1820 @ 2.70GHz           | 1        | 1.45%   |
| Intel Celeron CPU 5205U @ 1.90GHz           | 1        | 1.45%   |
| Intel Celeron CPU 3965U @ 2.20GHz           | 1        | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 20       | 28.99%  |
| Intel Atom              | 7        | 10.14%  |
| Intel Pentium           | 5        | 7.25%   |
| Intel Core i7           | 5        | 7.25%   |
| Intel Core i5           | 5        | 7.25%   |
| Intel Core i3           | 5        | 7.25%   |
| Intel Xeon              | 4        | 5.8%    |
| AMD Ryzen 5             | 3        | 4.35%   |
| Intel Core 2 Duo        | 2        | 2.9%    |
| AMD G                   | 2        | 2.9%    |
| Intel Pentium Dual-Core | 1        | 1.45%   |
| Intel Genuine           | 1        | 1.45%   |
| Intel Core 2 Quad       | 1        | 1.45%   |
| ARM Cortex              | 1        | 1.45%   |
| AMD Ryzen 9             | 1        | 1.45%   |
| AMD Ryzen 7             | 1        | 1.45%   |
| AMD Ryzen 3             | 1        | 1.45%   |
| AMD Phenom II X4        | 1        | 1.45%   |
| AMD GX                  | 1        | 1.45%   |
| AMD Athlon II X4        | 1        | 1.45%   |
| AMD A10                 | 1        | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 36       | 52.17%  |
| 2       | 25       | 36.23%  |
| 12      | 4        | 5.8%    |
| 24      | 1        | 1.45%   |
| 16      | 1        | 1.45%   |
| 8       | 1        | 1.45%   |
| Unknown | 1        | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 68       | 98.55%  |
| Unknown | 1        | 1.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 49       | 71.01%  |
| 2       | 19       | 27.54%  |
| Unknown | 1        | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 9        | 13.04%  |
| KabyLake      | 9        | 13.04%  |
| Haswell       | 8        | 11.59%  |
| Bonnell       | 6        | 8.7%    |
| Goldmont      | 4        | 5.8%    |
| CometLake     | 4        | 5.8%    |
| Penryn        | 3        | 4.35%   |
| Goldmont plus | 3        | 4.35%   |
| Zen 2         | 2        | 2.9%    |
| Zen           | 2        | 2.9%    |
| Westmere      | 2        | 2.9%    |
| Skylake       | 2        | 2.9%    |
| K10           | 2        | 2.9%    |
| IvyBridge     | 2        | 2.9%    |
| Bobcat        | 2        | 2.9%    |
| Unknown       | 2        | 2.9%    |
| Zen+          | 1        | 1.45%   |
| Zen 3         | 1        | 1.45%   |
| SandyBridge   | 1        | 1.45%   |
| Piledriver    | 1        | 1.45%   |
| Jaguar        | 1        | 1.45%   |
| Core          | 1        | 1.45%   |
| Broadwell     | 1        | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 46       | 69.7%   |
| Nvidia | 11       | 16.67%  |
| AMD    | 9        | 13.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7        | 10.45%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 7.46%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 5.97%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 4.48%   |
| Intel HD Graphics 610                                                                    | 3        | 4.48%   |
| Intel HD Graphics 500                                                                    | 3        | 4.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 4.48%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 4.48%   |
| Intel HD Graphics 620                                                                    | 2        | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.99%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 2.99%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 1.49%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.49%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.49%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.49%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.49%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 1.49%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.49%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.49%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.49%   |
| Intel HD Graphics 630                                                                    | 1        | 1.49%   |
| Intel HD Graphics 5500                                                                   | 1        | 1.49%   |
| Intel HD Graphics 530                                                                    | 1        | 1.49%   |
| Intel Comet Lake UHD Graphics                                                            | 1        | 1.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.49%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.49%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1        | 1.49%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 1.49%   |
| AMD Trinity [Radeon HD 7660D]                                                            | 1        | 1.49%   |
| AMD RV620 GL [FirePro 2260]                                                              | 1        | 1.49%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.49%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.49%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 1.49%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 1.49%   |
| AMD Caicos [Radeon HD 6450A/7450A]                                                       | 1        | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 41       | 59.42%  |
| 1 x Nvidia | 11       | 15.94%  |
| 1 x AMD    | 8        | 11.59%  |
| 2 x Intel  | 5        | 7.25%   |
| Other      | 3        | 4.35%   |
| 2 x AMD    | 1        | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 56       | 81.16%  |
| Proprietary | 8        | 11.59%  |
| Unknown     | 5        | 7.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 85.51%  |
| 7.01-8.0   | 2        | 2.9%    |
| 1.01-2.0   | 2        | 2.9%    |
| 0.01-0.5   | 2        | 2.9%    |
| 5.01-6.0   | 1        | 1.45%   |
| 3.01-4.0   | 1        | 1.45%   |
| 8.01-16.0  | 1        | 1.45%   |
| 0.51-1.0   | 1        | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Dell    | 5        | 26.32%  |
| AOC     | 4        | 21.05%  |
| Lenovo  | 2        | 10.53%  |
| ZL_     | 1        | 5.26%   |
| Philips | 1        | 5.26%   |
| Mi      | 1        | 5.26%   |
| Haier   | 1        | 5.26%   |
| GRR     | 1        | 5.26%   |
| CAN     | 1        | 5.26%   |
| BenQ    | 1        | 5.26%   |
| Acer    | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch   | 1        | 5.26%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch        | 1        | 5.26%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch     | 1        | 5.26%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch  | 1        | 5.26%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch    | 1        | 5.26%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch | 1        | 5.26%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch            | 1        | 5.26%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch        | 1        | 5.26%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch        | 1        | 5.26%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch        | 1        | 5.26%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch        | 1        | 5.26%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch       | 1        | 5.26%   |
| CAN F55C CAN0055 3840x2160 1210x680mm 54.6-inch          | 1        | 5.26%   |
| BenQ FP91G+ BNQ76A6 1280x1024 380x300mm 19.1-inch        | 1        | 5.26%   |
| AOC Q27P1B AOC2701 1920x1080 600x340mm 27.2-inch         | 1        | 5.26%   |
| AOC 2778X AOC2778 2560x1440 600x340mm 27.2-inch          | 1        | 5.26%   |
| AOC 2490W1 AOC2490 1920x1080 530x300mm 24.0-inch         | 1        | 5.26%   |
| AOC 2479W AOC2479 1920x1080 520x290mm 23.4-inch          | 1        | 5.26%   |
| Acer G195WV ACR0263 1440x900 410x260mm 19.1-inch         | 1        | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 47.37%  |
| 2560x1440 (QHD)    | 3        | 15.79%  |
| 1440x900 (WXGA+)   | 3        | 15.79%  |
| 3840x2160 (4K)     | 2        | 10.53%  |
| 1680x1050 (WSXGA+) | 1        | 5.26%   |
| 1280x1024 (SXGA)   | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 4        | 21.05%  |
| 24     | 4        | 21.05%  |
| 23     | 3        | 15.79%  |
| 19     | 3        | 15.79%  |
| 21     | 2        | 10.53%  |
| 54     | 1        | 5.26%   |
| 22     | 1        | 5.26%   |
| 18     | 1        | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 57.89%  |
| 401-500     | 5        | 26.32%  |
| 351-400     | 2        | 10.53%  |
| 1001-1500   | 1        | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 73.68%  |
| 16/10 | 4        | 21.05%  |
| 5/4   | 1        | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 52.63%  |
| 301-350        | 4        | 21.05%  |
| 151-200        | 4        | 21.05%  |
| More than 1000 | 1        | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 68.42%  |
| 101-120 | 5        | 26.32%  |
| 161-240 | 1        | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 50       | 71.43%  |
| 1     | 20       | 28.57%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 45       | 51.72%  |
| Realtek Semiconductor    | 35       | 40.23%  |
| Qualcomm Atheros         | 3        | 3.45%   |
| Broadcom                 | 2        | 2.3%    |
| Ralink Technology        | 1        | 1.15%   |
| Marvell Technology Group | 1        | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 30.3%   |
| Intel I211 Gigabit Network Connection                             | 14       | 14.14%  |
| Intel Ethernet Connection I217-LM                                 | 4        | 4.04%   |
| Intel 82583V Gigabit Network Connection                           | 4        | 4.04%   |
| Intel I350 Gigabit Network Connection                             | 3        | 3.03%   |
| Intel I210 Gigabit Network Connection                             | 3        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.02%   |
| Intel Wireless 7260                                               | 2        | 2.02%   |
| Intel Wireless 3165                                               | 2        | 2.02%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 2.02%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.02%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.01%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.01%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 1.01%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter   | 1        | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.01%   |
| Intel Wireless 3160                                               | 1        | 1.01%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.01%   |
| Intel Ethernet Connection X553 1GbE                               | 1        | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.01%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.01%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.01%   |
| Intel 82580 Gigabit Network Connection                            | 1        | 1.01%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.01%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.01%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.01%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.01%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 50%     |
| Realtek Semiconductor | 3        | 18.75%  |
| Qualcomm Atheros      | 3        | 18.75%  |
| Ralink Technology     | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                             | 2        | 12.5%   |
| Intel Wireless 3165                                             | 2        | 12.5%   |
| Intel Wi-Fi 6 AX200                                             | 2        | 12.5%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 6.25%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 6.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1        | 6.25%   |
| Ralink RT5370 Wireless Adapter                                  | 1        | 6.25%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 6.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1        | 6.25%   |
| Intel Wireless 3160                                             | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 6.25%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 39       | 52%     |
| Realtek Semiconductor    | 34       | 45.33%  |
| Marvell Technology Group | 1        | 1.33%   |
| Broadcom                 | 1        | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 36.14%  |
| Intel I211 Gigabit Network Connection                             | 14       | 16.87%  |
| Intel Ethernet Connection I217-LM                                 | 4        | 4.82%   |
| Intel 82583V Gigabit Network Connection                           | 4        | 4.82%   |
| Intel I350 Gigabit Network Connection                             | 3        | 3.61%   |
| Intel I210 Gigabit Network Connection                             | 3        | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.41%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.41%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.2%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.2%    |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.2%    |
| Intel Ethernet Connection X553 1GbE                               | 1        | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 1        | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.2%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.2%    |
| Intel 82580 Gigabit Network Connection                            | 1        | 1.2%    |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.2%    |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.2%    |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.2%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.2%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 82.93%  |
| WiFi     | 14       | 17.07%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 91.67%  |
| WiFi     | 6        | 8.33%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 30       | 43.48%  |
| 1     | 13       | 18.84%  |
| 6     | 9        | 13.04%  |
| 4     | 9        | 13.04%  |
| 5     | 5        | 7.25%   |
| 7     | 2        | 2.9%    |
| 0     | 1        | 1.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 77.78%  |
| Yes  | 16       | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 54.55%  |
| Realtek Semiconductor           | 2        | 18.18%  |
| Qualcomm Atheros Communications | 1        | 9.09%   |
| Cambridge Silicon Radio         | 1        | 9.09%   |
| Apple                           | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 3        | 27.27%  |
| Intel AX200 Bluetooth                                       | 2        | 18.18%  |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 9.09%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1        | 9.09%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 9.09%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 9.09%   |
| Apple Bluetooth Host Controller                             | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 45       | 65.22%  |
| AMD                    | 12       | 17.39%  |
| Nvidia                 | 11       | 15.94%  |
| Generalplus Technology | 1        | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5        | 6.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5        | 6.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4        | 5.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4        | 5.06%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 3.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 3.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 3.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 3.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 3.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3        | 3.8%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 3.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3        | 3.8%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 2.53%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 2.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 2.53%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 2.53%   |
| AMD FCH Azalia Controller                                                                         | 2        | 2.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.27%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.27%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 1.27%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 1.27%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 1.27%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.27%   |
| Intel Jasper Lake HD Audio                                                                        | 1        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.27%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1        | 1.27%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.27%   |
| Generalplus Technology USB Audio Device                                                           | 1        | 1.27%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 1.27%   |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 17       | 22.97%  |
| Unknown             | 12       | 16.22%  |
| Kingston            | 11       | 14.86%  |
| Micron Technology   | 9        | 12.16%  |
| SK hynix            | 7        | 9.46%   |
| A-DATA Technology   | 6        | 8.11%   |
| Unknown             | 3        | 4.05%   |
| Nanya Technology    | 2        | 2.7%    |
| G.Skill             | 2        | 2.7%    |
| Team                | 1        | 1.35%   |
| Ramsta              | 1        | 1.35%   |
| Ramaxel Technology  | 1        | 1.35%   |
| Elpida              | 1        | 1.35%   |
| Corsair             | 1        | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3        | 3.9%    |
| Unknown                                                    | 3        | 3.9%    |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                 | 2        | 2.6%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 2        | 2.6%    |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s       | 2        | 2.6%    |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s              | 1        | 1.3%    |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s | 1        | 1.3%    |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                  | 1        | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                 | 1        | 1.3%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 1.3%    |
| Unknown RAM Module 1GB DIMM SDRAM                          | 1        | 1.3%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                   | 1        | 1.3%    |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s      | 1        | 1.3%    |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s         | 1        | 1.3%    |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM 1066MT/s            | 1        | 1.3%    |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s       | 1        | 1.3%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 1.3%    |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 1.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1        | 1.3%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 1        | 1.3%    |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s       | 1        | 1.3%    |
| SK hynix RAM 8ATF1G64HZ-2G3A1 8GB DIMM DDR4 2400MT/s       | 1        | 1.3%    |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 1333MT/s        | 1        | 1.3%    |
| Samsung RAM M471B5273DM0-CH9 4GB DIMM DDR3 1333MT/s        | 1        | 1.3%    |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.3%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 1        | 1.3%    |
| Samsung RAM M471B5273DH0-CK0 4GB DIMM DDR3 1333MT/s        | 1        | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 1.3%    |
| Samsung RAM M471B1G73QHO-YKO 4GB SODIMM DDR3 1600MT/s      | 1        | 1.3%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB DDR3 1600MT/s          | 1        | 1.3%    |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1        | 1.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1        | 1.3%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1        | 1.3%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s      | 1        | 1.3%    |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s        | 1        | 1.3%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                 | 1        | 1.3%    |
| Ramsta RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 1.3%    |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s      | 1        | 1.3%    |
| Nanya RAM NT8GC64B8HB0NS-DI 8GB SODIMM DDR3 1600MT/s       | 1        | 1.3%    |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1        | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 32       | 48.48%  |
| DDR4    | 27       | 40.91%  |
| DDR2    | 4        | 6.06%   |
| Unknown | 2        | 3.03%   |
| SDRAM   | 1        | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 38       | 56.72%  |
| SODIMM  | 26       | 38.81%  |
| Unknown | 2        | 2.99%   |
| RIMM    | 1        | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 26       | 36.62%  |
| 8192  | 21       | 29.58%  |
| 2048  | 14       | 19.72%  |
| 16384 | 8        | 11.27%  |
| 1024  | 2        | 2.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 23.29%  |
| 2133    | 10       | 13.7%   |
| 1333    | 10       | 13.7%   |
| 2667    | 6        | 8.22%   |
| 2400    | 6        | 8.22%   |
| 800     | 6        | 8.22%   |
| 3200    | 5        | 6.85%   |
| 2666    | 3        | 4.11%   |
| 1334    | 3        | 4.11%   |
| 2933    | 2        | 2.74%   |
| 667     | 2        | 2.74%   |
| 1867    | 1        | 1.37%   |
| 1066    | 1        | 1.37%   |
| Unknown | 1        | 1.37%   |

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
| Logitech                | 2        | 50%     |
| Z-Star Microelectronics | 1        | 25%     |
| Microdia                | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Lenovo USB2.0 UVC Camera | 1        | 25%     |
| Microdia Camera                 | 1        | 25%     |
| Logitech Webcam C170            | 1        | 25%     |
| Logitech C670i FHD Webcam       | 1        | 25%     |

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
| 1     | 30       | 43.48%  |
| 0     | 30       | 43.48%  |
| 2     | 9        | 13.04%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 35       | 76.09%  |
| Net/wireless             | 6        | 13.04%  |
| Card reader              | 2        | 4.35%   |
| Sound                    | 1        | 2.17%   |
| Net/ethernet             | 1        | 2.17%   |
| Bluetooth                | 1        | 2.17%   |

