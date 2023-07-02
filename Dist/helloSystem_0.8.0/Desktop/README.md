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

Total: 111

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo    | Kabini CRB 31900058 STD     | [127f92759b](https://bsd-hardware.info/?probe=127f92759b) | Jun 26, 2023 |
| Dell      | 0PC5F7 A02                  | [b22c9a0cdf](https://bsd-hardware.info/?probe=b22c9a0cdf) | May 13, 2023 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [3f089673e0](https://bsd-hardware.info/?probe=3f089673e0) | May 01, 2023 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [396d7f268c](https://bsd-hardware.info/?probe=396d7f268c) | May 01, 2023 |
| NCR       | Richmond BIOS.6.0           | [e41e1e5c70](https://bsd-hardware.info/?probe=e41e1e5c70) | Apr 28, 2023 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [cf0771c3a2](https://bsd-hardware.info/?probe=cf0771c3a2) | Apr 25, 2023 |
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
| amd64 | 98       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 97       | 98.98%  |
| KDE5         | 1        | 1.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 98       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 98       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 37       | 36.63%  |
| en    | 31       | 30.69%  |
| fr    | 11       | 10.89%  |
| ru    | 6        | 5.94%   |
| es    | 4        | 3.96%   |
| pt    | 3        | 2.97%   |
| en_GB | 2        | 1.98%   |
| zh_TW | 1        | 0.99%   |
| pl    | 1        | 0.99%   |
| nl    | 1        | 0.99%   |
| it    | 1        | 0.99%   |
| es_ES | 1        | 0.99%   |
| de_DE | 1        | 0.99%   |
| de    | 1        | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 97       | 98.98%  |
| BIOS | 1        | 1.02%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 66       | 66.67%  |
| Zfs    | 33       | 33.33%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 97       | 98.98%  |
| MBR  | 1        | 1.02%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 25.51%  |
| Gigabyte Technology | 18       | 18.37%  |
| Dell                | 12       | 12.24%  |
| Hewlett-Packard     | 9        | 9.18%   |
| ASRock              | 8        | 8.16%   |
| Lenovo              | 7        | 7.14%   |
| MSI                 | 6        | 6.12%   |
| Biostar             | 3        | 3.06%   |
| Pegatron            | 2        | 2.04%   |
| Intel               | 2        | 2.04%   |
| NCR                 | 1        | 1.02%   |
| MACHINIST           | 1        | 1.02%   |
| Google              | 1        | 1.02%   |
| Fujitsu             | 1        | 1.02%   |
| AOpen               | 1        | 1.02%   |
| AMD                 | 1        | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 3.06%   |
| MSI MS-7C37                         | 2        | 2.04%   |
| MSI MS-7A38                         | 2        | 2.04%   |
| Pegatron IPPPV-D3G                  | 1        | 1.02%   |
| Pegatron IPM41-D3                   | 1        | 1.02%   |
| NCR 7703-1515-8801                  | 1        | 1.02%   |
| MSI MS-7B89                         | 1        | 1.02%   |
| MSI MS-7918                         | 1        | 1.02%   |
| MACHINIST X99-k9 V2.0               | 1        | 1.02%   |
| Lenovo ThinkCentre M93p 10AB004DUS  | 1        | 1.02%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK  | 1        | 1.02%   |
| Lenovo ThinkCentre M910s 10MK0039US | 1        | 1.02%   |
| Lenovo ThinkCentre M83 10AHA0X9LS   | 1        | 1.02%   |
| Lenovo ThinkCentre M82 2929AZ6      | 1        | 1.02%   |
| Lenovo ThinkCentre M700 10GS        | 1        | 1.02%   |
| Lenovo H515s 10126                  | 1        | 1.02%   |
| Intel MAHOBAY                       | 1        | 1.02%   |
| Intel DN2800MT AAG23738-600         | 1        | 1.02%   |
| HP Z240 SFF Workstation             | 1        | 1.02%   |
| HP Slim Desktop S01-aF1xxx          | 1        | 1.02%   |
| HP ProDesk 600 G4 SFF               | 1        | 1.02%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.02%   |
| HP EliteDesk 800 G1 SFF             | 1        | 1.02%   |
| HP EliteDesk 700 G1 SFF             | 1        | 1.02%   |
| HP Desktop Pro A G3                 | 1        | 1.02%   |
| HP Compaq 8200 Elite USDT PC        | 1        | 1.02%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 1.02%   |
| Google Panther                      | 1        | 1.02%   |
| Gigabyte X570 UD                    | 1        | 1.02%   |
| Gigabyte X570 AORUS PRO             | 1        | 1.02%   |
| Gigabyte X399 AORUS Gaming 7        | 1        | 1.02%   |
| Gigabyte P61-USB3-B3                | 1        | 1.02%   |
| Gigabyte H81M-H                     | 1        | 1.02%   |
| Gigabyte H61M-S2PV                  | 1        | 1.02%   |
| Gigabyte H61M-S1                    | 1        | 1.02%   |
| Gigabyte H510M S2H V2               | 1        | 1.02%   |
| Gigabyte H270M-DS3H                 | 1        | 1.02%   |
| Gigabyte GA-MA770T-UD3              | 1        | 1.02%   |
| Gigabyte GA-990X-Gaming SLI-CF      | 1        | 1.02%   |
| Gigabyte G1.Sniper A88X-CF          | 1        | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 7        | 7.14%   |
| Lenovo ThinkCentre      | 6        | 6.12%   |
| ASUS PRIME              | 5        | 5.1%    |
| ASUS ROG                | 4        | 4.08%   |
| ASUS All                | 3        | 3.06%   |
| MSI MS-7C37             | 2        | 2.04%   |
| MSI MS-7A38             | 2        | 2.04%   |
| HP EliteDesk            | 2        | 2.04%   |
| HP Compaq               | 2        | 2.04%   |
| Gigabyte X570           | 2        | 2.04%   |
| Dell Precision          | 2        | 2.04%   |
| Dell Inspiron           | 2        | 2.04%   |
| ASUS P8Z68-V            | 2        | 2.04%   |
| Pegatron IPPPV-D3G      | 1        | 1.02%   |
| Pegatron IPM41-D3       | 1        | 1.02%   |
| NCR 7703-1515-8801      | 1        | 1.02%   |
| MSI MS-7B89             | 1        | 1.02%   |
| MSI MS-7918             | 1        | 1.02%   |
| MACHINIST X99-k9        | 1        | 1.02%   |
| Lenovo H515s            | 1        | 1.02%   |
| Intel MAHOBAY           | 1        | 1.02%   |
| Intel DN2800MT          | 1        | 1.02%   |
| HP Z240                 | 1        | 1.02%   |
| HP Slim                 | 1        | 1.02%   |
| HP ProDesk              | 1        | 1.02%   |
| HP Pavilion             | 1        | 1.02%   |
| HP Desktop              | 1        | 1.02%   |
| Google Panther          | 1        | 1.02%   |
| Gigabyte X399           | 1        | 1.02%   |
| Gigabyte P61-USB3-B3    | 1        | 1.02%   |
| Gigabyte H81M-H         | 1        | 1.02%   |
| Gigabyte H61M-S2PV      | 1        | 1.02%   |
| Gigabyte H61M-S1        | 1        | 1.02%   |
| Gigabyte H510M          | 1        | 1.02%   |
| Gigabyte H270M-DS3H     | 1        | 1.02%   |
| Gigabyte GA-MA770T-UD3  | 1        | 1.02%   |
| Gigabyte GA-990X-Gaming | 1        | 1.02%   |
| Gigabyte G1.Sniper      | 1        | 1.02%   |
| Gigabyte F2A88XM-D3H    | 1        | 1.02%   |
| Gigabyte B450M          | 1        | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 12       | 12.24%  |
| 2018 | 12       | 12.24%  |
| 2013 | 9        | 9.18%   |
| 2020 | 8        | 8.16%   |
| 2012 | 8        | 8.16%   |
| 2021 | 7        | 7.14%   |
| 2015 | 7        | 7.14%   |
| 2014 | 7        | 7.14%   |
| 2011 | 7        | 7.14%   |
| 2010 | 7        | 7.14%   |
| 2022 | 6        | 6.12%   |
| 2008 | 3        | 3.06%   |
| 2016 | 2        | 2.04%   |
| 2009 | 2        | 2.04%   |
| 2017 | 1        | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 98       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 98.98%  |
| Yes  | 1        | 1.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 30       | 30.61%  |
| 16.01-24.0  | 28       | 28.57%  |
| 4.01-8.0    | 20       | 20.41%  |
| 32.01-64.0  | 7        | 7.14%   |
| 64.01-256.0 | 6        | 6.12%   |
| 2.01-3.0    | 5        | 5.1%    |
| 24.01-32.0  | 1        | 1.02%   |
| 0.51-1.0    | 1        | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 43       | 43.88%  |
| 0.51-1.0  | 29       | 29.59%  |
| 1.01-2.0  | 18       | 18.37%  |
| 2.01-3.0  | 5        | 5.1%    |
| 4.01-8.0  | 1        | 1.02%   |
| 3.01-4.0  | 1        | 1.02%   |
| 8.01-16.0 | 1        | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 49%     |
| 2      | 23       | 23%     |
| 3      | 12       | 12%     |
| 5      | 5        | 5%      |
| 4      | 5        | 5%      |
| 0      | 3        | 3%      |
| 6      | 2        | 2%      |
| 10     | 1        | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 61.22%  |
| Yes       | 38       | 38.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 98       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 64.65%  |
| Yes       | 35       | 35.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 72.45%  |
| Yes       | 27       | 27.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 21       | 21.43%  |
| Russia       | 14       | 14.29%  |
| Brazil       | 7        | 7.14%   |
| Spain        | 6        | 6.12%   |
| Germany      | 6        | 6.12%   |
| Taiwan       | 5        | 5.1%    |
| UK           | 4        | 4.08%   |
| Poland       | 3        | 3.06%   |
| Italy        | 3        | 3.06%   |
| Canada       | 3        | 3.06%   |
| Portugal     | 2        | 2.04%   |
| Norway       | 2        | 2.04%   |
| Mexico       | 2        | 2.04%   |
| Indonesia    | 2        | 2.04%   |
| India        | 2        | 2.04%   |
| France       | 2        | 2.04%   |
| Belgium      | 2        | 2.04%   |
| Australia    | 2        | 2.04%   |
| Thailand     | 1        | 1.02%   |
| South Africa | 1        | 1.02%   |
| Serbia       | 1        | 1.02%   |
| Peru         | 1        | 1.02%   |
| Japan        | 1        | 1.02%   |
| Hungary      | 1        | 1.02%   |
| Colombia     | 1        | 1.02%   |
| China        | 1        | 1.02%   |
| Bulgaria     | 1        | 1.02%   |
| Argentina    | 1        | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Moscow                 | 4        | 4%      |
| Aquan                  | 4        | 4%      |
| Yekaterinburg          | 2        | 2%      |
| Voronezh               | 2        | 2%      |
| Volgograd              | 2        | 2%      |
| Temple                 | 2        | 2%      |
| Saratov                | 2        | 2%      |
| Manchester             | 2        | 2%      |
| Gistel                 | 2        | 2%      |
| Zhengzhou              | 1        | 1%      |
| Yala                   | 1        | 1%      |
| Winnipeg               | 1        | 1%      |
| Willingboro            | 1        | 1%      |
| Veliko Tarnovo         | 1        | 1%      |
| Valledupar             | 1        | 1%      |
| Valencia               | 1        | 1%      |
| Trieste                | 1        | 1%      |
| Trebujena              | 1        | 1%      |
| Tasikmalaya            | 1        | 1%      |
| Tallahassee            | 1        | 1%      |
| Szigetszentmiklos      | 1        | 1%      |
| Surrey                 | 1        | 1%      |
| Sumaré                | 1        | 1%      |
| Spartanburg            | 1        | 1%      |
| Southminster           | 1        | 1%      |
| Seville                | 1        | 1%      |
| Sao Domingos das Dores | 1        | 1%      |
| Salisbury              | 1        | 1%      |
| Salem                  | 1        | 1%      |
| Rosignano Marittimo    | 1        | 1%      |
| Richardson             | 1        | 1%      |
| Rhinelander            | 1        | 1%      |
| Remshalden             | 1        | 1%      |
| Reinsvoll              | 1        | 1%      |
| Recklinghausen         | 1        | 1%      |
| Québec                | 1        | 1%      |
| Portland               | 1        | 1%      |
| Pieve a Nievole        | 1        | 1%      |
| Palembang              | 1        | 1%      |
| Osasco                 | 1        | 1%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 41     | 18.87%  |
| Seagate             | 27       | 31     | 16.98%  |
| Samsung Electronics | 24       | 33     | 15.09%  |
| Hitachi             | 12       | 15     | 7.55%   |
| Toshiba             | 9        | 10     | 5.66%   |
| Kingston            | 9        | 10     | 5.66%   |
| Crucial             | 7        | 9      | 4.4%    |
| A-DATA Technology   | 6        | 7      | 3.77%   |
| SanDisk             | 5        | 6      | 3.14%   |
| SPCC                | 3        | 8      | 1.89%   |
| PNY                 | 2        | 2      | 1.26%   |
| Patriot             | 2        | 2      | 1.26%   |
| Lexar               | 2        | 3      | 1.26%   |
| Hewlett-Packard     | 2        | 2      | 1.26%   |
| XrayDisk            | 1        | 1      | 0.63%   |
| Transcend           | 1        | 1      | 0.63%   |
| SK hynix            | 1        | 1      | 0.63%   |
| Silicon Motion      | 1        | 1      | 0.63%   |
| Reletech            | 1        | 1      | 0.63%   |
| Plextor             | 1        | 1      | 0.63%   |
| Pioneer             | 1        | 1      | 0.63%   |
| OCZ                 | 1        | 1      | 0.63%   |
| Mushkin             | 1        | 4      | 0.63%   |
| MidasForce          | 1        | 1      | 0.63%   |
| Micron Technology   | 1        | 1      | 0.63%   |
| LDLC                | 1        | 1      | 0.63%   |
| KingSpec            | 1        | 1      | 0.63%   |
| Intenso             | 1        | 1      | 0.63%   |
| Gigabyte Technology | 1        | 1      | 0.63%   |
| Fanxiang            | 1        | 1      | 0.63%   |
| Emtec               | 1        | 1      | 0.63%   |
| Corsair             | 1        | 1      | 0.63%   |
| China               | 1        | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 2.19%   |
| Samsung SSD 860 EVO 1TB         | 3        | 1.64%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 1.09%   |
| Toshiba MQ01ABD050 500GB        | 2        | 1.09%   |
| Toshiba HDWD110 1TB             | 2        | 1.09%   |
| Seagate ST3500418AS 500GB       | 2        | 1.09%   |
| Seagate ST3250310AS 250GB       | 2        | 1.09%   |
| Seagate ST2000LM007-1R8174 2TB  | 2        | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 1.09%   |
| Samsung SSD 980 PRO 1TB         | 2        | 1.09%   |
| Samsung SSD 860 PRO 512GB       | 2        | 1.09%   |
| Samsung SSD 860 EVO 500GB       | 2        | 1.09%   |
| Samsung HD322HJ 320GB           | 2        | 1.09%   |
| Kingston SA400S37240G 240GB     | 2        | 1.09%   |
| Hitachi HDS721616PLA380 160GB   | 2        | 1.09%   |
| A-DATA SU800 256GB              | 2        | 1.09%   |
| XrayDisk SSD 256GB              | 1        | 0.55%   |
| WDC WDS500G3XHC-00SJG0 500GB    | 1        | 0.55%   |
| WDC WDS500G2X0C-00L350 500GB    | 1        | 0.55%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.55%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 0.55%   |
| WDC WDS120G2G0B-00EPW0 120GB    | 1        | 0.55%   |
| WDC WD80EFAX-68KNBN0 8TB        | 1        | 0.55%   |
| WDC WD50NPZZ-00A9JT0 5TB        | 1        | 0.55%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.55%   |
| WDC WD5000LPCX-60VHAT0 500GB    | 1        | 0.55%   |
| WDC WD5000AZLX-60K2TA1 500GB    | 1        | 0.55%   |
| WDC WD5000AVVS-63H0B1 500GB     | 1        | 0.55%   |
| WDC WD5000AAVS-00ZTB0 500GB     | 1        | 0.55%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1        | 0.55%   |
| WDC WD5000AAKS-00YGA0 500GB     | 1        | 0.55%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1        | 0.55%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.55%   |
| WDC WD3200BEVT-00ZCT0 320GB     | 1        | 0.55%   |
| WDC WD3200AAKS-75L9A0 320GB     | 1        | 0.55%   |
| WDC WD3003FZEX-00Z4SA0 3TB      | 1        | 0.55%   |
| WDC WD2500BEVT-75A23T0 250GB    | 1        | 0.55%   |
| WDC WD20EZAZ-22L9GB0 2TB        | 1        | 0.55%   |
| WDC WD20EFRX-68EUZN0 2TB        | 1        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 31     | 34.18%  |
| WDC                 | 25       | 32     | 31.65%  |
| Hitachi             | 12       | 15     | 15.19%  |
| Samsung Electronics | 8        | 8      | 10.13%  |
| Toshiba             | 6        | 7      | 7.59%   |
| Hewlett-Packard     | 1        | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 16     | 16.92%  |
| Kingston            | 7        | 8      | 10.77%  |
| Crucial             | 6        | 8      | 9.23%   |
| A-DATA Technology   | 6        | 7      | 9.23%   |
| SanDisk             | 5        | 6      | 7.69%   |
| WDC                 | 4        | 5      | 6.15%   |
| Toshiba             | 3        | 3      | 4.62%   |
| SPCC                | 3        | 8      | 4.62%   |
| PNY                 | 2        | 2      | 3.08%   |
| Patriot             | 2        | 2      | 3.08%   |
| XrayDisk            | 1        | 1      | 1.54%   |
| Transcend           | 1        | 1      | 1.54%   |
| Plextor             | 1        | 1      | 1.54%   |
| Pioneer             | 1        | 1      | 1.54%   |
| OCZ                 | 1        | 1      | 1.54%   |
| Mushkin             | 1        | 4      | 1.54%   |
| MidasForce          | 1        | 1      | 1.54%   |
| Micron Technology   | 1        | 1      | 1.54%   |
| Lexar               | 1        | 1      | 1.54%   |
| KingSpec            | 1        | 1      | 1.54%   |
| Intenso             | 1        | 1      | 1.54%   |
| Hewlett-Packard     | 1        | 1      | 1.54%   |
| Gigabyte Technology | 1        | 1      | 1.54%   |
| Fanxiang            | 1        | 1      | 1.54%   |
| Emtec               | 1        | 1      | 1.54%   |
| China               | 1        | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 62       | 94     | 46.97%  |
| SSD  | 50       | 84     | 37.88%  |
| NVMe | 20       | 23     | 15.15%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 91       | 178    | 81.98%  |
| NVMe | 20       | 23     | 18.02%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 75       | 113    | 61.48%  |
| 0.51-1.0   | 26       | 32     | 21.31%  |
| 1.01-2.0   | 14       | 19     | 11.48%  |
| 3.01-4.0   | 3        | 4      | 2.46%   |
| 2.01-3.0   | 2        | 8      | 1.64%   |
| 4.01-10.0  | 2        | 2      | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 61       | 61.62%  |
| 101-250    | 15       | 15.15%  |
| 251-500    | 11       | 11.11%  |
| 501-1000   | 5        | 5.05%   |
| 1001-2000  | 4        | 4.04%   |
| 51-100     | 2        | 2.02%   |
| 21-50      | 1        | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 95       | 95.96%  |
| 101-250  | 3        | 3.03%   |
| 501-1000 | 1        | 1.01%   |

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
| Hitachi HDS721616PLA380 160GB     | 1        | 1      | 4.55%   |
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
| Works    | 78       | 163    | 72.9%   |
| Malfunc  | 20       | 23     | 18.69%  |
| Detected | 7        | 13     | 6.54%   |
| Failed   | 2        | 2      | 1.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 64       | 47.76%  |
| AMD                          | 34       | 25.37%  |
| Samsung Electronics          | 8        | 5.97%   |
| SanDisk                      | 6        | 4.48%   |
| JMicron Technology           | 4        | 2.99%   |
| ASMedia Technology           | 4        | 2.99%   |
| Silicon Motion               | 2        | 1.49%   |
| Shenzhen Longsys Electronics | 2        | 1.49%   |
| Phison Electronics           | 2        | 1.49%   |
| Kingston Technology Company  | 2        | 1.49%   |
| VIA Technologies             | 1        | 0.75%   |
| SK hynix                     | 1        | 0.75%   |
| Realtek Semiconductor        | 1        | 0.75%   |
| Micron/Crucial Technology    | 1        | 0.75%   |
| Marvell Technology Group     | 1        | 0.75%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 10.71%  |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 2.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 2.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 2.98%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 2.38%   |
| AMD FCH SATA Controller D                                                               | 4        | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 1.79%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.19%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2        | 1.19%   |
| Sandisk WD Black SN770 NVMe SSD                                                         | 2        | 1.19%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.19%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.19%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.19%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.19%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.19%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.19%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.19%   |
| Unknown                                                                                 | 2        | 1.19%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.6%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 0.6%    |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1        | 0.6%    |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.6%    |
| Realtek NVMe Controller                                                                 | 1        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.6%    |
| Phison E12 NVMe Controller                                                              | 1        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 75       | 58.14%  |
| IDE  | 28       | 21.71%  |
| NVMe | 23       | 17.83%  |
| RAID | 3        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 65.31%  |
| AMD    | 34       | 34.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 3.06%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 3.06%   |
| Intel Core 2 Duo                            | 3        | 3.06%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 2.04%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 2.04%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 2.04%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.04%   |
| AMD Phenom II X4 945 Processor              | 2        | 2.04%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 1.02%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1        | 1.02%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 1.02%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.02%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 1.02%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.02%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.02%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.02%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.02%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.02%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.02%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.02%   |
| Intel Core i9-9900KS CPU @ 4.00GHz          | 1        | 1.02%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.02%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.02%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 1.02%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.02%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.02%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.02%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.02%   |
| Intel Core i5-8500T CPU @ 2.10GHz           | 1        | 1.02%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.02%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.02%   |
| Intel Core i5-6500TE CPU @ 2.30GHz          | 1        | 1.02%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.02%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 1.02%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.02%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.02%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.02%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.02%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.02%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 21       | 21.43%  |
| Intel Core i3           | 10       | 10.2%   |
| Intel Core i7           | 7        | 7.14%   |
| AMD Ryzen 5             | 7        | 7.14%   |
| AMD Phenom II X4        | 5        | 5.1%    |
| Intel Xeon              | 4        | 4.08%   |
| Intel Pentium Dual-Core | 4        | 4.08%   |
| Intel Core 2 Duo        | 4        | 4.08%   |
| Intel Celeron           | 4        | 4.08%   |
| AMD Ryzen 7             | 4        | 4.08%   |
| Intel Pentium           | 3        | 3.06%   |
| AMD Ryzen 9             | 3        | 3.06%   |
| AMD Ryzen 3             | 3        | 3.06%   |
| AMD FX                  | 3        | 3.06%   |
| Other                   | 2        | 2.04%   |
| Intel Atom              | 2        | 2.04%   |
| Intel Pentium Silver    | 1        | 1.02%   |
| Intel Core i9           | 1        | 1.02%   |
| Intel Core 2 Quad       | 1        | 1.02%   |
| Intel Core 2            | 1        | 1.02%   |
| AMD Ryzen Threadripper  | 1        | 1.02%   |
| AMD Ryzen 5 PRO         | 1        | 1.02%   |
| AMD Ryzen 3 PRO         | 1        | 1.02%   |
| AMD E1                  | 1        | 1.02%   |
| AMD Athlon II X4        | 1        | 1.02%   |
| AMD Athlon              | 1        | 1.02%   |
| AMD A8                  | 1        | 1.02%   |
| AMD A10                 | 1        | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 40       | 40.82%  |
| 2       | 23       | 23.47%  |
| 6       | 10       | 10.2%   |
| 8       | 7        | 7.14%   |
| 16      | 5        | 5.1%    |
| 12      | 5        | 5.1%    |
| Unknown | 3        | 3.06%   |
| 24      | 2        | 2.04%   |
| 32      | 1        | 1.02%   |
| 10      | 1        | 1.02%   |
| 1       | 1        | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 75       | 76.53%  |
| 2       | 20       | 20.41%  |
| Unknown | 3        | 3.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 12       | 12.24%  |
| KabyLake      | 11       | 11.22%  |
| SandyBridge   | 9        | 9.18%   |
| Penryn        | 7        | 7.14%   |
| Zen+          | 6        | 6.12%   |
| Zen 3         | 6        | 6.12%   |
| K10           | 6        | 6.12%   |
| IvyBridge     | 6        | 6.12%   |
| Zen           | 5        | 5.1%    |
| Zen 2         | 4        | 4.08%   |
| Skylake       | 4        | 4.08%   |
| Core          | 4        | 4.08%   |
| Piledriver    | 3        | 3.06%   |
| Westmere      | 2        | 2.04%   |
| Silvermont    | 2        | 2.04%   |
| CometLake     | 2        | 2.04%   |
| Bonnell       | 2        | 2.04%   |
| Unknown       | 2        | 2.04%   |
| Steamroller   | 1        | 1.02%   |
| Jaguar        | 1        | 1.02%   |
| Goldmont plus | 1        | 1.02%   |
| Excavator     | 1        | 1.02%   |
| Broadwell     | 1        | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 37       | 37%     |
| Intel  | 37       | 37%     |
| AMD    | 26       | 26%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 7%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 5%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3%      |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2%      |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 2%      |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 2%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2%      |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2%      |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2%      |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 2%      |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2%      |
| Intel HD Graphics 530                                                       | 2        | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2%      |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2%      |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1%      |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 1%      |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1%      |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1%      |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1%      |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1%      |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1%      |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1%      |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1%      |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 1%      |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 1%      |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1%      |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1%      |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1%      |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1%      |
| Nvidia G84GL [Quadro FX 570]                                                | 1        | 1%      |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1        | 1%      |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 37       | 37.76%  |
| 1 x Intel   | 33       | 33.67%  |
| 1 x AMD     | 24       | 24.49%  |
| 2 x Intel   | 2        | 2.04%   |
| Intel + AMD | 2        | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 65       | 66.33%  |
| Proprietary | 29       | 29.59%  |
| Unknown     | 4        | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 53       | 54.08%  |
| 1.01-2.0   | 12       | 12.24%  |
| 3.01-4.0   | 9        | 9.18%   |
| 0.51-1.0   | 8        | 8.16%   |
| 5.01-6.0   | 6        | 6.12%   |
| 0.01-0.5   | 6        | 6.12%   |
| 7.01-8.0   | 3        | 3.06%   |
| 8.01-16.0  | 1        | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 8        | 14.04%  |
| Acer                 | 8        | 14.04%  |
| Samsung Electronics  | 6        | 10.53%  |
| Dell                 | 6        | 10.53%  |
| Hewlett-Packard      | 5        | 8.77%   |
| Philips              | 3        | 5.26%   |
| MSI                  | 3        | 5.26%   |
| AOC                  | 3        | 5.26%   |
| LG Electronics       | 2        | 3.51%   |
| BenQ                 | 2        | 3.51%   |
| Vizio                | 1        | 1.75%   |
| ViewSonic            | 1        | 1.75%   |
| Toshiba              | 1        | 1.75%   |
| NEC Computers        | 1        | 1.75%   |
| Lenovo Group Limited | 1        | 1.75%   |
| Insignia             | 1        | 1.75%   |
| Iiyama               | 1        | 1.75%   |
| Idek Iiyama          | 1        | 1.75%   |
| CHD                  | 1        | 1.75%   |
| ASUSTek Computer     | 1        | 1.75%   |
| Unknown              | 1        | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2        | 3.39%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch           | 2        | 3.39%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2        | 3.39%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1        | 1.69%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch            | 1        | 1.69%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 1.69%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1        | 1.69%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1        | 1.69%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1        | 1.69%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1        | 1.69%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1        | 1.69%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch     | 1        | 1.69%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1        | 1.69%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1        | 1.69%   |
| Philips LCD Monitor PHL0868 1680x1050 470x290mm 21.7-inch             | 1        | 1.69%   |
| Philips LCD Monitor PHL 243V7 3840x1080                               | 1        | 1.69%   |
| NEC Computers LCD175VXM+ NEC66C0 1280x1024 340x270mm 17.1-inch        | 1        | 1.69%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1        | 1.69%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 1        | 1.69%   |
| LG Electronics LCD Monitor E2441 3840x1080                            | 1        | 1.69%   |
| Lenovo Group Limited LCD Monitor C24-25 1920x1080                     | 1        | 1.69%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1        | 1.69%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 1.69%   |
| Idek Iiyama LCD Monitor PL3270Q 2560x1440                             | 1        | 1.69%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 1.69%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x290mm 23.1-inch          | 1        | 1.69%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1        | 1.69%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 1        | 1.69%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch             | 1        | 1.69%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                   | 1        | 1.69%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1        | 1.69%   |
| Goldstar LG HDR WFHD GSM5BA0 2560x1080 800x340mm 34.2-inch            | 1        | 1.69%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1        | 1.69%   |
| Goldstar E2240 GSM57A4 1920x1080 480x270mm 21.7-inch                  | 1        | 1.69%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1        | 1.69%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1        | 1.69%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1        | 1.69%   |
| Dell LCD Monitor LNK0001 1920x1080 300x230mm 14.9-inch                | 1        | 1.69%   |
| Dell LCD Monitor E2014H                                               | 1        | 1.69%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1        | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 60.71%  |
| 2560x1440 (QHD)    | 5        | 8.93%   |
| 2560x1080          | 3        | 5.36%   |
| 1680x1050 (WSXGA+) | 3        | 5.36%   |
| 3440x1440          | 2        | 3.57%   |
| 1366x768 (WXGA)    | 2        | 3.57%   |
| 1280x1024 (SXGA)   | 2        | 3.57%   |
| 3840x1080          | 1        | 1.79%   |
| 3520x1080          | 1        | 1.79%   |
| 1600x900 (HD+)     | 1        | 1.79%   |
| 1440x900 (WXGA+)   | 1        | 1.79%   |
| Unknown            | 1        | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 17.54%  |
| 21      | 8        | 14.04%  |
| 23      | 7        | 12.28%  |
| 31      | 6        | 10.53%  |
| 24      | 6        | 10.53%  |
| 27      | 5        | 8.77%   |
| 34      | 4        | 7.02%   |
| 19      | 3        | 5.26%   |
| 18      | 2        | 3.51%   |
| 50      | 1        | 1.75%   |
| 41      | 1        | 1.75%   |
| 33      | 1        | 1.75%   |
| 22      | 1        | 1.75%   |
| 17      | 1        | 1.75%   |
| 14      | 1        | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 31.58%  |
| 401-500     | 13       | 22.81%  |
| Unknown     | 10       | 17.54%  |
| 601-700     | 6        | 10.53%  |
| 701-800     | 5        | 8.77%   |
| 351-400     | 1        | 1.75%   |
| 301-350     | 1        | 1.75%   |
| 201-300     | 1        | 1.75%   |
| 1001-1500   | 1        | 1.75%   |
| 901-1000    | 1        | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 63.64%  |
| Unknown | 8        | 14.55%  |
| 21/9    | 5        | 9.09%   |
| 16/10   | 4        | 7.27%   |
| 5/4     | 2        | 3.64%   |
| 4/3     | 1        | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 35.09%  |
| 351-500        | 11       | 19.3%   |
| Unknown        | 10       | 17.54%  |
| 301-350        | 5        | 8.77%   |
| 151-200        | 3        | 5.26%   |
| 141-150        | 3        | 5.26%   |
| 251-300        | 2        | 3.51%   |
| More than 1000 | 1        | 1.75%   |
| 101-110        | 1        | 1.75%   |
| 501-1000       | 1        | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 58.93%  |
| 101-120 | 11       | 19.64%  |
| Unknown | 10       | 17.86%  |
| 1-50    | 1        | 1.79%   |
| 121-160 | 1        | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 76.53%  |
| 0     | 18       | 18.37%  |
| 2     | 5        | 5.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 59       | 47.97%  |
| Intel                 | 40       | 32.52%  |
| Qualcomm Atheros      | 12       | 9.76%   |
| TP-Link               | 2        | 1.63%   |
| Ralink Technology     | 2        | 1.63%   |
| Edimax Technology     | 2        | 1.63%   |
| Ralink                | 1        | 0.81%   |
| OPPO Electronics      | 1        | 0.81%   |
| IMC Networks          | 1        | 0.81%   |
| Broadcom              | 1        | 0.81%   |
| Belkin Components     | 1        | 0.81%   |
| ASUSTek Computer      | 1        | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 37.14%  |
| Intel Ethernet Connection I217-LM                                 | 7        | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.29%   |
| Intel I211 Gigabit Network Connection                             | 4        | 2.86%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.14%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 2.14%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 1.43%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.43%   |
| Intel Wireless 8265 / 8275                                        | 2        | 1.43%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.43%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.71%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.71%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.71%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 0.71%   |
| Intel Wireless 8260                                               | 1        | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 29.73%  |
| Intel                 | 9        | 24.32%  |
| Qualcomm Atheros      | 6        | 16.22%  |
| TP-Link               | 2        | 5.41%   |
| Ralink Technology     | 2        | 5.41%   |
| Edimax Technology     | 2        | 5.41%   |
| Ralink                | 1        | 2.7%    |
| IMC Networks          | 1        | 2.7%    |
| Broadcom              | 1        | 2.7%    |
| Belkin Components     | 1        | 2.7%    |
| ASUSTek Computer      | 1        | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                         | 3        | 8.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 5.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2        | 5.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2        | 5.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2        | 5.41%   |
| Ralink RT5370 Wireless Adapter                                              | 2        | 5.41%   |
| Intel Wireless 8265 / 8275                                                  | 2        | 5.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1        | 2.7%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1        | 2.7%    |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 2.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1        | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 2.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 2.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 1        | 2.7%    |
| Intel Wireless 8260                                                         | 1        | 2.7%    |
| Intel Wireless 7260                                                         | 1        | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1        | 2.7%    |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 2.7%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 1        | 2.7%    |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 2.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 2.7%    |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]          | 1        | 2.7%    |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 56       | 56%     |
| Intel                 | 36       | 36%     |
| Qualcomm Atheros      | 7        | 7%      |
| OPPO Electronics      | 1        | 1%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 50.49%  |
| Intel Ethernet Connection I217-LM                                 | 7        | 6.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 5.83%   |
| Intel I211 Gigabit Network Connection                             | 4        | 3.88%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 3.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.91%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 2.91%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.97%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.97%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.97%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.97%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.97%   |
| Intel 82577LM Gigabit Network Connection                          | 1        | 0.97%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 98       | 74.24%  |
| WiFi     | 34       | 25.76%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 93.48%  |
| WiFi     | 6        | 6.52%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 73.47%  |
| 2     | 25       | 25.51%  |
| 3     | 1        | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 98.98%  |
| Yes  | 1        | 1.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 9        | 33.33%  |
| Cambridge Silicon Radio    | 8        | 29.63%  |
| Realtek Semiconductor      | 4        | 14.81%  |
| Silicon Wave               | 1        | 3.7%    |
| Ralink                     | 1        | 3.7%    |
| Integrated System Solution | 1        | 3.7%    |
| IMC Networks               | 1        | 3.7%    |
| ASUSTek Computer           | 1        | 3.7%    |
| Apple                      | 1        | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 8        | 29.63%  |
| Intel Bluetooth wireless interface                      | 4        | 14.81%  |
| Intel AX200 Bluetooth                                   | 3        | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 7.41%   |
| Silicon Wave Bluetooth Wireless Adapter                 | 1        | 3.7%    |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE             | 1        | 3.7%    |
| Realtek Bluetooth Adapter                               | 1        | 3.7%    |
| Ralink RT3290 Bluetooth                                 | 1        | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 3.7%    |
| Intel AX210 Bluetooth                                   | 1        | 3.7%    |
| Integrated System Solution Bluetooth Device             | 1        | 3.7%    |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS | 1        | 3.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 1        | 3.7%    |
| Apple Bluetooth Host Controller                         | 1        | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 60       | 40%     |
| AMD                    | 38       | 25.33%  |
| Nvidia                 | 33       | 22%     |
| C-Media Electronics    | 6        | 4%      |
| Texas Instruments      | 2        | 1.33%   |
| Logitech               | 2        | 1.33%   |
| Google                 | 2        | 1.33%   |
| Yamaha                 | 1        | 0.67%   |
| VIA Technologies       | 1        | 0.67%   |
| RME                    | 1        | 0.67%   |
| Razer USA              | 1        | 0.67%   |
| Generalplus Technology | 1        | 0.67%   |
| Creative Technology    | 1        | 0.67%   |
| ASUSTek Computer       | 1        | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 10       | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                      | 10       | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 8        | 4.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 8        | 4.44%   |
| Intel Cannon Lake PCH cAVS                                                  | 8        | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 8        | 4.44%   |
| AMD Starship/Matisse HD Audio Controller                                    | 7        | 3.89%   |
| Nvidia TU116 High Definition Audio Controller                               | 6        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 6        | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 6        | 3.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 5        | 2.78%   |
| Intel 200 Series PCH HD Audio                                               | 4        | 2.22%   |
| AMD FCH Azalia Controller                                                   | 4        | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 2.22%   |
| Nvidia High Definition Audio Controller                                     | 3        | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                             | 3        | 1.67%   |
| Nvidia GM206 High Definition Audio Controller                               | 3        | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 3        | 1.67%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 3        | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 3        | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 2        | 1.11%   |
| Nvidia GP108 High Definition Audio Controller                               | 2        | 1.11%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 2        | 1.11%   |
| Nvidia GF119 HDMI Audio Controller                                          | 2        | 1.11%   |
| Nvidia GF108 High Definition Audio Controller                               | 2        | 1.11%   |
| Logitech HD Webcam C510                                                     | 2        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller  | 2        | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 2        | 1.11%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 1.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 2        | 1.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 2        | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 2        | 1.11%   |
| Google Pixel earbuds                                                        | 2        | 1.11%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 2        | 1.11%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2        | 1.11%   |
| Yamaha Steinberg UR22mkII                                                   | 1        | 0.56%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.56%   |
| Texas Instruments PCM2900C Audio CODEC                                      | 1        | 0.56%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                           | 1        | 0.56%   |
| RME Babyface Pro (Class Compliant Mode)                                     | 1        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 24       | 18.9%   |
| Unknown             | 18       | 14.17%  |
| Samsung Electronics | 14       | 11.02%  |
| SK hynix            | 13       | 10.24%  |
| Crucial             | 11       | 8.66%   |
| Micron Technology   | 9        | 7.09%   |
| Unknown             | 7        | 5.51%   |
| G.Skill             | 6        | 4.72%   |
| Ramaxel Technology  | 4        | 3.15%   |
| Patriot             | 4        | 3.15%   |
| Transcend           | 3        | 2.36%   |
| Team                | 3        | 2.36%   |
| Corsair             | 3        | 2.36%   |
| GOODRAM             | 2        | 1.57%   |
| PNY                 | 1        | 0.79%   |
| Nanya Technology    | 1        | 0.79%   |
| GLOWAY              | 1        | 0.79%   |
| GeIL                | 1        | 0.79%   |
| Elpida              | 1        | 0.79%   |
| A-DATA Technology   | 1        | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown                                               | 7        | 5.04%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 4        | 2.88%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 3        | 2.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 2        | 1.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 2        | 1.44%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s     | 2        | 1.44%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s  | 2        | 1.44%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s     | 2        | 1.44%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s  | 2        | 1.44%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s  | 2        | 1.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 0.72%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 1        | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.72%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2                      | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s              | 1        | 0.72%   |
| Unknown RAM Module 1GB DIMM DDR2 400MT/s              | 1        | 0.72%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s  | 1        | 0.72%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s     | 1        | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s   | 1        | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s   | 1        | 0.72%   |
| Team RAM Elite-13 4GB DIMM DDR3 667MT/s               | 1        | 0.72%   |
| Team RAM Elite-1 2GB DIMM DDR3 667MT/s                | 1        | 0.72%   |
| SK hynix RAM Module 8GB DIMM DDR4 2667MT/s            | 1        | 0.72%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s          | 1        | 0.72%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s            | 1        | 0.72%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s            | 1        | 0.72%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.72%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.72%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1067MT/s  | 1        | 0.72%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 0.72%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 0.72%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s  | 1        | 0.72%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB RIMM DDR4 2133MT/s | 1        | 0.72%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s           | 1        | 0.72%   |
| Samsung RAM Module 8GB DIMM DDR3 1333MT/s             | 1        | 0.72%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 43       | 43.43%  |
| DDR3    | 39       | 39.39%  |
| DDR2    | 8        | 8.08%   |
| SDRAM   | 4        | 4.04%   |
| Unknown | 4        | 4.04%   |
| DDR     | 1        | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 89       | 90.82%  |
| SODIMM | 8        | 8.16%   |
| RIMM   | 1        | 1.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 39       | 33.05%  |
| 4096  | 36       | 30.51%  |
| 2048  | 24       | 20.34%  |
| 16384 | 13       | 11.02%  |
| 32768 | 3        | 2.54%   |
| 1024  | 3        | 2.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 19       | 18.45%  |
| 1600    | 17       | 16.5%   |
| 3200    | 12       | 11.65%  |
| 2400    | 10       | 9.71%   |
| 2667    | 8        | 7.77%   |
| 2133    | 7        | 6.8%    |
| 800     | 7        | 6.8%    |
| 2666    | 6        | 5.83%   |
| Unknown | 4        | 3.88%   |
| 2933    | 2        | 1.94%   |
| 1866    | 2        | 1.94%   |
| 1066    | 2        | 1.94%   |
| 667     | 2        | 1.94%   |
| 3000    | 1        | 0.97%   |
| 2866    | 1        | 0.97%   |
| 1867    | 1        | 0.97%   |
| 1067    | 1        | 0.97%   |
| 400     | 1        | 0.97%   |

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
| Logitech                      | 3        | 33.33%  |
| Sunplus Innovation Technology | 2        | 22.22%  |
| Z-Star Microelectronics       | 1        | 11.11%  |
| Microdia                      | 1        | 11.11%  |
| Genesys Logic                 | 1        | 11.11%  |
| Arkmicro Technologies         | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Sunplus USB 2.0 Camera           | 2        | 22.22%  |
| Logitech HD Pro Webcam C920      | 2        | 22.22%  |
| Z-Star Venus USB2.0 Camera       | 1        | 11.11%  |
| Microdia Camera                  | 1        | 11.11%  |
| Logitech Webcam C310             | 1        | 11.11%  |
| Genesys Logic Digital Microscope | 1        | 11.11%  |
| Arkmicro Webcam Carrefour        | 1        | 11.11%  |

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
| 1     | 45       | 45.92%  |
| 0     | 40       | 40.82%  |
| 2     | 11       | 11.22%  |
| 3     | 2        | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 48       | 69.57%  |
| Net/wireless             | 10       | 14.49%  |
| Bluetooth                | 4        | 5.8%    |
| Sound                    | 3        | 4.35%   |
| Card reader              | 2        | 2.9%    |
| Storage/raid             | 1        | 1.45%   |
| Network                  | 1        | 1.45%   |

