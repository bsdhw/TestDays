TrueNAS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for TrueNAS.

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

Total: 39

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | ProLiant ML10 v2            | [72254b033d](https://bsd-hardware.info/?probe=72254b033d) | Jun 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [378021707a](https://bsd-hardware.info/?probe=378021707a) | Apr 17, 2022 |
| ASRock        | X570M Pro4                  | [e245cecbe8](https://bsd-hardware.info/?probe=e245cecbe8) | Apr 06, 2022 |
| ASUSTek       | P10S-I Series               | [190fe4d13f](https://bsd-hardware.info/?probe=190fe4d13f) | Mar 24, 2022 |
| Supermicro    | X9DRD-7LN4F                 | [ea62f49750](https://bsd-hardware.info/?probe=ea62f49750) | Feb 15, 2022 |
| Supermicro    | X8STi                       | [970e2c91ec](https://bsd-hardware.info/?probe=970e2c91ec) | Feb 15, 2022 |
| Supermicro    | X9DRD-7LN4F                 | [74dffd5c4f](https://bsd-hardware.info/?probe=74dffd5c4f) | Feb 15, 2022 |
| Unknown       | Unknown                     | [bd78c2db3d](https://bsd-hardware.info/?probe=bd78c2db3d) | Jan 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| HP            | ProLiant ML150 G6           | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| Supermicro    | X8SIE 0001                  | [fbd2abda35](https://bsd-hardware.info/?probe=fbd2abda35) | Oct 17, 2021 |
| ASRock        | B560M Pro4/ac               | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| Supermicro    | X8SIE 0001                  | [f679c0bf61](https://bsd-hardware.info/?probe=f679c0bf61) | Jul 22, 2021 |
| Supermicro    | X8SIE 0001                  | [d739af226b](https://bsd-hardware.info/?probe=d739af226b) | Jul 20, 2021 |
| ASUSTek       | TUF Z270 MARK 2             | [fd0f333074](https://bsd-hardware.info/?probe=fd0f333074) | Jul 15, 2021 |
| Unknown       | Unknown                     | [df39a39ec7](https://bsd-hardware.info/?probe=df39a39ec7) | Jul 15, 2021 |
| Unknown       | Unknown                     | [968859e99d](https://bsd-hardware.info/?probe=968859e99d) | Jun 03, 2021 |
| ASRock        | C2750D4I                    | [e08a5e6f7c](https://bsd-hardware.info/?probe=e08a5e6f7c) | May 31, 2021 |
| ASRock        | C2750D4I                    | [9bd610c0ea](https://bsd-hardware.info/?probe=9bd610c0ea) | May 31, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [e308becda4](https://bsd-hardware.info/?probe=e308becda4) | May 29, 2021 |
| Lenovo        | ThinkServer TS440           | [6390c16543](https://bsd-hardware.info/?probe=6390c16543) | May 28, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [cec3cb521d](https://bsd-hardware.info/?probe=cec3cb521d) | May 20, 2021 |
| Unknown       | Unknown                     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | [760e148164](https://bsd-hardware.info/?probe=760e148164) | Feb 19, 2021 |
| Unknown       | Unknown                     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| TYAN Compu... | S5512                       | [6a6164af73](https://bsd-hardware.info/?probe=6a6164af73) | Jan 27, 2021 |
| Unknown       | Unknown                     | [96ca836be9](https://bsd-hardware.info/?probe=96ca836be9) | Jan 19, 2021 |
| HP            | ProLiant MicroServer Gen... | [415023d5a1](https://bsd-hardware.info/?probe=415023d5a1) | Jan 10, 2021 |
| Gigabyte      | GA-A75-UD4H                 | [98fdc2713d](https://bsd-hardware.info/?probe=98fdc2713d) | Dec 18, 2020 |
| Gigabyte      | GA-A75-UD4H                 | [fb58243913](https://bsd-hardware.info/?probe=fb58243913) | Dec 18, 2020 |
| HP            | 3397                        | [3d51aa7204](https://bsd-hardware.info/?probe=3d51aa7204) | Dec 18, 2020 |
| Unknown       | Unknown                     | [aa113d54a8](https://bsd-hardware.info/?probe=aa113d54a8) | Dec 16, 2020 |
| Supermicro    | X9SPV-F/LN4F                | [24031a56b9](https://bsd-hardware.info/?probe=24031a56b9) | Dec 16, 2020 |
| Gigabyte      | H97-D3H-CF                  | [4d6f6bb683](https://bsd-hardware.info/?probe=4d6f6bb683) | Dec 16, 2020 |
| ASRock        | C2750D4I                    | [8328ebb73d](https://bsd-hardware.info/?probe=8328ebb73d) | Dec 16, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| TrueNAS 12.2-p2  | 8        | 25%     |
| TrueNAS 12.2-p6  | 6        | 18.75%  |
| TrueNAS 12.2-p9  | 4        | 12.5%   |
| TrueNAS 12.2-p12 | 4        | 12.5%   |
| TrueNAS 12.2-RC3 | 3        | 9.38%   |
| TrueNAS 12.2-p10 | 2        | 6.25%   |
| TrueNAS 12.3-p1  | 1        | 3.13%   |
| TrueNAS 12.2-p3  | 1        | 3.13%   |
| TrueNAS 12.2-p14 | 1        | 3.13%   |
| TrueNAS 12.2-p11 | 1        | 3.13%   |
| TrueNAS 12.2     | 1        | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TrueNAS | 31       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 31       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 28       | 90.32%  |
| helloDesktop | 2        | 6.45%   |
| TWM          | 1        | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 30       | 96.77%  |
| X11     | 1        | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 31       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 31       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 19       | 61.29%  |
| EFI  | 12       | 38.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 28       | 90.32%  |
| XXX     | 2        | 6.45%   |
| Unknown | 1        | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 31       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6        | 19.35%  |
| Supermicro          | 5        | 16.13%  |
| Gigabyte Technology | 5        | 16.13%  |
| ASUSTek Computer    | 5        | 16.13%  |
| Hewlett-Packard     | 4        | 12.9%   |
| ASRock              | 4        | 12.9%   |
| TYAN Computer       | 1        | 3.23%   |
| Lenovo              | 1        | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 6        | 19.35%  |
| TYAN S5512                          | 1        | 3.23%   |
| Supermicro X9SPV-F/LN4F             | 1        | 3.23%   |
| Supermicro X9SCL/X9SCM              | 1        | 3.23%   |
| Supermicro X9DRD-7LN4F              | 1        | 3.23%   |
| Supermicro X8STi                    | 1        | 3.23%   |
| Supermicro ReadyDATA 5200           | 1        | 3.23%   |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1        | 3.23%   |
| HP ProLiant ML150 G6                | 1        | 3.23%   |
| HP ProLiant ML10 v2                 | 1        | 3.23%   |
| HP ProLiant MicroServer Gen8        | 1        | 3.23%   |
| HP Compaq Elite 8300 SFF            | 1        | 3.23%   |
| Gigabyte H97-D3H                    | 1        | 3.23%   |
| Gigabyte GA-A75-UD4H                | 1        | 3.23%   |
| Gigabyte B550I AORUS PRO AX         | 1        | 3.23%   |
| Gigabyte B450M DS3H                 | 1        | 3.23%   |
| Gigabyte 990FXA-UD3                 | 1        | 3.23%   |
| ASUS TUF Z270 MARK 2                | 1        | 3.23%   |
| ASUS P10S-I Series                  | 1        | 3.23%   |
| ASUS M5A99X EVO R2.0                | 1        | 3.23%   |
| ASUS M5A78L-M/USB3                  | 1        | 3.23%   |
| ASUS M5A78L-M PLUS/USB3             | 1        | 3.23%   |
| ASRock X570M Pro4                   | 1        | 3.23%   |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1        | 3.23%   |
| ASRock C2750D4I                     | 1        | 3.23%   |
| ASRock B560M Pro4/ac                | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 6        | 19.35%  |
| HP ProLiant                     | 3        | 9.68%   |
| ASUS M5A78L-M                   | 2        | 6.45%   |
| TYAN S5512                      | 1        | 3.23%   |
| Supermicro X9SPV-F              | 1        | 3.23%   |
| Supermicro X9SCL                | 1        | 3.23%   |
| Supermicro X9DRD-7LN4F          | 1        | 3.23%   |
| Supermicro X8STi                | 1        | 3.23%   |
| Supermicro ReadyDATA            | 1        | 3.23%   |
| Lenovo 70AQ0009UX               | 1        | 3.23%   |
| HP Compaq                       | 1        | 3.23%   |
| Gigabyte H97-D3H                | 1        | 3.23%   |
| Gigabyte GA-A75-UD4H            | 1        | 3.23%   |
| Gigabyte B550I                  | 1        | 3.23%   |
| Gigabyte B450M                  | 1        | 3.23%   |
| Gigabyte 990FXA-UD3             | 1        | 3.23%   |
| ASUS TUF                        | 1        | 3.23%   |
| ASUS P10S-I                     | 1        | 3.23%   |
| ASUS M5A99X                     | 1        | 3.23%   |
| ASRock X570M                    | 1        | 3.23%   |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1        | 3.23%   |
| ASRock C2750D4I                 | 1        | 3.23%   |
| ASRock B560M                    | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 19.35%  |
| 2014    | 4        | 12.9%   |
| 2019    | 3        | 9.68%   |
| 2018    | 3        | 9.68%   |
| 2016    | 3        | 9.68%   |
| 2013    | 3        | 9.68%   |
| 2012    | 3        | 9.68%   |
| 2011    | 2        | 6.45%   |
| 2021    | 1        | 3.23%   |
| 2020    | 1        | 3.23%   |
| 2010    | 1        | 3.23%   |
| 2009    | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 10       | 32.26%  |
| 16.01-24.0  | 10       | 32.26%  |
| 64.01-256.0 | 4        | 12.9%   |
| 24.01-32.0  | 3        | 9.68%   |
| 8.01-16.0   | 3        | 9.68%   |
| 4.01-8.0    | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 12       | 38.71%  |
| 1.01-2.0   | 9        | 29.03%  |
| 2.01-3.0   | 3        | 9.68%   |
| 16.01-24.0 | 2        | 6.45%   |
| 4.01-8.0   | 1        | 3.23%   |
| 32.01-64.0 | 1        | 3.23%   |
| 3.01-4.0   | 1        | 3.23%   |
| 8.01-16.0  | 1        | 3.23%   |
| 0.01-0.5   | 1        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 6        | 18.75%  |
| 0      | 6        | 18.75%  |
| 17     | 2        | 6.25%   |
| 9      | 2        | 6.25%   |
| 6      | 2        | 6.25%   |
| 5      | 2        | 6.25%   |
| 4      | 2        | 6.25%   |
| 27     | 1        | 3.13%   |
| 21     | 1        | 3.13%   |
| 19     | 1        | 3.13%   |
| 16     | 1        | 3.13%   |
| 12     | 1        | 3.13%   |
| 11     | 1        | 3.13%   |
| 10     | 1        | 3.13%   |
| 8      | 1        | 3.13%   |
| 7      | 1        | 3.13%   |
| 2      | 1        | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 93.75%  |
| Yes       | 2        | 6.25%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 93.55%  |
| Yes       | 2        | 6.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 93.55%  |
| Yes       | 2        | 6.45%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 29.03%  |
| Australia   | 4        | 12.9%   |
| Thailand    | 2        | 6.45%   |
| Switzerland | 2        | 6.45%   |
| Germany     | 2        | 6.45%   |
| Czechia     | 2        | 6.45%   |
| Spain       | 1        | 3.23%   |
| Romania     | 1        | 3.23%   |
| Norway      | 1        | 3.23%   |
| Nicaragua   | 1        | 3.23%   |
| Greece      | 1        | 3.23%   |
| France      | 1        | 3.23%   |
| Estonia     | 1        | 3.23%   |
| Canada      | 1        | 3.23%   |
| Brazil      | 1        | 3.23%   |
| Belgium     | 1        | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Melbourne         | 3        | 9.68%   |
| Springfield       | 2        | 6.45%   |
| Brno              | 2        | 6.45%   |
| Bangkok           | 2        | 6.45%   |
| Yverdon-les-Bains | 1        | 3.23%   |
| Willisau          | 1        | 3.23%   |
| Tartu             | 1        | 3.23%   |
| Sydney            | 1        | 3.23%   |
| Skiptvet          | 1        | 3.23%   |
| Raleigh           | 1        | 3.23%   |
| Perry Hall        | 1        | 3.23%   |
| Ougree            | 1        | 3.23%   |
| Northville        | 1        | 3.23%   |
| Managua           | 1        | 3.23%   |
| Lüneburg         | 1        | 3.23%   |
| Lubbock           | 1        | 3.23%   |
| JaraguÃ¡ do Sul | 1        | 3.23%   |
| Fontaine-le-Comte | 1        | 3.23%   |
| Fayetteville      | 1        | 3.23%   |
| East Granby       | 1        | 3.23%   |
| Dresden           | 1        | 3.23%   |
| Clare             | 1        | 3.23%   |
| Calgary           | 1        | 3.23%   |
| Bucharest         | 1        | 3.23%   |
| Athens            | 1        | 3.23%   |
| Algete            | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 68     | 21.21%  |
| Seagate             | 11       | 49     | 16.67%  |
| Samsung Electronics | 7        | 10     | 10.61%  |
| Toshiba             | 5        | 10     | 7.58%   |
| Hitachi             | 5        | 16     | 7.58%   |
| Kingston            | 4        | 9      | 6.06%   |
| Crucial             | 4        | 5      | 6.06%   |
| SanDisk             | 3        | 3      | 4.55%   |
| HPT                 | 2        | 31     | 3.03%   |
| Hewlett-Packard     | 2        | 8      | 3.03%   |
| WD MediaMax         | 1        | 3      | 1.52%   |
| SPCC                | 1        | 1      | 1.52%   |
| PNY                 | 1        | 1      | 1.52%   |
| Mushkin             | 1        | 1      | 1.52%   |
| Intel               | 1        | 2      | 1.52%   |
| HGST                | 1        | 10     | 1.52%   |
| China               | 1        | 1      | 1.52%   |
| Apacer              | 1        | 1      | 1.52%   |
| AMD                 | 1        | 2      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 4        | 2.8%    |
| Samsung SSD 860 EVO 250GB           | 4        | 2.8%    |
| WDC WD40EFRX-68N32N0 4TB            | 3        | 2.1%    |
| WDC WD60EFRX-68MYMN1 6TB            | 2        | 1.4%    |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 1.4%    |
| WDC WD30EFRX-68AX9N0 3TB            | 2        | 1.4%    |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 1.4%    |
| WDC WD20EFRX-68AX9N0 2TB            | 2        | 1.4%    |
| Seagate ST500DM002-1BD142 500GB     | 2        | 1.4%    |
| Kingston SA400S37120G 120GB         | 2        | 1.4%    |
| HPT DISK 0_9 3TB                    | 2        | 1.4%    |
| HPT DISK 0_8 3TB                    | 2        | 1.4%    |
| HPT DISK 0_7 3TB                    | 2        | 1.4%    |
| HPT DISK 0_6 3TB                    | 2        | 1.4%    |
| HPT DISK 0_5 18TB                   | 2        | 1.4%    |
| HPT DISK 0_4 18TB                   | 2        | 1.4%    |
| HPT DISK 0_3 3TB                    | 2        | 1.4%    |
| HPT DISK 0_2 3TB                    | 2        | 1.4%    |
| HPT DISK 0_14 3TB                   | 2        | 1.4%    |
| HPT DISK 0_13 2TB                   | 2        | 1.4%    |
| HPT DISK 0_12 1TB                   | 2        | 1.4%    |
| HPT DISK 0_11 1TB                   | 2        | 1.4%    |
| HPT DISK 0_10 1TB                   | 2        | 1.4%    |
| HPT DISK 0_1 6TB                    | 2        | 1.4%    |
| HPT DISK 0_0 4TB                    | 2        | 1.4%    |
| WDC WD80EFAX-68LHPN0 8TB            | 1        | 0.7%    |
| WDC WD8004FRYZ-01VAEB0 8TB          | 1        | 0.7%    |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1        | 0.7%    |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.7%    |
| WDC WD5000AAKX-00U6AA0 500GB        | 1        | 0.7%    |
| WDC WD30PURX-64P6ZY0 3TB            | 1        | 0.7%    |
| WDC WD30EZRX-00MMMB0 3TB            | 1        | 0.7%    |
| WDC WD30EFRX-68N32N0 3TB            | 1        | 0.7%    |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1        | 0.7%    |
| WDC WD3001FFSX-68JNUN0 3TB          | 1        | 0.7%    |
| WDC WD3000F9YZ-09N20L1 3TB          | 1        | 0.7%    |
| WDC WD3000F9YZ-09N20L0 3TB          | 1        | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.7%    |
| WDC WD2002FFSX-68PF8N0 2TB          | 1        | 0.7%    |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 0.7%    |
| WDC WD10JPVX-80JC3T0 1TB            | 1        | 0.7%    |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 0.7%    |
| WDC WD10EURX-61C57Y0 1TB            | 1        | 0.7%    |
| WDC WD100EMAZ-00WJTA0 10TB          | 1        | 0.7%    |
| WD MediaMax WL2000GSA6454 2TB       | 1        | 0.7%    |
| Toshiba THNSNX032GTNT M.2 2242 32GB | 1        | 0.7%    |
| Toshiba THNSNX032GTNT 32GB          | 1        | 0.7%    |
| Toshiba HDWN180 8TB                 | 1        | 0.7%    |
| Toshiba HDWF180 8TB                 | 1        | 0.7%    |
| Toshiba HDWD130 3TB                 | 1        | 0.7%    |
| Toshiba DT01ACA300 3TB              | 1        | 0.7%    |
| Toshiba DT01ACA200 2TB              | 1        | 0.7%    |
| Toshiba DT01ACA100 1TB              | 1        | 0.7%    |
| SPCC SPCCSolidStateDisk 256GB       | 1        | 0.7%    |
| Seagate ST980310AS 80GB             | 1        | 0.7%    |
| Seagate ST9320421AS 320GB           | 1        | 0.7%    |
| Seagate ST9320325AS 320GB           | 1        | 0.7%    |
| Seagate ST8000VN0022-2EL112 8TB     | 1        | 0.7%    |
| Seagate ST500DL001 HD503HI 500GB    | 1        | 0.7%    |
| Seagate ST4000DM005-2DP166 4TB      | 1        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 68     | 33.33%  |
| Seagate             | 11       | 49     | 26.19%  |
| Toshiba             | 5        | 8      | 11.9%   |
| Hitachi             | 5        | 16     | 11.9%   |
| HPT                 | 2        | 31     | 4.76%   |
| Hewlett-Packard     | 2        | 8      | 4.76%   |
| WD MediaMax         | 1        | 3      | 2.38%   |
| Samsung Electronics | 1        | 3      | 2.38%   |
| HGST                | 1        | 10     | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 7      | 26.09%  |
| Kingston            | 4        | 7      | 17.39%  |
| SanDisk             | 3        | 3      | 13.04%  |
| Crucial             | 2        | 3      | 8.7%    |
| Toshiba             | 1        | 2      | 4.35%   |
| SPCC                | 1        | 1      | 4.35%   |
| PNY                 | 1        | 1      | 4.35%   |
| Mushkin             | 1        | 1      | 4.35%   |
| Intel               | 1        | 2      | 4.35%   |
| China               | 1        | 1      | 4.35%   |
| Apacer              | 1        | 1      | 4.35%   |
| AMD                 | 1        | 2      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 196    | 53.19%  |
| SSD  | 19       | 31     | 40.43%  |
| NVMe | 3        | 4      | 6.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 25       | 227    | 89.29%  |
| NVMe | 3        | 4      | 10.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 56     | 32.84%  |
| 1.01-2.0   | 12       | 38     | 17.91%  |
| 2.01-3.0   | 11       | 65     | 16.42%  |
| 3.01-4.0   | 7        | 24     | 10.45%  |
| 4.01-10.0  | 7        | 15     | 10.45%  |
| 0.51-1.0   | 5        | 23     | 7.46%   |
| 10.01-20.0 | 3        | 6      | 4.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 25.81%  |
| 1-20           | 8        | 25.81%  |
| 251-500        | 7        | 22.58%  |
| 21-50          | 2        | 6.45%   |
| 51-100         | 2        | 6.45%   |
| Unknown        | 2        | 6.45%   |
| More than 3000 | 1        | 3.23%   |
| 501-1000       | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 29       | 93.55%  |
| Unknown | 2        | 6.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD30EFRX-68AX9N0 3TB       | 2        | 5      | 8.7%    |
| WDC WD60EFRX-68MYMN1 6TB       | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-00U6AA0 500GB   | 1        | 1      | 4.35%   |
| WDC WD30PURX-64P6ZY0 3TB       | 1        | 1      | 4.35%   |
| WDC WD30EZRX-00MMMB0 3TB       | 1        | 2      | 4.35%   |
| WDC WD20EFRX-68AX9N0 2TB       | 1        | 1      | 4.35%   |
| WDC WD10PURX-64E5EY0 1TB       | 1        | 1      | 4.35%   |
| WDC WD10EZEX-00RKKA0 1TB       | 1        | 1      | 4.35%   |
| WD MediaMax WL2000GSA6454 2TB  | 1        | 3      | 4.35%   |
| Toshiba HDWD130 3TB            | 1        | 2      | 4.35%   |
| Seagate ST980310AS 80GB        | 1        | 1      | 4.35%   |
| Seagate ST9320325AS 320GB      | 1        | 1      | 4.35%   |
| Seagate ST4000DM000-1F2168 4TB | 1        | 1      | 4.35%   |
| Seagate ST3320311CS 320GB      | 1        | 2      | 4.35%   |
| Seagate ST31500341AS 1.5TB     | 1        | 1      | 4.35%   |
| Seagate ST3000VN007-2E4166 3TB | 1        | 1      | 4.35%   |
| Seagate ST2000DL003-9VT166 2TB | 1        | 1      | 4.35%   |
| Seagate ST2000DL001-9VT156 2TB | 1        | 1      | 4.35%   |
| Seagate ST1000VM002-1SD102 1TB | 1        | 2      | 4.35%   |
| Hitachi HTS725032A9A364 320GB  | 1        | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB  | 1        | 1      | 4.35%   |
| Hitachi HDS723020BLA642 2TB    | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 5        | 11     | 38.46%  |
| WDC         | 4        | 13     | 30.77%  |
| Hitachi     | 2        | 3      | 15.38%  |
| WD MediaMax | 1        | 3      | 7.69%   |
| Toshiba     | 1        | 2      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 5        | 11     | 38.46%  |
| WDC         | 4        | 13     | 30.77%  |
| Hitachi     | 2        | 3      | 15.38%  |
| WD MediaMax | 1        | 3      | 7.69%   |
| Toshiba     | 1        | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 32     | 100%    |

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
| Works    | 25       | 163    | 67.57%  |
| Malfunc  | 9        | 32     | 24.32%  |
| Detected | 3        | 36     | 8.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 22       | 35.48%  |
| AMD                         | 9        | 14.52%  |
| Marvell Technology Group    | 7        | 11.29%  |
| Broadcom / LSI              | 7        | 11.29%  |
| Silicon Image               | 2        | 3.23%   |
| Micron/Crucial Technology   | 2        | 3.23%   |
| Kingston Technology Company | 2        | 3.23%   |
| JMicron Technology          | 2        | 3.23%   |
| HighPoint Technologies      | 2        | 3.23%   |
| Hewlett-Packard             | 2        | 3.23%   |
| ASMedia Technology          | 2        | 3.23%   |
| Silicon Motion              | 1        | 1.61%   |
| QLogic                      | 1        | 1.61%   |
| Areca Technology            | 1        | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 6        | 8.33%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 4        | 5.56%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 4.17%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 2        | 2.78%   |
| Kingston Company A2000 NVMe SSD                                                | 2        | 2.78%   |
| JMicron JMB58x AHCI SATA controller                                            | 2        | 2.78%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 2        | 2.78%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 2        | 2.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 2.78%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 2.78%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 2        | 2.78%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 2.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.39%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 1.39%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1        | 1.39%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                    | 1        | 1.39%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.39%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.39%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1        | 1.39%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.39%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 1.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 1.39%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 1.39%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 1.39%   |
| HP Smart Array G6 controllers                                                  | 1        | 1.39%   |
| HP Smart Array Controller                                                      | 1        | 1.39%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 1        | 1.39%   |
| Areca ARC-188x series PCIe 2.0/3.0 to SAS/SATA 6/12Gb RAID Controller          | 1        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 1.39%   |
| AMD FCH IDE Controller                                                         | 1        | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 1.39%   |
| Unknown                                                                        | 1        | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 28       | 50%     |
| RAID | 10       | 17.86%  |
| SAS  | 6        | 10.71%  |
| IDE  | 6        | 10.71%  |
| NVMe | 5        | 8.93%   |
| SCSI | 1        | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 70.97%  |
| AMD    | 9        | 29.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Xeon CPU E5504 @ 2.00GHz           | 2        | 6.45%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 2        | 6.45%   |
| Intel Atom CPU C2750 @ 2.40GHz           | 2        | 6.45%   |
| AMD Ryzen 5 3600 6-Core Processor        | 2        | 6.45%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1        | 3.23%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1        | 3.23%   |
| Intel Xeon CPU E5506 @ 2.13GHz           | 1        | 3.23%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz       | 1        | 3.23%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz      | 1        | 3.23%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1        | 3.23%   |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz      | 1        | 3.23%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1        | 3.23%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 1        | 3.23%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1        | 3.23%   |
| Intel Core i7-3555LE CPU @ 2.50GHz       | 1        | 3.23%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 3.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1        | 3.23%   |
| Intel Core i3-4330 CPU @ 3.50GHz         | 1        | 3.23%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 1        | 3.23%   |
| Intel Celeron CPU G1610T @ 2.30GHz       | 1        | 3.23%   |
| AMD Ryzen 7 1800X Eight-Core Processor   | 1        | 3.23%   |
| AMD FX-8350 Eight-Core Processor         | 1        | 3.23%   |
| AMD FX-8320E Eight-Core Processor        | 1        | 3.23%   |
| AMD FX-8300 Eight-Core Processor         | 1        | 3.23%   |
| AMD FX-6300 Six-Core Processor           | 1        | 3.23%   |
| AMD E1-2500 APU with Radeon HD Graphics  | 1        | 3.23%   |
| AMD A8-3870 APU with Radeon HD Graphics  | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 12       | 38.71%  |
| Intel Core i5 | 4        | 12.9%   |
| AMD FX        | 4        | 12.9%   |
| Intel Core i3 | 2        | 6.45%   |
| Intel Atom    | 2        | 6.45%   |
| AMD Ryzen 5   | 2        | 6.45%   |
| Intel Core i7 | 1        | 3.23%   |
| Intel Celeron | 1        | 3.23%   |
| AMD Ryzen 7   | 1        | 3.23%   |
| AMD E1        | 1        | 3.23%   |
| AMD A8        | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 14       | 45.16%  |
| 8       | 8        | 25.81%  |
| 2       | 4        | 12.9%   |
| 12      | 2        | 6.45%   |
| 16      | 1        | 3.23%   |
| 6       | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 90.32%  |
| 2      | 3        | 9.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 23       | 74.19%  |
| 2       | 7        | 22.58%  |
| Unknown | 1        | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 5        | 16.13%  |
| Piledriver  | 4        | 12.9%   |
| Nehalem     | 4        | 12.9%   |
| KabyLake    | 4        | 12.9%   |
| Haswell     | 4        | 12.9%   |
| Zen 2       | 2        | 6.45%   |
| Silvermont  | 2        | 6.45%   |
| Zen         | 1        | 3.23%   |
| SandyBridge | 1        | 3.23%   |
| K10 Llano   | 1        | 3.23%   |
| Jaguar      | 1        | 3.23%   |
| CometLake   | 1        | 3.23%   |
| Broadwell   | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Matrox Electronics Systems | 10       | 33.33%  |
| AMD                        | 7        | 23.33%  |
| Intel                      | 6        | 20%     |
| ASPEED Technology          | 5        | 16.67%  |
| Nvidia                     | 2        | 6.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems MGA G200eW WPCM450                               | 5        | 16.67%  |
| ASPEED Technology ASPEED Graphics Family                                    | 5        | 16.67%  |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 6.67%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 6.67%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2        | 6.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.67%   |
| Intel HD Graphics 630                                                       | 2        | 6.67%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 6.67%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 6.67%   |
| Matrox Electronics Systems MGA G200eH3                                      | 1        | 3.33%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.33%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1        | 3.33%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 3.33%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Matrox | 10       | 32.26%  |
| 1 x AMD    | 7        | 22.58%  |
| 1 x Intel  | 6        | 19.35%  |
| 1 x ASPEED | 5        | 16.13%  |
| 1 x Nvidia | 2        | 6.45%   |
| Other      | 1        | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 30       | 96.77%  |
| Unknown | 1        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 100%    |

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 31       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 23       | 62.16%  |
| Realtek Semiconductor | 8        | 21.62%  |
| Broadcom              | 4        | 10.81%  |
| QLogic                | 1        | 2.7%    |
| Aquantia              | 1        | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 6        | 13.64%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 9.09%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 6.82%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 6.82%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 4.55%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.55%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 4.55%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 4.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 4.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 2.27%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 2.27%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.27%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 2.27%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1        | 2.27%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.27%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 2.27%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 2.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.27%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 2.27%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 2.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 2.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200            | 1        | 50%     |
| Intel Tiger Lake PCH CNVi WiFi | 1        | 50%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 22       | 61.11%  |
| Realtek Semiconductor | 8        | 22.22%  |
| Broadcom              | 4        | 11.11%  |
| QLogic                | 1        | 2.78%   |
| Aquantia              | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 6        | 14.29%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 9.52%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 7.14%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 7.14%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 4.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.76%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 4.76%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 4.76%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 4.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 2.38%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 2.38%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 2.38%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1        | 2.38%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.38%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 2.38%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 2.38%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.38%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 2.38%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 2.38%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 93.94%  |
| WiFi     | 2        | 6.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 10       | 32.26%  |
| 1     | 10       | 32.26%  |
| 5     | 4        | 12.9%   |
| 4     | 3        | 9.68%   |
| 6     | 2        | 6.45%   |
| 3     | 2        | 6.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 50%     |
| Intel AX200 Bluetooth                          | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 7        | 58.33%  |
| Intel  | 3        | 25%     |
| Nvidia | 2        | 16.67%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 17.65%  |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 11.76%  |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 11.76%  |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 11.76%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 5.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 5.88%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 5.88%   |
| AMD FCH Azalia Controller                                                         | 1        | 5.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 5.88%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1        | 5.88%   |
| Unknown                                                                           | 1        | 5.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 19.35%  |
| Unknown             | 6        | 19.35%  |
| Samsung Electronics | 5        | 16.13%  |
| Micron Technology   | 5        | 16.13%  |
| Crucial             | 2        | 6.45%   |
| Toshiba             | 1        | 3.23%   |
| Team                | 1        | 3.23%   |
| SK hynix            | 1        | 3.23%   |
| PNY                 | 1        | 3.23%   |
| Patriot             | 1        | 3.23%   |
| Hewlett-Packard     | 1        | 3.23%   |
| Corsair             | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown                                                  | 6        | 18.75%  |
| Toshiba RAM 9965525-138.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 3.13%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s           | 1        | 3.13%   |
| SK hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 800MT/s   | 1        | 3.13%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 3.13%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s  | 1        | 3.13%   |
| Samsung RAM M393B1K70DH0-CH9 8192MB DIMM DDR3 800MT/s    | 1        | 3.13%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.13%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s   | 1        | 3.13%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 2133MT/s   | 1        | 3.13%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s      | 1        | 3.13%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s      | 1        | 3.13%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s      | 1        | 3.13%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s   | 1        | 3.13%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s     | 1        | 3.13%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s   | 1        | 3.13%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s      | 1        | 3.13%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s    | 1        | 3.13%   |
| Kingston RAM 9965684-012.A00G 8192MB DIMM DDR4 2400MT/s  | 1        | 3.13%   |
| Kingston RAM 9965527-026.A00LF 8192MB DIMM DDR3 1333MT/s | 1        | 3.13%   |
| Kingston RAM 9965525-140.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 3.13%   |
| Kingston RAM 9965525-037.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 3.13%   |
| Kingston RAM 9965516-057.A00LF 8192MB DIMM DDR3 1066MT/s | 1        | 3.13%   |
| HP RAM Module 4096MB DIMM DDR3 1600MT/s                  | 1        | 3.13%   |
| Crucial RAM BLS8G3D1609DS 8192MB DIMM DDR3 800MT/s       | 1        | 3.13%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s   | 1        | 3.13%   |
| Corsair RAM CMD16GX4M2B3000C15 8192MB DIMM DDR4 2133MT/s | 1        | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 16       | 64%     |
| DDR4    | 6        | 24%     |
| Unknown | 3        | 12%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 25       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 61.29%  |
| 4096  | 5        | 16.13%  |
| 16384 | 4        | 12.9%   |
| 2048  | 3        | 9.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 8        | 30.77%  |
| 1600  | 7        | 26.92%  |
| 800   | 3        | 11.54%  |
| 2133  | 2        | 7.69%   |
| 3200  | 1        | 3.85%   |
| 3000  | 1        | 3.85%   |
| 2667  | 1        | 3.85%   |
| 2400  | 1        | 3.85%   |
| 1066  | 1        | 3.85%   |
| 667   | 1        | 3.85%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 16       | 51.61%  |
| 2     | 5        | 16.13%  |
| 1     | 5        | 16.13%  |
| 3     | 4        | 12.9%   |
| 5     | 1        | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 10       | 41.67%  |
| Communication controller | 8        | 33.33%  |
| Net/wireless             | 2        | 8.33%   |
| Firewire controller      | 2        | 8.33%   |
| Bluetooth                | 2        | 8.33%   |

