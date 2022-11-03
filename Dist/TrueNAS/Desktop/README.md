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

Total: 40

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Supermicro    | X9SCI/X9SCA                 | [6e7e782b00](https://bsd-hardware.info/?probe=6e7e782b00) | Aug 13, 2022 |
| ASRock        | N3150M                      | [6f8942c3cd](https://bsd-hardware.info/?probe=6f8942c3cd) | Jul 15, 2022 |
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
| TrueNAS 12.2-p2  | 8        | 23.53%  |
| TrueNAS 12.2-p6  | 6        | 17.65%  |
| TrueNAS 12.2-p9  | 4        | 11.76%  |
| TrueNAS 12.2-p12 | 4        | 11.76%  |
| TrueNAS 12.2-RC3 | 3        | 8.82%   |
| TrueNAS 13.1     | 2        | 5.88%   |
| TrueNAS 12.2-p10 | 2        | 5.88%   |
| TrueNAS 12.3-p1  | 1        | 2.94%   |
| TrueNAS 12.2-p3  | 1        | 2.94%   |
| TrueNAS 12.2-p14 | 1        | 2.94%   |
| TrueNAS 12.2-p11 | 1        | 2.94%   |
| TrueNAS 12.2     | 1        | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TrueNAS | 33       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 33       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 29       | 87.88%  |
| helloDesktop | 3        | 9.09%   |
| TWM          | 1        | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 32       | 96.97%  |
| X11     | 1        | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 33       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 33       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 21       | 63.64%  |
| EFI  | 12       | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 29       | 87.88%  |
| XXX     | 3        | 9.09%   |
| Unknown | 1        | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 33       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Supermicro          | 6        | 18.18%  |
| Unknown             | 6        | 18.18%  |
| Gigabyte Technology | 5        | 15.15%  |
| ASUSTek Computer    | 5        | 15.15%  |
| ASRock              | 5        | 15.15%  |
| Hewlett-Packard     | 4        | 12.12%  |
| TYAN Computer       | 1        | 3.03%   |
| Lenovo              | 1        | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 6        | 18.18%  |
| TYAN S5512                          | 1        | 3.03%   |
| Supermicro X9SPV-F/LN4F             | 1        | 3.03%   |
| Supermicro X9SCL/X9SCM              | 1        | 3.03%   |
| Supermicro X9SCI/X9SCA              | 1        | 3.03%   |
| Supermicro X9DRD-7LN4F              | 1        | 3.03%   |
| Supermicro X8STi                    | 1        | 3.03%   |
| Supermicro ReadyDATA 5200           | 1        | 3.03%   |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1        | 3.03%   |
| HP ProLiant ML150 G6                | 1        | 3.03%   |
| HP ProLiant ML10 v2                 | 1        | 3.03%   |
| HP ProLiant MicroServer Gen8        | 1        | 3.03%   |
| HP Compaq Elite 8300 SFF            | 1        | 3.03%   |
| Gigabyte H97-D3H                    | 1        | 3.03%   |
| Gigabyte GA-A75-UD4H                | 1        | 3.03%   |
| Gigabyte B550I AORUS PRO AX         | 1        | 3.03%   |
| Gigabyte B450M DS3H                 | 1        | 3.03%   |
| Gigabyte 990FXA-UD3                 | 1        | 3.03%   |
| ASUS TUF Z270 MARK 2                | 1        | 3.03%   |
| ASUS P10S-I Series                  | 1        | 3.03%   |
| ASUS M5A99X EVO R2.0                | 1        | 3.03%   |
| ASUS M5A78L-M/USB3                  | 1        | 3.03%   |
| ASUS M5A78L-M PLUS/USB3             | 1        | 3.03%   |
| ASRock X570M Pro4                   | 1        | 3.03%   |
| ASRock N3150M                       | 1        | 3.03%   |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1        | 3.03%   |
| ASRock C2750D4I                     | 1        | 3.03%   |
| ASRock B560M Pro4/ac                | 1        | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 6        | 18.18%  |
| HP ProLiant                     | 3        | 9.09%   |
| ASUS M5A78L-M                   | 2        | 6.06%   |
| TYAN S5512                      | 1        | 3.03%   |
| Supermicro X9SPV-F              | 1        | 3.03%   |
| Supermicro X9SCL                | 1        | 3.03%   |
| Supermicro X9SCI                | 1        | 3.03%   |
| Supermicro X9DRD-7LN4F          | 1        | 3.03%   |
| Supermicro X8STi                | 1        | 3.03%   |
| Supermicro ReadyDATA            | 1        | 3.03%   |
| Lenovo 70AQ0009UX               | 1        | 3.03%   |
| HP Compaq                       | 1        | 3.03%   |
| Gigabyte H97-D3H                | 1        | 3.03%   |
| Gigabyte GA-A75-UD4H            | 1        | 3.03%   |
| Gigabyte B550I                  | 1        | 3.03%   |
| Gigabyte B450M                  | 1        | 3.03%   |
| Gigabyte 990FXA-UD3             | 1        | 3.03%   |
| ASUS TUF                        | 1        | 3.03%   |
| ASUS P10S-I                     | 1        | 3.03%   |
| ASUS M5A99X                     | 1        | 3.03%   |
| ASRock X570M                    | 1        | 3.03%   |
| ASRock N3150M                   | 1        | 3.03%   |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1        | 3.03%   |
| ASRock C2750D4I                 | 1        | 3.03%   |
| ASRock B560M                    | 1        | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 18.18%  |
| 2018    | 4        | 12.12%  |
| 2014    | 4        | 12.12%  |
| 2019    | 3        | 9.09%   |
| 2016    | 3        | 9.09%   |
| 2013    | 3        | 9.09%   |
| 2012    | 3        | 9.09%   |
| 2011    | 3        | 9.09%   |
| 2021    | 1        | 3.03%   |
| 2020    | 1        | 3.03%   |
| 2010    | 1        | 3.03%   |
| 2009    | 1        | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 33       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 11       | 33.33%  |
| 32.01-64.0  | 10       | 30.3%   |
| 64.01-256.0 | 4        | 12.12%  |
| 8.01-16.0   | 4        | 12.12%  |
| 24.01-32.0  | 3        | 9.09%   |
| 4.01-8.0    | 1        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 13       | 39.39%  |
| 1.01-2.0   | 9        | 27.27%  |
| 2.01-3.0   | 3        | 9.09%   |
| 16.01-24.0 | 2        | 6.06%   |
| 0.01-0.5   | 2        | 6.06%   |
| 4.01-8.0   | 1        | 3.03%   |
| 32.01-64.0 | 1        | 3.03%   |
| 3.01-4.0   | 1        | 3.03%   |
| 8.01-16.0  | 1        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 6        | 17.65%  |
| 0      | 6        | 17.65%  |
| 9      | 3        | 8.82%   |
| 4      | 3        | 8.82%   |
| 17     | 2        | 5.88%   |
| 6      | 2        | 5.88%   |
| 5      | 2        | 5.88%   |
| 27     | 1        | 2.94%   |
| 21     | 1        | 2.94%   |
| 19     | 1        | 2.94%   |
| 16     | 1        | 2.94%   |
| 12     | 1        | 2.94%   |
| 11     | 1        | 2.94%   |
| 10     | 1        | 2.94%   |
| 8      | 1        | 2.94%   |
| 7      | 1        | 2.94%   |
| 2      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 94.12%  |
| Yes       | 2        | 5.88%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 93.94%  |
| Yes       | 2        | 6.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 93.94%  |
| Yes       | 2        | 6.06%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 27.27%  |
| Australia   | 4        | 12.12%  |
| Thailand    | 3        | 9.09%   |
| Germany     | 3        | 9.09%   |
| Switzerland | 2        | 6.06%   |
| Czechia     | 2        | 6.06%   |
| Spain       | 1        | 3.03%   |
| Romania     | 1        | 3.03%   |
| Norway      | 1        | 3.03%   |
| Nicaragua   | 1        | 3.03%   |
| Greece      | 1        | 3.03%   |
| France      | 1        | 3.03%   |
| Estonia     | 1        | 3.03%   |
| Canada      | 1        | 3.03%   |
| Brazil      | 1        | 3.03%   |
| Belgium     | 1        | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Melbourne         | 3        | 9.09%   |
| Springfield       | 2        | 6.06%   |
| Brno              | 2        | 6.06%   |
| Bangkok           | 2        | 6.06%   |
| Yverdon-les-Bains | 1        | 3.03%   |
| Willisau          | 1        | 3.03%   |
| Tartu             | 1        | 3.03%   |
| Sydney            | 1        | 3.03%   |
| Skiptvet          | 1        | 3.03%   |
| Raleigh           | 1        | 3.03%   |
| Perry Hall        | 1        | 3.03%   |
| Ougree            | 1        | 3.03%   |
| Northville        | 1        | 3.03%   |
| Managua           | 1        | 3.03%   |
| Lüneburg         | 1        | 3.03%   |
| Ludwigsburg       | 1        | 3.03%   |
| Lubbock           | 1        | 3.03%   |
| Khlong Luang      | 1        | 3.03%   |
| JaraguÃ¡ do Sul | 1        | 3.03%   |
| Fontaine-le-Comte | 1        | 3.03%   |
| Fayetteville      | 1        | 3.03%   |
| East Granby       | 1        | 3.03%   |
| Dresden           | 1        | 3.03%   |
| Clare             | 1        | 3.03%   |
| Calgary           | 1        | 3.03%   |
| Bucharest         | 1        | 3.03%   |
| Athens            | 1        | 3.03%   |
| Algete            | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 68     | 20%     |
| Seagate             | 11       | 49     | 15.71%  |
| Samsung Electronics | 7        | 10     | 10%     |
| Hitachi             | 7        | 26     | 10%     |
| Toshiba             | 5        | 10     | 7.14%   |
| Crucial             | 5        | 7      | 7.14%   |
| Kingston            | 4        | 9      | 5.71%   |
| SanDisk             | 3        | 3      | 4.29%   |
| Intel               | 2        | 3      | 2.86%   |
| HPT                 | 2        | 31     | 2.86%   |
| Hewlett-Packard     | 2        | 8      | 2.86%   |
| WD MediaMax         | 1        | 3      | 1.43%   |
| SPCC                | 1        | 1      | 1.43%   |
| PNY                 | 1        | 1      | 1.43%   |
| Mushkin             | 1        | 1      | 1.43%   |
| HGST                | 1        | 10     | 1.43%   |
| China               | 1        | 1      | 1.43%   |
| Apacer              | 1        | 1      | 1.43%   |
| AMD                 | 1        | 2      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB        | 4        | 2.68%   |
| Samsung SSD 860 EVO 250GB       | 4        | 2.68%   |
| WDC WD40EFRX-68N32N0 4TB        | 3        | 2.01%   |
| WDC WD60EFRX-68MYMN1 6TB        | 2        | 1.34%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2        | 1.34%   |
| WDC WD30EFRX-68AX9N0 3TB        | 2        | 1.34%   |
| WDC WD20EFRX-68EUZN0 2TB        | 2        | 1.34%   |
| WDC WD20EFRX-68AX9N0 2TB        | 2        | 1.34%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 1.34%   |
| Kingston SA400S37120G 120GB     | 2        | 1.34%   |
| HPT DISK 0_9 3TB                | 2        | 1.34%   |
| HPT DISK 0_8 3TB                | 2        | 1.34%   |
| HPT DISK 0_7 3TB                | 2        | 1.34%   |
| HPT DISK 0_6 3TB                | 2        | 1.34%   |
| HPT DISK 0_5 18TB               | 2        | 1.34%   |
| HPT DISK 0_4 18TB               | 2        | 1.34%   |
| HPT DISK 0_3 3TB                | 2        | 1.34%   |
| HPT DISK 0_2 3TB                | 2        | 1.34%   |
| HPT DISK 0_14 3TB               | 2        | 1.34%   |
| HPT DISK 0_13 2TB               | 2        | 1.34%   |
| HPT DISK 0_12 1TB               | 2        | 1.34%   |
| HPT DISK 0_11 1TB               | 2        | 1.34%   |
| HPT DISK 0_10 1TB               | 2        | 1.34%   |
| HPT DISK 0_1 6TB                | 2        | 1.34%   |
| HPT DISK 0_0 4TB                | 2        | 1.34%   |
| Hitachi HDS723020BLA642 2TB     | 2        | 1.34%   |
| Hitachi HDS722020ALA330 2TB     | 2        | 1.34%   |
| Crucial M4-CT064M4SSD2 64GB     | 2        | 1.34%   |
| WDC WD80EFAX-68LHPN0 8TB        | 1        | 0.67%   |
| WDC WD8004FRYZ-01VAEB0 8TB      | 1        | 0.67%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.67%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 1        | 0.67%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1        | 0.67%   |
| WDC WD30PURX-64P6ZY0 3TB        | 1        | 0.67%   |
| WDC WD30EZRX-00MMMB0 3TB        | 1        | 0.67%   |
| WDC WD30EFRX-68N32N0 3TB        | 1        | 0.67%   |
| WDC WD3003FZEX-00Z4SA0 3TB      | 1        | 0.67%   |
| WDC WD3001FFSX-68JNUN0 3TB      | 1        | 0.67%   |
| WDC WD3000F9YZ-09N20L1 3TB      | 1        | 0.67%   |
| WDC WD3000F9YZ-09N20L0 3TB      | 1        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 68     | 31.82%  |
| Seagate             | 11       | 49     | 25%     |
| Hitachi             | 7        | 26     | 15.91%  |
| Toshiba             | 5        | 8      | 11.36%  |
| HPT                 | 2        | 31     | 4.55%   |
| Hewlett-Packard     | 2        | 8      | 4.55%   |
| WD MediaMax         | 1        | 3      | 2.27%   |
| Samsung Electronics | 1        | 3      | 2.27%   |
| HGST                | 1        | 10     | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 7      | 24%     |
| Kingston            | 4        | 7      | 16%     |
| SanDisk             | 3        | 3      | 12%     |
| Crucial             | 3        | 5      | 12%     |
| Intel               | 2        | 3      | 8%      |
| Toshiba             | 1        | 2      | 4%      |
| SPCC                | 1        | 1      | 4%      |
| PNY                 | 1        | 1      | 4%      |
| Mushkin             | 1        | 1      | 4%      |
| China               | 1        | 1      | 4%      |
| Apacer              | 1        | 1      | 4%      |
| AMD                 | 1        | 2      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 206    | 52.94%  |
| SSD  | 21       | 34     | 41.18%  |
| NVMe | 3        | 4      | 5.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 240    | 90%     |
| NVMe | 3        | 4      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 58     | 33.33%  |
| 1.01-2.0   | 13       | 40     | 18.06%  |
| 2.01-3.0   | 12       | 73     | 16.67%  |
| 3.01-4.0   | 7        | 24     | 9.72%   |
| 4.01-10.0  | 7        | 15     | 9.72%   |
| 0.51-1.0   | 6        | 24     | 8.33%   |
| 10.01-20.0 | 3        | 6      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 24.24%  |
| 1-20           | 8        | 24.24%  |
| 251-500        | 7        | 21.21%  |
| 51-100         | 3        | 9.09%   |
| Unknown        | 3        | 9.09%   |
| 21-50          | 2        | 6.06%   |
| More than 3000 | 1        | 3.03%   |
| 501-1000       | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 30       | 90.91%  |
| Unknown | 3        | 9.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD30EFRX-68AX9N0 3TB       | 2        | 5      | 8.33%   |
| Hitachi HDS723020BLA642 2TB    | 2        | 2      | 8.33%   |
| WDC WD60EFRX-68MYMN1 6TB       | 1        | 1      | 4.17%   |
| WDC WD5000AAKX-00U6AA0 500GB   | 1        | 1      | 4.17%   |
| WDC WD30PURX-64P6ZY0 3TB       | 1        | 1      | 4.17%   |
| WDC WD30EZRX-00MMMB0 3TB       | 1        | 2      | 4.17%   |
| WDC WD20EFRX-68AX9N0 2TB       | 1        | 1      | 4.17%   |
| WDC WD10PURX-64E5EY0 1TB       | 1        | 1      | 4.17%   |
| WDC WD10EZEX-00RKKA0 1TB       | 1        | 1      | 4.17%   |
| WD MediaMax WL2000GSA6454 2TB  | 1        | 3      | 4.17%   |
| Toshiba HDWD130 3TB            | 1        | 2      | 4.17%   |
| Seagate ST980310AS 80GB        | 1        | 1      | 4.17%   |
| Seagate ST9320325AS 320GB      | 1        | 1      | 4.17%   |
| Seagate ST4000DM000-1F2168 4TB | 1        | 1      | 4.17%   |
| Seagate ST3320311CS 320GB      | 1        | 2      | 4.17%   |
| Seagate ST31500341AS 1.5TB     | 1        | 1      | 4.17%   |
| Seagate ST3000VN007-2E4166 3TB | 1        | 1      | 4.17%   |
| Seagate ST2000DL003-9VT166 2TB | 1        | 1      | 4.17%   |
| Seagate ST2000DL001-9VT156 2TB | 1        | 1      | 4.17%   |
| Seagate ST1000VM002-1SD102 1TB | 1        | 2      | 4.17%   |
| Hitachi HTS725032A9A364 320GB  | 1        | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB  | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 5        | 11     | 35.71%  |
| WDC         | 4        | 13     | 28.57%  |
| Hitachi     | 3        | 4      | 21.43%  |
| WD MediaMax | 1        | 3      | 7.14%   |
| Toshiba     | 1        | 2      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 5        | 11     | 35.71%  |
| WDC         | 4        | 13     | 28.57%  |
| Hitachi     | 3        | 4      | 21.43%  |
| WD MediaMax | 1        | 3      | 7.14%   |
| Toshiba     | 1        | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 33     | 100%    |

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
| Works    | 27       | 175    | 67.5%   |
| Malfunc  | 10       | 33     | 25%     |
| Detected | 3        | 36     | 7.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 24       | 36.36%  |
| AMD                         | 9        | 13.64%  |
| Broadcom / LSI              | 8        | 12.12%  |
| Marvell Technology Group    | 7        | 10.61%  |
| ASMedia Technology          | 3        | 4.55%   |
| Silicon Image               | 2        | 3.03%   |
| Micron/Crucial Technology   | 2        | 3.03%   |
| Kingston Technology Company | 2        | 3.03%   |
| JMicron Technology          | 2        | 3.03%   |
| HighPoint Technologies      | 2        | 3.03%   |
| Hewlett-Packard             | 2        | 3.03%   |
| Silicon Motion              | 1        | 1.52%   |
| QLogic                      | 1        | 1.52%   |
| Areca Technology            | 1        | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 7        | 9.21%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 4        | 5.26%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 3        | 3.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3        | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 3.95%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3        | 3.95%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 2        | 2.63%   |
| Kingston Company A2000 NVMe SSD                                                  | 2        | 2.63%   |
| JMicron JMB58x AHCI SATA controller                                              | 2        | 2.63%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 2        | 2.63%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 2        | 2.63%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2        | 2.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2        | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 2.63%   |
| HighPoint RocketRAID 2760 SAS Controller                                         | 2        | 2.63%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 2.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 1.32%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1        | 1.32%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 1.32%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                      | 1        | 1.32%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1        | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 1.32%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1        | 1.32%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1        | 1.32%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1        | 1.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1        | 1.32%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                          | 1        | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1        | 1.32%   |
| HP Smart Array G6 controllers                                                    | 1        | 1.32%   |
| HP Smart Array Controller                                                        | 1        | 1.32%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1        | 1.32%   |
| ASMedia ASM1061 SATA IDE Controller                                              | 1        | 1.32%   |
| Areca ARC-188x series PCIe 2.0/3.0 to SAS/SATA 6/12Gb RAID Controller            | 1        | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 30       | 50%     |
| RAID | 11       | 18.33%  |
| IDE  | 7        | 11.67%  |
| SAS  | 6        | 10%     |
| NVMe | 5        | 8.33%   |
| SCSI | 1        | 1.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 24       | 72.73%  |
| AMD    | 9        | 27.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Xeon CPU E5504 @ 2.00GHz           | 2        | 6.06%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 2        | 6.06%   |
| Intel Atom CPU C2750 @ 2.40GHz           | 2        | 6.06%   |
| AMD Ryzen 5 3600 6-Core Processor        | 2        | 6.06%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1        | 3.03%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1        | 3.03%   |
| Intel Xeon CPU E5506 @ 2.13GHz           | 1        | 3.03%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz       | 1        | 3.03%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz      | 1        | 3.03%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1        | 3.03%   |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz      | 1        | 3.03%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1        | 3.03%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz      | 1        | 3.03%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 1        | 3.03%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1        | 3.03%   |
| Intel Core i7-3555LE CPU @ 2.50GHz       | 1        | 3.03%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1        | 3.03%   |
| Intel Core i3-4330 CPU @ 3.50GHz         | 1        | 3.03%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 1        | 3.03%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 1        | 3.03%   |
| Intel Celeron CPU G1610T @ 2.30GHz       | 1        | 3.03%   |
| AMD Ryzen 7 1800X Eight-Core Processor   | 1        | 3.03%   |
| AMD FX-8350 Eight-Core Processor         | 1        | 3.03%   |
| AMD FX-8320E Eight-Core Processor        | 1        | 3.03%   |
| AMD FX-8300 Eight-Core Processor         | 1        | 3.03%   |
| AMD FX-6300 Six-Core Processor           | 1        | 3.03%   |
| AMD E1-2500 APU with Radeon HD Graphics  | 1        | 3.03%   |
| AMD A8-3870 APU with Radeon HD Graphics  | 1        | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 13       | 39.39%  |
| Intel Core i5 | 4        | 12.12%  |
| AMD FX        | 4        | 12.12%  |
| Intel Core i3 | 2        | 6.06%   |
| Intel Celeron | 2        | 6.06%   |
| Intel Atom    | 2        | 6.06%   |
| AMD Ryzen 5   | 2        | 6.06%   |
| Intel Core i7 | 1        | 3.03%   |
| AMD Ryzen 7   | 1        | 3.03%   |
| AMD E1        | 1        | 3.03%   |
| AMD A8        | 1        | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 16       | 48.48%  |
| 8       | 8        | 24.24%  |
| 2       | 4        | 12.12%  |
| 12      | 2        | 6.06%   |
| 16      | 1        | 3.03%   |
| 6       | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 90.91%  |
| 2      | 3        | 9.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 25       | 75.76%  |
| 2       | 7        | 21.21%  |
| Unknown | 1        | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 6        | 18.18%  |
| Piledriver  | 4        | 12.12%  |
| Nehalem     | 4        | 12.12%  |
| KabyLake    | 4        | 12.12%  |
| Haswell     | 4        | 12.12%  |
| Silvermont  | 3        | 9.09%   |
| Zen 2       | 2        | 6.06%   |
| Zen         | 1        | 3.03%   |
| SandyBridge | 1        | 3.03%   |
| K10 Llano   | 1        | 3.03%   |
| Jaguar      | 1        | 3.03%   |
| CometLake   | 1        | 3.03%   |
| Broadwell   | 1        | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Matrox Electronics Systems | 11       | 34.38%  |
| Intel                      | 7        | 21.88%  |
| AMD                        | 7        | 21.88%  |
| ASPEED Technology          | 5        | 15.63%  |
| Nvidia                     | 2        | 6.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6        | 18.75%  |
| ASPEED Technology ASPEED Graphics Family                                                 | 5        | 15.63%  |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 6.25%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 6.25%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 6.25%   |
| Intel HD Graphics 630                                                                    | 2        | 6.25%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 6.25%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2        | 6.25%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 3.13%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 3.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.13%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1        | 3.13%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1        | 3.13%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1        | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Matrox | 11       | 33.33%  |
| 1 x Intel  | 7        | 21.21%  |
| 1 x AMD    | 7        | 21.21%  |
| 1 x ASPEED | 5        | 15.15%  |
| 1 x Nvidia | 2        | 6.06%   |
| Other      | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 32       | 96.97%  |
| Unknown | 1        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 100%    |

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
| 0     | 33       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 24       | 61.54%  |
| Realtek Semiconductor | 9        | 23.08%  |
| Broadcom              | 4        | 10.26%  |
| QLogic                | 1        | 2.56%   |
| Aquantia              | 1        | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 15.22%  |
| Intel 82574L Gigabit Network Connection                                       | 5        | 10.87%  |
| Intel I350 Gigabit Network Connection                                         | 3        | 6.52%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 6.52%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 4.35%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 4.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.35%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 4.35%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 4.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 4.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 2.17%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 2.17%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.17%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 2.17%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1        | 2.17%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.17%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 2.17%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 2.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.17%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 2.17%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 2.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 2.17%   |

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
| Intel                 | 23       | 60.53%  |
| Realtek Semiconductor | 9        | 23.68%  |
| Broadcom              | 4        | 10.53%  |
| QLogic                | 1        | 2.63%   |
| Aquantia              | 1        | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 15.91%  |
| Intel 82574L Gigabit Network Connection                                       | 5        | 11.36%  |
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
| Intel I211 Gigabit Network Connection                                         | 1        | 2.27%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1        | 2.27%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.27%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 2.27%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 2.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.27%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 2.27%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 2.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 94.29%  |
| WiFi     | 2        | 5.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 33.33%  |
| 2     | 10       | 30.3%   |
| 5     | 4        | 12.12%  |
| 4     | 4        | 12.12%  |
| 6     | 2        | 6.06%   |
| 3     | 2        | 6.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 100%    |

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
| Kingston            | 7        | 21.21%  |
| Unknown             | 6        | 18.18%  |
| Samsung Electronics | 6        | 18.18%  |
| Micron Technology   | 5        | 15.15%  |
| Crucial             | 2        | 6.06%   |
| Toshiba             | 1        | 3.03%   |
| Team                | 1        | 3.03%   |
| SK hynix            | 1        | 3.03%   |
| PNY                 | 1        | 3.03%   |
| Patriot             | 1        | 3.03%   |
| Hewlett-Packard     | 1        | 3.03%   |
| Corsair             | 1        | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 2.86%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 2.86%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                   | 1        | 2.86%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 2.86%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 2.86%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 2.86%   |
| Toshiba RAM 9965525-138.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 2.86%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s           | 1        | 2.86%   |
| SK hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 800MT/s   | 1        | 2.86%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 2.86%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s  | 1        | 2.86%   |
| Samsung RAM M393B1K70DH0-CH9 8192MB DIMM DDR3 800MT/s    | 1        | 2.86%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1600MT/s      | 1        | 2.86%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.86%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s   | 1        | 2.86%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 2133MT/s   | 1        | 2.86%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s      | 1        | 2.86%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s      | 1        | 2.86%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s      | 1        | 2.86%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s   | 1        | 2.86%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s     | 1        | 2.86%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s   | 1        | 2.86%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s      | 1        | 2.86%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1400MT/s          | 1        | 2.86%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s    | 1        | 2.86%   |
| Kingston RAM 9965684-012.A00G 8192MB DIMM DDR4 2400MT/s  | 1        | 2.86%   |
| Kingston RAM 9965527-026.A00LF 8192MB DIMM DDR3 1333MT/s | 1        | 2.86%   |
| Kingston RAM 9965525-140.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 2.86%   |
| Kingston RAM 9965525-037.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 2.86%   |
| Kingston RAM 9965516-057.A00LF 8192MB DIMM DDR3 1066MT/s | 1        | 2.86%   |
| HP RAM Module 4096MB DIMM DDR3 1600MT/s                  | 1        | 2.86%   |
| Crucial RAM BLS8G3D1609DS 8192MB DIMM DDR3 800MT/s       | 1        | 2.86%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s   | 1        | 2.86%   |
| Corsair RAM CMD16GX4M2B3000C15 8192MB DIMM DDR4 2133MT/s | 1        | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 18       | 66.67%  |
| DDR4    | 6        | 22.22%  |
| Unknown | 3        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 27       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 63.64%  |
| 4096  | 5        | 15.15%  |
| 16384 | 4        | 12.12%  |
| 2048  | 3        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 8        | 28.57%  |
| 1333  | 8        | 28.57%  |
| 800   | 3        | 10.71%  |
| 2133  | 2        | 7.14%   |
| 3200  | 1        | 3.57%   |
| 3000  | 1        | 3.57%   |
| 2667  | 1        | 3.57%   |
| 2400  | 1        | 3.57%   |
| 1400  | 1        | 3.57%   |
| 1066  | 1        | 3.57%   |
| 667   | 1        | 3.57%   |

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
| 0     | 17       | 51.52%  |
| 2     | 6        | 18.18%  |
| 1     | 5        | 15.15%  |
| 3     | 4        | 12.12%  |
| 5     | 1        | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 10       | 40%     |
| Communication controller | 9        | 36%     |
| Net/wireless             | 2        | 8%      |
| Firewire controller      | 2        | 8%      |
| Bluetooth                | 2        | 8%      |

