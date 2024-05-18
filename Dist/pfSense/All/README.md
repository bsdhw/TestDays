pfSense - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for pfSense.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/pfSense/Desktop/README.md) and [notebooks](/Dist/pfSense/Notebook/README.md).

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

Total: 50

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| eMachines     | E525                        | Notebook    | [3c06a422b8](https://bsd-hardware.info/?probe=3c06a422b8) | Mar 23, 2024 |
| Sophos        | XG                          | Firewall    | [452db53e17](https://bsd-hardware.info/?probe=452db53e17) | Feb 25, 2024 |
| PC Engines    | APU2                        | Desktop     | [66d6af8951](https://bsd-hardware.info/?probe=66d6af8951) | Feb 20, 2024 |
| Azulle        | Access3                     | Stick pc    | [451d2b5708](https://bsd-hardware.info/?probe=451d2b5708) | Jan 05, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [7387d0de6b](https://bsd-hardware.info/?probe=7387d0de6b) | Dec 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [19a5ef28f8](https://bsd-hardware.info/?probe=19a5ef28f8) | Dec 28, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [83673368b9](https://bsd-hardware.info/?probe=83673368b9) | Nov 17, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [0d6203b7c9](https://bsd-hardware.info/?probe=0d6203b7c9) | Nov 07, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [e69fadd7a8](https://bsd-hardware.info/?probe=e69fadd7a8) | Oct 29, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [eaf7d5bd39](https://bsd-hardware.info/?probe=eaf7d5bd39) | Sep 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b6e5a7e7bc](https://bsd-hardware.info/?probe=b6e5a7e7bc) | Jun 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2d50927445](https://bsd-hardware.info/?probe=2d50927445) | Jun 18, 2023 |
| HP            | 0AA0h                       | Desktop     | [bed2f4cfd7](https://bsd-hardware.info/?probe=bed2f4cfd7) | May 16, 2023 |
| Advantech     | UNO-2271G_V2                | Desktop     | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| HP            | 805D                        | Desktop     | [4912ca5cd6](https://bsd-hardware.info/?probe=4912ca5cd6) | Jan 11, 2023 |
| HP            | 805D                        | Desktop     | [3da9c57f1f](https://bsd-hardware.info/?probe=3da9c57f1f) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b73e61a78](https://bsd-hardware.info/?probe=5b73e61a78) | Jul 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [699fea1ac9](https://bsd-hardware.info/?probe=699fea1ac9) | Jul 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [92f62da399](https://bsd-hardware.info/?probe=92f62da399) | Jun 22, 2022 |
| PC Engines    | APU2                        | Desktop     | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8bbeb73a52](https://bsd-hardware.info/?probe=8bbeb73a52) | Jan 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [98ed242ae0](https://bsd-hardware.info/?probe=98ed242ae0) | Jan 01, 2022 |
| Dell          | 06D7TR A02                  | Desktop     | [201ba6cbba](https://bsd-hardware.info/?probe=201ba6cbba) | Nov 04, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [289423796b](https://bsd-hardware.info/?probe=289423796b) | Jul 17, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [64d08bd493](https://bsd-hardware.info/?probe=64d08bd493) | Jul 17, 2021 |
| PC Engines    | APU                         | Desktop     | [60d7917c9d](https://bsd-hardware.info/?probe=60d7917c9d) | Mar 28, 2021 |
| Dell          | 02YYK5 A00                  | Desktop     | [d4708d5f62](https://bsd-hardware.info/?probe=d4708d5f62) | Mar 07, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [dadf566436](https://bsd-hardware.info/?probe=dadf566436) | Jan 06, 2021 |
| HP            | 18E7                        | Desktop     | [8c4d8cbfc9](https://bsd-hardware.info/?probe=8c4d8cbfc9) | Dec 22, 2020 |
| HP            | 213D A01                    | Desktop     | [623a12f06b](https://bsd-hardware.info/?probe=623a12f06b) | Dec 20, 2020 |
| AWOW          | PC BOX                      | Mini pc     | [c966a1e1f6](https://bsd-hardware.info/?probe=c966a1e1f6) | Dec 17, 2020 |
| Supermicro    | X7SPA-HF                    | Desktop     | [84225d9f44](https://bsd-hardware.info/?probe=84225d9f44) | Dec 16, 2020 |
| Netgate       | SG-5100 1                   | Desktop     | [8336fb3a61](https://bsd-hardware.info/?probe=8336fb3a61) | Dec 16, 2020 |
| Unknown       | Unknown                     | Desktop     | [237f10ea9c](https://bsd-hardware.info/?probe=237f10ea9c) | Dec 16, 2020 |
| AWOW          | PC BOX                      | Mini pc     | [e975767e84](https://bsd-hardware.info/?probe=e975767e84) | Dec 16, 2020 |
| Dell          | 02YYK5 A00                  | Desktop     | [3fc7c8bb8d](https://bsd-hardware.info/?probe=3fc7c8bb8d) | Nov 01, 2020 |
| TYAN Compu... | Unknown                     | Desktop     | [5ba6da7c5f](https://bsd-hardware.info/?probe=5ba6da7c5f) | Oct 29, 2020 |
| Protectli     | FW2B Ver                    | Desktop     | [4fcfd19048](https://bsd-hardware.info/?probe=4fcfd19048) | Sep 21, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| ADI Engine... | RCC-VE                      | Desktop     | [91f0c6425b](https://bsd-hardware.info/?probe=91f0c6425b) | Jun 03, 2020 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [215cea62e1](https://bsd-hardware.info/?probe=215cea62e1) | Jun 02, 2020 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| pfSense 2.4.5       | 13        | 33.33%  |
| pfSense 2.6.0       | 7         | 17.95%  |
| pfSense 2.7.2       | 4         | 10.26%  |
| pfSense 2.5.0       | 4         | 10.26%  |
| pfSense 12.3-STABLE | 4         | 10.26%  |
| pfSense 2.4.4       | 2         | 5.13%   |
| pfSense 12.2-STABLE | 2         | 5.13%   |
| pfSense 23.09.1     | 1         | 2.56%   |
| pfSense 23.05.1     | 1         | 2.56%   |
| pfSense 2.7.0       | 1         | 2.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| pfSense | 38        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 37        | 97.37%  |
| arm   | 1         | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 38        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 38        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 38        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 73.68%  |
| C       | 7         | 18.42%  |
| en_US   | 2         | 5.26%   |
| pt_BR   | 1         | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 20        | 52.63%  |
| EFI  | 18        | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 21        | 55.26%  |
| Ufs  | 17        | 44.74%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 29        | 76.32%  |
| MBR  | 9         | 23.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 10.53%  |
| PC Engines          | 3         | 7.89%   |
| ASUSTek Computer    | 3         | 7.89%   |
| Unknown             | 3         | 7.89%   |
| Techvision          | 2         | 5.26%   |
| Protectli           | 2         | 5.26%   |
| Lenovo              | 2         | 5.26%   |
| Intel               | 2         | 5.26%   |
| Dell                | 2         | 5.26%   |
| AWOW                | 2         | 5.26%   |
| ZOTAC               | 1         | 2.63%   |
| TYAN Computer       | 1         | 2.63%   |
| Supermicro          | 1         | 2.63%   |
| Sophos              | 1         | 2.63%   |
| Netgate             | 1         | 2.63%   |
| Itautec             | 1         | 2.63%   |
| Gigabyte Technology | 1         | 2.63%   |
| eMachines           | 1         | 2.63%   |
| Azulle              | 1         | 2.63%   |
| Apple               | 1         | 2.63%   |
| AMI                 | 1         | 2.63%   |
| Advantech           | 1         | 2.63%   |
| ADI Engineering     | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 4         | 10.53%  |
| Techvision TVI7309X               | 2         | 5.26%   |
| PC Engines APU2                   | 2         | 5.26%   |
| Intel Q3XXG4-P V1.0               | 2         | 5.26%   |
| AWOW PC BOX                       | 2         | 5.26%   |
| ZOTAC ZBOX-CI323NANO              | 1         | 2.63%   |
| Supermicro X7SPA-HF               | 1         | 2.63%   |
| Sophos XG                         | 1         | 2.63%   |
| Protectli FW4B                    | 1         | 2.63%   |
| Protectli FW2B                    | 1         | 2.63%   |
| PC Engines APU                    | 1         | 2.63%   |
| Netgate SG-5100                   | 1         | 2.63%   |
| Lenovo ThinkCentre M92p 3209D9U   | 1         | 2.63%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1         | 2.63%   |
| Itautec Infoway                   | 1         | 2.63%   |
| HP xw4600 Workstation             | 1         | 2.63%   |
| HP t620 PLUS Quad Core TC         | 1         | 2.63%   |
| HP ProDesk 600 G2 SFF             | 1         | 2.63%   |
| HP ProDesk 600 G1 SFF             | 1         | 2.63%   |
| Gigabyte B85M-D3H                 | 1         | 2.63%   |
| eMachines E525                    | 1         | 2.63%   |
| Dell OptiPlex 990                 | 1         | 2.63%   |
| Dell OptiPlex 7020                | 1         | 2.63%   |
| Azulle Access3                    | 1         | 2.63%   |
| ASUS P5Q SE PLUS                  | 1         | 2.63%   |
| ASUS All Series                   | 1         | 2.63%   |
| ASUS A88XM-E                      | 1         | 2.63%   |
| Apple Macmini7,1                  | 1         | 2.63%   |
| AMI Aptio CRB                     | 1         | 2.63%   |
| Advantech UNO-2271G_V2            | 1         | 2.63%   |
| ADI Engineering RCC-VE            | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 4         | 10.53%  |
| Techvision TVI7309X    | 2         | 5.26%   |
| PC Engines APU2        | 2         | 5.26%   |
| Lenovo ThinkCentre     | 2         | 5.26%   |
| Intel Q3XXG4-P         | 2         | 5.26%   |
| HP ProDesk             | 2         | 5.26%   |
| Dell OptiPlex          | 2         | 5.26%   |
| AWOW PC                | 2         | 5.26%   |
| ZOTAC ZBOX-CI323NANO   | 1         | 2.63%   |
| Supermicro X7SPA-HF    | 1         | 2.63%   |
| Sophos XG              | 1         | 2.63%   |
| Protectli FW4B         | 1         | 2.63%   |
| Protectli FW2B         | 1         | 2.63%   |
| PC Engines APU         | 1         | 2.63%   |
| Netgate SG-5100        | 1         | 2.63%   |
| Itautec Infoway        | 1         | 2.63%   |
| HP xw4600              | 1         | 2.63%   |
| HP t620                | 1         | 2.63%   |
| Gigabyte B85M-D3H      | 1         | 2.63%   |
| eMachines E525         | 1         | 2.63%   |
| Azulle Access3         | 1         | 2.63%   |
| ASUS P5Q               | 1         | 2.63%   |
| ASUS All               | 1         | 2.63%   |
| ASUS A88XM-E           | 1         | 2.63%   |
| Apple Macmini7         | 1         | 2.63%   |
| AMI Aptio              | 1         | 2.63%   |
| Advantech UNO-2271G    | 1         | 2.63%   |
| ADI Engineering RCC-VE | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 7         | 18.42%  |
| 2016    | 5         | 13.16%  |
| 2015    | 5         | 13.16%  |
| 2022    | 3         | 7.89%   |
| 2020    | 2         | 5.26%   |
| 2019    | 2         | 5.26%   |
| 2017    | 2         | 5.26%   |
| 2014    | 2         | 5.26%   |
| 2012    | 2         | 5.26%   |
| 2010    | 2         | 5.26%   |
| 2009    | 2         | 5.26%   |
| 2021    | 1         | 2.63%   |
| 2013    | 1         | 2.63%   |
| 2006    | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 30        | 78.95%  |
| Mini pc  | 5         | 13.16%  |
| Stick pc | 1         | 2.63%   |
| Firewall | 1         | 2.63%   |
| Notebook | 1         | 2.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 89.47%  |
| Yes  | 4         | 10.53%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 42.11%  |
| 8.01-16.0   | 12        | 31.58%  |
| 16.01-24.0  | 6         | 15.79%  |
| 2.01-3.0    | 2         | 5.26%   |
| 32.01-64.0  | 1         | 2.63%   |
| 64.01-256.0 | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 25        | 65.79%  |
| 0.51-1.0 | 8         | 21.05%  |
| 4.01-8.0 | 2         | 5.26%   |
| 2.01-3.0 | 2         | 5.26%   |
| 1.01-2.0 | 1         | 2.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 74.36%  |
| 2      | 5         | 12.82%  |
| 0      | 5         | 12.82%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 84.21%  |
| Yes       | 6         | 15.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 97.37%  |
| No        | 1         | 2.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 71.05%  |
| Yes       | 11        | 28.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 84.21%  |
| Yes       | 6         | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 52.63%  |
| Brazil      | 3         | 7.89%   |
| UK          | 2         | 5.26%   |
| Russia      | 2         | 5.26%   |
| Germany     | 2         | 5.26%   |
| Taiwan      | 1         | 2.63%   |
| Sweden      | 1         | 2.63%   |
| New Zealand | 1         | 2.63%   |
| Netherlands | 1         | 2.63%   |
| Mozambique  | 1         | 2.63%   |
| India       | 1         | 2.63%   |
| Greece      | 1         | 2.63%   |
| Canada      | 1         | 2.63%   |
| Cameroon    | 1         | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Salem             | 2         | 5.26%   |
| Yegor'yevsk       | 1         | 2.63%   |
| Wellington        | 1         | 2.63%   |
| Waconia           | 1         | 2.63%   |
| Uxbridge          | 1         | 2.63%   |
| Stuttgart         | 1         | 2.63%   |
| Silver Spring     | 1         | 2.63%   |
| Sao Paulo         | 1         | 2.63%   |
| Renton            | 1         | 2.63%   |
| Phoenix           | 1         | 2.63%   |
| Philadelphia      | 1         | 2.63%   |
| Pasadena          | 1         | 2.63%   |
| Orlando           | 1         | 2.63%   |
| Moscow            | 1         | 2.63%   |
| Maputo            | 1         | 2.63%   |
| Malmo             | 1         | 2.63%   |
| Longmont          | 1         | 2.63%   |
| Long Beach        | 1         | 2.63%   |
| London            | 1         | 2.63%   |
| Lawrenceville     | 1         | 2.63%   |
| Kottenheim        | 1         | 2.63%   |
| JaraguГЎ do Sul | 1         | 2.63%   |
| Jaraguá do Sul   | 1         | 2.63%   |
| Hoboken           | 1         | 2.63%   |
| Glen Allen        | 1         | 2.63%   |
| Fletcher          | 1         | 2.63%   |
| Fairford          | 1         | 2.63%   |
| Fair Oaks         | 1         | 2.63%   |
| Douliu            | 1         | 2.63%   |
| Douala            | 1         | 2.63%   |
| Daly City         | 1         | 2.63%   |
| Centreville       | 1         | 2.63%   |
| Bengaluru         | 1         | 2.63%   |
| Atlanta           | 1         | 2.63%   |
| Athens            | 1         | 2.63%   |
| Ashburn           | 1         | 2.63%   |
| Amsterdam         | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 18.92%  |
| Seagate             | 4         | 4      | 10.81%  |
| Samsung Electronics | 4         | 4      | 10.81%  |
| Intel               | 3         | 4      | 8.11%   |
| WDC                 | 2         | 3      | 5.41%   |
| SanDisk             | 2         | 2      | 5.41%   |
| Phison              | 2         | 2      | 5.41%   |
| Hitachi             | 2         | 2      | 5.41%   |
| FORESEE             | 2         | 2      | 5.41%   |
| Crucial             | 2         | 2      | 5.41%   |
| Apacer              | 2         | 2      | 5.41%   |
| SPCC                | 1         | 1      | 2.7%    |
| Silicon Motion      | 1         | 1      | 2.7%    |
| Netac               | 1         | 1      | 2.7%    |
| Hoodisk             | 1         | 1      | 2.7%    |
| China               | 1         | 2      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SUV500MS120G 120GB       | 2         | 5.41%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 2.7%    |
| WDC WD10EFRX-68FYTN0 1TB          | 1         | 2.7%    |
| SPCC Solid State Disk 120GB       | 1         | 2.7%    |
| Silicon Motion NVME SSD 128GB     | 1         | 2.7%    |
| Seagate ST500DM002-1BD142 500GB   | 1         | 2.7%    |
| Seagate ST380815AS 80GB           | 1         | 2.7%    |
| Seagate ST3160023A 160GB          | 1         | 2.7%    |
| Seagate ST240HM000-1G5152 240GB   | 1         | 2.7%    |
| SanDisk SDSSDP064G 64GB           | 1         | 2.7%    |
| SanDisk SDSSDA120G 120GB          | 1         | 2.7%    |
| Samsung SSD RBX Series 64GB M     | 1         | 2.7%    |
| Samsung SSD 860 EVO 250GB         | 1         | 2.7%    |
| Samsung SSD 850 EVO mSATA 250GB   | 1         | 2.7%    |
| Samsung SSD 850 EVO 120GB         | 1         | 2.7%    |
| Phison SATA SSD 32GB              | 1         | 2.7%    |
| Phison SATA SSD 240GB             | 1         | 2.7%    |
| Netac SSD 256GB                   | 1         | 2.7%    |
| Kingston SUV500MS240G 240GB       | 1         | 2.7%    |
| Kingston SUV500M8120G 120GB       | 1         | 2.7%    |
| Kingston SNVS1000G 1TB            | 1         | 2.7%    |
| Kingston SNS4151S316G 16GB        | 1         | 2.7%    |
| Kingston RBUSNS8180DS3128GH 128GB | 1         | 2.7%    |
| Intel SSDSC2BA800G3 800GB         | 1         | 2.7%    |
| Intel SSDSA2CW080G3 80GB          | 1         | 2.7%    |
| Intel SSDMCEAC030B3 32GB          | 1         | 2.7%    |
| Hoodisk SSD 32GB                  | 1         | 2.7%    |
| Hitachi HTS727550A9E364 500GB     | 1         | 2.7%    |
| Hitachi HTS545025B9A300 250GB     | 1         | 2.7%    |
| FORESEE 64GB SSD                  | 1         | 2.7%    |
| FORESEE 128GB SSD                 | 1         | 2.7%    |
| Crucial CT500P2SSD8 500GB         | 1         | 2.7%    |
| Crucial CT1000MX500SSD1 1TB       | 1         | 2.7%    |
| China SATA SSD 256GB              | 1         | 2.7%    |
| Apacer 64GB SATA Flash Drive      | 1         | 2.7%    |
| Apacer 32GB SATA Flash Drive      | 1         | 2.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| WDC     | 2         | 3      | 28.57%  |
| Hitachi | 2         | 2      | 28.57%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 22.22%  |
| Samsung Electronics | 4         | 4      | 14.81%  |
| Intel               | 3         | 4      | 11.11%  |
| SanDisk             | 2         | 2      | 7.41%   |
| Phison              | 2         | 2      | 7.41%   |
| FORESEE             | 2         | 2      | 7.41%   |
| Apacer              | 2         | 2      | 7.41%   |
| SPCC                | 1         | 1      | 3.7%    |
| Seagate             | 1         | 1      | 3.7%    |
| Netac               | 1         | 1      | 3.7%    |
| Hoodisk             | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |
| China               | 1         | 2      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 24        | 29     | 70.59%  |
| HDD  | 7         | 8      | 20.59%  |
| NVMe | 3         | 3      | 8.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 37     | 90.91%  |
| NVMe | 3         | 3      | 9.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 32     | 90.32%  |
| 0.51-1.0   | 3         | 5      | 9.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 34.21%  |
| 51-100     | 8         | 21.05%  |
| 21-50      | 7         | 18.42%  |
| 501-1000   | 4         | 10.53%  |
| 251-500    | 3         | 7.89%   |
| 1-20       | 3         | 7.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 37        | 97.37%  |
| 21-50   | 1         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Kingston SNS4151S316G 16GB    | 1         | 1      | 33.33%  |
| Hitachi HTS727550A9E364 500GB | 1         | 1      | 33.33%  |
| Apacer 32GB SATA Flash Drive  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 1         | 1      | 33.33%  |
| Hitachi  | 1         | 1      | 33.33%  |
| Apacer   | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 31        | 37     | 91.18%  |
| Malfunc | 3         | 3      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 29        | 72.5%   |
| AMD                         | 6         | 15%     |
| Silicon Motion              | 1         | 2.5%    |
| Silicon Image               | 1         | 2.5%    |
| Micron/Crucial Technology   | 1         | 2.5%    |
| Kingston Technology Company | 1         | 2.5%    |
| JMicron Technology          | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 11.36%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 6.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 4.55%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 4.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 4.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 2.27%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 2.27%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 2.27%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                               | 1         | 2.27%   |
| JMicron JMB368 IDE controller                                                    | 1         | 2.27%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.27%   |
| Intel Elkhart Lake SATA AHCI                                                     | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.27%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1         | 2.27%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1         | 2.27%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1         | 2.27%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1         | 2.27%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 2.27%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 2.27%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.27%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 2.27%   |
| AMD AMD-8111 IDE                                                                 | 1         | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 29        | 74.36%  |
| IDE  | 4         | 10.26%  |
| RAID | 3         | 7.69%   |
| NVMe | 3         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 81.58%  |
| AMD    | 6         | 15.79%  |
| ARM    | 1         | 2.63%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2         | 5.26%   |
| Intel Celeron N5105 @ 2.00GHz            | 2         | 5.26%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 2         | 5.26%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 5.26%   |
| AMD GX-412TC SOC                         | 2         | 5.26%   |
| Intel Xeon CPU E3-1275 v3 @ 3.50GHz      | 1         | 2.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 1         | 2.63%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1         | 2.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 2.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1         | 2.63%   |
| Intel Core i5-4278U CPU @ 2.60GHz        | 1         | 2.63%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 1         | 2.63%   |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1         | 2.63%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 1         | 2.63%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz    | 1         | 2.63%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1         | 2.63%   |
| Intel Celeron N6210 @ 1.20GHz            | 1         | 2.63%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 1         | 2.63%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 1         | 2.63%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 1         | 2.63%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1         | 2.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 1         | 2.63%   |
| Intel Celeron CPU 900 @ 2.20GHz          | 1         | 2.63%   |
| Intel Celeron CPU 450 @ 2.20GHz          | 1         | 2.63%   |
| Intel Atom CPU D525 @ 1.80GHz            | 1         | 2.63%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 1         | 2.63%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 1         | 2.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1         | 2.63%   |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1         | 2.63%   |
| AMD Opteron Processor 252                | 1         | 2.63%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 1         | 2.63%   |
| AMD G-T40E Processor                     | 1         | 2.63%   |
| AMD Athlon X4 860K Quad Core Processor   | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Celeron     | 14        | 36.84%  |
| Intel Core i5     | 8         | 21.05%  |
| Intel Atom        | 3         | 7.89%   |
| AMD GX            | 3         | 7.89%   |
| Intel Core i7     | 2         | 5.26%   |
| Other             | 1         | 2.63%   |
| Intel Xeon        | 1         | 2.63%   |
| Intel Core 2 Quad | 1         | 2.63%   |
| Intel Core 2 Duo  | 1         | 2.63%   |
| ARM Cortex        | 1         | 2.63%   |
| AMD Opteron       | 1         | 2.63%   |
| AMD G             | 1         | 2.63%   |
| AMD Athlon X4     | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 25        | 65.79%  |
| 2       | 8         | 21.05%  |
| Unknown | 4         | 10.53%  |
| 1       | 1         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 36        | 94.74%  |
| 2       | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 28        | 73.68%  |
| 2       | 6         | 15.79%  |
| Unknown | 4         | 10.53%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 7         | 18.42%  |
| Unknown       | 6         | 15.79%  |
| Haswell       | 5         | 13.16%  |
| Penryn        | 3         | 7.89%   |
| Goldmont      | 3         | 7.89%   |
| Puma          | 2         | 5.26%   |
| IvyBridge     | 2         | 5.26%   |
| Broadwell     | 2         | 5.26%   |
| TigerLake     | 1         | 2.63%   |
| Steamroller   | 1         | 2.63%   |
| Skylake       | 1         | 2.63%   |
| SandyBridge   | 1         | 2.63%   |
| K8 Hammer     | 1         | 2.63%   |
| Goldmont plus | 1         | 2.63%   |
| Bonnell       | 1         | 2.63%   |
| Bobcat        | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 26        | 83.87%  |
| AMD                        | 4         | 12.9%   |
| Matrox Electronics Systems | 1         | 3.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 16.13%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 9.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 6.45%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 6.45%   |
| Intel HD Graphics 6000                                                                   | 2         | 6.45%   |
| Intel HD Graphics 500                                                                    | 2         | 6.45%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 3.23%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.23%   |
| Intel HD Graphics 530                                                                    | 1         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 3.23%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 1         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 3.23%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 3.23%   |
| AMD RV710 [Radeon HD 4550]                                                               | 1         | 3.23%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1         | 3.23%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1         | 3.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 25        | 65.79%  |
| Other      | 7         | 18.42%  |
| 1 x AMD    | 4         | 10.53%  |
| 2 x Intel  | 1         | 2.63%   |
| 1 x Matrox | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 31        | 81.58%  |
| Unknown | 7         | 18.42%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

Zero info for selected period =(

Monitor Model
-------------

Monitor models

Zero info for selected period =(

Monitor Resolution
------------------

Monitor screen resolution

Zero info for selected period =(

Monitor Diagonal
----------------

Diagonal size in inches

Zero info for selected period =(

Monitor Width
-------------

Physical width

Zero info for selected period =(

Aspect Ratio
------------

Proportional relationship between the width and the height

Zero info for selected period =(

Monitor Area
------------

Area in inch²

Zero info for selected period =(

Pixel Density
-------------

Pixels per inch

Zero info for selected period =(

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 38        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 28        | 54.9%   |
| Realtek Semiconductor     | 12        | 23.53%  |
| Qualcomm Atheros          | 4         | 7.84%   |
| Broadcom                  | 4         | 7.84%   |
| Solarflare Communications | 1         | 1.96%   |
| NetXen Incorporated       | 1         | 1.96%   |
| MediaTek                  | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 11        | 16.92%  |
| Intel I211 Gigabit Network Connection                                         | 7         | 10.77%  |
| Intel I210 Gigabit Network Connection                                         | 5         | 7.69%   |
| Intel Wireless 3165                                                           | 4         | 6.15%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 4.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 3.08%   |
| Intel Ethernet Controller I225-V                                              | 2         | 3.08%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.08%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 3.08%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 1.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 1.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 1.54%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1         | 1.54%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 1.54%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1         | 1.54%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.54%   |
| Intel Ethernet Controller I226-V                                              | 1         | 1.54%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 1.54%   |
| Intel Ethernet Connection I354                                                | 1         | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.54%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.54%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 1.54%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.54%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 1.54%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 1.54%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 1         | 1.54%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 1.54%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 1.54%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 1         | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5         | 45.45%  |
| Qualcomm Atheros      | 4         | 36.36%  |
| Realtek Semiconductor | 1         | 9.09%   |
| Broadcom              | 1         | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 4         | 36.36%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 18.18%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 9.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 9.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 9.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1         | 9.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 1         | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 24        | 55.81%  |
| Realtek Semiconductor     | 12        | 27.91%  |
| Broadcom                  | 4         | 9.3%    |
| Solarflare Communications | 1         | 2.33%   |
| Qualcomm Atheros          | 1         | 2.33%   |
| MediaTek                  | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 11        | 20.75%  |
| Intel I211 Gigabit Network Connection                                         | 7         | 13.21%  |
| Intel I210 Gigabit Network Connection                                         | 5         | 9.43%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 5.66%   |
| Intel Ethernet Controller I225-V                                              | 2         | 3.77%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.77%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 3.77%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 1.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 1.89%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 1.89%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.89%   |
| Intel Ethernet Controller I226-V                                              | 1         | 1.89%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 1.89%   |
| Intel Ethernet Connection I354                                                | 1         | 1.89%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.89%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.89%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 1.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 1.89%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.89%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 1.89%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 1         | 1.89%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 1.89%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 75.51%  |
| WiFi     | 11        | 22.45%  |
| Unknown  | 1         | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 12        | 31.58%  |
| 5     | 7         | 18.42%  |
| 2     | 7         | 18.42%  |
| 4     | 5         | 13.16%  |
| 6     | 4         | 10.53%  |
| 9     | 1         | 2.63%   |
| 8     | 1         | 2.63%   |
| 0     | 1         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 89.47%  |
| Yes  | 4         | 10.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 5         | 83.33%  |
| Apple  | 1         | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface       | 4         | 66.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1         | 16.67%  |
| Apple Bluetooth Host Controller          | 1         | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 88.89%  |
| AMD    | 3         | 11.11%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 12.12%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 9.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 6.06%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 6.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 6.06%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 6.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 6.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 6.06%   |
| AMD FCH Azalia Controller                                                                         | 2         | 6.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 3.03%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 1         | 3.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 3.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 3.03%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 3.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 3.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 19.44%  |
| Crucial             | 6         | 16.67%  |
| Samsung Electronics | 5         | 13.89%  |
| Unknown (ABCD)      | 3         | 8.33%   |
| SK hynix            | 3         | 8.33%   |
| Transcend           | 2         | 5.56%   |
| Micron Technology   | 2         | 5.56%   |
| V-Color             | 1         | 2.78%   |
| Unknown (0x1636)    | 1         | 2.78%   |
| Ramaxel Technology  | 1         | 2.78%   |
| Nanya Technology    | 1         | 2.78%   |
| Kingston            | 1         | 2.78%   |
| Corsair             | 1         | 2.78%   |
| A-DATA Technology   | 1         | 2.78%   |
| Unknown             | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 5.56%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 5.56%   |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s         | 2         | 5.56%   |
| V-Color RAM TN432G32D822 32GB SODIMM DDR4 3200MT/s               | 1         | 2.78%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s              | 1         | 2.78%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 2.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 2.78%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s                    | 1         | 2.78%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 2.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.78%   |
| Unknown (0x1636) RAM 5.6.5 4GB SODIMM DDR4 2667MT/s              | 1         | 2.78%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s            | 1         | 2.78%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s                | 1         | 2.78%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.78%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s                       | 1         | 2.78%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 2.78%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 1         | 2.78%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 2.78%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s              | 1         | 2.78%   |
| Ramaxel RAM RML1320KE48D8F-800 2GB DIMM DDR2 800MT/s             | 1         | 2.78%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s               | 1         | 2.78%   |
| Micron RAM MTA8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 1         | 2.78%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 2.78%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s            | 1         | 2.78%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s            | 1         | 2.78%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Corsair RAM CM2X1024-6400 1GB DIMM DDR2 800MT/s                  | 1         | 2.78%   |
| A-DATA RAM AEDS1600W8G11-BNAD 8GB DIMM DDR3 1600MT/s             | 1         | 2.78%   |
| Unknown                                                          | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 18        | 54.55%  |
| DDR4    | 6         | 18.18%  |
| SDRAM   | 3         | 9.09%   |
| LPDDR4  | 3         | 9.09%   |
| DDR2    | 2         | 6.06%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 20        | 62.5%   |
| SODIMM | 12        | 37.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 17        | 51.52%  |
| 2048  | 6         | 18.18%  |
| 16384 | 4         | 12.12%  |
| 8192  | 4         | 12.12%  |
| 32768 | 1         | 3.03%   |
| 1024  | 1         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 40.63%  |
| 2400    | 4         | 12.5%   |
| 1333    | 4         | 12.5%   |
| 800     | 4         | 12.5%   |
| 3200    | 3         | 9.38%   |
| Unknown | 2         | 6.25%   |
| 2667    | 1         | 3.13%   |
| 2133    | 1         | 3.13%   |

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


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Suyin  | 1         | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 100%    |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 17        | 44.74%  |
| 1     | 14        | 36.84%  |
| 3     | 4         | 10.53%  |
| 2     | 2         | 5.26%   |
| 5     | 1         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 19        | 55.88%  |
| Bluetooth                | 7         | 20.59%  |
| Net/wireless             | 4         | 11.76%  |
| Card reader              | 3         | 8.82%   |
| Network                  | 1         | 2.94%   |

