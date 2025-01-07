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

Total: 55

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | Z77X-UP4 TH                 | [3b5e5eeea4](https://bsd-hardware.info/?probe=3b5e5eeea4) | Dec 25, 2024 |
| ASUSTek       | M5A99X EVO                  | [497b67a38e](https://bsd-hardware.info/?probe=497b67a38e) | Nov 01, 2024 |
| Unknown       | Unknown                     | [8413a82b26](https://bsd-hardware.info/?probe=8413a82b26) | Nov 01, 2024 |
| Unknown       | Unknown                     | [89007fbfac](https://bsd-hardware.info/?probe=89007fbfac) | Aug 28, 2024 |
| Unknown       | Unknown                     | [bc07108ffa](https://bsd-hardware.info/?probe=bc07108ffa) | Jul 21, 2024 |
| ASUSTek       | P8H67-I                     | [70e83653e3](https://bsd-hardware.info/?probe=70e83653e3) | Mar 23, 2024 |
| Unknown       | Unknown                     | [1bed6c30cd](https://bsd-hardware.info/?probe=1bed6c30cd) | Nov 22, 2023 |
| Gigabyte      | H610M H DDR4                | [bdc4fdaf9c](https://bsd-hardware.info/?probe=bdc4fdaf9c) | Nov 05, 2023 |
| Gigabyte      | H610M H DDR4                | [ab5400f952](https://bsd-hardware.info/?probe=ab5400f952) | Oct 08, 2023 |
| Unknown       | Unknown                     | [05925afd0a](https://bsd-hardware.info/?probe=05925afd0a) | Jun 19, 2023 |
| Unknown       | Unknown                     | [74d372e7a4](https://bsd-hardware.info/?probe=74d372e7a4) | Jun 19, 2023 |
| Dell          | 0HY9JP A02                  | [ca71c8ab2b](https://bsd-hardware.info/?probe=ca71c8ab2b) | Jan 25, 2023 |
| Unknown       | Unknown                     | [41b04a4c81](https://bsd-hardware.info/?probe=41b04a4c81) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| Unknown       | Unknown                     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
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
| TrueNAS 12.2-p2  | 8        | 17.02%  |
| TrueNAS 13.1-p9  | 6        | 12.77%  |
| TrueNAS 12.2-p6  | 6        | 12.77%  |
| TrueNAS 12.2-p9  | 4        | 8.51%   |
| TrueNAS 12.2-p12 | 4        | 8.51%   |
| TrueNAS 12.2-RC3 | 3        | 6.38%   |
| TrueNAS 13.1-p7  | 2        | 4.26%   |
| TrueNAS 13.1-p2  | 2        | 4.26%   |
| TrueNAS 13.1     | 2        | 4.26%   |
| TrueNAS 12.2-p10 | 2        | 4.26%   |
| TrueNAS 13.3     | 1        | 2.13%   |
| TrueNAS 12.3-p7  | 1        | 2.13%   |
| TrueNAS 12.3-p2  | 1        | 2.13%   |
| TrueNAS 12.3-p1  | 1        | 2.13%   |
| TrueNAS 12.2-p3  | 1        | 2.13%   |
| TrueNAS 12.2-p14 | 1        | 2.13%   |
| TrueNAS 12.2-p11 | 1        | 2.13%   |
| TrueNAS 12.2     | 1        | 2.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TrueNAS | 46       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 46       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 42       | 91.3%   |
| helloDesktop | 3        | 6.52%   |
| TWM          | 1        | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 45       | 97.83%  |
| X11     | 1        | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 46       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 42       | 91.3%   |
| C     | 4        | 8.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 24       | 52.17%  |
| EFI  | 22       | 47.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 41       | 89.13%  |
| XXX     | 3        | 6.52%   |
| Unknown | 2        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 46       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 28.26%  |
| Gigabyte Technology | 7        | 15.22%  |
| ASUSTek Computer    | 7        | 15.22%  |
| Supermicro          | 6        | 13.04%  |
| ASRock              | 5        | 10.87%  |
| Hewlett-Packard     | 4        | 8.7%    |
| Lenovo              | 2        | 4.35%   |
| TYAN Computer       | 1        | 2.17%   |
| Dell                | 1        | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 13       | 28.26%  |
| TYAN S5512                          | 1        | 2.17%   |
| Supermicro X9SPV-F/LN4F             | 1        | 2.17%   |
| Supermicro X9SCL/X9SCM              | 1        | 2.17%   |
| Supermicro X9SCI/X9SCA              | 1        | 2.17%   |
| Supermicro X9DRD-7LN4F              | 1        | 2.17%   |
| Supermicro X8STi                    | 1        | 2.17%   |
| Supermicro ReadyDATA 5200           | 1        | 2.17%   |
| Lenovo ThinkCentre M73 10AXS01800   | 1        | 2.17%   |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1        | 2.17%   |
| HP ProLiant ML150 G6                | 1        | 2.17%   |
| HP ProLiant ML10 v2                 | 1        | 2.17%   |
| HP ProLiant MicroServer Gen8        | 1        | 2.17%   |
| HP Compaq Elite 8300 SFF            | 1        | 2.17%   |
| Gigabyte Z77X-UP4 TH                | 1        | 2.17%   |
| Gigabyte H97-D3H                    | 1        | 2.17%   |
| Gigabyte H610M H DDR4               | 1        | 2.17%   |
| Gigabyte GA-A75-UD4H                | 1        | 2.17%   |
| Gigabyte B550I AORUS PRO AX         | 1        | 2.17%   |
| Gigabyte B450M DS3H                 | 1        | 2.17%   |
| Gigabyte 990FXA-UD3                 | 1        | 2.17%   |
| Dell OptiPlex 790                   | 1        | 2.17%   |
| ASUS TUF Z270 MARK 2                | 1        | 2.17%   |
| ASUS P8H67-I                        | 1        | 2.17%   |
| ASUS P10S-I Series                  | 1        | 2.17%   |
| ASUS M5A99X EVO R2.0                | 1        | 2.17%   |
| ASUS M5A99X EVO                     | 1        | 2.17%   |
| ASUS M5A78L-M/USB3                  | 1        | 2.17%   |
| ASUS M5A78L-M PLUS/USB3             | 1        | 2.17%   |
| ASRock X570M Pro4                   | 1        | 2.17%   |
| ASRock N3150M                       | 1        | 2.17%   |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1        | 2.17%   |
| ASRock C2750D4I                     | 1        | 2.17%   |
| ASRock B560M Pro4/ac                | 1        | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 13       | 28.26%  |
| HP ProLiant                     | 3        | 6.52%   |
| ASUS M5A99X                     | 2        | 4.35%   |
| ASUS M5A78L-M                   | 2        | 4.35%   |
| TYAN S5512                      | 1        | 2.17%   |
| Supermicro X9SPV-F              | 1        | 2.17%   |
| Supermicro X9SCL                | 1        | 2.17%   |
| Supermicro X9SCI                | 1        | 2.17%   |
| Supermicro X9DRD-7LN4F          | 1        | 2.17%   |
| Supermicro X8STi                | 1        | 2.17%   |
| Supermicro ReadyDATA            | 1        | 2.17%   |
| Lenovo ThinkCentre              | 1        | 2.17%   |
| Lenovo 70AQ0009UX               | 1        | 2.17%   |
| HP Compaq                       | 1        | 2.17%   |
| Gigabyte Z77X-UP4               | 1        | 2.17%   |
| Gigabyte H97-D3H                | 1        | 2.17%   |
| Gigabyte H610M                  | 1        | 2.17%   |
| Gigabyte GA-A75-UD4H            | 1        | 2.17%   |
| Gigabyte B550I                  | 1        | 2.17%   |
| Gigabyte B450M                  | 1        | 2.17%   |
| Gigabyte 990FXA-UD3             | 1        | 2.17%   |
| Dell OptiPlex                   | 1        | 2.17%   |
| ASUS TUF                        | 1        | 2.17%   |
| ASUS P8H67-I                    | 1        | 2.17%   |
| ASUS P10S-I                     | 1        | 2.17%   |
| ASRock X570M                    | 1        | 2.17%   |
| ASRock N3150M                   | 1        | 2.17%   |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1        | 2.17%   |
| ASRock C2750D4I                 | 1        | 2.17%   |
| ASRock B560M                    | 1        | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 26.09%  |
| 2011    | 6        | 13.04%  |
| 2012    | 5        | 10.87%  |
| 2018    | 4        | 8.7%    |
| 2014    | 4        | 8.7%    |
| 2019    | 3        | 6.52%   |
| 2016    | 3        | 6.52%   |
| 2013    | 2        | 4.35%   |
| 2023    | 1        | 2.17%   |
| 2022    | 1        | 2.17%   |
| 2021    | 1        | 2.17%   |
| 2020    | 1        | 2.17%   |
| 2015    | 1        | 2.17%   |
| 2010    | 1        | 2.17%   |
| 2009    | 1        | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 46       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 46       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 16       | 34.78%  |
| 16.01-24.0  | 13       | 28.26%  |
| 8.01-16.0   | 8        | 17.39%  |
| 24.01-32.0  | 4        | 8.7%    |
| 64.01-256.0 | 4        | 8.7%    |
| 4.01-8.0    | 1        | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 16       | 34.78%  |
| 1.01-2.0   | 11       | 23.91%  |
| 4.01-8.0   | 4        | 8.7%    |
| 0.01-0.5   | 4        | 8.7%    |
| 2.01-3.0   | 3        | 6.52%   |
| 24.01-32.0 | 2        | 4.35%   |
| 16.01-24.0 | 2        | 4.35%   |
| 8.01-16.0  | 2        | 4.35%   |
| 32.01-64.0 | 1        | 2.17%   |
| 3.01-4.0   | 1        | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 12       | 25%     |
| 3      | 8        | 16.67%  |
| 6      | 4        | 8.33%   |
| 4      | 4        | 8.33%   |
| 9      | 3        | 6.25%   |
| 5      | 3        | 6.25%   |
| 17     | 2        | 4.17%   |
| 11     | 2        | 4.17%   |
| 27     | 1        | 2.08%   |
| 21     | 1        | 2.08%   |
| 19     | 1        | 2.08%   |
| 16     | 1        | 2.08%   |
| 12     | 1        | 2.08%   |
| 10     | 1        | 2.08%   |
| 8      | 1        | 2.08%   |
| 7      | 1        | 2.08%   |
| 2      | 1        | 2.08%   |
| 1      | 1        | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 93.75%  |
| Yes       | 3        | 6.25%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 93.48%  |
| Yes       | 3        | 6.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 95.65%  |
| Yes       | 2        | 4.35%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 12       | 26.09%  |
| France      | 5        | 10.87%  |
| Australia   | 5        | 10.87%  |
| Germany     | 4        | 8.7%    |
| Thailand    | 3        | 6.52%   |
| Switzerland | 2        | 4.35%   |
| Romania     | 2        | 4.35%   |
| Czechia     | 2        | 4.35%   |
| Spain       | 1        | 2.17%   |
| Russia      | 1        | 2.17%   |
| Norway      | 1        | 2.17%   |
| Nicaragua   | 1        | 2.17%   |
| New Zealand | 1        | 2.17%   |
| Greece      | 1        | 2.17%   |
| Estonia     | 1        | 2.17%   |
| Canada      | 1        | 2.17%   |
| Brazil      | 1        | 2.17%   |
| Belgium     | 1        | 2.17%   |
| Austria     | 1        | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Melbourne         | 3        | 6.52%   |
| Taylor            | 2        | 4.35%   |
| Springfield       | 2        | 4.35%   |
| Brno              | 2        | 4.35%   |
| Bangkok           | 2        | 4.35%   |
| Yverdon-les-Bains | 1        | 2.17%   |
| Willisau          | 1        | 2.17%   |
| Tartu             | 1        | 2.17%   |
| Sydney            | 1        | 2.17%   |
| St Petersburg     | 1        | 2.17%   |
| Skiptvet          | 1        | 2.17%   |
| Raleigh           | 1        | 2.17%   |
| Perth             | 1        | 2.17%   |
| Perry Hall        | 1        | 2.17%   |
| Paris             | 1        | 2.17%   |
| Ougree            | 1        | 2.17%   |
| Northville        | 1        | 2.17%   |
| Managua           | 1        | 2.17%   |
| Lüneburg         | 1        | 2.17%   |
| Ludwigsburg       | 1        | 2.17%   |
| Lubbock           | 1        | 2.17%   |
| Le Mesnil-Amelot  | 1        | 2.17%   |
| Konstanz          | 1        | 2.17%   |
| Khlong Luang      | 1        | 2.17%   |
| JaraguÃ¡ do Sul | 1        | 2.17%   |
| Hamilton          | 1        | 2.17%   |
| Genas             | 1        | 2.17%   |
| Fontaine-le-Comte | 1        | 2.17%   |
| Fayetteville      | 1        | 2.17%   |
| Falkenstein       | 1        | 2.17%   |
| East Granby       | 1        | 2.17%   |
| Dresden           | 1        | 2.17%   |
| Clare             | 1        | 2.17%   |
| Calgary           | 1        | 2.17%   |
| Bucharest         | 1        | 2.17%   |
| Brentwood         | 1        | 2.17%   |
| Béziers          | 1        | 2.17%   |
| Athens            | 1        | 2.17%   |
| Apahida           | 1        | 2.17%   |
| Algete            | 1        | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 76     | 18.39%  |
| Seagate             | 13       | 53     | 14.94%  |
| Samsung Electronics | 9        | 15     | 10.34%  |
| Hitachi             | 7        | 26     | 8.05%   |
| Toshiba             | 6        | 14     | 6.9%    |
| Kingston            | 6        | 13     | 6.9%    |
| Crucial             | 6        | 8      | 6.9%    |
| SanDisk             | 5        | 5      | 5.75%   |
| HGST                | 3        | 17     | 3.45%   |
| Intel               | 2        | 3      | 2.3%    |
| HPT                 | 2        | 31     | 2.3%    |
| Hewlett-Packard     | 2        | 8      | 2.3%    |
| WD MediaMax         | 1        | 3      | 1.15%   |
| SPCC                | 1        | 1      | 1.15%   |
| PNY                 | 1        | 1      | 1.15%   |
| Patriot             | 1        | 2      | 1.15%   |
| Netac               | 1        | 1      | 1.15%   |
| Mushkin             | 1        | 1      | 1.15%   |
| Fanxiang            | 1        | 1      | 1.15%   |
| China               | 1        | 1      | 1.15%   |
| Apacer              | 1        | 1      | 1.15%   |
| AMD                 | 1        | 2      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB        | 4        | 2.37%   |
| Samsung SSD 860 EVO 250GB       | 4        | 2.37%   |
| WDC WD40EFRX-68N32N0 4TB        | 3        | 1.78%   |
| SanDisk SDSSDA120G 120GB        | 3        | 1.78%   |
| Kingston SA400S37120G 120GB     | 3        | 1.78%   |
| WDC WD60EFRX-68MYMN1 6TB        | 2        | 1.18%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2        | 1.18%   |
| WDC WD30EFRX-68AX9N0 3TB        | 2        | 1.18%   |
| WDC WD20EFRX-68EUZN0 2TB        | 2        | 1.18%   |
| WDC WD20EFRX-68AX9N0 2TB        | 2        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 1.18%   |
| Samsung HD204UI 2TB             | 2        | 1.18%   |
| HPT DISK 0_9 3TB                | 2        | 1.18%   |
| HPT DISK 0_8 3TB                | 2        | 1.18%   |
| HPT DISK 0_7 1TB                | 2        | 1.18%   |
| HPT DISK 0_6 1TB                | 2        | 1.18%   |
| HPT DISK 0_5 1TB                | 2        | 1.18%   |
| HPT DISK 0_4 1TB                | 2        | 1.18%   |
| HPT DISK 0_3 1TB                | 2        | 1.18%   |
| HPT DISK 0_2 1TB                | 2        | 1.18%   |
| HPT DISK 0_14 3TB               | 2        | 1.18%   |
| HPT DISK 0_13 2TB               | 2        | 1.18%   |
| HPT DISK 0_12 1TB               | 2        | 1.18%   |
| HPT DISK 0_11 1TB               | 2        | 1.18%   |
| HPT DISK 0_10 1TB               | 2        | 1.18%   |
| HPT DISK 0_1 1TB                | 2        | 1.18%   |
| HPT DISK 0_0 4TB                | 2        | 1.18%   |
| Hitachi HDS723020BLA642 2TB     | 2        | 1.18%   |
| Hitachi HDS722020ALA330 2TB     | 2        | 1.18%   |
| Crucial M4-CT064M4SSD2 64GB     | 2        | 1.18%   |
| WDC WD80EFAX-68LHPN0 8TB        | 1        | 0.59%   |
| WDC WD8004FRYZ-01VAEB0 8TB      | 1        | 0.59%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.59%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 1        | 0.59%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1        | 0.59%   |
| WDC WD30PURX-64P6ZY0 3TB        | 1        | 0.59%   |
| WDC WD30EZRX-00MMMB0 3TB        | 1        | 0.59%   |
| WDC WD30EFRX-68N32N0 3TB        | 1        | 0.59%   |
| WDC WD3003FZEX-00Z4SA0 3TB      | 1        | 0.59%   |
| WDC WD3001FFSX-68JNUN0 3TB      | 1        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 75     | 30.77%  |
| Seagate             | 13       | 53     | 25%     |
| Hitachi             | 7        | 26     | 13.46%  |
| Toshiba             | 6        | 12     | 11.54%  |
| HGST                | 3        | 17     | 5.77%   |
| Samsung Electronics | 2        | 7      | 3.85%   |
| HPT                 | 2        | 31     | 3.85%   |
| Hewlett-Packard     | 2        | 8      | 3.85%   |
| WD MediaMax         | 1        | 3      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 21.88%  |
| Kingston            | 6        | 11     | 18.75%  |
| SanDisk             | 5        | 5      | 15.63%  |
| Crucial             | 4        | 6      | 12.5%   |
| Intel               | 2        | 3      | 6.25%   |
| WDC                 | 1        | 1      | 3.13%   |
| Toshiba             | 1        | 2      | 3.13%   |
| SPCC                | 1        | 1      | 3.13%   |
| PNY                 | 1        | 1      | 3.13%   |
| Mushkin             | 1        | 1      | 3.13%   |
| China               | 1        | 1      | 3.13%   |
| Apacer              | 1        | 1      | 3.13%   |
| AMD                 | 1        | 2      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 232    | 50.77%  |
| SSD  | 27       | 43     | 41.54%  |
| NVMe | 5        | 8      | 7.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 34       | 275    | 87.18%  |
| NVMe | 5        | 8      | 12.82%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 30       | 62     | 37.5%   |
| 1.01-2.0   | 15       | 48     | 18.75%  |
| 2.01-3.0   | 12       | 65     | 15%     |
| 3.01-4.0   | 7        | 24     | 8.75%   |
| 0.51-1.0   | 7        | 51     | 8.75%   |
| 4.01-10.0  | 6        | 17     | 7.5%    |
| 10.01-20.0 | 3        | 8      | 3.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 23.91%  |
| 1-20           | 9        | 19.57%  |
| 251-500        | 8        | 17.39%  |
| 51-100         | 7        | 15.22%  |
| More than 3000 | 3        | 6.52%   |
| Unknown        | 3        | 6.52%   |
| 21-50          | 2        | 4.35%   |
| 501-1000       | 2        | 4.35%   |
| 2001-3000      | 1        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 42       | 91.3%   |
| Unknown | 3        | 6.52%   |
| 251-500 | 1        | 2.17%   |

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
| Works    | 34       | 214    | 72.34%  |
| Malfunc  | 10       | 33     | 21.28%  |
| Detected | 3        | 36     | 6.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 33       | 36.67%  |
| AMD                         | 12       | 13.33%  |
| Marvell Technology Group    | 10       | 11.11%  |
| Broadcom / LSI              | 9        | 10%     |
| ASMedia Technology          | 5        | 5.56%   |
| JMicron Technology          | 4        | 4.44%   |
| Silicon Image               | 2        | 2.22%   |
| Micron/Crucial Technology   | 2        | 2.22%   |
| Kingston Technology Company | 2        | 2.22%   |
| HighPoint Technologies      | 2        | 2.22%   |
| Hewlett-Packard             | 2        | 2.22%   |
| Silicon Motion              | 1        | 1.11%   |
| Samsung Electronics         | 1        | 1.11%   |
| Realtek Semiconductor       | 1        | 1.11%   |
| QLogic                      | 1        | 1.11%   |
| Netac Technology            | 1        | 1.11%   |
| MAXIO Technology (Hangzhou) | 1        | 1.11%   |
| Areca Technology            | 1        | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 7        | 6.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 5.83%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 5        | 4.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 4.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 3.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4        | 3.88%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 2.91%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3        | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 2.91%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 2        | 1.94%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 2        | 1.94%   |
| JMicron JMB58x AHCI SATA controller                                            | 2        | 1.94%   |
| JMicron JMB362 SATA Controller                                                 | 2        | 1.94%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 2        | 1.94%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 2        | 1.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 1.94%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 1.94%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 2        | 1.94%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 2        | 1.94%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.97%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.97%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1        | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.97%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.97%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                    | 1        | 0.97%   |
| Netac PCIe 3 NVMe SSD (DRAM-less)                                              | 1        | 0.97%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 0.97%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 0.97%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1        | 0.97%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                | 1        | 0.97%   |
| Marvell Group 88SE9125 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.97%   |
| Intel SATA Controller [RAID Mode]                                              | 1        | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 0.97%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.97%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1        | 0.97%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1        | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 42       | 51.85%  |
| RAID | 11       | 13.58%  |
| IDE  | 10       | 12.35%  |
| SAS  | 8        | 9.88%   |
| NVMe | 8        | 9.88%   |
| SCSI | 2        | 2.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 34       | 73.91%  |
| AMD    | 12       | 26.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Xeon CPU E5504 @ 2.00GHz           | 2        | 4.35%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 2        | 4.35%   |
| Intel Atom CPU C2750 @ 2.40GHz           | 2        | 4.35%   |
| AMD Ryzen 5 3600 6-Core Processor        | 2        | 4.35%   |
| AMD FX-8150 Eight-Core Processor         | 2        | 4.35%   |
| Intel Xeon Silver 4108 CPU @ 1.80GHz     | 1        | 2.17%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1        | 2.17%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1        | 2.17%   |
| Intel Xeon CPU E5506 @ 2.13GHz           | 1        | 2.17%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz       | 1        | 2.17%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz      | 1        | 2.17%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1        | 2.17%   |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz      | 1        | 2.17%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1        | 2.17%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz      | 1        | 2.17%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 1        | 2.17%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1        | 2.17%   |
| Intel Pentium CPU G860 @ 3.00GHz         | 1        | 2.17%   |
| Intel Core i7-3770K CPU @ 3.50GHz        | 1        | 2.17%   |
| Intel Core i7-3555LE CPU @ 2.50GHz       | 1        | 2.17%   |
| Intel Core i7-2600 CPU @ 3.40GHz         | 1        | 2.17%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 2.17%   |
| Intel Core i5-4570T CPU @ 2.90GHz        | 1        | 2.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1        | 2.17%   |
| Intel Core i5-2500T CPU @ 2.30GHz        | 1        | 2.17%   |
| Intel Core i5-2500S CPU @ 2.70GH         | 1        | 2.17%   |
| Intel Core i3-4330 CPU @ 3.50GHz         | 1        | 2.17%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 1        | 2.17%   |
| Intel Celeron N5105 @ 2.00GHz            | 1        | 2.17%   |
| Intel Celeron N4505 @ 2.00GHz            | 1        | 2.17%   |
| Intel Celeron G6900T                     | 1        | 2.17%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 1        | 2.17%   |
| Intel Celeron CPU G1610T @ 2.30GHz       | 1        | 2.17%   |
| AMD Ryzen 7 1800X Eight-Core Processor   | 1        | 2.17%   |
| AMD FX-8350 Eight-Core Processor         | 1        | 2.17%   |
| AMD FX-8320E Eight-Core Processor        | 1        | 2.17%   |
| AMD FX-8300 Eight-Core Processor         | 1        | 2.17%   |
| AMD FX-6300 Six-Core Processor           | 1        | 2.17%   |
| AMD E1-2500 APU with Radeon HD Graphics  | 1        | 2.17%   |
| AMD A8-5500 APU with Radeon HD Graphics  | 1        | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Xeon        | 13       | 28.26%  |
| Intel Core i5     | 7        | 15.22%  |
| AMD FX            | 6        | 13.04%  |
| Intel Celeron     | 5        | 10.87%  |
| Intel Core i7     | 3        | 6.52%   |
| Intel Core i3     | 2        | 4.35%   |
| Intel Atom        | 2        | 4.35%   |
| AMD Ryzen 5       | 2        | 4.35%   |
| AMD A8            | 2        | 4.35%   |
| Intel Xeon Silver | 1        | 2.17%   |
| Intel Pentium     | 1        | 2.17%   |
| AMD Ryzen 7       | 1        | 2.17%   |
| AMD E1            | 1        | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 22       | 47.83%  |
| 8       | 10       | 21.74%  |
| 2       | 8        | 17.39%  |
| 16      | 2        | 4.35%   |
| 12      | 2        | 4.35%   |
| 6       | 1        | 2.17%   |
| Unknown | 1        | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 91.3%   |
| 2      | 4        | 8.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 34       | 73.91%  |
| 2       | 11       | 23.91%  |
| Unknown | 1        | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 7        | 15.22%  |
| SandyBridge | 5        | 10.87%  |
| Piledriver  | 5        | 10.87%  |
| Haswell     | 5        | 10.87%  |
| Nehalem     | 4        | 8.7%    |
| KabyLake    | 4        | 8.7%    |
| Silvermont  | 3        | 6.52%   |
| Unknown     | 3        | 6.52%   |
| Zen 2       | 2        | 4.35%   |
| Bulldozer   | 2        | 4.35%   |
| Zen         | 1        | 2.17%   |
| Skylake     | 1        | 2.17%   |
| K10 Llano   | 1        | 2.17%   |
| Jaguar      | 1        | 2.17%   |
| CometLake   | 1        | 2.17%   |
| Broadwell   | 1        | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 16       | 34.78%  |
| Matrox Electronics Systems | 11       | 23.91%  |
| AMD                        | 10       | 21.74%  |
| ASPEED Technology          | 6        | 13.04%  |
| Nvidia                     | 3        | 6.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6        | 13.04%  |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 13.04%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 8.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 6.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 4.35%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 4.35%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2        | 4.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 2        | 4.35%   |
| Intel HD Graphics 630                                                                    | 2        | 4.35%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 4.35%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 4.35%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2        | 4.35%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 2.17%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 2.17%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 2.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.17%   |
| Intel Alder Lake-S GT1 [UHD Graphics 710]                                                | 1        | 2.17%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1        | 2.17%   |
| AMD Oland GL [FirePro W2100]                                                             | 1        | 2.17%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1        | 2.17%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1        | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 15       | 32.61%  |
| 1 x Matrox     | 11       | 23.91%  |
| 1 x AMD        | 10       | 21.74%  |
| 1 x ASPEED     | 6        | 13.04%  |
| 1 x Nvidia     | 2        | 4.35%   |
| Other          | 1        | 2.17%   |
| Intel + Nvidia | 1        | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 45       | 97.83%  |
| Unknown | 1        | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 46       | 100%    |

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
| 0     | 46       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 30       | 56.6%   |
| Realtek Semiconductor | 16       | 30.19%  |
| Broadcom              | 5        | 9.43%   |
| QLogic                | 1        | 1.89%   |
| Aquantia              | 1        | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 14       | 21.54%  |
| Intel 82574L Gigabit Network Connection                                                       | 6        | 9.23%   |
| Intel I350 Gigabit Network Connection                                                         | 5        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4        | 6.15%   |
| Intel I210 Gigabit Network Connection                                                         | 3        | 4.62%   |
| Intel Ethernet Controller I225-V                                                              | 2        | 3.08%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 3.08%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 3.08%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 3.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                          | 2        | 3.08%   |
| Intel 82576 Gigabit Network Connection                                                        | 2        | 3.08%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                                              | 2        | 3.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                              | 2        | 3.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 1.54%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.54%   |
| QLogic cLOM8214 1/10GbE Controller                                                            | 1        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 1.54%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.54%   |
| Intel Ethernet Connection X722 for 1GbE                                                       | 1        | 1.54%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                                              | 1        | 1.54%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1        | 1.54%   |
| Intel 82580 Gigabit Network Connection                                                        | 1        | 1.54%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                 | 1        | 1.54%   |
| Intel 82571EB Gigabit Ethernet Controller                                                     | 1        | 1.54%   |
| Intel 82541PI Gigabit Ethernet Controller                                                     | 1        | 1.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                              | 1        | 1.54%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]                | 1        | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2        | 66.67%  |
| Realtek Semiconductor | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 33.33%  |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 33.33%  |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 29       | 55.77%  |
| Realtek Semiconductor | 16       | 30.77%  |
| Broadcom              | 5        | 9.62%   |
| QLogic                | 1        | 1.92%   |
| Aquantia              | 1        | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 14       | 22.58%  |
| Intel 82574L Gigabit Network Connection                                        | 6        | 9.68%   |
| Intel I350 Gigabit Network Connection                                          | 5        | 8.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4        | 6.45%   |
| Intel I210 Gigabit Network Connection                                          | 3        | 4.84%   |
| Intel Ethernet Controller I225-V                                               | 2        | 3.23%   |
| Intel Ethernet Connection I217-V                                               | 2        | 3.23%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 3.23%   |
| Intel Ethernet Connection (2) I219-V                                           | 2        | 3.23%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2        | 3.23%   |
| Intel 82576 Gigabit Network Connection                                         | 2        | 3.23%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                               | 2        | 3.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 2        | 3.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 1.61%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 1.61%   |
| QLogic cLOM8214 1/10GbE Controller                                             | 1        | 1.61%   |
| Intel I211 Gigabit Network Connection                                          | 1        | 1.61%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 1        | 1.61%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1        | 1.61%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.61%   |
| Intel 82580 Gigabit Network Connection                                         | 1        | 1.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1        | 1.61%   |
| Intel 82571EB Gigabit Ethernet Controller                                      | 1        | 1.61%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 1        | 1.61%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1        | 1.61%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 93.88%  |
| WiFi     | 3        | 6.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 39.13%  |
| 2     | 13       | 28.26%  |
| 5     | 5        | 10.87%  |
| 4     | 5        | 10.87%  |
| 3     | 3        | 6.52%   |
| 6     | 2        | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 46       | 100%    |

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
| AMD    | 8        | 47.06%  |
| Intel  | 7        | 41.18%  |
| Nvidia | 2        | 11.76%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 12.5%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 12.5%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 8.33%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 8.33%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1        | 4.17%   |
| Intel Jasper Lake HD Audio                                                        | 1        | 4.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 4.17%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 1        | 4.17%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 4.17%   |
| AMD FCH Azalia Controller                                                         | 1        | 4.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 4.17%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1        | 4.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 8        | 18.6%   |
| Kingston            | 8        | 18.6%   |
| Samsung Electronics | 6        | 13.95%  |
| Crucial             | 6        | 13.95%  |
| Micron Technology   | 5        | 11.63%  |
| SK hynix            | 2        | 4.65%   |
| Corsair             | 2        | 4.65%   |
| Toshiba             | 1        | 2.33%   |
| Team                | 1        | 2.33%   |
| PNY                 | 1        | 2.33%   |
| Patriot             | 1        | 2.33%   |
| Hewlett-Packard     | 1        | 2.33%   |
| G.Skill             | 1        | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                 | 1        | 2.17%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 2.17%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 2.17%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                    | 1        | 2.17%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                   | 1        | 2.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 2.17%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 2.17%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 2.17%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 2.17%   |
| Toshiba RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s            | 1        | 2.17%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s    | 1        | 2.17%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 2.17%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s   | 1        | 2.17%   |
| Samsung RAM M393B1K70DH0-CH9 8GB DIMM DDR3 1333MT/s       | 1        | 2.17%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s    | 1        | 2.17%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 2133MT/s       | 1        | 2.17%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s       | 1        | 2.17%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s       | 1        | 2.17%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s    | 1        | 2.17%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s    | 1        | 2.17%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1400MT/s           | 1        | 2.17%   |
| Kingston RAM 99U5403-195.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5403-083.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s     | 1        | 2.17%   |
| Kingston RAM 9965684-012.A00G 8GB DIMM DDR4 2400MT/s      | 1        | 2.17%   |
| Kingston RAM 9965527-026.A00LF 8192MB DIMM DDR3 1333MT/s  | 1        | 2.17%   |
| Kingston RAM 9965525-140.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 9965525-037.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 9965516-057.A00LF 8192MB DIMM DDR3 1066MT/s  | 1        | 2.17%   |
| HP RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 2.17%   |
| G.Skill RAM F3-10666CL7-4GBRH 4GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s | 1        | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 23       | 67.65%  |
| DDR4    | 8        | 23.53%  |
| Unknown | 3        | 8.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 32       | 94.12%  |
| SODIMM | 2        | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 59.52%  |
| 4096  | 8        | 19.05%  |
| 16384 | 6        | 14.29%  |
| 2048  | 3        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 11       | 30.56%  |
| 1600  | 9        | 25%     |
| 3200  | 2        | 5.56%   |
| 3000  | 2        | 5.56%   |
| 2400  | 2        | 5.56%   |
| 1066  | 2        | 5.56%   |
| 800   | 2        | 5.56%   |
| 2667  | 1        | 2.78%   |
| 2666  | 1        | 2.78%   |
| 2133  | 1        | 2.78%   |
| 1866  | 1        | 2.78%   |
| 1400  | 1        | 2.78%   |
| 667   | 1        | 2.78%   |

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
| 0     | 23       | 50%     |
| 2     | 8        | 17.39%  |
| 1     | 7        | 15.22%  |
| 3     | 6        | 13.04%  |
| 5     | 1        | 2.17%   |
| 4     | 1        | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 15       | 38.46%  |
| Communication controller | 15       | 38.46%  |
| Net/wireless             | 3        | 7.69%   |
| Firewire controller      | 3        | 7.69%   |
| Bluetooth                | 2        | 5.13%   |
| Storage/raid             | 1        | 2.56%   |

