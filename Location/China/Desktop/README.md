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

Total: 144

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASRock        | B360M Xtreme                | [e84af03816](https://bsd-hardware.info/?probe=e84af03816) | Feb 16, 2024 |
| Techvision    | TVI7309X B0                 | [0a384151b6](https://bsd-hardware.info/?probe=0a384151b6) | Jan 20, 2024 |
| Unknown       | Unknown                     | [609434dc71](https://bsd-hardware.info/?probe=609434dc71) | Jan 18, 2024 |
| Unknown       | Unknown                     | [ba78787dff](https://bsd-hardware.info/?probe=ba78787dff) | Dec 29, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [06457349dc](https://bsd-hardware.info/?probe=06457349dc) | Dec 22, 2023 |
| Intel         | SKYBAY                      | [6ad2ae72f1](https://bsd-hardware.info/?probe=6ad2ae72f1) | Dec 13, 2023 |
| MSI           | B450M MORTAR                | [4017ce5221](https://bsd-hardware.info/?probe=4017ce5221) | Nov 29, 2023 |
| Supermicro    | X9SCL-II/X9SCM-II           | [34833316ac](https://bsd-hardware.info/?probe=34833316ac) | Nov 27, 2023 |
| Silicom       | 80300-0214-G16 R310         | [34382c8f4b](https://bsd-hardware.info/?probe=34382c8f4b) | Nov 24, 2023 |
| Unknown       | Unknown                     | [456d5ad8bf](https://bsd-hardware.info/?probe=456d5ad8bf) | Nov 05, 2023 |
| YanRay Tec... | B1904                       | [7d194ae12b](https://bsd-hardware.info/?probe=7d194ae12b) | Oct 28, 2023 |
| MECHREVO      | Unknown                     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | [da1e562510](https://bsd-hardware.info/?probe=da1e562510) | Oct 10, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | [d7cf15da0c](https://bsd-hardware.info/?probe=d7cf15da0c) | Oct 09, 2023 |
| Unknown       | Unknown                     | [c54bad3277](https://bsd-hardware.info/?probe=c54bad3277) | Oct 04, 2023 |
| Biostar       | A55MLC2                     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Techvision    | TVI7309X B0                 | [93c70115bd](https://bsd-hardware.info/?probe=93c70115bd) | Aug 19, 2023 |
| Intel         | SKYBAY                      | [53fb653186](https://bsd-hardware.info/?probe=53fb653186) | Aug 18, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| Unknown       | Unknown                     | [75e009424e](https://bsd-hardware.info/?probe=75e009424e) | Aug 07, 2023 |
| Intel         | SKYBAY                      | [fde75b4094](https://bsd-hardware.info/?probe=fde75b4094) | Aug 04, 2023 |
| AZW           | EQ                          | [a581a63aae](https://bsd-hardware.info/?probe=a581a63aae) | Jul 29, 2023 |
| AZW           | EQ                          | [1feeda5ce9](https://bsd-hardware.info/?probe=1feeda5ce9) | Jul 29, 2023 |
| Unknown       | Unknown                     | [3ca61a6a18](https://bsd-hardware.info/?probe=3ca61a6a18) | Jul 24, 2023 |
| AZW           | EQ                          | [7d2884120c](https://bsd-hardware.info/?probe=7d2884120c) | Jul 23, 2023 |
| NEC Comput... | IS8XM                       | [9f50189f65](https://bsd-hardware.info/?probe=9f50189f65) | Jul 22, 2023 |
| OEM           | ITX-SC3 V1.1                | [a58b6ba2d4](https://bsd-hardware.info/?probe=a58b6ba2d4) | Jul 18, 2023 |
| OEM           | ITX-SC3 V1.1                | [7c550acc8c](https://bsd-hardware.info/?probe=7c550acc8c) | Jul 18, 2023 |
| Unknown       | Unknown                     | [4c5d9c5da3](https://bsd-hardware.info/?probe=4c5d9c5da3) | Jun 29, 2023 |
| WlanCN        | 6000 Series                 | [d2e71531b6](https://bsd-hardware.info/?probe=d2e71531b6) | Jun 05, 2023 |
| NORCO         | HB133                       | [1d59c53b9b](https://bsd-hardware.info/?probe=1d59c53b9b) | May 25, 2023 |
| DS            | FJ04D JHS60K                | [7561a5e28b](https://bsd-hardware.info/?probe=7561a5e28b) | May 11, 2023 |
| Colorful T... | C.J1900A-BTC PLUS V20       | [07add98717](https://bsd-hardware.info/?probe=07add98717) | May 03, 2023 |
| Colorful T... | C.J1900A-BTC PLUS V20       | [b718c75566](https://bsd-hardware.info/?probe=b718c75566) | May 01, 2023 |
| Dell          | 0VTC0D A02                  | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Lenovo        | YangTianM6880N              | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| YENTEK        | ITX-B75R1                   | [7443f81ab1](https://bsd-hardware.info/?probe=7443f81ab1) | Apr 10, 2023 |
| Gigabyte      | M52L-S3P                    | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| YENTEK        | ITX-B75R1                   | [3cab1716e0](https://bsd-hardware.info/?probe=3cab1716e0) | Apr 08, 2023 |
| Unknown       | Unknown                     | [0976c12353](https://bsd-hardware.info/?probe=0976c12353) | Apr 03, 2023 |
| Intel         | MAHOBAY                     | [6e8443e9f4](https://bsd-hardware.info/?probe=6e8443e9f4) | Apr 01, 2023 |
| Dell          | 0KYJ8C A02                  | [ea8759f206](https://bsd-hardware.info/?probe=ea8759f206) | Mar 09, 2023 |
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
| helloSystem 0.7.0 | 9        | 7.44%   |
| OPNsense 21.7.1   | 6        | 4.96%   |
| OPNsense 23.1.11  | 5        | 4.13%   |
| OPNsense 21.7.3   | 4        | 3.31%   |
| OPNsense 21.1.7   | 4        | 3.31%   |
| helloSystem 0.5.0 | 4        | 3.31%   |
| FreeBSD 13.1-p2   | 4        | 3.31%   |
| OPNsense 23.1.5   | 3        | 2.48%   |
| OPNsense 23.1.1   | 3        | 2.48%   |
| OPNsense 22.7.5   | 3        | 2.48%   |
| OPNsense 21.7.5   | 3        | 2.48%   |
| OPNsense 21.7.2   | 3        | 2.48%   |
| FreeBSD 13.2      | 3        | 2.48%   |
| OPNsense 23.7.9   | 2        | 1.65%   |
| OPNsense 23.7.7   | 2        | 1.65%   |
| OPNsense 23.7.5   | 2        | 1.65%   |
| OPNsense 23.7.1   | 2        | 1.65%   |
| OPNsense 23.1.7   | 2        | 1.65%   |
| OPNsense 22.7.2   | 2        | 1.65%   |
| OPNsense 22.1.4   | 2        | 1.65%   |
| OPNsense 22.1.2   | 2        | 1.65%   |
| OPNsense 22.1.10  | 2        | 1.65%   |
| OPNsense 21.1.6   | 2        | 1.65%   |
| OPNsense 21.1.3   | 2        | 1.65%   |
| OPNsense 21.1     | 2        | 1.65%   |
| helloSystem 0.8.1 | 2        | 1.65%   |
| helloSystem 0.6.0 | 2        | 1.65%   |
| helloSystem 0.4.0 | 2        | 1.65%   |
| FreeBSD 14.0      | 2        | 1.65%   |
| OPNsense 23.7.12  | 1        | 0.83%   |
| OPNsense 23.7.11  | 1        | 0.83%   |
| OPNsense 23.7     | 1        | 0.83%   |
| OPNsense 23.1.9   | 1        | 0.83%   |
| OPNsense 23.1.6   | 1        | 0.83%   |
| OPNsense 23.1.2   | 1        | 0.83%   |
| OPNsense 22.7.9   | 1        | 0.83%   |
| OPNsense 22.7.8   | 1        | 0.83%   |
| OPNsense 22.7.6   | 1        | 0.83%   |
| OPNsense 22.7.4   | 1        | 0.83%   |
| OPNsense 22.7.3   | 1        | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 59       | 60.82%  |
| helloSystem | 21       | 21.65%  |
| FreeBSD     | 15       | 15.46%  |
| OpenBSD     | 1        | 1.03%   |
| GhostBSD    | 1        | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 93       | 96.88%  |
| arm64   | 2        | 2.08%   |
| powerpc | 1        | 1.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 66       | 68.04%  |
| helloDesktop | 22       | 22.68%  |
| KDE5         | 5        | 5.15%   |
| XFCE         | 1        | 1.03%   |
| MATE         | 1        | 1.03%   |
| i3           | 1        | 1.03%   |
| GNUstep      | 1        | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 67       | 69.79%  |
| X11     | 29       | 30.21%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 68       | 70.1%   |
| SLiM    | 22       | 22.68%  |
| SDDM    | 6        | 6.19%   |
| LightDM | 1        | 1.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 63       | 64.95%  |
| en_US   | 18       | 18.56%  |
| C       | 9        | 9.28%   |
| zh_CN   | 5        | 5.15%   |
| fr_FR   | 2        | 2.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 84       | 87.5%   |
| BIOS | 12       | 12.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 48       | 48.98%  |
| Zfs    | 41       | 41.84%  |
| Cd9660 | 8        | 8.16%   |
| Ffs    | 1        | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 87       | 90.63%  |
| MBR     | 6        | 6.25%   |
| Unknown | 3        | 3.13%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 23       | 23.96%  |
| Dell                                       | 8        | 8.33%   |
| Lenovo                                     | 7        | 7.29%   |
| MSI                                        | 5        | 5.21%   |
| Gigabyte Technology                        | 5        | 5.21%   |
| ASUSTek Computer                           | 4        | 4.17%   |
| Techvision                                 | 3        | 3.13%   |
| ShenZhen MinWin Technology                 | 3        | 3.13%   |
| Intel                                      | 3        | 3.13%   |
| Hewlett-Packard                            | 3        | 3.13%   |
| ASRock                                     | 3        | 3.13%   |
| PAIQ                                       | 2        | 2.08%   |
| OEM                                        | 2        | 2.08%   |
| NEC Computers                              | 2        | 2.08%   |
| Colorful Technology                        | 2        | 2.08%   |
| YENTEK                                     | 1        | 1.04%   |
| YANYU                                      | 1        | 1.04%   |
| YanRay Technology                          | 1        | 1.04%   |
| WlanCN                                     | 1        | 1.04%   |
| TOPFEEL                                    | 1        | 1.04%   |
| Supermicro                                 | 1        | 1.04%   |
| Silicom                                    | 1        | 1.04%   |
| Protectli                                  | 1        | 1.04%   |
| ONDA                                       | 1        | 1.04%   |
| NORCO                                      | 1        | 1.04%   |
| MECHREVO                                   | 1        | 1.04%   |
| MAXSUN                                     | 1        | 1.04%   |
| GuoGuang                                   | 1        | 1.04%   |
| Google                                     | 1        | 1.04%   |
| DS                                         | 1        | 1.04%   |
| Colorful YuGong Technology And Development | 1        | 1.04%   |
| CNCTION-IAF-E3845                          | 1        | 1.04%   |
| Centerm                                    | 1        | 1.04%   |
| Biostar                                    | 1        | 1.04%   |
| AZW                                        | 1        | 1.04%   |
| AMD                                        | 1        | 1.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 25       | 26.04%  |
| Techvision TVI7309X                | 3        | 3.13%   |
| ShenZhen MinWin MW-NANO-APL-4L     | 3        | 3.13%   |
| PAIQ EC3-BT19D4L                   | 2        | 2.08%   |
| YENTEK ITX-B75R1                   | 1        | 1.04%   |
| YANYU ITX-N29 VER:1.5 baytrail     | 1        | 1.04%   |
| YanRay B1904                       | 1        | 1.04%   |
| WlanCN 6000 Series                 | 1        | 1.04%   |
| TOPFEEL Topone series              | 1        | 1.04%   |
| Supermicro NS-EI36S                | 1        | 1.04%   |
| Silicom 6200                       | 1        | 1.04%   |
| Protectli FW6                      | 1        | 1.04%   |
| ONDA N78G5D3 Ver:5.00              | 1        | 1.04%   |
| OEM ITX-SC3                        | 1        | 1.04%   |
| OEM B85 JHS359                     | 1        | 1.04%   |
| NORCO HB133                        | 1        | 1.04%   |
| NEC Computers SHARKBAY             | 1        | 1.04%   |
| NEC Computers PC-MC32MBZCEECH      | 1        | 1.04%   |
| MSI MS-7C82                        | 1        | 1.04%   |
| MSI MS-7C37                        | 1        | 1.04%   |
| MSI MS-7B89                        | 1        | 1.04%   |
| MSI MS-7A38                        | 1        | 1.04%   |
| MSI MS-7972                        | 1        | 1.04%   |
| MAXSUN MS-H110D4L FS M.2           | 1        | 1.04%   |
| Lenovo YangTianW2090v-00           | 1        | 1.04%   |
| Lenovo YangTianM6880N              | 1        | 1.04%   |
| Lenovo YangTianA8800T              | 1        | 1.04%   |
| Lenovo ThinkCentre M93p 10AA0020CN | 1        | 1.04%   |
| Lenovo SHARKBAY SDK0A46860 WIN     | 1        | 1.04%   |
| Lenovo SHARKBAY 0B98401 WIN        | 1        | 1.04%   |
| Lenovo IdeaCentre B545 10100       | 1        | 1.04%   |
| Intel X58                          | 1        | 1.04%   |
| Intel SKYBAY                       | 1        | 1.04%   |
| Intel MAHOBAY                      | 1        | 1.04%   |
| HP t620 PLUS Quad Core TC          | 1        | 1.04%   |
| HP Slim Desktop S01-pF1xxx         | 1        | 1.04%   |
| HP Compaq Elite 8300 USDT          | 1        | 1.04%   |
| GuoGuang IC2M1028V-6               | 1        | 1.04%   |
| Google Guado                       | 1        | 1.04%   |
| Gigabyte M52L-S3P                  | 1        | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 25       | 26.04%  |
| Techvision TVI7309X            | 3        | 3.13%   |
| ShenZhen MinWin MW-NANO-APL-4L | 3        | 3.13%   |
| Dell Precision                 | 3        | 3.13%   |
| Dell OptiPlex                  | 3        | 3.13%   |
| PAIQ EC3-BT19D4L               | 2        | 2.08%   |
| Lenovo SHARKBAY                | 2        | 2.08%   |
| ASUS TUF                       | 2        | 2.08%   |
| YENTEK ITX-B75R1               | 1        | 1.04%   |
| YANYU ITX-N29                  | 1        | 1.04%   |
| YanRay B1904                   | 1        | 1.04%   |
| WlanCN 6000                    | 1        | 1.04%   |
| TOPFEEL Topone                 | 1        | 1.04%   |
| Supermicro NS-EI36S            | 1        | 1.04%   |
| Silicom 6200                   | 1        | 1.04%   |
| Protectli FW6                  | 1        | 1.04%   |
| ONDA N78G5D3                   | 1        | 1.04%   |
| OEM ITX-SC3                    | 1        | 1.04%   |
| OEM B85                        | 1        | 1.04%   |
| NORCO HB133                    | 1        | 1.04%   |
| NEC Computers SHARKBAY         | 1        | 1.04%   |
| NEC Computers PC-MC32MBZCEECH  | 1        | 1.04%   |
| MSI MS-7C82                    | 1        | 1.04%   |
| MSI MS-7C37                    | 1        | 1.04%   |
| MSI MS-7B89                    | 1        | 1.04%   |
| MSI MS-7A38                    | 1        | 1.04%   |
| MSI MS-7972                    | 1        | 1.04%   |
| MAXSUN MS-H110D4L              | 1        | 1.04%   |
| Lenovo YangTianW2090v-00       | 1        | 1.04%   |
| Lenovo YangTianM6880N          | 1        | 1.04%   |
| Lenovo YangTianA8800T          | 1        | 1.04%   |
| Lenovo ThinkCentre             | 1        | 1.04%   |
| Lenovo IdeaCentre              | 1        | 1.04%   |
| Intel X58                      | 1        | 1.04%   |
| Intel SKYBAY                   | 1        | 1.04%   |
| Intel MAHOBAY                  | 1        | 1.04%   |
| HP t620                        | 1        | 1.04%   |
| HP Slim                        | 1        | 1.04%   |
| HP Compaq                      | 1        | 1.04%   |
| GuoGuang IC2M1028V-6           | 1        | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 12       | 12.5%   |
| 2019    | 10       | 10.42%  |
| 2023    | 8        | 8.33%   |
| 2022    | 8        | 8.33%   |
| 2020    | 8        | 8.33%   |
| 2018    | 8        | 8.33%   |
| 2017    | 7        | 7.29%   |
| 2012    | 7        | 7.29%   |
| 2014    | 5        | 5.21%   |
| 2013    | 5        | 5.21%   |
| 2016    | 4        | 4.17%   |
| 2015    | 4        | 4.17%   |
| 2010    | 3        | 3.13%   |
| 2011    | 2        | 2.08%   |
| 2008    | 2        | 2.08%   |
| Unknown | 2        | 2.08%   |
| 2007    | 1        | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 96       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 94       | 97.92%  |
| Yes  | 2        | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 36       | 36.73%  |
| 4.01-8.0   | 20       | 20.41%  |
| 16.01-24.0 | 19       | 19.39%  |
| 2.01-3.0   | 11       | 11.22%  |
| 32.01-64.0 | 8        | 8.16%   |
| 0.51-1.0   | 2        | 2.04%   |
| 24.01-32.0 | 1        | 1.02%   |
| 1.01-2.0   | 1        | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 58       | 59.79%  |
| 0.51-1.0 | 29       | 29.9%   |
| 1.01-2.0 | 7        | 7.22%   |
| 3.01-4.0 | 1        | 1.03%   |
| 2.01-3.0 | 1        | 1.03%   |
| 0        | 1        | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 62%     |
| 0      | 16       | 16%     |
| 2      | 14       | 14%     |
| 3      | 4        | 4%      |
| 5      | 3        | 3%      |
| 4      | 1        | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 87.63%  |
| Yes       | 12       | 12.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 97.92%  |
| No        | 2        | 2.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 80.21%  |
| Yes       | 19       | 19.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 85.42%  |
| Yes       | 14       | 14.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 96       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Shenzhen         | 13       | 12.26%  |
| Shanghai         | 10       | 9.43%   |
| Beijing          | 10       | 9.43%   |
| Zhengzhou        | 7        | 6.6%    |
| Jinrongjie       | 6        | 5.66%   |
| Chengdu          | 6        | 5.66%   |
| Guangzhou        | 5        | 4.72%   |
| Xi'an            | 4        | 3.77%   |
| Chongqing        | 3        | 2.83%   |
| Yancheng         | 2        | 1.89%   |
| Suzhou           | 2        | 1.89%   |
| Qingdao          | 2        | 1.89%   |
| Ningbo           | 2        | 1.89%   |
| Hangzhou         | 2        | 1.89%   |
| Zhongshan        | 1        | 0.94%   |
| Zhangjiakou      | 1        | 0.94%   |
| Xicheng District | 1        | 0.94%   |
| Xiamen           | 1        | 0.94%   |
| Wuhan            | 1        | 0.94%   |
| Wenzhou          | 1        | 0.94%   |
| Tongshan         | 1        | 0.94%   |
| Tieling          | 1        | 0.94%   |
| Songjiang        | 1        | 0.94%   |
| Shijiazhuang     | 1        | 0.94%   |
| Shenyang         | 1        | 0.94%   |
| Shahekou         | 1        | 0.94%   |
| Qinnan           | 1        | 0.94%   |
| Qingpu           | 1        | 0.94%   |
| Putuo            | 1        | 0.94%   |
| Nanjing          | 1        | 0.94%   |
| Liuzhou          | 1        | 0.94%   |
| Kunming          | 1        | 0.94%   |
| Kuiju            | 1        | 0.94%   |
| Jinhua           | 1        | 0.94%   |
| Jiangbei         | 1        | 0.94%   |
| Huangshi         | 1        | 0.94%   |
| Hongkou          | 1        | 0.94%   |
| Guli             | 1        | 0.94%   |
| Gaoqiao          | 1        | 0.94%   |
| Gaoleshan        | 1        | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 21     | 14.02%  |
| WDC                 | 14       | 28     | 13.08%  |
| Samsung Electronics | 13       | 23     | 12.15%  |
| Intel               | 11       | 11     | 10.28%  |
| SanDisk             | 7        | 9      | 6.54%   |
| Toshiba             | 6        | 6      | 5.61%   |
| China               | 4        | 6      | 3.74%   |
| Transcend           | 3        | 4      | 2.8%    |
| Kingston            | 3        | 4      | 2.8%    |
| Hitachi             | 3        | 3      | 2.8%    |
| KIOXIA-EXCERIA      | 2        | 3      | 1.87%   |
| HGST                | 2        | 7      | 1.87%   |
| FORESEE             | 2        | 2      | 1.87%   |
| tigo                | 1        | 1      | 0.93%   |
| SK hynix            | 1        | 1      | 0.93%   |
| Ramsta              | 1        | 1      | 0.93%   |
| Plextor             | 1        | 2      | 0.93%   |
| ORICO               | 1        | 1      | 0.93%   |
| NVMe                | 1        | 2      | 0.93%   |
| Netac               | 1        | 1      | 0.93%   |
| Micron Technology   | 1        | 2      | 0.93%   |
| LITEONIT            | 1        | 1      | 0.93%   |
| Lenovo              | 1        | 1      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| Hewlett-Packard     | 1        | 1      | 0.93%   |
| GLOWAY              | 1        | 1      | 0.93%   |
| FREEBSD             | 1        | 1      | 0.93%   |
| Faspeed             | 1        | 1      | 0.93%   |
| Crucial             | 1        | 2      | 0.93%   |
| Colorful            | 1        | 1      | 0.93%   |
| Centerm             | 1        | 1      | 0.93%   |
| BORY                | 1        | 1      | 0.93%   |
| BIWIN               | 1        | 3      | 0.93%   |
| Apacer              | 1        | 1      | 0.93%   |
| A-DATA Technology   | 1        | 2      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3        | 2.44%   |
| Seagate ST1000DM003-1SB102 1TB    | 3        | 2.44%   |
| Intel SSDSA2SH032G1GN 32GB        | 2        | 1.63%   |
| WDC WUH721414ALE6L4 14TB          | 1        | 0.81%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 1        | 0.81%   |
| WDC WDS500G1B0C-00S6U0 500GB      | 1        | 0.81%   |
| WDC WDS100T2B0C-00PXH0 1TB        | 1        | 0.81%   |
| WDC WD7500LPCX-00KHST0 752GB      | 1        | 0.81%   |
| WDC WD5000LPCX-24C6HT0 500GB      | 1        | 0.81%   |
| WDC WD5000LPCX-00VHAT0 500GB      | 1        | 0.81%   |
| WDC WD5000AAKX-083CA0 500GB       | 1        | 0.81%   |
| WDC WD40EZAZ-00ZGHB0 4TB          | 1        | 0.81%   |
| WDC WD4005FZBX-00K5WB0 4TB        | 1        | 0.81%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 0.81%   |
| WDC WD30EZRZ-00WN9B0 3TB          | 1        | 0.81%   |
| WDC WD20SPZX-22UA7T0 2TB          | 1        | 0.81%   |
| WDC WD2003FYYS-007BA0 2TB         | 1        | 0.81%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1        | 0.81%   |
| WDC WD1600AAJS-22L7A0 160GB       | 1        | 0.81%   |
| WDC WD120EMAZ-11BLFA0 12TB        | 1        | 0.81%   |
| WDC WD10SPZX-00Z10T0 1TB          | 1        | 0.81%   |
| WDC WD10SPCX-00KHST0 1TB          | 1        | 0.81%   |
| WDC WD10EZEX-22MFCA0 1TB          | 1        | 0.81%   |
| WDC WD10EZEX-21WN4A0 1TB          | 1        | 0.81%   |
| WDC WD10EJRX-89N74Y0 1TB          | 1        | 0.81%   |
| WDC WD10EARS-003BB1 1TB           | 1        | 0.81%   |
| Transcend TS64GMSA230S 64GB       | 1        | 0.81%   |
| Transcend TS4GCF150 4GB           | 1        | 0.81%   |
| Transcend TS128GMTS400 128GB      | 1        | 0.81%   |
| Toshiba THNSFJ256GMCT 256GB       | 1        | 0.81%   |
| Toshiba MQ04ABF100 1TB            | 1        | 0.81%   |
| Toshiba KBG40ZMT128G MEMORY 128GB | 1        | 0.81%   |
| Toshiba DT01ACA100 1TB            | 1        | 0.81%   |
| Toshiba DT01ACA050 500GB          | 1        | 0.81%   |
| Toshiba A100 240GB                | 1        | 0.81%   |
| tigo SSD 480GB                    | 1        | 0.81%   |
| SK hynix HFS064G3AMNB-2220A 64GB  | 1        | 0.81%   |
| Seagate ST940110A 40GB            | 1        | 0.81%   |
| Seagate ST500LM000-1EJ162 500GB   | 1        | 0.81%   |
| Seagate ST500DM002-1SB10A 500GB   | 1        | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 21     | 39.47%  |
| WDC                 | 13       | 25     | 34.21%  |
| Toshiba             | 3        | 3      | 7.89%   |
| Hitachi             | 3        | 3      | 7.89%   |
| HGST                | 2        | 7      | 5.26%   |
| Samsung Electronics | 1        | 1      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Intel               | 8        | 8      | 14.29%  |
| SanDisk             | 7        | 9      | 12.5%   |
| Samsung Electronics | 7        | 8      | 12.5%   |
| China               | 4        | 6      | 7.14%   |
| Transcend           | 3        | 4      | 5.36%   |
| Kingston            | 3        | 4      | 5.36%   |
| Toshiba             | 2        | 2      | 3.57%   |
| KIOXIA-EXCERIA      | 2        | 3      | 3.57%   |
| FORESEE             | 2        | 2      | 3.57%   |
| tigo                | 1        | 1      | 1.79%   |
| SK hynix            | 1        | 1      | 1.79%   |
| Ramsta              | 1        | 1      | 1.79%   |
| ORICO               | 1        | 1      | 1.79%   |
| NVMe                | 1        | 1      | 1.79%   |
| Netac               | 1        | 1      | 1.79%   |
| Micron Technology   | 1        | 2      | 1.79%   |
| LITEONIT            | 1        | 1      | 1.79%   |
| Lenovo              | 1        | 1      | 1.79%   |
| KingSpec            | 1        | 1      | 1.79%   |
| FREEBSD             | 1        | 1      | 1.79%   |
| Faspeed             | 1        | 1      | 1.79%   |
| Colorful            | 1        | 1      | 1.79%   |
| Centerm             | 1        | 1      | 1.79%   |
| BORY                | 1        | 1      | 1.79%   |
| BIWIN               | 1        | 3      | 1.79%   |
| Apacer              | 1        | 1      | 1.79%   |
| A-DATA Technology   | 1        | 2      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 52       | 68     | 50.49%  |
| HDD  | 33       | 61     | 32.04%  |
| NVMe | 18       | 27     | 17.48%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 74       | 129    | 80.43%  |
| NVMe | 18       | 27     | 19.57%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 65       | 92     | 69.89%  |
| 0.51-1.0   | 16       | 19     | 17.2%   |
| 1.01-2.0   | 6        | 7      | 6.45%   |
| 3.01-4.0   | 2        | 4      | 2.15%   |
| 2.01-3.0   | 2        | 3      | 2.15%   |
| 10.01-20.0 | 1        | 2      | 1.08%   |
| 4.01-10.0  | 1        | 2      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 29       | 29%     |
| 1-20       | 27       | 27%     |
| 251-500    | 14       | 14%     |
| 21-50      | 13       | 13%     |
| 51-100     | 10       | 10%     |
| 501-1000   | 4        | 4%      |
| 1001-2000  | 3        | 3%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 88       | 89.8%   |
| 21-50   | 6        | 6.12%   |
| 51-100  | 3        | 3.06%   |
| 101-250 | 1        | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-083CA0 500GB       | 1        | 1      | 5.88%   |
| WDC WD1600AAJS-22L7A0 160GB       | 1        | 1      | 5.88%   |
| WDC WD10EJRX-89N74Y0 1TB          | 1        | 1      | 5.88%   |
| SK hynix HFS064G3AMNB-2220A 64GB  | 1        | 1      | 5.88%   |
| Seagate ST3320418AS 320GB         | 1        | 2      | 5.88%   |
| Seagate ST31500541AS 1.5TB        | 1        | 1      | 5.88%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 5.88%   |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 5.88%   |
| Intel SSDSA2M120G2GC 120GB        | 1        | 1      | 5.88%   |
| Intel SSDPEKKW256G7 256GB         | 1        | 1      | 5.88%   |
| Hitachi HTS723232A7A364 320GB     | 1        | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB        | 1        | 5      | 5.88%   |
| Colorful SL500 640GB              | 1        | 1      | 5.88%   |
| China XJH-32GB                    | 1        | 1      | 5.88%   |
| Centerm SSD 8GB                   | 1        | 1      | 5.88%   |
| BORY M500 16G                     | 1        | 1      | 5.88%   |
| BIWIN SSD 32GB                    | 1        | 3      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 17.65%  |
| Seagate             | 3        | 4      | 17.65%  |
| Intel               | 2        | 2      | 11.76%  |
| SK hynix            | 1        | 1      | 5.88%   |
| Samsung Electronics | 1        | 1      | 5.88%   |
| Hitachi             | 1        | 1      | 5.88%   |
| HGST                | 1        | 5      | 5.88%   |
| Colorful            | 1        | 1      | 5.88%   |
| China               | 1        | 1      | 5.88%   |
| Centerm             | 1        | 1      | 5.88%   |
| BORY                | 1        | 1      | 5.88%   |
| BIWIN               | 1        | 3      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 33.33%  |
| Seagate             | 3        | 4      | 33.33%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |
| HGST                | 1        | 5      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 14     | 52.94%  |
| SSD  | 7        | 9      | 41.18%  |
| NVMe | 1        | 1      | 5.88%   |

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
| Works    | 68       | 128    | 77.27%  |
| Malfunc  | 17       | 24     | 19.32%  |
| Detected | 3        | 4      | 3.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 76       | 67.86%  |
| AMD                          | 13       | 11.61%  |
| Samsung Electronics          | 6        | 5.36%   |
| SanDisk                      | 4        | 3.57%   |
| Nvidia                       | 2        | 1.79%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.79%   |
| Broadcom / LSI               | 2        | 1.79%   |
| Shenzhen Longsys Electronics | 1        | 0.89%   |
| Micron/Crucial Technology    | 1        | 0.89%   |
| Lite-On Technology           | 1        | 0.89%   |
| KIOXIA                       | 1        | 0.89%   |
| INNOGRIT                     | 1        | 0.89%   |
| ASMedia Technology           | 1        | 0.89%   |
| Unknown                      | 1        | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10       | 7.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7        | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7        | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7        | 5.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6        | 4.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5        | 3.76%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 4        | 3.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4        | 3.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4        | 3.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3        | 2.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 2.26%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2        | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 1.5%    |
| Nvidia MCP61 SATA Controller                                                     | 2        | 1.5%    |
| Nvidia MCP61 IDE                                                                 | 2        | 1.5%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 2        | 1.5%    |
| Intel SATA Controller [RAID Mode]                                                | 2        | 1.5%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 1.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 1.5%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 1.5%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 1.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2        | 1.5%    |
| AMD 400 Series Chipset SATA Controller                                           | 2        | 1.5%    |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                | 1        | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1        | 0.75%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 1        | 0.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1        | 0.75%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 1        | 0.75%   |
| Lite-On M9PeG, M9PeGN, M9PeY NVMe SSD                                            | 1        | 0.75%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1        | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 76       | 65.52%  |
| NVMe | 20       | 17.24%  |
| IDE  | 16       | 13.79%  |
| RAID | 3        | 2.59%   |
| SAS  | 1        | 0.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 77       | 80.21%  |
| AMD     | 16       | 16.67%  |
| ARM     | 2        | 2.08%   |
| Unknown | 1        | 1.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 9        | 9.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 6        | 6.25%   |
| Intel Celeron N5105 @ 2.00GHz               | 4        | 4.17%   |
| Intel Atom CPU D525 @ 1.80GHz               | 4        | 4.17%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 3        | 3.13%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 2        | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.08%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2        | 2.08%   |
| ARM Cortex-A53 r0p4                         | 2        | 2.08%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 1.04%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 1.04%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz         | 1        | 1.04%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 1.04%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 1.04%   |
| Intel Xeon                                  | 1        | 1.04%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.04%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1        | 1.04%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.04%   |
| Intel Pentium CPU G3460T @ 3.00GHz          | 1        | 1.04%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.04%   |
| Intel Genuine CPU 0000 @ 2.50GHz            | 1        | 1.04%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 1.04%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.04%   |
| Intel Core i7-4785T CPU @ 2.20GHz           | 1        | 1.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.04%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.04%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.04%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 1.04%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.04%   |
| Intel Core i5-6360U CPU @ 2.00GHz           | 1        | 1.04%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.04%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.04%   |
| Intel Core i3-N305                          | 1        | 1.04%   |
| Intel Core i3-8100T CPU @ 3.10GHz           | 1        | 1.04%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.04%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1        | 1.04%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 1.04%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 31       | 32.29%  |
| Intel Core i5           | 9        | 9.38%   |
| Intel Atom              | 8        | 8.33%   |
| Intel Xeon              | 6        | 6.25%   |
| Intel Pentium           | 6        | 6.25%   |
| Intel Core i7           | 6        | 6.25%   |
| Intel Core i3           | 6        | 6.25%   |
| AMD Ryzen 5             | 4        | 4.17%   |
| Intel Core 2 Duo        | 2        | 2.08%   |
| ARM Cortex              | 2        | 2.08%   |
| AMD Ryzen 7             | 2        | 2.08%   |
| AMD G                   | 2        | 2.08%   |
| AMD Athlon II X4        | 2        | 2.08%   |
| Other                   | 1        | 1.04%   |
| Intel Pentium Dual-Core | 1        | 1.04%   |
| Intel Genuine           | 1        | 1.04%   |
| Intel Core 2 Quad       | 1        | 1.04%   |
| AMD Ryzen 9             | 1        | 1.04%   |
| AMD Ryzen 3             | 1        | 1.04%   |
| AMD Phenom II X4        | 1        | 1.04%   |
| AMD GX                  | 1        | 1.04%   |
| AMD Athlon X2           | 1        | 1.04%   |
| AMD A10                 | 1        | 1.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 52       | 54.17%  |
| 2       | 29       | 30.21%  |
| 12      | 4        | 4.17%   |
| 8       | 3        | 3.13%   |
| 16      | 2        | 2.08%   |
| 6       | 2        | 2.08%   |
| Unknown | 2        | 2.08%   |
| 24      | 1        | 1.04%   |
| 1       | 1        | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 93       | 96.88%  |
| Unknown | 3        | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 70       | 72.92%  |
| 2       | 23       | 23.96%  |
| Unknown | 3        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 12       | 12.5%   |
| KabyLake      | 11       | 11.46%  |
| Haswell       | 9        | 9.38%   |
| Unknown       | 9        | 9.38%   |
| Goldmont plus | 7        | 7.29%   |
| IvyBridge     | 6        | 6.25%   |
| Bonnell       | 6        | 6.25%   |
| Goldmont      | 5        | 5.21%   |
| Skylake       | 4        | 4.17%   |
| CometLake     | 4        | 4.17%   |
| Zen           | 3        | 3.13%   |
| Penryn        | 3        | 3.13%   |
| K10           | 3        | 3.13%   |
| Zen 2         | 2        | 2.08%   |
| Westmere      | 2        | 2.08%   |
| Bobcat        | 2        | 2.08%   |
| Zen+          | 1        | 1.04%   |
| Zen 3         | 1        | 1.04%   |
| SandyBridge   | 1        | 1.04%   |
| Piledriver    | 1        | 1.04%   |
| K10 Llano     | 1        | 1.04%   |
| Jaguar        | 1        | 1.04%   |
| Core          | 1        | 1.04%   |
| Broadwell     | 1        | 1.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 63       | 69.23%  |
| Nvidia                     | 14       | 15.38%  |
| AMD                        | 13       | 14.29%  |
| Matrox Electronics Systems | 1        | 1.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10       | 10.87%  |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 7.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 6.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 4.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 4        | 4.35%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 4.35%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 3.26%   |
| Intel HD Graphics 610                                                                    | 3        | 3.26%   |
| Intel HD Graphics 500                                                                    | 3        | 3.26%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 3.26%   |
| Intel HD Graphics 620                                                                    | 2        | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.17%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 2.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 2.17%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.09%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.09%   |
| Nvidia GP106 [GeForce GTX 1060 5GB]                                                      | 1        | 1.09%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.09%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.09%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 1.09%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 1.09%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 1.09%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.09%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.09%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.09%   |
| Intel Iris Graphics 540                                                                  | 1        | 1.09%   |
| Intel HD Graphics 630                                                                    | 1        | 1.09%   |
| Intel HD Graphics 5500                                                                   | 1        | 1.09%   |
| Intel HD Graphics 530                                                                    | 1        | 1.09%   |
| Intel Comet Lake UHD Graphics                                                            | 1        | 1.09%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 1        | 1.09%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.09%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.09%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1        | 1.09%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 1.09%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 58       | 60.42%  |
| 1 x Nvidia | 14       | 14.58%  |
| 1 x AMD    | 12       | 12.5%   |
| Other      | 5        | 5.21%   |
| 2 x Intel  | 5        | 5.21%   |
| 2 x AMD    | 1        | 1.04%   |
| 1 x Matrox | 1        | 1.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 79       | 82.29%  |
| Proprietary | 10       | 10.42%  |
| Unknown     | 7        | 7.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 84       | 87.5%   |
| 1.01-2.0   | 3        | 3.13%   |
| 7.01-8.0   | 2        | 2.08%   |
| 0.01-0.5   | 2        | 2.08%   |
| 5.01-6.0   | 1        | 1.04%   |
| 4.01-5.0   | 1        | 1.04%   |
| 3.01-4.0   | 1        | 1.04%   |
| 8.01-16.0  | 1        | 1.04%   |
| 0.51-1.0   | 1        | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Dell      | 5        | 23.81%  |
| AOC       | 4        | 19.05%  |
| Lenovo    | 2        | 9.52%   |
| ZL_       | 1        | 4.76%   |
| ViewSonic | 1        | 4.76%   |
| Philips   | 1        | 4.76%   |
| Mi        | 1        | 4.76%   |
| IPS       | 1        | 4.76%   |
| Haier     | 1        | 4.76%   |
| GRR       | 1        | 4.76%   |
| CAN       | 1        | 4.76%   |
| BenQ      | 1        | 4.76%   |
| Acer      | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch        | 1        | 4.76%   |
| ViewSonic VX2880-4K-HDU VSCA33A 3840x2160 630x360mm 28.6-inch | 1        | 4.76%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch             | 1        | 4.76%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch          | 1        | 4.76%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch       | 1        | 4.76%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch         | 1        | 4.76%   |
| IPS W220A IPS3150 3840x2160 700x390mm 31.5-inch               | 1        | 4.76%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch      | 1        | 4.76%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                 | 1        | 4.76%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch             | 1        | 4.76%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch             | 1        | 4.76%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch             | 1        | 4.76%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch             | 1        | 4.76%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch            | 1        | 4.76%   |
| CAN F55C CAN0055 3840x2160 1210x680mm 54.6-inch               | 1        | 4.76%   |
| BenQ FP91G+ BNQ76A6 1280x1024 380x300mm 19.1-inch             | 1        | 4.76%   |
| AOC Q27P1B AOC2701 1920x1080 600x340mm 27.2-inch              | 1        | 4.76%   |
| AOC 2778X AOC2778 2560x1440 600x340mm 27.2-inch               | 1        | 4.76%   |
| AOC 2490W1 AOC2490 1920x1080 530x300mm 24.0-inch              | 1        | 4.76%   |
| AOC 2479W AOC2479 1920x1080 520x290mm 23.4-inch               | 1        | 4.76%   |
| Acer G195WV ACR0263 1440x900 410x260mm 19.1-inch              | 1        | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 42.86%  |
| 3840x2160 (4K)     | 4        | 19.05%  |
| 2560x1440 (QHD)    | 3        | 14.29%  |
| 1440x900 (WXGA+)   | 3        | 14.29%  |
| 1680x1050 (WSXGA+) | 1        | 4.76%   |
| 1280x1024 (SXGA)   | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 4        | 19.05%  |
| 24     | 4        | 19.05%  |
| 23     | 3        | 14.29%  |
| 19     | 3        | 14.29%  |
| 21     | 2        | 9.52%   |
| 54     | 1        | 4.76%   |
| 31     | 1        | 4.76%   |
| 28     | 1        | 4.76%   |
| 22     | 1        | 4.76%   |
| 18     | 1        | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 52.38%  |
| 401-500     | 5        | 23.81%  |
| 601-700     | 2        | 9.52%   |
| 351-400     | 2        | 9.52%   |
| 1001-1500   | 1        | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 16       | 76.19%  |
| 16/10 | 4        | 19.05%  |
| 5/4   | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 47.62%  |
| 301-350        | 4        | 19.05%  |
| 151-200        | 4        | 19.05%  |
| 351-500        | 2        | 9.52%   |
| More than 1000 | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 61.9%   |
| 101-120 | 5        | 23.81%  |
| 121-160 | 2        | 9.52%   |
| 161-240 | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 74       | 76.29%  |
| 1     | 23       | 23.71%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 65       | 54.62%  |
| Realtek Semiconductor    | 46       | 38.66%  |
| Qualcomm Atheros         | 3        | 2.52%   |
| Broadcom                 | 2        | 1.68%   |
| Ralink Technology        | 1        | 0.84%   |
| Marvell Technology Group | 1        | 0.84%   |
| Apple                    | 1        | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 37       | 26.81%  |
| Intel I211 Gigabit Network Connection                                  | 15       | 10.87%  |
| Intel Ethernet Controller I226-V                                       | 7        | 5.07%   |
| Intel Ethernet Controller I225-V                                       | 5        | 3.62%   |
| Intel 82583V Gigabit Network Connection                                | 5        | 3.62%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 2.9%    |
| Intel I350 Gigabit Network Connection                                  | 4        | 2.9%    |
| Intel Ethernet Connection I217-LM                                      | 4        | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 2.17%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 2.17%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 2.17%   |
| Intel Wireless 7260                                                    | 2        | 1.45%   |
| Intel Wireless 3165                                                    | 2        | 1.45%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 1.45%   |
| Intel Ethernet Connection X553 1GbE                                    | 2        | 1.45%   |
| Intel Ethernet Connection I217-V                                       | 2        | 1.45%   |
| Intel 82576 Gigabit Network Connection                                 | 2        | 1.45%   |
| Intel 82575EB Gigabit Network Connection                               | 2        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.72%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.72%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.72%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 0.72%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter        | 1        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1        | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.72%   |
| Intel Wireless 3160                                                    | 1        | 0.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1        | 0.72%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 0.72%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 0.72%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 1        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 52.38%  |
| Realtek Semiconductor | 5        | 23.81%  |
| Qualcomm Atheros      | 3        | 14.29%  |
| Ralink Technology     | 1        | 4.76%   |
| Broadcom              | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                             | 2        | 9.52%   |
| Intel Wireless 3165                                             | 2        | 9.52%   |
| Intel Wi-Fi 6 AX200                                             | 2        | 9.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 4.76%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 4.76%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 1        | 4.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1        | 4.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1        | 4.76%   |
| Ralink RT5370 Wireless Adapter                                  | 1        | 4.76%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 4.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1        | 4.76%   |
| Intel Wireless 3160                                             | 1        | 4.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 1        | 4.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 1        | 4.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 4.76%   |
| Intel CNVi: Wi-Fi                                               | 1        | 4.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 57       | 54.81%  |
| Realtek Semiconductor    | 44       | 42.31%  |
| Marvell Technology Group | 1        | 0.96%   |
| Broadcom                 | 1        | 0.96%   |
| Apple                    | 1        | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 37       | 31.62%  |
| Intel I211 Gigabit Network Connection                                  | 15       | 12.82%  |
| Intel Ethernet Controller I226-V                                       | 7        | 5.98%   |
| Intel Ethernet Controller I225-V                                       | 5        | 4.27%   |
| Intel 82583V Gigabit Network Connection                                | 5        | 4.27%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 3.42%   |
| Intel I350 Gigabit Network Connection                                  | 4        | 3.42%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 3.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 2.56%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 2.56%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 2.56%   |
| Intel Ethernet Connection X553 1GbE                                    | 2        | 1.71%   |
| Intel Ethernet Connection I217-V                                       | 2        | 1.71%   |
| Intel 82576 Gigabit Network Connection                                 | 2        | 1.71%   |
| Intel 82575EB Gigabit Network Connection                               | 2        | 1.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.85%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.85%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 0.85%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 1        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.85%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.85%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1        | 0.85%   |
| Intel 82580 Gigabit Network Connection                                 | 1        | 0.85%   |
| Intel 82575GB Gigabit Network Connection                               | 1        | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.85%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                        | 1        | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 83.19%  |
| WiFi     | 19       | 16.81%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 91       | 93.81%  |
| WiFi     | 6        | 6.19%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 37       | 38.54%  |
| 1     | 18       | 18.75%  |
| 4     | 16       | 16.67%  |
| 6     | 11       | 11.46%  |
| 5     | 6        | 6.25%   |
| 7     | 2        | 2.08%   |
| 3     | 2        | 2.08%   |
| 0     | 2        | 2.08%   |
| 10    | 1        | 1.04%   |
| 8     | 1        | 1.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 78       | 76.47%  |
| Yes  | 24       | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 64.29%  |
| Realtek Semiconductor           | 2        | 14.29%  |
| Qualcomm Atheros Communications | 1        | 7.14%   |
| Cambridge Silicon Radio         | 1        | 7.14%   |
| Apple                           | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 3        | 21.43%  |
| Intel AX200 Bluetooth                                       | 2        | 14.29%  |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 7.14%   |
| Realtek Bluetooth 4.0 Adapter                               | 1        | 7.14%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 7.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 7.14%   |
| Intel AX210 Bluetooth                                       | 1        | 7.14%   |
| Intel AX201 Bluetooth                                       | 1        | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 7.14%   |
| Apple Bluetooth Host Controller                             | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 62       | 65.96%  |
| AMD                    | 16       | 17.02%  |
| Nvidia                 | 14       | 14.89%  |
| Generalplus Technology | 1        | 1.06%   |
| C-Media Electronics    | 1        | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 6.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 5.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6        | 5.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 4.72%   |
| Intel Jasper Lake HD Audio                                                                        | 4        | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4        | 3.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 3.77%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 2.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 2.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 2.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 2.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 2.83%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 2.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3        | 2.83%   |
| AMD FCH Azalia Controller                                                                         | 3        | 2.83%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 2.83%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 1.89%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 1.89%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.89%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 1.89%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.94%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.94%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 0.94%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.94%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 0.94%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.94%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.94%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 0.94%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 1        | 0.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 22       | 21.78%  |
| Kingston            | 16       | 15.84%  |
| Unknown             | 15       | 14.85%  |
| SK hynix            | 10       | 9.9%    |
| Micron Technology   | 10       | 9.9%    |
| A-DATA Technology   | 8        | 7.92%   |
| Unknown             | 6        | 5.94%   |
| Corsair             | 3        | 2.97%   |
| Nanya Technology    | 2        | 1.98%   |
| G.Skill             | 2        | 1.98%   |
| Team                | 1        | 0.99%   |
| Ramsta              | 1        | 0.99%   |
| Ramaxel Technology  | 1        | 0.99%   |
| Juhor               | 1        | 0.99%   |
| GeIL                | 1        | 0.99%   |
| Elpida              | 1        | 0.99%   |
| Crucial             | 1        | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown                                                    | 6        | 5.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3        | 2.83%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                 | 2        | 1.89%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 2        | 1.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2        | 1.89%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 2        | 1.89%   |
| Kingston RAM KHX3200C16FB/8G 8GB SODIMM DDR4 2400MT/s      | 2        | 1.89%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s       | 2        | 1.89%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s              | 1        | 0.94%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s | 1        | 0.94%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                  | 1        | 0.94%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                  | 1        | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                 | 1        | 0.94%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 1        | 0.94%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 0.94%   |
| Unknown RAM Module 1GB DIMM SDRAM                          | 1        | 0.94%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                   | 1        | 0.94%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s      | 1        | 0.94%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s         | 1        | 0.94%   |
| SK hynix RAM Module 8GB DIMM DDR4 2400MT/s                 | 1        | 0.94%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM 1066MT/s            | 1        | 0.94%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s       | 1        | 0.94%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 0.94%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 0.94%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 0.94%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1        | 0.94%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s       | 1        | 0.94%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 1        | 0.94%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s       | 1        | 0.94%   |
| SK hynix RAM 8ATF1G64HZ-2G3A1 8GB DIMM DDR4 2400MT/s       | 1        | 0.94%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 1333MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5273DM0-CH9 4GB DIMM DDR3 1333MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 1        | 0.94%   |
| Samsung RAM M471B5273DH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 0.94%   |
| Samsung RAM M471B1G73QHO-YKO 4GB SODIMM DDR3 1600MT/s      | 1        | 0.94%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DDR3 1600MT/s             | 1        | 0.94%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1        | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 41       | 45.56%  |
| DDR4    | 40       | 44.44%  |
| DDR2    | 4        | 4.44%   |
| Unknown | 3        | 3.33%   |
| SDRAM   | 1        | 1.11%   |
| DDR5    | 1        | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 53       | 58.24%  |
| SODIMM  | 35       | 38.46%  |
| Unknown | 2        | 2.2%    |
| RIMM    | 1        | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 36       | 37.11%  |
| 4096  | 33       | 34.02%  |
| 2048  | 15       | 15.46%  |
| 16384 | 11       | 11.34%  |
| 1024  | 2        | 2.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 25.51%  |
| 2400    | 15       | 15.31%  |
| 2133    | 13       | 13.27%  |
| 1333    | 11       | 11.22%  |
| 2667    | 7        | 7.14%   |
| 800     | 7        | 7.14%   |
| 3200    | 6        | 6.12%   |
| 2666    | 3        | 3.06%   |
| 1334    | 3        | 3.06%   |
| 2933    | 2        | 2.04%   |
| 667     | 2        | 2.04%   |
| 4800    | 1        | 1.02%   |
| 1867    | 1        | 1.02%   |
| 1066    | 1        | 1.02%   |
| Unknown | 1        | 1.02%   |

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


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Z-Star Lenovo USB 2.0 UVC Camera | 1        | 25%     |
| Microdia Camera                  | 1        | 25%     |
| Logitech Webcam C170             | 1        | 25%     |
| Logitech C670i FHD Webcam        | 1        | 25%     |

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
| 1     | 44       | 45.83%  |
| 0     | 39       | 40.63%  |
| 2     | 12       | 12.5%   |
| 4     | 1        | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 53       | 77.94%  |
| Net/wireless             | 7        | 10.29%  |
| Sound                    | 2        | 2.94%   |
| Net/ethernet             | 2        | 2.94%   |
| Card reader              | 2        | 2.94%   |
| Bluetooth                | 2        | 2.94%   |

