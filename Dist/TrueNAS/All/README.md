TrueNAS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for TrueNAS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/TrueNAS/Desktop/README.md) and [notebooks](/Dist/TrueNAS/Notebook/README.md).

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

Total: 57

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASRock        | N3150M                      | Desktop     | [6f8942c3cd](https://bsd-hardware.info/?probe=6f8942c3cd) | Jul 15, 2022 |
| HP            | ProLiant ML10 v2            | Desktop     | [72254b033d](https://bsd-hardware.info/?probe=72254b033d) | Jun 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [378021707a](https://bsd-hardware.info/?probe=378021707a) | Apr 17, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [e245cecbe8](https://bsd-hardware.info/?probe=e245cecbe8) | Apr 06, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [190fe4d13f](https://bsd-hardware.info/?probe=190fe4d13f) | Mar 24, 2022 |
| Supermicro    | X10SLM-F                    | Server      | [4ade9fbcf8](https://bsd-hardware.info/?probe=4ade9fbcf8) | Mar 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8460816b1f](https://bsd-hardware.info/?probe=8460816b1f) | Mar 13, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [5c8df4dcad](https://bsd-hardware.info/?probe=5c8df4dcad) | Mar 10, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Desktop     | [ea62f49750](https://bsd-hardware.info/?probe=ea62f49750) | Feb 15, 2022 |
| Supermicro    | X8STi                       | Desktop     | [970e2c91ec](https://bsd-hardware.info/?probe=970e2c91ec) | Feb 15, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Desktop     | [74dffd5c4f](https://bsd-hardware.info/?probe=74dffd5c4f) | Feb 15, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5606f6d091](https://bsd-hardware.info/?probe=5606f6d091) | Feb 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a07a15f667](https://bsd-hardware.info/?probe=a07a15f667) | Feb 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd78c2db3d](https://bsd-hardware.info/?probe=bd78c2db3d) | Jan 16, 2022 |
| Dell          | 0DT021 A02                  | Server      | [d1fdef3d4d](https://bsd-hardware.info/?probe=d1fdef3d4d) | Jan 09, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [ad308cc715](https://bsd-hardware.info/?probe=ad308cc715) | Dec 08, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [df981410a9](https://bsd-hardware.info/?probe=df981410a9) | Dec 04, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| Supermicro    | X8SIE 0001                  | Desktop     | [fbd2abda35](https://bsd-hardware.info/?probe=fbd2abda35) | Oct 17, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [20f9d1c3f0](https://bsd-hardware.info/?probe=20f9d1c3f0) | Oct 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [88d44cfe0c](https://bsd-hardware.info/?probe=88d44cfe0c) | Oct 05, 2021 |
| Dell          | 0020HJ A02                  | Server      | [fbcc442d47](https://bsd-hardware.info/?probe=fbcc442d47) | Oct 02, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [a40a382f62](https://bsd-hardware.info/?probe=a40a382f62) | Aug 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f43771bc21](https://bsd-hardware.info/?probe=f43771bc21) | Aug 05, 2021 |
| Supermicro    | X8SIE 0001                  | Desktop     | [f679c0bf61](https://bsd-hardware.info/?probe=f679c0bf61) | Jul 22, 2021 |
| Supermicro    | X8SIE 0001                  | Desktop     | [d739af226b](https://bsd-hardware.info/?probe=d739af226b) | Jul 20, 2021 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [fd0f333074](https://bsd-hardware.info/?probe=fd0f333074) | Jul 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [df39a39ec7](https://bsd-hardware.info/?probe=df39a39ec7) | Jul 15, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f6d72c011d](https://bsd-hardware.info/?probe=f6d72c011d) | Jul 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [968859e99d](https://bsd-hardware.info/?probe=968859e99d) | Jun 03, 2021 |
| Dell          | 0C4Y3R A02                  | Server      | [7cec65d8f8](https://bsd-hardware.info/?probe=7cec65d8f8) | Jun 02, 2021 |
| ASRock        | C2750D4I                    | Desktop     | [e08a5e6f7c](https://bsd-hardware.info/?probe=e08a5e6f7c) | May 31, 2021 |
| ASRock        | C2750D4I                    | Desktop     | [9bd610c0ea](https://bsd-hardware.info/?probe=9bd610c0ea) | May 31, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [e308becda4](https://bsd-hardware.info/?probe=e308becda4) | May 29, 2021 |
| Lenovo        | ThinkServer TS440           | Desktop     | [6390c16543](https://bsd-hardware.info/?probe=6390c16543) | May 28, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [cec3cb521d](https://bsd-hardware.info/?probe=cec3cb521d) | May 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [760e148164](https://bsd-hardware.info/?probe=760e148164) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| TYAN Compu... | S5512                       | Desktop     | [6a6164af73](https://bsd-hardware.info/?probe=6a6164af73) | Jan 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [96ca836be9](https://bsd-hardware.info/?probe=96ca836be9) | Jan 19, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [415023d5a1](https://bsd-hardware.info/?probe=415023d5a1) | Jan 10, 2021 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [98fdc2713d](https://bsd-hardware.info/?probe=98fdc2713d) | Dec 18, 2020 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [fb58243913](https://bsd-hardware.info/?probe=fb58243913) | Dec 18, 2020 |
| HP            | 3397                        | Desktop     | [3d51aa7204](https://bsd-hardware.info/?probe=3d51aa7204) | Dec 18, 2020 |
| Unknown       | Unknown                     | Desktop     | [aa113d54a8](https://bsd-hardware.info/?probe=aa113d54a8) | Dec 16, 2020 |
| Supermicro    | X9SPV-F/LN4F                | Desktop     | [24031a56b9](https://bsd-hardware.info/?probe=24031a56b9) | Dec 16, 2020 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [4d6f6bb683](https://bsd-hardware.info/?probe=4d6f6bb683) | Dec 16, 2020 |
| Supermicro    | X10SAE                      | Server      | [2758b438c6](https://bsd-hardware.info/?probe=2758b438c6) | Dec 16, 2020 |
| Dell          | 0PM2CW A05                  | Server      | [21cd577877](https://bsd-hardware.info/?probe=21cd577877) | Dec 16, 2020 |
| ASRock        | C2750D4I                    | Desktop     | [8328ebb73d](https://bsd-hardware.info/?probe=8328ebb73d) | Dec 16, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| TrueNAS 12.2-p2  | 9         | 20%     |
| TrueNAS 12.2-p6  | 8         | 17.78%  |
| TrueNAS 12.2-p9  | 6         | 13.33%  |
| TrueNAS 12.2-p12 | 6         | 13.33%  |
| TrueNAS 12.2-RC3 | 4         | 8.89%   |
| TrueNAS 12.2-p11 | 4         | 8.89%   |
| TrueNAS 12.2-p10 | 3         | 6.67%   |
| TrueNAS 13.1     | 1         | 2.22%   |
| TrueNAS 12.3-p1  | 1         | 2.22%   |
| TrueNAS 12.2-p3  | 1         | 2.22%   |
| TrueNAS 12.2-p14 | 1         | 2.22%   |
| TrueNAS 12.2     | 1         | 2.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TrueNAS | 40        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 36        | 90%     |
| helloDesktop | 3         | 7.5%    |
| TWM          | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 39        | 97.5%   |
| X11     | 1         | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 40        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 40        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 25        | 62.5%   |
| EFI  | 15        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 36        | 90%     |
| XXX     | 3         | 7.5%    |
| Unknown | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 40        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Supermicro          | 8         | 20%     |
| Unknown             | 6         | 15%     |
| Gigabyte Technology | 5         | 12.5%   |
| Dell                | 5         | 12.5%   |
| ASUSTek Computer    | 5         | 12.5%   |
| ASRock              | 5         | 12.5%   |
| Hewlett-Packard     | 4         | 10%     |
| TYAN Computer       | 1         | 2.5%    |
| Lenovo              | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 6         | 15%     |
| Dell PowerEdge R720xd               | 2         | 5%      |
| TYAN S5512                          | 1         | 2.5%    |
| Supermicro X9SPV-F/LN4F             | 1         | 2.5%    |
| Supermicro X9SCL/X9SCM              | 1         | 2.5%    |
| Supermicro X9DRD-7LN4F              | 1         | 2.5%    |
| Supermicro X8STi                    | 1         | 2.5%    |
| Supermicro X10SLM-F                 | 1         | 2.5%    |
| Supermicro X10SLH-F/X10SLM+-F       | 1         | 2.5%    |
| Supermicro X10SAE                   | 1         | 2.5%    |
| Supermicro ReadyDATA 5200           | 1         | 2.5%    |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1         | 2.5%    |
| HP ProLiant ML150 G6                | 1         | 2.5%    |
| HP ProLiant ML10 v2                 | 1         | 2.5%    |
| HP ProLiant MicroServer Gen8        | 1         | 2.5%    |
| HP Compaq Elite 8300 SFF            | 1         | 2.5%    |
| Gigabyte H97-D3H                    | 1         | 2.5%    |
| Gigabyte GA-A75-UD4H                | 1         | 2.5%    |
| Gigabyte B550I AORUS PRO AX         | 1         | 2.5%    |
| Gigabyte B450M DS3H                 | 1         | 2.5%    |
| Gigabyte 990FXA-UD3                 | 1         | 2.5%    |
| Dell PowerEdge T310                 | 1         | 2.5%    |
| Dell PowerEdge T110 II              | 1         | 2.5%    |
| Dell PowerEdge 2950                 | 1         | 2.5%    |
| ASUS TUF Z270 MARK 2                | 1         | 2.5%    |
| ASUS P10S-I Series                  | 1         | 2.5%    |
| ASUS M5A99X EVO R2.0                | 1         | 2.5%    |
| ASUS M5A78L-M/USB3                  | 1         | 2.5%    |
| ASUS M5A78L-M PLUS/USB3             | 1         | 2.5%    |
| ASRock X570M Pro4                   | 1         | 2.5%    |
| ASRock N3150M                       | 1         | 2.5%    |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1         | 2.5%    |
| ASRock C2750D4I                     | 1         | 2.5%    |
| ASRock B560M Pro4/ac                | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 6         | 15%     |
| Dell PowerEdge                  | 5         | 12.5%   |
| HP ProLiant                     | 3         | 7.5%    |
| ASUS M5A78L-M                   | 2         | 5%      |
| TYAN S5512                      | 1         | 2.5%    |
| Supermicro X9SPV-F              | 1         | 2.5%    |
| Supermicro X9SCL                | 1         | 2.5%    |
| Supermicro X9DRD-7LN4F          | 1         | 2.5%    |
| Supermicro X8STi                | 1         | 2.5%    |
| Supermicro X10SLM-F             | 1         | 2.5%    |
| Supermicro X10SLH-F             | 1         | 2.5%    |
| Supermicro X10SAE               | 1         | 2.5%    |
| Supermicro ReadyDATA            | 1         | 2.5%    |
| Lenovo 70AQ0009UX               | 1         | 2.5%    |
| HP Compaq                       | 1         | 2.5%    |
| Gigabyte H97-D3H                | 1         | 2.5%    |
| Gigabyte GA-A75-UD4H            | 1         | 2.5%    |
| Gigabyte B550I                  | 1         | 2.5%    |
| Gigabyte B450M                  | 1         | 2.5%    |
| Gigabyte 990FXA-UD3             | 1         | 2.5%    |
| ASUS TUF                        | 1         | 2.5%    |
| ASUS P10S-I                     | 1         | 2.5%    |
| ASUS M5A99X                     | 1         | 2.5%    |
| ASRock X570M                    | 1         | 2.5%    |
| ASRock N3150M                   | 1         | 2.5%    |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1         | 2.5%    |
| ASRock C2750D4I                 | 1         | 2.5%    |
| ASRock B560M                    | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 6         | 15%     |
| 2014    | 6         | 15%     |
| Unknown | 6         | 15%     |
| 2019    | 4         | 10%     |
| 2016    | 3         | 7.5%    |
| 2013    | 3         | 7.5%    |
| 2012    | 3         | 7.5%    |
| 2020    | 2         | 5%      |
| 2011    | 2         | 5%      |
| 2010    | 2         | 5%      |
| 2021    | 1         | 2.5%    |
| 2017    | 1         | 2.5%    |
| 2009    | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 32        | 80%     |
| Server  | 8         | 20%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 12        | 30%     |
| 16.01-24.0  | 12        | 30%     |
| 64.01-256.0 | 6         | 15%     |
| 24.01-32.0  | 5         | 12.5%   |
| 8.01-16.0   | 4         | 10%     |
| 4.01-8.0    | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 15        | 37.5%   |
| 1.01-2.0   | 11        | 27.5%   |
| 2.01-3.0   | 5         | 12.5%   |
| 16.01-24.0 | 2         | 5%      |
| 0.01-0.5   | 2         | 5%      |
| 4.01-8.0   | 1         | 2.5%    |
| 32.01-64.0 | 1         | 2.5%    |
| 3.01-4.0   | 1         | 2.5%    |
| 24.01-32.0 | 1         | 2.5%    |
| 8.01-16.0  | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 3      | 6         | 14.63%  |
| 0      | 6         | 14.63%  |
| 4      | 4         | 9.76%   |
| 14     | 3         | 7.32%   |
| 9      | 3         | 7.32%   |
| 17     | 2         | 4.88%   |
| 7      | 2         | 4.88%   |
| 6      | 2         | 4.88%   |
| 5      | 2         | 4.88%   |
| 2      | 2         | 4.88%   |
| 27     | 1         | 2.44%   |
| 21     | 1         | 2.44%   |
| 19     | 1         | 2.44%   |
| 16     | 1         | 2.44%   |
| 15     | 1         | 2.44%   |
| 12     | 1         | 2.44%   |
| 11     | 1         | 2.44%   |
| 10     | 1         | 2.44%   |
| 8      | 1         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 87.8%   |
| Yes       | 5         | 12.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 95%     |
| Yes       | 2         | 5%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 95%     |
| Yes       | 2         | 5%      |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 27.5%   |
| Germany     | 4         | 10%     |
| Australia   | 4         | 10%     |
| Thailand    | 3         | 7.5%    |
| Greece      | 3         | 7.5%    |
| Switzerland | 2         | 5%      |
| Czechia     | 2         | 5%      |
| Canada      | 2         | 5%      |
| Brazil      | 2         | 5%      |
| Spain       | 1         | 2.5%    |
| Romania     | 1         | 2.5%    |
| Norway      | 1         | 2.5%    |
| Nicaragua   | 1         | 2.5%    |
| France      | 1         | 2.5%    |
| Estonia     | 1         | 2.5%    |
| Belgium     | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Melbourne            | 3         | 6.82%   |
| Springfield          | 2         | 4.55%   |
| Lüneburg            | 2         | 4.55%   |
| Brno                 | 2         | 4.55%   |
| Bangkok              | 2         | 4.55%   |
| Athens               | 2         | 4.55%   |
| Yverdon-les-Bains    | 1         | 2.27%   |
| Willisau             | 1         | 2.27%   |
| Tartu                | 1         | 2.27%   |
| Tamm                 | 1         | 2.27%   |
| Sydney               | 1         | 2.27%   |
| Skiptvet             | 1         | 2.27%   |
| SÃ£o Paulo         | 1         | 2.27%   |
| Raleigh              | 1         | 2.27%   |
| Perry Hall           | 1         | 2.27%   |
| Ougree               | 1         | 2.27%   |
| Northville           | 1         | 2.27%   |
| Managua              | 1         | 2.27%   |
| Lubbock              | 1         | 2.27%   |
| Khlong Luang         | 1         | 2.27%   |
| Kennedale            | 1         | 2.27%   |
| JundiaГ­           | 1         | 2.27%   |
| Jundiaí             | 1         | 2.27%   |
| JundiaÃ­           | 1         | 2.27%   |
| JaraguÃ¡ do Sul    | 1         | 2.27%   |
| Hendersonville       | 1         | 2.27%   |
| Gatineau             | 1         | 2.27%   |
| Galatista            | 1         | 2.27%   |
| Fontaine-le-Comte    | 1         | 2.27%   |
| Fayetteville         | 1         | 2.27%   |
| East Granby          | 1         | 2.27%   |
| Dresden              | 1         | 2.27%   |
| Clare                | 1         | 2.27%   |
| Campo Limpo Paulista | 1         | 2.27%   |
| Calgary              | 1         | 2.27%   |
| Bucharest            | 1         | 2.27%   |
| Algete               | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 85     | 20.45%  |
| Seagate             | 18        | 109    | 20.45%  |
| Samsung Electronics | 8         | 12     | 9.09%   |
| Hitachi             | 7         | 24     | 7.95%   |
| Toshiba             | 6         | 11     | 6.82%   |
| Intel               | 6         | 14     | 6.82%   |
| Crucial             | 5         | 7      | 5.68%   |
| Kingston            | 4         | 9      | 4.55%   |
| SanDisk             | 3         | 3      | 3.41%   |
| HPT                 | 2         | 31     | 2.27%   |
| Hewlett-Packard     | 2         | 8      | 2.27%   |
| WD MediaMax         | 1         | 3      | 1.14%   |
| Transcend           | 1         | 1      | 1.14%   |
| SPCC                | 1         | 1      | 1.14%   |
| PNY                 | 1         | 1      | 1.14%   |
| Mushkin             | 1         | 1      | 1.14%   |
| HGST                | 1         | 10     | 1.14%   |
| China               | 1         | 1      | 1.14%   |
| Apacer              | 1         | 1      | 1.14%   |
| AMD                 | 1         | 2      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| WDC WD40EFRX-68N32N0 4TB            | 5         | 2.79%   |
| WDC WD30EFRX-68EUZN0 3TB            | 4         | 2.23%   |
| Samsung SSD 860 EVO 250GB           | 4         | 2.23%   |
| WDC WD40EFRX-68WT0N0 4TB            | 3         | 1.68%   |
| WDC WD20EFRX-68EUZN0 2TB            | 3         | 1.68%   |
| WDC WD60EFRX-68MYMN1 6TB            | 2         | 1.12%   |
| WDC WD30EFRX-68AX9N0 3TB            | 2         | 1.12%   |
| WDC WD20EZRX-00D8PB0 2TB            | 2         | 1.12%   |
| WDC WD20EFRX-68AX9N0 2TB            | 2         | 1.12%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 1.12%   |
| Seagate ST4000DM000-1F2168 4TB      | 2         | 1.12%   |
| Seagate ST2000DM001-1ER164 2TB      | 2         | 1.12%   |
| Kingston SA400S37120G 120GB         | 2         | 1.12%   |
| Intel SSDSC2BB120G4 120GB           | 2         | 1.12%   |
| HPT DISK 0_9 3TB                    | 2         | 1.12%   |
| HPT DISK 0_8 3TB                    | 2         | 1.12%   |
| HPT DISK 0_7 3TB                    | 2         | 1.12%   |
| HPT DISK 0_6 3TB                    | 2         | 1.12%   |
| HPT DISK 0_5 18TB                   | 2         | 1.12%   |
| HPT DISK 0_4 18TB                   | 2         | 1.12%   |
| HPT DISK 0_3 3TB                    | 2         | 1.12%   |
| HPT DISK 0_2 3TB                    | 2         | 1.12%   |
| HPT DISK 0_14 3TB                   | 2         | 1.12%   |
| HPT DISK 0_13 2TB                   | 2         | 1.12%   |
| HPT DISK 0_12 1TB                   | 2         | 1.12%   |
| HPT DISK 0_11 1TB                   | 2         | 1.12%   |
| HPT DISK 0_10 1TB                   | 2         | 1.12%   |
| HPT DISK 0_1 6TB                    | 2         | 1.12%   |
| HPT DISK 0_0 4TB                    | 2         | 1.12%   |
| Hitachi HUA722020ALA331 2TB         | 2         | 1.12%   |
| Hitachi HDS723020BLA642 2TB         | 2         | 1.12%   |
| Hitachi HDS722020ALA330 2TB         | 2         | 1.12%   |
| Crucial M4-CT064M4SSD2 64GB         | 2         | 1.12%   |
| WDC WD80EFAX-68LHPN0 8TB            | 1         | 0.56%   |
| WDC WD8004FRYZ-01VAEB0 8TB          | 1         | 0.56%   |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1         | 0.56%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 0.56%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 0.56%   |
| WDC WD4003FFBX-68MU3N0 4TB          | 1         | 0.56%   |
| WDC WD30PURX-64P6ZY0 3TB            | 1         | 0.56%   |
| WDC WD30EZRX-00MMMB0 3TB            | 1         | 0.56%   |
| WDC WD30EFRX-68N32N0 3TB            | 1         | 0.56%   |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1         | 0.56%   |
| WDC WD3001FFSX-68JNUN0 3TB          | 1         | 0.56%   |
| WDC WD3000F9YZ-09N20L1 3TB          | 1         | 0.56%   |
| WDC WD3000F9YZ-09N20L0 3TB          | 1         | 0.56%   |
| WDC WD2002FFSX-68PF8N0 2TB          | 1         | 0.56%   |
| WDC WD2000FYYZ 2TB                  | 1         | 0.56%   |
| WDC WD120EDAZ-11F3RA0 12TB          | 1         | 0.56%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 0.56%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.56%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 0.56%   |
| WDC WD10EURX-61C57Y0 1TB            | 1         | 0.56%   |
| WDC WD100EMAZ-00WJTA0 10TB          | 1         | 0.56%   |
| WD MediaMax WL2000GSA6454 2TB       | 1         | 0.56%   |
| Transcend TS64GSSD370S 64GB         | 1         | 0.56%   |
| Toshiba THNSNX032GTNT M.2 2242 32GB | 1         | 0.56%   |
| Toshiba THNSNX032GTNT 32GB          | 1         | 0.56%   |
| Toshiba MG03ACA200 2TB              | 1         | 0.56%   |
| Toshiba HDWN180 8TB                 | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 85     | 32.14%  |
| Seagate             | 18        | 109    | 32.14%  |
| Hitachi             | 7         | 24     | 12.5%   |
| Toshiba             | 6         | 9      | 10.71%  |
| HPT                 | 2         | 31     | 3.57%   |
| Hewlett-Packard     | 2         | 8      | 3.57%   |
| WD MediaMax         | 1         | 3      | 1.79%   |
| Samsung Electronics | 1         | 3      | 1.79%   |
| HGST                | 1         | 10     | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 24.14%  |
| Kingston            | 4         | 7      | 13.79%  |
| Intel               | 4         | 12     | 13.79%  |
| SanDisk             | 3         | 3      | 10.34%  |
| Crucial             | 3         | 5      | 10.34%  |
| Transcend           | 1         | 1      | 3.45%   |
| Toshiba             | 1         | 2      | 3.45%   |
| SPCC                | 1         | 1      | 3.45%   |
| PNY                 | 1         | 1      | 3.45%   |
| Mushkin             | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| Apacer              | 1         | 1      | 3.45%   |
| AMD                 | 1         | 2      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 282    | 53.97%  |
| SSD  | 24        | 46     | 38.1%   |
| NVMe | 5         | 6      | 7.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 328    | 87.18%  |
| NVMe | 5         | 6      | 12.82%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 76     | 30.95%  |
| 1.01-2.0   | 15        | 57     | 17.86%  |
| 2.01-3.0   | 12        | 72     | 14.29%  |
| 3.01-4.0   | 11        | 61     | 13.1%   |
| 4.01-10.0  | 8         | 27     | 9.52%   |
| 0.51-1.0   | 8         | 28     | 9.52%   |
| 10.01-20.0 | 4         | 7      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12        | 29.27%  |
| 101-250        | 9         | 21.95%  |
| 251-500        | 8         | 19.51%  |
| 21-50          | 4         | 9.76%   |
| 51-100         | 3         | 7.32%   |
| Unknown        | 3         | 7.32%   |
| More than 3000 | 1         | 2.44%   |
| 501-1000       | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 37        | 92.5%   |
| Unknown | 3         | 7.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68AX9N0 3TB        | 2         | 5      | 7.14%   |
| Hitachi HDS723020BLA642 2TB     | 2         | 2      | 7.14%   |
| WDC WD60EFRX-68MYMN1 6TB        | 1         | 1      | 3.57%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1         | 1      | 3.57%   |
| WDC WD30PURX-64P6ZY0 3TB        | 1         | 1      | 3.57%   |
| WDC WD30EZRX-00MMMB0 3TB        | 1         | 2      | 3.57%   |
| WDC WD20EFRX-68AX9N0 2TB        | 1         | 1      | 3.57%   |
| WDC WD2000FYYZ 2TB              | 1         | 2      | 3.57%   |
| WDC WD10PURX-64E5EY0 1TB        | 1         | 1      | 3.57%   |
| WDC WD10EZEX-00RKKA0 1TB        | 1         | 1      | 3.57%   |
| WD MediaMax WL2000GSA6454 2TB   | 1         | 3      | 3.57%   |
| Toshiba HDWD130 3TB             | 1         | 2      | 3.57%   |
| Seagate ST980310AS 80GB         | 1         | 1      | 3.57%   |
| Seagate ST9320325AS 320GB       | 1         | 1      | 3.57%   |
| Seagate ST4000DM000-1F2168 4TB  | 1         | 1      | 3.57%   |
| Seagate ST3320311CS 320GB       | 1         | 2      | 3.57%   |
| Seagate ST31500341AS 1.5TB      | 1         | 1      | 3.57%   |
| Seagate ST3000VN007-2E4166 3TB  | 1         | 1      | 3.57%   |
| Seagate ST3000NM0033-9ZM178 3TB | 1         | 7      | 3.57%   |
| Seagate ST2000NM0033-9ZM175 2TB | 1         | 1      | 3.57%   |
| Seagate ST2000DL003-9VT166 2TB  | 1         | 1      | 3.57%   |
| Seagate ST2000DL001-9VT156 2TB  | 1         | 1      | 3.57%   |
| Seagate ST1000VM002-1SD102 1TB  | 1         | 2      | 3.57%   |
| Intel SSDSC2BA200G3T 200GB      | 1         | 1      | 3.57%   |
| Hitachi HTS725032A9A364 320GB   | 1         | 1      | 3.57%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 19     | 35.29%  |
| WDC         | 5         | 15     | 29.41%  |
| Hitachi     | 3         | 4      | 17.65%  |
| WD MediaMax | 1         | 3      | 5.88%   |
| Toshiba     | 1         | 2      | 5.88%   |
| Intel       | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 19     | 37.5%   |
| WDC         | 5         | 15     | 31.25%  |
| Hitachi     | 3         | 4      | 18.75%  |
| WD MediaMax | 1         | 3      | 6.25%   |
| Toshiba     | 1         | 2      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 43     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 34        | 254    | 70.83%  |
| Malfunc  | 11        | 44     | 22.92%  |
| Detected | 3         | 36     | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 30        | 37.97%  |
| Broadcom / LSI              | 13        | 16.46%  |
| AMD                         | 9         | 11.39%  |
| Marvell Technology Group    | 7         | 8.86%   |
| ASMedia Technology          | 4         | 5.06%   |
| Silicon Image               | 2         | 2.53%   |
| Micron/Crucial Technology   | 2         | 2.53%   |
| Kingston Technology Company | 2         | 2.53%   |
| JMicron Technology          | 2         | 2.53%   |
| HighPoint Technologies      | 2         | 2.53%   |
| Hewlett-Packard             | 2         | 2.53%   |
| Silicon Motion              | 1         | 1.27%   |
| QLogic                      | 1         | 1.27%   |
| Dell                        | 1         | 1.27%   |
| Areca Technology            | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 11        | 12.09%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 6.59%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 4         | 4.4%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 3         | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 3.3%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 3.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 3.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 3.3%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 3.3%    |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 2         | 2.2%    |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 2.2%    |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 2.2%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 2         | 2.2%    |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 2         | 2.2%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2         | 2.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 2.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 2.2%    |
| HighPoint RocketRAID 2760 SAS Controller                                         | 2         | 2.2%    |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 2         | 2.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.1%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 1.1%    |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 1.1%    |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                      | 1         | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.1%    |
| Intel PCIe Data Center SSD                                                       | 1         | 1.1%    |
| Intel NVMe Optane Memory Series                                                  | 1         | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.1%    |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 1.1%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.1%    |
| Intel 631xESB/632xESB IDE Controller                                             | 1         | 1.1%    |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                          | 1         | 1.1%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 1.1%    |
| HP Smart Array G6 controllers                                                    | 1         | 1.1%    |
| HP Smart Array Controller                                                        | 1         | 1.1%    |
| Dell PowerEdge Expandable RAID controller 5                                      | 1         | 1.1%    |
| ASMedia ASM1061 SATA IDE Controller                                              | 1         | 1.1%    |
| Areca ARC-188x series PCIe 2.0/3.0 to SAS/SATA 6/12Gb RAID Controller            | 1         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.1%    |
| AMD FCH IDE Controller                                                           | 1         | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 1.1%    |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.1%    |
| Unknown                                                                          | 1         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 33        | 45.21%  |
| RAID | 12        | 16.44%  |
| SAS  | 10        | 13.7%   |
| IDE  | 9         | 12.33%  |
| NVMe | 7         | 9.59%   |
| SCSI | 2         | 2.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 77.5%   |
| AMD    | 9         | 22.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5504 @ 2.00GHz           | 2         | 5%      |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 2         | 5%      |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 2         | 5%      |
| Intel Core i5-7500 CPU @ 3.40GHz         | 2         | 5%      |
| Intel Atom CPU C2750 @ 2.40GHz           | 2         | 5%      |
| AMD Ryzen 5 3600 6-Core Processor        | 2         | 5%      |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 2.5%    |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 2.5%    |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 2.5%    |
| Intel Xeon CPU E5506 @ 2.13GHz           | 1         | 2.5%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz       | 1         | 2.5%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz       | 1         | 2.5%    |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz       | 1         | 2.5%    |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz      | 1         | 2.5%    |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz      | 1         | 2.5%    |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1         | 2.5%    |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz      | 1         | 2.5%    |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1         | 2.5%    |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1         | 2.5%    |
| Intel Xeon CPU 5160 @ 3.00GHz            | 1         | 2.5%    |
| Intel Core i7-3555LE CPU @ 2.50GHz       | 1         | 2.5%    |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 2.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1         | 2.5%    |
| Intel Core i3-4330 CPU @ 3.50GHz         | 1         | 2.5%    |
| Intel Core i3-10100 CPU @ 3.60GHz        | 1         | 2.5%    |
| Intel Celeron CPU N3150 @ 1.60GHz        | 1         | 2.5%    |
| Intel Celeron CPU G1610T @ 2.30GHz       | 1         | 2.5%    |
| AMD Ryzen 7 1800X Eight-Core Processor   | 1         | 2.5%    |
| AMD FX-8350 Eight-Core Processor         | 1         | 2.5%    |
| AMD FX-8320E Eight-Core Processor        | 1         | 2.5%    |
| AMD FX-8300 Eight-Core Processor         | 1         | 2.5%    |
| AMD FX-6300 Six-Core Processor           | 1         | 2.5%    |
| AMD E1-2500 APU with Radeon HD Graphics  | 1         | 2.5%    |
| AMD A8-3870 APU with Radeon HD Graphics  | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Intel Xeon    | 20        | 50%     |
| Intel Core i5 | 4         | 10%     |
| AMD FX        | 4         | 10%     |
| Intel Core i3 | 2         | 5%      |
| Intel Celeron | 2         | 5%      |
| Intel Atom    | 2         | 5%      |
| AMD Ryzen 5   | 2         | 5%      |
| Intel Core i7 | 1         | 2.5%    |
| AMD Ryzen 7   | 1         | 2.5%    |
| AMD E1        | 1         | 2.5%    |
| AMD A8        | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 21        | 52.5%   |
| 8       | 8         | 20%     |
| 2       | 4         | 10%     |
| 16      | 3         | 7.5%    |
| 12      | 2         | 5%      |
| 6       | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 85%     |
| 2      | 6         | 15%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 29        | 72.5%   |
| 2       | 10        | 25%     |
| Unknown | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Haswell     | 7         | 17.5%   |
| IvyBridge   | 6         | 15%     |
| Nehalem     | 5         | 12.5%   |
| Piledriver  | 4         | 10%     |
| KabyLake    | 4         | 10%     |
| Silvermont  | 3         | 7.5%    |
| SandyBridge | 3         | 7.5%    |
| Zen 2       | 2         | 5%      |
| Zen         | 1         | 2.5%    |
| K10 Llano   | 1         | 2.5%    |
| Jaguar      | 1         | 2.5%    |
| Core        | 1         | 2.5%    |
| CometLake   | 1         | 2.5%    |
| Broadwell   | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Matrox Electronics Systems | 14        | 35.9%   |
| Intel                      | 8         | 20.51%  |
| AMD                        | 8         | 20.51%  |
| ASPEED Technology          | 7         | 17.95%  |
| Nvidia                     | 2         | 5.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 7         | 17.95%  |
| ASPEED Technology ASPEED Graphics Family                                                 | 7         | 17.95%  |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 5.13%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 5.13%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 5.13%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 5.13%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 5.13%   |
| Intel HD Graphics 630                                                                    | 2         | 5.13%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 5.13%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 5.13%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.56%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1         | 2.56%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 2.56%   |
| AMD ES1000                                                                               | 1         | 2.56%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Matrox | 14        | 35%     |
| 1 x Intel  | 8         | 20%     |
| 1 x AMD    | 8         | 20%     |
| 1 x ASPEED | 7         | 17.5%   |
| 1 x Nvidia | 2         | 5%      |
| Other      | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 39        | 97.5%   |
| Unknown | 1         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 100%    |

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
| 0     | 40        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 58.7%   |
| Realtek Semiconductor | 9         | 19.57%  |
| Broadcom              | 8         | 17.39%  |
| QLogic                | 1         | 2.17%   |
| Aquantia              | 1         | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7         | 11.86%  |
| Intel I210 Gigabit Network Connection                                         | 6         | 10.17%  |
| Intel I350 Gigabit Network Connection                                         | 4         | 6.78%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 6.78%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 6.78%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 5.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 5.08%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.39%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 3.39%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 3.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.69%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 1.69%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.69%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.69%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.69%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 1.69%   |
| Intel Ethernet Connection I217-V                                              | 1         | 1.69%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.69%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 1.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.69%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 1.69%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 1.69%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 1.69%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 1.69%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.69%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 1.69%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 1.69%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2         | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200            | 1         | 50%     |
| Intel Tiger Lake PCH CNVi WiFi | 1         | 50%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 57.78%  |
| Realtek Semiconductor | 9         | 20%     |
| Broadcom              | 8         | 17.78%  |
| QLogic                | 1         | 2.22%   |
| Aquantia              | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7         | 12.28%  |
| Intel I210 Gigabit Network Connection                                         | 6         | 10.53%  |
| Intel I350 Gigabit Network Connection                                         | 4         | 7.02%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 7.02%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 7.02%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 5.26%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 5.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.51%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 3.51%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 3.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.75%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 1.75%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.75%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 1.75%   |
| Intel Ethernet Connection I217-V                                              | 1         | 1.75%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.75%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 1.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.75%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 1.75%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 1.75%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 1.75%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 1.75%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.75%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 1.75%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 1.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 95.24%  |
| WiFi     | 2         | 4.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 12        | 30%     |
| 1     | 12        | 30%     |
| 4     | 6         | 15%     |
| 6     | 4         | 10%     |
| 5     | 4         | 10%     |
| 3     | 2         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2         | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 50%     |
| Intel AX200 Bluetooth                          | 1         | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 7         | 53.85%  |
| Intel  | 4         | 30.77%  |
| Nvidia | 2         | 15.38%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 15.79%  |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 10.53%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2         | 10.53%  |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 10.53%  |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 10.53%  |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1         | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1         | 5.26%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 5.26%   |
| AMD FCH Azalia Controller                                                         | 1         | 5.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 5.26%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 5.26%   |
| Unknown                                                                           | 1         | 5.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 23.26%  |
| Kingston            | 8         | 18.6%   |
| Unknown             | 6         | 13.95%  |
| Micron Technology   | 5         | 11.63%  |
| SK hynix            | 4         | 9.3%    |
| Crucial             | 2         | 4.65%   |
| Corsair             | 2         | 4.65%   |
| Transcend           | 1         | 2.33%   |
| Toshiba             | 1         | 2.33%   |
| Team                | 1         | 2.33%   |
| PNY                 | 1         | 2.33%   |
| Patriot             | 1         | 2.33%   |
| Hewlett-Packard     | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 2.13%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                | 1         | 2.13%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                      | 1         | 2.13%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                     | 1         | 2.13%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                | 1         | 2.13%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 2.13%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 2.13%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Toshiba RAM 9965525-138.A00LF 8192MB DIMM DDR3 1600MT/s     | 1         | 2.13%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s              | 1         | 2.13%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 2.13%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8192MB DIMM DDR3 1600MT/s     | 1         | 2.13%   |
| SK hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 800MT/s      | 1         | 2.13%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 2.13%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 2.13%   |
| Samsung RAM M395T5750EZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1         | 2.13%   |
| Samsung RAM M395T5750CZ4-CE61 2048MB FB-DIMM DDR2 667MT/s   | 1         | 2.13%   |
| Samsung RAM M393B2K70CM0-CF8 16384MB DIMM DDR3 1066MT/s     | 1         | 2.13%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s     | 1         | 2.13%   |
| Samsung RAM M393B1K73CHD-CF8 8192MB DIMM DDR3 1066MT/s      | 1         | 2.13%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s         | 1         | 2.13%   |
| Samsung RAM M393B1K70DH0-CH9 8192MB DIMM DDR3 800MT/s       | 1         | 2.13%   |
| Samsung RAM M393B1G70QH0-YK0 8GB DIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s      | 1         | 2.13%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 2133MT/s      | 1         | 2.13%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s         | 1         | 2.13%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s         | 1         | 2.13%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s      | 1         | 2.13%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s        | 1         | 2.13%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s      | 1         | 2.13%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1400MT/s             | 1         | 2.13%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s       | 1         | 2.13%   |
| Kingston RAM 9965684-012.A00G 8192MB DIMM DDR4 2400MT/s     | 1         | 2.13%   |
| Kingston RAM 9965527-026.A00LF 8192MB DIMM DDR3 1333MT/s    | 1         | 2.13%   |
| Kingston RAM 9965525-140.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 2.13%   |
| Kingston RAM 9965525-054.A00LF 4096MB DIMM DDR3 1600MT/s    | 1         | 2.13%   |
| Kingston RAM 9965525-037.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 2.13%   |
| Kingston RAM 9965516-057.A00LF 8192MB DIMM DDR3 1066MT/s    | 1         | 2.13%   |
| HP RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 2.13%   |
| Crucial RAM BLS8G3D1609DS 8192MB DIMM DDR3 800MT/s          | 1         | 2.13%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s      | 1         | 2.13%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s        | 1         | 2.13%   |
| Corsair RAM CMD16GX4M2B3000C15 8192MB DIMM DDR4 2133MT/s    | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 24        | 70.59%  |
| DDR4    | 6         | 17.65%  |
| Unknown | 3         | 8.82%   |
| DDR2    | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 33        | 97.06%  |
| FB-DIMM | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 61.9%   |
| 4096  | 7         | 16.67%  |
| 16384 | 5         | 11.9%   |
| 2048  | 4         | 9.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 12        | 33.33%  |
| 1333  | 9         | 25%     |
| 1066  | 3         | 8.33%   |
| 800   | 3         | 8.33%   |
| 2133  | 2         | 5.56%   |
| 667   | 2         | 5.56%   |
| 3200  | 1         | 2.78%   |
| 3000  | 1         | 2.78%   |
| 2667  | 1         | 2.78%   |
| 2400  | 1         | 2.78%   |
| 1400  | 1         | 2.78%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 20        | 50%     |
| 2     | 9         | 22.5%   |
| 1     | 5         | 12.5%   |
| 3     | 4         | 10%     |
| 5     | 1         | 2.5%    |
| 4     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 13        | 41.94%  |
| Sound                    | 11        | 35.48%  |
| Firewire controller      | 3         | 9.68%   |
| Net/wireless             | 2         | 6.45%   |
| Bluetooth                | 2         | 6.45%   |

