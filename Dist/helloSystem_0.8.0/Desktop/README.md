helloSystem 0.8.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 99

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Fujitsu   | D3009-A1 S26361-D3009-A1    | [66739867ed](https://bsd-hardware.info/?probe=66739867ed) | Feb 26, 2023 |
| ASUSTek   | ROG STRIX Z390-E GAMING     | [be81f2675f](https://bsd-hardware.info/?probe=be81f2675f) | Feb 25, 2023 |
| ASRock    | X470 Gaming K4              | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [31122bd298](https://bsd-hardware.info/?probe=31122bd298) | Feb 24, 2023 |
| Gigabyte  | A320M-H-CF                  | [02970305db](https://bsd-hardware.info/?probe=02970305db) | Feb 21, 2023 |
| Gigabyte  | B450M AORUS ELITE           | [6af537ff20](https://bsd-hardware.info/?probe=6af537ff20) | Feb 18, 2023 |
| ASUSTek   | PRIME H310M-C R2.0          | [9761fb446b](https://bsd-hardware.info/?probe=9761fb446b) | Feb 18, 2023 |
| ASRock    | A320M-DGS                   | [032d7f0c91](https://bsd-hardware.info/?probe=032d7f0c91) | Feb 17, 2023 |
| ASUSTek   | P8Z68-V LX                  | [99ede66a89](https://bsd-hardware.info/?probe=99ede66a89) | Feb 16, 2023 |
| ASUSTek   | PRIME A320M-K               | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| Dell      | 0D28YY A03                  | [b8dc69069d](https://bsd-hardware.info/?probe=b8dc69069d) | Feb 12, 2023 |
| Dell      | 0PU052                      | [03bcc500c0](https://bsd-hardware.info/?probe=03bcc500c0) | Feb 12, 2023 |
| Dell      | 0PU052                      | [035408150f](https://bsd-hardware.info/?probe=035408150f) | Feb 11, 2023 |
| ASUSTek   | P8Z68-V                     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| ASRock    | H61M/U3S3                   | [48c80bbb1f](https://bsd-hardware.info/?probe=48c80bbb1f) | Feb 11, 2023 |
| HP        | 83EE                        | [cf914f58eb](https://bsd-hardware.info/?probe=cf914f58eb) | Feb 10, 2023 |
| ASRock    | A770DE+                     | [cf1c018ede](https://bsd-hardware.info/?probe=cf1c018ede) | Feb 10, 2023 |
| Lenovo    | MAHOBAY NOK                 | [d6be869761](https://bsd-hardware.info/?probe=d6be869761) | Feb 09, 2023 |
| Biostar   | TA970                       | [8c1a7aedf1](https://bsd-hardware.info/?probe=8c1a7aedf1) | Feb 09, 2023 |
| ASUSTek   | M5A78L-M LX3                | [9af803f850](https://bsd-hardware.info/?probe=9af803f850) | Feb 08, 2023 |
| MSI       | Z97 GAMING 3                | [bbe7b327fd](https://bsd-hardware.info/?probe=bbe7b327fd) | Feb 06, 2023 |
| AOpen     | D1007 0BBA                  | [0873652381](https://bsd-hardware.info/?probe=0873652381) | Feb 06, 2023 |
| ASUSTek   | P8Z77-M                     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| Biostar   | H61MLV3                     | [dee9a22461](https://bsd-hardware.info/?probe=dee9a22461) | Feb 06, 2023 |
| MSI       | MPG X570 GAMING PLUS        | [c04d9caf55](https://bsd-hardware.info/?probe=c04d9caf55) | Feb 06, 2023 |
| Gigabyte  | H510M S2H V2                | [85628154a2](https://bsd-hardware.info/?probe=85628154a2) | Feb 05, 2023 |
| Dell      | 0PC5F7 A02                  | [5512097fd0](https://bsd-hardware.info/?probe=5512097fd0) | Feb 05, 2023 |
| ASUSTek   | PRIME B450M-A               | [7c56590eaa](https://bsd-hardware.info/?probe=7c56590eaa) | Feb 03, 2023 |
| Gigabyte  | F2A88XM-D3H                 | [fa88a5ce31](https://bsd-hardware.info/?probe=fa88a5ce31) | Feb 02, 2023 |
| HP        | 1496                        | [fae90baa23](https://bsd-hardware.info/?probe=fae90baa23) | Jan 31, 2023 |
| Dell      | 0F373D A00                  | [cd4202e58b](https://bsd-hardware.info/?probe=cd4202e58b) | Jan 30, 2023 |
| ASUSTek   | M4A89TD PRO USB3            | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Gigabyte  | GA-MA770T-UD3               | [6b63a16799](https://bsd-hardware.info/?probe=6b63a16799) | Jan 26, 2023 |
| Gigabyte  | B360M D2V                   | [6685066b6e](https://bsd-hardware.info/?probe=6685066b6e) | Jan 26, 2023 |
| ASUSTek   | H81M-D R2.0                 | [07982549ac](https://bsd-hardware.info/?probe=07982549ac) | Jan 26, 2023 |
| Gigabyte  | H61M-S2PV                   | [9a307961ed](https://bsd-hardware.info/?probe=9a307961ed) | Jan 26, 2023 |
| ASUSTek   | PRIME H310M-K               | [1c97950ce9](https://bsd-hardware.info/?probe=1c97950ce9) | Jan 25, 2023 |
| HP        | 802E                        | [1f3bf517af](https://bsd-hardware.info/?probe=1f3bf517af) | Jan 25, 2023 |
| Google    | Panther                     | [73d3147166](https://bsd-hardware.info/?probe=73d3147166) | Jan 24, 2023 |
| Dell      | 0DFRFW A01                  | [23415b954f](https://bsd-hardware.info/?probe=23415b954f) | Jan 24, 2023 |
| HP        | 1495                        | [69faf0563a](https://bsd-hardware.info/?probe=69faf0563a) | Jan 24, 2023 |
| Gigabyte  | GA-990X-Gaming SLI-CF       | [9cd4d2810a](https://bsd-hardware.info/?probe=9cd4d2810a) | Jan 23, 2023 |
| ASRock    | Z390 Pro4                   | [b9d64a7496](https://bsd-hardware.info/?probe=b9d64a7496) | Jan 23, 2023 |
| Gigabyte  | X570 AORUS PRO              | [6cf4f6761e](https://bsd-hardware.info/?probe=6cf4f6761e) | Jan 23, 2023 |
| Gigabyte  | A520M S2H                   | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek   | PRIME A320M-K               | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| ASUSTek   | J1800I-C                    | [27ea626000](https://bsd-hardware.info/?probe=27ea626000) | Jan 23, 2023 |
| ASUSTek   | J1800I-C                    | [abc17c6fc6](https://bsd-hardware.info/?probe=abc17c6fc6) | Jan 23, 2023 |
| MSI       | B450M MORTAR MAX            | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| ASUSTek   | X99-A/USB                   | [006553f965](https://bsd-hardware.info/?probe=006553f965) | Jan 23, 2023 |
| Gigabyte  | H81M-H                      | [4b3a05fc2a](https://bsd-hardware.info/?probe=4b3a05fc2a) | Jan 22, 2023 |
| ASUSTek   | P5KPL-AM SE                 | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Dell      | 03KWTV A02                  | [28088f7e94](https://bsd-hardware.info/?probe=28088f7e94) | Jan 22, 2023 |
| Gigabyte  | H270M-DS3H-CF               | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| Gigabyte  | G1.Sniper A88X-CF           | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| Dell      | 0K240Y A02                  | [379b59f079](https://bsd-hardware.info/?probe=379b59f079) | Jan 05, 2023 |
| Gigabyte  | X399 AORUS Gaming 7         | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| ASUSTek   | CM1530                      | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| ASUSTek   | PRIME Z390M-PLUS            | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| Dell      | 0M017G A00                  | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Gigabyte  | P61-USB3-B3                 | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte  | P61-USB3-B3                 | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte  | H61M-S1                     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte  | 970A-D3P                    | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte  | 970A-D3P                    | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek   | P5KPL-VM-TWPC               | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| HP        | 1998                        | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| Gigabyte  | H270M-DS3H-CF               | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| Lenovo    | 3106 SDK0J40705 WIN 3425... | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| HP        | 843B                        | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| HP        | 843B                        | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| MSI       | B450M PRO-VDH PLUS          | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| HP        | 86FC MVB                    | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP        | 86FC MVB                    | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Dell      | 0T10XW A01                  | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| ASRock    | ConRoeXFire-eSATA2          | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| ASUSTek   | ROG STRIX B550-I GAMING     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| ASUSTek   | P5QL-ASUS-SE                | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| ASUSTek   | K30AM-J                     | [470ced8f30](https://bsd-hardware.info/?probe=470ced8f30) | Aug 05, 2022 |
| MSI       | MPG X570 GAMING PLUS        | [a80b1c4f3c](https://bsd-hardware.info/?probe=a80b1c4f3c) | Jul 17, 2022 |
| HP        | 1998                        | [e4fda48283](https://bsd-hardware.info/?probe=e4fda48283) | Jul 15, 2022 |
| Pegatron  | IPM41-D3                    | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Biostar   | G41D3C                      | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| ASUSTek   | K30AM-J                     | [f4352f7897](https://bsd-hardware.info/?probe=f4352f7897) | May 16, 2022 |
| Lenovo    | 30D9 SDK0J40705 WIN 3425... | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| MSI       | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASRock    | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel     | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| ASUSTek   | TUF GAMING X570-PLUS        | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| AMD       | X64                         | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| MACHINIST | X99-k9 V2.0                 | [0a36d71db1](https://bsd-hardware.info/?probe=0a36d71db1) | Feb 10, 2022 |
| Pegatron  | IPPPV-D3G                   | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| Intel     | MAHOBAY                     | [2036093b68](https://bsd-hardware.info/?probe=2036093b68) | Jan 25, 2022 |
| HP        | 8648                        | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| Dell      | 0593VH A00                  | [484d14dbef](https://bsd-hardware.info/?probe=484d14dbef) | Jan 22, 2022 |
| ASRock    | B365M Pro4                  | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| Dell      | 0YF8P5 A00                  | [913b2a7483](https://bsd-hardware.info/?probe=913b2a7483) | Jan 18, 2022 |
| Dell      | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 90       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 89       | 98.89%  |
| KDE5         | 1        | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 90       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 90       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 37       | 40.22%  |
| en    | 27       | 29.35%  |
| fr    | 8        | 8.7%    |
| ru    | 5        | 5.43%   |
| pt    | 3        | 3.26%   |
| es    | 3        | 3.26%   |
| en_GB | 2        | 2.17%   |
| zh_TW | 1        | 1.09%   |
| pl    | 1        | 1.09%   |
| nl    | 1        | 1.09%   |
| it    | 1        | 1.09%   |
| es_ES | 1        | 1.09%   |
| de_DE | 1        | 1.09%   |
| de    | 1        | 1.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 89       | 98.89%  |
| BIOS | 1        | 1.11%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 63       | 69.23%  |
| Zfs    | 28       | 30.77%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 89       | 98.89%  |
| MBR  | 1        | 1.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 23.33%  |
| Gigabyte Technology | 17       | 18.89%  |
| Dell                | 12       | 13.33%  |
| Hewlett-Packard     | 9        | 10%     |
| ASRock              | 8        | 8.89%   |
| MSI                 | 6        | 6.67%   |
| Lenovo              | 5        | 5.56%   |
| Biostar             | 3        | 3.33%   |
| Pegatron            | 2        | 2.22%   |
| Intel               | 2        | 2.22%   |
| MACHINIST           | 1        | 1.11%   |
| Google              | 1        | 1.11%   |
| Fujitsu             | 1        | 1.11%   |
| AOpen               | 1        | 1.11%   |
| AMD                 | 1        | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 3.33%   |
| MSI MS-7C37                         | 2        | 2.22%   |
| MSI MS-7A38                         | 2        | 2.22%   |
| Pegatron IPPPV-D3G                  | 1        | 1.11%   |
| Pegatron IPM41-D3                   | 1        | 1.11%   |
| MSI MS-7B89                         | 1        | 1.11%   |
| MSI MS-7918                         | 1        | 1.11%   |
| MACHINIST X99-k9 V2.0               | 1        | 1.11%   |
| Lenovo ThinkCentre M93p 10AB004DUS  | 1        | 1.11%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK  | 1        | 1.11%   |
| Lenovo ThinkCentre M910s 10MK0039US | 1        | 1.11%   |
| Lenovo ThinkCentre M82 2929AZ6      | 1        | 1.11%   |
| Lenovo ThinkCentre M700 10GS        | 1        | 1.11%   |
| Intel MAHOBAY                       | 1        | 1.11%   |
| Intel DN2800MT AAG23738-600         | 1        | 1.11%   |
| HP Z240 SFF Workstation             | 1        | 1.11%   |
| HP Slim Desktop S01-aF1xxx          | 1        | 1.11%   |
| HP ProDesk 600 G4 SFF               | 1        | 1.11%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.11%   |
| HP EliteDesk 800 G1 SFF             | 1        | 1.11%   |
| HP EliteDesk 700 G1 SFF             | 1        | 1.11%   |
| HP Desktop Pro A G3                 | 1        | 1.11%   |
| HP Compaq 8200 Elite USDT PC        | 1        | 1.11%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 1.11%   |
| Google Panther                      | 1        | 1.11%   |
| Gigabyte X570 AORUS PRO             | 1        | 1.11%   |
| Gigabyte X399 AORUS Gaming 7        | 1        | 1.11%   |
| Gigabyte P61-USB3-B3                | 1        | 1.11%   |
| Gigabyte H81M-H                     | 1        | 1.11%   |
| Gigabyte H61M-S2PV                  | 1        | 1.11%   |
| Gigabyte H61M-S1                    | 1        | 1.11%   |
| Gigabyte H510M S2H V2               | 1        | 1.11%   |
| Gigabyte H270M-DS3H                 | 1        | 1.11%   |
| Gigabyte GA-MA770T-UD3              | 1        | 1.11%   |
| Gigabyte GA-990X-Gaming SLI-CF      | 1        | 1.11%   |
| Gigabyte G1.Sniper A88X-CF          | 1        | 1.11%   |
| Gigabyte F2A88XM-D3H                | 1        | 1.11%   |
| Gigabyte B450M AORUS ELITE          | 1        | 1.11%   |
| Gigabyte B360M-D2V                  | 1        | 1.11%   |
| Gigabyte A520M S2H                  | 1        | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 7        | 7.78%   |
| Lenovo ThinkCentre      | 5        | 5.56%   |
| ASUS PRIME              | 4        | 4.44%   |
| ASUS All                | 3        | 3.33%   |
| MSI MS-7C37             | 2        | 2.22%   |
| MSI MS-7A38             | 2        | 2.22%   |
| HP EliteDesk            | 2        | 2.22%   |
| HP Compaq               | 2        | 2.22%   |
| Dell Precision          | 2        | 2.22%   |
| Dell Inspiron           | 2        | 2.22%   |
| ASUS ROG                | 2        | 2.22%   |
| ASUS P8Z68-V            | 2        | 2.22%   |
| Pegatron IPPPV-D3G      | 1        | 1.11%   |
| Pegatron IPM41-D3       | 1        | 1.11%   |
| MSI MS-7B89             | 1        | 1.11%   |
| MSI MS-7918             | 1        | 1.11%   |
| MACHINIST X99-k9        | 1        | 1.11%   |
| Intel MAHOBAY           | 1        | 1.11%   |
| Intel DN2800MT          | 1        | 1.11%   |
| HP Z240                 | 1        | 1.11%   |
| HP Slim                 | 1        | 1.11%   |
| HP ProDesk              | 1        | 1.11%   |
| HP Pavilion             | 1        | 1.11%   |
| HP Desktop              | 1        | 1.11%   |
| Google Panther          | 1        | 1.11%   |
| Gigabyte X570           | 1        | 1.11%   |
| Gigabyte X399           | 1        | 1.11%   |
| Gigabyte P61-USB3-B3    | 1        | 1.11%   |
| Gigabyte H81M-H         | 1        | 1.11%   |
| Gigabyte H61M-S2PV      | 1        | 1.11%   |
| Gigabyte H61M-S1        | 1        | 1.11%   |
| Gigabyte H510M          | 1        | 1.11%   |
| Gigabyte H270M-DS3H     | 1        | 1.11%   |
| Gigabyte GA-MA770T-UD3  | 1        | 1.11%   |
| Gigabyte GA-990X-Gaming | 1        | 1.11%   |
| Gigabyte G1.Sniper      | 1        | 1.11%   |
| Gigabyte F2A88XM-D3H    | 1        | 1.11%   |
| Gigabyte B450M          | 1        | 1.11%   |
| Gigabyte B360M-D2V      | 1        | 1.11%   |
| Gigabyte A520M          | 1        | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 12       | 13.33%  |
| 2018 | 10       | 11.11%  |
| 2013 | 8        | 8.89%   |
| 2012 | 8        | 8.89%   |
| 2020 | 7        | 7.78%   |
| 2015 | 7        | 7.78%   |
| 2011 | 7        | 7.78%   |
| 2021 | 6        | 6.67%   |
| 2014 | 6        | 6.67%   |
| 2010 | 6        | 6.67%   |
| 2022 | 5        | 5.56%   |
| 2017 | 2        | 2.22%   |
| 2016 | 2        | 2.22%   |
| 2009 | 2        | 2.22%   |
| 2008 | 2        | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 90       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 89       | 98.89%  |
| Yes  | 1        | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 28       | 31.11%  |
| 16.01-24.0  | 27       | 30%     |
| 4.01-8.0    | 18       | 20%     |
| 32.01-64.0  | 6        | 6.67%   |
| 2.01-3.0    | 5        | 5.56%   |
| 64.01-256.0 | 4        | 4.44%   |
| 24.01-32.0  | 1        | 1.11%   |
| 0.51-1.0    | 1        | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 42       | 46.67%  |
| 0.51-1.0  | 26       | 28.89%  |
| 1.01-2.0  | 15       | 16.67%  |
| 2.01-3.0  | 5        | 5.56%   |
| 4.01-8.0  | 1        | 1.11%   |
| 8.01-16.0 | 1        | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 50%     |
| 2      | 22       | 23.91%  |
| 3      | 11       | 11.96%  |
| 4      | 5        | 5.43%   |
| 5      | 4        | 4.35%   |
| 6      | 2        | 2.17%   |
| 0      | 2        | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 62.22%  |
| Yes       | 34       | 37.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 90       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 68.13%  |
| Yes       | 29       | 31.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 73.33%  |
| Yes       | 24       | 26.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 17       | 18.89%  |
| Russia       | 13       | 14.44%  |
| Brazil       | 7        | 7.78%   |
| Spain        | 6        | 6.67%   |
| Germany      | 6        | 6.67%   |
| Taiwan       | 5        | 5.56%   |
| UK           | 4        | 4.44%   |
| Poland       | 3        | 3.33%   |
| Italy        | 3        | 3.33%   |
| Canada       | 3        | 3.33%   |
| Portugal     | 2        | 2.22%   |
| Indonesia    | 2        | 2.22%   |
| India        | 2        | 2.22%   |
| France       | 2        | 2.22%   |
| Belgium      | 2        | 2.22%   |
| Thailand     | 1        | 1.11%   |
| South Africa | 1        | 1.11%   |
| Serbia       | 1        | 1.11%   |
| Peru         | 1        | 1.11%   |
| Norway       | 1        | 1.11%   |
| Mexico       | 1        | 1.11%   |
| Japan        | 1        | 1.11%   |
| Hungary      | 1        | 1.11%   |
| Colombia     | 1        | 1.11%   |
| China        | 1        | 1.11%   |
| Bulgaria     | 1        | 1.11%   |
| Australia    | 1        | 1.11%   |
| Argentina    | 1        | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Aquan                  | 4        | 4.35%   |
| Moscow                 | 3        | 3.26%   |
| Yekaterinburg          | 2        | 2.17%   |
| Voronezh               | 2        | 2.17%   |
| Volgograd              | 2        | 2.17%   |
| Temple                 | 2        | 2.17%   |
| Saratov                | 2        | 2.17%   |
| Gistel                 | 2        | 2.17%   |
| Zhengzhou              | 1        | 1.09%   |
| Yala                   | 1        | 1.09%   |
| Winnipeg               | 1        | 1.09%   |
| Willingboro            | 1        | 1.09%   |
| Veliko Tarnovo         | 1        | 1.09%   |
| Valledupar             | 1        | 1.09%   |
| Valencia               | 1        | 1.09%   |
| Trieste                | 1        | 1.09%   |
| Trebujena              | 1        | 1.09%   |
| Tasikmalaya            | 1        | 1.09%   |
| Tallahassee            | 1        | 1.09%   |
| Szigetszentmiklos      | 1        | 1.09%   |
| Surrey                 | 1        | 1.09%   |
| Sumaré                | 1        | 1.09%   |
| Southminster           | 1        | 1.09%   |
| Seville                | 1        | 1.09%   |
| Sao Domingos das Dores | 1        | 1.09%   |
| Salisbury              | 1        | 1.09%   |
| Salem                  | 1        | 1.09%   |
| Rosignano Marittimo    | 1        | 1.09%   |
| Richardson             | 1        | 1.09%   |
| Rhinelander            | 1        | 1.09%   |
| Remshalden             | 1        | 1.09%   |
| Reinsvoll              | 1        | 1.09%   |
| Recklinghausen         | 1        | 1.09%   |
| Québec                | 1        | 1.09%   |
| Portland               | 1        | 1.09%   |
| Pieve a Nievole        | 1        | 1.09%   |
| Palembang              | 1        | 1.09%   |
| Osasco                 | 1        | 1.09%   |
| Oryol                  | 1        | 1.09%   |
| Oklahoma City          | 1        | 1.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 38     | 18.79%  |
| Seagate             | 24       | 27     | 16.11%  |
| Samsung Electronics | 22       | 27     | 14.77%  |
| Hitachi             | 11       | 13     | 7.38%   |
| Toshiba             | 9        | 10     | 6.04%   |
| Kingston            | 9        | 10     | 6.04%   |
| Crucial             | 7        | 9      | 4.7%    |
| A-DATA Technology   | 6        | 7      | 4.03%   |
| SanDisk             | 5        | 6      | 3.36%   |
| SPCC                | 2        | 2      | 1.34%   |
| PNY                 | 2        | 2      | 1.34%   |
| Patriot             | 2        | 2      | 1.34%   |
| Lexar               | 2        | 3      | 1.34%   |
| Hewlett-Packard     | 2        | 2      | 1.34%   |
| XrayDisk            | 1        | 1      | 0.67%   |
| Transcend           | 1        | 1      | 0.67%   |
| SK hynix            | 1        | 1      | 0.67%   |
| Silicon Motion      | 1        | 1      | 0.67%   |
| Reletech            | 1        | 1      | 0.67%   |
| Plextor             | 1        | 1      | 0.67%   |
| Pioneer             | 1        | 1      | 0.67%   |
| OCZ                 | 1        | 1      | 0.67%   |
| MidasForce          | 1        | 1      | 0.67%   |
| Micron Technology   | 1        | 1      | 0.67%   |
| LDLC                | 1        | 1      | 0.67%   |
| KingSpec            | 1        | 1      | 0.67%   |
| Intenso             | 1        | 1      | 0.67%   |
| Gigabyte Technology | 1        | 1      | 0.67%   |
| Fanxiang            | 1        | 1      | 0.67%   |
| Emtec               | 1        | 1      | 0.67%   |
| Corsair             | 1        | 1      | 0.67%   |
| China               | 1        | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 3        | 1.78%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 1.18%   |
| Toshiba MQ01ABD050 500GB        | 2        | 1.18%   |
| Toshiba HDWD110 1TB             | 2        | 1.18%   |
| Seagate ST3250310AS 250GB       | 2        | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 1.18%   |
| Samsung SSD 860 EVO 1TB         | 2        | 1.18%   |
| Samsung HD322HJ 320GB           | 2        | 1.18%   |
| Kingston SA400S37240G 240GB     | 2        | 1.18%   |
| Hitachi HDS721616PLA380 160GB   | 2        | 1.18%   |
| A-DATA SU800 256GB              | 2        | 1.18%   |
| XrayDisk SSD 256GB              | 1        | 0.59%   |
| WDC WDS500G3XHC-00SJG0 500GB    | 1        | 0.59%   |
| WDC WDS500G2X0C-00L350 500GB    | 1        | 0.59%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.59%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 0.59%   |
| WDC WDS120G2G0B-00EPW0 120GB    | 1        | 0.59%   |
| WDC WD80EFAX-68KNBN0 8TB        | 1        | 0.59%   |
| WDC WD50NPZZ-00A9JT0 5TB        | 1        | 0.59%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.59%   |
| WDC WD5000LPCX-60VHAT0 500GB    | 1        | 0.59%   |
| WDC WD5000AZLX-60K2TA1 500GB    | 1        | 0.59%   |
| WDC WD5000AVVS-63H0B1 500GB     | 1        | 0.59%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1        | 0.59%   |
| WDC WD5000AAKS-00YGA0 500GB     | 1        | 0.59%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.59%   |
| WDC WD3200BEVT-00ZCT0 320GB     | 1        | 0.59%   |
| WDC WD3200AAKS-75L9A0 320GB     | 1        | 0.59%   |
| WDC WD3003FZEX-00Z4SA0 3TB      | 1        | 0.59%   |
| WDC WD2500BEVT-75A23T0 250GB    | 1        | 0.59%   |
| WDC WD20EZAZ-22L9GB0 2TB        | 1        | 0.59%   |
| WDC WD20EFRX-68EUZN0 2TB        | 1        | 0.59%   |
| WDC WD20EARS-00MVWB0 2TB        | 1        | 0.59%   |
| WDC WD2003FYYS-02W0B1 2TB       | 1        | 0.59%   |
| WDC WD2002FFSX-68PF8N0 2TB      | 1        | 0.59%   |
| WDC WD2002FAEX-007BA0 2TB       | 1        | 0.59%   |
| WDC WD1600AAJS-61WAA0 160GB     | 1        | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB        | 1        | 0.59%   |
| WDC WD10EZRZ-00HTKB0 1TB        | 1        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 27     | 32.88%  |
| WDC                 | 23       | 29     | 31.51%  |
| Hitachi             | 11       | 13     | 15.07%  |
| Samsung Electronics | 8        | 8      | 10.96%  |
| Toshiba             | 6        | 7      | 8.22%   |
| Hewlett-Packard     | 1        | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 14.75%  |
| Kingston            | 7        | 8      | 11.48%  |
| Crucial             | 6        | 8      | 9.84%   |
| A-DATA Technology   | 6        | 7      | 9.84%   |
| SanDisk             | 5        | 6      | 8.2%    |
| WDC                 | 4        | 5      | 6.56%   |
| Toshiba             | 3        | 3      | 4.92%   |
| SPCC                | 2        | 2      | 3.28%   |
| PNY                 | 2        | 2      | 3.28%   |
| Patriot             | 2        | 2      | 3.28%   |
| XrayDisk            | 1        | 1      | 1.64%   |
| Transcend           | 1        | 1      | 1.64%   |
| Plextor             | 1        | 1      | 1.64%   |
| Pioneer             | 1        | 1      | 1.64%   |
| OCZ                 | 1        | 1      | 1.64%   |
| MidasForce          | 1        | 1      | 1.64%   |
| Micron Technology   | 1        | 1      | 1.64%   |
| Lexar               | 1        | 1      | 1.64%   |
| KingSpec            | 1        | 1      | 1.64%   |
| Intenso             | 1        | 1      | 1.64%   |
| Hewlett-Packard     | 1        | 1      | 1.64%   |
| Gigabyte Technology | 1        | 1      | 1.64%   |
| Fanxiang            | 1        | 1      | 1.64%   |
| Emtec               | 1        | 1      | 1.64%   |
| China               | 1        | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 57       | 85     | 46.72%  |
| SSD  | 47       | 70     | 38.52%  |
| NVMe | 18       | 21     | 14.75%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 84       | 155    | 82.35%  |
| NVMe | 18       | 21     | 17.65%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 70       | 102    | 63.06%  |
| 0.51-1.0   | 24       | 30     | 21.62%  |
| 1.01-2.0   | 13       | 18     | 11.71%  |
| 4.01-10.0  | 2        | 2      | 1.8%    |
| 3.01-4.0   | 1        | 1      | 0.9%    |
| 2.01-3.0   | 1        | 2      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 58       | 63.74%  |
| 101-250    | 14       | 15.38%  |
| 251-500    | 9        | 9.89%   |
| 501-1000   | 4        | 4.4%    |
| 1001-2000  | 3        | 3.3%    |
| 51-100     | 2        | 2.2%    |
| 21-50      | 1        | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 87       | 95.6%   |
| 101-250  | 3        | 3.3%    |
| 501-1000 | 1        | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 10%     |
| WDC WD5000LPCX-60VHAT0 500GB      | 1        | 1      | 5%      |
| WDC WD5000AVVS-63H0B1 500GB       | 1        | 1      | 5%      |
| WDC WD10EZRZ-00HTKB0 1TB          | 1        | 1      | 5%      |
| WDC WD10EADS-65M2BX 1TB           | 1        | 1      | 5%      |
| WDC WD10EACS-00D6B1 1TB           | 1        | 2      | 5%      |
| Toshiba MK1255GSX H 120GB         | 1        | 1      | 5%      |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 5%      |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 5%      |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 5%      |
| Pioneer APS-SL3N-240 240GB        | 1        | 1      | 5%      |
| OCZ VERTEX3 240GB                 | 1        | 1      | 5%      |
| MidasForce SSD 120GB              | 1        | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB     | 1        | 1      | 5%      |
| Hitachi HTS541680J9SA00 80GB      | 1        | 1      | 5%      |
| Hitachi HDT721010SLA360 1TB       | 1        | 1      | 5%      |
| Hitachi HDS721616PLA380 160GB     | 1        | 1      | 5%      |
| Crucial CT1050MX300SSD1 1TB       | 1        | 1      | 5%      |
| A-DATA Technology SU800 256GB     | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 25%     |
| Hitachi             | 4        | 4      | 20%     |
| Seagate             | 3        | 3      | 15%     |
| Samsung Electronics | 2        | 2      | 10%     |
| Toshiba             | 1        | 1      | 5%      |
| Pioneer             | 1        | 1      | 5%      |
| OCZ                 | 1        | 1      | 5%      |
| MidasForce          | 1        | 1      | 5%      |
| Crucial             | 1        | 1      | 5%      |
| A-DATA Technology   | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 33.33%  |
| Hitachi             | 4        | 4      | 26.67%  |
| Seagate             | 3        | 3      | 20%     |
| Samsung Electronics | 2        | 2      | 13.33%  |
| Toshiba             | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 16     | 75%     |
| SSD  | 5        | 5      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST3250310AS 250GB       | 1        | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 73       | 140    | 73%     |
| Malfunc  | 18       | 21     | 18%     |
| Detected | 7        | 13     | 7%      |
| Failed   | 2        | 2      | 2%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 61       | 50.83%  |
| AMD                          | 29       | 24.17%  |
| Samsung Electronics          | 6        | 5%      |
| SanDisk                      | 4        | 3.33%   |
| JMicron Technology           | 4        | 3.33%   |
| ASMedia Technology           | 3        | 2.5%    |
| Silicon Motion               | 2        | 1.67%   |
| Shenzhen Longsys Electronics | 2        | 1.67%   |
| Phison Electronics           | 2        | 1.67%   |
| Kingston Technology Company  | 2        | 1.67%   |
| SK hynix                     | 1        | 0.83%   |
| Realtek Semiconductor        | 1        | 0.83%   |
| Micron/Crucial Technology    | 1        | 0.83%   |
| Marvell Technology Group     | 1        | 0.83%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 9.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 5.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 3.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 3.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 3.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 3.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 1.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.97%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.97%   |
| Unknown                                                                                 | 3        | 1.97%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.32%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2        | 1.32%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 1.32%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.32%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.32%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.32%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.32%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1        | 0.66%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1        | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.66%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.66%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.66%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 1        | 0.66%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]                       | 1        | 0.66%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 69       | 58.97%  |
| IDE  | 26       | 22.22%  |
| NVMe | 19       | 16.24%  |
| RAID | 3        | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 61       | 67.78%  |
| AMD    | 29       | 32.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 3.33%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 3.33%   |
| Intel Core 2 Duo                            | 3        | 3.33%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 2.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 2.22%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.22%   |
| AMD Phenom II X4 945 Processor              | 2        | 2.22%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 1.11%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1        | 1.11%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 1.11%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.11%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 1.11%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.11%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.11%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.11%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.11%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.11%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.11%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.11%   |
| Intel Core i9-9900KS CPU @ 4.00GHz          | 1        | 1.11%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.11%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.11%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 1.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.11%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.11%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.11%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.11%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.11%   |
| Intel Core i5-8500T CPU @ 2.10GHz           | 1        | 1.11%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.11%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.11%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.11%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 1.11%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.11%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.11%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.11%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.11%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.11%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.11%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 22.22%  |
| Intel Core i3           | 9        | 10%     |
| AMD Ryzen 5             | 7        | 7.78%   |
| Intel Core i7           | 6        | 6.67%   |
| AMD Phenom II X4        | 5        | 5.56%   |
| Intel Xeon              | 4        | 4.44%   |
| Intel Pentium Dual-Core | 4        | 4.44%   |
| Intel Core 2 Duo        | 4        | 4.44%   |
| Intel Celeron           | 4        | 4.44%   |
| Intel Pentium           | 3        | 3.33%   |
| AMD FX                  | 3        | 3.33%   |
| Other                   | 2        | 2.22%   |
| Intel Atom              | 2        | 2.22%   |
| AMD Ryzen 9             | 2        | 2.22%   |
| AMD Ryzen 7             | 2        | 2.22%   |
| AMD Ryzen 3             | 2        | 2.22%   |
| Intel Pentium Silver    | 1        | 1.11%   |
| Intel Core i9           | 1        | 1.11%   |
| Intel Core 2 Quad       | 1        | 1.11%   |
| Intel Core 2            | 1        | 1.11%   |
| AMD Ryzen Threadripper  | 1        | 1.11%   |
| AMD Ryzen 5 PRO         | 1        | 1.11%   |
| AMD Ryzen 3 PRO         | 1        | 1.11%   |
| AMD Athlon II X4        | 1        | 1.11%   |
| AMD Athlon              | 1        | 1.11%   |
| AMD A8                  | 1        | 1.11%   |
| AMD A10                 | 1        | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 37       | 41.11%  |
| 2       | 21       | 23.33%  |
| 6       | 10       | 11.11%  |
| 8       | 7        | 7.78%   |
| 12      | 5        | 5.56%   |
| 16      | 3        | 3.33%   |
| Unknown | 3        | 3.33%   |
| 24      | 2        | 2.22%   |
| 10      | 1        | 1.11%   |
| 1       | 1        | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 90       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 69       | 76.67%  |
| 2       | 18       | 20%     |
| Unknown | 3        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 11       | 12.22%  |
| Haswell       | 11       | 12.22%  |
| SandyBridge   | 9        | 10%     |
| Penryn        | 7        | 7.78%   |
| Zen+          | 6        | 6.67%   |
| K10           | 6        | 6.67%   |
| IvyBridge     | 6        | 6.67%   |
| Zen 2         | 4        | 4.44%   |
| Zen           | 4        | 4.44%   |
| Core          | 4        | 4.44%   |
| Zen 3         | 3        | 3.33%   |
| Skylake       | 3        | 3.33%   |
| Piledriver    | 3        | 3.33%   |
| Silvermont    | 2        | 2.22%   |
| CometLake     | 2        | 2.22%   |
| Bonnell       | 2        | 2.22%   |
| Unknown       | 2        | 2.22%   |
| Westmere      | 1        | 1.11%   |
| Steamroller   | 1        | 1.11%   |
| Goldmont plus | 1        | 1.11%   |
| Excavator     | 1        | 1.11%   |
| Broadwell     | 1        | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 36       | 39.13%  |
| Intel  | 34       | 36.96%  |
| AMD    | 22       | 23.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 6.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.26%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.17%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 2.17%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 2.17%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.17%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.17%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 2.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.17%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.09%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 1.09%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.09%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.09%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.09%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1.09%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.09%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.09%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.09%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 1.09%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 1.09%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.09%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.09%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.09%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.09%   |
| Nvidia G84GL [Quadro FX 570]                                                | 1        | 1.09%   |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1        | 1.09%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 1.09%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.09%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 36       | 40%     |
| 1 x Intel   | 30       | 33.33%  |
| 1 x AMD     | 20       | 22.22%  |
| 2 x Intel   | 2        | 2.22%   |
| Intel + AMD | 2        | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 58       | 64.44%  |
| Proprietary | 28       | 31.11%  |
| Unknown     | 4        | 4.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 53.33%  |
| 1.01-2.0   | 12       | 13.33%  |
| 3.01-4.0   | 8        | 8.89%   |
| 0.51-1.0   | 7        | 7.78%   |
| 5.01-6.0   | 6        | 6.67%   |
| 0.01-0.5   | 5        | 5.56%   |
| 7.01-8.0   | 3        | 3.33%   |
| 8.01-16.0  | 1        | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 8        | 14.81%  |
| Acer                 | 7        | 12.96%  |
| Samsung Electronics  | 6        | 11.11%  |
| Dell                 | 6        | 11.11%  |
| Hewlett-Packard      | 5        | 9.26%   |
| Philips              | 3        | 5.56%   |
| MSI                  | 3        | 5.56%   |
| BenQ                 | 2        | 3.7%    |
| AOC                  | 2        | 3.7%    |
| Vizio                | 1        | 1.85%   |
| ViewSonic            | 1        | 1.85%   |
| Toshiba              | 1        | 1.85%   |
| NEC Computers        | 1        | 1.85%   |
| LG Electronics       | 1        | 1.85%   |
| Lenovo Group Limited | 1        | 1.85%   |
| Insignia             | 1        | 1.85%   |
| Iiyama               | 1        | 1.85%   |
| Idek Iiyama          | 1        | 1.85%   |
| CHD                  | 1        | 1.85%   |
| ASUSTek Computer     | 1        | 1.85%   |
| Unknown              | 1        | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2        | 3.57%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch           | 2        | 3.57%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2        | 3.57%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1        | 1.79%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch            | 1        | 1.79%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 1.79%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1        | 1.79%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1        | 1.79%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1        | 1.79%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1        | 1.79%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1        | 1.79%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch     | 1        | 1.79%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1        | 1.79%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1        | 1.79%   |
| Philips LCD Monitor PHL0868 1680x1050 470x290mm 21.7-inch             | 1        | 1.79%   |
| Philips LCD Monitor PHL 243V7 3840x1080                               | 1        | 1.79%   |
| NEC Computers LCD175VXM+ NEC66C0 1280x1024 340x270mm 17.1-inch        | 1        | 1.79%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1        | 1.79%   |
| LG Electronics LCD Monitor E2441 3840x1080                            | 1        | 1.79%   |
| Lenovo Group Limited LCD Monitor C24-25 1920x1080                     | 1        | 1.79%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1        | 1.79%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 1.79%   |
| Idek Iiyama LCD Monitor PL3270Q 2560x1440                             | 1        | 1.79%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 1.79%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x290mm 23.1-inch          | 1        | 1.79%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1        | 1.79%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 1        | 1.79%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch             | 1        | 1.79%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                   | 1        | 1.79%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1        | 1.79%   |
| Goldstar LG HDR WFHD GSM5BA0 2560x1080 800x340mm 34.2-inch            | 1        | 1.79%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1        | 1.79%   |
| Goldstar E2240 GSM57A4 1920x1080 480x270mm 21.7-inch                  | 1        | 1.79%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1        | 1.79%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1        | 1.79%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1        | 1.79%   |
| Dell LCD Monitor LNK0001 1920x1080 300x230mm 14.9-inch                | 1        | 1.79%   |
| Dell LCD Monitor E2014H                                               | 1        | 1.79%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1        | 1.79%   |
| Dell E2216HV DELF06F 1920x1080 480x270mm 21.7-inch                    | 1        | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 60.38%  |
| 2560x1440 (QHD)    | 5        | 9.43%   |
| 2560x1080          | 3        | 5.66%   |
| 1680x1050 (WSXGA+) | 3        | 5.66%   |
| 3440x1440          | 2        | 3.77%   |
| 1280x1024 (SXGA)   | 2        | 3.77%   |
| 3840x1080          | 1        | 1.89%   |
| 3520x1080          | 1        | 1.89%   |
| 1600x900 (HD+)     | 1        | 1.89%   |
| 1440x900 (WXGA+)   | 1        | 1.89%   |
| 1366x768 (WXGA)    | 1        | 1.89%   |
| Unknown            | 1        | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 16.67%  |
| 21      | 8        | 14.81%  |
| 31      | 6        | 11.11%  |
| 24      | 6        | 11.11%  |
| 23      | 6        | 11.11%  |
| 27      | 5        | 9.26%   |
| 34      | 4        | 7.41%   |
| 19      | 3        | 5.56%   |
| 50      | 1        | 1.85%   |
| 41      | 1        | 1.85%   |
| 33      | 1        | 1.85%   |
| 22      | 1        | 1.85%   |
| 18      | 1        | 1.85%   |
| 17      | 1        | 1.85%   |
| 14      | 1        | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 31.48%  |
| 401-500     | 12       | 22.22%  |
| Unknown     | 9        | 16.67%  |
| 601-700     | 6        | 11.11%  |
| 701-800     | 5        | 9.26%   |
| 351-400     | 1        | 1.85%   |
| 301-350     | 1        | 1.85%   |
| 201-300     | 1        | 1.85%   |
| 1001-1500   | 1        | 1.85%   |
| 901-1000    | 1        | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 63.46%  |
| Unknown | 7        | 13.46%  |
| 21/9    | 5        | 9.62%   |
| 16/10   | 4        | 7.69%   |
| 5/4     | 2        | 3.85%   |
| 4/3     | 1        | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 35.19%  |
| 351-500        | 11       | 20.37%  |
| Unknown        | 9        | 16.67%  |
| 301-350        | 5        | 9.26%   |
| 151-200        | 3        | 5.56%   |
| 251-300        | 2        | 3.7%    |
| 141-150        | 2        | 3.7%    |
| More than 1000 | 1        | 1.85%   |
| 101-110        | 1        | 1.85%   |
| 501-1000       | 1        | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 58.49%  |
| 101-120 | 11       | 20.75%  |
| Unknown | 9        | 16.98%  |
| 1-50    | 1        | 1.89%   |
| 121-160 | 1        | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 76.67%  |
| 0     | 16       | 17.78%  |
| 2     | 5        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 54       | 48.65%  |
| Intel                 | 36       | 32.43%  |
| Qualcomm Atheros      | 11       | 9.91%   |
| TP-Link               | 2        | 1.8%    |
| Ralink Technology     | 2        | 1.8%    |
| Edimax Technology     | 2        | 1.8%    |
| OPPO Electronics      | 1        | 0.9%    |
| IMC Networks          | 1        | 0.9%    |
| Broadcom              | 1        | 0.9%    |
| ASUSTek Computer      | 1        | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 39.52%  |
| Intel Ethernet Connection I217-LM                                 | 6        | 4.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.84%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 3.23%   |
| Intel I211 Gigabit Network Connection                             | 3        | 2.42%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 1.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.61%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.61%   |
| Intel Wireless 8265 / 8275                                        | 2        | 1.61%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.81%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.81%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.81%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 0.81%   |
| Intel Wireless 7260                                               | 1        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.81%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.81%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 30%     |
| Intel                 | 7        | 23.33%  |
| Qualcomm Atheros      | 5        | 16.67%  |
| TP-Link               | 2        | 6.67%   |
| Ralink Technology     | 2        | 6.67%   |
| Edimax Technology     | 2        | 6.67%   |
| IMC Networks          | 1        | 3.33%   |
| Broadcom              | 1        | 3.33%   |
| ASUSTek Computer      | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 6.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2        | 6.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2        | 6.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2        | 6.67%   |
| Ralink RT5370 Wireless Adapter                                              | 2        | 6.67%   |
| Intel Wireless 8265 / 8275                                                  | 2        | 6.67%   |
| Intel Wi-Fi 6 AX200                                                         | 2        | 6.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1        | 3.33%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 3.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 1        | 3.33%   |
| Intel Wireless 7260                                                         | 1        | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1        | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1        | 3.33%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 3.33%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 1        | 3.33%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 3.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 3.33%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 51       | 56.04%  |
| Intel                 | 32       | 35.16%  |
| Qualcomm Atheros      | 7        | 7.69%   |
| OPPO Electronics      | 1        | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 52.13%  |
| Intel Ethernet Connection I217-LM                                 | 6        | 6.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 6.38%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 4.26%   |
| Intel I211 Gigabit Network Connection                             | 3        | 3.19%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.06%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 1.06%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.06%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.06%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 1        | 1.06%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 76.27%  |
| WiFi     | 28       | 23.73%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 81       | 94.19%  |
| WiFi     | 5        | 5.81%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 76.67%  |
| 2     | 21       | 23.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 89       | 98.89%  |
| Yes  | 1        | 1.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 8        | 33.33%  |
| Intel                      | 7        | 29.17%  |
| Realtek Semiconductor      | 4        | 16.67%  |
| Integrated System Solution | 1        | 4.17%   |
| IMC Networks               | 1        | 4.17%   |
| Bluetooth Device           | 1        | 4.17%   |
| ASUSTek Computer           | 1        | 4.17%   |
| Apple                      | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 8        | 33.33%  |
| Intel Bluetooth wireless interface                       | 3        | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 8.33%   |
| Intel AX200 Bluetooth                                    | 2        | 8.33%   |
| Realtek  Bluetooth Adapter                               | 1        | 4.17%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 4.17%   |
| Intel AX210 Bluetooth                                    | 1        | 4.17%   |
| Integrated System Solution Bluetooth Device              | 1        | 4.17%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS  | 1        | 4.17%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 4.17%   |
| Apple Bluetooth Host Controller                          | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 56       | 40.29%  |
| AMD                    | 33       | 23.74%  |
| Nvidia                 | 32       | 23.02%  |
| C-Media Electronics    | 6        | 4.32%   |
| Logitech               | 2        | 1.44%   |
| Google                 | 2        | 1.44%   |
| Yamaha                 | 1        | 0.72%   |
| VIA Technologies       | 1        | 0.72%   |
| Texas Instruments      | 1        | 0.72%   |
| RME                    | 1        | 0.72%   |
| Razer USA              | 1        | 0.72%   |
| Generalplus Technology | 1        | 0.72%   |
| Creative Technology    | 1        | 0.72%   |
| ASUSTek Computer       | 1        | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 10       | 6.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 8        | 4.91%   |
| Intel Cannon Lake PCH cAVS                                                  | 8        | 4.91%   |
| AMD Family 17h/19h HD Audio Controller                                      | 8        | 4.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 7        | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 7        | 4.29%   |
| Nvidia TU116 High Definition Audio Controller                               | 6        | 3.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 6        | 3.68%   |
| AMD Starship/Matisse HD Audio Controller                                    | 5        | 3.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 5        | 3.07%   |
| Intel 200 Series PCH HD Audio                                               | 4        | 2.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 2.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 4        | 2.45%   |
| Nvidia High Definition Audio Controller                                     | 3        | 1.84%   |
| Nvidia GM206 High Definition Audio Controller                               | 3        | 1.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 3        | 1.84%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 3        | 1.84%   |
| AMD FCH Azalia Controller                                                   | 3        | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 2        | 1.23%   |
| Nvidia GP108 High Definition Audio Controller                               | 2        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                             | 2        | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 2        | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                          | 2        | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                               | 2        | 1.23%   |
| Logitech HD Webcam C510                                                     | 2        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller  | 2        | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 2        | 1.23%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 1.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 2        | 1.23%   |
| Google Pixel earbuds                                                        | 2        | 1.23%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 2        | 1.23%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 2        | 1.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2        | 1.23%   |
| Unknown                                                                     | 2        | 1.23%   |
| Yamaha Steinberg UR22mkII                                                   | 1        | 0.61%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.61%   |
| Texas Instruments PCM2900C Audio CODEC                                      | 1        | 0.61%   |
| RME Babyface Pro (Class Compliant Mode)                                     | 1        | 0.61%   |
| Razer USA Nari Ultimate                                                     | 1        | 0.61%   |
| Nvidia TU102 High Definition Audio Controller                               | 1        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 24       | 20.17%  |
| Unknown             | 17       | 14.29%  |
| Samsung Electronics | 13       | 10.92%  |
| SK hynix            | 12       | 10.08%  |
| Crucial             | 10       | 8.4%    |
| Micron Technology   | 9        | 7.56%   |
| Unknown             | 7        | 5.88%   |
| Ramaxel Technology  | 4        | 3.36%   |
| Patriot             | 4        | 3.36%   |
| Transcend           | 3        | 2.52%   |
| G.Skill             | 3        | 2.52%   |
| Corsair             | 3        | 2.52%   |
| Team                | 2        | 1.68%   |
| GOODRAM             | 2        | 1.68%   |
| PNY                 | 1        | 0.84%   |
| Nanya Technology    | 1        | 0.84%   |
| GLOWAY              | 1        | 0.84%   |
| GeIL                | 1        | 0.84%   |
| Elpida              | 1        | 0.84%   |
| A-DATA Technology   | 1        | 0.84%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown                                               | 7        | 5.34%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 4        | 3.05%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 3        | 2.29%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 2        | 1.53%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 2        | 1.53%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s     | 2        | 1.53%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s  | 2        | 1.53%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s     | 2        | 1.53%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s  | 2        | 1.53%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s  | 2        | 1.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2                      | 1        | 0.76%   |
| Unknown RAM Module 1GB DIMM DDR2 400MT/s              | 1        | 0.76%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s  | 1        | 0.76%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s     | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s   | 1        | 0.76%   |
| Team RAM Elite-13 4GB DIMM DDR3 667MT/s               | 1        | 0.76%   |
| Team RAM Elite-1 2GB DIMM DDR3 667MT/s                | 1        | 0.76%   |
| SK hynix RAM Module 8GB DIMM DDR4 2667MT/s            | 1        | 0.76%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s          | 1        | 0.76%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s            | 1        | 0.76%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s            | 1        | 0.76%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.76%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1067MT/s  | 1        | 0.76%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 0.76%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 0.76%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s  | 1        | 0.76%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB RIMM DDR4 2133MT/s | 1        | 0.76%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s           | 1        | 0.76%   |
| Samsung RAM Module 8GB DIMM DDR3 1333MT/s             | 1        | 0.76%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 0.76%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s             | 1        | 0.76%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s             | 1        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 38       | 42.22%  |
| DDR3    | 37       | 41.11%  |
| DDR2    | 8        | 8.89%   |
| Unknown | 4        | 4.44%   |
| SDRAM   | 3        | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 82       | 91.11%  |
| SODIMM | 7        | 7.78%   |
| RIMM   | 1        | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 37       | 33.64%  |
| 4096  | 35       | 31.82%  |
| 2048  | 23       | 20.91%  |
| 16384 | 11       | 10%     |
| 1024  | 3        | 2.73%   |
| 32768 | 1        | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 18       | 18.95%  |
| 1600    | 15       | 15.79%  |
| 3200    | 10       | 10.53%  |
| 2667    | 8        | 8.42%   |
| 2400    | 8        | 8.42%   |
| 2133    | 7        | 7.37%   |
| 800     | 7        | 7.37%   |
| 2666    | 6        | 6.32%   |
| Unknown | 4        | 4.21%   |
| 2933    | 2        | 2.11%   |
| 1866    | 2        | 2.11%   |
| 1066    | 2        | 2.11%   |
| 667     | 2        | 2.11%   |
| 3000    | 1        | 1.05%   |
| 1867    | 1        | 1.05%   |
| 1067    | 1        | 1.05%   |
| 400     | 1        | 1.05%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 2        | 33.33%  |
| Z-Star Microelectronics | 1        | 16.67%  |
| Microdia                | 1        | 16.67%  |
| Genesys Logic           | 1        | 16.67%  |
| Arkmicro Technologies   | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Logitech HD Pro Webcam C920      | 2        | 33.33%  |
| Z-Star Venus USB2.0 Camera       | 1        | 16.67%  |
| Microdia Camera                  | 1        | 16.67%  |
| Genesys Logic Digital Microscope | 1        | 16.67%  |
| Arkmicro Webcam Carrefour        | 1        | 16.67%  |

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
| 1     | 42       | 46.67%  |
| 0     | 36       | 40%     |
| 2     | 11       | 12.22%  |
| 3     | 1        | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 46       | 73.02%  |
| Net/wireless             | 9        | 14.29%  |
| Sound                    | 3        | 4.76%   |
| Bluetooth                | 3        | 4.76%   |
| Storage/raid             | 1        | 1.59%   |
| Card reader              | 1        | 1.59%   |

