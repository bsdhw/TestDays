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

Total: 51

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 45       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 45       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 45       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 45       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 36       | 78.26%  |
| en    | 5        | 10.87%  |
| zh_TW | 1        | 2.17%   |
| ru    | 1        | 2.17%   |
| pt    | 1        | 2.17%   |
| fr    | 1        | 2.17%   |
| es    | 1        | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 44       | 97.78%  |
| BIOS | 1        | 2.22%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 30       | 65.22%  |
| Zfs    | 16       | 34.78%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 44       | 97.78%  |
| MBR  | 1        | 2.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 20%     |
| Gigabyte Technology | 7        | 15.56%  |
| Dell                | 7        | 15.56%  |
| Hewlett-Packard     | 5        | 11.11%  |
| MSI                 | 4        | 8.89%   |
| Lenovo              | 3        | 6.67%   |
| ASRock              | 3        | 6.67%   |
| Pegatron            | 2        | 4.44%   |
| Intel               | 2        | 4.44%   |
| MACHINIST           | 1        | 2.22%   |
| Biostar             | 1        | 2.22%   |
| AMD                 | 1        | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7A38                         | 2        | 4.44%   |
| Pegatron IPPPV-D3G                  | 1        | 2.22%   |
| Pegatron IPM41-D3                   | 1        | 2.22%   |
| MSI MS-7C37                         | 1        | 2.22%   |
| MSI MS-7B89                         | 1        | 2.22%   |
| MACHINIST X99-k9 V2.0               | 1        | 2.22%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK  | 1        | 2.22%   |
| Lenovo ThinkCentre M910s 10MK0039US | 1        | 2.22%   |
| Lenovo ThinkCentre M700 10GS        | 1        | 2.22%   |
| Intel MAHOBAY                       | 1        | 2.22%   |
| Intel DN2800MT AAG23738-600         | 1        | 2.22%   |
| HP Slim Desktop S01-aF1xxx          | 1        | 2.22%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 2.22%   |
| HP EliteDesk 800 G1 SFF             | 1        | 2.22%   |
| HP EliteDesk 700 G1 SFF             | 1        | 2.22%   |
| HP Desktop Pro A G3                 | 1        | 2.22%   |
| Gigabyte X399 AORUS Gaming 7        | 1        | 2.22%   |
| Gigabyte P61-USB3-B3                | 1        | 2.22%   |
| Gigabyte H81M-H                     | 1        | 2.22%   |
| Gigabyte H61M-S1                    | 1        | 2.22%   |
| Gigabyte H270M-DS3H                 | 1        | 2.22%   |
| Gigabyte G1.Sniper A88X-CF          | 1        | 2.22%   |
| Gigabyte 970A-D3P                   | 1        | 2.22%   |
| Dell Studio 540                     | 1        | 2.22%   |
| Dell Precision Tower 5810           | 1        | 2.22%   |
| Dell Precision 3440                 | 1        | 2.22%   |
| Dell OptiPlex 3060                  | 1        | 2.22%   |
| Dell OptiPlex 3010                  | 1        | 2.22%   |
| Dell Inspiron 3891                  | 1        | 2.22%   |
| Dell Inspiron 3656                  | 1        | 2.22%   |
| Biostar G41D3C                      | 1        | 2.22%   |
| ASUS TUF GAMING X570-PLUS           | 1        | 2.22%   |
| ASUS ROG STRIX B550-I GAMING        | 1        | 2.22%   |
| ASUS PRIME Z390M-PLUS               | 1        | 2.22%   |
| ASUS P5QL-ASUS-SE                   | 1        | 2.22%   |
| ASUS P5KPL-VM-TWPC                  | 1        | 2.22%   |
| ASUS P5KPL-AM SE                    | 1        | 2.22%   |
| ASUS K30AM-J                        | 1        | 2.22%   |
| ASUS CM1530                         | 1        | 2.22%   |
| ASUS All Series                     | 1        | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| Lenovo ThinkCentre        | 3        | 6.67%   |
| MSI MS-7A38               | 2        | 4.44%   |
| HP EliteDesk              | 2        | 4.44%   |
| Dell Precision            | 2        | 4.44%   |
| Dell OptiPlex             | 2        | 4.44%   |
| Dell Inspiron             | 2        | 4.44%   |
| Pegatron IPPPV-D3G        | 1        | 2.22%   |
| Pegatron IPM41-D3         | 1        | 2.22%   |
| MSI MS-7C37               | 1        | 2.22%   |
| MSI MS-7B89               | 1        | 2.22%   |
| MACHINIST X99-k9          | 1        | 2.22%   |
| Intel MAHOBAY             | 1        | 2.22%   |
| Intel DN2800MT            | 1        | 2.22%   |
| HP Slim                   | 1        | 2.22%   |
| HP Pavilion               | 1        | 2.22%   |
| HP Desktop                | 1        | 2.22%   |
| Gigabyte X399             | 1        | 2.22%   |
| Gigabyte P61-USB3-B3      | 1        | 2.22%   |
| Gigabyte H81M-H           | 1        | 2.22%   |
| Gigabyte H61M-S1          | 1        | 2.22%   |
| Gigabyte H270M-DS3H       | 1        | 2.22%   |
| Gigabyte G1.Sniper        | 1        | 2.22%   |
| Gigabyte 970A-D3P         | 1        | 2.22%   |
| Dell Studio               | 1        | 2.22%   |
| Biostar G41D3C            | 1        | 2.22%   |
| ASUS TUF                  | 1        | 2.22%   |
| ASUS ROG                  | 1        | 2.22%   |
| ASUS PRIME                | 1        | 2.22%   |
| ASUS P5QL-ASUS-SE         | 1        | 2.22%   |
| ASUS P5KPL-VM-TWPC        | 1        | 2.22%   |
| ASUS P5KPL-AM             | 1        | 2.22%   |
| ASUS K30AM-J              | 1        | 2.22%   |
| ASUS CM1530               | 1        | 2.22%   |
| ASUS All                  | 1        | 2.22%   |
| ASRock G41C-VS            | 1        | 2.22%   |
| ASRock ConRoeXFire-eSATA2 | 1        | 2.22%   |
| ASRock B365M              | 1        | 2.22%   |
| AMD X64                   | 1        | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 5        | 11.11%  |
| 2021 | 4        | 8.89%   |
| 2020 | 4        | 8.89%   |
| 2018 | 4        | 8.89%   |
| 2015 | 4        | 8.89%   |
| 2013 | 4        | 8.89%   |
| 2010 | 4        | 8.89%   |
| 2022 | 3        | 6.67%   |
| 2014 | 3        | 6.67%   |
| 2011 | 3        | 6.67%   |
| 2012 | 2        | 4.44%   |
| 2009 | 2        | 4.44%   |
| 2008 | 2        | 4.44%   |
| 2017 | 1        | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 45       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 15       | 33.33%  |
| 4.01-8.0    | 11       | 24.44%  |
| 8.01-16.0   | 10       | 22.22%  |
| 32.01-64.0  | 3        | 6.67%   |
| 2.01-3.0    | 3        | 6.67%   |
| 64.01-256.0 | 2        | 4.44%   |
| 24.01-32.0  | 1        | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 17       | 37.78%  |
| 0.51-1.0 | 16       | 35.56%  |
| 1.01-2.0 | 8        | 17.78%  |
| 2.01-3.0 | 3        | 6.67%   |
| 4.01-8.0 | 1        | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 52.17%  |
| 2      | 11       | 23.91%  |
| 3      | 6        | 13.04%  |
| 5      | 2        | 4.35%   |
| 6      | 1        | 2.17%   |
| 4      | 1        | 2.17%   |
| 0      | 1        | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 68.89%  |
| Yes       | 14       | 31.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 65.22%  |
| Yes       | 16       | 34.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 75.56%  |
| Yes       | 11       | 24.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 9        | 20%     |
| Russia       | 6        | 13.33%  |
| Taiwan       | 5        | 11.11%  |
| Brazil       | 4        | 8.89%   |
| Spain        | 3        | 6.67%   |
| UK           | 2        | 4.44%   |
| Poland       | 2        | 4.44%   |
| Italy        | 2        | 4.44%   |
| France       | 2        | 4.44%   |
| Canada       | 2        | 4.44%   |
| South Africa | 1        | 2.22%   |
| Serbia       | 1        | 2.22%   |
| Norway       | 1        | 2.22%   |
| Mexico       | 1        | 2.22%   |
| India        | 1        | 2.22%   |
| Germany      | 1        | 2.22%   |
| China        | 1        | 2.22%   |
| Argentina    | 1        | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Aquan               | 4        | 8.51%   |
| Volgograd           | 2        | 4.26%   |
| Temple              | 2        | 4.26%   |
| Moscow              | 2        | 4.26%   |
| Zhengzhou           | 1        | 2.13%   |
| Yekaterinburg       | 1        | 2.13%   |
| Winnipeg            | 1        | 2.13%   |
| Willingboro         | 1        | 2.13%   |
| Voronezh            | 1        | 2.13%   |
| Trieste             | 1        | 2.13%   |
| Surrey              | 1        | 2.13%   |
| Southminster        | 1        | 2.13%   |
| Seville             | 1        | 2.13%   |
| Salisbury           | 1        | 2.13%   |
| Rosignano Marittimo | 1        | 2.13%   |
| Richardson          | 1        | 2.13%   |
| Reinsvoll           | 1        | 2.13%   |
| Pieve a Nievole     | 1        | 2.13%   |
| Munich              | 1        | 2.13%   |
| Monterrey           | 1        | 2.13%   |
| Medford             | 1        | 2.13%   |
| Londrina            | 1        | 2.13%   |
| LogroÃ±o          | 1        | 2.13%   |
| Lafayette           | 1        | 2.13%   |
| Katowice            | 1        | 2.13%   |
| Jedlicze            | 1        | 2.13%   |
| Guadalupe           | 1        | 2.13%   |
| Escondido           | 1        | 2.13%   |
| Dayuan              | 1        | 2.13%   |
| Curitiba            | 1        | 2.13%   |
| Cournon-d'Auvergne  | 1        | 2.13%   |
| Chennai             | 1        | 2.13%   |
| Chatou              | 1        | 2.13%   |
| Buenos Aires        | 1        | 2.13%   |
| Brasília           | 1        | 2.13%   |
| Blumenau            | 1        | 2.13%   |
| Bloemfontein        | 1        | 2.13%   |
| Belgrade            | 1        | 2.13%   |
| Beighton            | 1        | 2.13%   |
| Austin              | 1        | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 15     | 16.22%  |
| WDC                 | 10       | 13     | 13.51%  |
| Samsung Electronics | 9        | 11     | 12.16%  |
| Kingston            | 7        | 7      | 9.46%   |
| Hitachi             | 7        | 7      | 9.46%   |
| Toshiba             | 5        | 5      | 6.76%   |
| Crucial             | 3        | 4      | 4.05%   |
| SPCC                | 2        | 2      | 2.7%    |
| SanDisk             | 2        | 3      | 2.7%    |
| PNY                 | 2        | 2      | 2.7%    |
| Patriot             | 2        | 2      | 2.7%    |
| XrayDisk            | 1        | 1      | 1.35%   |
| SK hynix            | 1        | 1      | 1.35%   |
| Silicon Motion      | 1        | 1      | 1.35%   |
| OCZ                 | 1        | 1      | 1.35%   |
| Lexar               | 1        | 2      | 1.35%   |
| LDLC                | 1        | 1      | 1.35%   |
| KingSpec            | 1        | 1      | 1.35%   |
| Intenso             | 1        | 1      | 1.35%   |
| Hewlett-Packard     | 1        | 1      | 1.35%   |
| Gigabyte Technology | 1        | 1      | 1.35%   |
| Emtec               | 1        | 1      | 1.35%   |
| Corsair             | 1        | 1      | 1.35%   |
| A-DATA Technology   | 1        | 1      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Toshiba MQ01ABD050 500GB        | 2        | 2.41%   |
| Hitachi HDS721616PLA380 160GB   | 2        | 2.41%   |
| XrayDisk SSD 256GB              | 1        | 1.2%    |
| WDC WDS500G2X0C-00L350 500GB    | 1        | 1.2%    |
| WDC WDS500G2B0A 500GB           | 1        | 1.2%    |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 1.2%    |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 1.2%    |
| WDC WD5000AZLX-60K2TA1 500GB    | 1        | 1.2%    |
| WDC WD5000AVVS-63H0B1 500GB     | 1        | 1.2%    |
| WDC WD5000AAKS-00YGA0 500GB     | 1        | 1.2%    |
| WDC WD3003FZEX-00Z4SA0 3TB      | 1        | 1.2%    |
| WDC WD2500BEVT-75A23T0 250GB    | 1        | 1.2%    |
| WDC WD20EZAZ-22L9GB0 2TB        | 1        | 1.2%    |
| WDC WD20EFRX-68EUZN0 2TB        | 1        | 1.2%    |
| WDC WD10JPVX-22JC3T0 1TB        | 1        | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB        | 1        | 1.2%    |
| Toshiba TR200 480GB             | 1        | 1.2%    |
| Toshiba Q300 240GB              | 1        | 1.2%    |
| Toshiba DT01ACA100 1TB          | 1        | 1.2%    |
| SPCC Solid State Disk 56GB      | 1        | 1.2%    |
| SPCC Solid State Disk 512GB     | 1        | 1.2%    |
| SK hynix BC711 NVMe 256GB       | 1        | 1.2%    |
| Silicon Motion NE-256 256GB     | 1        | 1.2%    |
| Seagate ST9120821AS 118GB       | 1        | 1.2%    |
| Seagate ST500DM002-1BD142 500GB | 1        | 1.2%    |
| Seagate ST4000DM004-2CV104 4TB  | 1        | 1.2%    |
| Seagate ST3250310AS 250GB       | 1        | 1.2%    |
| Seagate ST3160811AS 160GB       | 1        | 1.2%    |
| Seagate ST3000DM001-1CH166 3TB  | 1        | 1.2%    |
| Seagate ST250LT003-9YG14C 250GB | 1        | 1.2%    |
| Seagate ST2000LX001-1RG174 2TB  | 1        | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB  | 1        | 1.2%    |
| Seagate ST2000DL003-9VT166 2TB  | 1        | 1.2%    |
| Seagate ST1000VX001-1Z4102 1TB  | 1        | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB  | 1        | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB  | 1        | 1.2%    |
| Seagate ST1000DM003-9YN162 1TB  | 1        | 1.2%    |
| Seagate ST1000DM003-1ER162 1TB  | 1        | 1.2%    |
| SanDisk SDSA5GK-016G-1006 16GB  | 1        | 1.2%    |
| SanDisk SD8SN8U-128G-1006 128GB | 1        | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 15     | 35.29%  |
| WDC                 | 9        | 10     | 26.47%  |
| Hitachi             | 7        | 7      | 20.59%  |
| Toshiba             | 3        | 3      | 8.82%   |
| Samsung Electronics | 2        | 2      | 5.88%   |
| Hewlett-Packard     | 1        | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 16.67%  |
| Samsung Electronics | 4        | 5      | 13.33%  |
| Toshiba             | 2        | 2      | 6.67%   |
| SPCC                | 2        | 2      | 6.67%   |
| SanDisk             | 2        | 3      | 6.67%   |
| PNY                 | 2        | 2      | 6.67%   |
| Patriot             | 2        | 2      | 6.67%   |
| Crucial             | 2        | 3      | 6.67%   |
| XrayDisk            | 1        | 1      | 3.33%   |
| WDC                 | 1        | 1      | 3.33%   |
| OCZ                 | 1        | 1      | 3.33%   |
| Lexar               | 1        | 1      | 3.33%   |
| KingSpec            | 1        | 1      | 3.33%   |
| Intenso             | 1        | 1      | 3.33%   |
| Gigabyte Technology | 1        | 1      | 3.33%   |
| Emtec               | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 38     | 44.44%  |
| SSD  | 23       | 33     | 36.51%  |
| NVMe | 12       | 14     | 19.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 43       | 71     | 78.18%  |
| NVMe | 12       | 14     | 21.82%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 48     | 63.46%  |
| 0.51-1.0   | 11       | 13     | 21.15%  |
| 1.01-2.0   | 6        | 7      | 11.54%  |
| 3.01-4.0   | 1        | 1      | 1.92%   |
| 2.01-3.0   | 1        | 2      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 27       | 60%     |
| 101-250    | 8        | 17.78%  |
| 251-500    | 6        | 13.33%  |
| 1001-2000  | 2        | 4.44%   |
| 501-1000   | 1        | 2.22%   |
| 51-100     | 1        | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 42       | 93.33%  |
| 101-250  | 2        | 4.44%   |
| 501-1000 | 1        | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63H0B1 500GB       | 1        | 1      | 14.29%  |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 14.29%  |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 14.29%  |
| OCZ VERTEX3 240GB                 | 1        | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB     | 1        | 1      | 14.29%  |
| Hitachi HTS541680J9SA00 80GB      | 1        | 1      | 14.29%  |
| Hitachi HDS721616PLA380 160GB     | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 3        | 3      | 42.86%  |
| WDC                 | 1        | 1      | 14.29%  |
| Seagate             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| OCZ                 | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 3        | 3      | 50%     |
| WDC                 | 1        | 1      | 16.67%  |
| Seagate             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 6      | 85.71%  |
| SSD  | 1        | 1      | 14.29%  |

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
| Works    | 38       | 72     | 80.85%  |
| Malfunc  | 6        | 7      | 12.77%  |
| Detected | 3        | 6      | 6.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 32       | 51.61%  |
| AMD                          | 13       | 20.97%  |
| Samsung Electronics          | 3        | 4.84%   |
| Silicon Motion               | 2        | 3.23%   |
| SanDisk                      | 2        | 3.23%   |
| Kingston Technology Company  | 2        | 3.23%   |
| JMicron Technology           | 2        | 3.23%   |
| SK hynix                     | 1        | 1.61%   |
| Shenzhen Longsys Electronics | 1        | 1.61%   |
| Phison Electronics           | 1        | 1.61%   |
| Micron/Crucial Technology    | 1        | 1.61%   |
| Marvell Technology Group     | 1        | 1.61%   |
| ASMedia Technology           | 1        | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 10.26%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 6.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 6.41%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 3.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 3.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 2.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 2.56%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 2.56%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1        | 1.28%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1        | 1.28%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 1.28%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.28%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.28%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.28%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.28%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 1        | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.28%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.28%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.28%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 1.28%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.28%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.28%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 54.1%   |
| IDE  | 15       | 24.59%  |
| NVMe | 12       | 19.67%  |
| RAID | 1        | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 32       | 71.11%  |
| AMD    | 13       | 28.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz                | 2        | 4.44%   |
| Intel Xeon CPU E5462 @ 2.80GHz                  | 1        | 2.22%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz            | 1        | 2.22%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz             | 1        | 2.22%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz        | 1        | 2.22%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz     | 1        | 2.22%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 2.22%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 2.22%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 2.22%   |
| Intel Pentium CPU G4400 @ 3.30GHz               | 1        | 2.22%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 2.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 2.22%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 2.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 2.22%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 2.22%   |
| Intel Core i5-8500T CPU @ 2.10GHz               | 1        | 2.22%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 2.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 2.22%   |
| Intel Core i5-4570T CPU @ 2.90GHz               | 1        | 2.22%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 2.22%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 2.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 2.22%   |
| Intel Core i3-2120 CPU                          | 1        | 2.22%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 2.22%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 2.22%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1        | 2.22%   |
| Intel Core 2 CPU 6600 @ 2.40GHz                 | 1        | 2.22%   |
| Intel Celeron CPU J1800 @ 2.41GHz               | 1        | 2.22%   |
| Intel Atom CPU N2800 @ 1.86GHz                  | 1        | 2.22%   |
| Intel Atom CPU D425 @ 1.80GHz                   | 1        | 2.22%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 1        | 2.22%   |
| AMD Ryzen Threadripper 1900X 8-Core Processor   | 1        | 2.22%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 2.22%   |
| AMD Ryzen 5 PRO 3400G with Radeon Vega Graphics | 1        | 2.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 2.22%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 1        | 2.22%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.22%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 2.22%   |
| AMD Ryzen 3 2200GE with Radeon Vega Graphics    | 1        | 2.22%   |
| AMD RX-8120 Processor                           | 1        | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 15.56%  |
| Intel Core i3           | 5        | 11.11%  |
| Intel Pentium Dual-Core | 4        | 8.89%   |
| Intel Core i7           | 4        | 8.89%   |
| AMD Ryzen 5             | 4        | 8.89%   |
| Intel Xeon              | 3        | 6.67%   |
| Other                   | 2        | 4.44%   |
| Intel Atom              | 2        | 4.44%   |
| Intel Pentium Silver    | 1        | 2.22%   |
| Intel Pentium           | 1        | 2.22%   |
| Intel Core 2 Quad       | 1        | 2.22%   |
| Intel Core 2 Duo        | 1        | 2.22%   |
| Intel Core 2            | 1        | 2.22%   |
| Intel Celeron           | 1        | 2.22%   |
| AMD Ryzen Threadripper  | 1        | 2.22%   |
| AMD Ryzen 9             | 1        | 2.22%   |
| AMD Ryzen 5 PRO         | 1        | 2.22%   |
| AMD Ryzen 3             | 1        | 2.22%   |
| AMD Phenom II X4        | 1        | 2.22%   |
| AMD FX                  | 1        | 2.22%   |
| AMD Athlon II X4        | 1        | 2.22%   |
| AMD A10                 | 1        | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 15       | 33.33%  |
| 2       | 11       | 24.44%  |
| 6       | 5        | 11.11%  |
| 8       | 4        | 8.89%   |
| 12      | 3        | 6.67%   |
| Unknown | 3        | 6.67%   |
| 24      | 1        | 2.22%   |
| 16      | 1        | 2.22%   |
| 10      | 1        | 2.22%   |
| 1       | 1        | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 30       | 66.67%  |
| 2       | 12       | 26.67%  |
| Unknown | 3        | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 6        | 13.33%  |
| Haswell       | 6        | 13.33%  |
| KabyLake      | 5        | 11.11%  |
| Zen           | 3        | 6.67%   |
| IvyBridge     | 3        | 6.67%   |
| Zen+          | 2        | 4.44%   |
| Zen 2         | 2        | 4.44%   |
| Skylake       | 2        | 4.44%   |
| K10           | 2        | 4.44%   |
| Core          | 2        | 4.44%   |
| Bonnell       | 2        | 4.44%   |
| Unknown       | 2        | 4.44%   |
| Zen 3         | 1        | 2.22%   |
| Silvermont    | 1        | 2.22%   |
| SandyBridge   | 1        | 2.22%   |
| Piledriver    | 1        | 2.22%   |
| Goldmont plus | 1        | 2.22%   |
| Excavator     | 1        | 2.22%   |
| CometLake     | 1        | 2.22%   |
| Broadwell     | 1        | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 19       | 40.43%  |
| Intel  | 17       | 36.17%  |
| AMD    | 11       | 23.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 6.38%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 4.26%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 4.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 4.26%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 4.26%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.13%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 2.13%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.13%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 2.13%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.13%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 2.13%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 2.13%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 2.13%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2.13%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 2.13%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 2.13%   |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1        | 2.13%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 2.13%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 2.13%   |
| Intel HD Graphics 630                                                       | 1        | 2.13%   |
| Intel HD Graphics 530                                                       | 1        | 2.13%   |
| Intel HD Graphics 510                                                       | 1        | 2.13%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 2.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 2.13%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 2.13%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 2.13%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.13%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 2.13%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 2.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.13%   |
| AMD Kryptos [Radeon RX 350]                                                 | 1        | 2.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 19       | 42.22%  |
| 1 x Intel   | 14       | 31.11%  |
| 1 x AMD     | 9        | 20%     |
| Intel + AMD | 2        | 4.44%   |
| 2 x Intel   | 1        | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 60%     |
| Proprietary | 14       | 31.11%  |
| Unknown     | 4        | 8.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 53.33%  |
| 1.01-2.0   | 7        | 15.56%  |
| 5.01-6.0   | 5        | 11.11%  |
| 0.51-1.0   | 4        | 8.89%   |
| 3.01-4.0   | 2        | 4.44%   |
| 0.01-0.5   | 2        | 4.44%   |
| 7.01-8.0   | 1        | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 15.63%  |
| Goldstar            | 5        | 15.63%  |
| Dell                | 5        | 15.63%  |
| Acer                | 4        | 12.5%   |
| MSI                 | 3        | 9.38%   |
| Hewlett-Packard     | 2        | 6.25%   |
| AOC                 | 2        | 6.25%   |
| Vizio               | 1        | 3.13%   |
| Toshiba             | 1        | 3.13%   |
| Philips             | 1        | 3.13%   |
| Insignia            | 1        | 3.13%   |
| Iiyama              | 1        | 3.13%   |
| BenQ                | 1        | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2        | 5.88%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2        | 5.88%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1        | 2.94%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1        | 2.94%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1        | 2.94%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1        | 2.94%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1        | 2.94%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1        | 2.94%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1        | 2.94%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 2.94%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 2.94%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1        | 2.94%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch           | 1        | 2.94%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1        | 2.94%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1        | 2.94%   |
| Goldstar E2240 GSM57A4 1920x1080 480x270mm 21.7-inch                  | 1        | 2.94%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1        | 2.94%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1        | 2.94%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1        | 2.94%   |
| Dell LCD Monitor LNK0001 1920x1080 300x230mm 14.9-inch                | 1        | 2.94%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1        | 2.94%   |
| Dell E2216HV DELF06F 1920x1080 480x270mm 21.7-inch                    | 1        | 2.94%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 1        | 2.94%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                     | 1        | 2.94%   |
| AOC Q2577W AOC2577 2560x1440 550x310mm 24.9-inch                      | 1        | 2.94%   |
| AOC 2481W AOC2481 1920x1080 530x300mm 24.0-inch                       | 1        | 2.94%   |
| Acer GN246HL ACR02FA 1920x1080 530x300mm 24.0-inch                    | 1        | 2.94%   |
| Acer B276HL ACR0332 1920x1080 600x340mm 27.2-inch                     | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 23       | 71.88%  |
| 3440x1440          | 2        | 6.25%   |
| 1680x1050 (WSXGA+) | 2        | 6.25%   |
| 2560x1440 (QHD)    | 1        | 3.13%   |
| 2560x1080          | 1        | 3.13%   |
| 1600x900 (HD+)     | 1        | 3.13%   |
| 1366x768 (WXGA)    | 1        | 3.13%   |
| 1280x1024 (SXGA)   | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 7        | 20.59%  |
| 31      | 5        | 14.71%  |
| 24      | 4        | 11.76%  |
| 23      | 4        | 11.76%  |
| 34      | 2        | 5.88%   |
| 27      | 2        | 5.88%   |
| 19      | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 50      | 1        | 2.94%   |
| 41      | 1        | 2.94%   |
| 33      | 1        | 2.94%   |
| 22      | 1        | 2.94%   |
| 18      | 1        | 2.94%   |
| 14      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 29.41%  |
| 401-500     | 10       | 29.41%  |
| 601-700     | 5        | 14.71%  |
| 701-800     | 3        | 8.82%   |
| Unknown     | 2        | 5.88%   |
| 351-400     | 1        | 2.94%   |
| 201-300     | 1        | 2.94%   |
| 1001-1500   | 1        | 2.94%   |
| 901-1000    | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 26       | 81.25%  |
| 21/9  | 3        | 9.38%   |
| 5/4   | 1        | 3.13%   |
| 4/3   | 1        | 3.13%   |
| 16/10 | 1        | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 44.12%  |
| 351-500        | 8        | 23.53%  |
| 301-350        | 2        | 5.88%   |
| 151-200        | 2        | 5.88%   |
| Unknown        | 2        | 5.88%   |
| More than 1000 | 1        | 2.94%   |
| 251-300        | 1        | 2.94%   |
| 141-150        | 1        | 2.94%   |
| 101-110        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 57.58%  |
| 101-120 | 10       | 30.3%   |
| Unknown | 2        | 6.06%   |
| 1-50    | 1        | 3.03%   |
| 121-160 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 71.11%  |
| 0     | 10       | 22.22%  |
| 2     | 3        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 50%     |
| Intel                 | 15       | 26.79%  |
| Qualcomm Atheros      | 7        | 12.5%   |
| Ralink Technology     | 1        | 1.79%   |
| OPPO Electronics      | 1        | 1.79%   |
| IMC Networks          | 1        | 1.79%   |
| Edimax Technology     | 1        | 1.79%   |
| Broadcom              | 1        | 1.79%   |
| ASUSTek Computer      | 1        | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 27       | 43.55%  |
| Intel Ethernet Connection I217-LM                                           | 4        | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 3.23%   |
| Intel Wireless 8265 / 8275                                                  | 2        | 3.23%   |
| Intel Wi-Fi 6 AX200                                                         | 2        | 3.23%   |
| Intel 82574L Gigabit Network Connection                                     | 2        | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 1.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 1.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1        | 1.61%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 1.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                   | 1        | 1.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                               | 1        | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 1.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1        | 1.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                       | 1        | 1.61%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                              | 1        | 1.61%   |
| Intel Ethernet Controller I225-V                                            | 1        | 1.61%   |
| Intel Ethernet Connection (7) I219-V                                        | 1        | 1.61%   |
| Intel Ethernet Connection (2) I219-V                                        | 1        | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                                       | 1        | 1.61%   |
| Intel Ethernet Connection (2) I218-V                                        | 1        | 1.61%   |
| Intel Ethernet Connection (11) I219-LM                                      | 1        | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 1        | 1.61%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 1.61%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 1.61%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 25%     |
| Intel                 | 4        | 25%     |
| Qualcomm Atheros      | 3        | 18.75%  |
| Ralink Technology     | 1        | 6.25%   |
| IMC Networks          | 1        | 6.25%   |
| Edimax Technology     | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |
| ASUSTek Computer      | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 12.5%   |
| Intel Wireless 8265 / 8275                                                  | 2        | 12.5%   |
| Intel Wi-Fi 6 AX200                                                         | 2        | 12.5%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 6.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 6.25%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 6.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 6.25%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 6.25%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 6.25%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 6.25%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 62.22%  |
| Intel                 | 12       | 26.67%  |
| Qualcomm Atheros      | 4        | 8.89%   |
| OPPO Electronics      | 1        | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 58.7%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 8.7%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.17%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 2.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 2.17%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1        | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.17%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.17%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.17%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 75%     |
| WiFi     | 15       | 25%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 93.18%  |
| WiFi     | 3        | 6.82%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 75.56%  |
| 2     | 11       | 24.44%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 97.78%  |
| Yes  | 1        | 2.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 4        | 36.36%  |
| Realtek Semiconductor      | 3        | 27.27%  |
| Integrated System Solution | 1        | 9.09%   |
| Cambridge Silicon Radio    | 1        | 9.09%   |
| Bluetooth Device           | 1        | 9.09%   |
| Apple                      | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 18.18%  |
| Intel Bluetooth wireless interface                       | 2        | 18.18%  |
| Intel AX200 Bluetooth                                    | 2        | 18.18%  |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1        | 9.09%   |
| Integrated System Solution Bluetooth Device              | 1        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 1        | 9.09%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1        | 9.09%   |
| Apple Apple Broadcom Built-in Bluetooth                  | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 31       | 42.47%  |
| AMD                 | 17       | 23.29%  |
| Nvidia              | 16       | 21.92%  |
| C-Media Electronics | 4        | 5.48%   |
| Google              | 2        | 2.74%   |
| Yamaha              | 1        | 1.37%   |
| Logitech            | 1        | 1.37%   |
| Creative Technology | 1        | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 9.52%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 5.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.57%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 3.57%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 3.57%   |
| Nvidia High Definition Audio Controller                                    | 2        | 2.38%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 2.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 2.38%   |
| Google Pixel earbuds                                                       | 2        | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 2.38%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 2.38%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.38%   |
| Yamaha Steinberg UR22mkII                                                  | 1        | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.19%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.19%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.19%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.19%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.19%   |
| Logitech HD Webcam C510                                                    | 1        | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.19%   |
| Creative Technology Sound BlasterX G1                                      | 1        | 1.19%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.19%   |
| C-Media Electronics Cmedia Audio                                           | 1        | 1.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.19%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 1.19%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.19%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 11       | 18.97%  |
| Kingston            | 8        | 13.79%  |
| SK hynix            | 7        | 12.07%  |
| Micron Technology   | 6        | 10.34%  |
| Crucial             | 6        | 10.34%  |
| Samsung Electronics | 5        | 8.62%   |
| Transcend           | 3        | 5.17%   |
| Unknown             | 3        | 5.17%   |
| Corsair             | 2        | 3.45%   |
| Team                | 1        | 1.72%   |
| Ramaxel Technology  | 1        | 1.72%   |
| Patriot             | 1        | 1.72%   |
| Nanya Technology    | 1        | 1.72%   |
| GLOWAY              | 1        | 1.72%   |
| G.Skill             | 1        | 1.72%   |
| A-DATA Technology   | 1        | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 3        | 4.48%   |
| Unknown                                                | 3        | 4.48%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2        | 2.99%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s      | 2        | 2.99%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s   | 2        | 2.99%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s   | 2        | 2.99%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 1.49%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s   | 1        | 1.49%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s      | 1        | 1.49%   |
| Team RAM Elite-13 4GB DIMM DDR3 667MT/s                | 1        | 1.49%   |
| Team RAM Elite-1 2GB DIMM DDR3 667MT/s                 | 1        | 1.49%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.49%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 1.49%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 1.49%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 1.49%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB RIMM DDR4 2133MT/s  | 1        | 1.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s            | 1        | 1.49%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s              | 1        | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 1.49%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 1.49%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2133MT/s    | 1        | 1.49%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB DIMM DDR3 1600MT/s  | 1        | 1.49%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 3200MT/s        | 1        | 1.49%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s     | 1        | 1.49%   |
| Micron RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 1.49%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 1        | 1.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 1        | 1.49%   |
| Micron RAM 8ATF1G64HZ-2G6J1 8GB SODIMM DDR4 2667MT/s   | 1        | 1.49%   |
| Micron RAM 4ATF51264AZ-3G2J1 4GB DIMM DDR4 3200MT/s    | 1        | 1.49%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 1        | 1.49%   |
| Kingston RAM KHX3200C18D4/16G 16GB DIMM DDR4 3200MT/s  | 1        | 1.49%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 1        | 1.49%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s   | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 21       | 46.67%  |
| DDR3    | 14       | 31.11%  |
| DDR2    | 5        | 11.11%  |
| SDRAM   | 3        | 6.67%   |
| Unknown | 2        | 4.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 40       | 88.89%  |
| SODIMM | 4        | 8.89%   |
| RIMM   | 1        | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 20       | 33.33%  |
| 4096  | 19       | 31.67%  |
| 2048  | 12       | 20%     |
| 16384 | 7        | 11.67%  |
| 1024  | 2        | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 9        | 18.75%  |
| 3200    | 5        | 10.42%  |
| 2133    | 5        | 10.42%  |
| 1333    | 5        | 10.42%  |
| 800     | 5        | 10.42%  |
| 2667    | 4        | 8.33%   |
| 2400    | 4        | 8.33%   |
| Unknown | 4        | 8.33%   |
| 2666    | 3        | 6.25%   |
| 2933    | 2        | 4.17%   |
| 1066    | 1        | 2.08%   |
| 667     | 1        | 2.08%   |

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
| Z-Star Microelectronics | 1        | 20%     |
| Microdia                | 1        | 20%     |
| Logitech                | 1        | 20%     |
| Genesys Logic           | 1        | 20%     |
| Arkmicro Technologies   | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera       | 1        | 20%     |
| Microdia Camera                  | 1        | 20%     |
| Logitech HD Pro Webcam C920      | 1        | 20%     |
| Genesys Logic Digital Microscope | 1        | 20%     |
| Arkmicro Webcam Carrefour        | 1        | 20%     |

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
| 0     | 21       | 46.67%  |
| 1     | 19       | 42.22%  |
| 2     | 4        | 8.89%   |
| 3     | 1        | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 19       | 65.52%  |
| Net/wireless             | 7        | 24.14%  |
| Sound                    | 1        | 3.45%   |
| Card reader              | 1        | 3.45%   |
| Bluetooth                | 1        | 3.45%   |

