OpenBSD 7.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.0.

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

Total: 43

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Raspberry ... | Raspberry Pi 4 Model B      | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [f2836f4a6c](https://bsd-hardware.info/?probe=f2836f4a6c) | Aug 01, 2022 |
| Apple         | PowerMac10,1                | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| PC Engines    | apu4                        | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Unknown       | Raspberry Pi 3 Model B R... | [040f37113c](https://bsd-hardware.info/?probe=040f37113c) | Apr 06, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Intel         | D945GSEJT                   | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| Dell          | OptiPlex 755                | [9ddfe010c4](https://bsd-hardware.info/?probe=9ddfe010c4) | Feb 24, 2022 |
| Gigabyte      | X58A-UD5                    | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [07546b5925](https://bsd-hardware.info/?probe=07546b5925) | Feb 18, 2022 |
| MSI           | MS-7253                     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Unknown       | LeMaker Banana Pi           | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| HP            | t620 Quad Core TC           | [965ced51e6](https://bsd-hardware.info/?probe=965ced51e6) | Feb 12, 2022 |
| MSI           | MS-7C96                     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi 400            | [b35265f8f4](https://bsd-hardware.info/?probe=b35265f8f4) | Jan 29, 2022 |
| Gigabyte      | Z590 VISION G               | [9c73c01062](https://bsd-hardware.info/?probe=9c73c01062) | Jan 28, 2022 |
| WYSE          | D CLASS                     | [5f31ae866c](https://bsd-hardware.info/?probe=5f31ae866c) | Jan 24, 2022 |
| ASRock        | X570 Pro4                   | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | MS-7C56                     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Unknown       | TI AM335x BeagleBone Bla... | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING     | [2ee4c7fefe](https://bsd-hardware.info/?probe=2ee4c7fefe) | Dec 27, 2021 |
| PC Engines    | APU2                        | [d271c4a29f](https://bsd-hardware.info/?probe=d271c4a29f) | Dec 15, 2021 |
| Gigabyte      | H81M-S2PV                   | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| MSI           | MS-7C56                     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| PC Engines    | APU2                        | [15a26da041](https://bsd-hardware.info/?probe=15a26da041) | Nov 14, 2021 |
| Unknown       | Hardkernel ODROID-N2        | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| Yanling       | YL-KBR6L                    | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Lenovo        | SHARKBAY No DPK             | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Protectli     | FW6                         | [de39c4e316](https://bsd-hardware.info/?probe=de39c4e316) | Oct 15, 2021 |
| MSI           | MS-7D54                     | [ac1f6ee8a6](https://bsd-hardware.info/?probe=ac1f6ee8a6) | Oct 13, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [46672cf89f](https://bsd-hardware.info/?probe=46672cf89f) | Oct 01, 2021 |
| Gigabyte      | BRi3(H)-10110               | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 22       | 64.71%  |
| arm64  | 6        | 17.65%  |
| i386   | 3        | 8.82%   |
| armv7  | 2        | 5.88%   |
| macppc | 1        | 2.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| fvwm          | 21       | 60%     |
| Console       | 12       | 34.29%  |
| XFCE          | 1        | 2.86%   |
| Enlightenment | 1        | 2.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 20       | 58.82%  |
| Console | 14       | 41.18%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 33       | 97.06%  |
| SLiM    | 1        | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 88.24%  |
| ru_RU   | 1        | 2.94%   |
| en_US   | 1        | 2.94%   |
| de_DE   | 1        | 2.94%   |
| C       | 1        | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 21       | 61.76%  |
| EFI  | 13       | 38.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 34       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 23       | 67.65%  |
| GPT  | 11       | 32.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Gigabyte Technology     | 6        | 17.65%  |
| Unknown                 | 5        | 14.71%  |
| MSI                     | 4        | 11.76%  |
| Raspberry Pi Foundation | 3        | 8.82%   |
| PC Engines              | 2        | 5.88%   |
| Lenovo                  | 2        | 5.88%   |
| Intel                   | 2        | 5.88%   |
| Hewlett-Packard         | 2        | 5.88%   |
| ASRock                  | 2        | 5.88%   |
| Yanling                 | 1        | 2.94%   |
| WYSE                    | 1        | 2.94%   |
| Protectli               | 1        | 2.94%   |
| Dell                    | 1        | 2.94%   |
| ASUSTek Computer        | 1        | 2.94%   |
| Apple                   | 1        | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 5        | 14.71%  |
| RPi Raspberry Pi 400               | 2        | 5.88%   |
| Yanling YL-KBR6L                   | 1        | 2.94%   |
| WYSE D CLASS                       | 1        | 2.94%   |
| RPi Raspberry Pi 4 Model B         | 1        | 2.94%   |
| Protectli FW6                      | 1        | 2.94%   |
| PC Engines apu4                    | 1        | 2.94%   |
| PC Engines APU2                    | 1        | 2.94%   |
| MSI MS-7D54                        | 1        | 2.94%   |
| MSI MS-7C96                        | 1        | 2.94%   |
| MSI MS-7C56                        | 1        | 2.94%   |
| MSI MS-7253                        | 1        | 2.94%   |
| Lenovo ThinkPad T400 2768W3A       | 1        | 2.94%   |
| Lenovo ThinkCentre M73z 10BB001DRU | 1        | 2.94%   |
| Intel DCP847SKE                    | 1        | 2.94%   |
| Intel D945GSEJT                    | 1        | 2.94%   |
| HP t620 Quad Core TC               | 1        | 2.94%   |
| HP Compaq dc5700 Microtower        | 1        | 2.94%   |
| Gigabyte Z590 VISION G             | 1        | 2.94%   |
| Gigabyte X58A-UD5                  | 1        | 2.94%   |
| Gigabyte X470 AORUS ULTRA GAMING   | 1        | 2.94%   |
| Gigabyte H81M-S2PV                 | 1        | 2.94%   |
| Gigabyte BRi3(H)-10110             | 1        | 2.94%   |
| Gigabyte B450M DS3H                | 1        | 2.94%   |
| Dell OptiPlex 755                  | 1        | 2.94%   |
| ASUS P10S-I Series                 | 1        | 2.94%   |
| ASRock X570 Pro4                   | 1        | 2.94%   |
| ASRock FM2A88X Extreme6+           | 1        | 2.94%   |
| Apple PowerMac10,1                 | 1        | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 5        | 14.71%  |
| RPi Raspberry          | 3        | 8.82%   |
| Yanling YL-KBR6L       | 1        | 2.94%   |
| WYSE D                 | 1        | 2.94%   |
| Protectli FW6          | 1        | 2.94%   |
| PC Engines apu4        | 1        | 2.94%   |
| PC Engines APU2        | 1        | 2.94%   |
| MSI MS-7D54            | 1        | 2.94%   |
| MSI MS-7C96            | 1        | 2.94%   |
| MSI MS-7C56            | 1        | 2.94%   |
| MSI MS-7253            | 1        | 2.94%   |
| Lenovo ThinkPad        | 1        | 2.94%   |
| Lenovo ThinkCentre     | 1        | 2.94%   |
| Intel DCP847SKE        | 1        | 2.94%   |
| Intel D945GSEJT        | 1        | 2.94%   |
| HP t620                | 1        | 2.94%   |
| HP Compaq              | 1        | 2.94%   |
| Gigabyte Z590          | 1        | 2.94%   |
| Gigabyte X58A-UD5      | 1        | 2.94%   |
| Gigabyte X470          | 1        | 2.94%   |
| Gigabyte H81M-S2PV     | 1        | 2.94%   |
| Gigabyte BRi3(H)-10110 | 1        | 2.94%   |
| Gigabyte B450M         | 1        | 2.94%   |
| Dell OptiPlex          | 1        | 2.94%   |
| ASUS P10S-I            | 1        | 2.94%   |
| ASRock X570            | 1        | 2.94%   |
| ASRock FM2A88X         | 1        | 2.94%   |
| Apple PowerMac10       | 1        | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 6        | 17.65%  |
| Unknown | 6        | 17.65%  |
| 2020    | 5        | 14.71%  |
| 2021    | 3        | 8.82%   |
| 2018    | 2        | 5.88%   |
| 2015    | 2        | 5.88%   |
| 2014    | 2        | 5.88%   |
| 2022    | 1        | 2.94%   |
| 2016    | 1        | 2.94%   |
| 2012    | 1        | 2.94%   |
| 2011    | 1        | 2.94%   |
| 2009    | 1        | 2.94%   |
| 2008    | 1        | 2.94%   |
| 2007    | 1        | 2.94%   |
| 2006    | 1        | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 34       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 91.18%  |
| Yes  | 3        | 8.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 8        | 23.53%  |
| 16.01-24.0  | 7        | 20.59%  |
| 4.01-8.0    | 4        | 11.76%  |
| 8.01-16.0   | 4        | 11.76%  |
| 0.51-1.0    | 3        | 8.82%   |
| 2.01-3.0    | 2        | 5.88%   |
| 1.01-2.0    | 2        | 5.88%   |
| 32.01-64.0  | 1        | 2.94%   |
| 24.01-32.0  | 1        | 2.94%   |
| 64.01-256.0 | 1        | 2.94%   |
| 0.01-0.5    | 1        | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 27       | 79.41%  |
| 0        | 3        | 8.82%   |
| 0.51-1.0 | 2        | 5.88%   |
| 1.01-2.0 | 1        | 2.94%   |
| Unknown  | 1        | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 48.57%  |
| 2      | 8        | 22.86%  |
| 4      | 4        | 11.43%  |
| 3      | 3        | 8.57%   |
| 0      | 2        | 5.71%   |
| 6      | 1        | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 97.06%  |
| Yes       | 1        | 2.94%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 76.47%  |
| No        | 8        | 23.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 73.53%  |
| Yes       | 9        | 26.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 85.29%  |
| Yes       | 5        | 14.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 8        | 23.53%  |
| Poland      | 7        | 20.59%  |
| USA         | 6        | 17.65%  |
| UK          | 2        | 5.88%   |
| Switzerland | 2        | 5.88%   |
| Germany     | 2        | 5.88%   |
| Ukraine     | 1        | 2.94%   |
| Sweden      | 1        | 2.94%   |
| Romania     | 1        | 2.94%   |
| Hungary     | 1        | 2.94%   |
| France      | 1        | 2.94%   |
| Cyprus      | 1        | 2.94%   |
| Austria     | 1        | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Moscow          | 3        | 8.33%   |
| Wroclaw         | 2        | 5.56%   |
| Miedziana Gora  | 2        | 5.56%   |
| Zhukovskiy      | 1        | 2.78%   |
| Zagnansk        | 1        | 2.78%   |
| Wolfsburg       | 1        | 2.78%   |
| Wheaton         | 1        | 2.78%   |
| Voskresensk     | 1        | 2.78%   |
| Volgograd       | 1        | 2.78%   |
| Vienna          | 1        | 2.78%   |
| Varpalota       | 1        | 2.78%   |
| Syeverodonets'k | 1        | 2.78%   |
| Stockholm       | 1        | 2.78%   |
| St Petersburg   | 1        | 2.78%   |
| Poplar          | 1        | 2.78%   |
| Onalaska        | 1        | 2.78%   |
| Oensingen       | 1        | 2.78%   |
| Naters          | 1        | 2.78%   |
| Mogilno         | 1        | 2.78%   |
| Lyubertsy       | 1        | 2.78%   |
| London          | 1        | 2.78%   |
| Larnaca         | 1        | 2.78%   |
| Kingman         | 1        | 2.78%   |
| Irvine          | 1        | 2.78%   |
| Glendale        | 1        | 2.78%   |
| Giroussens      | 1        | 2.78%   |
| Gdansk          | 1        | 2.78%   |
| Erlangen        | 1        | 2.78%   |
| Cluj-Napoca     | 1        | 2.78%   |
| Burkatow        | 1        | 2.78%   |
| Ames            | 1        | 2.78%   |
| Akarp           | 1        | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 6        | 6      | 12.5%   |
| Seagate                            | 6        | 9      | 12.5%   |
| NVMe                               | 6        | 6      | 12.5%   |
| Toshiba                            | 4        | 4      | 8.33%   |
| Samsung Electronics                | 4        | 5      | 8.33%   |
| Kingston                           | 4        | 6      | 8.33%   |
| StoreJet                           | 1        | 1      | 2.08%   |
| SSDPR-CX                           | 1        | 1      | 2.08%   |
| SanDisk                            | 1        | 1      | 2.08%   |
| Product:              USB DISK 3.0 | 1        | 1      | 2.08%   |
| Product:              USB DISK 2.0 | 1        | 1      | 2.08%   |
| Phison                             | 1        | 1      | 2.08%   |
| Patriot                            | 1        | 1      | 2.08%   |
| OPENBSD                            | 1        | 1      | 2.08%   |
| Maxtor                             | 1        | 2      | 2.08%   |
| Intel                              | 1        | 2      | 2.08%   |
| HPE                                | 1        | 2      | 2.08%   |
| Hitachi                            | 1        | 1      | 2.08%   |
| HGST                               | 1        | 1      | 2.08%   |
| Generic                            | 1        | 1      | 2.08%   |
| Crucial                            | 1        | 1      | 2.08%   |
| ASMT                               | 1        | 1      | 2.08%   |
| Argon                              | 1        | 1      | 2.08%   |
| Apacer                             | 1        | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| WDC WDS240G2G0B-00EPW0 240GB                         | 1        | 2%      |
| WDC WD6400AARS-00Y5B1 640GB                          | 1        | 2%      |
| WDC WD20PURX-64P6ZY0 2TB                             | 1        | 2%      |
| WDC WD1600BEVE-00UYT0 160GB                          | 1        | 2%      |
| WDC WD10EADS-00M2B0 1TB                              | 1        | 2%      |
| WDC WD101KFBX-68R56N0 10TB                           | 1        | 2%      |
| Toshiba MQ04ABF100 1TB                               | 1        | 2%      |
| Toshiba MK3276GSX -63 320GB                          | 1        | 2%      |
| Toshiba MK2555GSX 250GB                              | 1        | 2%      |
| Toshiba DT01ACA050 500GB                             | 1        | 2%      |
| StoreJet Transcend 120GB                             | 1        | 2%      |
| SSDPR-CX 400-512-G2 512GB                            | 1        | 2%      |
| Seagate ST3250318AS 250GB                            | 1        | 2%      |
| Seagate ST250DM000-1BD141 250GB                      | 1        | 2%      |
| Seagate ST2000VN000-1HJ164 2TB                       | 1        | 2%      |
| Seagate ST2000NE0025-2FL101 2TB                      | 1        | 2%      |
| Seagate ST2000DM008-2FR102 2TB                       | 1        | 2%      |
| Seagate ST1000LM035-1RK172 1TB                       | 1        | 2%      |
| Seagate BUP Slim BL 1TB                              | 1        | 2%      |
| SanDisk Ultra 32GB                                   | 1        | 2%      |
| Samsung SSD 860 EVO 500GB                            | 1        | 2%      |
| Samsung SSD 860 EVO 250GB                            | 1        | 2%      |
| Samsung HD501LJ 500GB                                | 1        | 2%      |
| Samsung Flash Drive FIT 32GB                         | 1        | 2%      |
| Product:              USB DISK 3.0 USB DISK 3.0 64GB | 1        | 2%      |
| Product:              USB DISK 2.0 USB DISK 2.0 4GB  | 1        | 2%      |
| Phison SATA SSD 16GB                                 | 1        | 2%      |
| Patriot Burst 120GB                                  | 1        | 2%      |
| OPENBSD SR RAID 1 1TB                                | 1        | 2%      |
| NVMe WDS500G3X0C-00SJ 500GB                          | 1        | 2%      |
| NVMe WDC WDS100T2B0C- 1TB                            | 1        | 2%      |
| NVMe TOSHIBA-RC100 240GB                             | 1        | 2%      |
| NVMe Samsung SSD 980 2TB                             | 1        | 2%      |
| NVMe Samsung SSD 970 250GB                           | 1        | 2%      |
| NVMe PCIe SSD 512GB                                  | 1        | 2%      |
| Maxtor 6Y160P0 160GB                                 | 1        | 2%      |
| Maxtor 6Y080L0 82GB                                  | 1        | 2%      |
| Kingston SV300S37A240G 240GB                         | 1        | 2%      |
| Kingston SUV500MS480G 480GB                          | 1        | 2%      |
| Kingston SUV500MS240G 240GB                          | 1        | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 6        | 9      | 20%     |
| WDC                                | 5        | 5      | 16.67%  |
| Toshiba                            | 4        | 4      | 13.33%  |
| NVMe                               | 3        | 3      | 10%     |
| Samsung Electronics                | 2        | 3      | 6.67%   |
| StoreJet                           | 1        | 1      | 3.33%   |
| SSDPR-CX                           | 1        | 1      | 3.33%   |
| Product:              USB DISK 3.0 | 1        | 1      | 3.33%   |
| Product:              USB DISK 2.0 | 1        | 1      | 3.33%   |
| OPENBSD                            | 1        | 1      | 3.33%   |
| Maxtor                             | 1        | 2      | 3.33%   |
| Hitachi                            | 1        | 1      | 3.33%   |
| HGST                               | 1        | 1      | 3.33%   |
| Generic                            | 1        | 1      | 3.33%   |
| ASMT                               | 1        | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 4        | 6      | 22.22%  |
| NVMe                | 3        | 3      | 16.67%  |
| Samsung Electronics | 2        | 2      | 11.11%  |
| WDC                 | 1        | 1      | 5.56%   |
| SanDisk             | 1        | 1      | 5.56%   |
| Phison              | 1        | 1      | 5.56%   |
| Patriot             | 1        | 1      | 5.56%   |
| Intel               | 1        | 2      | 5.56%   |
| HPE                 | 1        | 2      | 5.56%   |
| Crucial             | 1        | 1      | 5.56%   |
| Argon               | 1        | 1      | 5.56%   |
| Apacer              | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 35     | 54.29%  |
| SSD  | 16       | 22     | 45.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 57     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 26       | 38     | 68.42%  |
| 0.51-1.0   | 7        | 9      | 18.42%  |
| 1.01-2.0   | 4        | 9      | 10.53%  |
| 4.01-10.0  | 1        | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 12       | 34.29%  |
| 101-250        | 9        | 25.71%  |
| 21-50          | 5        | 14.29%  |
| 1-20           | 3        | 8.57%   |
| 51-100         | 3        | 8.57%   |
| 501-1000       | 2        | 5.71%   |
| More than 3000 | 1        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 22       | 64.71%  |
| 21-50     | 5        | 14.71%  |
| 101-250   | 4        | 11.76%  |
| 2001-3000 | 1        | 2.94%   |
| 501-1000  | 1        | 2.94%   |
| 51-100    | 1        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD1600BEVE-00UYT0 160GB     | 1        | 1      | 20%     |
| WDC WD10EADS-00M2B0 1TB         | 1        | 1      | 20%     |
| Toshiba MQ04ABF100 1TB          | 1        | 1      | 20%     |
| Seagate ST250DM000-1BD141 250GB | 1        | 1      | 20%     |
| Kingston SMS200S330G 32GB       | 1        | 2      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 2        | 2      | 40%     |
| Toshiba  | 1        | 1      | 20%     |
| Seagate  | 1        | 1      | 20%     |
| Kingston | 1        | 2      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Toshiba | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 80%     |
| SSD  | 1        | 2      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 23       | 36     | 60.53%  |
| Detected | 9        | 14     | 23.68%  |
| Malfunc  | 5        | 6      | 13.16%  |
| Failed   | 1        | 1      | 2.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 13       | 41.94%  |
| AMD                    | 11       | 35.48%  |
| SanDisk                | 2        | 6.45%   |
| VIA Technologies       | 1        | 3.23%   |
| Toshiba                | 1        | 3.23%   |
| Samsung Electronics    | 1        | 3.23%   |
| Phison Electronics     | 1        | 3.23%   |
| HighPoint Technologies | 1        | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8        | 21.05%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2        | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 5.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 5.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 5.26%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 2.63%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1        | 2.63%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1        | 2.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 2.63%   |
| SanDisk unknown                                                                | 1        | 2.63%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 2.63%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 2.63%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 2.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 2.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 2.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 2.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1        | 2.63%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 1        | 2.63%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 1        | 2.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1        | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 2.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.63%   |
| HighPoint unknown                                                              | 1        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 62.5%   |
| IDE  | 6        | 18.75%  |
| NVMe | 5        | 15.63%  |
| RAID | 1        | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 13       | 38.24%  |
| AMD     | 12       | 35.29%  |
| ARM     | 8        | 23.53%  |
| PowerPC | 1        | 2.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| ARM Cortex-A72 r0p3                                                                   | 4        | 11.76%  |
| ARM Cortex-A53 r0p4                                                                   | 2        | 5.88%   |
| AMD Ryzen 7 5800X 8-Core Processor                                                    | 2        | 5.88%   |
| AMD GX-412TC SOC                                                                      | 2        | 5.88%   |
| PowerPC 7447A (Revision 0x102)                                                        | 1        | 2.94%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                                                   | 1        | 2.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                                     | 1        | 2.94%   |
| Intel Core i7 CPU 970 @ 3.20GHz                                                       | 1        | 2.94%   |
| Intel Core i5-4570S CPU @ 2.90GHz                                                     | 1        | 2.94%   |
| Intel Core i3-10110U CPU @ 2.10GHz                                                    | 1        | 2.94%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                                                  | 1        | 2.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                                                  | 1        | 2.94%   |
| Intel Core 2 CPU 6400 @ 2.13GHz                                                       | 1        | 2.94%   |
| Intel Celeron CPU G1820 @ 2.70GHz                                                     | 1        | 2.94%   |
| Intel Celeron CPU 847E @ 1.10GHz                                                      | 1        | 2.94%   |
| Intel Celeron CPU 3865U @ 1.80GHz                                                     | 1        | 2.94%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)                              | 1        | 2.94%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz                                               | 1        | 2.94%   |
| ARM Cortex-A8 r3p2                                                                    | 1        | 2.94%   |
| ARM Cortex-A7 r0p4                                                                    | 1        | 2.94%   |
| AMD Ryzen 7 5700G with Radeon Graphics                                                | 1        | 2.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor                                                 | 1        | 2.94%   |
| AMD Ryzen 5 3600 6-Core Processor                                                     | 1        | 2.94%   |
| AMD Ryzen 3 3100 4-Core Processor                                                     | 1        | 2.94%   |
| AMD GX-415GA SOC with Radeon HD Graphics                                              | 1        | 2.94%   |
| AMD G-T48E Processor                                                                  | 1        | 2.94%   |
| AMD Athlon 64 X2 Dual Core Processor 4000+ ("AuthenticAMD" 686-class, 512KB L2 cache) | 1        | 2.94%   |
| AMD A10-6800K APU with Radeon HD Graphics                                             | 1        | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| ARM Cortex       | 8        | 23.53%  |
| AMD Ryzen 7      | 4        | 11.76%  |
| Intel Celeron    | 3        | 8.82%   |
| AMD GX           | 3        | 8.82%   |
| Other            | 2        | 5.88%   |
| Intel Core i7    | 2        | 5.88%   |
| Intel Core 2 Duo | 2        | 5.88%   |
| Intel Xeon       | 1        | 2.94%   |
| Intel Core i5    | 1        | 2.94%   |
| Intel Core i3    | 1        | 2.94%   |
| Intel Core 2     | 1        | 2.94%   |
| Intel Atom       | 1        | 2.94%   |
| AMD Ryzen 5      | 1        | 2.94%   |
| AMD Ryzen 3      | 1        | 2.94%   |
| AMD G            | 1        | 2.94%   |
| AMD Athlon 64 X2 | 1        | 2.94%   |
| AMD A10          | 1        | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 38.24%  |
| 4       | 7        | 20.59%  |
| 2       | 6        | 17.65%  |
| 1       | 3        | 8.82%   |
| 16      | 2        | 5.88%   |
| 8       | 2        | 5.88%   |
| 6       | 1        | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 17       | 50%     |
| Unknown | 16       | 47.06%  |
| 2       | 1        | 2.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 47.06%  |
| 1       | 14       | 41.18%  |
| 2       | 4        | 11.76%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 13       | 38.24%  |
| KabyLake    | 3        | 8.82%   |
| Zen 2       | 2        | 5.88%   |
| Puma        | 2        | 5.88%   |
| Penryn      | 2        | 5.88%   |
| Haswell     | 2        | 5.88%   |
| Zen+        | 1        | 2.94%   |
| Zen 3       | 1        | 2.94%   |
| Westmere    | 1        | 2.94%   |
| Skylake     | 1        | 2.94%   |
| SandyBridge | 1        | 2.94%   |
| Piledriver  | 1        | 2.94%   |
| Jaguar      | 1        | 2.94%   |
| Core        | 1        | 2.94%   |
| Bonnell     | 1        | 2.94%   |
| Bobcat      | 1        | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 11       | 45.83%  |
| AMD               | 11       | 45.83%  |
| Nvidia            | 1        | 4.17%   |
| ASPEED Technology | 1        | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2        | 8%      |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2        | 8%      |
| Nvidia GF110 [GeForce GTX 580]                                                | 1        | 4%      |
| Intel UHD Graphics 620                                                        | 1        | 4%      |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 1        | 4%      |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1        | 4%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 4%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1        | 4%      |
| Intel HD Graphics 610                                                         | 1        | 4%      |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1        | 4%      |
| Intel 82Q963/Q965 Integrated Graphics Controller                              | 1        | 4%      |
| Intel 82Q35 Express Integrated Graphics Controller                            | 1        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1        | 4%      |
| ASPEED Technology ASPEED Graphics Family                                      | 1        | 4%      |
| AMD Wrestler [Radeon HD 6250]                                                 | 1        | 4%      |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                     | 1        | 4%      |
| AMD RV280 [Radeon 9200]                                                       | 1        | 4%      |
| AMD Richland [Radeon HD 8670D]                                                | 1        | 4%      |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                | 1        | 4%      |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 1        | 4%      |
| AMD Kabini [Radeon HD 8330E]                                                  | 1        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1        | 4%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1        | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x AMD    | 11       | 32.35%  |
| Other      | 10       | 29.41%  |
| 1 x Intel  | 8        | 23.53%  |
| 2 x Intel  | 3        | 8.82%   |
| 1 x Nvidia | 1        | 2.94%   |
| 1 x ASPEED | 1        | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 22       | 62.86%  |
| Unknown | 13       | 37.14%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2        | 15.38%  |
| Ancor Communications | 2        | 15.38%  |
| SHI                  | 1        | 7.69%   |
| Philips              | 1        | 7.69%   |
| NEC Computers        | 1        | 7.69%   |
| Lenovo               | 1        | 7.69%   |
| Iiyama               | 1        | 7.69%   |
| Goldstar             | 1        | 7.69%   |
| Dell                 | 1        | 7.69%   |
| AOC                  | 1        | 7.69%   |
| Acer                 | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                   | 1        | 7.69%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1        | 7.69%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 7.69%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch             | 1        | 7.69%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch            | 1        | 7.69%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch               | 1        | 7.69%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                 | 1        | 7.69%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1        | 7.69%   |
| Dell P2312H DEL4076 1920x1080 510x290mm 23.1-inch                     | 1        | 7.69%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                        | 1        | 7.69%   |
| Ancor Communications PA249 ACI24B2 1920x1200 520x320mm 24.0-inch      | 1        | 7.69%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch  | 1        | 7.69%   |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 4        | 33.33%  |
| 3840x2160 (4K)    | 2        | 16.67%  |
| 1440x900 (WXGA+)  | 2        | 16.67%  |
| 3440x1440         | 1        | 8.33%   |
| 1920x1200 (WUXGA) | 1        | 8.33%   |
| 1360x768          | 1        | 8.33%   |
| 1280x1024 (SXGA)  | 1        | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 31     | 3        | 25%     |
| 23     | 2        | 16.67%  |
| 21     | 2        | 16.67%  |
| 34     | 1        | 8.33%   |
| 24     | 1        | 8.33%   |
| 19     | 1        | 8.33%   |
| 17     | 1        | 8.33%   |
| 14     | 1        | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 601-700     | 3        | 25%     |
| 501-600     | 3        | 25%     |
| 401-500     | 3        | 25%     |
| 701-800     | 1        | 8.33%   |
| 301-350     | 1        | 8.33%   |
| 201-300     | 1        | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 7        | 58.33%  |
| 16/10 | 3        | 25%     |
| 5/4   | 1        | 8.33%   |
| 21/9  | 1        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 4        | 33.33%  |
| 201-250        | 4        | 33.33%  |
| 81-90          | 1        | 8.33%   |
| 251-300        | 1        | 8.33%   |
| 151-200        | 1        | 8.33%   |
| 141-150        | 1        | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 41.67%  |
| 121-160 | 3        | 25%     |
| 101-120 | 3        | 25%     |
| 1-50    | 1        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 18       | 51.43%  |
| 1     | 16       | 45.71%  |
| 2     | 1        | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 41.67%  |
| Realtek Semiconductor           | 9        | 25%     |
| Qualcomm Atheros Communications | 3        | 8.33%   |
| TP-Link                         | 2        | 5.56%   |
| Qualcomm Atheros                | 2        | 5.56%   |
| VIA Technologies                | 1        | 2.78%   |
| LG Electronics                  | 1        | 2.78%   |
| Broadcom                        | 1        | 2.78%   |
| Apple                           | 1        | 2.78%   |
| 3Com                            | 1        | 2.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 20.51%  |
| Intel I211 Gigabit Network Connection                             | 4        | 10.26%  |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 7.69%   |
| Intel I210 Gigabit Network Connection                             | 2        | 5.13%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 2.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 2.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 2.56%   |
| LG Optimus Android Phone [USB tethering mode]                     | 1        | 2.56%   |
| Intel Wireless 7260                                               | 1        | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 2.56%   |
| Intel Ultimate N WiFi Link 5300                                   | 1        | 2.56%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.56%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.56%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 2.56%   |
| Intel Centrino Wireless-N 2230                                    | 1        | 2.56%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 2.56%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1        | 2.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 2.56%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 2.56%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1        | 2.56%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 40%     |
| Qualcomm Atheros Communications | 3        | 30%     |
| TP-Link                         | 2        | 20%     |
| Qualcomm Atheros                | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                  | 3        | 30%     |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]              | 1        | 10%     |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]     | 1        | 10%     |
| Qualcomm Atheros AR9485 Wireless Network Adapter | 1        | 10%     |
| Intel Wireless 7260                              | 1        | 10%     |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz           | 1        | 10%     |
| Intel Ultimate N WiFi Link 5300                  | 1        | 10%     |
| Intel Centrino Wireless-N 2230                   | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 50%     |
| Realtek Semiconductor | 9        | 32.14%  |
| VIA Technologies      | 1        | 3.57%   |
| Qualcomm Atheros      | 1        | 3.57%   |
| Broadcom              | 1        | 3.57%   |
| Apple                 | 1        | 3.57%   |
| 3Com                  | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 28.57%  |
| Intel I211 Gigabit Network Connection                             | 4        | 14.29%  |
| Intel I210 Gigabit Network Connection                             | 2        | 7.14%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 3.57%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.57%   |
| Intel Ethernet Connection I217-V                                  | 1        | 3.57%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 3.57%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 3.57%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.57%   |
| Intel 82567LM Gigabit Network Connection                          | 1        | 3.57%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 3.57%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 3.57%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 3.57%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1        | 3.57%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 70.27%  |
| WiFi     | 10       | 27.03%  |
| Modem    | 1        | 2.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 76.92%  |
| WiFi     | 6        | 23.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 44.12%  |
| 0     | 8        | 23.53%  |
| 2     | 7        | 20.59%  |
| 7     | 1        | 2.94%   |
| 6     | 1        | 2.94%   |
| 4     | 1        | 2.94%   |
| 3     | 1        | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 60%     |
| Qualcomm Atheros Communications | 1        | 20%     |
| Cambridge Silicon Radio         | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 20%     |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 20%     |
| Intel Bluetooth wireless interface                  | 1        | 20%     |
| Intel AX210 Bluetooth                               | 1        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 11       | 42.31%  |
| AMD                 | 10       | 38.46%  |
| C-Media Electronics | 2        | 7.69%   |
| VIA Technologies    | 1        | 3.85%   |
| Nvidia              | 1        | 3.85%   |
| Blue Microphones    | 1        | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 4        | 11.43%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                          | 2        | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2        | 5.71%   |
| C-Media Electronics FX-AUDIO                                            | 2        | 5.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 2        | 5.71%   |
| AMD FCH Azalia Controller                                               | 2        | 5.71%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller          | 1        | 2.86%   |
| Nvidia GF110 High Definition Audio Controller                           | 1        | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1        | 2.86%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 1        | 2.86%   |
| Intel Sunrise Point-LP HD Audio                                         | 1        | 2.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 2.86%   |
| Intel Comet Lake PCH-LP cAVS                                            | 1        | 2.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                        | 1        | 2.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                          | 1        | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 1        | 2.86%   |
| Blue Microphones Yeti Stereo Microphone                                 | 1        | 2.86%   |
| AMD Wrestler HDMI Audio                                                 | 1        | 2.86%   |
| AMD Trinity HDMI Audio Controller                                       | 1        | 2.86%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 1        | 2.86%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                         | 1        | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 1        | 2.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 2.86%   |
| AMD Navi 10 HDMI Audio                                                  | 1        | 2.86%   |
| AMD Kabini HDMI/DP Audio                                                | 1        | 2.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 1        | 2.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 1        | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 50%     |
| Transcend           | 1        | 25%     |
| SK hynix            | 1        | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s     | 1        | 20%     |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s   | 1        | 20%     |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 20%     |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 20%     |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s   | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 1        | 50%     |
| DDR2 | 1        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| SODIMM | 1        | 50%     |
| DIMM   | 1        | 50%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 4096 | 1        | 50%     |
| 1024 | 1        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 1        | 50%     |
| 667   | 1        | 50%     |

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
| Z-Star Microelectronics | 1        | 50%     |
| Microdia                | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Integrated Camera        | 1        | 50%     |
| Microdia Ltd., USB  Live camera | 1        | 50%     |

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
| 0     | 19       | 54.29%  |
| 1     | 9        | 25.71%  |
| 2     | 7        | 20%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 10       | 45.45%  |
| Graphics card            | 6        | 27.27%  |
| Net/wireless             | 2        | 9.09%   |
| Storage/raid             | 1        | 4.55%   |
| Sound                    | 1        | 4.55%   |
| Net/ethernet             | 1        | 4.55%   |
| Firewire controller      | 1        | 4.55%   |

