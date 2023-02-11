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

Total: 70

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 63       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 62       | 98.41%  |
| KDE5         | 1        | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 63       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 63       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 37       | 57.81%  |
| en    | 13       | 20.31%  |
| ru    | 4        | 6.25%   |
| pt    | 2        | 3.13%   |
| fr    | 2        | 3.13%   |
| zh_TW | 1        | 1.56%   |
| it    | 1        | 1.56%   |
| es_ES | 1        | 1.56%   |
| es    | 1        | 1.56%   |
| en_GB | 1        | 1.56%   |
| de    | 1        | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 62       | 98.41%  |
| BIOS | 1        | 1.59%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 44       | 68.75%  |
| Zfs    | 20       | 31.25%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 62       | 98.41%  |
| MBR  | 1        | 1.59%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 22.22%  |
| Gigabyte Technology | 13       | 20.63%  |
| Dell                | 9        | 14.29%  |
| Hewlett-Packard     | 8        | 12.7%   |
| MSI                 | 4        | 6.35%   |
| ASRock              | 4        | 6.35%   |
| Lenovo              | 3        | 4.76%   |
| Pegatron            | 2        | 3.17%   |
| Intel               | 2        | 3.17%   |
| MACHINIST           | 1        | 1.59%   |
| Google              | 1        | 1.59%   |
| Biostar             | 1        | 1.59%   |
| AMD                 | 1        | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 4.76%   |
| MSI MS-7A38                         | 2        | 3.17%   |
| Pegatron IPPPV-D3G                  | 1        | 1.59%   |
| Pegatron IPM41-D3                   | 1        | 1.59%   |
| MSI MS-7C37                         | 1        | 1.59%   |
| MSI MS-7B89                         | 1        | 1.59%   |
| MACHINIST X99-k9 V2.0               | 1        | 1.59%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK  | 1        | 1.59%   |
| Lenovo ThinkCentre M910s 10MK0039US | 1        | 1.59%   |
| Lenovo ThinkCentre M700 10GS        | 1        | 1.59%   |
| Intel MAHOBAY                       | 1        | 1.59%   |
| Intel DN2800MT AAG23738-600         | 1        | 1.59%   |
| HP Z240 SFF Workstation             | 1        | 1.59%   |
| HP Slim Desktop S01-aF1xxx          | 1        | 1.59%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.59%   |
| HP EliteDesk 800 G1 SFF             | 1        | 1.59%   |
| HP EliteDesk 700 G1 SFF             | 1        | 1.59%   |
| HP Desktop Pro A G3                 | 1        | 1.59%   |
| HP Compaq 8200 Elite USDT PC        | 1        | 1.59%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 1.59%   |
| Google Panther                      | 1        | 1.59%   |
| Gigabyte X570 AORUS PRO             | 1        | 1.59%   |
| Gigabyte X399 AORUS Gaming 7        | 1        | 1.59%   |
| Gigabyte P61-USB3-B3                | 1        | 1.59%   |
| Gigabyte H81M-H                     | 1        | 1.59%   |
| Gigabyte H61M-S2PV                  | 1        | 1.59%   |
| Gigabyte H61M-S1                    | 1        | 1.59%   |
| Gigabyte H270M-DS3H                 | 1        | 1.59%   |
| Gigabyte GA-MA770T-UD3              | 1        | 1.59%   |
| Gigabyte GA-990X-Gaming SLI-CF      | 1        | 1.59%   |
| Gigabyte G1.Sniper A88X-CF          | 1        | 1.59%   |
| Gigabyte B360M-D2V                  | 1        | 1.59%   |
| Gigabyte A520M S2H                  | 1        | 1.59%   |
| Gigabyte 970A-D3P                   | 1        | 1.59%   |
| Dell Studio 540                     | 1        | 1.59%   |
| Dell Precision Tower 5810           | 1        | 1.59%   |
| Dell Precision 3440                 | 1        | 1.59%   |
| Dell OptiPlex 780                   | 1        | 1.59%   |
| Dell OptiPlex 760                   | 1        | 1.59%   |
| Dell OptiPlex 3060                  | 1        | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 4        | 6.35%   |
| Lenovo ThinkCentre      | 3        | 4.76%   |
| ASUS All                | 3        | 4.76%   |
| MSI MS-7A38             | 2        | 3.17%   |
| HP EliteDesk            | 2        | 3.17%   |
| HP Compaq               | 2        | 3.17%   |
| Dell Precision          | 2        | 3.17%   |
| Dell Inspiron           | 2        | 3.17%   |
| ASUS PRIME              | 2        | 3.17%   |
| Pegatron IPPPV-D3G      | 1        | 1.59%   |
| Pegatron IPM41-D3       | 1        | 1.59%   |
| MSI MS-7C37             | 1        | 1.59%   |
| MSI MS-7B89             | 1        | 1.59%   |
| MACHINIST X99-k9        | 1        | 1.59%   |
| Intel MAHOBAY           | 1        | 1.59%   |
| Intel DN2800MT          | 1        | 1.59%   |
| HP Z240                 | 1        | 1.59%   |
| HP Slim                 | 1        | 1.59%   |
| HP Pavilion             | 1        | 1.59%   |
| HP Desktop              | 1        | 1.59%   |
| Google Panther          | 1        | 1.59%   |
| Gigabyte X570           | 1        | 1.59%   |
| Gigabyte X399           | 1        | 1.59%   |
| Gigabyte P61-USB3-B3    | 1        | 1.59%   |
| Gigabyte H81M-H         | 1        | 1.59%   |
| Gigabyte H61M-S2PV      | 1        | 1.59%   |
| Gigabyte H61M-S1        | 1        | 1.59%   |
| Gigabyte H270M-DS3H     | 1        | 1.59%   |
| Gigabyte GA-MA770T-UD3  | 1        | 1.59%   |
| Gigabyte GA-990X-Gaming | 1        | 1.59%   |
| Gigabyte G1.Sniper      | 1        | 1.59%   |
| Gigabyte B360M-D2V      | 1        | 1.59%   |
| Gigabyte A520M          | 1        | 1.59%   |
| Gigabyte 970A-D3P       | 1        | 1.59%   |
| Dell Studio             | 1        | 1.59%   |
| Biostar G41D3C          | 1        | 1.59%   |
| ASUS TUF                | 1        | 1.59%   |
| ASUS ROG                | 1        | 1.59%   |
| ASUS P5QL-ASUS-SE       | 1        | 1.59%   |
| ASUS P5KPL-VM-TWPC      | 1        | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 7        | 11.11%  |
| 2019 | 7        | 11.11%  |
| 2018 | 7        | 11.11%  |
| 2013 | 6        | 9.52%   |
| 2011 | 6        | 9.52%   |
| 2015 | 5        | 7.94%   |
| 2021 | 4        | 6.35%   |
| 2012 | 4        | 6.35%   |
| 2010 | 4        | 6.35%   |
| 2022 | 3        | 4.76%   |
| 2014 | 3        | 4.76%   |
| 2017 | 2        | 3.17%   |
| 2009 | 2        | 3.17%   |
| 2008 | 2        | 3.17%   |
| 2016 | 1        | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 63       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 98.41%  |
| Yes  | 1        | 1.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 30.16%  |
| 8.01-16.0   | 17       | 26.98%  |
| 4.01-8.0    | 15       | 23.81%  |
| 32.01-64.0  | 4        | 6.35%   |
| 2.01-3.0    | 4        | 6.35%   |
| 64.01-256.0 | 3        | 4.76%   |
| 24.01-32.0  | 1        | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 29       | 46.03%  |
| 0.51-1.0  | 18       | 28.57%  |
| 1.01-2.0  | 10       | 15.87%  |
| 2.01-3.0  | 4        | 6.35%   |
| 4.01-8.0  | 1        | 1.59%   |
| 8.01-16.0 | 1        | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 53.13%  |
| 2      | 15       | 23.44%  |
| 3      | 8        | 12.5%   |
| 5      | 3        | 4.69%   |
| 4      | 2        | 3.13%   |
| 6      | 1        | 1.56%   |
| 0      | 1        | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 68.25%  |
| Yes       | 20       | 31.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 63       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 65.63%  |
| Yes       | 22       | 34.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 71.43%  |
| Yes       | 18       | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 12       | 19.05%  |
| USA          | 11       | 17.46%  |
| Taiwan       | 5        | 7.94%   |
| Brazil       | 5        | 7.94%   |
| Spain        | 4        | 6.35%   |
| UK           | 3        | 4.76%   |
| Italy        | 3        | 4.76%   |
| Germany      | 3        | 4.76%   |
| Poland       | 2        | 3.17%   |
| Indonesia    | 2        | 3.17%   |
| France       | 2        | 3.17%   |
| Canada       | 2        | 3.17%   |
| South Africa | 1        | 1.59%   |
| Serbia       | 1        | 1.59%   |
| Portugal     | 1        | 1.59%   |
| Norway       | 1        | 1.59%   |
| Mexico       | 1        | 1.59%   |
| India        | 1        | 1.59%   |
| China        | 1        | 1.59%   |
| Bulgaria     | 1        | 1.59%   |
| Argentina    | 1        | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Aquan               | 4        | 6.15%   |
| Moscow              | 3        | 4.62%   |
| Voronezh            | 2        | 3.08%   |
| Volgograd           | 2        | 3.08%   |
| Temple              | 2        | 3.08%   |
| Saratov             | 2        | 3.08%   |
| Zhengzhou           | 1        | 1.54%   |
| Yekaterinburg       | 1        | 1.54%   |
| Winnipeg            | 1        | 1.54%   |
| Willingboro         | 1        | 1.54%   |
| Veliko Tarnovo      | 1        | 1.54%   |
| Trieste             | 1        | 1.54%   |
| Tasikmalaya         | 1        | 1.54%   |
| Surrey              | 1        | 1.54%   |
| Sumaré             | 1        | 1.54%   |
| Southminster        | 1        | 1.54%   |
| Seville             | 1        | 1.54%   |
| Salisbury           | 1        | 1.54%   |
| Rosignano Marittimo | 1        | 1.54%   |
| Richardson          | 1        | 1.54%   |
| Reinsvoll           | 1        | 1.54%   |
| Recklinghausen      | 1        | 1.54%   |
| Pieve a Nievole     | 1        | 1.54%   |
| Palembang           | 1        | 1.54%   |
| Oryol               | 1        | 1.54%   |
| Oklahoma City       | 1        | 1.54%   |
| Munich              | 1        | 1.54%   |
| Monterrey           | 1        | 1.54%   |
| Medford             | 1        | 1.54%   |
| Marcus Hook         | 1        | 1.54%   |
| Málaga             | 1        | 1.54%   |
| Londrina            | 1        | 1.54%   |
| LogroÃ±o          | 1        | 1.54%   |
| Lisbon              | 1        | 1.54%   |
| Lafayette           | 1        | 1.54%   |
| Katowice            | 1        | 1.54%   |
| Jedlicze            | 1        | 1.54%   |
| Hull                | 1        | 1.54%   |
| Guadalupe           | 1        | 1.54%   |
| Genoa               | 1        | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 16.5%   |
| WDC                 | 16       | 22     | 15.53%  |
| Samsung Electronics | 12       | 15     | 11.65%  |
| Kingston            | 9        | 9      | 8.74%   |
| Toshiba             | 8        | 8      | 7.77%   |
| Hitachi             | 8        | 8      | 7.77%   |
| Crucial             | 5        | 6      | 4.85%   |
| SanDisk             | 3        | 4      | 2.91%   |
| SPCC                | 2        | 2      | 1.94%   |
| PNY                 | 2        | 2      | 1.94%   |
| Patriot             | 2        | 2      | 1.94%   |
| A-DATA Technology   | 2        | 2      | 1.94%   |
| XrayDisk            | 1        | 1      | 0.97%   |
| SK hynix            | 1        | 1      | 0.97%   |
| Silicon Motion      | 1        | 1      | 0.97%   |
| Plextor             | 1        | 1      | 0.97%   |
| Pioneer             | 1        | 1      | 0.97%   |
| OCZ                 | 1        | 1      | 0.97%   |
| MidasForce          | 1        | 1      | 0.97%   |
| Lexar               | 1        | 2      | 0.97%   |
| LDLC                | 1        | 1      | 0.97%   |
| KingSpec            | 1        | 1      | 0.97%   |
| Intenso             | 1        | 1      | 0.97%   |
| Hewlett-Packard     | 1        | 1      | 0.97%   |
| Gigabyte Technology | 1        | 1      | 0.97%   |
| Fanxiang            | 1        | 1      | 0.97%   |
| Emtec               | 1        | 1      | 0.97%   |
| Corsair             | 1        | 1      | 0.97%   |
| China               | 1        | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Toshiba MQ01ABD050 500GB        | 2        | 1.72%   |
| Toshiba HDWD110 1TB             | 2        | 1.72%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.72%   |
| Kingston SA400S37240G 240GB     | 2        | 1.72%   |
| Hitachi HDS721616PLA380 160GB   | 2        | 1.72%   |
| XrayDisk SSD 256GB              | 1        | 0.86%   |
| WDC WDS500G2X0C-00L350 500GB    | 1        | 0.86%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.86%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 0.86%   |
| WDC WD80EFAX-68KNBN0 8TB        | 1        | 0.86%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.86%   |
| WDC WD5000LPCX-60VHAT0 500GB    | 1        | 0.86%   |
| WDC WD5000AZLX-60K2TA1 500GB    | 1        | 0.86%   |
| WDC WD5000AVVS-63H0B1 500GB     | 1        | 0.86%   |
| WDC WD5000AAKS-00YGA0 500GB     | 1        | 0.86%   |
| WDC WD3003FZEX-00Z4SA0 3TB      | 1        | 0.86%   |
| WDC WD2500BEVT-75A23T0 250GB    | 1        | 0.86%   |
| WDC WD20EZAZ-22L9GB0 2TB        | 1        | 0.86%   |
| WDC WD20EFRX-68EUZN0 2TB        | 1        | 0.86%   |
| WDC WD20EARS-00MVWB0 2TB        | 1        | 0.86%   |
| WDC WD2003FYYS-02W0B1 2TB       | 1        | 0.86%   |
| WDC WD2002FFSX-68PF8N0 2TB      | 1        | 0.86%   |
| WDC WD10JPVX-22JC3T0 1TB        | 1        | 0.86%   |
| WDC WD10EZRZ-00HTKB0 1TB        | 1        | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB        | 1        | 0.86%   |
| WDC WD10EADS-65M2BX 1TB         | 1        | 0.86%   |
| WDC WD10EACS-00D6B1 1TB         | 1        | 0.86%   |
| WDC WD1002FAEX-00Y9A0 1TB       | 1        | 0.86%   |
| Toshiba TR200 480GB             | 1        | 0.86%   |
| Toshiba Q300 240GB              | 1        | 0.86%   |
| Toshiba MK1255GSX H 120GB       | 1        | 0.86%   |
| Toshiba DT01ACA100 1TB          | 1        | 0.86%   |
| SPCC Solid State Disk 56GB      | 1        | 0.86%   |
| SPCC Solid State Disk 512GB     | 1        | 0.86%   |
| SK hynix BC711 NVMe 256GB       | 1        | 0.86%   |
| Silicon Motion NE-256 256GB     | 1        | 0.86%   |
| Seagate ST9120821AS 118GB       | 1        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB  | 1        | 0.86%   |
| Seagate ST3500418AS 500GB       | 1        | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 34%     |
| WDC                 | 15       | 19     | 30%     |
| Hitachi             | 8        | 8      | 16%     |
| Toshiba             | 6        | 6      | 12%     |
| Samsung Electronics | 3        | 3      | 6%      |
| Hewlett-Packard     | 1        | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 7      | 16.28%  |
| Samsung Electronics | 6        | 8      | 13.95%  |
| Crucial             | 4        | 5      | 9.3%    |
| SanDisk             | 3        | 4      | 6.98%   |
| Toshiba             | 2        | 2      | 4.65%   |
| SPCC                | 2        | 2      | 4.65%   |
| PNY                 | 2        | 2      | 4.65%   |
| Patriot             | 2        | 2      | 4.65%   |
| A-DATA Technology   | 2        | 2      | 4.65%   |
| XrayDisk            | 1        | 1      | 2.33%   |
| WDC                 | 1        | 1      | 2.33%   |
| Plextor             | 1        | 1      | 2.33%   |
| Pioneer             | 1        | 1      | 2.33%   |
| OCZ                 | 1        | 1      | 2.33%   |
| MidasForce          | 1        | 1      | 2.33%   |
| Lexar               | 1        | 1      | 2.33%   |
| KingSpec            | 1        | 1      | 2.33%   |
| Intenso             | 1        | 1      | 2.33%   |
| Gigabyte Technology | 1        | 1      | 2.33%   |
| Fanxiang            | 1        | 1      | 2.33%   |
| Emtec               | 1        | 1      | 2.33%   |
| China               | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 40       | 57     | 45.98%  |
| SSD  | 35       | 47     | 40.23%  |
| NVMe | 12       | 14     | 13.79%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 61       | 104    | 83.56%  |
| NVMe | 12       | 14     | 16.44%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 47       | 66     | 61.04%  |
| 0.51-1.0   | 17       | 20     | 22.08%  |
| 1.01-2.0   | 10       | 14     | 12.99%  |
| 3.01-4.0   | 1        | 1      | 1.3%    |
| 2.01-3.0   | 1        | 2      | 1.3%    |
| 4.01-10.0  | 1        | 1      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 41       | 65.08%  |
| 101-250    | 11       | 17.46%  |
| 251-500    | 7        | 11.11%  |
| 1001-2000  | 2        | 3.17%   |
| 501-1000   | 1        | 1.59%   |
| 51-100     | 1        | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 60       | 95.24%  |
| 101-250  | 2        | 3.17%   |
| 501-1000 | 1        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB      | 1        | 1      | 7.14%   |
| WDC WD5000AVVS-63H0B1 500GB       | 1        | 1      | 7.14%   |
| WDC WD10EZRZ-00HTKB0 1TB          | 1        | 1      | 7.14%   |
| WDC WD10EADS-65M2BX 1TB           | 1        | 1      | 7.14%   |
| WDC WD10EACS-00D6B1 1TB           | 1        | 1      | 7.14%   |
| Toshiba MK1255GSX H 120GB         | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 7.14%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 7.14%   |
| Pioneer APS-SL3N-240 240GB        | 1        | 1      | 7.14%   |
| OCZ VERTEX3 240GB                 | 1        | 1      | 7.14%   |
| MidasForce SSD 120GB              | 1        | 1      | 7.14%   |
| Hitachi HTS545050A7E380 500GB     | 1        | 1      | 7.14%   |
| Hitachi HTS541680J9SA00 80GB      | 1        | 1      | 7.14%   |
| Hitachi HDS721616PLA380 160GB     | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 35.71%  |
| Hitachi             | 3        | 3      | 21.43%  |
| Toshiba             | 1        | 1      | 7.14%   |
| Seagate             | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Pioneer             | 1        | 1      | 7.14%   |
| OCZ                 | 1        | 1      | 7.14%   |
| MidasForce          | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 45.45%  |
| Hitachi             | 3        | 3      | 27.27%  |
| Toshiba             | 1        | 1      | 9.09%   |
| Seagate             | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 11     | 78.57%  |
| SSD  | 3        | 3      | 21.43%  |

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
| Works    | 51       | 94     | 75%     |
| Malfunc  | 12       | 14     | 17.65%  |
| Detected | 5        | 10     | 7.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 44       | 53.01%  |
| AMD                          | 19       | 22.89%  |
| Samsung Electronics          | 3        | 3.61%   |
| JMicron Technology           | 3        | 3.61%   |
| Silicon Motion               | 2        | 2.41%   |
| SanDisk                      | 2        | 2.41%   |
| Kingston Technology Company  | 2        | 2.41%   |
| SK hynix                     | 1        | 1.2%    |
| Shenzhen Longsys Electronics | 1        | 1.2%    |
| Realtek Semiconductor        | 1        | 1.2%    |
| Phison Electronics           | 1        | 1.2%    |
| Micron/Crucial Technology    | 1        | 1.2%    |
| Marvell Technology Group     | 1        | 1.2%    |
| Lite-On IT Corp. / Plextor   | 1        | 1.2%    |
| ASMedia Technology           | 1        | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 9.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 5.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 4.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.9%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.9%    |
| Unknown                                                                                 | 2        | 1.9%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1        | 0.95%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1        | 0.95%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.95%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.95%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.95%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.95%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.95%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 1        | 0.95%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]                       | 1        | 0.95%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.95%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.95%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.95%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.95%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 48       | 58.54%  |
| IDE  | 20       | 24.39%  |
| NVMe | 13       | 15.85%  |
| RAID | 1        | 1.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 44       | 69.84%  |
| AMD    | 19       | 30.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 3.17%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 3.17%   |
| Intel Core 2 Duo                            | 2        | 3.17%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 3.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 3.17%   |
| AMD Phenom II X4 945 Processor              | 2        | 3.17%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 1.59%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1        | 1.59%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 1.59%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.59%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 1.59%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.59%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.59%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.59%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.59%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.59%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.59%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.59%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 1.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.59%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.59%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.59%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.59%   |
| Intel Core i5-8500T CPU @ 2.10GHz           | 1        | 1.59%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.59%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.59%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.59%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.59%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.59%   |
| Intel Core i3-2120 CPU                      | 1        | 1.59%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.59%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 1.59%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.59%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 1        | 1.59%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.59%   |
| Intel Celeron 2955U @ 1.40GHz               | 1        | 1.59%   |
| Intel Atom CPU N2800 @ 1.86GHz              | 1        | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 10       | 15.87%  |
| Intel Core i3           | 7        | 11.11%  |
| Intel Core i7           | 5        | 7.94%   |
| AMD Ryzen 5             | 5        | 7.94%   |
| Intel Xeon              | 4        | 6.35%   |
| Intel Pentium Dual-Core | 4        | 6.35%   |
| Intel Celeron           | 4        | 6.35%   |
| Intel Core 2 Duo        | 3        | 4.76%   |
| AMD Phenom II X4        | 3        | 4.76%   |
| Other                   | 2        | 3.17%   |
| Intel Atom              | 2        | 3.17%   |
| AMD Ryzen 3             | 2        | 3.17%   |
| AMD FX                  | 2        | 3.17%   |
| Intel Pentium Silver    | 1        | 1.59%   |
| Intel Pentium           | 1        | 1.59%   |
| Intel Core 2 Quad       | 1        | 1.59%   |
| Intel Core 2            | 1        | 1.59%   |
| AMD Ryzen Threadripper  | 1        | 1.59%   |
| AMD Ryzen 9             | 1        | 1.59%   |
| AMD Ryzen 7             | 1        | 1.59%   |
| AMD Ryzen 5 PRO         | 1        | 1.59%   |
| AMD Athlon II X4        | 1        | 1.59%   |
| AMD A10                 | 1        | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 22       | 34.92%  |
| 2       | 17       | 26.98%  |
| 6       | 7        | 11.11%  |
| 8       | 5        | 7.94%   |
| 12      | 4        | 6.35%   |
| Unknown | 3        | 4.76%   |
| 16      | 2        | 3.17%   |
| 24      | 1        | 1.59%   |
| 10      | 1        | 1.59%   |
| 1       | 1        | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 46       | 73.02%  |
| 2       | 14       | 22.22%  |
| Unknown | 3        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 8        | 12.7%   |
| Haswell       | 8        | 12.7%   |
| Penryn        | 7        | 11.11%  |
| SandyBridge   | 4        | 6.35%   |
| K10           | 4        | 6.35%   |
| Zen+          | 3        | 4.76%   |
| Zen 2         | 3        | 4.76%   |
| Zen           | 3        | 4.76%   |
| Skylake       | 3        | 4.76%   |
| IvyBridge     | 3        | 4.76%   |
| Core          | 3        | 4.76%   |
| Zen 3         | 2        | 3.17%   |
| Silvermont    | 2        | 3.17%   |
| Piledriver    | 2        | 3.17%   |
| Bonnell       | 2        | 3.17%   |
| Unknown       | 2        | 3.17%   |
| Goldmont plus | 1        | 1.59%   |
| Excavator     | 1        | 1.59%   |
| CometLake     | 1        | 1.59%   |
| Broadwell     | 1        | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 26       | 40%     |
| Intel  | 23       | 35.38%  |
| AMD    | 16       | 24.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 4.62%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 3.08%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 3.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.08%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 3.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 3.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 3.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 3.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.54%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.54%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.54%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.54%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1.54%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.54%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.54%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.54%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 1.54%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.54%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.54%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.54%   |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1        | 1.54%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 1.54%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.54%   |
| Intel HD Graphics 630                                                       | 1        | 1.54%   |
| Intel HD Graphics 530                                                       | 1        | 1.54%   |
| Intel HD Graphics 510                                                       | 1        | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.54%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 26       | 41.27%  |
| 1 x Intel   | 19       | 30.16%  |
| 1 x AMD     | 14       | 22.22%  |
| 2 x Intel   | 2        | 3.17%   |
| Intel + AMD | 2        | 3.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 40       | 63.49%  |
| Proprietary | 19       | 30.16%  |
| Unknown     | 4        | 6.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 50.79%  |
| 1.01-2.0   | 9        | 14.29%  |
| 5.01-6.0   | 5        | 7.94%   |
| 3.01-4.0   | 5        | 7.94%   |
| 0.51-1.0   | 5        | 7.94%   |
| 0.01-0.5   | 4        | 6.35%   |
| 7.01-8.0   | 3        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 8        | 17.78%  |
| Samsung Electronics | 6        | 13.33%  |
| Hewlett-Packard     | 5        | 11.11%  |
| Dell                | 5        | 11.11%  |
| Acer                | 5        | 11.11%  |
| MSI                 | 3        | 6.67%   |
| Philips             | 2        | 4.44%   |
| AOC                 | 2        | 4.44%   |
| Vizio               | 1        | 2.22%   |
| ViewSonic           | 1        | 2.22%   |
| Toshiba             | 1        | 2.22%   |
| NEC Computers       | 1        | 2.22%   |
| Insignia            | 1        | 2.22%   |
| Iiyama              | 1        | 2.22%   |
| CHD                 | 1        | 2.22%   |
| BenQ                | 1        | 2.22%   |
| ASUSTek Computer    | 1        | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2        | 4.26%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch           | 2        | 4.26%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2        | 4.26%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1        | 2.13%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch            | 1        | 2.13%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1        | 2.13%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1        | 2.13%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1        | 2.13%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch     | 1        | 2.13%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1        | 2.13%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1        | 2.13%   |
| Philips LCD Monitor PHL0868 1680x1050 470x290mm 21.7-inch             | 1        | 2.13%   |
| NEC Computers LCD175VXM+ NEC66C0 1280x1024 340x270mm 17.1-inch        | 1        | 2.13%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1        | 2.13%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1        | 2.13%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 2.13%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 2.13%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x290mm 23.1-inch          | 1        | 2.13%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1        | 2.13%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 1        | 2.13%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch             | 1        | 2.13%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                   | 1        | 2.13%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1        | 2.13%   |
| Goldstar LG HDR WFHD GSM5BA0 2560x1080 800x340mm 34.2-inch            | 1        | 2.13%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1        | 2.13%   |
| Goldstar E2240 GSM57A4 1920x1080 480x270mm 21.7-inch                  | 1        | 2.13%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1        | 2.13%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1        | 2.13%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1        | 2.13%   |
| Dell LCD Monitor LNK0001 1920x1080 300x230mm 14.9-inch                | 1        | 2.13%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1        | 2.13%   |
| Dell E2216HV DELF06F 1920x1080 480x270mm 21.7-inch                    | 1        | 2.13%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 1        | 2.13%   |
| CHD LCD Monitor CHD0320 2560x1440 700x390mm 31.5-inch                 | 1        | 2.13%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                     | 1        | 2.13%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 520x290mm 23.4-inch          | 1        | 2.13%   |
| AOC Q2577W AOC2577 2560x1440 550x310mm 24.9-inch                      | 1        | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 64.44%  |
| 2560x1440 (QHD)    | 3        | 6.67%   |
| 2560x1080          | 3        | 6.67%   |
| 1680x1050 (WSXGA+) | 3        | 6.67%   |
| 3440x1440          | 2        | 4.44%   |
| 1280x1024 (SXGA)   | 2        | 4.44%   |
| 1600x900 (HD+)     | 1        | 2.22%   |
| 1440x900 (WXGA+)   | 1        | 2.22%   |
| 1366x768 (WXGA)    | 1        | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 8        | 17.02%  |
| 31      | 6        | 12.77%  |
| 24      | 6        | 12.77%  |
| 23      | 6        | 12.77%  |
| 27      | 5        | 10.64%  |
| 34      | 4        | 8.51%   |
| 19      | 3        | 6.38%   |
| Unknown | 2        | 4.26%   |
| 50      | 1        | 2.13%   |
| 41      | 1        | 2.13%   |
| 33      | 1        | 2.13%   |
| 22      | 1        | 2.13%   |
| 18      | 1        | 2.13%   |
| 17      | 1        | 2.13%   |
| 14      | 1        | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 36.17%  |
| 401-500     | 12       | 25.53%  |
| 601-700     | 6        | 12.77%  |
| 701-800     | 5        | 10.64%  |
| Unknown     | 2        | 4.26%   |
| 351-400     | 1        | 2.13%   |
| 301-350     | 1        | 2.13%   |
| 201-300     | 1        | 2.13%   |
| 1001-1500   | 1        | 2.13%   |
| 901-1000    | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 33       | 73.33%  |
| 21/9  | 5        | 11.11%  |
| 16/10 | 4        | 8.89%   |
| 5/4   | 2        | 4.44%   |
| 4/3   | 1        | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 40.43%  |
| 351-500        | 11       | 23.4%   |
| 301-350        | 5        | 10.64%  |
| 151-200        | 3        | 6.38%   |
| 251-300        | 2        | 4.26%   |
| 141-150        | 2        | 4.26%   |
| Unknown        | 2        | 4.26%   |
| More than 1000 | 1        | 2.13%   |
| 101-110        | 1        | 2.13%   |
| 501-1000       | 1        | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 67.39%  |
| 101-120 | 11       | 23.91%  |
| Unknown | 2        | 4.35%   |
| 1-50    | 1        | 2.17%   |
| 121-160 | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 74.6%   |
| 0     | 13       | 20.63%  |
| 2     | 3        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 40       | 49.38%  |
| Intel                 | 24       | 29.63%  |
| Qualcomm Atheros      | 8        | 9.88%   |
| TP-Link               | 2        | 2.47%   |
| Ralink Technology     | 2        | 2.47%   |
| OPPO Electronics      | 1        | 1.23%   |
| IMC Networks          | 1        | 1.23%   |
| Edimax Technology     | 1        | 1.23%   |
| Broadcom              | 1        | 1.23%   |
| ASUSTek Computer      | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 37       | 41.57%  |
| Intel Ethernet Connection I217-LM                                           | 4        | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 3        | 3.37%   |
| Intel 82574L Gigabit Network Connection                                     | 3        | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 2.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2        | 2.25%   |
| Ralink RT5370 Wireless Adapter                                              | 2        | 2.25%   |
| Intel Wireless 8265 / 8275                                                  | 2        | 2.25%   |
| Intel Wi-Fi 6 AX200                                                         | 2        | 2.25%   |
| Intel I211 Gigabit Network Connection                                       | 2        | 2.25%   |
| Intel Ethernet Connection (7) I219-V                                        | 2        | 2.25%   |
| Intel Ethernet Connection (2) I219-LM                                       | 2        | 2.25%   |
| Intel 82567LM-3 Gigabit Network Connection                                  | 2        | 2.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1        | 1.12%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1        | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1        | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                   | 1        | 1.12%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                               | 1        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1        | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                       | 1        | 1.12%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                              | 1        | 1.12%   |
| Intel Ethernet Controller I225-V                                            | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                        | 1        | 1.12%   |
| Intel Ethernet Connection (2) I218-V                                        | 1        | 1.12%   |
| Intel Ethernet Connection (11) I219-LM                                      | 1        | 1.12%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 1.12%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 1.12%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 1.12%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 30.43%  |
| Qualcomm Atheros      | 4        | 17.39%  |
| Intel                 | 4        | 17.39%  |
| TP-Link               | 2        | 8.7%    |
| Ralink Technology     | 2        | 8.7%    |
| IMC Networks          | 1        | 4.35%   |
| Edimax Technology     | 1        | 4.35%   |
| Broadcom              | 1        | 4.35%   |
| ASUSTek Computer      | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 8.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2        | 8.7%    |
| Ralink RT5370 Wireless Adapter                                              | 2        | 8.7%    |
| Intel Wireless 8265 / 8275                                                  | 2        | 8.7%    |
| Intel Wi-Fi 6 AX200                                                         | 2        | 8.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1        | 4.35%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 4.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 4.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 4.35%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 4.35%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 4.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 4.35%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 59.38%  |
| Intel                 | 21       | 32.81%  |
| Qualcomm Atheros      | 4        | 6.25%   |
| OPPO Electronics      | 1        | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37       | 56.06%  |
| Intel Ethernet Connection I217-LM                                 | 4        | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.55%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 2        | 3.03%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.52%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 1.52%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.52%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.52%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 75%     |
| WiFi     | 21       | 25%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 93.44%  |
| WiFi     | 4        | 6.56%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 74.6%   |
| 2     | 16       | 25.4%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 98.41%  |
| Yes  | 1        | 1.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 7        | 38.89%  |
| Intel                      | 4        | 22.22%  |
| Realtek Semiconductor      | 3        | 16.67%  |
| Integrated System Solution | 1        | 5.56%   |
| IMC Networks               | 1        | 5.56%   |
| Bluetooth Device           | 1        | 5.56%   |
| Apple                      | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 7        | 38.89%  |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 11.11%  |
| Intel Bluetooth wireless interface                       | 2        | 11.11%  |
| Intel AX200 Bluetooth                                    | 2        | 11.11%  |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1        | 5.56%   |
| Integrated System Solution Bluetooth Device              | 1        | 5.56%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS  | 1        | 5.56%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1        | 5.56%   |
| Apple Apple Broadcom Built-in Bluetooth                  | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 42       | 42%     |
| Nvidia              | 23       | 23%     |
| AMD                 | 23       | 23%     |
| C-Media Electronics | 4        | 4%      |
| Logitech            | 2        | 2%      |
| Google              | 2        | 2%      |
| Yamaha              | 1        | 1%      |
| Texas Instruments   | 1        | 1%      |
| RME                 | 1        | 1%      |
| Creative Technology | 1        | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 6.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 5.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 5.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 4.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 4.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 3.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.59%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 2.59%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 2.59%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.72%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.72%   |
| Logitech HD Webcam C510                                                    | 2        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 1.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.72%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 1.72%   |
| Google Pixel earbuds                                                       | 2        | 1.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.72%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.72%   |
| Yamaha Steinberg UR22mkII                                                  | 1        | 0.86%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1        | 0.86%   |
| RME Babyface Pro (Class Compliant Mode)                                    | 1        | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.86%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.86%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.86%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 17.28%  |
| Kingston            | 13       | 16.05%  |
| SK hynix            | 9        | 11.11%  |
| Samsung Electronics | 9        | 11.11%  |
| Crucial             | 8        | 9.88%   |
| Micron Technology   | 7        | 8.64%   |
| Unknown             | 5        | 6.17%   |
| Transcend           | 3        | 3.7%    |
| Ramaxel Technology  | 2        | 2.47%   |
| GOODRAM             | 2        | 2.47%   |
| G.Skill             | 2        | 2.47%   |
| Corsair             | 2        | 2.47%   |
| Team                | 1        | 1.23%   |
| Patriot             | 1        | 1.23%   |
| Nanya Technology    | 1        | 1.23%   |
| GLOWAY              | 1        | 1.23%   |
| A-DATA Technology   | 1        | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown                                               | 5        | 5.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 4        | 4.4%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 2        | 2.2%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 2        | 2.2%    |
| Unknown RAM Module 1GB DIMM SDRAM                     | 2        | 2.2%    |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s     | 2        | 2.2%    |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s  | 2        | 2.2%    |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s  | 2        | 2.2%    |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s  | 2        | 2.2%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM SDRAM                     | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 1.1%    |
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 1.1%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 1        | 1.1%    |
| Unknown RAM Module 2GB DIMM DDR2                      | 1        | 1.1%    |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s  | 1        | 1.1%    |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s     | 1        | 1.1%    |
| Team RAM Elite-13 4GB DIMM DDR3 667MT/s               | 1        | 1.1%    |
| Team RAM Elite-1 2GB DIMM DDR3 667MT/s                | 1        | 1.1%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s          | 1        | 1.1%    |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s            | 1        | 1.1%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s  | 1        | 1.1%    |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 1.1%    |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s  | 1        | 1.1%    |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s  | 1        | 1.1%    |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB RIMM DDR4 2133MT/s | 1        | 1.1%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s           | 1        | 1.1%    |
| Samsung RAM Module 8GB DIMM DDR3 1333MT/s             | 1        | 1.1%    |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 1.1%    |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s             | 1        | 1.1%    |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s             | 1        | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 1.1%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s   | 1        | 1.1%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s   | 1        | 1.1%    |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2133MT/s   | 1        | 1.1%    |
| Ramaxel RAM RMT3170ME68F9F1600 4GB DIMM DDR3 1600MT/s | 1        | 1.1%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB DIMM DDR3 1600MT/s | 1        | 1.1%    |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 3200MT/s       | 1        | 1.1%    |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s    | 1        | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 28       | 44.44%  |
| DDR3    | 23       | 36.51%  |
| DDR2    | 6        | 9.52%   |
| SDRAM   | 3        | 4.76%   |
| Unknown | 3        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 56       | 88.89%  |
| SODIMM | 6        | 9.52%   |
| RIMM   | 1        | 1.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 33.75%  |
| 4096  | 26       | 32.5%   |
| 2048  | 17       | 21.25%  |
| 16384 | 8        | 10%     |
| 1024  | 2        | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 12       | 18.18%  |
| 1600    | 10       | 15.15%  |
| 3200    | 8        | 12.12%  |
| 2400    | 6        | 9.09%   |
| 2133    | 6        | 9.09%   |
| 800     | 6        | 9.09%   |
| 2667    | 5        | 7.58%   |
| 2666    | 4        | 6.06%   |
| Unknown | 4        | 6.06%   |
| 2933    | 2        | 3.03%   |
| 1866    | 1        | 1.52%   |
| 1066    | 1        | 1.52%   |
| 667     | 1        | 1.52%   |

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
| 1     | 28       | 44.44%  |
| 0     | 28       | 44.44%  |
| 2     | 6        | 9.52%   |
| 3     | 1        | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 29       | 69.05%  |
| Net/wireless             | 9        | 21.43%  |
| Bluetooth                | 2        | 4.76%   |
| Sound                    | 1        | 2.38%   |
| Card reader              | 1        | 2.38%   |

