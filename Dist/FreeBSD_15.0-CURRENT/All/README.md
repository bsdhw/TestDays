FreeBSD 15.0-CURRENT - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 15.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_15.0-CURRENT/Desktop/README.md) and [notebooks](/Dist/FreeBSD_15.0-CURRENT/Notebook/README.md).

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

Total: 73

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [587525ebab](https://bsd-hardware.info/?probe=587525ebab) | Jan 02, 2025 |
| Apple         | MacBookPro8,3               | Notebook    | [af06d6afc4](https://bsd-hardware.info/?probe=af06d6afc4) | Dec 24, 2024 |
| Unknown       | Unknown                     | All in one  | [cb659e7cd1](https://bsd-hardware.info/?probe=cb659e7cd1) | Dec 24, 2024 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [09413cb67c](https://bsd-hardware.info/?probe=09413cb67c) | Dec 10, 2024 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [4edaabd936](https://bsd-hardware.info/?probe=4edaabd936) | Dec 07, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [c8d95da1f8](https://bsd-hardware.info/?probe=c8d95da1f8) | Nov 26, 2024 |
| Supermicro    | X10SDV-TP8F                 | Server      | [f764b90e3d](https://bsd-hardware.info/?probe=f764b90e3d) | Nov 14, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [7aa93cd8ba](https://bsd-hardware.info/?probe=7aa93cd8ba) | Nov 03, 2024 |
| ASRock        | X570 Taichi                 | Desktop     | [4c642bb872](https://bsd-hardware.info/?probe=4c642bb872) | Oct 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [bbc44a72cc](https://bsd-hardware.info/?probe=bbc44a72cc) | Oct 03, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [24de39a693](https://bsd-hardware.info/?probe=24de39a693) | Sep 26, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [5d6734e438](https://bsd-hardware.info/?probe=5d6734e438) | Sep 18, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [fbfc038a2d](https://bsd-hardware.info/?probe=fbfc038a2d) | Sep 18, 2024 |
| Framework     | Laptop                      | Notebook    | [c374e02dcb](https://bsd-hardware.info/?probe=c374e02dcb) | Sep 11, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [854819dc14](https://bsd-hardware.info/?probe=854819dc14) | Sep 10, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [a0946e4145](https://bsd-hardware.info/?probe=a0946e4145) | Sep 07, 2024 |
| Google        | Dragonair                   | Notebook    | [d49059cd45](https://bsd-hardware.info/?probe=d49059cd45) | Sep 06, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [3648ccf01b](https://bsd-hardware.info/?probe=3648ccf01b) | Aug 07, 2024 |
| Acer          | E5-572G-57VZ                | Notebook    | [f4c2bf9852](https://bsd-hardware.info/?probe=f4c2bf9852) | Jul 27, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [cc3b04bc73](https://bsd-hardware.info/?probe=cc3b04bc73) | Jul 23, 2024 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [7eed45e354](https://bsd-hardware.info/?probe=7eed45e354) | Jul 14, 2024 |
| Lenovo        | FALCON SB27A42854           | Server      | [e0b9a15ecd](https://bsd-hardware.info/?probe=e0b9a15ecd) | Jul 14, 2024 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [930b346dd0](https://bsd-hardware.info/?probe=930b346dd0) | Jul 14, 2024 |
| Lenovo        | FALCON SB27A42854           | Server      | [7f0bfb6be8](https://bsd-hardware.info/?probe=7f0bfb6be8) | Jul 14, 2024 |
| TUXEDO        | Pulse 14 Gen3               | Notebook    | [3400ac8782](https://bsd-hardware.info/?probe=3400ac8782) | Jul 13, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | Notebook    | [3ecc86438d](https://bsd-hardware.info/?probe=3ecc86438d) | Jul 08, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [4b9cdbf4d2](https://bsd-hardware.info/?probe=4b9cdbf4d2) | Jul 07, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [e27538e64c](https://bsd-hardware.info/?probe=e27538e64c) | Jun 28, 2024 |
| ASRockRack    | B650D4U                     | Server      | [ec5b0e44e9](https://bsd-hardware.info/?probe=ec5b0e44e9) | Jun 26, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [c2ac893b66](https://bsd-hardware.info/?probe=c2ac893b66) | Jun 25, 2024 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [e41fe01667](https://bsd-hardware.info/?probe=e41fe01667) | Jun 16, 2024 |
| Google        | Astronaut                   | Notebook    | [7d888b2dd9](https://bsd-hardware.info/?probe=7d888b2dd9) | Jun 05, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [1f9f3170fd](https://bsd-hardware.info/?probe=1f9f3170fd) | May 25, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [6c9cc5620b](https://bsd-hardware.info/?probe=6c9cc5620b) | May 22, 2024 |
| Dell          | Precision 7560              | Notebook    | [62956576cd](https://bsd-hardware.info/?probe=62956576cd) | May 06, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [8558fc6b60](https://bsd-hardware.info/?probe=8558fc6b60) | May 04, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [db2e2d1fbc](https://bsd-hardware.info/?probe=db2e2d1fbc) | May 02, 2024 |
| Quanta        | S5HF MB 31S5HMB0010         | Server      | [cdfd36bbab](https://bsd-hardware.info/?probe=cdfd36bbab) | May 02, 2024 |
| Dell          | Precision 7560              | Notebook    | [2f6e45641d](https://bsd-hardware.info/?probe=2f6e45641d) | May 02, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [f5683de21a](https://bsd-hardware.info/?probe=f5683de21a) | Apr 24, 2024 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [94b19fd1c0](https://bsd-hardware.info/?probe=94b19fd1c0) | Apr 13, 2024 |
| Lenovo        | ThinkBook 16 G6+ IMH 21L... | Notebook    | [7ae1277ce9](https://bsd-hardware.info/?probe=7ae1277ce9) | Apr 12, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [ad2494f0c0](https://bsd-hardware.info/?probe=ad2494f0c0) | Apr 11, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [3fb8a577ad](https://bsd-hardware.info/?probe=3fb8a577ad) | Apr 10, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [7c5ed3c2fe](https://bsd-hardware.info/?probe=7c5ed3c2fe) | Apr 06, 2024 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [b2bbe7eb8d](https://bsd-hardware.info/?probe=b2bbe7eb8d) | Apr 04, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a596a6f2fc](https://bsd-hardware.info/?probe=a596a6f2fc) | Mar 30, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [8a5397997e](https://bsd-hardware.info/?probe=8a5397997e) | Mar 18, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [e97bd00aad](https://bsd-hardware.info/?probe=e97bd00aad) | Mar 13, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [4d63500465](https://bsd-hardware.info/?probe=4d63500465) | Feb 26, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [db2c57b081](https://bsd-hardware.info/?probe=db2c57b081) | Jan 24, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [ae1a4bcbae](https://bsd-hardware.info/?probe=ae1a4bcbae) | Jan 23, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [d876c335eb](https://bsd-hardware.info/?probe=d876c335eb) | Jan 21, 2024 |
| AZW           | SER                         | Mini pc     | [be54157bac](https://bsd-hardware.info/?probe=be54157bac) | Jan 21, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [33704d0025](https://bsd-hardware.info/?probe=33704d0025) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [79707e220e](https://bsd-hardware.info/?probe=79707e220e) | Jan 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | Notebook    | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| EVGA          | X570 DARK.0                 | Desktop     | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [406d7a0572](https://bsd-hardware.info/?probe=406d7a0572) | Dec 07, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [cc4538374c](https://bsd-hardware.info/?probe=cc4538374c) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8e245ccb85](https://bsd-hardware.info/?probe=8e245ccb85) | Oct 25, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [24e745026c](https://bsd-hardware.info/?probe=24e745026c) | Sep 08, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [b83ebfd33b](https://bsd-hardware.info/?probe=b83ebfd33b) | Aug 29, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 43        | 91.49%  |
| arm64 | 4         | 8.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Console   | 15        | 31.25%  |
| KDE5      | 8         | 16.67%  |
| XFCE      | 4         | 8.33%   |
| GNOME     | 3         | 6.25%   |
| wlroots   | 2         | 4.17%   |
| TWM       | 2         | 4.17%   |
| Openbox   | 2         | 4.17%   |
| KDE       | 2         | 4.17%   |
| i3        | 2         | 4.17%   |
| Budgie    | 2         | 4.17%   |
| Wayfire   | 1         | 2.08%   |
| LXQt      | 1         | 2.08%   |
| Hyprland  | 1         | 2.08%   |
| Fluxbox   | 1         | 2.08%   |
| Compton   | 1         | 2.08%   |
| AwesomeWM | 1         | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 26        | 55.32%  |
| Console | 16        | 34.04%  |
| Wayland | 5         | 10.64%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 21        | 43.75%  |
| SDDM    | 14        | 29.17%  |
| LightDM | 4         | 8.33%   |
| SLiM    | 3         | 6.25%   |
| GDM     | 3         | 6.25%   |
| XDM     | 2         | 4.17%   |
| Ly      | 1         | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 34        | 72.34%  |
| en_US   | 8         | 17.02%  |
| ru_RU   | 2         | 4.26%   |
| ru      | 1         | 2.13%   |
| pl_PL   | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 47        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 39        | 82.98%  |
| Ufs  | 8         | 17.02%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 47        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 12        | 25.53%  |
| ASUSTek Computer                     | 7         | 14.89%  |
| Framework                            | 5         | 10.64%  |
| Apple                                | 3         | 6.38%   |
| Hewlett-Packard                      | 2         | 4.26%   |
| ASRock                               | 2         | 4.26%   |
| Unknown                              | 2         | 4.26%   |
| TUXEDO                               | 1         | 2.13%   |
| Supermicro                           | 1         | 2.13%   |
| SolidRun                             | 1         | 2.13%   |
| Shenzhen Meigao Electronic Equipment | 1         | 2.13%   |
| Quanta                               | 1         | 2.13%   |
| MSI                                  | 1         | 2.13%   |
| HUAWEI                               | 1         | 2.13%   |
| Google                               | 1         | 2.13%   |
| Gigabyte Technology                  | 1         | 2.13%   |
| EVGA                                 | 1         | 2.13%   |
| Dell                                 | 1         | 2.13%   |
| AZW                                  | 1         | 2.13%   |
| ASRockRack                           | 1         | 2.13%   |
| Acer                                 | 1         | 2.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Framework Laptop 16 (AMD Ryzen 7040 Series)       | 2         | 4.26%   |
| Unknown                                           | 2         | 4.26%   |
| TUXEDO Pulse 14 Gen3                              | 1         | 2.13%   |
| Supermicro SYS-5018D-FN8T                         | 1         | 2.13%   |
| SolidRun CEX7 Platform                            | 1         | 2.13%   |
| Shenzhen Meigao Electronic Equipment Venus series | 1         | 2.13%   |
| Quanta QuantaPlex T22HF-1U                        | 1         | 2.13%   |
| MSI MS-7C96                                       | 1         | 2.13%   |
| Lenovo ThinkPad X260 20F5A28AUK                   | 1         | 2.13%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JBM          | 1         | 2.13%   |
| Lenovo ThinkPad T14s Gen 4 21F60029US             | 1         | 2.13%   |
| Lenovo ThinkPad T14 Gen 3 21CF002UMZ              | 1         | 2.13%   |
| Lenovo ThinkPad P17 Gen 2i 20YVS1L900             | 1         | 2.13%   |
| Lenovo ThinkPad E16 Gen 1 21JNCTO1WW              | 1         | 2.13%   |
| Lenovo ThinkBook 16 G6+ IMH 21LE                  | 1         | 2.13%   |
| Lenovo ThinkBook 15 G4 IAP 21DJ                   | 1         | 2.13%   |
| Lenovo ThinkBook 14 G6 IRL 21KG                   | 1         | 2.13%   |
| Lenovo IdeaPad 3 15ITL6 82MD                      | 1         | 2.13%   |
| Lenovo B40-30 80F1                                | 1         | 2.13%   |
| Lenovo 7X35A007NA HR350A 7X35CTO1WW               | 1         | 2.13%   |
| HUAWEI MRGFG-XX                                   | 1         | 2.13%   |
| HP ZBook 17 G2                                    | 1         | 2.13%   |
| HP EliteBook 8570p                                | 1         | 2.13%   |
| Google Astronaut                                  | 1         | 2.13%   |
| Gigabyte R272-P31-00                              | 1         | 2.13%   |
| Framework Laptop 13 (AMD Ryzen 7040Series)        | 1         | 2.13%   |
| Framework Laptop (12th Gen Intel Core)            | 1         | 2.13%   |
| Framework Laptop                                  | 1         | 2.13%   |
| EVGA X570 DARK                                    | 1         | 2.13%   |
| Dell Precision 7560                               | 1         | 2.13%   |
| AZW SER                                           | 1         | 2.13%   |
| ASUS TUF Gaming B650M-PLUS                        | 1         | 2.13%   |
| ASUS ROG STRIX X870E-E GAMING WIFI                | 1         | 2.13%   |
| ASUS ROG STRIX X670E-F GAMING WIFI                | 1         | 2.13%   |
| ASUS ROG STRIX B650E-I GAMING WIFI                | 1         | 2.13%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI                   | 1         | 2.13%   |
| ASUS PRIME Z790-A WIFI                            | 1         | 2.13%   |
| ASUS PRIME Z370-P II                              | 1         | 2.13%   |
| ASRockRack B650D4U                                | 1         | 2.13%   |
| ASRock Z790M-ITX WiFi                             | 1         | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 6         | 12.77%  |
| Framework Laptop                           | 5         | 10.64%  |
| Lenovo ThinkBook                           | 3         | 6.38%   |
| ASUS ROG                                   | 3         | 6.38%   |
| ASUS PRIME                                 | 2         | 4.26%   |
| Apple MacBookPro8                          | 2         | 4.26%   |
| Unknown                                    | 2         | 4.26%   |
| TUXEDO Pulse                               | 1         | 2.13%   |
| Supermicro SYS-5018D-FN8T                  | 1         | 2.13%   |
| SolidRun CEX7                              | 1         | 2.13%   |
| Shenzhen Meigao Electronic Equipment Venus | 1         | 2.13%   |
| Quanta QuantaPlex                          | 1         | 2.13%   |
| MSI MS-7C96                                | 1         | 2.13%   |
| Lenovo IdeaPad                             | 1         | 2.13%   |
| Lenovo B40-30                              | 1         | 2.13%   |
| Lenovo 7X35A007NA                          | 1         | 2.13%   |
| HUAWEI MRGFG-XX                            | 1         | 2.13%   |
| HP ZBook                                   | 1         | 2.13%   |
| HP EliteBook                               | 1         | 2.13%   |
| Google Astronaut                           | 1         | 2.13%   |
| Gigabyte R272-P31-00                       | 1         | 2.13%   |
| EVGA X570                                  | 1         | 2.13%   |
| Dell Precision                             | 1         | 2.13%   |
| AZW SER                                    | 1         | 2.13%   |
| ASUS TUF                                   | 1         | 2.13%   |
| ASUS Pro                                   | 1         | 2.13%   |
| ASRockRack B650D4U                         | 1         | 2.13%   |
| ASRock Z790M-ITX                           | 1         | 2.13%   |
| ASRock X570                                | 1         | 2.13%   |
| Apple MacBookAir7                          | 1         | 2.13%   |
| Acer E5-572G-57VZ                          | 1         | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 15        | 31.91%  |
| 2024    | 7         | 14.89%  |
| 2022    | 7         | 14.89%  |
| 2019    | 4         | 8.51%   |
| 2021    | 3         | 6.38%   |
| 2020    | 3         | 6.38%   |
| 2018    | 2         | 4.26%   |
| 2016    | 2         | 4.26%   |
| 2014    | 1         | 2.13%   |
| 2013    | 1         | 2.13%   |
| 2012    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 26        | 55.32%  |
| Desktop    | 13        | 27.66%  |
| Server     | 5         | 10.64%  |
| Mini pc    | 2         | 4.26%   |
| All in one | 1         | 2.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 97.87%  |
| Yes  | 1         | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 64.01-256.0 | 17        | 34.69%  |
| 16.01-24.0  | 14        | 28.57%  |
| 32.01-64.0  | 10        | 20.41%  |
| 8.01-16.0   | 5         | 10.2%   |
| 4.01-8.0    | 2         | 4.08%   |
| 0.51-1.0    | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 12        | 24.49%  |
| 1.01-2.0 | 11        | 22.45%  |
| 4.01-8.0 | 8         | 16.33%  |
| 0.01-0.5 | 8         | 16.33%  |
| 2.01-3.0 | 7         | 14.29%  |
| 3.01-4.0 | 3         | 6.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 30        | 60%     |
| 1      | 14        | 28%     |
| 2      | 4         | 8%      |
| 7      | 1         | 2%      |
| 3      | 1         | 2%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 87.23%  |
| Yes       | 6         | 12.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 76.6%   |
| No        | 11        | 23.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 74.47%  |
| No        | 12        | 25.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 74.47%  |
| No        | 12        | 25.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 18.75%  |
| UK          | 6         | 12.5%   |
| Germany     | 6         | 12.5%   |
| Russia      | 4         | 8.33%   |
| Canada      | 4         | 8.33%   |
| Switzerland | 2         | 4.17%   |
| Netherlands | 2         | 4.17%   |
| Hungary     | 2         | 4.17%   |
| France      | 2         | 4.17%   |
| Czechia     | 2         | 4.17%   |
| Brazil      | 2         | 4.17%   |
| Taiwan      | 1         | 2.08%   |
| Sweden      | 1         | 2.08%   |
| Spain       | 1         | 2.08%   |
| Serbia      | 1         | 2.08%   |
| Poland      | 1         | 2.08%   |
| China       | 1         | 2.08%   |
| Bangladesh  | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Stockport              | 2         | 3.7%    |
| Richmond               | 2         | 3.7%    |
| Moscow                 | 2         | 3.7%    |
| Hove                   | 2         | 3.7%    |
| Darmstadt              | 2         | 3.7%    |
| Budapest               | 2         | 3.7%    |
| Brighton               | 2         | 3.7%    |
| Břeclav               | 2         | 3.7%    |
| Amsterdam              | 2         | 3.7%    |
| Zurich                 | 1         | 1.85%   |
| Warsaw                 | 1         | 1.85%   |
| Viladecans             | 1         | 1.85%   |
| Vancouver              | 1         | 1.85%   |
| Stuttgart              | 1         | 1.85%   |
| Stockholm              | 1         | 1.85%   |
| St. Albert             | 1         | 1.85%   |
| Smolensk               | 1         | 1.85%   |
| Siblingen              | 1         | 1.85%   |
| Rio de Janeiro         | 1         | 1.85%   |
| Pevensey               | 1         | 1.85%   |
| New York               | 1         | 1.85%   |
| New Taipei             | 1         | 1.85%   |
| Mississauga            | 1         | 1.85%   |
| Macaiba                | 1         | 1.85%   |
| Letchworth Garden City | 1         | 1.85%   |
| Landorthe              | 1         | 1.85%   |
| Kirov                  | 1         | 1.85%   |
| Karlsruhe              | 1         | 1.85%   |
| Haywards Heath         | 1         | 1.85%   |
| Hangzhou               | 1         | 1.85%   |
| Hadleigh               | 1         | 1.85%   |
| Glasgow                | 1         | 1.85%   |
| Fort Lauderdale        | 1         | 1.85%   |
| Durant                 | 1         | 1.85%   |
| Dhaka                  | 1         | 1.85%   |
| Courbevoie             | 1         | 1.85%   |
| Cologne                | 1         | 1.85%   |
| Carlsbad               | 1         | 1.85%   |
| Bognor Regis           | 1         | 1.85%   |
| Boca Raton             | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 16     | 27.27%  |
| Kingston            | 3         | 5      | 13.64%  |
| Seagate             | 2         | 4      | 9.09%   |
| HGST                | 2         | 14     | 9.09%   |
| Crucial             | 2         | 2      | 9.09%   |
| WDC                 | 1         | 1      | 4.55%   |
| SK hynix            | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Lenovo              | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Hitachi             | 1         | 1      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 8.7%    |
| Samsung SSD 860 EVO 500GB          | 2         | 8.7%    |
| Kingston SV300S37A120G 120GB       | 2         | 8.7%    |
| HGST HTS721010A9E630 1TB           | 2         | 8.7%    |
| WDC WD7500BPKX-60HPJT0 752GB       | 1         | 4.35%   |
| SK hynix SC401 SATA 256GB          | 1         | 4.35%   |
| SanDisk Ultra II 1TB               | 1         | 4.35%   |
| Samsung SSD 860 EVO 250GB          | 1         | 4.35%   |
| Samsung SSD 850 EVO 500GB          | 1         | 4.35%   |
| Samsung SSD 850 EVO 250GB          | 1         | 4.35%   |
| Samsung MZ7L37T6HBLA-00A07 7.6TB   | 1         | 4.35%   |
| Samsung MZ7KH240HAHQ-00005 240GB   | 1         | 4.35%   |
| Lenovo SSD SL700 120G              | 1         | 4.35%   |
| Kingston SA400S37-120GB            | 1         | 4.35%   |
| Intel SSDSC2BF240A5L 240GB         | 1         | 4.35%   |
| Hitachi HTS727575A9E362 752GB      | 1         | 4.35%   |
| Crucial CT2000BX500SSD1 2TB        | 1         | 4.35%   |
| Crucial CT1000MX500SSD1 1TB        | 1         | 4.35%   |
| Apple SSD SM0128G 121GB            | 1         | 4.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 33.33%  |
| HGST    | 2         | 14     | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 16     | 37.5%   |
| Kingston            | 3         | 5      | 18.75%  |
| Crucial             | 2         | 2      | 12.5%   |
| SK hynix            | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Lenovo              | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| Apple               | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 15        | 28     | 78.95%  |
| HDD  | 4         | 20     | 21.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 48     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 20     | 61.9%   |
| 0.51-1.0   | 6         | 22     | 28.57%  |
| 1.01-2.0   | 1         | 1      | 4.76%   |
| 4.01-10.0  | 1         | 5      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 13        | 26%     |
| 101-250        | 11        | 22%     |
| 1001-2000      | 10        | 20%     |
| 251-500        | 7         | 14%     |
| 51-100         | 7         | 14%     |
| More than 3000 | 1         | 2%      |
| 21-50          | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 31        | 62%     |
| 21-50    | 9         | 18%     |
| 101-250  | 6         | 12%     |
| 51-100   | 3         | 6%      |
| 501-1000 | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB  | 2         | 3      | 33.33%  |
| HGST HTS721010A9E630 1TB      | 2         | 6      | 33.33%  |
| WDC WD7500BPKX-60HPJT0 752GB  | 1         | 1      | 16.67%  |
| Hitachi HTS727575A9E362 752GB | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 2         | 3      | 33.33%  |
| HGST     | 2         | 6      | 33.33%  |
| WDC      | 1         | 1      | 16.67%  |
| Hitachi  | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 6      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 8      | 66.67%  |
| SSD  | 2         | 3      | 33.33%  |

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
| Works   | 15        | 37     | 75%     |
| Malfunc | 5         | 11     | 25%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 13        | 18.84%  |
| Intel                                   | 13        | 18.84%  |
| AMD                                     | 11        | 15.94%  |
| SanDisk                                 | 10        | 14.49%  |
| Phison Electronics                      | 5         | 7.25%   |
| SK hynix                                | 2         | 2.9%    |
| Shenzhen Unionmemory Information System | 2         | 2.9%    |
| Micron Technology                       | 2         | 2.9%    |
| Broadcom / LSI                          | 2         | 2.9%    |
| ASMedia Technology                      | 2         | 2.9%    |
| ADATA Technology                        | 2         | 2.9%    |
| Shenzhen Longsys Electronics            | 1         | 1.45%   |
| O2 Micro                                | 1         | 1.45%   |
| Micron/Crucial Technology               | 1         | 1.45%   |
| Lite-On Technology                      | 1         | 1.45%   |
| Kingston Technology Company             | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                | 6         | 7.79%   |
| AMD FCH SATA Controller [AHCI mode]                                                           | 5         | 6.49%   |
| Sandisk WD Black SN850X NVMe SSD                                                              | 4         | 5.19%   |
| AMD 600 Series Chipset SATA Controller                                                        | 4         | 5.19%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                       | 3         | 3.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                 | 3         | 3.9%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                           | 3         | 3.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                | 3         | 3.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                          | 2         | 2.6%    |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                                | 2         | 2.6%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                                   | 2         | 2.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                   | 2         | 2.6%    |
| Intel Volume Management Device NVMe RAID Controller                                           | 2         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                  | 2         | 2.6%    |
| Broadcom / LSI SAS3408 Fusion-MPT Tri-Mode I/O Controller Chip (IOC)                          | 2         | 2.6%    |
| Shenzhen Unionmemory Information System RPEYJ1T24MKN2QWY PCIe 4.0 NVMe SSD 1024GB (DRAM-less) | 1         | 1.3%    |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                             | 1         | 1.3%    |
| Sandisk WD Black SN770M NVMe SSD (DRAM-less)                                                  | 1         | 1.3%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                                   | 1         | 1.3%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                    | 1         | 1.3%    |
| Phison PS5027-E27T PCIe4 NVMe Controller (DRAM-less)                                          | 1         | 1.3%    |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                                           | 1         | 1.3%    |
| O2 Micro FORESEE E2M2 NVMe SSD                                                                | 1         | 1.3%    |
| Micron/Crucial T705 NVMe PCIe SSD                                                             | 1         | 1.3%    |
| Micron 3400 NVMe SSD [Hendrix]                                                                | 1         | 1.3%    |
| Micron 2400 NVMe SSD (DRAM-less)                                                              | 1         | 1.3%    |
| Lite-On M8Pe Series NVMe SSD                                                                  | 1         | 1.3%    |
| Kingston Company OM8PGP4 NVMe PCIe SSD (DRAM-less)                                            | 1         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                         | 1         | 1.3%    |
| Intel Tiger Lake-LP SATA Controller                                                           | 1         | 1.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                            | 1         | 1.3%    |
| Intel SSD 660P Series                                                                         | 1         | 1.3%    |
| Intel Raptor Lake SATA AHCI Controller                                                        | 1         | 1.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                        | 1         | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]                 | 1         | 1.3%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile                    | 1         | 1.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                              | 1         | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                              | 1         | 1.3%    |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                           | 1         | 1.3%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                                  | 1         | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 36        | 53.73%  |
| SATA | 24        | 35.82%  |
| RAID | 4         | 5.97%   |
| SAS  | 2         | 2.99%   |
| IDE  | 1         | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 53.19%  |
| AMD    | 18        | 38.3%   |
| ARM    | 2         | 4.26%   |
| NXP    | 1         | 2.13%   |
| Ampere | 1         | 2.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen 9 7940HS w/ Radeon 780M Graphics | 3         | 6.38%   |
| AMD Ryzen 9 7900 12-Core Processor         | 2         | 4.26%   |
| NXP Cortex-A72                             | 1         | 2.13%   |
| Intel Xeon CPU D-1518 @ 2.20GHz            | 1         | 2.13%   |
| Intel Core Ultra 7 155H                    | 1         | 2.13%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 1         | 2.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 1         | 2.13%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz         | 1         | 2.13%   |
| Intel Core i7-3520M CPU @ 2.90GHz          | 1         | 2.13%   |
| Intel Core i7-2760QM CPU @ 2.40GHz         | 1         | 2.13%   |
| Intel Core i7-2635QM CPU @ 2.00GHz         | 1         | 2.13%   |
| Intel Core i7-14700KF                      | 1         | 2.13%   |
| Intel Core i7-14700K                       | 1         | 2.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 1         | 2.13%   |
| Intel Core i5-5350U CPU @ 1.80GHz          | 1         | 2.13%   |
| Intel Core i5-4210M CPU @ 2.60GHz          | 1         | 2.13%   |
| Intel Celeron CPU N3350 @ 1.10GHz          | 1         | 2.13%   |
| Intel Celeron CPU N2840 @ 2.16GHz          | 1         | 2.13%   |
| Intel 13th Gen Core i7-13700H              | 1         | 2.13%   |
| Intel 13th Gen Core i7-1360P               | 1         | 2.13%   |
| Intel 13th Gen Core i7-1355U               | 1         | 2.13%   |
| Intel 13th Gen Core i3-1315U               | 1         | 2.13%   |
| Intel 12th Gen Core i7-1280P               | 1         | 2.13%   |
| Intel 12th Gen Core i7-1260P               | 1         | 2.13%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz    | 1         | 2.13%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz    | 1         | 2.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 1         | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 1         | 2.13%   |
| ARM Neoverse-N1 r3p1                       | 1         | 2.13%   |
| ARM Cortex-A55 r2p0                        | 1         | 2.13%   |
| Ampere eMAG                                | 1         | 2.13%   |
| AMD Ryzen Threadripper PRO 5975WX 32-Cores | 1         | 2.13%   |
| AMD Ryzen 9 9950X 16-Core Processor        | 1         | 2.13%   |
| AMD Ryzen 9 7950X3D 16-Core Processor      | 1         | 2.13%   |
| AMD Ryzen 9 7950X 16-Core Processor        | 1         | 2.13%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 1         | 2.13%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics | 1         | 2.13%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics  | 1         | 2.13%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 1         | 2.13%   |
| AMD Ryzen 7 7735HS with Radeon Graphics    | 1         | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 13        | 27.66%  |
| AMD Ryzen 9            | 9         | 19.15%  |
| Intel Core i7          | 8         | 17.02%  |
| AMD Ryzen 7            | 4         | 8.51%   |
| Intel Core i5          | 3         | 6.38%   |
| Intel Celeron          | 2         | 4.26%   |
| AMD Ryzen 5            | 2         | 4.26%   |
| Intel Xeon             | 1         | 2.13%   |
| Intel Core             | 1         | 2.13%   |
| ARM Cortex             | 1         | 2.13%   |
| AMD Ryzen Threadripper | 1         | 2.13%   |
| AMD Ryzen 7 PRO        | 1         | 2.13%   |
| AMD EPYC               | 1         | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 16      | 8         | 16.67%  |
| 4       | 8         | 16.67%  |
| 8       | 7         | 14.58%  |
| 2       | 6         | 12.5%   |
| 32      | 3         | 6.25%   |
| Unknown | 3         | 6.25%   |
| 64      | 2         | 4.17%   |
| 24      | 2         | 4.17%   |
| 12      | 2         | 4.17%   |
| 10      | 2         | 4.17%   |
| 6       | 2         | 4.17%   |
| 28      | 1         | 2.08%   |
| 22      | 1         | 2.08%   |
| 14      | 1         | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 45        | 95.74%  |
| Unknown | 2         | 4.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 25        | 52.08%  |
| 1       | 20        | 41.67%  |
| Unknown | 3         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 28        | 59.57%  |
| Zen 3       | 3         | 6.38%   |
| TigerLake   | 2         | 4.26%   |
| SandyBridge | 2         | 4.26%   |
| KabyLake    | 2         | 4.26%   |
| Haswell     | 2         | 4.26%   |
| Broadwell   | 2         | 4.26%   |
| Zen 2       | 1         | 2.13%   |
| Zen         | 1         | 2.13%   |
| Skylake     | 1         | 2.13%   |
| Silvermont  | 1         | 2.13%   |
| IvyBridge   | 1         | 2.13%   |
| Goldmont    | 1         | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 20        | 40%     |
| AMD               | 20        | 40%     |
| Nvidia            | 5         | 10%     |
| ASPEED Technology | 5         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                  | 5         | 9.62%   |
| AMD Phoenix1                                                              | 5         | 9.62%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                   | 5         | 9.62%   |
| AMD Raphael                                                               | 4         | 7.69%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 3         | 5.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 3.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 3.85%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.85%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 3.85%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                        | 1         | 1.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1         | 1.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1         | 1.92%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.92%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 1         | 1.92%   |
| Intel UHD Graphics 620                                                    | 1         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.92%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1         | 1.92%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 1         | 1.92%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                  | 1         | 1.92%   |
| Intel HD Graphics 6000                                                    | 1         | 1.92%   |
| Intel HD Graphics 500                                                     | 1         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 1.92%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                             | 1         | 1.92%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                  | 1         | 1.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 1.92%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 1         | 1.92%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                           | 1         | 1.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 34.04%  |
| 1 x AMD        | 15        | 31.91%  |
| 1 x ASPEED     | 4         | 8.51%   |
| 1 x Nvidia     | 3         | 6.38%   |
| Other          | 2         | 4.26%   |
| 2 x AMD        | 2         | 4.26%   |
| Intel + Nvidia | 2         | 4.26%   |
| Intel + AMD    | 2         | 4.26%   |
| AMD + ASPEED   | 1         | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 85.11%  |
| Proprietary | 5         | 10.64%  |
| Unknown     | 2         | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 71.43%  |
| 1.01-2.0   | 6         | 12.24%  |
| 16.01-24.0 | 2         | 4.08%   |
| 8.01-16.0  | 2         | 4.08%   |
| 0.51-1.0   | 2         | 4.08%   |
| 7.01-8.0   | 1         | 2.04%   |
| 3.01-4.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 5         | 17.24%  |
| BOE                 | 5         | 17.24%  |
| Philips             | 2         | 6.9%    |
| LG Display          | 2         | 6.9%    |
| AU Optronics        | 2         | 6.9%    |
| SDC                 | 1         | 3.45%   |
| Samsung Electronics | 1         | 3.45%   |
| HUAWEI              | 1         | 3.45%   |
| HPN                 | 1         | 3.45%   |
| HKC                 | 1         | 3.45%   |
| Goldstar            | 1         | 3.45%   |
| CTO                 | 1         | 3.45%   |
| CSO                 | 1         | 3.45%   |
| Chimei Innolux      | 1         | 3.45%   |
| BenQ                | 1         | 3.45%   |
| Apple               | 1         | 3.45%   |
| Acer                | 1         | 3.45%   |
| Unknown             | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch            | 2         | 5.71%   |
| SDC LCD Monitor 5440x1080                                        | 1         | 2.86%   |
| SDC LCD Monitor 3520x1080                                        | 1         | 2.86%   |
| SDC LCD Monitor 1600x900                                         | 1         | 2.86%   |
| SDC LCD Monitor                                                  | 1         | 2.86%   |
| Samsung Electronics S19C200 SAM09AC 1366x768 410x230mm 18.5-inch | 1         | 2.86%   |
| Philips LCD Monitor 271P4 5440x1080                              | 1         | 2.86%   |
| Philips LCD Monitor 271P4 3520x1080                              | 1         | 2.86%   |
| Philips LCD Monitor 271P4                                        | 1         | 2.86%   |
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD06ED 1920x1200 300x190mm 14.0-inch     | 1         | 2.86%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch      | 1         | 2.86%   |
| HUAWEI AD80HW HWV2402 1920x1080 530x300mm 24.0-inch              | 1         | 2.86%   |
| HPN LCD Monitor HP P24h G4                                       | 1         | 2.86%   |
| HKC 27E6QC HKC274F 2560x1440 600x330mm 27.0-inch                 | 1         | 2.86%   |
| Goldstar 24GM77 GSM5A91 1920x1080 530x300mm 24.0-inch            | 1         | 2.86%   |
| Dell U3417W DELA0DF 3440x1440 800x330mm 34.1-inch                | 1         | 2.86%   |
| Dell U3417W DELA0DE 3440x1440 800x330mm 34.1-inch                | 1         | 2.86%   |
| Dell U2720Q DEL41B4 3840x2160 600x340mm 27.2-inch                | 1         | 2.86%   |
| Dell U2311H DELA060 1920x1080 510x290mm 23.1-inch                | 1         | 2.86%   |
| Dell S2522HG DELA1C1 1920x1080 540x300mm 24.3-inch               | 1         | 2.86%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                | 1         | 2.86%   |
| CTO LCD Monitor CTO1115 3840x2160 340x190mm 15.3-inch            | 1         | 2.86%   |
| CSO LCD Monitor CSO1423 1920x1200 300x190mm 14.0-inch            | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1520 1920x1080 340x190mm 15.3-inch | 1         | 2.86%   |
| BOE NE135A1M-NY1 BOE0CB4 2880x1920 290x190mm 13.6-inch           | 1         | 2.86%   |
| BOE LCD Monitor BOE0BC9 2560x1600 340x220mm 15.9-inch            | 1         | 2.86%   |
| BOE LCD Monitor BOE06DF 1920x1080 310x170mm 13.9-inch            | 1         | 2.86%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO369F 1920x1080 340x190mm 15.3-inch   | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO31ED 1920x1080 340x190mm 15.3-inch   | 1         | 2.86%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch             | 1         | 2.86%   |
| Acer XV272U X ACR0832 2560x1440 600x340mm 27.2-inch              | 1         | 2.86%   |
| Unknown                                                          | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 10        | 34.48%  |
| 2560x1440 (QHD)   | 3         | 10.34%  |
| 3840x2160 (4K)    | 2         | 6.9%    |
| 2256x1504         | 2         | 6.9%    |
| 1920x1200 (WUXGA) | 2         | 6.9%    |
| 1600x900 (HD+)    | 2         | 6.9%    |
| 5440x1080         | 1         | 3.45%   |
| 3520x1080         | 1         | 3.45%   |
| 3440x1440         | 1         | 3.45%   |
| 2880x1920         | 1         | 3.45%   |
| 2560x1600         | 1         | 3.45%   |
| 1440x900 (WXGA+)  | 1         | 3.45%   |
| 1366x768 (WXGA)   | 1         | 3.45%   |
| Unknown           | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 6         | 23.08%  |
| 27      | 5         | 19.23%  |
| 13      | 5         | 19.23%  |
| 24      | 3         | 11.54%  |
| 14      | 2         | 7.69%   |
| Unknown | 2         | 7.69%   |
| 34      | 1         | 3.85%   |
| 23      | 1         | 3.85%   |
| 18      | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 9         | 34.62%  |
| 301-350     | 7         | 26.92%  |
| 201-300     | 6         | 23.08%  |
| Unknown     | 2         | 7.69%   |
| 701-800     | 1         | 3.85%   |
| 401-500     | 1         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 15        | 60%     |
| 3/2     | 4         | 16%     |
| 16/10   | 3         | 12%     |
| Unknown | 2         | 8%      |
| 21/9    | 1         | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 26.92%  |
| 301-350        | 5         | 19.23%  |
| 91-100         | 4         | 15.38%  |
| 201-250        | 3         | 11.54%  |
| Unknown        | 2         | 7.69%   |
| 351-500        | 1         | 3.85%   |
| 251-300        | 1         | 3.85%   |
| 141-150        | 1         | 3.85%   |
| 111-120        | 1         | 3.85%   |
| 101-110        | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 7         | 26.92%  |
| 161-240       | 6         | 23.08%  |
| 121-160       | 5         | 19.23%  |
| 101-120       | 4         | 15.38%  |
| More than 240 | 2         | 7.69%   |
| Unknown       | 2         | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 26        | 53.06%  |
| 1     | 18        | 36.73%  |
| 2     | 3         | 6.12%   |
| 3     | 2         | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 48.53%  |
| Realtek Semiconductor | 15        | 22.06%  |
| MediaTek              | 6         | 8.82%   |
| Broadcom              | 3         | 4.41%   |
| Qualcomm Atheros      | 2         | 2.94%   |
| Samsung Electronics   | 1         | 1.47%   |
| Qualcomm Technologies | 1         | 1.47%   |
| Mellanox Technologies | 1         | 1.47%   |
| Lenovo                | 1         | 1.47%   |
| Hewlett-Packard       | 1         | 1.47%   |
| Edimax Technology     | 1         | 1.47%   |
| D-Link System         | 1         | 1.47%   |
| Aquantia              | 1         | 1.47%   |
| American Megatrends   | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6         | 6.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 6.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 5.68%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 4.55%   |
| Intel Ethernet Controller I225-V                                       | 4         | 4.55%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 3.41%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 3.41%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 3.41%   |
| Intel Ethernet Controller I226-V                                       | 3         | 3.41%   |
| Realtek USB 2.5GbE Controller                                          | 2         | 2.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 2.27%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 2         | 2.27%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 2.27%   |
| Intel Ethernet Controller I219-V                                       | 2         | 2.27%   |
| Intel Ethernet Connection (23) I219-V                                  | 2         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 2.27%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 1.14%   |
| Realtek RT8126 PCIe Ethernet Controller                                | 1         | 1.14%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 1.14%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                | 1         | 1.14%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 1.14%   |
| Intel Wireless 8265 / 8275                                             | 1         | 1.14%   |
| Intel Wireless 8260                                                    | 1         | 1.14%   |
| Intel Wireless 7265                                                    | 1         | 1.14%   |
| Intel Wireless 7260                                                    | 1         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.14%   |
| Intel Meteor Lake PCH CNVi WiFi                                        | 1         | 1.14%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.14%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                          | 1         | 1.14%   |
| Intel Ethernet Controller X550                                         | 1         | 1.14%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 1.14%   |
| Intel Ethernet Connection X552 10 GbE SFP+                             | 1         | 1.14%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.14%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 56.41%  |
| MediaTek              | 5         | 12.82%  |
| Realtek Semiconductor | 4         | 10.26%  |
| Broadcom              | 3         | 7.69%   |
| Qualcomm Atheros      | 2         | 5.13%   |
| Qualcomm Technologies | 1         | 2.56%   |
| Edimax Technology     | 1         | 2.56%   |
| D-Link System         | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                  | 6         | 15.38%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 5         | 12.82%  |
| Intel Raptor Lake PCH CNVi WiFi                                            | 4         | 10.26%  |
| Intel Wi-Fi 6 AX200                                                        | 3         | 7.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 2         | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2         | 5.13%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                          | 2         | 5.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 2         | 5.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 2.56%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                 | 1         | 2.56%   |
| Intel Wireless 8265 / 8275                                                 | 1         | 2.56%   |
| Intel Wireless 8260                                                        | 1         | 2.56%   |
| Intel Wireless 7265                                                        | 1         | 2.56%   |
| Intel Wireless 7260                                                        | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 2.56%   |
| Intel Meteor Lake PCH CNVi WiFi                                            | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1         | 2.56%   |
| Edimax AC600 Wireless LAN USB Adapter                                      | 1         | 2.56%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 2.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 58.54%  |
| Realtek Semiconductor | 11        | 26.83%  |
| Broadcom              | 2         | 4.88%   |
| Samsung Electronics   | 1         | 2.44%   |
| Lenovo                | 1         | 2.44%   |
| Aquantia              | 1         | 2.44%   |
| American Megatrends   | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 6         | 13.04%  |
| Intel Ethernet Controller I225-V                                               | 4         | 8.7%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 6.52%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 6.52%   |
| Intel Ethernet Controller I226-V                                               | 3         | 6.52%   |
| Realtek USB 2.5GbE Controller                                                  | 2         | 4.35%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 4.35%   |
| Intel Ethernet Controller I219-V                                               | 2         | 4.35%   |
| Intel Ethernet Connection (23) I219-V                                          | 2         | 4.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 4.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 2.17%   |
| Realtek RT8126 PCIe Ethernet Controller                                        | 1         | 2.17%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 2.17%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 2.17%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 2.17%   |
| Intel Ethernet Controller X550                                                 | 1         | 2.17%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 2.17%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                     | 1         | 2.17%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 2.17%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 2.17%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 2.17%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 2.17%   |
| Intel 82599 10 Gigabit Network Connection                                      | 1         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 2.17%   |
| Aquantia AQtion AQC100 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1         | 2.17%   |
| American Megatrends Virtual Ethernet                                           | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 36        | 48.65%  |
| WiFi     | 35        | 47.3%   |
| Unknown  | 2         | 2.7%    |
| Modem    | 1         | 1.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 65.79%  |
| WiFi     | 13        | 34.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 51.06%  |
| 1     | 14        | 29.79%  |
| 3     | 5         | 10.64%  |
| 0     | 2         | 4.26%   |
| 8     | 1         | 2.13%   |
| 4     | 1         | 2.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 65.31%  |
| Yes  | 17        | 34.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 60%     |
| MediaTek                        | 3         | 8.57%   |
| Foxconn / Hon Hai               | 3         | 8.57%   |
| Apple                           | 3         | 8.57%   |
| Realtek Semiconductor           | 2         | 5.71%   |
| USI                             | 1         | 2.86%   |
| Qualcomm Atheros Communications | 1         | 2.86%   |
| Lite-On Technology              | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX210 Bluetooth                          | 6         | 17.14%  |
| Intel AX211 Bluetooth                          | 5         | 14.29%  |
| Intel AX200 Bluetooth                          | 4         | 11.43%  |
| MediaTek Wireless_Device                       | 3         | 8.57%   |
| Intel Bluetooth wireless interface             | 3         | 8.57%   |
| Realtek Bluetooth Adapter                      | 2         | 5.71%   |
| Intel AX201 Bluetooth                          | 2         | 5.71%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter      | 2         | 5.71%   |
| Apple Bluetooth Host Controller                | 2         | 5.71%   |
| USI Qualcomm WCN685x Bluetooth Adapter         | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 2.86%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 2.86%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 2.86%   |
| Apple Broadcom Built-in Bluetooth              | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 24        | 35.82%  |
| AMD                                  | 21        | 31.34%  |
| Nvidia                               | 4         | 5.97%   |
| C-Media Electronics                  | 4         | 5.97%   |
| ASUSTek Computer                     | 4         | 5.97%   |
| Universal Audio                      | 1         | 1.49%   |
| Thesycon Systemsoftware & Consulting | 1         | 1.49%   |
| SteelSeries ApS                      | 1         | 1.49%   |
| Mark of the Unicorn                  | 1         | 1.49%   |
| Lenovo                               | 1         | 1.49%   |
| Huawei Technologies                  | 1         | 1.49%   |
| Cambridge Silicon Radio              | 1         | 1.49%   |
| Blue Microphones                     | 1         | 1.49%   |
| BEHRINGER International              | 1         | 1.49%   |
| Alesis                               | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller                          | 11        | 13.1%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                     | 11        | 13.1%   |
| AMD Navi 31 HDMI/DP Audio                                                      | 5         | 5.95%   |
| Intel Raptor Lake-P/U/H cAVS                                                   | 4         | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                       | 3         | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                    | 2         | 2.38%   |
| Intel Tiger Lake-H HD Audio Controller                                         | 2         | 2.38%   |
| Intel Sunrise Point-LP HD Audio                                                | 2         | 2.38%   |
| Intel Raptor Lake High Definition Audio Controller                             | 2         | 2.38%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                        | 2         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller            | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller     | 2         | 2.38%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                         | 2         | 2.38%   |
| C-Media Electronics Blue Snowball                                              | 2         | 2.38%   |
| ASUSTek Computer Realtek USB Audio                                             | 2         | 2.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                      | 2         | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                             | 2         | 2.38%   |
| Universal Audio Volt 176                                                       | 1         | 1.19%   |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control             | 1         | 1.19%   |
| SteelSeries ApS SteelSeries Siberia 350                                        | 1         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                 | 1         | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                                  | 1         | 1.19%   |
| Nvidia GP102 HDMI Audio Controller                                             | 1         | 1.19%   |
| Nvidia GK107 HDMI Audio Controller                                             | 1         | 1.19%   |
| Mark of the Unicorn M Series                                                   | 1         | 1.19%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                      | 1         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller               | 1         | 1.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                        | 1         | 1.19%   |
| Intel Meteor Lake-P HD Audio Controller                                        | 1         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster              | 1         | 1.19%   |
| Intel Broadwell-U Audio Controller                                             | 1         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller     | 1         | 1.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller            | 1         | 1.19%   |
| Intel 200 Series PCH HD Audio                                                  | 1         | 1.19%   |
| Huawei Technologies KT USB Audio                                               | 1         | 1.19%   |
| Cambridge Silicon Radio Mpow HC5 Headset in charging mode - HID / Mass Storage | 1         | 1.19%   |
| Blue Microphones Yeti Stereo Microphone                                        | 1         | 1.19%   |
| BEHRINGER International X18/XR18                                               | 1         | 1.19%   |
| ASUSTek Computer USB Audio                                                     | 1         | 1.19%   |
| ASUSTek Computer OEM Device Extension                                          | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 20.83%  |
| SK hynix            | 7         | 14.58%  |
| Kingston            | 6         | 12.5%   |
| Micron Technology   | 5         | 10.42%  |
| G.Skill             | 5         | 10.42%  |
| A-DATA Technology   | 3         | 6.25%   |
| Unknown             | 3         | 6.25%   |
| Crucial             | 2         | 4.17%   |
| Corsair             | 2         | 4.17%   |
| Ramaxel Technology  | 1         | 2.08%   |
| Patriot             | 1         | 2.08%   |
| Lexar Co Limited    | 1         | 2.08%   |
| Lexar               | 1         | 2.08%   |
| fef5                | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| A-DATA RAM AD5S560032G-SFW 32GB SODIMM DDR5 5600MT/s          | 3         | 6.12%   |
| Unknown                                                       | 3         | 6.12%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 4.08%   |
| Kingston RAM 9965794-016.A00G 32GB DIMM DDR5 4800MT/s         | 2         | 4.08%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 4800MT/s          | 2         | 4.08%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 2.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s        | 1         | 2.04%   |
| SK hynix RAM HMA82GR7CJR4N-XN 16GB DIMM DDR4 3200MT/s         | 1         | 2.04%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB DIMM LPDDR5 6400MT/s      | 1         | 2.04%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                      | 1         | 2.04%   |
| SK hynix RAM H58G56AK6BX069 2GB Row Of Chips LPDDR5 6400MT/s  | 1         | 2.04%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                   | 1         | 2.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 2.04%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 1         | 2.04%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 1         | 2.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 2.04%   |
| Samsung RAM M393A2K43CB2-CTD 16GB DIMM DDR4 2667MT/s          | 1         | 2.04%   |
| Samsung RAM M386A8K40BM1-CPB 64GB DIMM DDR4 2133MT/s          | 1         | 2.04%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 2.04%   |
| Ramaxel RAM RMSA3310MF96HAF-3200 8GB SODIMM DDR4 3200MT/s     | 1         | 2.04%   |
| Patriot RAM PSD48G320081 8GB DIMM DDR4 3200MT/s               | 1         | 2.04%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s    | 1         | 2.04%   |
| Micron RAM MT40A1G16TB-062E:F 8GB Row Of Chips DDR4 3200MT/s  | 1         | 2.04%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.04%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s         | 1         | 2.04%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s         | 1         | 2.04%   |
| Lexar RAM LD4AS008G-3200ST 8GB SODIMM DDR4 3200MT/s           | 1         | 2.04%   |
| Lexar Co Limited RAM LD5EU016G-6400LA 16GB DIMM DDR5 5600MT/s | 1         | 2.04%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s         | 1         | 2.04%   |
| Kingston RAM CBD56S46BD8HA-32 32GB SODIMM DDR5 5600MT/s       | 1         | 2.04%   |
| Kingston RAM 9965684-012.A00G 8GB DIMM DDR4 2400MT/s          | 1         | 2.04%   |
| Kingston RAM 9905789-057.A00G 32GB SODIMM DDR5 5600MT/s       | 1         | 2.04%   |
| G.Skill RAM F5-6400J3239G16G 16GB DIMM DDR5 6400MT/s          | 1         | 2.04%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s        | 1         | 2.04%   |
| G.Skill RAM F4-2133C15-16GRS 16GB SODIMM DDR4 2133MT/s        | 1         | 2.04%   |
| fef5 RAM H9HCNNN8KUMLHR 1GB 2400MT/s                          | 1         | 2.04%   |
| Crucial RAM CT32G4SFD832A.C16FB 32GB SODIMM DDR4 3200MT/s     | 1         | 2.04%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s       | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 18        | 40.91%  |
| DDR5    | 14        | 31.82%  |
| DDR3    | 6         | 13.64%  |
| LPDDR5  | 4         | 9.09%   |
| LPDDR3  | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 48.89%  |
| DIMM         | 17        | 37.78%  |
| Row Of Chips | 5         | 11.11%  |
| Unknown      | 1         | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 32768 | 13        | 29.55%  |
| 16384 | 11        | 25%     |
| 8192  | 11        | 25%     |
| 4096  | 6         | 13.64%  |
| 65536 | 1         | 2.27%   |
| 2048  | 1         | 2.27%   |
| 1024  | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 25%     |
| 5600  | 7         | 15.91%  |
| 4800  | 6         | 13.64%  |
| 6400  | 4         | 9.09%   |
| 2400  | 3         | 6.82%   |
| 2133  | 3         | 6.82%   |
| 1600  | 3         | 6.82%   |
| 2667  | 2         | 4.55%   |
| 1333  | 2         | 4.55%   |
| 7500  | 1         | 2.27%   |
| 3600  | 1         | 2.27%   |
| 1867  | 1         | 2.27%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Bison Electronics                      | 7         | 26.92%  |
| Chicony Electronics                    | 4         | 15.38%  |
| Logitech                               | 3         | 11.54%  |
| Realtek Semiconductor                  | 2         | 7.69%   |
| Framework                              | 2         | 7.69%   |
| Apple                                  | 2         | 7.69%   |
| Unknown (3730304233343731345430)       | 1         | 3.85%   |
| Syntek                                 | 1         | 3.85%   |
| Sunplus Innovation Technology          | 1         | 3.85%   |
| Microdia                               | 1         | 3.85%   |
| Luxvisions Innotech Limited            | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                                  | 6         | 23.08%  |
| Realtek Laptop Camera                                                    | 2         | 7.69%   |
| Framework Laptop Webcam Module (2nd Gen)                                 | 2         | 7.69%   |
| Chicony HD WebCam                                                        | 2         | 7.69%   |
| Apple FaceTime HD Camera                                                 | 2         | 7.69%   |
| Unknown (3730304233343731345430) USB Camera                              | 1         | 3.85%   |
| Syntek Integrated Camera                                                 | 1         | 3.85%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 3.85%   |
| Microdia USB 2.0 Camera                                                  | 1         | 3.85%   |
| Luxvisions Innotech Limited Integrated RGB Camera                        | 1         | 3.85%   |
| Logitech Webcam C270                                                     | 1         | 3.85%   |
| Logitech HD Pro Webcam C920                                              | 1         | 3.85%   |
| Logitech C920 PRO HD Webcam                                              | 1         | 3.85%   |
| Chicony Integrated HP HD Webcam                                          | 1         | 3.85%   |
| Chicony Integrated Camera                                                | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 3.85%   |
| Bison Lenovo EasyCamera                                                  | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 2         | 40%     |
| Validity Sensors           | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |
| Fingerprint Cards          | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader                | 1         | 20%     |
| Fingerprint Cards FPC Fingerprint Reader          | 1         | 20%     |

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
| 2     | 14        | 29.17%  |
| 0     | 12        | 25%     |
| 3     | 10        | 20.83%  |
| 1     | 10        | 20.83%  |
| 5     | 1         | 2.08%   |
| 4     | 1         | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 24        | 36.36%  |
| Bluetooth                | 18        | 27.27%  |
| Net/wireless             | 8         | 12.12%  |
| Fingerprint reader       | 5         | 7.58%   |
| Network                  | 2         | 3.03%   |
| Net/ethernet             | 2         | 3.03%   |
| Firewire controller      | 2         | 3.03%   |
| Card reader              | 2         | 3.03%   |
| Storage/raid             | 1         | 1.52%   |
| Sound                    | 1         | 1.52%   |
| Dvb card                 | 1         | 1.52%   |

