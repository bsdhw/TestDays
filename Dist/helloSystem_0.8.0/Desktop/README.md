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

Total: 105

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [d05a143723](https://bsd-hardware.info/?probe=d05a143723) | Mar 08, 2023 |
| Gigabyte  | X570 UD                     | [13e4d3ce10](https://bsd-hardware.info/?probe=13e4d3ce10) | Mar 05, 2023 |
| ASUSTek   | PRIME A320M-E               | [ca70bceb83](https://bsd-hardware.info/?probe=ca70bceb83) | Mar 05, 2023 |
| ASUSTek   | P7H55                       | [3c78171104](https://bsd-hardware.info/?probe=3c78171104) | Mar 04, 2023 |
| ASUSTek   | P7H55                       | [5ce8dbf5f3](https://bsd-hardware.info/?probe=5ce8dbf5f3) | Mar 04, 2023 |
| Gigabyte  | GA-78LMT-S2P                | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
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
| amd64 | 94       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 93       | 98.94%  |
| KDE5         | 1        | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 94       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 94       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 37       | 38.54%  |
| en    | 27       | 28.13%  |
| fr    | 10       | 10.42%  |
| ru    | 6        | 6.25%   |
| es    | 4        | 4.17%   |
| pt    | 3        | 3.13%   |
| en_GB | 2        | 2.08%   |
| zh_TW | 1        | 1.04%   |
| pl    | 1        | 1.04%   |
| nl    | 1        | 1.04%   |
| it    | 1        | 1.04%   |
| es_ES | 1        | 1.04%   |
| de_DE | 1        | 1.04%   |
| de    | 1        | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 93       | 98.94%  |
| BIOS | 1        | 1.06%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 66       | 69.47%  |
| Zfs    | 29       | 30.53%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 93       | 98.94%  |
| MBR  | 1        | 1.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 23       | 24.47%  |
| Gigabyte Technology | 18       | 19.15%  |
| Dell                | 12       | 12.77%  |
| Hewlett-Packard     | 9        | 9.57%   |
| ASRock              | 8        | 8.51%   |
| MSI                 | 6        | 6.38%   |
| Lenovo              | 6        | 6.38%   |
| Biostar             | 3        | 3.19%   |
| Pegatron            | 2        | 2.13%   |
| Intel               | 2        | 2.13%   |
| MACHINIST           | 1        | 1.06%   |
| Google              | 1        | 1.06%   |
| Fujitsu             | 1        | 1.06%   |
| AOpen               | 1        | 1.06%   |
| AMD                 | 1        | 1.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 3.19%   |
| MSI MS-7C37                         | 2        | 2.13%   |
| MSI MS-7A38                         | 2        | 2.13%   |
| Pegatron IPPPV-D3G                  | 1        | 1.06%   |
| Pegatron IPM41-D3                   | 1        | 1.06%   |
| MSI MS-7B89                         | 1        | 1.06%   |
| MSI MS-7918                         | 1        | 1.06%   |
| MACHINIST X99-k9 V2.0               | 1        | 1.06%   |
| Lenovo ThinkCentre M93p 10AB004DUS  | 1        | 1.06%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK  | 1        | 1.06%   |
| Lenovo ThinkCentre M910s 10MK0039US | 1        | 1.06%   |
| Lenovo ThinkCentre M83 10AHA0X9LS   | 1        | 1.06%   |
| Lenovo ThinkCentre M82 2929AZ6      | 1        | 1.06%   |
| Lenovo ThinkCentre M700 10GS        | 1        | 1.06%   |
| Intel MAHOBAY                       | 1        | 1.06%   |
| Intel DN2800MT AAG23738-600         | 1        | 1.06%   |
| HP Z240 SFF Workstation             | 1        | 1.06%   |
| HP Slim Desktop S01-aF1xxx          | 1        | 1.06%   |
| HP ProDesk 600 G4 SFF               | 1        | 1.06%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.06%   |
| HP EliteDesk 800 G1 SFF             | 1        | 1.06%   |
| HP EliteDesk 700 G1 SFF             | 1        | 1.06%   |
| HP Desktop Pro A G3                 | 1        | 1.06%   |
| HP Compaq 8200 Elite USDT PC        | 1        | 1.06%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 1.06%   |
| Google Panther                      | 1        | 1.06%   |
| Gigabyte X570 UD                    | 1        | 1.06%   |
| Gigabyte X570 AORUS PRO             | 1        | 1.06%   |
| Gigabyte X399 AORUS Gaming 7        | 1        | 1.06%   |
| Gigabyte P61-USB3-B3                | 1        | 1.06%   |
| Gigabyte H81M-H                     | 1        | 1.06%   |
| Gigabyte H61M-S2PV                  | 1        | 1.06%   |
| Gigabyte H61M-S1                    | 1        | 1.06%   |
| Gigabyte H510M S2H V2               | 1        | 1.06%   |
| Gigabyte H270M-DS3H                 | 1        | 1.06%   |
| Gigabyte GA-MA770T-UD3              | 1        | 1.06%   |
| Gigabyte GA-990X-Gaming SLI-CF      | 1        | 1.06%   |
| Gigabyte G1.Sniper A88X-CF          | 1        | 1.06%   |
| Gigabyte F2A88XM-D3H                | 1        | 1.06%   |
| Gigabyte B450M AORUS ELITE          | 1        | 1.06%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 7        | 7.45%   |
| Lenovo ThinkCentre      | 6        | 6.38%   |
| ASUS PRIME              | 5        | 5.32%   |
| ASUS All                | 3        | 3.19%   |
| MSI MS-7C37             | 2        | 2.13%   |
| MSI MS-7A38             | 2        | 2.13%   |
| HP EliteDesk            | 2        | 2.13%   |
| HP Compaq               | 2        | 2.13%   |
| Gigabyte X570           | 2        | 2.13%   |
| Dell Precision          | 2        | 2.13%   |
| Dell Inspiron           | 2        | 2.13%   |
| ASUS ROG                | 2        | 2.13%   |
| ASUS P8Z68-V            | 2        | 2.13%   |
| Pegatron IPPPV-D3G      | 1        | 1.06%   |
| Pegatron IPM41-D3       | 1        | 1.06%   |
| MSI MS-7B89             | 1        | 1.06%   |
| MSI MS-7918             | 1        | 1.06%   |
| MACHINIST X99-k9        | 1        | 1.06%   |
| Intel MAHOBAY           | 1        | 1.06%   |
| Intel DN2800MT          | 1        | 1.06%   |
| HP Z240                 | 1        | 1.06%   |
| HP Slim                 | 1        | 1.06%   |
| HP ProDesk              | 1        | 1.06%   |
| HP Pavilion             | 1        | 1.06%   |
| HP Desktop              | 1        | 1.06%   |
| Google Panther          | 1        | 1.06%   |
| Gigabyte X399           | 1        | 1.06%   |
| Gigabyte P61-USB3-B3    | 1        | 1.06%   |
| Gigabyte H81M-H         | 1        | 1.06%   |
| Gigabyte H61M-S2PV      | 1        | 1.06%   |
| Gigabyte H61M-S1        | 1        | 1.06%   |
| Gigabyte H510M          | 1        | 1.06%   |
| Gigabyte H270M-DS3H     | 1        | 1.06%   |
| Gigabyte GA-MA770T-UD3  | 1        | 1.06%   |
| Gigabyte GA-990X-Gaming | 1        | 1.06%   |
| Gigabyte G1.Sniper      | 1        | 1.06%   |
| Gigabyte F2A88XM-D3H    | 1        | 1.06%   |
| Gigabyte B450M          | 1        | 1.06%   |
| Gigabyte B360M-D2V      | 1        | 1.06%   |
| Gigabyte A520M          | 1        | 1.06%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 12       | 12.77%  |
| 2018 | 11       | 11.7%   |
| 2013 | 8        | 8.51%   |
| 2012 | 8        | 8.51%   |
| 2021 | 7        | 7.45%   |
| 2020 | 7        | 7.45%   |
| 2015 | 7        | 7.45%   |
| 2014 | 7        | 7.45%   |
| 2011 | 7        | 7.45%   |
| 2010 | 7        | 7.45%   |
| 2022 | 5        | 5.32%   |
| 2017 | 2        | 2.13%   |
| 2016 | 2        | 2.13%   |
| 2009 | 2        | 2.13%   |
| 2008 | 2        | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 94       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 98.94%  |
| Yes  | 1        | 1.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 30       | 31.91%  |
| 16.01-24.0  | 27       | 28.72%  |
| 4.01-8.0    | 19       | 20.21%  |
| 32.01-64.0  | 6        | 6.38%   |
| 2.01-3.0    | 5        | 5.32%   |
| 64.01-256.0 | 5        | 5.32%   |
| 24.01-32.0  | 1        | 1.06%   |
| 0.51-1.0    | 1        | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 43       | 45.74%  |
| 0.51-1.0  | 27       | 28.72%  |
| 1.01-2.0  | 17       | 18.09%  |
| 2.01-3.0  | 5        | 5.32%   |
| 4.01-8.0  | 1        | 1.06%   |
| 8.01-16.0 | 1        | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 50%     |
| 2      | 22       | 22.92%  |
| 3      | 12       | 12.5%   |
| 5      | 5        | 5.21%   |
| 4      | 5        | 5.21%   |
| 6      | 2        | 2.08%   |
| 0      | 2        | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 61.7%   |
| Yes       | 36       | 38.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 67.37%  |
| Yes       | 31       | 32.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 74.47%  |
| Yes       | 24       | 25.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 18       | 19.15%  |
| Russia       | 14       | 14.89%  |
| Brazil       | 7        | 7.45%   |
| Spain        | 6        | 6.38%   |
| Germany      | 6        | 6.38%   |
| Taiwan       | 5        | 5.32%   |
| UK           | 4        | 4.26%   |
| Poland       | 3        | 3.19%   |
| Italy        | 3        | 3.19%   |
| Canada       | 3        | 3.19%   |
| Portugal     | 2        | 2.13%   |
| Mexico       | 2        | 2.13%   |
| Indonesia    | 2        | 2.13%   |
| India        | 2        | 2.13%   |
| France       | 2        | 2.13%   |
| Belgium      | 2        | 2.13%   |
| Australia    | 2        | 2.13%   |
| Thailand     | 1        | 1.06%   |
| South Africa | 1        | 1.06%   |
| Serbia       | 1        | 1.06%   |
| Peru         | 1        | 1.06%   |
| Norway       | 1        | 1.06%   |
| Japan        | 1        | 1.06%   |
| Hungary      | 1        | 1.06%   |
| Colombia     | 1        | 1.06%   |
| China        | 1        | 1.06%   |
| Bulgaria     | 1        | 1.06%   |
| Argentina    | 1        | 1.06%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Moscow                 | 4        | 4.17%   |
| Aquan                  | 4        | 4.17%   |
| Yekaterinburg          | 2        | 2.08%   |
| Voronezh               | 2        | 2.08%   |
| Volgograd              | 2        | 2.08%   |
| Temple                 | 2        | 2.08%   |
| Saratov                | 2        | 2.08%   |
| Gistel                 | 2        | 2.08%   |
| Zhengzhou              | 1        | 1.04%   |
| Yala                   | 1        | 1.04%   |
| Winnipeg               | 1        | 1.04%   |
| Willingboro            | 1        | 1.04%   |
| Veliko Tarnovo         | 1        | 1.04%   |
| Valledupar             | 1        | 1.04%   |
| Valencia               | 1        | 1.04%   |
| Trieste                | 1        | 1.04%   |
| Trebujena              | 1        | 1.04%   |
| Tasikmalaya            | 1        | 1.04%   |
| Tallahassee            | 1        | 1.04%   |
| Szigetszentmiklos      | 1        | 1.04%   |
| Surrey                 | 1        | 1.04%   |
| Sumaré                | 1        | 1.04%   |
| Southminster           | 1        | 1.04%   |
| Seville                | 1        | 1.04%   |
| Sao Domingos das Dores | 1        | 1.04%   |
| Salisbury              | 1        | 1.04%   |
| Salem                  | 1        | 1.04%   |
| Rosignano Marittimo    | 1        | 1.04%   |
| Richardson             | 1        | 1.04%   |
| Rhinelander            | 1        | 1.04%   |
| Remshalden             | 1        | 1.04%   |
| Reinsvoll              | 1        | 1.04%   |
| Recklinghausen         | 1        | 1.04%   |
| Québec                | 1        | 1.04%   |
| Portland               | 1        | 1.04%   |
| Pieve a Nievole        | 1        | 1.04%   |
| Palembang              | 1        | 1.04%   |
| Osasco                 | 1        | 1.04%   |
| Oryol                  | 1        | 1.04%   |
| Oklahoma City          | 1        | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 39     | 18.71%  |
| Seagate             | 27       | 30     | 17.42%  |
| Samsung Electronics | 23       | 31     | 14.84%  |
| Hitachi             | 12       | 15     | 7.74%   |
| Toshiba             | 9        | 10     | 5.81%   |
| Kingston            | 9        | 10     | 5.81%   |
| Crucial             | 7        | 9      | 4.52%   |
| A-DATA Technology   | 6        | 7      | 3.87%   |
| SanDisk             | 5        | 6      | 3.23%   |
| SPCC                | 2        | 2      | 1.29%   |
| PNY                 | 2        | 2      | 1.29%   |
| Patriot             | 2        | 2      | 1.29%   |
| Lexar               | 2        | 3      | 1.29%   |
| Hewlett-Packard     | 2        | 2      | 1.29%   |
| XrayDisk            | 1        | 1      | 0.65%   |
| Transcend           | 1        | 1      | 0.65%   |
| SK hynix            | 1        | 1      | 0.65%   |
| Silicon Motion      | 1        | 1      | 0.65%   |
| Reletech            | 1        | 1      | 0.65%   |
| Plextor             | 1        | 1      | 0.65%   |
| Pioneer             | 1        | 1      | 0.65%   |
| OCZ                 | 1        | 1      | 0.65%   |
| MidasForce          | 1        | 1      | 0.65%   |
| Micron Technology   | 1        | 1      | 0.65%   |
| LDLC                | 1        | 1      | 0.65%   |
| KingSpec            | 1        | 1      | 0.65%   |
| Intenso             | 1        | 1      | 0.65%   |
| Gigabyte Technology | 1        | 1      | 0.65%   |
| Fanxiang            | 1        | 1      | 0.65%   |
| Emtec               | 1        | 1      | 0.65%   |
| Corsair             | 1        | 1      | 0.65%   |
| China               | 1        | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 2.25%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 1.12%   |
| Toshiba MQ01ABD050 500GB        | 2        | 1.12%   |
| Toshiba HDWD110 1TB             | 2        | 1.12%   |
| Seagate ST3500418AS 500GB       | 2        | 1.12%   |
| Seagate ST3250310AS 250GB       | 2        | 1.12%   |
| Seagate ST2000LM007-1R8174 2TB  | 2        | 1.12%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.12%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 1.12%   |
| Samsung SSD 860 PRO 512GB       | 2        | 1.12%   |
| Samsung SSD 860 EVO 500GB       | 2        | 1.12%   |
| Samsung SSD 860 EVO 1TB         | 2        | 1.12%   |
| Samsung HD322HJ 320GB           | 2        | 1.12%   |
| Kingston SA400S37240G 240GB     | 2        | 1.12%   |
| Hitachi HDS721616PLA380 164GB   | 2        | 1.12%   |
| A-DATA SU800 256GB              | 2        | 1.12%   |
| XrayDisk SSD 256GB              | 1        | 0.56%   |
| WDC WDS500G3XHC-00SJG0 500GB    | 1        | 0.56%   |
| WDC WDS500G2X0C-00L350 500GB    | 1        | 0.56%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.56%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 0.56%   |
| WDC WDS120G2G0B-00EPW0 120GB    | 1        | 0.56%   |
| WDC WD80EFAX-68KNBN0 8TB        | 1        | 0.56%   |
| WDC WD50NPZZ-00A9JT0 5TB        | 1        | 0.56%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.56%   |
| WDC WD5000LPCX-60VHAT0 500GB    | 1        | 0.56%   |
| WDC WD5000AZLX-60K2TA1 500GB    | 1        | 0.56%   |
| WDC WD5000AVVS-63H0B1 500GB     | 1        | 0.56%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1        | 0.56%   |
| WDC WD5000AAKS-00YGA0 500GB     | 1        | 0.56%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1        | 0.56%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.56%   |
| WDC WD3200BEVT-00ZCT0 320GB     | 1        | 0.56%   |
| WDC WD3200AAKS-75L9A0 320GB     | 1        | 0.56%   |
| WDC WD3003FZEX-00Z4SA0 3TB      | 1        | 0.56%   |
| WDC WD2500BEVT-75A23T0 250GB    | 1        | 0.56%   |
| WDC WD20EZAZ-22L9GB0 2TB        | 1        | 0.56%   |
| WDC WD20EFRX-68EUZN0 2TB        | 1        | 0.56%   |
| WDC WD20EARS-00MVWB0 2TB        | 1        | 0.56%   |
| WDC WD2003FYYS-02W0B1 2TB       | 1        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 30     | 34.62%  |
| WDC                 | 24       | 30     | 30.77%  |
| Hitachi             | 12       | 15     | 15.38%  |
| Samsung Electronics | 8        | 8      | 10.26%  |
| Toshiba             | 6        | 7      | 7.69%   |
| Hewlett-Packard     | 1        | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 15     | 16.13%  |
| Kingston            | 7        | 8      | 11.29%  |
| Crucial             | 6        | 8      | 9.68%   |
| A-DATA Technology   | 6        | 7      | 9.68%   |
| SanDisk             | 5        | 6      | 8.06%   |
| WDC                 | 4        | 5      | 6.45%   |
| Toshiba             | 3        | 3      | 4.84%   |
| SPCC                | 2        | 2      | 3.23%   |
| PNY                 | 2        | 2      | 3.23%   |
| Patriot             | 2        | 2      | 3.23%   |
| XrayDisk            | 1        | 1      | 1.61%   |
| Transcend           | 1        | 1      | 1.61%   |
| Plextor             | 1        | 1      | 1.61%   |
| Pioneer             | 1        | 1      | 1.61%   |
| OCZ                 | 1        | 1      | 1.61%   |
| MidasForce          | 1        | 1      | 1.61%   |
| Micron Technology   | 1        | 1      | 1.61%   |
| Lexar               | 1        | 1      | 1.61%   |
| KingSpec            | 1        | 1      | 1.61%   |
| Intenso             | 1        | 1      | 1.61%   |
| Hewlett-Packard     | 1        | 1      | 1.61%   |
| Gigabyte Technology | 1        | 1      | 1.61%   |
| Fanxiang            | 1        | 1      | 1.61%   |
| Emtec               | 1        | 1      | 1.61%   |
| China               | 1        | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 61       | 91     | 47.66%  |
| SSD  | 48       | 73     | 37.5%   |
| NVMe | 19       | 22     | 14.84%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 88       | 164    | 82.24%  |
| NVMe | 19       | 22     | 17.76%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 73       | 106    | 61.86%  |
| 0.51-1.0   | 25       | 31     | 21.19%  |
| 1.01-2.0   | 14       | 19     | 11.86%  |
| 3.01-4.0   | 3        | 4      | 2.54%   |
| 4.01-10.0  | 2        | 2      | 1.69%   |
| 2.01-3.0   | 1        | 2      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 61       | 64.21%  |
| 101-250    | 14       | 14.74%  |
| 251-500    | 10       | 10.53%  |
| 501-1000   | 4        | 4.21%   |
| 1001-2000  | 3        | 3.16%   |
| 51-100     | 2        | 2.11%   |
| 21-50      | 1        | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 91       | 95.79%  |
| 101-250  | 3        | 3.16%   |
| 501-1000 | 1        | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3        | 3      | 13.64%  |
| WDC WD5000LPCX-60VHAT0 500GB      | 1        | 1      | 4.55%   |
| WDC WD5000AVVS-63H0B1 500GB       | 1        | 1      | 4.55%   |
| WDC WD10EZRZ-00HTKB0 1TB          | 1        | 1      | 4.55%   |
| WDC WD10EADS-65M2BX 1TB           | 1        | 1      | 4.55%   |
| WDC WD10EACS-00D6B1 1TB           | 1        | 2      | 4.55%   |
| Toshiba MK1255GSX H 120GB         | 1        | 1      | 4.55%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 4.55%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 4.55%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 4.55%   |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 4.55%   |
| Pioneer APS-SL3N-240 240GB        | 1        | 1      | 4.55%   |
| OCZ VERTEX3 240GB                 | 1        | 1      | 4.55%   |
| MidasForce SSD 120GB              | 1        | 1      | 4.55%   |
| Hitachi HTS545050A7E380 500GB     | 1        | 1      | 4.55%   |
| Hitachi HTS541680J9SA00 80GB      | 1        | 1      | 4.55%   |
| Hitachi HDT721010SLA360 1TB       | 1        | 1      | 4.55%   |
| Hitachi HDS721616PLA380 164GB     | 1        | 1      | 4.55%   |
| Crucial CT1050MX300SSD1 1TB       | 1        | 1      | 4.55%   |
| A-DATA Technology SU800 256GB     | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 22.73%  |
| Seagate             | 5        | 5      | 22.73%  |
| Hitachi             | 4        | 4      | 18.18%  |
| Samsung Electronics | 2        | 2      | 9.09%   |
| Toshiba             | 1        | 1      | 4.55%   |
| Pioneer             | 1        | 1      | 4.55%   |
| OCZ                 | 1        | 1      | 4.55%   |
| MidasForce          | 1        | 1      | 4.55%   |
| Crucial             | 1        | 1      | 4.55%   |
| A-DATA Technology   | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 29.41%  |
| Seagate             | 5        | 5      | 29.41%  |
| Hitachi             | 4        | 4      | 23.53%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| Toshiba             | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 18     | 77.27%  |
| SSD  | 5        | 5      | 22.73%  |

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
| Works    | 75       | 148    | 72.12%  |
| Malfunc  | 20       | 23     | 19.23%  |
| Detected | 7        | 13     | 6.73%   |
| Failed   | 2        | 2      | 1.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 63       | 49.61%  |
| AMD                          | 31       | 24.41%  |
| Samsung Electronics          | 7        | 5.51%   |
| SanDisk                      | 5        | 3.94%   |
| JMicron Technology           | 4        | 3.15%   |
| ASMedia Technology           | 3        | 2.36%   |
| Silicon Motion               | 2        | 1.57%   |
| Shenzhen Longsys Electronics | 2        | 1.57%   |
| Phison Electronics           | 2        | 1.57%   |
| Kingston Technology Company  | 2        | 1.57%   |
| VIA Technologies             | 1        | 0.79%   |
| SK hynix                     | 1        | 0.79%   |
| Realtek Semiconductor        | 1        | 0.79%   |
| Micron/Crucial Technology    | 1        | 0.79%   |
| Marvell Technology Group     | 1        | 0.79%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 10.56%  |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 4.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 4.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 3.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 3.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 3.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 3.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 3.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 3.11%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 3.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 2.48%   |
| AMD FCH SATA Controller D                                                               | 4        | 2.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 1.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.24%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2        | 1.24%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 1.24%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.24%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.24%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.24%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.24%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.24%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.24%   |
| Unknown                                                                                 | 2        | 1.24%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.62%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1        | 0.62%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1        | 0.62%   |
| Sandisk NVMe Controller                                                                 | 1        | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.62%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.62%   |
| Realtek NVMe Controller                                                                 | 1        | 0.62%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.62%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 72       | 58.54%  |
| IDE  | 27       | 21.95%  |
| NVMe | 21       | 17.07%  |
| RAID | 3        | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 63       | 67.02%  |
| AMD    | 31       | 32.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 3.19%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 3.19%   |
| Intel Core 2 Duo                            | 3        | 3.19%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 2.13%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 2.13%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 2.13%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.13%   |
| AMD Phenom II X4 945 Processor              | 2        | 2.13%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 1.06%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1        | 1.06%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 1.06%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.06%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 1.06%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.06%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.06%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.06%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.06%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.06%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.06%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.06%   |
| Intel Core i9-9900KS CPU @ 4.00GHz          | 1        | 1.06%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.06%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.06%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 1.06%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.06%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.06%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.06%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.06%   |
| Intel Core i5-8500T CPU @ 2.10GHz           | 1        | 1.06%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.06%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.06%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 1.06%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.06%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.06%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.06%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.06%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.06%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.06%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 21.28%  |
| Intel Core i3           | 10       | 10.64%  |
| Intel Core i7           | 7        | 7.45%   |
| AMD Ryzen 5             | 7        | 7.45%   |
| AMD Phenom II X4        | 5        | 5.32%   |
| Intel Xeon              | 4        | 4.26%   |
| Intel Pentium Dual-Core | 4        | 4.26%   |
| Intel Core 2 Duo        | 4        | 4.26%   |
| Intel Celeron           | 4        | 4.26%   |
| Intel Pentium           | 3        | 3.19%   |
| AMD Ryzen 7             | 3        | 3.19%   |
| AMD Ryzen 3             | 3        | 3.19%   |
| AMD FX                  | 3        | 3.19%   |
| Other                   | 2        | 2.13%   |
| Intel Atom              | 2        | 2.13%   |
| AMD Ryzen 9             | 2        | 2.13%   |
| Intel Pentium Silver    | 1        | 1.06%   |
| Intel Core i9           | 1        | 1.06%   |
| Intel Core 2 Quad       | 1        | 1.06%   |
| Intel Core 2            | 1        | 1.06%   |
| AMD Ryzen Threadripper  | 1        | 1.06%   |
| AMD Ryzen 5 PRO         | 1        | 1.06%   |
| AMD Ryzen 3 PRO         | 1        | 1.06%   |
| AMD Athlon II X4        | 1        | 1.06%   |
| AMD Athlon              | 1        | 1.06%   |
| AMD A8                  | 1        | 1.06%   |
| AMD A10                 | 1        | 1.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 39       | 41.49%  |
| 2       | 22       | 23.4%   |
| 6       | 10       | 10.64%  |
| 8       | 7        | 7.45%   |
| 12      | 5        | 5.32%   |
| 16      | 4        | 4.26%   |
| Unknown | 3        | 3.19%   |
| 24      | 2        | 2.13%   |
| 10      | 1        | 1.06%   |
| 1       | 1        | 1.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 71       | 75.53%  |
| 2       | 20       | 21.28%  |
| Unknown | 3        | 3.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 12       | 12.77%  |
| KabyLake      | 11       | 11.7%   |
| SandyBridge   | 9        | 9.57%   |
| Penryn        | 7        | 7.45%   |
| Zen+          | 6        | 6.38%   |
| K10           | 6        | 6.38%   |
| IvyBridge     | 6        | 6.38%   |
| Zen           | 5        | 5.32%   |
| Zen 3         | 4        | 4.26%   |
| Zen 2         | 4        | 4.26%   |
| Core          | 4        | 4.26%   |
| Skylake       | 3        | 3.19%   |
| Piledriver    | 3        | 3.19%   |
| Westmere      | 2        | 2.13%   |
| Silvermont    | 2        | 2.13%   |
| CometLake     | 2        | 2.13%   |
| Bonnell       | 2        | 2.13%   |
| Unknown       | 2        | 2.13%   |
| Steamroller   | 1        | 1.06%   |
| Goldmont plus | 1        | 1.06%   |
| Excavator     | 1        | 1.06%   |
| Broadwell     | 1        | 1.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 37       | 38.54%  |
| Intel  | 35       | 36.46%  |
| AMD    | 24       | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 7.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.13%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.08%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 2.08%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 2.08%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2.08%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.08%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 2.08%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.08%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.04%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.04%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.04%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.04%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1.04%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.04%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.04%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.04%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 1.04%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 1.04%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.04%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.04%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.04%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.04%   |
| Nvidia G84GL [Quadro FX 570]                                                | 1        | 1.04%   |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1        | 1.04%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 1.04%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 37       | 39.36%  |
| 1 x Intel   | 31       | 32.98%  |
| 1 x AMD     | 22       | 23.4%   |
| 2 x Intel   | 2        | 2.13%   |
| Intel + AMD | 2        | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 64.89%  |
| Proprietary | 29       | 30.85%  |
| Unknown     | 4        | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 53.19%  |
| 1.01-2.0   | 12       | 12.77%  |
| 3.01-4.0   | 9        | 9.57%   |
| 0.51-1.0   | 8        | 8.51%   |
| 5.01-6.0   | 6        | 6.38%   |
| 0.01-0.5   | 5        | 5.32%   |
| 7.01-8.0   | 3        | 3.19%   |
| 8.01-16.0  | 1        | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 8        | 14.55%  |
| Acer                 | 7        | 12.73%  |
| Samsung Electronics  | 6        | 10.91%  |
| Dell                 | 6        | 10.91%  |
| Hewlett-Packard      | 5        | 9.09%   |
| Philips              | 3        | 5.45%   |
| MSI                  | 3        | 5.45%   |
| LG Electronics       | 2        | 3.64%   |
| BenQ                 | 2        | 3.64%   |
| AOC                  | 2        | 3.64%   |
| Vizio                | 1        | 1.82%   |
| ViewSonic            | 1        | 1.82%   |
| Toshiba              | 1        | 1.82%   |
| NEC Computers        | 1        | 1.82%   |
| Lenovo Group Limited | 1        | 1.82%   |
| Insignia             | 1        | 1.82%   |
| Iiyama               | 1        | 1.82%   |
| Idek Iiyama          | 1        | 1.82%   |
| CHD                  | 1        | 1.82%   |
| ASUSTek Computer     | 1        | 1.82%   |
| Unknown              | 1        | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2        | 3.51%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch           | 2        | 3.51%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2        | 3.51%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1        | 1.75%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch            | 1        | 1.75%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1        | 1.75%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1        | 1.75%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1        | 1.75%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch     | 1        | 1.75%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1        | 1.75%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1        | 1.75%   |
| Philips LCD Monitor PHL0868 1680x1050 470x290mm 21.7-inch             | 1        | 1.75%   |
| Philips LCD Monitor PHL 243V7 3840x1080                               | 1        | 1.75%   |
| NEC Computers LCD175VXM+ NEC66C0 1280x1024 340x270mm 17.1-inch        | 1        | 1.75%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1        | 1.75%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 1        | 1.75%   |
| LG Electronics LCD Monitor E2441 3840x1080                            | 1        | 1.75%   |
| Lenovo Group Limited LCD Monitor C24-25 1920x1080                     | 1        | 1.75%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1        | 1.75%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 1.75%   |
| Idek Iiyama LCD Monitor PL3270Q 2560x1440                             | 1        | 1.75%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 1.75%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x290mm 23.1-inch          | 1        | 1.75%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1        | 1.75%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 1        | 1.75%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch             | 1        | 1.75%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                   | 1        | 1.75%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1        | 1.75%   |
| Goldstar LG HDR WFHD GSM5BA0 2560x1080 800x340mm 34.2-inch            | 1        | 1.75%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1        | 1.75%   |
| Goldstar E2240 GSM57A4 1920x1080 480x270mm 21.7-inch                  | 1        | 1.75%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1        | 1.75%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1        | 1.75%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1        | 1.75%   |
| Dell LCD Monitor LNK0001 1920x1080 300x230mm 14.9-inch                | 1        | 1.75%   |
| Dell LCD Monitor E2014H                                               | 1        | 1.75%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1        | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 33       | 61.11%  |
| 2560x1440 (QHD)    | 5        | 9.26%   |
| 2560x1080          | 3        | 5.56%   |
| 1680x1050 (WSXGA+) | 3        | 5.56%   |
| 3440x1440          | 2        | 3.7%    |
| 1280x1024 (SXGA)   | 2        | 3.7%    |
| 3840x1080          | 1        | 1.85%   |
| 3520x1080          | 1        | 1.85%   |
| 1600x900 (HD+)     | 1        | 1.85%   |
| 1440x900 (WXGA+)   | 1        | 1.85%   |
| 1366x768 (WXGA)    | 1        | 1.85%   |
| Unknown            | 1        | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 18.18%  |
| 21      | 8        | 14.55%  |
| 31      | 6        | 10.91%  |
| 24      | 6        | 10.91%  |
| 23      | 6        | 10.91%  |
| 27      | 5        | 9.09%   |
| 34      | 4        | 7.27%   |
| 19      | 3        | 5.45%   |
| 50      | 1        | 1.82%   |
| 41      | 1        | 1.82%   |
| 33      | 1        | 1.82%   |
| 22      | 1        | 1.82%   |
| 18      | 1        | 1.82%   |
| 17      | 1        | 1.82%   |
| 14      | 1        | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 30.91%  |
| 401-500     | 12       | 21.82%  |
| Unknown     | 10       | 18.18%  |
| 601-700     | 6        | 10.91%  |
| 701-800     | 5        | 9.09%   |
| 351-400     | 1        | 1.82%   |
| 301-350     | 1        | 1.82%   |
| 201-300     | 1        | 1.82%   |
| 1001-1500   | 1        | 1.82%   |
| 901-1000    | 1        | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 62.26%  |
| Unknown | 8        | 15.09%  |
| 21/9    | 5        | 9.43%   |
| 16/10   | 4        | 7.55%   |
| 5/4     | 2        | 3.77%   |
| 4/3     | 1        | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 34.55%  |
| 351-500        | 11       | 20%     |
| Unknown        | 10       | 18.18%  |
| 301-350        | 5        | 9.09%   |
| 151-200        | 3        | 5.45%   |
| 251-300        | 2        | 3.64%   |
| 141-150        | 2        | 3.64%   |
| More than 1000 | 1        | 1.82%   |
| 101-110        | 1        | 1.82%   |
| 501-1000       | 1        | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 57.41%  |
| 101-120 | 11       | 20.37%  |
| Unknown | 10       | 18.52%  |
| 1-50    | 1        | 1.85%   |
| 121-160 | 1        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 76.6%   |
| 0     | 17       | 18.09%  |
| 2     | 5        | 5.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 57       | 49.14%  |
| Intel                 | 37       | 31.9%   |
| Qualcomm Atheros      | 12       | 10.34%  |
| TP-Link               | 2        | 1.72%   |
| Ralink Technology     | 2        | 1.72%   |
| Edimax Technology     | 2        | 1.72%   |
| OPPO Electronics      | 1        | 0.86%   |
| IMC Networks          | 1        | 0.86%   |
| Broadcom              | 1        | 0.86%   |
| ASUSTek Computer      | 1        | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 40%     |
| Intel Ethernet Connection I217-LM                                 | 7        | 5.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.62%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 3.08%   |
| Intel I211 Gigabit Network Connection                             | 3        | 2.31%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.54%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.54%   |
| Intel Wireless 8265 / 8275                                        | 2        | 1.54%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.77%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.77%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.77%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.77%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 0.77%   |
| Intel Wireless 7260                                               | 1        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.77%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.77%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 31.25%  |
| Intel                 | 7        | 21.88%  |
| Qualcomm Atheros      | 6        | 18.75%  |
| TP-Link               | 2        | 6.25%   |
| Ralink Technology     | 2        | 6.25%   |
| Edimax Technology     | 2        | 6.25%   |
| IMC Networks          | 1        | 3.13%   |
| Broadcom              | 1        | 3.13%   |
| ASUSTek Computer      | 1        | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 6.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2        | 6.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2        | 6.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2        | 6.25%   |
| Ralink RT5370 Wireless Adapter                                              | 2        | 6.25%   |
| Intel Wireless 8265 / 8275                                                  | 2        | 6.25%   |
| Intel Wi-Fi 6 AX200                                                         | 2        | 6.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1        | 3.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 3.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1        | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 3.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 1        | 3.13%   |
| Intel Wireless 7260                                                         | 1        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1        | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1        | 3.13%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 3.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 1        | 3.13%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 3.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 3.13%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 54       | 56.84%  |
| Intel                 | 33       | 34.74%  |
| Qualcomm Atheros      | 7        | 7.37%   |
| OPPO Electronics      | 1        | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 53.06%  |
| Intel Ethernet Connection I217-LM                                 | 7        | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 6.12%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 4.08%   |
| Intel I211 Gigabit Network Connection                             | 3        | 3.06%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.02%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.02%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.02%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.02%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.02%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 1        | 1.02%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 75.81%  |
| WiFi     | 30       | 24.19%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 94.38%  |
| WiFi     | 5        | 5.62%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 76.6%   |
| 2     | 22       | 23.4%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 98.94%  |
| Yes  | 1        | 1.06%   |

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
| Silicon Wave               | 1        | 4.17%   |
| Integrated System Solution | 1        | 4.17%   |
| IMC Networks               | 1        | 4.17%   |
| ASUSTek Computer           | 1        | 4.17%   |
| Apple                      | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 8        | 33.33%  |
| Intel Bluetooth wireless interface                      | 3        | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 8.33%   |
| Intel AX200 Bluetooth                                   | 2        | 8.33%   |
| Silicon Wave Bluetooth Wireless Adapter                 | 1        | 4.17%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE             | 1        | 4.17%   |
| Realtek Bluetooth Adapter                               | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 4.17%   |
| Intel AX210 Bluetooth                                   | 1        | 4.17%   |
| Integrated System Solution Bluetooth Device             | 1        | 4.17%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 1        | 4.17%   |
| Apple Bluetooth Host Controller                         | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 58       | 40%     |
| AMD                    | 35       | 24.14%  |
| Nvidia                 | 33       | 22.76%  |
| C-Media Electronics    | 6        | 4.14%   |
| Texas Instruments      | 2        | 1.38%   |
| Logitech               | 2        | 1.38%   |
| Google                 | 2        | 1.38%   |
| Yamaha                 | 1        | 0.69%   |
| VIA Technologies       | 1        | 0.69%   |
| RME                    | 1        | 0.69%   |
| Razer USA              | 1        | 0.69%   |
| Generalplus Technology | 1        | 0.69%   |
| Creative Technology    | 1        | 0.69%   |
| ASUSTek Computer       | 1        | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 10       | 5.78%   |
| AMD Family 17h/19h HD Audio Controller                                      | 10       | 5.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 8        | 4.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 8        | 4.62%   |
| Intel Cannon Lake PCH cAVS                                                  | 8        | 4.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 8        | 4.62%   |
| Nvidia TU116 High Definition Audio Controller                               | 6        | 3.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 6        | 3.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 6        | 3.47%   |
| AMD Starship/Matisse HD Audio Controller                                    | 5        | 2.89%   |
| Intel 200 Series PCH HD Audio                                               | 4        | 2.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 2.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 4        | 2.31%   |
| Nvidia High Definition Audio Controller                                     | 3        | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                             | 3        | 1.73%   |
| Nvidia GM206 High Definition Audio Controller                               | 3        | 1.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 3        | 1.73%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 3        | 1.73%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 3        | 1.73%   |
| AMD FCH Azalia Controller                                                   | 3        | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 2        | 1.16%   |
| Nvidia GP108 High Definition Audio Controller                               | 2        | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 2        | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                          | 2        | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                               | 2        | 1.16%   |
| Logitech HD Webcam C510                                                     | 2        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller  | 2        | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 2        | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 1.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 2        | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 2        | 1.16%   |
| Google Pixel earbuds                                                        | 2        | 1.16%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 2        | 1.16%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2        | 1.16%   |
| Yamaha Steinberg UR22mkII                                                   | 1        | 0.58%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.58%   |
| Texas Instruments PCM2900C Audio CODEC                                      | 1        | 0.58%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                           | 1        | 0.58%   |
| RME Babyface Pro (Class Compliant Mode)                                     | 1        | 0.58%   |
| Razer USA Nari Ultimate                                                     | 1        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 24       | 19.51%  |
| Unknown             | 18       | 14.63%  |
| SK hynix            | 13       | 10.57%  |
| Samsung Electronics | 13       | 10.57%  |
| Crucial             | 10       | 8.13%   |
| Micron Technology   | 9        | 7.32%   |
| Unknown             | 7        | 5.69%   |
| Ramaxel Technology  | 4        | 3.25%   |
| Patriot             | 4        | 3.25%   |
| G.Skill             | 4        | 3.25%   |
| Transcend           | 3        | 2.44%   |
| Team                | 3        | 2.44%   |
| Corsair             | 3        | 2.44%   |
| GOODRAM             | 2        | 1.63%   |
| PNY                 | 1        | 0.81%   |
| Nanya Technology    | 1        | 0.81%   |
| GLOWAY              | 1        | 0.81%   |
| GeIL                | 1        | 0.81%   |
| Elpida              | 1        | 0.81%   |
| A-DATA Technology   | 1        | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown                                               | 7        | 5.19%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 4        | 2.96%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 3        | 2.22%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 2        | 1.48%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 2        | 1.48%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s     | 2        | 1.48%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s  | 2        | 1.48%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s     | 2        | 1.48%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s  | 2        | 1.48%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s  | 2        | 1.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR2                      | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s              | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR2 400MT/s              | 1        | 0.74%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s  | 1        | 0.74%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s     | 1        | 0.74%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s   | 1        | 0.74%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s   | 1        | 0.74%   |
| Team RAM Elite-13 4GB DIMM DDR3 667MT/s               | 1        | 0.74%   |
| Team RAM Elite-1 2GB DIMM DDR3 667MT/s                | 1        | 0.74%   |
| SK hynix RAM Module 8GB DIMM DDR4 2667MT/s            | 1        | 0.74%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s          | 1        | 0.74%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s            | 1        | 0.74%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s            | 1        | 0.74%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.74%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.74%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1067MT/s  | 1        | 0.74%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 0.74%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 0.74%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s  | 1        | 0.74%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB RIMM DDR4 2133MT/s | 1        | 0.74%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s           | 1        | 0.74%   |
| Samsung RAM Module 8GB DIMM DDR3 1333MT/s             | 1        | 0.74%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 40       | 42.55%  |
| DDR3    | 38       | 40.43%  |
| DDR2    | 8        | 8.51%   |
| Unknown | 4        | 4.26%   |
| SDRAM   | 3        | 3.19%   |
| DDR     | 1        | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 86       | 91.49%  |
| SODIMM | 7        | 7.45%   |
| RIMM   | 1        | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 38       | 33.33%  |
| 4096  | 35       | 30.7%   |
| 2048  | 24       | 21.05%  |
| 16384 | 12       | 10.53%  |
| 1024  | 3        | 2.63%   |
| 32768 | 2        | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 19       | 19.19%  |
| 1600    | 16       | 16.16%  |
| 3200    | 11       | 11.11%  |
| 2400    | 9        | 9.09%   |
| 2667    | 8        | 8.08%   |
| 2133    | 7        | 7.07%   |
| 800     | 7        | 7.07%   |
| 2666    | 6        | 6.06%   |
| Unknown | 4        | 4.04%   |
| 2933    | 2        | 2.02%   |
| 1866    | 2        | 2.02%   |
| 1066    | 2        | 2.02%   |
| 667     | 2        | 2.02%   |
| 3000    | 1        | 1.01%   |
| 1867    | 1        | 1.01%   |
| 1067    | 1        | 1.01%   |
| 400     | 1        | 1.01%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 2        | 28.57%  |
| Z-Star Microelectronics       | 1        | 14.29%  |
| Sunplus Innovation Technology | 1        | 14.29%  |
| Microdia                      | 1        | 14.29%  |
| Genesys Logic                 | 1        | 14.29%  |
| Arkmicro Technologies         | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Logitech HD Pro Webcam C920      | 2        | 28.57%  |
| Z-Star Venus USB2.0 Camera       | 1        | 14.29%  |
| Sunplus USB 2.0 Camera           | 1        | 14.29%  |
| Microdia Camera                  | 1        | 14.29%  |
| Genesys Logic Digital Microscope | 1        | 14.29%  |
| Arkmicro Webcam Carrefour        | 1        | 14.29%  |

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
| 1     | 43       | 45.74%  |
| 0     | 39       | 41.49%  |
| 2     | 11       | 11.7%   |
| 3     | 1        | 1.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 47       | 73.44%  |
| Net/wireless             | 9        | 14.06%  |
| Sound                    | 3        | 4.69%   |
| Bluetooth                | 3        | 4.69%   |
| Storage/raid             | 1        | 1.56%   |
| Card reader              | 1        | 1.56%   |

